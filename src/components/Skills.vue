<template>
    <b-container>
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
    </b-container>
</template>

<style scoped>
/* TODO: Figure out how to avoid this duplication */
    img {
        max-height: 60px;
        margin: 0 auto;
    }
</style>