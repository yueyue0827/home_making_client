<template>
  <div class="waiter">
    <!-- <el-table
      :data="tableData"
      style="width: 100%">
      <el-table-column
        prop="date"
        label="日期"
        width="180">
      </el-table-column>
      <el-table-column
        prop="name"
        label="姓名"
        width="180">
      </el-table-column>
      <el-table-column
        prop="address"
        label="地址">
      </el-table-column>
      <el-table-column label="操作" width="80" align="center">
          <template #default="record">
             <el-button type="info" size="mini" @click.prevent="toxq">详情</el-button>
          </template>
        </el-table-column>
    </el-table> -->
    <!-- <div>
      <el-table :data="waiters" size="mini" @selection-change="handleSelectionChange">
        <el-table-column type="selection" width="55" />
        <el-table-column prop="id" label="编号" />
        <el-table-column prop="realname" label="姓名" />
        <el-table-column prop="gender" label="性别" />
        <el-table-column prop="telephone" label="手机号" />
        <el-table-column prop="password" label="密码" />
        <el-table-column prop="registerTime" label="注册时间" />
        <el-table-column prop="status" label="状态" />
        <el-table-column label="操作" width="80" align="center">
          <template #default="record">
            <el-button type="info" size="mini" @click.prevent="toxq">详情</el-button>
          </template>
        </el-table-column>
      </el-table>
    </div>-->
  </div>
</template>
<script>
// import { mapState, mapGetters, mapMutations, mapActions } from 'vuex'
export default {
  data() {
    return {
      // tableData: [{
      //   date: '2016-05-02',
      //   name: '王小虎',
      //   address: '上海市普陀区金沙江路 1518 弄'
      // }, {
      //   date: '2016-05-04',
      //   name: '王小虎',
      //   address: '上海市普陀区金沙江路 1517 弄'
      // }, {
      //   date: '2016-05-01',
      //   name: '王小虎',
      //   address: '上海市普陀区金沙江路 1519 弄'
      // }, {
      //   date: '2016-05-03',
      //   name: '王小虎',
      //   address: '上海市普陀区金沙江路 1516 弄'
      // }]
    }
  },
  // computed: {
  //   ...mapState('waiter', ['waiters'])
  // },
  // created() {
  //   this.findAllWaiters()
  // },
  // methods: {
  //   ...mapActions('waiter', ['findAllWaiters']),
  //   toxq() {
  //     this.$router.push('/waiter/details')
  //   }
  // }
}
</script>
