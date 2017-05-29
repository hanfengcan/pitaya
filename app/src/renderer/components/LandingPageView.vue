<template>
  <div style="height: 100%;">
    <el-row style="height: 100%;">
      <el-col :xs="18" :sm="14" :md="16" :lg="18" style="height: 100%;"><div class="code"></div></el-col>
      <el-col :xs="6" :sm="10" :md="8" :lg="6" style="height: 100%;">
        <div class="button">

        </div>
        <div class="output">

        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script>

  export default {
    components: {
    },
    name: 'landing-page'
  }

</script>

<style scoped>
  .code {
    background: #FF8;
    height: 100%;
    padding-right: 2px;
  }

  .button {
    background: #FA6;
    height: 30%;
    padding-left: 2px;
  }

  .output {
    background: #AC9;
    height: 70%;
    padding-left: 2px;
  }
</style>
