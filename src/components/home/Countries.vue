<template>
  <div id="data">
    <div class="container my-2">
      <div class="row">
        <div class="col-md-6 offset-md-3">
        <select   v-model="country" id="countries" class="form-group form-control">
                <option id="country_select_global"  value="global" selected >Global</option>
                <option id="country_select_Afghanistan"  value="Afghanistan">Afghanistan</option>
                <option id="country_select_Albania" value="Albania">Albania</option>
                <option id="country_select_Algeria" value="Algeria">Algeria</option>
                <option id="country_select_Andorra" value="Andorra">Andorra</option>
                <option id="country_select_Angola" value="Angola">Angola</option>
                <option id="country_select_Antigua and Barbuda" value="Antigua and Barbuda">Antigua and Barbuda</option>
                <option id="country_select_Argentina" value="Argentina">Argentina</option>
                <option id="country_select_Armenia" value="Armenia">Armenia</option>
                <option id="country_select_Australia" value="Australia">Australia</option>
                <option id="country_select_Austria" value="Austria">Austria</option>
                <option id="country_select_Azerbaijan" value="Azerbaijan">Azerbaijan</option>
                <option id="country_select_Bahamas" value="Bahamas">Bahamas</option>
                <option id="country_select_Bahrain" value="Bahrain">Bahrain</option>
                <option id="country_select_Bangladesh" value="Bangladesh">Bangladesh</option>
                <option id="country_select_Barbados" value="Barbados">Barbados</option>
                <option id="country_select_Belarus" value="Belarus">Belarus</option>
                <option id="country_select_Belgium" value="Belgium">Belgium</option>
                <option id="country_select_Belize" value="Belize">Belize</option>
                <option id="country_select_Benin" value="Benin">Benin</option>
                <option id="country_select_Bhutan" value="Bhutan">Bhutan</option>
                <option id="country_select_Bolivia" value="Bolivia">Bolivia</option>
                <option id="country_select_Bosnia and Herzegovina" value="Bosnia and Herzegovina">Bosnia and Herzegovina</option>
                <option id="country_select_Botswana" value="Botswana">Botswana</option>
                <option id="country_select_Brazil" value="Brazil">Brazil</option>
                <option id="country_select_Bulgaria" value="Bulgaria">Bulgaria</option>
                <option id="country_select_Burkina Faso" value="Burkina Faso">Burkina Faso</option>
                <option id="country_select_Burundi" value="Burundi">Burundi</option>
                <option id="country_select_Cambodia" value="Cambodia">Cambodia</option>
                <option id="country_select_Cameroon" value="Cameroon">Cameroon</option>
                <option id="country_select_Canada" value="Canada">Canada</option>
                <option id="country_select_Central African Republic" value="Central African Republic">Central African Republic</option>
                <option id="country_select_Chad" value="Chad">Chad</option>
                <option id="country_select_Chile" value="Chile">Chile</option>
                <option id="country_select_China" value="China">China</option>
                <option id="country_select_Colombia" value="Colombia">Colombia</option>
                <option id="country_select_Comoros" value="Comoros">Comoros</option>
                <option id="country_select_Costa Rica" value="Costa Rica">Costa Rica</option>
                <option id="country_select_Cote D'ivoire" value="Cote D'ivoire">Cote D'ivoire</option>
                <option id="country_select_Croatia" value="Croatia">Croatia</option>
                <option id="country_select_Cuba" value="Cuba">Cuba</option>
                <option id="country_select_Cyprus" value="Cyprus">Cyprus</option>
                <option id="country_select_Denmark" value="Denmark">Denmark</option>
                <option id="country_select_Djibouti" value="Djibouti">Djibouti</option>
                <option id="country_select_Dominica" value="Dominica">Dominica</option>
                <option id="country_select_Dominican Republic" value="Dominican Republic">Dominican Republic</option>
                <option id="country_select_Ecuador" value="Ecuador">Ecuador</option>
                <option id="country_select_Egypt" value="Egypt">Egypt</option>
                <option id="country_select_El Salvador" value="El Salvador">El Salvador</option>
                <option id="country_select_Equatorial Guinea" value="Equatorial Guinea">Equatorial Guinea</option>
                <option id="country_select_Eritrea" value="Eritrea">Eritrea</option>
                <option id="country_select_Estonia" value="Estonia">Estonia</option>
                <option id="country_select_Ethiopia" value="Ethiopia">Ethiopia</option>
                <option id="country_select_Fiji" value="Fiji">Fiji</option>
                <option id="country_select_Finland" value="Finland">Finland</option>
                <option id="country_select_France" value="France">France</option>
                <option id="country_select_Gabon" value="Gabon">Gabon</option>
                <option id="country_select_Georgia" value="Georgia">Georgia</option>
                <option id="country_select_Germany" value="Germany">Germany</option>
                <option id="country_select_Ghana" value="Ghana">Ghana</option>
                <option id="country_select_Greece" value="Greece">Greece</option>
                <option id="country_select_Grenada" value="Grenada">Grenada</option>
                <option id="country_select_Guatemala" value="Guatemala">Guatemala</option>
                <option id="country_select_Guinea" value="Guinea">Guinea</option>
                <option id="country_select_Guinea-bissau" value="Guinea-bissau">Guinea-bissau</option>
                <option id="country_select_Guyana" value="Guyana">Guyana</option>
                <option id="country_select_Haiti" value="Haiti">Haiti</option>
                <option id="country_select_Honduras" value="Honduras">Honduras</option>
                <option id="country_select_Hungary" value="Hungary">Hungary</option>
                <option id="country_select_Iceland" value="Iceland">Iceland</option>
                <option id="country_select_India" value="India">India</option>
                <option id="country_select_Indonesia" value="Indonesia">Indonesia</option>
                <option id="country_select_Iran" value="Iran">Iran</option>
                <option id="country_select_Iraq" value="Iraq">Iraq</option>
                <option id="country_select_Ireland" value="Ireland">Ireland</option>
                <option id="country_select_Israel" value="Israel">Israel</option>
                <option id="country_select_Italy" value="Italy">Italy</option>
                <option id="country_select_Jamaica" value="Jamaica">Jamaica</option>
                <option id="country_select_Japan" value="Japan">Japan</option>
                <option id="country_select_Jordan" value="Jordan">Jordan</option>
                <option id="country_select_Kazakhstan" value="Kazakhstan">Kazakhstan</option>
                <option id="country_select_Kenya" value="Kenya">Kenya</option>
                <option id="country_select_Korea, Democratic People's Republic of" value="Korea, Democratic People's Republic of">Korea, Democratic People's Republic of</option>
                <option id="country_select_Kuwait" value="Kuwait">Kuwait</option>
                <option id="country_select_Kyrgyzstan" value="Kyrgyzstan">Kyrgyzstan</option>
                <option id="country_select_Lao People's Democratic Republic" value="Lao People's Democratic Republic">Lao People's Democratic Republic</option>
                <option id="country_select_Latvia" value="Latvia">Latvia</option>
                <option id="country_select_Lebanon" value="Lebanon">Lebanon</option>
                <option id="country_select_Lesotho" value="Lesotho">Lesotho</option>
                <option id="country_select_Liberia" value="Liberia">Liberia</option>
                <option id="country_select_Liechtenstein" value="Liechtenstein">Liechtenstein</option>
                <option id="country_select_Lithuania" value="Lithuania">Lithuania</option>
                <option id="country_select_Luxembourg" value="Luxembourg">Luxembourg</option>
                <option id="country_select_Madagascar" value="Madagascar">Madagascar</option>
                <option id="country_select_Malawi" value="Malawi">Malawi</option>
                <option id="country_select_Malaysia" value="Malaysia">Malaysia</option>
                <option id="country_select_Maldives" value="Maldives">Maldives</option>
                <option id="country_select_Mali" value="Mali">Mali</option>
                <option id="country_select_Malta" value="Malta">Malta</option>
                <option id="country_select_Mauritania" value="Mauritania">Mauritania</option>
                <option id="country_select_Mauritius" value="Mauritius">Mauritius</option>
                <option id="country_select_Mexico" value="Mexico">Mexico</option>
                <option id="country_select_Monaco" value="Monaco">Monaco</option>
                <option id="country_select_Mongolia" value="Mongolia">Mongolia</option>
                <option id="country_select_Montenegro" value="Montenegro">Montenegro</option>
                <option id="country_select_Morocco" value="Morocco">Morocco</option>
                <option id="country_select_Mozambique" value="Mozambique">Mozambique</option>
                <option id="country_select_Namibia" value="Namibia">Namibia</option>
                <option id="country_select_Nepal" value="Nepal">Nepal</option>
                <option id="country_select_Netherlands" value="Netherlands">Netherlands</option>
                <option id="country_select_New Caledonia" value="New Caledonia">New Caledonia</option>
                <option id="country_select_New Zealand" value="New Zealand">New Zealand</option>
                <option id="country_select_Nicaragua" value="Nicaragua">Nicaragua</option>
                <option id="country_select_Niger" value="Niger">Niger</option>
                <option id="country_select_Nigeria" value="Nigeria">Nigeria</option>
                <option id="country_select_Norway" value="Norway">Norway</option>
                <option id="country_select_Oman" value="Oman">Oman</option>
                <option id="country_select_Pakistan" value="Pakistan">Pakistan</option>
                <option id="country_select_Panama" value="Panama">Panama</option>
                <option id="country_select_Papua New Guinea" value="Papua New Guinea">Papua New Guinea</option>
                <option id="country_select_Paraguay" value="Paraguay">Paraguay</option>
                <option id="country_select_Peru" value="Peru">Peru</option>
                <option id="country_select_Philippines" value="Philippines">Philippines</option>
                <option id="country_select_Poland" value="Poland">Poland</option>
                <option id="country_select_Portugal" value="Portugal">Portugal</option>
                <option id="country_select_Qatar" value="Qatar">Qatar</option>
                <option id="country_select_Romania" value="Romania">Romania</option>
                <option id="country_select_Rwanda" value="Rwanda">Rwanda</option>
                <option id="country_select_Saint Kitts and Nevis" value="Saint Kitts and Nevis">Saint Kitts and Nevis</option>
                <option id="country_select_Saint Lucia" value="Saint Lucia">Saint Lucia</option>
                <option id="country_select_Saint Vincent and The Grenadines" value="Saint Vincent and The Grenadines">Saint Vincent and The Grenadines</option>
                <option id="country_select_San Marino" value="San Marino">San Marino</option>
                <option id="country_select_Sao Tome and Principe" value="Sao Tome and Principe">Sao Tome and Principe</option>
                <option id="country_select_Saudi Arabia" value="Saudi Arabia">Saudi Arabia</option>
                <option id="country_select_Senegal" value="Senegal">Senegal</option>
                <option id="country_select_Serbia" value="Serbia">Serbia</option>
                <option id="country_select_Seychelles" value="Seychelles">Seychelles</option>
                <option id="country_select_Sierra Leone" value="Sierra Leone">Sierra Leone</option>
                <option id="country_select_Singapore" value="Singapore">Singapore</option>
                <option id="country_select_Slovakia" value="Slovakia">Slovakia</option>
                <option id="country_select_Slovenia" value="Slovenia">Slovenia</option>
                <option id="country_select_Somalia" value="Somalia">Somalia</option>
                <option id="country_select_South Africa" value="South Africa">South Africa</option>
                <option id="country_select_Spain" value="Spain">Spain</option>
                <option id="country_select_Sri Lanka" value="Sri Lanka">Sri Lanka</option>
                <option id="country_select_Sudan" value="Sudan">Sudan</option>
                <option id="country_select_Suriname" value="Suriname">Suriname</option>
                <option id="country_select_Sweden" value="Sweden">Sweden</option>
                <option id="country_select_Switzerland" value="Switzerland">Switzerland</option>
                <option id="country_select_Tajikistan" value="Tajikistan">Tajikistan</option>
                <option id="country_select_Thailand" value="Thailand">Thailand</option>
                <option id="country_select_Timor-leste" value="Timor-leste">Timor-leste</option>
                <option id="country_select_Togo" value="Togo">Togo</option>
                <option id="country_select_Trinidad and Tobago" value="Trinidad and Tobago">Trinidad and Tobago</option>
                <option id="country_select_Tunisia" value="Tunisia">Tunisia</option>
                <option id="country_select_Turkey" value="Turkey">Turkey</option>
                <option id="country_select_Uganda" value="Uganda">Uganda</option>
                <option id="country_select_Ukraine" value="Ukraine">Ukraine</option>
                <option id="country_select_United Arab Emirates" value="United Arab Emirates">United Arab Emirates</option>
                <option id="country_select_United Kingdom" value="United Kingdom">United Kingdom</option>
                <option id="country_select_USA" value="USA">USA</option>
                <option id="country_select_Uruguay" value="Uruguay">Uruguay</option>
                <option id="country_select_Uzbekistan" value="Uzbekistan">Uzbekistan</option>
                <option id="country_select_Venezuela" value="Venezuela">Venezuela</option>
                <option id="country_select_Vietnam" value="Vietnam">Vietnam</option>
                <option id="country_select_Western Sahara" value="Western Sahara">Western Sahara</option>
                <option id="country_select_Yemen" value="Yemen">Yemen</option>
                <option id="country_select_Zambia" value="Zambia">Zambia</option>
                <option id="country_select_Zimbabwe" value="Zimbabwe">Zimbabwe</option>
              </select>
      </div>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-md-4 p-2">
          <div class="card rounded-pill shadow">
            <div class="card-body">
              <h5 class="card-title font-weight-bold">Infected</h5>
              <p class="card-text">
                <img src="@/assets/infected.png" alt="infected corvid-19 image">
              </p>
              <div v-if="!load">
                <h2 class="font-weight-bold">
                {{infected|addComma}}
                </h2>
                <p>
                  {{date}}
                </p>
              </div>
              <div v-else>
                <img src="@/assets/200.gif" alt="loading gif">
              </div>
              <p class="font-weight-bold">
                Number of confirmed cases <br> of COVID19
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4 p-2">
          <div class="card rounded-pill shadow">
            <div class="card-body">
              <h5 class="card-title font-weight-bold">Recovered</h5>
              <p class="card-text">
                <img src="@/assets/recovered.png" alt="recovered corvid-19 image">
              </p>
              <div v-if="!load">
                <h2 class="font-weight-bold">
                {{recovered|addComma}}
                </h2>
                <p>
                  {{date}}
                </p>
              </div>
              <div v-else>
                <img src="@/assets/200.gif" alt="loading gif">
              </div>
              <p class="font-weight-bold">
                Number of recovories <br> from COVID19
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4 p-2">
          <div class="card rounded-pill shadow">
            <div class="card-body">
              <h5 class="card-title font-weight-bold">Deaths</h5>
              <p class="card-text">
                <img src="@/assets/death.jpg" alt="death corvid-19 image">
              </p>
              <div v-if="!load">
                <h2 class="font-weight-bold">
                {{dead|addComma}}
                </h2>
                <p>
                  {{date}}
                </p>
              </div>
              <div v-else>
                <img src="@/assets/200.gif" alt="loading gif">
              </div>
              <p class="font-weight-bold text-wrap">
                Number of deaths caused <br> by COVID19
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container py-3 " id="charts">
      <div class="row">
        <canvas id="pie" width="800" height="450"></canvas>
      </div>
    </div>

  </div>
