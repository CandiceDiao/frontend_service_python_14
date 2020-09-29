<template>
  <v-app>
    <!-- 路由匹配到的组件将渲染在这里 -->
    <!--<router-view>会加载route.js中的所有页面 -->
    <router-view></router-view>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
 
  },

  data: () => ({
    //
  }),
};
</script>
