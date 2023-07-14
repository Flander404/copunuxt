<template>

<!DOCTYPE html>
<html lang="ru">
   
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>
        MEALHUB    </title>
	<meta name="description" content="MEALHUB"/>
	
    <link href="https://mealhub.info/favicon.ico" rel="icon" type="image/x-icon" />	
	<link rel="apple-touch-icon" sizes="180x180" href="https://mealhub.info/apple-touch-icon.png">
	<link rel="icon" type="image/png" sizes="32x32" href="https://mealhub.info/favicon-32x32.png">
	<link rel="icon" type="image/png" sizes="192x192" href="https://mealhub.infoandroid-chrome-192x192.png">
	<link rel="icon" type="image/png" sizes="16x16" href="https://mealhub.info/favicon-16x16.png">
	<link rel="manifest" href="https://mealhub.info/site.webmanifest">
	<link rel="mask-icon" href="https://mealhub.info/safari-pinned-tab.svg" color="#2d89ef">
	<meta name="apple-mobile-web-app-title" content="MEALHUB">
	<meta name="application-name" content="MEALHUB">
	<meta name="msapplication-TileColor" content="#2d89ef">
	<meta name="msapplication-TileImage" content="/mstile-144x144.png">
	<meta name="theme-color" content="#ffffff">

	<meta property="og:type" content="website">
	<meta property="og:site_name" content="http://mealhub.info/">
	<meta property="og:title" content="MEALHUB">
	<meta property="og:description" content="MEALHUB">
	<!-- <meta property="og:url" content="https://meal-hub.ru/"> -->
	<meta property="og:locale" content="ru_RU">
	<meta property="og:image" content="https://mealhub.info/images/preview.png">
	<meta property="og:image:width" content="968">
	<meta property="og:image:height" content="504">

	<meta name="twitter:card" content="summary_large_image">
	<meta name="twitter:title" content="MEALHUB">
	<meta name="twitter:description" content="MEALHUB">
	<meta name="twitter:image:src" content="https://mealhub.info/images/preview.png">
	<!-- <meta name="twitter:url" content="https://meal-hub.ru/"> -->
	<!-- <meta name="twitter:domain" content="meal-hub.ru/"> -->

	<!-- <link rel="manifest" href="/manifest.json"> -->
	<!-- <link rel="stylesheet" href="https://mealhub.info/css/animate.css"> -->
	<!-- <link rel="stylesheet" href="https://mealhub.info/css/glide.core.min.css"> -->
	<!-- <link rel="stylesheet" href="https://mealhub.info/css/glide.theme.min.css"> -->

	<link rel="stylesheet" href="https://mealhub.info/css/splide.min.css">
	<link rel="stylesheet" href="https://mealhub.info/css/splide-default.min.css">
	<link rel="stylesheet" href="https://mealhub.info/css/custom_slider.css">

	<link rel="stylesheet" href="https://mealhub.info/css/style.css?v2.961">
	<link rel="stylesheet" href="https://mealhub.info/css/mobile.css?v2.8">
	<link rel="stylesheet" href="https://mealhub.info/css/animation.css">

</head>	
<body>
		<main class="bigBackground">


<nav id="nav" class="navbar nav" role="navigation">
    <a href="/">
        <div class="logo"></div>
    </a>
    
    
    <ul class="nav__menu navbarLinks" id="menu" tabindex="-1" aria-label="main navigation" hidden>
        <a href="/">
            Всем        </a>
        <a href="/catering">
            Ресторанам        </a>
     
        <a href="/news/">
            Новости        </a>
        <a href="/team">
            Команда        </a>
        <div class="dropdown">
            <button class="dropbtn" onclick="myFunction()" id="myDropdownBtn">
                ru                <svg class="dropbtn-nav-arrow" width="14" height="8" viewBox="0 0 14 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M13 7L7 1L1 7" stroke="#2B2B2B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>

            </button>
            <div class="dropdown-content" id="myDropdown">
                <a href="?lang=en">en</a>
                <a href="?lang=ru">ru</a>
                <a href="?lang=ee">ee</a>
                <a href="?lang=ch">ch</a>
                <a href="?lang=lv">lv</a>
                <a href="?lang=am">am</a>
                <a href="?lang=ara">ara</a>
                <a href="?lang=gre">gre</a>
                <a href="?lang=tr">tr</a>
                <a href="?lang=fr">fr</a>
                <a href="?lang=geo">geo</a>
            </div>
        </div> 
    </ul>

    <a href="#nav" class="nav__toggle" role="button" aria-expanded="false" aria-controls="menu">
  
    <div class="menu-open-btn">
        <svg width="30" height="16" viewBox="0 0 30 16" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M30 15C30 15.5523 29.4404 16 28.75 16L1.25 16C0.559645 16 7.15256e-07 15.5523 7.15256e-07 15C7.15256e-07 14.4477 0.559645 14 1.25 14L28.75 14C29.4404 14 30 14.4477 30 15Z" fill="#4F4F4F"/>
            <path fill-rule="evenodd" clip-rule="evenodd" d="M30 8C30 8.55228 29.4404 9 28.75 9L6.25 9C5.55965 9 5 8.55228 5 8C5 7.44772 5.55965 7 6.25 7L28.75 7C29.4404 7 30 7.44772 30 8Z" fill="#4F4F4F"/>
            <path fill-rule="evenodd" clip-rule="evenodd" d="M30 1C30 1.55228 29.4404 2 28.75 2L1.25 2C0.559645 2 0 1.55228 0 1C0 0.447715 0.559645 0 1.25 0L28.75 0C29.4404 0 30 0.447715 30 1Z" fill="#4F4F4F"/>
        </svg>

    </div>
    <svg class="menuicon menuicon__bar-closeBtn" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#4F4F4F"/>
    </svg>

    </a>
    <div class="splash"></div>
    
</nav>
<section id="screen_1">
    <div class="screen_1-wrapper">
        <div class="screen_1-wrapper-left"></div>
        <div class="screen_1-wrapper-right"></div>
    </div>
    <div class="screen_1">
        <div class="screen_1-actionBlock">
            <p>
                MEALHUB. <span class="gradient-text">Food in touch.</span><br> ТАМ, ГДЕ ВЫ хотите ЕСТЬ            </p>
            <div class="screen_2-subHeader">
                Крупнейший ресторанный концентратор, а также уникальный сервис по предоставлению всех ресторанных услуг онлайн.
	Рестораны, кафе, бары, уличная еда, кофейни, пельменные на любой вкус и кошелек, далеко и близко, новые и популярные, большие и маленькие, сетевые и исключительные – все готовы начать готовить для вас уже в тот момент, когда вы только нажали несколько кнопок на своем телефоне или компьютере            </div>
        </div>
        <div class="screen_1-btnBar">
            <a href="https://mealhub.group/#signup" target="_blank" class="btn-pink">
                Зарегистрироваться            </a>
            <div class="app-btn-container">
                <a href="/" class="apple-btn-svg" onclick="currentSlide(event,11, false)">
                    <img src="https://mealhub.info/images/apple-btn-svg.svg" alt="">
                </a>
                <a href="/" class="google-btn-svg" onclick="currentSlide(event,11, false)">
                    <img src="https://mealhub.info/images/google-btn-svg.svg" alt="">
                </a>
            </div>
        </div>
    </div>
    <div class="screen_1-chat">
        <div>
            <div class="screen_1-chat-white">
                <p class="typing-text">
                    Где поесть балтийской корюшки в Новосибирске?                </p>
                
            </div>
        </div>
       <div>
            <!-- <div class="screen_1-chat-yellow">
                Уже ищем!            </div> -->
            <a href="https://mealhub.group/#signup" target="_blank" class="screen_1-chat-yellow">
                Уже ищем!            </a>
       </div>
    </div>
</section><section id="screen_2">
    <div class="container">
        <div class="screen_2-header">
            <div>
                <span class="gradient-text">MEALHUB.USERS это:</span>            </div>
        </div>
        <div class="screen_2-subHeader">
            <div>
                MEALHUB.USERS поможет найти подходящий именно вам и именно в данный конкретный момент ресторан в любой стране мира.
									Благодаря умному поиску, вы сможете найти заведение, максимально удовлетворяющее вас по параметрам
	            </div>
        </div>
        <div class="splide" id="splide_1">
            <div data-splide-el="track" class="splide__track">
                <div class="splide__list">
                    <div class="splide__slide">
                        <div class="screen_2-item">
                            <div>
                                <img src="https://mealhub.info/images/screen_2-item_1.png" alt="">
                            </div>
                            <div class="screen_2-item-text">
                                С MEALHUB.USERS вы можете забронировать для себя стол в любом ресторане любого города любой страны мира. А можете даже и не для себя!                            </div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_2-item">
                            <div>
                                <img src="https://mealhub.info/images/screen_2-item_2.png" alt="">
                            </div>
                            <div class="screen_2-item-text">
                                В MEALHUB.USERS вы можете ознакомиться с интерьером заведений, с их рейтингом, с отзывами других гостей, посмотреть фотографии блюд, почитать меню, оформить доставку, заказать блюда на вынос и даже сделать заказ блюд к определенному часу! И все это в одном месте, и не покидая своего дома или офиса!                            </div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_2-item">
                            <div>
                                <img src="https://mealhub.info/images/screen_2-item_3.png" alt="">
                            </div>
                            <div class="screen_2-item-text">
                                В MEALHUB.USERS вы можете оплатить свой заказ картой, а также из любого кошелька из любой точки мира. И еще вы можете передумать – тогда мы вернем вам деньги!                            </div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_2-item">
                            <div>
                                <img src="https://mealhub.info/images/screen_2-item_4.png" alt="">
                            </div>
                            <div class="screen_2-item-text">
                                С MEALHUB.USERS вы можете выбрать заведение, подходящее вам для проведения любого мероприятия и сразу же сделать предварительный заказ. MEALHUB.USERS – это единственный на сегодня многофункциональный сайт и приложение для любых заказов из ресторанов сразу и онлайн!                            </div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_2-item">
                            <div>
                                <img src="https://mealhub.info/images/screen_2-item_5.png" alt="">
                            </div>
                            <div class="screen_2-item-text">
                                С MEALHUB.USERS вы не будете ждать свой заказ, скучая за столиком и теряя свое драгоценное время. С MEALHUB.USERS ваш заказ будет вас ждать: ароматный, свежий, горячий, аппетитный, абсолютно готовый и весь ваш!	С MEALHUB.USERS вам останется только пройти за стол и сразу начать есть!                            </div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_2-item">
                            <div>
                                <img src="https://mealhub.info/images/screen_2-item_6.png" alt="">
                            </div>
                            <div class="screen_2-item-text">
                                С MEALHUB.USERS вы будете экономить свое время каждый день, где бы вы ни были! Благодаря MEALHUB.USERS от 20 минут до двух-трех часов в день остаются вашим личным временем! За время, проведенное в ожидании обеда, вы сможете закончить работу и прийти домой раньше. За время, проведенное в ожидании ужина, вы посмотрите новую серию любимого сериала! Это ваше личное время, которое мы освободили для вас – делайте с ним, что хотите!                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- <div class="splide__bullets" data-splide-el="controls[nav]">
                <button class="splide__bullet" data-splide-dir="=0"></button>
                <button class="splide__bullet" data-splide-dir="=1"></button>
                <button class="splide__bullet" data-splide-dir="=2"></button>
                <button class="splide__bullet" data-splide-dir="=3"></button>
                <button class="splide__bullet" data-splide-dir="=4"></button>
                <button class="splide__bullet" data-splide-dir="=5"></button>
            </div> -->
        </div>
        <!-- <div class="screen_2-items-wrapper">
            <div class="screen_2-item">
                <div>
                    <img src="https://mealhub.info/images/screen_2-item_1.png" alt="">
                </div>
                <div class="screen_2-item-header">
                    <br />
