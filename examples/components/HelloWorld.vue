<template>
  <colorPicker v-model="color" v-on:change="headleChangeColor"></colorPicker>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data () {
		return {
			color: '#ff0000'
		}
	},
	methods: {
		headleChangeColor () {
			console.log('颜色改变')
		}
	}
}
</script>

