<template>
    <section id="trialForm" class="request-trial scroll-mt">
        <b-container>
            <header class="text-center">
                <h1 class="request-trial-title">Request Trial</h1>
                <p class="request-trial-subTitle">Complete the form below and one of our representatives will be in
                    touch with you.</p>
            </header>
            <b-row class="justify-content-center align-items-center pt-4">
                <b-col lg="10">
                    <b-form>
                        <b-form-input class="mb-3" id="input-default" placeholder="First Name"></b-form-input>
                        <b-form-input class="mb-3" id="input-default" placeholder="Last Name"></b-form-input>
                        <b-form-input class="mb-3" id="input-default" placeholder="Phone Number"></b-form-input>
                        <b-form-input class="mb-3" id="input-default" placeholder="Email Address"></b-form-input>
                        <b-form-input class="mb-3" id="input-default" placeholder="Company/Organization"></b-form-input>
                    </b-form>
                    <b-form-checkbox id="checkbox-1" name="checkbox-1" value="accepted" unchecked-value="not_accepted">
                        I agree to my personal data being sotred and used by CTFN for delivery of it's services. Please
                        see <a href="/privacy-policy" style="color:blue">privacy</a> and <a href="/terms"
                            style="color:blue">terms & conditions.</a>
                    </b-form-checkbox>
                    <div class="text-center mt-4">
                        <b-btn class="trialBtn">Request Trial</b-btn>
                    </div>
                </b-col>
            </b-row>
        </b-container>
    </section>
</template>
<style>
@import "../assets/styles/trial-form.css";
</style>