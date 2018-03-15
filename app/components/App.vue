<template>
  <h1>{{hoge}}</h1>
</template>
<script>
import Vue from 'vue';

export default Vue.extend({
  data() {
    return {
      hoge: 'fuga',
    };
  }
});
</script>
