<template>
  <div class="home">
    <HelloWorld/>
    <q-card class="my-card w-64  q-ma-xl">
      <q-card-section class="q-pt-md">
        <q-input v-model="text" type="text" label="Username" />
        <q-input v-model="pw" type="password" label="Password" />
        <q-btn color="red" label="Masuk" @click="onClick" style="margin-top: 20px; width: 100%;" to="/home" />
        <h6 class="text-center">Power By Kang R</h6>
      </q-card-section>
    </q-card>
    <div class="text-h3 text-center text-bold">Intinya Bisa Ya</div>
  </div>
</template>
<style>
</style>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
