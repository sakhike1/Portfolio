<template>
    <div>
        <Navbar />
        <designs />
        <VueCursor />
        <Footer />
    </div>
</template>

<script>
import vueCursor from "../components/vueCursor.vue";
export default {
    components: {
        vueCursor
    }
};
</script>

<style lang="scss" scoped></style>