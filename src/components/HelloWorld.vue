<template>
  <div>
    <angry-header></angry-header>
  </div>
</template>

<script>
import {Components} from 'advo-package-proto'
export default {
  name: 'HelloWorld',
  components: {
    ...Components
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "~advo-package-proto/dist/advo-proto.css";
h3 {
  margin: 40px 0 0;
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
