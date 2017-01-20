<template>
    <div>
        <hr/>
        <h1>{{ msg }}</h1>
        Este es otro componente!!!!
    </div>
</template>

<script>
    export default {
        name: 'test',
        data () {
            return {
                msg: 'Testing property like Hello World but *special*!!'
            }
        }
    }
</script>