<template>
  <div class="home">
    <div class="container">
      <div class="col-sm-12 text-left judul mt-3">
        <h2 class="ml-3">Hello, Welcome <br> to this fake app</h2>
        <hr class="hr-judul">
      </div>
      <div class="content">
        <div class="col-sm-12">
          <img src="../assets/SVG/mobile-home.svg" class="img-fluid img-content" alt="">
        </div>
        <div class="col-sm-12">
          <router-link to="/name-form"><button class="btn btn-primary btn-block mt-5 btn-pills">Take me</button></router-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import 'bootstrap/dist/css/bootstrap.css';

export default {
  name: 'Home',
  data: function() {
      return {
          myName: ""
      }
  },
  components: {
    // HelloWorld
  }
}
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
    .home {
      font-family: 'Montserrat', sans-serif;
    }
    .hr-judul {
      margin-left: 16px;
      width: 30%;
      border: 1px solid rgb(150, 150, 150);
    }
    .img-content {
      margin-top: 200px;
    }
    .btn {
      font-size: 20px;
      padding: 10px 0px;
      border-radius: 25px;
    }
</style>
