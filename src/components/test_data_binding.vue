<template>
  <div class="data_binding">
    <form>
      <div class="container">
      <div class="text-center mb-3 mt-3"><h3><b>{{ msg }}</b></h3></div> 
        <div class="mb-3 row">
          <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
          <div class="col-sm-10">
            <input type="text" class="form-control" id="staticEmail" value="email@example.com">
          </div>
        </div>
        <div class="mb-3 row">
          <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
          <div class="col-sm-10">
            <input type="password" class="form-control" id="inputPassword">
          </div>
        </div>
        <div class="mb-3 row justify-content-center">
          <button class="btn btn-dark" type="submit" id="loginBtn">Login</button>
        </div>
      </div>
    </form>

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
h3 {
  color: #42b983;
}
#loginBtn{
  color: #42b983;
  width: 200px;
}
.container{
  width: 30%;
}
</style>