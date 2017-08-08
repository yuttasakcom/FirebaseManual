<template>
  <div>
    <h1>Firebase 101</h1>
    <app-navtab></app-navtab>
    <app-authen></app-authen>
  </div>
</template>

<script>
  import appNavtab from '@/components/Navtab'
  import Authen from '@/containers/Authen'
  export default {
    components: {
      appNavtab: appNavtab,
      appAuthen: Authen
    }
  }
</script>