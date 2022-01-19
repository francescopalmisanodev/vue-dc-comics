<template>
  <main>
    <section class="content bg-black">
      <Cards/>
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
import Cards from "./Cards";
export default {
  name: "Main",
  components:{
    Cards,
  }
};
</script>

<style lang="scss">
main {
  width: 100%;
  .content {
    color: white;
    width: 100%;
    .container {
      display: flex;
      height: 100%;
      padding: 20px;
      ul {
        width: 100%;
        list-style: none;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        li {
          display: flex;
          align-items: center;
          img {
            width: 20%;
            margin-right: 15px;
          }
        }
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
