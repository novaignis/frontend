<template>
    <div class="wsmobileheader clearfix">
        <span class="smllogo"><img src="/assets/images/logo-white.png" alt="mobile-logo" /></span>
    </div>
</template>

<script>
export default {
    methods: {
        toggleMobileMenu() {
            // toggle body class "dark-mode"
            document.body.classList.toggle("wsactive");
        }
    }
};
</script>