<b>Warning</b>:  Undefined array key "index_screen_2_item_1_header" in <b>/appprod/components/index/screen_2.php</b> on line <b>93</b><br />
                </div>
                <div class="screen_2-item-text">
                    С MEALHUB.USERS вы можете забронировать для себя стол в любом ресторане любого города любой страны мира. А можете даже и не для себя!                </div>
            </div>
            <div class="screen_2-item screen_2-item-toBottom">
                <div>
                    <img src="https://mealhub.info/images/screen_2-item_2.png" alt="">
                </div>
                <div class="screen_2-item-header">
                    <br />
<b>Warning</b>:  Undefined array key "index_screen_2_item_2_header" in <b>/appprod/components/index/screen_2.php</b> on line <b>104</b><br />
                </div>
                <div class="screen_2-item-text">
                    В MEALHUB.USERS вы можете ознакомиться с интерьером заведений, с их рейтингом, с отзывами других гостей, посмотреть фотографии блюд, почитать меню, оформить доставку, заказать блюда на вынос и даже сделать заказ блюд к определенному часу! И все это в одном месте, и не покидая своего дома или офиса!                </div>
            </div>
            <div class="screen_2-item">
                <div>
                    <img src="https://mealhub.info/images/screen_2-item_3.png" alt="">
                </div>
                <div class="screen_2-item-header">
                    <br />
<b>Warning</b>:  Undefined array key "index_screen_2_item_3_header" in <b>/appprod/components/index/screen_2.php</b> on line <b>115</b><br />
                </div>
                <div class="screen_2-item-text">
                    В MEALHUB.USERS вы можете оплатить свой заказ картой, а также из любого кошелька из любой точки мира. И еще вы можете передумать – тогда мы вернем вам деньги!                </div>
            </div>
            <div class="screen_2-item screen_2-item-toBottom">
                <div>
                    <img src="https://mealhub.info/images/screen_2-item_4.png" alt="">
                </div>
                <div class="screen_2-item-header">
                    <br />
<b>Warning</b>:  Undefined array key "index_screen_2_item_4_header" in <b>/appprod/components/index/screen_2.php</b> on line <b>126</b><br />
                </div>
                <div class="screen_2-item-text">
                    С MEALHUB.USERS вы можете выбрать заведение, подходящее вам для проведения любого мероприятия и сразу же сделать предварительный заказ. MEALHUB.USERS – это единственный на сегодня многофункциональный сайт и приложение для любых заказов из ресторанов сразу и онлайн!                </div>
            </div>
        </div> -->
        <!-- <div class="screen_2_phone">
            <div>
                <div class="screen_2_phone-header gradient-text">
                MEALHUB.USERS
                </div>
                <div class="screen_2_phone-subHeader">
                    Многофункциональный сервис, который позволяет:                </div>
                <div class="screen_2_phone-text">
                    Ознакомиться с интерьером заведений, с их рейтингом, отзывами других гостей, посмотреть фотографии блюд, почитать меню, оформить доставку, заказать блюда на вынос и даже сделать заказ блюд к определенному часу!                </div>
            </div>
        </div> -->
    </div>
</section><section id="screen_3">
    <div class="container">
        <div class="screen_3-pink">
            <div class="screen_3-pink-content">
                 <div class="screen_3-header">
                    GO MEAL                </div>
                <div class="screen_3-text">
                    Благодаря сервису «GO MEAL» вы делаете заказ блюд в ресторане онлайн, из дома или офиса, в дороге или же прямо по пути в ресторан, что сокращает практически до нуля время ожидания блюд в самом ресторане                </div>
                <div class="screen_3-searchBlock">
                    <a href="https://mealhub.group/#signup" target="_blank" class="gradient-btn">
                        Зарегистрироваться                    </a>
                    <!-- <a href="https://mealhub.group/#signup" target="_blank" class="screen_3-search-btn">
                        Зарегистрироваться                    </a> -->
                </div>
            </div>
           <div class="screen_3-pink-pic">
               <img src="https://mealhub.info/images/screen_3-pink-pic.png" alt="">
           </div>
        </div>
        <div class="header_with_link">
            <div>
                <div class="screen_3-header">
                    Мы объединили ваши <span class="gradient-text">любимые сервисы</span> и сделали их доступными в <span class="gradient-text">одном приложении</span>                </div>
                <div class="screen_3-text">
                    Теперь доставка, бронь стола и даже организация банкета<br>стали доступны в несколько кликов                </div>
            </div>
            <div>
                <a href="/services/" class="catalog_link">
                    <div>
                        Подробнее о сервисах MealHub                    </div>
                    <div class="separator"></div>
                </a>
            </div>
        </div>
       
    </div>
</section><section class="screen_4">
    <div class="screen_4-klyaksa"></div>
    <div class="container">
        <div class="screen_4-flex flex-reverse">
            <div>
                <div class="screen_4-title">
                    GO MEAL
                </div>
                <div class="screen_4-text">
                    Сервис дает возможность выбрать заведения, расположенные рядом с вами и предоставляющие данную услугу, в моменте забронировать в подходящем именно вам заведении стол до шести человек включительно, выбрать сколько угодно блюд из меню, оплатить заказ, сразу же получить уведомление о времени его приготовления, а далее только ждать сообщения о его готовности!
	<br><br>С сервисом «GO MEAL» вы сможете практически до минуты рассчитать свое время и не потратить ни одну из них впустую!                </div>
                <!-- <button class="btn-pink" onclick="currentSlide(1)">
                    Узнать подробнее
                </button> -->
                <a href="/services/go_meal" class="btn-pink">
                    Узнать больше                </a>
            </div>
            <div>
                <img src="https://mealhub.info/images/screen_4_pic_1.png" alt="" style="width: 100%; max-width: 431px">
            </div>
        </div>
        <div class="screen_4-flex">
            <div>
                <img src="https://mealhub.info/images/screen_4_pic_2.png" alt="" style="width: 100%; max-width: 313px">
            </div>
            <div>
                <div class="screen_4-title">
                TAKE-OUT MEAL
                </div>
                <div class="screen_4-text">
                    Сервис «TAKE-OUT MEAL» позволяет сделать заказ в любом заведении и забрать его самостоятельно. Казалось бы – ничего нового, но мы пошли дальше и сделали возможность спланировать заказ заранее.
	<br><br>
	В этом сервисе вы можете предварительно, за неделю запланировать себе романтический ужин или день рождения, выбрать подходящий день и время для того, чтобы забрать ваш готовый заказ                </div>
                <!-- <button class="btn-pink" onclick="currentSlide(2)">
                    Узнать подробнее
                </button> -->
                <a href="/services/take-out_meal" class="btn-pink">
                    Узнать больше                </a>
            </div>
        </div>
    </div>
</section><section class="screen_4">
    <div class="screen_5-klyaksa"></div>
    <div class="container">
        <div class="screen_4-flex flex-reverse">
            <div>
                <div class="screen_4-title">
                DELIVER MEAL
                </div>
                <div class="screen_4-text">
                    Мы сделали все, чтобы ваши любимые блюда доставляли вам по любому адресу,
                                            в удобное время и из любого заведения. 
                                            <br><br>
                                            Редактируйте условия доставки под себя: выбирайте заведения с 
                                            быстрой или только с бесплатной доставкой, выбирайте заведения 
                                            по рейтингу или кухне, по месторасположению и отзывам о доставке                </div>
                <!-- <button class="btn-pink" onclick="currentSlide(3)">
                    Узнать подробнее
                </button> -->
                <a href="/services/deliver_meal" class="btn-pink">
                    Узнать больше                </a>
            </div>
            <div>
                <img src="https://mealhub.info/images/screen_5_pic_1.png" alt="" style="width: 100%; max-width: 396px">
            </div>
        </div>
        <div class="screen_4-flex">
            <div>
                <img src="https://mealhub.info/images/screen_5_pic_2.png" alt="" style="width: 100%; max-width: 323px">
            </div>
            <div>
                <div class="screen_4-title">
                BOOK MEAL
                </div>
                <div class="screen_4-text">
                    Бронируйте и выбирайте нужный стол самостоятельно!
										Вы выбираете заведение, дату, время, зал в заведении, стол, 
										указываете необходимое количество гостей. 
										<br><br>
										Также вы можете выбрать повод, по которому  планируете провести 
										время в заведении и оставить пожелания к своей брони                </div>
                <!-- <button class="btn-pink" onclick="currentSlide(4)">
                    Узнать подробнее
                </button> -->
                <a href="/services/book_meal" class="btn-pink">
                    Узнать больше                </a>
            </div>
        </div>
    </div>
