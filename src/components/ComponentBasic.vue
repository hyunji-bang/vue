<template>
  <div>
    <p>도시를 선택해주세요</p>
    <select name="" id="" v-model="selectCityName" @change="changeCity">
        <option value="02">서울</option>
        <option value="031">경기도</option>
        <option value="051">부산</option>
    </select>
  </div>
</template>

<script>
export default {
  name: 'AboutName', // 컴포넌트 이름
  components: {}, // 다른 컴포넌트 사용 시 컴포넌트를 import하고 배열로 저장
  data () { // html과 자바스크립트 코드에서 사용할 데이터 변수 선언
    return {
      selectCityName: ''
    }
  },
  methods: {
    changeCity () {
      console.log(this.selectCityName)
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  select {width: 200px; padding:5px}
</style>
