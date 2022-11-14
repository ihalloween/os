<div class="navbar bg-neutral text-neutral-content" id="navbar__element">
  <div class="navbar-start">
    <div class="dropdown">
      <!-- svelte-ignore a11y-label-has-associated-control -->
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <label tabindex="0" class="btn btn-ghost lg:hidden">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          ><path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h8m-8 6h16"
          /></svg
        >
      </label>
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <ul
        tabindex="0"
        class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52"
      >
        <!-- svelte-ignore a11y-missing-attribute -->
        <li>
          <!-- svelte-ignore a11y-click-events-have-key-events -->
          <a
            on:click={() =>
              document.getElementById('hero__bg--img').scrollIntoView({
                behavior: 'smooth',
                block: 'center',
                inline: 'center'
              })}>About</a
          >
        </li>
        <!-- svelte-ignore a11y-missing-attribute -->
        <!-- svelte-ignore a11y-click-events-have-key-events -->
        <li>
          <!-- svelte-ignore a11y-click-events-have-key-events -->
          <a
            on:click={() =>
              document.getElementById('features__element').scrollIntoView({
                behavior: 'smooth',
                block: 'center',
                inline: 'center'
              })}>Features</a
          >
        </li>
        <!-- svelte-ignore a11y-missing-attribute -->
        <!-- svelte-ignore a11y-click-events-have-key-events -->
        <li>
          <!-- svelte-ignore a11y-click-events-have-key-events -->
          <a
            on:click={() =>
              document.getElementById('downloads__element').scrollIntoView({
                behavior: 'smooth',
                block: 'center',
                inline: 'center'
              })}>Download</a
          >
        </li>
        <!-- svelte-ignore a11y-missing-attribute -->
        <li><a href="https://discord.gg/n4K3B7pDVF">Discord</a></li>
      </ul>
    </div>
    <!-- svelte-ignore a11y-missing-attribute -->
    <a class="btn btn-ghost normal-case text-xl">iHalloween</a>
  </div>
  <!-- Desktop Navbar -->
  <div class="navbar-center hidden lg:flex">
    <ul class="menu menu-horizontal p-0">
      <!-- svelte-ignore a11y-missing-attribute -->
      <li>
        <!-- svelte-ignore a11y-click-events-have-key-events -->
        <a
          on:click={() =>
            document.getElementById('hero__bg--img').scrollIntoView({
              behavior: 'smooth',
              block: 'center',
              inline: 'center'
            })}>About</a
        >
      </li>
      <!-- svelte-ignore a11y-missing-attribute -->
      <li>
        <!-- svelte-ignore a11y-click-events-have-key-events -->
        <a
          on:click={() =>
            document.getElementById('downloads__element').scrollIntoView({
              behavior: 'smooth',
              block: 'center',
              inline: 'center'
            })}>Download</a
        >
      </li>
      <li><a href="https://discord.gg/n4K3B7pDVF">Discord</a></li>
    </ul>
  </div>
  <div class="navbar-end">
    <!-- svelte-ignore a11y-missing-attribute -->
    <a href="https://github.com/ihalloween" class="btn btn-active">Github</a>
  </div>
</div>
