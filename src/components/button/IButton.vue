<template>
    <button>{{title}}</button>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
  props: {

    title: {
        type: String,

     
    }
    
  }
})
</script>