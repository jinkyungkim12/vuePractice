<template>
  <div class="data_binding">
    
    <h1>{{ msg }}</h1> 

  </div>
</template>

<script>
export default {
  name: 'test_data_binding',
  props: {
    msg: String
  }
}
//   methods: {
//     test() {
//       console.log('dfsdf')
//     }
//   },
// }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 40px 0 0;
  color: #42b983;
}
</style>