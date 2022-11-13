<template>
    <section id="team" class="team scroll-mt">
        <b-container>
            <header class="team-header">
                <h1>Our Team</h1>
                <p class="team-header-description">CTFN was born out of the desire to meet the need for quality
                    reporting on major corporate events. We
                    are committed to excellent journalism and strive to meet our readers' unique demand for timely
                    information by employing intrepid and experienced reporters and analysts who share our core values
                    of
                    integrity and a desire to seek the truth.</p>
            </header>

            <b-row>
                <b-col lg="4" v-for="(n, i) in 9" :key="i" class="mt-5">
                    <div class="team-member">
                        <div class="team-member-content">
                            <h3 class="team-name">Firstname Lastname</h3>
                            <h4 class="team-title">Title</h4>
                            <div class="horizontal-line-style"></div>
                            <p class="team-bio">[Bio goes here.]</p>
                        </div>
                    </div>
                </b-col>
            </b-row>

            <header class="team-header mt-5">
                <h1>Team Members</h1>
                <p class="team-header-description">Our growing team of journalists has decades of investigative
                    reporting experience and is supported by
                    multiple seasoned and well-researched analysts.</p>
            </header>

            <b-row>
                <b-col lg="4" v-for="(n, i) in 6" :key="i" class="mt-5">
                    <div class="team-member">
                        <div class="team-member-content">
                            <h3 class="team-name">Firstname Lastname</h3>
                            <h4 class="team-title">Title</h4>
                            <div class="horizontal-line-style"></div>
                            <p class="team-bio">[Bio goes here.]</p>
                        </div>
                    </div>
                </b-col>
            </b-row>
        </b-container>
    </section>
</template>
<style scoped>
@import "../assets/styles/team.css";
</style>