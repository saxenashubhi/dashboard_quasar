<template>
  <q-layout>
    <div slot="header" class="toolbar">
      <q-toolbar-title :padding="150" :margin-left="100">
       Indian Premier League: 10 Saal Aapke Naam 
      </q-toolbar-title>
    </div>

    
    <div class="layout-view">
    <div class="layout-padding">
     <div>
        <div class ="card" inline style="width: 100%" >
            <div class="card-title">
              IPL All Seasons Analysis
             </div>
            <q-parallax src='https://s-media-cache-ak0.pinimg.com/736x/85/4e/2c/854e2c99ad78a0e2061762058c5bd8f4--logo-pictures-pictures-images.jpg' style="height: 500px">
            </q-parallax>
          <br />
            <q-rating
              class="orange"
              v-model="ratingModel"
              :max="5"
              styel="margin-left: 40px"
            ></q-rating>
          <div class="card-content">
             <br/>
             <p> <b>Analysis of all 10 Seasons.</b><br /> Please rate it if you like it!</p>
          </div> 
        </div>
        <div class="row">
          <div class="card bg-red-14 text-white" inline style="width:500px">
            <div class="card-title" slot="overlay">
            <b> Mumbai Indians </b>
            <br />
            <span slot="subtitle">Has won most number of matches that is 80 in total!</span>
            </div>
            <img src="~assets/mostmatches1.png">
          </div>
          <div class="card bg-cyan-14 text-black-14" style="width:500px">
          <div class="card-title" slot="overlay">
            <b> Chris Gayle </b>
            <br />
            <span slot="subtitle">Has won most number of man of matches!</span>
            </div>
            <img src="~assets/manofmatches.jpg">
          </div>
         </div>
         <div class="card text-purple-14" style="width: 100%">
            <div class="card-title">
              Deccan Chargers
             </div>
             <q-parallax src='http://timesofindia.indiatimes.com/photo/46863109.cms' style="height: 500px">
            </q-parallax>
             <div class="card-content">
             <br/>
             <p> <b>Win By maximun number of wickets</b><br /> Against Mumbai Indians, season 2008!</p>
          </div> 
         </div>
         <div class="row">
          <div class="card bg-teal text-white" inline style="width:500px">
            <div class="card-title" slot="overlay">
            <b> Chris Gayle Again!! </b>
            <br />
            <span slot="subtitle">Has most number of sixes in all seasons!</span>
            </div>
            <img src="~assets/sixesbyplayer.jpg">
          </div>
          <div class="card bg-blue-grey text-white" style="width:500px">
          <div class="card-title" slot="overlay">
            <b> Gautam Gambhir </b>
            <br />
            <span slot="subtitle">Has most number of fours in all seasons!</span>
            </div>
            <img src="~assets/foursbyplayer.jpg">
          </div>
         </div>
         <div class="row">
          <div class="card bg-red-14 text-white" inline style="width:500px">
            <div class="card-title" slot="overlay">
            <b>Favourite Umpire </b>
            <br />
            <span slot="subtitle">HDPK Dharmasena!</span>
            </div>
            <img src="https://ssl.c.photoshelter.com/img-get2/I00009iDTnza5s2Q/fit=1000x750/JR-Match-47-KKR-v-RR-1131.jpg">
          </div>
          <div class="card bg-lime" style="width:500px">
          <div class="card-title" slot="overlay">
            <b> Gujrat Lions </b>
            <br />
            <span slot="subtitle">Have the highest  number of total runs!</span>
            </div>
            <img src="~assets/highestruns.jpg">
          </div>
         </div>
         <div class="row">
          <div class="card text-blue-14" inline style="width:500px">
            <div class="card-title" slot="overlay">
            <b>SL Malinga </b>
            <br />
            <span slot="subtitle">Taken the most wickets till now!</span>
            </div>
            <img src="http://a.espncdn.com/combiner/i?img=/media/motion/cricinfo/2014/0531/cric_140531_COM_CRICKET_England_vs_Sri_Lanka_Malinga_wickets_and_death_bowling_20140531/cric_140531_COM_CRICKET_England_vs_Sri_Lanka_Malinga_wickets_and_death_bowling_20140531.jpg">
          </div>
          <div class="card" style="width:500px">
            <img src="~assets/mostnowickets.jpg">
          </div>
         </div>
           <div class="card bg-pink text-white" style="width: 100%">
            <div class="card-title">
              Win by highest number of runs!
             </div>
             <div class="card-subtitle" style="margin-left:15px">
              Obviously Royal Challengers Banglore!
             </div>
             <img src='https://i.ytimg.com/vi/c6p0SGwV7SA/maxresdefault.jpg' style="height:350px" /> 
         </div>


     </div>
     
    </div>
    </div>
  </q-layout>
</template>

<script>
</script>

<style lang="styl">
</style>
