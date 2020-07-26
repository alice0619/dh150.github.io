---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
        
<div id="slideshow">
<p class="active">
        <a href="searchbyprefecture.markdown"><img src="8D0BE253-069E-48F3-B903-DE002E58BF93-min.jpeg" width="500" height="300" alt=""></a>
                Tsunoshima Ohashi (Yamaguchi)</p>
        <p><a href="searchbyprefecture.markdown"><img src="94330D2F-2703-47D2-BA21-89AE2FFF84D5-min.jpeg" width="500" height="300" alt=""></a>
                Istukuma Jinja (Hiroshima)</p>
        <p><a href="searchbyprefecture.markdown"><img src="A54B0539-92DD-4828-A5D3-2D3123BD897B-min.jpeg" width="500" height="300" alt=""></a>
                Kanmon Kaikyo (Yamaguchi/Fukuoka)</p>
        <p><a href="searchbyprefecture.markdown"><img src="CD2C95F7-AF6B-4474-9980-AAA17B422D3E-min.jpeg" width="500" height="300" alt=""></a>
                Motonosumi Inari Jinja (Yamaguchi)</p>
</div>

<style type="text/css">
#slideshow {
   position: relative;
   width:  640px; /* ボックスの横幅 */
   height: 300px; /* ボックスの高さ */
}

#slideshow p {
   position: absolute;
   top:  0;
   left: 0;
   z-index: 8;
   opacity: 0.0;
   margin: 0;
   background-color: white; /* ボックスの背景色(必須) */
   height: 300px; /* ボックスの高さ */
}

#slideshow p.active {
   z-index: 10;
   opacity: 1.0;
}

#slideshow p.last-active {
   z-index: 9;
}

#slideshow p img {
   width:  640px; /* 画像の横幅 */
   height: 270px; /* 画像の高さ */
   display: block;
   border: 0;
   margin-bottom: 10px; /* 画像下部の余白 */
}
</style>
<script type="text/javascript">
function slideSwitch() {
   var $active = $('#slideshow p.active');

   if ( $active.length == 0 ) $active = $('#slideshow p:last');

   var $next =  $active.next().length ? $active.next()
      : $('#slideshow p:first');

   $active.addClass('last-active');

   $next.css({opacity: 0.0})
      .addClass('active')
      .animate({opacity: 1.0}, 1000, function() {
         $active.removeClass('active last-active');
      });
}

$(function() {
   setInterval( "slideSwitch()", 5000 );
});
</script>

<script src=""https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
										  

<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1rMVt1bc2Xd8mjDe3hJpEtVabljleHwMF" width="640" height="480"></iframe>
