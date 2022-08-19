<template>
    <div>
        <p>Hello world</p>
        <media-library-attachment name="cover" />
        <hr>
        <media-library-collection name="images" />
    </div>
</template>

<script>
import { MediaLibraryAttachment } from "spatie-media-lib-pro/media-library-pro-vue3-attachment";
import { MediaLibraryCollection } from "spatie-media-lib-pro/media-library-pro-vue3-collection";

export default {
    name: "UploadComponent",
    components: {
        MediaLibraryAttachment,
        MediaLibraryCollection,
    }
}
</script>
