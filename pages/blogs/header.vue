<template>
    <div>
        <app-header></app-header>
        <nuxt />
    </div>
</template>
<script>
import AppHeader from '@/components/AppHeader'
export default{
    components:{
        AppHeader
    }
}
</script>