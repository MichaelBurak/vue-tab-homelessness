<template>
  <div class="hello">
    <div>
    <Tableau 
    url="https://public.tableau.com/views/Unemployment-MRB-72618/Sheet1"
    height="1000px" 
    width="1000px" 
    ref="tableau">
</Tableau>
  </div>
</div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
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
