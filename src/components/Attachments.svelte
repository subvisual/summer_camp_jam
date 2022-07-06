<script>
  import Text from './Text.svelte';
  import Attachment from './Attachment.svelte';

  const files = [
    'resume_back_end.pdf',
    'resume_front_end.pdf',
    'another_example.pdf',
  ];
</script>

<div class="Attachments">
  <Text>Attachments</Text>
  <ul class="Attachments-list">
    {#each files as name}
      <Attachment name="{name}" />
    {/each}
  </ul>
</div>

<style>
  .Attachments {
    display: grid;
    grid-template-columns: 1fr 2fr;
  }
</style>
