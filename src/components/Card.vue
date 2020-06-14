<template>
  <div>
    <div class="card">
      <img src="#" alt="Avatar" style="width:100%">
      <div class="container">
        <h1>It is h1 for test</h1>
        <h4>
          <b>It' is card of stest</b>
        </h4>
        <p>Content card</p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Card",
  props: {
    textBody: String
  }
};
</script>

<style scoped>
h1 {
  color: rgb(209, 199, 167);
  font-family: Impact, Haettenschweiler, "Arial Narrow Bold", sans-serif;
}
.card {
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  transition: 0.3s;
}

/* On mouse-over, add a deeper shadow */
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
}

/* Add some padding inside the card container */
.container {
  padding: 2px 16px;
}
</style>