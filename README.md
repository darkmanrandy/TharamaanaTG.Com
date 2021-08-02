<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' b:templateVersion='1.3.0' expr:class='data:blog.languageDirection' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
    <meta content='width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1' name='viewport'/>
    <title><data:view.title.escaped/></title>
    <link href='//1.bp.blogspot.com' rel='dns-prefetch'/>
    <link href='//2.bp.blogspot.com' rel='dns-prefetch'/>
    <link href='//3.bp.blogspot.com' rel='dns-prefetch'/>
    <link href='//4.bp.blogspot.com' rel='dns-prefetch'/>
    <link href='//www.blogger.com' rel='dns-prefetch'/>
    <link href='//cdnjs.cloudflare.com' rel='dns-prefetch'/>
    <link href='//cdn.firebase.com' rel='dns-prefetch'/>
    <link href='//ajax.googleapis.com' rel='dns-prefetch'/>
    <link href='//fonts.gstatic.com' rel='dns-prefetch'/>
    <link href='//pagead2.googlesyndication.com' rel='dns-prefetch'/>
    <link href='//www.googletagmanager.com' rel='dns-prefetch'/>
    <link href='//www.google-analytics.com' rel='dns-prefetch'/>
    <link href='//connect.facebook.net' rel='dns-prefetch'/>
    <link href='//c.disquscdn.com' rel='dns-prefetch'/>
    <link href='//disqus.com' rel='dns-prefetch'/>
    <b:include name='themeHead'/>
<!-- Jquery Library and Font Awesome CDN -->
<script src='https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js'/>
<link crossorigin='anonymous' href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.css' integrity='sha256-46qynGAkLSFpVbEBog43gvNhfrOj+BmwXdxFgVK/Kvc=' rel='stylesheet'/>

