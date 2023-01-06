<script setup>
import GuestLayout from '@/Layouts/GuestLayout.vue'
import Label from '@/Components/Label.vue'
import Input from '@/Components/Input.vue'

const emitTest = e => console.log(e)
</script>

<template>
    <GuestLayout>
        <Label value="件名">タイトル</Label>
        <Input
        value="初期値"
        @update:modelValue="emitTest"></Input>
    </GuestLayout>

</template>
