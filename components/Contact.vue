<template>
    <section id="contact" class="contact scroll-mt">
        <b-container>
            <b-row>
                <b-col lg="6">
                    <header>
                        <h1>Contact Us</h1>
                        <p class="contact-description">Get in touch with us to learn more about our reporting
                            services, request a trial, or share your feedback on our
                            stories. We are always available to assist our readers if
                            the need arises.
                        </p>
                    </header>
                    <div>
                        <b-form-input class="input-field" id="input-large" size="lg" placeholder="Your Name">
                        </b-form-input>
                        <b-form-input class="input-field" id="input-large" size="lg" placeholder="Your Email">
                        </b-form-input>
                        <b-form-textarea class="input-field" id="textarea-large" size="lg" placeholder="Your Message"
                            rows="5">
                        </b-form-textarea>

                        <b-btn class="submitBtn">Submit</b-btn>
                    </div>
                </b-col>

                <b-col lg="6">

                    <div class="text-right">
                        <h1 class="mb-4">Our Offices</h1>
                        <p class="location" v-for="(address, i) in addresses" :key="i">{{ address.location }}</p>
                    </div>

                    <div class="join-section">
                        <h1>Join Us</h1>
                        <p class="join-description">We are seeking applicants who share our
                            passion for accurate and quality journalism,
                            with a deep respect for their work and their
                            colleagues. Click below to learn more.
                        </p>
                        <b-btn class="submitBtn" href="https://www.linkedin.com/company/ctfn/about/" target="_blank">
                            Careers</b-btn>
                    </div>

                </b-col>
            </b-row>

            <div class="commitment">
                <h1>Commitment to Our Readers</h1>
                <p class="commitment-description">CTFN is committed to quality journalism. We strive to meet our
                    readers’ needs for accurate
                    and timely information by employing hardworking reporters and analysts who share our core
                    values of integrity and a desire to seek the truth.</p>
                <p class="commitment-description">We respect the trust our readers place in us to deliver our best
                    work, and in return, we
                    promise a spirit of collaboration and dedication to our craft. We carry that commitment to our
                    employees and our communities by promoting a culture of diversity, inclusion, and
                    mindfulness toward personal growth and sustainability.</p>
            </div>
        </b-container>
    </section>
</template>
<script>
export default {
    data() {
        return {
            addresses: [
                {
                    location: "152 Main St., Westport, CT"
                },
                {
                    location: "1100 15th St., Washington, DC"
                },
                {
                    location: "7 Bell Yard, London WC2A 2JR, UK"
                },

            ]
        }
    },
}
</script>
<style scoped>
@import "../assets/styles/contact.css";
</style>