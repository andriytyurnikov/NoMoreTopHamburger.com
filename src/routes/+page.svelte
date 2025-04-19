<article
	class="text-neutral-50 p-4 flex flex-col flex-grow flex-1 grow min-h-full h-full items-center justify-center"
>
	<div class="w-full max-w-[32rem] mx-auto">
		<p class="text-[1.25rem] mb-2">
			The hamburger menu [☰] at the top of mobile screens is poor design.
		</p>

		<ul class="mb-4 list-disc">
			<li>It is hard to reach with your thumb</li>
			<li>It hides navigation options</li>
			<li>It adds unnecessary taps</li>
		</ul>

		<h2 class="text-[1.25rem] mb-2">[Mobile] bottom Navigation Bar is just better:</h2>
		<ul class="mb-0 list-disc">
			<li>Easy to reach with your fingers</li>
			<li>Instantly visible</li>
			<li>A common pattern in native apps</li>
		</ul>
	</div>
</article>

<style>
	@reference "../app.css";

	article {
		@apply bg-black bg-center bg-cover;

		background-image:
			linear-gradient(rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0.25)),
			url('/images/burger-with-knife-in-it.jpg');
	}
</style>
