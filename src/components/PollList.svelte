<script>
  export let polls = [];
</script>

<div class="poll-list">
  {#each polls as {question, id}}
     <div>{question}</div>
  {/each}
</div>

<style>
  .poll-list {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 20px;
  }
</style>