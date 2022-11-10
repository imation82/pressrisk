<template>
    <section>
        <b-container>
            <header class="team-header">
                <h1>Our Team</h1>
                <p>CTFN was born out of the desire to meet the need for quality reporting on major corporate events. We
                    are committed to excellent journalism and strive to meet our readers' unique demand for timely
                    information by employing intrepid and experienced reporters and analysts who share our core values
                    of
                    integrity and a desire to seek the truth.</p>
            </header>

            <b-row>
                <b-col lg="4" v-for="(n, i) in 9" :key="n" class="mt-5">
                    <div class="team-member">
                        <div class="team-member-content">
                            <h3>Firstname Lastname</h3>
                            <h2>Title</h2>
                            <p>[Bio goes here.]</p>
                        </div>
                    </div>
                </b-col>
            </b-row>
        </b-container>
    </section>
</template>
<style>
@import "../assets/styles/team.css";
</style>