</section><section class="screen_4">
    <div class="screen_6-klyaksa"></div>
    <div class="container">
        <div class="screen_4-flex flex-reverse">
            <div>
                <div class="screen_4-title">
                PRE-ORDER MEAL
                </div>
                <div class="screen_4-text">
                    Сервис «PRE-ORDER MEAL» позволяет вам к уже забронированному вами столу самостоятельно сделать заказ блюд и, конечно же, не приходя специально для этого в выбранное заведение.
											<br><br>
											В самое подходящее для вас время, хоть глубокой ночью, вы можете внимательно и не спеша изучить все меню заведения                </div>
                <!-- <button class="btn-pink" onclick="currentSlide(5)">
                    Узнать подробнее
                </button> -->
                <a href="/services/pre-order_meal" class="btn-pink">
                    Узнать больше                </a>
            </div>
            <div>
                <img src="https://mealhub.info/images/screen_6_pic_1.png" alt="" style="width: 100%; max-width: 430px">
            </div>
        </div>
        <div class="screen_4-flex">
            <div>
                <img src="https://mealhub.info/images/screen_6_pic_2.png" alt="" style="width: 100%; max-width: 364px">
            </div>
            <div>
                <div class="screen_4-title">
                MEAL COST
                </div>
                <div class="screen_4-text">
                    Рассчитайте все затраты на банкет самостоятельно онлайн с банкетным калькулятором MEAL COST.
										<br><br>
										С его помощью вы можете заранее просчитать стоимость банкета, 
										в зависимости от того, в каком заведении он будет проходить, 
										сколько человек у вас планируется на мероприятии и какой планируется формат мероприятия                </div>
                <!-- <button class="btn-pink" onclick="currentSlide(6)">
                    Узнать подробнее
                </button> -->
                <a href="/services/meal_cost" class="btn-pink">
                    Узнать больше                </a>
            </div>
        </div>
    </div>
</section><section id="screen_7">
    <div class="container">
        <div class="header_with_link">
            <div>
                <div class="screen_3-header">
                        <span class="gradient-text">KARMA.HUB</span><br><br>
                    Заботясь о <span class="gradient-text">«хлебе насущном»</span> для вас, мы не могли не позаботиться и о <span class="gradient-text">вашей душе</span>                </div>
                <div class="screen_3-text">
                    У нас есть целый раздел, посвященный социальным проектам и благотворительности и, конечно же, он напрямую связан с нашей деятельностью – с ресторанными услугами и с заведениями, размещенными на нашем сайте.
								<br><br>
								Чтобы было легко понять, какие заведения участвуют в благотворительных
								и социально направленных мероприятиях, мы создали специальные
								иконки-обозначения в виде небольших изображений нашей планеты. <img src="https://mealhub.info/images/planet.png" alt="">
								По ним вы сможете легко ориентироваться среди всех заведений
								и понимать, в каких проектах они задействованы
								<br><br>
								Одна планета – одно доброе дело!                </div>
            </div>
            <div>
                <a href="/karma/" class="catalog_link">
                    <div>
                        Подробнее о благотворительных акциях                    </div>
                    <div class="separator"></div>
                </a>
            </div>
        </div>
        <!-- <div class="screen_7-cards-block"> -->
        <div class="splide" id="splide_2">
            <div class="splide__track">
                <div class="splide__list">
                    <div class="splide__slide">
                        <div class="screen_7-card">
                            <div>
                                <div class="screen_7-card-planets-block">
                                    <div class="screen_7-card-planet"></div>
                                </div>
                                <div class="screen_7-card-title">
                                    HUNG MEAL
                                </div>
                                <div class="screen_7-card-text">
                                    Наш вариант всемирно известной итальянской благотворительной 
								акции CAFFE SOSPESO. Заказывая кофе для себя, вы можете оплатить 
								одну или более чашек кофе для нуждающихся                                </div>
                                <!-- <button class="btn-pink">
                                    Узнать подробнее
                                </button> -->
                                <a href="/karma/hung_meal" class="btn-pink">
                                    Узнать больше                                </a>
                            </div>
                            <div class="screen_7-card-img_1"></div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_7-card">
                            <div>
                                <div class="screen_7-card-planets-block">
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                </div>
                                <div class="screen_7-card-title">
                                    HALF PRICE MEAL
                                </div>
                                <div class="screen_7-card-text">
                                    Проект, которвый позволяет всем
										желающим приобрести любые
										блюда в заведении со скидкой 50 %
										от первоначальной стоимости и более                                </div>
                                <!-- <button class="btn-pink">
                                    Узнать подробнее
                                </button> -->
                                <a href="/karma/half-price_meal" class="btn-pink">
                                    Узнать больше                                </a>
                            </div>
                            <div class="screen_7-card-img_2"></div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_7-card">
                            <div>
                                <div class="screen_7-card-planets-block">
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                </div>
                                <div class="screen_7-card-title">
                                    FREE MEAL
                                </div>
                                <div class="screen_7-card-text">
                                    Мы создали сервис, благодаря которому
								нуждающиеся люди могут получать еду
								совершенно бесплатно. Все что нужно -
								лишь ваше желание помочь                                </div>
                                <!-- <button class="btn-pink">
                                    Узнать подробнее
                                </button> -->
                                <a href="/karma/free_meal" class="btn-pink">
                                    Узнать больше                                </a>
                            </div>
                            <div class="screen_7-card-img_3"></div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_7-card">
                            <div>
                                <div class="screen_7-card-planets-block">
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                </div>
                                <div class="screen_7-card-title">
                                GIFT MEAL
                                </div>
                                <div class="screen_7-card-text">
                                    Мы знаем, как важно внимание,
								особенно для тех, кто, в силу обстоятельств,
								часто лишен его. Наш благотворительный
								проект GIFT MEAL направлен именно
								на оказание знаков внимания,
								в виде «съедобных подарков»                                </div>
                                <!-- <button class="btn-pink">
                                    Узнать подробнее
                                </button> -->
                                <a href="/karma/gift_meal" class="btn-pink">
                                    Узнать больше                                </a>
                            </div>
                            <div class="screen_7-card-img_4"></div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_7-card">
                            <div>
                                <div class="screen_7-card-planets-block">
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                </div>
                                <div class="screen_7-card-title">
                                CHARITY MEAL
                                </div>
                                <div class="screen_7-card-text">
                                    Организация благотворительных ужинов
								для пожилых людей, ветеранов, людей,
								с ограниченными  возможностями или для
								детей из малоимущих семей и детей сирот                                </div>
                                <!-- <button class="btn-pink">
                                    Узнать подробнее
                                </button> -->
                                <a href="/karma/charity_meal" class="btn-pink">
                                    Узнать больше                                </a>
                            </div>
                            <div class="screen_7-card-img_5"></div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_7-card">
                            <div>
                                <div class="screen_7-card-planets-block">
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                </div>
                                <div class="screen_7-card-title">
                                CARE HUB
                                </div>
                                <div class="screen_7-card-text">
                                    Проект, который позволяет людям,
								с ограниченными возможностями
								не испытывать никаких ограничений,
								находясь в заведении общественного питания                                </div>
                                <!-- <button class="btn-pink">
                                    Узнать подробнее
                                </button> -->
                                <a href="/karma/care_hub" class="btn-pink">
                                    Узнать больше                                </a>
                            </div>
                            <div class="screen_7-card-img_6"></div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_7-card">
                            <div>
                                <div class="screen_7-card-planets-block">
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                    <div class="screen_7-card-planet"></div>
                                </div>
                                <div class="screen_7-card-title">
                                RECYCLING HUB
                                </div>
                                <div class="screen_7-card-text">
                                    Мы знаем, как много стекла, пластика 
									и картона остается в заведениях после рабочего дня.
									Поэтому мы взяли на себя ответственность помочь заведениям 
									общественного питания наладить организованный сбыт продуктов для вторичной переработки                                </div>
                                <!-- <button class="btn-pink">
                                    Узнать подробнее
                                </button> -->
                                <a href="/karma/recycling_hub" class="btn-pink">
                                    Узнать больше                                </a>
                            </div>
                            <div class="screen_7-card-img_7"></div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_7-card">
                            <div>
                                <div class="screen_7-card-planets-block">
                                </div>
                                <div class="screen_7-card-title">
                                GOOD HUB
                                </div>
                                <div class="screen_7-card-text">
                                    Проект, в котором принимают
								участие заведения, которые готовы
								участвовать в благотворительной
								деятельности. Любая помощь имеет
								значение!                                </div>
                                <!-- <button class="btn-pink">
                                    Узнать подробнее
                                </button> -->
                                <a href="/karma/good_hub" class="btn-pink">
                                    Узнать больше                                </a>
                            </div>
                            <div class="screen_7-card-img_8"></div>
                        </div>
                    </div>
                    <div class="splide__slide">
                        <div class="screen_7-card">
                            <div>
                                <div class="screen_7-card-planets-block">
                                </div>
                                <div class="screen_7-card-title">
                                HELP HUB
                                </div>
                                <div class="screen_7-card-text">
                                    Проект ориентирован на любую помощь
								близким людям – людям, находящимся
								рядом территориально                                </div>
                                <!-- <button class="btn-pink">
                                    Узнать подробнее
                                </button> -->
                                <a href="/karma/help_hub" class="btn-pink">
                                    Узнать больше                                </a>
                            </div>
                            <div class="screen_7-card-img_9"></div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- <div class="glide__bullets" data-glide-el="controls[nav]">
                <button class="glide__bullet" data-glide-dir="=0"></button>
                <button class="glide__bullet" data-glide-dir="=1"></button>
                <button class="glide__bullet" data-glide-dir="=2"></button>
                <button class="glide__bullet" data-glide-dir="=3"></button>
                <button class="glide__bullet" data-glide-dir="=4"></button>
                <button class="glide__bullet" data-glide-dir="=5"></button>
                <button class="glide__bullet" data-glide-dir="=6"></button>
                <button class="glide__bullet" data-glide-dir="=7"></button>
                <button class="glide__bullet" data-glide-dir="=8"></button>
            </div> -->
        </div>
    </div>
</section><section id="screen_3">
    <div class="container">
        <div class="screen_8-yellow">
            <div class="screen_8-yellow-content">
                <div class="screen_3-header">
                    Участвовать в благотворительности<br>и делать добрые дела c MealHub стало проще!                </div>
                <div class="screen_3-text">
                    На сегодняшний день мы смогли реализовать на своей платформе уже более 7 социально важных проектов, которые напрямую связаны с нашей деятельностью - с ресторанными услугами и с заведениями,	размещенными на нашем сайте                </div>
            </div>
            <div>
                <img src="https://mealhub.info/images/screen_8-pic.png" alt="" style="width: 100%">
            </div>
            <!-- <div class="screen_3-searchBlock">
                <button class="screen_3-search-btn">
                    Хочу помогать
                </button>
            </div> -->
        </div>
        <div class="screen_3-header">
            Мы позаботились о том, чтобы <span class="gradient-text">доступ к сервису</span> <span class="gradient-text">был удобным</span> для каждого пользователя        </div>
        <div class="screen_3-text">
            Поэтому в личном кабинете вы можете обратиться к нам за помощью и решить любой свой вопрос. Мы работаем, чтобы сделать ваш опыт взаимодействия с сервисом проще        </div>
    </div>
