<template>
  <q-page class="row items-center justify-evenly">
   Hello
   <div class="q-pa-md q-gutter-sm">
    <q-btn color="white" text-color="black" label="Standard" @="alertText('Standard')"/>
    <q-btn color="primary" label="Primary" />
    <q-btn color="secondary" label="Secondary" />
    <q-btn color="amber" glossy label="Amber" />
    <q-btn color="brown-5" label="Brown 5" />
    <q-btn color="deep-orange" glossy label="Deep Orange" />
    <q-btn color="purple" label="Purple" />
    <q-btn color="black" label="Black" />
  </div>
  </q-page>
</template>

<script setup lang="ts">
import { ref } from 'vue';

defineOptions({
  name: 'welcome'
});

const alertText = (text:string)=>{
  alert(text)
}

</script>
