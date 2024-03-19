<template>
    <nav class="navbar">
        <NavLink href="/">
            <template v-if="mode === 'arrow'">
                <span class="nav-link-arrow"> &#x2190;</span>
            </template>
            <template v-if="mode === 'text'">
                <span class="nav-link-btn">Enregistrer et Quitter</span>
            </template>
        </NavLink>
    </nav>
</template>

<script setup>
import {ref} from 'vue';
import NavLink from './NavLink.vue';

const props = defineProps({
    mode: String
})
</script>


<style>
.navbar {
    display: flex;
    padding: 0 0 1rem 0;
}

.nav-link-btn {
    font-size: 12px;
    display: inline-block;
    padding: 0.1rem 0.3rem;
    margin-left: 1rem;
    margin-top: 1rem;
    color: #7e7d7d;
    border: 1px solid #7e7d7d;
    border-radius: 25px;
}

.nav-link-arrow {
    display: block;
    font-size: 25px;
    color: #7e7d7d;
    margin-left: 1rem;
    margin-top: 1rem;
}

</style>
