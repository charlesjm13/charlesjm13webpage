<template>
  <div class="home">
    <div style="font-weight: bold; font-size: 40px; font-family: cursive; padding-bottom: 20px;" class="w3-cursive">
      Welcome!
    </div>
    <div style = "padding-bottom: 10px;">
      <img alt="Face" src="./assets/face.png" style="height: auto; max-width: 25%;">
    </div>
    <div style="font-weight: bold; font-size: 40px; font-family: cursive; padding-bottom: 20px; max-width: 50%; text-align: center;" class="w3-cursive">
      My name is Charles Mennerick. I am from Saint Louis, Missouri. I am a computer science major and chemistry minor. I attend Knox College in Galesburg, Illinois.
    </div>
    <div style="padding-bottom: 20px;">
      <button 
        v-on:click="showResume = !showResume"
        style="font-size: 40px;"
        >
        Toggle Resume
      </button>
    </div>
    <div v-if="showResume">
        <img alt="Resume" src="./assets/CharlesMennerickResume.png" style="height: auto; max-width: 100%; margin: auto;">
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  data() {
    return {
      showResume: false
    }
  }

}
</script>

<style>
.home {
 text-align: center;
 background-color: #727474;
 color: #c6c9c7;
 max-width: auto;
 max-height: auto;
 margin: auto;
}
</style>
