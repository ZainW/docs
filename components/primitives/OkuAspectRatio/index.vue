<script setup lang="ts">
import { OkuAspectRatio } from '@oku-ui/aspect-ratio'
</script>

<template>
  <div class="flex items-center justify-center">
    <div class="w-[250px] rounded-sm overflow-hidden">
      <OkuAspectRatio :ratio="3 / 2">
        <img
          class="object-cover w-full h-full rounded-lg"
          src="https://images.unsplash.com/photo-1604156788872-fa65cd2575f5?w=600&dpr=2&q=80"
          alt="Landscape photograph by Tobias Tullius"
        >
      </OkuAspectRatio>
    </div>
    <span class="absolute bottom-2 right-2 text-xs">
      Photo by <a
        href="https://unsplash.com/@timgarifov?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText"
      >Timur
        Garifov</a> on <a
        href="https://unsplash.com/photos/DdIDRN3Fw2A?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText"
      >Unsplash</a>
    </span>
  </div>
</template>
