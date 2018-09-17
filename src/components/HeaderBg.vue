<template>
    <div class="bg">
      <div class="bg-images">
    <div class="black-bg">
      asd
    </div>
      </div>
    </div>
</template>
<style scoped>
.bg {
  --color-1: #20c997;
  --color-2: #050f2c;
  --color-3: #03a9f4;
  width: 100%;
  min-height: 400px;
  background: #7f7fd5;
  background: linear-gradient(to bottom, #050f2c, #656f8d);
  /*background-image: linear-gradient(#656f8d, #3f2e7a);*/
}
.bg-images {
  width: 100%;
  min-height: 400px;
  background: url(../assets/iop-left-1.svg) bottom 0 left 0 no-repeat,
    url(../assets/iop-mid-1.svg) bottom 0 left 0 repeat-x,
    url(../assets/iop-right-1.svg) bottom 0 right 0 no-repeat;
  opacity: 0.8;
}
.black-bg {
  width: 100%;
  min-height: 400px;
  background-color: rgba(0, 0, 0, 0.3);
}
</style>
