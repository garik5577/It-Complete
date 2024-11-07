<!DOCTYPE html>
<html lang="en" prefix="og: http://ogp.me/ns#">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <meta property="og:type" content="article">
    <meta property="og:title" content="Мои обмеры">
    <meta property="og:description" content="Новейшие технологии позволяют нам получать точные обмеры человеческого тела. Powered by #TexelPortal">
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:site" content="texelinc">
    <meta property="og:image" content="https://content.texel.graphics/render/9pNW8/frame0000.jpg">
    <meta property="twitter:image" content="https://content.texel.graphics/render/9pNW8/frame0000.jpg">
    <title>Texel Portal — Мои обмеры</title>
    <link rel="icon" type="image/x-icon" href="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/favicon.ico">

    <link href="https://client.texel.graphics/assets/texel-client/common/css/bootstrap.min.css" rel="stylesheet"/>
    <link href="https://client.texel.graphics/assets/texel-client/common/css/bootstrap-theme.min.css" rel="stylesheet"/>

    <link href="https://client.texel.graphics/assets/texel-client/common/css/lightslider.min.css" media="screen" rel="stylesheet" type="text/css">
    <link href="https://client.texel.graphics/assets/texel-client/template/texel-measurements/css/style.css" media="screen" rel="stylesheet" type="text/css">
    <script src="https://client.texel.graphics/assets/texel-client/common/js/jquery.min.js"></script>
    <script src="https://client.texel.graphics/assets/texel-client/common/js/bootstrap.min.js"></script>

    <script type="text/javascript" src="https://client.texel.graphics/assets/texel-client/common/js/lightslider.min.js"></script>
    <script type="text/javascript" src="https://client.texel.graphics/assets/texel-client/content/js/content.js"></script>
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
        <script src="https://client.texel.graphics/assets/texel-client/common/js/html5shiv.min.js"></script>
        <script src="https://client.texel.graphics/assets/texel-client/common/js/respond.min.js"></script>
        <![endif]-->
</head>

