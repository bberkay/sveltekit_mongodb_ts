<script lang="ts">
  import type { ActionData } from './$types';
  import ContactForm from '$lib/components/contact/ContactForm.svelte';

  // Comes from +page.server.ts
  export let form: ActionData;
</script>

<h2 class = "mb-4">Contact</h2>
<ContactForm {form} /> 


