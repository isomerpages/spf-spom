---
title: Event
permalink: /event/
description: ""
variant: markdown
---
<style type="text/css">
	@import "/files/Assets/css/bootstrap/dist/css/bootstrap.min.css";
		.navbar-brand, .navbar-tabs {
  align-items: stretch;
  display: flex;
  flex-shrink: 0;
  min-height: 6.25rem;
	padding: 0px;
	margin: 0px;
}
@media screen and (max-width: 1023px) {
  .navbar {
    padding: 0;
  }
}
@font-face {
    font-family: "nowblack";
    src: url("/files/Assets/fonts/now-black-webfont.woff2") format("woff2"), url("../fonts/now-black-webfont.woff") format("woff");
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: "nowbold";
    src: url("/files/Assets/fonts/now-bold-webfont.woff2") format("woff2"), url("../fonts/now-bold-webfont.woff") format("woff");
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: "nowlight";
    src: url("/files/Assets/fonts/now-light-webfont.woff2") format("woff2"), url("../fonts/now-light-webfont.woff") format("woff");
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: "nowmedium";
    src: url("../fonts/now-medium-webfont.woff2") format("woff2"), url("../fonts/now-medium-webfont.woff") format("woff");
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: "nowregular";
    src: url("/files/Assets/fonts/now-regular-webfont.woff2") format("woff2"), url("../fonts/now-regular-webfont.woff") format("woff");
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: "nowthin";
    src: url("/files/Assets/fonts/now-thin-webfont.woff2") format("woff2"), url("../fonts/now-thin-webfont.woff") format("woff");
    font-weight: normal;
    font-style: normal;
}
	body {
    font-family: "nowregular" !important;
    font-size: 14px !important;
    background-color: #ffffff !important;
}
	a[href$=".pdf"]::before {
    display: none;
}

h1.has-text-white {
  color: #ffffff;
  font-size: 30px;
  font-family: "nowbold";
  text-shadow: -1px 1px 8px rgba(0, 0, 0, 0.3);
  text-align: center;
  padding-top: 0px;
  text-transform: uppercase;
}
/*.masthead-container {
  background-color: #ebe7e4;
}
.navbar {
  background: #EBE7E4;
  padding: 40px;
}
.nav-item a {
  text-decoration: none;
}
.navbar-start {
  margin: 0 auto;
}*/
.tab-content {
  border: none;
}
	.bp-section-pagetitle {
        background: url(/files/Assets/images/event-bg.jpg) no-repeat center center !important;
        background-size: auto;
        background-size: cover !important;
        height: 338px !important;
    }
