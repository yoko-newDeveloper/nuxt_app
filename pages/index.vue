<!-- テンプレート -->
<template>
  <div>
    {{message}}
    <RouterLink to="/next">次ページへ</RouterLink>
  </div>
</template>

<!-- スクリプト -->
<script>
export default {
  data: function() {
    return {
      message: 'Hello Nuxt!'
    }
  }
}
</script>

<!-- スタイル -->
<style>
</style>
