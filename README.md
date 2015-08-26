/*
Theme Name: chidltheme
Description: Thème enfant de chidltheme
Author: Sylvain MOREAU
Version: 1.0.0
Template: zerif-lite
*/
/*
Theme Name: Zerif Lite
Theme URI: http://themeisle.com/themes/zerif-lite/
Author: ThemeIsle
Author URI: http://themeisle.com
Description: Zerif LITE is a free one page Wordpress theme. It's perfect for web agency business,corporate business,personal and parallax business portfolio, photography sites and freelancer.Is built on BootStrap with parallax support, is responsive, clean, modern, flat and minimal. Zerif Lite is ecommerce (WooCommerce) Compatible, WPML, RTL, Retina-Ready, SEO Friendly and with parallax, full screen image is one of the best business themes.
Version: 1.8.2.2
License: GNU General Public License version 3
License URI: license.txt
Text Domain: zerif-lite
Domain Path: /languages/
Tags: black, gray, red, white, one-column, two-columns, right-sidebar,fixed-layout,light,front-page-post-form,full-width-template,rtl-language-support,sticky-post,theme-options,responsive-layout, custom-background, custom-menu, editor-style, featured-images, threaded-comments, translation-ready,photoblogging
*/


/*--------------------------------------------------------------
1.0 - Reset  
--------------------------------------------------------------*/
html {
	font-size: 62.5%; /* Corrects text resizing oddly in IE6/7 when body font-size is set using em units http://clagnut.com/blog/348/#c790 */
	overflow-y: scroll; /* Keeps page centered in all browsers regardless of content height */
	-webkit-text-size-adjust: 100%; /* Prevents iOS text size adjust after orientation change, without disabling user zoom */
	-ms-text-size-adjust:     100%; /* www.456bereastreet.com/archive/201012/controlling_text_size_in_safari_for_ios_without_disabling_user_zoom/ */
}
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, font, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td {
	border: 0;
	font-family: inherit;
	font-size: 16px;
	font-style: inherit;
	font-weight: inherit;
	margin: 0;
	outline: 0;
	padding: 0;
	vertical-align: baseline;
}
*,
*:before,
*:after { /* apply a natural box layout model to all elements; see http://www.paulirish.com/2012/box-sizing-border-box-ftw/ */
	-webkit-box-sizing: border-box; /* Not needed for modern webkit but still used by Blackberry Browser 7.0; see http://caniuse.com/#search=box-sizing */
	-moz-box-sizing:    border-box; /* Still needed for Firefox 28; see http://caniuse.com/#search=box-sizing */
	box-sizing:         border-box;
}
body {
	background: #fff;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
main,
nav,
section {
	display: block;
}
ol, ul {
	list-style: none;
}
table { /* tables still need 'cellspacing="0"' in the markup */
	border-collapse: separate;
	border-spacing: 0;
}
caption, th, td {
	font-weight: normal;
	text-align: left;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: "";
}
blockquote, q {
	quotes: "" "";
}
a:focus {
	outline: thin dotted;
}
a:hover,
a:active {
	outline: 0;
}
a img {
	border: 0;
}
body {
	font-family: 'Lato', sans-serif !important;
	font-size: 14px;
	color: #808080;
	font-weight: normal;
	overflow-x: hidden;
	line-height: 25px;
	text-align: center;
}
/* Internet Explorer 10 in Windows 8 and Windows Phone 8 Bug fix */
@-webkit-viewport {
	width: device-width;
}
@-moz-viewport {
	width: device-width;
}
@-ms-viewport {
	width: device-width;
}
@-o-viewport {
	width: device-width;
}
@viewport {
	width: device-width;
}
/* Other fixes*/
*,*:before,*:after {
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}
i {
	vertical-align: middle;
}
ul, ol {
padding-left: 0 !important;
}
/* Selection colours (easy to forget) */
::selection {
	background: #FC6D6D;
	color: #FFF;
}
::-moz-selection {
	background: #FC6D6D;
	color: #FFF;
}
a {
	color: #e96656;
	-webkit-transition: all 700ms;
	transition: all 700ms;
}
a,a:hover {
	text-decoration: none;
}
a:hover {
	color: #cb4332;
}
p {
    margin: 0;
}
.full-width {
	width: 100%;
	margin: auto;
}
/*--------------------------------------------------------------
2.0 Typography
--------------------------------------------------------------*/
body,
button,
input,
select,
textarea {
	color: #404040;
	font-family: sans-serif;
	font-size: 16px;
	font-size: 1.6rem;
	line-height: 1.5;
}
h1, h2, h3, h4, h5, h6 {
	clear: both;
}
p {
	margin-bottom: 1.5em;
}
b, strong {
	font-weight: bold;
}
dfn, cite, em, i {
	font-style: italic;
}
blockquote {
	margin: 0 1.5em;
}
blockquote {
	font-size: 18px;
	font-style: italic;
	font-weight: 300;
	margin: 24px 40px;
	line-height: 26px;
}
address {
	margin: 0 0 1.5em;
}
pre {
	background: #eee;
	font-family: "Courier 10 Pitch", Courier, monospace;
	font-size: 15px;
	font-size: 1.5rem;
	line-height: 1.6;
	margin-bottom: 1.6em;
	max-width: 100%;
	overflow: auto;
	padding: 1.6em;
}
code, kbd, tt, var {
	font: 15px Monaco, Consolas, "Andale Mono", "DejaVu Sans Mono", monospace;
}
abbr, acronym {
	border-bottom: 1px dotted #666;
	cursor: help;
}
mark, ins {
	background: #fff9c0;
	text-decoration: none;
}
sup,
sub {
	font-size: 75%;
	height: 0;
	line-height: 0;
	position: relative;
	vertical-align: baseline;
}
sup {
	bottom: 1ex;
}
sub {
	top: .5ex;
}
small {
	font-size: 75%;
}
big {
	font-size: 125%;
}
dl {
	margin: 0 20px;
}
h1, h2, h3, h4, h5, h6 {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
	margin-bottom: 10px;
	display: block;
	clear: both;
}
h1,h2 {
	font-family: 'Montserrat', 'sans-serif';
	font-weight: 700;
	line-height: 35px;
}
h1,
h1 span {
	font-size: 30px;
}
h2 {
	font-size: 26px;
}
h3 {
	font-size: 24px;
}
h4 {
	font-size: 18px;
}
h5 {
	font-size: 17px;
}
h6 {
	font-size: 16px;
}
/*--------------------------------------------------------------
3.0 Buttons
--------------------------------------------------------------*/
.buttons {
	text-align: center;
	margin-top: 45px;
}
.button {
	display: inline-block !important;
	text-align: center;
	text-transform: uppercase;
	padding: 10px 35px 10px 35px;
	border-radius: 4px;
	margin: 10px;
}
.custom-button {
	display: inline-block !important;
	text-align: center;
	text-transform: uppercase;
	padding: 13px 35px 13px 35px;
	border-radius: 4px;
	margin: 10px;
	border: none;
}
.red-btn {
	background: #e96656;
}
.green-btn {
	background: #20AA73;
}
.blue-btn {
	background: #3ab0e2;
}
.yellow-btn {
	background: #E7AC44;
}
.red-btn,.green-btn,.blue-btn,.yellow-btn {
	color: #FFF !important;
	-webkit-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}
.blue-btn:hover {
	color: #FFF;
	background: #1288b9;
}
.red-btn:hover {
	color: #FFF;
	background: #cb4332;
}
.green-btn:hover {
	color: #FFF;
	background: #069059;
}
.yellow-btn:hover {
	color: #FFF;
	background: #d8951e;
}
.btn:hover{
    box-shadow: none;
}
/*--------------------------------------------------------------
3.0 Elements
--------------------------------------------------------------*/
hr {
	background-color: #ccc;
	border: 0;
	height: 1px;
	margin-bottom: 1.5em;
}
ul, ol {
	margin: 0 0 1.5em 3em;
}
ul {
	list-style: disc;
}
ol {
	list-style: decimal;
}
li > ul,
li > ol {
	margin-bottom: 0;
	margin-left: 1.5em;
}
dt {
	font-weight: bold;
}
dd {
	margin: 0 1.5em 1.5em 0;
}
img {
	height: auto; /* Make sure images are scaled correctly. */
	max-width: 100%; /* Adhere to container width. */
}
figure {
	margin: 0;
}
.site-main p {
	margin: 0 0 24px;
}
table {
	border-bottom: 1px solid #ededed;
	border-collapse: collapse;
	border-spacing: 0;
	font-size: 14px;
	line-height: 2;
	margin: 0 0 20px;
	width: 100%;
}
caption,
th,
td {
	font-weight: normal;
	text-align: left;
}
caption {
	font-size: 16px;
	margin: 20px 0;
}
th {
	font-weight: bold;
	text-transform: uppercase;
	border-top: 1px solid #ededed;
	padding: 6px 10px 6px 0;
}
td {
	border-top: 1px solid #ededed;
	padding: 6px 10px 6px 0;
}
thead th{
	border: none;
}
/*---------------------------------------
 **   COLORS                         -----
-----------------------------------------*/
/** BACKGROUNDS **/
.red-bg {
	background: #e96656;
}
.green-bg {
	background: #34d293;
}
.blue-bg {
	background: #3ab0e2;
}
.yellow-bg {
	background: #E7AC44;
}
.dark-bg {
	background: #404040;
}
.white-bg {
	background:  #FFFFFF;
}
/** FOR TEXTS AND ICON FONTS **/
.red-text {
	color: #e96656;
}
.green-text {
	color: #34d293;
}
.blue-text {
	color: #3ab0e2;
}
.yellow-text {
	color: #f7d861;
}
.dark-text {
	color: #404040;
}
.white-text {
	color: #FFFFFF;
}
/*---------------------------------------
 **   BORDER BOTTOMS                 -----
-----------------------------------------*/
.white-border-bottom:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 50%;
	height: 2px;
	background: #F5F5F5;
	bottom: -9px;
	left: 25%;
}
.dark-border-bottom:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 50%;
	height: 2px;
	background: #404040;
	bottom: -9px;
	left: 25%;
}
.red-border-bottom:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 75%;
	height: 2px;
	background: #e96656;
	bottom: -9px;
	left: 12.5%;
}
.green-border-bottom:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 75%;
	height: 2px;
	background: #34d293;
	bottom: -9px;
	left: 12.5%;
}
.blue-border-bottom:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 75%;
	height: 2px;
	background: #3ab0e2;
	bottom: -9px;
	left: 12.5%;
}
.yellow-border-bottom:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 75%;
	height: 2px;
	background: #f7d861;
	bottom: -9px;
	left: 12.5%;
}
/*---------------------------------------
 **   4.0 Forms                     -----
-----------------------------------------*/
button,
input,
select,
textarea {
	font-size: 100%; /* Corrects font size not being inherited in all browsers */
	margin: 0; /* Addresses margins set differently in IE6/7, F3/4, S5, Chrome */
	vertical-align: baseline; /* Improves appearance and consistency in all browsers */
	*vertical-align: middle; /* Improves appearance and consistency in IE6/IE7 */
}
button,
input[type="button"],
input[type="reset"],
input[type="submit"] {
	text-align: center;
	text-transform: uppercase;
	padding: 13px 35px 13px 35px;
	border-radius: 4px;
	margin: 10px;
	border: none;
	background-color: #e96656;
	box-shadow: none;
	text-shadow: none;
	font-weight: 400;
	vertical-align: middle;
	cursor: pointer;
	white-space: nowrap;
	font-size: 14px;
	color: #FFF;
}
button:hover,
input[type="button"]:hover,
input[type="reset"]:hover,
input[type="submit"]:hover {
	border-color: #ccc #bbb #aaa #bbb;
	box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.8), inset 0 15px 17px rgba(255, 255, 255, 0.8), inset 0 -5px 12px rgba(0, 0, 0, 0.02);
}
button:focus,
input[type="button"]:focus,
input[type="reset"]:focus,
input[type="submit"]:focus,
button:active,
input[type="button"]:active,
input[type="reset"]:active,
input[type="submit"]:active {
	border-color: #aaa #bbb #bbb #bbb;
	box-shadow: inset 0 -1px 0 rgba(255, 255, 255, 0.5), inset 0 2px 5px rgba(0, 0, 0, 0.15);
}
input[type="checkbox"],
input[type="radio"] {
	padding: 0; /* Addresses excess padding in IE8/9 */
}
input[type="search"] {
	-webkit-appearance: textfield; /* Addresses appearance set to searchfield in S5, Chrome */
	-webkit-box-sizing: content-box; /* Addresses box sizing set to border-box in S5, Chrome (include -moz to future-proof) */
	-moz-box-sizing:    content-box;
	box-sizing:         content-box;
}
input[type="search"]::-webkit-search-decoration { /* Corrects inner padding displayed oddly in S5, Chrome on OSX */
	-webkit-appearance: none;
}
button::-moz-focus-inner,
input::-moz-focus-inner { /* Corrects inner padding and border displayed oddly in FF3/4 www.sitepen.com/blog/2008/05/14/the-devils-in-the-details-fixing-dojos-toolbar-buttons/ */
	border: 0;
	padding: 0;
}
input[type="text"],
input[type="email"],
input[type="url"],
input[type="password"],
input[type="search"],
textarea {
	color: #555;
	border: 1px solid rgba(0, 0, 0, 0.1);
	border-radius: 0;
}
input[type="text"]:focus,
input[type="email"]:focus,
input[type="url"]:focus,
input[type="password"]:focus,
input[type="search"]:focus,
textarea:focus {
	color: #111;
}
input[type="text"],
input[type="email"],
input[type="url"],
input[type="password"],
input[type="search"] {
	padding: 3px;
}
textarea {
	overflow: auto; /* Removes default vertical scrollbar in IE6/7/8/9 */
	padding-left: 3px;
	vertical-align: top; /* Improves readability and alignment in all browsers */
	width: 98%;
}
.entry-content button,
.entry-content input[type="button"],
.entry-content input[type="reset"],
.entry-content input[type="submit"] {
	padding: 5px 20px 5px 20px;
}
.entry-content button:hover,
.entry-content input[type="button"]:hover,
.entry-content input[type="reset"]:hover,
.entry-content input[type="submit"]:hover {
	background: #cb4332;
}
.input-box {
	border: 0 !important;
	width: 274px;
	text-align: left;
	text-transform: none;
	padding: 9px;
	min-height: 46px;
	padding-left: 15px !important;
	display: inline-block;
	border-radius: 4px;
	background: rgba(255,255,255, 0.95);
}
.textarea-box {
	border: 0;
	text-align: left;
	text-transform: none;
	padding: 9px;
	min-height: 250px;
	padding-left: 15px;
	display: inline-block;
	border-radius: 4px;
	background: rgba(255,255,255, 0.95);
}
textarea:hover,
input:hover,
textarea:active,
input:active,
textarea:focus,
input:focus {
    outline: 1 !important;
    outline-color: #e96656 !important;

  -webkit-box-shadow:none !important;
  box-shadow:none !important;
}
 /*---------------------------------------
 **   5.0 Navigation                 -----
-----------------------------------------*/
 /*---------------------------------------
 **   5.1 Links                 -----
-----------------------------------------*/
a {
	color: #e96656;
}
a:visited {
	color: #e96656;
}
a:hover,
a:focus,
a:active {
	color: #cb4332;
}
/*---------------------------------------
 **   5.2 Menus                  -----
-----------------------------------------*/
.main-navigation {
	clear: both;
	display: block;
	float: left;
	width: 100%;
}
.main-navigation ul {
	list-style: none;
	margin: 0;
	padding-left: 0;
}
.main-navigation li {
	float: left;
	position: relative;
}
.main-navigation a {
	display: block;
	text-decoration: none;
}
.main-navigation ul ul {
	box-shadow: 0 3px 3px rgba(0, 0, 0, 0.2);
	display: none;
	float: left;
	left: 0;
	position: absolute;
	top: 1.5em;
	z-index: 99999;
}
.main-navigation ul ul ul {
	left: 100%;
	top: 0;
}
.main-navigation ul ul a {
	width: 200px;
}
.main-navigation ul ul li {
}
.main-navigation li:hover > a {
}
.main-navigation ul ul :hover > a {
}
.main-navigation ul ul a:hover {
}
.main-navigation ul li:hover > ul {
	display: block;
}
.main-navigation .current_page_item a,
.main-navigation .current-menu-item a {
}
.navbar-collapse{
	overflow: visible !important;
}
/* Small menu */
/*
.menu-toggle {
	cursor: pointer;
	display: none;
}
@media screen and (max-width: 600px) {
	.menu-toggle,
	.main-navigation.toggled .nav-menu {
		display: block;
	}
	.main-navigation ul {
		display: none;
	}
}
*/
.site-main .comment-navigation,
.site-main .paging-navigation,
.site-main .post-navigation {
	margin: 0 0 1.5em;
	overflow: hidden;
}
.comment-navigation .nav-previous,
.paging-navigation .nav-previous,
.post-navigation .nav-previous {
	float: left;
}
.comment-navigation .nav-next,
.paging-navigation .nav-next,
.post-navigation .nav-next {
	float: right;
	text-align: right;
	width: 50%;
}
.nav-links a {
	color:#e96656;
}
.site-main .post-navigation {
	float: left;
	width: 100%;
}
 /*---------------------------------------
 **   6.0 Accessibility                   -----
-----------------------------------------*/
/* Text meant only for screen readers */
.screen-reader-text {
	clip: rect(1px, 1px, 1px, 1px);
	position: absolute !important;
}
.screen-reader-text:hover,
.screen-reader-text:active,
.screen-reader-text:focus {
	background-color: #f1f1f1;
	border-radius: 3px;
	box-shadow: 0 0 2px 2px rgba(0, 0, 0, 0.6);
	clip: auto !important;
	color: #21759b;
	display: block;
	font-size: 14px;
	font-weight: bold;
	height: auto;
	left: 5px;
	line-height: normal;
	padding: 15px 23px 14px;
	text-decoration: none;
	top: 5px;
	width: auto;
	z-index: 100000; /* Above WP toolbar */
}
 /*---------------------------------------
 **   7.0 Alignments                   -----
-----------------------------------------*/
.alignleft {
	display: inline;
	float: left;
	margin-right: 1.5em;
}
.alignright {
	display: inline;
	float: right;
	margin-left: 1.5em;
}
.aligncenter {
	clear: both;
	display: block;
	margin: 0 auto;
}
 /*---------------------------------------
 **   8.0 Clearings                   -----
-----------------------------------------*/
.clear:before,
.clear:after,
.entry-content:before,
.entry-content:after,
.comment-content:before,
.comment-content:after,
.site-header:before,
.site-header:after,
.site-content:before,
.site-content:after,
.site-footer:before,
.site-footer:after {
	content: '';
	display: table;
}
.clear:after,
.entry-content:after,
.comment-content:after,
.site-header:after,
.site-content:after,
.site-footer:after {
	clear: both;
}
 /*---------------------------------------
 **   9.0 Widgets                   -----
-----------------------------------------*/
.sidebar-wrap {
	border-left: 1px solid rgba(0, 0, 0, 0.05);
}
.widget {
	/*margin: 0 0 1.5em;
	margin-bottom: 30px;*/
}
.widget .widget-title {
	color: #404040;
	text-transform: uppercase;
	margin-bottom: 30px;
	font-weight: bold;
	font-size: 17px;
	position: relative;
	text-align: left;
	margin-top: 30px;
	padding-bottom: 5px;
	float: none;
}
.widget .widget-title:before{
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 35%;
	height: 2px;
	background: #e96656;
	bottom: -9px;
	left: 0;
}

