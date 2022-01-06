<template>
  <div>
      <School></School>
      <Student></Student>
  </div>
</template>

<script>
    // 引用组件
    import School from './School'
    import Student from "./Student"

    export default {
        components: { School },
                name:'App',
                comments: {
                    School,
                    Student
                }

    }
</script>