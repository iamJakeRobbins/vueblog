<template>
  <div class="new">
		<Header/>
    <h1>This is a new view</h1>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';

export default {
  name: 'new',
  components: {
		Header,
  }
}
</script>
