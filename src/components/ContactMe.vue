<template>
<div id="contact">
    <b-container>
        <b-row>
            <b-col class="mt-5">
                <h2 class="main-header">Hit me up!</h2>
            </b-col>
        </b-row>
        <b-row>
            <b-col>
                <h6>If you have an exciting project or opportunity, I'd love to learn more.</h6>
                <h6>Feel free to reach out to me.</h6>
                
            </b-col>
        </b-row>
        <b-row class="mt-5">
            <b-col>
                <div>
                    <a href="https://www.linkedin.com/in/samuelgonsalves" class="contact-link" title="LinkedIn">
                        <font-awesome-icon :icon="['fab', 'linkedin']"  size="6x" />
                    </a>
                </div>
            </b-col>
            <b-col>
                <div>
                    <a href="https://www.github.com/samuelgonsalves" class="contact-link" title="GitHub">
                        <font-awesome-icon :icon="['fab', 'github']"  size="6x" />
                    </a>
                </div>
            </b-col>
            <b-col>
                <div>
                    <a href="https://medium.com/@samueldavidgonsalves" class="contact-link" title="Medium">
                        <font-awesome-icon :icon="['fab', 'medium']"  size="6x" />
                    </a>
                </div>
            </b-col>
            <b-col>
                <div>
                    <a href="mailto:sgonsal@ncsu.edu" class="contact-link" title="Email">
                        <font-awesome-icon :icon="['fas', 'envelope']"  size="6x" />
                    </a>
                </div>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>

<style scoped>
    #contact {
        height: 80vh;
        background-color: #233342;
        color: #6ad4b1;
    }   
    font-awesome-icon {
        width: 4em;
    }
    .contact-link {
        text-decoration: none;
        color: #6ad4b1;
    }
    a:hover {
        color:#80fad1;
    }
</style>