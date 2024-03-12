<script>
  import Button from "./Button.svelte";

  let user = {
    name: "Krishna Kiran",
    path: "/images/krishna-kiran.png",
  };
</script>

<div class="mt-[50px] px-32 flex gap-14">
  <div class="h-[200px] w-[120px]">
    <img src={user.path} alt="profile" class="h-[120px] w-[120px]" />
    <div class="text-center font-bold text-xl text-slate-700">
      {user.name.split(" ")[0]}
    </div>
    <div class="text-center font-bold text-xl text-slate-700">
      {user.name.split(" ")[1]}
    </div>
  </div>
  <div class="w-[620px]">
    <p class="mb-5">
      Co-Founder and CEO at Duggup - Social network for people in tech.
      Ex-Amazon Head of Engineering. I write hot-takes on building a business,
      shipping delightful products and accelerating product and career growth.
    </p>
    <div
      class="rounded-md border border-b-4 border-b-[#4D4D4D] h-fit w-fit py-2 px-5 mt-1"
    >
      <div class="flex items-center justify-center">
        <p>Followed</p>
      </div>
    </div>
  </div>
  <div class=" text-right w-fit ml-6">
    <div class="flex justify-end">
      <img
        src="/images/duggup-icon.jpg"
        alt="icon"
        class="rounded-full h-[36px] w-[36px]"
      />
    </div>
    <h1 class="font-bold mt-3">Duggup</h1>
    <p class="text-[#7A9299]">Co-Founder and CEO</p>
    <div class="mt-6 flex gap-2 text-[#595959]">
      My website
      <i class="fa-solid fa-arrow-up-right-from-square text-xs mt-1" />
      <div class="h-3 w-10 border-b-8 border-dotted mt-1"></div>
    </div>
  </div>
</div>
