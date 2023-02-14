<script lang='ts' setup>
import { useTheme } from "vuetify";
const theme = useTheme();
theme.global.name.value = "dark";

</script>
<template>
    <NuxtLayout>
        <NuxtPage />
    </NuxtLayout>
</template>
<script lang='ts'>

export default {
    name: 'App',
}
</script>
<style lang='less' scoped>

</style>