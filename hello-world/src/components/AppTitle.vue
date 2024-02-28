<script>
export default {
    name:"AppTitle",
}
</script>
<template>
    <h1>La mia prima app con Vite!</h1>
</template>
<style>

h1
{
    font-size: 48px;
    text-align: center;
    animation: pulse 3s infinite linear;
}

@keyframes pulse{
0% {
    color: yellow;
    
}
100%{color: red;}}
</style>