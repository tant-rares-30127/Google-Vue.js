<template>
  <div class="navbar">
    <a href="#" class="textLink">Gmail</a>
    <a href="#" class="textLink">Imagini</a>
    <a href="#" class="topImg">
      <svg class="menu" focusable="false" viewBox="0 0 24 24">
        <path
          d="M6,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM16,6c0,1.1 0.9,2 2,2s2,-0.9 2,-2 -0.9,-2 -2,-2 -2,0.9 -2,2zM12,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2z"
        ></path>
      </svg>
    </a>
    <a href="#" class="topImg"><img src="../assets/me.png" class="myphoto"/></a>
  </div>
</template>

<style>
.navbar {
  display: flex;
  justify-content: flex-end;
  flex-direction: row;
}

.myphoto {
  border-radius: 50%;
}

.menu {
  height: 24px;
  width: 24px;
  fill: rgb(95, 99, 104);
}

.topImg {
  padding: 5px;
  padding-bottom: 1px;
  border: transparent;
}

.topImg:hover {
  box-shadow: 0px 1px 5px #949494;
  background-color: rgba(60, 64, 67, 0.08);
  border-radius: 50%;
}
</style>
