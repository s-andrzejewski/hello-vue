<template>
  <div>
    <button @click="sayHello">Greet please</button>
  </div>
</template>

<script>
export default {
  name: 'MyFirstComponent',
  setup() {
    const sayHello = () => {
      alert("Hello user! Nice to meet you.");
    }

    return { sayHello };
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
