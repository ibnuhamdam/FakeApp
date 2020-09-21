<template>
    <div class="profile">
        <div class="header">
            <h5 class="pt-5">Coba cek <br> Apa benar ini kamu ?</h5>                
        </div>
        <img src="../assets/vio.jpeg" class="img-fluid avatar" alt="">
        <div class="informasi">
            <p>Violyta Radina Putri <br>
                <span class="ttl">September 20, 1998</span>
            </p>
            <p class="alamat">Lubuk Linggau, Sumatra Selatan, <br> Sumatra Indonesia </p>
            <h2 class="mt-4">STKIP PGRI Lubuk Linggau</h2>
        </div>
        <div class="navigation">
            <button class="btn btn-outline-primary mr-2">Sepertinya Bukan</button>
            <router-link to="/birthday"><button class="btn btn-primary btn-benar">Ya, benar</button></router-link>
        </div>
    </div>
</template>

<script>

import 'bootstrap/dist/css/bootstrap.css';

export default {
    name: 'profile',
    data: function() {
        return {
            myName: ""
        }
    }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
    .profile {
        font-family: 'Montserrat', sans-serif;
    }
    .header {
        background-color: #ffc93c;
        height: 300px;
        border-bottom-right-radius: 30px;
        border-bottom-left-radius: 30px;
    }
    .header h5 {
        color: #07689f;
        font-weight: bold;
    }
    .avatar {
        border: .5px solid rgb(255, 255, 255);
        border-radius: 50%;
        margin-top: -100px;
        width: 50%;
    }
    .informasi {
        font-size: 23px;
        font-weight: bold;
        color: #07689f;
    }
    .ttl {
        font-weight: 500;
        font-size: 16px;
        color: #40a8c4;
    }
    .alamat {
        font-weight: 500;
        font-size: 12px;
        color: #40a8c4;
    }
    .informasi h2 {
        font-size: 21px;
        font-weight: bold;
        color: #40a8c4;
    }
    .navigation {
        margin-top: 100px;
    }
    .navigation .btn {
        font-size: 13px;
        padding: 15px 15px;
        border-radius: 23px;
    }
    .navigation .btn-benar {
        padding: 15px 40px;
    }
</style>