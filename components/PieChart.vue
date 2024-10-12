<script setup lang="ts">
import { Pie } from "vue-chartjs";
import { Chart, ArcElement, type ChartOptions } from "chart.js";
import ChartDataLabels from "chartjs-plugin-datalabels";

Chart.register(ArcElement, ChartDataLabels);

const props = defineProps<{
  data: ChartDataRow[];
}>();

interface ChartDataRow {
  label: string;
  value: number;
  color: string;
}

const data = {
  labels: props.data.map((row) => row.label),
  datasets: [
    {
      backgroundColor: props.data.map((row) => row.color),
      data: props.data.map((row) => row.value),
    },
  ],
};

const chartOptions: ChartOptions<"pie"> = {
  maintainAspectRatio: false,
  animation: false,
  plugins: {
    datalabels: {
      color: "#fff",
      font: {
        weight: "bold",
        size: 20,
      },
      formatter: (_value, ctx) => {
        return ctx.chart?.data.labels?.[ctx.dataIndex];
      },
      textStrokeColor: "#666",
      textStrokeWidth: 2,
    },
  },
};
</script>

<template>
  <Pie :data="data" :options="chartOptions" />
</template>
