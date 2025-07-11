<script>
  import i1 from "$lib/assets/sa1.jpeg";
  import p1 from "$lib/assets/phil1.jpeg";
</script>

<main>
  <div class="container">
    <h1>Phil LeVota</h1>
    <h2>Sexually abused by Phil?</h2>
    <div class="images">
      <img src={p1} alt="" />
      <img src={i1} alt="" />
    </div>
    <p>
      You're not alone, many women have been victimized by him, here we are
      empowering them to share their stories.
    </p>
    <h3>Supporting Survivors, Cultivating Community, Pursuing Justice.</h3>
  </div>
</main>

<style>
  .images {
    display: flex;
    padding: 1rem 0;
    img {
      width: 50%;
      &:nth-child(1) {
        border-top-left-radius: 1rem;
        border-bottom-left-radius: 1rem;
      }
      &:nth-child(2) {
        border-top-right-radius: 1rem;
        border-bottom-right-radius: 1rem;
      }
    }
  }
</style>
