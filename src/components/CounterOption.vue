<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
    name: 'CounterOption',
    components: {},
    data(){
        let counter = 0;
        return {counter}
    },
    methods: {
        addCounter(){
            this.counter++
        },
        decrementCounter(){
            this.counter--
        },
        resetCounter(){
            this.counter = 0;
        }
    }
})

</script>

<template>
    <div class="flex justify-center flex-col mt-10">
        <h3 class="text-center">{{ counter }}</h3>
        <div class="flex justify-center row gap-2">
            <button class="p-2 rounded-lg bg-red-500 border-r-2 " @click="decrementCounter">Decrementar</button>
            <button class="p-2 rounded-lg bg-gray-500 border-r-2 " @click="resetCounter">Restaurar</button>
            <button class="p-2 rounded-lg bg-green-500 border-r-2 " @click="addCounter">Incrementar</button>
        </div>
    </div>
</template>

<style scoped>
</style>