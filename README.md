<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>FramTracker</title>
    <link rel="preconnect" href="https://fonts.googleapis.com"> 
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
    <link href="https://fonts.googleapis.com/css2?family=Josefin+Slab:wght@100&display=swap" rel="stylesheet"> 
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
      />
      <style>
        *{
    margin: 0%; padding: 0%; box-sizing: border-box;
    font-family: 'Josefin Slab', serif;
    /*background-image: linear-gradient(rgba(0,0,0,0.3),rgba(0,0,0,1)) ,url('img1.jpg');*/
}

header{
    width: 100%; height: 100%;
   background-image: linear-gradient(rgba(0,0,0,0.3),rgba(0,0,0,1)) ,url('img1.jpg');
    background-repeat: no-repeat;
    background-size:100%;
    background-attachment: fixed;
}
nav{
    width: 100%; height: 5vh;
    background: rgb(0, 0, 0);
    color:white; display:flex; justify-content: space-between;
    align-items: center; text-transform: uppercase;
    position:fixed;
    text-align: center;

}
nav .logo{
    width: 25%; text-align: center;
    margin-top: 0.9%;
}
nav .menu{
    width: 40%; display: flex;
    justify-content: space-around;
    margin-top: 0.9%;
}
nav .menu a{
    width: 25%;
    text-decoration: none;
    font-weight: bolder;
    color: rgb(255, 255, 255);
}
nav .menu a:first-child{
    color: #00b894;
}
main{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}
/*section{
    position:relative;
    top: 500px;
 }*/
 section h2{
     font-size: 60px;
 }
