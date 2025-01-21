<script>
  import FaLinkedin from 'svelte-icons/fa/FaLinkedin.svelte';
  import FaGithub from 'svelte-icons/fa/FaGithub.svelte';
  import FaEnvelope from 'svelte-icons/fa/FaEnvelope.svelte';

  const socialLinks = [
    {
      href: 'https://www.linkedin.com/in/dpoljak/',
      ariaLabel: 'LinkedIn',
      icon: FaLinkedin,
      hoverClass: 'hover:text-blue-500',
    },
    {
      href: 'https://github.com/Lumunix',
      ariaLabel: 'GitHub',
      icon: FaGithub,
      hoverClass: 'hover:text-gray-900 dark:hover:text-gray-400',
    },
    {
      href: 'mailto:dylanpoljak@icloud.com',
      ariaLabel: 'Email',
      icon: FaEnvelope,
      hoverClass: 'hover:text-green-500',
    },
  ];
</script>

<div class="icons">
  {#each socialLinks as { href, ariaLabel, icon: Icon, hoverClass }}
    <a
      href={href}
      target="_blank"
      class="text-gray-700 dark:text-gray-200 {hoverClass}"
      aria-label={ariaLabel}
    >
      <Icon />
    </a>
  {/each}
</div>

<style>
.icons {
  display: flex !important;
  justify-content: center !important;
  align-items: center;
  gap: 10px;
  cursor: pointer;
  font-size: 20px;
  max-width: 100px;
}
</style>

