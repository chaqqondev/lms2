<template>
  <HeaderItem/>
  <router-view/>
</template>

<script>
import HeaderItem from './components/lib/HeaderItem';
export default {
  components:{
    HeaderItem
  }
}
</script>

<style lang="scss">
@import './styles/app.scss';
</style>
