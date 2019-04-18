<template>
    <div>
        <h2>{{msg}}</h2>
        <hr/>
        <h3>{{count}}</h3>
    </div>
</template>

<script>
import store from '@/vuex/store/store';
export default {
    data(){
        return {msg: 'Hello Vuex', count: store.state.count}
    }
}
</script>

<style>

</style>
