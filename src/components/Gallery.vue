<template>
  <div class="gallery">
    <h2>My Works</h2>
    <section id="portfolio">
      <div class="row">
        <div class="col-lg-4 mt-4">
            <div class="card">
                <img class="card-img-top" src="./images/portfolioImage1.jpg" alt="Card image" style="width:100%">
                <div class="card-body">
                    <h4 class="card-title">YouTube Clone</h4>
                    <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                    <div class="text-center">
                        <a href="#" class="btn btn-success">Link</a>
                    </div>
                </div>
            </div>
        </div>

        <div class="col-lg-4 mt-4">
            <div class="card portfolioContent">
                <img class="card-img-top" src="./images/portfolioImage4.jpg" alt="Card image" style="width:100%">
                <div class="card-body">
                    <h4 class="card-title">Quiz App</h4>
                    <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                    <div class="text-center">
                        <a href="#" class="btn btn-success">Link</a>
                    </div>
                </div>
            </div>
        </div>

        <div class="col-lg-4 mt-4">
            <div class="card portfolioContent">
                <img class="card-img-top" src="./images/portfolioImage3.jpg" alt="Card image" style="width:100%">
                <div class="card-body">
                    <h4 class="card-title">Product Landing Page</h4>
                    <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                    <div class="text-center">
                        <a href="#" class="btn btn-success">Link</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-lg-4 mt-4">
            <div class="card portfolioContent">
                <img class="card-img-top" src="./images/portfolioImage4.jpg" alt="Card image" style="width:100%">
                <div class="card-body">
                    <h4 class="card-title">Messaging Service</h4>
                    <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                    <div class="text-center">
                        <a href="#" class="btn btn-success">Link</a>
                    </div>
                </div>
            </div>
        </div>

        <div class="col-lg-4 mt-4">
            <div class="card portfolioContent">
                <img class="card-img-top" src="./images/portfolioImage1.jpg" alt="Card image" style="width:100%">
                <div class="card-body">
                    <h4 class="card-title">Twitter Clone</h4>
                    <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                    <div class="text-center">
                        <a href="#" class="btn btn-success">Link</a>
                    </div>
                </div>
            </div>
        </div>

        <div class="col-lg-4 mt-4">
            <div class="card portfolioContent">
                <img class="card-img-top" src="./images/portfolioImage4.jpg" alt="Card image" style="width:100%">
                <div class="card-body">
                    <h4 class="card-title">Blog App</h4>
                    <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                    <div class="text-center">
                        <a href="#" class="btn btn-success">Link</a>
                    </div>
                </div>
            </div>
      </div>
    </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'gallery',
  data () {
    return {
      msg: 'Gallery'
    }
  }
}
</script>


<style scoped>
.gallery{
  margin: 0 55px;
  font-family: Helvetica, sans-serif;
}

h2{
  letter-spacing: 5px;
  margin-bottom: -5px;
  margin-top: 50px;
}

.servicesText.card {
    height: 280px;
    cursor: pointer;
  }
.servicesIcon {
    font-size: 36px;
    text-align: center;
    width: 100%;
}
.card-title {
    text-align: center;
}
.card:hover .servicesIcon {
    color: #008000;
}
.servicesText:hover {
    border: 1px solid #008000;
}
</style>
