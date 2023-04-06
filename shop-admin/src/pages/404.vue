<template>
  <div>
    <el-col :sm="12" :lg="6">
      <el-result
        icon="warning"
        title="404页面"
        sub-title="您查找的页面不存在"
      >
        <template #extra>
          <el-button type="primary">返回上一页</el-button>
        </template>
      </el-result>
    </el-col>
  </div>
</template>