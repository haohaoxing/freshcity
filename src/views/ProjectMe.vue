<!--  -->
<template>
  <div class="body">
      <project-header></project-header>
      <project-me-con></project-me-con>
      <project-footer></project-footer>
  </div>
</template>

<script  type='text/ecmascript-6'>
import ProjectHeader from "../components/commons/ProjectHeader"
import ProjectFooter from "../components/commons/ProjectFooter"
import ProjectMeCon from "./ProjectMeCon"
export default {
  data () {
    return {
    };
  },

  components: {
    ProjectMeCon,
    ProjectHeader,
    ProjectFooter
  },

  methods: {}
}

</script>
<style lang="scss" scoped>
.body{
  height:100%;
  display:flex;
  flex-direction: column;
  justify-content: space-between;
  overflow-x: hidden;
}
  
</style>