.widget-area {
	float: left;
	width: 100%;
}
.widget-area .widget {
	clear: both;
}
/* Make sure select elements fit in widgets */
.widget select {
	max-width: 100%;
	width: 100%;
	padding: 10px;
	border: 1px solid #e9e9e9;
}
.tagcloud a{
	background: #FCFCFC;

	padding: 2px 5px;
}
/* Search widget */
.widget_search .search-submit {
/*	display: none; */
	display: block;
	width: 46px;
	height: 46px;
	position: absolute;
	top: 0;
	right: 0;
	padding: 0;
	margin: 0;
	background: url(images/search_icon.png) no-repeat center center;
	text-indent: -99999999999px;
}
.widget_search label{
	margin-bottom: 5px;
	width: 100%;
	position: relative;
}
.widget_search form{
	position: relative;
}
.widget_search input{
	width: 83%;
	padding: 12px 15% 12px 2%;
}
.widget ul {
	margin:0;
	padding:0;
	display: block;
}
.widget li {
	list-style: none;
	margin: 15px 0;
	text-align: left;
	margin-left: 3%;
	position: relative;
	padding-left: 10px;
}
.widget li:before{
	content: '';
	width: 4px;
	height: 4px;
	background: #e9e9e9;
	float: left;
	position: absolute;
	margin-top: 11px;
	left: 0;
}
.widget li a {
	color:#808080;
}
.widget li a:hover {
	color:#404040
}
 /*---------------------------------------
 **   10.0 Content                   -----
-----------------------------------------*/

.container>.navbar-header, 
.container-fluid>.navbar-header, 
.container>.navbar-collapse, 
.container-fluid>.navbar-collapse {
    margin-right: 0;
    margin-left: 0;
}
.site-content {
	background: #FFF;
}
.home .site-content {
	background: none;
}

 /*---------------------------------------
 **   10.1 Posts and pages                   -----
-----------------------------------------*/
.sticky {
}
.hentry {
	margin: 0 0 1.5em;
}
.byline,
.updated {
	display: none;
}
.single .byline,
.group-blog .byline {
	display: inline;
}
.entry-meta-large .byline,
.entry-meta-large .updated {
	display: none;
}
.page-content,
.entry-content,
.entry-summary {
	margin: 1.5em 0 0;
}
.page-links {
	clear: both;
	margin: 0 0 1.5em;
}
.page-header{
	text-align: left;
	border-bottom: none;
	margin: 0px 0 40px;
}
.search-results .page-header {
	margin: 0px 0 40px;
}
.page-header .page-title{
	position: relative;
}
.page-header .page-title:before{
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 35%;
	height: 2px;
	background: #e9e9e9;
	bottom: -9px;
	left: 0;
}
.taxonomy-description{
	margin-top:  15px;
}
.entry-title{
	position: relative;
}
.entry-title:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 10%;
	height: 2px;
	background: #e96656;
	bottom: -9px;
	left: 0;
}
.entry-meta{
	margin-top: 10px;
}
 /*---------------------------------------
 **   10.2 Asides                   -----
-----------------------------------------*/
.blog .format-aside .entry-title,
.archive .format-aside .entry-title {
	display: none;
}
 /*---------------------------------------
 **   10.3 Comments                   -----
-----------------------------------------*/
.comment {
	list-style:none;
	margin-top:10px;
	margin-bottom:10px;
}
.comment a {
	color:#c7254e;
}
.comment-body {
	text-align: left;
	border-bottom: 1px solid rgba(0, 0, 0, 0.05);
	padding-bottom: 10px;
	position: relative;
	padding-left: 40px;
}
.comment-content a {
	word-wrap: break-word;
}
.bypostauthor {
}
.comment-form, .comments-title, .comment-reply-title {
	text-align:left;
}
.comment .reply a {
	font-size: 12px;
}
.comment-form p {
	margin:10px 10px 10px 0;
}
.comment-form  label {
	width:85px;
}
.comments-title {
	font-size:20px;
	margin-bottom:20px;
}
.comment-list {
	margin-left:0px;
}
.comment-list li{
	list-style: none;
	float: left;
	width: 100%;
}
.comment-reply-link {
	border: 1px solid #ccc;
	border-radius: 3px;
	font-size: 1.2rem;
	line-height: 1;
	padding: .6em 1em .4em;
	text-shadow: 0 1px 0 rgba(255, 255, 255, 0.8);
	font-family: sans-serif;
	box-shadow:inset 0 1px 0 rgba(255, 255, 255, 0.5), inset 0 15px 17px rgba(255, 255, 255, 0.5), inset 0 -5px 12px rgba(0, 0, 0, 0.05);
	box-shadow: none;
	text-shadow: none;
	padding: 3px 5px;
	position: absolute;
	top: 0;
	right: 0;
}
.comment-form #submit, .comment-reply-link {
	background:#e96656;
	border-color:#e96656;
	color:#fff !important;
}
.comment-form #submit:hover {

	background: #cb4332;
}
.comment-meta{

	margin-top: 0 !important;
	padding-top: 0 !important;
}
.comment-metadata{
	position: absolute;
	top: -2px;
	right: 55px;
}
.comment-metadata,
.comment-metadata a{
	color: #bdbdbd;
	font-style: italic;
	font-size: 12px;
	padding: 3px 0px;
}
.comment-reply-link:hover{
	background: #cb4332;
	box-shadow: none;
}
.comment-author img{
	border-radius: 50%;
	position: absolute;
	left: 0;
}
.comment-author b.fn{
	color: #000;
}
 /*---------------------------------------
 **   11.0 Infinite scroll                    -----
-----------------------------------------*/
/* Globally hidden elements when Infinite Scroll is supported and in use. */
.infinite-scroll .paging-navigation, /* Older / Newer Posts Navigation (always hidden) */
.infinite-scroll.neverending .site-footer { /* Theme Footer (when set to scrolling) */
	display: none;
}
/* When Infinite Scroll has reached its end we need to re-display elements that were hidden (via .neverending) before */
.infinity-end.neverending .site-footer {
	display: block;
}
 /*---------------------------------------
 **   12.0 Media                    -----
-----------------------------------------*/
.page-content img.wp-smiley,
.entry-content img.wp-smiley,
.comment-content img.wp-smiley {
	border: none;
	margin-bottom: 0;
	margin-top: 0;
	padding: 0;
}
.wp-caption {
	border: 1px solid #ccc;
	margin-bottom: 1.5em;
	max-width: 100%;
}
.wp-caption img[class*="wp-image-"] {
	display: block;
	margin: 1.2% auto 0;
	max-width: 98%;
}
.wp-caption-text {
	text-align: center;
}
.wp-caption .wp-caption-text {
	margin: 0.8075em 0;
}
.site-main .gallery {
	margin-bottom: 1.5em;
}
.gallery-caption {
}
.site-main .gallery a img {
	border: none;
	height: auto;
	max-width: 90%;
}
.site-main .gallery dd,
.site-main .gallery figcaption {
	margin: 0;
}
.site-main .gallery-columns-4 .gallery-item {
}
.site-main .gallery-columns-4 .gallery-item img {
}
/* Make sure embeds and iframes fit their containers */
embed,
iframe,
object {
	max-width: 100%;
}
 /*---------------------------------------
 **   6.5 Gallery                    -----
-----------------------------------------*/
.gallery {
	margin-bottom: 20px;
}
.gallery-item {
	float: left;
	margin: 0 4px 4px 0;
	overflow: hidden;
	position: relative;
}
.gallery-columns-1 .gallery-item {
	max-width: 100%;
}
.gallery-columns-2 .gallery-item {
	max-width: 48%;
	max-width: -webkit-calc(50% - 4px);
	max-width:         calc(50% - 4px);
}
.gallery-columns-3 .gallery-item {
	max-width: 32%;
	max-width: -webkit-calc(33.3% - 4px);
	max-width:         calc(33.3% - 4px);
}
.gallery-columns-4 .gallery-item {
	max-width: 23%;
	max-width: -webkit-calc(25% - 4px);
	max-width:         calc(25% - 4px);
}
.gallery-columns-5 .gallery-item {
	max-width: 19%;
	max-width: -webkit-calc(20% - 4px);
	max-width:         calc(20% - 4px);
}
.gallery-columns-6 .gallery-item {
	max-width: 15%;
	max-width: -webkit-calc(16.7% - 4px);
	max-width:         calc(16.7% - 4px);
}
.gallery-columns-7 .gallery-item {
	max-width: 13%;
	max-width: -webkit-calc(14.28% - 4px);
	max-width:         calc(14.28% - 4px);
}
.gallery-columns-8 .gallery-item {
	max-width: 11%;
	max-width: -webkit-calc(12.5% - 4px);
	max-width:         calc(12.5% - 4px);
}
.gallery-columns-9 .gallery-item {
	max-width: 9%;
	max-width: -webkit-calc(11.1% - 4px);
	max-width:         calc(11.1% - 4px);
}
.gallery-columns-1 .gallery-item:nth-of-type(1n),
.gallery-columns-2 .gallery-item:nth-of-type(2n),
.gallery-columns-3 .gallery-item:nth-of-type(3n),
.gallery-columns-4 .gallery-item:nth-of-type(4n),
.gallery-columns-5 .gallery-item:nth-of-type(5n),
.gallery-columns-6 .gallery-item:nth-of-type(6n),
.gallery-columns-7 .gallery-item:nth-of-type(7n),
.gallery-columns-8 .gallery-item:nth-of-type(8n),
.gallery-columns-9 .gallery-item:nth-of-type(9n) {
	margin-right: 0;
}
.gallery-columns-1.gallery-size-medium figure.gallery-item:nth-of-type(1n+1),
.gallery-columns-1.gallery-size-thumbnail figure.gallery-item:nth-of-type(1n+1),
.gallery-columns-2.gallery-size-thumbnail figure.gallery-item:nth-of-type(2n+1),
.gallery-columns-3.gallery-size-thumbnail figure.gallery-item:nth-of-type(3n+1) {
	clear: left;
}
.gallery-caption {
	background-color: rgba(0, 0, 0, 0.7);
	-webkit-box-sizing: border-box;
	-moz-box-sizing:    border-box;
	box-sizing:         border-box;
	color: #fff;
	font-size: 12px;
	line-height: 1.5;
	margin: 0;
	max-height: 50%;
	opacity: 0;
	padding: 6px 8px;
	position: absolute;
	bottom: 0;
	left: 0;
	text-align: left;
	width: 100%;
}
.gallery-caption:before {
	content: "";
	height: 100%;
	min-height: 49px;
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
}
.gallery-item:hover .gallery-caption {
	opacity: 1;
}
.gallery-columns-7 .gallery-caption,
.gallery-columns-8 .gallery-caption,
.gallery-columns-9 .gallery-caption {
	display: none;
}
.gallery-item img{
	max-width: 100% !important;
}
/*---------------------------------------
 **   Header               -----
-----------------------------------------*/
/*** SECTION HEADERS ***/
.focus,.works,.about-us,.features,.packages,.products,.testimonial,.contact-us {
	padding-top: 100px;
}
.section-header {
	text-align: center;
	padding-bottom: 75px;
}
.section-header h2 {
	padding-bottom: 10px;
	line-height: 40px;
	position: relative;
	display: inline-block;
	font-size: 45px;
	text-transform: uppercase;
	margin-top: 15px;
	margin-bottom: 0;
}
.section-header h6 {
	font-size: 16px;
	margin-bottom: 0;
	color: #808080;
	padding-top: 0;
}
/* PRE LOADER */
.preloader {
	position: fixed;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	background-color: #fefefe;
	z-index: 99999;
	height: 100%;
	width: 100%;
	overflow: hidden !important;
}
.status {
	width: 200px;
	height: 200px;
	position: absolute;
	left: 50%;
	top: 50%;
	background-image: url(images/loading.gif);
	background-repeat: no-repeat;
	background-position: center;
	margin: -100px 0 0 -100px;
}
/*---------------------------------------
 **   Section: Home                  -----
-----------------------------------------*/
.header.header {
	min-height: 76px;
}
.header.header > .navbar {
	-webkit-box-shadow: 0px 5px 11px 0px rgba(50, 50, 50, 0.08);
	box-shadow: 0px 5px 11px 0px rgba(50, 50, 50, 0.08);
}
.header-content-wrap {
	background: rgba(0, 0, 0, 0.5);
	position: relative;
	-webkit-box-shadow: 0px 5px 11px 0px rgba(50, 50, 50, 0.08);
	box-shadow: 0px 5px 11px 0px rgba(50, 50, 50, 0.08);
	padding: 285px 0 210px;
}
.header_title {
    float: left;
    height:50px;
    margin-top:10px;
}
.header_title h1{
    font-size: 20px;
    line-height: 20px;
    margin-bottom: 5px;
    text-align: center;
    margin-top: 5px;
}
.header_title h2{
	font-size:15px !important;
	line-height:15px;
    margin: 0;
}
.header_title a {
	color:#000;
}
/*----  SECTION:  HOME > TOP BAR   ----*/
 #site-navigation {
 	height: 1px;
	float: right;
	margin-right: 0;
	margin-left: 0;

}
.navbar {
	background: #FFF;
	border: 0;
	border-radius: 0 !important;
	text-align: left;
}
#main-nav {
	position: fixed;
	width: 100%;
	z-index: 1000;
	min-height: 75px;
	margin-bottom: 0;
}
#main-nav.fixed {
	position: fixed;
	top: 0;
}
.navbar-inverse .navbar-nav {
	margin-left: 0;
	margin-right: 0;
}
.navbar-inverse .navbar-nav >li {
	display: inline;
	margin-right: 20px;
	margin-top: 20px;
}
.navbar-inverse .navbar-nav>li:last-child {
	margin-right: 0 !important;
}
.navbar-inverse .navbar-nav>li>a {
	color: #404040;
	padding: 0;
	line-height: 35px;
}
.navbar-inverse .main-navigation ul > li {
	display: inline;
	margin-right: 20px;
	margin-top: 20px;
}
.navbar-inverse .main-navigation > ul > li:last-child {
	margin-right: 0 !important;
}
.navbar-inverse .main-navigation > ul > li > a {
	color: #404040;
	padding: 0;
	line-height: 35px;
}
.navbar-inverse .navbar-nav ul.sub-menu {
	display: none;
	position: absolute; top: 100%;
	background:#fff;
	width:200px;
	box-shadow: 3px 3px 2px rgba(50, 50, 50, 0.08);
	z-index: 9999;
}
.navbar-inverse .navbar-nav ul.sub-menu {
	margin:0;
}
.navbar-inverse .navbar-nav ul.sub-menu ul.sub-menu{
	position: absolute;
	left:100%;
	top:0;
}
.navbar-inverse .navbar-nav ul.sub-menu li {
	float: none;
	position: relative;
	list-style:none;
	padding:10px;
}
.navbar-inverse .navbar-nav ul.sub-menu li a {
	color:#404040;
}
.navbar-inverse .navbar-nav ul.sub-menu li:hover > a {
	color:#e96656;
}
.navbar-inverse .navbar-nav li:hover > ul.sub-menu {
	display: block;
}

