<template>
<div id="skills">
    <b-container>
        <b-row>
            <b-col>
                <div class="mt-5">
                    <h3 class="main-header">Most recently I've used</h3>
                    <h6>I love learning new technologies and I like to think of myself as being language-agnostic.</h6>
                    <b-row class="mt-5 mb-3">
                        <b-col>
                            <div>
                            <b-card class="card-skill">
                                <h4>Backend</h4>
                                <img src="@/assets/cs.png"/>
                                <h6>C#</h6>
                            </b-card> 
                            </div>
                        </b-col>
                        <b-col>
                            <div>
                                <b-card class="card-skill">
                                    <h4>Database</h4>
                                    <img src="@/assets/sql.png"/>
                                    <h6>SQL Server</h6>
                                </b-card>
                            </div>
                        </b-col>
                    </b-row>
                    <b-row class="mb-3">
                        <b-col>
                            <div>
                                <b-card class="card-skill">
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
                    <b-row class="mb-1">
                        <b-col>
                            <div>
                                <b-card class="card-skill">
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
    </b-container>
</div>
</template>

<style scoped>
/* TODO: Figure out how to avoid this duplication */
    img {
        max-height: 60px;
        margin: 0 auto;
    }
    #skills {
        background-color: #233342;
        color: #6ad4b1;
    }
    .card-skill {
        background-color: #1e3e5c;

    }

</style>