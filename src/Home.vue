<template>
  <div id="home">
    <b-tabs title="Home" active>
      <p>Welcome to my webpage</p>
    </b-tabs>
    <b-tabs title="About Me" active>
      <p>My name is Charles</p>
    </b-tabs>
    <b-tabs title="My Resume" active>
      <img alt="Vue logo" src="./assets/CharlesMennerickResume.png">
    </b-tabs>
  </div>
</template>

<script>

export default {
  name: 'Home',

}
</script>

<style>
#home {
 margin: auto; 
 text-align: center;
}
</style>
