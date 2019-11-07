<template>
  <div style="margin-top: 10px">
    <el-tabs v-model="defaultTab" type="card">
      <el-tab-pane label="菜单管理" name="menuMana">
        <menu-mana></menu-mana>
      </el-tab-pane>
   <!--   <el-tab-pane label="菜单权限管理" name="positionMana">
        <pos-mana state="position"></pos-mana>
      </el-tab-pane>-->
      <!--<el-tab-pane label="职称管理" name="jobTitleMana">
        <pos-mana state="jobtitle"></pos-mana>
      </el-tab-pane>
      <el-tab-pane label="奖惩规则" name="ecCfg">
        <ec-mana></ec-mana>
      </el-tab-pane>
      <el-tab-pane label="权限组" name="menuRole">
        <menu-role></menu-role>
      </el-tab-pane>-->
    </el-tabs>
  </div>
</template>
<script>

  import MenuMana from './basic/MenuMana.vue'

  export default {
    data() {
      return {
        defaultTab: 'menuMana'
      };
    },
    methods: {},
    components: {
      'menu-mana': MenuMana

    }
  };
</script>
