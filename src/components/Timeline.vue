<template>
<div id="experience">
    <b-container>
        <b-row>
            <b-col class="mt-5">
                <h2 class="main-header">
                    My Timeline
                </h2>
                <h6>A glimpse into my background and experience.</h6>
                
                <div id="exp" class="mt-5">
                    <b-row>
                        <b-col cols="4">
                            <h3 class="center-date">2018</h3>                            
                        </b-col>
                        <b-col>
                            <b-card class="exp-class w-75 mb-5">
                            <h4><strong>Graduate Software Engineer</strong> at Inmar</h4>
                            <h6>Primarily working in C# and .NET full stack development.</h6> 
                            <h6>Responsible for coding, testing and deployment of applications and cloud-based services.</h6>            
                            </b-card>            
                        </b-col>
                    </b-row>
                    <b-row>
                    <b-col cols="4">                    
                        <h3 class="center-date">2017</h3>                        
                    </b-col>
                    <b-col>
                        <b-card class="exp-class w-75 mb-5">
                            <h4><strong>Software Engineering Intern</strong> at Inmar</h4>
                            <h6>Built an IoT solution using Azure IoT Event Hub.</h6>
                            <h6>Developed a scalable Function utility to migrate blob files across storage containers and storage accounts.</h6>                    
                        </b-card>
                    </b-col>
                    </b-row>
                    <b-row>
                        <b-col cols="4">
                            <h3 class="center-date">2016</h3>     
                        </b-col>
                        <b-col>
                            <b-card class="exp-class w-75 mb-5">
                                <h4><strong>North Carolina State University</strong></h4>
                                <h6>Graduated with a Masters in Computer Science.</h6>
                            </b-card>
                        </b-col>
                    </b-row>
                    <b-row>
                        <b-col cols="4">                        
                            <h3 class="center-date">2012</h3>
                        </b-col>
                        <b-col>
                            <b-card class="exp-class w-75 mb-5">
                                <h4><strong>University of Pune</strong></h4>
                                <h6>Graduated with a Bachelors in Computer Engineering.</h6>
                            </b-card>
                        </b-col>
                    </b-row>
                </div>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>
<script>
</script>

<style scoped>
/* 
TODO: Remove duplication, learn how to style multiple components similarly
*/
    img {
        max-height: 60px;
        margin: 0 auto;
    }
    ul {
        list-style-type: none;
    }
    #experience {
        background-color: #233342;
        color: #6ad4b1;
    }
    #exp {
        text-align: left;
    }
    .exp-class {
        background-color: #162738;
    }
    .center-date {
        text-align: center;
        margin-top: 10%;
    }
</style>