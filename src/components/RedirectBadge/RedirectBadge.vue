<script setup>
const props = defineProps({
  redirectLink: {
    type: String,
    required: true,
  },
});
</script>
<template>
  <a
    class="badge badge-outline hover:bg-black hover:text-white rounded-full p-3"
    :href="props.redirectLink"
    target="_blank"
    rel="noreferrer"
  >
    {{ props.redirectLink }}
  </a>
</template>
