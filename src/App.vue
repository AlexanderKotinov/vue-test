<template>
    <div class="container text-center">
        <div class="row">
            <div class="col-xs-12">
               <app-quote quote="Some quote props">
                   <h5>{{ textInSlot }}</h5>
               </app-quote>
            </div>
        </div>
    </div>
</template>

<script>
    import Quote from './components/Quote.vue'
    export default {
      data: function() {
        return ({textInSlot: 'Text in slot'})
      },
        components: {
            appQuote: Quote
        }
    }
</script>

<style>
</style>
