<template>
  <div class="about">
    <div class="rightSection">
      <h1>About</h1>
      <div class="hl"></div>
      <div class="section1">
        <p>This website is about Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <img src="./images/sample-about.jpg" alt="Programming Image">
        <p>Our mission is to Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      </div>
    </div>
    
    <div class="leftSection"></div>
    
  </div>
</template>

<script>
export default {
  name: 'about',
  data () {
    return {
      msg: 'About'
    }
  }
}
</script>


<style scoped>
.about{
  font-family: Helvetica, sans-serif;
  margin: 50px 0 0 55px;
  display: flex;
}

h1{
  letter-spacing: 5px;
  font-size: 30px;
}

.hl {
  margin-bottom: 20px;
  height: 1px;
  width: 100%;
  background: lightgrey;
}

.leftSection{
  margin: 5em;
  width: 100em;
  height: 30em;
  background: white;
  filter: drop-shadow(0 0 2px #333);
}

img{
  width: 60%;
  margin: 0 15% 20px 15%;
}

</style>
