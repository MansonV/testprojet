<template>
    <div class= "tagsearch">
        <h1> Ajoute un tag pour trouver un jeu</h1>
        <label> Tag <input type="text" v-model="jeu.tag" /></label>
        <button> + </button>
         <p> Nombre de jeux comportant ce tag : {{ counter }}</p>
    </div>
</template>

<script>

export default {
    data () {
        return {
            jeu: []
        }
    },
    computed: {
        counter () {
            return this.jeu.length
        }
    }
}
    methods: {}
</script>

<style>
</style>