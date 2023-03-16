<template>
  <main>
    <div class="h-32 bg-gray-200">This is the banner to be designed</div>
    <div class="h-16 bg-red-200 pt-6 pl-4">
      <svg
        class="w-6 h-6 float-left mr-2"
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="currentColor"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
        />
      </svg>

      <div class="float-left">{{ name }}</div>
    </div>
  </main>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      default: 'alexrazbakov',
    },
  },
}
</script>

<style></style>
