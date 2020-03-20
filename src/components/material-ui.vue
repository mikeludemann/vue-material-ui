<template lang="html">

	<section class="material-ui">
		<div class="material">
			<md-button class="md-raised">
				<ng-content></ng-content>
			</md-button>
		</div>
	</section>

</template>

<script>

	export default {
		name: 'MaterialUI',
		props: [],
		mounted () {

		},
		data () {
			return {

			}
		},
		methods: {

		},
		computed: {

		}
}


</script>

<style scoped lang="scss">
	.material-ui {

	}
</style>
