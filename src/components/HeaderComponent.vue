<template>
  <div id="app" class="header">
    <h1 class="title">tomoguru</h1>
    <p class="slogan">Conecta con gente de tu mismo rollo</p>
    <button class="btn">
      <span class="explorer">Explora eventos</span>
    </button>
  </div>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Varela&display=swap");
.header {
  background: linear-gradient(71.87deg, #14a6ec 0.62%, #f959d0 97.87%);
  width: 1440px;
  height: 850px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.title {
  width: 180px;
  height: 30px;
  color: white;
  font-family: "Varela", sans-serif;
  font-size: 56px;
  line-height: 15px;
}
.slogan {
  width: 600px;
  height: 26px;
  /* margin: 15px; */
  margin-left: 16%;
  margin-top: 2%;
  color: white;
  font-family: "Varela", sans-serif;
  font-size: 26px;
}
.btn {
  background-color: transparent;
  width: 200px;
  height: 43px;
  border: 3px solid white;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.15);
  border-radius: 50px;
  margin-top: 3%;
  margin-left: 6%;
}
.explorer {
  color: white;
  width: 200px;
  height: 26px;
  font-family: "Varela", sans-serif;
  font-size: 18px;
}
</style>
