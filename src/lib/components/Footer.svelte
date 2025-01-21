<script lang="ts">
import SocialLinks from '$lib/components/SocialLinks.svelte';
let currentYear = new Date().getFullYear();
</script>




 <footer>
    <!-- Page Separator -->
    <hr class="border-t border-gray-300 my-6" />
    <div class="flex flex-col md:flex-row items-center justify-between space-y-4 md:space-y-0 p-4 rounded-lg">
        <!-- Footer Content -->
        <div class="text-sm">
            ©{currentYear} Dylan Poljak. All Rights Reserved.
        </div>

        <!-- Social Media Icons -->
        <div class="flex">
        <SocialLinks/>
        </div>
 </footer>