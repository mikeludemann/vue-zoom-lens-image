<template>
	<div class="home">
		<img alt="Vue logo" src="../assets/logo.png">
		<HelloWorld msg="Welcome to Your Vue.js App"/>
		<ZoomLensImage
			id="image-test"
			size="50px"
			width="600"
			height="400"
			imagename="https://www.scinexx.de/wp-content/uploads/0/1/01-34892-supernova.jpg"
			alttext="Supernova"
			zoomlevel="5"
		></ZoomLensImage>
	</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import ZoomLensImage from '@/components/zoomLensImage.vue'

export default {
	name: 'Home',
	components: {
		HelloWorld,
		ZoomLensImage
	}
}
</script>
