<template>
  <div class="home">
    <audio id="player" src="../../public/sound.mp3"></audio>
    <div class="player">
      <h3 onclick="document.getElementById('player').play(); document.getElementById('player').volume=0.1">charon.pw</h3>
    </div> 
    <a href="https://vk.com/austinly" target="_blank" rel="noopener noreferrer">vk</a> |
    <a href="https://www.youtube.com/channel/UCjbgucEBsBC0HtgsZdYppOA?view_as=subscriber" target="_blank" rel="noopener noreferrer">yt</a> |
    <a href="https://soundcloud.com/ledior" target="_blank" rel="noopener noreferrer">sc</a> |
    <a href="https://steamcommunity.com/id/gallerist" target="_blank" rel="noopener noreferrer">ac</a>
    <div class="blockquote" style="margin-top: 2%">
      <p class="quote">death is not so scary when everything died</p>
    </div>
    <p class="discord">heming#1871</p>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
@media screen and (max-width: 1200px) {
  .blockquote {
    width: 100%;
  }
  img {
    display: none;
  }
}
.player {
  display: flex;
  justify-content: center;
}
.home {
  margin-top: 15%;
  transition-duration: 5s;
  color: #fff;
}
.discord {
  font-family: "vcc";
  font-size: 20px;
  color: #333;
}
a {
  font-family: "vcc";
  text-decoration: none;
  color: #555;
  margin-left: 10px;
  margin-right: 10px;
  font-size: 20px;
  transition-duration: .5s;
}
a:hover {
  color: red;
  text-shadow: 1px 1px 2px black, 0 0 1em red;
}
h3 {
  margin-top: 2%;
  font-family: "vcc";
  transition-duration: .5s;
  text-align: center;
}
h3:hover {
  cursor: pointer;
  color: red;
  text-shadow: 1px 1px 2px black, 0 0 1em red;
}
.blockquote {
  width: 50%;
  margin: 0 auto;
}
.quote {
  margin-top: -2%;
  font-family: "vcc";
  color: #fff;
  font-size: 25px;
}
img {
  width: 30%;
}
</style>