---
title: Gallery Page 2
permalink: /gallery-1/
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
        background: url(/files/Assets/images/photo-gallery-bg.jpg) no-repeat center center !important;
        background-size: auto;
        background-size: cover !important;
        height: 338px !important;
    }
	/* Photo Gallery css */

.photo-gallery-main {
    background: url(/files/Assets/images/photo-gallery-bg.jpg) no-repeat center center;
    background-size: 100%;
}

.photo-gallery .photo-gallery-inner {
    padding: 0px 0 0px;
    width: 100%;
}

.photo-gallery-main .photo-gallery-inner .redeem-ttl {
    justify-content: center;
    width: 100%;
    display: flex;
    align-items: center;
}

@media (min-width: 1200px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 400px;
    }
}

@media (max-width: 992px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 338px;
    }
}

@media (max-width: 991.98px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 250px;
    }
}

@media (max-width: 767.98px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 200px;
    }
}

@media (max-width: 575.98px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 180px;
    }
}

@media (min-width: 1200px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 400px;
    }
}

@media (max-width: 1366px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 375px;
    }
}

@media (max-width: 1199.98px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 274px;
    }
}

@media (max-width: 991.98px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 205px;
    }
}

@media (max-width: 767.98px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 185px;
    }
}

@media (max-width: 575.98px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 122px;
    }
}

@media (max-width: 320px) {
    .photo-gallery-main .photo-gallery-inner .redeem-ttl {
        height: 90px;
    }
}

.photo-gallery-main .photo-gallery-inner h2 {
    color: #ffffff;
    font-size: 30px;
    font-family: "nowbold";
    text-shadow: -1px 1px 8px rgba(0, 0, 0, 0.3);
    text-align: center;
    padding-top: 0px;
}

@media (max-width: 767.98px) {
    .photo-gallery-main .photo-gallery-inner h2 {
        font-size: 20px;
    }
}

.photo-gallery-container {
    max-width: 890px;
    margin: 0 auto;
    padding: 0 15px;
}

.photo-gallery-container .photo-gallery-box {
    margin-bottom: 25px;
    height: 200px;
    overflow: hidden;
}

.photo-gallery-container .photo-gallery-box img {
    width: 100%;
    /* height:100%; */
}

.pagination {
    display: flex;
    justify-content: flex-end;
    margin-top: -10px;
}

@media (max-width: 991.98px) {
    .pagination {
        display: flex;
        justify-content: center;
    }
}

.nav-link {
    color: #414042 !important;
    margin-right: 10px !important;
    background-color: #ebe7e4 !important;
    border: 0 !important;
    border-radius: 0 !important;
}

.page-item {
    font-size: 18px !important;
    color: #414042 !important;
    font-weight: 600 !important;
    cursor: pointer !important;
}

.active-link {
    background: transparent !important;
    color: #414042 !important;
    border: 1px solid #ebe7e4 !important;
    margin-right: 10px !important;
    font-size: 18px !important;
    padding: 7px 14px !important;
}

.page-no {
    background-color: #fff !important;
    padding: .5rem 0 !important;
}

.page-link:focus {
    box-shadow: none !important;
    outline: 0 !important;
}

.photo-gallery-modal .modal-header {
    padding: 0.5rem !important;
    border: 0 !important;
}

.photo-gallery-modal .modal-body {
    width: 100%;
    overflow: hidden;
    text-align: center;
    position: relative;
    padding-top: 0 !important;
}

.modal.lightbox .modal-dialog {
    max-width: 1000px !important;
    position: relative;
    margin: 5rem auto !important;
}

.modal.lightbox .modal-content {
    margin: 0;
    border-radius: 0;
    width: 100%;
    max-width: 100%;
    height: 70vh;
    background-color: transparent !important;
    border: 0 !important;
}

.modal.lightbox .modal-body {
    height: 100vh;
    width: 100%;
    padding: 0;
    overflow: hidden;
}
	.pagination{display:-ms-flexbox !important;display:flex !important;padding-left:0 !important;list-style:none !important;border-radius:.25rem !important}
