---
title: Facility
permalink: /facility/
description: ""
---
<style type="text/css">.bp-section-pagetitle {
        background: url(/files/Assets/images/facility-bg.jpg) no-repeat center center !important;
        background-size: auto;
        background-size: 100% !important;
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
  background: #fff;
  color: #1ABC9C;
}
.clear-backend > input:checked + span + i {
  color: #1ABC9C;
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
  background: #f0f0f0;
  display: block;
  width: 200px;
  height: 60px;
  line-height: 60px;
  text-align: center;
  z-index: 9;
}
.tab-content {
  position: absolute;
  top: 0;
  right: 0;
  width: calc(100% - 200px);
  height: 100%;
  padding-top: 60px;
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
</style>
<div class="container">
<div class="clear-backend">
<input type="radio" class="tab-1" name="tab" checked="checked">
<span>Home</span><i class="fa fa-home"></i>
<input type="radio" class="tab-2" name="tab">
<span>Posts</span><i class="fa fa-medium"></i>
<input type="radio" class="tab-3" name="tab">
<span>Users</span><i class="fa fa-user"></i>
<input type="radio" class="tab-4" name="tab">
<span>Comments</span><i class="fa fa-comment"></i>
<div class="tab-content">
  <section class="tab-item-1">
    <div id="event-space" class="tabcontent facility-tab-content">
          <div class="facility-media">
            <div class="demo">
              <div class="item">
                <div class="clearfix" style="max-width:474px;margin: 0 auto;">
                  <section class="gallery">
                    <div class="gallery__item">
                      <input class="gallery__selector" name="gallery" checked="" id="img-1" type="radio">
                      <img alt="" src="/files/Assets/media/facility/KTVPrivateRoom.jpg" class="gallery__img">
                      <label class="gallery__thumb" for="img-1">
                        <img alt="" src="/files/Assets/media/facility/KTVPrivateRoom.jpg">
                      </label>
                    </div>
                    <div class="gallery__item">
                      <input class="gallery__selector" name="gallery" id="img-2" type="radio">
                      <img alt="" src="/files/Assets/media/facility/KTVLounge.jpg" class="gallery__img">
                      <label class="gallery__thumb" for="img-2">
                        <img alt="" src="/files/Assets/media/facility/KTVLounge.jpg">
                      </label>
                    </div>
                    <div class="gallery__item">
                      <input class="gallery__selector" name="gallery" id="img-3" type="radio">
                      <img alt="" src="/files/Assets/media/facility/ChaletRooms.jpg" class="gallery__img">
                      <label class="gallery__thumb" for="img-3">
                        <img alt="" src="/files/Assets/media/facility/ChaletRooms.jpg">
                      </label>
                    </div>
                  </section>
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
                  <section class="gallery2">
                    <div class="gallery2__item">
                      <input class="gallery2__selector" name="gallery" checked="" id="img2-1" type="radio">
                      <img alt="" src="/files/Assets/media/facility/Bar&amp;Dinning.jpg" class="gallery2__img">
                      <label class="gallery2__thumb" for="img2-1">
                        <img alt="" src="/files/Assets/media/facility/Bar&amp;Dinning.jpg">
                      </label>
                    </div>
                    <div class="gallery2__item">
                      <input class="gallery2__selector" name="gallery" id="img2-2" type="radio">
                      <img alt="" src="/files/Assets/media/facility/BBQPits.jpg" class="gallery2__img">
                      <label class="gallery2__thumb" for="img2-2">
                        <img alt="" src="/files/Assets/media/facility/BBQPits.jpg">
                      </label>
                    </div>
                  </section>
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
                  <ul id="image-gallery-meeting" class="gallery list-unstyled cS-hidden">
                    <li data-thumb="/files/Assets/media/facility/Foyer.jpg">
                      <img class="slider-image" src="/files/Assets/media/facility/Foyer.jpg">
                      <div class="caption">
                        <p>Foyer</p>
                      </div>
                    </li>
                  </ul>
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
                  <ul id="image-gallery-leisure" class="gallery list-unstyled cS-hidden">
                    <li data-thumb="/files/Assets/media/facility/Gymnasium.jpg">
                      <img class="slider-image" src="/files/Assets/media/facility/Gymnasium.jpg">
                      <div class="caption">
                        <p>Gymnasium</p>
                      </div>
                    </li>
                    <li data-thumb="/files/Assets/media/facility/thumbs/Dartboard.jpg" width="100%">
                      <img class="slider-image" src="/files/Assets/media/facility/Dartboard.jpg">
                      <div class="caption">
                        <p>Dartboard</p>
                      </div>
                    </li>
                    <li data-thumb="/files/Assets/media/facility/FoosballTable.jpg">
                      <img class="slider-image" src="/files/Assets/media/facility/FoosballTable.jpg">
                      <div class="caption">
                        <p>Foosball Table</p>
                      </div>
                    </li>
                  </ul>
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
  </section>
</div>
</div>
	<div class="row justify-content-center facility-highlights-main">
                    <div class="col-12 col-md-12 align-center">
                        <h3 class="facility-type-title">Type of facility</h3>                       
                        <div class="row">
                             <div class="col-12 col-md-4 col-lg-3 facility-left">
                                <div class="tab facility-nav">
                                    <button class="tablinks" id="defaultOpen">Event Space</button>
                                    <button class="tablinks">Dining Rooms</button>
                                    <button class="tablinks">Meeting Rooms</button>
                                    <button class="tablinks">Leisure</button>
                                  </div>                                
                             </div>                            
                             <div class="col-12 col-md-8 col-lg-9 facility-right">
                                <div id="event-space" class="tabcontent facility-tab-content">
                                    <div class="facility-media">
                                        <div class="demo">
                                            <div class="item">
                                                <div class="clearfix" style="max-width:474px;margin: 0 auto;">																									 
<section class="gallery">
  <div class="gallery__item">
    <input class="gallery__selector" name="gallery" checked="" id="img-1" type="radio">
    <img alt="" src="/files/Assets/media/facility/KTVPrivateRoom.jpg" class="gallery__img">
    <label class="gallery__thumb" for="img-1"><img alt="" src="/files/Assets/media/facility/KTVPrivateRoom.jpg"></label>
  </div>
  <div class="gallery__item">
    <input class="gallery__selector" name="gallery" id="img-2" type="radio">
    <img alt="" src="/files/Assets/media/facility/KTVLounge.jpg" class="gallery__img">
    <label class="gallery__thumb" for="img-2"><img alt="" src="/files/Assets/media/facility/KTVLounge.jpg"></label>
  </div>
  <div class="gallery__item">
    <input class="gallery__selector" name="gallery" id="img-3" type="radio">
    <img alt="" src="/files/Assets/media/facility/ChaletRooms.jpg" class="gallery__img">
    <label class="gallery__thumb" for="img-3"><img alt="" src="/files/Assets/media/facility/ChaletRooms.jpg"></label>
  </div>
</section>                                                    
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="facility-type-details">
                                        <h3 class="facility-title">Event Space</h3>
                                        <p>
                                            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
                                        </p>
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
                                                <td class="facility-price data-right"><span class="dollor-sign">$</span>50 / 4hrs</td>
                                                
                                              </tr>
                                              <tr>
                                              
                                                <td class="facility-name even-data-left">Dining Hall  <br> <span>(Incl. free use of Foyer
                                                    )</span></td>
                                                <td class="facility-price even-data-right"><span class="dollor-sign">$</span>150 / day</td>
                                             
                                              </tr>
                                              <tr>
                                              
                                                <td class="facility-name data-left">Foyer <br> <span>(Free with booking
                                                    of Dining hall)</span>
                                                    </td>
                                                <td class="facility-price data-right"> <span class="dollor-sign">$</span>30 / 4hrs </td>
                                                
                                              </tr>
                                              <tr>
                                                  <td class="facility-name even-data-left">
                                                    Lawn
                                                  </td>
                                                  <td class="facility-price even-data-right">
                                                    <span class="dollor-sign">$</span>20 /day
                                                  </td>
                                              </tr>
                                            
                                            </tbody>
                                          </table>
                                    </div>
                                  </div>
                                  
                                  <div id="dining" class="tabcontent facility-tab-content">
                                    <div class="facility-media">
                                        <div class="demo">
                                            <div class="item">
                                                <div class="clearfix" style="max-width:474px;margin: 0 auto;">
																									<section class="gallery2">
  <div class="gallery2__item">
    <input class="gallery2__selector" name="gallery" checked="" id="img2-1" type="radio">
    <img alt="" src="/files/Assets/media/facility/Bar&amp;Dinning.jpg" class="gallery2__img">
    <label class="gallery2__thumb" for="img2-1"><img alt="" src="/files/Assets/media/facility/Bar&amp;Dinning.jpg"></label>
  </div>
  <div class="gallery2__item">
    <input class="gallery2__selector" name="gallery" id="img2-2" type="radio">
    <img alt="" src="/files/Assets/media/facility/BBQPits.jpg" class="gallery2__img">
    <label class="gallery2__thumb" for="img2-2"><img alt="" src="/files/Assets/media/facility/BBQPits.jpg"></label>
  </div>
</section>                                                    
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="facility-type-details">
                                        <h3 class="facility-title">Dining Rooms</h3>
                                        <p>
                                            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
                                        </p>
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
                                                <td class="facility-price even-data-right"><span class="dollor-sign">$</span>40 / 4hrs</td>
                                                
                                              </tr>
                                              
                                              </tbody>
                                            </table>
                                       
                                    </div>
                                  </div>
                                  
                                  <div id="meeting" class="tabcontent facility-tab-content">
                                    <div class="facility-media">
                                        <div class="demo">
                                            <div class="item">
                                                <div class="clearfix" style="max-width:474px;margin: 0 auto;">
                                                    <ul id="image-gallery-meeting" class="gallery list-unstyled cS-hidden">
                                                        
                                                        <li data-thumb="/files/Assets/media/facility/Foyer.jpg">
                                                            <img class="slider-image" src="/files/Assets/media/facility/Foyer.jpg">
                                                            <div class="caption">
                                                                <p>Foyer</p>
                                                            </div>
                                                        </li>
                                                        
                                                       
                                                     </ul>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="facility-type-details">
                                        <h3 class="facility-title">Meeting Rooms</h3>
                                        <p>
                                            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
                                        </p>
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
                                                <td class="facility-price data-right"><span class="dollor-sign">$</span>20 / 4hrs</td>
                                                
                                              </tr>
                                              <tr>
                                              
                                                <td class="facility-name even-data-left">Games Room</td>
                                                <td class="facility-price even-data-right"><span class="dollor-sign">$</span>20 / 4hrs</td>
                                                
                                              </tr>
                                              <tr>
                                              
                                                <td class="facility-name data-left">Library</td>
                                                <td class="facility-price data-right"><span class="dollor-sign">$</span>20 / 4hrs</td>
                                                
                                              </tr>
                                              
                                              </tbody>
                                            </table>
                                    </div>
                                  </div>
                                  <div id="leisure" class="tabcontent facility-tab-content">
                                    <div class="facility-media">
                                        <div class="demo">
                                            <div class="item">
                                                <div class="clearfix" style="max-width:474px;margin: 0 auto;">
                                                    <ul id="image-gallery-leisure" class="gallery list-unstyled cS-hidden">
                                                        
                                                        <li data-thumb="/files/Assets/media/facility/Gymnasium.jpg">
                                                            <img class="slider-image" src="/files/Assets/media/facility/Gymnasium.jpg">
                                                          
                                                            <div class="caption">
                                                                <p>Gymnasium</p>
                                                            </div>
                                                        </li>
                                                        <li data-thumb="/files/Assets/media/facility/thumbs/Dartboard.jpg" width="100%">
                                                            <img class="slider-image" src="/files/Assets/media/facility/Dartboard.jpg">
                                                            <div class="caption">
                                                                <p>Dartboard</p>
                                                            </div>
                                                        </li>
                                                        <li data-thumb="/files/Assets/media/facility/FoosballTable.jpg">
                                                            <img class="slider-image" src="/files/Assets/media/facility/FoosballTable.jpg">
                                                            <div class="caption">
                                                                <p>Foosball Table</p>
                                                            </div>
                                                        </li>
                                                       
                                                     </ul>
                                                </div>
                                            </div>
                                        </div> 
                                    </div>
                                    <div class="facility-type-details">
                                        <h3 class="facility-title">Leisure</h3>
                                        <p>
                                            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.

                                            
                                        </p>
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
                                                <td class="facility-price data-right"><span class="dollor-sign">$</span>7.50 / hr</td>
                                                
                                              </tr>
                                              <tr>
                                              
                                                <td class="facility-name even-data-left">KTV - Private Room</td>
                                                <td class="facility-price even-data-right"> <span class="dollor-sign">$</span>10 / 2hrs</td>
                                             
                                              </tr>
                                              <tr>
                                              
                                                <td class="facility-name data-left">KTV - Lounge</td>
                                                <td class="facility-price data-right"> <span class="dollor-sign">$</span>40 / 2hrs</td>
                                                
                                              </tr>
                                              <tr>
                                                  <td class="facility-name even-data-left">
                                                    Chalest <br> <span>(incl. free use of BBQ Pits)</span>
                                                  </td>
                                                  <td class="facility-price even-data-right">
                                                    <span class="dollor-sign">$</span>40 / day
                                                  </td>
                                              </tr>
                                              <tr>
                                                  <td class="facility-name data-left">
                                                    BBQ Pits <br><span>(Free with booking of Chalet)</span>
                                                  </td>
                                                  <td class="facility-price data-right"> <span class="dollor-sign">$</span>10 / day</td>
                                              </tr>
                                            </tbody>
                                          </table>
                                    </div>
                                  </div>
                             </div>
                            
                            </div>
                        </div>

                    </div>
            </div>
