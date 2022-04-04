<template>
  <div class="blog">
    <div class="header">
      <h2>My Blogs</h2>
    </div>
    <div class="row">
      <div class="content">
        <div class="card">
          <h2>MY FIRST CLIENT</h2>
          <h5>Title description, Dec 7, 2021</h5>
          <img src="./images/portfolioImage3.jpg" alt="Image">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Semper auctor neque vitae tempus. Lectus mauris ultrices eros in cursus turpis massa tincidunt. At risus viverra adipiscing at in tellus integer feugiat. Quis commodo odio aenean sed adipiscing diam donec. Phasellus vestibulum lorem sed risus ultricies tristique nulla aliquet. Non arcu risus quis varius quam quisque id. Eget aliquet nibh praesent tristique magna sit amet purus. Eget gravida cum sociis natoque penatibus et magnis dis. Cras pulvinar mattis nunc sed blandit. Quam nulla porttitor massa id neque aliquam vestibulum morbi. Cursus euismod quis viverra nibh. Scelerisque in dictum non consectetur. Interdum velit euismod in pellentesque massa placerat duis. Diam quam nulla porttitor massa id. Tortor dignissim convallis aenean et tortor. <br><br> Sagittis nisl rhoncus mattis rhoncus urna neque viverra justo nec. Tortor consequat id porta nibh venenatis cras sed felis. Rhoncus dolor purus non enim praesent elementum. Ultricies lacus sed turpis tincidunt id aliquet risus feugiat in. Dis parturient montes nascetur ridiculus mus mauris vitae. A erat nam at lectus urna duis convallis convallis. Gravida quis blandit turpis cursus in. Congue nisi vitae suscipit tellus mauris a diam maecenas sed. Ultrices neque ornare aenean euismod elementum. Morbi tempus iaculis urna id volutpat lacus laoreet non curabitur. Fermentum posuere urna nec tincidunt praesent semper. Nulla pellentesque dignissim enim sit amet venenatis urna cursus. Tortor at risus viverra adipiscing at in tellus integer feugiat. Mattis rhoncus urna neque viverra justo nec. Dictumst quisque sagittis purus sit. Enim facilisis gravida neque convallis a cras semper. Cursus mattis molestie a iaculis.Sapien eget mi proin sed libero. Diam vulputate ut pharetra sit amet aliquam. Sit amet dictum sit amet justo donec enim.</p>
        </div>
        <div class="card">
          <h2>HOW I BECOME A WEB DEVELOPER</h2>
          <h5>Title description, Sep 2, 2021</h5>
          <img src="./images/portfolioImage4.jpg" alt="Image">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Semper auctor neque vitae tempus. Lectus mauris ultrices eros in cursus turpis massa tincidunt. At risus viverra adipiscing at in tellus integer feugiat. Quis commodo odio aenean sed adipiscing diam donec. Phasellus vestibulum lorem sed risus ultricies tristique nulla aliquet. Non arcu risus quis varius quam quisque id. Eget aliquet nibh praesent tristique magna sit amet purus. Eget gravida cum sociis natoque penatibus et magnis dis. Cras pulvinar mattis nunc sed blandit. Quam nulla porttitor massa id neque aliquam vestibulum morbi. Cursus euismod quis viverra nibh. Scelerisque in dictum non consectetur. Interdum velit euismod in pellentesque massa placerat duis. Diam quam nulla porttitor massa id. Tortor dignissim convallis aenean et tortor. <br><br> Sagittis nisl rhoncus mattis rhoncus urna neque viverra justo nec. Tortor consequat id porta nibh venenatis cras sed felis. Rhoncus dolor purus non enim praesent elementum. Ultricies lacus sed turpis tincidunt id aliquet risus feugiat in. Dis parturient montes nascetur ridiculus mus mauris vitae. A erat nam at lectus urna duis convallis convallis. Gravida quis blandit turpis cursus in. Congue nisi vitae suscipit tellus mauris a diam maecenas sed. Ultrices neque ornare aenean euismod elementum. Morbi tempus iaculis urna id volutpat lacus laoreet non curabitur. Fermentum posuere urna nec tincidunt praesent semper. Nulla pellentesque dignissim enim sit amet venenatis urna cursus. Tortor at risus viverra adipiscing at in tellus integer feugiat. Mattis rhoncus urna neque viverra justo nec. Dictumst quisque sagittis purus sit. Enim facilisis gravida neque convallis a cras semper. Cursus mattis molestie a iaculis. Sapien eget mi proin sed libero. Diam vulputate ut pharetra sit amet aliquam. Sit amet dictum sit amet justo donec enim.</p>
        </div>
      </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'blog',
  data () {
    return {
      title: 'Blog'
    }
  }
}
</script>

<style scoped>
.blog {
  margin: 50px 0 0 55px;
  font-family: Helvetica, sans-serif;
}

.header {
  letter-spacing: 5px;
  font-size: 30px;
  margin-bottom: -15px;
}

.content {
  width: 75%;
  
}

img{
  width: 75%;
  margin: 0 0 1em 10%;
}

.card {
  background-color: white;
  padding: 20px;
  margin-top: 20px;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>