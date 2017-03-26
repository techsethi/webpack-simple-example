<template>
	<div>
		<input type="text" name="" v-model="message">
		<p>{{ message }}</p>
	</div>
</template>

<script type="text/javascript">
	export default {
		data() {
			return {
				message: ''
			}
		}
	}
</script>