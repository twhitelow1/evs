
<template>
  <div class="sitterapply">
    <!-- Page width 'Boxed' of 'Full' -->
      <section id="contact" class="color-section">
         <div class="container">
            <div class="col-lg-8 col-lg-offset-2">
               <!-- Section heading -->
               <div class="section-heading">
                  <h2>Sitter Application</h2>
               </div>
            </div>
            <!-- Contact -->
            <div class="col-lg-12 text-center">
              <h4>Candidate Requirements</h4>  
              <!-- Requirements info -->			   
              <div class="requirements-info">
                <p>If you meet or surpass the listed requirements, we would love to work with you. All candidates must have:</p>
                <ul class="applicant-requirements">
                  <li>CPR and First Aid Training</li>
                  <li>2 years childcare or applicable experience</li>
                  <li>U.S. Work Authorization</li>
                  <li>2 Childcare or applicable references</li>
                  <li>No criminal background</li>
                </ul>
                <p>We welcome additional qualifications such as experience teaching, child development training, multilingual fluency, food-allergy awareness, and sensitivity to physical, mental, and social abilities.</p>
              </div>
            </div>
            <!-- Applicant Form -->
             <div class="col-lg-7 col-lg-offset-1">
               <h4>Application Form</h4>
				<!-- Form Starts -->
                <div id="contact_form">
                  <v-form ref="form" v-model="valid" lazy-validation>
                    <div class="form-group">
                      <h5>Contact Information</h5>
                      <input type="text" name="fname" class="form-control input-field" placeholder="First Name" required=""> 
                      <input type="text" name="mname" class="form-control input-field" placeholder="Middle Name" required="">                              
                      <input type="text" name="lname" class="form-control input-field" placeholder="Last Name" required="">
                      <input type="email" name="email" class="form-control input-field" placeholder="Email" required="">           
                    </div>
                    <div class="form-group">
                      <h5>Questions</h5>
                      <h6>Describe your babysitting and childcare related experience</h6>
                      <textarea name="q1" id="q1" class="textarea-field form-control" rows="4" placeholder="" required=""></textarea>    
                    </div>
                    <textarea name="message" id="message" class="textarea-field form-control" rows="4" placeholder="Enter your message" required=""></textarea>
                    <button type="submit" id="submit_btn" value="Submit" class="btn center-block">Send message</button>
                  </v-form>
               </div> 
              <!-- Contact results -->
               <div id="contact_results"></div>
            </div> 
            <!--/Contact form -->
         </div>
         <!-- /container-->
      </section>
      <!--Section ends -->
      
  </div>
</template>

<style>
</style>

<script>
export default {
  data: function () {
    return {};
  },
  created: function () {},
  methods: {},
  components: {},
};
</script>

