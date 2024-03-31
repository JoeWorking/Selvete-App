 <script lang="ts">
	import { setupIonicBase } from 'ionic-svelte';

  import '../app.pcss'
	/* Theme variables */
	import '../theme/variables.css';

	/* load and register all components - you can also import separately to code split */
  import 'ionic-svelte/components/all';

	/* run base configuration code from ionic/core */
	setupIonicBase();
</script>


<ion-header>
  <ion-toolbar>
    <ion-title>Header</ion-title>
  </ion-toolbar>
</ion-header>
<ion-app>
  
   <slot />
</ion-app>


