<template>
    <v-app-bar app color="white" dark flat class="px-12" elevation="4">
        <v-btn >
            <v-icon color="red" left class="mr-2">fas fa-code</v-icon>Maxwell
        </v-btn>
        <v-spacer></v-spacer>
        <v-btn text @click="scroll('home')" >Home</v-btn>
        <v-btn text @click="scroll('aboutMe')"  >About Me</v-btn>
        <v-btn text @click="scroll('projects')" class="text-red" >Projects</v-btn>
        <v-btn text @click="scroll('contact')" >Contact</v-btn>
        <v-btn elevation="2" color="red" rounded href="https://pdfhost.io/v/a69yiy8fX_Microsoft_Word_Maxwell_Green_EN_2022docx" target="_blank">Resume</v-btn>
    </v-app-bar>
</template>

<script>
    export default {
        methods: {
            scroll(refName) {
                const element = document.getElementById(refName);
                element.scrollIntoView({behavior: "smooth"});
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>