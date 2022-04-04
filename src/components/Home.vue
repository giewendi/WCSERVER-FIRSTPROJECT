<template>
  <div class="home">
    <div id="head">
      <h1>GIEWEN PINLAC</h1>
      <h2>Web Developer</h2>
    </div>
    <div class="vl"></div>
    <p class="welcome"> <br> Welcome to my website!</p>
    <section id="services">
        <div class="container">
            <h1 class="text-center">Services</h1>
            <div class="row">
                <div class="col-lg-4 mt-4">
                    <div class="card servicesText">
                        <div class="card-body">
                            <h4 class="card-title mt-3">Website Development</h4>
                            <p class="card-text mt-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Semper auctor neque vitae tempus. Lectus mauris ultrices eros in cursus turpis massa tincidunt.</p>
                        </div>
                    </div>  
                </div>
                <div class="col-lg-4 mt-4">
                    <div class="card servicesText">
                        <div class="card-body">
                            <h4 class="card-title mt-3">Website Design</h4>
                            <p class="card-text mt-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Semper auctor neque vitae tempus. Lectus mauris ultrices eros in cursus turpis massa tincidunt.</p>
                        </div>
                    </div>  
                </div>

                <div class="col-lg-4 mt-4">
                    <div class="card servicesText">
                        <div class="card-body">
                            <h4 class="card-title mt-3">Website Deployment</h4>
                            <p class="card-text mt-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Semper auctor neque vitae tempus. Lectus mauris ultrices eros in cursus turpis massa tincidunt.</p>
                        </div>
                    </div>  
                </div>
            </div>

            <div class="row">
                <div class="col-lg-4 mt-4">
                    <div class="card servicesText">
                        <div class="card-body">
                            <h4 class="card-title mt-3">SEO</h4>
                            <p class="card-text mt-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Semper auctor neque vitae tempus. Lectus mauris ultrices eros in cursus turpis massa tincidunt.</p>
                        </div>
                    </div>  
                </div>

                <div class="col-lg-4 mt-4">
                    <div class="card servicesText">
                        <div class="card-body">
                            <h4 class="card-title mt-3">DevOps</h4>
                            <p class="card-text mt-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Semper auctor neque vitae tempus. Lectus mauris ultrices eros in cursus turpis massa tincidunt.</p>
                        </div>
                    </div>  
                </div>

                <div class="col-lg-4 mt-4">
                    <div class="card servicesText">
                        <div class="card-body">
                            <h4 class="card-title mt-3">QA</h4>
                            <p class="card-text mt-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Semper auctor neque vitae tempus. Lectus mauris ultrices eros in cursus turpis massa tincidunt.</p>
                        </div>
                    </div>  
                </div>
            </div>
        </div>
    </section>
    <div class="extra"></div>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style scoped>
.home{
  font-family: Helvetica, sans-serif;
}

#head{
  background-image: url("./images/bg-home.jpg");
  background-repeat: no-repeat;
  background-size: 100%;
  justify-content: center;
  align-content: center;
  align-items: center;
  text-align: center;
  color: aliceblue;
  padding: 10%;
}

h1{
  letter-spacing: 25px;
  margin: 1em;
}

h2{
  letter-spacing: 15px;
  margin: 1em;
}

.vl {
  border-left: 1px solid lightgray;
  height: 100px;
  margin: 0 50%;
}

.welcome{
  text-align: center;
  font-style: oblique;
  color: gray;
  letter-spacing: 5px;
  margin-bottom: 100px;
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

.servicesText:hover {
    border: 1px solid gray;
}

.extra{
  height: 5em;
}
</style>