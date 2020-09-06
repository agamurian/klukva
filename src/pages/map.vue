<template>
  <div>
    <g-image class="mapy" alt="Example image" src="./map.png" style="margin-left: -50vw; margin-top: 0px; width: 150vw;position:absolute; z-index:-100; position:fixed" />  
<div style="height: 100vh;background-image: ; color: #afbfdf; text-align: center; width: 100wv; margin: auto;">

  <Layout>
    
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <br><br><br>
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
        width:150vw;
        margin-left:0vw;
        margin-top: 0px;
    }
        50% {
  margin-top: -2000px;  
         margin-left: -200vw; 
        width: 400vw;
    }
    100% {
        width:150vw;
        margin-left:0vw;
        margin-top: 0px;
    }

}

.mapy{
animation-name: mapy;
  animation-duration: 400s;  
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
