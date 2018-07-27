<template>
  <div class="VizMain">
    <Tableau 
    url="https://public.tableau.com/views/Unemployment-MRB-72618/Sheet1"
    height="500px" 
    width="500px" 
    ref="tableau">
</Tableau>
</div>
</template>

<script>
export default {
  name: "VizMain"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.VizMain {
  display: flex;
  justify-content: center;
  align-items: center;
}
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
button {
  visibility: hidden;
}
</style>