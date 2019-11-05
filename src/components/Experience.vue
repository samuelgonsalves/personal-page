<template>
<div id="experience">
    <b-container>
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
                        <h6>Accomplishments:</h6>
                        <ul>
                            <li>Performed support sweeper duties, fixing application issues to ensure platform stability.</li>                        
                            <li>Mentored an intern, providing career guidance, and presentation strategies.</li>                                            
                        </ul>
                        <img src="@/assets/inmar.png" />                    
                        <h6><strong>Software Engineering Intern</strong></h6>
                        <h6>May 2018 to May 2018</h6>
                        <h6>Accomplishments:</h6>
                        <ul>
                            <li>Developed an end-to-end IoT solution allowing scanning stations to notify managers about their status.</li>
                            <li>Implemented a highly scalable Azure Function utility to migrate over 100M blob files across storage containers and storage accounts.</li>                    
                        </ul>
                    </b-col>
                </b-row>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>

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
</style>