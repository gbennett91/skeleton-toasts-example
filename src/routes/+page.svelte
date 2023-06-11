<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->
<script lang="ts">
	import { toastStore } from '@skeletonlabs/skeleton';

	function showToast() {
		toastStore.trigger({ message: 'Hello' });
	}
</script>

<div class="container h-full mx-auto flex justify-center items-center">
	<button class="btn variant-filled" on:click={showToast}>Click Me!</button>
</div>
