<template>
  <div id="main">
    <Header title="我的喵喵" />
    <div id="content">
      <keep-alive>
        <router-link></router-link>
      </keep-alive>
      <Login />
    </div>
    <TabBar></TabBar>
  </div>

</template>

<script>
import Header from '@/components/Header'
import TabBar from '@/components/TabBar'
import Login from '@/components/Login'
export default {
  name: 'Mine',
  components: {
    Header,
    TabBar,
    Login
  }
}
</script>

<style>
</style>
