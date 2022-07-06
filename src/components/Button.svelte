<script>
  let count = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button class="Button" on:click="{increment}">
  Clicks: {count}
</button>

<style>
  .Button {
    color: #ff3e00;
  }
</style>
