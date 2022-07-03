<template>
  <div>
    <input type="text" name="" id="" v-bind:value="userId" readonly />
    <input type="text" name="" id="" :value="userId" readonly />
    <br />
    <img :src="imgSrc" alt="" style="width:100px; height:auto;">
    <br />
    <input type="search" name="" id="" v-model="txt1">
    <button :disabled="txt1 === ''">조회</button>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      userId: 'jan92',
      imgSrc: 'https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Apple_logo_black.svg/1667px-Apple_logo_black.svg.png',
      txt1: ''
    }
  },
  setup() {},
  created() {},
  mounted() {},
  methods: {}
}
</script>
