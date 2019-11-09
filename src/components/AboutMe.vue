<template>
<div id="aboutme">
    <b-container>
        <b-row>
            <b-col class="mt-3">
                <h2 class="main-header">About me</h2>
            </b-col>
        </b-row>
        <b-row class="mt-5">
            <b-col>
                <div id="me">
                    <img src="@/assets/me.png" />
                </div>
            </b-col>                
            <b-col>
                <div id="aboutmedesc">
                    <h6>Hello! I'm Samuel.</h6>
                    <h6>I work for Inmar as a software engineer where I design, develop & support client-facing web applications and services.</h6>
                    <h6>My primary responsibilities include -</h6>                
                    <ul class="list-decoration">
                        <li>Writing and testing code</li>
                        <li>Coordinating deployments</li>
                        <li>Supporting applications and services</li>
                    </ul>
                </div>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>

<style scoped>
#aboutme {
    background-color: #233342;
    color: #6ad4b1;
}
img {
    width: 300px;
    /* padding: 5px; */
    border-radius: 50%;
    border: #162738 solid 5px;
}
img:hover {
    /* border-color: red; */
}
#aboutmedesc {
    text-align: left;
    margin-top: 8%;
}
.list-decoration {
    list-style-type: square
}
</style>