<template>
    <div class="v-header">
        <div class="v-header__container">
            <v-upper-header />

            <div class="v-middle-header">
                <div class="header-logo-container">
                    <a href="#" class="header-logo">
                        <img src="../../assets/img/icons/icons.svg#logo" class="logo-icon" alt="logo"/>
                    </a>
                </div>
            </div>
            
        </div>
    </div>
</template>

<script>
    import vUpperHeader from './header/v-upper-header'

    export default {
        name: 'v-header',
        components: {
            vUpperHeader
        }
    }
</script>

<style lang="scss" scoped>
    .v-header {}
</style>