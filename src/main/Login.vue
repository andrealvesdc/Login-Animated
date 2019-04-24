<template>
    <div class="login">
        <Tela />
        <Ondas />
        <Cabecalho />
    </div>

    
</template>

<script>
import Cabecalho from "../components/Cabecalho"
import Tela from "../components/Tela"
import Ondas from "../components/Ondas"

export default {
    components: {Cabecalho,Tela, Ondas}

}
</script>


<style>

.login {
    align-content: center;
    height: 320px;
    width: 235px;
    border-radius: 5px;
    overflow: hidden;

    display: grid;
    grid-template-columns: repeat(4, 25%);
    grid-template-rows: 1fr 48px 48px 48px 48px 48px;
}

</style>
