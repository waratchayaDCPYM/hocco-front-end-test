<template>
<v-container>
  <div>
    <!-- Header with back button -->
    <v-row>
      <v-col cols="12" md="12">
        <v-btn class="ma-2" tile text large color="#f9891b">
          <v-icon left>mdi-chevron-left</v-icon>
          <p class="font-button mt-4"> BACK </p>
        </v-btn>
        <v-divider class="mx-6 mb-8" color="#f9891b"></v-divider>
      </v-col>
    </v-row>

    <!-- TUNA -->
    <v-row align="center">
      <v-col cols="12" md="6" align="center" class="mx-3 mt-12 mb-12">
        <v-img src="@/assets/Mask Group 13@3x.png" class="image-tuna" aspect-ratio="1" contain></v-img>
      </v-col>

      <v-col cols="12" md="4" class="mx-3 mt-2">
        <v-row>
          <p class="text-tuna mt-8">TUNA</p>
        </v-row>
        <v-row>
          <p class="text-solid-chuck-flake-shredded mt-1">SOLID, CHUCK, FLAKE, SHREDDED</p>
        </v-row>
        <v-row>
          <p class="text-tuna-description my-12">Pellentesque semper quis neque dictum hendrerit. Sed nulla ipsum, porttitor pharetra tortor in,consequat imperdiet nisi. Phasellus at quam tristique, cursus tellus vitae, convallis neque.</p>
        </v-row>
        <v-row>
        <v-divider  class="divider-size-bold mt-4" color="#3b98c9"></v-divider>
        </v-row>
      </v-col>
    </v-row>

    <!-- SPEICIES -->
    <v-content>
      <div class="Rectangle-background-gray mt-12">
        <v-row>
          <!-- <v-col cols="12"> -->
              <div class="text-page-header-absolute-brown  ml-12">SPEICIES</div>

                <!-- SPEICIES Content -->
                <v-row justify="center" align="center" class="mt-12">
                  <!-- ALBACORE -->
                  <v-col cols="12" md="4">
                    <v-row class="mt-12">
                      <v-col cols="12" md="12" align="center">
                        <div class="Rectangle-medium">
                          <v-row> </v-row>
                          <div align="left" class="mt-12 ml-12">
                            <p class="text-card-header-orange">ALBACORE</p>
                            <p class="text-card-content">(Thunnus alalunga)</p>
                          </div>
                          <v-row align="left" class="mt-12">
                            <v-img src="@/assets/Image 54@3x.png" class="image-speicies-small content-left-margin-50"></v-img>
                          </v-row>
                        </div>
                      </v-col>
                    </v-row>
                  </v-col>

                  <!-- TONGOL -->
                  <v-col cols="12" md="4" >
                    <v-row class="mt-12">
                      <v-col cols="12" md="12" align="center">
                        <div class="Rectangle-large">
                          <v-row> </v-row>
                          <div align="left" class="mt-12 ml-12">
                            <p class="text-card-header-orange">TONGOL</p>
                            <p class="text-card-content">(hunnus tonggol)</p>
                          </div>
                          <v-row align="left" class="mt-12">
                            <v-img src="@/assets/Image 76@3x.png" class="image-speicies-large content-left-margin-50"></v-img>
                          </v-row>
                        </div>
                      </v-col>
                    </v-row>
                  </v-col>

                  <!-- YELLOWFIN -->
                  <v-col cols="12" md="4" >
                    <v-row class="mt-12">
                      <v-col cols="12" md="12" align="center">
                        <div class="Rectangle-medium">
                          <v-row> </v-row>
                          <div align="left" class="mt-12 ml-12">
                            <p class="text-card-header-orange">YELLOWFIN</p>
                            <p class="text-card-content">(Thunnus albacares)</p>
                          </div>
                          <v-row align="left" class="mt-12">
                            <v-img src="@/assets/Image 77@3x.png" class="image-speicies-small content-left-margin-50"></v-img>
                          </v-row>
                        </div>
                      </v-col>
                    </v-row>
                  </v-col>
                </v-row>
          <!-- </v-col> -->
        </v-row>
      </div>
    </v-content>
    
    <!-- PREV & Next button -->
    <v-content>
      <v-row class="content-top-margin-200">
          <v-btn class="ma-2 ml-12" tile text large color="#f9891b">
            <v-icon left>mdi-chevron-left</v-icon>
            <p class="font-button mt-4"> PREV </p>
          </v-btn>
          <v-spacer></v-spacer>
          <v-btn class="ma-2 mr-12" align="right" tile text large color="#f9891b">
            <p class="font-button mt-4"> Next </p>
            <v-icon right>mdi-chevron-right</v-icon> 
          </v-btn>
      </v-row>
    </v-content>

    <!-- MEAT -->
    <div class="Rectangle-background-white content-top-margin-100">
      <v-row>
        <!-- <v-col cols="12" md="12"> -->
          <div class="text-page-header-absolute-brown ml-12">MEAT</div>

            <!-- MEAT Content -->
            <v-row align="center" justify="center" class="mt-8">
              <!-- SOLID -->
                <v-col cols="12" md="2" align="center" justify="center" class="mx-12 mb-12">
                  <v-row align="center" justify="center">
                    <p class="text-card-header-gray">SOLID</p>
                  </v-row>
                  <v-row align="center" justify="center" class="mt-6">
                    <v-img src="@/assets/Group 201@3x.png" class="image-meat" contain></v-img>
                  </v-row>
                </v-col>

              <!-- CHUCK -->
                <v-col cols="12" md="2" align="center" justify="center" class="mx-12 mb-12">
                  <v-row align="center" justify="center">
                    <p class="text-card-header-gray">CHUCK</p>
                  </v-row>
                  <v-row align="center" justify="center" class="mt-6">
                    <v-img src="@/assets/Group 203@3x.png" class="image-meat" contain></v-img>
                  </v-row>
                </v-col>

                <!-- FLAKE -->
                <v-col cols="12" md="2" align="center" justify="center" class="mx-12 mb-12">
                  <v-row align="center" justify="center">
                    <p class="text-card-header-gray">FLAKE</p>
                  </v-row>
                  <v-row align="center" justify="center" class="mt-6">
                    <v-img src="@/assets/Group 202@3x.png" class="image-meat" contain></v-img>
                  </v-row>
                </v-col>

                <!-- SHREDDED -->
                <v-col cols="12" md="2" align="center" justify="center" class="mx-12 mb-12">
                  <v-row align="center" justify="center">
                    <p class="text-card-header-gray">SHREDDED</p>
                  </v-row>
                  <v-row align="center" justify="center" class="mt-6">
                    <v-img src="@/assets/Group 198@3x.png" class="image-meat" contain></v-img>
                  </v-row>
                </v-col>
            </v-row>
          <!-- </v-col> -->
      </v-row>
    </div>

    <!-- MEDIA -->
    <div class="Rectangle-background-yellow">
      <v-row>
        <v-col cols="12">
          <p class="text-page-header-absolute-white text-md-center content-top-margin-100">MEDIA</p>

           <!-- MEDIA Content -->
           <div class="content-top-margin-100">
              <v-row justify="center" class="mt-8">
                  <!-- BRINE -->
                  <v-col cols="12" md="3" lg="2" align="center" class="mx-2 mb-12">
                    <div class="Rectangle-card-white" align="center" justify="center">
                      <v-col cols="12" md="12" align="center" justify="center">
                        <v-row align="center" justify="center">
                          <p class="text-card-header-orange mt-12 text-md-center">BRINE</p>
                        </v-row>
                        <v-row align="center" justify="center">
                          <v-img src="@/assets/Image 92@3x.png" class="image-media" contain></v-img>
                        </v-row>
                      </v-col>
                    </div>
                  </v-col>

                  <!-- SOYBEAN OIL -->
                  <v-col cols="12" md="3" lg="2" align="center" class="mx-2 mb-12">
                    <div class="Rectangle-card-white" align="center" justify="center">
                      <v-col cols="12" md="12" align="center" justify="center">
                        <v-row align="center" justify="center">
                          <p class="text-card-header-orange mt-12 text-md-center">SOYBEAN OIL</p>
                        </v-row>
                        <v-row align="center" justify="center">
                          <v-img src="@/assets/Image 68@3x.png" class="image-media" contain></v-img>
                        </v-row>
                      </v-col>
                    </div>
                  </v-col>

                  <!-- SUNFLOWER OIL -->
                  <v-col cols="12" md="3" lg="2"  align="center" class="mx-2 mb-12">
                    <div class="Rectangle-card-white" align="center" justify="center">
                      <v-col cols="12" md="12" align="center" justify="center">
                        <v-row align="center" justify="center">
                          <p class="text-card-header-orange mt-12 text-md-center">SUNFLOWER OIL</p>
                        </v-row>
                        <v-row align="center" justify="center">
                          <v-img src="@/assets/Image 91@3x.png" class="image-media" contain></v-img>
                        </v-row>
                      </v-col>
                    </div>
                  </v-col>

                  <!-- OLIVE OIL -->
                  <v-col cols="12" md="3" lg="2" align="center" class="mx-2 mb-12">
                    <div class="Rectangle-card-white" align="center" justify="center">
                      <v-col cols="12" md="12" align="center" justify="center">
                        <v-row align="center" justify="center">
                          <p class="text-card-header-orange mt-12 text-md-center">SUNFLOWER OIL</p>
                        </v-row>
                        <v-row align="center" justify="center">
                          <v-img src="@/assets/Mask Group 20@3x.png" class="image-media" contain></v-img>
                        </v-row>
                      </v-col>
                    </div>   
                  </v-col>
              </v-row>
              
           </div>

        </v-col>
      </v-row>
    </div>

    <!-- SIZE -->
    <v-row>
      <v-col cols="12">
        <p class="text-page-header-brown text-md-center content-top-margin-250">SIZE</p>
      </v-col>
    </v-row>

    <div class="Rectangle-card-gray content-top-margin-50">
      <v-row>
        <v-col cols="2"></v-col>
        <v-col cols="8">
          <v-tabs class="mt-6"
            fixed-tabs
            background-color="transparent"
            color="#f9891b"
          >
            <v-tab>
              <p style="font-family: Roboto; font-size: 20px;">SOLID</p>
            </v-tab>
            <v-tab>
              <p style="font-family: Roboto; font-size: 20px;">CHUCK</p>
            </v-tab>
            <v-tab>
              <p style="font-family: Roboto; font-size: 20px;">FLAKE</p>
            </v-tab>
            <v-tab>
              <p style="font-family: Roboto; font-size: 20px;">SHREDDED</p> 
            </v-tab>
          </v-tabs>
        </v-col>
        <v-col cols="2"></v-col>
      </v-row>
    </div>

    <!-- Table -->
    <v-row>
      <v-col cols="2"></v-col>
      <v-col cols="8">
        <v-simple-table fixed-header height="700px">
          <template v-slot:default>
              <thead>
                <tr class="text-table-header">
                    <th class="text-center"><br>NET WEIGHT <p class="text-table-subheader">(g.)</p></th>
                    <th class="text-center"><br>NET WEIGHT <p class="text-table-subheader">(2)</p></th>
                    <th class="text-center">DRAIN WEIGHT</th>
                    <th class="text-center">CAN SIZE</th>
                    <th class="text-center">CANS/CARTON</th>
                    <th class="text-center"><br>CANS/20’FCL <p class="text-table-subheader">(Normal Lid)</p></th>
                    <th class="text-center"><br>CANS/20’FCL <p class="text-table-subheader">(EOE)</p></th>
                </tr>
              </thead>
            <tbody class="text-table-content">
              <tr v-for="item in size" :key="item.NetWeightg">
                <td class="text-center">{{ item.NetWeightg }}</td>
                <td class="text-center">{{ item.NetWeight2 }}</td>
                <td class="text-center">{{ item.DrainWeight }}</td>
                <td class="text-center">{{ item.CanSize }}</td>
                <td class="text-center">{{ item.CansCarton }}</td>
                <td class="text-center">{{ item.CanNormal }}</td>
                <td class="text-center">{{ item.CanEoe }}</td>
              </tr>
            </tbody>
          </template>
        </v-simple-table>
      </v-col>
      <v-col cols="2"></v-col>
    </v-row>

    <!-- copy right -->
    <div class="Rectangle-background-darkblue content-top-margin-50">
      <v-row align="center" justify="center">
        <p class="text-card-content-white mt-6 text-md-center">Copyright © A.E.C. CANNING COMPANY LIMITED 2017</p>
      </v-row>
    </div>
  </div>