.navbar-brand {
	height: 76px;
	position: relative;
	line-height: 60px;
	padding: 7px 15px;
	display: inline-block;
}
.navbar-brand > img {
	max-height: 100%;
}
.navbar-inverse .navbar-nav>li>a:hover {
	color: #e96656;
	outline: none;
}
.navbar-toggle {
	border: 0;
	background-color: #808080;
	margin-top: 23px;
}
.navbar-inverse .navbar-toggle:hover,.navbar-inverse .navbar-toggle:focus {
	background-color: #e96656;
	filter: alpha(opacity=100);
	opacity: 1;
	box-shadow: none;
}
.navbar-toggle.active{
    background-color: #e96656 !important;
}
.navbar-toggle.collapsed{
    background-color: #808080 !important;
}
.menu-align-center #site-navigation {
	width: 100%;
}
.menu-align-center #site-navigation > ul {
	width: 100%;
	text-align: center;
}
.menu-align-center #site-navigation > ul ul {
	text-align: left;
}
.menu-align-center #site-navigation > ul > li {
	float: none;
	display: inline-block;
}
.menu-align-center .responsive-logo {
	width: 100%;
	text-align: center;
}
.menu-align-center .zerif_header_title {
	width: 100%;
}
.menu-align-center .navbar-inverse .navbar-nav > li {
	margin-top: 0;
	margin-bottom: 0;
}
.menu-align-center .responsive-logo > a{
	float: none;
	display: inline-block;
}
.navbar-inverse .navbar-nav>li>a:hover, 
.navbar-inverse .navbar-nav>li>a:focus {
	color: #e96656;
}
.navbar-inverse .navbar-nav>li.current>a {
	color: #e96656;
	position: relative;
	outline: none;
}
ul.nav > li.menu-item-home > a:before {
	content: "";
	display: none;
}
li.current>a:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 75%;
	height: 2px;
	background: #e96656;
	bottom: 0px;
	left: 12.5%;
}
ul.nav > li.current_page_item > a:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 75%;
	height: 2px;
	background: #e96656;
	bottom: 0px;
	left: 12.5%;
	display: block;
}
ul.nav > li.current_page_item.menu-item-home > a:before {
	content: "";
	display: none;
}
ul.nav > li.current_page_item.current > a:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 75%;
	height: 2px;
	background: #e96656;
	bottom: 0px;
	left: 12.5%;
	display: block;
}


/*----  SECTION:  HOME > INTRO AND SHORT MSGS   ----*/
.intro {
	text-align: center;
	color: #FFF;
	margin-top: 25%;
	line-height: 65px;
	z-index: 0;
	text-transform: uppercase;
	font-size: 55px;
	float:none;
}
.intro-text{
	text-align: center;
	color: #FFF;
	line-height: 65px;
	z-index: 0;
	text-transform: uppercase;
	font-size: 55px;
	float:none;
}
/* Short Messages */
.bottom-message-section {
	margin-top: 14%;
	position: relative;
}
.short-text {
	margin: auto;
	text-align: center;
	color: rgba(255,255,255,0.7);
	text-transform: uppercase;
}
/*----  SECTION:  HOME > LATEST NEWS   ----*/
.latest-news {
	padding-bottom: 66px;
	padding-top: 100px;
	background: #FFFFFF;
}
.carousel-inner {
/*	margin: 0 30px; */
}
#carousel-homepage-latestnews .item{
	height: auto;
}
.latesnews-content p,
.latesnews-content {
	font-size: 14px;
	line-height: 18px;
	color: #909090;
}
#carousel-homepage-latestnews .carousel-inner .item .latestnews-title {
	margin-bottom: 15px;
	color: #404040;
	position: relative;
	display: inline-block;
	text-transform: uppercase;
	margin-bottom: 30px;
	font-weight: bold;
	font-size: 17px;
	float: none;
	width: auto;
	margin-top: 15px;
}
#carousel-homepage-latestnews .carousel-inner .item .latestnews-title a {
	text-transform: uppercase;
	color: #404040;
	font-weight: 700;
	display: block;
}
#carousel-homepage-latestnews .item .latestnews-box .latestnews-title a:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 75%;
	height: 2px;
	background: #e96656;
	bottom: -9px;
	left: 12.5%;
}
#carousel-homepage-latestnews .item .latestnews-box:nth-child(4n+1) .latestnews-title a:before {
	background: #e96656;
}
#carousel-homepage-latestnews .item .latestnews-box:nth-child(4n+2) .latestnews-title a:before {
	background: #34d293;
}
#carousel-homepage-latestnews .item .latestnews-box:nth-child(4n+3) .latestnews-title a:before {
	background: #3ab0e2;
}
#carousel-homepage-latestnews .item .latestnews-box:nth-child(4n) .latestnews-title a:before {
	background: #f7d861;
}
#carousel-homepage-latestnews {
	margin: 0 30px;
}
#carousel-homepage-latestnews .carousel-control {
	width: 45px;
	background: none;
}
.carousel-control.left {
	margin-left: -45px;
}
.carousel-control.right {
	margin-right: -45px;
}
#carousel-homepage-latestnews .glyphicon-chevron-left:before{
	content: "";
	background: url(images/left-arrow.png) no-repeat center center;
	width: 30px;
	height: 30px;
	float: left;
}
#carousel-homepage-latestnews .glyphicon-chevron-right:before{
	content: "";
	background: url(images/right-arrow.png) no-repeat center center;	
	width: 30px;
	height: 30px;
	float: left;
}
#carousel-homepage-latestnews {
}

/*---------------------------------------
 **   Section: Our focus             -----
-----------------------------------------*/
.focus-box .service-icon .pixeden  {
	border-radius: 50%;
}
.focus {
	padding-bottom: 100px;
	overflow: hidden;
	background: #FFFFFF;

}
.focus .row {
 	text-align:center;
}
.focus .row .focus-box, .our-team .row .team-box {
 	display:inline-block;
 	float:none !important;	
 	margin-right: -4px;
	vertical-align: top;
	margin-bottom: 25px;
}
/* FOCUS BOX */
.focus-box .service-icon {
	margin-bottom: 30px;
	width: 145px;
	height: 145px;
	margin: auto;
	border-radius: 50%;
	border: 10px solid #ececec;
	margin-bottom: 20px;
	position: relative;
	-webkit-transition: all 0.2s ease-in-out;
	transition: all 0.2s ease-in-out;
}
/* ON HOVER COLORED ROUNDED CIRCLE AROUND ICONS */
/* ON HOVER COLORED ROUNDED CIRCLE AROUND ICONS */
.red,.green,.blue,.yellow {
	-webkit-transition: all 0.2s ease-in-out;
	transition: all 0.2s ease-in-out;
}
.focus-box:nth-child(4n+1) .service-icon:hover {
	border: 10px solid #e96656;
}
.focus-box:nth-child(4n+2) .service-icon:hover{
	border: 10px solid #34d293;
}
.focus-box:nth-child(4n+3) .service-icon:hover {
	border: 10px solid #3ab0e2;
}
.focus-box:nth-child(4n+4) .service-icon:hover{
	border: 10px solid #f7d861;
}
.focus-box:nth-child(4n+1) .red-border-bottom:before {
	background: #e96656;
}
.focus-box:nth-child(4n+2) .red-border-bottom:before {
	background: #34d293;
}
.focus-box:nth-child(4n+3) .red-border-bottom:before {
	background: #3ab0e2;
}
.focus-box:nth-child(4n+4) .red-border-bottom:before {
	background: #f7d861;
}
.focus-box h5 {
	margin-bottom: 15px;
	color: #404040;
	position: relative;
	display: inline-block;
	text-transform: uppercase;
	margin-bottom: 30px;
	font-weight: bold;
	font-size: 17px;
	float: none;
    width: auto;
    background: none;
}
.focus-box p {
	font-size: 14px;
	color: #808080;
}
/*----OTHER FOCUSES ----*/
.other-focuses {
	background: url(images/lines.png) repeat-x center;
	margin-bottom: 25px;
}
.other-focuses .section-footer-title {
	padding: 0 15px;
	color: #404040;
	font-weight: bold;
}
.other-focus-list {
	padding-top: 5px;
	margin-bottom: -17px;
}
.other-focus-list ul li {
	display: inline-block;
	margin-right: 50px;
	padding-bottom: 15px;
	text-transform: uppercase;
}
.other-focus-list ul li:last-child {
	margin-right: 0;
}
.other-focus-list ul li i {
	margin-right: 8px;
}
/*---------------------------------------
 **   Secction:  Separator one        -----
-----------------------------------------*/
.separator-one {
	background: rgba(52, 210, 147, 0.8);
	padding: 100px 0 100px 0;
}
.separator-one .green-btn {
	background: #14a168;
}
.separator-one .green-btn:hover {
	background: #007345;
}
.separator-one .text {
	color: #FFF;
	line-height: 34px;
	padding: 0;
	max-width: 800px;
	margin-bottom: 20px;
	margin-top: 15px;
}
/*---------------------------------------
 **   Section: Portfolio          -----
-----------------------------------------*/
.works {
	padding-bottom: 100px;
	background: #FFFFFF;
	min-height: 800px;
}
/* IMAGE GRID */
.cbp-rfgrid {
	margin: auto;
	padding: 0;
	list-style: none;
	position: relative;
	width: 100%;
}
.cbp-rfgrid li {
	position: relative;
	float: left;
	overflow: hidden;
	width: 25%; /* Fallback */
width: -webkit-calc(100% / 4);
	width: calc(100% / 4);
	-webkit-transition: 0.4s all linear;
	transition: 0.4s all linear;
}
.cbp-rfgrid li a,.cbp-rfgrid li a img {
	display: block;
	max-width: 100%;
	-webkit-transform: scale(1,1);
	-ms-transform: scale(1,1);
	transform: scale(1,1);
	-webkit-transition-timing-function: ease-in;
	transition-timing-function: ease-in;
	-webkit-transition-duration: 250ms;
	transition-duration: 250ms;
	cursor: pointer;
	-webkit-transition: 0.4s all linear;
	transition: 0.4s all linear;
	width: 100%;
}
.cbp-rfgrid li a:hover img {
	-webkit-transform: scale(1.05,1.07);
	-ms-transform: scale(1.05,1.07);
	transform: scale(1.05,1.07);
	-webkit-transition-timing-function: ease-out;
	transition-timing-function: ease-out;
	-webkit-transition-duration: 250ms;
	transition-duration: 250ms;
}
/* Flexbox is used for centering the heading */
.cbp-rfgrid li a .project-info {
	position: absolute;
	left: 10px;
	top: 10px;
	right: 10px;
	bottom: 10px;
	background: rgba(0,0,0,0.5);
	padding-top: 25%;
	text-align: center;
	filter: alpha(opacity=0);
	opacity: 0;
	-webkit-transition: all ease .25s;
	transition: all ease .25s;
}
.cbp-rfgrid li a .project-info .project-details {
	position: relative;
	top: -29px;
	filter: alpha(opacity=0);
	opacity: 0;
	-webkit-transition: all ease .25s;
	transition: all ease .25s;
	width: 100%;
}
.cbp-rfgrid li a .project-info h5 {
	position: relative;
	display: inline-block;
	margin-bottom: 15px;
	margin-top: 15px;
	font-weight: bold;
	text-transform: uppercase;
}
.cbp-rfgrid li a:hover .project-info {
	filter: alpha(opacity=100);
	opacity: 1;
}
.cbp-rfgrid li a:hover .project-details {
	filter: alpha(opacity=100);
	opacity: 1;
	top: 0;
}
.cbp-rfgrid li a:hover .button {
	filter: alpha(opacity=100);
	opacity: 1;
	bottom: -50px;
}
.cbp-rfgrid li.cbp-rfgrid-open a .project-info {
	filter: alpha(opacity=100);
	opacity: 1;
}
.cbp-rfgrid-tr {
	position: absolute;
	top: 0;
	width: 100%;
	height: 100%;
	margin-bottom: 0;
	z-index: 9;
}
.cbp-rfgrid li.cbp-rfgrid-open a .project-info .project-details {
	top: 0;
	opacity: 1;
}
/* media queries:  change number of items per row */
@media screen and (max-width: 1190px) {
	.cbp-rfgrid li {
		width: 25%; /* Fallback */
		width: -webkit-calc(100% / 4);
		width: calc(100% / 4);
	}
}
@media screen and (max-width: 1024px) {
	.cbp-rfgrid li {
		width: 33.33333333333333%; /* Fallback */
		width: -webkit-calc(100% / 3);
		width: calc(100% / 3);
	}
}
@media screen and (max-width: 768px) {
	.cbp-rfgrid li {
		width: 50%; /* Fallback */
		width: -webkit-calc(100% / 2);
		width: calc(100% / 2);
	}
}
@media screen and (max-width: 480px) {
	.cbp-rfgrid li {
		width: 100%;
	}
}
@media screen and (max-width: 300px) {
	.cbp-rfgrid li {
		width: 100%;
	}
}
/* PROJECT DETAILS LOADER */
#back-button {
	display: none;
	text-align: center;
	text-transform: uppercase;
	padding: 13px 35px 13px 35px;
	border-radius: 4px;
	margin: 10px;
}
#back-button i {
	margin-right: 10px;
}
#loader {
	min-height: 930px;
	position: relative;
	display: none;
}
#loader .loader-icon {
	background: url(images/loading.gif) no-repeat center center;
	background-color: #FFF;
	margin: -22px -22px;
	top: 50%;
	left: 50%;
	z-index: 10000;
	position: fixed;
	width: 44px;
	height: 44px;
	-webkit-background-size: 30px 30px;
	background-size: 30px 30px;
	border-radius: 5px;
}
/*---------------------------------------
 **   Section: Abot us;              -----
-----------------------------------------*/
.about-us {
	background: #272727;
	color: #FFF;
	padding-bottom: 100px;
}
.about-us .row {
	margin-left: -15px;
	margin-right: -15px;
}
.about-us .big-intro {
	text-align: right;
	font-weight: 300;
	font-size: 60px;
	line-height: normal;
	margin-top: -15px;
}
.about-us .section-header h6 {
	color: #FFF;
}
.about-us p {
	text-align: left;
	color: #939393;
	font-size: 14px;
	line-height: 25px;
}
.about-us .column {
	margin-bottom: 78px;
}
/*--SKILLS --*/
.skills {
	text-align: left;
	margin: 0 0 0 0;
}
.skills .skill {
	display: block;
	clear: both;
	margin-top: 0;
	margin-bottom: 25px;
}
.skills .skill .skill-count {
	display: inline-block;
	height: 64px;
	margin-top: 3px;
	float: left;
	margin-right: 15px;
	margin-bottom: 25px;
}
.skills li:last-child {
	margin-bottom: 0;
}
.skills .skill .skill1,.skill2,.skill3,.skill4 {
	font-size: 16px !important;
}
.skills .skill h6 {
	text-transform: uppercase;
	font-weight: 700;
	clear: none;
	width: auto;
	float: none;
	margin-top: 0;
	margin-bottom: 0;
}
.skills .skill p {
	line-height: 20px;
	font-size: 14px;
	color: #8f8f8f;
}
/*--OUR CLIENTS --*/
.our-clients {
	background: url(images/lines-dark.png) repeat-x center;
	margin-bottom: 40px;
    float: left;
    width: 100%;
}
.our-clients .section-footer-title {
	background: #272727;
	padding: 0 15px;
	color: #FFF;
}
.our-clients h5 {
	font-weight: 700;
	float:none;
	margin-top: 0;
	margin-bottom: 0
}
.client-list {
	padding-top: 5px;
	margin-bottom: -17px;
}
.client-list ul{
	margin: 0;
}
.client-list ul li {
	vertical-align: middle;
	display: inline-block;
	margin-right: 24px;
	padding-bottom: 15px;
	text-transform: uppercase;
}
.client-list ul li img {
	max-width: 130px;
	-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=80)";
	filter: alpha(opacity=80);
	opacity: 0.8;
	-webkit-transition: all ease .55s;
	transition: all ease .55s;
}
.client-list ul li img:hover {
	-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=100)";
	filter: alpha(opacity=100);
	opacity: 1;
}
.client-list ul li:last-child {
	margin-right: 0;
}
.client-list ul li i {
	margin-right: 8px;
}
.client-list div{
	margin: 0;
}
.client-list div a{
    margin-right: 24px;
}
.client-list div a:last-child{
    margin-right: 0;
}
.client-list div img {
	max-width: 130px;
	-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=80)";
	filter: alpha(opacity=80);
	opacity: 0.8;
	-webkit-transition: all ease .55s;
	transition: all ease .55s;
	padding-bottom: 15px;
}
.client-list div img:hover {
	-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=100)";
	filter: alpha(opacity=100);
	opacity: 1;
}
.client-list div a:last-child {
	margin-right: 0;
}
/*---------------------------------------
 **   Section: stats                 -----
-----------------------------------------*/
.stats {
	background: rgba(0, 0, 0, 0.5);
	padding: 100px 0 60px 0 !important;
	clear: both;
}
.stat {
	margin-bottom: 40px;
}
.stat .icon-top {
	font-size: 40px;
	height: 50px;
	line-height: 50px;
}
.stat .stat-text {
	display: inline-block;
	position: relative;
}
.stat h3 {
	margin-top: 20px;
	padding-bottom: 5px;
	position: relative;
	display: inline-block;
}
.stat h6 {
	color: #d1d1d1;
	margin-top: 15px;
}
/*---------------------------------------
 **   Section: Our team;              -----
-----------------------------------------*/
.our-team {
	padding-bottom: 66px;
	padding-top: 100px;
	background: #FFFFFF;
}
.team-member {
	border-radius: 4px;
	overflow: hidden;
	position: relative;
	margin-bottom: 35px;
}
.team-member .details {
	text-align: left;
	font-size: 13px;
	line-height: 20px;
	position: absolute;
	padding: 15px;
	top: -200px;
	left: 0;
	width: 100%;
	height: 190px;
	-webkit-transition: all 500ms;
	transition: all 500ms;
	-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=0)";
	filter: alpha(opacity=0);
	opacity: 0;
}
.team-member .member-details {
	position: relative;
	display: inline-block;
	padding-bottom: 5px;
}
.team-member:hover .details {
	top: 0;
	background: #333;
	color: white;
	-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=100)";
	filter: alpha(opacity=100);
	opacity: 1;
}
.team-member.team-member-open .details {
	display: block;
	top: 0;
	background: #333;
	color: white;
	-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=100)";
	filter: alpha(opacity=100);
	opacity: 1;
	-webkit-transition: none;
	-moz-transition: none;
	-o-transition: none;
	transition: none;
}
.team-member .profile-pic {
	border-radius: 50%;
	width: 174px;
	height: 174px;
	margin: auto;
	overflow: hidden;
	margin-bottom: 25px;
}
.team-member .profile-pic img {
	width: 100%;
	height: 100%;
}
.team-member h5 {
	text-transform: uppercase;
	color: #404040;
	font-weight: 700;
	position: relative;
	margin-top: 15px;
}
.team-member .position {
	font-size: 13px;
}
.team-member .social-icons {
	margin-bottom: 25px;
}
.team-member .social-icons ul {
	margin: 0 0 1.5em 0;
}
.team-member .social-icons ul li {
	display: inline-block;
	line-height: 32px;
	margin: 6px;
}
.team-member .social-icons ul li a {
	background: #FFF;
	font-size: 18px;
	border-radius: 50%;
	color: #808080;
}
.team-member .social-icons ul li a:hover {
	color: #e96656;
}
.our-team .row > div:nth-child(4n+1) .red-border-bottom:before{
    background: #e96656;
}
.our-team .row > div:nth-child(4n+2) .red-border-bottom:before{
    background: #34d293;
}
.our-team .row > div:nth-child(4n+3) .red-border-bottom:before{
    background: #3ab0e2;
}
.our-team .row > div:nth-child(4n+4) .red-border-bottom:before{
    background: #f7d861;
}

