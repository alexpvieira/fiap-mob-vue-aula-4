<template>
    <h1 :style="headingStyles">{{title}}</h1>
</template>

<script>
export default {
    props: ["title", "color"],

    data() {
        return {
            headingStyles: {
                color: this.color
            }
        }
    }
}
</script>