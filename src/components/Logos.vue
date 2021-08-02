<template>
  <div class="logos-wrapper">
    <h3 class="title-header">Find Best Logo</h3>
    <div class="item-logos">
      <img class="logo" alt="Vue logo" src="../assets/logo-test-1.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="Vue logo" src="../assets/logo-test-2.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="Vue logo" src="../assets/logo-test-3.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="Vue logo" src="../assets/logo-test-4.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="Vue logo" src="../assets/logo-test-5.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="Vue logo" src="../assets/logo-test-6.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="Vue logo" src="../assets/logo-test-3.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="Vue logo" src="../assets/logo-test-4.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="Vue logo" src="../assets/logo-test-5.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="Vue logo" src="../assets/logo-test-6.png" />
    </div>
  </div>
</template>
    


<script>
export default {
  name: "Logos",
};
</script>



<style scoped>
.title-header {
  margin-bottom: 80px;
  text-align: left;
}
.logos-wrapper {
  width: 62%;
  overflow: hidden;
  margin: auto;
  /* background: honeydew; */
}

.item-logos {
  width: 150px;
  height: 150px;
  float: left;
  margin: 0 70px 70px 0;
}

.item-logos .logo {
  width: 150px;
  height: 150px;
}
</style>