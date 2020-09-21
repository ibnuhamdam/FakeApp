<template>
  <div class="form-name">
      <div class="col-sm-12 gambar mt-5">
          <img src="../assets/ai-robots.png" class="img-fluid" alt="">
      </div>
      <div class="col-sm-12 content text-left mt-5">
          <h3 class="ml-4 mt-2">Kata pepatah, tak sayang maka tak kenal</h3>
          <p class="ml-4 ">Boleh kenalan dulu, siapa namanya ?</p>
      </div>
      <div class="container">
          <div class="row">
            <div class="col-10 offset-1 form mt-5">
                <div class="form-group text-left">
                    <label for="Fullname" class="labelname">Full Name</label>
                    <input type="text" v-model="myName" class="form-control" id="Fullname" aria-describedby="Fullname">
                </div>
            </div>
            <div class="col-12 mt-3">
                <router-link to="/profile"><button class="btn btn-take btn-block">Take me</button></router-link>
            </div>
          </div>
      </div>

      <!-- <dataProfile v-bind:myName="myName"/> -->
      
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import 'bootstrap/dist/css/bootstrap.css';

// import dataProfile from "../components/dataProfile.vue";

export default {
  name: 'Form-name',
  data: function() {
      return {
          myName: ""
      }
  },
  components: {
    // dataProfile
  }
}
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
    .form-name {
        font-family: 'Montserrat', sans-serif;
    }
    .content h3 {
        font-size: 23px;
        color: #40a8c4;
    }
    .content p {
        font-size: 14px;
        color: #a2d5f2;
    }
    .form-control {
        border: none;
        border-bottom: 1px solid #ced4da;
        border-radius: 0px;
        color: #40a8c4;
    }
    .labelname {
        color: #40a8c4;
    }
    .btn-take {
        background-color: #ffc93c;
        color: white;
        font-size: 20px;
        padding: 8px 0px;
        border-radius: 20px;
    }
</style>
