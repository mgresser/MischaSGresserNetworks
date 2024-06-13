<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Looking to network with likeminded cloud security professionals,<br />
      connect with me today!
    </p>
    <h3>Essential Links</h3>
    <ul
      <li>
        <a href="https://www.linkedin.com/in/mischagresser/" target="_blank" rel="noopener">My LinkedIn</a>
      </li>
      <li>
        <a href="https://www.cloudsecurityofficehours.com/" target="_blank" rel="noopener">Cloud Security Office Hours</a>
      </li>
      <li>
        <a href="https://twitter.com/wiz_io" target="_blank" rel="noopener">Twitter</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "MischaSGresserNetworks",
  props: {
    msg: String,
  },
};
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
  color: #42b983;
}
</style>
