---
title: Facilities
permalink: /facility/
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
        background: url(/files/Assets/images/facility-bg.jpg) no-repeat center center !important;
        background-size: auto;
        background-size: cover !important;
        height: 338px !important;
}
.clear-backend {
  background: #fff;
  width: 100%;
  height: 800px;
  position: relative;
}
.clear-backend > input {
  position: absolute;
  filter: alpha(opacity=0);
  opacity: 0;
}
.clear-backend > input:hover {
  cursor: pointer;
}
.clear-backend > input:hover + span,
.clear-backend > input:checked + span {
  background: #1e1d56;
  color: #FFF;
}
.clear-backend > input:checked:after {
  content: ">";
  font-family: "nowbold";
  position: absolute;
  color: #fff !important;
  font-size: 18px !important;
  right: 15px;
  top: 15px;
}
.clear-backend > input:checked + span + i {
  color: #FFF;
}
.clear-backend > i {
  position: absolute;
  margin-top: -40px;
  padding: 0 20px;
  font-size: 20px;
}
.clear-backend > span,
.clear-backend > i {
  -webkit-transition: all .5s;
     -moz-transition: all .5s;
     -o-transition: all .5s;
      transition: all .5s;
}
.clear-backend > input,
.clear-backend > span {
  background: #ebe7e4;
display: block;
width: 200px;
height: 60px;
line-height: 60px;
text-align: left;
z-index: 9;
padding-left: 15px;
font-size: 18px;
font-weight: 600;
}
.tab-content {
  position: absolute;
  top: 0;
  right: 0;
  width: calc(100% - 200px);
  height: 100%;
  overflow: hidden;
}
.tab-content section {
  position: absolute;
  width: 100%;
  height: 100%;
  padding: 20px;
  display: none;
}
.clear-backend > input.tab-1:checked ~ .tab-content .tab-item-1 {
  display: block;
}
.clear-backend > input.tab-2:checked ~ .tab-content .tab-item-2 {
  display: block;
}
.clear-backend > input.tab-3:checked ~ .tab-content .tab-item-3 {
  display: block;
}
.clear-backend > input.tab-4:checked ~ .tab-content .tab-item-4 {
  display: block;
}
.facility-type-title {
  font-size: 21px;
  line-height: 24px;
  color: #000000 !important;
  text-transform: uppercase;
  margin-bottom: 20px;
}
@media only screen and (max-width: 641px) {
  .avatar, 
  .clear-backend > input,
  .clear-backend > span {
    width: 60px;
    height: 60px;
  }
  .clear-backend > span {
    filter: alpha(opacity=0);
    opacity: 0;
  }
  .avatar div {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    top: 5px;
    left: 5px;
  }
  .top-bar,
  .tab-content {
  width: calc(100% - 60px);
  }
}
	.facility-main {
    background: url(/files/Assets/images/facility-bg.jpg) no-repeat center center;
    background-size: 100%;
}

.facility-main .facility-inner {
    padding: 0px 0 0px;
    width: 100%;
}

.facility-main .facility-inner .redeem-ttl {
    justify-content: center;
    width: 100%;
    display: flex;
    align-items: center;
}

@media (min-width: 1200px) {
    .facility-main .facility-inner .redeem-ttl {
        height: 345px;
    }
}

@media (max-width: 1366px) {
    .facility-main .facility-inner .redeem-ttl {
        height: 345px;
    }
}

@media (max-width: 1199.98px) {
    .facility-main .facility-inner .redeem-ttl {
        height: 274px;
    }
}

@media (max-width: 991.98px) {
    .facility-main .facility-inner .redeem-ttl {
        height: 205px;
    }
}

@media (max-width: 767.98px) {
    .facility-main .facility-inner .redeem-ttl {
        height: 185px;
    }
}

@media (max-width: 575.98px) {
    .facility-main .facility-inner .redeem-ttl {
        height: 122px;
    }
}

@media (max-width: 320px) {
    .facility-main .facility-inner .redeem-ttl {
        height: 90px;
    }
}

.facility-main .facility-inner h2 {
    color: #ffffff;
    font-size: 30px;
    font-family: "nowbold";
    text-shadow: -1px 1px 8px rgba(0, 0, 0, 0.3);
    text-align: center;
    padding-top: 0px;
}

