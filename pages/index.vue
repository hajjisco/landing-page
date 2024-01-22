<template> 
<div>{{ count }}</div>
    <button @click="increment" class="p-3" >increase</button>
    <br>
    <button @click="decrement" class="p-3 bg-black text-white">decrease</button>
    </template>
    <script>
        export default {
            data() {
                return {
                    count: 0
                }
            },
            methods: {
                increment(){
                    this.count++
                },
                decrement(){
                    this.count--
                }
            },
            
        }
    </script>