<template>
    <div>
        <BodyPic/>
        <BodyWiki/>
        <BodyVid/>
    </div>
</template>

<script>

import BodyPic from "./body_components/BodyPic.vue"
import BodyWiki from "./body_components/BodyWiki.vue"
import BodyVid from "./body_components/BodyVid.vue"

export default {
    name: "MyBody",
    components: {
        BodyPic,
        BodyWiki,
        BodyVid
    }
}

</script>

<style scoped>

</style>
