<script>
	import { twMerge } from 'tailwind-merge'
</script>

<div class="pb-8">
	<div class={twMerge('max-w-7xl mx-auto px-4 sm:px-6 md:px-8', $$restProps.class)}>
		<slot />
	</div>
</div>
