<template>
  <div>
    <p class="content">ヘッダー</p>
    <nuxt />
    <p>フッター</p>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'DefaultLayout',
})
</script>
