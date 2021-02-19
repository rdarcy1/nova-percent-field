<template>
    <span v-if="field.isNull">&mdash;</span>
    <span v-else>{{ field.value }}<span v-if="field.displayPercentSign">&nbsp;%</span></span>
</template>

<script>
export default {
    props: ['resourceName', 'field'],
}
</script>
