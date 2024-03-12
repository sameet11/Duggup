<script>
  export let path;
  export let company;
  export let date;
</script>

<div class="h-[157px] text-right w-[176px] p-3">
  <div class="flex justify-end">
    <img src={path} alt="icon" class="rounded-full h-[48px] w-[48px]" />
  </div>

  <div class="font-bold text-lg">{company}</div>
  <div class="text-[#7A9299]">San Fransico Bay Area</div>
  <div class="text-[#7A9299]">{date}</div>
</div>
