<template>
    <header class="header">
        <router-link to="/" class="logo">
            <img src="@/assets/images/logo.png" alt="logo">
        </router-link>
        <ul class="header__menu">
            <li><router-link to="/">Курсы</router-link></li>
            <li><router-link to="/">O нас</router-link></li>
            <li><router-link to="/">Блог</router-link></li>
            <li>
                <span>Еще</span>
                <ul class="header__dropdown">
                    <li>
                        <router-link to="/">FAQ</router-link>
                    </li>
                    <li>
                        <router-link to="/">Курсы</router-link>
                    </li>
                    <li>
                        <router-link to="/">Условия оплаты</router-link>
                    </li>
                </ul>
            </li>
        </ul>
        <button class="btn">Войти</button>
    </header>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import '@/styles/components/header.scss'
</style>