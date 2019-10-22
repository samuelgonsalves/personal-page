<template>
<div id="about">
<b-container fluid > 
    <b-row class="mt-3">
        <b-col>
            <div><h1>Samuel Gonsalves</h1></div>
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
        font-size: 3em;
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
    #skills b-col {
        background-color: black;
    }
    #about {
        background-image: url("../assets/background-3.jpg");
        background-size: cover;
        height: 100vh;
        overflow: hidden;   
    }
</style>