<template>
    
    <Movie/>
    <faq/>
    
  
</template>

<script>
// @ is an alias to /src
import faq from '@/components/faq.vue'
import Movie from '@/components/Movie.vue'

export default {
  name: 'Home',
  components: {
    faq,
    Movie
  }
}
</script>
