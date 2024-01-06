<template>
  <div class="singer">
      33
  </div>
</template>

<script>
import { getSingerList } from '../service/singer'

export default {
  name: 'm-singer',
  async created() {
    const result = await getSingerList()
    console.log(result)
  }
}
</script>