</v-container>
</template>

<script>
 export default {
    data () {
      return {
        size: [
          {
            NetWeightg: '80',
            NetWeight2: '3',
            DrainWeight: '56',
            CanSize: '211x109',
            CansCarton: '48',
            CanNormal:'3,600',
            CanEoe: '3,300'
          },
          {
            NetWeightg: '95',
            NetWeight2: '3.5',
            DrainWeight: '67',
            CanSize: '211x109',
            CansCarton: '48',
            CanNormal: '3,500',
            CanEoe:'3,200'
          },
          {
            NetWeightg: '140',
            NetWeight2: '5',
            DrainWeight: '98',
            CanSize: '307x105.0',
            CansCarton: '48',
            CanNormal: '2,400',
            CanEoe:'2,300'
          },
          {
            NetWeightg: '150',
            NetWeight2: '5.5',
            DrainWeight: '105',
            CanSize: '307x108',
            CansCarton: '48',
            CanNormal: '2,400',
            CanEoe:'2,300'
          },
          {
            NetWeightg: '160',
            NetWeight2: '6',
            DrainWeight: '112',
            CanSize: '307x108',
            CansCarton: '48',
            CanNormal: '2,100',
            CanEoe:'2,000'
          },
          {
            NetWeightg: '170',
            NetWeight2: '6',
            DrainWeight: '120',
            CanSize: '307x111',
            CansCarton: '48',
            CanNormal: '2,100',
            CanEoe:'2,000'
          },
          {
            NetWeightg: '185',
            NetWeight2: '6.5',
            DrainWeight: '130',
            CanSize: '307x111',
            CansCarton: '48',
            CanNormal: '2,000',
            CanEoe:'1,800'
          },
          {
            NetWeightg: '200',
            NetWeight2: '7',
            DrainWeight: '140',
            CanSize: '307x113',
            CansCarton: '48',
            CanNormal: '1,800',
            CanEoe: '1,750'
          },
          {
            NetWeightg: '400',
            NetWeight2: '15',
            DrainWeight: '298',
            CanSize: '401x212',
            CansCarton: '24',
            CanNormal: '1,800',
            CanEoe: '1,550'
          },
          {
            NetWeightg: '425',
            NetWeight2: '15',
            DrainWeight: '298',
            CanSize: '401x212',
            CansCarton: '24',
            CanNormal: '1,800',
            CanEoe: '1,550'
          },
          {
            NetWeightg: '1,000',
            NetWeight2: '35',
            DrainWeight: '700',
            CanSize: '603x212',
            CansCarton: '12',
            CanNormal: '1,300',
            CanEoe: '-'
          },
          {
            NetWeightg: '1,850',
            NetWeight2: '66.5',
            DrainWeight: '1,300',
            CanSize: '603x408',
            CansCarton: '6',
            CanNormal: '1,600',
            CanEoe: '-'
          },

        ],
      }
    },
  }
