<!--  -->
<template>
 <footer>
   <a href="#"><i></i><span>首页</span></a>
   <a href="#"><i></i><span>探店</span></a>
   <a href="#"><i></i><span>发现</span></a>
   <a href="#"><i></i><span>我</span></a>
 </footer>
</template>

<script  type='text/ecmascript-6'>
export default {
  data () {
    return {
    };
  },

  components: {},

  methods: {}
}

</script>
<style lang="scss" scoped>
  footer{
    display: flex;
    justify-content: space-around;
		width:100%;
		line-height: .52rem;
		background: #f9f9f9;
    font-size: .09rem;
    a{
      color:#2f2f2f;
    }
	}
</style>