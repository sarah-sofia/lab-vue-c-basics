<template>
    <div class="iteration4playground">
    <h2>Posts</h2>
        <ul>
            <li v-for="(post, index) in posts" :key="index">
                <h3>{{ post.title }}</h3>
                <p>{{ post.description }}</p>
                <div>{{ post.content }}</div>
            </li>
        </ul>
    </div>
</template>
      
<script>
      export default {
          name: 'iteration4',
          data() {
              return {
                post: [
                    {
                        title: 'First Post',
                        description: 'This is the first post',
                        content: 'Hello Im the first post content'
                    },
                    {
                        title: 'Second Post',
                        description: 'This is the second post',
                        content: 'Hello Im the first post content'
                    },
                    {
                        title: 'Third Post',
                        description: 'This is the third post',
                        content: 'Hello Im the third post content'
                    },
                ]
              } 
          }
        }
</script>
      
<style scoped>
    .iteration4playground {
        background-color: #dadada;
    }
</style>