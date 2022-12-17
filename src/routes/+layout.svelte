<script>
  import ContactButtons from '../lib/ContactButtons.svelte';

  import "@skeletonlabs/skeleton/themes/theme-skeleton.css";
  import "@skeletonlabs/skeleton/styles/all.css";
  import "../app.postcss";
  import { AppShell, AppBar, LightSwitch } from "@skeletonlabs/skeleton";
</script>

<!-- App Shell -->
<AppShell slotSidebarLeft="bg-surface-500/5 w-56 p-4">
  <svelte:fragment slot="header">
    <!-- App Bar -->
    <AppBar>
      <svelte:fragment slot="lead">
        <a href="/"><strong class="text-xl">megareclama</strong></a>
      </svelte:fragment>
      <svelte:fragment slot="trail">
        <ContactButtons></ContactButtons>
        <a
          class="hidden sm:flex btn btn-sm btn-ghost-surface"
          href="tel:+79882931800"
          target="_blank"
          rel="noreferrer">+7 (988) 293-18-00</a
        >
        <LightSwitch class="hidden sm:flex" />
      </svelte:fragment>
    </AppBar>
  </svelte:fragment>
  <!-- Page Route Content -->
  <slot />
</AppShell>
