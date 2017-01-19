<template>
    <div class="container">
        <div class="row">
            <div class="col-xs-12">
                <br>
                <button class="btn btn-primary">Load Blue Template</button>
                <button class="btn btn-success">Load Green Template</button>
                <button class="btn btn-danger">Load Red Template</button>
                <hr>
                <app-blue>
                    <h2 slot="title">Blue</h2>
                    <div slot="content">
                        <p>Blue is the favorite color of all people. It’s nature’s color for water and sky, but is rarely found in fruits and vegetables. Today, blue is embraced as the color of heaven and authority, denim jeans and corporate logos. It is cold, wet, and slow as compared to red’s warmth, fire, and intensity.</p>
                    </div>
                </app-blue>
                <app-green>
                    <h2 slot="title">Green</h2>
                    <div slot="content">
                        <p>Green is no longer just a color. It's now the symbol of ecology and a verb.</p>
                        <p>Since the beginning of time, green has signified growth, rebirth, and fertility. In pagan times, there was the "Green Man" - a symbol of fertility.  In Muslim countries, it is a holy color and in Ireland, a lucky color. It was the color of the heavens in the Ming Dynasty.</p>
                    </div>
                </app-green>
                <app-red>
                    <h2 slot="title">Red</h2>
                    <div slot="content">
                        <p>Red is the color of extremes. It’s the color of passionate love, seduction, violence, danger, anger, and adventure. Our prehistoric ancestors saw red as the color of fire and blood – energy and primal life forces – and most of red’s symbolism today arises from its powerful associations in the past.</p>
                    </div>
                </app-red>
            </div>
        </div>
    </div>
</template>

<script>
    import Blue from './components/Blue.vue';
    import Green from './components/Green.vue';
    import Red from './components/Red.vue';

    export default {
        components: {
            appBlue: Blue,
            appGreen: Green,
            appRed: Red
        }
    }
</script>

<style>
</style>
