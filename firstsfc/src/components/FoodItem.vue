<template>
  <div class="Strawberry">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Strawberry',
      message: 'I like Strawberry'
    }
  }
};
</script>

<style>
  .Strawberry {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: red;
  }

</style>