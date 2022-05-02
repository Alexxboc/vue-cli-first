<template>
    <div class="jumbotron">
        <p>“Choose a life. Choose a job. Choose a career. Choose a family. Choose a fucking big television. 
            Choose washing machines, cars, compact disc players and electrical tin openers... Choose DSY and wondering who the fuck you are on a Sunday morning. 
            Choose sitting on that couch watching mind-numbing, spirit crushing game shows, stucking junk food into your mouth. Choose rotting away in the end of it all, pishing your last in a miserable home, nothing more than an embarrassment to the selfish, 
            fucked up brats you spawned to replace yourself, choose your future. Choose life... But why would I want to do a thing like that?”</p>
    </div>
</template>

<script>
export default {
    name: 'heroImage'
}
</script>

<style scoped>
    .jumbotron {
    max-width: 1440px;
    margin: auto;
    height: 1000px;
    background-image: url(https://vdnews.tv/media/trainspotting.jpg);
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0.7;
    box-shadow: -10px 0px 4px 5px #ffa500d4;
    border-radius: 2rem;
}

    p {
        width: 50%;
        font-size: 35px;
        color: white;
        font-family: Arial, Helvetica, sans-serif;
        text-align: start;
        z-index: 1;
    }
    
</style>