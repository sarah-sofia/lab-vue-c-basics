<template>
  <div class="iteration3playground">
    <p v-if="showElement">This element will only show up if the show element is TRUE</p>
    <button @click="toggleElement">Toggle Element</button>
  </div>
    </template>
    
    <script>
    export default {
        name: 'iteration3',
        data() {
            return {
                showElement: true
            } 
        },
    methods: {
        toggleElement() {
            this.showElement = !this.showElement
        }
        }
    }
    </script>
    
    <style scoped>
    .iteration3playground {
        background-color: #e1e1e1;
    }
    </style>