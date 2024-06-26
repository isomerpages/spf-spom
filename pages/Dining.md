---
title: Dining
permalink: /dining/
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
        background: url(/files/Assets/images/dining-bg.jpg) no-repeat center center !important;
        background-size: auto;
        background-size: cover !important;
        height: 338px !important;
    }
    /* Dining css starts */

.dining-main {
    background: url(/files/Assets/images/dining-bg.jpg) no-repeat center center;
    background-size: 100%;
}

.dining-main .dining-inner {
    padding: 0px 0 0px;
    width: 100%;
}

.dining-main .dining-inner .redeem-ttl {
    justify-content: center;
    width: 100%;
    display: flex;
    align-items: center;
}

@media (min-width: 1200px) {
    .dining-main .dining-inner .redeem-ttl {
        height: 400px;
    }
}

@media (max-width: 1366px) {
    .dining-main .dining-inner .redeem-ttl {
        height: 375px;
    }
}

@media (max-width: 1199.98px) {
    .dining-main .dining-inner .redeem-ttl {
        height: 274px;
    }
}

@media (max-width: 991.98px) {
    .dining-main .dining-inner .redeem-ttl {
        height: 205px;
    }
}

@media (max-width: 767.98px) {
    .dining-main .dining-inner .redeem-ttl {
        height: 185px;
    }
}

@media (max-width: 575.98px) {
    .dining-main .dining-inner .redeem-ttl {
        height: 122px;
    }
}

@media (max-width: 320px) {
    .dining-main .dining-inner .redeem-ttl {
        height: 90px;
    }
}

.dining-main .dining-inner h2 {
    color: #ffffff;
    font-size: 30px;
    font-family: "nowbold";
    text-shadow: -1px 1px 8px rgba(0, 0, 0, 0.3);
    text-align: center;
    padding-top: 0px;
}

@media (max-width: 575.98px) {
    .dining-main .dining-inner h2 {
        font-size: 20px;
    }
}

.dining-highlights-main {
    padding: 50px 0 40px;
}

.dining-highlights-main h3 {
    font-family: "nowmedium";
    font-size: 30px;
    color: #414042;
    margin-bottom: 20px;
}

.dining-highlights-main p {
    font-family: "nowregular";
    font-size: 18px;
    max-width: 72%;
    margin: 0 auto;
    color: #414042;
    line-height: 30px;
}

.dining-mission-main {
    padding: 0px;
}

.dining-container {
    max-width: 1050px;
    margin: 0 auto;
    padding: 0 15px;
}

.dining-container .dining-detail-left .dining-title {
    /*font-size: 20px;*/
    line-height: 22px;
    color: #414042;
    margin-top:10px;
    margin-bottom:20px;
}

.dining-container .dining-detail-left p {
    font-size: 15px;
    margin-bottom:1.5rem;
}

.dining-container .dining-detail-left .dining-table {
    /*width: 55%;*/
    margin-bottom: 3.3rem;
}

.dining-container .dining-detail-left .dining-table .list-title {
    width: 38%;
    position: relative;
}

.dining-container .dining-detail-left .dining-table .list-title:after {
    content: ":";
    position: absolute;
    right: 0;
}

.dining-container .dining-detail-left .dining-table .list-detail {
    width: 62%;
    padding-left: 10%;
}
.dining-container .dining-detail-left .detail-btn {
    padding: 10px;
    height: 50px;
    display: inline-block;
    background-color: #1e1d56;
    color: #fff;
    font-size: 18px;
    text-transform: uppercase;
    text-align: center;
    width: 48%;
    border: 0;
    text-decoration: none;
}

.dining-detail-right ul {
    list-style: none outside none;
    padding-left: 0;
    margin: 0;
}
@media (max-width: 991.98px) {
    .dining-container .dining-detail-left .dining-table {
        width: 100%;
        margin-bottom:1rem;
    }
    .dining-container .dining-detail-left .dining-table .list-title {
        width: 33%;
        position: relative;
    }
    .dining-container .dining-detail-left .dining-table .list-detail{
        width:67%;
        position: relative;
    }
    .dining-container .dining-detail-left p{
        margin-bottom:0.5rem;
    }
}
@media (max-width: 767.98px) {
    .dining-detail-right {
        margin-top: 60px;
    }
    .dining-detail-left .btn-container{
        text-align: center;
    }
    .dining-container .dining-detail-left .dining-table{
        width:60%;
        margin-bottom:1.5rem;
    }
    .dining-highlights-main {
        padding: 30px  0 10px;
    }
    .dining-container .dining-detail-left .dining-title{
        margin-bottom: 15px;
    }
    
    .dining-container .dining-detail-left p{
        margin-bottom:1rem;
        
    }
    .dining-highlights-main p{
        max-width:90%;
    }
   
}

