<template>
  <div>
    <button id="TrSave">导出</button>
    <button @click="text">文字</button>
    <div id="MainCy" style="width:100%;height:750px;"></div>
  </div>
</template>

<script>
  export default {
    name: "index",
    data() {
      return{
        flag: false,
      }
    },
    methods: {
      text() {
        this.flag = !this.flag;
        if (this.flag) {
          cy.collection("edge").removeClass("edgeShowText");
        }else {
          cy.collection("edge").addClass("edgeShowText");
        }
      }
    }
  }
</script>

<style scoped>

</style>
