<script>
  import TimeDesignation from "./TimeDesignation.svelte";
  export let post;
  export let type;
</script>

<div class="flex w-[761px] mt-10 ml-3">
  <TimeDesignation {post} {type} />
</div>
