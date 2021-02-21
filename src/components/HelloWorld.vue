<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      <a href="https://www.ipscape.com" target="_blank" rel="noopener">ipSCAPE website</a>
    </p>
    <p>
      <input v-model="greetingName" />
    </p>
    <p>
      <button @click="greet">Say hi</button>
    </p>
    <p>
      <img v-show="showSecretImage" alt="Vue logo" src="../assets/logo.png">
    </p>
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
      greetingName: '',
    };
  },
  computed:{
    showSecretImage(){
      return this.greetingName === 'ipscape';
    }
  },
  methods:{
    greet(){
      alert(this.greetingName);
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
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
  color: orange;
}
</style>
