<template>
  <div>
    <p>메인 페이지</p>
  </div>
</template>

<script>
import axios from 'axios'

export default {
  async created() {
    const response = await axios.get('https://localhost:3000/products')
    console.log(response)
  }
}
</script>


<style>
</style>
