<template>
  <div class="big-header">
    <h1>{{ message }}</h1>
    <br />
    <router-link class="button" to="/game">Go to Page</router-link>
    <br />
  </div>
</template>

<script>

export default {
  data() {
    return {
      message: 'INTRO + RÈGLES DU JEU'
    }
  }
};
</script>