</script>

<style>
.divider-size-bold {
  height: 3px !important;
  max-height: 5px !important;
}

.font-button {
  font-family: Roboto;
  font-size: 20px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.3;
  letter-spacing: 2px;
  text-align: left;
  color: #f9891b;
}

.image-tuna {
  width: 572px;
  height: 299px;
  object-fit: contain;
}

.image-speicies-small {
  width: 313px;
  height: 125px;
  object-fit: contain;
}

.image-speicies-large {
  width: 369px;
  height: 177px;
  object-fit: contain;
}

.image-meat {
  width: 250px;
  height: 250px; 
}

.image-media{
  width: 197px;
  height: 148px;
}

.Rectangle-medium{
  width: 288px;
  height: 340px;
  box-shadow: 0 0 30px 0 rgba(0, 0, 0, 0.1);
  background-color: #ffffff;
}

.Rectangle-large {
  width: 343.2px;
  height: 405.1px;
  box-shadow: 0 0 30px 0 rgba(0, 0, 0, 0.1);
  background-color: #ffffff;
}

.Rectangle-background-gray {
  position: relative;
  height: 400px;
  background-color: #fafafa;
}

.Rectangle-background-white{
  position: relative;
  height: 380px;
  border-radius: 5px;
  box-shadow: 0 0 30px 0 rgba(0, 0, 0, 0.1);
  background-color: #ffffff;
}

