<template>
  <img :src="`/flags/${iso.toLowerCase()}.svg`">
</template>

<script>
import css from './CountryFlag.css'
export default {
  name: 'CountryFlag',
  props: {
    iso: String
  },
  setup(props) {
  },
}
</script>
