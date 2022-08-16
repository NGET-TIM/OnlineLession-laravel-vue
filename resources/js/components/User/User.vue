<template>
    <li>{{ user.name }}</li>
</template>

<script>
export default {
    name: 'User',
    props: {
        user: {}
    }
}
</script>
