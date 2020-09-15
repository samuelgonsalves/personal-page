<template>
<div id="personalprojects">
<b-container>
    <b-row>
        <b-col>
            <h2 class="main-header">Personal Projects</h2>
            <h6>I enjoy tinkering and building things with software!</h6>
            <b-row class="mb-3 mt-5">
                <b-col>
                    <b-card class="h-100 card-project">
                        <h6><strong>Date Recommender App</strong></h6>
                        <h6>Currently building a web app to recommend date ideas by connecting to Yelp, Trello and other cool APIs.</h6>
                        <h6><u>Technologies</u>: Vue.js</h6>
                        <b-button pill variant="outline-primary" href="https://github.com/samuelgonsalves/date-recommender">Code</b-button>
                    </b-card>
                </b-col>
                <b-col>
                    <b-card class="h-100 card-project">
                        <h6><strong>Game Engine</strong></h6>
                        <h6>Built a game engine with a game object model, multithreaded architecture, event management system, scripting engine.</h6>
                        <h6><u>Technologies</u>: Java, Processing Framework, JavaScript</h6>
                        <b-button pill variant="outline-primary" href="https://github.com/samuelgonsalves/game-engine">Code</b-button>
                    </b-card>
                </b-col>
            </b-row>
            <b-row class="mb-3">                
                <b-col>
                    <b-card class="h-100 card-project">
                        <h6><strong>Bank app</strong></h6>
                        <h6>Developed an MVC application emulating the functionality of an online banking system.</h6>
                        <h6><u>Technologies</u>: Ruby on Rails, PostgreSQL, JavaScript</h6>
                        <b-button pill variant="outline-primary" href="https://github.com/samuelgonsalves/bank-app">Code</b-button>
                    </b-card>
                </b-col>
                <b-col>
                    <b-card class="h-100 card-project">
                        <h6><strong>Continuous Integration Slack Bot</strong></h6>
                        <h6>Built a Slack chatbot to assist with Continuous Integration (CI) tasks.</h6>
                        <h6><u>Technologies</u>: Node.js, APIs: Travis CI, Coveralls, Slack, GitHub</h6>
                        <b-button pill variant="outline-primary" href="https://github.com/CiBotProject/bot">Code</b-button>
                    </b-card>
                </b-col>
            </b-row>
            <b-row>
                <b-col>
                    <b-card class="card-project">
                        <h6><strong>Open Source Contributions</strong></h6>
                        <h6>Fixed UI bugs in TheOdinProject web application.</h6>
                        <h6>Contributed to the open source project FreeCodeCamp.</h6>
                        <h6>Researched and added content to Wikipedia's Jasmine testing framework article.</h6>
                        <h6>Added survey functionality to the open source project Expertiza to allow instructors to administer surveys for students.</h6>
                        <b-button pill variant="outline-primary" href="https://tools.wmflabs.org/sigma/usersearch.py?name=Samuelg123&page=Jasmine_%28JavaScript_testing_framework%29&server=enwiki&max=">Wikipedia Contributions</b-button>
                    </b-card>
                </b-col>
            </b-row>
        </b-col>
    </b-row>
</b-container>
</div>
</template>

<style scoped>
    #personalprojects {
        /* height: 100vh; */
                background-color: #233342;
        color: #6ad4b1;
    }
    .card-project {
        background-color: #1e3e5c;
    }
    /* .btn-outline-primary {
        border-color: #6ad4b1;
    } */
</style>
