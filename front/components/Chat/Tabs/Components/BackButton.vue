<template>
  <button class="text-yellow flex flex-wrap items-center focus:outline-none" @click="$emit('back')">
    <svg class="mx-2 h-5 w-5 transform rotate-90" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
      <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
    </svg>
    <slot></slot>
  </button>
</template>

<script lang="ts">
import Vue from 'vue'
import {Component} from 'nuxt-property-decorator'

@Component({})
export default class BackButton extends Vue {

}
</script>

<style scoped>

</style>
