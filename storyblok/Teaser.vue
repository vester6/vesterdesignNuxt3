<template>
  <div
    v-editable="blok"
    :cat="$attrs.cat"
    class="py-8 mb-6 text-5xl font-bold text-center"
    style="red"
    data-test="teaser"
  >
    {{ blok.headline }} 
  </div>
  <p>test</p>
</template>

<script setup>
defineProps({ blok: Object });
</script>
