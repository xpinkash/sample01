<template>
  
  <div class="mainContent">
    <headerSection />
    <div class="inner">
         <bodybody />
      </div>
  </div>
</template>

<script>
import headerSection from '~/components/headerSection'
import bodybody from '~/components/bodybody'
export default {
  components: {
    headerSection,
    bodybody
  }
}
</script>