@media (max-width: 767.98px) {
    .facility-main .facility-inner h2 {
        font-size: 20px;
    }
}
.facility-highlights-main {
    padding: 50px 0 40px;
}
.facility-left{padding-right:0 !important;}
.facility-right{padding-left:0 !important;}
.facility-type-title{
        font-size:21px;
        line-height:24px;
        color:#000000;
        /* font-weight:600; */
        text-transform: uppercase;
        margin-bottom:20px;
}
.facility-nav .nav-link{
    padding: 15px !important;
   font-size:18px !important;
  line-height:22px !important;
}
.facility-nav .nav-link.active{
    background: #1e1d56 !important;
    color: #fff !important;
    font-family: "nowbold";
    position: relative;
    
}
.facility-nav .nav-link.active:after{
    content: ">";
    font-family: "nowbold";
    position: absolute;
    color: #fff !important;
    font-size:18px !important;
    right:15px;
    top:15px;
}

.facility-tab-content .facility-media{
    width:50%;
    float: left;
    padding-right:15px;
}
.facility-tab-content .facility-media .lslide{
    position: relative;
}
.facility-tab-content .facility-media .slider-image-text{
    position: absolute;
    bottom:0;
    width: 100%;
    margin-bottom: 0;
    display: inline-block;
    padding:5px;
    background-color:#000;
    opacity:0.5;
    font-size:16px;
    color:#fff;
    font-family: "nowbold";
}
.facility-tab-content .facility-media .slider-image-text span{
    font-size:16px;
    color:#fff;
    font-family: "nowbold";
}
.facility-tab-content .facility-type-details{
    width:50%;
    float: right;
    padding:0 15px 0 0;
}
.facility-tab-content .facility-type-details .facility-title{
    color: #1e1d56;
   font-size:30px;
    font-family: "nowbold";
}
.facility-tab-content .facility-type-details p{
    margin-bottom:25px;
}
.facility-tab-content .facility-table thead th{
    color:#fff !important;
    padding: 5px 7px !important;
    font-size: 16px;
}
.facility-tab-content .facility-table td{
    padding:3px 7px !important;
    font-size:16px;
    font-weight:600;
    color:#414042;
}


