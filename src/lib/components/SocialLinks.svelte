<script>
  import FaLinkedin from 'svelte-icons/fa/FaLinkedin.svelte';
  import FaGithub from 'svelte-icons/fa/FaGithub.svelte';
  import FaEnvelope from 'svelte-icons/fa/FaEnvelope.svelte';
  import FaMedium from 'svelte-icons/fa/FaMedium.svelte';
</script>

<div class="icons">
  <!-- LinkedIn Icon -->
  <a
    href="https://www.linkedin.com/in/dpoljak/"
    target="_blank"
    class="text-gray-700 dark:text-gray-200 hover:text-blue-500"
    aria-label="LinkedIn">
    <FaLinkedin />
  </a>

  <!-- GitHub Icon -->
  <a
    href="https://github.com"
    target="_blank"
    class="text-gray-700 dark:text-gray-200 hover:text-gray-900 dark:hover:text-gray-400"
    aria-label="GitHub">
    <FaGithub />
  </a>
</div>

<style>
 .icons {
        display: flex !important;
        justify-content: center !important;
		align-items: center;
		gap: 10px;
		cursor: pointer;
		font-size: 20px;
		display: flex;
		justify-content: space-between;
		max-width: 75px;
  }
</style>
