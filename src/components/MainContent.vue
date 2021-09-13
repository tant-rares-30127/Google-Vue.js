<template>
  <div class="main-content">
    <div class="center">
      <img src="../assets/google-logo.png" class="logo" />
    </div>
    <div class="search">
      <img src="../assets/glass-2.png" />
      <input type="text" class="search-bar" />
      <a href="#" class="mic"><img src="../assets/mic-2.png" /> </a>
    </div>
    <div class="search-buttons">
      <button type="button" class="btn">Căutare Google</button>
      <button type="button" class="btn">Mă simt norocos</button>
    </div>
    <div class="center">
      <p>Google oferit în:</p>
      <a href="#">English</a>
      <a href="#">Magyar</a>
      <a href="#">Deutsch</a>
    </div>
  </div>
</template>

<style>
.main-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.logo {
  margin: 5px;
}

.search {
  display: flex;
  justify-content: center;
  justify-content: space-between;
  align-items: center;
  border: solid 1px gray;
  border-radius: 30px;
  height: 40px;
  width: 30%;
  min-width: 300px;
}

.search:hover {
  box-shadow: 0px 1px 5px #949494;
}

.search-bar {
  height: 90%;
  width: 90%;
  padding-left: 10px;
  padding-right: 10px;
  border: transparent;
}

.search-bar:focus-visible {
  outline: none;
}

.search-buttons {
  display: flex;
  justify-content: center;
  margin-top: 30px;
  gap: 20px;
  height: 13%;
}

.btn {
  background-color: #f8f9fa;
  border: #f8f9fa;
  padding: 5px;
}

.btn:hover {
  box-shadow: 0px 1px 5px #949494;
}

.center {
  display: flex;
  justify-content: center;
  align-items: center;
  color: #3c4043;
}
</style>