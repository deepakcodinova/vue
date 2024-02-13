<template>
<el-row>
    <el-col
      v-for="(o) in 12"
      :key="o"
      :span="4"
    >
    <CardGif  />
    </el-col>
  </el-row>
  
</template>

<script>


 import CardGif from "./CardGif.vue" 

export default {
  name: "HelloWorld",
  components:{
     CardGif 
    
  },
};
</script>

<style >
.el-col 
{
  margin: auto;
}
</style>
