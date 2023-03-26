<template>
<div class="navbarPlatground">
<h1>I'm a navbar</h1>
<p>For the second iteration 2 + 2 is {{ 2 + 2 }}</p>
<p>{{ getString() }}</p>
</div>
</template>

<script>
export default {
    name: 'navbar',
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
.navbarPlatground {
    background-color: darkgrey;
    color: white;
}
</style>