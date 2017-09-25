<template>
  <div class="index">
   <div class="box_top">

   </div>
   <div class="box_bottom">
      <div class="box_bottom_left">

      </div>
      <div class="box_bottom_right">
         <el-row>
            <el-col :span="12"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="12"><div class="grid-content bg-purple-light"></div></el-col>
          </el-row>
      </div>
   </div>

  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.index{
  width: 100%;
  height: 100%;
.box_top{
    height: 10%;
    width: 100%;
    background: darkblue;
  }
  .box_bottom{
    height: 90%;
    width: 100%;    
   
    display: flex;
    .box_bottom_left{
      width: 230px;
       background: saddlebrown;
       height: 100%;
    }
    .box_bottom_right{
      flex: 1;
      
       height: 100%;
     
    }
  }
}
  
    .el-row {
    margin-bottom: 20px;
    &:last-child {
      margin-bottom: 0;
    }
  }
  .el-col {
    border-radius: 4px;
  }
  .bg-purple-dark {
    background: #99a9bf;
  }
  .bg-purple {
    background: #d3dce6;
  }
  .bg-purple-light {
    background: #e5e9f2;
  }
  .grid-content {
    border-radius: 4px;
    min-height: 36px;
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
</style>
