<script lang="ts">
	import '../app.css';
	
	let { children } = $props();
</script>

<div class="bg-gray-600 min-h-screen">
		<div class="banner text-white py-2 px-4">
		<div>VA Lookup</div>
		<div class="tab">
			<button>Voice Actors</button>
			<button>Anime</button>
		</div>
	</div>

	<hr class="border-gray-400 w-50/51 mx-auto p-2">

	<div class="inline-grid grid-cols-4 gap-2 pl-4">
		<div class='bg-gray-700 rounded-lg shadow-xl w-[300px] h-[300px]'></div>
		<div class='bg-gray-700 rounded-lg shadow-xl w-[300px] h-[300px]'></div>
		<div class='bg-gray-700 rounded-lg shadow-xl w-[300px] h-[300px]'></div>
		<div class='bg-gray-700 rounded-lg shadow-xl w-[300px] h-[300px]'></div>
		<div class='bg-gray-700 rounded-lg shadow-xl w-[300px] h-[300px]'></div>
		<div class='bg-gray-700 rounded-lg shadow-xl w-[300px] h-[300px]'></div>
		<div class='bg-gray-700 rounded-lg shadow-xl w-[300px] h-[300px]'></div>
		<div class='bg-gray-700 rounded-lg shadow-xl w-[300px]  h-[300px]'></div>
		<div class='bg-gray-700 rounded-lg shadow-xl w-[300px] h-[300px]'></div>
		<div class='bg-gray-700 rounded-lg shadow-xl w-[300px] h-[300px]'></div>
	</div>

	{@render children()}
</div>

