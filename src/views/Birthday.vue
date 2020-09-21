<template>
    <div class="birthday">
        <div class="container pb-5">
            <div class="row">
                <div class="col-sm-12 content">
                    <img src="../assets/birthday.svg" class="img-fluid pt-5" alt="">
                    <h4>Happy Birthday Babe !!</h4>
                    <p class="mt-3">Semoga di umur ke-22 ini bisa semakin sukses, lancar rezekinya dan selalu dimudahkan dalam setiap urusannya, Aamiin</p>
                </div>
                <div class="col-sm-12 navigation">
                    <router-link to="/gallery"><button class="btn btn-primary btn-block">Take me to gallery's</button></router-link>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css';

export default {
    
}
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
    .birthday {
      font-family: 'Montserrat', sans-serif;
    }
    .content {
        margin-top: 50px;
    }
    .content h4 {
        margin-top: 30px;
        color:  #07689f;
    }
    .content p {
        font-size: 13px;
        color: #40a8c4;
    }
    .navigation {
        margin-top: 200px;
    }
    .navigation .btn {
        font-size: 16px;
        color: white;
        padding: 10px 0px;
        border-radius: 25px;
    }
</style>