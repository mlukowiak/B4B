<template>
  <div>
    <NewestCopies/>
  </div>
</template>

<script>
// @ is an alias to /src
import NewestCopies from '@/components/NewestCopies.vue'

export default {
  name: 'Home',
  components: {
    NewestCopies
  }
}
</script>
