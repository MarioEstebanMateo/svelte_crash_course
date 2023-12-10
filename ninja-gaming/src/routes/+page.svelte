<script>
  let title = "Ninja Gaming Guides";

  const updateTitle = () => {
    title = "something else";
  };
</script>

<div class="index">
  <h2>{title}</h2>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus dolore
    doloremque quas voluptatibus voluptatem ea omnis suscipit quaerat eius non
    tempore deleniti cum, aut fuga adipisci, pariatur soluta iste et, esse porro
    nemo fugit quia. Magni labore atque accusantium dicta fugiat minus veritatis
    itaque ipsum possimus, rem non aperiam provident similique quas fuga tenetur
    at, quos temporibus aliquid. Molestias, aperiam?
  </p>
  <button on:click={updateTitle}>Change Title</button>
  <input type="text" name="" id="" bind:value={title} />
</div>

<style>
  .index {
    text-align: center;
    display: block;
    margin: 20px auto;
  }
</style>