.page-link{position:relative !important;display:block !important;padding:.5rem .75rem !important;margin-left:-1px !important;line-height:1.25 !important;color:#007bff !important;background-color:#fff !important;border:1px solid #dee2e6 !important}
.page-link:hover{z-index:2 !important;color:#0056b3;text-decoration:none !important;background-color:#e9ecef !important;border-color:#dee2e6 !important}
.page-link:focus{z-index:3 !important;outline:0 !important;box-shadow:0 0 0 .2rem rgba(0,123,255,.25) !important}
.page-item:first-child .page-link{margin-left:0 !important;border-top-left-radius:.25rem !important;border-bottom-left-radius:.25rem !important}
.page-item:last-child .page-link{border-top-right-radius:.25rem !important;border-bottom-right-radius:.25rem !important}
.page-item.active .page-link{z-index:3 !important;color:#fff !important;background-color:#007bff !important;border-color:#007bff !important}
.page-item.disabled .page-link{color:#6c757d !important;pointer-events:none !important;cursor:auto !important;background-color:#fff !important;border-color:#dee2e6 !important}
.pagination-lg .page-link{padding:.75rem 1.5rem !important;font-size:1.25rem !important;line-height:1.5 !important}
.pagination-lg .page-item:first-child .page-link{border-top-left-radius:.3rem !important;border-bottom-left-radius:.3rem !important}
.pagination-lg .page-item:last-child .page-link{border-top-right-radius:.3rem !important;border-bottom-right-radius:.3rem !important}
.pagination-sm .page-link{padding:.25rem .5rem !important;font-size:.875rem !important;line-height:1.5 !important}
.pagination-sm .page-item:first-child .page-link{border-top-left-radius:.2rem !important;border-bottom-left-radius:.2rem !important}
.pagination-sm .page-item:last-child .page-link{border-top-right-radius:.2rem !important;border-bottom-right-radius:.2rem !important}
</style>
<section class="cms-page-container">
<div class="row justify-content-center abt-highlights-main">
                    <div class="col-12 col-md-12 align-center text-center">
                        <p class="mbr-section-subtitle align-center mbr-fonts-style pb-2 display-5">
                            Reminisce the joyous moments!
                        </p>
                     </div>
                    <div class="photo-gallery-container popup-gallery">
                        <div class="row">                           
                            <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
                                <div class="photo-gallery-box">
                                    <a target="_blank" href="/files/Assets/media/gallery/photo-gallery-preview-6.png">
                                        <img src="/files/Assets/media/gallery/photo-gallery-6.png">
                                    </a>                                   
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
                                <div class="photo-gallery-box">
                                    <a target="_blank" href="/files/Assets/media/gallery/photo-gallery-preview-3.png">
                                        <img src="/files/Assets/media/gallery/photo-gallery-3.png">
                                    </a>                                   
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
                                <div data-target="#mymodal" data-toggle="modal" class="photo-gallery-box">
                                    <a target="_blank" href="/files/Assets/media/gallery/photo-gallery-preview-9.png">
                                        <img src="/files/Assets/media/gallery/photo-gallery-9.png">
                                    </a>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
                                <div class="photo-gallery-box">
                                    <a target="_blank" href="/files/Assets/media/gallery/photo-gallery-preview-2.png">
                                        <img src="/files/Assets/media/gallery/photo-gallery-2.png">
                                    </a>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
                                <div class="photo-gallery-box">
                                    <a target="_blank" href="/files/Assets/media/gallery/photo-gallery-preview-4.png">
                                        <img src="/files/Assets/media/gallery/photo-gallery-4.png">
                                    </a>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
                                <div class="photo-gallery-box">
                                    <a href="/files/Assets/media/gallery/photo-gallery-preview-1.png">
                                        <img src="/files/Assets/media/gallery/photo-gallery-1.png">
                                    </a>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
                                <div class="photo-gallery-box">
                                    <a target="_blank" href="/files/Assets/media/gallery/photo-gallery-preview-7.png">
                                        <img src="/files/Assets/media/gallery/photo-gallery-7.png">
                                    </a>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
                                <div class="photo-gallery-box">
                                    <a target="_blank" href="/files/Assets/media/gallery/photo-gallery-preview-9.png">
                                        <img src="/files/Assets/media/gallery/photo-gallery-9.png">
                                    </a>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
                                <div class="photo-gallery-box">
                                    <a target="_blank" href="/files/Assets/media/gallery/photo-gallery-preview-8.png">
                                        <img src="/files/Assets/media/gallery/photo-gallery-8.png">
                                    </a>
                                </div>
                            </div>
                        </div>
                        <nav aria-label="...">
                            <ul class="pagination">
                              <li class="page-item">
                                <a href="/gallery" class="page-link nav-link"> Page 1 </a>
                              </li>       
                            </ul>
                          </nav>
                    </div>
</div>
</section>