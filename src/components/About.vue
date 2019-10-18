<template>
<b-container>
    <b-row>
        <b-col>
            <h1>Samuel David Gonsalves</h1>
            <div>
                Hi there! I'm Samuel, a full stack software developer.
                After graduation, I joined Inmar as a software engineer where I'm working on developing web applications and scaling them by leveraging the cloud.
            </div>
        </b-col>
    </b-row>
    <b-row>
        <b-col>
            <h2>
                Where I graduated from
            </h2>
            <b-row>
                <b-col>
                    <img src="@/assets/nc-state.png" />
                    <h6><strong>North Carolina State University</strong></h6>
                    <h6>Masters in Computer Science</h6>
                    <h6>2016 to 2018</h6>
                </b-col>
            </b-row>
            <b-row>
                <b-col>
                    <img src="@/assets/pune.png" />
                    <h6><strong>University of Pune</strong></h6>
                    <h6>Bachelors in Computer Engineering</h6>
                    <h6>2012 to 2016</h6>
                </b-col>
            </b-row>
        </b-col>
    </b-row>
</b-container>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    h1 {
        font-size: 3em;
        font-weight: 700;
        color: navy;
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
</style>