</section><section id="screen_9">
    <div class="container">
        <div class="screen_9-block">
            <div class="screen_9-card">
                <div class="screen_9-card-title">Mealhub Info</div>
                <div class="screen_9-card-text">
                    Благодаря настраиваемому радиусу, вы можете видеть на сайте только то, что хотите видеть. Умный поиск и объемная база данных откроют вам доступ не только к фотографиям заведений и их описаниям, но еще и к полному меню каждого ресторана и кафе. В личном кабинете вы всегда можете посмотреть всю информацию о своих заказах, включая вашу личную статистику по ним                </div>
            </div>
            <div class="screen_9-card">
                <div class="screen_9-card-title">Mealhub Search</div>
                <div class="screen_9-card-text">
                    С помощью автоматического определения вашего местоположения и настраиваемому радиусу поиска, вы всегда будете окружены только тем, что вам интересно. Ищите заведения на карте, по названию, по кухне, среднему чеку, рейтингу, отзывам и наличию дополнительных услуг. Кроме того, можно отсортировать, например, только новые заведения или же только те заведения, которые осуществляют доставку                </div>
            </div>
        </div>
        <div class="screen_9-block">
            <div class="screen_9-card">
                <div class="screen_9-card-title">Mealhub Consulting</div>
                <div class="screen_9-card-text">
                    MEALHUB – это огромная команда, работающая круглосуточно, которая готова прийти на помощь и ответить на любые ваши вопросы в режиме реального времени. Наш приоритет - ваш положительный опыт сотрудничества с нами, а через нас – со всем окружающим вас кулинарным миром                </div>
            </div>
            <div class="screen_9-card">
                <div class="screen_9-card-title">Mealhub Statistic</div>
                <div class="screen_9-card-text">
                    В этом разделе вы сможете следить за своими расходами, анализировать их, планировать бюджет, исходя из своих предпочтений, видеть свои заказы, своих «фаворитов» среди заведений, знать, что вы чаще заказываете и даже отcлеживать потраченные суммы на разные категории блюд и напитков!                </div>
            </div>
        </div>
        <div class="screen_9_mobile-man">
            <img src="https://mealhub.info/images/screen_9-bg.png" style="width: 100%" alt="">
        </div>
    </div>
    
</section><section id="screen_10">
    <div class="container">
        <div class="screen_10-purple">
            <div class="screen_10-purple-content">
                <div class="screen_10-header">
                    Регистрируйетсь на сайте MealHub и получайте доступ к огромному количеству ресторанов по всему миру                </div>
                <div class="screen_3-searchBlock">
                    <!-- <input type="text" name="name" class="screen_10-input" placeholder="Имя">
                    <input type="phone" name="phone" class="screen_10-input" placeholder="Номер телефона">
                    <input type="email" name="email" class="screen_10-input" placeholder="E-mail">
                    <div style="width: 100%;">
                        <button class="screen_3-search-btn">
                            Зарегистрироваться                        </button>
                    </div> -->
                    <a href="https://mealhub.group/#signup" target="_blank" class="screen_3-search-btn">
                        Зарегистрироваться                    </a>
                </div>
            </div>
            
            <div>
                <img src="https://mealhub.info/images/screen_10-pic-2.png" alt="" style="width: 100%">
            </div>
        </div>
    </div>
</section><section>
    <div class="container">
        <div class="screen_3-header">
            Ваши любимые рестораны <span class="gradient-text">стали ближе</span>        </div>
        <div class="screen_3-text">
            Приложение MealHub позволяет получить доступ ко всем<br>
	ресторанам в нужном радиусе и по заданным параметрам,<br>
	а также осуществить множество дополнительных функций онлайн        </div>
        <div class="screen_11-block">
            <div>
                <img class="screen_11-img" src="https://mealhub.info/images/screen_11-pic.png" alt="">
            </div>
            <div class="screen_11-info-block">
                <div class="screen_11-block-title">
                    MEALHUB.USERS
                </div>
                <div class="screen_11-block-text">
                    MEALHUB.USERS – это самый полный каталог ресторанных услуг онлайн.                </div>
                <div class="screen_11-block-text">
                    Только в MEALHUB.USERS можно получить все услуги одновременно и в одном месте.                </div>
                <div class="screen_11-block-text">
                    И только в MEALHUB.USERS можно получить любую услугу полностью от начала и до конца прямо на сайте.                </div>
                <div class="screen_11-block-text">
                    Мы хотели реализовать возможность получения любой услуги удаленно, только при помощи сайта, не покидая своего настоящего местоположения, не прибегая к поисковым платформам, не совершая звонков по телефону и не назначая личных встреч и, мы уверены, у нас получилось!                </div>
                <div class="screen_11-block-APPtext">
                    Уже доступно в AppStore и GooglePlay                </div>
                <!-- <div class="screen_11-block-APPbtn">
                    <a href="#">
                        <img src="https://mealhub.info/images/appstore.png" alt="" style="width: 90%;">
                    </a>
                    <a href="#">
                        <img src="https://mealhub.info/images/googleplay.png" alt="" style="width: 90%;">
                    </a>
                </div> --> 
                <div class="app-btn-container">
                    <a href="/" class="apple-btn-svg" onclick="currentSlide(event,11, false)">
                        <img src="https://mealhub.info/images/apple-btn-svg.svg" alt="">
                    </a>
                    <a href="/" class="google-btn-svg" onclick="currentSlide(event,11, false)">
                        <img src="https://mealhub.info/images/google-btn-svg.svg" alt="">
                    </a>
                </div>
            </div>
        </div>
    </div>
</section>		</main>
		<footer>
    <div class="container">
        <div class="screen_1-wrapper">
            <div class="footer-logo">
            </div>
            <div style="margin-top:10px">
                <div class="dropdown">
                    <button class="dropbtn-footer" onclick="myFunctionFooter()" id="myDropdownBtn-footer">
                        <div class="dropbtn-footer-ancor" style="display: flex;align-items: center">
                        
                            <img class="dropbtn-footer-ancor" src="https://mealhub.info/images/lang_icon/ru.png" alt="" style="margin-right: 10px">                            <!-- <img class="dropbtn-footer-ancor" src="https://mealhub.info/images/lang_icon/us.png" alt="" style="margin-right: 10px"> -->
                            <span class="dropbtn-footer-ancor">
                                Русский                            </span>
                        </div>
                        
                        <svg class="dropbtn-nav-arrow" width="14" height="8" viewBox="0 0 14 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M13 7L7 1L1 7" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>

                    </button>
                    <div class="dropdown-content-footer" id="myDropdown-footer">
                        <a href="?lang=en">
                            <div style="display: flex;align-items: center">
                                <img src="https://mealhub.info/images/lang_icon/us.png" alt="" style="margin-right: 10px">
                                <span>
                                    English
                                </span>
                            </div>
                        </a>
                        <a href="?lang=ru">
                            <div style="display: flex;align-items: center">
                                <img src="https://mealhub.info/images/lang_icon/ru.png" alt="" style="margin-right: 10px">
                                <span>
                                    Русский
                                </span>
                            </div>
                        </a>
                        <a href="?lang=ee">
                            <div style="display: flex;align-items: center">
                                <img src="https://mealhub.info/images/lang_icon/ee.png" alt="" style="margin-right: 10px">
                                <span>
                                    Eesti
                                </span>
                            </div>
                        </a>
                        <a href="?lang=ch">
                            <div style="display: flex;align-items: center">
                                <img src="https://mealhub.info/images/lang_icon/cn.png" alt="" style="margin-right: 10px">
                                <span>
                                    中国人
                                </span>
                            </div>
                        </a>
                        <a href="?lang=lv">
                            <div style="display: flex;align-items: center">
                                <img src="https://mealhub.info/images/lang_icon/lv.png" alt="" style="margin-right: 10px">
                                <span>
                                    Latviski
                                </span>
                            </div>
                        </a>
                        <a href="?lang=am">
                            <div style="display: flex;align-items: center">
                                <img src="https://mealhub.info/images/lang_icon/am.png" alt="" style="margin-right: 10px">
                                <span>
                                    Hայերեն
                                </span>
                            </div>
                        </a>
                        <a href="?lang=ara">
                            <div style="display: flex;align-items: center">
                                <img src="https://mealhub.info/images/lang_icon/ae.png" alt="" style="margin-right: 10px">
                                <span>
                                عرب 
                                </span>
                            </div>
                        </a>
                        <a href="?lang=gre">
                            <div style="display: flex;align-items: center">
                                <img src="https://mealhub.info/images/lang_icon/gr.png" alt="" style="margin-right: 10px">
                                <span>
                                Ελληνικά
                                </span>
                            </div>
                        </a>
                        <a href="?lang=tr">
                            <div style="display: flex;align-items: center">
                                <img src="https://mealhub.info/images/lang_icon/tr.png" alt="" style="margin-right: 10px">
                                <span>
                                Türk
                                </span>
                            </div>
                        </a>
                        <a href="?lang=geo">
                            <div style="display: flex;align-items: center">
                                <img src="https://mealhub.info/images/lang_icon/ge.png" alt="" style="margin-right: 10px">
                                <span>
                                    ქართული
                                </span>
                            </div>
                        </a>
                        <a href="?lang=fr">
                            <div style="display: flex;align-items: center">
                                <img src="https://mealhub.info/images/lang_icon/fr.png" alt="" style="margin-right: 10px">
                                <span>
                                    Français
                                </span>
                            </div>
                        </a>
                    </div>
                </div> 
            </div>

        </div>
        <hr style="background-color: #F2F2F2; opacity: .5; margin: 10px 0 30px">
        <div class="footer-top-block">
            <div class="footer-middle-block">
                <div class="footer-top-block-middle">
                    <div>
                        <a href="#" class="footer-bold-link">
                            О Компании                        </a>
                        <a href="/news/" class="footer-link">
                            Новости                        </a>
                        <!-- <a href="/vacancy" class="footer-link">
                            Вакансии                        </a> -->
                        <a href="/team" class="footer-link">
                            Команда                        </a>
                        </a>
                        <a href="/offices" class="footer-link">
                            Офисы                        </a>
                    </div>
                    <div>
                        <a href="/" class="footer-bold-link">
                            Пользователям                        </a>
                        <a href="/services/" class="footer-link">
                            Сервисы MealHub                        </a>
                        <a href="/karma/" class="footer-link">
                            Karma Hub
                        </a>
                    </div>
                    <div>
                        <a href="/catering" class="footer-bold-link">
                            Ресторанам                        </a>
                        <a href="/catering_services/" class="footer-link">
                            Сервисы MealHub                        </a>
                        <a href="/catering_lk/" class="footer-link">
                            Личный кабинет                        </a>
                        <a href="/catering_tarifs/" class="footer-link">
                            Тарифы                        </a>
                    </div>
                    <div>
                        <a href="/partners" class="footer-bold-link">
                            Партнёрам                        </a>
                        <a href="/catering_services/" class="footer-link">
                            Сервисы MealHub                        </a>
                    </div>
                    <div>
                        <a href="/couriers" class="footer-bold-link">
                            Курьерам                        </a>
                        <a href="/catering_services/" class="footer-link">
                            Сервисы MealHub                        </a>
                    </div>
                    <div>
                        <div style="font-size: 16px; margin-bottom: 74px">
                            Подписывайтесь, чтобы всегда<br>оставаться на связи                        </div>
                        <form action="" id="footer_form">
                            <input type="email" name="email" placeholder="E-mail" class="footer-input" required>
                            <input type="hidden" name="lang" value="ru">
                            <input type="hidden" name="utm_source" value="landing">
                            <button>
                                <svg width="27" height="22" viewBox="0 0 27 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M16.5521 20.9753C16.3586 21.1723 16.0421 21.1752 15.845 20.9818C15.648 20.7883 15.6451 20.4718 15.8385 20.2747L24.4537 11.5L1.34375 11.5C1.06761 11.5 0.84375 11.2761 0.84375 11C0.84375 10.7239 1.06761 10.5 1.34375 10.5L24.4537 10.5L15.8385 1.72529C15.6451 1.52825 15.648 1.21168 15.845 1.01822C16.0421 0.824755 16.3586 0.82766 16.5521 1.02471L26.0021 10.6497C26.1931 10.8442 26.1931 11.1558 26.0021 11.3503L16.5521 20.9753Z" fill="white"/>
                                </svg>
                            </button>
                        </form>
                        
                    </div>
                </div>
            </div>

            <hr style="background-color: #F2F2F2; opacity: .5; margin: 10px 0 30px">
            
            <div class="footer-middle-block">
                <div>
                    <!-- <div class="footer-bold-link">
                        Мы в соцсетях                    </div> -->
                    <div class="footer-social">
                        <a href="#">
                            <img src="https://mealhub.info/images/youtube-icon.png" alt="">
                        </a>
                        <a href="#">
                            <img src="https://mealhub.info/images/tg-icon.png" alt="">
                        </a>
                        <a href="#">
                            <img src="https://mealhub.info/images/ya-icon.png" alt="">
                        </a>
                        <a href="#">
                            <img src="https://mealhub.info/images/vk-icon.png" alt="">
                        </a>
                    </div>
                </div>
                <!-- <div class="footer-logo-wrapper">
                    <div class="footer-logo">
                    </div>
                    <div style="margin-top:10px">
                        <a href="/policy" class="footer-copyright">
                            Политика конфиденциальности                        </a>
                    </div>
                </div> -->
                <div class="footer-copyright footer-copyright-block">
                    Copyright © Meal Hub 2023 Все права защищены                </div>
                <div style="margin-top:10px" class="footer-copyright-block">
                    <a href="/policy" class="footer-copyright">
                        Политика конфиденциальности                    </a>
                </div>
           </div>
        </div>
        <!-- <div class="footer-bottom-block">
            <div class="footer-copyright">
                Copyright © Meal Hub 2023 Все права защищены            </div>
        </div> -->
    </div>
