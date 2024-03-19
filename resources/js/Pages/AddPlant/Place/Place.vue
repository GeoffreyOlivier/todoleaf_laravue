<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import {Head} from '@inertiajs/vue3';
import './Place.css';
import NavLink from "@/Components/NavLink.vue";
import NavBar from "@/Components/NavBar.vue";
</script>
<template>
    <div class="app-container">
        <NavBar mode="text"/>
        <div class="main-content">
            <h1>Emplacement</h1>
            <p>Où se situe la plante que vous souhaitez enregistrer? Le salon, la terrasse, le jardin? Ajouter un
                emplacement si nécessaire.</p>

            <div class="button-group">
                <button class="location-button selected">Salon</button>
                <button class="location-button">Terrasse</button>
                <button class="location-button">Potager</button>
                <button class="location-button">Semis</button>
            </div>

            <button class="add-location">+ Ajouter un nouvel emplacement</button>
        </div>

        <div class="footer">
            <button class="nav-button prev">Retour</button>
            <button class="nav-button next">Suivant</button>
            <div class="divider"></div>
        </div>
    </div>
</template>
