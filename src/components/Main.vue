<template>
<div id="main">
    <b-container fluid > 
        <b-row class="mt-3">
            <b-col class="float-left">
                <div>
                    <h1>Samuel David Gonsalves</h1>
                </div>
            </b-col>
        </b-row>
        <b-row class="mt-5">
            <b-col>
                <div>
                    <h6>Hi there! I'm Samuel, a passionate full stack software developer.</h6>
                    <h6>I work at Inmar Intelligence as a software engineer where I primarily develop web applications and cloud services.</h6>
                </div>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    h1 {
        font-size: 4em;
        font-weight: 700;
        color: #6ad4b1;
    }
    h6 {
        font-size: 1.2em;
    }
    div {
        color: #6ad4b1;
    }
    i {
        font-size: 0.75em;
    }
    img {
        max-height: 60px;
        margin: 0 auto;
    }
    #main {
        background-image: url("../assets/background.jpg");
        background-size: cover;
        height: 100vh;
        overflow: hidden;   
    }
</style>