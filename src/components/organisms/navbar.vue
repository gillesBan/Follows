<template>
    <nav class="w-full fixed flex align-middle py-15 px-25">
        <div class="main-navlinks">
            <button class="burger" type="button" aria-label="toggle navigation" aria-expanded="false">
                <span></span>
                <span></span>
                <span></span>
            </button>
        </div>

        <div class="decoration">
            <ul class="flex">
                <li><a href="#" alt="follows icon" ><span>Follows</span></a></li>
                <li><a href="#" alt="follows icon" ><span>Test 1</span></a></li>
                <li><a href="#" alt="follows icon" ><span>Test 1</span></a></li>
                <li><a href="#" alt="follows icon" ><span>Test 1</span></a></li>
                <li><a href="#" alt="follows icon" ><span>Testss 1</span></a></li>
            </ul>
        </div>

        <div class="nav-auth">
            <a href="#"><CommunityIcon />rrr</a>
        </div>
    </nav>
</template>

<script setup lang="ts">
import CommunityIcon from '../icons/IconCommunity.vue'
</script>
<style scoped>

</style>