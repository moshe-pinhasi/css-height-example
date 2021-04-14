<template>
  <div id="app">
    <div class="header center">header</div>
    <div class="body">body</div>
    <div class="footer center">
      <button>btn example</button>
    </div>
  </div>
</template>

<style lang="scss">
#app {
  height: 100%;
  display: flex;
  flex-direction: column;
}

.header {
  height: 40px;
  background-color: burlywood;
  color: white;
}

.body {
  flex: 1;
}

.footer {
  height: 40px;
  background-color:cadetblue;
  color: white;
}

.center {
  display: flex;
  justify-content: center;
  align-items: center;
}

</style>
