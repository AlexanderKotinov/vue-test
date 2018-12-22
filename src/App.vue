<template>
    <div class="container text-center">
        <div class="row">
            <div class="col-xs-12">
               <app-quote quote="Some quote props">
                   <h5>Text in slot</h5>
               </app-quote>
            </div>
        </div>
    </div>
</template>

<script>
    import Quote from './components/Quote.vue'
    export default {
        components: {
            appQuote: Quote
        }
    }
</script>

<style>
</style>
