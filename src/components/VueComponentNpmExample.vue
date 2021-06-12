<template>
  <button>{{ text }}</button>
</template>

<script>
export default {
  name: 'VueComponentNpmExample',
  props: {
    text: {type: String, default: "Default text"}
  }
}
</script>
