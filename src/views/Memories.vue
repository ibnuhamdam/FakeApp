<template>
    <div class="memories">
        <div class="container">
            <div class="row">
                <div class="col-sm-12 content">
                    <img src="../assets/SVG/thanks.svg" class="img-fluid" width="60%" alt="">
                </div>
            </div>
            <div class="row">
                <div class="col-12 text-left gallery">
                <h5>Your Memories</h5>
                    <div class="row mt-2">
                        <div class="col-4">
                            <img src="../assets/gallery-1.jpg" class="img-fluid" alt="">
                        </div>
                        <div class="col-4">
                            <img src="../assets/gallery-2.jpg" class="img-fluid" alt="">
                        </div>
                        <div class="col-4">
                            <img src="../assets/gallery-3.jpg" class="img-fluid" alt="">
                        </div>
                    </div>
                    <div class="row mt-2">
                        <div class="col-4">
                            <img src="../assets/gallery-4.jpg" class="img-fluid" alt="">
                        </div>
                        <div class="col-4">
                            <img src="../assets/gallery-5.jpg" class="img-fluid" alt="">
                        </div>
                        <div class="col-4">
                            <img src="../assets/gallery-6.jpg" class="img-fluid" alt="">
                        </div>
                    </div>
                    <div class="row mt-2">
                        <div class="col-4">
                            <img src="../assets/gallery-7.jpg" class="img-fluid" alt="">
                        </div>
                        <div class="col-4">
                            <img src="../assets/gallery-8.jpg" class="img-fluid" alt="">
                        </div>
                        <div class="col-4">
                            <img src="../assets/gallery-9.jpg" class="img-fluid" alt="">
                        </div>
                    </div>
                </div>
                <div class="col-12 navigation mt-5 mb-5">
                    <a href="https://wa.me/6285727633969"><button class="btn btn-primary btn-block">Thank You !</button></a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
    .memories {
      font-family: 'Montserrat', sans-serif;
    }
    .content {
        margin-top: 30px;
    }
    .gallery {
        margin: 5px 10px;
    }
    .gallery h5 {
        margin-top: 30px;
        font-size: 16px;
        font-weight: bold;
        color: #07689f;
    }
    .gallery .img {
        height: 100px;
    }
    .gallery .btn {
        padding: 10px 0px;
        font-size: 14px;
    }
</style>