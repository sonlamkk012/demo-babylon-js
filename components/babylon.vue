<!-- Please remove this file from your project -->
<template>
  <div class="container">
    <div class="title">
      <h2>
        <span>Lâm Sơn</span>
      </h2>
      <h3><span>Babylon Js</span></h3>
    </div>
    <iframe
      id="iframeAR"
      scroll="no"
      room="none"
      width="100%"
      height="1000"
      src="demo2/demo-babylon.html"
      frameborder="0"
      allowtransparency="true"
    ></iframe>
  </div>
</template>

<script>
export default {
  name: "Babylon",
  mounted() {},
};
</script>

<style>
.container {
  background-color: black;
}

.title {
  padding-top: 50px;
}

h2 {
  font-size: 60px;
  line-height: 60px;
  font-weight: 900;
  text-align: center;
}

h2 span {
  background: linear-gradient(
    0deg,
    rgba(148, 187, 233, 1) 0%,
    rgba(119, 190, 187, 1) 20%,
    rgba(238, 174, 202, 1) 50%
  );
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

h3 {
  font-size: 50px;
  line-height: 50px;
  font-weight: 900;
  text-align: center;
}
span {
  background: linear-gradient(92deg, #c7a0ca, #5e68b3 49.48%, #61c2ee), #fff;
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
