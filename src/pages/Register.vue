
<template>

  <div id="register">
    <div style="width: 80%; margin: 0 auto">
      <h2>Registration</h2>
      <br />
      <hr />
      <br />

<div class="container-row" style="display:flex;justify-content: center;">

    <div class="container-cell">
        <label for="userName">Username</label><br><br>
        <label for="firstName">First Name</label><br><br>
        <label for="lastName">Last Name</label><br><br>
        <label for="country">Country</label><br><br>
        <label for="password">Password</label><br><br>
        <label for="passwordConfirmation">Password</label><br><br>
        <label for="email">E-Mail</label><br><br>
        <label for="profilePictureURL">Picture URL</label><br><br>
    </div>

    <div class="container-cell">
             <input type="text" id="userName" style="width:200px;" v-model="userName"/><br><br>
            <input type="text" id="firstName" style="width:200px;" v-model="firstName" /><br><br>
            <input type="text" id="lastName" style="width:200px;" v-model="lastName" /><br><br>

<select style="width:200px;" v-model="country">
              <option value selected disabled hidden>Choose a Country</option>
              <option value="Afghanistan">Afghanistan</option>
              <option value="Albania">Albania</option>
              <option value="Algeria">Algeria</option>
              <option value="Andorra">Andorra</option>
              <option value="Angola">Angola</option>
              <option value="Antigua and Barbuda">Antigua and Barbuda</option>
              <option value="Argentina">Argentina</option>
              <option value="Armenia">Armenia</option>
              <option value="Australia">Australia</option>
              <option value="Austria">Austria</option>
              <option value="Azerbaijan">Azerbaijan</option>
              <option value="Bahamas">Bahamas</option>
              <option value="Bahrain">Bahrain</option>
              <option value="Bangladesh">Bangladesh</option>
              <option value="Barbados">Barbados</option>
              <option value="Belarus">Belarus</option>
              <option value="Belgium">Belgium</option>
              <option value="Belize">Belize</option>
              <option value="Benin">Benin</option>
              <option value="Bhutan">Bhutan</option>
              <option value="Bolivia">Bolivia</option>
              <option value="Bosnia and Herzegovina">Bosnia and Herzegovina</option>
              <option value="Botswana">Botswana</option>
              <option value="Brazil">Brazil</option>
              <option value="Brunei">Brunei</option>
              <option value="Bulgaria">Bulgaria</option>
              <option value="Burkina Faso">Burkina Faso</option>
              <option value="Burundi">Burundi</option>
              <option value="Cֳ´te d'Ivoire">Cֳ´te d'Ivoire</option>
              <option value="Cabo Verde">Cabo Verde</option>
              <option value="Cambodia">Cambodia</option>
              <option value="Cameroon">Cameroon</option>
              <option value="Canada">Canada</option>
              <option value="Central African Republic">Central African Republic</option>
              <option value="Chad">Chad</option>
              <option value="Chile">Chile</option>
              <option value="China">China</option>
              <option value="Colombia">Colombia</option>
              <option value="Comoros">Comoros</option>
              <option value="Congo (Congo-Brazzaville)">Congo (Congo-Brazzaville)</option>
              <option value="Costa Rica">Costa Rica</option>
              <option value="Croatia">Croatia</option>
              <option value="Cuba">Cuba</option>
              <option value="Cyprus">Cyprus</option>
              <option value="Czechia (Czech Republic)">Czechia (Czech Republic)</option>
              <option value="Democratic Republic of the Congo">Democratic Republic of the Congo</option>
              <option value="Denmark">Denmark</option>
              <option value="Djibouti">Djibouti</option>
              <option value="Dominica">Dominica</option>
              <option value="Dominican Republic">Dominican Republic</option>
              <option value="Ecuador">Ecuador</option>
              <option value="Egypt">Egypt</option>
              <option value="El Salvador">El Salvador</option>
              <option value="Equatorial Guinea">Equatorial Guinea</option>
              <option value="Eritrea">Eritrea</option>
              <option value="Estonia">Estonia</option>
              <option value="Eswatini">Eswatini</option>
              <option value="Ethiopia">Ethiopia</option>
              <option value="Fiji">Fiji</option>
              <option value="Finland">Finland</option>
              <option value="France">France</option>
              <option value="Gabon">Gabon</option>
              <option value="Gambia">Gambia</option>
              <option value="Georgia">Georgia</option>
              <option value="Germany">Germany</option>
              <option value="Ghana">Ghana</option>
              <option value="Greece">Greece</option>
              <option value="Grenada">Grenada</option>
              <option value="Guatemala">Guatemala</option>
              <option value="Guinea">Guinea</option>
              <option value="Guinea-Bissau">Guinea-Bissau</option>
              <option value="Guyana">Guyana</option>
              <option value="Haiti">Haiti</option>
              <option value="Holy See">Holy See</option>
              <option value="Honduras">Honduras</option>
              <option value="Hungary">Hungary</option>
              <option value="Iceland">Iceland</option>
              <option value="India">India</option>
              <option value="Indonesia">Indonesia</option>
              <option value="Iran">Iran</option>
              <option value="Iraq">Iraq</option>
              <option value="Ireland">Ireland</option>
              <option value="Israel">Israel</option>
              <option value="Italy">Italy</option>
              <option value="Jamaica">Jamaica</option>
              <option value="Japan">Japan</option>
              <option value="Jordan">Jordan</option>
              <option value="Kazakhstan">Kazakhstan</option>
              <option value="Kenya">Kenya</option>
              <option value="Kiribati">Kiribati</option>
              <option value="Kuwait">Kuwait</option>
              <option value="Kyrgyzstan">Kyrgyzstan</option>
              <option value="Laos">Laos</option>
              <option value="Latvia">Latvia</option>
              <option value="Lebanon">Lebanon</option>
              <option value="Lesotho">Lesotho</option>
              <option value="Liberia">Liberia</option>
              <option value="Libya">Libya</option>
              <option value="Liechtenstein">Liechtenstein</option>
              <option value="Lithuania">Lithuania</option>
              <option value="Luxembourg">Luxembourg</option>
              <option value="Madagascar">Madagascar</option>
              <option value="Malawi">Malawi</option>
              <option value="Malaysia">Malaysia</option>
              <option value="Maldives">Maldives</option>
              <option value="Mali">Mali</option>
              <option value="Malta">Malta</option>
              <option value="Marshall Islands">Marshall Islands</option>
              <option value="Mauritania">Mauritania</option>
              <option value="Mauritius">Mauritius</option>
              <option value="Mexico">Mexico</option>
              <option value="Micronesia">Micronesia</option>
              <option value="Moldova">Moldova</option>
              <option value="Monaco">Monaco</option>
              <option value="Mongolia">Mongolia</option>
              <option value="Montenegro">Montenegro</option>
              <option value="Morocco">Morocco</option>
              <option value="Mozambique">Mozambique</option>
              <option value="Myanmar">Myanmar</option>
              <option value="Namibia">Namibia</option>
              <option value="Nauru">Nauru</option>
              <option value="Nepal">Nepal</option>
              <option value="Netherlands">Netherlands</option>
              <option value="New Zealand">New Zealand</option>
              <option value="Nicaragua">Nicaragua</option>
              <option value="Niger">Niger</option>
              <option value="Nigeria">Nigeria</option>
              <option value="North Korea">North Korea</option>
              <option value="North Macedonia">North Macedonia</option>
              <option value="Norway">Norway</option>
              <option value="Oman">Oman</option>
              <option value="Pakistan">Pakistan</option>
              <option value="Palau">Palau</option>
              <option value="Palestine State">Palestine State</option>
              <option value="Panama">Panama</option>
              <option value="Papua New Guinea">Papua New Guinea</option>
              <option value="Paraguay">Paraguay</option>
              <option value="Peru">Peru</option>
              <option value="Philippines">Philippines</option>
              <option value="Poland">Poland</option>
              <option value="Portugal">Portugal</option>
              <option value="Qatar">Qatar</option>
              <option value="Romania">Romania</option>
              <option value="Russia">Russia</option>
              <option value="Rwanda">Rwanda</option>
              <option value="Saint Kitts and Nevis">Saint Kitts and Nevis</option>
              <option value="Saint Lucia">Saint Lucia</option>
              <option value="Saint Vincent and the Grenadines">Saint Vincent and the Grenadines</option>
              <option value="Samoa">Samoa</option>
              <option value="San Marino">San Marino</option>
              <option value="Sao Tome and Principe">Sao Tome and Principe</option>
              <option value="Saudi Arabia">Saudi Arabia</option>
              <option value="Senegal">Senegal</option>
              <option value="Serbia">Serbia</option>
              <option value="Seychelles">Seychelles</option>
              <option value="Sierra Leone">Sierra Leone</option>
              <option value="Singapore">Singapore</option>
              <option value="Slovakia">Slovakia</option>
              <option value="Slovenia">Slovenia</option>
              <option value="Solomon Islands">Solomon Islands</option>
              <option value="Somalia">Somalia</option>
              <option value="South Africa">South Africa</option>
              <option value="South Korea">South Korea</option>
              <option value="South Sudan">South Sudan</option>
              <option value="Spain">Spain</option>
              <option value="Sri Lanka">Sri Lanka</option>
              <option value="Sudan">Sudan</option>
              <option value="Suriname">Suriname</option>
              <option value="Sweden">Sweden</option>
              <option value="Switzerland">Switzerland</option>
              <option value="Syria">Syria</option>
              <option value="Tajikistan">Tajikistan</option>
              <option value="Tanzania">Tanzania</option>
              <option value="Thailand">Thailand</option>
              <option value="Timor-Leste">Timor-Leste</option>
              <option value="Togo">Togo</option>
              <option value="Tonga">Tonga</option>
              <option value="Trinidad and Tobago">Trinidad and Tobago</option>
              <option value="Tunisia">Tunisia</option>
              <option value="Turkey">Turkey</option>
              <option value="Turkmenistan">Turkmenistan</option>
              <option value="Tuvalu">Tuvalu</option>
              <option value="Uganda">Uganda</option>
              <option value="Ukraine">Ukraine</option>
              <option value="United Arab Emirates">United Arab Emirates</option>
              <option value="United Kingdom">United Kingdom</option>
              <option value="United States of America">United States of America</option>
              <option value="Uruguay">Uruguay</option>
              <option value="Uzbekistan">Uzbekistan</option>
              <option value="Vanuatu">Vanuatu</option>
              <option value="Venezuela">Venezuela</option>
              <option value="Vietnam">Vietnam</option>
              <option value="Yemen">Yemen</option>
              <option value="Zambia">Zambia</option>
              <option value="Zimbabwe">Zimbabwe</option>
            </select>
