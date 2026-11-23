<template>
  <q-page class="q-pa-md">
    <h1 class="text-h5">Detalji opažanja</h1>
    <p>Ovdje će biti prikaz pojedinog opažanja.</p>
    <p>Tu će se detaljnije opisati opažanja.</p>
    <p>Što je korisnik vidio, kada te ostale pojedine informacije.</p>
    <p>ID opažanja: {{ route.params.id }}</p>
  </q-page>
</template>


<script setup>
import { useRoute } from 'vue-router';
const route = useRoute();
</script>