</footer><div class="modal-wrapper" style="display: none;">
    <div class="modal">
        <div class="modal-close-btn">
            <button onclick="closeModal()">
                <svg height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
        <div class="modal-flex">
            <div class="modal-img">
                <img src="https://mealhub.info/images/screen_4_pic_1.png" alt="" style="width: 100%; max-width: 431px">
            </div>
            <div style="max-width: 550px;">
                <div class="modal-header">
                GO MEAL
                </div>
                <div>
                    <p class="modal-text">
                    Абсолютно новая услуга на рынке ресторанных услуг, позволяющая экономить самый драгоценный ресурс современности – время! 
                    <br><br>
                    Благодаря сервису GO MEAL вы делаете заказ блюд в ресторане онлайн, из дома или офиса, в дороге или прямо по пути 
                    в ресторан. Так время ожидания блюд в самом ресторане сокращается практически до нуля!
                    <br><br>
                    Сервис дает возможность выбрать понравившееся заведение рядом с вами, забронировать стол до 6 человек, выбрать нужное количество блюд из меню, оплатить заказ, сразу же получить уведомление о времени его приготовления, а далее только ждать сообщения о его готовности! 
                    <br><br>
                    С сервисом GO MEAL вы сможете практически до минуты рассчитать свое время и не потратить ни одну из них впустую! 
                    К вашему приходу в ресторане уже будет накрыт стол, и ваш заказ будет ждать вас, а не вы его. 
                    </p>
                </div>
                <div>
                    <button class="btn-pink">
                        Хочу сделать заказ
                    </button>
                </div>
            </div>
        </div>
        <div class="modal-bottom-bar">
            <button onclick="minusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0001 1C8.16351 1 1 8.16351 1 17.0001C1 25.8368 8.16351 33.0003 17.0001 33.0003C25.8368 33.0003 33.0003 25.8368 33.0003 17.0001C33.0003 8.16351 25.8368 1 17.0001 1ZM0 17.0001C0 7.61122 7.61122 0 17.0001 0C26.3891 0 34.0003 7.61122 34.0003 17.0001C34.0003 26.3891 26.3891 34.0003 17.0001 34.0003C7.61122 34.0003 0 26.3891 0 17.0001ZM17.354 10.0468C17.5493 10.2421 17.5493 10.5587 17.354 10.7539L11.6079 16.5H23.6005C23.8766 16.5 24.1005 16.7239 24.1005 17C24.1005 17.2761 23.8766 17.5 23.6005 17.5H11.607L17.354 23.247C17.5493 23.4422 17.5493 23.7588 17.354 23.9541C17.1587 24.1493 16.8422 24.1493 16.6469 23.9541L10.0468 17.354C9.94909 17.2563 9.90028 17.1281 9.90039 17M10.0597 16.6341L16.6469 10.0468C16.8422 9.85157 17.1587 9.85157 17.354 10.0468M9.9004 16.9972C9.90118 16.8538 9.96231 16.7248 10.0597 16.6341L9.9004 16.9972Z" fill="#4F4F4F"/>
                </svg>
            </button>
            <button onclick="plusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0004 33C25.837 33 33.0005 25.8365 33.0005 16.9999C33.0005 8.16332 25.837 0.999836 17.0004 0.999836C8.16382 0.999836 1.00034 8.16332 1.00034 16.9999C1.00034 25.8365 8.16382 33 17.0004 33ZM34.0005 16.9999C34.0005 26.3888 26.3893 34 17.0004 34C7.61153 34 0.000339508 26.3888 0.000339508 16.9999C0.000339508 7.61103 7.61153 -0.000164032 17.0004 -0.000164032C26.3893 -0.000164032 34.0005 7.61103 34.0005 16.9999ZM16.6475 23.9531C16.4522 23.7579 16.4522 23.4413 16.6475 23.246L22.3944 17.5L10.402 17.5C10.1258 17.5 9.90199 17.2761 9.90199 17C9.90199 16.7239 10.1258 16.5 10.402 16.5L22.3952 16.5L16.6475 10.7531C16.4522 10.5579 16.4522 10.2413 16.6475 10.046C16.8427 9.85074 17.1593 9.85072 17.3546 10.046L23.9556 16.646C24.0109 16.7013 24.0519 16.7682 24.0763 16.8411C24.0932 16.8917 24.1021 16.9452 24.1021 16.9996C24.1021 16.9997 24.1021 16.9999 24.1021 17C24.1021 17.1443 24.0409 17.2744 23.9431 17.3657L17.3546 23.9532C17.1593 24.1484 16.8427 24.1484 16.6475 23.9531Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
    </div>
    <div class="modal">
        <div class="modal-close-btn">
            <button onclick="closeModal()">
                <svg height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
        <div class="modal-flex">
            <div class="modal-img">
                <img src="https://mealhub.info/images/screen_4_pic_2.png" alt="" style="width: 100%; max-width: 313px">
            </div>
            <div style="max-width: 550px;">
                <div class="modal-header">
                TAKE-OUT MEAL
                </div>
                <div>
                    <p class="modal-text">
                    Сервис TAKE-OUT MEAL позволяет сделать заказ в любом заведении и забрать его самостоятельно.
                    Казалось бы – 
                    ничего нового, но мы пошли дальше и сделали возможность спланировать заказ заранее. 
                    <br><br>
                    В этом сервисе вы можете предварительно, за неделю запланировать себе романтический ужин или день рождения, выбрать подходящий день и время для того, чтобы забрать ваш готовый заказ.
                    <br><br>
                    Всю неделю вам не надо будет думать о том, где заказать готовую еду для вашего домашнего мероприятия, а главное – как найти для этого время!
                    <br><br>
                    После оформления заказа в разделе TAKE-OUT MEAL вы можете больше не вспоминать о нем – в день получения заказа вам заранее придет напоминание о заказе и о времени, к которому он будет готов!
                    </p>
                </div>
                <div>
                    <button class="btn-pink">
                        Хочу сделать заказ
                    </button>
                </div>
            </div>
        </div>
        <div class="modal-bottom-bar">
            <button onclick="minusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0001 1C8.16351 1 1 8.16351 1 17.0001C1 25.8368 8.16351 33.0003 17.0001 33.0003C25.8368 33.0003 33.0003 25.8368 33.0003 17.0001C33.0003 8.16351 25.8368 1 17.0001 1ZM0 17.0001C0 7.61122 7.61122 0 17.0001 0C26.3891 0 34.0003 7.61122 34.0003 17.0001C34.0003 26.3891 26.3891 34.0003 17.0001 34.0003C7.61122 34.0003 0 26.3891 0 17.0001ZM17.354 10.0468C17.5493 10.2421 17.5493 10.5587 17.354 10.7539L11.6079 16.5H23.6005C23.8766 16.5 24.1005 16.7239 24.1005 17C24.1005 17.2761 23.8766 17.5 23.6005 17.5H11.607L17.354 23.247C17.5493 23.4422 17.5493 23.7588 17.354 23.9541C17.1587 24.1493 16.8422 24.1493 16.6469 23.9541L10.0468 17.354C9.94909 17.2563 9.90028 17.1281 9.90039 17M10.0597 16.6341L16.6469 10.0468C16.8422 9.85157 17.1587 9.85157 17.354 10.0468M9.9004 16.9972C9.90118 16.8538 9.96231 16.7248 10.0597 16.6341L9.9004 16.9972Z" fill="#4F4F4F"/>
                </svg>
            </button>
            <button onclick="plusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0004 33C25.837 33 33.0005 25.8365 33.0005 16.9999C33.0005 8.16332 25.837 0.999836 17.0004 0.999836C8.16382 0.999836 1.00034 8.16332 1.00034 16.9999C1.00034 25.8365 8.16382 33 17.0004 33ZM34.0005 16.9999C34.0005 26.3888 26.3893 34 17.0004 34C7.61153 34 0.000339508 26.3888 0.000339508 16.9999C0.000339508 7.61103 7.61153 -0.000164032 17.0004 -0.000164032C26.3893 -0.000164032 34.0005 7.61103 34.0005 16.9999ZM16.6475 23.9531C16.4522 23.7579 16.4522 23.4413 16.6475 23.246L22.3944 17.5L10.402 17.5C10.1258 17.5 9.90199 17.2761 9.90199 17C9.90199 16.7239 10.1258 16.5 10.402 16.5L22.3952 16.5L16.6475 10.7531C16.4522 10.5579 16.4522 10.2413 16.6475 10.046C16.8427 9.85074 17.1593 9.85072 17.3546 10.046L23.9556 16.646C24.0109 16.7013 24.0519 16.7682 24.0763 16.8411C24.0932 16.8917 24.1021 16.9452 24.1021 16.9996C24.1021 16.9997 24.1021 16.9999 24.1021 17C24.1021 17.1443 24.0409 17.2744 23.9431 17.3657L17.3546 23.9532C17.1593 24.1484 16.8427 24.1484 16.6475 23.9531Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
    </div>
    <div class="modal">
        <div class="modal-close-btn">
            <button onclick="closeModal()">
                <svg height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
        <div class="modal-flex">
            <div class="modal-img">
                <img src="https://mealhub.info/images/screen_5_pic_1.png" alt="" style="width: 100%; max-width: 396px">
            </div>
            <div style="max-width: 550px;">
                <div class="modal-header">
                DELIVER MEAL
                </div>
                <div>
                    <p class="modal-text">
                    Трудно представить себе современный мир без услуг по доставке, поэтому мы не смогли обойти её стороной и сделали все, чтобы ваши любимые блюда доставляли вам по любому адресу, в любое указанное время, на любую сумму и из любого заведения!
                    <br><br>
                    Благодаря высокой функциональности сервиса, вы можете выбрать для себя, например, только заведения с быстрой доставкой, или только с бесплатной. Выбирйте заведения по рейтингу или кухне, по месторасположению и отзывам о доставке. 
                    Но главное – вы можете сравнить заведения или блюда, после чего принять самое верное для вас решение 
                    о доставке!
                    <br><br>
                    После того, как вы выбрали блюда и оплатили их, вы можете следить за временем их приготовления, временем самой доставки, а также за местонахождением курьера, осуществляющего вам доставку и, при необходимости, 
                    связаться как с курьером, так и с заведением.
                    </p>
                </div>
                <div>
                    <button class="btn-pink">
                        Хочу сделать заказ
                    </button>
                </div>
            </div>
        </div>
        <div class="modal-bottom-bar">
            <button onclick="minusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0001 1C8.16351 1 1 8.16351 1 17.0001C1 25.8368 8.16351 33.0003 17.0001 33.0003C25.8368 33.0003 33.0003 25.8368 33.0003 17.0001C33.0003 8.16351 25.8368 1 17.0001 1ZM0 17.0001C0 7.61122 7.61122 0 17.0001 0C26.3891 0 34.0003 7.61122 34.0003 17.0001C34.0003 26.3891 26.3891 34.0003 17.0001 34.0003C7.61122 34.0003 0 26.3891 0 17.0001ZM17.354 10.0468C17.5493 10.2421 17.5493 10.5587 17.354 10.7539L11.6079 16.5H23.6005C23.8766 16.5 24.1005 16.7239 24.1005 17C24.1005 17.2761 23.8766 17.5 23.6005 17.5H11.607L17.354 23.247C17.5493 23.4422 17.5493 23.7588 17.354 23.9541C17.1587 24.1493 16.8422 24.1493 16.6469 23.9541L10.0468 17.354C9.94909 17.2563 9.90028 17.1281 9.90039 17M10.0597 16.6341L16.6469 10.0468C16.8422 9.85157 17.1587 9.85157 17.354 10.0468M9.9004 16.9972C9.90118 16.8538 9.96231 16.7248 10.0597 16.6341L9.9004 16.9972Z" fill="#4F4F4F"/>
                </svg>
            </button>
            <button onclick="plusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0004 33C25.837 33 33.0005 25.8365 33.0005 16.9999C33.0005 8.16332 25.837 0.999836 17.0004 0.999836C8.16382 0.999836 1.00034 8.16332 1.00034 16.9999C1.00034 25.8365 8.16382 33 17.0004 33ZM34.0005 16.9999C34.0005 26.3888 26.3893 34 17.0004 34C7.61153 34 0.000339508 26.3888 0.000339508 16.9999C0.000339508 7.61103 7.61153 -0.000164032 17.0004 -0.000164032C26.3893 -0.000164032 34.0005 7.61103 34.0005 16.9999ZM16.6475 23.9531C16.4522 23.7579 16.4522 23.4413 16.6475 23.246L22.3944 17.5L10.402 17.5C10.1258 17.5 9.90199 17.2761 9.90199 17C9.90199 16.7239 10.1258 16.5 10.402 16.5L22.3952 16.5L16.6475 10.7531C16.4522 10.5579 16.4522 10.2413 16.6475 10.046C16.8427 9.85074 17.1593 9.85072 17.3546 10.046L23.9556 16.646C24.0109 16.7013 24.0519 16.7682 24.0763 16.8411C24.0932 16.8917 24.1021 16.9452 24.1021 16.9996C24.1021 16.9997 24.1021 16.9999 24.1021 17C24.1021 17.1443 24.0409 17.2744 23.9431 17.3657L17.3546 23.9532C17.1593 24.1484 16.8427 24.1484 16.6475 23.9531Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
    </div>
    <div class="modal">
        <div class="modal-close-btn">
            <button onclick="closeModal()">
                <svg height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
        <div class="modal-flex">
            <div class="modal-img">
                <img src="https://mealhub.info/images/screen_5_pic_2.png" alt="" style="width: 100%; max-width: 323px">
            </div>
            <div style="max-width: 550px;">
                <div class="modal-header">
                BOOK MEAL
                </div>
                <div>
                    <p class="modal-text">
                    Несмотря на удобные условия доставки мы знаем, как вы любите посещать заведения. Ведь ничто не заменит приятную дружескую болтовню в уютной кофейне, романтический ужин 
                    в ресторане с известным шефом, деловую встречу за обедом или же веселое времяпрепровождение в шумном баре 
                    и вытекающий из него позднего завтрака в любимом кафе.
                    <br><br>
                    Поэтому мы пошли дальше и сделали доступным и применимым абсолютно во всех заведениях сервис BOOK MEAL. С этим сервисом, вы можете не только забронировать стол в заведении, но еще и выбрать нужный стол самостоятельно!
                    <br><br>
                    Вы выбираете заведение, указываете дату, время, зал 
                    в заведении, выбираете стол и количество гостей. 
                    Вы так же можете выбрать повод вашего мероприятия 
                    и оставить пожелания к своей брони и все -  вам остается 
                    только дождаться подтверждения от заведения!
                    <br><br>
                    Также вы можете сразу же выбрать блюда, но это уже совсем другая история!
                    </p>
                </div>
                <div>
                    <button class="btn-pink">
                        Хочу сделать заказ
                    </button>
                </div>
            </div>
        </div>
        <div class="modal-bottom-bar">
            <button onclick="minusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0001 1C8.16351 1 1 8.16351 1 17.0001C1 25.8368 8.16351 33.0003 17.0001 33.0003C25.8368 33.0003 33.0003 25.8368 33.0003 17.0001C33.0003 8.16351 25.8368 1 17.0001 1ZM0 17.0001C0 7.61122 7.61122 0 17.0001 0C26.3891 0 34.0003 7.61122 34.0003 17.0001C34.0003 26.3891 26.3891 34.0003 17.0001 34.0003C7.61122 34.0003 0 26.3891 0 17.0001ZM17.354 10.0468C17.5493 10.2421 17.5493 10.5587 17.354 10.7539L11.6079 16.5H23.6005C23.8766 16.5 24.1005 16.7239 24.1005 17C24.1005 17.2761 23.8766 17.5 23.6005 17.5H11.607L17.354 23.247C17.5493 23.4422 17.5493 23.7588 17.354 23.9541C17.1587 24.1493 16.8422 24.1493 16.6469 23.9541L10.0468 17.354C9.94909 17.2563 9.90028 17.1281 9.90039 17M10.0597 16.6341L16.6469 10.0468C16.8422 9.85157 17.1587 9.85157 17.354 10.0468M9.9004 16.9972C9.90118 16.8538 9.96231 16.7248 10.0597 16.6341L9.9004 16.9972Z" fill="#4F4F4F"/>
                </svg>
            </button>
            <button onclick="plusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0004 33C25.837 33 33.0005 25.8365 33.0005 16.9999C33.0005 8.16332 25.837 0.999836 17.0004 0.999836C8.16382 0.999836 1.00034 8.16332 1.00034 16.9999C1.00034 25.8365 8.16382 33 17.0004 33ZM34.0005 16.9999C34.0005 26.3888 26.3893 34 17.0004 34C7.61153 34 0.000339508 26.3888 0.000339508 16.9999C0.000339508 7.61103 7.61153 -0.000164032 17.0004 -0.000164032C26.3893 -0.000164032 34.0005 7.61103 34.0005 16.9999ZM16.6475 23.9531C16.4522 23.7579 16.4522 23.4413 16.6475 23.246L22.3944 17.5L10.402 17.5C10.1258 17.5 9.90199 17.2761 9.90199 17C9.90199 16.7239 10.1258 16.5 10.402 16.5L22.3952 16.5L16.6475 10.7531C16.4522 10.5579 16.4522 10.2413 16.6475 10.046C16.8427 9.85074 17.1593 9.85072 17.3546 10.046L23.9556 16.646C24.0109 16.7013 24.0519 16.7682 24.0763 16.8411C24.0932 16.8917 24.1021 16.9452 24.1021 16.9996C24.1021 16.9997 24.1021 16.9999 24.1021 17C24.1021 17.1443 24.0409 17.2744 23.9431 17.3657L17.3546 23.9532C17.1593 24.1484 16.8427 24.1484 16.6475 23.9531Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
    </div>
    <div class="modal">
        <div class="modal-close-btn">
            <button onclick="closeModal()">
                <svg height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
        <div class="modal-flex">
            <div class="modal-img">
                <img src="https://mealhub.info/images/screen_6_pic_1.png" alt="" style="width: 100%; max-width: 430px">
            </div>
            <div style="max-width: 550px;">
                <div class="modal-header">
                PRE-ORDER MEAL
                </div>
                <div>
                    <p class="modal-text">
                    Сервис позволяет предварительно в режиме онлайн сделать заказ блюд к уже забронированному вами столу.
                    <br><br>
                    В подходящее для вас время вы можете внимательно изучить все меню заведения, ознакомиться с каждым блюдом, при необходимости – сравнить их с похожими блюдами из других заведений. 
                    <br><br>
                    И только после того, как вы будете абсолютно уверены в правильности своего выбора, бронируйте стол или зал в выбранном заведении, добавляйте к своей брони все самые вкусные блюда в нужном количестве, указывайте время, к которому необходимо накрыть столы, а также время подачи горячих закусок и горячих блюд. 
                    <br><br>
                    Сервис дает возможность оставить любые комментарии 
                    и пожелания к своему заказу и можете быть спокойны -  все именно так и будет!
                    </p>
                </div>
                <div>
                    <button class="btn-pink">
                        Хочу сделать заказ
                    </button>
                </div>
            </div>
        </div>
        <div class="modal-bottom-bar">
            <button onclick="minusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0001 1C8.16351 1 1 8.16351 1 17.0001C1 25.8368 8.16351 33.0003 17.0001 33.0003C25.8368 33.0003 33.0003 25.8368 33.0003 17.0001C33.0003 8.16351 25.8368 1 17.0001 1ZM0 17.0001C0 7.61122 7.61122 0 17.0001 0C26.3891 0 34.0003 7.61122 34.0003 17.0001C34.0003 26.3891 26.3891 34.0003 17.0001 34.0003C7.61122 34.0003 0 26.3891 0 17.0001ZM17.354 10.0468C17.5493 10.2421 17.5493 10.5587 17.354 10.7539L11.6079 16.5H23.6005C23.8766 16.5 24.1005 16.7239 24.1005 17C24.1005 17.2761 23.8766 17.5 23.6005 17.5H11.607L17.354 23.247C17.5493 23.4422 17.5493 23.7588 17.354 23.9541C17.1587 24.1493 16.8422 24.1493 16.6469 23.9541L10.0468 17.354C9.94909 17.2563 9.90028 17.1281 9.90039 17M10.0597 16.6341L16.6469 10.0468C16.8422 9.85157 17.1587 9.85157 17.354 10.0468M9.9004 16.9972C9.90118 16.8538 9.96231 16.7248 10.0597 16.6341L9.9004 16.9972Z" fill="#4F4F4F"/>
                </svg>
            </button>
            <button onclick="plusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0004 33C25.837 33 33.0005 25.8365 33.0005 16.9999C33.0005 8.16332 25.837 0.999836 17.0004 0.999836C8.16382 0.999836 1.00034 8.16332 1.00034 16.9999C1.00034 25.8365 8.16382 33 17.0004 33ZM34.0005 16.9999C34.0005 26.3888 26.3893 34 17.0004 34C7.61153 34 0.000339508 26.3888 0.000339508 16.9999C0.000339508 7.61103 7.61153 -0.000164032 17.0004 -0.000164032C26.3893 -0.000164032 34.0005 7.61103 34.0005 16.9999ZM16.6475 23.9531C16.4522 23.7579 16.4522 23.4413 16.6475 23.246L22.3944 17.5L10.402 17.5C10.1258 17.5 9.90199 17.2761 9.90199 17C9.90199 16.7239 10.1258 16.5 10.402 16.5L22.3952 16.5L16.6475 10.7531C16.4522 10.5579 16.4522 10.2413 16.6475 10.046C16.8427 9.85074 17.1593 9.85072 17.3546 10.046L23.9556 16.646C24.0109 16.7013 24.0519 16.7682 24.0763 16.8411C24.0932 16.8917 24.1021 16.9452 24.1021 16.9996C24.1021 16.9997 24.1021 16.9999 24.1021 17C24.1021 17.1443 24.0409 17.2744 23.9431 17.3657L17.3546 23.9532C17.1593 24.1484 16.8427 24.1484 16.6475 23.9531Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
    </div>
    <div class="modal">
        <div class="modal-close-btn">
            <button onclick="closeModal()">
                <svg height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
        <div class="modal-flex">
            <div class="modal-img">
                <img src="https://mealhub.info/images/screen_6_pic_2.png" alt="" style="width: 100%; max-width: 364px">
            </div>
            <div style="max-width: 550px;">
                <div class="modal-header">
                MEAL COST
                </div>
                <div>
                    <p class="modal-text">
                    Для того, чтобы вы могли самостоятельно и при этом легко просчитать все предполагаемые затраты на ваш банкет, мы разработали уникальный продукт – универсальный банкетный калькулятор MEAL COST.
                    <br><br>
                    С помощью сервиса MEAL COST вы можете заранее просчитать требуемую сумму на ваш банкет, в зависимости от того, в каком заведении он будет проходить, сколько человек планируется 
                    на мероприятии и какой формат вашего банкета. Расчитайте необходимое количество блюд и затраты на каждого гостя. Составьте праздничное меню и оставьте комментарии по каждой выбранной позиции. Расскажите о ваших пожеланиях 
                    к оформлению зала и столов, отметить любые важные детали, которые касаются вашего мероприятия и все это – не покидая своего дома или офиса! 
                    <br><br>
                    Конечно, хлопоты по организации своего праздника – это приятные хлопоты, но уверенность в том, что все пройдет как  надо, без неожиданностей и неприятных сюрпризов, вдвойне приятнее! С нашим сайтом и приложением MEALHUB.USERS, 
                    а также с умным сервисом MEAL COST вы будете наслаждаться торжеством, не отвлекаясь на организационные мелочи!
                    </p>
                </div>
                <div>
                    <button class="btn-pink">
                        Хочу сделать заказ
                    </button>
                </div>
            </div>
        </div>
        <div class="modal-bottom-bar">
            <button onclick="minusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0001 1C8.16351 1 1 8.16351 1 17.0001C1 25.8368 8.16351 33.0003 17.0001 33.0003C25.8368 33.0003 33.0003 25.8368 33.0003 17.0001C33.0003 8.16351 25.8368 1 17.0001 1ZM0 17.0001C0 7.61122 7.61122 0 17.0001 0C26.3891 0 34.0003 7.61122 34.0003 17.0001C34.0003 26.3891 26.3891 34.0003 17.0001 34.0003C7.61122 34.0003 0 26.3891 0 17.0001ZM17.354 10.0468C17.5493 10.2421 17.5493 10.5587 17.354 10.7539L11.6079 16.5H23.6005C23.8766 16.5 24.1005 16.7239 24.1005 17C24.1005 17.2761 23.8766 17.5 23.6005 17.5H11.607L17.354 23.247C17.5493 23.4422 17.5493 23.7588 17.354 23.9541C17.1587 24.1493 16.8422 24.1493 16.6469 23.9541L10.0468 17.354C9.94909 17.2563 9.90028 17.1281 9.90039 17M10.0597 16.6341L16.6469 10.0468C16.8422 9.85157 17.1587 9.85157 17.354 10.0468M9.9004 16.9972C9.90118 16.8538 9.96231 16.7248 10.0597 16.6341L9.9004 16.9972Z" fill="#4F4F4F"/>
                </svg>
            </button>
            <button onclick="plusSlide()">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M17.0004 33C25.837 33 33.0005 25.8365 33.0005 16.9999C33.0005 8.16332 25.837 0.999836 17.0004 0.999836C8.16382 0.999836 1.00034 8.16332 1.00034 16.9999C1.00034 25.8365 8.16382 33 17.0004 33ZM34.0005 16.9999C34.0005 26.3888 26.3893 34 17.0004 34C7.61153 34 0.000339508 26.3888 0.000339508 16.9999C0.000339508 7.61103 7.61153 -0.000164032 17.0004 -0.000164032C26.3893 -0.000164032 34.0005 7.61103 34.0005 16.9999ZM16.6475 23.9531C16.4522 23.7579 16.4522 23.4413 16.6475 23.246L22.3944 17.5L10.402 17.5C10.1258 17.5 9.90199 17.2761 9.90199 17C9.90199 16.7239 10.1258 16.5 10.402 16.5L22.3952 16.5L16.6475 10.7531C16.4522 10.5579 16.4522 10.2413 16.6475 10.046C16.8427 9.85074 17.1593 9.85072 17.3546 10.046L23.9556 16.646C24.0109 16.7013 24.0519 16.7682 24.0763 16.8411C24.0932 16.8917 24.1021 16.9452 24.1021 16.9996C24.1021 16.9997 24.1021 16.9999 24.1021 17C24.1021 17.1443 24.0409 17.2744 23.9431 17.3657L17.3546 23.9532C17.1593 24.1484 16.8427 24.1484 16.6475 23.9531Z" fill="#4F4F4F"/>
                </svg>
            </button>
        </div>
    </div>
    <div class="modal">
        <div class="modal-close-btn">
            <button onclick="closeModal()">
                <svg height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#FFFFFF"/>
                </svg>
            </button>
        </div>
        <div class="modal-flex">
            <div>
                <div class="modal-header">
                    Хотите лично пообщаться с нашими специалистами?                </div>
                <div>
                    <div class="modal-error" style="display: none;">
                        <svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M11 6C11.5523 6 12 6.44772 12 7V11C12 11.5523 11.5523 12 11 12C10.4477 12 10 11.5523 10 11V7C10 6.44772 10.4477 6 11 6Z" fill="white"/>
                            <path d="M11 14C10.4477 14 10 14.4477 10 15C10 15.5523 10.4477 16 11 16H11.01C11.5623 16 12.01 15.5523 12.01 15C12.01 14.4477 11.5623 14 11.01 14H11Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M0 11C0 4.92487 4.92487 0 11 0C17.0751 0 22 4.92487 22 11C22 17.0751 17.0751 22 11 22C4.92487 22 0 17.0751 0 11ZM11 2C6.02944 2 2 6.02944 2 11C2 15.9706 6.02944 20 11 20C15.9706 20 20 15.9706 20 11C20 6.02944 15.9706 2 11 2Z" fill="white"/>
                        </svg>
                        <div class="modal-error-text"></div>
                    </div>
                   <form action="" id="feedbackForm">
                       <div class="form_input-div">
                            <input type="text" name="name" require placeholder="Имя">
                            <input type="email" name="email" require placeholder="E-mail">
                       </div>
                       <textarea name="mess" id="" cols="30" rows="10" require placeholder="Ваше сообщение"></textarea>
                       <input type="hidden" id="form_addresat" name="adressat" value="">
                        <div style="text-align: center;">
                            <button class="btn-pink" style="width: 250px;">
                                Отправить                            </button>
                        </div>
                   </form>
                </div>
            </div>
        </div>
    </div>
    <div class="modal">
        <div class="modal-close-btn">
            <button onclick="closeModal()">
                <svg height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#FFFFFF"/>
                </svg>
            </button>
        </div>
        <div class="modal-flex">
            <div>
                <div class="modal-header">
                    Ваше сообщение отправлено!                </div>
                <div class="modal-text">
                    Мы свяжемся с вами в ближайшее время                </div>
            </div>
        </div>
    </div>
    <div class="modal">
        <div class="modal-close-btn">
            <button onclick="closeModal()">
                <svg height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#FFFFFF"/>
                </svg>
            </button>
        </div>
        <div class="modal-flex">
            <div>
                <div class="modal-header">
                    Теперь Вы подписанны на нашу новостную рассылку                </div>
                <!-- <div class="modal-text">
                Мы свяжемся  с вами в ближайшее время
                </div> -->
            </div>
        </div>
    </div>
    <div class="modal">
        <div class="modal-close-btn">
            <button onclick="closeModal()">
                <svg height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#FFFFFF"/>
                </svg>
            </button>
        </div>
        <div class="modal-flex">
            <div>
                <div class="modal-header">
                    Вы уже подписаны                </div>
                <!-- <div class="modal-text">
                Попробуйте повторить позднее
                </div> -->
            </div>
        </div>
    </div>
    <!-- модалка приложений -->
    <div class="modal">
        <div class="modal-close-btn">
            <button onclick="closeModal()">
                <svg height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.29289 1.29289C1.68342 0.902369 2.31658 0.902369 2.70711 1.29289L10 8.58579L17.2929 1.29289C17.6834 0.902369 18.3166 0.902369 18.7071 1.29289C19.0976 1.68342 19.0976 2.31658 18.7071 2.70711L11.4142 10L18.7071 17.2929C19.0976 17.6834 19.0976 18.3166 18.7071 18.7071C18.3166 19.0976 17.6834 19.0976 17.2929 18.7071L10 11.4142L2.70711 18.7071C2.31658 19.0976 1.68342 19.0976 1.29289 18.7071C0.902369 18.3166 0.902369 17.6834 1.29289 17.2929L8.58579 10L1.29289 2.70711C0.902369 2.31658 0.902369 1.68342 1.29289 1.29289Z" fill="#FFFFFF"/>
                </svg>
            </button>
        </div>
        <div class="modal-flex">
            <div>
                <div class="modal-header">
                    Приложение в разработке                </div>
            </div>
        </div>
    </div>
