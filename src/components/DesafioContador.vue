<template>
    <div class="DesafioContador">
        <h1>Contador = {{contador}}</h1>
        <button @click="subtrair">-</button>
        <button @click="somar">+</button>
    </div>
</template>

<script>
export default {
    name:'DesafioContador',
    data(){
        return{
            contador:0
        }
    },
    methods:{
        subtrair(){
            this.contador = this.contador-1
        },
        somar(){
            this.contador = this.contador+1
        }
    }
}
</script>

<style scoped>

</style>