.tabset > input[type="radio"] {
  position: absolute;
  left: -200vw;
}
.tabset .tab-panel {
  display: none;
  animation: fadein .8s;
}
@keyframes fadein {
    from {
        opacity:0;
    }
    to {
        opacity:1;
    }
}
.tabset > input:first-child:checked ~ .tab-panels > .tab-panel:first-child,
.tabset > input:nth-child(3):checked ~ .tab-panels > .tab-panel:nth-child(2),
.tabset > input:nth-child(5):checked ~ .tab-panels > .tab-panel:nth-child(3),
.tabset > input:nth-child(7):checked ~ .tab-panels > .tab-panel:nth-child(4),
.tabset > input:nth-child(9):checked ~ .tab-panels > .tab-panel:nth-child(5),
.tabset > input:nth-child(11):checked ~ .tab-panels > .tab-panel:nth-child(6) {
  display: block;
}
.tabset > label {
  position: relative;
  display: inline-block;
  padding: 15px 15px 25px;
  border: 1px solid transparent;
  border-bottom: 0;
  cursor: pointer;
}
.tabset > label::after {
  background: #8d8d8d;
}
input:focus-visible + label {
  outline: 2px solid rgba(0,102,204,1);
  border-radius: 3px;
}
.tabset > label:hover,
.tabset > input:focus + label,
.tabset > input:checked + label {
  color: #06c;
}
.tabset > label:hover::after,
.tabset > input:focus + label::after,
.tabset > input:checked + label::after {
  background: #06c;
}
.tabset > input:checked + label {
  background: #1e1d56  !important;
  color: #fff !important;
}
.tab-panel {
  padding: 30px 0 0 0;
}
.tabset {
  max-width: 65em;
  text-align: center;
}
.tabset .nav-link {
  color: #414042 !important;
  margin-right: 10px !important;
  background-color: #ebe7e4 !important;
  border: 0 !important;
  border-radius: 0 !important;
  display: inline-block;
  min-width: 160px !important;
  padding: 15px !important;
  font-family: "nowbold" !important;
}
/*input.read-more-state {
  display: none;
}
p.read-more-target {
  font-size: 0;
  max-height: 0;
  opacity: 0;
  transition: .25s ease;
}
input.read-more-state:checked ~ div.read-more-wrap p.read-more-target {  
  font-size: 1.25rem;
  max-height: 999em;
  opacity: 1;
}
input.read-more-state ~ label.read-more-trigger:before {
  content: 'Read more';
}
input.read-more-state:checked ~ label.read-more-trigger:before {
  content: 'Read less';
}
label.read-more-trigger {
  cursor: pointer;
  display: inline-block;
}*/
</style>
<div class="tabset">
	<input type="radio" name="tabset" id="tab1" aria-controls="2019" checked="">
  <label for="tab1" class="nav-link">2019</label>  
	
  <input type="radio" name="tabset" id="tab2" aria-controls="2018">
  <label for="tab2" class="nav-link">2018</label>  
	
  <input type="radio" name="tabset" id="tab3" aria-controls="2017">
  <label for="tab3" class="nav-link">2017</label>	
	<div class="tab-panels">
		<section id="2019" class="tab-panel">      
        <div class="event-tab-content" id="pills-tabContent">
          <div class="tab-pane" id="pills-home" role="tabpanel" aria-labelledby="pills-home-tab">
            <div class="row">
              <div class="event">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2019/event-1.png" alt="spom happy hour">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOM Happy Hour</h3>
                    <span class="event-date"> 26 July 2019 </span>
                    <p> On the idyllic Friday evening of 26 July 2019, officers relaxed in the comfort of the SPOM Lounge and Ante Hall after hours. Mugs clinked and toasts were made amid the excited conversation that flowed freely </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="event">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2019/event-2.png" alt="spom happy hour">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOM Durian Night</h3>
                    <span class="event-date"> 12 July 2019 </span>
                    <p> The familiar aroma of durians first greeted the guests as they arrived and it was evident, “The King is back”. The evening kicked off with the traditional opening of the first durian by our Guests of Honour, the Commissioner of Police, Mr Hoong Wee Teck, and the Attorney-General of the Republic of Singapore, Mr Lucien Wong. </p>
                    <p>SPOM members had an enjoyable evening savouring the “King” and other tropical fruits. As always, SPOM members left satiated and all durian cravings fulfilled!</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="event">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2019/whiskeynight.jpg" alt="WHISKY APPRECIATION NIGHT">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">WHISKY APPRECIATION NIGHT – A MASTERCLASS</h3>
                    <span class="event-date"> 3 March 2019 </span>		    
                    <div id="section" class="show-more-wrp">
		      <input class="read-more-state" id="read-more-controller" type="checkbox">
                      <div class="article read-more-wrap">
                        <p> Whisky always had this aura of mystery and sophistication and to help dispel some of the myths and allow officers to appreciate it better, SPOM organised an appreciation night on 1 March to learn more about the “Water of Life”. </p>
                        <p> The evening started off with 2 different “flights” (or sessions) arranged by the organisers to accommodate the talk given by a brand ambassador. Attendees learnt more about the history of whisky, how it is made and how to best appreciate it. </p>
                        <p class="read-more-target"> Stepping into the antehall after the talk, Officers enjoyed an amazing spread of food to accompany the various expressions of whisky that were available for sampling. There was even a quiz where participants won whisky glasses and mini sample bottles to take home with them. It was yet another evening filled with laughter and everyone left with a big smile on their face! </p>
                        <p class="read-more-target"> “An excellent event to have a mini reunion accompanied by a sophisticated drink!” <br>
                          <strong>Mr Seah Tong Pin, Lima Division</strong>
                        </p>
                        <p class="read-more-target"> “An educational night where we learnt more about Whisky” <br>
                          <strong>Mr Luther Kim, Ops Dept</strong>
                        </p>
                      </div>
											<label class="read-more-trigger" for="read-more-controller"></label>                      
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="event no-border">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2019/spomlympic_2019.png" alt="spom happy hour">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOMlympics</h3>
                    <span class="event-date"> 25 January 2019 </span>
                    <div id="section" class="show-more-wrp">
                      <div class="article">
                        <p> On 25 Jan 2019, SPOMlympics saw a total of 26 teams comprising more than 100 members from various units coming together to compete. Members faced the challenge of evading arrows shot at them in Archery Tag, non-stop shooting into hoops at the Basketball Shootout and having adrenaline acceleration with a game of Daytona racing. </p>
                        <p> After an exciting evening of hits and misses, members gathered in the Ante Hall for the address by Mr How Kwang Hwee, the President of the Mess Committee (PMC) and the prize presentation. </p>
                        <p class="read-more-target"> The prize presentation started with the SPOM running challenge where Alpha Division clinched the Challenge Shield once again. Apart from the top three team prizes from SPOMlympics, nine other prizes were given out to outstanding individuals for their special “abilities”, ranging from being the “Butter Finger” at Basketball Shootout to “King of the Road” at Daytona. The event ended with a sumptuous dinner and smiles all around. </p>
                        <p class="read-more-target"> “Really enjoyed the fun and laughter created! Kudos to the committee. It is a testament of hardwork and planning put together by the team.” <br>
                          <strong>Mr Alex Tan, ProCom</strong>
                        </p>
                        <p class="read-more-target"> “A great evening, jam-packed with fun games, good company and laughter all round!”. <br>
                          <strong>Mr Andrew Ong, P&amp;O</strong>
                        </p>
                      </div>                      
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
  </section>
  <section id="2018" class="tab-panel">      
        <div class="event-tab-content" id="pills-tabContent">
          <div class="tab-pane" id="pills2018" role="tabpanel" aria-labelledby="pills2018-tab">
            <div class="row">
              <div class="event">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2018/yearendcarnival2.jpg" alt="YEAR-END CARNIVAL">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOM YEAR-END CARNIVAL</h3>
                    <span class="event-date"> 22 December 2018 </span>
                    <div id="section" class="show-more-wrp">
                      <div class="article">
                        <p>Fun for all. All for Fun. What is rain when you can have an afternoon of fun and games at SPOM’s first ever Year End Carnival? The afternoon showers certainly did not dampen the spirits of SPOM members and their families who arrived in droves!</p>
                        <p>More than 11 carnival games lined the 1st floor of SPOM, providing fun and laughter for everyone. The games might look like they were catered for the children, but uh-uh! The adults definitely had their fair share of fun, trying their skills in knocking down rubber duckies and shooting Nerf guns. But the No. 1 crowd pleaser? Definitely the Zoomoov station! No child could contain their excitement waiting for their turn and when they do board the animals with their parents, their infectious laughter filled the second floor of SPOM.</p>
                        <p class="read-more-target">Along with the sights and sounds of the carnival games, the smell of freshly made popcorn and cotton candy lingered in the air, adding to the joyous carnival atmosphere. The day was rounded up with a gift-giving session by Santa Claus who made a special appearance. It was a day truly enjoyed by both adults and children alike.</p>
                        <p class="read-more-target"> “This is my first time attending such an event. My children had a very fun time with all the games and activities.” <br>
                          <strong>Mr Louis Lou, E Division</strong>
                        </p>
                        <p class="read-more-target"> “It was a great opportunity for me to spend time with family and also bond with friends and colleagues!” <br>
                          <strong>Mr Teo Hong Yi, MPD</strong>
                        </p>
                      </div>                      
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="event">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2018/novfest.jpg" alt="November Fest">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">November Fest: Beer- Certainly One of Our Most Beloved Drinks </h3>
                    <span class="event-date"> 23 November 2018 </span>
                    <div id="section" class="show-more-wrp">
                      <div class="article">
                        <p>On 23 November 2018, more than 150 SPOM members gathered in SPOM for the Novembeer Fest and experienced 24 different types of beer to choose from, not to mention the buffet-style dinner and freshly served laksa that kept everyone satiated!</p>
                        <p>In keeping with the spirit of the event, the SPOM Ante Hall was decorated with eye-catching and informative posters of different beers, their origins, descriptions, and alcohol percentages. There was also a well-decorated photo booth with props which drew participants in and made it an undeniable hit of the event!</p>
                        <p class="read-more-target">On the other side of the Ante Hall was a Foosball table which attracted crowds to got everyone hyped up and ready to have fun!</p>
                        <p class="read-more-target">Drinking games were held for participants to guess the origin of some beers. This made the Novembeer Fest an interactive and educational one. Kudos to the SPOM organisers who also dutifully put up anti-drink driving posters as reminders at the exit of the Ante Hall!</p>
                        <p class="read-more-target"> “I enjoyed the beer, the company, and the friendship amongst different divisions and generations of officers.” <br>
                          <strong>Mr Samuel Koh, Investigation Officer, Jurong Division</strong>
                        </p>
                        <p class="read-more-target"> “It was a fun-filled evening with friends as we clinked our glass bottles filled with bubbles and hearts.” <br>
                          <strong>Mr Esh J Wadarajan, Senior Investigation Officer, CAD</strong>
                        </p>
                        <p class="read-more-target">
                          <b> Written by: Mr Boh Ping Hui</b>
                        </p>
                      </div>                      
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="event">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2018/bbqnight.jpg" alt="BBQ NIGHT">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOM BBQ Night</h3>
                    <span class="event-date"> 20 September 2018 </span>
                    <div id="section" class="show-more-wrp">
                      <div class="article">
                        <p>Despite the heavy downpour, the high spirits of our members were not dampened, buoyed by the gastronomic delights served during the SPOM BBQ. With “Variety” being the aim of the event, it could not be better portrayed than the wide array of barbequed food served at SPOM to all our members, with wine and beer in accompaniment.</p>
                        <p>The succulent lamb which had roasted over a fire pit, stole the show. But the satay, kebab and chicken wings which were barbecued with a tantalizing sauce, did not disappoint either. Members has the choice to wash down the sumptuous meat buffet with free flow of wine and beer provided.</p>
                        <p class="read-more-target">There could not be a more perfect opportunity to catch up with old friends over food and drinks. It was an evening that even bad weather could not bring down the spirited atmosphere of the event. </p>
                        <p class="read-more-target"> “The food was great and the warm atmosphere made this an awesome place to relax.” <br>
                          <strong>Mr Tommy Khoo, Ops Department</strong>
                        </p>
                        <p class="read-more-target"> “It was a night where members got together to enjoy each other’s company. The lamb and wine was delicious.” <br>
                          <strong>Mr Joel Ho, CCK NPC</strong>
                        </p>
                      </div>                      
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="event">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2018/happyhour.jpg" alt="Happy Hour">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOM Happy Hour 2018</h3>
                    <span class="event-date"> 31 August 2018 </span>
                    <div id="section" class="show-more-wrp">
                      <div class="article">
                        <p> It is said that the best days in life, end with a cold mug in your hand and a good chat with a friend. </p>
                        <p> SPOM Happy Hour is organised on a regular basis where many members gathered to explore the games and decked the hallways, have a drink and unwind after a week at work. Ice cold beer warmed the hearts of all as officers from all walks of life gather and forged new bonds. Many officers took this opportunity to explore the many facilities that SPOM had to offer and the rich culture that it embodies. </p>
                        <p class="read-more-target">While officers, young and old, sat together to share their experiences, the sweet aroma of freshly prepared food permeated the air. The free beer was only made better by the delicious food served out from SPOM’s restaurant. Beer and laughter flowed freely throughout the nights.</p>
                        <p class="read-more-target">As the moments shared were eternalized in SPOM’s history, the hour passed quickly and the supply of free beer inevitably diminished. Friends, old and new, soon bade each other good bye. Many looked forward to the next Happy Hour at SPOM, where an hour of happiness brings about a lifetime of memories. </p>
                        <p class="read-more-target"> “I enjoyed Happy Hour!” <br>
                          <strong>Mr Letts Tan, A Division</strong>
                        </p>
                        <p class="read-more-target"> “Events such as Happy Hour at SPOM is a good chance to catch up with friends and former colleagues and unwind together.” <br>
                          <strong>Mr Jayapandian, TCDD</strong>
                        </p>
                        <p class="read-more-target"> “Nothing is happier than chilling out with great friends after a day of work.” <br>
                          <strong>Ms Sabrina Koh, PHQ</strong>
                        </p>
                        <p class="read-more-target"> “It was my first time at SPOM Happy Hour and I had a great time catching up with peers from various units. The atmosphere was informal and relaxed, and free flow of beer always tastes delicious. I look forward to going back to SPOM for another round.” <br>
                          <strong>Mr Lee Ting Wei, TCDD</strong>
                        </p>
                        <p class="read-more-target">
                          <b> Written by: Mr Garret Chua</b>
                        </p>
                      </div>                      
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="event">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2018/duriannight.jpg" alt="Durian Night">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOM Durian Night</h3>
                    <h3 class="event-title">A THORNILY ENJOYABLE AFFAIR</h3>
                    <span class="event-date"> 10 August 2018 </span>
                    <div id="section" class="show-more-wrp">
                      <div class="article">
                        <p> With the spike in the supply of durians, members arriving for the bi-annual Durian Night at SPOM were understandably excited. They were looking forward to digging into the famed Mao Shan Wang durians as well as those of the D24 variety. </p>
                        <p> The balmy weather of this Friday evening allowed everyone to arrive in good spirits. When the Guest of Honour, Commissioner of Police, Mr Hoong Wee Teck arrived, he kicked-off the event by opening the first durian as well as leading the members in a hearty rendition of “Happy Birthday” to celebrate Singapore’s National Day. The organisers had even specially ordered a Durian birthday cake to commemorate the occasion! </p>
                        <p class="read-more-target"> There were plenty of laughter and smiles all round, and the 160 members who turned up could not ask for more, knowing that there were more than 220 KG of each durian variety available. It was indeed a lovely opportunity to catch up with friends while feasting on the king of fruits, washed down by cooling coconut juice. </p>
                        <p class="read-more-target"> “The food and durian were fabulous, and the weather was kind. These, and the good company made for an extremely enjoyable evening!” <br>
                          <strong>SUPT (1A) Ang Eng Seng</strong>
                        </p>
                      </div>                      
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="event  no-border">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2018/annualdinner.jpg" alt="Annual Dinner 2018">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOM Annual Dinner</h3>
                    <div id="section" class="show-more-wrp">
                      <div class="article">
                        <p> SPOM Annual Dinner is the one-day of the year, where our fraternity of senior officers gather at a single event and cast aside appointments, ranks and seniority as we celebrate our identity together as one SPOM. The scale of this event brought together the different SPOM Sub-Committees (Food &amp; Beverage, Membership and Internal Communications and Publications) to plan and execute the event. They joined existing members and retired senior officers that included former Commissioner of Police, Mr Tee Tua Ba, and former Deputy Commissioners. FY 2018 / 2019 was unique as 2 SPOM Annual Dinners were held in a year. </p>
                        <p class="read-more-target"> For SPOM Annual Dinner 2018, led by Mr Elvis Chong of Operations Department with the theme of an ‘Enchanted Garden’, achieved a record attendance of 550 guests. Annual Dinner 2018 introduced unique elements for the first time in this edition; first introduction of a digital LED back-drop, a performance by ‘Baracuda Batucada’, a percussion band from Ngee Ann Polytechnic, a unique ‘LED Wing Dance’, a powerful display of SPF’s talents with 4 bands serenading guests and the one-and-only ‘Kumar’ stole the show. </p>
                      </div>                      
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
    </section>
    <section id="2017" class="tab-panel">      
        <div class="event-tab-content" id="pills-tabContent">
          <div class="tab-pane" id="pills-profile" role="tabpanel" aria-labelledby="pills-profile-tab">
            <div class="row">
              <div class="event">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2017-2019/golf_2017.png" alt="spom happy hour">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOM Medal 2017 (Golf) </h3>
                    <span class="event-date"> 24 March 2017 </span>
                    <p> The 12th SPOM Golf Medal, which was co-organised by SPOM Sport Sub-Committee and Police Golfing Society, saw a total of 34 SPOM members competing at the 18-hole course at Seletar Country Club (SCC) on 24 Mar 2017. </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="event">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2017-2019/photography_2017.png" alt="spom happy hour">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOM Basic Photography Course</h3>
                    <span class="event-date"> 24 February 2017 </span>
                    <p> Our members at the inaugural SPOM Basic Photography Course were taught the key elements and technical aspects to photography, and the 6 golden principles to capturing a great image. </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="event">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2017-2019/spomlympic_2017.png" alt="spom happy hour">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOMlympics</h3>
                    <span class="event-date"> 6 February 2017 </span>
                    <p> The Loser Tog "battle field" came to life as participant took to the SPOM tennis courts in teams of four with a single aim - to gain victory by securing a symbolic red flag. The game was not only physically challenging, requiring teamwork, quick reflexes and a significant amount of running, it also saw officers cracking their brains to devise the best strategies to outdo each other. </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="event no-border">
                <div class="col-12 col-sm-6">
                  <div class="event-image">
                    <img src="/files/Assets/media/event/2017-2019/durian_2017.png" alt="spom happy hour">
                  </div>
                </div>
                <div class="col-12 col-sm-6">
                  <div class="event-details">
                    <h3 class="event-title">SPOM Durian Night</h3>
                    <span class="event-date"> 20 January 2017 </span>
                    <p> SPOM was honoured to have our Minister for Home Affairs, Mr K. Shanmugam and his wife, Dr. Seetha Shanmugam gracing the event with 180 SPOM members! </p>
                    <p>The evening saw more than 400 kilograms of quality D13, D24, Red Prawn and Mao Shan Wang durians being served and it was certainly a well-rounded experience for our members' palates as they satisfied their cravings, caught up with colleagues and interacted with our Minister.</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
    </section>
  </div>  
</div>