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
            <div id="skills">
                <h2>Most recently I've used</h2>
                <b-row>
                    <b-col>
                        <b-card>
                        <div>
                            <h4>Backend</h4>
                            <img src="@/assets/cs.png"/>
                            <h6>C#</h6>
                        </div>
                        </b-card> 
                    </b-col>
                    <b-col>
                        <b-card>
                            <div>
                                <h4>Database</h4>
                                <img src="@/assets/sql.png"/>
                                <h6>SQL Server</h6>
                            </div>
                        </b-card>
                    </b-col>
                </b-row>
                <b-row>
                    <b-col>
                        <div>
                            <b-card>
                                <h4>Frontend</h4>
                                <b-row>
                                    <b-col>
                                    <img src="@/assets/logo.png"/>
                                    <h6>Vue</h6>
                                    </b-col>
                                    <b-col>
                                        <img src="@/assets/jquery.png"/>
                                        <h6>jQuery</h6>
                                    </b-col>
                                    <b-col>
                                        <img src="@/assets/typescript.png"/>
                                        <h6>TypeScript</h6>
                                    </b-col>
                                </b-row>
                            </b-card>
                        </div>
                    </b-col>
                </b-row>
                <b-row>
                    <b-col>
                        <div>
                            <b-card>
                                <h4>Azure Cloud</h4>
                                <b-row>
                                    <b-col>
                                        <img src="@/assets/storage.png"/>
                                        <h6>Storage</h6>
                                    </b-col>
                                    <b-col>
                                        <img src="@/assets/functions.png"/>
                                        <h6>Functions</h6>
                                    </b-col>
                                    <b-col>
                                        <img src="@/assets/appinsights.png"/>
                                        <h6>Application Insights</h6>
                                    </b-col>
                                    <b-col>
                                        <img src="@/assets/sb.png"/>
                                        <h6>Service Bus</h6>
                                    </b-col>
                                    <b-col>
                                        <img src="@/assets/iot.png"/>
                                        <h6>IoT Hub</h6>
                                    </b-col>
                                </b-row>
                            </b-card>
                        </div>
                    </b-col>
                </b-row>
            </div>
        </b-col>
    </b-row>
    <b-row>
        <b-col>
            <h2>
                Where I've worked
            </h2>
            <b-row>
                <b-col>
                    <img src="@/assets/inmar.png" />
                    <h6><strong>Graduate Software Engineer</strong></h6>
                    <h6>June 2018 to Present</h6>
                    <p></p>
                    <h6><strong>Software Engineering Intern</strong></h6>
                    <h6>May 2018 to May 2018</h6>
                </b-col>
            </b-row>
        </b-col>
        <b-col>
            <h2>
                Where I graduated from
            </h2>
            <b-row>
                <b-col>
                    <img src="@/assets/nc-state.png" />
                    <h6><strong>North Carolina State University</strong></h6>
                    <h6>Masters in Computer Science</h6>
                </b-col>
            </b-row>
            <b-row>
                <b-col>
                    <img src="@/assets/pune.png" />
                    <h6><strong>University of Pune</strong></h6>
                    <h6>Bachelors in Computer Engineering</h6>
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
    ul {
        list-style-type: none;
    }
    img {
        max-height: 60px;
        margin: 0 auto;
    }
    #skills b-col {
        background-color: black;
    }
</style>