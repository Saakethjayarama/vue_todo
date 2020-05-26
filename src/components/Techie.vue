<template>
    <div class="techie">
        {{msg}}
    </div>
</template>
<script>
export default {
    name: "Saaketh",
    props: {
        msg: String
    }
}
</script>
<style scoped>
.techie{
    color: tomato;
}
</style>