/*---------------------------------------
 **   Features            -----
-----------------------------------------*/
.features {
	background: #FFFFFF;
	text-align: left;
	padding-bottom: 51px;
}
.features .feature {
	margin-bottom: 55px;
}
.features .feature-icon {
	font-size: 55px;
	float: left;
	margin-top: 10px;
	margin-right: 25px;
}
.features .feature h5 {
	font-weight: bold;
	line-height: 28px;
	color: #404040;
}
.features .feature p {
	font-size: 14px;
}
/*---------------------------------------
 **   Pacages               -----
-----------------------------------------*/
.packages {
	padding-bottom: 50px;
	background: rgba(0, 0, 0, 0.5);
}
.package {
	border-radius: 4px;
	background: #FFFFFF;
	margin-top: 25px;
	margin-bottom: 50px;
	padding-bottom: 15px;
}
.package-header {
	height: 57px;
	color: #FFF;
	line-height: 57px;
	border-top-left-radius: 4px;
	border-top-right-radius: 4px;
}
.package-header h5 {
	text-transform: uppercase;
	font-weight: bold;
}
.price {
	line-height: 120px;
	height: 100px;
	color: #FFF;
	font-weight: 400;
}
.price h4 {
	display: inline;
	font-size: 40px;
	line-height: normal;
	margin-bottom: 0;
}
.price h4 .dollar-sign {
	font-size: 17px;
	vertical-align: super;
}
.price .price-meta {
	line-height: normal;
	text-transform: uppercase;
	color: #9f9f9f;
}
.package ul li {
	padding-top: 10px;
	padding-bottom: 10px;
	width: 80%;
	margin: auto;
	border-bottom: 1px dotted #dadada;
}
.package ul li:last-child {
	border-bottom: 0;
}
.best-value .package {
	margin-top: 0;
}
.best-value .package-header {
	padding-top: 17px;
	height: 82px !important;
}
.best-value .package-header h4 {
	font-weight: bold;
	line-height: 29px;
	text-transform: uppercase;
}
.best-value .package-header .meta-text {
	font-size: 13px;
	line-height: normal;
}
.best-value .package-header {
	height: 72px;
}
.package ul li i {
	font-size: 13px;
	margin-right: 5px;
}
.order {
	background: #d8ccba;
	color: #404040;
}
.package .order-now {
	line-height: 45px;
	max-width: 100%;
	display: block;
	background: #404040;
	color: #FFF;
	-webkit-transition: all 700ms;
	transition: all 700ms;
	border-bottom-right-radius: 4px;
	border-bottom-left-radius: 4px;
}
.package .order-now:hover {
	background: #e96656;
}
/*---------------------------------------
**   Producs            -----
-----------------------------------------*/
.products .color-overlay {
	background: rgba(39,144,176, 0.96);
	margin-top: -100px;
	padding-top: 100px;
	padding-bottom: 70px;
}

/*---ITEM STYLE ---*/
.item {
	width: 100%;
	height: 260px;
	display: block;
	-webkit-background-size: 100%;
	background-size: 100%;
	position: relative;
	margin: auto;
	margin-bottom: 30px;
	z-index: 5;
	-webkit-backface-visibility: hidden;
	overflow: hidden;
	border-radius: 4px;
}
.item-overlay {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	overflow: hidden;
	-webkit-transition: background-color 0.3s ease-in-out;
	transition: background-color 0.3s ease-in-out;
}
.item-content {
	position: absolute;
	width: 100%;
	bottom: 0;
	-webkit-transform: translate(0,100%);
	-ms-transform: translate(0,100%);
	transform: translate(0,100%);
	-webkit-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}
.item:hover .item-content {
	-webkit-transform: translate(0,0);
	-ms-transform: translate(0,0);
	transform: translate(0,0);
	-webkit-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}
.item-top-content {
	position: relative;
}
.item-top-content-inner {
	position: absolute;
	bottom: 0;
	padding: 10px 15px 10px 15px;
	background: rgba(255,255,255,.95);
	width: 100%;
}
.item-add-content {
	padding: 0 15px 15px 15px;
	-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=0)";
	filter: alpha(opacity=0);
	opacity: 0;
	-webkit-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}
.item:hover .item-add-content {
	-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=100)";
	filter: alpha(opacity=100);
	opacity: 1;
}
.item-add-content-inner {
	border: 0px solid #dadada;
	border-top-width: 1px;
	padding-top: 10px;
}
.item-top-title {
	text-align: left;
}
.item-top-title h5 {
	color: #404040;
	font-weight: 700;
}
/* ITEM DETAILS */
.item-product {
	width: 70%;
	float: left;
}
.item-product-price {
	width: 30%;
	float: right;
	text-align: right;
}
.subdescription {
	font-size: 14px;
	font-weight: 400;
	color: #7d7d7d;
}
/*---PRODUCT PRICE---*/
.item-product-price {
	font-size: 1em;
	font-weight: 700;
	position: relative;
}
.item-product-price .subdescription {
	color: #808080;
}
.old-price {
	border: 0 solid #808080;
	border-bottom-width: 1px;
	margin-top: -11px;
	width: 30px;
	position: absolute;
	right: -2px;
	bottom: 10px;
	-webkit-transform: rotate(-30deg);
	-ms-transform: rotate(-30deg);
	transform: rotate(-30deg);
}
/*---ITEM DESCRIPTION ---*/
.item-content {
	background: rgba(255,255,255,.85);
}
.item-add-content {
	font-weight: 400;
	color: #808080;
}
.item-add-content .section {
	margin-bottom: 10px;
}
.item-add-content .section:last-of-type {
	margin-bottom: 0;
}
.item-add-content p {
	font-size: 14PX;
}
/*---------------------------------------
 **   Newsletter           -----
-----------------------------------------*/
.newsletter {
	padding-top: 62px;
	padding-bottom: 62px;
	background: rgba(0, 0, 0, 0.5);
}
.newsletter h3 {
	font-size: 28px;
	text-transform: uppercase;
	font-family: 'Montserrat', sans-serif;
	font-weight: 700;
	margin-bottom: 8px;
}
.newsletter .subscription {
	margin-top: 15px;
}
.newsletter .custom-button {
    margin-top: 7px;
}
/*----------------------------------------
 **   Testionial           -----
-----------------------------------------*/
.testimonial {
	background: #dbbf56;
	padding-bottom: 90px;
}
.testimonial .section-header h6 {
	color: #FFF;
}
#client-feedbacks .feedback-box {
	width: 30%;
	float:left;
	background: #FFFFFF;
	padding: 25px;
	margin: 13px;
	text-align: left;
	border-radius: 4px;
	-webkit-box-shadow: none;
	box-shadow: none;
	display: block;
	z-index: 5;
}
.feedback-box .message {
	font-size: 15px;
	color: #909090;
}
.feedback-box .client {
	margin-top: 30px;
	height: 73px;
	position: relative;
}
.feedback-box .quote {
	float: left;
	font-size: 45px;
	line-height: 80px;
}
.feedback-box .client-info {
	float: left;
	margin-left: 18px;
	padding-top: 15px;
}
.feedback-box .client-info .client-name {
	font-family: 'Homemade Apple', serif;
	color: #404040;
}
.feedback-box .client-info .client-company {
	font-size: 13px;
	margin-top: -3px;
}
.feedback-box .client-image {
	float: right;
	width: 73px;
	height: 73px;
	border-radius: 50%;
	overflow: hidden;
	border: 3px solid #f6f6f6;
}
.feedback-box .client-image img {
	width:100%;
	height:100%;
}
.customNavigation {
	text-align: center;
}
.owl-theme .owl-controls .owl-page span {
	background: #886e0e;
	border-radius: 50%;
}
.customNavigation a {
	-webkit-user-select: none;
	-moz-user-select: none;
	-ms-user-select: none;
	user-select: none;
	-webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
/*----------------------------------------
 **   Purchase now           -----
-----------------------------------------*/
.purchase-now {
	background: #e96656;
	padding-top: 70px;
	padding-bottom: 70px;
}
.purchase-now h3 {
	text-align: left;
	line-height: 40px;
	margin-top: 14px;
}
.purchase-now .red-btn {
	float: right;
	background: #db5a4a;
}
.purchase-now .red-btn:hover {
	background: #bf3928;
}
.ribbon-without-button h3 {
	text-align: center;
}
.ribbon-without-button .col-md-9 {
	width: 100%;
}

/*----------------------------------------
 **   Contact us             -----
-----------------------------------------*/
.contact-us {
	background: rgba(0, 0, 0, 0.5);
	padding-bottom: 95px;
}
.contact-us .section-header h6 {
	color: #FFF;
}
.contact-us .input-box,textarea {
	width: 100%;
	margin: auto;
	margin-bottom: 20px;
	border-radius: 4px;
}
.contact-us .custom-button {
	float: right;
	margin-right: 15px;
}
.g-recaptcha {
	margin-left: 15px;
	display: none;
}
.contact-us .notification p {
	border-radius: 3px;
	color: #FFF;
	padding: 5px 10px;
	display: inline-block;
	margin-bottom: 10px;
}
.contact-us .error p {
	background: #E96656;
}
.contact-us .success p {
	background: #34d293;
}

/*---------------------------------------
 **   Footer           -----
-----------------------------------------*/
#footer {
	background: #272727;
	line-height: 20px;
}
.company-details {
	color: #939393;
	padding-top: 67px;
	padding-bottom: 30px;
}
.company-details a {
	color:#939393;
	text-decoration:none;
}

.company-details a:hover {
	color: #e96656;
}
.company-details .icon-top {
	font-size: 30px;
	margin-bottom: 10px;
}
.copyright {
	padding-top: 68px;
	padding-bottom: 68px;
	background: #171717;
}
.social {
	margin: 0 0 1.5em 0 !important;
}
.social li {
	display: inline-block;
	margin: 5px;
}
.social li a {
	color: #939393;
	font-size: 18px;
}
.social li a:hover {
	color: #e96656;
}
.copyright p {
	margin-bottom: 0;
	color: #939393;
}
/*---------------------------------------
 **   Single page           -----
-----------------------------------------*/
.single-project {
	text-align: left;
	margin-bottom: 25px;
}
.single-project .project-image {
	width: 100%;
	float: left;
	text-align: left;
	margin-bottom: 25px;
}
.single-project h3 {
	margin-bottom: 10px;
	padding-bottom: 7px;
	line-height: 40px;
	border-bottom: 1px dotted #dadada;
}
.single-project .project-description {
	margin-bottom: 25px;
}
.single-project .button {
	margin-left: 0;
}
.single-project .project-information {
	margin-bottom: 10px;
}
.single-project .project-information ul li {
	border-bottom: 1px dotted #dadada;
	padding-bottom: 5px;
	margin-top: 10px;
}
.single-project .project-information ul li span {
	font-weight: 700;
	margin-right: 5px;
}
/*---------------------------------------
 **   Section blog            -----
-----------------------------------------*/
.blog {
	min-height: 175px;
	position: relative;
	overflow: hidden;
}
.blog-list{
	background: #FFF;
}
.post-img-wrap{
	float: left;
	margin-right: 20px;
	display: inline-block;
	overflow: hidden;
}
.post-img-wrap a{
}
.post-img-wrap a img{
	width: 200px;
	height: auto;
	-webkit-transform: scale(1);
	-moz-transform: scale(1);
	-o-transform: scale(1);
	-ms-transform: scale(1);
	transform: scale(1);
	-webkit-transition: all 0.3s ease-out;
	-moz-transition: all 0.3s ease-out;
	-ms-transition: all 0.3s ease-out;
	-o-transition: all 0.3s ease-out;
	transition: all 0.3 ease-out;
}
.post-img-wrap a:hover img{
	-webkit-transform: scale(1.1);
	-moz-transform: scale(1.1);
	-o-transform: scale(1.1);
	-ms-transform: scale(1.1);
	transform: scale(1.1);
	-webkit-transition: all 0.5s ease-out;
	-moz-transition: all 0.5s ease-out;
	-ms-transition: all 0.5s ease-out;
	-o-transition: all 0.5s ease-out;
	transition: all 0.5 ease-out;
}
article.hentry{
	float: left;
	width: 100%;
	margin-bottom: 30px;
	padding-bottom: 30px;
	border-bottom: 1px solid rgba(0, 0, 0, 0.05);
}
article.sticky{
	background: #f9f9f9;
	padding: 10px;
}
article{
	text-align: left;
}
article .entry-meta a{
	color :#bdbdbd;
	font-style: italic;
}
article .posted-on a:hover{
	color: #e96656;
}
.entry-footer a{
	color :#bdbdbd;
	font-style: italic;
}
.entry-footer a:hover{
	color: #e96656;
}
.entry-title,
.entry-title a,
.widget-title,
.widget-title a{
	font-size: 20px;
	line-height: 22px;
	color: #404040;
}
.entry-title a:hover{
	color: #e96656;;
}
.clear{
	clear: both;
}
.content-left-wrap{
	padding-top: 60px;
}
.sidebar-wrap.content-left-wrap{
	margin-top: 60px;
	padding-top: 0;
}
.debar-wrap {
	margin-top: 50px;
}
.listpost-content-wrap{
}
.listpost-content-wrap h1.entry-title,
.list-post-top h1.entry-title {
	float: none;
	clear: none;
	margin-top: 0;
}
.listpost-content-wrap .entry-title:before {
	display: none;
	content: "";
}
.listpost-content-wrap .entry-title a:after {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 35%;
	height: 2px;
	background: #e96656;
	bottom: -9px;
	left: 0;
	width: 50px;
}
.post .entry-footer {
}
.listpost-content-wrap h1.entry-title a {
	float: none;
	position: relative;
}
.listpost-content-wrap-full{
	width: 100%;
}
.listpost-content-wrap-full .list-post-top{
	min-height: 1px;
}
.entry-title{
	font-size: 20px;
	margin-top: 0;
	padding-top: 0;
}
.listpost-content-wrap .entry-content {
	margin-top: 1em;
}
.listpost-content-wrap .entry-footer {
	padding-top: 10px;
}
.listpost-content-wrap-full .entry-footer > span,
.listpost-content-wrap .entry-footer > span {
	padding-right: 15px;
}
.listpost-content-wrap .entry-content p {
	min-height: 90px;
	margin-bottom: 0
}
.entry-content{
	line-height: 20px;
}
.list-post-top{
	min-height: 130px;
}
.search .list-post-top{
	min-height: 1px;
}
.entry-footer{
	background: transparent;
}
.entry-footer-large a{
	color :#8b8b8b;
	font-style: italic;
}
.entry-footer-large a:hover{
	color: #e96656;
}
.entry-footer-large{
	background: transparent;
	padding: 0 0 20px 0px;
	position: relative;
	padding-right: 200px;
	float: left;
	width: 100%;
}
.entry-footer-large > span {
	padding-right: 5px;
}
.entry-footer-large-left {
	float: left;
}
.large-container .entry-content p {
	margin: 4px 20px 0px 0px;
	text-align: justify;
}
.entry-content{
	margin: 1em 0 0;
}
.row{
    float: left;
    width: 100%;
    margin-right: 0;
    margin-left: 0;
}
/* Calendar style */
/* Calendar Widget */
.widget_calendar table,
.widget_calendar td {
	border: 0;
	border-collapse: separate;
	border-spacing: 1px;
}
.widget_calendar caption {
	font-size: 14px;
	margin: 0;
	margin-bottom: 6px;
}
.widget_calendar th,
.widget_calendar td {
	padding: 0;
	text-align: center;
}
.widget_calendar a {
	display: block;
	background: #f9f9f9;
	color: #e96656;
}
.widget_calendar a:hover {
	background-color: #e96656;
	color: #FFF;
}
.widget_calendar tbody td {
	background-color: #f9f9f9;
}
.site-footer .widget_calendar tbody td {
	background-color: rgba(255, 255, 255, 0.05);
}
.widget_calendar tbody .pad, .site-footer .widget_calendar tbody .pad {
	background-color: transparent;
}
.widget_calendar thead th{
	background: #e9e9e9;
	border: none;
}