.facility-tab-content .facility-table .facility-name span{
    font-size:12px;
}
.facility-media .demo .lSSlideOuter .lSPager.lSGallery img{height:75px !important;}
.facility-media .demo .lSSlideOuter .lSPager.lSGallery{margin-top:10px !important;}
.facility-table .data-left{background-color:#e7e7e7;}
.facility-table .data-right{background-color:#efefef;}
.facility-table .even-data-left{background-color:#c1c1c1;}
.facility-table .even-data-right{background-color:#d6d6d6;}
.facility-table .thead-right {background-color:#292882;width:40%;}
.facility-table .thead-left {background-color:#1e1d56;width:60%;}
/* facility-v2 style */
.facility-nav{
    display: flex;
    flex-direction: column;
}
.facility-nav .tablinks{
    border:0 !important;
    text-align: left !important;
    color: #000000 !important;
    font-weight:600 !important;
    margin-right: 10px !important;
    background-color: #ebe7e4 !important;
    border: 0 !important;
    border-radius: 0 !important;
    padding: 15px !important;
    font-size: 18px !important;
    line-height: 22px !important;

}
.facility-nav  .tablinks.active{
    
        background: #1e1d56 !important;
        color: #fff !important;
        font-family: "nowbold";
        position: relative;
    
    
    
}
.facility-nav  button:focus{
    outline:none !important;
}
.facility-nav  .tablinks.active:after{
    content: ">";
    font-family: "nowbold";
    position: absolute;
    color: #fff !important;
    font-size:18px !important;
    right:15px;
    top:15px;
}
.lightSlider > li {
    position: relative;
}
.facility-media .demo .caption {
    background-color: rgba(0, 0, 0, 0.5);
    /* height: 35px; */
    position: absolute;
    font-family: "nowbold";
    bottom: 0;
    left: 0;
    font-size:18px;
    line-height:22px;
    padding:11px 15px;
    color: white;
    width: 100%;
}
.facility-media .demo .caption p {
    margin:0;
}
	.print-content .cms-page-container .tab-content {
	position: unset;
	width: 100%;
	height: auto;
	margin-top: 0;
	overflow: unset;
}

.print-content .cms-page-container .clear-backend > span {
	width: 100%;
	height: auto;
	position: unset;
	opacity: 1;
}

.print-content .cms-page-container .clear-backend > input {
	width: 100%;
	height: auto;
	position: unset;
	opacity: 0;
}

.print-content .cms-page-container .tab-content section {
	position: unset;
	padding: 0;
}

.print-content .cms-page-container .facility-tab-content .facility-type-details, 
.print-content .cms-page-container .facility-tab-content .facility-media {
	padding: 0;
}
/* .dollor-sign{font-family:nowbold !important;} */
.facility-price{font-family: "nowbold";}
.lSSlideOuter .lSPager.lSGallery li.active, .lSSlideOuter .lSPager.lSGallery li:hover{border-radius:0 !important;}
@media (max-width: 991px) {
    .facility-tab-content .facility-type-details,.facility-tab-content .facility-media{
        width:100%;
        float: left;
        padding:15px;
    }
}
@media (max-width:767px){
    .facility-media .demo{margin-top:2rem;}
    .facility-tab-content .facility-table{width:100% !important;}
    .facility-left{padding-right:10px !important;}
    .facility-right{padding-left:10px !important;}
}
@media (max-width:568px){
    .event-highlights-main{padding:40px 0 0;}
}
$max-img-width: 600px;
$max-img-height: 400px;
.gallery img {
  max-width: 100% !important;
  vertical-align: top !important;
}
.gallery {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-gap: 20px;
  grid-column-start: 1;
  grid-row-start: 1;
  grid-row-end: 3;
  align-content: start;
  max-width: 700px;
  margin: 0 auto;
  transition: all 150ms linear;
}
.gallery input[type="radio"] {
  display: none;
}
.gallery label {
  position: relative;
  display: block;
  padding-bottom: 60%;
  margin: 5px;
  cursor: pointer;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 50% 50%;
}
.gallery label:before {
  border: 1px solid #e3e3e3;
  content: '';
  position: absolute;
  left: -5px;
  right: -5px;
  bottom: -5px;
  top: -5px;
}
.gallery img {
  display: none;
  grid-column-start: 1;
  grid-column-end: 5;
  grid-row-start: 1;
  grid-row-end: 2;
  width: 100%;
  transition: all 150ms linear;
}
.gallery input[name="select"]:checked + label + img {
  display: block;
}
.gallery input[name="select"]:checked + label:before {
  border: 1px solid #000;
}
.gallery2 {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-gap: 20px;
  grid-column-start: 1;
  grid-row-start: 1;
  grid-row-end: 3;
  align-content: start;
  max-width: 700px;
  margin: 0 auto;
  transition: all 150ms linear;
}
.gallery2 input[type="radio"] {
  display: none;
}
.gallery2 label {
  position: relative;
  display: block;
  padding-bottom: 60%;
  margin: 5px;
  cursor: pointer;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 50% 50%;
}
.gallery2 label:before {
  border: 1px solid #e3e3e3;
  content: '';
  position: absolute;
  left: -5px;
  right: -5px;
  bottom: -5px;
  top: -5px;
}
.gallery2 img {
  display: none;
  grid-column-start: 1;
  grid-column-end: 5;
  grid-row-start: 1;
  grid-row-end: 2;
  width: 100%;
  transition: all 150ms linear;
}
.gallery2 input[name="select2"]:checked + label + img {
  display: block;
}
.gallery2 input[name="select2"]:checked + label:before {
  border: 1px solid #000;
}	
.gallery3 {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-gap: 20px;
  grid-column-start: 1;
  grid-row-start: 1;
  grid-row-end: 3;
  align-content: start;
  max-width: 700px;
  margin: 0 auto;
  transition: all 150ms linear;
}
.gallery3 input[type="radio"] {
  display: none;
}
.gallery3 label {
  position: relative;
  display: block;
  padding-bottom: 60%;
  margin: 5px;
  cursor: pointer;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 50% 50%;
}
.gallery3 label:before {
  border: 1px solid #e3e3e3;
  content: '';
  position: absolute;
  left: -5px;
  right: -5px;
  bottom: -5px;
  top: -5px;
}
.gallery3 img {
  display: none;
  grid-column-start: 1;
  grid-column-end: 5;
  grid-row-start: 1;
  grid-row-end: 2;
  width: 100%;
  transition: all 150ms linear;
}
.gallery3 input[name="select3"]:checked + label + img {
  display: block;
}
.gallery3 input[name="select3"]:checked + label:before {
  border: 1px solid #000;
}	
</style>
<section class="cms-page-container">
<div class="container">
<div class="clear-backend">
<h3 class="facility-type-title">Type of facility</h3>
<input type="radio" class="tab-1" name="tab" checked="checked">
<span>Event Space</span><i class="fa fa-home"></i>
<input type="radio" class="tab-2" name="tab">
<span>Dining Rooms</span><i class="fa fa-medium"></i>
<input type="radio" class="tab-3" name="tab">
<span>Meeting Rooms</span><i class="fa fa-user"></i>
<input type="radio" class="tab-4" name="tab">
<span>Leisure</span><i class="fa fa-comment"></i>
<div class="tab-content">
  <section class="tab-item-1">
    <div id="event-space" class="tabcontent facility-tab-content">
          <div class="facility-media">
            <div class="demo">
              <div class="item">
                <div class="clearfix mb-5" style="max-width:474px;margin: 0 auto;">
                                    <div class="gallery">
                                            <input id="img-tab-1" name="select" checked="checked" type="radio">
                                        <label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/facility/KTVPrivateRoom.jpg);" for="img-tab-1"></label>
                                        <img border="0" src="/files/Assets/media/facility/KTVPrivateRoom.jpg">
                                        <input id="img-tab-2" name="select" type="radio">
                                        <label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/facility/KTVLounge.jpg);" for="img-tab-2"></label>
                                        <img border="0" src="/files/Assets/media/facility/KTVLounge.jpg">
                                        <input id="img-tab-3" name="select" type="radio">
                                        <label style="background-image: url('https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/facility/ChaletRooms.jpg');" for="img-tab-3"></label>
                                        <img border="0" src="/files/Assets/media/facility/ChaletRooms.jpg"> 
                                    </div>
                  </div>
                </div>
              </div>
            </div>          
          <div class="facility-type-details">
            <h3 class="facility-title">Event Space</h3>
            <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. </p>
            <table class="table  facility-table">
              <thead>
                <tr>
                  <th scope="col" class="thead-left">Facility</th>
                  <th scope="col" class="thead-right">Fee</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td class="facility-name data-left">Ante Hall</td>
                  <td class="facility-price data-right">
                    <span class="dollor-sign">$</span>50 / 4hrs
                  </td>
                </tr>
                <tr>
                  <td class="facility-name even-data-left">Dining Hall <br>
                    <span>(Incl. free use of Foyer )</span>
                  </td>
                  <td class="facility-price even-data-right">
                    <span class="dollor-sign">$</span>150 / day
                  </td>
                </tr>
                <tr>
                  <td class="facility-name data-left">Foyer <br>
                    <span>(Free with booking of Dining hall)</span>
                  </td>
                  <td class="facility-price data-right">
                    <span class="dollor-sign">$</span>30 / 4hrs
                  </td>
                </tr>
                <tr>
                  <td class="facility-name even-data-left"> Lawn </td>
                  <td class="facility-price even-data-right">
                    <span class="dollor-sign">$</span>20 /day
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
    </div>
  </section>
  <section class="tab-item-2">
    <div id="dining" class="tabcontent facility-tab-content">
          <div class="facility-media">
            <div class="demo">
              <div class="item">
                <div class="clearfix" style="max-width:474px;margin: 0 auto;">
									<div class="gallery2">
											<input id="img-tab-21" name="select2" checked="checked" type="radio">
										<label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/facility/Bar&amp;Dinning.jpg);" for="img-tab-21"></label>
										<img border="0" src="/files/Assets/media/facility/Bar&amp;Dinning.jpg">
										<input id="img-tab-22" name="select2" type="radio">
										<label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/facility/BBQPits.jpg);" for="img-tab-22"></label>
										<img border="0" src="/files/Assets/media/facility/BBQPits.jpg">
									</div>
                </div>
              </div>
            </div>
          </div>
          <div class="facility-type-details">
            <h3 class="facility-title">Dining Rooms</h3>
            <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. </p>
            <table class="table  facility-table">
              <thead>
                <tr>
                  <th scope="col" class="thead-left">Facility</th>
                  <th scope="col" class="thead-right">Fee</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td class="facility-name data-left">Private Dining Room</td>
                  <td class="facility-price data-right">Free</td>
                </tr>
                <tr>
                  <td class="facility-name even-data-left">Fine Dining Room</td>
                  <td class="facility-price even-data-right">
                    <span class="dollor-sign">$</span>40 / 4hrs
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
  </section>
  <section class="tab-item-3">
    <div id="meeting" class="tabcontent facility-tab-content">
          <div class="facility-media">
            <div class="demo">
              <div class="item">
                <div class="clearfix" style="max-width:474px;margin: 0 auto;">
                  <div style="padding-top:10px">                    
                      <img alt="" src="/files/Assets/media/facility/Foyer.jpg">
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="facility-type-details">
            <h3 class="facility-title">Meeting Rooms</h3>
            <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. </p>
            <table class="table  facility-table">
              <thead>
                <tr>
                  <th scope="col" class="thead-left">Facility</th>
                  <th scope="col" class="thead-right">Fee</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td class="facility-name data-left">Committee Room</td>
                  <td class="facility-price data-right">
                    <span class="dollor-sign">$</span>20 / 4hrs
                  </td>
                </tr>
                <tr>
                  <td class="facility-name even-data-left">Games Room</td>
                  <td class="facility-price even-data-right">
                    <span class="dollor-sign">$</span>20 / 4hrs
                  </td>
                </tr>
                <tr>
                  <td class="facility-name data-left">Library</td>
                  <td class="facility-price data-right">
                    <span class="dollor-sign">$</span>20 / 4hrs
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
  </section>
  <section class="tab-item-4">
    <div id="leisure" class="tabcontent facility-tab-content">
          <div class="facility-media">
            <div class="demo">
              <div class="item">
                <div class="clearfix" style="max-width:474px;margin: 0 auto;">
									<div class="gallery3">
											<input id="img-tab-31" name="select3" checked="checked" type="radio">
										<label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/facility/Gymnasium.jpg);" for="img-tab-31"></label>
										<img border="0" src="/files/Assets/media/facility/Gymnasium.jpg">
										<input id="img-tab-32" name="select3" type="radio">
										<label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/facility/Dartboard.jpg);" for="img-tab-32"></label>
										<img border="0" src="/files/Assets/media/facility/Dartboard.jpg">
										<input id="img-tab-33" name="select3" type="radio">
										<label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/facility/FoosballTable.jpg);" for="img-tab-33"></label>
										<img border="0" src="/files/Assets/media/facility/FoosballTable.jpg">
									</div>            
                </div>
              </div>
            </div>
          </div>
          <div class="facility-type-details">
            <h3 class="facility-title">Leisure</h3>
            <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. </p>
            <table class="table  facility-table">
              <thead>
                <tr>
                  <th scope="col" class="thead-left">Facility</th>
                  <th scope="col" class="thead-right">Fee</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td class="facility-name data-left">Tennis</td>
                  <td class="facility-price data-right">
                    <span class="dollor-sign">$</span>7.50 / hr
                  </td>
                </tr>
                <tr>
                  <td class="facility-name even-data-left">KTV - Private Room</td>
                  <td class="facility-price even-data-right">
                    <span class="dollor-sign">$</span>10 / 2hrs
                  </td>
                </tr>
                <tr>
                  <td class="facility-name data-left">KTV - Lounge</td>
                  <td class="facility-price data-right">
                    <span class="dollor-sign">$</span>40 / 2hrs
                  </td>
                </tr>
                <tr>
                  <td class="facility-name even-data-left"> Chalest <br>
                    <span>(incl. free use of BBQ Pits)</span>
                  </td>
                  <td class="facility-price even-data-right">
                    <span class="dollor-sign">$</span>40 / day
                  </td>
                </tr>
                <tr>
                  <td class="facility-name data-left"> BBQ Pits <br>
                    <span>(Free with booking of Chalet)</span>
                  </td>
                  <td class="facility-price data-right">
                    <span class="dollor-sign">$</span>10 / day
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
  </section></div></div></div></section>