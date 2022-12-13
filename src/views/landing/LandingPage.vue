<template>
    <div class="dashboard-button">
        <router-link :to="'/dashboard'">
            <v-btn style="background-color: #69C0F7">
                Dashboard
            </v-btn>
        </router-link>
    </div>
</template>

<script>
    import { RouterLink } from 'vue-router';
    
    export default {
    name:'landing',
    components: { RouterLink },

    data(){
        return{
            
        }
    }
}
</script>

<style>
.dashboard-button {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>
