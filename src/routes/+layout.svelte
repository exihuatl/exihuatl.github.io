<script lang="ts">
	import { inject } from '@vercel/analytics';
	inject({ mode: import.meta.env.DEV ? 'development' : 'production' });
</script>
