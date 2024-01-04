<template>
    <div>
        <div>Person Info</div>
        <div>Name: {{ person.name }}</div>
        <div>Age: {{ person.age }}</div>
    </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue';
import { type Person } from '@/types';



const p: Person = {
    id: '#001',
    name: 'Bill',
    age: 20
}

const person = ref(p)
</script>