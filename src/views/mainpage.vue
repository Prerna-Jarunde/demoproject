<template>
  <div class="home">
    <HeaderSection/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSection from '@/components/headerSection.vue';

export default {
	name: 'mainpage',
	components: {
		HeaderSection,
	},
};
</script>