/* ====================== Large TEMPLATE ============================== */
.entry-meta-large{
	float: right;
	position: absolute;
	right: 0;
	top: 0
}
.entry-content p {
	text-align:justify;
}
.post-img-wrap-large a img{
	max-width: 100%;
	width: 100%;
	height: auto;
	-webkit-transform: scale(1);
	-moz-transform: scale(1);
	-o-transform: scale(1);
	-ms-transform: scale(1);
	transform: scale(1);
	-webkit-transition: all 0.3s ease-out;
	-moz-transition: all 0.3s ease-out;
	-ms-transition: all 0.3s ease-out;
	-o-transition: all 0.3s ease-out;
	transition: all 0.3 ease-out;	
}
.listpost-content-wrap-large{
	position: absolute;
	bottom: 0px;
	background: rgba(255, 255, 255, 0.9) none repeat scroll 0% 0%;
	min-height: 50px;
	width: 100%;
	padding: 15px 20px 0px 20px;
	border-top: 2px solid #FFF;
}
.large-container {
	background-color: #fff;
	border-radius:4px;
	margin: 0 0 35px 0;
	position: relative;
	width: 95%;
	float: left;
}
.large-container .list-post-top {
	min-height: 130px;
}

/* woocommerce v2.3.5 */
*:focus {
    outline: 0;
}
.woocommerce-page .page-description {
	text-align: justify;
	margin-top: 20px;
	float: left;
}
.woocommerce-page h1.page-title {
	text-align:left;
	position: relative;
	font-size: 20px;
	font-size: 20px;
	line-height: 22px;
	color: #404040;
}
.woocommerce-page .page-title:before {
	position: absolute;
	margin: auto;
	z-index: 1;
	content: "";
	width: 10%;
	height: 2px;
	background: #e96656;
	bottom: -9px;
	left: 0;
}
.woocommerce span.onsale {
	width: 55px;
	height: 55px;
	border: 4px solid #34d293;
	border-radius: 50%;
	background: rgba(255,255,255,0.9);
	text-shadow: none;
	text-transform: uppercase;
	padding: 0px;
	position: absolute;
	line-height: 46px;
	font-size: 13px;
	color: #000;
	left: -20px;
	top: -20px;	
}
.woocommerce ul.products li.product .onsale{
	left: -20px;
	top: -20px;	
}
.woocommerce-page .woocommerce-ordering select {
	padding: 12px 15px 12px 10px;
	color: #A0A0A0;
	border: 1px solid rgba(0, 0, 0, 0.1);
	border-radius: 0;
}	
.woocommerce-page .products .product > a:first-child {
	position: relative;
	text-align: center;
/*	min-height: 385px; */
	display: block;
}
.woocommerce-page .products a.button {
	background: #e96656;
	display: inline-block;
	text-align: center;
	text-transform: uppercase;
	padding: 10px 20px 10px 20px;
	border-radius: 4px;
	margin: 10px;
	border: none;
	color: #FFF;
	font-size: 12px;
	margin: 0;
}
.woocommerce-page .products a.button:hover {
	background: #cb4332;
}
.woocommerce-page .products h3 {
	color: #404040;
	position: relative;
	display: inline-block;
	text-transform: uppercase;
	margin-bottom: 30px;
	font-weight: bold;
	font-size: 12px;
	line-height: 14px;
	float: none;
	width: auto;
	min-height: 42px;
	margin: 0;
}
.woocommerce-page .products a .price {
	color: #000 ;
	line-height: 20px;
	width: 100%;
	float: left;
	height: auto;
	min-height: 40px;
	text-align: center;
	padding: 10px 0;
}
.woocommerce-page .products a .price del {
	display: block;
	line-height: 20px;
}
.woocommerce ul.products li.product .price {
	color: #000;
}
.woocommerce-page .products a .price ins {
	display: block;
	color: #e96656;
	font-weight: bold;
	background: none;
	line-height: 20px;
}
.woocommerce-page .products .star-rating {
	position: relative;
	width: 100px;
	height: 20px;
	text-indent: 99999px;
	position: relative;
	overflow: hidden;
	background: url(images/woostars.png);
	background-repeat: no-repeat;
	background-position: top left;
	margin: 0 auto;
}
.woocommerce-page .products .star-rating span {
	position: absolute;
	top: 0;
	left: 0;
	width: 100px;
	height: 20px;
	background: url(images/woostars.png);
	background-repeat: no-repeat;
	background-position: bottom left;
	overflow: hidden;
	padding: 1px;
}
.woocommerce-page .products .price {
	padding: 5px 0;
}
.woocommerce-page .products .added_to_cart {
	display: inline-block;
	text-align: center;
	text-transform: uppercase;
	padding: 10px 20px 10px 20px;
	border-radius: 4px;
	border: none;
	color: #E96656;
	font-size: 12px;
	margin: 0;
}
.woocommerce-page .woocommerce-result-count {
	float: left;
	font-size: 14px;
	line-height: 46px;
	margin-top: 20px;
}
.woocommerce-page .woocommerce-ordering {
	float: right;
	margin-top: 20px;
}
.woocommerce-page .product-type-simple {
	position: relative;
}
.woocommerce-page .product .images {
	float: left;
	width: 50%;
}
.woocommerce-page .product .entry-summary {
	float: right;
	width: 50%;
	padding-left: 5%;
	margin-top: 0;
}
.woocommerce-page .product .quantity {
	float: left;
	margin-bottom: 15px;
	display: block;
}
.woocommerce-page .product .quantity input {
	border: 1px solid #CCC;
	width: 78px;
	padding: 5px;
	border-radius: 3px;
}
.woocommerce-page #content .quantity input.minus {
	width: 15px;
	height: 15px;
	border: none;
	margin-left: 0px;
	position: relative;
	float: left;
	background: #cccccc;
	padding: 0;
	color: #FFF;
	text-shadow: none;
	position: absolute;
	top: 15px;
	right: 5px;
}
.woocommerce-page #content .quantity input.plus {
	width: 15px;
	height: 15px;
	border: none;
	margin-left: 0px;
	position: relative;
	float: left;
	background: #cccccc;
	padding: 0;
	color: #FFF;
	text-shadow: none;
	position: absolute;
	top: 0;
	right: 5px;
}
.woocommerce #content .quantity, .woocommerce .quantity, .woocommerce-page #content .quantity, .woocommerce-page .quantity {
	position: relative;
}
.woocommerce #content .quantity input.qty, 
.woocommerce .quantity input.qty, 
.woocommerce-page #content .quantity input.qty, 
.woocommerce-page .quantity input.qty {
	height: 30px;
}
.woocommerce-page .quantity.buttons_added {
	width: auto;
}
.woocommerce-page .product .product_meta a {
	color: #e96656;
}
.woocommerce-page .product_title {
	text-align: left;
	margin-top: 0;
}
.woocommerce-page .product .price {
	text-align: left;
	padding: 30px 0;
	margin-bottom: 0;
}
.woocommerce-page .product div[itemprop="description"] {
	float: left;
	text-align: justify;
}
.woocommerce-page .product .stock ,
.woocommerce-page .product .cart,
.woocommerce-page .product .product_meta {
	float: left;
	text-align: left;
	clear: left;
}
.woocommerce-page .product .cart .button {
	margin: 0;
	margin-bottom: 25px;
	clear: left;
	float: left;
}
.woocommerce-page .product .cart .button:hover {
	background: rgb(203, 67, 50);
	box-shadow: none;
}
.woocommerce-page .product .images .thumbnails {
	width: 100%;
}
.woocommerce-page .product .images .thumbnails a {
	float: left;
	display: inline-block;
}
.woocommerce-page .woocommerce-tabs {
	float: left;
	width: 100%;
	margin-top: 50px; 
}
.woocommerce-page .woocommerce-tabs .tabs {
	padding: 0;
	margin: 0;
	border-bottom: 2px solid #CCC;
}
.woocommerce-page .woocommerce-tabs .tabs li {
	list-style: none;
	display: inline-block;
	padding: 10px 20px;
	margin-bottom: -2px;
}
.woocommerce-page .woocommerce-tabs .tabs li.active {
	border-bottom: 2px solid #e96656;
}
.woocommerce-page .woocommerce-tabs .tabs li.active a,
.woocommerce-page .woocommerce-tabs .tabs li a:hover {
	color: #e96656;
	text-decoration: none;
}
.woocommerce-page .woocommerce-tabs .tabs li a{
	color: rgb(64, 64, 64);
	font-size: 18px;
}
.woocommerce-page .woocommerce-tabs .entry-content {
	text-align: justify;
	margin-bottom: 50px;
	box-shadow: none;
}
.woocommerce-page h3.comment-reply-title {
	min-height: auto;
}
.woocommerce-page .product .price {
	color: #000;
	line-height: 20px;
	width: 100%;
	float: left;
	height: auto;
	min-height: 40px;
}
.woocommerce div.product p.price {
	color: #000;
}
.woocommerce-page .product .price del {
	display: block;
	line-height: 20px;
}
.woocommerce-page .product .price ins {
	display: block;
	color: #e96656;
	font-weight: bold;
	background: none;
	line-height: 20px;
}
.woocommerce-page .product .comment-form input {
	border-radius: 3px;
}
.woocommerce-page .product .comment-form input[type="submit"] {
	margin-left: 0;
}
.woocommerce-page .product .comment-form label {
	width: auto;
	line-height: 32px;
	float: left;
}
.woocommerce-page .product .comment-form .comment-form-rating label {
	line-height: 20px;
}
.woocommerce-page .product .comment-form-author label,
.woocommerce-page .product .comment-form-email label {
	width: 100px;
}

