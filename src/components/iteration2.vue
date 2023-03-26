<template>
    <div class="iteration2Playground">
    <p>For the second iteration 2 + 2 is {{ 2 + 2 }}</p>
    <p>{{ getString() }}</p>
    </div>
    </template>
    
    <script>
    export default {
        name: 'iteration2',
        data() {
            return {
                name: 'Sarah',
                age: 30
            } 
    
        },
    methods: {
        getString() {
            return `I used a getString method to write this: My name is ${this.name} and my age is ${this.age}`
            }
        }
    }
    </script>
    
    <style scoped>
    .iteration2Playground {
        background-color: #eeeeee;
    }
    </style>