<br><br>
            <input type="password" id="password" style="width:200px;" v-model="password" /><br><br>
            <input type="password" id="passwordConfirmation" style="width:200px;" v-model="passwordConfirmation"/><br><br>
            <input type="text" id="email" style="width:200px;" placeholder="name@example.com" v-model="email" /><br><br>
            <input type="text" id="profilePictureURL" style="width:200px;" v-model="profilePictureURL"/><br><br>

    </div>

      <div class="container-cell">
        <label id="userNameError" style="color: red;font-weight: normal;"></label><br><br>
        <label id="firstNameError" style="color: red;font-weight: normal;"></label><br><br>
        <label id="lastNameError" style="color: red;font-weight: normal;"></label><br><br>
        <label id="countryError" style="color: red;font-weight: normal;"></label><br><br>
        <label id="passwordError" style="color: red;font-weight: normal;"></label><br><br>
        <label id="passwordConfirmationError" style="color: red;font-weight: normal;"></label><br><br>
        <label id="emailError"  style="color: red;font-weight: normal;"></label><br><br>
        <label id="profilePictureError" style="color: red;font-weight: normal;"></label><br><br>

      </div>
</div>

<div style="display:flex;justify-content: center;">
    <div style="padding:20px;">
      <button type="submit" v-on:click="handleRegistration"><b>Register</b></button>
    </div>
    <div style="padding:20px;">
      <button type="reset" v-on:click="resetErrors"><b>Reset</b></button>
    </div>
