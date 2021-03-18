<template>
  <div class="flex justify-between h-16">
    <div class="flex">
      <div class="flex-shrink-0 flex items-center">
        <Logo />
      </div>
      <div class="hidden sm:-my-px sm:ml-6 sm:flex sm:space-x-8">
        <!-- Current: "border-indigo-500 text-gray-900", Default: "border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700" -->
        <a
          href="#"
          class="border-indigo-500 text-gray-900 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"
        >
          Dashboard
        </a>

        <a
          href="#"
          class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"
        >
          Team
        </a>

        <a
          href="#"
          class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"
        >
          Projects
        </a>

        <a
          href="#"
          class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"
        >
          Calendar
        </a>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Navbar',
}
</script>