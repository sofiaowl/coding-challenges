<template>
  <div class="container">
    <h1>Coding Challenge</h1>
    <h3>
      Implement a button in the middle of the screen, so that it can be dragged
      around. As it moves towards the edges, the background color changes from
      white to
      <span class="tag accent">lightblue</span>
      .
    </h3>
    <img src="../assets/example.gif" width="320" height="320" />
  </div>
</template>

<script>
export default {
  name: "CodingChallange",
};
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}

.tag {
  padding: 2px 8px;
  border-radius: 2px;
}

.accent {
  background: lightblue;
  color: white;
}

img {
  margin-top: 26px;
}
</style>
