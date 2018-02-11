<template>
  <div>
    <h1>{{ msg }}</h1>
    <h2>{{ msg2 }}</h2>
  </div>
</template>

<script>
export default {
  name: 'Message',
  data() {
    return {
      msg: 'NikolasMelui starts here!',
      msg2: 'And here))'
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-weight: normal;
}
a {
  color: #42b983;
}
</style>
