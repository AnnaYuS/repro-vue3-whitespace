<template>
    <span>hi</span><span>hello</span>

    <span>hi</span>
    <span>hello</span>

  <Test>
    <template #default>
      default template content
    </template>

    <template #buttons>
      <button>click</button>
    </template>
  </Test>
</template>

<script>
import Test from './Test'
export default {
  name: 'HelloWorld',
  components: { Test }
}
</script>
