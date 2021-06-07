<template>
    <money v-if="field.type == 'real'" v-model="field.value"></money>
    <span v-else>{{ field.value }}</span>
</template>

<script>
export default {
    props: ['resourceName', 'field'],
}
</script>
