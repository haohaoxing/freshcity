<!--  -->
<template>
  <header>
		<div>西安<i></i></div>
		<h1>鲜城</h1>
		<a href="#"><img src="../../assets/images/commons/sousu.png"/></a>
	</header>
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
  header{
		display:flex;
		justify-content: space-between;
		width:100%;
		height:.48rem;
		background: #25262b;
		font-size: .09rem;
		div{
			width:.72rem;
			text-align: center;
			line-height: .48rem;
			font-size:.14rem;
			color:#fff;
		}
		h1{
			line-height: .48rem;
			font-size:.2rem;
			font-weight: 100;
			color:#fff;
		}
		a{
			display: block;
			height:100%;
		}
	}
</style>