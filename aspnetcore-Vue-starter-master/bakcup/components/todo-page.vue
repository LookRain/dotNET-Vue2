<template>
  <div>
    <h1>{{val}}</h1>
    <button @click="pop">im ddda button</button>
  </div>
</template>

<script>
	export default {
		data() {
			return {
				val: 'hahahaha'
			}	
		},

		methods: {
        pop() {
            alert('asdfsd');
        }
		}
	}
</script>