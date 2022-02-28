<template>
  <terminal-template :poste="poste"></terminal-template>
</template>
<script>
import TerminalTemplate from "@/components/TerminalTemplate.vue";

export default {
    components: {TerminalTemplate},
    data(){
        return{
            poste: "P_SZKLENIE"
        }
    }
}
</script>
