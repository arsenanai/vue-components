<template>
    <div class="container">
        <app-header></app-header>
        <hr>
        <div class="row">
            <app-server-titles></app-server-titles> 
            <app-server-details></app-server-details>
        </div>
        <hr>
        <app-footer></app-footer>
    </div>
</template>

<script>
    import Header from './components/Header.vue';
    import Footer from './components/Footer.vue';
    import ServerTitles from './components/ServerTitles.vue';
    import ServerDetails from './components/ServerDetails.vue';
    export default {
        components: {
            'app-header': Header,
            'app-server-titles': ServerTitles,
            'app-server-details': ServerDetails,
            'app-footer': Footer
        }
    }
</script>

<style>
</style>