.woocommerce-page .product .comment-form .star-rating{
	float: right;
	width: 100px;
	height: 20px;
	background: url(images/woostars.png) repeat-x left bottom;
} 
.woocommerce-page .product .comment-form .star-rating span{
	background: url(images/woostars.png) repeat-x left top;
	height: 0;
	padding-top: 16px;
	overflow: hidden;
	float: left;
} 
.woocommerce-page .product .comment-form .hreview-aggregate .star-rating{
	margin: 10px 0 0 0;
} 
.woocommerce-page .product .comment-form #review_form #respond{
	position: static;
	margin: 0;
	width: auto;
	padding: 0 0 0;
	background: transparent none;
	border: 0;
} 
.woocommerce-page .product .comment-form #review_form #respond:after{
	content:""; 
	display: block;
	clear: both;
} 
.woocommerce-page .product .comment-form #review_form #respond p {
	margin: 0 0 10px;
} 
.woocommerce-page .product .comment-form #review_form #respond .form-submit input{
	left: auto;
} 
.woocommerce-page .product .comment-form #review_form #respond textarea {
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
	width: 100%;
} 
.woocommerce-page .product .comment-form p.stars:after{
	content: "";
	display: block;
	clear: both;
} 
.woocommerce-page .product .comment-form p.stars span{
	width: 100px;
	height: 20px;
	position: relative;
	float: left;
	background: url(images/woostars.png) repeat-x left 0;
	margin-left: 10px;
} 
.woocommerce-page .product .comment-form p.stars span a {
	float: left ;
	position: absolute;
	left: 0;
	top: 0;
	width: 20px;
	height: 0;
	padding-top: 20px;
	overflow: hidden;
} 
.woocommerce-page .product .comment-form p.stars span a:hover,
.woocommerce-page .product .comment-form p.stars span a:focus{
	background: url(images/woostars.png) repeat-x left bottom;
	-webkit-transition: initial;
	-moz-transition: initial;
	-o-transition: initial;
	transition: initial;
} 
.woocommerce-page .product .comment-form p.stars span a.active {
	background: url(images/woostars.png) repeat-x left bottom ;
} 
.woocommerce-page .product .comment-form p.stars span a.star-1 {
	width: 20px;
	z-index:10;
} 
.woocommerce-page .product .comment-form p.stars span a.star-1:after {
	content: '';
}
.woocommerce-page .product .comment-form p.stars span a.star-2 {
	width: 40px;
	z-index: 9;
} 
.woocommerce-page .product .comment-form p.stars span a.star-2:after {
	content: '';
}
.woocommerce-page .product .comment-form p.stars span a.star-3 {
	width: 60px;
	z-index: 8;
} 
.woocommerce-page .product .comment-form p.stars span a.star-3:after {
	content: '';
}
.woocommerce-page .product .comment-form p.stars span a.star-4 {
	width: 80px;
	z-index: 7;
}
.woocommerce-page .product .comment-form p.stars span a.star-4:after {
	content: '';
} 
.woocommerce-page .product .comment-form p.stars span a.star-5 {
	width: 100px;
	z-index: 6;
}
.woocommerce-page .product .comment-form p.stars span a.star-5:after {
	content: '';
}
.woocommerce-page .product .comment-form p.stars span a {
	border: none;
}
.woocommerce-page .comment-form-rating {
	float: left;
	width: 100%;
	margin-top: 15px;
}
.woocommerce-page .product #review_form_wrapper {
	float: left;
	width: 100%;
}
.woocommerce-page .woocommerce-tabs .commentlist {
	padding: 0;
	margin: 0;
}
.woocommerce-page .woocommerce-tabs .commentlist .comment {
	float: left;
	clear: left;
	width: 100%;
}
.woocommerce-page .woocommerce-tabs .comment-text {
	display: inline-block;
}
.woocommerce-page .woocommerce-tabs .description {
	width: 100%;
}
.woocommerce-page .woocommerce-product-rating,
.woocommerce div.product .woocommerce-product-rating {
	float: left;
	text-align: left;
	margin-top: 30px;
	margin-bottom: 0;
}
.woocommerce-page .woocommerce-product-rating .star-rating {
	position: relative;
	width: 100px;
	height: 20px;
	text-indent: 99999px;
	position: relative;
	overflow: hidden;
	background: url(images/woostars.png);
	background-repeat: no-repeat;
	background-position: top left;
}
.woocommerce-page .woocommerce-product-rating .star-rating span {
	position: absolute;
	top: 0;
	left: 0;
	width: 100px;
	height: 20px;
	background: url(images/woostars.png);
	background-repeat: no-repeat;
	background-position: bottom left;
	overflow: hidden;
	padding: 1px
}
.woocommerce-page .woocommerce-product-rating .woocommerce-review-link,
.woocommerce-page .woocommerce-product-rating .woocommerce-review-link span {
	font-size: 11px;
	color: #eca420;
}
.woocommerce-page .comment-text .star-rating {
	position: relative;
	width: 100px;
	height: 20px;
	text-indent: 99999px;
	position: relative;
	overflow: hidden;
	background: url(images/woostars.png);
	background-repeat: no-repeat;
	background-position: top left;
}
.woocommerce-page .comment-text .star-rating span {
	position: absolute;
	top: 0;
	left: 0;
	width: 100px;
	height: 20px;
	background: url(images/woostars.png);
	background-repeat: no-repeat;
	background-position: bottom left;
	overflow: hidden;
	padding: 1px;
}
.woocommerce-page .woocommerce-tabs .comment-text {
	width: 100%;
}
.woocommerce-page .woocommerce-tabs .comment_container {
	position: relative;
	padding-left: 50px;
}
.woocommerce-page .woocommerce-tabs .comment_container > img {
	position: absolute;
	left: 0;
	top: 0;
}
.woocommerce-page .woocommerce-message {
	margin: 0px 0 40px;
	background: #20AA73;
	border-radius: 3px;
	color: #FFF;
	list-style: none;
}
.woocommerce-page .woocommerce-message a {
	background-color: #38C28B;
	padding: 6px 14px;
	font-size: 12px;
	color: #FFF;
}
.woocommerce-page .woocommerce-error {
	list-style: none;
	padding: 0;
	margin: 0px 0 40px;
	background: #E96656;
	border-radius: 3px;
	color: #FFF;
	border: none;
	float: left;
	width: 100%;
}
.woocommerce-page .woocommerce-error a {
	background-color: #F47565;
	padding: 6px 14px;
	font-size: 12px;
	color: #FFF;
}
.woocommerce-page .woocommerce .woocommerce-error:before {
	color: #FFF;
}
.woocommerce-page .woocommerce-info {
	list-style: none;
	padding: 0;
	margin: 0px 0 40px;
	background: #3ab0e2;
	border-radius: 3px;
	color: #FFF;
	border: none;
	float: left;
	width: 100%;
	margin-top: 25px !important;
}
.woocommerce-page .woocommerce-info a {
	background-color: #5fb8dd;
	padding: 6px 14px;
	font-size: 12px;
	color: #FFF;
}
.woocommerce-page .woocommerce-info:before {
	color: #FFF;
}
.woocommerce-page .woocommerce-info {
	float: left;
	text-align: left;
	padding-top: 30px;
}
.woocommerce-page .woocommerce .woocommerce-info {
	background: rgb(58, 176, 226);
	color: #FFF;
	border-radius: 3px;
	border: none;
	padding-top: 15px;
	margin-bottom: 40px;
}
.woocommerce-page .woocommerce .woocommerce-info a {
	color: #FFF;
	opacity: 0.9;
}
.woocommerce-page .woocommerce .woocommerce-info:before {
	color: #FFFFFF;
}
.woocommerce-page .woocommerce input {
	border-radius: 3px;
	padding: 10px 5px;
}
.woocommerce-page .woocommerce .woocommerce-error {
	border-top-color: #b81c23;
	border-radius: 3px;
	padding: 1em 2em 1em 3.5em!important;
}
.woocommerce-page .woocommerce .products .product h3 {
	float:none;
	color: #404040;
}
.woocommerce-page .woocommerce .added_to_cart, .woocommerce .button  {
	display: inline-block;
	text-align: center;
	text-transform: uppercase;
	padding: 13px 35px 13px 35px;
	border-radius: 4px;
	margin: 10px;
	border: none;
	background: #f3f3f3;
	color: #000;	
}
.woocommerce-page .woocommerce .add_to_cart_button, .woocommerce .checkout-button, .woocommerce .single_add_to_cart_button, .woocommerce #place_order,
.woocommerce div.product form.cart .button {
	display: inline-block;
	text-align: center;
	text-transform: uppercase;
	padding: 13px 35px 13px 35px;
	border-radius: 4px;
	margin: 10px;
	border: none;
	background: #e96656;
	color: #FFF;
	margin-left: 0;
}
.woocommerce-page .woocommerce-tabs .tabs {
	border-bottom: 1px solid #CCC;
}
.woocommerce-page .woocommerce .add_to_cart_button:hover, .woocommerce .checkout-button:hover, .woocommerce .single_add_to_cart_button :hover, .woocommerce #place_order:hover,
.woocommerce div.product form.cart .button:hover {
	background:#bf3928;
}
.woocommerce-page .woocommerce .price del {
	display:block;
}
.woocommerce-page .woocommerce .price {
	height:auto;
	line-height:normal;
}
.woocommerce-page .woocommerce .price ins {
	color: #000;
	font-weight:bold;
	font-size: 20px;
}
.woocommerce-page .woocommerce #coupon_code {
	padding: 6px 10px;
	color: #A0A0A0;
	border: 1px solid rgba(0, 0, 0, 0.1);
	border-radius: 0;
	margin-top: 2px;
	border-radius: 5px!important;
	padding: 6px;
	min-width: 110px;
}
.woocommerce-page .woocommerce .product-name a {
	color:#404040;
}
.woocommerce div.product form.cart {
	margin-bottom: 0
}
.woocommerce-page .woocommerce .cart_totals tr.cart-subtotal th, 
.woocommerce-page .woocommerce .cart_totals tr.order-total th {
	width: 50%;
}
.woocommerce-page .woocommerce .entry-title {
	text-align:left;
}
.woocommerce .woocommerce-info:before, 
.woocommerce-page .woocommerce-info:before,
.woocommerce .woocommerce-error:before, 
.woocommerce-page .woocommerce-error:before {
	padding: 0;
}
.woocommerce-page .woocommerce .checkout input, 
.woocommerce-page .woocommerce .checkout textarea, 
.woocommerce-page .woocommerce .checkout select {
	padding: 12px 15% 12px 2%;
}
.woocommerce-page .woocommerce ul.payment_methods {
	padding-left:1em;
}
.woocommerce-page ul.products  {
	margin-top: 40px;
	float: left;
	width: 100%;
}
.woocommerce-page .woocommerce .summary, 
.woocommerce-page .woocommerce .entry-summary, 
.woocommerce-page .woocommerce div.product .woocommerce-tabs .panel {
	text-align:justify;
}
.woocommerce-page .woocommerce .quantity input.input-text {
	width: 100px;
	height: 42px;
	margin-right: 10px;
}
.woocommerce-page .woocommerce form.cart button.single_add_to_cart_button {
	margin: 0px;
}
.woocommerce-page .woocommerce .comment-form label {
	width:100%;
}
.woocommerce-page .woocommerce .woocommerce-message {
	background: #20AA80;
	text-align: left;
	color: white;
	border-radius: 3px;
	border:none;
	float: left;
	width: 100%;
}
.woocommerce-page .woocommerce .woocommerce-message a.button {
	margin:0px;
	padding:7px 17px;
}
.woocommerce-page .woocommerce .woocommerce-message:before {
	color: #fff;
}
.woocommerce-page .woocommerce ul.products li.product .star-rating {
	font-size:inherit;
}
.woocommerce-page .woocommerce input[type="submit"],
.woocommerce-page #content input.button,
.woocommerce input.button.alt, .woocommerce-page #content input.button.alt, .woocommerce-page input.button.alt {
	background: #e96656;
	display: inline-block;
	text-align: center;
	text-transform: uppercase;
	padding: 10px 20px 10px 20px;
	border-radius: 4px;
	margin: 10px;
	border: none;
	color: #FFF;
	font-size: 12px;
	margin: 0;
	text-shadow: none;
}
.woocommerce-page .woocommerce input[type="submit"]:hover,
.woocommerce-page #content input.button:hover,
.woocommerce input.button.alt:hover, .woocommerce-page #content input.button.alt:hover, .woocommerce-page input.button.alt:hover {
	background: #cb4332;
	color: #FFF;
	box-shadow: none;
}
.woocommerce-page .woocommerce .product-quantity input.qty {
	width: 60px;
	height: 30px;
	margin-right: 0;
	padding: 0 0 0 5px;
	text-align: left;
}
.woocommerce a.button.alt {
	background: #e96656;
	color: #FFF;
}
.woocommerce a.button.alt:hover {
	background: #cb4332;
	color: #FFF;
}
.woocommerce-page .woocommerce a.remove:hover {
	color: #fff !important;
	background: #e96656;
	line-height: 20px;
}
.woocommerce-page .woocommerce a.remove {
	color: #e96656 !important;
	line-height: 20px;
}
.woocommerce-page .woocommerce-info {
	width: 100%;
}
.woocommerce-page .woocommerce-checkout .col-1,
.woocommerce-page .woocommerce-checkout .col-2 {
	float: left;
	width: 100%;
}
.woocommerce-page .woocommerce-checkout-review-order {
	clear: left;
}
.woocommerce-page .woocommerce .checkbox {
	padding-left: 0;
	float: left;
}
.woocommerce-page .woocommerce .input-checkbox {
	margin: 15px 0 0 10px;
}
.woocommerce-page .woocommerce-checkout #payment {
	background: #FAFAFA;
}
.woocommerce-page .woocommerce-checkout #payment div.payment_box {
	background-color: #ECECEC;
}
.woocommerce-page .woocommerce-checkout #payment div.payment_box:after {
	content: "";
	border: 8px solid #ECECEC;
	border-right-color: transparent;
	border-left-color: transparent;
	border-top-color: transparent;
	margin: -13px 0 0 2em;
}
.woocommerce-page .woocommerce .order_details li.order {
	background: #FFFFFF;
}
.woocommerce-page .products a.button {
	text-decoration: none;
}
.woocommerce-page .product .cart .button {
	color: #FFF;
}
.woocommerce-page .woocommerce {
	margin-top: 25px;
}
.woocommerce-page .woocommerce .order {
	background: #FFF;
}
.woocommerce-page .woocommerce table.my_account_orders .order-actions .button {
	font-size: 12px;
}
.woocommerce-page .woocommerce #payment ul.payment_methods {
    text-align: left;
    padding: 1em;
    border-bottom: 1px solid #D3CED2;
    margin: 0px;
    list-style: outside none none;
}
.woocommerce-page .woocommerce #payment ul.payment_methods li {
    line-height: 2;
    text-align: left;
    margin-left: 2em;
    font-weight: 400;
}
.woocommerce-page .woocommerce #payment {
    background: none repeat scroll 0% 0% #FAFAFA;
}
.woocommerce-page .woocommerce #payment div.payment_box {
    position: relative;
    width: 96%;
    padding: 1em 2%;
    margin: 1em 0px;
    font-size: 0.92em;
    border-radius: 2px;
    line-height: 1.5;
    background-color: #DFDCDE;
    color: #515151;
}
.woocommerce-page .woocommerce #payment div.payment_box {
    background-color: #ECECEC;
}
.woocommerce-page .woocommerce #payment div.payment_box p {
	margin-bottom: 0;
}
.woocommerce-page .woocommerce #payment div.payment_box:after {
    content: "";
    position: absolute;
	top: -3px;
	left: 0px;
    border-width: 8px;
    border-style: solid;
    border-color: transparent transparent #ECECEC;
    -moz-border-top-colors: none;
    -moz-border-right-colors: none;
    -moz-border-bottom-colors: none;
    -moz-border-left-colors: none;
    border-image: none;
    margin: -13px 0px 0px 2em;
}
.woocommerce-page .woocommerce #payment h3{
	padding-left: 20px;
}
.woocommerce-page .woocommerce a.button {
	font-size: 14px;
	margin-left: 0;
}
.woocommerce-page .woocommerce button.button {
	font-size: 12px;
	margin-left: 0;
	padding: 13px 35px 13px 35px;
}
.woocommerce button.button {
	width: 100%;
}
.woocommerce-page .woocommerce select {
	color: #A0A0A0;
	border: 1px solid rgba(0, 0, 0, 0.1);
	box-sizing: border-box;
	width: 100%;
	margin: 0;
	outline: 0;
	line-height: 1;
	border-radius: 3px;
	padding: 10px 5px;
}
.woocommerce-page .woocommerce #order_review {
	clear: left;
}
.woocommerce-page .woocommerce .login {
	float: left;
	width: 100%;
}
.woocommerce-page .select2-drop {
	text-align: left;
}
.woocommerce-page .woocommerce-account .addresses .title .edit {
	float: left;
}
.woocommerce-page div.product .woocommerce-tabs ul.tabs li {
	border: none;
	background: none;
	padding-bottom: 0
}
.woocommerce-page div.product .woocommerce-tabs ul.tabs li.active:before {
	content: "";
	border: none;
}
.woocommerce-page div.product .woocommerce-tabs ul.tabs:before {
	content: "";
	display: none;
}
.woocommerce-page .woocommerce div.product .woocommerce-tabs ul.tabs li.active:after {
	content: '';
	display: none;
}
.woocommerce div.product .woocommerce-tabs ul.tabs li:after, 
.woocommerce div.product .woocommerce-tabs ul.tabs li:before {
	content: "";
	display: none;
}
.woocommerce div.product .woocommerce-tabs ul.tabs {
	overflow: visible;
}
.woocommerce div.product .woocommerce-tabs ul.tabs li.active {
	border-bottom: 2px solid #e96656;
	margin-bottom: -1px;
}
.woocommerce div.product .woocommerce-tabs ul.tabs li {
	box-shadow: none;
}
.woocommerce-page .comment-form {
	float: left;
	float: left;
	margin-top: 15px;
	width: 100%;
}
.woocommerce #review_form #respond .form-submit input {
	background: #e96656;
	display: inline-block;
	text-align: center;
	text-transform: uppercase;
	padding: 13px 35px 13px 35px;
	border-radius: 4px;
	margin: 10px;
	border: none;
}
.woocommerce #review_form #respond textarea {
	width: 100%;
	height: 130px;
}
.woocommerce #reviews #comments ol.commentlist li .comment-text {
	margin: 0;
}
.woocommerce-cart .cart-collaterals .cart_totals table {
	clear: left;
}
.woocommerce table.shop_table {
	clear: left;
}
.woocommerce #content div.product div.thumbnails a, 
.woocommerce div.product div.thumbnails a, 
.woocommerce-page #content div.product div.thumbnails a, 
.woocommerce-page div.product div.thumbnails a {
	margin-bottom: 1em;
}
.woocommerce .upsells.products ul, 
.woocommerce .upsells.products ul.products {
	float: left;
	clear: left;
}
/**/
.woocommerce .woocommerce-message:before, .woocommerce-page .woocommerce-message:before {
	content: "\2713";
	padding: 0;
}
.woocommerce .shipping_calculator h2 a {
	font-size: 18px;
}
/**/
.woocommerce-page .upsells.products ul li.product,
.woocommerce-page .upsells.products ul.products li.product {
	float: left;
	margin: 0 3.8% 2.992em 0;
	padding: 0;
	position: relative;
	width: 22.05%;
	clear: none;
}
.woocommerce .upsells.products ul li.product:nth-child(4), 
.woocommerce-page ul.products li.product:nth-child(4) {
	margin-right: 0;
}
.woocommerce .upsells.products ul li.product:nth-child(4+1), 
.woocommerce-page ul.products li.product:nth-child(4+1) {
	clear: left;
}
/*woocommerce pagination*/
.woocommerce nav.woocommerce-pagination {
	float: left;
	width: 100%;
	padding-bottom: 30px;
}
.woocommerce .woocommerce-pagination ul.page-numbers .current:before, 
.woocommerce-page .woocommerce-pagination ul.page-numbers .current:before {
	content: "";
	display: none;
}
.woocommerce #content nav.woocommerce-pagination ul, 
.woocommerce nav.woocommerce-pagination ul, 
.woocommerce-page #content nav.woocommerce-pagination ul, 
.woocommerce-page nav.woocommerce-pagination ul,
.woocommerce nav.woocommerce-pagination ul {
	border: none;
}
.woocommerce #content nav.woocommerce-pagination ul li, 
.woocommerce-page #content nav.woocommerce-pagination ul li, 
.woocommerce-page nav.woocommerce-pagination ul li
.woocommerce nav.woocommerce-pagination ul li {
	border: none;
	margin: 0 3px;
}
.woocommerce nav.woocommerce-pagination ul li a,
.woocommerce nav.woocommerce-pagination ul li span {
	width: 32px;
	min-width: 32px;
	border: none;
	border-radius: 4px;
	background: rgb(236, 236, 236);
	color: #000;
}
.woocommerce #content nav.woocommerce-pagination ul li span.current,
.woocommerce nav.woocommerce-pagination ul li span.current,
.woocommerce-page #content nav.woocommerce-pagination ul li span.current,
.woocommerce-page nav.woocommerce-pagination ul li span.current,
.woocommerce nav.woocommerce-pagination ul li span.current,
.woocommerce nav.woocommerce-pagination ul li a:hover,
.woocommerce-page nav.woocommerce-pagination ul li a:hover,
.woocommerce-page #content nav.woocommerce-pagination ul li a:hover,
.woocommerce nav.woocommerce-pagination ul li a:hover,
.woocommerce #content nav.woocommerce-pagination ul li a:hover {
	background: rgb(233, 102, 86);
	color: #FFF;
}

