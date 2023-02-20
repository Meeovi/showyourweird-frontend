<template>
    <v-footer border>
        <v-row justify="center" no-gutters>
            <v-btn variant="text" class="mx-2" rounded="xl" href="/">
                Home
            </v-btn>
            <v-btn variant="text" class="mx-2" rounded="xl" href="/about/">
                About Us
            </v-btn>
            <v-btn variant="text" class="mx-2" rounded="xl" href="/legal/terms">
                Terms and Conditions
            </v-btn>
            <v-btn variant="text" class="mx-2" rounded="xl" href="/legal/privacy">
                Privacy Policies
            </v-btn>
            <v-btn variant="text" class="mx-2" rounded="xl" href="/shop/">
                Shop
            </v-btn>
            <v-btn variant="text" class="mx-2" rounded="xl" href="/legal/returns">
                Return Policies
            </v-btn>
            <v-col class="text-center mt-4" cols="12">
                {{ new Date().getFullYear() }} — <strong><a href="https://www.here2mingle.com">The Here2Mingle Company</a></strong>
            </v-col>
        </v-row>
    </v-footer>
</template>

<script>
    export default {}
</script>