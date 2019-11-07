<template>
  <div>
    <el-row :gutter="20">
      <el-col :span="6">
        <div class="grid-content bg-purple"></div>
      </el-col>
      <el-col :span="6">
        <div class="grid-content bg-purple"></div>
      </el-col>
      <el-col :span="6">
        <div class="grid-content bg-purple"></div>
      </el-col>
      <el-col :span="6">
        <div class="grid-content bg-purple"></div>
      </el-col>
    </el-row>
  </div>
</template>
<script>
  export default {
    data() {
      return {
        emp: {
          name: '',
          gender: '',
          birthday: '',
          idCard: '',
          wedlock: '',
          nationId: '',
          nativePlace: '',
          politicId: '',
          email: '',
          phone: '',
          address: '',
          departmentId: '',
          departmentName: '所属部门...',
          jobLevelId: '',
          posId: '',
          engageForm: '',
          tiptopDegree: '',
          specialty: '',
          school: '',
          beginDate: '',
          workState: '',
          workID: '',
          contractTerm: '',
          conversionTime: '',
          notWorkDate: '',
          beginContract: '',
          endContract: '',
          workAge: ''
        }
      }
    }
  }
</script>
<style>
  .el-row {
    margin-bottom: 20px;

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
