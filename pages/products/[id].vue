<template>
    <div>
<p> Product details for {{ id }}</p>
<p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Vero quibusdam sint ipsum corrupti fugit delectus asperiores iste nihil cum rerum eligendi debitis nisi provident architecto incidunt, corporis consectetur, voluptas amet.</p>
    </div>
</template>

<script setup>
const {id } = useRoute().params
definePageMeta({
    layout:'products'
})
</script>

<style scoped>

</style>