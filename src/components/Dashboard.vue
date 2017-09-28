<template>
  <div class="hello">
    <iframe id="kl-station" title="Example2" width="700" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="http://www.rejseplanen.dk/bin/help.exe/mn?L=vs_tus.vs_new&tpl=monitor&station=10120&view=dep&stopFrequency=high&p1=bus&p1rows=15&preview=200&p1icon=yes&p1freeTitle=Departures%20from%20Klampenborgvej%20St."></iframe>
    <iframe id="kl-station" title="Example2" width="700" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="http://www.rejseplanen.dk/bin/help.exe/mn?L=vs_tus.vs_new&tpl=monitor&station=8600675&view=dep&stopFrequency=high&p1=stog&p1rows=15&preview=200&p1icon=yes&p1freeTitle=Departures%20from%20Lyngby%20St."></iframe>

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
#kl-station{
  height: 100vh;
}

h1,
h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
