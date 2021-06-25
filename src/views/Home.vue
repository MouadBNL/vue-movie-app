<template>
	<AppLayout>
		<div class="home">
			<h1 class="text-lg">Vue movie app</h1>
		</div>
	</AppLayout>
</template>

<script>
import AppLayout from '@/layouts/AppLayout.vue'
// @ is an alias to /src

export default {
  components: { AppLayout },
  name: 'Home',
}
</script>
