<script>
  import Button from "./Button.svelte";
  import Navitems from "./Navitems.svelte";
  import Navprofile from "./Navprofile.svelte";
</script>

<div
  class="flex p-4 justify-between border-b-[3px] border-dotted h-auto max-h-[73px]"
>
  <button class="flex gap-1 mt-2">
    <img
      src="/images/duggup-icon.jpg"
      alt="icon"
      class="h-[27px] w-[27px] rounded-lg"
    />
    <h1 class="font-bold text-lg">duggup</h1>
  </button>
  <div class="flex gap-10">
    <Navitems text="Home" path="/images/Iconhome.png" classname="gap-3" />
    <Navitems
      text="Explore"
      path="/images/Storyexplore.png"
      classname="gap-1"
    />
    <Navitems text="Learn" path="/images/Iconlearn.png" classname="gap-3" />
    <Button />
    <Navprofile />
  </div>
</div>