@media (max-width: 1200px) {
	
	.header-content-wrap{
		padding: 235px 0 150px;
	}

}

@media (max-width: 992px) {

	.woocommerce-page .woocommerce .cart-collaterals .cart_totals {
		width: 100%;
	}
	.woocommerce-page .products .product > a:first-child {
/*		min-height: 325px; */
	}
	.large-container {
		width: 100%;
	}

}
@media (max-width: 767px) {
	.woocommerce-page .upsells.products ul li.product,
	.woocommerce-page .upsells.products ul.products li.product{
		width: 48%;
		float: left;
		clear: both;
		margin: 0 0 2.992em;
	}
	.woocommerce .upsells.products ul li.product:nth-child(4), 
	.woocommerce-page ul.products li.product:nth-child(4) {
		margin: 0 0 2.992em;
	}
	.woocommerce .upsells.products ul li.product:nth-child(4+1), 
	.woocommerce-page ul.products li.product:nth-child(4+1) {
		clear: none;
	}
	.woocommerce .upsells.products ul li.product:nth-child(even), 
	.woocommerce-page ul.products li.product:nth-child(even) {
		margin-right: 0;
		float: right;
	}
	.woocommerce .upsells.products ul li.product:nth-child(odd), 
	.woocommerce-page ul.products li.product:nth-child(odd) {
		clear: left;
	}
	.listpost-content-wrap-large {
		position: relative;
	}
	.menu-align-center .responsive-logo > a {
		float: left;
	}
}
@media (max-width: 600px) {

	.woocommerce-page .product .images {
		width: 100%;
	}
	.woocommerce-page .product .entry-summary {
		width: 100%;
		padding-left: 0%;
		margin-top: 50px;
	}
	.woocommerce-page .woocommerce-tabs .tabs li a {
		font-size: 14px;
	}
	.woocommerce-page .woocommerce-tabs .tabs li {
		padding: 10px 10px;
	}
	.listpost-content-wrap-large {
		position: relative;
	}
	.listpost-content-wrap-large {
		padding: 20px 0px 0px 0px;
	}
	#wpadminbar {
  		position: fixed;
	}
	.entry-meta-large {
		position: relative;
		float: left;
		width: 100%;
	}
	.entry-footer-large {
		padding-right: 0;
	}
}
@media (max-width: 480px) {

	.woocommerce ul.products li.product, .woocommerce-page ul.products li.product {
		width: 100%;
	}
	.woocommerce-page .woocommerce-result-count {
		text-align: center;
		width: 100%;
		margin-bottom: 0px;
	}
	.woocommerce-page .woocommerce-ordering {
		float: none;
	}
	.woocommerce-page .products .product > a:first-child {
		width: 240px;
	}
	.woocommerce-page .woocommerce-tabs .tabs li {
		width: 100%;
	}
	.woocommerce-page .woocommerce-tabs .tabs li {
		width: 100%;
		border-bottom: 2px solid #CCC;
	}
	.woocommerce-page .woocommerce-tabs .tabs {
		border-bottom: 0;
	}
	.woocommerce-page .woocommerce-tabs .comment_container {
		position: relative;
		padding-left: 0px;
		padding-top: 50px;
	}
	.woocommerce-page .comment-text .star-rating {
		width: 100%;
		margin-bottom: 5px;
		float: left;
	}
	.woocommerce-page .products .product > a:first-child {
		width: 100%;
	}
	/* cart page */
	.woocommerce table.shop_table th {
		padding: 5px 5px;
		font-size: 8px;
	}
	.woocommerce-page .woocommerce .product-name a {
		font-size: 12px;
		line-height: 16px;
		float: left;
	}
	.woocommerce table.shop_table td {
		padding: 6px 4px;
	}
	.woocommerce table.shop_table td,
	.woocommerce table.shop_table td span,
	.woocommerce table.shop_table td a,
	.woocommerce table.shop_table td strong {
		font-size: 12px;
	}
	.woocommerce table.shop_table td .amount {
		font-size: 12px;
	}
	.woocommerce-page .woocommerce .product-quantity input.qty {
		width: 45px;
	}
	.woocommerce td.product-quantity {
		min-width: 40px;
	}
	.woocommerce-page .woocommerce input[type="submit"] {
		font-size: 10px;
	}
	.woocommerce-page .woocommerce .cart_totals tr.cart-subtotal th {
		font-size: 12px;
	}
	.woocommerce-cart .cart-collaterals .cart_totals tr th {
		font-size: 12px;
	}
	.woocommerce-cart .cart-collaterals .cart_totals table td,
	.woocommerce-cart .cart-collaterals .cart_totals table td span,
	.woocommerce-cart .cart-collaterals .cart_totals table td a {
		font-size: 12px;
	}
	.woocommerce form .form-row label {
		font-size: 12px;
	}
	.woocommerce-page .woocommerce .woocommerce-info,
	.woocommerce-page .woocommerce .woocommerce-info a {
		font-size: 12px;
	}
	.woocommerce-checkout-payment label {
		font-size: 14px;
	}
	.woocommerce-page .woocommerce #payment div.payment_box p {
		font-size: 12px;
		line-height: 16px;
		text-align: justify;
	}
	.woocommerce form .form-row {
		width: 100%;
	}
	.woocommerce-page .woocommerce .order_details li {
		width: 100%;
		border-bottom: 1px dashed #d3ced2;
		border-right: none;
		padding: 0 0 5px 0;
		margin-bottom: 5px;
		margin-top: 5px 
	}
	.woocommerce-page address {
		font-size: 12px;
	}
	.woocommerce-page .woocommerce-error,
	.woocommerce-page .woocommerce-message,
	.woocommerce-page .woocommerce-error li {
		font-size: 12px;
	}
	.woocommerce-page .woocommerce .cart-collaterals .cart_totals a {
		width: 100%;
		margin-right: 0;
	}
	.woocommerce-page .woocommerce .checkbox {
		font-size: 16px;
	}
	.woocommerce-page .myaccount_address {
		font-size: 12px;
	}
	.woocommerce-page #content .quantity input.minus,
	.woocommerce-page #content .quantity input.plus {
		display: none;
	}
	.woocommerce-page .upsells.products ul li.product,
	.woocommerce-page .upsells.products ul.products li.product{
		width: 100%;
	}

}
/* [end] woocommerce */

body.home.page {
	background-image:none !important;
}

body.custom-background {
	background-position: top center !important;
	background-attachment: fixed !important;
}

.zerif_team:nth-child(4n+1), .our-team .col-lg-3:nth-child(4n+1) {
	clear:both;
}

.dropdownmenu {
	display: none;
}

/*---------------------------------------
 **   Responsive            -----
-----------------------------------------*/

@media (max-width: 1200px) {
	
	.header-content-wrap{
		padding: 235px 0 150px;
	}

}

@media (min-width: 768px) and (max-width: 1024px) {

    /* TOP BAR ELEMENTS */

     /* HOME */
	.intro {
		margin-top: 40%;
		line-height: 55px;
		font-size: 45px;
	}

      /* ABOUT US */
	.big-intro {
		text-align: center !important;
	}
	.about-us .column {
		margin-bottom: 40px;
	}
	.skills {
		margin-bottom: 78px !important;
	}

      /* TEAM */
	.team-member .profile-pic {
		width: 128px;
		height: 128px;
	}
	.team-member .details {
		line-height: 18px;
	}
      /* PURCHASE NOW */
	.purchase-now {
		margin: auto;
		text-align: center !important;
	}
	.purchase-now h3 {
		text-align: center;
		margin-bottom: 20px;
	}
	.purchase-now .button {
		float: none;
	}

      /* FOOTER */
	footer {
		padding-top: 40px;
	}
	.company-details {
		padding-top: 0;
		padding-bottom: 33px;
	}
	.copyright {
		width: 100%;
		padding-top: 33px;
		padding-bottom: 33px;
	}
}

@media (max-width: 992px) {

	.purchase-now .red-btn{
	    float: none;
	}
	.skills{
	    margin-left: 0;
	}
	#client-feedbacks .feedback-box{
	    width: 100%;
	    margin-left: 0;
        margin-right: 0;
	}
	.header-content-wrap {
		padding-top: 26%;
	}
	.intro-text{
        font-size: 45px;
        line-height: 55px;
    }
    .section-header h2{
        font-size: 35px;
    }
    .section-header {
        padding-bottom: 30px;
    }
    .focus, .works, .about-us, .features, .packages, .products, .testimonial, .contact-us {
        padding-top: 60px;
        padding-bottom: 60px;
    }
    .header-content-wrap{
		padding: 225px 0 150px;
	}

}
@media (max-width: 767px) {

	/* HEADER */
	.bs-navbar-collapse {
		border: 0;
	}
	#main-nav {
		overflow: visible;
	}
	#main-nav,
	#main-nav.fixed {
		position: relative;
	}
	.navbar-inverse .navbar-nav {
		padding-left: 10px;
		line-height: normal;
		text-align: center;
	}
	.navbar-inverse .navbar-nav>li {
		display: inline-block;
		margin-bottom: 0;
	}
	.navbar-inverse .navbar-nav > li {
		width: 100%;
		border-bottom: 1px solid #EDEDED;
		position: relative;
		margin: 8px 0 0 0;
		padding: 0 0 8px 0;
	}
	.navbar-inverse .navbar-nav > li  a {
		text-align: left;
	}
	.navbar-inverse .navbar-nav ul.sub-menu {
		display: none !important;
		position: relative;
		top: 0;
		box-shadow: none;
		width: 100%;
	}
	.navbar-inverse .navbar-nav li.this-open > ul {
		display: block !important;
	}
	.navbar-inverse .navbar-nav ul.sub-menu li {
		width: 100%;
		float: left;
	}
	.navbar-inverse .navbar-nav ul.sub-menu li a {
		width: 100%;
		float: left;
		padding: 8px 25px 8px 0;
		border-bottom: 1px solid #EDEDED;
	}
	.navbar-inverse .navbar-nav ul.sub-menu li:last-child a {
		border-bottom: none;
	}
	.navbar-inverse .navbar-nav ul.sub-menu ul.sub-menu {
		position: relative;
		left: 0;
		top: 0;
	}
	#main-nav {
		overflow: hidden;
	}
	#main-nav,
	#main-nav.fixed {
		position: relative;
	}
	.navbar-collapse {
		max-height: 100%;
	}
	.navbar-inverse .navbar-nav ul.sub-menu li {
		padding-left: 20px;
	}
	.navbar-inverse .navbar-nav ul.sub-menu li {
		padding-bottom: 0;
		padding-top: 0;
	}
	.dropdownmenu {
		display: block;
		position: absolute;
		z-index: 9;
		right: 0;
		top: 5px;
		width: 25px;
		height: 25px;
		margin: 0;
		padding: 0;
		border-radius: 3px;
		background: url(images/menu-icon.png) center center no-repeat #e96656;
	}
	.navbar-inverse .navbar-nav ul.sub-menu li{
		margin-right: 0;
		padding-right: 0;
	}
	.navbar-inverse .navbar-nav > li > a:hover {
		color: #404040 !important;
	}
	.this-open > a {
		color: #e96656 !important;
	}
	li.current>a:before {
		content: "";
		display: none !important;
	}
	ul.nav > li.current_page_item > a:before {
		content: "";
		left: 0px;
		width: 50px;
	}

    /* HOME */
	.header {
		min-height: inherit;
		padding-bottom: 0 !important;
	}
	.intro {
		line-height: 8vh;
		font-size: 6.5vw;
	}
    .header-content-wrap {
    	padding-top: 30%;
    }
	.intro-text{
        font-size: 41px;
        line-height: 49px;
    }
	.focus-box {
        margin-bottom: 75px;
    }
    .section-header {
        float: left;
        width: 100%;
    }

      /* ABOUT US */
	.big-intro {
		text-align: center !important;
		font-size: 8vw !important;
	}
	.about-us .column {
		margin-bottom: 40px;
	}
	.skills {
		margin-bottom: 78px !important;
	}
	.our-clients{
	    width: 100%;
	    float: left;
	}

      /* PURCHASE NOW */
	.purchase-now {
		margin: auto;
		text-align: center !important;
	}
	.purchase-now h3 {
		text-align: center;
		margin-bottom: 20px;
	}
	.purchase-now .button {
		float: none;
	}

      /* FOOTER */
	footer {
		padding-top: 40px;
	}
	.company-details {
		padding-top: 0;
		padding-bottom: 33px;
	}
	.copyright {
		width: 100%;
		padding-top: 33px;
		padding-bottom: 33px;
	}
	/* comments */
	.comment-metadata {
		position: relative;
		top: 0px;
		right: 0px;
	}
}
@media (max-width: 480px) {

/* HOME */
	.intro {
		margin-top: 60%;
		line-height: 6vh;
		font-size: 6.5vw;
	}
	
	.header-content-wrap {
	    padding-top: 40%;
	}
	.intro-text{
        font-size: 32px;
        line-height: 37px;
    }
	h2 {
		font-size: 6.5vw !important;
	}
	.other-focus-list ul li {
		display: block;
		text-align: left;
		margin-right: 0;
	}
	/* blog */
	.post-img-wrap {
		width: 100%;
	}
	.listpost-content-wrap {
		width: 100%;
		margin-top: 20px;
		float: left;
	}
	.entry-content p {
  		margin: 4px 0px 0px 0px;
	}
	.post-img-wrap a {
		float: none;
		margin: 0 auto;
		width: 250px;
		height: 250px;
	}
	.post-img-wrap {
		text-align: center;
		margin-right: 0;
	}
	.post-img-wrap a img{
		width: auto;
	}
	/* comments */
	.comment-reply-link{
		position: relative;
		margin-top: 10px;
	}
	.post-img-wrap a img{
		width: 250px;
		height: auto;
		-webkit-transform: scale(1);
		-moz-transform: scale(1);
		-o-transform: scale(1);
		-ms-transform: scale(1);
		transform: scale(1);
		-webkit-transition: all 0.3s ease-out;
		-moz-transition: all 0.3s ease-out;
		-ms-transition: all 0.3s ease-out;
		-o-transition: all 0.3s ease-out;
		transition: all 0.3 ease-out;
	}
	.post-img-wrap a:hover img{
		-webkit-transform: scale(1);
		-moz-transform: scale(1);
		-o-transform: scale(1);
		-ms-transform: scale(1);
		transform: scale(1);
		-webkit-transition: all 0.3s ease-out;
		-moz-transition: all 0.3s ease-out;
		-ms-transition: all 0.3s ease-out;
		-o-transition: all 0.3s ease-out;
		transition: all 0.3 ease-out;
	}
}
@media (max-width: 320px) {
    .intro {
		line-height: 25px;
		font-size: 7vw;
	}
	.header-content-wrap {
        padding-top: 50%;
    }
    .intro-text {
        font-size: 22px;
        line-height: 30px;
    }
	.client-list ul li {
		display: block;
	}
	.listpost-content-wrap-large{
		position: relative;
	}
	.post-img-wrap-large{
		display:none;
	}
}

.zerif-copyright {
	color:#939393!important;
}

.zerif-copyright-box {
	width: 100%;
}


