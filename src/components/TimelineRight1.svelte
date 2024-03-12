<script>
  import Timelinecard from "./Timelinecard.svelte";
  export let path1;
  export let path2;
</script>

<div class="p-2">
  <div class="flex gap-3">
    <Timelinecard
      path={path1}
      text="No amount of technology can convert a bad story into a good story."
    />
    <Timelinecard
      path={path2}
      text="Most people don't have original ideas. Here is how Sam Altman pushes himself to have unpopular ideas."
    />
  </div>
</div>
