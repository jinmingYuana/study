<template>
  {{ msg }}{{ num }}{{ ok?"yes":"no" }}

  0
</template>
<script>
export default{
  data(){
    return{
      msg:"神奇的语法",
      num:1+1,
      ok:true
    }
  }
}  
</script>
