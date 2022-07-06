<script>
</script>

<hr />

<div class="Grid-Container">
  <div class="Attachments">Attachments</div>
  <div class="Documents">
    <span>file1.pdf</span>
  </div>
  <div class="Downloads">Download</div>
</div>

<hr />

<style>
  .Grid-Container {
    display: grid;
    grid-template-columns: auto auto auto;
    width: 50%;
    /* margin-left: 35px; */
  }

  .Attachments {
    text-align: center;
  }

  .Documents {
    text-align: center;
  }

  .Downloads {
    text-align: center;
    color: blue;
  }

  .Downloads:hover {
    text-decoration: underline;
  }
</style>
