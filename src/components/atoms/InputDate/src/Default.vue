<template>
  <input
    :class="className"
    type="date">
</template>

<script>
import Presenter from '../Presenter.vue'
export default {
  name: 'VbInputDate',
  extends: Presenter,
  props: {
    ...Presenter.props
  }
}
</script>

<style lang="scss">
@import './style.scss';
</style>
