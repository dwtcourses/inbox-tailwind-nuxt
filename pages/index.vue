<template>
  <div class="px-10">
    <div class="text-sm text-gray-500">22th July 2017</div>
    <h1>Today meeting opened!</h1>
    <ul class="my-2 text-xs">
      <li
        class="inline-block bg-blue-100 text-blue-500 border border-blue-200 rounded-sm px-2 py-1 mr-1"
      >
        <span class="">work</span>
        <button class="ml-2">x</button>
      </li>
      <li
        class="inline-block bg-gray-100 text-gray-500 border border-gray-200 rounded-sm px-2 py-1 mr-1"
      >
        <span>work</span>
        <button class="ml-2">x</button>
      </li>
    </ul>
    <div class="mt-8">
      <p class="mb-5">
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text ever
        since the 1500s, when an unknown printer took a galley of type and
        scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining
        essentially unchanged. It was popularised in the 1960s with the release
        of Letraset sheets containing Lorem Ipsum passages, and more recently
        with desktop publishing software like Aldus PageMaker including versions
        of Lorem Ipsum.
      </p>
      <p class="mb-5">
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text ever
        since the 1500s, when an unknown printer took a galley of type and
        scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining
        essentially unchanged. It was popularised in the 1960s with the release
        of Letraset sheets containing Lorem Ipsum passages, and more recently
        with desktop publishing software like Aldus PageMaker including versions
        of Lorem Ipsum.
      </p>
      <p class="mb-5">
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text ever
        since the 1500s, when an unknown printer took a galley of type and
        scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining
        essentially unchanged. It was popularised in the 1960s with the release
        of Letraset sheets containing Lorem Ipsum passages, and more recently
        with desktop publishing software like Aldus PageMaker including versions
        of Lorem Ipsum.
      </p>
    </div>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'
// import NewMessage from '~/components/dialogs/NewMessage.vue'

export default {
  components: {
    // NewMessage
  },
  data() {
    return {
      // showNewMessageDialog: false
    }
  }
}
</script>

<style lang="sass" scoped>
h1
  @apply text-4xl
</style>
