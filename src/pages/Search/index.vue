<template>
  <div>
    Search<br>
     params参数:{{$route.params.keyword}}
    params:{{keyword}}
    query参数:{{$route.query.keyword}}
    query:{{keyword2}}
    
    </div>
</template>

<script>
export default {
  name: 'Search',
  props:['keyword','keyword2','name']
}
</script>

<style lang="less" scoped>

</style>