</div>

    </div>
  </div>
</template>


<script>
import axios from 'axios';

export default {
  name: "Register",

  data() {
    return {
      userName: "",
      firstName: "",
      lastName: "",
      country: "",
      password: "",
      passwordConfirmation: "",
      email: "",
      profilePictureURL: ""
    }


  },

  methods: {
    resetErrors: function() {
      $("#firstNameError").text("");
      $("#lastNameError").text("");
      $("#userNameError").text("");
      $("#passwordError").text("");
      $("#passwordConfirmationError").text("");
      $("#countryError").text("");
      $("#emailError").text("");
      $("#profilePictureError").text("");
    },

    handleRegistration: function() {
      event.preventDefault();
      this.resetErrors();
      let flag = false;

      if (!this.userName)
      {
          $("#userNameError").text("Error: Username is required");
          flag = true;
      }

      if (!this.firstName)
      {
          $("#firstNameError").text("Error: First name is required");
          flag = true;
      }

      if (!this.lastName)
      {
          $("#lastNameError").text("Error: Last name is required");
          flag = true;
      }

      if (!this.country) {
        $("#countryError").text("Error: Country is required");
          flag = true;
      }

      if (!this.password)
      {
          $("#passwordError").text("Error: Password is required");
          flag = true;
      }

      if (!this.passwordConfirmation)
      {
          $("#passwordConfirmationError").text("Error: Password confirmation is required");
          flag = true;
      }

      if (!this.email)
      {
          $("#emailError").text("Error: Email is required");
          flag = true;
      }

      if (!this.profilePictureURL)
      {
          $("#profilePictureError").text("Error: Profile picture is required");
          flag = true;
      }


      if (flag)
        return;

      if (
        this.userName.length < 3 ||
        this.userName.length > 8 ||
        !/^[a-zA-Z]+$/.test(this.userName)
      ) {
        $("#userNameError").text(
          "Error: Length between 3 and 8 and Letters only"
        );
        return;
      }

      if (this.password != this.passwordConfirmation) {
        $("#passwordError").text("Error: Passwords are not the same");
        $("#passwordConfirmationError").text(
          "Error: Passwords are not the same"
        );
        return;
      }

      if (this.password.length < 5 || this.password.length > 10) {
        $("#passwordError").text("Error: Length between 5 and 10");
        $("#passwordConfirmationError").text("Error: Length between 5 and 10");
        return;
      }

      if (!/\d/.test(this.password)) {
        $("#passwordError").text("Error: At least 1 digit");
        $("#passwordConfirmationError").text("Error: At least 1 digit");
        return;
      }

      if (/^[a-zA-Z0-9]+$/.test(this.password)) {
        $("#passwordError").text("Error: At least 1 symbol");
        $("#passwordConfirmationError").text("Error: At least 1 symbol");
        return;
      }

      const res = axios.post('http://localhost:3000/user/isUsernameExists', {username: this.userName}).then(response => {

            if (response.data)
            {
               $("#userNameError").text("Error: Username already exists");
            }
            else
            {
                    const res = axios.post('http://localhost:3000/register', 
                    {
                      username: this.userName,
                      firstName: this.firstName,
                      lastName: this.lastName,
                      country: this.country,
                      password: this.password,
                      passwordConfirmation: this.passwordConfirmation,
                      email: this.email,
                      profilePictureURL: this.profilePictureURL,
                      }
                    ).then(res => {

                      this.$root.$router.push("/login");

                    });
            }

        }).
        catch(error => {
          alert(error);
  })
      

      
    }
  }
};
</script>

<style>
@import "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css";
</style>