<template>
  <ion-app>
    <ion-page class="show-page">
      <ion-header>
        <ion-toolbar>
          <ion-title>Your application title</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-content class="content" padding>
        {{ msg }}
      </ion-content>
    </ion-page>
  </ion-app>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'See? It works!'
    }
  }
}
</script>

<style lang="scss">

</style>
