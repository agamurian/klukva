<template>
  <div style="background-color: black; position: absolute; z-index: -200; width:100vw;">
    <g-image class="mapy" alt="Example image" src="./map.jpg" style="margin-left: -50vw; margin-top: 0px; width: 150vw;position:absolute; z-index:-100; position:fixed" />  
<div style="height: 100vh;background-image: ; color: #afbfdf; text-align: center; width: 100wv; margin: auto;">

  <Layout>
    
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <br>
    <g-image alt="Helicoter" src="./ver.png" style="width: 162px; height:112px; margin-right: -2vw; margin-top: -2vh;" />
    <h1>Карта Пленера Клюква</h1>
    <br><br><br>

    <p class="home-links" style="margin: auto;">
      <g-link href="/plainairs" target="_blank" rel="noopener">Пленеры</g-link>
    </p>

  </Layout>
</div></div>
</template>



<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>

<style>

@keyframes mapy {
    0% {
      opacity: 0.1;
        width:200vw;
        margin-left:-100vw;
        margin-top: -100px;
    }
    100% {
      opacity: 1.0;
        width:250vw;
        margin-left:-70vw;
        margin-top: -2000px;
    }

}

.mapy{
animation-name: mapy;
  animation-duration: 170s;  
}


.body{
	background-color: #002e44;
	color: #ededed;
}
.a{
	color: #e49e23;
}
.home-links a {
  margin-right: 1rem;
	color: #aebede;
}
</style>
