<template>
<div class="info">
<h1>hello, bcdroid</h1>
<button type="button" @click="add()"></button>
</div>
</template>
<script>
export default {
name: "Info",
methods: {
add() {
console.log("Info执行了方法，按下了按钮")
}
}
}
</script>
