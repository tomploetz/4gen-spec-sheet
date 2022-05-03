<template>
  <div class="text-center">
    <v-col class="mb-4">
      <v-text-field
        label="Enter Part Number"
        v-model="partNumber"
      >
      
      </v-text-field>
      <v-btn
        @click="select"
      >
        Submit
      </v-btn>
    </v-col>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      partNumber: ""
    }
  },
  methods: {
    select () {
      
    }
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
