<script>
	import Image from '$lib/icons/Image.svelte';
	import Burgir from '$lib/icons/burgir.svelte';
</script>

<div class=" flex place-content-center w-screen bg-[#ff8482]">
	<div class=" lg:w-[calc(100%-270px)] w-[calc(100%-30px)]">
		<div class=" h-[80px] grid content-center w-full">
			<!-- Mobile -->
			<div class=" flex lg:hidden w-full">
				<div class=" grow font-Alfo h-full text-white text-[40px] leading-[48px]">Logo</div>
				<div class=" grow place-content-end content-center h-full grid"><Burgir /></div>
			</div>
			<!-- Desktop -->
			<div class=" hidden lg:flex w-full">
				<div class=" grow font-Alfo h-full text-white text-[40px] leading-[48px]">Logo</div>
				<div class=" grid content-center grid-flow-col h-full text-center">
					<div class=" font-DM text-white m-4">Portfolio</div>
					<div class=" font-DM text-white m-4">Contact</div>
				</div>
				<div class=" grow place-content-end content-center h-full grid"><Burgir /></div>
			</div>
		</div>
		<!-- Mobile -->
		<div class=" block lg:hidden w-full">
			<div class=" text-white font-[20px] font-DM font-bold">Delectus instructior</div>
			<div class=" font-Alfo text-[56px] text-white">Vide legim- us consec- tetuer</div>
			<input
				type="text"
				placeholder="Email"
				class=" p-4 h-[48px] w-full border-[1px] border-[#DADADA] rounded-[4px] mb-6"
			/>
			<button class=" w-1/2 h-[48px] bg-white border-[2px] border-black rounded-[4px]"
				>Submit</button
			>
			<Image />
		</div>
		<!-- Desktop -->
	</div>
</div>
