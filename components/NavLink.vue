<template>
  <a
    href="#"
    class="border-indigo-500 text-gray-900 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"
  >
    {{ text }}
  </a>
</template>
<script>
export default {
  props: ['text', 'link'],
}
</script>