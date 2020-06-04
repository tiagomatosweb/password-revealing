<template>
    <div
        id="app"
        class="container mx-auto mt-10"
    >
        <div
            class="mx-auto mt-20"
            style="width: 300px;"
        >
            <h3 class="text-lg text-center font-bold mb-4">
                Password Revealing
            </h3>

            <label class="text-sm font-medium mb-2">Password</label>
            <PasswordRevealing
                v-model="password"
                placeholder="Digite a sua senha"
            />
        </div>
    </div>
</template>

<script>
    import PasswordRevealing from '@/components/PasswordRevealing';

    export default {
        name: 'App',

        components: {
            PasswordRevealing,
        },

        data() {
            return {
                password: '',
            };
        },

        methods: {},
    };
</script>
