---
title: Dining
permalink: /dining/
description: ""
---
<style type="text/css">.bp-section-pagetitle {
        background: url(/files/Assets/images/dining-bg.jpg) no-repeat center center !important;
        background-size: auto;
        background-size: 100% !important;
        height: 338px !important;
    }
$max-img-width: 600px;
$max-img-height: 400px;
img {
  max-width: 100%;
  vertical-align: top;
}
.gallery {
  display: flex;
    margin: 10px auto;
    max-width: $max-img-width;
    position: relative;
    padding-top: $max-img-height/$max-img-width * 100%;    
    @media screen and (min-width: $max-img-width){
      padding-top: $max-img-height;
    }  
  &__img {
    position: absolute;
    top: 0;
    left: 0;
    opacity: 0;
    transition: opacity 0.3s ease-in-out;
  }  
   &__thumb {
    padding-top: 6px;
    margin: 6px;
    display: block;
  }  
  &__selector {
    position: absolute;
    opacity: 0;
    visibility: hidden;    
    &:checked {
      + .gallery__img {
        opacity: 1;
      }
      ~ .gallery__thumb > img {
        box-shadow: 0 0 0 3px #0be2f6;;
      }
    }
  } 
}
</style>
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
                            <h3 class="dining-title">The Peak Bistro</h3>
                            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make
                                a type specimen book. </p>
                            <p>It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the</p>
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
                                        <section class="gallery">
  <div class="gallery__item">
    <input class="gallery__selector" name="gallery" checked="" id="img-1" type="radio">
    <img alt="" src="/files/Assets/media/dining/dine-1.jpg" class="gallery__img">
    <label class="gallery__thumb" for="img-1"><img alt="" src="/files/Assets/media/dining/thumb/dine-thumb-1.jpg"></label>
  </div>
  <div class="gallery__item">
    <input class="gallery__selector" name="gallery" id="img-2" type="radio">
    <img alt="" src="/files/Assets/media/dining/dine-2.jpg" class="gallery__img">
    <label class="gallery__thumb" for="img-2"><img alt="" src="/files/Assets/media/dining/thumb/dine-thumb-2.jpg"></label>
  </div>
  <div class="gallery__item">
    <input class="gallery__selector" name="gallery" id="img-3" type="radio">
    <img alt="" src="/files/Assets/media/dining/dine-3.jpg" class="gallery__img">
    <label class="gallery__thumb" for="img-3"><img alt="" src="/files/Assets/media/dining/thumb/dine-thumb-3.jpg"></label>
  </div>
  <div class="gallery__item">
    <input class="gallery__selector" name="gallery" id="img-4" type="radio">
    <img alt="" src="/files/Assets/media/dining/dine-4.jpg" class="gallery__img">
    <label class="gallery__thumb" for="img-4"><img alt="" src="/files/Assets/media/dining/thumb/dine-thumb-4.jpg"></label>
  </div>
</section>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
</div>