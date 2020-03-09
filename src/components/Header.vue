<template>
   <div id="header">

     <header class="header">

           <div class="img-header">
             <img src="" alt="">
           </div>
           
           <div class="nav-header">
              <nav>
                    <div class="router-links">
                      <router-link to="/">Home</router-link>
                      <router-link to="/about">Sobre Nós</router-link>
                      <router-link to="/contact">Contato</router-link>
                    </div>
              </nav>


           </div>
     </header>
     
   </div>  
</template>

<script>
export default {
name:"Header"

}
</script>

<style scoped>
header {
    width: 100vw;
    height: 80px;
}

</style>