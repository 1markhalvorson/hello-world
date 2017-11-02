# hello-world
Montana Web

h1 {
  font-family: 'Cormorant', serif;
  font-size: 120px;
  font-weight: 200;
  font-variant: small-caps;
  color: RoyalBlue;
  letter-spacing: 7px;
}
h1 span {
  font-family: 'Cormorant', serif;
  font-size: 40px;
  font-style: oblique;
  color: black;
}
h2 {
  font-family: 'Cormorant', serif;
  font-size: 44px;
  font-weight: lighter;
  letter-spacing: 3px;
  color: black;
  margin: 7px 0px 25px 0px;
}
h2 span {
  font-family: 'Cormorant', serif;
  font-size: 26px;
  font-weight: lighter;
  font-style: oblique;
  letter-spacing: 3px;
  color: RoyalBlue;
}
h3 {
  font-family: 'Cormorant', serif;
  font-size: 20px;
  font-weight: 100;
  font-style: oblique;
  letter-spacing: 2px;
  color: black;
  border-color: RoyalBlue;
  border-style: solid;
  border-width: 1px;
  border-right-width: 17px;
  border-left-style: none;
  border-bottom-style: none;
  padding: 10px 10px 10px 10px;
}
h3 span {
  font-family: 'Cormorant', serif;
  color: RoyalBlue;
  font-style: normal;
  font-size: 20px;
  font-weight: 400;
}
h4 {
  font-family: 'Cormorant', serif;
  font-size: 30px;
  font-weight: 400;
  font-variant: small-caps;
  color: black;
  letter-spacing: 1px;
}
p {
  font-family: 'Cormorant', serif;
  font-size: 21px;
  font-color: black;
}
.img1 {
  height: 350px;
  width: 100%;
  border-radius: 50%;
}
.div-rows {
  margin: 25px 10px 0px 10px;
}
.list1 {
  font-family: 'Cormorant', serif;
  font-size: 22px;
  font-style: italic;
  color: black;
  padding-top: 15px;
}
.list2 {
  font-family: 'Cormorant', serif;
  font-size: 22px;
  color: green;
}

<div class="container-fluid">
  <div class="row">
    <div class="col-md-12 text-center">
      <h1>Montana <span>"Oro</span>y<span>Plata"</span></h1>
    </div>
  </div>
  <div class="row">
    <div class="col-md-12 text-center">
      <h2 class=>'Big Sky Country' <span>and / or</span> 'The Treasure State' <span> work well, too.</span></h2>
    </div>
  </div>
  <div class="row div-rows">
    <div class="col-md-8">
      <h3 class="text-center"><span>"I’m in love with Montana</span>. For other states I have admiration, respect, recognition, even some affection. But with Montana it is love. And it’s difficult to analyze love when you’re in it.<span>" John Steinbeck</span></h3>
      <ul class="list1 text-center">
        <li>Tree: Ponderosa Pine</li>
        <li>Flower: Bitterroot</li>
        <li>Gems: Sapphire and Agate</li>
        <li>Fish: Westslope Cutthroat Trout</li>
        <li>Mammal: Grizzly Bear</li>
      </ul>
    </div>
    <div class="col-md-4">
      <a href="https://en.wikipedia.org/wiki/Montana"><img class="img-responsive img1" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Montana_territory_coat_of_arms_%28illustrated%2C_1876%29.jpg/800px-Montana_territory_coat_of_arms_%28illustrated%2C_1876%29.jpg" alt="of old"></a>
    </div>
  </div>
  <div class="row div-rows">
    <div class="col-md-5">
      <a href="http://www.visitmt.com/"><img class="img-responsive img1" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Montana-StateSeal.svg/713px-Montana-StateSeal.svg.png" alt="of new"></a>
    </div>
    <div class="col-md-7">
      <h4>and of 'National' concern,</h4>
      <ul class="list2">
        <li>Bighorn Canyon - National Recreation Area</li>
        <li>Fort Union Trading Post - National Historic Site</li>
        <li>Glacier - National Park</li>
        <li>Yellowstone - National Park</li>
        <li>Lewis & Clark - National Historic Trail</li>
        <li>Little Bighorn Battlefield - National Monument</li>
        <li>Nez Perce - National Historic Park</li>
      </ul>
      <p>here's an interesting, more <a href="https://www.nps.gov/iafl/index.htm">Ice Age-ish tidbit.</a> Enjoy!</p>
    </div>
  </div>
