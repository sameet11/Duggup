<script>
  export let path;
  export let text;
  export let classname;
</script>

<div class={"flex items-center justify-center " + classname}>
  <img src={path} alt="icon" class="h-[16px] w-[16px]" />
  <p>{text}</p>
</div>
