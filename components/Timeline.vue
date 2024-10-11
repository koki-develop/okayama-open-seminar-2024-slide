<script setup lang="ts">
import { defineProps } from "vue";
import clsx from "clsx";

interface TimelineItem {
  date: string;
  description: string;
}

const props = defineProps<{
  items: TimelineItem[];
}>();
</script>

<template>
  <ol class="relative border-s border-gray-200 dark:border-gray-700">
    <li
      v-for="(item, index) in props.items"
      :key="index"
      class="mb-1 list-none"
    >
      <div
        :class="
          clsx(
            'absolute w-4 h-4 rounded-full mt-2 -start-2 border border-white dark:border-gray-900',
            {
              'bg-blue-500': index === props.items.length - 1,
              'bg-gray-300 dark:bg-gray-400': index !== props.items.length - 1,
            },
          )
        "
      />
      <time
        :class="
          clsx('mb-1 text-sm text-gray-600 dark:text-gray-300', {
            'font-semibold': index === props.items.length - 1,
          })
        "
        >{{ item.date }}</time
      >
      <h2
        :class="
          clsx('!text-2xl text-gray-900 dark:text-white', {
            'font-semibold': index === props.items.length - 1,
          })
        "
      >
        {{ item.description }}
      </h2>
    </li>
  </ol>
</template>
