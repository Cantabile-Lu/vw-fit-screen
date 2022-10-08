<template>
  <div class="header">header</div>
  <div class="projectOverView-frame">
    <div>one</div>
    <div class="frame__map">two</div>
    <div>three</div>
    <div>four</div>
    <div>five</div>
    <div>six</div>
    <div>seven</div>
    <div>eight</div>
  </div>
</template>

<style lang="scss">
@import "styles/unitll";
* {
  margin: 0;
  padding: 0;
}
body {
  box-sizing: border-box;
}

.header {
  height: vh(100);
  border: 1px solid blue;
  margin-bottom: vh(20);
}
.projectOverView-frame {
  box-sizing: border-box;
  font-size: 16px;
  display: grid;
  grid-template-columns: vw(440) vw(960) vw(440);
  grid-template-rows: vh(386) vh(268) vh(246);
  gap: vh(20);
  justify-content: center;
  div {
    border: 1px solid green;
  }
  .frame__map {
    grid-row-start: span 2;
  }
}
</style>
