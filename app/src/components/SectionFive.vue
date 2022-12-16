<template>
  <div class="">
    <div class="container">
      <img src="images/pic5.png" alt="" />
      <div class="wrapper">
        <h2 class="stage">Stage 5: Solitude, 1923</h2>
        <p class="description">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat. Duis aute irure dolor in
          reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
          pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
          culpa qui officia deserunt mollit anim id est laborum.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionFive",
};
</script>

<style scoped>
img {
  width: 25rem;
  height: 25rem;
}

.stage {
  margin-bottom: 3rem;
}

.container {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  align-items: center;
}

.wrapper {
  width: 40%;
}
</style>