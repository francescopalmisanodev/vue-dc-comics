<template>
  <main>
    <section class="content bg-black">
      <div class="container">--> Content goes here</div>
    </section>
    <section class="content bg-blue">
      <div class="container">
        <ul>
          <li>
            <img
              src="@/dc-comics-assets/img/buy-comics-digital-comics.png"
              alt="buy digital comics"
            />DIGITAL COMICS
          </li>
          <li>
            <img
              src="@/dc-comics-assets/img/buy-comics-digital-comics.png"
              alt="buy digital comics"
            />DIGITAL COMICS
          </li>
          <li>
            <img
              src="@/dc-comics-assets/img/buy-comics-digital-comics.png"
              alt="buy digital comics"
            />DIGITAL COMICS
          </li>
          <li>
            <img
              src="@/dc-comics-assets/img/buy-comics-digital-comics.png"
              alt="buy digital comics"
            />DIGITAL COMICS
          </li>
          <li>
            <img
              src="@/dc-comics-assets/img/buy-comics-digital-comics.png"
              alt="buy digital comics"
            />DIGITAL COMICS
          </li>
        </ul>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style lang="scss">
main {
  width: 100%;
  .content {
    color: white;
    width: 100%;
    height: 15vh;
    .container {
      display: flex;
      align-items: center;
      height: 100%;
      ul {
        width: 100%;
        list-style: none;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        li {
          display: flex;
          align-items: center;
        }
      }
      img {
        width: 20%;
        margin-right: 15px;
      }
    }
  }
  .content.bg-black {
    font-size: 2rem;
  }
  .content.bg-blue {
    font-size: 1rem;
  }
  .bg-black {
    background: #000;
  }
  .bg-blue {
    background: #0c7cec;
  }
}
</style>
