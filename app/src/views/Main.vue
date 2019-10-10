<template>

  <div class="main">

    <!-- Alert info -->
    <div class="alert-info danger">
      <!-- <img src="../assets/icon-location.png" alt="icon of location"> -->
      <p>Aucun incident en cours</p>
    </div>

  </div>
  

</template>

<script>
export default {
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

.alert-info {
  background: #F7F7F7;
  width: 100vw;
  height: 260px;
  display: flex;
  justify-content: center;
  flex-direction: column;
}

.danger {
  background: #E7464C;
  color: #ffffff;
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
</style>
