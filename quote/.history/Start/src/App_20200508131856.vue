<template>
    <div class="container">
        
    <app-quote-grid :quotes="quotes"></app-quote-grid>
    </div>
</template>

<script>
import QuoteGrid from './components/QuoteGrid.vue';
import NewQuote from './components/NewQuote.vue';

    export default {
        data: function(){
            return{
                quotes: ['Just a quote to see something'],
                maxQuotes: 10
            }
        },
        components:{
            appQuoteGrid: QuoteGrid,
            appNewQute: NewQuote
        }
    }
</script>

<style>
</style>
