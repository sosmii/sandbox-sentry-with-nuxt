<template lang="pug">
  button(@click="err") Error
</template>

<script>
export default {
  methods: {
    err() {
      throw new Error('Sentry確認用')
    }
  }
}
</script>
