<template>
    <app-layout>
        <template #header>
            <h2 class="h4 font-weight-bold">
                Home
            </h2>
        </template>

        <!-- <welcome /> -->
        <account/>

    </app-layout>
</template>

<script>
    import AppLayout from '@/Layouts/AppLayout'
    import Welcome from '@/Jetstream/Welcome'
    import Account from '@/Jetstream/Account'

    export default {
        components: {
            AppLayout,
            Welcome,
        },
    }
</script>
