<template>
    <div class="page-library-open">
        开发中。。。
    </div>
</template>

<script>
    import BasePage from '@/common/mixins/base-page';
    import libraryManager from '@/extends/mixins/library-manager';

    export default {
        name: 'page-library-open',
        mixins: [BasePage, libraryManager],
        data() {
            return {};
        }
    };
</script>