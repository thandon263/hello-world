<!doctype html>
<html class="no-js" lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="x-ua-compatible" content="ie=edge">
        <title>hackerYou | Technical Challenge 2016</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="css/style.css">
        <style type="text/css">
        
        @import url(http://fonts.googleapis.com/css?family=Raleway:400,200,500,700);

/* reset --------------------------  */

html,
body,
div,
ul,
ol,
li,
dl,
dt,
dd,
h1,
h2,
h3,
h4,
h5,
h6,
pre,
form,
dfn,
del,
p,
blockquote,
fieldset,
input,
textarea,
select,
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
nav,
section,
button,
canvas,
video {
    margin: 0;
    padding: 0;
}

h1,
h2,
h3,
h4,
h5,
h6,
pre,
code,
address,
caption,
cite,
code,
th,
dfn,
del {
    font-weight: normal;
    font-style: normal;
}

ul,
ol {
    list-style: none
}

fieldset,
img {
    border: none
}

caption,
th {
    text-align: left
}

table {
    border-collapse: collapse;
    border-spacing: 0;
}

input[type="button"],
input[type="submit"],
input[type="reset"],
button {
    cursor: pointer
}

input[type="button"],
input[type="submit"],
input[type="reset"],
button,
input[type="search"],
input[type="text"],
input[type="email"],
input[type="tel"],
input[type="number"],
textarea {
    -webkit-appearance: none;
    -moz-appearance: none;
    -ms-appearance: none;
    appearance: none;
}

input,
button,
textarea {
    line-height: normal;
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}

input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
    -webkit-appearance: none
}

button::-moz-focus-inner,
input::-moz-focus-inner {
    border: 0;
    padding: 0;
}

input[type="hidden"],
[hidden],
.hidden {
    display: none
}

textarea {
    overflow: auto;
    resize: none;
}

article,
aside,
details,
figcaption,
figure,
footer,
header,
nav,
section,
.clearfix {
    display: block
}

audio,
canvas,
video {
    display: inline-block
}

a > img {
    vertical-align: bottom
}

strong,
.strong,
b {
    font-weight: bold
}

em,
.italic,
i {
    font-style: italic
}

del,
.del {
    text-decoration: line-through
}

:focus {
    outline: none
}

img {
    max-width: 100%;
    width: auto;
    height: auto;
}

/* tools --------------------------  */

.clear {
    clear: both;
    display: block;
    line-height: 0;
    height: 0;
    font-size: 0;
}

.clearfix:after,
.wrap:after,
.spanning:after,
.content:after,
.main:after,
aside:after,
section:after,
article:after,
.text:after {
    content: ".";
    display: block;
    clear: both;
    visibility: hidden;
    line-height: 0;
    height: 0;
    font-size: 0;
}

.align-left {
    float: left !important
}

.align-right {
    float: right !important
}

.overflow-hidden {
    overflow: hidden;
    display: block;
}

/* common --------------------------  */

.comments .tab-prev,
.comments .tab-next,
.button-download:after {
    background: url(../images/) 0 0 no-repeat
}

html {
    height: 100%;
    background: white;
}

body {
    height: 100%;
    font: 16px/28px "Helvetica Neue", Helvetica, Arial, sans-serif;
    color: #222222;
    -webkit-font-smoothing: antialiased;
    -webkit-backface-visibility: hidden;
    -ms-text-size-adjust: 100%;
    -webkit-text-size-adjust: 100%;
}