<body>

    <nav class="navbar navbar-default navbar-static-top">
        <div class="container">
            <div class="navbar-header">
                <button type="button" data-target="#navbar-collapse-container" data-toggle="collapse" class="navbar-toggle">
                    <span class="sr-only">Меню</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>

                <a href="http://texel.graphics" title="Texel Portal">
                    <img id="logo" src="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/logo.png"/>
                </a>
            </div>

            <div class="collapse navbar-collapse" id="navbar-collapse-container">
                <ul class="nav navbar-nav navbar-right">
                    <li>
                        <a href="http://texel.graphics/#contacts">Контакты</a>
                    </li>
                    <li class="active">
                        <a href="#" onclick="javascript:document.location.href = Texel.Content.updateQueryStringParameter(document.location.href, 'l', 'ru')" title="Русский">Русский</a>
                    </li>
                    <li>
                        <a href="#" onclick="javascript:document.location.href = Texel.Content.updateQueryStringParameter(document.location.href, 'l', 'en')" title="English">English</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div id="item-slider-container">
        <div class="container">
            <div class="col-xs-12">
                <div id="item-slider-wrapper">
                    <a id="item-slider-prev" href="#">
                        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
                    </a>
                    <ul id="item-slider"></ul>
                    <a id="item-slider-next" href="#">
                        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
                    </a>
                </div>

            </div>
        </div>
    </div>

    <div id="content-wrapper">
        <div class="container">
            <div class="col-xs-12 text-center">
                <div id="item" style="margin: 0 auto"></div>
            </div>
            <div class="col-xs-12 text-center">
                <div id="share" style="margin: 0 auto; margin-top: 15px;">
                    <div>
                        <a href="#" data-url="https://vk.com/share.php?url={{url}}" data-locale="ru" title="VK.com" target="_blank">
                            <img src="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/share-vk.png"/>
                        </a>
                    </div>
                    <div>
                        <a href="#" data-url="https://www.facebook.com/sharer.php?u={{url}}" data-locale="ru" title="Facebook" target="_blank">
                            <img src="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/share-facebook.png"/>
                        </a>
                    </div>
                    <div>
                        <a href="#" data-url="https://connect.mail.ru/share?url={{url}}" data-locale="ru" title="Mail.Ru" target="_blank">
                            <img src="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/share-mail.png"/>
                        </a>
                    </div>
                    <div>
                        <a href="#" data-url="https://www.odnoklassniki.ru/dk?st.cmd=addShare&st.s=1&st._surl={{url}}" data-locale="ru" title="Ok.ru" target="_blank">
                            <img src="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/share-ok.png"/>
                        </a>
                    </div>
                    <div>
                        <a href="#" data-url="https://twitter.com/intent/tweet?url={{url}}&hashtags=TexelPortal,3D,3DScanner" data-locale="ru" title="Twitter" target="_blank">
                            <img src="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/share-twitter.png"/>
                        </a>
                    </div>
                    <div>
                        <a href="#" title="Скачать" class="download-link download-link-all" data-file-name="portal" target="_blank">
                            <img src="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/share-download.png"/>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script type="text/javascript">

    $(document).ready(function()
    {
        Texel.Content.album({
            "id": "aBmoZB",
            "url": "https:\/\/portal.texel.graphics\/c\/aBmoZB",
            "imageUrl": "https:\/\/content.texel.graphics\/render\/9pNW8\/frame0000.jpg",
            "items": [{
                "id": "r9pNW8",
                "name": "surprise_moon",
                "created": "2024-10-31T23:53:53+00:00",
                "installationNumber": "1585934",
                "scanLocalId": 349,
                "url": "https:\/\/portal.texel.graphics\/c\/r9pNW8",
                "imageUrl": "https:\/\/content.texel.graphics\/render\/9pNW8\/frame0000.jpg",
                "embedUrl": "https:\/\/portal.texel.graphics\/c\/embed\/r9pNW8",
                "embedWidth": 512,
                "embedHeight": 512,
                "downloadUrl": null,
                "downloadType": null
            }, {
                "id": "rPzlxZ",
                "name": "future_city3",
                "created": "2024-10-31T23:53:53+00:00",
                "installationNumber": "1585934",
                "scanLocalId": 349,
                "url": "https:\/\/portal.texel.graphics\/c\/rPzlxZ",
                "imageUrl": "https:\/\/content.texel.graphics\/render\/PzlxZ\/frame0000.jpg",
                "embedUrl": "https:\/\/portal.texel.graphics\/c\/embed\/rPzlxZ",
                "embedWidth": 512,
                "embedHeight": 512,
                "downloadUrl": null,
                "downloadType": null
            }, {
                "id": "rlNrBJ",
                "name": "future_city2",
                "created": "2024-10-31T23:53:53+00:00",
                "installationNumber": "1585934",
                "scanLocalId": 349,
                "url": "https:\/\/portal.texel.graphics\/c\/rlNrBJ",
                "imageUrl": "https:\/\/content.texel.graphics\/render\/lNrBJ\/frame0000.jpg",
                "embedUrl": "https:\/\/portal.texel.graphics\/c\/embed\/rlNrBJ",
                "embedWidth": 512,
                "embedHeight": 512,
                "downloadUrl": null,
                "downloadType": null
            }, {
                "id": "rz0Pex",
                "name": "future_city1",
                "created": "2024-10-31T23:53:53+00:00",
                "installationNumber": "1585934",
                "scanLocalId": 349,
                "url": "https:\/\/portal.texel.graphics\/c\/rz0Pex",
                "imageUrl": "https:\/\/content.texel.graphics\/render\/z0Pex\/frame0000.jpg",
                "embedUrl": "https:\/\/portal.texel.graphics\/c\/embed\/rz0Pex",
                "embedWidth": 512,
                "embedHeight": 512,
                "downloadUrl": null,
                "downloadType": null
            }, {
                "id": "rB2Dgx",
                "name": "background_color",
                "created": "2024-10-31T23:53:53+00:00",
                "installationNumber": "1585934",
                "scanLocalId": 349,
                "url": "https:\/\/portal.texel.graphics\/c\/rB2Dgx",
                "imageUrl": "https:\/\/content.texel.graphics\/render\/B2Dgx\/frame0000.jpg",
                "embedUrl": "https:\/\/portal.texel.graphics\/c\/embed\/rB2Dgx",
                "embedWidth": 512,
                "embedHeight": 512,
                "downloadUrl": null,
                "downloadType": null
            }, {
                "id": "rq5137",
                "name": "background_no_color",
                "created": "2024-10-31T23:53:53+00:00",
                "installationNumber": "1585934",
                "scanLocalId": 349,
                "url": "https:\/\/portal.texel.graphics\/c\/rq5137",
                "imageUrl": "https:\/\/content.texel.graphics\/render\/q5137\/frame0000.jpg",
                "embedUrl": "https:\/\/portal.texel.graphics\/c\/embed\/rq5137",
                "embedWidth": 512,
                "embedHeight": 512,
                "downloadUrl": null,
                "downloadType": null
            }],
            "currentItemId": "r9pNW8",
            "metadata": [],
            "measurements": []
        });
    });
    </script>

    <footer class="footer">
        <div class="container">
            <div class="col-xs-12 col-md-8">
                <p class="text-muted">
                    &copy; 2014&mdash;2024 
                    <a href="http://texel.graphics/">Texel Inc.</a>
                     Все права защищены. Powered by 
                    <a href="http://texel.graphics/">Texel Portal</a>
                    .
                </p>
            </div>
            <div class="col-xs-12 col-md-4 text-right">
                <div id="social">
                    <div>
                        <a href="https://vk.com/texelinc" title="VK.com">
                            <img src="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/social-vk.png"/>
                        </a>
                    </div>
                    <div>
                        <a href="https://www.facebook.com/texelinc" title="Facebook">
                            <img src="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/social-facebook.png"/>
                        </a>
                    </div>
                    <div>
                        <a href="https://twitter.com/texelinc" title="Twitter">
                            <img src="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/social-twitter.png"/>
                        </a>
                    </div>
                    <div>
                        <a href="https://instagram.com/texelinc" title="Instagram">
                            <img src="https://client.texel.graphics/assets/texel-client/template/texel-measurements/images/social-instagram.png"/>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </footer>

</body>
</html>

