<template>
  <div class="">
    <div class="container">
      <img src="images/pic3.png" alt="" />
      <div class="wrapper">
        <h2 class="stage">Stage 3: Desolation, 1906</h2>
        <p class="description">
          <span class="type">Context:</span> American Realism was characterized
          by a focus on ordinary, everyday life and the depiction of ordinary
          people and their experiences in a realistic and honest manner.
          American realist writers and artists sought to capture the
          complexities and contradictions of life in a rapidly changing society,
          and to expose the injustices and inequalities that existed within it.
          <br /><br /><span class="type">Style:</span> this piece could be
          considered an example of American realism in its depiction of a common
          human experience - the loss of a loved one. The painting's focus on
          Leonce's sorrowful state and the use of muted colors and loose,
          expressive brushstrokes convey a sense of raw emotion and honesty, and
          suggest that the artist is attempting to capture the complexities and
          contradictions of grief in a realistic and authentic way. <br /><br />
          <span class="type">Interpretation:</span> the painting fits within the
          tradition of American realism in its depiction of ordinary, everyday
          life and its focus on the emotional experiences of ordinary people. It
          exposes the pain and suffering that can be a part of the human
          experience, and suggests that even in the midst of such difficult
          circumstances, individuals can find ways to cope and move forward.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionThree",
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

span.type {
  font-weight: bold;
}
</style>