<template>
    <div>
        <h1>{{ message }}</h1>
        <button @click="handleClick">click meeeeee</button>
        <input type="text" v-model="message" />
    </div>
</template>
<script>
export default {
    name: "MyComponent",
    data() {
        return {
            message: "Hello from MyComponent"
        }
    },
    methods: {
        handleClick() {
            alert("hello world")
        }
    }
}
</script>