.Rectangle-background-yellow {
  position: relative;
  height: 350px;
  background-color: #f9c410;
}

.Rectangle-background-darkblue {
  height: 79px;
  background-color: #041225;
}

.Rectangle-card-white {
  width: 288px;
  height: 180px;
  border: solid 1px #f9c410;
  background-color: #ffffff;
}

.Rectangle-card-gray {
  height: 100px;
  background-color: #fafafa;
}


.text-tuna {
  font-family: Roboto;
  font-size: 30px;
  font-weight: 500;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.3;
  letter-spacing: 3px;
  color: #3b98c9;
}

.text-solid-chuck-flake-shredded {
  font-family: Roboto;
  font-size: 20px;
  font-weight: 300;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.3;
  letter-spacing: 2px;
  color: #939393;
}

.text-tuna-description {
  font-family: Roboto;
  font-size: 14px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.36;
  letter-spacing: normal;
  color: #a8a8a8;
}

.text-page-header-absolute-white {
  font-family: Roboto;
  font-size: 60px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 0.5;
  letter-spacing: 6px;
  color: #ffffff;
}

.text-page-header-absolute-brown {
  position: absolute;
  top: -10px;
  font-family: Roboto;
  font-size: 50px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 0.6;
  letter-spacing: 5px;
  color: #ddc7a9;
}

