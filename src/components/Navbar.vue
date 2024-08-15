<template>
	<v-container fluid>
			<v-app-bar
        color="primary"
        density="compact"
      >
				<v-spacer />
				<v-btn outlined class="ml-3" color="white">
					<router-link to="/">Главная</router-link>
				</v-btn>
				<v-btn outlined class="ml-3" color="white">
					<router-link to="/photo">Фото</router-link>
				</v-btn>
      </v-app-bar>
		</v-container>
</template>

<script>
	export default {
		
	}
</script>

<style scoped>

</style>