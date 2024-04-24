<template>
    <div>
        <h1>Primeira aula de Vue... {{ nome }}</h1>
        <input type="text" v-model="nome" />
        <Button text="Teste"/>
    </div>
</template>

<script setup lang="ts">
    import { ref } from "vue";
    import Button from "./components/Button.vue";

    const nome = ref<String>("");
</script>

<style scoped></style>
