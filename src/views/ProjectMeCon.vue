<!--  -->
<template>
  <section>
		<div class="box"></div>	
    <div class="box"></div>
	</section>
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
  section{
		flex:1;
		overflow-y: auto;
		width:100%;
    .box{
      width:100%;
      height:2rem;
      background: pink;
    }
	}
	
</style>