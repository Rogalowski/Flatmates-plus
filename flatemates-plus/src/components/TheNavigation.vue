<script>
import favicon from "../../public/favicon.ico"
</script>

<template>
<header>

<div class="home">
    <div id="nav" class="wrapper">
        <router-link  to="/">  <img src="../../public/favicon.ico"  /> </router-link>

        <router-link to="/">Home</router-link>
        <router-link to="/expenses">Expenses</router-link>
        <router-link to="/calendar">Calendar</router-link>
        <router-link to="/about">About Flatemates+</router-link>
    </div>
</div>

</header>
    <div class="container" >
        <router-view/>
    </div>
</template>


<style scoped>

</style>
