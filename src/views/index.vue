<template lang="pug">
  .view
    .title
      img(src="https://imgland.oss-cn-hangzhou.aliyuncs.com/photo/2018/47957fec-8abb-41d1-8146-f2cb9ec00971.png")
    .subTitle Long press the picture below and then share it to your friend
</template>

<script type="es6">
export default {
  name: 'home',
  data () {
    return {
    }
  },
  methods: {

  },
};
</script>

<style lang="stylus">
.container {
  min-width: 100vw;
  min-height: 100vh;
  background: url("https://imgland.oss-cn-hangzhou.aliyuncs.com/photo/2018/294d2924-6a20-4f75-aa29-cc48ae63305f.png");
  background-size: cover;
  background-position: 50%;
  background-repeat: no-repeat;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  div, span {
    font-size: 14px;
    font-family: SFUIDisplay-Semibold;
    font-weight: 600;
    color: rgba(255, 255, 255, 1);
    line-height: 16px;
  }
}
</style>
