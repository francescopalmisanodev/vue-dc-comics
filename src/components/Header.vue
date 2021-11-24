<template>
  <header>
    <div class="container">
      <img src="@/dc-comics-assets/img/dc-logo.png" alt="DC LOGO" />
      <ul>
        <li>Character</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>Tv</li>
        <li>Games</li>
        <li>Collectables</li>
        <li>Videos</li>
        <li>Fans</li>
        <li>News</li>
        <li>Shop</li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss">
header {
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 15vh;
    img {
      width: 7%;
      height: auto;
    }
    ul {
      list-style: none;
      display: flex;
      align-items: center;
      height: 100%;
      li {
        display: flex;
        margin: 0 10px;
        border-bottom: 5px solid #0c7cec;
        height: 100%;
        align-items: center;
      }
    }
  }
}
</style>
