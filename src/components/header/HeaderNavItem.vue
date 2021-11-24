<template>
<div class="d-flex">
    <li>
        <a class="nav-link color-lightW" href="#" v-html="navInfo"></a>
    </li>
</div>
    
</template>
<script>
export default {
    name:"HeaderNavItem",
    props:['navInfo']
    
}
</script>