</div><script src="https://mealhub.info/js/mobile.js"></script>
<script src="https://mealhub.info/js/axios.js"></script>
<!-- Yandex.Metrika counter -->
<script type="text/javascript" >
   (function(m,e,t,r,i,k,a){m[i]=m[i]||function(){(m[i].a=m[i].a||[]).push(arguments)};
   m[i].l=1*new Date();
   for (var j = 0; j < document.scripts.length; j++) {if (document.scripts[j].src === r) { return; }}
   k=e.createElement(t),a=e.getElementsByTagName(t)[0],k.async=1,k.src=r,a.parentNode.insertBefore(k,a)})
   (window, document, "script", "https://mc.yandex.ru/metrika/tag.js", "ym");

   ym(92974951, "init", {
        clickmap:true,
        trackLinks:true,
        accurateTrackBounce:true,
        webvisor:true
   });
</script>
<noscript><div><img src="https://mc.yandex.ru/watch/92974951" style="position:absolute; left:-9999px;" alt="" /></div></noscript>
<!-- /Yandex.Metrika counter -->
<script>
    window.onscroll = function (e) {  
    let position_y = window.scrollY;
    if(position_y >= 500){
        document.querySelector('nav').style.position = 'fixed'
        // document.querySelector('nav').style.backgroundColor = '#fff'
        document.querySelector('nav').style.zIndex = 10
        document.querySelector('nav').style.top = 0
        document.querySelector('nav').classList.add("scrolledNav");
        // document.querySelector('nav').style.padding = '20px'

        // document.querySelector('nav').style.borderRadius = '0px 0px 15px 15px'
        // document.querySelector('nav').style.boxShadow = '0px 4px 8px rgba(0, 0, 0, 0.1)'

        // document.querySelector('nav > .logo').style.top = '10px'
    } else {
        document.querySelector('nav').style.position = 'absolute'
        // document.querySelector('nav').style.backgroundColor = 'unset'
        document.querySelector('nav').style.zIndex = '1'
        document.querySelector('nav').classList.remove("scrolledNav");
        document.querySelector('nav').style.top = '35px'
        // document.querySelector('nav').style.padding = 'unset'
        document.querySelector('nav').style.borderRadius = 'unset'
        // document.querySelector('nav').style.boxShadow = 'unset'
        // document.querySelector('nav > .logo').style.top = '70px'

    }
} 
function closeModal () {
    document.querySelector('.modal-wrapper').style.display = 'none'
}

