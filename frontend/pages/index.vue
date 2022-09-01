<template>
    <v-container>
        <h1>Gráficos</h1>
        <h3>Gráfico com plotly a partir de dados de um csv</h3>
        <h3>Gráfico com plotly a partir de dados da Api do ##</h3>
        <h3>Gráfico com plotly a partir de um modelo de ML</h3>
        <h1>Vantagens do Nuxt</h1>
        <h3>Vuetify</h3>
        <br>
        <div style="display: flex">
            <Exemplo_vuetify_card></Exemplo_vuetify_card>
            <Exemplo_vuetify_card></Exemplo_vuetify_card>

        </div>
        <h3>Páginas dinâmicas</h3>

        
    </v-container>
</template>

<script>
import Exemplo_vuetify_card from '../components/exemplo_vuetify_card.vue';
import Quadro_cards from '../components/quadro_cards.vue';
export default {
    components: { Exemplo_vuetify_card, Quadro_cards }
}
</script>