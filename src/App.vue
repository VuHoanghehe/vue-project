<template>
    <myInput />
    <myButton background="darkslateblue" color="white" :disabled="!valid" />
</template>

<script>
import myButton from "./components/myButton.vue";
import myInput from "./components/myInput.vue"

export default {
    components: {
        myButton,
        myInput,
    },
    data() {
        return {
            valid: true,
        };
    },
};
</script>

<style scoped></style>
