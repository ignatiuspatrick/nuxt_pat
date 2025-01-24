<template>
    <div>
        <nav-bar></nav-bar>
        <NuxtLayout>
            <NuxtPage></NuxtPage>
        </NuxtLayout>
    </div>
</template>

<script>
import {defineComponent} from "vue";
import NavBar from "~/components/navbar/NavBar.vue";

export default defineComponent({
    components: {NavBar}
})
</script>