const modalWrapper = document.querySelector('.modal-wrapper');
modalWrapper.addEventListener('click', (e) => {
    if (e.target === document.querySelector('.modal-wrapper')) {
        document.querySelector('.modal-wrapper').style.display = 'none'
    }
})

/* Индекс слайда по умолчанию */
var slideIndex = 1;
// showSlides(slideIndex);

/* Функция увеличивает индекс на 1, показывает следующй слайд*/
function plusSlide(e) {
    showSlides(slideIndex += 1);
}

/* Функция уменьшяет индекс на 1, показывает предыдущий слайд*/
function minusSlide(e) {
    showSlides(slideIndex -= 1);  
}

/* Устанавливает текущий слайд */
function currentSlide(e,n, addresat) {
    if (e) {
        e.preventDefault()
    }
    
    if (addresat) {
        document.getElementById('form_addresat').value = addresat
    }
    
    showSlides(slideIndex = n);
}

/* Основная функция слайдера */
function showSlides(n) {
    console.log('log '+n);
    if (document.querySelector('.modal-wrapper').style.display == 'none') {
        document.querySelector('.modal-wrapper').style.display = 'flex'
    }
    var i;
    var slides = document.getElementsByClassName("modal");
    // var dots = document.getElementsByClassName("slider-dots_item");
    if (n > slides.length) {
      slideIndex = 1
    }
    if (n < 1) {
        slideIndex = slides.length
    }
    for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
    }
    // for (i = 0; i < dots.length; i++) {
    //     dots[i].className = dots[i].className.replace(" active", "");
    // }
    slides[slideIndex - 1].style.display = "block";
    // dots[slideIndex - 1].className += " active";
}
const form = document.getElementById( "feedbackForm" );
form.addEventListener( "submit", async function ( event ) {
    event.preventDefault();
    let response = await fetch('/api/mail.php', {
      method: 'POST',
      body: new FormData(document.getElementById( "feedbackForm" ))
    });

    let result = await response.json();
    if (result.error) {
        document.querySelector('.modal-error').style.display = 'flex'
        document.querySelector('.modal-error-text').innerHTML = result.message
    } else {
        document.querySelector('.modal-error').style.display = 'none'
        document.querySelector('.modal-error-text').innerHTML = ''
        form.reset()
        currentSlide(false,8, false)
    }
    console.log(result);
    
  } );