/*----------------------------------------------------------------------------------
 ----- Personnalisation Thème ------------------------------------------------------
------------------------------------------------------------------------------------ */  

	/* Largeur bootstrap et outils */
	
	@media (min-width: 1200px) {
	    .container{
	        max-width: 1054px;
	    }
	}
	.no-padding { padding: 0;}

	html, body, div, span, applet, object, iframe,
 	h1, h2, h3, h4, h5, h6, p, blockquote, pre, a,
	abbr, acronym, address, big, cite, code, del,
	dfn, em, font, ins, kbd, q, s, samp, small, strike
	, strong, sub, sup, tt, var, dl, dt, dd, ol,
	ul, li, fieldset, form, label, legend, table,
	caption, tbody, tfoot, thead, tr, th, td {
	     	font-family: 'Century Gothic';
	     }


	/* A° Style navbar */
		.navbar {
			background: none;
			-webkit-transition: all 0.5s ease;
		    -moz-transition: all 0.5s ease;
		    -o-transition: all 0.5s ease;
		    transition: all 0.5s ease;
		}
		.navbar .lang-item { 
			border: 1px solid #fff; 
			padding:0 5px;
		}
		
		.navbar .home a{
			font-weight: bold;
		}
		.navbar.background-darken{
    		background-color: rgba(0, 0, 0, 0.556863);
    		-webkit-transition: all 0.5s ease;
		    -moz-transition: all 0.5s ease;
		    -o-transition: all 0.5s ease;
		    transition: all 0.5s ease;
		}
		.navbar ul.nav > li.current_page_item > a:before {
			background: none;
		}
		.navbar .current_page_item a { 
			font-weight: bold;
		}
		
		.header.header > .navbar {
			box-shadow: none;
		}
		.navbar-inverse .navbar-nav > li > a{
			font-size: 22px;
			color: #fff;
		}
		/* responsive */
		@media (max-width: 767px) {
				.navbar .lang-item { 
					border: none; 
					border-radius: 0;
				}
				#main-nav, #main-nav.fixed {
					position: fixed;
					top:initial;
				}
			
			}
	/* End A° */


	/* B° Home */

		/* 1 More Fun More Value */
		section.big-title {
			background: url(images/bigTitle.jpg)  center center;
			background-position: center top;
    		background-size: cover;		
    		background-attachment: fixed;				
		}
		.intro-home span {
			color: #fff;
			font-size:61px;
		}
		.intro-home span.pink {
			color: #DF4B88;
		}
		.scroll-invit {
			color: #fff;
			padding-top:376px;
		}
		.scroll-invit-mobile {
			display: none;
		}
		.scroll-invit img{
			display:inline;
			padding-right: 10px;
		}
		.scroll-invit p{
			display:inline;
		}
		
		.header-content-wrap { 
			background: none;
			padding-top: 450px;
			padding-bottom: 90px;
		    -webkit-box-shadow: none;
    		box-shadow: none;
		}

		/* responsive */
			@media (max-width: 767px) {
				.intro-home span.pink {
				display: block;
				padding-top:25px;
				}
				.intro-home span {
					font-size:41px;
				}
				.header-content-wrap { 
					padding-top: 250px;
				}
				.scroll-invit {
					padding-top:200px;
					display: none;
				}
				section.big-title {
		    		background-attachment: initial;				
				}
				.scroll-invit-mobile {
					display: block;
					padding-top:200px;
				}

			}


		/* 2 Notre groupe */
		section.our-group {
			background: url(images/ourGroup.jpg)  center center;
			background-position: center top;
    		background-size: cover;						
		}

		.group-home .row { 
			margin-bottom: 35px;
		}
		.group-home p { 
			font-size: 24px;
		}
	
		.group-home .vcenter {
		    display: inline-block;
		    vertical-align: middle;
		    float: none;
		    text-align:left;
		}

		/* responsive */

			@media (min-width: 768px) and (max-width: 991px) {
				.group-home p {
					width: 300px;
					padding-left: 30px;    				    
				}
				.group-home img {
					width: 80px;  				    
				}
				.group-home .row.top-group { margin:0;}
				
			}
			@media (max-width: 767px) {
				.group-home p {
					width: 300px;
					padding-left: 30px;    				    
				}
				.group-home img {
					width: 70px;  				    
				}
				.group-home .row.top-group { margin:0;}

			}

			@media (max-width: 480px) {
				.group-home p {					
					width: auto;
					padding:0;									    
					}
				.group-home .vcenter {										
					text-align:center;	
					width:100%;					 			    
				}
			}

		/* 3 B2C */
		section.about-us {
			background: url(images/peopleColor.jpg)  center center repeat-y;
			background-position: center top;
    		background-size: cover;	
    		padding-top:85px;					
		}

		section.about-us p {
			color: #fff;
			font-size: 29px;
			text-align: center;
			line-height:1.2;
			margin-bottom: 90px;
		}

		section.about-us p.second-text,
		section.about-us .section-header {
			margin-bottom:90px;
		}

		.link-btoc {
			display:block;
			margin-bottom:90px;
		}
		.link-btoc a {
			text-align:center;
			background-color: white;
			padding:15px 25px;
			height:30px;
			color: #000;
			font-size:29px;
			cursor:pointer;
		}
		.link-btoc a:hover {
			background-color: #DF4B88;			
			color: #fff;
		}
		/* responsive */

			@media (max-width: 767px) {
				section.about-us p {
					font-size: 20px;
				}
				.link-btoc a {
					font-size:16px;
					padding:10px 10px;
				}
				section.about-us .row { margin: 0;}

			}


		/* 4 B2B */
		section.btob {
			background: url(images/cityNight.jpg)  center center repeat-y;
			background-position: center top;
    		background-size: cover;		
    		padding-top:85px;					
		}

		section.btob p {
			color: #fff;
			font-size: 29px;
			text-align: center;
			line-height:1.2;
			margin-bottom: 90px;
		}

		section.btob p.second-text,
		section.btob .section-header {
			margin-bottom:90px;
		}

		.link-btob {
			display:block;
			margin-bottom:180px;
		}
		.link-btob a {
			text-align:center;
			background-color: white;
			padding:15px 25px;
			height:30px;
			color: #000;
			font-size:29px;
			cursor:pointer;
		}
		.link-btob a:hover {
			background-color: #DF4B88;			
			color: #fff;
		}

		/* responsive */
			@media (max-width: 767px) {
				section.btob p {
					font-size: 20px;
				}
				.link-btob a {
					font-size:16px;
					padding:10px 10px;
				}
			}

		/* 5 News */

		.latest-news .latesnews-content { 
			text-align:left;			
		}
		.latest-news .date-news {
			border-bottom:1px solid #BFBFBF;
			padding-top:2px;
			padding-bottom: 8px;
		}
		.latest-news .date-news .day {
			color: #DF4B88;
			font-size: 28px;
			padding-right:5px;
		}
		.latest-news .date-news .date {
			color: #000;
			font-size: 14px;
		}
		.latest-news .title-news{
			padding-bottom:38px;
		}
		.latest-news .title-news a{
			color: #000;
			font-size: 26px;
		}
		.latest-news #carousel-homepage-latestnews .carousel-inner .item .latestnews-title {
			margin-top: 0;	
		}
		.latest-news .latestnews-box:first-child {
			padding-bottom:40px;

		}
		.latest-news .latestnews-box:first-child .hr{
			width: 300px;
			border-bottom: 1px solid #BFBFBF;
			display: inline-block;
		}
		.latest-news .carousel-control { 
			margin-top: -80px;
		}
		
		/* responsive */
		@media (max-width: 767px) {
			.latest-news .latesnews-content p { 
				padding-top: 20px;		
				}
			.news-zone { 
				width: 80px; 
				margin: 0 auto;
				}
			.latest-news .date-news {
				border-bottom:1px solid #BFBFBF;
				padding-top:2px;
				padding-bottom: 0;
				}
			.latest-news #carousel-homepage-latestnews .carousel-inner .item .latestnews-title a{ 
				color: #000;
				padding-top: 20px;				
				}
				#carousel-homepage-latestnews .carousel-inner .item .latestnews-title {
					position: static;
					margin-bottom: 0;
				}

			}


		/* 6 Jobs*/
		section.home-jobs {
			background: url(images/buildingNight.jpg)  center center repeat-y;
			background-position: center top;
    		background-size: cover;		
    		padding-top:85px;					
		}
		section.home-jobs .section-header p {
			font-size: 24px;
			padding-top:20px;
		}
		section.home-jobs .darken {
			background:rgba(0,0,0,0.68);
			height: 600px;
			max-height: 600px;
			margin-bottom: 50px;
		}
		section.home-jobs .nav-tabs > li.active > a,
	 	section.home-jobs .nav-tabs > li.active > a:hover,
	 	section.home-jobs .nav-tabs > li.active > a:focus{
			background:none;
			border-color: transparent;
			color: #fff;
		}
		section.home-jobs a{
			color: #6a6a6a;
		}
		section.home-jobs ul{
			margin-left: 0;
		}
		section.home-jobs .nav li{
			float:none;
			display:inline-block;
		}
		section.home-jobs .hr{
			height:1px;
			width:400px;
			display:block;
			background-color: #6a6a6a;
			margin: 0 auto;

		}
		section.home-jobs .nav li a{
			display:inline-block;
			float:none;
		}
		section.home-jobs .nav-tabs{
			border:none;
		}
		section.home-jobs .title-news{
			float:left;
			font-size:20px;
			padding-top:20px;
		}
		section.home-jobs .tab-pane p{
			float:left;
			text-align: left;
			font-size:16px;
			color: #C9C9C9;
			padding-top:20px;
			padding-left: 20px;
			width:800px;
			height:120px;
			overflow: hidden;
			text-overflow: ellipsis;
			white-space: nowrap;			
		}

		section.home-jobs .tab-pane a{
			float:right;
			font-size:16px;
			color: #fff;
			font-weight: bold;
			padding-top:20px;
			padding-right:20px;
		}
		section.home-jobs .tab-pane a:hover{
			text-decoration: underline;
		}

		/* responsive */

			@media (min-width: 768px) and (max-width: 991px) {
				section.home-jobs .tab-pane p{
					width:80%;
					height:80px;
				}
				section.home-jobs .title-news {
					text-align: left;
				}
			}
			@media (max-width: 767px) {		
				section.home-jobs .tab-pane p{
					width:80%;
					height:40px;
				}
				section.home-jobs .title-news {
					text-align: left;
				}
			}

		/* 7 Nos Services */
		.our-services {
			background-color: #fff;
			padding-top: 85px;
			padding-bottom: 45px;	
		}
		.our-services h2{
			color: #404040;
		}
		.our-services .col-lg-12 {
			margin-bottom:75px;
		}

		/* responsive */
			@media (min-width: 768px) and (max-width: 991px) {
				.our-services img {
					width:25%;
					padding-bottom: 10px;
				}
			}
			@media (max-width: 767px) {		
				.our-services img {
					width:55%;
					padding-bottom: 10px;
				}
				.group-home .row { 
					margin: 0;
				}
				.group-home .services-top { 
					margin-bottom: 60px;
				}
			}


		/* Footer */
		.footer .return p{
			float:right;
			padding-top: 20px;
			color: #CECECE;
			font-size: 12px;
			padding-right: 35px;
		}
		.footer .linkedin img{
			float:left;
			padding-left:35px;
		}
		.footer .link-footer span{
			float:left;
			padding-bottom: 45px;
			padding-left: 30px;
		}
		.footer .link-footer span a{
			color: #FFFFFF;
			padding: 0 10px;
			font-size: 17px;
		}
		.footer .link-menu{
			border-bottom: 1px solid #353535;
		}
		.footer .link-menu ul{
			float:left;
			margin: 0;
			padding-top:30px;
			padding-bottom: 10px;
		}
		.footer .link-menu li{
			display: inline;
			padding-right: 40px;
			padding-bottom: 10px;
			padding-left:35px;
		}
		.footer .link-menu li a{
			font-size: 20px;
			color: #CECECE;
		}
		.footer .mentions span{
			float:right;
			padding: 30px;
		}
		.footer .mentions p{
			display: inline;
			padding-left: 35px;
			font-size: 17px;
			color: #868686;
		}
		.footer .mentions a{
			display: inline;
			padding-right: 35px;
			font-size: 17px;
			color: #868686;
		}

		/* Responsive */
		@media (max-width: 767px) {			
		
		}

	
	/* B° End Home ----------------------------------------------------------------------
	-------------------------------------------------------------------------------------*/ 










	/* C° Page Groupe */
	.group-page .header-content-wrap{
			background: url(images/peopleColor.jpg)  center center repeat-y;
			background-position: center top;
    		background-size: cover;					
		}

	.group-page .zone {
		color: #DF4B88;
		font-weight: bold;
		display:inline;
		font-size: 30px;
	}

	/* C° Page btoc */
	.btoc-page .header-content-wrap{
			background: url(images/peopleColor.jpg)  center center repeat-y;
			background-position: center top;
    		background-size: cover;					
		}

	.btoc-page .device{
			background: url(images/peopleColor.jpg)  center center repeat-y;
			background-position: center top;
    		background-size: cover;					
		}













	/* General Demo Style */
	*,
	*:after,
	*:before {
		-webkit-box-sizing: border-box;
		-moz-box-sizing: border-box;
		box-sizing: border-box;
		padding: 0;
		margin: 0;
	}

	/* Clearfix hack by Nicolas Gallagher: http://nicolasgallagher.com/micro-clearfix-hack/ */
	.clearfix:before,
	.clearfix:after {
	    content: " ";
	    display: table;
	}

	.clearfix:after {
	    clear: both;
	}

	.clearfix {
	    *zoom: 1;
	}

	.og-grid {
		list-style: none;
		padding: 20px 0;
		margin: 0 auto;
		text-align: center;
		width: 100%;
	}

	.og-grid li {
		display: inline-block;
		margin: 10px 5px 0 5px;
		vertical-align: top;
		height: 250px;
	}

	.og-grid li > a,
	.og-grid li > a img {
		border: none;
		outline: none;
		display: block;
		position: relative;
	}

	.og-grid li.og-expanded > a::after {
		top: auto;
		border: solid transparent;
		content: " ";
		height: 0;
		width: 0;
		position: absolute;
		pointer-events: none;
		border-bottom-color: #d4d4d4;
		border-width: 15px;
		left: 50%;
		margin: -20px 0 0 -15px;
	}

	.og-expander {
		position: absolute;
		background: #d4d4d4;
		top: auto;
		left: 0;
		width: 100%;
		margin-top: 10px;
		text-align: left;
		height: 0;
		overflow: hidden;
	}

	.og-expander-inner {
		padding: 50px 30px;
		height: 100%;
	}

	.og-close {
		position: absolute;
		width: 40px;
		height: 40px;
		top: 20px;
		right: 20px;
		cursor: pointer;
	}

	.og-close::before,
	.og-close::after {
		content: '';
		position: absolute;
		width: 100%;
		top: 50%;
		height: 1px;
		background: #888;
		-webkit-transform: rotate(45deg);
		-moz-transform: rotate(45deg);
		transform: rotate(45deg);
	}

	.og-close::after {
		-webkit-transform: rotate(-45deg);
		-moz-transform: rotate(-45deg);
		transform: rotate(-45deg);
	}

	.og-close:hover::before,
	.og-close:hover::after {
		background: #333;
	}

	.og-fullimg,
	.og-details {
		width: 50%;
		float: left;
		height: 100%;
		overflow: hidden;
		position: relative;
	}

	.og-details {
		padding: 0 40px 0 20px;
	}

	.og-fullimg {
		text-align: center;
	}

	.og-fullimg img {
		display: inline-block;
		max-height: 100%;
		max-width: 100%;
	}

	.og-details h3 {
		font-weight: 300;
		font-size: 52px;
		padding: 40px 0 10px;
		margin-bottom: 10px;
	}

	.og-details p {
		font-weight: 300;
		font-size: 20px;
		line-height: 26px;
		color: #888;
		word-spacing: 1px;
	}

	.og-details p strong {
		font-weight: 400;
		font-size: 24px;
	}

	.og-details p em {
		font-size: 22px;
	}

	.og-details a {
		font-weight: 700;
		font-size: 16px;
		color: #444;
		text-transform: uppercase;
		letter-spacing: 2px;
		padding: 10px 20px;
		border: 3px solid #444;
		display: inline-block;
		margin: 30px 0 0;
		outline: none;
	}

	.og-details a::before {
		content: '\2192';
		display: inline-block;
		margin-right: 10px;
	}

	.og-details a:hover {
		border-color: #111;
		color: #000;
	}

	.og-loading {
		width: 20px;
		height: 20px;
		border-radius: 50%;
		background: #d4d4d4;
		box-shadow: 0 0 1px #ccc, 15px 30px 1px #ccc, -15px 30px 1px #ccc;
		position: absolute;
		top: 50%;
		left: 50%;
		margin: -25px 0 0 -25px;
		-webkit-animation: loader 0.5s infinite ease-in-out both;
		-moz-animation: loader 0.5s infinite ease-in-out both;
		animation: loader 0.5s infinite ease-in-out both;
	}

	@-webkit-keyframes loader {
		0% { background: #d4d4d4; }
		33% { background: #ccc; box-shadow: 0 0 1px #ccc, 15px 30px 1px #ccc, -15px 30px 1px #d4d4d4; }
		66% { background: #ccc; box-shadow: 0 0 1px #ccc, 15px 30px 1px #d4d4d4, -15px 30px 1px #ccc; }
	}

	@-moz-keyframes loader {
		0% { background: #d4d4d4; }
		33% { background: #ccc; box-shadow: 0 0 1px #ccc, 15px 30px 1px #ccc, -15px 30px 1px #d4d4d4; }
		66% { background: #ccc; box-shadow: 0 0 1px #ccc, 15px 30px 1px #d4d4d4, -15px 30px 1px #ccc; }
	}

	@keyframes loader {
		0% { background: #d4d4d4; }
		33% { background: #ccc; box-shadow: 0 0 1px #ccc, 15px 30px 1px #ccc, -15px 30px 1px #d4d4d4; }
		66% { background: #ccc; box-shadow: 0 0 1px #ccc, 15px 30px 1px #d4d4d4, -15px 30px 1px #ccc; }
	}

	@media screen and (max-width: 830px) {

		.og-expander h3 { font-size: 32px; }
		.og-expander p { font-size: 13px; }
		.og-expander a { font-size: 12px; }

	}

	@media screen and (max-width: 650px) {

		/*.og-fullimg { display: none; }*/
		.og-fullimg { float: none; width: 55%; margin: auto; height: auto;}
		.og-details h3 { padding-top: 10px; }
		/*.og-expander { height: 200%; }*/
		.og-expander-inner { height: 200%; }
		.og-details { float: none; width: 100%; }
		
	}

