<template>
  <v-card>
    <v-img :src="imgSrc" height="200px">
    </v-img>
    <v-card-title primary-title>
      <div>
        <div v-line-clamp:20="1" class="headline">{{title}}</div>
        <span v-line-clamp:20="3" class="grey--text">{{body}}</span>
      </div>
    </v-card-title>
  </v-card>
</template>

<script>

export default {
	name: 'Portfolio',
	props: {
		date: {type: String},
		title: {type: String},
		body: {type: String},
		imgSrc: {type: String},
	},
	data() {
		return {
			//
		}
	}
}
</script>