const footerForm = document.getElementById( "footer_form" );

footerForm.addEventListener( "submit", async function ( event ) {
    event.preventDefault();
    const fm = new FormData(document.getElementById( "footer_form" ))

    let response = await axios.post('/api/subscribe.php', fm)

    // let result = await response.json();
    if (response.data.status == "error") {
        footerForm.reset()
        currentSlide(false,10, false)
    } else {
        footerForm.reset()
        currentSlide(false,9, false)
    }
    // console.log(result);
    console.log(response);
    
  } );

function scrollDown() {
    window.scrollTo({
        top: 1000,
        behavior: "smooth"
    });
}
function changeLang (e, val) {
    e.preventDefault()
    switch (val) {
        case 'ru': location.href = '?lang=ru';break;
        case 'en': location.href = '?lang=en';break;
        default: location.href = '?lang=en';break;
    }
}
/* When the user clicks on the button, 
toggle between hiding and showing the dropdown content */
function myFunction() {
    document.getElementById("myDropdown").classList.toggle("show");
    document.getElementById("myDropdownBtn").classList.toggle("nav-open");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(e) {

  if (!e.target.matches('.dropbtn') && !e.target.matches('.dropbtn-nav-arrow')) {
    var myDropdown = document.getElementById("myDropdown");
      if (myDropdown.classList.contains('show')) {
        myDropdown.classList.remove('show');
      }
      if (document.getElementById("myDropdownBtn").classList.contains('nav-open')) {
        document.getElementById("myDropdownBtn").classList.remove('nav-open');
      }
  }
}
//lang footer
function myFunctionFooter() {
    document.getElementById("myDropdown-footer").classList.toggle("show");
    document.getElementById("myDropdownBtn-footer").classList.toggle("nav-open-footer");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(e) {

  if (!e.target.matches('.dropbtn-footer') && !e.target.matches('.dropbtn-nav-arrow')&& !e.target.matches('.dropbtn-footer-ancor')) {
    var myDropdown = document.getElementById("myDropdown-footer");
      if (myDropdown.classList.contains('show')) {
        myDropdown.classList.remove('show');
      }
      if (document.getElementById("myDropdownBtn-footer").classList.contains('nav-open-footer')) {
        document.getElementById("myDropdownBtn-footer").classList.remove('nav-open-footer');
      }
  }
}
</script>		<script src="https://mealhub.info/js/splide.min.js"></script>
		<script>
            const splide_1 = new Splide( '#splide_1', {
                type: 'loop',
                gap: 20,
                autoplay: true,
                fixedWidth: 600,
                arrows: false,
                breakpoints: {
                    900: {
                        fixedWidth: 300,
                    }
                }
            } ).mount();
            const splide_2 = new Splide( '#splide_2', {
                type: 'loop',
                gap: 20,
                autoplay: true,
                fixedWidth: 650,
                arrows: false,
                breakpoints: {
                    900: {
                        fixedWidth: 280,
                    }
                }
            } ).mount();
		</script>
	</body>
</html>
</template>