.text-page-header-brown {
  font-family: Roboto;
  font-size: 60px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 0.5;
  letter-spacing: 6px;
  color: #ddc7a9;
}

.text-card-header-orange {
  font-family: Roboto;
  font-size: 20px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.3;
  letter-spacing: 2px;
  color: #f9891b;
}

.text-card-header-gray {
  font-family: Roboto;
  font-size: 20px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.3;
  letter-spacing: 2px;
  text-align: left;
  color: #939393;
}

.text-card-content{
  font-family: Roboto;
  font-size: 20px;
  font-weight: 300;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.3;
  letter-spacing: 2px;
  text-align: left;
  color: #939393;
}

.text-card-content-white {
  font-family: Roboto;
  font-size: 20px;
  font-weight: 300;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.3;
  letter-spacing: 2px;
  color: #ffffff;
}

.text-table-header{
  font-family: Roboto;
  font-size: 14px;
  font-weight: 300;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.43;
  letter-spacing: 1.4px;
  color: #000000;
}

.text-table-subheader{
  font-family: Roboto;
  font-size: 14px;
  font-weight: 300;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.43;
  letter-spacing: 1.4px;
  color: #6a7990;
}

.text-table-content{
  font-family: Roboto;
  font-weight: 300;
  font-stretch: normal;
  font-style: normal;
  line-height: 2.5;
  letter-spacing: normal;
  color: #6a7990;
}

.v-data-table tbody td {
    font-size: 20px !important;
}
.v-data-table thead th {
    font-size: 14px !important;
}

.content-top-margin-250{
  margin-top: 250px;
}

.content-top-margin-200{
  margin-top: 200px;
}

.content-top-margin-100{
  margin-top: 100px;
}

.content-top-margin-50{
  margin-top: 50px;
}

.content-left-margin-50{
  margin-left: -50px;
}

</style>