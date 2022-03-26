 <template>
  <div id="app">
    <div class="container">
      <div class="row">
        <div class="col-12">
            <div class="header">
              <mioTitolo />
              <img alt="Vue logo" src="./assets/logo.png" />

            
            </div>
    
            <div class="jumbo">
              <mioEroe />
              <img  alt="Vue logo" src="./assets/img/montagna.jpg" />
              
              
            </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>

import mioTitolo from "./components/titolo.vue" ;
import mioEroe from "./components/hero.vue" ;
export default {
  name: 'App',
  components:{
    mioTitolo,
    mioEroe,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}

.jumbo img{
  width: 100%;
  height: calc(100% - 262.933px );
}

</style>
