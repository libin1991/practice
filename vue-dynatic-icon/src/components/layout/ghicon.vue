<template>
  <a href="https://github.com/Guoch0526/practice/tree/master/vue-dynatic-icon" class="github">
    <img :src="githubImg" alt="github" class="github_icon">
    <span class="star">star</span>
  </a>
</template>

<script>
  import githubImg from '../../../static/img/timg.png'

  export default{
    data() {
      return {
        githubImg
      }
    },
  }
</script>
<style lang="less" rel="stylesheet/less">
    .github{
      display: inline-block;
      margin-left: 5px;
      background-color: #eeeeee;
      border: 1px solid #d5d5d5;
      padding: 2px 5px 2px 4px;
      color: #333;
      text-decoration: none;
      text-shadow: 0 1px 0 #fff;
      white-space: nowrap;
      cursor: pointer;
      border-radius: 3px;
      background-image: linear-gradient(to bottom,#fcfcfc 0,#eee 100%);
      box-sizing: border-box;
      height: 20px;
      line-height: 14px;
      .github_icon{
        display: inline-block;
        width: 14px;
        height: 14px;
        // background-image: url(../../../static/img/timg.png);
        background-size: 100% 100%;
        background-repeat: no-repeat;
      }
      .star{
        display: inline-block;
        color: #333;
        text-decoration: none;
        text-shadow: 0 1px 0 #fff;
        font-size: 14px;
        font-weight: 700;
        line-height: 14px;
        vertical-align: top;
      }
    }
    .github:hover{
      background-image:  linear-gradient(to bottom,#eee 0,#ddd 100%);;
    }
</style>
