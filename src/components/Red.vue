<template>
    <div>
        <slot name="title--red"></slot>
        <slot name="content--red"></slot>
    </div>
</template>

<script>

</script>

<style scoped>
    div {
        border: 1px solid red;
        background-color: lightcoral;
        padding: 30px;
        margin: 20px auto;
        text-align: center
    }
</style>