</template>

<script>
import axios from 'axios'
import Chart from 'chart.js'

export default {
  name: 'Countries',
  data () {
    return {
      country: 'global',
      recovered: '',
      infected: '',
      dead: '',
      date: '',
      load: false

    }
  },
  methods: {
    fetchData () {
      let url = ''
      if (this.country === 'global') {
        // API endpoint for global results
        url = 'https://covid19.mathdro.id/api/'
      } else {
        // API endpoint for country results
        url = 'https://covid19.mathdro.id/api/countries/' + this.country
      }

      axios.get(url).then(response => {
        // reset loading
        this.load = false

        console.log(response.data)
        this.infected = response.data.confirmed.value
        this.recovered = response.data.recovered.value
        this.dead = response.data.deaths.value
        this.date = response.data.lastUpdate.substring(0, 10)

        const chartData = {
          type: 'pie',
          data: {
            labels: ['Infected Active', 'Recovered', 'Deaths'],
            datasets: [
              { // one line graph
                label: 'Number of Corana Virus Cases',
                data: [this.infected - this.recovered, this.recovered, this.dead],
                backgroundColor: ['#3e95cd', '#00FF00', '#FF0000']
              }]
          },
          options: {
            title: {
              display: true,
              text: 'Corona Virus cases in ' + (this.country === 'global' ? 'Whole World' : this.country)
            },
            responsive: true,
            legend: {
              display: true,
              labels: {
                padding: 20
              }
            },
            tooltips: {
              enabled: true
            }
          }
        }

        this.createChart('pie', chartData)
      })
        .catch(err => {
          console.log(err)
        })

      // loading
      this.load = true
    },
    createChart (chartId, chartData) {
      const ctx = document.getElementById(chartId).getContext('2d')
      // eslint-disable-next-line no-unused-vars
      const myChart = new Chart(ctx, {
        type: chartData.type,
        data: chartData.data,
        options: chartData.options
      })
    }
  },
  watch: {
    country: function (val, oldVal) {
      // fetch data
      this.fetchData()
    }
  },
  mounted () {
    this.fetchData()
  },
  filters: {
    addComma: function (num) {
      // addComma() : add commas to seperate given number
      // PARAM num : original number
      //       per : add comma per X digits
      const per = 3

      const cString = num.toString()
      let aComma = ''

      if (cString.length > per) {
        var j = 0
        for (let i = (cString.length - 1); i >= 0; i--) {
          // Add last character
          aComma = cString.charAt(i) + aComma

          // Add comma?
          j++
          if (j === per && i !== 0) {
            aComma = ',' + aComma
            j = 0
          }
        }
      } else {
        aComma = cString
      }

      return aComma
    }
  }

}
</script>

<style scoped>
img{
  width: 150px;
}
</style>
