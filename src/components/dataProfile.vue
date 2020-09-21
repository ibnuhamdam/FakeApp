<template>
    <div>
        <!-- <input type="checkbox" onclick="" class="form-check-input" id="exampleCheck1">
        <label class="form-check-label item" v-bind:class="{'item-complete':tugasSaya.isDone}" for="exampleCheck1">{{tugasSaya.namaTugas}}</label> -->
        <h3>{{myName}}</h3>
    </div>
</template>

<script>
export default {
    name: "dataProfile",
    props: ["myName"]
}
</script>

<style scoped>

</style>