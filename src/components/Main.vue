<template>
<div id="main">
    <b-container fluid > 
        <b-row class="mt-3">
            <b-col class="float-left">
                <div>
                    <h1>Samuel</h1>
                    <h1>Gonsalves</h1>
                </div>
            </b-col>
        </b-row>
        <b-row class="mt-5">
            <b-col>
                <div>
                    <h6>Hi there! I'm Samuel, a full stack software developer.</h6>
                    <h6>After graduation, I joined Inmar as a software engineer where I'm working on developing web applications and scaling them by leveraging the cloud.</h6>
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