<template>
	<div class="home">
		<img alt="Vue logo" src="@web/assets/logo.png" />
		<HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
	</div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@web/components/HelloWorld.vue';

@Component({
	components: {
		HelloWorld,
	},
})
export default class Home extends Vue {}
</script>
