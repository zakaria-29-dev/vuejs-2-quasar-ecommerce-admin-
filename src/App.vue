<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container>
     <router-view></router-view>
    </q-page-container>
  </q-layout>
</template>

<script>


export default {
  name: 'LayoutDefault',


  setup () {
    return {
    //  leftDrawerOpen: ref(false)
    }
  }
}
</script>
