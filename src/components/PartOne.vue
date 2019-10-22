<template>
  <div class="part-one">
    <img class="part-one-image" :src="headImage" alt="头像">
    <p>姓&emsp;&emsp;名：黄庚中</p>
    <p>工作年限：3 年</p>
    <p>大学专业：软件工程</p>
    <p>年&emsp;&emsp;龄：26</p>
    <p>联系电话：18825113670</p>
    <p>电子邮箱：915835528@qq.com</p>
    <p>CSDN博客：<a href="https://blog.csdn.net/xiaodi520520" target="_blank">xiaodi520520</a></p>
    <p>GitHub：<a href="https://github.com/huanggengzhong" target="_blank">huanggengzhong</a></p>
  </div>
</template>

<script>
export default {
  name: "partOne",
  data() {
    return {
      headImage: require('../assets/img/微信图片_20191022171931.jpg')
    }
  }
};
</script>

<style scoped>
a {
  color: deepskyblue;
}
a:hover {
  color: rgb(118, 190, 248);
}
p {
  line-height: 30px;
}
.part-one {
  width: 100%;
  height: 500px;
  border: 40px solid transparent;
  border-image: url("~@/./assets/img/border_image.png") 30 30 stretch;
  background: #18202d;
  padding-left: 10px;
}
.part-one-image {
  width: 130px;
  height: 130px;
  display: block;
  /* border-radius: 50%; */
  margin-left: 51px;
    margin-bottom: 16px;
}
</style>