<template>
  <img :src="`/flags/${iso.toLowerCase()}.svg`">
</template>

<script>
export default {
  name: 'CountryFlag',
  props: {
    iso: String
  },
  setup(props) {
  },
}
</script>
