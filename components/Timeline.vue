<script setup lang="ts">
import clsx from "clsx";
import { computed } from "vue";

interface TimelineItem {
  date: string;
  description: string;
  highlight?: boolean;
}

const props = defineProps<{
  items: TimelineItem[];
}>();

const highlightedItems = computed(() => {
  return props.items.filter((item) => item.highlight ?? false);
});

const notHighlightedItems = computed(() => {
  return props.items.filter((item) => !item.highlight);
});
</script>

<template>
  <ol
    v-click="1"
    class="inline-block relative border-s border-gray-200 dark:border-gray-500"
  >
    <li
      v-for="(item, index) in notHighlightedItems"
      :key="index"
      class="mb-1 list-none !leading-snug py-1"
    >
      <div
        :class="'absolute w-4 h-4 mt-1 rounded-full -start-2 border border-white dark:border-gray-900 bg-gray-300 dark:bg-gray-400'"
      />
      <div data-highlight="false" class="flex flex-col">
        <time class="text-base text-gray-500 dark:text-gray-300">{{
          item.date
        }}</time>
        <div class="text-gray-900 dark:text-white">
          {{ item.description }}
        </div>
      </div>
    </li>

    <div
      v-mark="{ at: 1, type: 'box', style: 'padding: 20px' }"
      class="inline-block pr-4"
    >
      <li
        v-for="(item, index) in highlightedItems"
        :key="index"
        class="mb-1 list-none !leading-snug py-1"
      >
        <div
          :class="
            clsx(
              'absolute w-4 h-4 rounded-full mt-1 -start-2 border border-white dark:border-gray-900',
              {
                'bg-blue-500': index === highlightedItems.length - 1,
                'bg-gray-300 dark:bg-gray-400':
                  index !== highlightedItems.length - 1,
              },
            )
          "
        />
        <div data-highlight="true" class="flex flex-col">
          <time class="text-base text-gray-500 dark:text-gray-300">{{
            item.date
          }}</time>
          <div class="text-gray-900 dark:text-white">
            {{ item.description }}
          </div>
        </div>
      </li>
    </div>
  </ol>
</template>

<style scoped>
.slidev-vclick-hidden {
  opacity: 1 !important;
}

.slidev-vclick-current,
.slidev-vclick-prior {
  [data-highlight="true"] {
    @apply !font-bold;
  }
  [data-highlight="false"] {
    @apply !opacity-30;
  }
}
</style>
