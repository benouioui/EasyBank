<template>
  <div>
    <MainPage class="h-screen" style="background-color: hsl(0, 0%, 98%);"/>
    <secondPage style="background-color:  hsl(220, 16%, 96%);"/>
    <thirdPage style="background-color: hsl(0, 0%, 98%);"/>
    <bottomFoot/>
  </div>
</template>

<script>

import MainPage from '@/components/MainPage'
import secondPage from '@/components/secondPage'
import thirdPage from '@/components/thirdPage'
import bottomFoot from '@/components/bottomFoot'

export default {
  components: {
    MainPage,
    secondPage,
    thirdPage,
    bottomFoot
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
