<script lang="ts">
  import packageJSON from "@auth/sveltekit/package.json";
  import ExternalIcon from "./external-icon.svelte";
</script>

<footer class="flex w-[100%] justify-between items-center">
  <div class="gap-4 flex flex-wrap items-center">
    <a href="https://sveltekit.authjs.dev">Documentation <ExternalIcon /></a>
    <a href="https://www.npmjs.com/package/next-auth"> NPM <ExternalIcon /> </a>
    <a
      href="https://github.com/nextauthjs/next-auth/tree/main/apps/examples/sveltekit"
    >
      Source on GitHub <ExternalIcon />
    </a>
    <a class="no-underline" href="/policy">Policy</a>
  </div>
  <div class="gap-4 flex flex-wrap items-center">
    <img
      class="h-[24px] w-[24-px]"
      src="https://authjs.dev/img/logo-sm.png"
      alt="Auth.js Logo"
    />
    <a
      class="text-black underline-offset-4 font-medium flex items-end gap-1"
      href="https://www.npmjs.com/package/@auth/sveltekit"
    >
      @auth/sveltekit@{packageJSON.version}
      <ExternalIcon />
    </a>
  </div>
</footer>

<style>
  footer {
    padding-inline: 1.25rem;
    margin-block: 2rem;
  }
</style>
