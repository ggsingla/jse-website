<script>
  import Hero from "../components/Home/Hero.svelte"

</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<style>
	.base-image {
      margin-top: 40px;
      background-image: linear-gradient(rgb(255, 255, 255), rgba(4, 4, 4));
      mask-image: linear-gradient(0deg, white, white, white, transparent);
      -webkit-mask-image: linear-gradient(0deg,
          white,
          white,
          white,
          transparent);
      background-color: #cccccc;
      height: 400px;
      background-position: 0% 28%;
      background-repeat: no-repeat;
      background-size: cover;
    }
</style>

<img src="src/lib/images/Temple_above_footer.png" class="base-image w-full" alt="">
<div id="footer" class="">
<div class="bg-[#1E1E1E] w-full flex flex-row">
	<div class="flex basis-3/5 flex-col text-white p-10">
		<div class="text-2xl text-wrap">
			Sign Up for our newsletter
		</div>
		<div>
			Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui Lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat.
		</div>
	</div>
	<div class="flex basis-2/5 flex-row text-white p-10 items-center justify-around">
		<input class="rounded-xl h-3/5 w-7/12 p-3 text-black" type="text" placeholder="Enter your email">
		<button class="bg-[#D62222] p-3 w-4/12 rounded-xl">Notify Me</button>
	</div>
	<div></div>
</div>
<div class="bg-[#1E1E1E] flex flex-row">
	<div class="basis-1/2 p-8">
	<img src="src/lib/images/JSE_logo.png" class="w-1/3" alt="">
	</div>
	<div class="basis-1/2 p-8">
	<div class="uppercase font-bold text-[#828787] pb-4 text-[13px]">Contact Us</div>
	<div class="flex flex-row gap-24">
		<div>
			<div class="font-bold text-white text-[16px]">Delhi</div>
			<div class="text-[#828787] pt-4 pb-4 text-[16px]">White Rock, British Columbia, Canada (By Appointment Only)</div>
			<div class="font-bold text-white text-[13px]">+91 87654789030</div>
		</div>
		<div>
			<div class="font-bold text-white text-[16px]">Jalandhar</div>
			<div class="text-[#828787] pt-4 pb-4">4th Floor, Shakti Tower, Grand trunk road, above vishal mega mart, near BMC chowk, Jalandhar, Punjab 144001</div>
			<div class="font-bold text-white text-[13px]">+91 87654789030</div>
		</div>
	</div>
	</div>
</div>
<div class="bg-[#1E1E1E] flex flex-row text-[#828787] p-4">
	<div class="flex flex-row w-2/5 justify-around text-[11px]">
		<p>Privacy Policy</p>
		<p>Terms and Conditions</p>
		<p>Tax Exemption</p>
		<p>Jobs</p>
	</div>
	<div class="flex flex-row w-3/5 justify-end pr-8 text-[13px]">
		<p>Copyright 2022-2023 - All Rights Reserved</p>
	</div>
</div>
</div>