section h3{
    font: 35px;
    font: weight 200; 
    letter-spacing: 3px;
text-shadow: 1px,1px,5px,2px yellowgreen;
}
section h1{
    margin:70px 0;
    font-size: 80px;
   font-weight: 700;
    text-shadow: 2px 1px 5px yellowgreen;
    text-transform: uppercase;
 }
 section p{
     font-size: 25px;
     word-spacing:  2px;
     margin-bottom: 25px;
     text-shadow: 1px 1px 1px yellowgreen;
    
 
 }
 section a{
     padding: 12px 30px;
     border-radius: 4px;
     outline: none;
     text-transform: uppercase;
     font-size: 13px;
     font-weight: 500;
     text-decoration: none;
     letter-spacing: 1px;
     transition: all .5s ease;
 }
 section .btnone{
    /* background-color: #0084;*/
    background: #ffff;
    color: #000;
 }
 .btnone:hover{
    background: #00b894;
    color: white;
 }
 section .btntwo{
    background: #00b894;
    color: white;
 }
 .btntwo:hover{
    background: #ffff;
    color: #000;
 }
 .change_content:after{
     content: '';
     animation: changetext 10s infinite linear;
     color: #00b894;;
 }
 @keyframes changetex{
     0%{content:"say";} 
     20%{content:"say";} 
     30%{content:"say";} 
 }
 footer{
        background-color: rgb(218, 252, 0);
       
       
     }

      </style>
  </head>
  <body>
    <header>
      <nav>
        <div class="logo"><h1 class="animate__heartBeat">FramTracker</h1></div>
        <div class="menu">
          <a href="#">Home</a>
          <a href="#">Gallery</a>
          <a href="#">About</a>
          <a href="#">Contact</a>
        </div>
      </nav>
      <main>
        <section>
          <h1>Tomato</h1>
          <h2><b>Crop Description and Climate</b><span></span></h2><br>
          <p>
            Tomato is a rapidly growing crop with a growing period of 90 to 150
            days. It is a daylength neutral plant. Optimum mean daily
            temperature for growth is 18 to 25ºC with night temperatures between
            10 and 20ºC. Larger differences between day and night temperatures,
            however, adversely affect yield. The crop is very sensitive to
            frost. Temperatures above 25ºC, when accompanied by high humidity
            and strong wind, result in reduced yield. Night temperatures above
            2OºC accompanied by high humidity and low sunshine lead to excessive
            vegetative growth and poor fruit production. High humidity leads to
            a greater incidence of pests and diseases and fruit rotting. Dry
            climates are therefore preferred for tomato production.
          </p><br>
          <a
            href="https://www.fao.org/land-water/databases-and-software/crop-information/tomato/en/"
            class="btnone"
            >learn more</a>
          <a
            href="https://translate.google.co.in/?sl=en&tl=hi&text=Tomato%20is%20a%20rapidly%20growing%20crop%20with%20a%20growing%20period%20of%2090%20to%20150%0A%20%20%20%20%20%20%20%20%20%20%20%20days.%20It%20is%20a%20daylength%20neutral%20plant.%20Optimum%20mean%20daily%0A%20%20%20%20%20%20%20%20%20%20%20%20temperature%20for%20growth%20is%2018%20to%2025ºC%20with%20night%20temperatures%20between%0A%20%20%20%20%20%20%20%20%20%20%20%2010%20and%2020ºC.%20Larger%20differences%20between%20day%20and%20night%20temperatures%2C%0A%20%20%20%20%20%20%20%20%20%20%20%20however%2C%20adversely%20affect%20yield.%20The%20crop%20is%20very%20sensitive%20to%0A%20%20%20%20%20%20%20%20%20%20%20%20frost.%20Temperatures%20above%2025ºC%2C%20when%20accompanied%20by%20high%20humidity%0A%20%20%20%20%20%20%20%20%20%20%20%20and%20strong%20wind%2C%20result%20in%20reduced%20yield.%20Night%20temperatures%20above%0A%20%20%20%20%20%20%20%20%20%20%20%202OºC%20accompanied%20by%20high%20humidity%20and%20low%20sunshine%20lead%20to%20excessive%0A%20%20%20%20%20%20%20%20%20%20%20%20vegetative%20growth%20and%20poor%20fruit%20production.%20High%20humidity%20leads%20to%0A%20%20%20%20%20%20%20%20%20%20%20%20a%20greater%20incidence%20of%20pests%20and%20diseases%20and%20fruit%20rotting.%20Dry%0A%20%20%20%20%20%20%20%20%20%20%20%20climates%20are%20therefore%20preferred%20for%20tomato%20production.&op=translate"
            class="btntwo"
            >Google Tanslate</a><br><br><br>
          <h2><b>Water Requirements</b><span></span></h2><br>
          <p>
            Total water requirements (ETm) after transplanting, of a tomato crop
            grown in the field for 90 to 120 days, are 400 to 600 mm, depending
            on the climate. Water requirements related to reference
            evapotranspiration (ETo) in mm/period are given by the crop factor
            (Kc) for different crop development stages, or: during the initial
            stage 0. 4-0. 5 (10 to 15 days), the development stage 0. 7-0.8 (20
            to 30 days), the mid- season stage 1.05-1.25 (30 to 40 days), the
            late-season stage 0.8-0.9 (30 to 40 days) and at harvest 0.6-0.65.
          </p>
          <a href="#" class="btnone">learn more</a>
          <a
            href="https://translate.google.co.in/?source=osdd&sl=auto&tl=hi&text=Total%20water%20requirements%20(ETm)%20after%20transplanting%2C%20of%20a%20tomato%20crop%20grown%20in%20the%20field%20for%2090%20to%20120%20days%2C%20are%20400%20to%20600%20mm%2C%20depending%20on%20the%20climate.%20Water%20requirements%20related%20to%20reference%20evapotranspiration%20(ETo)%20in%20mm%2Fperiod%20are%20given%20by%20the%20crop%20factor%20(Kc)%20for%20different%20crop%20development%20stages%2C%20or%3A%20during%20the%20initial%20stage%200.%204-0.%205%20(10%20to%2015%20days)%2C%20the%20development%20stage%200.%207-0.8%20(20%20to%2030%20days)%2C%20the%20mid-%20season%20stage%201.05-1.25%20(30%20to%2040%20days)%2C%20the%20late-season%20stage%200.8-0.9%20(30%20to%2040%20days)%20and%20at%20harvest%200.6-0.65.&op=translate"
            class="btntwo"
            >Google Tanslate</a><br><br><br>
          <h2><b>Irrigation Scheduling</b><span></span></h2><br>
          <p>
            The crop performance is sensitive to the irrigation practices. In
            general a prolonged severe water deficit limits growth and reduces
            yields which cannot be corrected by heavy watering later on. Highest
            demand for water is during flowering. however, withholding
            irrigation during this period is sometimes recommended to force less
            mature plants into flowering in order to obtain uniform flowering
            and ripening. Care should be exercised in this to avoid damage to
            the mature plants.
          </p>
          <a
            href="https://www.fao.org/land-water/databases-and-software/crop-information/tomato/en/"
            class="btnone"
            >learn more</a>
          <a
            href="https://translate.google.co.in/?source=osdd&sl=auto&tl=hi&text=The%20crop%20performance%20is%20sensitive%20to%20the%20irrigation%20practices.%20In%20general%20a%20prolonged%20severe%20water%20deficit%20limits%20growth%20and%20reduces%20yields%20which%20cannot%20be%20corrected%20by%20heavy%20watering%20later%20on.%20Highest%20demand%20for%20water%20is%20during%20flowering.%20however%2C%20withholding%20irrigation%20during%20this%20period%20is%20sometimes%20recommended%20to%20force%20less%20mature%20plants%20into%20flowering%20in%20order%20to%20obtain%20uniform%20flowering%20and%20ripening.%20Care%20should%20be%20exercised%20in%20this%20to%20avoid%20damage%20to%20the%20mature%20plants.%0A&op=translate"
            class="btntwo"
            >Google Tanslate</a><br><br><br>
          <h2><b>Irrigation Methods</b><span></span></h2><br>
          <p>
            Surface irrigation by furrow is commonly practised. Under sprinkler
            irrigation the occurrence of fungal diseases and possibly bacterial
            canker may become a major problem. Further, under sprinkler, fruit
            set may be reduced with an increase in fruit rotting. In the case of
            poor quality water, leaf burn will occur with sprinkler irriga-tion;
            this may be reduced by sprinkling at night and shifting of sprinkler
            lines with the direction of the prevailing wind. Due to the crops
            specific demands for a high soil water content achieved without leaf
            wetting, trickle or drip irrigation has been successfully applied.
          </p>
          <a href="#" class="btnone">learn more</a>
          <a
            href="https://translate.google.co.in/?source=osdd&sl=auto&tl=hi&text=Surface%20irrigation%20by%20furrow%20is%20commonly%20practised.%20Under%20sprinkler%20irrigation%20the%20occurrence%20of%20fungal%20diseases%20and%20possibly%20bacterial%20canker%20may%20become%20a%20major%20problem.%20Further%2C%20under%20sprinkler%2C%20fruit%20set%20may%20be%20reduced%20with%20an%20increase%20in%20fruit%20rotting.%20In%20the%20case%20of%20poor%20quality%20water%2C%20leaf%20burn%20will%20occur%20with%20sprinkler%20irriga-tion%3B%20this%20may%20be%20reduced%20by%20sprinkling%20at%20night%20and%20shifting%20of%20sprinkler%20lines%20with%20the%20direction%20of%20the%20prevailing%20wind.%20Due%20to%20the%20crops%20specific%20demands%20for%20a%20high%20soil%20water%20content%20achieved%20without%20leaf%20wetting%2C%20trickle%20or%20drip%20irrigation%20has%20been%20successfully%20applied.&op=translate"
            class="btntwo"
            >Google Tanslate</a><br><br><br>
          <h2><b>Yield</b><span></span></h2><br>
          <p>
            Frequent light irrigation improve the size, shape, juiciness and
            colour of the fruit, but total solids (dry matter content) and acid
            content will be reduced. However, the decrease in solids will lower
            the fruit quality for processing. In selecting the irrigation
            practices consideration must therefore be given to teh type of end
            product required. Prolonged water deficits leads to fruit cracking.
            Where fruit rot is a problem, frequent sprinkler irrigation should
            be avoided during the period of yield formation.
          </p>
          <a
            href="https://www.fao.org/land-water/databases-and-software/crop-information/tomato/en/"
            class="btnone"
            >learn more</a
          >
          <a
            href="https://translate.google.co.in/?source=osdd&sl=auto&tl=hi&text=Frequent%20light%20irrigation%20improve%20the%20size%2C%20shape%2C%20juiciness%20and%20colour%20of%20the%20fruit%2C%20but%20total%20solids%20(dry%20matter%20content)%20and%20acid%20content%20will%20be%20reduced.%20However%2C%20the%20decrease%20in%20solids%20will%20lower%20the%20fruit%20quality%20for%20processing.%20In%20selecting%20the%20irrigation%20practices%20consideration%20must%20therefore%20be%20given%20to%20teh%20type%20of%20end%20product%20required.%20Prolonged%20water%20deficits%20leads%20to%20fruit%20cracking.%20Where%20fruit%20rot%20is%20a%20problem%2C%20frequent%20sprinkler%20irrigation%20should%20be%20avoided%20during%20the%20period%20of%20yield%20formation.%0A%0A&op=translate"
            class="btntwo"
            >Google Tanslate</a><br><br><br>
        </section>
      </main>
    </header>
   <footer>
      <h6>Reference website :- <a href="https://www.fao.org">https://www.fao.org</a></h6><br>
      <p>@Copyright2022</p>
    </footer>
  </body>
</html>