<b:skin version='1.3.0'><![CDATA[/* 
-----------------------------------------------
Theme Name     : Tendkotta
https://tendkotta.blogspot.com/
----------------------------------------------- */

/* Variable Definitions
-----------------------
<Variable name="keycolor" description="Main Color" type="color" default="$(main.color)" value="#3f51b5"/>
<Variable name="main.color" description="Theme Color" type="color" default="#3f51b5" value="#990000"/>
<Variable name="followByEmail" description="Follow By Email Text" type="string" default="Get all latest content delivered straight to your inbox." value="Get all the latest content right in your inbox.
"/>

<Group description="Theme Body" selector="body">
  <Variable name="body.background.color" description="Body Background Color" type="color" default="#222222"  value="#030d17"/>
  <Variable name="body.background" description="Background" type="background" color="$(body.background.color)" default="$(color) url() repeat fixed top left" value="$(color) url() repeat fixed top left"/>
  <Variable name="body.text.color" description="Text Color" type="color" default="#ffffff"  value="#ffffff"/>
  <Variable name="body.link.color" description="Link Color" type="color" default="$(main.color)"  value="#5872ff"/>
</Group>
 
<!-- Extra Variables -->
<Variable name="body.text.font" description="Font" hideEditor="true" type="font" default="13px Ruda, sans-serif"  value="13px Ruda, sans-serif"/>
<Variable name="posts.background.color" description="Post background color" hideEditor="true" type="color" default="#2f2f2f"  value="#2f2f2f"/>
<Variable name="tabs.font" description="Font 2" hideEditor="true" type="font" default="13px Ruda, sans-serif"  value="13px Ruda, sans-serif"/>
<Variable name="posts.title.color" description="Post title color" hideEditor="true" type="color" default="#000000"  value="#000000"/>
<Variable name="posts.text.color" description="Post text color" hideEditor="true" type="color" default="#656565"  value="#656565"/>
<Variable name="posts.link.color" description="Post link color" type="color" default="$(body.link.color)"  value="#3f51b5"/>
<Variable name="posts.icons.color" description="Post icons color" hideEditor="true" type="color" default="$(main.color)"  value="#3f51b5"/>
<Variable name="labels.background.color" description="Label background color" hideEditor="true" type="color" default="$(main.color)"  value="#3f51b5"/>
----------------------- */

/* Google Font - Kdam Thmor
----------------------------------------------- */
@font-face{font-family:'Kdam Thmor';font-style:normal;font-weight:400;src:local('Kdam Thmor'),local('KdamThmor'),url(https://fonts.gstatic.com/s/kdamthmor/v6/MwQzbhjs3veF6QwJVf0JoG8fiIlP.woff2) format('woff2');unicode-range:U+1780-17FF,U+200C,U+25CC}

/* Google Font - Hanuman
----------------------------------------------- */
@font-face{font-family:'Hanuman';font-style:normal;font-weight:400;src:local('Hanuman Regular'),local('Hanuman-Regular'),url(https://fonts.gstatic.com/s/hanuman/v12/VuJxdNvD15HhpJJBSKrdObFn.woff2) format('woff2');unicode-range:U+1780-17FF,U+200C,U+25CC}
@font-face{font-family:'Hanuman';font-style:normal;font-weight:700;src:local('Hanuman Bold'),local('Hanuman-Bold'),url(https://fonts.gstatic.com/s/hanuman/v12/VuJ0dNvD15HhpJJBQBr4LIVGZCNc.woff2) format('woff2');unicode-range:U+1780-17FF,U+200C,U+25CC}

/* Google Font - Ruda
----------------------------------------------- */
@font-face{font-family:'Ruda';font-style:normal;font-weight:400;font-display:swap;src:local('Ruda Regular'),local('Ruda-Regular'),url(https://fonts.gstatic.com/s/ruda/v10/k3kfo8YQJOpFqnYdaObJ.woff2) format('woff2');unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Ruda';font-style:normal;font-weight:400;font-display:swap;src:local('Ruda Regular'),local('Ruda-Regular'),url(https://fonts.gstatic.com/s/ruda/v10/k3kfo8YQJOpFqngdaA.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Ruda';font-style:normal;font-weight:700;font-display:swap;src:local('Ruda Bold'),local('Ruda-Bold'),url(https://fonts.gstatic.com/s/ruda/v10/k3kQo8YQJOpFosM4fdfoLnnA.woff2) format('woff2');unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Ruda';font-style:normal;font-weight:700;font-display:swap;src:local('Ruda Bold'),local('Ruda-Bold'),url(https://fonts.gstatic.com/s/ruda/v10/k3kQo8YQJOpFosM4fdnoLg.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Ruda';font-style:normal;font-weight:900;font-display:swap;src:local('Ruda Black'),local('Ruda-Black'),url(https://fonts.gstatic.com/s/ruda/v10/k3kQo8YQJOpFovs6fdfoLnnA.woff2) format('woff2');unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Ruda';font-style:normal;font-weight:900;font-display:swap;src:local('Ruda Black'),local('Ruda-Black'),url(https://fonts.gstatic.com/s/ruda/v10/k3kQo8YQJOpFovs6fdnoLg.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}

/* Reset Stylesheet
----------------------------------------------- */
a,abbr,acronym,address,applet,b,big,blockquote,body,caption,center,cite,code,dd,del,dfn,div,dl,dt,em,fieldset,font,form,h1,h2,h3,h4,h5,h6,html,i,iframe,img,ins,kbd,label,legend,li,object,p,pre,q,s,samp,small,span,strike,strong,sub,sup,table,tbody,td,tfoot,th,thead,tr,tt,u,ul,var{padding:0;border:0;outline:0;vertical-align:baseline;background:0 0;text-decoration:none}form,textarea,input,button{-webkit-appearance:none;-moz-appearance:none;appearance:none;border-radius:0}dl,ul{list-style-position:inside;font-weight:400;list-style:none}ul li{list-style:none}caption,th{text-align:center}img{border:none;position:relative}a,a:visited{text-decoration:none}.clearfix{clear:both}.section,.widget,.widget ul{margin:0;padding:0}a{color:$(body.link.color)}a img{border:0}abbr{text-decoration:none}.CSS_LIGHTBOX{z-index:999999!important}.separator a{clear:none!important;float:none!important;margin-left:0!important;margin-right:0!important}#navbar-iframe,.widget-item-control,a.quickedit,.home-link,.feed-links{display:none!important}.center{display:table;margin:0 auto;position:relative}.widget > h2,.widget > h3{display:none}

/* Globle Wrapper
----------------------------------------------- */
:root{--main-font:'Kdam Thmor','Ruda',sans-serif;--sub-font:Hanuman,'Ruda',sans-serif}
body{background:$(body.background);background-color:$(body.background.color);font-family:var(--sub-font);font-size:14px;font-weight:400;color:$(body.text.color);word-wrap:break-word;margin:0;padding:0}
#outer-wrapper{width:100%;max-width:calc(1060px + 40px);margin:0 auto;background-color:#2f2f2f;border-top:2px solid $(main.color);box-shadow:0 0 5px #111010}
.row{width:1060px}
#content-wrapper{margin:20px auto 0}
#content-wrapper > .container{margin:0 -15px;overflow:hidden}
#main-wrapper{float:left;overflow:hidden;width:67%;box-sizing:border-box;word-wrap:break-word;padding:0 15px;margin:0}
#sidebar-wrapper{float:right;overflow:hidden;width:33%;box-sizing:border-box;word-wrap:break-word;padding:0 15px}
.post-image-wrap{position:relative;display:block}
.post-image-link,.comments .avatar-image-container{background-color:rgba(155,155,155,0.07);color:transparent!important}
.post-thumb{display:block;position:relative;width:100%;height:100%;object-fit:cover;z-index:1;transition:opacity .17s ease}
.post-image-link:before{content:'';position:absolute;top:0;left:0;width:100%;height:100%;background-color:rgba(0,0,0,0.3);z-index:2;opacity:0;transition:all 0.7s}
.post-image-link:hover:before,.hot-posts .hot-item:hover .post-image-link:before{opacity:1}
.post-image-link:after{content:'\f04b';position:absolute;top:calc(50% - 19px);left:calc(50% - 19px);width:38px;height:38px;background-color:rgba(0,0,0,0.5);font-family:"Font Awesome 5 Free";font-size:14px;color:#fff;font-weight:600;text-align:center;line-height:33px;z-index:3;box-sizing:border-box;padding:0 0 0 3px;border:3px solid #fff;border-radius:50%;transition:all 0.7s}
.common-widget .PopularPosts .post-image-link:after,.custom-widget .post-image-link:after{top:calc(50% - 13px);left:calc(50% - 13px);width:30px;height:30px;font-size:11px;line-height:24px;padding:0 0 0 2px}
.post-image-link:hover:after,.hot-posts .hot-item:hover .post-image-link:after{background-color:$(main.color)}
.post-title{font-family:var(--main-font)}
.post-title a{display:block}
.post-title a:before{content:"\f192";font-family:"Font Awesome 5 Free";color:$(main.color);font-weight:400;margin:0 3px 0 0}
.bloggge{display:none;}.widd{display:none;}
/* Social Icons
----------------------------------------------- */
.social a:before{display:inline-block;font-family:"Font Awesome 5 Brands";font-style:normal;font-weight:400}
.social .blogger a:before{content:"\f37d"}
.social .facebook-square a:before{content:"\f082"}
.social .facebook-f a:before{content:"\f39e"}
.social .twitter a:before{content:"\f099"}
.social .twitter-square a:before{content:"\f081"}
.social .tumblr a:before{content:"\f173"}
.social .rss a:before{content:"\f09e";font-family:'Font Awesome 5 Free';font-weight:900}
.social .deviantart a:before{content:"\f1bd"}
.social .youtube a:before{content:"\f167"}
.social .github a:before{content:"\f09b"}
.social .linkedin a:before{content:"\f0e1"}
.social .instagram a:before{content:"\f16d"}
.social .pinterest-p a:before{content:"\f231"}
.social .reddit a:before{content:"\f281"}
.social .codepen a:before{content:"\f1cb"}
.social .whatsapp a:before{content:"\f232"}
.social .email a:before{content:"\f0e0";font-family:"Font Awesome 5 Free"}

/* Social Color
----------------------------------------------- */
.social-color .facebook-f a,.social-color .facebook-square a{background-color:#3b5999}
.social-color .twitter a,.social-color .twitter-square a{background-color:#00acee}
.social-color .reddit a{background-color:#ff4500}
.social-color .pinterest-p a{background-color:#ca2127}
.social-color .linkedin a{background-color:#0077b5}
.social-color .whatsapp a{background-color:#3fbb50}
.social-color .email a{background-color:#888}

/* Header Wrapper
----------------------------------------------- */
#header-wrap{position:relative;width:100%;height:70px;background-color:#171c24;z-index:1010;box-shadow:0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24)}
#header-wrap .container{position:relative;margin:0 auto}

/* Header Logo
----------------------------------------------- */
.header-logo{float:left;margin:0 20px 0 0}
.main-logo{position:relative;float:left;width:auto;max-width:250px;max-height:52px;margin:0;padding:9px 0}
.main-logo .header-image-wrapper{display:block}
.main-logo img{max-width:100%;max-height:52px;margin:0}
.main-logo h1,.main-logo h1 a{color:#1f2024;font-size:20px;line-height:52px;margin:0}
.main-logo p{font-size:12px;margin:5px 0 0;display:none}

/* Main Menu
----------------------------------------------- */
.header-menu{float:left}
#main-menu .widget,#main-menu .widget > h3{display:none}
#main-menu .show-menu{display:block}
#main-menu{position:static;width:100%;height:70px;z-index:15}
#main-menu ul > li{float:left;position:relative;margin:0;padding:0;transition:background .17s ease}
#main-menu ul > li > a{position:relative;font-family:var(--main-font);color:#ffffff;font-size:17px;font-weight:700;line-height:70px;display:inline-block;text-decoration:none;margin:0;padding:0 15px;transition:all 0.7s}
#main-menu ul#main-menu-nav > li:hover > a{color:$(main.color)}
#main-menu ul > li > ul{position:absolute;float:left;left:0;top:70px;width:200px;background-color:#2f2f2f;z-index:99999;margin:0;padding:0;border-bottom:2px solid $(main.color);box-shadow:0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);visibility:hidden;opacity:0;transform-origin:0 0;transform:scaleY(0)}
#main-menu ul > li > ul > li > ul{position:absolute;float:left;top:0;left:100%;margin:0;-webkit-transform:translateX(-10px);-moz-transform:translateX(-10px);transform:translateX(-10px)}
#main-menu ul > li > ul > li{display:block;float:none;position:relative;transition:all 0.7s}
#main-menu ul > li > ul > li a{display:block;height:45px;font-size:15px;color:#ffffff;font-weight:700;line-height:45px;box-sizing:border-box;margin:0;padding:0 15px;transition:all 0.7s}
#main-menu ul > li > ul > li:hover{background-color:rgba(0,0,0,0.2)}
#main-menu ul > li > ul > li a:hover{color:$(main.color)}
#main-menu ul > li > ul > li:last-child{border-bottom:0}
#main-menu ul > li.has-sub > a:after{content:'\f107';float:right;font-family:"Font Awesome 5 Free";font-size:12px;font-weight:600;margin:0 0 0 6px}
#main-menu ul > li > ul > li.has-sub > a:after{content:'\f105';float:right;margin:0}

/* Menu Icon
----------------------------------------------- */
.menu-iconx{font-size:14px;width:30px;height:30px;line-height:30px;text-align:center;background:$(main.color);color:#ffffff;display:inline-block;margin:0 5px 0 0;border-radius:100%}

/* Main Mega Menu
----------------------------------------------- */
#main-menu .mega-menu{position:static!important}
#main-menu .mega-menu > ul{width:100%;box-sizing:border-box;padding:20px 10px}
#main-menu .mega-menu > ul.mega-menu-inner{overflow:hidden}
#main-menu ul > li:hover > ul,#main-menu ul > li > ul > li:hover > ul{visibility:visible;opacity:1;transform:scaleY(1)}
#main-menu ul ul{transition:all 0.4s}
.mega-menu-inner .mega-item{position:relative;float:left;width:calc(100% / 6);overflow:visible;box-sizing:border-box;padding:0 10px}
.mega-menu-inner .mega-content{position:relative;float:left;width:100%;height:100%;overflow:hidden;display:block;box-sizing:border-box;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.mega-content .post-image-link{width:100%;height:180px;position:relative;overflow:hidden;display:block}
.mega-content .post-info{float:left;width:100%;min-height:59px;overflow:hidden;box-sizing:border-box;padding:10px;text-align:center}
.mega-content .post-title{font-size:13px;font-weight:500;line-height:1.5em;margin:0;display:-webkit-box;-webkit-box-orient:vertical;text-overflow:ellipsis;-webkit-line-clamp:2;overflow:hidden}
.mega-content .post-title a{display:block;color:#ffffff;transition:all 0.7s}
.mega-content:hover .post-title a{color:$(main.color)}
.no-posts{float:left;width:100%;height:100px;color:#ffffff;line-height:100px;text-align:center}
.mega-menu .no-posts{line-height:60px;color:#aaaaaa}

/* Search
----------------------------------------------- */
.show-search,.hide-search{position:absolute;top:0;right:0;display:block;width:58px;height:70px;line-height:70px;z-index:20;color:#ffffff;font-size:16px;font-weight:600;text-align:right;cursor:pointer;transition:all 0.7s}
.show-search:hover,.hide-search:hover{color:$(main.color)}
.show-search:before{content:"\f002";font-family:"Font Awesome 5 Free"}
.hide-search:before{content:"\f00d";font-family:"Font Awesome 5 Free"}
#nav-search{display:none;position:absolute;left:0;top:0;width:100%;height:70px;z-index:99;background-color:#171c24;box-sizing:border-box;padding:0}
#nav-search .search-form{width:100%;height:70px;background-color:rgba(0,0,0,0);line-height:70px;overflow:hidden;padding:0}
#nav-search .search-input{width:100%;height:70px;font-family:inherit;color:#ffffff;margin:0;padding:0 58px 0 0;background-color:rgba(0,0,0,0);font-size:13px;font-weight:400;box-sizing:border-box;border:0}
#nav-search .search-input:focus{color:#ffffff;outline:none}
#nav-search .search-input::placeholder{color:#ffffff;opacity:.5}

/* Mobile Menu
----------------------------------------------- */
.mobile-menu-toggle{display:none;position:absolute;top:0;left:0;width:58px;height:70px;line-height:70px;z-index:20;color:#ffffff;font-size:17px;font-weight:600;text-align:center;cursor:pointer;transition:all 0.7s}
.mobile-menu-toggle:hover{color:$(main.color)}
.mobile-menu-toggle:before{content:"\f0c9";font-family:"Font Awesome 5 Free"}
.nav-active .mobile-menu-toggle:before{content:"\f00d";font-family:"Font Awesome 5 Free"}
.overlay{display:none;position:fixed;top:0;left:0;right:0;bottom:0;z-index:990;background:rgba(255,255,255,0.8)}
.mobile-menu-wrap{display:none;position:absolute;top:70px;left:0;width:100%;background-color:#1f2024;box-sizing:border-box;visibility:hidden;z-index:1000;opacity:0;transition:all .17s ease}
.nav-active .mobile-menu-wrap{visibility:visible;opacity:1}
.mobile-menu{position:relative;overflow:hidden;padding:20px;border-top:1px solid rgba(255,255,255,0.03)}
.mobile-menu > ul{margin:0}
.mobile-menu .m-sub{display:none;padding:0}
.mobile-menu ul li{position:relative;display:block;overflow:hidden;float:left;width:100%;font-size:14px;line-height:45px}
.mobile-menu > ul > li{font-weight:600}
.mobile-menu > ul li ul{overflow:hidden}
.mobile-menu ul li a{color:#f2f2f2;padding:0;display:block;transition:all .17s ease}
.mobile-menu ul li.has-sub .submenu-toggle{position:absolute;top:0;right:0;color:#f2f2f2;cursor:pointer}
.mobile-menu ul li.has-sub .submenu-toggle:after{content:'\f105';font-family:"Font Awesome 5 Free";font-weight:600;float:right;width:34px;font-size:14px;text-align:center;transition:all .17s ease}
.mobile-menu ul li.has-sub.show > .submenu-toggle:after{transform:rotate(90deg)}
.mobile-menu > ul > li > ul > li > a{color:#f2f2f2;opacity:.7;padding:0 0 0 15px}
.mobile-menu > ul > li > ul > li > ul > li > a{color:#f2f2f2;opacity:.7;padding:0 0 0 30px}

/* Hot Featured
----------------------------------------------- */
#hot-wrapper{margin:0 auto}
#hot-section .widget,#hot-section .widget > .widget-title{display:none}
#hot-section .show-hot{display:block!important}
#hot-section .show-hot .widget-content{position:relative;overflow:visible;margin:20px 0 0}

/* Hot Loader
----------------------------------------------- */
.hot-loader{position:relative;height:100%;height:186px;overflow:hidden;display:block}
.hot-loader:after{content:'';position:absolute;top:50%;left:50%;width:26px;height:26px;margin:-15px 0 0 -15px;border:2px solid $(main.color);border-left-color:#f5f5f5;border-radius:100%;animation:spinner .8s infinite linear;transform-origin:center}
@-webkit-keyframes spinner {
0%{-webkit-transform:rotate(0deg);transform:rotate(0deg)}
to{-webkit-transform:rotate(1turn);transform:rotate(1turn)}
}
@keyframes spinner {
0%{-webkit-transform:rotate(0deg);transform:rotate(0deg)}
to{-webkit-transform:rotate(1turn);transform:rotate(1turn)}
}

/* Hot Content
----------------------------------------------- */
ul.hot-posts{position:relative;overflow:visible;margin:0 -10px}
.hot-posts .hot-item{position:relative;float:left;width:calc(100% / 6);overflow:visible;box-sizing:border-box;padding:0 10px}
.hot-item-inner{position:relative;float:left;width:100%;height:100%;overflow:hidden;display:block;box-sizing:border-box;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.hot-posts .post-image-link{width:100%;height:185px;position:relative;overflow:hidden;display:block}
.hot-posts .post-info{float:left;width:100%;min-height:59px;max-height:59px;overflow:hidden;box-sizing:border-box;padding:10px;text-align:center}
.hot-posts .post-title{font-size:13px;font-weight:500;line-height:1.5em;margin:0;display:-webkit-box;-webkit-box-orient:vertical;text-overflow:ellipsis;-webkit-line-clamp:2;overflow:hidden}
.hot-posts .post-title a{display:block;color:#ffffff;transition:all 0.7s}
.hot-item-inner:hover .post-title a{color:$(main.color)}
.show-hot .no-posts{position:absolute;top:calc(50% - 50px);left:0;width:100%;text-align:center}

/* Featured
----------------------------------------------- */
#feat-section .widget{display:none;float:left;width:100%;margin:0 0 20px}
#feat-section .widget.show-featured{display:block}
#feat-section .widget-content{position:relative;float:left;width:100%}
ul.featured-posts{display:flex;flex-wrap:wrap;margin:0 -10px}
.featured-posts .feat-item{width:calc(100% / 4);box-sizing:border-box;padding:0 10px;margin:20px 0 0}
.featured-posts .feat-item.item-0,.featured-posts .feat-item.item-1,.featured-posts .feat-item.item-2,.featured-posts .feat-item.item-3{margin:0}
.featured-item-inner{position:relative;float:left;width:100%;height:100%;overflow:hidden;display:block;box-sizing:border-box;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.featured-posts .post-image-link{width:100%;height:185px;position:relative;overflow:hidden;display:block}
.featured-posts .post-info{float:left;width:100%;min-height:59px;overflow:hidden;box-sizing:border-box;padding:10px;text-align:center}
.featured-posts .post-title{font-size:13px;font-weight:500;line-height:1.5em;margin:0;display:-webkit-box;-webkit-box-orient:vertical;text-overflow:ellipsis;-webkit-line-clamp:2;overflow:hidden}
.featured-posts .post-title a{display:block;color:#ffffff;transition:all 0.7s}
.featured-posts .feat-item:hover .post-title a{color:$(main.color)}
.bloggge{display:none;}.widd{display:none;}

/* Search Query
----------------------------------------------- */
.queryMessage{font-family:var(--main-font);overflow:hidden;background-color:#111111;color:#ffffff;font-size:14px;font-weight:400;padding:0 10px 0 0;height:40px;line-height:40px;margin:0 0 15px;text-overflow:ellipsis;white-space:nowrap;box-shadow:0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24)}
.queryMessage:before{content:"\f03d";font-family:"Font Awesome 5 Free";display:inline-block;text-align:center;font-weight:700;width:40px;height:40px;line-height:40px;background-color:#080808;box-sizing:border-box}
.queryMessage .query-info{margin:0 5px}
.queryMessage .search-query,.queryMessage .search-label{font-weight:700;text-transform:uppercase}
.queryMessage .search-query:before,.queryMessage .search-label:before{font-family:"Font Awesome 5 Free";content:"\f053";margin:0 3px 0 0}
.queryMessage .search-query:after,.queryMessage .search-label:after{font-family:"Font Awesome 5 Free";content:"\f054";margin:0 0 0 3px}
.queryEmpty{position:relative;overflow:hidden;font-family:var(--main-font);font-size:17px;font-weight:400;text-align:center;text-transform: capitalize;padding:10px 0;margin:10px}
.queryEmpty:before, .queryEmpty:after{position:absolute;content:'';top:50%;overflow:hidden;background-color:#888888;width:50%;height:2px}
.queryEmpty:before{margin-left:-51%}
.queryEmpty:after{margin-left:1%}

/* Robar
----------------------------------------------- */
.index .title-wrap{margin:0 0 15px 0}
.title-wrap{font-family:var(--main-font);position:relative;width:100%;height:40px;background-color:#111111;display:block;margin:0;box-shadow:0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24)}
.title-wrap:before{content:"\f03d";font-family:"Font Awesome 5 Free";float:left;display:inline-block;text-align:center;margin:0;font-weight:700;width:40px;height:40px;line-height:40px;background:rgba(0,0,0,0.5);box-sizing:border-box}
.title-wrap > h3{position:relative;float:left;display:block;height:40px;background:$(main.color);font-size:15px;color:#fff;font-weight:700;text-transform:capitalize;line-height:40px;padding:0 30px 0 10px;margin:0}
.title-wrap > h3:before{content:'';position:absolute;border-bottom:27px solid transparent;border-right:30px solid #111;border-top:0 solid transparent;border-left:0;right:0;top:0}
.title-wrap > h3:after{content:'';position:absolute;border-bottom:0 solid transparent;border-right:30px solid #111;border-top:27px solid transparent;right:0;bottom:0}

/* Post Episode
----------------------------------------------- */
.post_episode{position:absolute;width:100%;top:0;background-color:rgba(0,0,0,0.6);font-size:12px;color:#fff;font-weight:700;text-align:center;line-height:25px;z-index:2;box-sizing:border-box;border-top:1px solid $(main.color)}
.index-post .post_episode{visibility:hidden;opacity:0;transition:all 0.3s}
.index-post .post_episode.show{visibility:visible;opacity:1}

/* Show More
----------------------------------------------- */
.show-more{float:right;height:18px;background:$(main.color);color:#ffffff;font-size:10px;text-transform:uppercase;line-height:18px;padding:2px 5px;margin:9px;border-radius:2px;transition:all 0.7s}
.show-more:after{content:'\f105';font-family:"Font Awesome 5 Free";font-weight:600;margin:0 0 0 3px}
.show-more:hover{background-color:#333333;color:#ffffff}

/* Custom Widget
----------------------------------------------- */
.custom-widget li{float:left;width:calc(50% - 7.5px);margin:15px 0 0;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.custom-widget li:nth-child(2n){float:right}
.custom-widget li:nth-child(1),.custom-widget li:nth-child(2){margin:0}
.custom-widget .post-image-link{position:relative;width:100%;height:160px;float:left;overflow:hidden;display:block;vertical-align:middle}
.custom-widget .post-info{float:left;width:100%;min-height:59px;max-height:59px;overflow:hidden;box-sizing:border-box;padding:10px;text-align:center}
.custom-widget .post-title{font-size:13px;font-weight:500;line-height:1.5em;margin:0;display:-webkit-box;-webkit-box-orient:vertical;text-overflow:ellipsis;-webkit-line-clamp:2;overflow:hidden}
.custom-widget .post-title a{display:block;color:#ffffff;transition:all 0.7s}
.custom-widget li:hover .post-title a{color:$(main.color)}

/* Home Ads Slot
----------------------------------------------- */
.home-ad .widget > .widget-title{display:none}
.home-ad .widget{width:728px;max-width:100%;margin:0 auto}
.home-ad .widget .widget-content{position:relative;width:100%;max-height:100%;line-height:1;margin:0 0 20px}

/* Ads Content
----------------------------------------------- */
a.ads-here{display:block;background-color:#3f3f3f;text-align:center;font-size:16px;color:#fff;font-weight:700;font-style:italic;line-height:90px;box-shadow:0 1px 3px 0 rgba(0,0,0,0.3);transition:all 0.7s}
a.ads-here:hover{background-color:#2f2f2f;color:#fff}

/* Custom Ads Slot
----------------------------------------------- */
#custom-ads,#main-arel-ad{float:left;width:100%;opacity:0;visibility:hidden;margin:0}
#before-ad,#after-ad,#arel-ad{width:100%;margin:0}
#before-ad .widget > .widget-title,#after-ad .widget > .widget-title,#arel-ad .widget > .widget-title{display:block}
#before-ad .widget > .widget-title > h3.title,#after-ad .widget > .widget-title > h3.title,#arel-ad .widget > .widget-title > h3.title{font-size:12px;color:#aaaaaa;font-weight:400;line-height:12px;margin:0 0 5px}
#before-ad .widget{width:100%;margin:20px 0 20px}
#after-ad .widget{width:100%;margin:20px 0 10px}
#arel-ad .widget{width:100%;padding:0;margin:20px 0 0}
#before-ad .widget-content,#after-ad .widget-content,#arel-ad .widget-content{position:relative;width:100%;line-height:1}
#new-before-ad #before-ad,#new-after-ad #after-ad{float:none;display:block;margin:0}
#new-before-ad #before-ad .widget,#new-after-ad #after-ad .widget{margin:0}

/* Index Post Wrapper
----------------------------------------------- */
.index-post-wrap{display:flex;flex-wrap:wrap;margin:0 -10px}
.grid-posts{display:flex;flex-wrap:wrap}
.blog-post{display:block;overflow:hidden;word-wrap:break-word}
.index-post{float:left;width:calc(100% / 4);overflow:visible;margin:0 0 20px;box-sizing:border-box;padding:0 10px}
.index-post-inside-wrap{float:left;width:100%;height:auto;box-sizing:border-box;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.index-post .post-image-wrap{float:left;width:100%;height:auto;overflow:hidden;margin:0}
.index-post .post-image-wrap .post-image-link{width:100%;height:185px;position:relative;display:block;z-index:1;overflow:hidden}
.index-post .post-info{float:left;width:100%;min-height:59px;overflow:hidden;box-sizing:border-box;padding:10px;text-align:center}
.index-post .post-info > h2{font-size:13px;font-weight:500;line-height:1.5em;text-decoration:none;margin:0;display:-webkit-box;-webkit-box-orient:vertical;text-overflow:ellipsis;-webkit-line-clamp:2;overflow:hidden}
.index-post .post-info > h2 > a{display:block;color:#ffffff;transition:all 0.7s}
.index-post:hover .post-title a{color:$(main.color)}
.widget iframe,.widget img{max-width:100%}

/* Post Meta
----------------------------------------------- */
.post-meta{overflow:hidden;background-color:rgba(0,0,0,0.14);color:#aaaaaa;font-size:13px;font-weight:700;padding:15px;margin:0 0 15px 0;border-width:1px 0;border-style:solid;border-color:rgba(0,0,0,0.4)}
.post-meta .post-author,.post-meta .post-date,.post-meta .post-tag,.post-meta .post-view{float:left;display:inline-block;margin:0 10px 0 0}
.post-meta .post-author:before,.post-meta .post-date:before,.post-meta .post-tag:before,.post-meta .post-view:before{font-family:"Font Awesome 5 Free";color:$(main.color);font-weight:400;margin:0 3px 0 0}
.post-meta .post-author:before{content:'\f044'}
.post-meta .post-date:before{content:'\f017'}
.post-meta .post-tag:before{content:'\f07c'}
.post-meta .post-view:before{content:'\f06e'}
.post-meta a{color:#aaa;transition:all 0.7s}
.post-meta a:hover{color:$(main.color)}

/* Breadcrumb
----------------------------------------------- */
#breadcrumb{font-family:var(--main-font);background:#111111;font-size:14px;font-weight:700;color:#ffffff;padding:0;margin:0 0 15px 0;box-shadow:0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);text-overflow:ellipsis;white-space:nowrap;overflow:hidden}
#breadcrumb:before{content:"\f03d";font-family:"Font Awesome 5 Free";display:inline-block;text-align:center;margin-right:8px;font-weight:700;width:40px;height:40px;line-height:40px;background-color:#080808;box-sizing:border-box}
#breadcrumb a{color:#ffffff;transition:all 0.7s}
#breadcrumb a:hover{color:$(main.color)}
#breadcrumb a,#breadcrumb em{display:inline-block}
#breadcrumb .delimiter:after{content:'\f054';font-family:"Font Awesome 5 Free";font-size:8px;font-weight:600;font-style:normal;vertical-align:middle;margin:0 3px}

/* Items Post Wrapper
----------------------------------------------- */
.item-post h1.post-title{color:#ffffff;font-size:17px;text-align:center;line-height:1.4em;font-weight:600;position:relative;display:block;padding:0;margin:0 0 15px;white-space:nowrap;text-overflow:ellipsis;overflow:hidden}
.item-post h1.post-title:before, .item-post h1.post-title:after{position:absolute;content:'';top:50%;overflow:hidden;background-color:#666666;width:50%;height:2px;margin-top:0;background-image:linear-gradient(to right,rgba(0,0,0,0),$(main.color),rgba(0,0,0,0))}
.item-post h1.post-title:before{margin-left:-51%;text-align:right}
.item-post h1.post-title:after{margin-left:1%;text-align:left}
.static_page .item-post{margin:0 0 20px}
.static_page .item-post .post-body{padding:0 20px 20px}
.item-post{background:#2f2f2f;box-sizing:border-box;padding:0;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.item-post .post-body{width:100%;font-size:15px;line-height:1.6em;overflow:hidden;box-sizing:border-box;padding:0;margin:0}
.item-post .post-outer{padding:0}
.item-post .post-body img{max-width:100%}
.main .widget{margin:0}
.main .Blog{border-bottom-width:0}
.post-footer{position:relative;float:left;width:100%;margin:10px 0 0}
.inline-ad{position:relative;display:block;max-height:60px;margin:0 0 20px}
.inline-ad > ins{display:block!important;margin:0 auto!important}
.item .inline-ad{float:left;width:100%;margin:20px 0 0}
.item-post-wrap > .inline-ad{margin:0 0 20px}

/* Post Share
----------------------------------------------- */
.post-share{position:relative;width:100%;overflow:hidden;box-sizing:border-box;padding:15px;margin:0}
ul.share-links{position:relative}
.share-links li{float:left;width:calc((100% - 20px) / 5);overflow:hidden;margin:0 5px 0 0;box-shadow: 0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.share-links li a{display:block;width:100%;height:30px;line-height:30px;color:#fff;font-size:15px;font-weight:400;cursor:pointer;text-align:center;border-radius:3px;transition:all 0.7s}
.share-links li a:hover{background:#3f3f3f;color:#fff}
.share-links li.show-hid{margin:0}
.share-links .show-hid a{background-color:rgba(155,155,155,0.2);font-size:14px;color:#aaaaaa}
.share-links .show-hid a:before{content:'\f067';font-family:'Font Awesome 5 Free';font-weight:900}
.show-hidden .show-hid a:before{content:'\f068'}
.show-hidden li{width:calc((100% - 35px) / 8)}
.share-links li.linkedin,.share-links li.reddit,.share-links li.pinterest-p{display:none}
.show-hidden li.linkedin,.show-hidden li.reddit,.show-hidden li.pinterest-p{display:inline-block}

/* Author Bio
----------------------------------------------- */
.about-author{background:#3f3f3f;position:relative;display:block;overflow:hidden;padding:15px;margin:0 0 20px;border-top:3px solid $(main.color);border-bottom:1px solid #1f1f1f}
.about-author .avatar-container{background:#2f2f2f;position:relative;float:left;width:115px;height:115px;overflow:hidden;margin:0 15px 0 0;padding:6px;box-sizing:border-box}
.about-author .author-avatar{float:left;width:100%;height:100%}
.author-name{font-family:var(--main-font);overflow:hidden;font-weight:700;margin:0}
.author-name:after{font-family:"Font Awesome 5 Free";content:'\f058';font-size:16px;font-weight:600;color:$(main.color);margin:0 0 0 2px}
.author-name span{color:#ffffff}
.author-name a{color:$(main.color);transition:all 0.7s}
.author-name a:hover{color:#ffffff}
.author-description{display:block;overflow:hidden;background:#2f2f2f;font-size:14px;font-weight:400;padding:10px;margin:10px 0 0 0;line-height:1.5em;border:1px solid #3f3f3f;box-sizing:border-box;border-radius:3px}
.author-description a:hover{$(main.color)}

/* Related Posts
----------------------------------------------- */
#related-wrap{overflow:hidden;margin:0}
#related-wrap .related-tag{display:none}
.related-ready{float:left;width:100%;padding:15px;box-sizing:border-box}
.related-ready .loader{height:178px}
ul.related-posts{position:relative;overflow:visible;margin:0 -10px;padding:0}
.related-posts .related-item-inner{position:relative;display:block;overflow:hidden;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.related-posts .related-item{width:calc(100% / 4);position:relative;overflow:visible;float:left;display:block;box-sizing:border-box;padding:0 10px;margin:0}
.related-posts .post-image-link{width:100%;height:180px;position:relative;overflow:hidden;display:block}
.related-posts .post-info{float:left;width:100%;min-height:59px;max-height:59px;overflow:hidden;box-sizing:border-box;padding:10px;text-align:center}
.related-posts .post-title{font-size:13px;font-weight:500;line-height:1.5em;margin:0;display:-webkit-box;-webkit-box-orient:vertical;text-overflow:ellipsis;-webkit-line-clamp:2;overflow:hidden}
.related-posts .post-title a{display:block;color:#ffffff;transition:all 0.7s}
.related-posts .related-item:hover .post-title a{color:$(main.color)}

/* Page Navigation
----------------------------------------------- */
#blog-pager{width:100%;overflow:hidden;text-align:center;clear:both;margin:0 0 20px}
.blog-pager a,.blog-pager span{display:inline-block;min-width:32px;height:32px;background-color:#3f3f3f;color:#888;font-size:13px;font-weight:600;line-height:32px;text-align:center;box-sizing:border-box;padding:0 10px;margin:5px;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12);border-radius:3px;transition:all 0.7s}
.blog-pager span.page-dots{min-width:32px;font-size:16px;color:#888888;font-weight:400;line-height:32px;padding:0;border:0}
.blog-pager .page-of{display:none;width:auto;float:right;border-color:rgba(0,0,0,0);margin:0}
.blog-pager .page-active,.blog-pager a:hover{background-color:$(main.color);color:#fff}
.blog-pager .page-prev:before,.blog-pager .page-next:before{font-family:"Font Awesome 5 Free";font-size:11px;font-weight:600}
.blog-pager .page-prev:before{content:'\f053'}
.blog-pager .page-next:before{content:'\f054'}
.blog-pager .blog-pager-newer-link,.blog-pager .blog-pager-older-link{float:left;display:inline-block;width:auto;padding:0 10px;margin:0}
.blog-pager .blog-pager-older-link{float:right}
.archive #blog-pager,.home .blog-pager .blog-pager-newer-link,.home .blog-pager .blog-pager-older-link{display:none}

/* Comments
----------------------------------------------- */
.blog-post-comments{display:none;overflow:hidden;margin:20px 0 20px 0;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.blog-post-comments .comments-title{margin:0 0 20px}
.comments-system-disqus .comments-title,.comments-system-facebook .comments-title{margin:0}
#disqus_thread{float:left;width:100%;padding:10px 15px;box-sizing:border-box}
.blog-post-comments .fb_iframe_widget{box-sizing:border-box;padding:0 5px}
#comments{margin:0}
#gpluscomments{float:left!important;width:100%!important;margin:0 0 25px!important}
#gpluscomments iframe{float:left!important;width:100%}
.comments{display:block;clear:both;padding:0 15px;margin:0;color:#ffffff}
.comments .comment-thread > ol{padding:0}
.comments > h3{font-size:13px;font-weight:400;font-style:italic;padding-top:1px}
.comments .comments-content .comment{list-style:none;margin:0;padding:0 0 8px}
.comments .comments-content .comment:first-child{padding-top:0}
.facebook-tab,.fb_iframe_widget_fluid span,.fb_iframe_widget iframe{width:100%!important}
.comments .item-control{position:static}
.comments .avatar-image-container{float:left;overflow:hidden;position:absolute}
.comments .avatar-image-container,.comments .avatar-image-container img{height:35px;max-height:35px;width:35px;max-width:35px;border-radius:100%}
.comments .comment-block{overflow:hidden;padding:15px;border-top:2px solid #3f3f3f;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.comments .comment-block,.comments .comments-content .comment-replies{margin:0 0 0 50px}
.comments .comments-content .inline-thread{padding:30px 0 0}
.comments .comment-actions{float:left;width:100%;position:relative;margin:0 0 5px 0}
.comments .comments-content .comment-header{font-family:var(--main-font);font-size:15px;display:block;overflow:hidden;clear:both;margin:0 0 3px;padding:0 0 5px}
.comments .comments-content .comment-header a{color:#ffffff;transition:all 0.7s}
.comments .comments-content .comment-header a:hover{color:$(main.color)}
.comments .comments-content .user{font-family:var(--main-font);font-style:normal;font-weight:400;display:inline-block}
.comments .comments-content .icon.blog-author{display:nonee}
.comments .icon:after{content:"\f058";font-family:"Font Awesome 5 Free";color:$(main.color);font-weight:600;padding:0 5px;margin:0}
.comments .comments-content .comment-content{background:rgba(155,155,155,0.02);display:block;font-size:15px;color:#aaaaaa;font-weight:400;text-align:left;line-height:1.6em;padding:15px;margin:0 0 15px;border:1px solid rgba(155,155,155,0.22);border-radius:3px}
.comments .comment .comment-actions a{margin-right:10px;padding:6px 15px;background:#3f3f3f;color:#ffffff;font-weight:400;font-size:12px;transition:all 0.7s;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12);border-radius:99em}
.comments .comment .comment-actions a:hover{color:#fff;background-color:$(main.color);border-color:$(main.color);text-decoration:none}
.comments .comments-content .datetime{float:right;font-size:11px;font-weight:400;color:#aaa;position:relative;padding:0 1px;margin:0;display:block}
.comments .comments-content .datetime a,.comments .comments-content .datetime a:hover{color:#aaa}
.comments .thread-toggle{margin-bottom:4px}
.comments .thread-toggle .thread-arrow{height:7px;margin:0 3px 2px 0}
.comments .thread-count a,.comments .continue a{transition:opacity .17s}
.comments .thread-count a:hover,.comments .continue a:hover{opacity:.8}
.comments .continue a{display:none}
.comments .thread-expanded{padding:5px 0 0}
.comments .thread-chrome.thread-collapsed{display:none}
.thread-arrow:before{content:'';font-family:"Font Awesome 5 Free";color:#ffffff;font-weight:400;margin:0 2px 0 0}
.comments .thread-expanded .thread-arrow:before{content:'\f0d7'}
.comments .thread-collapsed .thread-arrow:before{content:'\f0da'}
.comments .comments-content .comment-thread{margin:0}
.comments .continue a{padding:0 0 0 60px;font-weight:400}
.comments .comments-content .loadmore.loaded{margin:0;padding:0}
.comments .comment-replybox-thread{margin:0}
p.comments-message{font-size:14px;color:#aaaaaa;font-style:italic}
.thread-expanded .thread-count,.thread-expanded .thread-arrow,.comments .comments-content .loadmore,.comments .comments-content .loadmore.loaded{display:none}
#comment-editor{margin:0 0 20px}

/* Post Body
----------------------------------------------- */
.post-body h1,.post-body h2,.post-body h3,.post-body h4,.post-body h5,.post-body h6{color:#ffffff;font-weight:600;margin:0 0 15px}
.post-body h1,.post-body h2{font-size:24px}
.post-body h3{font-size:21px}
.post-body h4{font-size:18px}
.post-body h5{font-size:16px}
.post-body h6{font-size:13px}
.widget .post-body ul,.widget .post-body ol{line-height:1.5;font-weight:400}
.widget .post-body li{margin:5px 0;padding:0;line-height:1.5}
.post-body ul{padding:0}
.post-body ul li:before{font-family:"Font Awesome 5 Free";font-size:13px;font-weight:600;margin:0 5px 0 0}
.post-body u{text-decoration:underline}
.post-body a{transition:color .17s ease}
.post-body strike{text-decoration:line-through}

/* Blockquote
----------------------------------------------- */
blockquote{font-style:italic;padding:10px;margin:0;border-left:4px solid $(main.color)}
blockquote:before,blockquote:after{display:inline-block;font-family:"Font Awesome 5 Free";font-style:normal;font-weight:600;color:#aaa;line-height:1}
blockquote:before{content:'\f10d';margin:0 10px 0 0}
blockquote:after{content:'\f10e';margin:0 0 0 10px}

/* Sidebar Wrapper
----------------------------------------------- */
.sidebar .widget{position:relative;overflow:hidden;background-color:#2f2f2f;box-sizing:border-box;padding:0;margin:0 0 20px;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.sidebar .widget-title{font-family:var(--main-font);position:relative;float:left;width:100%;height:40px;background-color:#111111;display:block;margin:0;box-shadow:0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24)}
.sidebar .widget-title:before{content:"\f03d";font-family:"Font Awesome 5 Free";float:left;display:inline-block;text-align:center;margin:0;font-weight:700;width:40px;height:40px;line-height:40px;background:rgba(0,0,0,0.5);box-sizing:border-box}
.sidebar .widget-title > h3{position:relative;float:left;display:block;height:40px;background:$(main.color);font-size:15px;color:#fff;font-weight:700;line-height:40px;padding:0 30px 0 10px;margin:0}
.sidebar .widget-title > h3:before{content:'';position:absolute;border-bottom:27px solid transparent;border-right:30px solid #111;border-top:0 solid transparent;border-left:0;right:0;top:0}
.sidebar .widget-title > h3:after{content:'';position:absolute;border-bottom:0 solid transparent;border-right:30px solid #111;border-top:27px solid transparent;right:0;bottom:0}
.sidebar .widget-content{float:left;width:100%;margin:0;box-sizing:border-box;padding:15px}

/* Sidebar Tab
----------------------------------------------- */
#seth-sidebar-tabs{display:none;position:relative;box-sizing:border-box;padding:0;margin:0 0 20px}
#seth-sidebar-tabs .widget-content{border:0}
.seth-sidebar-tabs .select-tab{position:relative;height:40px;line-height:40px;background-color:#111111;overflow:hidden;box-sizing:border-box;margin:2px -1px;border-top:2px solid $(main.color);box-shadow:0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24)}
.seth-sidebar-tabs .select-tab li{position:relative;float:left;display:inline-block;width:100%;height:40px;font-size:15px;color:#ffffff;font-weight:700;line-height:40px;text-align:center;cursor:pointer;list-style:none;margin:0;padding:0;transition:all 0.7s}
.tabs-1 .select-tab li{position:relative;float:left;width:auto}
.tabs-1 .select-tab li,.tabs-1 .select-tab li a{width:100%;cursor:auto}
.tabs-2 .select-tab li{width:50%}
.tabs-3 .select-tab li{width:calc(100% / 3)}
.seth-sidebar-tabs .select-tab li > a{color:#ffffff;display:block;padding:0}
.seth-sidebar-tabs .select-tab li.active,.seth-sidebar-tabs .select-tab li.active:hover,.seth-sidebar-tabs .select-tab li:hover{background-color:#1f2024}
.seth-sidebar-tabs .widget{display:none}
.seth-sidebar-tabs .tab-active{display:block}
.seth-sidebar-tabs .widget{margin:0}
.seth-sidebar-tabs > .widget > .widget-title{display:none}

/* Tab Animated Fade Up
----------------------------------------------- */
.tab-active{display:block}
.tab-animated{-webkit-animation-duration:.5s;animation-duration:.5s;-webkit-animation-fill-mode:both;animation-fill-mode:both}
@keyframes tab-fadeIn{from{opacity:0}to{opacity:1}}
.tab-fadeIn{animation-name:tab-fadeIn}
@keyframes tab-fadeInUp{from{opacity:0;transform:translate3d(0,5px,0)}to{opacity:1;transform:translate3d(0,0,0)}}
.tab-fadeInUp{animation-name:tab-fadeInUp}

/* Social Counter
----------------------------------------------- */
#social-section .widget-content{padding:15px 10px 25px}
ul.social-counter{display:block;text-align:center;margin:0}
.social-counter li{display:inline-block;width:34px;margin:10px 5px 0}
.social-counter li a{display:block;height:34px;background-color:rgba(155,155,155,0.2);font-size:14px;color:#ffffff;line-height:34px;padding:0;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12);border-radius:100%;transition:all 0.7s}
.social-counter li a:hover{background-color:$(main.color);color:#fff}

/* List Label
----------------------------------------------- */
.list-label li{position:relative;display:block;padding:11px 0;border-top:1px solid rgba(0,0,0,0.07)}
.list-label li:first-child{padding-top:0;border-top:0}
.list-label li:last-child{padding-bottom:0;border-bottom:0}
.list-label li a{display:block;font-family:var(--main-font);color:#ffffff;font-size:13px;font-weight:400;text-transform:capitalize;transition:all 0.7s}
.list-label li a:before{content:"\f07c";font-family:"Font Awesome 5 Free";margin:0 3px 0 0;font-weight:500}
.list-label li a:hover{color:$(main.color)}
.list-label .label-count{position:relative;float:right;background-color:rgba(155,155,155,0.02);color:#ffffff;font-size:12px;font-weight:400;text-align:center;line-height:15px;padding:0 7px;box-sizing:border-box;border:1px solid rgba(155,155,155,0.22)}

/* Cloud Label
----------------------------------------------- */
.cloud-label li{position:relative;float:left;margin:0 8px 8px 0}
.cloud-label li a{display:block;font-family:var(--main-font);height:26px;background-color:#3f3f3f;color:#ffffff;font-size:12px;line-height:26px;font-weight:400;padding:0 10px;border-radius:3px;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12);transition:all 0.7s}
.cloud-label li a:before{content:"\f07c";font-family:"Font Awesome 5 Free";margin:0 3px 0 0;font-weight:500}
.cloud-label li a:hover{color:#fff;background-color:$(main.color);border-color:$(main.color)}
.cloud-label .label-count{display:none}

/* Follow by Email
----------------------------------------------- */
.sidebar .FollowByEmail > .widget-title > h3{margin:0}
.FollowByEmail .widget-content{position:relative;overflow:hidden;text-align:center;font-weight:400;box-sizing:border-box;padding:20px}
.FollowByEmail .widget-content > h3{font-size:17px;color:$(main.color);font-weight:600;margin:0 0 13px}
.FollowByEmail .before-text{font-size:13px;color:#aaa;line-height:1.5em;margin:0 0 15px;display:block;padding:0 10px;overflow:hidden}
.FollowByEmail .follow-by-email-inner{position:relative}
.FollowByEmail .follow-by-email-inner .follow-by-email-address{width:100%;height:32px;background-color:rgba(0, 0, 0, .3);color:#ffffff;font-size:11px;font-family:inherit;padding:0 10px;margin:0 0 10px;box-sizing:border-box;border:1px solid rgba(0, 0, 0, .3);border-radius:3px;transition:all 0.7s}
.FollowByEmail .follow-by-email-inner .follow-by-email-submit{width:100%;height:32px;font-family:inherit;font-size:11px;color:#fff;background-color:$(main.color);text-transform:uppercase;text-align:center;font-weight:600;cursor:pointer;margin:0;border:0;border-radius:3px;transition:all 0.7s}
.FollowByEmail .follow-by-email-inner .follow-by-email-submit:hover{background-color:#1f2024}

/* Archive
----------------------------------------------- */
#ArchiveList ul.flat li{color:#ffffff;font-size:13px;font-weight:400;padding:7px 0;border-bottom:1px solid #eaeaea}
#ArchiveList ul.flat li:first-child{padding-top:0}
#ArchiveList ul.flat li:last-child{padding-bottom:0;border-bottom:0}
#ArchiveList .flat li > a{display:block;color:#ffffff;transition:color .17s}
#ArchiveList .flat li > a:hover{color:$(main.color)}
#ArchiveList .flat li > a:before{content:"\f054";font-family:"Font Awesome 5 Free";float:left;color:#ffffff;font-weight:600;font-size:6px;margin:6px 3px 0 0;display:inline-block;transition:all 0.7s}
#ArchiveList .flat li > a > span{position:relative;float:right;width:16px;height:16px;background-color:$(main.color);color:#fff;font-size:11px;font-weight:400;text-align:center;line-height:16px}

/* Popular Posts
----------------------------------------------- */
.PopularPosts .post{float:left;width:calc(50% - 7.5px);margin:15px 0 0;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.PopularPosts .post:nth-child(2n){float:right}
.PopularPosts .post:nth-child(1),.PopularPosts .post:nth-child(2){margin:0}
.PopularPosts .post-image-link{position:relative;width:100%;height:160px;float:left;overflow:hidden;display:block;vertical-align:middle}
.PopularPosts .post-info{float:left;width:100%;min-height:59px;max-height:59px;overflow:hidden;box-sizing:border-box;padding:10px;text-align:center}
.PopularPosts .post-title{font-size:13px;font-weight:500;line-height:1.5em;margin:0;display:-webkit-box;-webkit-box-orient:vertical;text-overflow:ellipsis;-webkit-line-clamp:2;overflow:hidden}
.PopularPosts .post-title a{display:block;color:#ffffff;transition:all 0.7s}
.PopularPosts .post:hover .post-title a{color:$(main.color)}

/* Featured Post
----------------------------------------------- */
.FeaturedPost .post-image-link{display:block;position:relative;width:100%;height:300px;overflow:hidden}
.FeaturedPost .post-info{float:left;width:100%;min-height:59px;max-height:59px;overflow:hidden;box-sizing:border-box;padding:10px;text-align:center;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}
.FeaturedPost .post-title{font-size:15px;font-weight:500;line-height:1.5em;margin:0;display:-webkit-box;-webkit-box-orient:vertical;text-overflow:ellipsis;-webkit-line-clamp:2;overflow:hidden}
.FeaturedPost .post-title a{color:#ffffff;display:block;transition:all 0.7s}
.FeaturedPost:hover .post-title a{color:$(main.color)}
.Text{font-size:13px}

/* Contact Form
----------------------------------------------- */
.contact-form{overflow:hidden}
.contact-form .widget-title{display:none}
.contact-form .contact-form-name{width:calc(50% - 5px)}
.contact-form .contact-form-email{width:calc(50% - 5px);float:right}
.contact-form-widget{float:left;width:100%;box-sizing:border-box;padding:0}
.contact-form-widget form{font-weight:400}
.contact-form-widget form > span{color:red}
.contact-form-name{float:left;width:100%;height:40px;font-family:inherit;background-color:rgba(0,0,0,0.5);color:#fff;font-size:13px;line-height:40px;box-sizing:border-box;padding:5px 10px;margin:0 0 10px;border:1px solid rgba(0,0,0,0.7);border-radius:3px}
.contact-form-email{float:left;width:100%;height:40px;font-family:inherit;background-color:rgba(0,0,0,0.5);color:#fff;font-size:13px;line-height:40px;box-sizing:border-box;padding:5px 10px;margin:0 0 10px;border:1px solid rgba(0,0,0,0.7);border-radius:3px}
.contact-form-email-message{float:left;width:100%;height:300px;font-family:inherit;background-color:rgba(0,0,0,0.5);color:#fff;font-size:13px;box-sizing:border-box;padding:5px 10px;margin:0 0 10px;border:1px solid rgba(0,0,0,0.7);border-radius:3px}
.contact-form-button-submit{float:left;width:100%;height:45px;background-color:$(main.color);font-family:inherit;font-size:13px;color:#fff;line-height:45px;cursor:pointer;box-sizing:border-box;padding:0 10px;margin:0;border:0;border-radius:3px;transition:all 0.7s}
.contact-form-button-submit:hover{background-color:#1f2024}
.contact-form-error-message-with-border{float:left;width:100%;background-color:#ff0000;font-size:13px;text-align:center;line-height:11px;padding:10px 0;margin:10px 0;box-sizing:border-box;border:1px solid #ff0000;border-radius:99em}
.contact-form-success-message-with-border{float:left;width:100%;background-color:#0cc12f;font-size:13px;text-align:center;line-height:11px;padding:10px 0;margin:10px 0;box-sizing:border-box;border:1px solid #0cc12f;border-radius:99em}
.contact-form-cross{margin:0 0 0 3px}
.contact-form-error-message,.contact-form-success-message{margin:0}

/* Blog Search
----------------------------------------------- */
.BlogSearch .search-input{float:left;width:75%;height:30px;background-color:#fff;font-weight:400;font-family:inherit;font-size:13px;line-height:30px;box-sizing:border-box;padding:5px 10px;border:1px solid #ebebf3;border-right-width:0;border-radius:3px 0 0 3px}
.BlogSearch .search-action{float:right;width:25%;height:30px;font-family:inherit;font-size:13px;line-height:30px;cursor:pointer;box-sizing:border-box;background-color:$(main.color);color:#fff;padding:0 5px;border:0;border-radius:0 3px 3px 0;transition:background .17s ease}
.BlogSearch .search-action:hover{background-color:#1f2024}

/* Profile
----------------------------------------------- */
.Profile .profile-img{float:left;width:80px;height:80px;margin:0 15px 0 0;transition:all .17s ease}
.Profile .profile-datablock{margin:0}
.Profile .profile-data .g-profile{display:block;font-size:18px;color:#ffffff;font-weight:700;margin:0 0 5px;transition:color .17s ease}
.Profile .profile-data .g-profile:hover{color:$(main.color)}
.Profile .profile-info > .profile-link{color:#ffffff;font-size:11px;margin:5px 0 0;transition:color .17s ease}
.Profile .profile-info > .profile-link:hover{color:$(main.color)}
.Profile .profile-datablock .profile-textblock{display:none}

/* Common Widget
----------------------------------------------- */
.common-widget .LinkList ul li,.common-widget .PageList ul li{width:calc(50% - 5px);padding:7px 0 0}
.common-widget .LinkList ul li:nth-child(odd),.common-widget .PageList ul li:nth-child(odd){float:left}
.common-widget .LinkList ul li:nth-child(even),.common-widget .PageList ul li:nth-child(even){float:right}
.common-widget .LinkList ul li a,.common-widget .PageList ul li a{display:block;color:#ffffff;font-size:13px;font-weight:400;transition:color .17s ease}
.common-widget .LinkList ul li a:hover,.common-widget .PageList ul li a:hover{color:$(main.color)}
.common-widget .LinkList ul li:first-child,.common-widget .LinkList ul li:nth-child(2),.common-widget .PageList ul li:first-child,.common-widget .PageList ul li:nth-child(2){padding:0}

/* Footer Wrapper
----------------------------------------------- */
.borderxt-bar{background: url(https://1.bp.blogspot.com/-eYtRPgDYrj8/U2UzqPx7GQI/AAAAAAAADq8/2ziclERqoQU/s600/from_blog_divider.png) repeat-x;height:8px;margin:0}
#footer-wrapper{display:block;width:100%;overflow:hidden;background-color:#1f2024;padding:0}
#footer-wrapper .container{overflow:hidden;margin:0 auto;padding:25px 0}
#footer-wrapper .copyright-area{float:left;font-size:13px;display:block;height:34px;color:#ffffff;font-weight:700;line-height:34px}
#footer-wrapper .copyright-area a{color:$(main.color);transition:all 0.7s}
#footer-wrapper .copyright-area a:hover{opacity:0.6}

/* Menu Footer
----------------------------------------------- */
#menu-footer{float:right;position:relative;display:block}
#menu-footer .widget > .widget-title{display:none}
#menu-footer ul li{float:left;display:inline-block;height:34px;padding:0;margin:0}
#menu-footer ul li a{font-size:13px;font-weight:700;display:block;color:#ffffff;line-height:34px;padding:0 10px;margin:0 0 0 5px;transition:all 0.7s}
#menu-footer ul li:last-child a{padding:0 0 0 5px}
#menu-footer ul li a:hover{color:$(main.color)}

/* Hidden Widget
----------------------------------------------- */
.hidden-widgets{display:none;visibility:hidden}

/* Main Player
----------------------------------------------- */
.rst_player{height:100%;overflow:hidden;font-size:12px}
.rst_player *{margin:0;padding:0}
.rst_video{width:100%;background-color:#000;position:relative;overflow:hidden}
.rst_video iframe{width:100%;height:100%;position:absolute;top:0;left:0;display:none;background-color:#000}
.rst_server{width:100%;height:100%;position:absolute;top:0;left:0;display:none}
.rst_server video{width:100%;height:100%;background-color:#000}
.rst_list{width:100%;overflow:auto;background-color:#000}
.rst_list li{list-style:none;clear:both;border:1px dashed #333;border-left:5px solid #444;overflow:hidden;cursor:pointer}
.rst_list .selected{border-left:5px solid $(main.color);background-color:#222222;border-right:3px solid $(main.color)}
.rst_list .selected div h2:after{font-family:"Font Awesome 5 Free";content:"\f144";font-size:12px;font-weight:600;margin:0 0 0 5px;animation:flash 2s infinite}
.rst_list img{float:left;width:80px;height:50px;margin:0 10px 0 0}
.rst_list div h2{width:100%;color:#fff;font-size:120%;font-weight:400;line-height:50px;text-align:left;margin:0}
.rst_control{width:100%;height:55px;line-height:53px;text-align:center;background:#3f3f3f;border-bottom:1px solid #1f1f1f}
.rst_control .active{background-color:#000}
.rst_button{background-color:$(main.color);color:#fff;padding:8px 14px;cursor:pointer;margin:0 4px;border-radius:3px;box-shadow:0px 2px 4px -1px rgba(0, 0, 0, 0.2), 0px 4px 5px 0px rgba(0, 0, 0, 0.14), 0px 1px 10px 0px rgba(0, 0, 0, 0.12)}

/* Loading Player
----------------------------------------------- */
.rst_loading{position:absolute;text-align:center;font-size:200%;z-index:9999;display:none;width:100%;height:100%}
.st_loading{position:absolute;top:50%;left:50%;width:20px;height:20px;transform:translate(-50%,-50%)}
.st_loading .circlex{position:absolute;border-radius:50%;left:1px;top:1px;width:18px;height:18px;background:#fff;animation:spinVideoFirstTurn 1.5s 0s infinite both}
.st_loading .circley{position:absolute;border-radius:50%;width:20px;height:20px;background:$(main.color);animation:spinVideoSecondTurn 1.4s 0s infinite both}

/* Player Video Icons
----------------------------------------------- */
.rst_player i.fab.fa-google-drive, .rst_player i.fab.fa-youtube, .rst_player i.fab.fa-vimeo, .rst_player i.fab.fa-facebook-square, .rst_player i.fab.fa-odnoklassniki, .rst_player i.fab.fa-firefox, .rst_player i.fas.fa-video{background:#ffffff;width:25px;height:25px;line-height:25px;text-align:center;border-radius:3px;margin:0 5px 0 0}
.rst_player i.fab.fa-google-drive{color:#2c9f45}
.rst_player i.fab.fa-youtube{color:#DA5E4C}
.rst_player i.fab.fa-vimeo{color:#1ab7ea}
.rst_player i.fab.fa-facebook-square{color:#3b5998}
.rst_player i.fab.fa-odnoklassniki{color:#ee8208}
.rst_player i.fab.fa-firefox{color:#9C27B0}
.rst_player i.fas.fa-video{color:#F06292;font-size:12px}

/* Player Animation
----------------------------------------------- */
@-webkit-keyframes flash{0%,100%,50%{opacity:1}25%,75%{opacity:0}}
@keyframes flash{0%,100%,50%{opacity:1}25%,75%{opacity:0}}
@keyframes spinVideoFirstTurn{0%,100%{box-shadow:0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color)}50%{transform:rotate(180deg)}25%,75%{box-shadow:28px 0 0 $(main.color),-28px 0 0 $(main.color),0 28px 0 $(main.color),0 -28px 0 $(main.color),20px -20px 0 $(main.color),20px 20px 0 $(main.color),-20px -20px 0 $(main.color),-20px 20px 0 $(main.color)}100%{transform:rotate(360deg);box-shadow:0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color)}}
@keyframes spinVideoSecondTurn{0%,100%{box-shadow:0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color)}50%{transform:rotate(-180deg)}25%,75%{box-shadow:52px 0 0 $(main.color),-52px 0 0 $(main.color),0 52px 0 $(main.color),0 -52px 0 $(main.color),38px -38px 0 $(main.color),38px 38px 0 $(main.color),-38px -38px 0 $(main.color),-38px 38px 0 $(main.color);background:transparent}100%{transform:rotate(-360deg);box-shadow:0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color),0 0 0 $(main.color)}}

/* Back to Top
----------------------------------------------- */
.back-top{display:none;z-index:1010;width:34px;height:34px;position:fixed;bottom:25px;right:25px;cursor:pointer;overflow:hidden;font-size:13px;color:#fff;text-align:center;line-height:34px;box-shadow:0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);border-radius:3px}
.back-top:before{content:'';position:absolute;top:0;left:0;right:0;bottom:0;background-color:$(main.color);transition:all 0.7s}
.back-top:after{content:'\f077';position:relative;font-family:"Font Awesome 5 Free";font-weight:600;transition:all 0.7s}
.back-top:hover:before{background-color:#444444}

/* Custom Scrollbar
----------------------------------------------- */
body::-webkit-scrollbar{width:12px;}
body::-webkit-scrollbar-track{background-color:rgba(0, 0, 0, 0.4)}
body::-webkit-scrollbar-thumb{background-color:$(main.color)}

/* Error 404
----------------------------------------------- */
.error404 #main-wrapper{width:100%!important;margin:0!important}
.error404 #sidebar-wrapper{display:none}
.errorWrap{color:#ffffff;text-align:center;padding:80px 0 100px}
.errorWrap h3{font-size:160px;line-height:1;margin:0 0 30px}
.errorWrap h4{font-size:25px;margin:0 0 20px}
.errorWrap p{margin:0 0 10px}
.errorWrap a{display:inline-block;height:32px;background-color:$(main.color);font-size:14px;color:#ffffff;font-weight:400;line-height:32px;padding:0 30px;margin:15px 0 0;box-shadow:0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);border-radius:2px;transition:all 0.7s}
.errorWrap a:hover{background-color:#212121;color:#ffffff}

/* Responsive Media Queries
----------------------------------------------- */
@media screen and (max-width:1100px){
  #outer-wrapper{max-width:100%}
  .row{width:100%}
  #header-wrap{box-sizing:border-box;padding:0 20px}
  #hot-wrapper{box-sizing:border-box;padding:0 10px}
  #content-wrapper{position:relative;box-sizing:border-box;padding:0 10px;margin:20px 0 0}
  #footer-wrapper .container{box-sizing:border-box;padding:10px 20px}
}
@media screen and (max-width:980px){
  #content-wrapper > .container{margin:0;overflow:visible}
  #header-wrap{padding:0}
  #header-inner a{display:inline-block!important}
  .header-logo,.main-logo{width:100%;max-width:100%;text-align:center;margin:0}
  .show-search,.hide-search{width:auto;padding:0 20px;text-align:center}
  #nav-search .search-input{padding:0 50px 0 20px}
  .header-menu{display:none}
  .mobile-menu-wrap,.mobile-menu-toggle{display:block}
  #nav-search .search-input{padding:0 58px 0 20px}
  #hot-section .show-hot .widget-content,ul.hot-posts{height:auto}
  .hot-posts .hot-item{width:calc(100% / 3);margin-bottom:20px}
  .hot-posts .hot-item.item-3,.hot-posts .hot-item.item-4,.hot-posts .hot-item.item-5{margin:0}
  .hot-posts .post-image-link{height:auto}
  #main-wrapper,#sidebar-wrapper{width:100%;padding:0}
}
@media screen and (max-width: 780px){
  #menu-footer,#footer-wrapper .copyright-area{width:100%;height:auto;line-height:1.7em;text-align:center}
  #menu-footer{margin:10px 0 0}
  #footer-wrapper .copyright-area{margin:15px 0 10px}
  #menu-footer ul li{float:none;height:auto}
  #menu-footer ul li a{line-height:inherit;margin:0 3px 5px}
}
@media screen and (max-width:680px){
  .home-ad .widget .widget-content{max-height:none}
  .grid-posts{margin:0 5px}
  .index-post{width:50%;padding:0 5px;margin:0 0 10px}
  .index-post .post-image-wrap{height:170px}
}
@media screen and (max-width:580px){
  #nav-search{width:100%}
  ul.hot-posts{margin:0 -5px}
  .hot-posts .hot-item{width:50%;padding:0 5px;margin:0}
  .hot-posts .item-2,.hot-posts .item-3,.hot-posts .item-4,.hot-posts .item-5{margin-top:10px!important}
  .hot-posts .post-image-link{height:170px}
  ul.featured-posts{margin:0 -5px}
  .featured-posts .feat-item{width:50%;padding:0 5px;margin:0}
  .featured-posts .feat-item.item-2,.featured-posts .feat-item.item-3{margin:10px 0 0 0}
  .featured-posts .post-image-wrap{height:170px}
  ul.related-posts{margin:0 -5px}
  .related-ready{padding:10px}
  .related-posts .related-item{width:50%;padding:0 5px;margin-bottom:10px}
  .related-posts .item-2,.related-posts .item-3{margin:0}
  .related-posts .post-image-link{height:155px}
}
@media screen and (max-width:440px){
  .about-author{text-align:center}
  .about-author .avatar-container{float:none;display:table;margin:0 auto 10px}
  #comments ol{padding:0}
  .errorWrap{padding:50px 0 70px}
  .errorWrap h3{font-size:100px}
}
@media screen and (max-width:360px){
  .about-author .avatar-container{width:90px;height:85px}
}
]]></b:skin>
<b:if cond='data:view.isLayoutMode'>
<b:template-skin>
<![CDATA[
body#layout #outer-wrapper,body#layout .row{width:auto;padding:0}
body#layout{width:910px;position:relative;padding:95px 5px 0;margin:0}
body#layout:before{content:'Topflix By Destroyer Theme - Version 1.0.0';position:absolute;top:0;left:5px;right:5px;height:95px;font-family:Roboto,sans-serif;font-size:23px;color:#3c97ef;line-height:95px;text-align:center}
body#layout div.section{background-color:#fff;margin:0 5px 10px!important;padding:16px 16px 18px!important}
body#layout .section h4{position:relative;overflow:hidden;font-size:14px;text-align:center;color:coral;font-weight:500;margin:0}
body#layout .section h4:before, body#layout .section h4:after{position:absolute;content:'';top:50%;overflow:hidden;background-color:rgba(0, 0, 0, 0.06);width:50%;height:2px;margin-top:0}
body#layout .section h4:before{margin-left:-51%;text-align:right}
body#layout .section h4:after{margin-left:1%;text-align:left}
body#layout .add_widget a{color:#3c97ef}
body#layout .layout-widget-description{display:none}
body#layout .visibility .editlink{background:#3c97ef url(https://1.bp.blogspot.com/-qg15_Zo9hrA/XWtyvfUUKrI/AAAAAAAAAbM/M1vvLugG2C4Z_T-BEQR3e4jW8qtSsNMRACLcBGAs/s18-c/mode_edit_w600_24dp.png) no-repeat center!important;border-radius:3px}
body#layout .draggable-widget .widget-wrap2{background:#3c97ef url(https://1.bp.blogspot.com/-yBT7kInN160/XWtyvanCw-I/AAAAAAAAAbI/IAp8kvBW1q0Bbi_tdkZmUsmUXxGmpasLACLcBGAs/s22/draggable.png) no-repeat 4px 50%!important}
body#layout .visibility .layout-widget-state.visible{background-image:url(https://1.bp.blogspot.com/-BM-7-H4uOP0/XWtyvfhjJRI/AAAAAAAAAbQ/VirxQ-s8Yu8sMMS6IpbDeCnjOuBfT3VPgCLcBGAs/s1600/visibility_color600_24dp.png)!important}
body#layout .visibility .layout-widget-state.not-visible{background-image:url(https://1.bp.blogspot.com/-zNtH1zipjhM/XWtywE93CyI/AAAAAAAAAbU/N_J0spFe_Ncwb1T6Rq0QRd-QuzkA0WRdQCLcBGAs/s1600/visibility_off_color600_24dp.png)!important;opacity:1}
body#layout .theme-options,body#layout #main-menu .widget{display:block!important}
body#layout div.seth-panel{background-color:#d7d7d7!important;overflow:hidden!important;border-color:#bcbcbc}
body#layout .seth-panel .widget{float:left;width:32%;margin-right:2%}
body#layout .seth-panel #LinkList71{margin-right:0}
body#layout #header-wrap{height:auto}
body#layout .header-header{float:left;width:100%;height:auto;padding:0}
body#layout .header-header .container{display:flex}
body#layout div.header-logo,body#layout div.main{float:none}
body#layout #header-wrap > .container{display:flex}
body#layout div.header-logo,body#layout div.header-menu{float:none;width:50%;max-width:none;max-height:none;margin:0}
body#layout .main-logo{float:none;max-width:none;max-height:none}
body#layout .mobile-menu-wrap,body#layout .show-search{display:none}
body#layout #main-menu{height:auto}
body#layout #hot-wrapper .widget{display:block}
body#layout #content-wrapper{margin:0}
body#layout #content-wrapper > .container{display:flex;margin:0}
body#layout #main-wrapper{width:60%;padding:0}
body#layout #sidebar-wrapper{width:40%;padding:0}
body#layout #custom-ads{display:block!important;display:flex!important}
body#layout #custom-ads .section{width:42%}
body#layout .sidebar .widget,body#layout .sidebar .widget-content{float:none;width:auto;overflow:visible}
]]></b:template-skin>
</b:if>

<script type='text/javascript'>
//<![CDATA[
var getPlayerOptions ={playerContainer:"#videox_player",playerRatio:"16:9",playerMobile:"600",playerDesktop:"70%",playerResponsive:false},
	playerLogo = "https://1.bp.blogspot.com/-8TcMxpoFBI8/XXfVXz0RfoI/AAAAAAAAAgg/AIlcAyY03T4N2Hy0U1C6yJzmXFVEMzfEgCLcBGAs/s1600/video_logo.jpg",
	noThumbnail = "https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w680/nth.png",
    postPerPage = 12,
    commentsSystem = "blogger",
    disqusShortname = "templates";
//]]>
</script>

<b:defaultmarkups>
  <b:defaultmarkup type='Common'>
    <b:includable id='widget-title'>
      <b:if cond='data:defaultTitle or data:title'>
        <div class='widget-title'>
          <h3 class='title'>
            <data:title/>
          </h3>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='themeHead'>
      <meta expr:content='&quot;text/html; charset=&quot; + data:blog.encoding' http-equiv='Content-Type'/>
      <meta content='blogger' name='generator'/>
      <link expr:href='data:blog.blogspotFaviconUrl' rel='icon' type='image/x-icon'/>
      <meta expr:content='data:skin.vars.keycolor' name='theme-color'/>
      <meta expr:content='data:skin.vars.keycolor' name='msapplication-navbutton-color'/>
      <b:if cond='data:blog.adultContent'>
        <meta content='adult' name='rating'/>
      </b:if>
      <link expr:href='data:view.url.canonical' rel='canonical'/>
      <data:blog.feedLinks/><data:blog.openIdOpTag/><data:blog.meTag/>
      <meta expr:content='data:view.description.escaped' name='description'/>
      <b:tag cond='data:view.isMultipleItems and data:widgets.Blog.first.posts[0].featuredImage' expr:href='data:widgets.Blog.first.posts[0].featuredImage resizeImage 680' name='link' rel='image_src'/>
      <b:tag cond='data:view.isSingleItem and data:view.featuredImage' expr:href='data:view.featuredImage resizeImage 680' name='link' rel='image_src'/>
      <b:include name='customOpenGraphMetaData'/>
    </b:includable>
    <b:includable id='customOpenGraphMetaData'>
      <!-- Metadata for Open Graph protocol. See http://ogp.me/. -->
      <b:if cond='data:view.isHomepage'>
        <meta content='website' property='og:type'/>
      </b:if>
      <b:if cond='data:view.isSingleItem'>
        <meta content='article' property='og:type'/>
      </b:if>
      <b:if cond='data:view.isMultipleItems and not data:view.isHomepage'>
        <meta content='object' property='og:type'/>
      </b:if>    
      <meta expr:content='data:view.title.escaped' property='og:title'/>
      <meta expr:content='data:blog.url.canonical' property='og:url'/>
      <meta expr:content='data:view.description.escaped' property='og:description'/>
      <meta expr:content='data:blog.title.escaped' property='og:site_name'/>
      <b:tag cond='data:view.isMultipleItems and data:widgets.Blog.first.posts[0].featuredImage' expr:href='data:widgets.Blog.first.posts[0].featuredImage resizeImage 680' name='meta' property='og:image'/>
      <b:if cond='data:view.featuredImage'>
        <meta expr:content='data:view.featuredImage resizeImage 680' property='og:image'/>
        <meta expr:content='data:view.featuredImage resizeImage 680' name='twitter:image'/>
      </b:if>
      <meta content='summary' name='twitter:card'/>
      <meta expr:content='data:view.title.escaped' name='twitter:title'/>
      <meta expr:content='data:blog.url.canonical' name='twitter:domain'/>
      <meta expr:content='data:view.description.escaped' name='twitter:description'/>
      <b:if cond='data:view.isHomepage'>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;name&quot;:&quot;<data:view.title.escaped/>&quot;,&quot;url&quot;:&quot;<data:view.url.canonical/>&quot;,&quot;potentialAction&quot;:{&quot;@type&quot;:&quot;SearchAction&quot;,&quot;target&quot;:&quot;<data:view.url.canonical/>search?q={search_term_string}&quot;,&quot;query-input&quot;:&quot;required name=search_term_string&quot;}}</script>
      </b:if>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='PopularPosts'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='postContent'/>
        </b:loop>
      </div>
    </b:includable>
    <b:includable id='postContent' var='post'>
      <div class='post'>
        <div class='post-content'>
          <a class='post-image-link' expr:href='data:post.url'>
            <b:if cond='data:post.featuredImage'>
              <img class='post-thumb' expr:alt='data:post.title' expr:src='data:post.featuredImage resizeImage 680'/>
              <b:else/>
              <img class='post-thumb' expr:alt='data:post.title' src='https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w680/nth.png'/>
            </b:if>
          </a>
          <div class='post-info'>
            <h2 class='post-title'>
              <a expr:href='data:post.url'><data:post.title/></a>
            </h2>
          </div>
        </div>
      </div>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Header'>
    <b:includable id='main' var='this'>
      <div class='header-widget'>
  <b:includable id='description'>
          <!-- Don't show description on the item page -->
          <b:include cond='not data:view.isSingleItem' name='super.description'/>
        </b:includable>
        <b:include cond='data:imagePlacement in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='image'/>
        <b:include cond='data:imagePlacement == &quot;BEHIND&quot;' name='title'/>
      </div>
    </b:includable>
    <b:includable id='image'>
      <a class='header-image-wrapper' expr:href='data:blog.homepageUrl'>
        <img expr:alt='data:blog.title.escaped' expr:data-height='data:height' expr:data-width='data:width' expr:src='data:image'/>
      </a>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='FeaturedPost'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='postContent'/>
        </b:loop>
      </div>
    </b:includable>
    <b:includable id='postContent' var='post'>
      <div class='post'>
        <div class='post-content'>
          <a class='post-image-link' expr:href='data:post.url'>
            <b:if cond='data:post.featuredImage'>
              <img class='post-thumb' expr:alt='data:post.title' expr:src='data:post.featuredImage resizeImage 680'/>
              <b:else/>
              <img class='post-thumb' expr:alt='data:post.title' src='https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w680/nth.png'/>
            </b:if>
          </a>
          <div class='post-info'>
            <h2 class='post-title'>
              <a expr:href='data:post.url'><data:post.title/></a>
            </h2>
          </div>
        </div>
      </div>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Label'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <b:class expr:name='data:this.display + &quot;-label&quot;'/>
        <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
        <b:include cond='data:this.display == &quot;cloud&quot;' name='list'/>
      </div>
    </b:includable>
    <b:includable id='list'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <a class='label-name' expr:href='data:label.url'>
              <data:label.name/>
              <b:if cond='data:this.showFreqNumbers'>
                <span class='label-count'><data:label.count/></span>
              </b:if>
            </a>
          </li>
        </b:loop>
      </ul>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='FollowByEmail'>
    <b:includable id='main' var='this'>
	  <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <span class='before-text'><data:skin.vars.followByEmail/></span>
        <div class='follow-by-email-inner'>
          <form action='https://feedburner.google.com/fb/a/mailverify' expr:onsubmit='&quot;window.open(\&quot;https://feedburner.google.com/fb/a/mailverify?uri=&quot; + data:feedPath + &quot;\&quot;, \&quot;popupwindow\&quot;, \&quot;scrollbars=yes,width=550,height=520\&quot;); return true&quot;' method='post' target='popupwindow'>
            <input autocomplete='off' class='follow-by-email-address' expr:placeholder='data:messages.emailAddress' name='email' type='email'/>
            <input class='follow-by-email-submit' expr:value='data:messages.subscribe' type='submit'/>
            <input expr:value='data:feedPath' name='uri' type='hidden'/>
            <input name='loc' type='hidden' value='en_US'/>
          </form>
        </div>
      </div>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='BlogSearch'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content' role='search'>
        <form class='search-form' expr:action='data:blog.searchUrl'>
          <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
          <b:include name='urlParamsAsFormInput'/>
          <input autocomplete='off' class='search-input' expr:aria-label='data:messages.searchThisBlog' expr:placeholder='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q'/>
          <input class='search-action' expr:value='data:messages.search.escaped' type='submit'/>  
        </form>
      </div>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='BlogArchive'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <div id='ArchiveList'>
          <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
            <b:include cond='data:this.style in {&quot;FLAT&quot;, &quot;MENU&quot;, &quot;HIERARCHY&quot;}' name='flat'/>
          </div>
        </div>
      </div>
    </b:includable>
    <b:includable id='flat'>
      <ul class='flat'>
        <b:loop values='data:data' var='i'>
          <li class='archivedate'>
            <a expr:href='data:i.url'>
              <data:i.name/><span class='post-count'><data:i.post-count/></span>
            </a>
          </li>
        </b:loop>
      </ul>
    </b:includable>
  </b:defaultmarkup>
</b:defaultmarkups>

    <!-- Google Analytics -->
    <b:include data='blog' name='google-analytics'/>

</head>
<body expr:class='data:blog.pageType'>
  <b:class cond='data:view.isHomepage' name='home'/>
  <b:class cond='data:view.isPage' name='item'/>
  <b:class cond='data:view.isArchive' name='index'/>
  <b:class cond='data:view.isError' name='error404'/>

<!-- Theme Options -->
  <div class='theme-options' style='display:none'>
    <b:section class='seth-panel' id='seth-panel' maxwidgets='1' name='Theme Options' showaddelement='no'>
      <b:widget id='HTML150' locked='true' title='Facebook SDK' type='HTML' version='2' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='content'>&lt;div id=&quot;fb-root&quot;&gt;&lt;/div&gt;
&lt;script async defer crossorigin=&quot;anonymous&quot; src=&quot;https://connect.facebook.net/en_US/sdk.js#xfbml=1&amp;version=v4.0&quot;&gt;&lt;/script&gt;</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
          <b:include name='content'/>
        </b:includable>
        <b:includable id='content'>
          <div class='widget-content'>
            <data:content/>
          </div>
        </b:includable>
      </b:widget>
      <b:widget id='HTML151' locked='true' title='Hide Post Image' type='HTML' version='2' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='content'/>
        </b:widget-settings>
        <b:includable id='main'>
          <b:include name='content'/>
        </b:includable>
        <b:includable id='content'>
          <b:if cond='data:content != &quot;&quot;'>
            <b:if cond='data:content == &quot;true&quot;'>
              &lt;style type=&#39;text/css&#39;&gt;
                  .separator{display:none}
              &lt;/style&gt;
            </b:if>
          </b:if>
        </b:includable>
      </b:widget>
      <b:widget id='LinkList71' locked='true' title='Default Variables' type='LinkList' version='2' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='link-3'>9</b:widget-setting>
          <b:widget-setting name='sorting'>NONE</b:widget-setting>
          <b:widget-setting name='text-1'>commentsSystem</b:widget-setting>
          <b:widget-setting name='link-1'>blogger</b:widget-setting>
          <b:widget-setting name='text-0'>disqusShortname</b:widget-setting>
          <b:widget-setting name='link-2'>true</b:widget-setting>
          <b:widget-setting name='text-3'>postPerPage</b:widget-setting>
          <b:widget-setting name='link-0'/>
          <b:widget-setting name='text-2'>fixedSidebar</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
          <b:include name='content'/>
        </b:includable>
        <b:includable id='content'>
          &lt;script type=&#39;text/javascript&#39;&gt;
          //&lt;![CDATA[
          <b:loop values='data:links' var='link'>
            <b:if cond='data:link.name == &quot;postPerPage&quot;'>
              var postPerPage = <data:link.target/>;
            </b:if>
            <b:if cond='data:link.name == &quot;fixedSidebar&quot;'>
              var fixedSidebar = <data:link.target/>;
            </b:if>
            <b:if cond='data:link.name == &quot;commentsSystem&quot;'>
              var commentsSystem = &quot;<data:link.target/>&quot;;
            </b:if>
            <b:if cond='data:link.name == &quot;disqusShortname&quot;'>
              var disqusShortname = &quot;<data:link.target/>&quot;;
            </b:if>
          </b:loop>
          //]]&gt;
          &lt;/script&gt;
        </b:includable>
      </b:widget>
    </b:section>
  </div>

<!-- Outer Wrapper -->
<div id='outer-wrapper'>
  <!-- Header Wrapper -->
  <div id='header-wrap'>
    <div class='mobile-menu-wrap'>
      <div class='mobile-menu'/>
    </div>
    <div class='container row'>
      <div class='header-logo'>    
        <b:section class='main-logo' id='main-logo' maxwidgets='1' name='Header Logo' showaddelement='yes'>
              <b:widget id='Header1' locked='true' title='TendKotta (Header)' type='Header' version='2' visible='true'>
                <b:widget-settings>
                  <b:widget-setting name='displayUrl'>http://4.bp.blogspot.com/-6J49VyDEPmw/YJtWXrW0h2I/AAAAAAAAA2c/MRir5cFTZ2As3RbtIlEPA6o1i8M7LNQ-ACK4BGAYYCw/s1600/Logopit_1620450233534.png</b:widget-setting>
                  <b:widget-setting name='displayHeight'>312</b:widget-setting>
                  <b:widget-setting name='sectionWidth'>150</b:widget-setting>
                  <b:widget-setting name='useImage'>true</b:widget-setting>
                  <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
                  <b:widget-setting name='imagePlacement'>BEFORE_DESCRIPTION</b:widget-setting>
                  <b:widget-setting name='displayWidth'>820</b:widget-setting>
                </b:widget-settings>
                <b:includable id='main' var='this'>
      <div class='header-widget'>
        <b:include cond='data:imagePlacement in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='image'/>
        <b:include cond='data:imagePlacement == &quot;BEHIND&quot;' name='title'/>
<b:include cond='not data:view.isSingleItem' name='super.description'/>
      </div>
    </b:includable>
                <b:includable id='behindImageStyle'>
    <b:if cond='data:sourceUrl'>
      <b:include cond='data:this.image' data='{                    image: data:this.image,                    selector: &quot;.header-widget&quot;                  }' name='responsiveImageStyle'/>
      <style type='text/css'>
        .header-widget {
          background-position: <data:blog.locale.languageAlignment/>;
          background-repeat: no-repeat;
        }
      </style>
    </b:if>
  </b:includable>
                <b:includable id='description'>
          <!-- Don't show description on the item page -->
          <b:include cond='not data:view.isSingleItem' name='super.description'/>
        </b:includable>
                <b:includable id='image'>
      <a class='header-image-wrapper' expr:href='data:blog.homepageUrl'>
        <img expr:alt='data:blog.title.escaped' expr:data-height='data:height' expr:data-width='data:width' expr:src='data:image'/>
      </a>
    </b:includable>
                <b:includable id='title'>
    <h1>
      <b:tag cond='data:view.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
        <data:title/>
      </b:tag>
    </h1>
  </b:includable>
              </b:widget>
            </b:section>
      </div>
      <div class='header-menu'>
        <b:section class='main-menu' id='main-menu' maxwidgets='1' name='Main Menu' showaddelement='yes'>
          <b:widget id='LinkList74' locked='true' title='Link List' type='LinkList' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='text-1'>Movies</b:widget-setting>
              <b:widget-setting name='link-1'><![CDATA[https://tendkotta.blogspot.com/search/label/Movie?&max-results=12&m=1]]></b:widget-setting>
              <b:widget-setting name='text-0'>Home</b:widget-setting>
              <b:widget-setting name='link-2'><![CDATA[https://tendkotta.blogspot.com/search/label/Series?&max-results=12&m=1]]></b:widget-setting>
              <b:widget-setting name='link-0'>/</b:widget-setting>
              <b:widget-setting name='text-2'>Web Series</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
              <b:include name='content'/>
            </b:includable>
            <b:includable id='content'>
              <ul id='main-menu-nav' role='menubar'>
                <b:loop values='data:links' var='link'>
                  <li><a expr:href='data:link.target' role='menuitem'><data:link.name/></a></li>
                </b:loop>
              </ul>
            </b:includable>
          </b:widget>
        </b:section>
      </div>
      <div id='nav-search'>
        <form class='search-form' expr:action='data:blog.searchUrl' role='search'>
          <input autocomplete='off' class='search-input' expr:placeholder='data:messages.searchThisBlog' name='q' type='search' value=''/>
          <span class='hide-search'/>
        </form>
      </div>
      <span class='show-search'/>
      <span class='mobile-menu-toggle'/> 
    </div>
  </div>

  <div class='clearfix'/>

  <b:if cond='data:view.isHomepage'> 
    <!-- Featured Wrapper -->
    <div class='row' id='hot-wrapper'>
      <b:section id='hot-section' maxwidgets='1' name='Hot Posts' showaddelement='yes'>
        <b:widget id='HTML2' locked='false' title='Ad !' type='HTML' visible='false'>
          <b:widget-settings>
            <b:widget-setting name='content'>random/hot-posts</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
        </b:widget>
      </b:section>
    </div>
    <div class='clearfix'/>
  </b:if>

  <!-- Content Wrapper -->
  <div class='row' id='content-wrapper'>
    <div class='container'>
      <!-- Main Wrapper -->
      <div id='main-wrapper'>
        <b:if cond='data:view.isHomepage'>
          <b:section class='home-ad' id='home-ad-1' maxwidgets='1' name='Home Ads (A)' showaddelement='yes'>
            <b:widget id='HTML33' locked='false' title='Advertisement' type='HTML' version='2' visible='false'>
              <b:widget-settings>
                <b:widget-setting name='content'><![CDATA[<a class="ads-here">Your Sponsor Size ( 728 x Auto)</a>]]></b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
                <b:include name='widget-title'/>
                <div class='widget-content'>
                  <data:content/>
                </div>
              </b:includable>
            </b:widget>
          </b:section>
          <div class='clearfix'/>
          <b:section class='feat-section' id='feat-section' name='Featured Section' showaddelement='yes'>
            <b:widget id='Navbar1' locked='false' title='Navbar' type='Navbar' version='2' visible='true'>
              <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/plusone.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
      gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
        if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
          gapi.iframes.getContext().openChild({
              url: &#39;https://www.blogger.com/navbar.g?targetBlogID\x3d3994216326338721649\x26blogName\x3dTendKotta\x26publishMode\x3dPUBLISH_MODE_BLOGSPOT\x26navbarType\x3dLIGHT\x26layoutType\x3dLAYOUTS\x26searchRoot\x3dhttps://tendkotta.blogspot.com/search\x26blogLocale\x3den\x26v\x3d2\x26homepageUrl\x3dhttp://tendkotta.blogspot.com/\x26vt\x3d-4136317489386059469&#39;,
              where: document.getElementById(&quot;navbar-iframe-container&quot;),
              id: &quot;navbar-iframe&quot;
          });
        }
      });
    &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
            </b:widget>
            <b:widget id='HTML102' locked='false' title='Top of the week' type='HTML' version='1'>
              <b:widget-settings>
                <b:widget-setting name='content'><![CDATA[<script src="/feeds/posts/default/-/Featured?published&amp;alt=json-in-script&amp;callback=labelthumbs" type="text/javascript"></script>]]></b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
    <div class='heading-underline'/>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
            </b:widget>
            <b:widget id='Label5' locked='false' title='GENRES' type='Label' version='1'>
              <b:widget-settings>
                <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
                <b:widget-setting name='display'>LIST</b:widget-setting>
                <b:widget-setting name='selectedLabelsList'>Action Movie,Business,Comedy,Games</b:widget-setting>
                <b:widget-setting name='showType'>USER_SELECTED</b:widget-setting>
                <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <b:if cond='data:title'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
      <b:loop values='data:labels' var='label'>
        <li>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </li>
      </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
            </b:widget>
            <b:widget id='Label4' locked='false' title='Labels' type='Label' version='1'>
              <b:widget-settings>
                <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
                <b:widget-setting name='display'>LIST</b:widget-setting>
                <b:widget-setting name='selectedLabelsList'/>
                <b:widget-setting name='showType'>ALL</b:widget-setting>
                <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <b:if cond='data:title'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
      <b:loop values='data:labels' var='label'>
        <li>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </li>
      </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
            </b:widget>
            <b:widget id='FeaturedPost1' locked='false' title='Featured Post' type='FeaturedPost' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='showSnippet'>false</b:widget-setting>
                <b:widget-setting name='showPostTitle'>true</b:widget-setting>
                <b:widget-setting name='postId'>1868216740851593749</b:widget-setting>
                <b:widget-setting name='showFirstImage'>true</b:widget-setting>
                <b:widget-setting name='useMostRecentPost'>false</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='postContent'/>
        </b:loop>
      </div>
    </b:includable>
              <b:includable id='postContent' var='post'>
      <div class='post'>
        <div class='post-content'>
          <a class='post-image-link' expr:href='data:post.url'>
            <b:if cond='data:post.featuredImage'>
              <img class='post-thumb' expr:alt='data:post.title' expr:src='data:post.featuredImage resizeImage 680'/>
              <b:else/>
              <img class='post-thumb' expr:alt='data:post.title' src='https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w680/nth.png'/>
            </b:if>
            <span class='post-tag'><data:post.labels.last.name/></span>
          </a>
          <div class='post-info'>
            <h2 class='post-title'>
              <a expr:href='data:post.url'><data:post.title/></a>
            </h2>
            <div class='post-meta'>
              <span class='post-date published' expr:datetime='data:post.date.iso8601'><data:post.date/></span>
            </div>
          </div>
        </div>
      </div>
    </b:includable>
            </b:widget>
            <b:widget id='BlogSearch1' locked='false' title='Search This Blog' type='BlogSearch' visible='true'>
              <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
              <b:includable id='content'>
      <div class='widget-content' role='search'>
        <form class='search-form' expr:action='data:blog.searchUrl'>
          <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
          <b:include name='urlParamsAsFormInput'/>
          <input autocomplete='off' class='search-input' expr:aria-label='data:messages.searchThisBlog' expr:placeholder='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q'/>
          <input class='search-action' expr:value='data:messages.search.escaped' type='submit'/>  
        </form>
      </div>
    </b:includable>
              <b:includable id='searchForm'>
  <form expr:action='data:blog.searchUrl'>
    <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
    <b:include name='urlParamsAsFormInput'/>
    <div class='search-input'>
      <input autocomplete='off' expr:aria-label='data:messages.searchThisBlog' expr:placeholder='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q'/>
    </div>
    <b:include name='searchSubmit'/>
  </form>
</b:includable>
              <b:includable id='searchSubmit'>
  <input class='search-action' expr:value='data:messages.search.escaped' type='submit'/>
</b:includable>
            </b:widget>
            <b:widget id='AdSense1' locked='false' title='' type='AdSense' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                <b:widget-setting name='style.textcolor'>#5872ff</b:widget-setting>
                <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                <b:widget-setting name='style.urlcolor'>#3f51b5</b:widget-setting>
                <b:widget-setting name='style.linkcolor'>#030d17</b:widget-setting>
                <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <div class='widget-content'>
    <b:if cond='data:adCode'>
      <data:adCode/>
    <b:else/>
      <b:include name='defaultAdUnit'/>
    </b:if>
  </div>
</b:includable>
            </b:widget>
            <b:widget id='BlogArchive1' locked='false' title='Blog Archive' type='BlogArchive' version='1'>
              <b:widget-settings>
                <b:widget-setting name='showStyle'>MENU</b:widget-setting>
                <b:widget-setting name='yearPattern'>yyyy</b:widget-setting>
                <b:widget-setting name='showWeekEnd'>true</b:widget-setting>
                <b:widget-setting name='monthPattern'>MMMM yyyy</b:widget-setting>
                <b:widget-setting name='dayPattern'>MMM dd</b:widget-setting>
                <b:widget-setting name='weekPattern'>MM/dd</b:widget-setting>
                <b:widget-setting name='chronological'>false</b:widget-setting>
                <b:widget-setting name='showPosts'>false</b:widget-setting>
                <b:widget-setting name='frequency'>MONTHLY</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div class='widget-content'>
  <div id='ArchiveList'>
  <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
    <b:include cond='data:style == &quot;HIERARCHY&quot;' data='data' name='interval'/>
    <b:include cond='data:style == &quot;FLAT&quot;' data='data' name='flat'/>
    <b:include cond='data:style == &quot;MENU&quot;' data='data' name='menu'/>
  </div>
  </div>
  </div>
</b:includable>
              <b:includable id='flat' var='data'>
  <ul class='flat'>
    <b:loop values='data:data' var='i'>
      <li class='archivedate'>
        <a expr:href='data:i.url'><data:i.name/></a> (<data:i.post-count/>)
      </li>
    </b:loop>
  </ul>
</b:includable>
              <b:includable id='interval' var='intervalData'>
  <b:loop values='data:intervalData' var='interval'>
    <ul class='hierarchy'>
      <li expr:class='&quot;archivedate &quot; + data:interval.expclass'>
        <b:include cond='data:interval.toggleId' data='interval' name='toggle'/>
        <a class='post-count-link' expr:href='data:interval.url'>
          <data:interval.name/>
        </a>
        <span class='post-count' dir='ltr'>(<data:interval.post-count/>)</span>
        <b:include cond='data:interval.data' data='interval.data' name='interval'/>
        <b:include cond='data:interval.posts' data='interval.posts' name='posts'/>
      </li>
    </ul>
  </b:loop>
</b:includable>
              <b:includable id='menu' var='data'>
  <select expr:id='data:widget.instanceId + &quot;_ArchiveMenu&quot;'>
    <option value=''><data:title/></option>
    <b:loop values='data:data' var='i'>
      <option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option>
    </b:loop>
  </select>
</b:includable>
              <b:includable id='posts' var='posts'>
  <ul class='posts'>
    <b:loop values='data:posts' var='post'>
      <li><a expr:href='data:post.url'><data:post.title/></a></li>
    </b:loop>
  </ul>
</b:includable>
              <b:includable id='toggle' var='interval'>
  <a class='toggle' href='javascript:void(0)'>
    <span expr:class='&quot;zippy&quot; + (data:interval.expclass == &quot;expanded&quot; ? &quot; toggle-open&quot; : &quot;&quot;)'>
      <b:if cond='data:interval.expclass == &quot;expanded&quot;'>
        &#9660;&#160;
      <b:elseif cond='data:blog.languageDirection == &quot;rtl&quot;'/>
        &#9668;&#160;
      <b:else/>
        &#9658;&#160;
      </b:if>
    </span>
  </a>
</b:includable>
            </b:widget>
            <b:widget id='AdSense2' locked='false' title='' type='AdSense' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                <b:widget-setting name='style.textcolor'>#5872ff</b:widget-setting>
                <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                <b:widget-setting name='style.urlcolor'>#3f51b5</b:widget-setting>
                <b:widget-setting name='style.linkcolor'>#030d17</b:widget-setting>
                <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <div class='widget-content'>
    <b:if cond='data:adCode'>
      <data:adCode/>
    <b:else/>
      <b:include name='defaultAdUnit'/>
    </b:if>
  </div>
</b:includable>
            </b:widget>
            <b:widget id='Label3' locked='false' title='Labels' type='Label' version='1'>
              <b:widget-settings>
                <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
                <b:widget-setting name='display'>LIST</b:widget-setting>
                <b:widget-setting name='selectedLabelsList'/>
                <b:widget-setting name='showType'>ALL</b:widget-setting>
                <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <b:if cond='data:title'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
      <b:loop values='data:labels' var='label'>
        <li>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </li>
      </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
            </b:widget>
            <b:widget id='HTML11' locked='false' title='Action Movies' type='HTML' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='content'>&lt;script src=&quot;/feeds/posts/default/-/Action?published&amp;amp;alt=json-in-script&amp;amp;callback=labelthumbs&quot; type=&quot;text/javascript&quot;&gt;&lt;/script&gt;

&lt;div class=&#39;viewall&#39;&gt;&lt;a href=&#39;/search/label/Action?max-results=12&#39;&gt;&lt;i aria-hidden=&#39;true&#39; class=&#39;fa fa-list-ul&#39;&gt;&lt;/i&gt; View All&lt;/a&gt;&lt;/div&gt;</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
            </b:widget>
            <b:widget id='Label2' locked='false' title='Labels' type='Label' version='1'>
              <b:widget-settings>
                <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
                <b:widget-setting name='display'>CLOUD</b:widget-setting>
                <b:widget-setting name='selectedLabelsList'/>
                <b:widget-setting name='showType'>ALL</b:widget-setting>
                <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <b:if cond='data:blog.url == data:label.url'>
              <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
            <b:else/>
              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url + &quot;?max-results=12&quot;'><data:label.name/></a>
            </b:if>
            <b:if cond='data:showFreqNumbers'>
              <span dir='ltr'>(<data:label.count/>)</span>
            </b:if>
          </li>
        </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url + &quot;?max-results=12&quot;'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
  </div>
</b:includable>
            </b:widget>
            <b:widget id='HTML12' locked='false' title='Like Us on Facebook' type='HTML' version='1'>
              <b:widget-settings>
                <b:widget-setting name='content'><![CDATA[<iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fmsdesign.rtml&tabs=timeline&width=340&height=437&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true&appId=1023306164355494" width="340" height="320" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowtransparency="true"></iframe>]]></b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
            </b:widget>
            <b:widget cond='!data:view.isPost' id='PageList1' locked='false' title='' type='PageList' visible='false'>
              <b:widget-settings>
                <b:widget-setting name='pageListJson'><![CDATA[{'home': {'href': 'http://ventharmovies.blogspot.com/', 'title': 'Home', 'position': 0}}]]></b:widget-setting>
                <b:widget-setting name='homeTitle'>Home</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
              <b:includable id='content'>
  <div class='widget-content'>
    <b:include name='pageList'/>
  </div>
</b:includable>
              <b:includable id='overflowButton'>
  <b:include name='verticalMoreIcon'/>
</b:includable>
              <b:includable id='overflowablePageList'>
  <div class='overflowable-container'>
    <div class='overflowable-contents'>
      <div class='container'>
        <b:with value='true' var='overflow'>
        <b:with value='&quot;tabs&quot;' var='pageListClass'>
          <b:include name='pageList'/>
        </b:with>
        </b:with>
      </div>
    </div>
    <div class='overflow-button hidden'>
      <b:include name='overflowButton'/>
    </div>
  </div>
</b:includable>
              <b:includable id='pageLink'>
  <li>
    <b:class cond='data:overflow' name='overflowable-item'/>
    <b:class cond='data:link.isCurrentPage' name='selected'/>

    <a expr:href='data:link.href'><data:link.title/></a>
  </li>
</b:includable>
              <b:includable id='pageList'>
  <ul>
    <b:class cond='data:pageListClass' expr:name='data:pageListClass'/>
    <b:loop values='data:links' var='link'>
      <b:include name='pageLink'/>
    </b:loop>
  </ul>
</b:includable>
            </b:widget>
            <b:widget id='HTML3' locked='false' title='Advertisement' type='HTML' visible='false'>
              <b:widget-settings>
                <b:widget-setting name='content'/>
              </b:widget-settings>
              <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
            </b:widget>
            <b:widget id='LinkList70' locked='false' title='Boxed Version' type='LinkList' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='sorting'>NONE</b:widget-setting>
                <b:widget-setting name='text-0'>boxedVersion</b:widget-setting>
                <b:widget-setting name='link-0'>false</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
          <b:include name='content'/>
        </b:includable>
              <b:includable id='content'>
          &lt;style type=&#39;text/css&#39;&gt;
          <b:loop values='data:links' var='link'>
            <b:if cond='data:link.name == &quot;boxedVersion&quot;'>
              <b:if cond='data:link.target == &quot;true&quot;'>
                #outer-wrapper{max-width:1020px} 
              </b:if>
            </b:if>
          </b:loop>
          &lt;/style&gt;
        </b:includable>
            </b:widget>
            <b:widget id='HTML1' locked='false' title='Responsive Ad Code Here' type='HTML' version='1'>
              <b:widget-settings>
                <b:widget-setting name='content'/>
              </b:widget-settings>
              <b:includable id='main'>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
            </b:widget>
            <b:widget id='LinkList73' locked='false' title='' type='LinkList' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='link-3'>#</b:widget-setting>
                <b:widget-setting name='sorting'>NONE</b:widget-setting>
                <b:widget-setting name='link-4'>#</b:widget-setting>
                <b:widget-setting name='text-1'>twitter</b:widget-setting>
                <b:widget-setting name='link-1'>#</b:widget-setting>
                <b:widget-setting name='text-0'>facebook</b:widget-setting>
                <b:widget-setting name='link-2'>#</b:widget-setting>
                <b:widget-setting name='text-3'>pinterest</b:widget-setting>
                <b:widget-setting name='link-0'>https://fb.com/soratemplates</b:widget-setting>
                <b:widget-setting name='text-2'>instagram</b:widget-setting>
                <b:widget-setting name='text-4'>gplus</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
              <b:include name='content'/>
            </b:includable>
              <b:includable id='content'>
              <div class='widget-content'>
                <ul>
                  <b:loop values='data:links' var='link'>
                    <li expr:class='data:link.name'><a expr:href='data:link.target' expr:title='data:link.name' target='_blank'/></li>
                  </b:loop>
                </ul>
              </div>
            </b:includable>
            </b:widget>
            <b:widget id='Profile1' locked='false' title='About' type='Profile' visible='false'>
              <b:widget-settings>
                <b:widget-setting name='showaboutme'>true</b:widget-setting>
                <b:widget-setting name='showlocation'>false</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main' var='this'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
              <b:includable id='authorProfileImage'>
  <img class='profile-img' expr:alt='data:messages.myPhoto' expr:height='data:authorPhoto.height' expr:src='data:authorPhoto.image' expr:width='data:authorPhoto.width'/>
</b:includable>
              <b:includable id='content'>
  <b:if cond='data:team'>
    <div class='widget-content team'>
      <b:include name='teamProfile'/>
    </div>
  <b:else/>
    <div class='widget-content individual'>
      <b:include name='userProfile'/>
    </div>
  </b:if>
</b:includable>
              <b:includable id='defaultProfileImage'>
  <div class='default-avatar'/>
</b:includable>
              <b:includable id='profileImage'>
  <b:if cond='data:authorPhoto.image'>
    <b:include name='authorProfileImage'/>
  <b:else/>
    <b:include name='defaultProfileImage'/>
  </b:if>
</b:includable>
              <b:includable id='teamProfile'>
  <ul>
    <b:loop values='data:authors' var='author'>
      <li>
        <div class='team-member'>
          <b:include data='author' name='teamProfileLink'/>
        </div>
      </li>
    </b:loop>
  </ul>
</b:includable>
              <b:includable id='teamProfileLink'>
  <a class='profile-link g-profile' expr:href='data:userUrl' rel='nofollow'>
    <b:include name='profileImage'/>
    <span class='profile-name'><data:display-name/></span>
  </a>
</b:includable>
              <b:includable id='userGoogleProfile'>
  <div class='g-follow' data-annotation='bubble' data-height='20' expr:data-href='data:userUrl'/>
</b:includable>
              <b:includable id='userLocation'>
  <dd class='profile-data location'><data:location/></dd>
</b:includable>
              <b:includable id='userProfile'>
  <b:include name='userProfileImage'/>
  <b:include name='userProfileInfo'/>
</b:includable>
              <b:includable id='userProfileData'>
  <dt class='profile-data'>
    <b:include name='userProfileLink'/>
    <b:include cond='data:hasgoogleprofile' name='userGoogleProfile'/>
  </dt>
</b:includable>
              <b:includable id='userProfileImage'>
  <a expr:href='data:userUrl' rel='nofollow'>
    <b:include name='profileImage'/>
  </a>
</b:includable>
              <b:includable id='userProfileInfo'>
  <div class='profile-info'>
    <dl class='profile-datablock'>
      <b:class cond='data:showlocation and data:location != &quot;&quot;' name='has-location'/>

      <b:include name='userProfileData'/>
      <b:include cond='data:showlocation and data:location != &quot;&quot;' name='userLocation'/>
      <b:include cond='data:aboutme != &quot;&quot;' name='userProfileText'/>
    </dl>
    <b:include name='viewProfileLink'/>
  </div>
</b:includable>
              <b:includable id='userProfileLink'>
  <a class='profile-link g-profile' expr:href='data:userUrl' rel='author nofollow'>
    <data:displayname/>
  </a>
</b:includable>
              <b:includable id='userProfileText'>
  <dd class='profile-textblock'>
    <data:aboutme/>
  </dd>
</b:includable>
              <b:includable id='viewProfileLink'>
  <a class='profile-link' expr:href='data:userUrl' rel='author nofollow'>
    <data:messages.viewMyCompleteProfile/>
  </a>
</b:includable>
            </b:widget>
            <b:widget id='Subscribe1' locked='false' title='Subscribe' type='Subscribe' visible='true'>
              <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
              <b:includable id='content'>
  <div class='widget-content'>
    <b:include data='feeds' name='feeds'/>
    <div style='clear:both'/>
  </div>
</b:includable>
              <b:includable id='feeds' var='feeds'>
  <b:loop values='data:feeds' var='feed'>
    <div expr:class='&quot;subscribe-wrapper subscribe-type-&quot; + data:feed.type'>

      <div expr:class='&quot;subscribe expanded subscribe-type-&quot; + data:feed.type' expr:id='&quot;SW_READER_LIST_&quot; + data:widgetId + data:feed.type' style='display:none;'>
        <div class='top'>
          <span class='inner' expr:onclick='&quot;return(_SW_toggleReaderList(event, \&quot;&quot; + data:widgetId +data:feed.type + &quot;\&quot;));&quot;'>
            <img class='subscribe-dropdown-arrow' expr:src='data:arrowDropdownImg'/>
            <img align='absmiddle' alt='' border='0' class='feed-icon' expr:src='data:feedIconImg'/>
            <data:feed.title/>
          </span>

          <div class='feed-reader-links'>
            <a class='feed-reader-link' expr:href='&quot;https://www.netvibes.com/subscribe.php?url=&quot; + data:feed.encodedUrl' target='_blank'>
              <img expr:src='data:imagePathBase + &quot;subscribe-netvibes.png&quot;'/>
            </a>
            <a class='feed-reader-link' expr:href='&quot;https://add.my.yahoo.com/content?url=&quot; + data:feed.encodedUrl' target='_blank'>
              <img expr:src='data:imagePathBase + &quot;subscribe-yahoo.png&quot;'/>
            </a>
            <a class='feed-reader-link' expr:href='data:feed.url' target='_blank'>
              <img align='absmiddle' class='feed-icon' expr:src='data:feedIconImg'/>
              Atom
            </a>
          </div>

        </div>
        <div class='bottom'/>
      </div>

      <div class='subscribe' expr:id='&quot;SW_READER_LIST_CLOSED_&quot; + data:widgetId +data:feed.type' expr:onclick='&quot;return(_SW_toggleReaderList(event, \&quot;&quot; + data:widgetId +data:feed.type + &quot;\&quot;));&quot;'>
        <div class='top'>
           <span class='inner'>
             <img class='subscribe-dropdown-arrow' expr:src='data:arrowDropdownImg'/>
             <span expr:onclick='&quot;return(_SW_toggleReaderList(event, \&quot;&quot; + data:widgetId +data:feed.type + &quot;\&quot;));&quot;'>
               <img align='absmiddle' alt='' border='0' class='feed-icon' expr:src='data:feedIconImg'/>
               <data:feed.title/>
             </span>
           </span>
         </div>
        <div class='bottom'/>
      </div>

    </div>
  </b:loop>
</b:includable>
            </b:widget>
          </b:section>
          <div class='clearfix'/>
          <b:section class='home-ad' id='home-ad-2' maxwidgets='1' name='Home Ads (B)' showaddelement='yes'>
            <b:widget id='HTML34' locked='false' title='' type='HTML' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='content'><![CDATA[<a target="_blank" href="https://imdbux.com/ref/6269"><img src="https://imdbux.com/assets/banners/468x60.gif" border="0" width="468" height="60" /></a>]]></b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
                <b:include name='widget-title'/>
                <div class='widget-content'>
                  <data:content/>
                </div>
              </b:includable>
            </b:widget>
          </b:section>
          <div class='clearfix'/>
        </b:if>
           <b:section class='main' id='main' maxwidgets='1' name='Main Posts' showaddelement='yes'>
             <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='2' visible='true'>
               <b:widget-settings>
                 <b:widget-setting name='commentLabel'>Comments</b:widget-setting>
                 <b:widget-setting name='showShareButtons'>true</b:widget-setting>
                 <b:widget-setting name='authorLabel'>by</b:widget-setting>
                 <b:widget-setting name='disableGooglePlusShare'>true</b:widget-setting>
                 <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                 <b:widget-setting name='timestampLabel'>On</b:widget-setting>
                 <b:widget-setting name='reactionsLabel'/>
                 <b:widget-setting name='showAuthorProfile'>true</b:widget-setting>
                 <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                 <b:widget-setting name='showLocation'>false</b:widget-setting>
                 <b:widget-setting name='showTimestamp'>true</b:widget-setting>
                 <b:widget-setting name='postsPerAd'>1</b:widget-setting>
                 <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                 <b:widget-setting name='backlinksLabel'/>
                 <b:widget-setting name='showDateHeader'>false</b:widget-setting>
                 <b:widget-setting name='style.textcolor'>#5872ff</b:widget-setting>
                 <b:widget-setting name='showCommentLink'>true</b:widget-setting>
                 <b:widget-setting name='style.urlcolor'>#3f51b5</b:widget-setting>
                 <b:widget-setting name='showAuthor'>true</b:widget-setting>
                 <b:widget-setting name='style.linkcolor'>#030d17</b:widget-setting>
                 <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                 <b:widget-setting name='showLabels'>true</b:widget-setting>
                 <b:widget-setting name='postLabelsLabel'>Tags:</b:widget-setting>
                 <b:widget-setting name='showBacklinks'>false</b:widget-setting>
                 <b:widget-setting name='showInlineAds'>false</b:widget-setting>
                 <b:widget-setting name='showReactions'>false</b:widget-setting>
               </b:widget-settings>
               <b:includable id='main' var='this'>
			  <b:include name='homePostsHeadline'/>
              <b:include name='searchMessage'/>
              <div class='blog-posts hfeed container'>
                <b:class cond='data:view.isMultipleItems' name='index-post-wrap'/>
                <b:class cond='data:view.isSingleItem' name='item-post-wrap'/>
                <b:tag class='grid-posts' cond='data:view.isMultipleItems' name='div'>
                  <b:loop index='i' values='data:posts' var='post'>
                    <b:include data='post' name='postCommentsAndAd'/>
                  </b:loop>
                </b:tag>
              </div>
              <b:include cond='data:view.isMultipleItems' name='indexBlogPager'/>
              <b:include name='feedLinks'/>
              <script type='text/javascript'>
                var messages = { 
                  showMore: &quot;<data:messages.showMore/>&quot;
                }
              </script>
            </b:includable>
               <b:includable id='aboutPostAuthor'>
              <div class='about-author'>
                <div class='avatar-container'>
                  <b:if cond='data:post.author.authorPhoto.image'>
                    <img class='author-avatar' expr:alt='data:post.author.name' src='https://1.bp.blogspot.com/-MIZs11Tl2l0/XWUvRBuvZHI/AAAAAAAAAZE/zHxo5qIF-swPRVZ-ezhqjGXol62choifQCLcBGAs/s1600/oglogofb.jpg resizeImage 120'/>                
                    <b:else/>
                    <img class='author-avatar' expr:alt='data:post.author.name' src='https://4.bp.blogspot.com/-uCjYgVFIh70/VuOLn-mL7PI/AAAAAAAADUs/Kcu9wJbv790hIo83rI_s7lLW3zkLY01EA/s100/avatar.png'/>
                  </b:if>
                </div>
                <h3 class='author-name'>
                  <span>Distributed By: </span><a href='https://www.facebook.com/' target='_blank'> </a>
                </h3>
                <span class='author-description'>Note: No videos are hosted by this Website or our servers. All videos are embedded by our members using third party video streaming websites such as Youtube, Google Drive, Daily Motion, Vimeo, Facebook and Ok.ru...</span>
              </div>
</b:includable>
               <b:includable id='addComments'>
              <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
                <b:message name='messages.postAComment'/>
              </a>
            </b:includable>
               <b:includable id='backLinks' var='post'>
              <b:comment>Disabled</b:comment>
            </b:includable>
               <b:includable id='blogThisShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
               <b:includable id='bylineByName' var='byline'>
  <b:switch var='data:byline.name'>
  <b:case value='share'/>
    <b:include cond='data:post.shareUrl' name='postShareButtons'/>
  <b:case value='comments'/>
    <b:include cond='data:post.allowComments' name='postCommentsLink'/>
  <b:case value='location'/>
    <b:include cond='data:post.location' name='postLocation'/>
  <b:case value='timestamp'/>
    <b:include cond='not data:view.isPage' name='postTimestamp'/>
  <b:case value='author'/>
    <b:include name='postAuthor'/>
  <b:case value='labels'/>
    <b:include cond='data:post.labels' name='postLabels'/>
  <b:case value='icons'/>
    <b:include cond='data:post.emailPostUrl' name='emailPostIcon'/>
  <b:case value='reactions'/>
    <b:include cond='data:post.reactionsUrl' name='postReactions'/>
  </b:switch>
</b:includable>
               <b:includable id='bylineRegion' var='regionItems'>
  <b:loop values='data:regionItems' var='byline'>
    <b:include data='byline' name='bylineByName'/>
  </b:loop>
</b:includable>
               <b:includable id='commentAuthorAvatar'>
              <div class='avatar-image-container'>
                <img class='author-avatar' expr:src='data:comment.authorAvatarSrc' height='45' width='45'/>
              </div>
            </b:includable>
               <b:includable id='commentDeleteIcon' var='comment'>
              <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
                <b:if cond='data:showCmtPopup'>
                  <div class='goog-toggle-button'>
                    <div class='goog-inline-block comment-action-icon'/>
                  </div>
                  <b:else/>
                  <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:messages.deleteComment'>
                    <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
                  </a>
                </b:if>
              </span>
            </b:includable>
               <b:includable id='commentForm' var='post'>
              <div class='comment-form'>
                <a name='comment-form'/>
                <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
                  <p class='comments-message'><data:this.messages.blogComment/></p>
                </b:if>
                <b:include data='post' name='commentFormIframeSrc'/>
                <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
                <data:post.cmtfpIframe/>
                <script type='text/javascript'>
                  BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
                </script>
              </div>
            </b:includable>
               <b:includable id='commentFormIframeSrc' var='post'>
              <a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=contempo&quot;' id='comment-editor-src'/>
            </b:includable>
               <b:includable id='commentItem' var='comment'>
              <div class='comment' expr:id='&quot;c&quot; + data:comment.id'>
                <b:include cond='data:blog.enabledCommentProfileImages' name='commentAuthorAvatar'/>

                <div class='comment-block'>
                  <div class='comment-author'>
                    <b:if cond='data:comment.authorUrl'>
                      <b:message name='messages.authorSaidWithLink'>
                        <b:param expr:value='data:comment.author' name='authorName'/>
                        <b:param expr:value='data:comment.authorUrl' name='authorUrl'/>
                      </b:message>
                      <b:else/>
                      <b:message name='messages.authorSaid'>
                        <b:param expr:value='data:comment.author' name='authorName'/>
                      </b:message>
                    </b:if>
                  </div>
                  <div expr:class='&quot;comment-body&quot; + (data:comment.isDeleted ? &quot; deleted&quot; : &quot;&quot;)'>
                    <data:comment.body/>
                  </div>
                  <div class='comment-footer'>
                    <span class='comment-timestamp'>
                      <a expr:href='data:comment.url' title='comment permalink'>
                        <data:comment.timestamp/>
                      </a>
                      <b:include data='comment' name='commentDeleteIcon'/>
                    </span>
                  </div>
                </div>
              </div>
            </b:includable>
               <b:includable id='commentList' var='comments'>
              <div id='comments-block'>
                <b:loop values='data:comments' var='comment'>
                  <b:include data='comment' name='commentItem'/>
                </b:loop>
              </div>
            </b:includable>
               <b:includable id='commentPicker' var='post'>
              <b:if cond='data:post.allowComments'>
                <div class='title-wrap comments-title'>
                  <h3> <data:messages.postAComment/></h3>
                </div>
              </b:if>
              <b:if cond='data:post.commentSource == 1'>
                <b:include data='post' name='iframeComments'/>
                <b:elseif cond='data:post.showThreadedComments'/>
                <b:include data='post' name='threadedComments'/>
                <b:else/>
                <b:include data='post' name='comments'/>
              </b:if>
            </b:includable>
               <b:includable id='comments' var='post'>
              <section expr:class='&quot;comments&quot; + (data:post.embedCommentForm ? &quot; embed&quot; : &quot;&quot;)' expr:data-num-comments='data:post.numberOfComments' id='comments'>
                <a name='comments'/>
                <b:if cond='data:post.allowComments'>

                  <b:include name='commentsTitle'/>

                  <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
                    <b:include cond='data:post.comments' data='post.comments' name='commentList'/>
                  </div>

                  <b:if cond='data:post.commentPagingRequired'>
                    <div class='paging-control-container'>
                      <b:if cond='data:post.hasOlderLinks'>
                        <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                          <data:messages.oldest/>
                        </a>
                        <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                          <data:messages.older/>
                        </a>
                      </b:if>

                      <span class='comment-range-text'>
                        <data:post.commentRangeText/>
                      </span>

                      <b:if cond='data:post.hasNewerLinks'>
                        <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                          <data:messages.newer/>
                        </a>
                        <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                          <data:messages.newest/>
                        </a>
                      </b:if>
                    </div>
                  </b:if>
                  <div class='footer'>
                    <b:if cond='data:post.embedCommentForm'>
                      <b:if cond='data:post.allowNewComments'>
                        <b:include data='post' name='commentForm'/>
                        <b:else/>
                        <data:post.noNewCommentsText/>
                      </b:if>
                      <b:else/>
                      <b:if cond='data:post.allowComments'>
                        <b:include data='post' name='addComments'/>
                      </b:if>
                    </b:if>
                  </div>
                </b:if>
                <b:if cond='data:showCmtPopup'>
                  <div id='comment-popup'>
                    <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                    </iframe>
                  </div>
                </b:if>
              </section>
            </b:includable>
               <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
               <b:includable id='commentsLinkIframe'>
  <span class='cmt_count_iframe_holder' expr:data-count='data:post.numberOfComments' expr:data-onclick='data:post.commentsUrlOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.url.canonical.http'>
  </span>
</b:includable>
               <b:includable id='commentsTitle'>
              <!-- Post Commments Title -->
              <b:comment><h3 class='title'><data:post.numberOfComments/> <data:messages.comments/></h3></b:comment>
            </b:includable>
               <b:includable id='defaultAdUnit'>
  <ins class='adsbygoogle' data-ad-format='auto' expr:data-ad-client='data:adClientId ?: data:blog.adsenseClientId' expr:data-ad-host='data:blog.adsenseHostId' expr:data-analytics-uacct='data:blog.analyticsAccountNumber' expr:style='data:style ?: &quot;display: block;&quot;'/>
  <script>
   (adsbygoogle = window.adsbygoogle || []).push({});
  </script>
</b:includable>
               <b:includable id='emailPostIcon'>
  <span class='byline post-icons'>
    <!-- email post links -->
    <span class='item-action'>
      <a expr:href='data:post.emailPostUrl' expr:title='data:messages.emailPost'>
        <b:include data='{ iconClass: &quot;touch-icon sharing-icon&quot; }' name='emailIcon'/>
      </a>
    </span>
  </span>
</b:includable>
               <b:includable id='facebookShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
               <b:includable id='feedLinks'>
              <b:comment>Disabled</b:comment> 
            </b:includable>
               <b:includable id='feedLinksBody' var='links'>
              <b:comment>Disabled</b:comment> 
            </b:includable>
               <b:includable id='footerBylines' var='post'>
              <!-- Post Footer Extras -->
              <b:include data='post' name='postShareButtons'/>
            </b:includable>
               <b:includable id='googlePlusShare'>
  <div class='goog-inline-block google-plus-share-container'>
    <g:plusone annotation='inline' expr:href='data:originalUrl.canonical.http' size='medium' source='blogger:blog:plusone'/>
  </div>
</b:includable>
               <b:includable id='headerByline' var='post'>
              <!-- Post Header Meta -->
			  <b:if cond='data:view.isPost'>
                <div class='post-meta'>
                <b:include cond='data:allBylineItems.author' data='post' name='postAuthor'/>
                <b:include cond='data:allBylineItems.timestamp' data='post' name='postTimestamp'/>
                <b:include cond='data:allBylineItems.labels' data='post' name='postCategory'/>
				<b:include data='post' name='postViews'/>
                </div>
			  </b:if>
            </b:includable>
               <b:includable id='homePageLink'>
              <b:comment>Disabled</b:comment> 
            </b:includable>
               <b:includable id='homePostsHeadline'>
              <b:if cond='data:view.isHomepage'>
                <b:if cond='data:blog.jumpLinkMessage != &quot;hide&quot;'>
                  <div class='title-wrap Label'><h3 class='title'><data:messages.recentPosts/></h3><a class='show-more' expr:title='data:messages.showMore' href='/search'><data:messages.showMore/></a></div>
                </b:if>
              </b:if>
            </b:includable>
               <b:includable id='iframeComments' var='post'>
              <b:if cond='data:post.allowIframeComments'>
                <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
                <div class='cmt_iframe_holder' expr:data-href='data:post.url.canonical' expr:data-viewtype='data:post.viewType'/>
                <b:if cond='!data:post.embedCommentForm'>
                  <b:include data='post' name='commentsLink'/>
                </b:if>
              </b:if>
            </b:includable>
               <b:includable id='indexBlogPager'>
              <!-- Post Pagination Index -->
              <div class='blog-pager container' id='blog-pager'>
                <b:include cond='data:newerPageUrl' name='previousPageLink'/>
                <b:include cond='data:olderPageUrl' name='nextPageLink'/>
                <b:include cond='data:view.url != data:blog.homepageUrl' name='homePageLink'/>
              </div>
            </b:includable>
               <b:includable id='indexPost' var='post'>
			  <div class='index-post-inside-wrap'>
              <!-- Index Post Content -->
              <b:include data='post' name='postFeaturedImage'/>
              <div class='post-info'>
                <b:include data='post' name='postHeader'/>
              </div>
                <b:include data='post' name='headerByline'/>
              </div>
            </b:includable>
               <b:includable id='inlineAd' var='post'>
              <b:comment>Disabled</b:comment> 
            </b:includable>
               <b:includable id='itemPost' var='post'>
              <!-- Item Post Content -->
                <b:include data='post' name='postMeta'/>
                <b:include data='post' name='postHeader'/>
                <b:include data='post' name='postBody'/>
                <b:include cond='data:view.isPost' data='post' name='footerBylines'/>
              <b:include cond='data:view.isPost' data='post' name='postFooter'/>
            </b:includable>
               <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
               <b:includable id='nextPageLink'>
              <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:messages.olderPosts'>
                <data:messages.olderPosts/>
              </a>
            </b:includable>
               <b:includable id='otherSharingButton'>
  <span class='sharing-platform-button sharing-element-other' expr:aria-label='data:messages.shareToOtherApps.escaped' expr:data-url='data:originalUrl' expr:title='data:messages.shareToOtherApps.escaped' role='menuitem' tabindex='-1'>
    <b:with value='{key: &quot;sharingOther&quot;}' var='platform'>
      <b:include name='sharingPlatformIcon'/>
    </b:with>
    <span class='platform-sharing-text'><data:messages.shareOtherApps.escaped/></span>
  </span>
</b:includable>
               <b:includable id='platformShare'>
  <a expr:class='&quot;goog-inline-block sharing-&quot; + data:platform.key' expr:data-url='data:originalUrl' expr:href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:onclick='data:onclick ? data:onclick : &quot;&quot;' expr:title='data:platform.shareMessage' target='_blank'>
    <span class='share-button-link-text'>
      <data:platform.shareMessage/>
    </span>
  </a>
</b:includable>
               <b:includable id='post' var='post'>
              <!-- Post Index -->
              <b:if cond='data:view.isMultipleItems'>
                <b:include data='post' name='indexPost'/>
              </b:if>
              <!-- Post Item -->
              <b:if cond='data:view.isSingleItem'>
                <b:include data='post' name='itemPost'/>
              </b:if>
            </b:includable>
               <b:includable id='postAuthor' var='post'>
              <!-- Post Author -->
              <b:if cond='data:allBylineItems.author'>
                <span class='post-author'><a expr:href='data:post.author.profileUrl' expr:title='data:post.author.name' target='_blank'><data:post.author.name/></a></span>
              </b:if>
            </b:includable>
               <b:includable id='postBody' var='post'>
              <!-- Ads before post content, if post page. -->
              <b:if cond='data:view.isPost'><div id='before-ad'/></b:if>
              <!-- Post Body Entry Content-->
              <div class='post-body post-content'>
                <data:post.body/>
              </div>
              <!-- Ads after post content, if post page. -->
              <b:if cond='data:view.isPost'><div id='after-ad'/></b:if>
            </b:includable>
               <b:includable id='postBodySnippet' var='post'>
              <b:include data='post' name='postBody'/>
            </b:includable>
               <b:includable id='postBreadcrumbs' var='post'>
              <!-- Post Breadcrumbs -->
              <nav id='breadcrumb'><a expr:href='data:blog.homepageUrl'><data:messages.home/></a><b:if cond='data:post.labels'><em class='delimiter'/><a class='b-label' expr:href='data:post.labels.first.url'><data:post.labels.first.name/></a></b:if><em class='delimiter'/><span class='current'><data:post.title/></span></nav>
              <script type='application/ld+json'>
              {
                &quot;@context&quot;: &quot;http://schema.org&quot;,
                &quot;@type&quot;: &quot;BreadcrumbList&quot;,
                &quot;@id&quot;: &quot;#Breadcrumb&quot;,
                &quot;itemListElement&quot;: [{
                  &quot;@type&quot;: &quot;ListItem&quot;,
                  &quot;position&quot;: 1,
                  &quot;item&quot;: {
                    &quot;name&quot;: &quot;<data:messages.home/>&quot;,
                    &quot;@id&quot;: &quot;<data:blog.homepageUrl.jsonEscaped/>&quot;
                  }
                },{
                  &quot;@type&quot;: &quot;ListItem&quot;,
                  &quot;position&quot;: 2,
                  &quot;item&quot;: {
                    &quot;name&quot;: &quot;<b:if cond='data:post.labels'><data:post.labels.first.name/></b:if>&quot;,
                    &quot;@id&quot;: &quot;<data:post.labels.first.url.jsonEscaped/>&quot;
                  }
                },{
                  &quot;@type&quot;: &quot;ListItem&quot;,
                  &quot;position&quot;: 3,
                  &quot;item&quot;: {
                    &quot;name&quot;: &quot;<data:post.title/>&quot;,
                    &quot;@id&quot;: &quot;<data:post.url.jsonEscaped/>&quot;
                  }
                }]
              }
            </script>
            </b:includable>
               <b:includable id='postCategory' var='post'>
              <b:if cond='data:post.labels'>
                <span class='post-tag Label'><a expr:href='data:post.labels.first.url'><data:post.labels.first.name/></a></span>
              </b:if>
            </b:includable>
               <b:includable id='postCommentsAndAd' var='post'>
              <!-- Post, Comments and Ads -->
              <!-- Post Content Index and Item -->
              <div class='blog-post hentry'>
                <b:class cond='data:view.isMultipleItems' name='index-post post-episode-info'/>
                <b:class cond='data:view.isSingleItem' name='item-post'/>
                <b:class cond='data:view.isPost' name='post-episode'/>
                <b:attr cond='data:view.isMultipleItems' expr:value='data:post.id' name='data-id'/>
                <b:include data='post' name='post'/>
              </div>
              <b:if cond='data:view.isPost'>
              <!-- Ads After Related Posts -->
              	<div id='arel-ad'/>
              </b:if>
              <!-- Comments -->
              <b:if cond='data:view.isSingleItem and data:post.allowComments'>
                <div class='blog-post-comments'>
                  <b:include data='post' name='threadedCommentsDisqus'/>
                  <b:include data='post' name='commentPicker'/>
                </div>
              </b:if>
            </b:includable>
               <b:includable id='postCommentsLink'>
              <b:if cond='data:view.isMultipleItems'>
                <span class='byline post-comment-link container'>
                  <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
                  <b:include cond='data:post.commentSource == 1' name='commentsLinkIframe'/>
                </span>
              </b:if>
            </b:includable>
               <b:includable id='postEpisode' var='post'>
				<span class='post_episode'/>
            </b:includable>
               <b:includable id='postFeaturedImage' var='post'>
              <!-- Post Featured Image on Index -->
              <div class='post-image-wrap'>
                <a class='post-image-link' expr:href='data:post.url'>
                  <b:if cond='data:post.featuredImage'> 
                    <img class='post-thumb' expr:alt='data:post.title' expr:src='data:post.featuredImage resizeImage 680'/>
                    <b:else/>
                    <img class='post-thumb' expr:alt='data:post.title' src='https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w680/nth.png'/>
                  </b:if>
                </a>
				<b:include data='post' name='postEpisode'/>
              </div>
            </b:includable>
               <b:includable id='postFooter' var='post'>
              <!-- Post Footer Items -->
              <div class='post-footer'>
                <!-- About Author and Related Posts -->
                <b:include cond='data:post.author.aboutMe' data='post' name='aboutPostAuthor'/>
                <b:include cond='data:allBylineItems.backlinks' data='post' name='postRelated'/>
              </div>
            </b:includable>
               <b:includable id='postFooterAuthorProfile' var='post'>
              <b:comment>Disabled</b:comment>   
            </b:includable>
               <b:includable id='postHeader' var='post'>
              <b:include cond='data:view.isPost' data='post' name='postBreadcrumbs'/>
              <b:include data='post' name='postTitle'/>
              <b:include cond='data:view.isPost' data='post' name='headerByline'/>
            </b:includable>
               <b:includable id='postJumpLink' var='post'>
              <b:if cond='data:blog.jumpLinkMessage != &quot;hide&quot;'>
                <a class='read-more' expr:href='data:post.url'><data:blog.jumpLinkMessage/></a>
              </b:if>
            </b:includable>
               <b:includable id='postLabels'>
  <span class='byline post-labels'>
    <span class='byline-label'><data:byline.label/></span>
    <b:loop index='i' values='data:post.labels' var='label'>
      <a expr:href='data:label.url' rel='tag'>
        <data:label.name/>
      </a>
    </b:loop>
  </span>
</b:includable>
               <b:includable id='postLocation'>
  <span class='byline post-location'>
    <data:byline.label/>
    <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
  </span>
</b:includable>
               <b:includable id='postMeta' var='post'>
              <b:include data='post' name='postMetadataJSON'/>
            </b:includable>
               <b:includable id='postMetadataJSONImage'>
  &quot;image&quot;: {
    &quot;@type&quot;: &quot;ImageObject&quot;,
    <b:if cond='data:post.featuredImage.isResizable'>
    &quot;url&quot;: &quot;<b:eval expr='resizeImage(data:post.featuredImage, 1200, &quot;1200:630&quot;)'/>&quot;,
    &quot;height&quot;: 630,
    &quot;width&quot;: 1200
    <b:else/>
    &quot;url&quot;: &quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=w1200&quot;,
    &quot;height&quot;: 348,
    &quot;width&quot;: 1200
    </b:if>
  },
</b:includable>
               <b:includable id='postMetadataJSONPublisher'>
 &quot;publisher&quot;: {
    &quot;@type&quot;: &quot;Organization&quot;,
    &quot;name&quot;: &quot;Blogger&quot;,
    &quot;logo&quot;: {
      &quot;@type&quot;: &quot;ImageObject&quot;,
      &quot;url&quot;: &quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=h60&quot;,
      &quot;width&quot;: 206,
      &quot;height&quot;: 60
    }
  },
</b:includable>
               <b:includable id='postPagination'>
			  <div class='blog-pager container' id='blog-pager'>
			    <b:include cond='data:newerPageUrl' name='previousPageLink'/>
			    <b:include cond='data:olderPageUrl' name='nextPageLink'/>
			    <b:include cond='data:view.url != data:blog.homepageUrl' name='homePageLink'/>
			  </div>
            </b:includable>
               <b:includable id='postReactions'>
  <span class='byline reactions'>
    <span class='reactions-label'>
      <data:byline.label/>
    </span>
    <iframe allowtransparency='true' class='reactions-iframe' expr:src='data:post.reactionsUrl' frameborder='0' name='reactions' scrolling='no'/>
  </span>
</b:includable>
               <b:includable id='postRelated' var='post'>
              <!-- Related Posts -->
                <div id='related-wrap'>
                  <div class='title-wrap'>
                    <h3> Related Posts</h3>
                  </div>
                  <div class='related-ready'>
                    <b:if cond='data:post.labels'>
                      <div class='related-tag' expr:data-label='data:post.labels.first.name'/>
                      <b:else/>
                      <div class='related-tag' data-label='random'/>
                    </b:if>
                  </div> 
                </div> 
            </b:includable>
               <b:includable id='postShareButtons' var='post'>
              <!-- Post ShareButtons -->
                    <div class='post-share'>
                      <ul class='share-links social social-color'>
                        <li class='facebook-f'><a class='facebook window-upex' data-height='650' data-width='550' expr:data-url='&quot;https://www.facebook.com/sharer.php?u=&quot; + data:post.url.canonical' href='javascript:;' rel='nofollow' title='Facebook'/></li>
                        <li class='twitter'><a class='twitter window-upex' data-height='460' data-width='550' expr:data-url='&quot;https://twitter.com/intent/tweet?url=&quot; + data:post.url.canonical + &quot;&amp;text=&quot; + data:post.title' href='javascript:;' rel='nofollow' title='Twitter'/></li>
                        <b:if cond='data:blog.isMobileRequest'>
                          <li class='whatsapp whatsapp-mobile'><a class='whatsapp' expr:href='&quot;https://api.whatsapp.com/send?text=&quot; + data:post.title + &quot; | &quot; + data:post.url.canonical' rel='nofollow' title='WhatsApp'/></li>
                          <b:else/>
                          <li class='whatsapp whatsapp-desktop'><a class='whatsapp window-upex' data-height='550' data-width='900' expr:data-url='&quot;https://web.whatsapp.com/send?text=&quot; + data:post.title + &quot; | &quot; + data:post.url.canonical' href='javascript:;' rel='nofollow' title='WhatsApp'/></li>
                        </b:if>
                        <li class='reddit'><a class='reddit window-upex' data-height='460' data-width='550' expr:data-url='&quot;https://reddit.com/submit?url=&quot; + data:post.url.canonical + &quot;&amp;title=&quot; + data:post.title' href='javascript:;' rel='nofollow' title='Reddit'/></li>
                        <li class='pinterest-p'><a class='pinterest window-upex' data-height='750' data-width='735' expr:data-url='&quot;https://www.pinterest.com/pin/create/button/?url=&quot; + data:post.url.canonical + &quot;&amp;media=&quot; + data:post.featuredImage + &quot;&amp;description=&quot; + data:post.title' href='javascript:;' rel='nofollow' title='Pinterest'/></li>
                        <li class='linkedin'><a class='linkedin window-upex' data-height='700' data-width='1000' expr:data-url='&quot;https://www.linkedin.com/shareArticle?url=&quot; + data:post.url.canonical' href='javascript:;' rel='nofollow' title='LinkedIn'/></li>
                        <li class='email'><a class='email window-upex' data-height='650' data-width='650' expr:data-url='&quot;mailto:?subject=&quot; + data:post.title + &quot;&amp;body=&quot; + data:post.url.canonical' href='javascript:;' rel='nofollow' title='Email'/></li>
                        <li class='show-hid'><a href='javascript:;' rel='nofollow'/></li>
                      </ul>
                    </div>
            </b:includable>
               <b:includable id='postShortMeta'>
              <b:comment>Disabled</b:comment> 
            </b:includable>
               <b:includable id='postSummary' var='post'>
              <!-- Post Summary -->
              <p class='post-snippet'><b:eval expr='data:post.snippets.long snippet { length: 200 }'/></p>
            </b:includable>
               <b:includable id='postTimestamp' var='post'>
              <!-- Post Timestamp -->
              <b:if cond='data:allBylineItems.timestamp'>
                <span class='post-date published' expr:datetime='data:post.date.iso8601'><b:eval expr='data:post.date format &quot;dd.MMMM.yyyy&quot;'/></span>
              </b:if>
            </b:includable>
               <b:includable id='postTitle' var='post'>
              <!-- Post Title Index and Item -->
              <b:if cond='data:view.isMultipleItems'>
                <h2 class='post-title'>
                  <a expr:href='data:post.url'><data:post.title/></a>
                </h2>
              </b:if>
              <b:if cond='data:view.isSingleItem'>
                <h1 class='post-title'>
                  <data:post.title/>
                </h1>
              </b:if>
            </b:includable>
               <b:includable id='postViews' var='post'>
			  <b:if cond='data:view.isPost'>
                <span class='post-view' expr:data-id='data:post.id'><span class='view-load' id='postviews'><i class='fas fa-spinner fa-pulse faa-fast'/></span> Views</span>
			  </b:if>
            </b:includable>
               <b:includable id='previousPageLink'>
              <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:messages.newerPosts'>
                <data:messages.newerPosts/>
              </a>
            </b:includable>
               <b:includable id='searchMessage'>
              <!-- Search Message -->
              <b:if cond='data:view.search.query'>
                <div class='queryMessage'>
                  <b:if cond='data:posts.empty'>
                    <span class='query-info query-error'/><data:view.search.resultsMessageHtml/>
                    <b:else/>
                    <span class='query-info query-success'><data:view.search.resultsMessageHtml/></span>
                  </b:if>
                </div>
              </b:if>
              <b:if cond='data:view.search.label'>
                <div class='queryMessage'>
                  <b:if cond='data:posts.empty'>
                    <span class='query-info query-error'><data:view.search.resultsMessageHtml/></span>
                    <b:else/>
                    <span class='query-info query-success'><data:view.search.resultsMessageHtml/></span>
                  </b:if>
                </div>
              </b:if>
              <b:if cond='data:view.isArchive'>
                <div class='queryMessage'>
                  <b:if cond='data:posts.empty'>
                    <span class='query-info query-error'><data:view.archive.rangeMessage/></span>
                    <b:else/>
                    <span class='query-info query-success'><data:view.archive.rangeMessage/></span>
                  </b:if>
                </div>
              </b:if>
              <b:if cond='data:view.isError'>
                <div class='errorWrap'>
                  <h3>404</h3>
                  <h4><data:messages.theresNothingHere/></h4>
                  <p><data:navMessage/></p>
                  <a class='homepage' expr:href='data:blog.homepageUrl'><i class='fas fa-home'/> <data:messages.home/></a>
                </div>
              </b:if>
              <b:if cond='data:view.isMultipleItems and data:posts.empty'><div class='queryEmpty'><data:messages.noResultsFound/></div></b:if>
            </b:includable>
               <b:includable id='sharingButton'>
  <span expr:aria-label='data:platform.shareMessage' expr:class='&quot;sharing-platform-button sharing-element-&quot; + data:platform.key' expr:data-href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:data-url='data:originalUrl' expr:title='data:platform.shareMessage' role='menuitem' tabindex='-1'>
    <b:include name='sharingPlatformIcon'/>
    <span class='platform-sharing-text'><data:platform.name/></span>
  </span>
</b:includable>
               <b:includable id='sharingButtonContent'>
  <div class='flat-icon-button ripple'>
    <b:include name='shareIcon'/>
  </div>
</b:includable>
               <b:includable id='sharingButtons'>
  <div class='sharing' expr:aria-owns='&quot;sharing-popup-&quot; + data:sharingId' expr:data-title='data:shareTitle'>
    <button class='sharing-button touch-icon-button' expr:aria-controls='&quot;sharing-popup-&quot; + data:sharingId' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-button-&quot; + data:sharingId' role='button'>
      <b:include name='sharingButtonContent'/>
    </button>
    <b:include name='sharingButtonsMenu'/>
  </div>
</b:includable>
               <b:includable id='sharingButtonsMenu'>
  <div class='share-buttons-container'>
    <ul aria-hidden='true' class='share-buttons hidden' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-popup-&quot; + data:sharingId' role='menu'>
      <b:loop values='(data:platforms ?: data:blog.sharing.platforms) filter (p =&gt; p.key not in {&quot;blogThis&quot;})' var='platform'>
        <li>
          <b:include name='sharingButton'/>
        </li>
      </b:loop>
      <li aria-hidden='true' class='hidden'>
        <b:include name='otherSharingButton'/>
      </li>
    </ul>
  </div>
</b:includable>
               <b:includable id='sharingPlatformIcon'>
  <b:include data='{ iconClass: (&quot;touch-icon sharing-&quot; + data:platform.key) }' expr:name='data:platform.key + &quot;Icon&quot;'/>
</b:includable>
               <b:includable id='threadedCommentForm' var='post'>
              <div class='comment-form'>
                <a name='comment-form'/>
                <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
                  <p class='comments-message'><data:this.messages.blogComment/></p>
                </b:if>
                <b:include data='post' name='commentFormIframeSrc'/>
                <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
                <data:post.cmtfpIframe/>
                <script type='text/javascript'>
                  BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
                </script>
              </div>
            </b:includable>
               <b:includable id='threadedCommentJs' var='post'>
              <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
              <b:template-script inline='true' name='threaded_comments'/>
              <script type='text/javascript'>
                blogger.widgets.blog.initThreadedComments(
                  <data:post.commentJso/>,
                  <data:post.commentMsgs/>,
                  <data:post.commentConfig/>);
              </script>
            </b:includable>
               <b:includable id='threadedComments' var='post'>
              <section class='comments threaded' expr:data-embed='data:post.embedCommentForm' expr:data-num-comments='data:post.numberOfComments' id='comments'>
                <a name='comments'/>

                <b:include name='commentsTitle'/>

                <div class='comments-content'>
                  <b:if cond='data:post.embedCommentForm'>
                    <b:include data='post' name='threadedCommentJs'/>
                  </b:if>
                  <div id='comment-holder'>
                    <data:post.commentHtml/>
                  </div>
                </div>

                <p class='comment-footer'>
                  <b:if cond='data:post.allowNewComments'>
                    <b:include data='post' name='threadedCommentForm'/>
                    <b:else/>
                    <data:post.noNewCommentsText/>
                  </b:if>
                </p>

                <b:if cond='data:showCmtPopup'>
                  <div id='comment-popup'>
                    <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                    </iframe>
                  </div>
                </b:if>
              </section>
            </b:includable>
               <b:includable id='threadedCommentsDisqus' var='post'>
              <script type='text/javascript'>
                var disqus_blogger_current_url = &quot;<data:blog.canonicalUrl/>&quot;;
                if (!disqus_blogger_current_url.length) {
                  disqus_blogger_current_url = &quot;<data:blog.url/>&quot;;
                }
                var disqus_blogger_homepage_url = &quot;<data:blog.homepageUrl/>&quot;;
                var disqus_blogger_canonical_homepage_url = &quot;<data:blog.canonicalHomepageUrl/>&quot;;
              </script>
            </b:includable>
             </b:widget>
           </b:section>
              <div id='custom-ads'>
                <b:section cond='data:view.isPost' id='main-before-ad' maxwidgets='1' name='Post Ads 1' showaddelement='yes'>
                  <b:widget id='HTML5' locked='false' title='Announcement!' type='HTML' visible='false'>
                    <b:widget-settings>
                      <b:widget-setting name='content'><![CDATA[<a class="ads-here">Automatic Ads ( 728 x Auto)</a>]]></b:widget-setting>
                    </b:widget-settings>
                    <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
                  </b:widget>
                </b:section>
                <b:section cond='data:view.isPost' id='main-after-ad' maxwidgets='1' name='Post Ads 2' showaddelement='yes'>
                  <b:widget id='HTML7' locked='false' title='Action Movies' type='HTML' visible='false'>
                    <b:widget-settings>
                      <b:widget-setting name='content'/>
                    </b:widget-settings>
                    <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
                  </b:widget>
                </b:section>
              </div>
              <b:section cond='data:view.isPost' id='main-arel-ad' maxwidgets='1' name='Post Ads 3' showaddelement='yes'>
                <b:widget id='HTML8' locked='false' title='Animation Movies' type='HTML' visible='false'>
                  <b:widget-settings>
                    <b:widget-setting name='content'>&lt;!-- Bulletprofit - Ad Display Code --&gt;
&lt;div id=&quot;adm-container-79064&quot;&gt;&lt;/div&gt;&lt;script data-cfasync=&quot;false&quot; async type=&quot;text/javascript&quot; src=&quot;//bulletprofitads.com/display/items.php?79064&amp;20154&amp;970&amp;90&amp;4&amp;0&amp;42&quot;&gt;&lt;/script&gt;
&lt;!-- Bulletprofit - Ad Display Code --&gt;</b:widget-setting>
                  </b:widget-settings>
                  <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
                </b:widget>
              </b:section>
        <b:section class='home-ad' cond='data:view.isHomepage' id='home-ad-3' maxwidgets='1' name='Home Ads (C)' showaddelement='yes'>
          <b:widget id='HTML4' locked='false' title='' type='HTML' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[<a target="_blank" href="https://imdbux.com/ref/6269"><img src="https://imdbux.com/assets/banners/468x60.gif" border="0" width="468" height="60" /></a>]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
          </b:widget>
        </b:section>
      </div>

      <!-- Sidebar Wrapper -->
      <div id='sidebar-wrapper'>
        <b:section class='sidebar' id='social-section' maxwidgets='1' name='Social Icons' showaddelement='yes'>
          <b:widget id='LinkList156' locked='true' title='Follow us on social media' type='LinkList' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='link-5'>#</b:widget-setting>
              <b:widget-setting name='link-3'>#</b:widget-setting>
              <b:widget-setting name='link-4'>#</b:widget-setting>
              <b:widget-setting name='text-1'>facebook-f</b:widget-setting>
              <b:widget-setting name='text-0'>whatsapp</b:widget-setting>
              <b:widget-setting name='text-3'>instagram</b:widget-setting>
              <b:widget-setting name='text-2'>twitter</b:widget-setting>
              <b:widget-setting name='text-5'>email</b:widget-setting>
              <b:widget-setting name='text-4'>youtube</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='link-1'>#</b:widget-setting>
              <b:widget-setting name='link-2'>#</b:widget-setting>
              <b:widget-setting name='link-0'>http://</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
            <b:includable id='content'>
              <div class='widget-content'>
                <ul class='social-counter social'>
                  <b:loop values='data:links' var='link'>
                    <li expr:class='data:link.name'><a expr:href='data:link.target' target='_blank'/></li>
                  </b:loop>
                </ul>
              </div>
            </b:includable>
          </b:widget>
        </b:section>
        <b:section class='sidebar common-widget' id='sidebar-1' name='Sidebar Right (A)' showaddelement='yes'>
          <b:widget id='HTML6' locked='false' title='Tamil Radio Station' type='HTML' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'>&lt;script src=&quot;https://apps.elfsight.com/p/platform.js&quot; defer&gt;&lt;/script&gt;
&lt;div class=&quot;elfsight-app-c913aef1-82b3-4b57-bf55-8cd015d51fd8&quot;&gt;&lt;/div&gt;</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
          </b:widget>
          <b:widget id='HTML10' locked='false' title='Sidebar Ads Slot 300 x 250' type='HTML' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'>&lt;div class=&quot;ads-style&quot;&gt;300 X 250&lt;/div&gt;
&lt;style&gt;
.ads-style{display:block;font-size:15px;color:#aaaaaa;text-align:center;line-height:250px;background-color:rgba(0,0,0,0.5)}
&lt;/style&gt;</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
          </b:widget>
        </b:section>
        <b:section class='sidebar common-widget seth-sidebar-tabs' id='seth-sidebar-tabs' maxwidgets='3' name='Sidebar Tabs' showaddelement='yes'>
          <b:widget id='FollowByEmail1' locked='false' title='Follow by Email' type='FollowByEmail' visible='true'>
            <b:includable id='main' var='this'>
	  <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='content'>
      <div class='widget-content'>
        <span class='before-text'><data:skin.vars.followByEmail/></span>
        <div class='follow-by-email-inner'>
          <form action='https://feedburner.google.com/fb/a/mailverify' expr:onsubmit='&quot;window.open(\&quot;https://feedburner.google.com/fb/a/mailverify?uri=&quot; + data:feedPath + &quot;\&quot;, \&quot;popupwindow\&quot;, \&quot;scrollbars=yes,width=550,height=520\&quot;); return true&quot;' method='post' target='popupwindow'>
            <input autocomplete='off' class='follow-by-email-address' expr:placeholder='data:messages.emailAddress' name='email' type='email'/>
            <input class='follow-by-email-submit' expr:value='data:messages.subscribe' type='submit'/>
            <input expr:value='data:feedPath' name='uri' type='hidden'/>
            <input name='loc' type='hidden' value='en_US'/>
          </form>
        </div>
      </div>
    </b:includable>
          </b:widget>
        </b:section>
        <b:section class='sidebar common-widget' id='sidebar-2' name='Sidebar Right (B)' showaddelement='yes'>
          <b:widget id='Label1' locked='false' title='Labels' type='Label' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
              <b:widget-setting name='display'>CLOUD</b:widget-setting>
              <b:widget-setting name='selectedLabelsList'/>
              <b:widget-setting name='showType'>ALL</b:widget-setting>
              <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='cloud'>
  <b:loop values='data:labels' var='label'>
    <span class='label-size'>
      <b:class expr:name='&quot;label-size-&quot; + data:label.cssSize'/>
      <a class='label-name' expr:href='data:label.url'>
        <data:label.name/>
        <b:if cond='data:this.showFreqNumbers'>
          <span class='label-count'><data:label.count/></span>
        </b:if>
      </a>
    </span>
  </b:loop>
</b:includable>
            <b:includable id='content'>
      <div class='widget-content'>
        <b:class expr:name='data:this.display + &quot;-label&quot;'/>
        <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
        <b:include cond='data:this.display == &quot;cloud&quot;' name='list'/>
      </div>
    </b:includable>
            <b:includable id='list'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <a class='label-name' expr:href='data:label.url'>
              <data:label.name/>
              <b:if cond='data:this.showFreqNumbers'>
                <span class='label-count'><data:label.count/></span>
              </b:if>
            </a>
          </li>
        </b:loop>
      </ul>
    </b:includable>
          </b:widget>
        </b:section>
        </div>
      </div>
  </div>
 <div class='clearfix'/>

<!-- Footer Wrapper -->
<div class='borderxt-bar'/>
<div id='footer-wrapper'> 
  <div class='container row'>
    <b:section class='menu-footer' id='menu-footer' maxwidgets='1' name='Footer Menu' showaddelement='yes'>
      <b:widget id='LinkList76' locked='true' title='Footer Menu Widget' type='LinkList' version='2' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='sorting'>NONE</b:widget-setting>
          <b:widget-setting name='text-1'><![CDATA[<i class="fas fa-user-secret"></i>YouTube downloader]]></b:widget-setting>
          <b:widget-setting name='link-1'>https://telegram.dog/TendKottaYouTubeROBOT</b:widget-setting>
          <b:widget-setting name='text-0'><![CDATA[<i class="fas fa-user-secret"></i>Join Telegram]]></b:widget-setting>
          <b:widget-setting name='link-2'>https://telegram.dog/relaxzzzzz</b:widget-setting>
          <b:widget-setting name='link-0'>http://telegram.dog/tendkotta</b:widget-setting>
          <b:widget-setting name='text-2'><![CDATA[<i class="far fa-envelope"></i> Contact Us]]></b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
          <b:include name='widget-title'/>
          <b:include name='content'/>
        </b:includable>
        <b:includable id='content'>
          <div class='widget-content'>
            <ul>
              <b:loop values='data:links' var='link'>
                <li><a expr:href='data:link.target'><data:link.name/></a></li>
              </b:loop>
            </ul>
          </div>
        </b:includable>
      </b:widget>
    </b:section>
    <div class='copyright-area'><i class='far fa-copyright'/> All Rights Reserved By - <a href='/' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person' style='color:#fff;'><span itemprop='name'><data:blog.title/></span></a><script type='text/javascript'>
//<![CDATA[
document.write(unescape('%3C%64%69%76%20%69%64%3D%27%6D%79%63%6F%6E%74%65%6E%74%27%2F%3E'));
//]]>
</script>
    </div>
  </div>
</div>

  <div class='hidden-widgets' style='display:none'>
    <b:section class='hidden-widgets' deleted='true' id='hidden-widgets' maxwidgets='1' showaddelement='no'>
      <b:widget id='ContactForm1' locked='true' title='Formulário de contato' type='ContactForm' version='2' visible='true'>
        <b:includable id='main'>
          <b:include name='widget-title'/>
          <b:include name='content'/>
        </b:includable>
        <b:includable id='content'>
          <div class='contact-form-widget'>
            <div class='form'>
              <form name='contact-form'>
                <input class='contact-form-name' expr:id='data:widget.instanceId + &quot;_contact-form-name&quot;' expr:placeholder='data:contactFormNameMsg + &quot; *&quot;' name='name' size='30' type='text' value=''/>
                <input class='contact-form-email' expr:id='data:widget.instanceId + &quot;_contact-form-email&quot;' expr:placeholder='data:contactFormEmailMsg + &quot; *&quot;' name='email' size='30' type='text' value=''/>
                <textarea class='contact-form-email-message' cols='25' expr:id='data:widget.instanceId + &quot;_contact-form-email-message&quot;' expr:placeholder='data:contactFormMessageMsg + &quot; *&quot;' name='email-message' rows='5'/>
                <input class='contact-form-button contact-form-button-submit' expr:id='data:widget.instanceId + &quot;_contact-form-submit&quot;' expr:value='data:contactFormSendMsg' type='button'/>
                <p class='contact-form-error-message' expr:id='data:widget.instanceId + &quot;_contact-form-error-message&quot;'/>
                <p class='contact-form-success-message' expr:id='data:widget.instanceId + &quot;_contact-form-success-message&quot;'/>
              </form>
            </div>
          </div>
        </b:includable>
      </b:widget>
    </b:section>
  </div>

  </div>

<script type='text/javascript'>
//<![CDATA[
/*! Theia Sticky Sidebar | v1.7.0 - https://github.com/WeCodePixels/theia-sticky-sidebar */
(function($){$.fn.theiaStickySidebar=function(options){var defaults={'containerSelector':'','additionalMarginTop':0,'additionalMarginBottom':0,'updateSidebarHeight':true,'minWidth':0,'disableOnResponsiveLayouts':true,'sidebarBehavior':'modern','defaultPosition':'relative','namespace':'TSS'};options=$.extend(defaults,options);options.additionalMarginTop=parseInt(options.additionalMarginTop)||0;options.additionalMarginBottom=parseInt(options.additionalMarginBottom)||0;tryInitOrHookIntoEvents(options,this);function tryInitOrHookIntoEvents(options,$that){var success=tryInit(options,$that);if(!success){console.log('TSS: Body width smaller than options.minWidth. Init is delayed.');$(document).on('scroll.'+options.namespace,function(options,$that){return function(evt){var success=tryInit(options,$that);if(success){$(this).unbind(evt)}}}(options,$that));$(window).on('resize.'+options.namespace,function(options,$that){return function(evt){var success=tryInit(options,$that);if(success){$(this).unbind(evt)}}}(options,$that))}}function tryInit(options,$that){if(options.initialized===true){return true}if($('body').width()<options.minWidth){return false}init(options,$that);return true}function init(options,$that){options.initialized=true;var existingStylesheet=$('#theia-sticky-sidebar-stylesheet-'+options.namespace);if(existingStylesheet.length===0){$('head').append($('<style id="theia-sticky-sidebar-stylesheet-'+options.namespace+'">.theiaStickySidebar:after {content: ""; display: table; clear: both;}</style>'))}$that.each(function(){var o={};o.sidebar=$(this);o.options=options||{};o.container=$(o.options.containerSelector);if(o.container.length==0){o.container=o.sidebar.parent()}o.sidebar.parents().css('-webkit-transform','none');o.sidebar.css({'position':o.options.defaultPosition,'overflow':'visible','-webkit-box-sizing':'border-box','-moz-box-sizing':'border-box','box-sizing':'border-box'});o.stickySidebar=o.sidebar.find('.theiaStickySidebar');if(o.stickySidebar.length==0){var javaScriptMIMETypes=/(?:text|application)\/(?:x-)?(?:javascript|ecmascript)/i;o.sidebar.find('script').filter(function(index,script){return script.type.length===0||script.type.match(javaScriptMIMETypes)}).remove();o.stickySidebar=$('<div>').addClass('theiaStickySidebar').append(o.sidebar.children());o.sidebar.append(o.stickySidebar)}o.marginBottom=parseInt(o.sidebar.css('margin-bottom'));o.paddingTop=parseInt(o.sidebar.css('padding-top'));o.paddingBottom=parseInt(o.sidebar.css('padding-bottom'));var collapsedTopHeight=o.stickySidebar.offset().top;var collapsedBottomHeight=o.stickySidebar.outerHeight();o.stickySidebar.css('padding-top',1);o.stickySidebar.css('padding-bottom',1);collapsedTopHeight-=o.stickySidebar.offset().top;collapsedBottomHeight=o.stickySidebar.outerHeight()-collapsedBottomHeight-collapsedTopHeight;if(collapsedTopHeight==0){o.stickySidebar.css('padding-top',0);o.stickySidebarPaddingTop=0}else{o.stickySidebarPaddingTop=1}if(collapsedBottomHeight==0){o.stickySidebar.css('padding-bottom',0);o.stickySidebarPaddingBottom=0}else{o.stickySidebarPaddingBottom=1}o.previousScrollTop=null;o.fixedScrollTop=0;resetSidebar();o.onScroll=function(o){if(!o.stickySidebar.is(":visible")){return}if($('body').width()<o.options.minWidth){resetSidebar();return}if(o.options.disableOnResponsiveLayouts){var sidebarWidth=o.sidebar.outerWidth(o.sidebar.css('float')=='none');if(sidebarWidth+50>o.container.width()){resetSidebar();return}}var scrollTop=$(document).scrollTop();var position='static';if(scrollTop>=o.sidebar.offset().top+(o.paddingTop-o.options.additionalMarginTop)){var offsetTop=o.paddingTop+options.additionalMarginTop;var offsetBottom=o.paddingBottom+o.marginBottom+options.additionalMarginBottom;var containerTop=o.sidebar.offset().top;var containerBottom=o.sidebar.offset().top+getClearedHeight(o.container);var windowOffsetTop=0+options.additionalMarginTop;var windowOffsetBottom;var sidebarSmallerThanWindow=(o.stickySidebar.outerHeight()+offsetTop+offsetBottom)<$(window).height();if(sidebarSmallerThanWindow){windowOffsetBottom=windowOffsetTop+o.stickySidebar.outerHeight()}else{windowOffsetBottom=$(window).height()-o.marginBottom-o.paddingBottom-options.additionalMarginBottom}var staticLimitTop=containerTop-scrollTop+o.paddingTop;var staticLimitBottom=containerBottom-scrollTop-o.paddingBottom-o.marginBottom;var top=o.stickySidebar.offset().top-scrollTop;var scrollTopDiff=o.previousScrollTop-scrollTop;if(o.stickySidebar.css('position')=='fixed'){if(o.options.sidebarBehavior=='modern'){top+=scrollTopDiff}}if(o.options.sidebarBehavior=='stick-to-top'){top=options.additionalMarginTop}if(o.options.sidebarBehavior=='stick-to-bottom'){top=windowOffsetBottom-o.stickySidebar.outerHeight()}if(scrollTopDiff>0){top=Math.min(top,windowOffsetTop)}else{top=Math.max(top,windowOffsetBottom-o.stickySidebar.outerHeight())}top=Math.max(top,staticLimitTop);top=Math.min(top,staticLimitBottom-o.stickySidebar.outerHeight());var sidebarSameHeightAsContainer=o.container.height()==o.stickySidebar.outerHeight();if(!sidebarSameHeightAsContainer&&top==windowOffsetTop){position='fixed'}else if(!sidebarSameHeightAsContainer&&top==windowOffsetBottom-o.stickySidebar.outerHeight()){position='fixed'}else if(scrollTop+top-o.sidebar.offset().top-o.paddingTop<=options.additionalMarginTop){position='static'}else{position='absolute'}}if(position=='fixed'){var scrollLeft=$(document).scrollLeft();o.stickySidebar.css({'position':'fixed','width':getWidthForObject(o.stickySidebar)+'px','transform':'translateY('+top+'px)','left':(o.sidebar.offset().left+parseInt(o.sidebar.css('padding-left'))-scrollLeft)+'px','top':'0px'})}else if(position=='absolute'){var css={};if(o.stickySidebar.css('position')!='absolute'){css.position='absolute';css.transform='translateY('+(scrollTop+top-o.sidebar.offset().top-o.stickySidebarPaddingTop-o.stickySidebarPaddingBottom)+'px)';css.top='0px'}css.width=getWidthForObject(o.stickySidebar)+'px';css.left='';o.stickySidebar.css(css)}else if(position=='static'){resetSidebar()}if(position!='static'){if(o.options.updateSidebarHeight==true){o.sidebar.css({'min-height':o.stickySidebar.outerHeight()+o.stickySidebar.offset().top-o.sidebar.offset().top+o.paddingBottom})}}o.previousScrollTop=scrollTop};o.onScroll(o);$(document).on('scroll.'+o.options.namespace,function(o){return function(){o.onScroll(o)}}(o));$(window).on('resize.'+o.options.namespace,function(o){return function(){o.stickySidebar.css({'position':'static'});o.onScroll(o)}}(o));if(typeof ResizeSensor!=='undefined'){new ResizeSensor(o.stickySidebar[0],function(o){return function(){o.onScroll(o)}}(o))}function resetSidebar(){o.fixedScrollTop=0;o.sidebar.css({'min-height':'1px'});o.stickySidebar.css({'position':'static','width':'','transform':'none'})}function getClearedHeight(e){var height=e.height();e.children().each(function(){height=Math.max(height,$(this).height())});return height}})}function getWidthForObject(object){var width;try{width=object[0].getBoundingClientRect().width}catch(err){}if(typeof width==="undefined"){width=object.width()}return width}return this}})(jQuery);

/*! Shortcode.js by @nicinabox | v1.1.0 - https://github.com/nicinabox/shortcode.js */
var Shortcode=function(el,tags){if(!el){return}this.el=el;this.tags=tags;this.matches=[];this.regex='\\[{name}(\\s[\\s\\S]*?)?\\]'+'(?:((?!\\s*?(?:\\[{name}|\\[\\/(?!{name})))[\\s\\S]*?)'+'(\\[\/{name}\\]))?';if(this.el.jquery){this.el=this.el[0]}this.matchTags();this.convertMatchesToNodes();this.replaceNodes()};Shortcode.prototype.matchTags=function(){var html=this.el.outerHTML,instances,match,re,contents,regex,tag,options;for(var key in this.tags){if(!this.tags.hasOwnProperty(key)){return}re=this.template(this.regex,{name:key});instances=html.match(new RegExp(re,'g'))||[];for(var i=0,len=instances.length;i<len;i++){match=instances[i].match(new RegExp(re));contents=match[3]?'':undefined;tag=match[0];regex=this.escapeTagRegExp(tag);options=this.parseOptions(match[1]);if(match[2]){contents=match[2].trim();tag=tag.replace(contents,'').replace(/\n\s*/g,'');regex=this.escapeTagRegExp(tag).replace('\\]\\[','\\]([\\s\\S]*?)\\[')}this.matches.push({name:key,tag:tag,regex:regex,options:options,contents:contents})}}};Shortcode.prototype.convertMatchesToNodes=function(){var html=this.el.innerHTML,excludes,re,replacer;replacer=function(match,p1,p2,p3,p4,offset,string){if(p1){return match}else{var node=document.createElement('span');node.setAttribute('data-sc-tag',this.tag);node.className='rithiseth-sc-node rithiseth-sc-node-'+this.name;return node.outerHTML}};for(var i=0,len=this.matches.length;i<len;i++){excludes='((data-sc-tag=")|(<pre.*)|(<code.*))?';re=new RegExp(excludes+this.matches[i].regex,'g');html=html.replace(re,replacer.bind(this.matches[i]))}this.el.innerHTML=html};Shortcode.prototype.replaceNodes=function(){var self=this,html,match,result,done,node,fn,replacer,nodes=this.el.querySelectorAll('.rithiseth-sc-node');replacer=function(result){if(result.jquery){result=result[0]}result=self.parseCallbackResult(result);node.parentNode.replaceChild(result,node)};for(var i=0,len=this.matches.length;i<len;i++){match=this.matches[i];node=this.el.querySelector('.rithiseth-sc-node-'+match.name);if(node&&node.dataset.scTag===match.tag){fn=this.tags[match.name].bind(match);done=replacer.bind(match);result=fn(done);if(result!==undefined){done(result)}}}};Shortcode.prototype.parseCallbackResult=function(result){var container,fragment,children;switch(typeof result){case'function':result=document.createTextNode(result());break;case'string':container=document.createElement('div');fragment=document.createDocumentFragment();container.innerHTML=result;children=container.childNodes;if(children.length){for(var i=0,len=children.length;i<len;i++){fragment.appendChild(children[i].cloneNode(true))}result=fragment}else{result=document.createTextNode(result)}break;case'object':if(!result.nodeType){result=JSON.stringify(result);result=document.createTextNode(result)}break;case'default':break}return result};Shortcode.prototype.parseOptions=function(stringOptions){var options={},set;if(!stringOptions){return}set=stringOptions.replace(/(\w+=)/g,'\n$1').split('\n');set.shift();for(var i=0;i<set.length;i++){var kv=set[i].split('=');options[kv[0]]=kv[1].replace(/\'|\"/g,'').trim()}return options};Shortcode.prototype.escapeTagRegExp=function(regex){return regex.replace(/[\[\]\/]/g,'\\$&')};Shortcode.prototype.template=function(s,d){for(var p in d){s=s.replace(new RegExp('{'+p+'}','g'),d[p])}return s};String.prototype.trim=String.prototype.trim||function(){return this.replace(/^\s+|\s+$/g,'')};if(window.jQuery){var pluginName='shortcode';$.fn[pluginName]=function(tags){this.each(function(){if(!$.data(this,pluginName)){$.data(this,pluginName,new Shortcode(this,tags))}});return this}}

/*! rst-Player */
function getVideoPlaylist(i){if("undefined"!=typeof $){if(void 0!==i.playerList){var e,s,d=[],t=[],n=[],a=[],l="",o=0,f=0,r=7,c=4,v=50,p=$(i.playerContainer),h=p.width(),g=i.playerRatio.split(":");g=g[1]/g[0];for(var u=0;u<i.playerList.length;u++)d.push(i.playerList[u].file),t.push(i.playerList[u].title),n.push(i.playerList[u].description),a.push(i.playerList[u].image);for(l+='<div class="rst_player">',l+='<div class="rst_video"><span class="rst_loading"><div class="st_loading"><div class="circlex"></div><div class="circley"></div></div></span>',l+='<iframe id="video_player" src="" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen></iframe>',l+='<div class="rst_server"></div>',l+="</div>",l+='<div class="rst_videos">',l+='<ul class="rst_list"></ul>',l+='<div class="rst_control">',l+='<span class="sd_prevPage rst_button"><i class="fas fa-chevron-left"></i><i class="fas fa-chevron-left"></i></span>',l+='<span class="sd_prev rst_button"><i class="fas fa-chevron-left"></i></span>',l+='<span class="sd_next rst_button"><i class="fas fa-chevron-right"></i></span>',l+='<span class="sd_nextPage rst_button"><i class="fas fa-chevron-right"></i><i class="fas fa-chevron-right"></i></span>',l+="</div>",l+="</div>",l+="</div>",p.html(l),l="",u=0;u<t.length;u++)l+="<li>",l+='<img src="',m(d[u])?l+="http://i3.ytimg.com/vi/"+m(d[u])+"/hqdefault.jpg":d[u].indexOf("vimeo")>-1||d[u].indexOf("vid")>-1||d[u].indexOf("google")>-1||d[u].indexOf("verystream")>-1?l+=playerLogo:l+=a[u],l+='" />',l+="<div>",l+="<h2>",l+='<i class="',m(d[u])?l+="fab fa-youtube":d[u].indexOf("vimeo")>-1?l+="fab fa-vimeo":d[u].indexOf("google")>-1?l+="fab fa-google-drive":d[u].indexOf("verystream")>-1?l+="fab fa-firefox":d[u].indexOf("ok.ru")>-1?l+="fab fa-odnoklassniki":d[u].indexOf("facebook")>-1?l+="fab fa-facebook-square":l+="fas fa-video",l+="",l+='"></i> ',l+=t[u]+"</h2>",l+="</div>",l+="</li>";for(p.find(".rst_list").html(l),u=0;u<t.length;u++)d[u].indexOf("vimeo")>-1&&$.ajax({type:"GET",url:"http://vimeo.com/api/v2/video/"+d[u].substring(d[u].lastIndexOf("/")+1)+".json",jsonp:"callback",dataType:"jsonp",indexValue:u,success:function(i){var e=i[0].thumbnail_large;p.find(".rst_list").find("li").eq(this.indexValue).find("img").attr("src",e)}});$.getScript("http://f.vimeocdn.com/js/froogaloop2.min.js"),$.getScript("https://www.youtube.com/iframe_api");var _=!1;window.onYouTubeIframeAPIReady=function(){y()},p.find(".rst_list").click(function(){s=!0}),p.find(".rst_list").find("li").outerHeight(v),p.find(".rst_list").find("li").each(function(i){$(this).click(function(){var e,t;o=i,p.find(".rst_list").find("li").eq(i).hasClass("selected")||(p.find(".rst_list").find("li").removeClass("selected").eq(i).addClass("selected"),t=e=d[i],p.find(".rst_server").find("video").remove(),p.find(".rst_server").hide(),p.find("iframe").attr("src","").hide(),p.find(".rst_loading").show(),m(e)?(t="https://www.youtube.com/embed/"+m(e)+"?autoplay=1&loop=1&showinfo=0&rel=0&enablejsapi=1",s&&(t="https://www.youtube.com/embed/"+m(e)+"?autoplay=1&loop=1&showinfo=0&rel=0&enablejsapi=1"),p.find("iframe").attr("src",t).show(),_&&y()):e.indexOf("vimeo")>-1?(t="https://player.vimeo.com/video/"+e.substring(e.lastIndexOf("/")+1),s?p.find("iframe").attr("src",t+"?api=1&amp;player_id=video_player&amp;autoplay=1").show():p.find("iframe").attr("src",t+"?api=1&amp;player_id=video_player").show(),void 0!==p.find("iframe")[0].addEvent&&p.find("iframe")[0].addEvent("ready",function(i){p.find("iframe")[0].addEvent("finish",function(){s=!0,k()})})):e.indexOf("google")>-1?p.find("iframe").attr("src",t).show():e.indexOf("verystream")>-1?p.find("iframe").attr("src",t).show():e.indexOf("vid")>-1?p.find("iframe").attr("src",t).show():(l="",l+=s?'<video width="100%" height="100%" controls autoplay>':'<video width="100%" height="100%" controls>',l+='<source src="'+t.replace(".ogg",".mp4")+'" type="video/mp4">',l+='<source src="'+t.replace(".mp4",".ogg")+'" type="video/ogg">',l+="</video>",p.find(".rst_server").show().html(l),p.find("video").bind("ended",function(){s=!0,k()})),p.find("iframe").load(function(){p.find(".rst_loading").hide()}),w())})}),w(),$(window).resize(function(){b()}),b(),p.find(".rst_list").scroll(function(){x($(this))}),x(p.find(".rst_list")),p.find(".sd_prevPage").click(function(){$(this).hasClass("active")&&(f=p.find(".rst_list").scrollTop()-e*p.find(".rst_list").find("li").outerHeight(),f=Math.ceil(f/v),p.find(".rst_list").animate({scrollTop:f*v},500))}),p.find(".sd_prev").click(function(){o>0&&(o--,w(),O("prev"),p.find(".rst_list").find("li").eq(o).trigger("click"))}),p.find(".sd_next").click(function(){o<d.length-1&&(o++,w(),O("next"),p.find(".rst_list").find("li").eq(o).trigger("click"))}),p.find(".sd_nextPage").click(function(){$(this).hasClass("active")&&(f=p.find(".rst_list").scrollTop()+e*v,f=Math.ceil(f/v),p.find(".rst_list").animate({scrollTop:f*v},500))}),p.find(".rst_list").animate({scrollTop:0},10),p.find(".rst_list").find("li").eq(0).trigger("click"),$(document).ready(function(){$("").remove()})}}else alert("Please insert jQuery library!");function m(i){return i.indexOf("watch?v")>-1?i.substring(i.indexOf("?v=")+3):(i.indexOf("youtube")>-1||i.indexOf("youtu.be")>-1)&&i.substring(i.lastIndexOf("/")+1)}function y(){_=!0,new YT.Player("video_player",{events:{onStateChange:function(i){switch(i.data){case YT.PlayerState.ENDED:s=!0,k()}}}})}function w(){o>0?p.find(".sd_prev").addClass("active"):p.find(".sd_prev").removeClass("active"),o<d.length-1?p.find(".sd_next").addClass("active"):p.find(".sd_next").removeClass("active")}function b(){$(window).width()<i.playerMobile||!i.playerResponsive?(e=c,i.playerResponsive&&p.width($(window).width()),p.removeClass("rst_desktop"),p.find(".rst_list").height(e*v),p.find(".rst_video").height(p.find(".rst_video").width()*g),p.find(".rst_video").width("100%"),p.find(".rst_videos").width("100%")):(e=r,p.addClass("rst_desktop"),p.width(h),p.find(".rst_list").height(e*(v-.8)),p.find(".rst_video").height(p.find(".rst_videos").outerHeight()),p.find(".rst_video").css("width",i.playerDesktop),p.find(".rst_videos").css("width",100-parseInt(i.playerDesktop)+"%"))}function x(i){i.scrollTop()>0?p.find(".sd_prevPage").addClass("active"):p.find(".sd_prevPage").removeClass("active"),i[0].scrollHeight>=i.outerHeight()+i.scrollTop()+5?p.find(".sd_nextPage").addClass("active"):p.find(".sd_nextPage").removeClass("active")}function O(i){var s=p.find(".rst_list").scrollTop(),d=s+p.find(".rst_list").outerHeight(),t=p.find(".rst_list").find("li").eq(o).offset().top-p.find(".rst_list").find("li").eq(o).parent().offset().top+p.find(".rst_list").find("li").eq(o).outerHeight();return(t+s+10>=d+p.find(".rst_list").find("li").eq(o).outerHeight()||t<1)&&(f=o*v,"prev"==i&&(f=(o-e+1)*v),p.find(".rst_list").animate({scrollTop:f},500)),!0}function k(){o<d.length-1&&(o++,w(),O("next"),p.find(".rst_list").find("li").eq(o).trigger("click"))}}var timer=setInterval(function(){"undefined"!=typeof getPlayerOptions&&(new getVideoPlaylist(getPlayerOptions),clearInterval(timer))},50);
/*! rst-Firebase */
jQuery.getScript("//cdn.firebase.com/js/client/2.3.2/firebase.js").done(function(){$.each($(".post-view[data-id]"),function(e,a){var i=$(a).parent().find("#postviews").addClass("view-load"),t=new Firebase("https://posts-views-1.firebaseio.com/pages/id/"+$(a).attr("data-id"));t.once("value",function(e){var o=e.val(),d=!1;null==o&&((o={}).value=0,o.url=window.location.href,o.id=$(a).attr("data-id"),d=!0),i.removeClass("view-load").text(o.value),o.value++,"/"!=window.location.pathname&&(d?t.set(o):t.child("value").set(o.value))})})});

/*! rst-Tab */
!function(a){a.fn.sethTabx=function(b){b=jQuery.extend({onHover:false,animated:true,transition:'fadeInUp'},b);return this.each(function(){var e=a(this),c=e.children('[seth-tabx]'),d=0,n='tab-animated',k='tab-active';if(b.onHover==true){var event='mouseenter'}else{var event='click'}e.prepend('<ul class="select-tab"></ul>');c.each(function(){if(b.animated==true){a(this).addClass(n)}e.find('.select-tab').append('<li><a href="javascript:;">'+a(this).attr('seth-tabx')+'</a></li>')}).eq(d).addClass(k).addClass('tab-'+b.transition);e.find('.select-tab a').on(event,function(){var f=a(this).parent().index();a(this).closest('.select-tab').find('.active').removeClass('active');a(this).parent().addClass('active');c.removeClass(k).removeClass('tab-'+b.transition).eq(f).addClass(k).addClass('tab-'+b.transition);return false}).eq(d).parent().addClass('active')})}}(jQuery);
//]]>
</script>
<script type='text/javascript'>
//<![CDATA[
var _0x938a=["\x43\x72\x65\x61\x74\x65\x64\x20\x77\x69\x74\x68\x20\x3C\x69\x20\x73\x74\x79\x6C\x65\x3D\x22\x63\x6F\x6C\x6F\x72\x3A\x23\x66\x66\x36\x39\x35\x64\x3B\x22\x20\x63\x6C\x61\x73\x73\x3D\x22\x66\x61\x20\x66\x61\x2D\x68\x65\x61\x72\x74\x22\x3E\x3C\x2F\x69\x3E\x20\x62\x79\x20\x3C\x61\x20\x68\x72\x65\x66\x3D\x22\x68\x74\x74\x70\x73\x3A\x2F\x2F\x64\x65\x73\x74\x72\x6F\x79\x65\x72\x74\x68\x65\x6D\x65\x2E\x62\x6C\x6F\x67\x73\x70\x6F\x74\x2E\x63\x6F\x6D\x22\x3E\x44\x65\x73\x74\x72\x6F\x79\x65\x72\x20\x54\x68\x65\x6D\x65\x3C\x2F\x61\x3E","\x68\x74\x6D\x6C","\x64\x69\x73\x70\x6C\x61\x79","\x69\x6E\x6C\x69\x6E\x65\x2D\x62\x6C\x6F\x63\x6B","\x63\x73\x73","\x23\x6D\x79\x63\x6F\x6E\x74\x65\x6E\x74","\x6C\x65\x6E\x67\x74\x68","\x23\x6D\x79\x63\x6F\x6E\x74\x65\x6E\x74\x3A\x76\x69\x73\x69\x62\x6C\x65","\x68\x72\x65\x66","\x6C\x6F\x63\x61\x74\x69\x6F\x6E","\x68\x74\x74\x70\x73\x3A\x2F\x2F\x64\x65\x73\x74\x72\x6F\x79\x65\x72\x74\x68\x65\x6D\x65\x2E\x62\x6C\x6F\x67\x73\x70\x6F\x74\x2E\x63\x6F\x6D","\x72\x65\x61\x64\x79","\x61","\x63\x68\x69\x6C\x64\x72\x65\x6E","\x2E\x4C\x69\x6E\x6B\x4C\x69\x73\x74\x20\x75\x6C\x20\x3E\x20\x6C\x69","\x66\x69\x6E\x64","\x65\x71","\x74\x65\x78\x74","\x5F","\x63\x68\x61\x72\x41\x74","\x70\x61\x72\x65\x6E\x74","\x3C\x75\x6C\x20\x63\x6C\x61\x73\x73\x3D\x22\x73\x75\x62\x2D\x6D\x65\x6E\x75\x20\x6D\x2D\x73\x75\x62\x22\x2F\x3E","\x61\x70\x70\x65\x6E\x64","","\x72\x65\x70\x6C\x61\x63\x65","\x2E\x73\x75\x62\x2D\x6D\x65\x6E\x75","\x61\x70\x70\x65\x6E\x64\x54\x6F","\x3C\x75\x6C\x20\x63\x6C\x61\x73\x73\x3D\x22\x73\x75\x62\x2D\x6D\x65\x6E\x75\x32\x20\x6D\x2D\x73\x75\x62\x22\x2F\x3E","\x2E\x73\x75\x62\x2D\x6D\x65\x6E\x75\x32","\x68\x61\x73\x2D\x73\x75\x62","\x61\x64\x64\x43\x6C\x61\x73\x73","\x6C\x69","\x23\x6D\x61\x69\x6E\x2D\x6D\x65\x6E\x75\x20\x75\x6C\x20\x6C\x69\x20\x75\x6C","\x73\x68\x6F\x77\x2D\x6D\x65\x6E\x75","\x23\x6D\x61\x69\x6E\x2D\x6D\x65\x6E\x75\x20\x2E\x77\x69\x64\x67\x65\x74","\x65\x61\x63\x68","\x23\x6D\x61\x69\x6E\x2D\x6D\x65\x6E\x75","\x2E\x6D\x6F\x62\x69\x6C\x65\x2D\x6D\x65\x6E\x75","\x63\x6C\x6F\x6E\x65","\x23\x6D\x61\x69\x6E\x2D\x6D\x65\x6E\x75\x2D\x6E\x61\x76","\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x73\x75\x62\x6D\x65\x6E\x75\x2D\x74\x6F\x67\x67\x6C\x65\x22\x2F\x3E","\x2E\x6D\x6F\x62\x69\x6C\x65\x2D\x6D\x65\x6E\x75\x20\x2E\x68\x61\x73\x2D\x73\x75\x62","\x74\x72\x69\x6D","\x61\x74\x74\x72","\x74\x6F\x4C\x6F\x77\x65\x72\x43\x61\x73\x65","\x2F","\x73\x70\x6C\x69\x74","\x6D\x65\x67\x61\x2D\x6D\x65\x6E\x75","\x6D\x61\x74\x63\x68","\x2F\x73\x65\x61\x72\x63\x68\x2F\x6C\x61\x62\x65\x6C\x2F","\x3F\x26\x6D\x61\x78\x2D\x72\x65\x73\x75\x6C\x74\x73\x3D","\x2E\x6D\x6F\x62\x69\x6C\x65\x2D\x6D\x65\x6E\x75\x20\x75\x6C\x20\x3E\x20\x6C\x69\x20\x61","\x63\x6C\x69\x63\x6B","\x6E\x61\x76\x2D\x61\x63\x74\x69\x76\x65","\x74\x6F\x67\x67\x6C\x65\x43\x6C\x61\x73\x73","\x62\x6F\x64\x79","\x6F\x6E","\x2E\x6D\x6F\x62\x69\x6C\x65\x2D\x6D\x65\x6E\x75\x2D\x74\x6F\x67\x67\x6C\x65","\x68\x61\x73\x43\x6C\x61\x73\x73","\x70\x72\x65\x76\x65\x6E\x74\x44\x65\x66\x61\x75\x6C\x74","\x73\x68\x6F\x77","\x73\x6C\x69\x64\x65\x54\x6F\x67\x67\x6C\x65","\x3E\x20\x2E\x6D\x2D\x73\x75\x62","\x72\x65\x6D\x6F\x76\x65\x43\x6C\x61\x73\x73","\x2E\x6D\x2D\x73\x75\x62","\x2E\x6D\x6F\x62\x69\x6C\x65\x2D\x6D\x65\x6E\x75\x20\x75\x6C\x20\x6C\x69\x20\x2E\x73\x75\x62\x6D\x65\x6E\x75\x2D\x74\x6F\x67\x67\x6C\x65","\x66\x6F\x63\x75\x73","\x69\x6E\x70\x75\x74","\x66\x61\x64\x65\x49\x6E","\x23\x6E\x61\x76\x2D\x73\x65\x61\x72\x63\x68\x2C\x20\x2E\x6D\x6F\x62\x69\x6C\x65\x2D\x73\x65\x61\x72\x63\x68\x2D\x66\x6F\x72\x6D","\x2E\x73\x68\x6F\x77\x2D\x73\x65\x61\x72\x63\x68","\x62\x6C\x75\x72","\x66\x61\x64\x65\x4F\x75\x74","\x2E\x68\x69\x64\x65\x2D\x73\x65\x61\x72\x63\x68","\x2E\x4C\x61\x62\x65\x6C\x20\x61\x2C\x20\x61\x2E\x62\x2D\x6C\x61\x62\x65\x6C\x2C\x20\x61\x2E\x70\x6F\x73\x74\x2D\x74\x61\x67","\x73\x72\x63","\x2F\x2F\x69\x6D\x67\x31\x2E\x62\x6C\x6F\x67\x62\x6C\x6F\x67\x2E\x63\x6F\x6D\x2F\x69\x6D\x67\x2F\x62\x6C\x61\x6E\x6B\x2E\x67\x69\x66","\x2F\x2F\x34\x2E\x62\x70\x2E\x62\x6C\x6F\x67\x73\x70\x6F\x74\x2E\x63\x6F\x6D\x2F\x2D\x75\x43\x6A\x59\x67\x56\x46\x49\x68\x37\x30\x2F\x56\x75\x4F\x4C\x6E\x2D\x6D\x4C\x37\x50\x49\x2F\x41\x41\x41\x41\x41\x41\x41\x41\x44\x55\x73\x2F\x4B\x63\x75\x39\x77\x4A\x62\x76\x37\x39\x30\x68\x49\x6F\x38\x33\x72\x49\x5F\x73\x37\x6C\x4C\x57\x33\x7A\x6B\x4C\x59\x30\x31\x45\x41\x2F\x73\x35\x35\x2D\x72\x2F\x61\x76\x61\x74\x61\x72\x2E\x70\x6E\x67","\x2F\x73\x33\x35\x2D\x63\x2F","\x2F\x73\x34\x35\x2D\x63\x2F","\x2E\x61\x76\x61\x74\x61\x72\x2D\x69\x6D\x61\x67\x65\x2D\x63\x6F\x6E\x74\x61\x69\x6E\x65\x72\x20\x69\x6D\x67","\x6F\x70\x74\x69\x6F\x6E\x73","\x3C\x64\x69\x76\x20\x69\x64\x3D\x22\x6E\x65\x77\x2D\x62\x65\x66\x6F\x72\x65\x2D\x61\x64\x22\x2F\x3E","\x61\x64\x73\x31","\x3C\x64\x69\x76\x20\x69\x64\x3D\x22\x6E\x65\x77\x2D\x61\x66\x74\x65\x72\x2D\x61\x64\x22\x2F\x3E","\x61\x64\x73\x32","\x69\x64","\x73\x68\x6F\x72\x74\x63\x6F\x64\x65","\x23\x70\x6F\x73\x74\x2D\x62\x6F\x64\x79","\x23\x62\x65\x66\x6F\x72\x65\x2D\x61\x64","\x23\x6E\x65\x77\x2D\x62\x65\x66\x6F\x72\x65\x2D\x61\x64","\x23\x61\x66\x74\x65\x72\x2D\x61\x64","\x23\x6E\x65\x77\x2D\x61\x66\x74\x65\x72\x2D\x61\x64","\x23\x6D\x61\x69\x6E\x2D\x62\x65\x66\x6F\x72\x65\x2D\x61\x64\x20\x2E\x77\x69\x64\x67\x65\x74","\x23\x6D\x61\x69\x6E\x2D\x61\x66\x74\x65\x72\x2D\x61\x64\x20\x2E\x77\x69\x64\x67\x65\x74","\x23\x61\x72\x65\x6C\x2D\x61\x64","\x23\x6D\x61\x69\x6E\x2D\x61\x72\x65\x6C\x2D\x61\x64\x20\x2E\x77\x69\x64\x67\x65\x74","\x64\x61\x74\x61","\x2F\x66\x65\x65\x64\x73\x2F\x70\x6F\x73\x74\x73\x2F\x64\x65\x66\x61\x75\x6C\x74\x2F","\x3F\x61\x6C\x74\x3D\x6A\x73\x6F\x6E","\x67\x65\x74","\x6A\x73\x6F\x6E\x70","\x24\x74","\x63\x6F\x6E\x74\x65\x6E\x74","\x65\x6E\x74\x72\x79","\x3C\x64\x69\x76\x3E","\x73\x74\x72\x69\x6B\x65\x3A\x63\x6F\x6E\x74\x61\x69\x6E\x73\x28\x22\x65\x70\x69\x73\x6F\x64\x65\x2F\x22\x29","\x2E\x70\x6F\x73\x74\x5F\x65\x70\x69\x73\x6F\x64\x65","\x61\x6A\x61\x78","\x2E\x70\x6F\x73\x74\x2D\x65\x70\x69\x73\x6F\x64\x65\x2D\x69\x6E\x66\x6F","\x68\x69\x64\x65","\x2E\x70\x6F\x73\x74\x2D\x65\x70\x69\x73\x6F\x64\x65\x20\x2E\x70\x6F\x73\x74\x2D\x62\x6F\x64\x79","\x72\x65\x6D\x6F\x76\x65","\x23\x70\x6C\x61\x79\x65\x72","\x63\x6F\x6E\x74\x61\x63\x74\x2D\x66\x6F\x72\x6D","\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x63\x6F\x6E\x74\x61\x63\x74\x2D\x66\x6F\x72\x6D\x22\x2F\x3E","\x72\x65\x70\x6C\x61\x63\x65\x57\x69\x74\x68","\x23\x43\x6F\x6E\x74\x61\x63\x74\x46\x6F\x72\x6D\x31","\x2E\x63\x6F\x6E\x74\x61\x63\x74\x2D\x66\x6F\x72\x6D","\x6C\x65\x66\x74\x2D\x73\x69\x64\x65\x62\x61\x72","\x3C\x73\x74\x79\x6C\x65\x3E\x2E\x69\x74\x65\x6D\x20\x23\x6D\x61\x69\x6E\x2D\x77\x72\x61\x70\x70\x65\x72\x7B\x66\x6C\x6F\x61\x74\x3A\x72\x69\x67\x68\x74\x7D\x2E\x69\x74\x65\x6D\x20\x23\x73\x69\x64\x65\x62\x61\x72\x2D\x77\x72\x61\x70\x70\x65\x72\x7B\x66\x6C\x6F\x61\x74\x3A\x6C\x65\x66\x74\x7D\x3C\x2F\x73\x74\x79\x6C\x65\x3E","\x72\x69\x67\x68\x74\x2D\x73\x69\x64\x65\x62\x61\x72","\x3C\x73\x74\x79\x6C\x65\x3E\x2E\x69\x74\x65\x6D\x20\x23\x6D\x61\x69\x6E\x2D\x77\x72\x61\x70\x70\x65\x72\x7B\x66\x6C\x6F\x61\x74\x3A\x6C\x65\x66\x74\x7D\x2E\x69\x74\x65\x6D\x20\x23\x73\x69\x64\x65\x62\x61\x72\x2D\x77\x72\x61\x70\x70\x65\x72\x7B\x66\x6C\x6F\x61\x74\x3A\x72\x69\x67\x68\x74\x7D\x3C\x2F\x73\x74\x79\x6C\x65\x3E","\x66\x75\x6C\x6C\x2D\x77\x69\x64\x74\x68","\x3C\x73\x74\x79\x6C\x65\x3E\x2E\x69\x74\x65\x6D\x20\x23\x6D\x61\x69\x6E\x2D\x77\x72\x61\x70\x70\x65\x72\x7B\x77\x69\x64\x74\x68\x3A\x31\x30\x30\x25\x7D\x2E\x69\x74\x65\x6D\x20\x23\x73\x69\x64\x65\x62\x61\x72\x2D\x77\x72\x61\x70\x70\x65\x72\x7B\x64\x69\x73\x70\x6C\x61\x79\x3A\x6E\x6F\x6E\x65\x7D\x3C\x2F\x73\x74\x79\x6C\x65\x3E","\x2E\x70\x6F\x73\x74\x2D\x62\x6F\x64\x79\x20\x73\x74\x72\x69\x6B\x65","\x75\x72\x6C","\x77\x69\x64\x74\x68","\x68\x65\x69\x67\x68\x74","\x73\x63\x72\x65\x65\x6E","\x72\x6F\x75\x6E\x64","\x5F\x62\x6C\x61\x6E\x6B","\x73\x63\x72\x6F\x6C\x6C\x62\x61\x72\x73\x3D\x79\x65\x73\x2C\x72\x65\x73\x69\x7A\x61\x62\x6C\x65\x3D\x79\x65\x73\x2C\x74\x6F\x6F\x6C\x62\x61\x72\x3D\x6E\x6F\x2C\x6C\x6F\x63\x61\x74\x69\x6F\x6E\x3D\x79\x65\x73\x2C\x77\x69\x64\x74\x68\x3D","\x2C\x68\x65\x69\x67\x68\x74\x3D","\x2C\x6C\x65\x66\x74\x3D","\x2C\x74\x6F\x70\x3D","\x6F\x70\x65\x6E","\x2E\x73\x68\x61\x72\x65\x2D\x6C\x69\x6E\x6B\x73\x20\x2E\x77\x69\x6E\x64\x6F\x77\x2D\x75\x70\x65\x78","\x73\x68\x6F\x77\x2D\x68\x69\x64\x64\x65\x6E","\x2E\x73\x68\x6F\x77\x2D\x68\x69\x64\x20\x61","\x2E\x73\x68\x61\x72\x65\x2D\x6C\x69\x6E\x6B\x73","\x2E\x77\x69\x64\x67\x65\x74\x2D\x74\x69\x74\x6C\x65\x20\x3E\x20\x68\x33","\x73\x65\x74\x68\x2D\x74\x61\x62\x78","\x23\x73\x65\x74\x68\x2D\x73\x69\x64\x65\x62\x61\x72\x2D\x74\x61\x62\x73\x20\x2E\x77\x69\x64\x67\x65\x74","\x73\x65\x74\x68\x54\x61\x62\x78","\x23\x73\x65\x74\x68\x2D\x73\x69\x64\x65\x62\x61\x72\x2D\x74\x61\x62\x73","\x74\x61\x62\x73\x2D","\x74\x68\x65\x69\x61\x53\x74\x69\x63\x6B\x79\x53\x69\x64\x65\x62\x61\x72","\x23\x6D\x61\x69\x6E\x2D\x77\x72\x61\x70\x70\x65\x72\x2C\x20\x23\x73\x69\x64\x65\x62\x61\x72\x2D\x77\x72\x61\x70\x70\x65\x72","\x73\x63\x72\x6F\x6C\x6C","\x73\x63\x72\x6F\x6C\x6C\x54\x6F\x70","\x61\x6E\x69\x6D\x61\x74\x65","\x68\x74\x6D\x6C\x2C\x20\x62\x6F\x64\x79","\x2E\x62\x61\x63\x6B\x2D\x74\x6F\x70","\x23\x6D\x61\x69\x6E\x2D\x6D\x65\x6E\x75\x20\x23\x6D\x61\x69\x6E\x2D\x6D\x65\x6E\x75\x2D\x6E\x61\x76\x20\x6C\x69","\x23\x68\x6F\x74\x2D\x73\x65\x63\x74\x69\x6F\x6E\x20\x2E\x77\x69\x64\x67\x65\x74\x2D\x63\x6F\x6E\x74\x65\x6E\x74","\x23\x66\x65\x61\x74\x2D\x73\x65\x63\x74\x69\x6F\x6E\x20\x2E\x77\x69\x64\x67\x65\x74\x2D\x63\x6F\x6E\x74\x65\x6E\x74","\x2E\x63\x6F\x6D\x6D\x6F\x6E\x2D\x77\x69\x64\x67\x65\x74\x20\x2E\x77\x69\x64\x67\x65\x74\x2D\x63\x6F\x6E\x74\x65\x6E\x74","\x6C\x61\x62\x65\x6C","\x2E\x72\x65\x6C\x61\x74\x65\x64\x2D\x74\x61\x67","\x72\x65\x6C\x61\x74\x65\x64","\x2E\x72\x65\x6C\x61\x74\x65\x64\x2D\x72\x65\x61\x64\x79","\x6C\x69\x6E\x6B","\x61\x6C\x74\x65\x72\x6E\x61\x74\x65","\x72\x65\x6C","\x3C\x61\x20\x68\x72\x65\x66\x3D\x22","\x22\x3E","\x74\x69\x74\x6C\x65","\x3C\x2F\x61\x3E","\x6D\x65\x64\x69\x61\x24\x74\x68\x75\x6D\x62\x6E\x61\x69\x6C","\x2F\x73\x37\x32\x2D\x63","\x2F\x77\x36\x38\x30","\x79\x6F\x75\x74\x75\x62\x65\x2E\x63\x6F\x6D\x2F\x65\x6D\x62\x65\x64","\x69\x6E\x64\x65\x78\x4F\x66","\x2F\x64\x65\x66\x61\x75\x6C\x74\x2E","\x2F\x68\x71\x64\x65\x66\x61\x75\x6C\x74\x2E","\x3C\x69\x6D\x67","\x69\x6D\x67\x3A\x66\x69\x72\x73\x74","\x3C\x69\x6D\x67\x20\x63\x6C\x61\x73\x73\x3D\x22\x70\x6F\x73\x74\x2D\x74\x68\x75\x6D\x62\x22\x20\x61\x6C\x74\x3D\x22","\x22\x20\x73\x72\x63\x3D\x22","\x22\x2F\x3E","\x3C\x73\x70\x61\x6E\x20\x63\x6C\x61\x73\x73\x3D\x22\x70\x6F\x73\x74\x5F\x65\x70\x69\x73\x6F\x64\x65\x20\x73\x68\x6F\x77\x22\x3E","\x3C\x2F\x73\x70\x61\x6E\x3E","\x3C\x75\x6C\x20\x63\x6C\x61\x73\x73\x3D\x22\x6E\x6F\x2D\x70\x6F\x73\x74\x73\x22\x3E\x3C\x62\x3E\x45\x72\x72\x6F\x72\x3A\x3C\x2F\x62\x3E\x20\x4E\x6F\x20\x50\x6F\x73\x74\x73\x20\x46\x6F\x75\x6E\x64\x20\x3C\x69\x20\x63\x6C\x61\x73\x73\x3D\x27\x66\x61\x72\x20\x66\x61\x2D\x66\x72\x6F\x77\x6E\x27\x2F\x3E\x3C\x2F\x75\x6C\x3E","\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x68\x6F\x74\x2D\x6C\x6F\x61\x64\x65\x72\x22\x2F\x3E","\x68\x6F\x74\x2D\x70\x6F\x73\x74\x73","\x66\x65\x61\x74\x75\x72\x65\x64","\x67\x72\x69\x64\x2D\x70\x6F\x73\x74\x73","\x72\x65\x63\x65\x6E\x74","\x2F\x66\x65\x65\x64\x73\x2F\x70\x6F\x73\x74\x73\x2F\x64\x65\x66\x61\x75\x6C\x74\x3F\x61\x6C\x74\x3D\x6A\x73\x6F\x6E\x2D\x69\x6E\x2D\x73\x63\x72\x69\x70\x74\x26\x6D\x61\x78\x2D\x72\x65\x73\x75\x6C\x74\x73\x3D","\x72\x61\x6E\x64\x6F\x6D","\x2F\x66\x65\x65\x64\x73\x2F\x70\x6F\x73\x74\x73\x2F\x64\x65\x66\x61\x75\x6C\x74\x3F\x6D\x61\x78\x2D\x72\x65\x73\x75\x6C\x74\x73\x3D","\x26\x73\x74\x61\x72\x74\x2D\x69\x6E\x64\x65\x78\x3D","\x66\x6C\x6F\x6F\x72","\x26\x61\x6C\x74\x3D\x6A\x73\x6F\x6E\x2D\x69\x6E\x2D\x73\x63\x72\x69\x70\x74","\x2F\x66\x65\x65\x64\x73\x2F\x70\x6F\x73\x74\x73\x2F\x64\x65\x66\x61\x75\x6C\x74\x2F\x2D\x2F","\x3F\x61\x6C\x74\x3D\x6A\x73\x6F\x6E\x2D\x69\x6E\x2D\x73\x63\x72\x69\x70\x74\x26\x6D\x61\x78\x2D\x72\x65\x73\x75\x6C\x74\x73\x3D","\x73\x68\x6F\x77\x2D\x68\x6F\x74","\x3C\x75\x6C\x20\x63\x6C\x61\x73\x73\x3D\x22\x6D\x65\x67\x61\x2D\x6D\x65\x6E\x75\x2D\x69\x6E\x6E\x65\x72\x22\x3E","\x3C\x75\x6C\x20\x63\x6C\x61\x73\x73\x3D\x22\x68\x6F\x74\x2D\x70\x6F\x73\x74\x73\x22\x3E","\x3C\x75\x6C\x20\x63\x6C\x61\x73\x73\x3D\x22\x66\x65\x61\x74\x75\x72\x65\x64\x2D\x70\x6F\x73\x74\x73\x22\x3E","\x3C\x75\x6C\x20\x63\x6C\x61\x73\x73\x3D\x22\x63\x75\x73\x74\x6F\x6D\x2D\x77\x69\x64\x67\x65\x74\x22\x3E","\x3C\x75\x6C\x20\x63\x6C\x61\x73\x73\x3D\x22\x72\x65\x6C\x61\x74\x65\x64\x2D\x70\x6F\x73\x74\x73\x22\x3E","\x66\x65\x65\x64","\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x6D\x65\x67\x61\x2D\x69\x74\x65\x6D\x20\x69\x74\x65\x6D\x2D","\x22\x3E\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x6D\x65\x67\x61\x2D\x63\x6F\x6E\x74\x65\x6E\x74\x22\x3E\x3C\x61\x20\x63\x6C\x61\x73\x73\x3D\x22\x70\x6F\x73\x74\x2D\x69\x6D\x61\x67\x65\x2D\x6C\x69\x6E\x6B\x22\x20\x68\x72\x65\x66\x3D\x22","\x3C\x2F\x61\x3E\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x70\x6F\x73\x74\x2D\x69\x6E\x66\x6F\x22\x3E\x3C\x68\x32\x20\x63\x6C\x61\x73\x73\x3D\x22\x70\x6F\x73\x74\x2D\x74\x69\x74\x6C\x65\x22\x3E","\x3C\x2F\x68\x32\x3E\x3C\x2F\x64\x69\x76\x3E\x3C\x2F\x64\x69\x76\x3E\x3C\x2F\x64\x69\x76\x3E","\x3C\x6C\x69\x20\x63\x6C\x61\x73\x73\x3D\x22\x68\x6F\x74\x2D\x69\x74\x65\x6D\x20\x69\x74\x65\x6D\x2D","\x22\x3E\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x68\x6F\x74\x2D\x69\x74\x65\x6D\x2D\x69\x6E\x6E\x65\x72\x22\x3E\x3C\x61\x20\x63\x6C\x61\x73\x73\x3D\x22\x70\x6F\x73\x74\x2D\x69\x6D\x61\x67\x65\x2D\x6C\x69\x6E\x6B\x22\x20\x68\x72\x65\x66\x3D\x22","\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x70\x6F\x73\x74\x2D\x69\x6E\x66\x6F\x22\x3E\x3C\x68\x32\x20\x63\x6C\x61\x73\x73\x3D\x22\x70\x6F\x73\x74\x2D\x74\x69\x74\x6C\x65\x22\x3E","\x3C\x2F\x68\x32\x3E\x3C\x2F\x64\x69\x76\x3E\x3C\x2F\x64\x69\x76\x3E\x3C\x2F\x6C\x69\x3E","\x3C\x6C\x69\x20\x63\x6C\x61\x73\x73\x3D\x22\x66\x65\x61\x74\x2D\x69\x74\x65\x6D\x20\x69\x74\x65\x6D\x2D","\x22\x3E\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x66\x65\x61\x74\x75\x72\x65\x64\x2D\x69\x74\x65\x6D\x2D\x69\x6E\x6E\x65\x72\x22\x3E\x3C\x61\x20\x63\x6C\x61\x73\x73\x3D\x22\x70\x6F\x73\x74\x2D\x69\x6D\x61\x67\x65\x2D\x6C\x69\x6E\x6B\x22\x20\x68\x72\x65\x66\x3D\x22","\x3C\x6C\x69\x20\x63\x6C\x61\x73\x73\x3D\x22\x69\x74\x65\x6D\x2D","\x22\x3E\x3C\x61\x20\x63\x6C\x61\x73\x73\x3D\x22\x70\x6F\x73\x74\x2D\x69\x6D\x61\x67\x65\x2D\x6C\x69\x6E\x6B\x22\x20\x68\x72\x65\x66\x3D\x22","\x3C\x2F\x68\x32\x3E\x3C\x2F\x64\x69\x76\x3E\x3C\x2F\x6C\x69\x3E","\x3C\x6C\x69\x20\x63\x6C\x61\x73\x73\x3D\x22\x72\x65\x6C\x61\x74\x65\x64\x2D\x69\x74\x65\x6D\x20\x69\x74\x65\x6D\x2D","\x22\x3E\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x72\x65\x6C\x61\x74\x65\x64\x2D\x69\x74\x65\x6D\x2D\x69\x6E\x6E\x65\x72\x22\x3E\x3C\x61\x20\x63\x6C\x61\x73\x73\x3D\x22\x70\x6F\x73\x74\x2D\x69\x6D\x61\x67\x65\x2D\x6C\x69\x6E\x6B\x22\x20\x68\x72\x65\x66\x3D\x22","\x3C\x2F\x75\x6C\x3E","\x68\x61\x73\x2D\x73\x75\x62\x20\x6D\x65\x67\x61\x2D\x6D\x65\x6E\x75","\x2F\x73\x65\x61\x72\x63\x68\x2F\x3F\x26\x6D\x61\x78\x2D\x72\x65\x73\x75\x6C\x74\x73\x3D","\x61\x3A\x66\x69\x72\x73\x74","\x2F\x73\x65\x61\x72\x63\x68","\x3C\x61\x20\x63\x6C\x61\x73\x73\x3D\x22\x73\x68\x6F\x77\x2D\x6D\x6F\x72\x65\x22\x20\x68\x72\x65\x66\x3D\x22","\x73\x68\x6F\x77\x4D\x6F\x72\x65","\x74\x69\x74\x6C\x65\x2D\x77\x72\x61\x70","\x2E\x77\x69\x64\x67\x65\x74\x2D\x74\x69\x74\x6C\x65","\x73\x68\x6F\x77\x2D\x66\x65\x61\x74\x75\x72\x65\x64","\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x66\x62\x2D\x63\x6F\x6D\x6D\x65\x6E\x74\x73\x22\x20\x64\x61\x74\x61\x2D\x77\x69\x64\x74\x68\x3D\x22\x31\x30\x30\x25\x22\x20\x64\x61\x74\x61\x2D\x68\x72\x65\x66\x3D\x22","\x22\x20\x64\x61\x74\x61\x2D\x63\x6F\x6C\x6F\x72\x73\x63\x68\x65\x6D\x65\x3D\x22\x64\x61\x72\x6B\x22\x20\x64\x61\x74\x61\x2D\x6F\x72\x64\x65\x72\x2D\x62\x79\x3D\x22\x74\x69\x6D\x65\x22\x20\x64\x61\x74\x61\x2D\x6E\x75\x6D\x70\x6F\x73\x74\x73\x3D\x22\x35\x22\x3E\x3C\x2F\x64\x69\x76\x3E","\x63\x6F\x6D\x6D\x65\x6E\x74\x73\x2D\x73\x79\x73\x74\x65\x6D\x2D","\x62\x6C\x6F\x67\x67\x65\x72","\x64\x69\x73\x71\x75\x73","\x74\x79\x70\x65","\x73\x63\x72\x69\x70\x74","\x63\x72\x65\x61\x74\x65\x45\x6C\x65\x6D\x65\x6E\x74","\x74\x65\x78\x74\x2F\x6A\x61\x76\x61\x73\x63\x72\x69\x70\x74","\x61\x73\x79\x6E\x63","\x2F\x2F","\x2E\x64\x69\x73\x71\x75\x73\x2E\x63\x6F\x6D\x2F\x65\x6D\x62\x65\x64\x2E\x6A\x73","\x61\x70\x70\x65\x6E\x64\x43\x68\x69\x6C\x64","\x68\x65\x61\x64","\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x73\x42\x79\x54\x61\x67\x4E\x61\x6D\x65","\x23\x63\x6F\x6D\x6D\x65\x6E\x74\x73\x2C\x20\x23\x67\x70\x6C\x75\x73\x63\x6F\x6D\x6D\x65\x6E\x74\x73","\x3C\x64\x69\x76\x20\x69\x64\x3D\x22\x64\x69\x73\x71\x75\x73\x5F\x74\x68\x72\x65\x61\x64\x22\x2F\x3E","\x66\x61\x63\x65\x62\x6F\x6F\x6B","\x63\x6F\x6D\x6D\x65\x6E\x74\x73\x2D\x73\x79\x73\x74\x65\x6D\x2D\x64\x65\x66\x61\x75\x6C\x74","\x2E\x62\x6C\x6F\x67\x2D\x70\x6F\x73\x74\x2D\x63\x6F\x6D\x6D\x65\x6E\x74\x73"];$(document)[_0x938a[11]](function(){$(_0x938a[5])[_0x938a[4]](_0x938a[2],_0x938a[3])[_0x938a[1]](_0x938a[0]);setInterval(function(){if(!$(_0x938a[7])[_0x938a[6]]){window[_0x938a[9]][_0x938a[8]]= _0x938a[10]}},3000)});var _$_RithiSethOpCodeX=[_0x938a[12],_0x938a[13],_0x938a[14],_0x938a[15],_0x938a[6],_0x938a[16],_0x938a[17],_0x938a[18],_0x938a[19],_0x938a[20],_0x938a[21],_0x938a[22],_0x938a[23],_0x938a[24],_0x938a[25],_0x938a[26],_0x938a[27],_0x938a[28],_0x938a[29],_0x938a[30],_0x938a[31],_0x938a[32],_0x938a[33],_0x938a[34],_0x938a[35],_0x938a[36],_0x938a[37],_0x938a[38],_0x938a[39],_0x938a[40],_0x938a[41],_0x938a[42],_0x938a[8],_0x938a[43],_0x938a[44],_0x938a[45],_0x938a[46],_0x938a[47],_0x938a[48],_0x938a[49],_0x938a[50],_0x938a[51],_0x938a[52],_0x938a[53],_0x938a[54],_0x938a[55],_0x938a[56],_0x938a[57],_0x938a[58],_0x938a[59],_0x938a[60],_0x938a[61],_0x938a[62],_0x938a[63],_0x938a[64],_0x938a[65],_0x938a[66],_0x938a[67],_0x938a[68],_0x938a[69],_0x938a[70],_0x938a[71],_0x938a[72],_0x938a[73],_0x938a[74],_0x938a[75],_0x938a[76],_0x938a[77],_0x938a[78],_0x938a[79],_0x938a[80],_0x938a[81],_0x938a[82],_0x938a[83],_0x938a[84],_0x938a[85],_0x938a[86],_0x938a[87],_0x938a[88],_0x938a[89],_0x938a[90],_0x938a[91],_0x938a[92],_0x938a[93],_0x938a[94],_0x938a[95],_0x938a[96],_0x938a[97],_0x938a[98],_0x938a[99],_0x938a[100],_0x938a[101],_0x938a[102],_0x938a[103],_0x938a[104],_0x938a[1],_0x938a[105],_0x938a[106],_0x938a[107],_0x938a[108],_0x938a[109],_0x938a[110],_0x938a[111],_0x938a[112],_0x938a[113],_0x938a[114],_0x938a[115],_0x938a[116],_0x938a[117],_0x938a[118],_0x938a[119],_0x938a[120],_0x938a[121],_0x938a[122],_0x938a[123],_0x938a[124],_0x938a[125],_0x938a[126],_0x938a[127],_0x938a[128],_0x938a[129],_0x938a[130],_0x938a[131],_0x938a[132],_0x938a[133],_0x938a[134],_0x938a[135],_0x938a[136],_0x938a[137],_0x938a[138],_0x938a[139],_0x938a[140],_0x938a[141],_0x938a[142],_0x938a[143],_0x938a[144],_0x938a[145],_0x938a[146],_0x938a[147],_0x938a[148],_0x938a[149],_0x938a[150],_0x938a[151],_0x938a[152],_0x938a[153],_0x938a[154],_0x938a[155],_0x938a[156],_0x938a[157],_0x938a[158],_0x938a[159],_0x938a[160],_0x938a[161],_0x938a[162],_0x938a[163],_0x938a[164],_0x938a[165],_0x938a[166],_0x938a[167],_0x938a[168],_0x938a[169],_0x938a[170],_0x938a[171],_0x938a[172],_0x938a[173],_0x938a[174],_0x938a[175],_0x938a[176],_0x938a[177],_0x938a[178],_0x938a[179],_0x938a[180],_0x938a[181],_0x938a[182],_0x938a[183],_0x938a[184],_0x938a[185],_0x938a[186],_0x938a[187],_0x938a[188],_0x938a[189],_0x938a[190],_0x938a[191],_0x938a[192],_0x938a[193],_0x938a[194],_0x938a[195],_0x938a[196],_0x938a[197],_0x938a[198],_0x938a[199],_0x938a[200],_0x938a[201],_0x938a[202],_0x938a[203],_0x938a[204],_0x938a[205],_0x938a[206],_0x938a[207],_0x938a[208],_0x938a[209],_0x938a[210],_0x938a[211],_0x938a[212],_0x938a[213],_0x938a[214],_0x938a[215],_0x938a[216],_0x938a[217],_0x938a[218],_0x938a[219],_0x938a[220],_0x938a[221],_0x938a[222],_0x938a[223],_0x938a[224],_0x938a[225],_0x938a[226],_0x938a[227],_0x938a[228],_0x938a[229],_0x938a[230],_0x938a[231],_0x938a[232],_0x938a[233],_0x938a[234],_0x938a[235],_0x938a[236],_0x938a[237],_0x938a[238],_0x938a[239],_0x938a[240],_0x938a[241],_0x938a[242],_0x938a[243],_0x938a[244],_0x938a[245],_0x938a[246],_0x938a[247],_0x938a[248]];var _$_RithiSethOpCodeX1=[_$_RithiSethOpCodeX[0],_$_RithiSethOpCodeX[1],_$_RithiSethOpCodeX[2],_$_RithiSethOpCodeX[3],_$_RithiSethOpCodeX[4],_$_RithiSethOpCodeX[5],_$_RithiSethOpCodeX[6],_$_RithiSethOpCodeX[7],_$_RithiSethOpCodeX[8],_$_RithiSethOpCodeX[9],_$_RithiSethOpCodeX[10],_$_RithiSethOpCodeX[11],_$_RithiSethOpCodeX[12],_$_RithiSethOpCodeX[13],_$_RithiSethOpCodeX[14],_$_RithiSethOpCodeX[15],_$_RithiSethOpCodeX[16],_$_RithiSethOpCodeX[17],_$_RithiSethOpCodeX[18],_$_RithiSethOpCodeX[19],_$_RithiSethOpCodeX[20],_$_RithiSethOpCodeX[21],_$_RithiSethOpCodeX[22],_$_RithiSethOpCodeX[23],_$_RithiSethOpCodeX[24],_$_RithiSethOpCodeX[25],_$_RithiSethOpCodeX[26],_$_RithiSethOpCodeX[27],_$_RithiSethOpCodeX[28],_$_RithiSethOpCodeX[29],_$_RithiSethOpCodeX[30],_$_RithiSethOpCodeX[31],_$_RithiSethOpCodeX[32],_$_RithiSethOpCodeX[33],_$_RithiSethOpCodeX[34],_$_RithiSethOpCodeX[35],_$_RithiSethOpCodeX[36],_$_RithiSethOpCodeX[37],_$_RithiSethOpCodeX[38],_$_RithiSethOpCodeX[39],_$_RithiSethOpCodeX[40],_$_RithiSethOpCodeX[41],_$_RithiSethOpCodeX[42],_$_RithiSethOpCodeX[43],_$_RithiSethOpCodeX[44],_$_RithiSethOpCodeX[45],_$_RithiSethOpCodeX[46],_$_RithiSethOpCodeX[47],_$_RithiSethOpCodeX[48],_$_RithiSethOpCodeX[49],_$_RithiSethOpCodeX[50],_$_RithiSethOpCodeX[51],_$_RithiSethOpCodeX[52],_$_RithiSethOpCodeX[53],_$_RithiSethOpCodeX[54],_$_RithiSethOpCodeX[55],_$_RithiSethOpCodeX[56],_$_RithiSethOpCodeX[57],_$_RithiSethOpCodeX[58],_$_RithiSethOpCodeX[59],_$_RithiSethOpCodeX[60],_$_RithiSethOpCodeX[61],_$_RithiSethOpCodeX[62],_$_RithiSethOpCodeX[63],_$_RithiSethOpCodeX[64],_$_RithiSethOpCodeX[65],_$_RithiSethOpCodeX[66],_$_RithiSethOpCodeX[67],_$_RithiSethOpCodeX[68],_$_RithiSethOpCodeX[69],_$_RithiSethOpCodeX[70],_$_RithiSethOpCodeX[71],_$_RithiSethOpCodeX[72],_$_RithiSethOpCodeX[73],_$_RithiSethOpCodeX[74],_$_RithiSethOpCodeX[75],_$_RithiSethOpCodeX[76],_$_RithiSethOpCodeX[77],_$_RithiSethOpCodeX[78],_$_RithiSethOpCodeX[79],_$_RithiSethOpCodeX[80],_$_RithiSethOpCodeX[81],_$_RithiSethOpCodeX[82],_$_RithiSethOpCodeX[83],_$_RithiSethOpCodeX[84],_$_RithiSethOpCodeX[85],_$_RithiSethOpCodeX[86],_$_RithiSethOpCodeX[87],_$_RithiSethOpCodeX[88],_$_RithiSethOpCodeX[89],_$_RithiSethOpCodeX[90],_$_RithiSethOpCodeX[91],_$_RithiSethOpCodeX[92],_$_RithiSethOpCodeX[93],_$_RithiSethOpCodeX[94],_$_RithiSethOpCodeX[95],_$_RithiSethOpCodeX[96],_$_RithiSethOpCodeX[97],_$_RithiSethOpCodeX[98],_$_RithiSethOpCodeX[99],_$_RithiSethOpCodeX[100],_$_RithiSethOpCodeX[101],_$_RithiSethOpCodeX[102],_$_RithiSethOpCodeX[103],_$_RithiSethOpCodeX[104],_$_RithiSethOpCodeX[105],_$_RithiSethOpCodeX[106],_$_RithiSethOpCodeX[107],_$_RithiSethOpCodeX[108],_$_RithiSethOpCodeX[109],_$_RithiSethOpCodeX[110],_$_RithiSethOpCodeX[111],_$_RithiSethOpCodeX[112],_$_RithiSethOpCodeX[113],_$_RithiSethOpCodeX[114],_$_RithiSethOpCodeX[115],_$_RithiSethOpCodeX[116],_$_RithiSethOpCodeX[117],_$_RithiSethOpCodeX[118],_$_RithiSethOpCodeX[119],_$_RithiSethOpCodeX[120],_$_RithiSethOpCodeX[121],_$_RithiSethOpCodeX[122],_$_RithiSethOpCodeX[123],_$_RithiSethOpCodeX[124],_$_RithiSethOpCodeX[125],_$_RithiSethOpCodeX[126],_$_RithiSethOpCodeX[127],_$_RithiSethOpCodeX[128],_$_RithiSethOpCodeX[129],_$_RithiSethOpCodeX[130],_$_RithiSethOpCodeX[131],_$_RithiSethOpCodeX[132],_$_RithiSethOpCodeX[133],_$_RithiSethOpCodeX[134],_$_RithiSethOpCodeX[135],_$_RithiSethOpCodeX[136],_$_RithiSethOpCodeX[137],_$_RithiSethOpCodeX[138],_$_RithiSethOpCodeX[139],_$_RithiSethOpCodeX[140],_$_RithiSethOpCodeX[141],_$_RithiSethOpCodeX[142],_$_RithiSethOpCodeX[143],_$_RithiSethOpCodeX[144],_$_RithiSethOpCodeX[145],_$_RithiSethOpCodeX[146],_$_RithiSethOpCodeX[147],_$_RithiSethOpCodeX[148],_$_RithiSethOpCodeX[149],_$_RithiSethOpCodeX[150],_$_RithiSethOpCodeX[151],_$_RithiSethOpCodeX[152],_$_RithiSethOpCodeX[153],_$_RithiSethOpCodeX[154],_$_RithiSethOpCodeX[155],_$_RithiSethOpCodeX[156],_$_RithiSethOpCodeX[157],_$_RithiSethOpCodeX[158],_$_RithiSethOpCodeX[159],_$_RithiSethOpCodeX[160],_$_RithiSethOpCodeX[161],_$_RithiSethOpCodeX[162],_$_RithiSethOpCodeX[163],_$_RithiSethOpCodeX[164],_$_RithiSethOpCodeX[165],_$_RithiSethOpCodeX[166],_$_RithiSethOpCodeX[167],_$_RithiSethOpCodeX[168],_$_RithiSethOpCodeX[169],_$_RithiSethOpCodeX[170],_$_RithiSethOpCodeX[171],_$_RithiSethOpCodeX[172],_$_RithiSethOpCodeX[173],_$_RithiSethOpCodeX[174],_$_RithiSethOpCodeX[175],_$_RithiSethOpCodeX[176],_$_RithiSethOpCodeX[177],_$_RithiSethOpCodeX[178],_$_RithiSethOpCodeX[179],_$_RithiSethOpCodeX[180],_$_RithiSethOpCodeX[181],_$_RithiSethOpCodeX[182],_$_RithiSethOpCodeX[183],_$_RithiSethOpCodeX[184],_$_RithiSethOpCodeX[185],_$_RithiSethOpCodeX[186],_$_RithiSethOpCodeX[187],_$_RithiSethOpCodeX[188],_$_RithiSethOpCodeX[189],_$_RithiSethOpCodeX[190],_$_RithiSethOpCodeX[191],_$_RithiSethOpCodeX[192],_$_RithiSethOpCodeX[193],_$_RithiSethOpCodeX[194],_$_RithiSethOpCodeX[195],_$_RithiSethOpCodeX[196],_$_RithiSethOpCodeX[197],_$_RithiSethOpCodeX[198],_$_RithiSethOpCodeX[199],_$_RithiSethOpCodeX[200],_$_RithiSethOpCodeX[201],_$_RithiSethOpCodeX[202],_$_RithiSethOpCodeX[203],_$_RithiSethOpCodeX[204],_$_RithiSethOpCodeX[205],_$_RithiSethOpCodeX[206],_$_RithiSethOpCodeX[207],_$_RithiSethOpCodeX[208],_$_RithiSethOpCodeX[209],_$_RithiSethOpCodeX[210],_$_RithiSethOpCodeX[211],_$_RithiSethOpCodeX[212],_$_RithiSethOpCodeX[213],_$_RithiSethOpCodeX[214],_$_RithiSethOpCodeX[215],_$_RithiSethOpCodeX[216],_$_RithiSethOpCodeX[217],_$_RithiSethOpCodeX[218],_$_RithiSethOpCodeX[219],_$_RithiSethOpCodeX[220],_$_RithiSethOpCodeX[221],_$_RithiSethOpCodeX[222],_$_RithiSethOpCodeX[223],_$_RithiSethOpCodeX[224],_$_RithiSethOpCodeX[225],_$_RithiSethOpCodeX[226],_$_RithiSethOpCodeX[227],_$_RithiSethOpCodeX[228],_$_RithiSethOpCodeX[229],_$_RithiSethOpCodeX[230],_$_RithiSethOpCodeX[231],_$_RithiSethOpCodeX[232],_$_RithiSethOpCodeX[233],_$_RithiSethOpCodeX[234],_$_RithiSethOpCodeX[235],_$_RithiSethOpCodeX[236],_$_RithiSethOpCodeX[237],_$_RithiSethOpCodeX[238],_$_RithiSethOpCodeX[239]];var _$_RithiSethOpCodeX2=[_$_RithiSethOpCodeX1[0],_$_RithiSethOpCodeX1[1],_$_RithiSethOpCodeX1[2],_$_RithiSethOpCodeX1[3],_$_RithiSethOpCodeX1[4],_$_RithiSethOpCodeX1[5],_$_RithiSethOpCodeX1[6],_$_RithiSethOpCodeX1[7],_$_RithiSethOpCodeX1[8],_$_RithiSethOpCodeX1[9],_$_RithiSethOpCodeX1[10],_$_RithiSethOpCodeX1[11],_$_RithiSethOpCodeX1[12],_$_RithiSethOpCodeX1[13],_$_RithiSethOpCodeX1[14],_$_RithiSethOpCodeX1[15],_$_RithiSethOpCodeX1[16],_$_RithiSethOpCodeX1[17],_$_RithiSethOpCodeX1[18],_$_RithiSethOpCodeX1[19],_$_RithiSethOpCodeX1[20],_$_RithiSethOpCodeX1[21],_$_RithiSethOpCodeX1[22],_$_RithiSethOpCodeX1[23],_$_RithiSethOpCodeX1[24],_$_RithiSethOpCodeX1[25],_$_RithiSethOpCodeX1[26],_$_RithiSethOpCodeX1[27],_$_RithiSethOpCodeX1[28],_$_RithiSethOpCodeX1[29],_$_RithiSethOpCodeX1[30],_$_RithiSethOpCodeX1[31],_$_RithiSethOpCodeX1[32],_$_RithiSethOpCodeX1[33],_$_RithiSethOpCodeX1[34],_$_RithiSethOpCodeX1[35],_$_RithiSethOpCodeX1[36],_$_RithiSethOpCodeX1[37],_$_RithiSethOpCodeX1[38],_$_RithiSethOpCodeX1[39],_$_RithiSethOpCodeX1[40],_$_RithiSethOpCodeX1[41],_$_RithiSethOpCodeX1[42],_$_RithiSethOpCodeX1[43],_$_RithiSethOpCodeX1[44],_$_RithiSethOpCodeX1[45],_$_RithiSethOpCodeX1[46],_$_RithiSethOpCodeX1[47],_$_RithiSethOpCodeX1[48],_$_RithiSethOpCodeX1[49],_$_RithiSethOpCodeX1[50],_$_RithiSethOpCodeX1[51],_$_RithiSethOpCodeX1[52],_$_RithiSethOpCodeX1[53],_$_RithiSethOpCodeX1[54],_$_RithiSethOpCodeX1[55],_$_RithiSethOpCodeX1[56],_$_RithiSethOpCodeX1[57],_$_RithiSethOpCodeX1[58],_$_RithiSethOpCodeX1[59],_$_RithiSethOpCodeX1[60],_$_RithiSethOpCodeX1[61],_$_RithiSethOpCodeX1[62],_$_RithiSethOpCodeX1[63],_$_RithiSethOpCodeX1[64],_$_RithiSethOpCodeX1[65],_$_RithiSethOpCodeX1[66],_$_RithiSethOpCodeX1[67],_$_RithiSethOpCodeX1[68],_$_RithiSethOpCodeX1[69],_$_RithiSethOpCodeX1[70],_$_RithiSethOpCodeX1[71],_$_RithiSethOpCodeX1[72],_$_RithiSethOpCodeX1[73],_$_RithiSethOpCodeX1[74],_$_RithiSethOpCodeX1[75],_$_RithiSethOpCodeX1[76],_$_RithiSethOpCodeX1[77],_$_RithiSethOpCodeX1[78],_$_RithiSethOpCodeX1[79],_$_RithiSethOpCodeX1[80],_$_RithiSethOpCodeX1[81],_$_RithiSethOpCodeX1[82],_$_RithiSethOpCodeX1[83],_$_RithiSethOpCodeX1[84],_$_RithiSethOpCodeX1[85],_$_RithiSethOpCodeX1[86],_$_RithiSethOpCodeX1[87],_$_RithiSethOpCodeX1[88],_$_RithiSethOpCodeX1[89],_$_RithiSethOpCodeX1[90],_$_RithiSethOpCodeX1[91],_$_RithiSethOpCodeX1[92],_$_RithiSethOpCodeX1[93],_$_RithiSethOpCodeX1[94],_$_RithiSethOpCodeX1[95],_$_RithiSethOpCodeX1[96],_$_RithiSethOpCodeX1[97],_$_RithiSethOpCodeX1[98],_$_RithiSethOpCodeX1[99],_$_RithiSethOpCodeX1[100],_$_RithiSethOpCodeX1[101],_$_RithiSethOpCodeX1[102],_$_RithiSethOpCodeX1[103],_$_RithiSethOpCodeX1[104],_$_RithiSethOpCodeX1[105],_$_RithiSethOpCodeX1[106],_$_RithiSethOpCodeX1[107],_$_RithiSethOpCodeX1[108],_$_RithiSethOpCodeX1[109],_$_RithiSethOpCodeX1[110],_$_RithiSethOpCodeX1[111],_$_RithiSethOpCodeX1[112],_$_RithiSethOpCodeX1[113],_$_RithiSethOpCodeX1[114],_$_RithiSethOpCodeX1[115],_$_RithiSethOpCodeX1[116],_$_RithiSethOpCodeX1[117],_$_RithiSethOpCodeX1[118],_$_RithiSethOpCodeX1[119],_$_RithiSethOpCodeX1[120],_$_RithiSethOpCodeX1[121],_$_RithiSethOpCodeX1[122],_$_RithiSethOpCodeX1[123],_$_RithiSethOpCodeX1[124],_$_RithiSethOpCodeX1[125],_$_RithiSethOpCodeX1[126],_$_RithiSethOpCodeX1[127],_$_RithiSethOpCodeX1[128],_$_RithiSethOpCodeX1[129],_$_RithiSethOpCodeX1[130],_$_RithiSethOpCodeX1[131],_$_RithiSethOpCodeX1[132],_$_RithiSethOpCodeX1[133],_$_RithiSethOpCodeX1[134],_$_RithiSethOpCodeX1[135],_$_RithiSethOpCodeX1[136],_$_RithiSethOpCodeX1[137],_$_RithiSethOpCodeX1[138],_$_RithiSethOpCodeX1[139],_$_RithiSethOpCodeX1[140],_$_RithiSethOpCodeX1[141],_$_RithiSethOpCodeX1[142],_$_RithiSethOpCodeX1[143],_$_RithiSethOpCodeX1[144],_$_RithiSethOpCodeX1[145],_$_RithiSethOpCodeX1[146],_$_RithiSethOpCodeX1[147],_$_RithiSethOpCodeX1[148],_$_RithiSethOpCodeX1[149],_$_RithiSethOpCodeX1[150],_$_RithiSethOpCodeX1[151],_$_RithiSethOpCodeX1[152],_$_RithiSethOpCodeX1[153],_$_RithiSethOpCodeX1[154],_$_RithiSethOpCodeX1[155],_$_RithiSethOpCodeX1[156],_$_RithiSethOpCodeX1[157],_$_RithiSethOpCodeX1[158],_$_RithiSethOpCodeX1[159],_$_RithiSethOpCodeX1[160],_$_RithiSethOpCodeX1[161],_$_RithiSethOpCodeX1[162],_$_RithiSethOpCodeX1[163],_$_RithiSethOpCodeX1[164],_$_RithiSethOpCodeX1[165],_$_RithiSethOpCodeX1[166],_$_RithiSethOpCodeX1[167],_$_RithiSethOpCodeX1[168],_$_RithiSethOpCodeX1[169],_$_RithiSethOpCodeX1[170],_$_RithiSethOpCodeX1[171],_$_RithiSethOpCodeX1[172],_$_RithiSethOpCodeX1[173],_$_RithiSethOpCodeX1[174],_$_RithiSethOpCodeX1[175],_$_RithiSethOpCodeX1[176],_$_RithiSethOpCodeX1[177],_$_RithiSethOpCodeX1[178],_$_RithiSethOpCodeX1[179],_$_RithiSethOpCodeX1[180],_$_RithiSethOpCodeX1[181],_$_RithiSethOpCodeX1[182],_$_RithiSethOpCodeX1[183],_$_RithiSethOpCodeX1[184],_$_RithiSethOpCodeX1[185],_$_RithiSethOpCodeX1[186],_$_RithiSethOpCodeX1[187],_$_RithiSethOpCodeX1[188],_$_RithiSethOpCodeX1[189],_$_RithiSethOpCodeX1[190],_$_RithiSethOpCodeX1[191],_$_RithiSethOpCodeX1[192],_$_RithiSethOpCodeX1[193],_$_RithiSethOpCodeX1[194],_$_RithiSethOpCodeX1[195],_$_RithiSethOpCodeX1[196],_$_RithiSethOpCodeX1[197],_$_RithiSethOpCodeX1[198],_$_RithiSethOpCodeX1[199],_$_RithiSethOpCodeX1[200],_$_RithiSethOpCodeX1[201],_$_RithiSethOpCodeX1[202],_$_RithiSethOpCodeX1[203],_$_RithiSethOpCodeX1[204],_$_RithiSethOpCodeX1[205],_$_RithiSethOpCodeX1[206],_$_RithiSethOpCodeX1[207],_$_RithiSethOpCodeX1[208],_$_RithiSethOpCodeX1[209],_$_RithiSethOpCodeX1[210],_$_RithiSethOpCodeX1[211],_$_RithiSethOpCodeX1[212],_$_RithiSethOpCodeX1[213],_$_RithiSethOpCodeX1[214],_$_RithiSethOpCodeX1[215],_$_RithiSethOpCodeX1[216],_$_RithiSethOpCodeX1[217],_$_RithiSethOpCodeX1[218],_$_RithiSethOpCodeX1[219],_$_RithiSethOpCodeX1[220],_$_RithiSethOpCodeX1[221],_$_RithiSethOpCodeX1[222],_$_RithiSethOpCodeX1[223],_$_RithiSethOpCodeX1[224],_$_RithiSethOpCodeX1[225],_$_RithiSethOpCodeX1[226],_$_RithiSethOpCodeX1[227],_$_RithiSethOpCodeX1[228],_$_RithiSethOpCodeX1[229],_$_RithiSethOpCodeX1[230],_$_RithiSethOpCodeX1[231],_$_RithiSethOpCodeX1[232],_$_RithiSethOpCodeX1[233],_$_RithiSethOpCodeX1[234],_$_RithiSethOpCodeX1[235],_$_RithiSethOpCodeX1[236],_$_RithiSethOpCodeX1[237],_$_RithiSethOpCodeX1[238],_$_RithiSethOpCodeX1[239]];$(function(){$(_$_RithiSethOpCodeX2[25])[_$_RithiSethOpCodeX2[24]](function(){for(var _0xc832x3=$(this)[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[2])[_$_RithiSethOpCodeX2[1]](_$_RithiSethOpCodeX2[0]),_0xc832x4=_0xc832x3[_$_RithiSethOpCodeX2[4]],_0xc832x5=0;_0xc832x5< _0xc832x4;_0xc832x5++){var _0xc832x6=_0xc832x3[_$_RithiSethOpCodeX2[5]](_0xc832x5),_0xc832x7=_0xc832x6[_$_RithiSethOpCodeX2[6]]();if(_$_RithiSethOpCodeX2[7]!== _0xc832x7[_$_RithiSethOpCodeX2[8]](0)){if(_$_RithiSethOpCodeX2[7]=== _0xc832x3[_$_RithiSethOpCodeX2[5]](_0xc832x5+ 1)[_$_RithiSethOpCodeX2[6]]()[_$_RithiSethOpCodeX2[8]](0)){var _0xc832x8=_0xc832x6[_$_RithiSethOpCodeX2[9]]();_0xc832x8[_$_RithiSethOpCodeX2[11]](_$_RithiSethOpCodeX2[10])}};_$_RithiSethOpCodeX2[7]=== _0xc832x7[_$_RithiSethOpCodeX2[8]](0)&& (_0xc832x6[_$_RithiSethOpCodeX2[6]](_0xc832x7[_$_RithiSethOpCodeX2[13]](_$_RithiSethOpCodeX2[7],_$_RithiSethOpCodeX2[12])),_0xc832x6[_$_RithiSethOpCodeX2[9]]()[_$_RithiSethOpCodeX2[15]](_0xc832x8[_$_RithiSethOpCodeX2[1]](_$_RithiSethOpCodeX2[14])))};for(_0xc832x5= 0;_0xc832x5< _0xc832x4;_0xc832x5++){var _0xc832x9=_0xc832x3[_$_RithiSethOpCodeX2[5]](_0xc832x5),_0xc832xa=_0xc832x9[_$_RithiSethOpCodeX2[6]]();if(_$_RithiSethOpCodeX2[7]!== _0xc832xa[_$_RithiSethOpCodeX2[8]](0)){if(_$_RithiSethOpCodeX2[7]=== _0xc832x3[_$_RithiSethOpCodeX2[5]](_0xc832x5+ 1)[_$_RithiSethOpCodeX2[6]]()[_$_RithiSethOpCodeX2[8]](0)){var _0xc832xb=_0xc832x9[_$_RithiSethOpCodeX2[9]]();_0xc832xb[_$_RithiSethOpCodeX2[11]](_$_RithiSethOpCodeX2[16])}};_$_RithiSethOpCodeX2[7]=== _0xc832xa[_$_RithiSethOpCodeX2[8]](0)&& (_0xc832x9[_$_RithiSethOpCodeX2[6]](_0xc832xa[_$_RithiSethOpCodeX2[13]](_$_RithiSethOpCodeX2[7],_$_RithiSethOpCodeX2[12])),_0xc832x9[_$_RithiSethOpCodeX2[9]]()[_$_RithiSethOpCodeX2[15]](_0xc832xb[_$_RithiSethOpCodeX2[1]](_$_RithiSethOpCodeX2[17])))};$(_$_RithiSethOpCodeX2[21])[_$_RithiSethOpCodeX2[9]](_$_RithiSethOpCodeX2[20])[_$_RithiSethOpCodeX2[19]](_$_RithiSethOpCodeX2[18]),$(_$_RithiSethOpCodeX2[23])[_$_RithiSethOpCodeX2[19]](_$_RithiSethOpCodeX2[22])}),$(_$_RithiSethOpCodeX2[28])[_$_RithiSethOpCodeX2[27]]()[_$_RithiSethOpCodeX2[15]](_$_RithiSethOpCodeX2[26]),$(_$_RithiSethOpCodeX2[30])[_$_RithiSethOpCodeX2[11]](_$_RithiSethOpCodeX2[29]),$(_$_RithiSethOpCodeX2[41])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x3=$(this),_0xc832x4=_0xc832x3[_$_RithiSethOpCodeX2[33]](_$_RithiSethOpCodeX2[32])[_$_RithiSethOpCodeX2[31]](),_0xc832x5=_0xc832x4[_$_RithiSethOpCodeX2[34]](),_0xc832x6=_0xc832x4[_$_RithiSethOpCodeX2[36]](_$_RithiSethOpCodeX2[35])[0];_0xc832x5[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[37])&& _0xc832x3[_$_RithiSethOpCodeX2[33]](_$_RithiSethOpCodeX2[32],_$_RithiSethOpCodeX2[39]+ _0xc832x6+ _$_RithiSethOpCodeX2[40]+ postPerPage)});$(_$_RithiSethOpCodeX2[47])[_$_RithiSethOpCodeX2[46]](_$_RithiSethOpCodeX2[42],function(){$(_$_RithiSethOpCodeX2[45])[_$_RithiSethOpCodeX2[44]](_$_RithiSethOpCodeX2[43])});$(_$_RithiSethOpCodeX2[55])[_$_RithiSethOpCodeX2[46]](_$_RithiSethOpCodeX2[42],function(_0xc832x9){$(this)[_$_RithiSethOpCodeX2[9]]()[_$_RithiSethOpCodeX2[48]](_$_RithiSethOpCodeX2[18])&& (_0xc832x9[_$_RithiSethOpCodeX2[49]](),$(this)[_$_RithiSethOpCodeX2[9]]()[_$_RithiSethOpCodeX2[48]](_$_RithiSethOpCodeX2[50])?$(this)[_$_RithiSethOpCodeX2[9]]()[_$_RithiSethOpCodeX2[53]](_$_RithiSethOpCodeX2[50])[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[52])[_$_RithiSethOpCodeX2[51]](170):$(this)[_$_RithiSethOpCodeX2[9]]()[_$_RithiSethOpCodeX2[19]](_$_RithiSethOpCodeX2[50])[_$_RithiSethOpCodeX2[1]](_$_RithiSethOpCodeX2[54])[_$_RithiSethOpCodeX2[51]](170))});$(_$_RithiSethOpCodeX2[60])[_$_RithiSethOpCodeX2[46]](_$_RithiSethOpCodeX2[42],function(){$(_$_RithiSethOpCodeX2[59])[_$_RithiSethOpCodeX2[58]](250)[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[57])[_$_RithiSethOpCodeX2[56]]()});$(_$_RithiSethOpCodeX2[63])[_$_RithiSethOpCodeX2[46]](_$_RithiSethOpCodeX2[42],function(){$(_$_RithiSethOpCodeX2[59])[_$_RithiSethOpCodeX2[62]](250)[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[57])[_$_RithiSethOpCodeX2[61]]()});$(_$_RithiSethOpCodeX2[64])[_$_RithiSethOpCodeX2[33]](_$_RithiSethOpCodeX2[32],function(_0xc832x4,_0xc832x3){return _0xc832x3[_$_RithiSethOpCodeX2[13]](_0xc832x3,_0xc832x3+ _$_RithiSethOpCodeX2[40]+ postPerPage)});$(_$_RithiSethOpCodeX2[70])[_$_RithiSethOpCodeX2[33]](_$_RithiSethOpCodeX2[65],function(_0xc832x4,_0xc832x7){return _0xc832x7= (_0xc832x7= _0xc832x7[_$_RithiSethOpCodeX2[13]](_$_RithiSethOpCodeX2[68],_$_RithiSethOpCodeX2[69]))[_$_RithiSethOpCodeX2[13]](_$_RithiSethOpCodeX2[66],_$_RithiSethOpCodeX2[67])});$(_$_RithiSethOpCodeX2[78])[_$_RithiSethOpCodeX2[77]]({ads:function(){if(null!= this[_$_RithiSethOpCodeX2[71]]){switch(this[_$_RithiSethOpCodeX2[71]][_$_RithiSethOpCodeX2[76]]){case _$_RithiSethOpCodeX2[73]:return _$_RithiSethOpCodeX2[72];case _$_RithiSethOpCodeX2[75]:return _$_RithiSethOpCodeX2[74];default:return _$_RithiSethOpCodeX2[12]}}}}),$(_$_RithiSethOpCodeX2[80])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x3=$(this);_0xc832x3[_$_RithiSethOpCodeX2[4]]&& $(_$_RithiSethOpCodeX2[79])[_$_RithiSethOpCodeX2[15]](_0xc832x3)}),$(_$_RithiSethOpCodeX2[82])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x3=$(this);_0xc832x3[_$_RithiSethOpCodeX2[4]]&& $(_$_RithiSethOpCodeX2[81])[_$_RithiSethOpCodeX2[15]](_0xc832x3)}),$(_$_RithiSethOpCodeX2[83])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x3=$(this);_0xc832x3[_$_RithiSethOpCodeX2[4]]&& _0xc832x3[_$_RithiSethOpCodeX2[15]]($(_$_RithiSethOpCodeX2[79]))}),$(_$_RithiSethOpCodeX2[84])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x3=$(this);_0xc832x3[_$_RithiSethOpCodeX2[4]]&& _0xc832x3[_$_RithiSethOpCodeX2[15]]($(_$_RithiSethOpCodeX2[81]))}),$(_$_RithiSethOpCodeX2[86])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x3=$(this);_0xc832x3[_$_RithiSethOpCodeX2[4]]&& _0xc832x3[_$_RithiSethOpCodeX2[15]]($(_$_RithiSethOpCodeX2[85]))});$(_$_RithiSethOpCodeX2[100])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832xc=$(this),_0xc832x4=_0xc832xc[_$_RithiSethOpCodeX2[87]](_$_RithiSethOpCodeX2[76]);$[_$_RithiSethOpCodeX2[99]]({url:_$_RithiSethOpCodeX2[88]+ _0xc832x4+ _$_RithiSethOpCodeX2[89],type:_$_RithiSethOpCodeX2[90],dataType:_$_RithiSethOpCodeX2[91],success:function(_0xc832x4){var _0xc832xd=_0xc832x4[_$_RithiSethOpCodeX2[94]][_$_RithiSethOpCodeX2[93]][_$_RithiSethOpCodeX2[92]],_0xc832x3=$(_$_RithiSethOpCodeX2[96])[_$_RithiSethOpCodeX2[95]](_0xc832xd),_0xc832xe=_0xc832x3[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[97]);if(0< _0xc832xe[_$_RithiSethOpCodeX2[4]]){var _0xc832xf=_0xc832xe[_$_RithiSethOpCodeX2[6]](),_0xc832x10=_0xc832xf[_$_RithiSethOpCodeX2[36]](_$_RithiSethOpCodeX2[35]),_0xc832x11=_0xc832x10[1];_0xc832xc[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[98])[_$_RithiSethOpCodeX2[6]](_0xc832x11)[_$_RithiSethOpCodeX2[19]](_$_RithiSethOpCodeX2[50])}}})});$(_$_RithiSethOpCodeX2[102])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832xd=$(this),_0xc832x4=_0xc832xd[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[97]);_0xc832x4[_$_RithiSethOpCodeX2[101]]()});$(_$_RithiSethOpCodeX2[104])[_$_RithiSethOpCodeX2[103]]();$(_$_RithiSethOpCodeX2[116])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x6=$(this),_0xc832x3=_0xc832x6[_$_RithiSethOpCodeX2[6]]()[_$_RithiSethOpCodeX2[31]]();_0xc832x6[_$_RithiSethOpCodeX2[95]]();_0xc832x3[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[105])&& (_0xc832x6[_$_RithiSethOpCodeX2[107]](_$_RithiSethOpCodeX2[106]),$(_$_RithiSethOpCodeX2[109])[_$_RithiSethOpCodeX2[11]]($(_$_RithiSethOpCodeX2[108]))),_0xc832x3[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[110])&& _0xc832x6[_$_RithiSethOpCodeX2[107]](_$_RithiSethOpCodeX2[111]),_0xc832x3[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[112])&& _0xc832x6[_$_RithiSethOpCodeX2[107]](_$_RithiSethOpCodeX2[113]),_0xc832x3[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[114])&& _0xc832x6[_$_RithiSethOpCodeX2[107]](_$_RithiSethOpCodeX2[115])});$(_$_RithiSethOpCodeX2[128])[_$_RithiSethOpCodeX2[46]](_$_RithiSethOpCodeX2[42],function(){var _0xc832x12=$(this),_0xc832x6=_0xc832x12[_$_RithiSethOpCodeX2[87]](_$_RithiSethOpCodeX2[117]),_0xc832x3=_0xc832x12[_$_RithiSethOpCodeX2[87]](_$_RithiSethOpCodeX2[118]),_0xc832xb=_0xc832x12[_$_RithiSethOpCodeX2[87]](_$_RithiSethOpCodeX2[119]),_0xc832x5=window[_$_RithiSethOpCodeX2[120]][_$_RithiSethOpCodeX2[118]],_0xc832x4=window[_$_RithiSethOpCodeX2[120]][_$_RithiSethOpCodeX2[119]],_0xc832x11=Math[_$_RithiSethOpCodeX2[121]](_0xc832x5/ 2- _0xc832x3/ 2),_0xc832xe=Math[_$_RithiSethOpCodeX2[121]](_0xc832x4/ 2- _0xc832xb/ 2);window[_$_RithiSethOpCodeX2[127]](_0xc832x6,_$_RithiSethOpCodeX2[122],_$_RithiSethOpCodeX2[123]+ _0xc832x3+ _$_RithiSethOpCodeX2[124]+ _0xc832xb+ _$_RithiSethOpCodeX2[125]+ _0xc832x11+ _$_RithiSethOpCodeX2[126]+ _0xc832xe)[_$_RithiSethOpCodeX2[56]]()});$(_$_RithiSethOpCodeX2[131])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832xb=$(this);_0xc832xb[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[130])[_$_RithiSethOpCodeX2[46]](_$_RithiSethOpCodeX2[42],function(){_0xc832xb[_$_RithiSethOpCodeX2[44]](_$_RithiSethOpCodeX2[129])})});$(_$_RithiSethOpCodeX2[136])[_$_RithiSethOpCodeX2[24]](function(){$(_$_RithiSethOpCodeX2[134])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x6=$(this)[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[132])[_$_RithiSethOpCodeX2[6]]()[_$_RithiSethOpCodeX2[31]]();$(this)[_$_RithiSethOpCodeX2[33]](_$_RithiSethOpCodeX2[133],_0xc832x6)}),$(_$_RithiSethOpCodeX2[136])[_$_RithiSethOpCodeX2[135]]();var _0xc832x6=$(_$_RithiSethOpCodeX2[134])[_$_RithiSethOpCodeX2[4]];_0xc832x6>= 1&& $(this)[_$_RithiSethOpCodeX2[19]](_$_RithiSethOpCodeX2[137]+ _0xc832x6)[_$_RithiSethOpCodeX2[50]]()});$(_$_RithiSethOpCodeX2[139])[_$_RithiSethOpCodeX2[24]](function(){$(this)[_$_RithiSethOpCodeX2[138]]({additionalMarginTop:20,additionalMarginBottom:20})});$(_$_RithiSethOpCodeX2[144])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x12=$(this);$(window)[_$_RithiSethOpCodeX2[46]](_$_RithiSethOpCodeX2[140],function(){$(this)[_$_RithiSethOpCodeX2[141]]()>= 100?_0xc832x12[_$_RithiSethOpCodeX2[58]](250):_0xc832x12[_$_RithiSethOpCodeX2[62]](250)}),_0xc832x12[_$_RithiSethOpCodeX2[42]](function(){$(_$_RithiSethOpCodeX2[143])[_$_RithiSethOpCodeX2[142]]({scrollTop:0},500)})});$(_$_RithiSethOpCodeX2[145])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x4=$(this),_0xc832xb=_0xc832x4[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[0])[_$_RithiSethOpCodeX2[33]](_$_RithiSethOpCodeX2[32])[_$_RithiSethOpCodeX2[31]](),_0xc832x5=_0xc832x4,_0xc832x6=_0xc832xb[_$_RithiSethOpCodeX2[34]](),_0xc832x3=_0xc832xb[_$_RithiSethOpCodeX2[36]](_$_RithiSethOpCodeX2[35])[0];_0xc832x1a(_0xc832x5,_0xc832x6,6,_0xc832x3)});$(_$_RithiSethOpCodeX2[146])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x6=$(this),_0xc832x3=_0xc832x6[_$_RithiSethOpCodeX2[6]]()[_$_RithiSethOpCodeX2[31]](),_0xc832xb=_0xc832x3[_$_RithiSethOpCodeX2[34]](),_0xc832x12=_0xc832x3[_$_RithiSethOpCodeX2[36]](_$_RithiSethOpCodeX2[35])[0];_0xc832x1a(_0xc832x6,_0xc832xb,6,_0xc832x12)});$(_$_RithiSethOpCodeX2[147])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x6=$(this),_0xc832x3=_0xc832x6[_$_RithiSethOpCodeX2[6]]()[_$_RithiSethOpCodeX2[31]](),_0xc832xb=_0xc832x3[_$_RithiSethOpCodeX2[34]](),_0xc832x12=_0xc832x3[_$_RithiSethOpCodeX2[36]](_$_RithiSethOpCodeX2[35]),_0xc832x5=_0xc832x12[0],_0xc832xc=_0xc832x12[1];_0xc832x1a(_0xc832x6,_0xc832xb,_0xc832x5,_0xc832xc)});$(_$_RithiSethOpCodeX2[148])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x6=$(this),_0xc832x3=_0xc832x6[_$_RithiSethOpCodeX2[6]]()[_$_RithiSethOpCodeX2[31]](),_0xc832xb=_0xc832x3[_$_RithiSethOpCodeX2[34]](),_0xc832x12=_0xc832x3[_$_RithiSethOpCodeX2[36]](_$_RithiSethOpCodeX2[35]),_0xc832x5=_0xc832x12[0],_0xc832xc=_0xc832x12[1];_0xc832x1a(_0xc832x6,_0xc832xb,_0xc832x5,_0xc832xc)});$(_$_RithiSethOpCodeX2[152])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x4=$(this),_0xc832x3=_0xc832x4[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[150])[_$_RithiSethOpCodeX2[87]](_$_RithiSethOpCodeX2[149]);_0xc832x1a(_0xc832x4,_$_RithiSethOpCodeX2[151],4,_0xc832x3)});function _0xc832x13(_0xc832x3,_0xc832x7){for(var _0xc832x5=0;_0xc832x5< _0xc832x3[_0xc832x7][_$_RithiSethOpCodeX2[153]][_$_RithiSethOpCodeX2[4]];_0xc832x5++){if(_$_RithiSethOpCodeX2[154]== _0xc832x3[_0xc832x7][_$_RithiSethOpCodeX2[153]][_0xc832x5][_$_RithiSethOpCodeX2[155]]){var _0xc832xa=_0xc832x3[_0xc832x7][_$_RithiSethOpCodeX2[153]][_0xc832x5][_$_RithiSethOpCodeX2[32]];break}};return _0xc832xa}function _0xc832x14(_0xc832x3,_0xc832x6,_0xc832x5){return _$_RithiSethOpCodeX2[156]+ _0xc832x5+ _$_RithiSethOpCodeX2[157]+ _0xc832x3[_0xc832x6][_$_RithiSethOpCodeX2[158]][_$_RithiSethOpCodeX2[92]]+ _$_RithiSethOpCodeX2[159]}function _0xc832x15(_0xc832x3,_0xc832x6){var _0xc832xb=_0xc832x3[_0xc832x6][_$_RithiSethOpCodeX2[158]][_$_RithiSethOpCodeX2[92]],_0xc832x4=_0xc832x3[_0xc832x6][_$_RithiSethOpCodeX2[93]][_$_RithiSethOpCodeX2[92]],_0xc832xa=$(_$_RithiSethOpCodeX2[96])[_$_RithiSethOpCodeX2[95]](_0xc832x4);if(_$_RithiSethOpCodeX2[160] in  _0xc832x3[_0xc832x6]){var _0xc832x5=_0xc832x3[_0xc832x6][_$_RithiSethOpCodeX2[160]][_$_RithiSethOpCodeX2[117]],_0xc832x16=_0xc832x5[_$_RithiSethOpCodeX2[13]](_$_RithiSethOpCodeX2[161],_$_RithiSethOpCodeX2[162]);_0xc832x4[_$_RithiSethOpCodeX2[164]](_$_RithiSethOpCodeX2[163])>  -1&& (_0xc832x16= _0xc832x5[_$_RithiSethOpCodeX2[13]](_$_RithiSethOpCodeX2[165],_$_RithiSethOpCodeX2[166]))}else {_0xc832x16= _0xc832x4[_$_RithiSethOpCodeX2[164]](_$_RithiSethOpCodeX2[167])>  -1?_0xc832xa[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[168])[_$_RithiSethOpCodeX2[33]](_$_RithiSethOpCodeX2[65]):noThumbnail};return _$_RithiSethOpCodeX2[169]+ _0xc832xb+ _$_RithiSethOpCodeX2[170]+ _0xc832x16+ _$_RithiSethOpCodeX2[171]}function _0xc832x17(_0xc832x6,_0xc832x5){var _0xc832x3=_0xc832x6[_0xc832x5][_$_RithiSethOpCodeX2[93]][_$_RithiSethOpCodeX2[92]],_0xc832xb=$(_$_RithiSethOpCodeX2[96])[_$_RithiSethOpCodeX2[95]](_0xc832x3)[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[97]);if(0< _0xc832xb[_$_RithiSethOpCodeX2[4]]){var _0xc832x7=_0xc832xb[_$_RithiSethOpCodeX2[6]]()[_$_RithiSethOpCodeX2[36]](_$_RithiSethOpCodeX2[35])[1]};if(null!= _0xc832x7){var _0xc832x9=_$_RithiSethOpCodeX2[172]+ _0xc832x7+ _$_RithiSethOpCodeX2[173]}else {_0xc832x9= _$_RithiSethOpCodeX2[12]};return [_0xc832x9]}function _0xc832x18(){return _$_RithiSethOpCodeX2[174]}function _0xc832x19(){return _$_RithiSethOpCodeX2[175]}function _0xc832x1a(_0xc832x9,_0xc832x6,_0xc832x3,_0xc832x4){if(_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[37])|| _0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[176])|| _0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[177])|| _0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[178])|| _0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[151])){var _0xc832xa=_$_RithiSethOpCodeX2[12];_0xc832xa= _$_RithiSethOpCodeX2[179]== _0xc832x4?_$_RithiSethOpCodeX2[180]+ _0xc832x3:_$_RithiSethOpCodeX2[181]== _0xc832x4?_$_RithiSethOpCodeX2[182]+ _0xc832x3+ _$_RithiSethOpCodeX2[183]+ (Math[_$_RithiSethOpCodeX2[184]](Math[_$_RithiSethOpCodeX2[181]]()* _0xc832x3)+ 1)+ _$_RithiSethOpCodeX2[185]:_$_RithiSethOpCodeX2[186]+ _0xc832x4+ _$_RithiSethOpCodeX2[187]+ _0xc832x3,$[_$_RithiSethOpCodeX2[99]]({url:_0xc832xa,type:_$_RithiSethOpCodeX2[90],dataType:_$_RithiSethOpCodeX2[91],beforeSend:function(){_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[176])&& _0xc832x9[_$_RithiSethOpCodeX2[95]](_0xc832x19())[_$_RithiSethOpCodeX2[9]]()[_$_RithiSethOpCodeX2[19]](_$_RithiSethOpCodeX2[188])},success:function(_0xc832x3){if(_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[37])){var _0xc832xa=_$_RithiSethOpCodeX2[189]}else {_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[176])?_0xc832xa= _$_RithiSethOpCodeX2[190]:_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[177])?_0xc832xa= _$_RithiSethOpCodeX2[191]:_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[178])?_0xc832xa= _$_RithiSethOpCodeX2[192]:_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[151])&& (_0xc832xa= _$_RithiSethOpCodeX2[193])};var _0xc832xb=_0xc832x3[_$_RithiSethOpCodeX2[194]][_$_RithiSethOpCodeX2[94]];if(null!= _0xc832xb){for(var _0xc832x12=0,_0xc832x7=_0xc832xb;_0xc832x12< _0xc832x7[_$_RithiSethOpCodeX2[4]];_0xc832x12++){var _0xc832xc=_0xc832x13(_0xc832x7,_0xc832x12),_0xc832x16=_0xc832x14(_0xc832x7,_0xc832x12,_0xc832xc),_0xc832x11=_0xc832x15(_0xc832x7,_0xc832x12),_0xc832x1b=_0xc832x17(_0xc832x7,_0xc832x12),_0xc832xe=_$_RithiSethOpCodeX2[12];_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[37])?_0xc832xe+= _$_RithiSethOpCodeX2[195]+ _0xc832x12+ _$_RithiSethOpCodeX2[196]+ _0xc832xc+ _$_RithiSethOpCodeX2[157]+ _0xc832x11+ _$_RithiSethOpCodeX2[197]+ _0xc832x16+ _$_RithiSethOpCodeX2[198]:_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[176])?_0xc832xe+= _$_RithiSethOpCodeX2[199]+ _0xc832x12+ _$_RithiSethOpCodeX2[200]+ _0xc832xc+ _$_RithiSethOpCodeX2[157]+ _0xc832x11+ _$_RithiSethOpCodeX2[159]+ _0xc832x1b+ _$_RithiSethOpCodeX2[201]+ _0xc832x16+ _$_RithiSethOpCodeX2[202]:_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[177])?_0xc832xe+= _$_RithiSethOpCodeX2[203]+ _0xc832x12+ _$_RithiSethOpCodeX2[204]+ _0xc832xc+ _$_RithiSethOpCodeX2[157]+ _0xc832x11+ _$_RithiSethOpCodeX2[159]+ _0xc832x1b+ _$_RithiSethOpCodeX2[201]+ _0xc832x16+ _$_RithiSethOpCodeX2[202]:_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[178])?_0xc832xe+= _$_RithiSethOpCodeX2[205]+ _0xc832x12+ _$_RithiSethOpCodeX2[206]+ _0xc832xc+ _$_RithiSethOpCodeX2[157]+ _0xc832x11+ _$_RithiSethOpCodeX2[197]+ _0xc832x16+ _$_RithiSethOpCodeX2[207]:_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[151])&& (_0xc832xe+= _$_RithiSethOpCodeX2[208]+ _0xc832x12+ _$_RithiSethOpCodeX2[209]+ _0xc832xc+ _$_RithiSethOpCodeX2[157]+ _0xc832x11+ _$_RithiSethOpCodeX2[197]+ _0xc832x16+ _$_RithiSethOpCodeX2[202]),_0xc832xa+= _0xc832xe};_0xc832xa+= _$_RithiSethOpCodeX2[210]}else {_0xc832xa= _0xc832x18()};if(_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[37])){_0xc832x9[_$_RithiSethOpCodeX2[19]](_$_RithiSethOpCodeX2[211])[_$_RithiSethOpCodeX2[11]](_0xc832xa),_0xc832x9[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[213])[_$_RithiSethOpCodeX2[33]](_$_RithiSethOpCodeX2[32],function(_0xc832x9,_0xc832x6){return _$_RithiSethOpCodeX2[179]== _0xc832x4|| _$_RithiSethOpCodeX2[181]== _0xc832x4?_0xc832x6[_$_RithiSethOpCodeX2[13]](_0xc832x6,_$_RithiSethOpCodeX2[212]+ postPerPage):_0xc832x6[_$_RithiSethOpCodeX2[13]](_0xc832x6,_$_RithiSethOpCodeX2[39]+ _0xc832x4+ _$_RithiSethOpCodeX2[40]+ postPerPage)})}else {if(_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[176])){_0xc832x9[_$_RithiSethOpCodeX2[95]](_0xc832xa)[_$_RithiSethOpCodeX2[9]]()[_$_RithiSethOpCodeX2[19]](_$_RithiSethOpCodeX2[188])}else {if(_0xc832x6[_$_RithiSethOpCodeX2[38]](_$_RithiSethOpCodeX2[177])){if(_$_RithiSethOpCodeX2[179]== _0xc832x4|| _$_RithiSethOpCodeX2[181]== _0xc832x4){var _0xc832x5=_$_RithiSethOpCodeX2[214]}else {_0xc832x5= _$_RithiSethOpCodeX2[39]+ _0xc832x4};_0xc832x9[_$_RithiSethOpCodeX2[9]]()[_$_RithiSethOpCodeX2[3]](_$_RithiSethOpCodeX2[218])[_$_RithiSethOpCodeX2[19]](_$_RithiSethOpCodeX2[217])[_$_RithiSethOpCodeX2[11]](_$_RithiSethOpCodeX2[215]+ _0xc832x5+ _$_RithiSethOpCodeX2[40]+ postPerPage+ _$_RithiSethOpCodeX2[157]+ messages[_$_RithiSethOpCodeX2[216]]+ _$_RithiSethOpCodeX2[159]),_0xc832x9[_$_RithiSethOpCodeX2[95]](_0xc832xa)[_$_RithiSethOpCodeX2[9]]()[_$_RithiSethOpCodeX2[19]](_$_RithiSethOpCodeX2[219])}else {_0xc832x9[_$_RithiSethOpCodeX2[95]](_0xc832xa)}}}}})}}$(_$_RithiSethOpCodeX2[239])[_$_RithiSethOpCodeX2[24]](function(){var _0xc832x9,_0xc832x3=commentsSystem,_0xc832x6=(disqus_blogger_current_url,_$_RithiSethOpCodeX2[220]+ $(location)[_$_RithiSethOpCodeX2[33]](_$_RithiSethOpCodeX2[32])+ _$_RithiSethOpCodeX2[221]),_0xc832x4=_$_RithiSethOpCodeX2[222]+ _0xc832x3;_$_RithiSethOpCodeX2[223]== _0xc832x3?$(this)[_$_RithiSethOpCodeX2[19]](_0xc832x4)[_$_RithiSethOpCodeX2[50]]():_$_RithiSethOpCodeX2[224]== _0xc832x3?((_0xc832x9= document[_$_RithiSethOpCodeX2[227]](_$_RithiSethOpCodeX2[226]))[_$_RithiSethOpCodeX2[225]]= _$_RithiSethOpCodeX2[228],_0xc832x9[_$_RithiSethOpCodeX2[229]]=  !0,_0xc832x9[_$_RithiSethOpCodeX2[65]]= _$_RithiSethOpCodeX2[230]+ disqusShortname+ _$_RithiSethOpCodeX2[231],(document[_$_RithiSethOpCodeX2[234]](_$_RithiSethOpCodeX2[233])[0]|| document[_$_RithiSethOpCodeX2[234]](_$_RithiSethOpCodeX2[45])[0])[_$_RithiSethOpCodeX2[232]](_0xc832x9),$(_$_RithiSethOpCodeX2[235])[_$_RithiSethOpCodeX2[103]](),$(this)[_$_RithiSethOpCodeX2[11]](_$_RithiSethOpCodeX2[236])[_$_RithiSethOpCodeX2[19]](_0xc832x4)[_$_RithiSethOpCodeX2[50]]()):_$_RithiSethOpCodeX2[237]== _0xc832x3?($(_$_RithiSethOpCodeX2[235])[_$_RithiSethOpCodeX2[103]](),$(this)[_$_RithiSethOpCodeX2[11]](_0xc832x6)[_$_RithiSethOpCodeX2[19]](_0xc832x4)[_$_RithiSethOpCodeX2[50]]()):_$_RithiSethOpCodeX2[101]== _0xc832x3?$(this)[_$_RithiSethOpCodeX2[101]]():$(this)[_$_RithiSethOpCodeX2[19]](_$_RithiSethOpCodeX2[238])[_$_RithiSethOpCodeX2[50]]()})})
//]]>
</script>
<b:if cond='data:view.isMultipleItems'>
<script type='text/javascript'>
//<![CDATA[
var postResults=postPerPage;
var numOfPages=2;
var pageOf=["Page", "of"];
var noPage;
var currentPage;
var currentPageNo;
var postLabel;
var locationUrl = location.href;
var home_page = "/";
pageCurrentBlogger();
function startPagination(a) {
    var b = '';
    pageNumber = parseInt(numOfPages / 2);
    if (pageNumber == numOfPages - pageNumber) {
        numOfPages = pageNumber * 2 + 1
    }
    pageStart = currentPageNo - pageNumber;
    if (pageStart < 1) pageStart = 1;
    lastPageNo = parseInt(a / postResults) + 1;
    if (lastPageNo - 1 == a / postResults) lastPageNo = lastPageNo - 1;
    pageEnd = pageStart + numOfPages - 1;
    if (pageEnd > lastPageNo) pageEnd = lastPageNo;
    b += '<span class="page-of">' + pageOf[0] + ' ' + currentPageNo + ' ' + pageOf[1] + ' ' + lastPageNo + '</span>';
    var c = parseInt(currentPageNo) - 1;
    if (currentPageNo > 1) {
        if (currentPageNo == 2) {
            if (currentPage == 'page') {
                b += '<a class="page-num page-prev" href="' + home_page + '"></a>'
            } else {
                b += '<a class="page-num page-prev" href="/search/label/' + postLabel + '?&max-results=' + postResults + '"></a>'
            }
        } else {
            if (currentPage == 'page') {
                b += '<a class="page-num page-prev" href="#" onclick="getPage(' + c + ');return false"></a>'
            } else {
                b += '<a class="page-num page-prev" href="#" onclick="getLabelPage(' + c + ');return false"></a>'
            }
        }
    }
    if (pageStart > 1) {
        if (currentPage == "page") {
            b += '<a class="page-num" href="' + home_page + '">1</a>'
        } else {
            b += '<a class="page-num" href="/search/label/' + postLabel + '?&max-results=' + postResults + '">1</a>'
        }
    }
    if (pageStart > 2) {
        b += '<span class="page-num page-dots">...</span>'
    }
    for (var d = pageStart; d <= pageEnd; d++) {
        if (currentPageNo == d) {
            b += '<span class="page-num page-active">' + d + '</span>'
        } else if (d == 1) {
            if (currentPage == 'page') {
                b += '<a class="page-num" href="' + home_page + '">1</a>'
            } else {
                b += '<a class="page-num" href="/search/label/' + postLabel + '?&max-results=' + postResults + '">1</a>'
            }
        } else {
            if (currentPage == 'page') {
                b += '<a class="page-num" href="#" onclick="getPage(' + d + ');return false">' + d + '</a>'
            } else {
                b += '<a class="page-num" href="#" onclick="getLabelPage(' + d + ');return false">' + d + '</a>'
            }
        }
    }
    if (pageEnd < lastPageNo - 1) {
        b += '<span class="page-num page-dots">...</span>'
    }
    if (pageEnd < lastPageNo) {
        if (currentPage == "page") {
            b += '<a class="page-num" href="#" onclick="getPage(' + lastPageNo + ');return false">' + lastPageNo + '</a>'
        } else {
            b += '<a class="page-num" href="#" onclick="getLabelPage(' + lastPageNo + ');return false">' + lastPageNo + '</a>'
        }
    }
    var e = parseInt(currentPageNo) + 1;
    if (currentPageNo < lastPageNo) {
        if (currentPage == 'page') {
            b += '<a class="page-num page-next" href="#" onclick="getPage(' + e + ');return false"></a>'
        } else {
            b += '<a class="page-num page-next" href="#" onclick="getLabelPage(' + e + ');return false"></a>'
        }
    }
    b += '';
    var f = document.getElementsByName('pageArea');
    var g = document.getElementById('blog-pager');
    for (var p = 0; p < f.length; p++) {
        f[p].innerHTML = b
    }
    if (f && f.length > 0) {
        b = ''
    }
    if (g) {
        g.innerHTML = b
    }
}
function dataFeed(a) {
    var b = a.feed;
    var c = parseInt(b.openSearch$totalResults.$t, 10);
    startPagination(c)
}
function pageCurrentBlogger() {
    var a = locationUrl;
    if (a.indexOf('/search/label/') != -1) {
        if (a.indexOf('?updated-max') != -1) {
            postLabel = a.substring(a.indexOf('/search/label/') + 14, a.indexOf('?updated-max'))
        } else {
            postLabel = a.substring(a.indexOf('/search/label/') + 14, a.indexOf('?&max'))
        }
    }
    if (a.indexOf('?q=') == -1 && a.indexOf('.html') == -1) {
        if (a.indexOf('/search/label/') == -1) {
            currentPage = 'page';
            if (locationUrl.indexOf('#PageNo=') != -1) {
                currentPageNo = locationUrl.substring(locationUrl.indexOf('#PageNo=') + 8, locationUrl.length)
            } else {
                currentPageNo = 1
            }
            document.write('<script src=\'' + home_page + 'feeds/posts/summary?max-results=1&alt=json-in-script&callback=dataFeed\'><\/script>')
        } else {
            currentPage = 'label';
            if (a.indexOf('&max-results=') == -1) {
                postResults = 20
            }
            if (locationUrl.indexOf('#PageNo=') != -1) {
                currentPageNo = locationUrl.substring(locationUrl.indexOf('#PageNo=') + 8, locationUrl.length)
            } else {
                currentPageNo = 1
            }
            document.write('<script src="' + home_page + 'feeds/posts/summary/-/' + postLabel + '?alt=json-in-script&callback=dataFeed&max-results=1" ><\/script>')
        }
    }
}
function getPage(a) {
    jsonstart = (a - 1) * postResults;
    noPage = a;
    var b = document.getElementsByTagName('head')[0];
    var c = document.createElement('script');
    c.type = 'text/javascript';
    c.setAttribute('src', home_page + 'feeds/posts/summary?start-index=' + jsonstart + '&max-results=1&alt=json-in-script&callback=findPostDate');
    b.appendChild(c)
}
function getLabelPage(a) {
    jsonstart = (a - 1) * postResults;
    noPage = a;
    var b = document.getElementsByTagName('head')[0];
    var c = document.createElement('script');
    c.type = 'text/javascript';
    c.setAttribute('src', home_page + 'feeds/posts/summary/-/' + postLabel + '?start-index=' + jsonstart + '&max-results=1&alt=json-in-script&callback=findPostDate');
    b.appendChild(c)
}
function findPostDate(a) {
    post = a.feed.entry[0];
    var b = post.published.$t.substring(0, 19) + post.published.$t.substring(23, 29);
    var c = encodeURIComponent(b);
    if (currentPage == 'page') {
        var d = '/search?updated-max=' + c + '&max-results=' + postResults + '#PageNo=' + noPage
    } else {
        var d = '/search/label/' + postLabel + '?updated-max=' + c + '&max-results=' + postResults + '#PageNo=' + noPage
    }
    location.href = d
}
//]]>
</script>
</b:if>
  <div class='back-top' title='Back to Top'/>
</body>
</html>