@media (max-width: 575.98px) {
  
    .dining-container .dining-detail-left .detail-btn {
        width: 80%;
    }
    .dining-container .dining-detail-left .dining-table{
        width:100%;
    }
}
@media (max-width: 320px) {
    .dining-container .dining-detail-left .dining-table .list-title{width:37%;}
    .dining-container .dining-detail-left .dining-table .list-detail{width: 63%;}
}
@media (min-width: 768px) {
.dining-container .dining-detail-left .dining-btn {
    display: flex;
    justify-content: space-around;
}
}
@media (max-width: 767px) {
.dining-container .dining-detail-left .detail-btn {
    width: 80%;
    float: none;
    margin-bottom: 10px;
}
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
</style>
<section class="cms-page-container">
<div class="container">
                <div class="row justify-content-center dining-highlights-main">
                    <div class="col-12 col-md-12 align-center text-center">                        
                        <p class="mbr-section-subtitle align-center mbr-fonts-style pb-2 display-5">                            Indulge in a delightful dining experience                 </p>
                    </div>
                </div>
            </div>
<div class="dining-mission-main">
                <div class="dining-container">
                    <div class="row">
                        <div class="col-md-6 dining-detail-left">
                            <h3 class="dining-title">Bottle Tree Restaurant</h3>
                            <p>The Bottle Tree Restaurant @ SPOM is a halal-certified restaurant that offers a range of local and Western cuisines. The cozy dining environment and diverse menu make it an ideal destination for both casual meals and special celebrations. </p>
                            <table class="dining-table">
                                <tbody><tr>
                                    <td class="list-title">
                                        Open daily
                                    </td>
                                    <td class="list-detail">
                                        8am-5pm
                                    </td>
                                </tr>
                                <tr>
                                    <td class="list-title">
                                        Last order
                                    </td>
                                    <td class="list-detail">
                                        4:30pm
                                    </td>
                                </tr>
                            </tbody></table>
                            <div class="btn-container dining-btn">
                                <a class="detail-btn pull-left" href="/files/Assets/media/files/SPOM_TPB_Menu.pdf" target="_blank">Menu</a>
                                <a class="detail-btn pull-left" href="/files/Assets/media/files/Festive_Menu_TPB.pdf" target="_blank">Promotion</a>
                            </div>
                        </div>
                        <div class="col-md-6 dining-detail-right">
                            <div class="demo">
                                <div class="item">
                                    <div style="max-width:474px;margin: 0 auto;" class="clearfix">
                                        <div class="gallery">
                                        <input id="img-tab-1" name="select" checked="checked" type="radio">
                                        <label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/dining/thumb/dish-2-t.jpg);" for="img-tab-1"></label>
                                        <img border="0" src="/files/Assets/media/dining/dish-2.jpg">
                                        <input id="img-tab-2" name="select" type="radio">
                                        <label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/dining/thumbPlatter_BlackBG-t.jpg);" for="img-tab-2"></label>
                                        <img border="0" src="/files/Assets/media/dining/Platter_BlackBG.jpg">
                                        <input id="img-tab-3" name="select" type="radio">
                                        <label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/dining/thumb/Salmon_BlackBG-t.jpg);" for="img-tab-3"></label>
                                        <img border="0" src="/files/Assets/media/dining/Salmon_BlackBG.jpg">
                                        <input id="img-tab-4" name="select" type="radio">
                                        <label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/dining/thumb/dish-1-t.jpg);" for="img-tab-4"></label>
                                        <img border="0" src="/files/Assets/media/dining/dish-1.jpg">
																					<input id="img-tab-4" name="select" type="radio">
                                        <label style="background-image: url(https://staging.d193b78fy9jp3u.amplifyapp.com/files/Assets/media/dining/thumb/LobsterPorridge_BlackBG-t.jpg);" for="img-tab-4"></label>
                                        <img border="0" src="/files/Assets/media/dining/LobsterPorridge_BlackBG.jpg">
                                        </div>                                                                
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
</div>
</section>