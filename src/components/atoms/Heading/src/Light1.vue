<template>
  <component
    :is="tag"
    :class="className"
    class="is-light-1"
  >
    <slot>text</slot>
  </component>
</template>

<script>
import Presenter from '../Presenter.vue'
export default {
  name: 'VbHeadingLight1',
  extends: Presenter,
  props: {
    ...Presenter.props
  }
}
</script>

<style lang="scss">
@import './style.scss';
</style>
