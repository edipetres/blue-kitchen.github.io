<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-6 no-gutters">
        <iframe class="stboard" height="1080" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://www.rejseplanen.dk/bin/help.exe/mn?L=vs_tus.vs_new&tpl=monitor&station=10120&view=dep&stopFrequency=high&p1=bus&p1rows=15&preview=200&p1icon=yes&p1freeTitle=Klampenborgvej%20St."></iframe>
      </div>
      <div class="col-md-6 no-gutters">
        <iframe class="stboard" height="1080" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://www.rejseplanen.dk/bin/help.exe/mn?L=vs_tus.vs_new&tpl=monitor&station=8600675&view=dep&stopFrequency=high&p1=stog&p1rows=15&preview=200&p1icon=yes&p1freeTitle=Lyngby%20St."></iframe>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.no-gutters {
  margin-right: 0;
  margin-left: 0;
  padding-left: 0;
  padding-right: 0;
}

.stboard {
  width: 100%;
}

/* scale content size down */
#wrap {
  height: 100vh;
  padding: 0;
  overflow: hidden;
}

#frame {
  height: 100vh;
}

#frame {
  -ms-zoom: 0.75;
  -moz-transform: scale(0.75);
  -moz-transform-origin: 0 0;
  -o-transform: scale(0.75);
  -o-transform-origin: 0 0;
  -webkit-transform: scale(0.75);
  -webkit-transform-origin: 0 0;
}

</style>
