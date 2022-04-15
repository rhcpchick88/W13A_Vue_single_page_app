<template>
<!-- //Added the 3 sub components into body div-->
    <div>
        <BodyPic/>
        <BodyWiki/>
        <BodyVid/>
    </div>
</template>

<script>
//imported the component files
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
//exported the component so it is usable
//added in the 3 sub components
</script>

<style scoped>

</style>
