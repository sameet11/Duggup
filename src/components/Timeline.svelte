<script>
  import TimelineLeft1 from "./TimelineLeft1.svelte";
  import TimeLineMiddle from "./TimeLineMiddle.svelte";
  import TimelineRight1 from "./TimelineRight1.svelte";
  import TimeLineLeft2 from "./TimeLineLeft2.svelte";
  import TimeLineRight2 from "./TimeLineRight2.svelte";
</script>

<div class="flex h-auto w-auto max-h-[288px] max-w-[987px] mt-3 ml-[109px]">
  <TimelineLeft1 text="Dec 2023" />
  <TimeLineMiddle path="images/1-middle.png" />
  <TimelineRight1 path1="images/stevejobs.png" path2="images/samaltman.png" />
</div>
<div class="flex h-auto w-auto max-h-[288px] max-w-[987px] ml-[109px]">
  <TimeLineLeft2
    path="images/duggup-icon.jpg"
    company="Duggup"
    date="Nov 2023"
  />
  <TimeLineMiddle path="images/2-middle.png" />
  <TimeLineRight2 post="Co-Founder and CEO" type="Full-Time (Remote)" />
</div>
<div class="flex h-auto w-auto max-h-[288px] max-w-[987px] ml-[109px]">
  <TimelineLeft1 text="Dec 2023" />
  <TimeLineMiddle path="images/1-middle.png" />
  <TimelineRight1 path1="images/startup-1.png" path2="images/startup-2.png" />
</div>
<div class="flex h-auto w-auto max-h-[288px] max-w-[987px] ml-[109px]">
  <TimeLineLeft2
    path="images/betterup-icon.png"
    company="BetterUp"
    date="Sept 2022"
  />
  <TimeLineMiddle path="images/2-middle.png" />
  <TimeLineRight2 post="VP Engineering" type="Full-Time" />
</div>
