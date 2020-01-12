<template>
  <footer>
    <p>{{title}}</p>
  </footer>
</template>

<script>
export default {
    data() {
        return {
          title: 'Copyright 2019 Iskcon@Govindas'
        }
    }
}
</script>

<style scoped>
footer{
    background: #222;
    padding: 6px;
}
p{
        color: lightgreen;
        text-align: center;
}
</style>
