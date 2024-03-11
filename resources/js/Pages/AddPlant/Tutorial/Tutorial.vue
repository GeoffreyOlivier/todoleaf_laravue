<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
import './Tutorial.css';
</script>

<template>

    <div class="app-container">
        <h1>Ajouter une plante, c'est facile !</h1>
        <div class="chapter">
            <h2>1. Où est votre plante ?</h2>
            <p>
                Se trouve-elle dans votre maison ou de votre jardin ?
                Renseigner son emplacement vous permet de naviguer plus facilement
                entre vos différentes plantes.
            </p>
        </div>
        <div class="chapter">
            <h2>2. Qui est-elle ? </h2>
            <p>Attribuez-lui un nom ou un surnom et associez-lui une photo.</p>
        </div>
        <div class="chapter">
            <h2>3. Comment l’entretenez-vous ?</h2>
            <p>Choisissez parmi les options celles qui vous conviennent.
                Par exemple, programmez un arrosage tous les trois jours,
                ou prévoyez un rempotage tous les deux ans.</p>
        </div>
    </div>
</template>

