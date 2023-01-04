<template>
  <div class="">
    <div class="container">
      <img src="/pic1.png" alt="" />
      <div class="wrapper">
        <h2 class="stage">Stage 1: Extravagance, 1896</h2>
        <p class="">
          <span class="type">Composition:</span> the painting's focus on Leonce
          and his luxurious surroundings suggests that the artist is interested
          in depicting the man's wealth and status. The placement of Leonce's
          face in a dark shadow could be interpreted as a deliberate choice to
          obscure or conceal his identity, possibly suggesting that his wealth
          and status are more integral to his sense of self than his personal
          qualities or characteristics. <br /><br /><span class="type"
            >Style:</span
          >
          the bright, vibrant colors used to depict the luxury home and its
          surroundings could be interpreted as representing the superficial
          glamor and excess of Leonce's lifestyle. In contrast, the dark shadow
          cast over Leonce's face could be seen as symbolizing the emptiness or
          superficiality of his existence.<br /><br />
          <span class="type">Interpretation:</span> the painting could be
          interpreted as a commentary on the corrupting influence of wealth and
          the dangers of living a superficial, materialistic lifestyle. It
          suggests that even those who seem to have it all may be lacking in
          deeper meaning or fulfillment, and that the pursuit of wealth and
          status can ultimately lead to a sense of isolation and emptiness.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionOne",
};
</script>

<style scoped>
img {
  width: 25rem;
  height: 25rem;
}

.stage {
  margin-bottom: 2rem;
}

.container {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  align-items: center;
}

.wrapper {
  width: 45%;
}

@media (max-width: 1200px) {
  img {
    width: 20rem;
    height: 20rem;
  }
  .wrapper {
    width: 60%;
  }
}
</style>