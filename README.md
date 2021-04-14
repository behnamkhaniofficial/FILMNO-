<! doctype html>
<html ⚡4email>
<head>
  <meta charset = "utf-8">
  <script async src = "https://cdn.ampproject.org/v0.js"> </script>
  <script async custom-element = "amp-bind" src = "https://cdn.ampproject.org/v0/amp-bind-0.1.js"> </script>
  <script async custom-element = "amp-carousel" src = "https://cdn.ampproject.org/v0/amp-carousel-0.1.js"> </script>
 
  <style amp4email-boilerplate> body {visibility: hidden} </style>
  <style amp-custom>
    h1 {
    	font-family: arial؛
      	حاشیه: 10px؛
    }
    . مرکز {
		text-align: مرکز؛
    }
    پیش نمایش کاروسل {
      margin-top: 10px؛
    } 
  </style>
</head>
<بدنه>
	<amp-state id = "myState">
    <script type = "application / json">
      {"گربه ها": 
         [
           {
            "name": "آکاش" ،
            "description": "آقای بسیار نازنینی که در یک محیط پناهگاه کاملاً خجالتی است. ممکن است با نزدیک شدن اولیه در زیر پتو پنهان شود ، اما او یک حشره محبت است."
          } ،
          {
            "name": "فیلیپ" ،
            "description": "دوستانه و از حیوانات خانگی و مالش سر لذت می برد. معروف است که روی صفحه کلید می نشیند و از لمس هر چیزی با گربه روی آن امتناع می ورزد."
          } ،
          {
            "name": "جولیان" ،
            "description": "هم جسورانه و هم بسیار شیرین. در بررسی بوهای ، اشیا و مکانهای جدید وقت نمی گذارد ، اما از لق زدن در آفتاب لذت می برد!"
          } ،
          {
            "name": "جان" ،
            "description": "این گربه بازیگوش و روحیه دوست دارد در خارج از لانه پرورش خود باشد و هنگامی که به خانه ابدی خود با فضای بیشتری برای حرکت می رسد بسیار خوشحال خواهد شد."
          }
        ]
      }
    </script>
  </amp-state>
  </amp-state>
  <h1> حیوانات قابل قبول قابل قبول </ h1>
  <amp-carousel id = "چرخ فلک-با-پیش نمایش"
    عرض = "800"
    قد = "400"
    layout = "پاسخگو"
    نوع = "اسلایدها"
    روشن = "slideChange: AMP.setState ({currentCat: event.index})">
  <amp-img layout = "fill" src = "https://raw.githubusercontent.com/ampproject/docs/future/pages/static/img/docs/tutorials/firstemail/photo_by_caleb_woods.jpg" alt = "عکس با مجوز از Unsplash "> </amp-img>
  <amp-img layout = "fill" src = "https://raw.githubusercontent.com/ampproject/docs/future/pages/static/img/docs/tutorials/firstemail/photo_by_craig_mclaclan.jpg" alt = "عکس با مجوز از Unsplash "> </amp-img>
  <amp-img layout = "fill" src = "https://raw.githubusercontent.com/ampproject/docs/future/pages/static/img/docs/tutorials/firstemail/photo_by_lightscape.jpg" alt = "عکس با مجوز از Unsplash "> </amp-img>
  <amp-img layout = "fill" src = "https://raw.githubusercontent.com/ampproject/docs/future/pages/static/img/docs/tutorials/firstemail/photo_by_nick_karvounis.jpg" alt = "عکس با مجوز از Unsplash "> </amp-img>
 </amp-carousel>
  <div class = "center">
    <h1>
      <span [text] = "myState.cats [currentCat] .name"> آکاش </ span> برای تصویب در دسترس است!
    </ h1>
  </div>
  <p class = "center"> درباره <span [text] = "myState.cats [currentCat] .name"> آکاش </ span> </p>
  <p class = "center" [text] = "myState.cats [currentCat] .description"> آقای بسیار نازنینی که در یک محیط پناهگاهی کاملا خجالتی است. ممکن است با نزدیک شدن اولیه در زیر پتو پنهان شود ، اما او یک حشره محبت است. </ p>
</ body>
