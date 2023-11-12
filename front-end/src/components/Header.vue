<script>
export default {
  name: "Header",
  data() {
    return {
      msg: "微小目标识别与数据统计",
      activeIndex: "1",
    };
  },
  methods: {},
};
</script>

<template>
  <div id="Header">
    <div class="top-left-edition">
      <span style="color: rgb(38,179,185); font-weight: bold">
        <i class="el-icon-s-custom" style="font-size: 23px"></i>
        <i class="el-icon-message" style="font-size: 23px"></i>
      
       <img src="../img/like.png" width="20" height="20"> 
       <img src="../img/heart.jpg" width="20" height="20">
       <img src="../img/setting.jpg" width="20" height="20">  
       <img src="../img/b.jpg" width="20" height="20">
       <img src="../img/s.jpg" width="20" height="20"> 
      </span>
     
  
      <span>
        <img src="http://qqpublic.qpic.cn/qq_public/0/1-2018663934-EC352A6E69B06371C97DD5610E286D50/0" alt="帅气修勾" width="200" height="100">
      </span>
 
    </div>
    
  
  
   
    <div id="word">
      <h1>{{ msg }}</h1>
     
    </div>
  
  </div>

      
  
</template>
<style scoped>  

#Header {
  padding: 30px 110px 0 150px;
  width: 90%;
  margin: 10px auto;
}

#word {
  margin-left: 45%;
  margin-top: -35px;
  margin-bottom: 37px;
  height: 60px;
  line-height: 3.2em;
  letter-spacing: 8px;
}

h1 {
  /*text-align: center;*/
  color: rgb(38,179,185);
  margin-left:-310px;
  letter-spacing: 1px;
  font-size: 3em;
}

.el-menu-demo {
  width: 80%;
  margin: 0px auto;
  padding: 0px auto;
}

.top-left-edition span i {
  float: left;
  margin-right: 5px;
}

i,
input,
label {
  vertical-align: middle;
}

i {
  border: 0;
  display: block;
  cursor: pointer;
}

.top-left-edition span {
  float: left;
  font-size: 16px;
  color: #e710f3;
  line-height: 24px;
  margin-right: 40px;
}
</style>