.main {
    min-height: 100%;
    overflow: hidden;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

.wrap {
    margin: 0 auto;
    padding: 0 15px;
    max-width: 1140px;
}

.Overlap {
    position: absolute;
    z-index: 10;
    margin-left: 44%;
    margin-right: 50%;
    padding: 0;
    margin-top: -37px;
}

a {
    color: #10bbf1;
    cursor: pointer;
    background: transparent;
    text-decoration: none;
}

a:hover {
    color: #40c9f4
}

a:active {
    color: #0b97c3
}

.error {
    color: red !important;
    border-color: red !important;
}

.success {
    color: #00cc00 !important;
    border-color: #00cc00 !important;
}

.disabled {
    color: #999999 !important;
    border-color: #999999 !important;
    cursor: default !important;
}

.input-text,
.textarea {
    width: 100%;
    float: left;
    border: 2px solid #d8d8d8;
    background: white;
    height: 58px;
    padding: 10px 21px;
    font: 500 17px/34px "Raleway", "Helvetica Neue", Helvetica, Arial, sans-serif;
    -moz-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -ms-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -o-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -webkit-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -moz-border-radius: 5px;
    -webkit-border-radius: 5px;
    border-radius: 5px;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

.input-text:focus,
.textarea:focus {
    border-color: #aeaeae
}

.textarea {
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif
}

.buttons-wrapper1{


}

.button1 {


}

.button {
    width: 260px;
    color: white;
    background: #7F1FC3;
    height: 50px;
    font: 500 18px "Raleway", "Helvetica Neue", Tahoma, Arial, sans-serif;
    font-weight: bold;
    text-align: center;
    -moz-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -ms-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -o-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -webkit-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -moz-border-radius: 24px;
    -webkit-border-radius: 24px;
    border-radius: 24px;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}


.button-Heading {
    width: 260px;
    color: #000;
    background: white;
    height: 50px;
    font: 500 18px "Raleway", "Helvetica Neue", Tahoma, Arial, sans-serif;
    font-weight: bold;
    text-align: center;
    -moz-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -ms-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -o-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -webkit-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -moz-border-radius: 24px;
    -webkit-border-radius: 24px;
    border-radius: 24px;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}




.button:hover {
    background: #40c9f4;
    border-color: #40c9f4;
}

.button-Heading:hover {
    background: #40c9f4;
    border-color: #40c9f4;
}

.button:active {
    background: #0b97c3;
    border-color: #0b97c3;
}

a.button {
    text-decoration: none;
    display: inline-block;
    line-height: 54px;
    color: white;
}

a.button:hover {
    color: white
}

a.button:active {
    color: white
}

a.button.button-stripe {
    background-color: rgba(0, 0, 0, 0.2);
    border-color: white;
}

a.button.button-stripe:hover {
    color: #222222;
    background-color: white;
    border-color: white;
}

a.button.button-stripe:active {
    color: #222222;
    background-color: #e5e5e5;
    border-color: #e5e5e5;
}

::-webkit-input-placeholder {
    color: #cccccc
}

:-moz-placeholder {
    color: #cccccc
}

::-moz-placeholder {
    color: #cccccc
}

:-ms-input-placeholder {
    color: #cccccc
}

input:focus::-webkit-input-placeholder {
    color: transparent
}

/* div of the Navigation header -------------*/

@media screen and (max-width: 768px) {



}

@media screen and (max-width: 480px) {


}

/*---------- Normal Desktop Screen ------------------ */

.Header{
    height: 60px;
    background-color: ;
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    line-height: 0;
    border-bottom: 1px solid #fff;
    margin-top: 30px;
}

.Logo {
    float: left;
    font-family: Tahoma;
    margin-left: 120px;
    color: #ffffff;
    margin-top: 0px;
}

.Nav ul li a {
    text-decoration: none;
    color: #fff;
    list-style: none;
    float: left;
}

.Nav ul li a:hover{
    color: skyblue;
    
}

.Nav {
    float: right;
}

li{
    display: inline-block;
    margin-right: 20px;
    font-size: 11pt;
    font-weight: bolder;


}

ul{
    margin-right: 380px;
    margin-top: 4px;
}

/*

input [type="text"] {
    background-image: url("upload/search_icon.png") no-repeat 8px 3px #444;
    border: 0 none;
    font: bold 11px Arial, Helvetica, sans-serif;
    color: #777;
    width: 150px;
    height: 22px;
    padding: 6px 15px 6px 35px;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    border-radius: 20px;
    text-shadow: 0 2px 2px rgba(0, 0, 0, 0.3);
    -webkit-box-shadow: 0 1px 0 rgba(255, 255, 255, 0.1), 0.1px 3px rgba(0, 0, 0, 0.2) inset;
    -moz-box-shadow: 0 1px 0 rgba(255, 255, 255, 0.1), 0.1px 3px rgba(0, 0, 0, 0.2) inset;
    box-shadow: 0 1px 0 rgba(255, 255, 255, 0.1), 0.1px 3px rgba(0, 0, 0, 0.2) inset;
    -webkit-transition: all 0.7s ease 0s;
    -moz-transition: all 0.7s ease 0s;
    -o-transition: all 0.7s ease 0s;
    transition: all 0.7s ease 0s;

    
}

input [type="text"]:focus {
    background-color: url("upload/search_icon.png") no-repeat 8px 3px #EFEFEF;
    width: 200px;
    -webkit-box-shadow: 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(0, 0, 0, 0.9) inset;
    -moz-box-shadow: 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(0, 0, 0, 0.9) inset;
    box-shadow: 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(0, 0, 0, 0.9) inset;
    border: 1.5px #6F6F6F;
    border-radius: 20px;

}

input [type="text"]:hover {
    background-image: url("upload/search_icon.png") no-repeat 8px 3px #EFEFEF;
    margin: auto;
    width: 200px;
    box-shadow: 0 1px 0 rgba(255, 255, 255, 0.1), 0.1px 3px rgba(0, 0, 0, 0.2) inset;
    text-shadow: 0 2px 2px rgba(0, 0, 0, 0.3);

    -webkit-box-shadow: 0 1px 0 rgba(255, 255, 255, 0.1), 0.1px 3px rgba(0, 0, 0, 0.2) inset;
    -moz-box-shadow: 0 1px 0 rgba(255, 255, 255, 0.1), 0.1px 3px rgba(0, 0, 0, 0.2) inset;
   border: 1.5px #6F6F6F;
   border-radius: 20px;
}

--------------------------------------------------
--------------------------------------------------

CSS 3 Resource for SearchBox Transition Effect

*/ 

.SearchBar{
    float: right;
    margin-left: 600px;
    margin-right: 80px;
    margin-top: -10px;

}

.SearchBox{
    color: #000;
    background-color: #fff;
    font-family: Baskersville;
    font-size: 14pt;
    width: 220px;
    height: 30px;
    border-radius: 20px;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    padding-left: 18px;

}


/* header --------------------------  */

.More-Content{
    padding: 104px 0;
    background: url(../upload/background2.jpg) no-repeat 50% 50%;
    font: "Raleway", "Helvetica Neue", Helvetica, Arial, sans-serif;
    color: white;
    text-align: right;
    -moz-background-size: cover;
    -webkit-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

.More-Content h1 {
    font-size: 28px;
    line-height: 38px;
    font-weight: 500;
    margin-bottom: 38px;
}

.More-Content h1 span {
    font-weight: 200
}

.More-Content .autor {
    padding: 12px 0 0;
    font-size: 14px;
    line-height: 24px;
    font-weight: bold;
    color: white;
}

.More-Content .autor a {
    color: white
}

.More-Content .autor a:hover {
    color: white;
    opacity: 0.8;
    filter: alpha(opacity=80);
}

.More-Content .autor a:active {
    color: white;
    opacity: 1;
    filter: alpha(opacity=100);
}

.More-Content .buttons-wrapper {
    padding-top: 53px
}

.More-Content .buttons-wrapper .button-stripe {
    margin-left: 14px
}






/*-----------------------------------------*/




/*-------The Heaader -----------*/
header {
    padding: 104px 0;
    background: url(../upload/header.jpg) no-repeat 50% 50%;
    font: "Raleway", "Helvetica Neue", Helvetica, Arial, sans-serif;
    color: white;
    text-align: right;
    -moz-background-size: cover;
    -webkit-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

header h1 {
    font-size: 60px;
    line-height: 60px;
    font-weight: 500;
    margin-bottom: 38px;
}

header h1 span {
    font-weight: 200
}

header .autor {
    padding: 12px 0 0;
    font-size: 14px;
    line-height: 24px;
    font-weight: bold;
    color: white;
}

header .autor a {
    color: white
}

header .autor a:hover {
    color: white;
    opacity: 0.8;
    filter: alpha(opacity=80);
}

header .autor a:active {
    color: white;
    opacity: 1;
    filter: alpha(opacity=100);
}

header .buttons-wrapper {
    padding-top: 53px
}

header .buttons-wrapper .button-stripe {
    margin-left: 14px
}

.header-img {
    float: right
}

.header-wrapper {
    padding-top: 87px;
    max-width: 655px;
}

/* footer --------------------------  */

footer {
    background: #324a57;
    color: white;
    font-size: 16px;
    line-height: 28px;
    padding: 90px 0;
    text-align: center;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

footer p {

    float: left;
}

.Footer-One {

    background: hsla(353, 73%, 50%, 0.82);
    color: white;
    font-size: 16px;
    line-height: 28px;
    padding: 90px 0;
    text-align: center;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;   

}

.Footer-One h4 {
    float: left;
    margin-left: 20px;
    font-weight: bolder;
    font-size: 18pt;
}

.Footer-One p {

    float: left;
    text-align: left;
    margin-left: 20px;
    margin-top: 8px;
}

.Footer-One a {

    float: left;
    margin-left: -200px;
    margin-top: 120px;

}
/* home --------------------------  */

/* content --------------------------  */

.spanning {
    clear: both
}

.newsletter {
    background: #fafafa;
    padding: 103px 0 109px;
    text-align: center;
}

.newsletter p {
    font-size: 16px;
    line-height: 28px;
    max-width: 556px;
    margin: 0 auto;
    clear: both;
}

.newsletter-title {
    font: bold 48px/60px "Raleway", "Helvetica Neue", Helvetica, Arial, sans-serif;
    letter-spacing: 1px;
    text-transform: uppercase;
    margin-bottom: 38px;
}

.newsletter-form {
    position: relative;
    display: inline-block;
    padding-right: 169px;
    max-width: 556px;
    min-width: 556px;
    height: 58px;
    margin-bottom: 32px;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

.newsletter-form .button {
    position: absolute;
    right: 0;
    top: 0;
    padding-left: 0;
    padding-right: 0;
    width: 149px;
}

.promo {
    padding: 114px 0 54px
}

.promo-wrapper {
    margin: 0 -15px
    width: 120px;
    height: 400px;
}

.promo-column {
    padding: 0 15px 60px;
    display: inline-block;
    margin-left: 200px;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    width: 25%;
}



.simple {
    padding: 104px 0 89px
}

.simple-content {
    float: right;
    padding-top: 37px;
    width: 420px;
}

.simple-content h3 {
    font: 700 48px/48px "Raleway", "Helvetica Neue", Helvetica, Arial, sans-serif;
    text-transform: uppercase;
    border-bottom: solid 6px #f4f4f4;
    padding-bottom: 43px;
    margin-bottom: 43px;
}

.simple-content ul {
    margin-bottom: 5px
}

.simple-content ul li {
    font-size: 23px;
    line-height: 32px;
    font-weight: 300;
    margin-bottom: 31px;
}

.simple-content ul li img {
    float: left;
    margin-right: 23px;
}

.simple-content ul li span {
    display: block;
    overflow: hidden;
}

.simple-img {
    float: left;
    max-width: 587px;
    width: 53%;
}

.simple-img img {
    display: block;
    margin: 0 auto;
}

.comments {
    background: #10bbf1;
    color: white;
    text-align: center;
    padding: 70px 0 60px;
}

.comments .box {
    display: none;
    padding: 0 195px 55px;
}

.comments .box.visible {
    display: block
}

.comments .box h4 {
    font: 500 36px/46px "Raleway", "Helvetica Neue", Helvetica, Arial, sans-serif;
    margin-bottom: 37px;
}

.comments .box h4 a {
    font-weight: bold;
    color: white;
}

.comments .box h4 a:hover {
    text-decoration: underline
}

.comments .box p {
    font-size: 19px;
    line-height: 32px;
    font-weight: 300;
}

.comments .tabs {
    display: block;
    text-align: center;
    font-size: 0;
    line-height: 0;
}

.comments .tabs li {
    display: inline-block;
    margin: 0 8px;
    width: 11px;
    height: 11px;
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    background-color: rgba(255, 255, 255, 0.3);
    box-shadow: 0 0 0 2px rgba(255, 255, 255, 0);
    cursor: pointer;
    -moz-transition: box-shadow 0.3s ease, background-color 0.3s ease;
    -ms-transition: box-shadow 0.3s ease, background-color 0.3s ease;
    -o-transition: box-shadow 0.3s ease, background-color 0.3s ease;
    -webkit-transition: box-shadow 0.3s ease, background-color 0.3s ease;
    transition: box-shadow 0.3s ease, background-color 0.3s ease;
}

.comments .tabs li:hover {
    background-color: white
}

.comments .tabs li.active {
    background-color: transparent;
    box-shadow: 0 0 0 2px white;
}

.comments .tab {
    position: relative
}

.comments .tab-prev,
.comments .tab-next {
    position: absolute;
    left: 98px;
    top: 94px;
    width: 23px;
    height: 16px;
    background-position: 0 0;
    opacity: 0.5;
    filter: alpha(opacity=50);
}

.comments .tab-prev:hover,
.comments .tab-next:hover {
    opacity: 1;
    filter: alpha(opacity=100);
}

.comments .tab-next {
    left: auto;
    right: 98px;
    background-position: -50px 0;
}

/*.video-title {
    font: bold 48px/48px "Raleway", "Helvetica Neue", Helvetica, Arial, sans-serif;
    text-align: center;
    text-transform: uppercase;
    margin-bottom: 25px;
}

.video-subtitle {
    font-size: 19px;
    line-height: 25px;
    color: #919191;
    text-align: center;
}

.video {
    padding: 108px 0 116px
}

.video-block {
    padding-top: 34px;
    margin: 0 auto 32px;
    max-width: 760px;
}

.video-share-wrapper {
    clear: both;
    text-align: center;
}

.social-list {
    display: inline-block
}

.social-list li {
    font-size: 19px;
    line-height: 38px;
    float: left;
    margin: 0 9px;
}

.social-list li a {
    font-size: 15px;
    line-height: 38px;
    display: block;
    width: 160px;
    height: 38px;
    -moz-border-radius: 3px;
    -webkit-border-radius: 3px;
    border-radius: 3px;
    background-color: #3bcbff;
    color: white;
    text-align: center;
    -moz-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -ms-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -o-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    -webkit-transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
    transition: color 0.1s linear, background-color 0.1s linear, border-color 0.1s linear;
}

.social-list li a:hover {
    background-color: #6ed9ff
}

.social-list li a:active {
    background-color: #08bdff
}

.social-list li a.social-facebook {
    background-color: #1e3aa6
}

.social-list li a.social-facebook:hover {
    background-color: #2649d1
}

.social-list li a.social-facebook:active {
    background-color: #162b7b
}

.social-list li a.social-google {
    background-color: #d72d26
}

.social-list li a.social-google:hover {
    background-color: #e05650
}

.social-list li a.social-google:active {
    background-color: #ac241e
}
 */




/*------------------------------------------------------------*/

                         /*  Navigation */


/*
.Container {
	  max-width: 1000px;
	  margin: 0 auto;
	  padding: 0px 20px;
	  position: relative;
}


.Nav > ul {
  	float: right;
}

.Nav > ul > li {
  	text-align: center;
	  line-height: 40px;
	  margin-left: 70px;
}

.Nav > ul li ul li {
	  width: 100%;
  	text-align: left;
}

.Nav ul li:hover {
	  cursor: pointer;
	  position: relative;
}
.Nav ul li:hover > ul {
  	display: block;
}
.Nav ul li:hover > a {
	  color: #777;
}
.Nav > ul > li > a {
	  cursor: pointer;
	  display: block;
  	outline: none;
  	width: 100%;
	  text-decoration: none;
}

.Nav > ul > li {
  	float: left;
}
.Nav a {
	  color: white;
}
.Nav > ul li ul {
  	display: none;
  	position: absolute;
  	left: 0;
	  top: 100%;
  	width: 100%;
	  z-index: 2000;
}
.Nav > ul li ul li > a {
	  text-decoration: none;
}

[type="checkbox"], label {
	  display: none;
}

@media screen and (max-width: 768px) {
	.Nav ul {
		  display: none;
	}

	.label {
  		display: block;
  		background: #222;
		  width: 40px;
  		height: 40px;
  		cursor: pointer;
		  position: absolute;
		  right: 20px;
  		top: 0px;
	}
  
label:after{
  content:'';
  display: block;
  width: 30px;
  height: 5px;
  background: #777;
  margin: 7px 5px;
  box-shadow: 0px 10px 0px #777, 0px 20px 0px #777
}

	[type="checkbox"]:checked ~ ul {
  		display: block;
  		z-index: 9999;
  		position: absolute;
		  right: 20px;
		  left: 20px;
	}

	.Nav a {
		  color: #777;
	}

	.Nav ul li {
		  display: block;
  		float: none;
  		width: 100%;
  		text-align: left;
  		background: #222;
		  text-indent: 20px;
	}

	.Nav > ul > li {
  		margin-left: 0px;
	}

	.Nav > ul li ul li {
  		display: block;
		  float: none;
	}
  
	.Nav > ul li ul {
		  display: block;
  		position: relative;
  		width: 100%;
		  z-index: 9999;
		  float: none;
	}


}



*/


/*              ---------------------------------             */

.Social a{margin-left: 12px; margin-right: 6px; padding: 0; float: none;}
.content { text-align: left; float: right; width: 50%; text-indent: unset;}
.content1 { text-align: left; float: left; width: 50%; text-indent: unset;}
.Lorem-Ipsum {margin-top: 30px;}
.content-image {width: 49%; height: 464px; margin-left: 0px; margin-bottom: 0px; margin-top: -30.8px;}
.Content-image1 {width: 49%; height: 440px; margin-left: 0px; margin-bottom: 0px; margin-top: -30.8px;}
.discover {
    padding: 31px 0 25px;
    background: #EFEFEF;
}

/* Social Media Icons ------------------*/



/*--------------------------------------*/

.discover-content {
    float: none;
    text-align: center;
    margin-top: 11px;
    width: 50% 50%;
    padding: 77px 97px 50px 15px;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

[type="checkbox"], label {
	  display: none;
}

.discover-content h2 {
    font-size: 72px;
    line-height: 72px;
    font-weight: bold;
    margin-bottom: 29px;
}

.discover-button {
    padding-top: 68px;
    margin: 0 -10px;
    clear: both;
}

.Div-Paragraph1 {
        
        font-size: 10pt;
        text-align: left;
        font-family: Verdana;
        margin-top: 30px;
        
        
    }
    
    .Div-Paragraph2 {

        font-size: 15pt;
        text-align: justify;
        font-family: Baskersville;
        
    }

.Header-Title {

    font-size: 48pt;
    line-height: 0.8;
    text-align: left;
    margin-top: -42px;
}

    


.button-download {
    height: 62px;
    float: left;
    font: 500 11px/13px "Raleway", "Helvetica Neue", Helvetica, Arial, sans-serif;
    padding-left: 61px;
    padding-right: 0;
    width: 180px;
    text-align: left;
    margin: 0 10px 20px;
    position: relative;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

.button-download:after {
    content: "";
    position: absolute;
    left: 23px;
    top: 14px;
    width: 32px;
    height: 32px;
    background-position: -100px 0;
}

.button-download-title {
    padding: 11px 0 1px;
    display: block;
    font-size: 11px;
    line-height: 13px;
    text-align: left;
}

.button-download-subtitle {
    display: block;
    font-size: 21px;
    line-height: 23px;
    text-align: left;
}


.discover-img-inside {
    max-width: 49%;
    float: left;
}

/* sidebar --------------------------  */

/* media --------------------------  */

/* ===[ Responsive all mobile sizes ]=== */

@media (max-width: 979px) { 
  .newsletter-form {
      min-width: 0
  }

  .newsletter-title {
      font-size: 36px;
      line-height: 48px;
  }
    
    
    .button-Footer {
        
        display: none;
        
    }

    .Contact-Header {
        
        display: none;
    }
    
    .Contact-Paragraph {
        
        text-align: left;
        font-size: 10pt;
    }
    
.content-image {
    
    display: none;

    }

.Content-image2 {
    
    display: none;

    }

.Social a{margin-left: 12px; margin-right: 6px; margin-top: 220px; padding: 0; float: none;}
    
    /*
    -------------------------------------------------
    
                    More Content
    
    -------------------------------------------------
    */
    
    .More-Content{
    padding: 104px 0;
    background: url(../upload/background2.jpg) no-repeat 50% 50%;
    font: "Raleway", "Helvetica Neue", Helvetica, Arial, sans-serif;
    color: white;
    text-align: right;
    -moz-background-size: cover;
    -webkit-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}
    
    .More-Content img {
        
        display: none;
    }

    
    .button button-stripe{
        
        float:left;
       clear: both;
       margin-right: 300px;
        
    }
    
.More-Content h1 {
    font-size: 12pt;;
    line-height: 38px;
    font-weight: 500;
    margin-bottom: 38px;
    margin-left: 90px;
    float: left;
    text-align: left;
}

.More-Content h1 span {
    font-weight: 200;
}

.More-Content .autor {
    
    display: none;
}

    .More-Content.button button-stripe {
        
    }
    
    
    /*---------------------------------------------*/


  .header-img {
      display: none
  }

  .header-wrapper {
      padding-top: 0;
      max-width: none;
  
  }

  .discover {

    height: 480px;
  }

  .discover-content h1 {
    font-size: 24pt;
    line-height: 41px;
    font-weight: bold;
    text-align: center;
    margin-left: -50px;
    margin-top: -100px;
    margin-bottom: 29px;
}

.discover-content p {

    margin-left: 30px;
    text-align: left;
    text-indent: 1;
}

.discover-content {

    margin-right: 29px;
}


  .Header{
    height: 80px;
    background-color: ;
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    line-height: 0;
    margin-top: 30px;
}

.SearchBar{
    float: right;
    margin-left: 600px;
    margin-right: 10px;
    margin-top: -75px;

}

.SearchBox{
    color: #000;
    background-color: #fff;
    font-family: Baskersville;
    font-size: 12pt;
    width: 120px;
    height: 30px;
    
}

.SearchBox:hover {

    max-width: 200;
    font-size: 9pt;


}
    
  .Logo {
    float: left;
    font-family: Tahoma;
    margin-left: 120px;
    color: #ffffff;
    margin-top: 0px;
    max-width: 400px;
    max-height: 100px;
}

.Nav ul li a {
    text-decoration: none;
    color: #fff;
    list-style: none;
    float: left;
}

.Nav ul li a:hover{
    color: skyblue;
    
}


.Nav {
    float: right;
}

li{
    display: inline-block;
    margin-right: 20px;
    margin-left: 24px;
    font-size: 10pt;
    font-weight: bolder;


}

ul{
    margin: auto;
    margin-top: 40px;

}

.Header-Title {

    font-size: 48pt;
    line-height: 0.8;
    text-align: left;
}


  header {
      text-align: center;
      font-size: 19px;
      line-height: 28px;
  }

  header .buttons-wrapper .button {
      margin-bottom: 20px
  }

  .promo-column {
      width: auto;
      font-size: 11pt;
      max-width: 690px;
      margin-top: -30px;
      margin-left: auto;
      margin-right: auto;
      float: none;
      text-align: left;
  }

.content { text-align: left; float: right; width: 100%; text-indent: unset;}
.content1 { text-align: left; float: left; width: 100%; text-indent: unset;}

  .simple-content {
      float: none;
      width: auto;
      padding-top: 0;
  }

  .simple-content h3 {
      font-size: 36px;
      line-height: 46px;
      text-align: center;
  }

  .simple-content ul {
      max-width: 310px;
      margin-left: auto;
      margin-right: auto;
  }

  .simple-img {
      float: none;
      width: auto;
      max-width: none;
      margin-left: -80px;
      margin-right: -80px;
  }

  .comments .box {
      padding-left: 0;
      padding-right: 0;
  }

  .discover-content {
      float: none;
      width: auto;
      padding-left: 0;
      padding-right: 0;
      text-align: center;
  }

  .discover-content h2 {
      font-size: 60px;
      line-height: 60px;
  }

  .discover-button {
      text-align: center
  }

  .discover-button .button-download {
      float: none;
      display: inline-block;
  }


/* ===[ Responsive just mobile portrait ]=== */

@media (max-width: 479px) { 
  header .buttons-wrapper .button.button-stripe {
      margin-left: 0
  }

.SearchBox{

    display: none;
}

.Overlap {
     
    display: none;
    
    }

  .Logo {
    float: left;
    font-family: Tahoma;
    margin-left: 120px;
    color: #ffffff;
    margin-top: 0px;
    max-width: 400px;
    max-height: 100px;
}

.Header {

    height: 120px;

}
    
    
.Social a{ display: block; margin-left: 12px; margin-right: 26px; margin-top: 10px; padding: 0; float: left;}    
    
    
.content-image {
    
    display: none;

    }

.Content-image2 {
    
    display: none;

    }



.promo-column {
      width: auto;
      font-size: 9pt;
      max-width: 590px;
      margin-top: -50px;
      margin-left: auto;
      margin-right: auto;
      float: none;
      text-align: left;
  }


.Nav ul li a {
    text-decoration: none;
    color: #fff;
    list-style: none;
    float: left;
}

.Nav ul li a:hover{
    color: skyblue;
    
}

.Nav {
    float: right;
    width: 100%;
}

.Header-Title {

    font-size: 28pt;
    line-height: 0.8;
    text-align: left;
}

li{
    display: inline-block;
    margin-left: 3px;
    font-size: 10pt;
    font-weight: bolder;
}

ul{
    margin-right: 3;
    margin-top: 60px;
    margin-left: 40px;

}
    
    .List-Contact {
        
        display:none;
    }

  .discover-content h2 {
      font-size: 36px;
      line-height: 46px;
  }
    
    
    .Content-Div {
        
        font-size: 12pt;
        text-align: justify;
        
    }
    
    .Div-Paragraph1 {
        
        font-size: 10pt;
        text-align: left;
        font-family: Verdana;
        margin-top: 30px;
        
        
    }
    
    .Div-Paragraph2 {

        font-size: 14pt;
        text-align: justify;
        font-family: Baskersville;
        
    }
    
    
}

    

@media only screen and (-webkit-min-device-pixel-ratio: 2), only screen and (min--moz-device-pixel-ratio: 2), only screen and (-o-min-device-pixel-ratio: 2 / 1), only screen and (min-device-pixel-ratio: 2), only screen and (min-resolution: 192dpi), only screen and (min-resolution: 2dppx) { 
  
    
.Nav ul li a {
    text-decoration: none;
    color: #fff;
    list-style: none;
    float: left;
}

.Nav ul li a:hover{
    color: skyblue;
    
}


.Nav {
    float: right;
}

li{
    display: inline-block;
    margin-right: 20px;
    margin-left: 24px;
    font-size: 10pt;
    font-weight: bolder;


}

ul{
    margin-right: 3px;
    margin-top: 70px;

}

  }
}

        
        </style>
        
    </head>
    <body>

<!----------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------- -->

       <!-- The Header div //Fixed Header -->
        
        <div class="Header">

             <div class="Container">
                 <div class="Logo">
                     <img src="upload/logo.png">
                 </div>
                 
                 <div class="Nav">
                     
                     <input type="checkbox" id="nav" /><label for="nav"></label>
                    <ul>
                     <li><a href="#">About</a></li>
                     <li><a href="#">How It Works</a></li>
                     <li><a href="#">Services</a></li>
                     <li><a href="#">FAQ</a></li>
                     <li><a href="#" class="List-Contact">Contact</a></li>
                    </ul>   
                 </div>
                </div>
         <div class="SearchBar">
                    
                    <img height="1" width="1" />

                    <form action=" ">
                         <input type="text" class="SearchBox" placeholder="Search Website" ></input>
                     </form>
                   </div>
               
        </div>
        
             
            
        <!-- End of Fixed Header with Opacity os 0.15 -->


        <header> <!-- This is the Main Header with Background image -->
            <div class="wrap">
                <div class="header-wrapper">
                    <p class="Header-Title" style=" margin-top: 110px; text-align: right;">Custom Web Design <br /><br /> and Development</p>
                    <div class="buttons-wrapper">
                        <a href="#" class="button">Get Started</a>
                        <p style="font-size: 8pt; margin-right: 30px;">Lorem ipsum dolor sit amet, consectetur</p>
                        <!-- <a href="#" class="button button-stripe">Learn more</a>  
                           // The Button Learn More   // -->
                    
                    </div>
                </div>
                <!-- /.header-wrapper -->
            </div>
            <!-- /.wrap -->
        </header>

        <!-- The content styled in two rows and columns of paragraphs -->

                <div class="spanning">
               
            <div class="promo clearfix" style=" background-color: #2A3950; color: #fff;">
                    <div class="wrap">
                    <div class="promo-wrapper clearfix" >
                        <div class="promo-column">
                            <h4 style="font-family: Tahoma; font-weight: bold;">HEADING ONE</h4>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut</p>
                        </div>
                        <div class="promo-column"> 
                           <h4 style="font-family: Tahoma; font-weight: bold;">HEADING TWO</h4>   
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut </p>
                        </div>
                        <div class="promo-column">
                            <h4 style="font-family: Tahoma; font-weight: bold;">HEADING THREE</h4>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut </p>
                        </div>
                        <div class="promo-column">
                            <h4 style="font-family: Tahoma; font-weight: bold;">HEADING FOUR</h4>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut. </p>
                         </div>
                        </div>
                        </div>
                    </div>
                </div>
                <!-- The style-img.png image ,,, -->
                        

                      
    
                             <img class="Overlap" src="upload/style-img.png" />
    
                    


        <!-- The next div for Content -- -->

        <div class="discover clearfix" style="background: url(upload/background3.jpg);">
                <div class="wrap">
                    <div class="discover-content clearfix" style="margin-left: 60px; margin-top: 120px; margin-bottom: 80px; ">
                        <h1 style="color: #fff; 
  font-family: Courier, "Lucida Console", monospace;" >Here is a heading of medium importance </h1>
                        <p style="color: #fff; margin-top: 20px">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do <br /> eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut</p>
                        

                        <div class="buttons-Heading" style="margin-top: 20px; opacity: 0.99;">
                        <a href="#" class="button">Get Started</a>
                        <!-- <a href="#" class="button button-stripe">Learn more</a>  
                           // The Button Learn More   // -->
                    
                    </div>



                    </div>
                </div>
                </div>
            
            <!-- The div for the next content featured -->

            <!------------------------------------------>

            <div class="discover clearfix">
                    <div class="content clearfix">
                        <h4 style="font-weight: bold; margin-left: 12px;">HERE IS ANOTHER HEADING HERE. IMPORTANT STUFF</h4>
                        <p class="Lorem-Ipsum" style="margin-left: 12px; font-size: 16pt;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                        </p><br /><p style="margin-left: 10px; font-size: 13pt; font-family: Verdana;"> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut</p>
                        
                        </div>
                        <div class="content-image"><img src="upload/side-nav-img1.jpg" alt=""></div>
                    </div>
                   
                </div> 
                <!-- /.wrap -->
            </div>
            

            <!-- -------------------------------------- -->

            <!-- The next div content for more Info -->


                    <div class="discover clearfix" style="background: url(upload/background1.jpg);">
                <div class="Backboard" style="width: 100%; height: 300px;">
                    <div class="discover-content clearfix" style="background-color: hsla(283, 72%, 25%, 0.92); opacity: 0.90; margin-top: 30px; margin-bottom: 0px; width: 100%">
                        <h1 style="color: #fff; 
  font-family: Courier, "Lucida Console", monospace;" class="Contact-Header" >Contact us today </h1>
                        <p style="color: #fff; margin-top: 20px" class="Contact-Paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do <br /> eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut</p>
                        <div class="buttons-wrapper" style="margin-top: 20px; opacity: 0.99;">
                        <a href="#" class="button">Get Started</a>
                        <p style="font-size: 8pt; color: #fff; margin-left: 20px; margin-right: 30px;" class="button-Footer">Lorem ipsum dolor sit amet, consectetur</p>
                        <!-- <a href="#" class="button button-stripe">Learn more</a>  
                           // The Button Learn More   // -->
                    
                    </div>
                    </div>
                </div>
                </div>
            
            <!-- The div for the next content featured --> 
                            
                        </div>
                        
                    </div>
                </div>
                <!-- /.wrap -->
            </div>

            <!-- -------------------------------------- -->

                
                   <div class="More-Content">
            <div class="wrap">
                <img  style="border-radius: 68px; margin-top: 280px; margin-right: 240px;" src="upload/clientC.jpg" height="132" width="252" alt="" class="header-img">
                
                <div class="header-wrapper">
                <div class="buttons-wrapper">
                        <a href="#" style="border: 1px solid #fff;" class="button button-stripe">Photography</a>
                    </div>
                <br />
                    <h1>Design is not just what it looks and <br /> feels like. Design is how it works</h1>
                    <p class="autor"><a href="#">Vic Vineger, web developer</a></p>
                    
                </div>
                <!-- /.header-wrapper -->
            </div>
            <!-- /.wrap -->
        </div>

            <!-- Content Link to Student Alumni -->

            <!-- The Next div tag for content before footer One -->

              <div class="discover clearfix">
                <div class="wrap">
                    <div class="content1 clearfix">
                        <h4 style="font-weight: bold; margin-left: 12px;" class="Content-Div">IF YOU CAN BELIEVE IT IT'S ANOTHER HEADING</h4>
                        <p style="margin-left: 12px; font-size: 16pt;" class="Div-Paragraph1">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                        </p><br /><br /><p style="margin-left: 10px; font-family: Baskersville;" class="Div-Paragraph2"> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut consectetur adipisicing elit sed do.Lorem ipsum dolor.
</p>
                        </div>
                  </div>
                        <div class="Content-image2" style="float: right; margin-top: -313px; height: 458px; width: 49%;"><img src="upload/side-nav-img2.jpg" alt=""></div>
                </div>
                <!-- /.wrap -->
            </div>
           
             
            <!--- the End of the Content div -->
            
            <!-- The Footer One -->


           <div class="Footer-One">
        <div class="wrap">
             <h4>Get in touch</h4>
                            <br />
                            <p> consectetur adipisicing elit,<br> sed do.Lorem ipsum dolor<br>Lorem ipsum dolor sit amet,<br> sit amet, consectetur </p>
                            <br />
            
            
        
                
                            <a href="#">help@hackeryou.com</a>
            
           
																	
            <div class="Social">
            <a href="#" style="display:inline; margin-right: 5px; border:0;"><img src="upload/1.png" alt="" border="0" height="32" width="32"></a>
																	
																	<a href="#" style="display:inline; margin-right: 10px; border:0;"><img src="upload/2.png" alt="" border="0" height="32" width="32"></a>
																	<a href="#" style="display:inline; margin-right: 15px; border:0;"><img src="upload/3.png" alt="" border="0" height="32" width="32"></a>
																    <a href="#" style="display:inline; margin-right: 20px; border:0;"><img src="upload/4.png" alt="" border="0" height="32" width="32"></a>
                
            </div>
                        
        </div>
        <!-- /.wrap -->
               
              

    </div>

     <!-- The End -------------------->        
        
            <!-- The Footer Two ------------>
            
           <footer>
        <div class="wrap">
            <p>consectetur adipisicing elit, sed do.Lorem ipsum doloLorem ipsum dolor sit amet,r sit amet</p>
        </div>
        <!-- /.wrap -->
    </footer> <!-- The End -------------------->        
       
    </body>
</html>
