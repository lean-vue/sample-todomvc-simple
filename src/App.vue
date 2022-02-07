<template>
  <div class="well">
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Lean Vue App',
    };
  },
};
</script>

<style scoped>
h1 {
  font-size: 24px;
  font-weight: 500;
}
.well {
  max-width: 720px;
  margin: 4rem auto 0;
  padding: 2rem;
  background-color: #fafafa;
  border: 1px solid #c0c0c0;
  border-radius: 6px;
}
</style>
