
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="profile" href="http://gmpg.org/xfn/11">
<link rel="pingback" href="https://pybeebee.wordpress.com/xmlrpc.php">

<title>Meet ARGO! Part 1</title>
<script type="text/javascript">
  WebFontConfig = {"google":{"families":["Cinzel:b:latin,latin-ext","Quattrocento+Sans:r,i,b,bi:latin,latin-ext"]}};
  (function() {
    var wf = document.createElement('script');
    wf.src = 'https://s0.wp.com/wp-content/plugins/custom-fonts/js/webfont.js';
    wf.type = 'text/javascript';
    wf.async = 'true';
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(wf, s);
	})();
</script><style id="jetpack-custom-fonts-css">.wf-active body, .wf-active button, .wf-active input, .wf-active select, .wf-active textarea{font-family:"Quattrocento Sans",sans-serif}.wf-active code, .wf-active kbd, .wf-active tt, .wf-active var{font-family:"Quattrocento Sans",sans-serif}.wf-active button, .wf-active input[type="button"], .wf-active input[type="reset"], .wf-active input[type="submit"]{font-family:"Quattrocento Sans",sans-serif}.wf-active label{font-family:"Quattrocento Sans",sans-serif}.wf-active #infinite-handle span{font-family:"Quattrocento Sans",sans-serif}.wf-active .main-navigation{font-family:"Quattrocento Sans",sans-serif}.wf-active .comment-navigation a, .wf-active .post-navigation a, .wf-active .posts-navigation a{font-family:"Quattrocento Sans",sans-serif}.wf-active .site-description{font-family:"Quattrocento Sans",sans-serif}.wf-active .entry-footer, .wf-active .entry-meta{font-family:"Quattrocento Sans",sans-serif}.wf-active .page-links{font-family:"Quattrocento Sans",sans-serif}.wf-active .comments-area .comment-meta{font-family:"Quattrocento Sans",sans-serif}.wf-active .comments-area .comment-reply-link{font-family:"Quattrocento Sans",sans-serif}.wf-active #infinite-footer, .wf-active #infinite-footer .container{font-family:"Quattrocento Sans",sans-serif}.wf-active h1, .wf-active h2, .wf-active h3, .wf-active h4, .wf-active h5, .wf-active h6{font-family:"Cinzel",serif;font-weight:700;font-style:normal}.wf-active h1{font-size:30.1px;font-style:normal;font-weight:700}.wf-active h2{font-size:22.4px;font-style:normal;font-weight:700}.wf-active h3{font-size:14px;font-style:normal;font-weight:700}.wf-active h4{font-size:11.2px;font-style:normal;font-weight:700}.wf-active h5{font-size:9.1px;font-style:normal;font-weight:700}.wf-active h6{font-size:9.1px;font-style:normal;font-weight:700}@media screen and (min-width: 40.063em){.wf-active h1{font-size:44.1px;font-style:normal;font-weight:700}}@media screen and (min-width: 40.063em){.wf-active h2, .wf-active .single .entry-title{font-size:30.1px;font-style:normal;font-weight:700}}@media screen and (min-width: 40.063em){.wf-active h3{font-size:22.4px;font-style:normal;font-weight:700}}@media screen and (min-width: 40.063em){.wf-active h4{font-size:14px;font-style:normal;font-weight:700}}@media screen and (min-width: 40.063em){.wf-active h5{font-size:11.2px;font-style:normal;font-weight:700}}.wf-active .widget-title{font-size:11.2px;font-style:normal;font-weight:700}.wf-active .entry-title{font-size:22.4px;font-style:normal;font-weight:700}.wf-active .page-title{font-size:22.4px;font-style:normal;font-weight:700}.wf-active .site-title{font-size:44.1px;font-style:normal;font-weight:700}@media screen and (min-width: 50em){.wf-active .site-title{font-size:91px;font-style:normal;font-weight:700}}.wf-active .comments-area .comments-title{font-size:22.4px;font-style:normal;font-weight:700}</style>
<link rel='dns-prefetch' href='//s2.wp.com' />
<link rel='dns-prefetch' href='//s1.wp.com' />
<link rel='dns-prefetch' href='//s0.wp.com' />
<link rel='dns-prefetch' href='//fonts.googleapis.com' />
<link rel="alternate" type="application/rss+xml" title=" &raquo; Feed" href="https://pybeebee.wordpress.com/feed/" />
<link rel="alternate" type="application/rss+xml" title=" &raquo; Comments Feed" href="https://pybeebee.wordpress.com/comments/feed/" />
<link rel="alternate" type="application/rss+xml" title=" &raquo; Meet ARGO! Part&nbsp;1 Comments Feed" href="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/feed/" />
	<script type="text/javascript">
		/* <![CDATA[ */
		function addLoadEvent(func) {
			var oldonload = window.onload;
			if (typeof window.onload != 'function') {
				window.onload = func;
			} else {
				window.onload = function () {
					oldonload();
					func();
				}
			}
		}
		/* ]]> */
	</script>
			<script type="text/javascript">
			window._wpemojiSettings = {"baseUrl":"https:\/\/s0.wp.com\/wp-content\/mu-plugins\/wpcom-smileys\/twemoji\/2\/72x72\/","ext":".png","svgUrl":"https:\/\/s0.wp.com\/wp-content\/mu-plugins\/wpcom-smileys\/twemoji\/2\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/s1.wp.com\/wp-includes\/js\/wp-emoji-release.min.js?m=1532082729h&ver=4.9.8"}};
			!function(a,b,c){function d(a,b){var c=String.fromCharCode;l.clearRect(0,0,k.width,k.height),l.fillText(c.apply(this,a),0,0);var d=k.toDataURL();l.clearRect(0,0,k.width,k.height),l.fillText(c.apply(this,b),0,0);var e=k.toDataURL();return d===e}function e(a){var b;if(!l||!l.fillText)return!1;switch(l.textBaseline="top",l.font="600 32px Arial",a){case"flag":return!(b=d([55356,56826,55356,56819],[55356,56826,8203,55356,56819]))&&(b=d([55356,57332,56128,56423,56128,56418,56128,56421,56128,56430,56128,56423,56128,56447],[55356,57332,8203,56128,56423,8203,56128,56418,8203,56128,56421,8203,56128,56430,8203,56128,56423,8203,56128,56447]),!b);case"emoji":return b=d([55358,56760,9792,65039],[55358,56760,8203,9792,65039]),!b}return!1}function f(a){var c=b.createElement("script");c.src=a,c.defer=c.type="text/javascript",b.getElementsByTagName("head")[0].appendChild(c)}var g,h,i,j,k=b.createElement("canvas"),l=k.getContext&&k.getContext("2d");for(j=Array("flag","emoji"),c.supports={everything:!0,everythingExceptFlag:!0},i=0;i<j.length;i++)c.supports[j[i]]=e(j[i]),c.supports.everything=c.supports.everything&&c.supports[j[i]],"flag"!==j[i]&&(c.supports.everythingExceptFlag=c.supports.everythingExceptFlag&&c.supports[j[i]]);c.supports.everythingExceptFlag=c.supports.everythingExceptFlag&&!c.supports.flag,c.DOMReady=!1,c.readyCallback=function(){c.DOMReady=!0},c.supports.everything||(h=function(){c.readyCallback()},b.addEventListener?(b.addEventListener("DOMContentLoaded",h,!1),a.addEventListener("load",h,!1)):(a.attachEvent("onload",h),b.attachEvent("onreadystatechange",function(){"complete"===b.readyState&&c.readyCallback()})),g=c.source||{},g.concatemoji?f(g.concatemoji):g.wpemoji&&g.twemoji&&(f(g.twemoji),f(g.wpemoji)))}(window,document,window._wpemojiSettings);
		</script>
		<style type="text/css">
img.wp-smiley,
img.emoji {
	display: inline !important;
	border: none !important;
	box-shadow: none !important;
	height: 1em !important;
	width: 1em !important;
	margin: 0 .07em !important;
	vertical-align: -0.1em !important;
	background: none !important;
	padding: 0 !important;
}
</style>
	<link rel='stylesheet' id='all-css-0-1' href='https://s1.wp.com/_static/??-eJyFUdFuwyAM/KFRVnXttIdp3wLEbdxgQBiW9e/nJFuktRF7iezjzne66DEpF0OBUDRVlXy9YGA9JhdJMaGH2922c8xPelvG1bLLmApG2c7R+zi2+H38hKxstdaDqMvNw0rH4HztBBZAd4Z7lAO8IwyPlCvrIu+DjV/r0PL1OEwqKMm4Qc1bi246cVXW5J8m1n0RoQ6xzOnWoXXNxQyCUzJlYhB0aMADCa0lo3T6VU1jL8mbNktUa1MGZiVfwkqq9GL0TzyaoiytzOX/QR6ky0WdqtXArhbXQwx3/3LD5gIB8lLa5jhpP+h9fzwc9m+vp+eX6zdyaQGC?cssminify=yes' type='text/css' media='all' />
<style id='wpcom-admin-bar-inline-css' type='text/css'>

			.admin-bar {
				position: inherit !important;
				top: auto !important;
			}
			.admin-bar .goog-te-banner-frame {
				top: 32px !important
			}
			@media screen and (max-width: 782px) {
				.admin-bar .goog-te-banner-frame {
					top: 46px !important;
				}
			}
			@media screen and (max-width: 480px) {
				.admin-bar .goog-te-banner-frame {
					position: absolute;
				}
			}
		
</style>
<link rel='stylesheet' id='escutcheon-fonts-css'  href='https://fonts.googleapis.com/css?family=Oswald%3A400%2C300%2C700%7CAlegreya+Sans%3A400%2C400italic%2C700%2C700italic&#038;subset=latin%2Clatin-ext' type='text/css' media='all' />
<link rel='stylesheet' id='all-css-2-1' href='https://s2.wp.com/_static/??-eJyNkFFOAzEMRC+EcUsp4gdxFm/WTQNOHCVOV9yeLEJi20oRfx55nj02LhmcJuNkaGeOXDG3Cbm6Zu7MmjAkh9W+hGHJTuOjq/UBN1RskKX5kCpWdYEEIqe2rUfIEmbPVpFb7+pnYBBa0DhmIethfjb/Z8DvvtAt12IEe1YQdWShH7oVcBIKZYQmXePRHEOCiQpcnkbuwpOo76XH7trIEWRaoXDWYnDSEm/1HbrO/PuLlpnmfqLoRLJ63+Pb/ng4vLzuds/7j28MAb1b?cssminify=yes' type='text/css' media='all' />
<link rel='stylesheet' id='print-css-3-1' href='https://s2.wp.com/wp-content/mu-plugins/global-print/global-print.css?m=1465851035h&cssminify=yes' type='text/css' media='print' />
<link rel='stylesheet' id='all-css-4-1' href='https://s0.wp.com/_static/??-eJx9TssOwjAM+yFKgMG0C+Jbsq60QW0yNRn8PtsBEELs5Idsy/AYnRe2wAZlcmOeIrECDoXY9VihoFqoM3NyD7XSEPTjbb3qBv5MeCPhZeLN1uKjqLlrRqqgCStxfOFaS8UTZpclyrf4KVkKZb6ejhCz9JiXwKWc96em3XWHtuluTyr0Y1E=?cssminify=yes' type='text/css' media='all' />
<script type='text/javascript' src='https://s2.wp.com/_static/??-eJx9kFEKwjAMQC9kVycT9yOeZavZyGyb2qQbenr7MRFHFQIh5JHkRS9BoTc2XYH1lOOeID7WVE280/8A5XCMnUDl0L9hQ17Ai3ZJBZtG9Kw59WwiBkHK1UDW0rLF8+hALA6YuxEKXUc9WlCJIWbAS75qoAL3bYB+Rigt24iChM7cVATGJ5S8OXwUfz9spS7uXDft6dDWx2Y/vQBJS4U5'></script>
<link rel='stylesheet' id='all-css-0-2' href='https://s0.wp.com/wp-content/mu-plugins/highlander-comments/style.css?m=1530132353h&cssminify=yes' type='text/css' media='all' />
<!--[if lt IE 8]>
<link rel='stylesheet' id='highlander-comments-ie7-css'  href='https://s2.wp.com/wp-content/mu-plugins/highlander-comments/style-ie7.css?m=1351637563h&#038;ver=20110606' type='text/css' media='all' />
<![endif]-->
<link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://pybeebee.wordpress.com/xmlrpc.php?rsd" />
<link rel="wlwmanifest" type="application/wlwmanifest+xml" href="https://s1.wp.com/wp-includes/wlwmanifest.xml" /> 
<link rel='prev' title='Delivery! Python-Compatible Packages for Emotion&nbsp;Recognition' href='https://pybeebee.wordpress.com/2017/05/27/delivery-python-compatible-packages-for-emotion-recognition/' />
<link rel='next' title='Meet ARGO! Part&nbsp;2' href='https://pybeebee.wordpress.com/2017/09/02/meet-argo-part-2/' />
<meta name="generator" content="WordPress.com" />
<link rel="canonical" href="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/" />
<link rel='shortlink' href='https://wp.me/p4UAtn-5d' />
<link rel="alternate" type="application/json+oembed" href="https://public-api.wordpress.com/oembed/?format=json&amp;url=https%3A%2F%2Fpybeebee.wordpress.com%2F2017%2F07%2F15%2Fconstructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation%2F&amp;for=wpcom-auto-discovery" /><link rel="alternate" type="application/xml+oembed" href="https://public-api.wordpress.com/oembed/?format=xml&amp;url=https%3A%2F%2Fpybeebee.wordpress.com%2F2017%2F07%2F15%2Fconstructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation%2F&amp;for=wpcom-auto-discovery" />
<!-- Jetpack Open Graph Tags -->
<meta property="og:type" content="article" />
<meta property="og:title" content="Meet ARGO! Part 1" />
<meta property="og:url" content="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/" />
<meta property="og:description" content="Meet ARGO, an emotionally intelligent robot made of Legos. ARGO (Anthropomorphic Recognition and Generation Objective) is a multi-system robot that can be trained to recognize and generate facial e…" />
<meta property="article:published_time" content="2017-07-15T22:30:26+00:00" />
<meta property="article:modified_time" content="2018-01-03T16:35:52+00:00" />
<meta property="og:image" content="https://pybeebee.files.wordpress.com/2017/05/img_36692.jpg" />
<meta property="og:image:width" content="1979" />
<meta property="og:image:height" content="2181" />
<meta property="og:locale" content="en_US" />
<meta name="twitter:site" content="@wordpressdotcom" />
<meta name="twitter:text:title" content="Meet ARGO! Part&nbsp;1" />
<meta name="twitter:card" content="summary" />
<meta property="fb:app_id" content="249643311490" />
<meta property="article:publisher" content="https://www.facebook.com/WordPresscom" />

<!-- End Jetpack Open Graph Tags -->
<link rel='openid.server' href='https://pybeebee.wordpress.com/?openidserver=1' />
<link rel='openid.delegate' href='https://pybeebee.wordpress.com/' />
<link rel="search" type="application/opensearchdescription+xml" href="https://pybeebee.wordpress.com/osd.xml" title="" />
<link rel="search" type="application/opensearchdescription+xml" href="https://s1.wp.com/opensearch.xml" title="WordPress.com" />
<meta name="theme-color" content="#262626" />
		<style type="text/css">
			.recentcomments a {
				display: inline !important;
				padding: 0 !important;
				margin: 0 !important;
			}

			table.recentcommentsavatartop img.avatar, table.recentcommentsavatarend img.avatar {
				border: 0px;
				margin: 0;
			}

			table.recentcommentsavatartop a, table.recentcommentsavatarend a {
				border: 0px !important;
				background-color: transparent !important;
			}

			td.recentcommentsavatarend, td.recentcommentsavatartop {
				padding: 0px 0px 1px 0px;
				margin: 0px;
			}

			td.recentcommentstextend {
				border: none !important;
				padding: 0px 0px 2px 10px;
			}

			.rtl td.recentcommentstextend {
				padding: 0px 10px 2px 0px;
			}

			td.recentcommentstexttop {
				border: none;
				padding: 0px 0px 0px 10px;
			}

			.rtl td.recentcommentstexttop {
				padding: 0px 10px 0px 0px;
			}
		</style>
		<meta name="application-name" content="WordPress.com" /><meta name="msapplication-window" content="width=device-width;height=device-height" /><meta name="msapplication-tooltip" content="Fresh Topics in Mathematics and Artificial Intelligence" /><meta name="msapplication-task" content="name=Edit post;action-uri=https://wordpress.com/post/pybeebee.wordpress.com/323;icon-uri=https://s2.wp.com/i/icons/post.ico" /><meta name="msapplication-task" content="name=Write a post;action-uri=https://wordpress.com/post/pybeebee.wordpress.com;icon-uri=https://s2.wp.com/i/icons/post.ico" /><meta name="msapplication-task" content="name=Moderate comments;action-uri=https://pybeebee.wordpress.com/wp-admin/edit-comments.php?comment_status=moderated;icon-uri=https://s2.wp.com/i/icons/comment.ico" /><meta name="msapplication-task" content="name=Upload new media;action-uri=https://pybeebee.wordpress.com/wp-admin/media-new.php;icon-uri=https://s2.wp.com/i/icons/media.ico" /><meta name="msapplication-task" content="name=Blog stats;action-uri=https://pybeebee.wordpress.com/wp-admin/index.php?page=stats;icon-uri=https://s1.wp.com/i/icons/stats.ico" /><meta name="description" content="Meet ARGO, an emotionally intelligent robot made of Legos. ARGO (Anthropomorphic Recognition and Generation Objective) is a multi-system robot that can be trained to recognize and generate facial expressions. I built ARGO as part of my science fair project this year to investigate the field of Emotion Artificial Intelligence." />
<style type="text/css" id="custom-background-css">
body.custom-background { background-color: #262626; }
</style>
	<link rel="amphtml" href="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/amp/"><style type="text/css" media="print">#wpadminbar { display:none; }</style>
	<style type="text/css" media="screen">
	html { margin-top: 32px !important; }
	* html body { margin-top: 32px !important; }
	@media screen and ( max-width: 782px ) {
		html { margin-top: 46px !important; }
		* html body { margin-top: 46px !important; }
	}
</style>
	<style type="text/css" id="syntaxhighlighteranchor"></style>
<style type="text/css" id="custom-colors-css">.highlander-dark #respond #comment-form-comment textarea,.highlander-dark #comment-form-share-text-padder textarea,#respond #comment-form-comment,#comment-form-share-text-padder,.highlander-dark #respond .comment-form-service,.highlander-dark #respond .comment-form-fields div.comment-form-input{text-shadow:none !important;box-shadow:none !important}.highlander-dark #respond #comment-form-comment,.highlander-dark #respond #comment-form-comment.active,.highlander-dark #comment-form-share-text-padder:active{border:4px solid}.highlander-dark #respond #comment-form-identity{border-top:0}.jetpack_widget_social_icons a:hover,.widget_wpcom_social_media_icons_widget a:hover{color:inherit}@media screen and (max-width:50em){.main-navigation ul ul{background-color:transparent !important}}.comment-navigation a:hover,.posts-navigation a:hover,.post-navigation a:hover,.comment-navigation a:hover:visited,.posts-navigation a:hover:visited,.post-navigation a:hover:visited,button:hover,input[type=button]:hover,input[type=reset]:hover,input[type=submit]:hover{color:#595959}#infinite-footer,#infinite-footer .container,button,input[type=button],input[type=reset],input[type=submit],.highlander-dark #respond #comment-form-comment textarea,.highlander-dark #comment-form-share-text-padder textarea,.highlander-dark #respond .comment-form-fields div.comment-form-input{color:#fff}body,button,input,select,textarea,.blog .entry-title a:hover,.archive .entry-title a:hover,.search .entry-title a:hover,h3.sd-title,.main-navigation a:hover,.main-navigation a:visited:hover,#infinite-handle span{color:#eee}.highlander-dark #respond label,.highlander-dark #respond .comment-form-service a,.highlander-dark #respond .comment-form-fields p.comment-form-posting-as,.highlander-dark #respond .comment-form-fields p.comment-form-log-out{color:#aaa}.comment-navigation a,.posts-navigation a,.post-navigation a,.comment-navigation a:visited,.posts-navigation a:visited,.post-navigation a:visited{color:#aaa}.entry-meta a,.entry-footer a,.entry-meta a:visited,.entry-footer a:visited,.entry-meta,.entry-footer,.main-navigation a,.main-navigation a:visited,.comments-area .comments-title,.comments-area .comment-meta a,.comments-area .comment-meta a:visited,.comments-area .comment-meta,.site-footer a,.site-footer a:visited,.page-title{color:#aaa}input[type=text]:focus,input[type=email]:focus,input[type=url]:focus,input[type=password]:focus,input[type=search]:focus,textarea:focus{border-color:#aaa}input[type=text]:focus,input[type=email]:focus,input[type=url]:focus,input[type=password]:focus,input[type=search]:focus,textarea:focus,select,input[type=number]:focus,input[type=tel]:focus,input[type=range]:focus,input[type=date]:focus,input[type=month]:focus,input[type=week]:focus,input[type=time]:focus,input[type=datetime]:focus,input[type=datetime-local]:focus,input[type=color]:focus{color:#aaa}#infinite-footer .blog-info a,#infinite-footer .blog-credits a,#infinite-footer .container .blog-info a,#infinite-footer .container .blog-credits a,#infinite-footer .blog-info a:hover,#infinite-footer .blog-credits a:hover,#infinite-footer .container .blog-info a:hover,#infinite-footer .container .blog-credits a:hover{color:#969696}body,button,input[type=text],input[type=email],input[type=url],input[type=password],input[type=search],select,textarea,#infinite-footer,#infinite-footer .container{background-color:#262626}.main-navigation ul ul,.single .entry-meta:before,.site-title:after,.comments-area:after,.comments-area:before,.site-footer:before,.page-header:after{background-color:#131313}.main-navigation ul ul>li:first-of-type:before{border-bottom-color:#131313}.highlander-dark #respond #comment-form-identity,.highlander-dark #respond #comment-form-comment,.highlander-dark #comment-form-share-text-padder,.highlander-dark #respond .comment-form-fields div.comment-form-input{background-color:#262626}blockquote,q,input[type=text],input[type=email],input[type=url],input[type=password],input[type=search],select,textarea,input[type=number],input[type=tel],input[type=range],input[type=date],input[type=month],input[type=week],input[type=time],input[type=datetime],input[type=datetime-local],input[type=color],.comments-area .comment-list>.parent,th,td{border-color:#131313}input[type=text],input[type=email],input[type=url],input[type=password],input[type=search],textarea,input[type=number],input[type=tel],input[type=range],input[type=date],input[type=month],input[type=week],input[type=time],input[type=datetime],input[type=datetime-local],input[type=color]{color:#131313}.highlander-dark #respond #comment-form-comment,.highlander-dark #respond #comment-form-comment.active,.highlander-dark #comment-form-share-text-padder:active,.highlander-dark #respond .comment-form-fields div.comment-form-input{border-color:#131313}a,a:visited,a:hover,.comments-area .comment-reply-link,.comments-area .comment-reply-link:visited,.entry-meta a:hover,.entry-footer a:hover,.comments-area .comment-meta a:hover{color:#d1e751}.jetpack-social-navigation a:hover,.site-title,.site-title a:hover,.site-title a:visited,.entry-title a,.entry-title a:visited,.entry-title{color:#d1e751}.comment-navigation a,.posts-navigation a,.post-navigation a,button,input[type=button],input[type=reset],input[type=submit],button:hover,input[type=button]:hover,input[type=reset]:hover,input[type=submit]:hover,button,input[type=button],input[type=reset],input[type=submit],button:focus,input[type=button]:focus,input[type=reset]:focus,input[type=submit]:focus,button,input[type=button],input[type=reset],input[type=submit],button:active,input[type=button]:active,input[type=reset]:active,input[type=submit]:active,#infinite-handle span,#infinite-handle span:hover{border-color:#d1e751}.comment-navigation a:hover,.posts-navigation a:hover,.post-navigation a:hover{background-color:#d1e751}.main-navigation a:after,.entry-title a:after,button:hover,input[type=button]:hover,input[type=reset]:hover,input[type=submit]:hover{background-color:#d1e751}</style>
<link rel="icon" href="https://pybeebee.files.wordpress.com/2017/10/cropped-mecat.jpg?w=32" sizes="32x32" />
<link rel="icon" href="https://pybeebee.files.wordpress.com/2017/10/cropped-mecat.jpg?w=192" sizes="192x192" />
<link rel="apple-touch-icon-precomposed" href="https://pybeebee.files.wordpress.com/2017/10/cropped-mecat.jpg?w=180" />
<meta name="msapplication-TileImage" content="https://pybeebee.files.wordpress.com/2017/10/cropped-mecat.jpg?w=270" />
</head>

<body class="post-template-default single single-post postid-323 single-format-standard logged-in admin-bar no-customize-support custom-background mp6 customizer-styles-applied highlander-enabled highlander-dark">
<div id="page" class="hfeed site">
	<a class="skip-link screen-reader-text" href="#content">Skip to content</a>

	<header id="masthead" class="site-header" role="banner">
		<div class="navigation-wrapper">
					<nav class="jetpack-social-navigation jetpack-social-navigation-genericons" role="navigation" aria-label="Social Links Menu">
			<div class="menu-social-links-container"><ul id="menu-social-links" class="menu"><li id="menu-item-76" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-76"><a href="http://twitter.com/pybeebee"><span class="screen-reader-text">Twitter</span></a></li>
<li id="menu-item-78" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-78"><a href="http://facebook.com/pybeebee"><span class="screen-reader-text">Facebook</span></a></li>
<li id="menu-item-80" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-80"><a href="http://linkedin.com/in/gabrielleliu"><span class="screen-reader-text">LinkedIn</span></a></li>
<li id="menu-item-569" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-569"><a href="https://github.com/pybeebee"><span class="screen-reader-text">GitHub</span></a></li>
</ul></div>		</nav><!-- .jetpack-social-navigation -->
				<nav id="site-navigation" class="main-navigation" role="navigation">
				<button class="menu-toggle" aria-controls="primary-menu" aria-expanded="false">Menu</button>
							</nav><!-- #site-navigation -->
		</div>

		<div class="site-branding">
							<a href="https://pybeebee.wordpress.com/" rel="home">
					<img src="https://pybeebee.files.wordpress.com/2017/10/cropped-bg7small.jpg" width="1080" height="300" alt="" class="custom-header">
				</a>
									<h1 class="site-title"><a href="https://pybeebee.wordpress.com/" rel="home"></a></h1>
			<h2 class="site-description">Fresh Topics in Mathematics and Artificial Intelligence</h2>
		</div><!-- .site-branding -->

	</header><!-- #masthead -->

	<div id="content" class="site-content">
	<div id="primary" class="content-area">
		<main id="main" class="site-main" role="main">

		
				<article id="post-323" class="post-323 post type-post status-publish format-standard hentry category-uncategorized">

		<header class="entry-header">
			<div class="entry-meta">
				<span class="byline"> Written by <span class="author vcard"><a class="url fn n" href="https://pybeebee.wordpress.com/author/pybeebee/">Gabrielle Liu</a></span></span><span class="posted-on"><a href="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/" rel="bookmark"><time class="entry-date published" datetime="2017-07-15T16:30:26+00:00">July 15, 2017</time><time class="updated" datetime="2018-01-03T10:35:52+00:00">January 3, 2018</time></a></span>			</div><!-- .entry-meta -->
			<h1 class="entry-title">Meet ARGO! Part&nbsp;1</h1>		</header><!-- .entry-header -->

		
		<div class="entry-wrapper">

			<div class="entry-content">
				<p>Meet ARGO, an emotionally intelligent robot made of Legos.</p>
<p><img data-attachment-id="410" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/2017-03-17-10-38-12-3/" data-orig-file="https://pybeebee.files.wordpress.com/2017/02/2017-03-17-10-38-122.jpg" data-orig-size="1500,2000" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;2.2&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;iPhone 6 Plus&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;1489747092&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;4.15&quot;,&quot;iso&quot;:&quot;80&quot;,&quot;shutter_speed&quot;:&quot;0.25&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="2017-03-17 10.38.12" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/02/2017-03-17-10-38-122.jpg?w=225" data-large-file="https://pybeebee.files.wordpress.com/2017/02/2017-03-17-10-38-122.jpg?w=756" class="aligncenter size-full wp-image-410" src="https://pybeebee.files.wordpress.com/2017/02/2017-03-17-10-38-122.jpg?w=345" alt="2017-03-17 10.38.12.jpg" width="345" height="460" srcset="https://pybeebee.files.wordpress.com/2017/02/2017-03-17-10-38-122.jpg?w=345 345w, https://pybeebee.files.wordpress.com/2017/02/2017-03-17-10-38-122.jpg?w=690 690w, https://pybeebee.files.wordpress.com/2017/02/2017-03-17-10-38-122.jpg?w=113 113w, https://pybeebee.files.wordpress.com/2017/02/2017-03-17-10-38-122.jpg?w=225 225w" sizes="(max-width: 345px) 100vw, 345px" /></p>
<p>ARGO (Anthropomorphic Recognition and Generation Objective) is a multi-system robot that can be trained to recognize and generate facial expressions. I built ARGO as part of my science fair project this year to investigate the field of Emotion Artificial Intelligence. ARGO incorporates four key systems:</p>
<ol>
<li>Face detection and tracking</li>
<li>Facial expressions</li>
<li>Emotion recognition</li>
<li>Emotion generation</li>
</ol>
<p>In this post, I will describe the physical construction of ARGO using Legos and Mega Bloks. In the next post, I will discuss the software used to control the four systems of ARGO.</p>
<h3>Construction</h3>
<p>To start off, I wanted ARGO to move itself to track my face. My first attempt at building ARGO quickly led to a dead end &#8211; the “head” portion (indicated by yellow rectangle) couldn’t rotate!</p>
<figure data-shortcode="caption" id="attachment_396" style="width: 371px" class="wp-caption aligncenter"><img data-attachment-id="396" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/img_3669-3/" data-orig-file="https://pybeebee.files.wordpress.com/2017/05/img_36692.jpg?w=371&#038;h=409" data-orig-size="1979,2181" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;2.2&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;iPhone 5s&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;1485712572&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;4.15&quot;,&quot;iso&quot;:&quot;320&quot;,&quot;shutter_speed&quot;:&quot;0.033333333333333&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="IMG_3669" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/05/img_36692.jpg?w=371&#038;h=409?w=272" data-large-file="https://pybeebee.files.wordpress.com/2017/05/img_36692.jpg?w=371&#038;h=409?w=756" class="  wp-image-396 aligncenter" src="https://pybeebee.files.wordpress.com/2017/05/img_36692.jpg?w=371&#038;h=409" alt="IMG_3669.jpg" width="371" height="409" srcset="https://pybeebee.files.wordpress.com/2017/05/img_36692.jpg?w=371&amp;h=409 371w, https://pybeebee.files.wordpress.com/2017/05/img_36692.jpg?w=742&amp;h=818 742w, https://pybeebee.files.wordpress.com/2017/05/img_36692.jpg?w=136&amp;h=150 136w, https://pybeebee.files.wordpress.com/2017/05/img_36692.jpg?w=272&amp;h=300 272w" sizes="(max-width: 371px) 100vw, 371px" /><figcaption class="wp-caption-text">Initial design of ARGO.</figcaption></figure>
<p>After some tinkering, I developed a design that worked, which I describe below.</p>
<h3>Base</h3>
<p>I made ARGO&#8217;s base using my Mega Bloks and Legos that I&#8217;ve had since I was two years old.</p>
<figure data-shortcode="caption" id="attachment_339" style="width: 377px" class="wp-caption aligncenter"><img data-attachment-id="339" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/screen-shot-2017-05-01-at-8-58-59-pm/" data-orig-file="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-8-58-59-pm.png?w=377&#038;h=239" data-orig-size="363,230" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="Screen Shot 2017-05-01 at 8.58.59 PM" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-8-58-59-pm.png?w=377&#038;h=239?w=300" data-large-file="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-8-58-59-pm.png?w=377&#038;h=239?w=363" class="  wp-image-339 aligncenter" src="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-8-58-59-pm.png?w=377&#038;h=239" alt="Screen Shot 2017-05-01 at 8.58.59 PM.png" width="377" height="239" srcset="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-8-58-59-pm.png 363w, https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-8-58-59-pm.png?w=150&amp;h=95 150w, https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-8-58-59-pm.png?w=300&amp;h=190 300w" sizes="(max-width: 377px) 100vw, 377px" /><figcaption class="wp-caption-text">Mega Bloks (left) and Legos (right).</figcaption></figure>
<p>The base was made by stacking 3 rows of Mega Bloks.</p>
<figure data-shortcode="caption" id="attachment_342" style="width: 488px" class="wp-caption aligncenter"><img data-attachment-id="342" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/2017-05-01-20-14-16/" data-orig-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-14-16.jpg?w=488&#038;h=247" data-orig-size="2948,1492" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;2.2&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;iPhone 5s&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;1493669656&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;4.15&quot;,&quot;iso&quot;:&quot;320&quot;,&quot;shutter_speed&quot;:&quot;0.066666666666667&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="2017-05-01 20.14.16" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-14-16.jpg?w=488&#038;h=247?w=300" data-large-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-14-16.jpg?w=488&#038;h=247?w=756" class="  wp-image-342 aligncenter" src="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-14-16.jpg?w=488&#038;h=247" alt="2017-05-01 20.14.16.jpg" width="488" height="247" srcset="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-14-16.jpg?w=488&amp;h=247 488w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-14-16.jpg?w=976&amp;h=494 976w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-14-16.jpg?w=150&amp;h=76 150w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-14-16.jpg?w=300&amp;h=152 300w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-14-16.jpg?w=768&amp;h=389 768w" sizes="(max-width: 488px) 100vw, 488px" /><figcaption class="wp-caption-text">Completed base.</figcaption></figure>
<p>To mount ARGO on the base, I created a platform using Mega Bloks and Legos.</p>
<figure data-shortcode="caption" id="attachment_345" style="width: 404px" class="wp-caption aligncenter"><img data-attachment-id="345" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/2017-05-01-20-15-57/" data-orig-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-15-57.jpg" data-orig-size="2809,2399" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;2.2&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;iPhone 5s&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;1493669757&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;4.15&quot;,&quot;iso&quot;:&quot;320&quot;,&quot;shutter_speed&quot;:&quot;0.066666666666667&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="2017-05-01 20.15.57" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-15-57.jpg?w=300" data-large-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-15-57.jpg?w=756" class=" size-full wp-image-345 aligncenter" src="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-15-57.jpg?w=404" alt="2017-05-01 20.15.57.jpg" width="404" height="345" srcset="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-15-57.jpg?w=404 404w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-15-57.jpg?w=808 808w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-15-57.jpg?w=150 150w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-15-57.jpg?w=300 300w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-15-57.jpg?w=768 768w" sizes="(max-width: 404px) 100vw, 404px" /><figcaption class="wp-caption-text">Platform for head movement.</figcaption></figure>
<h3>Face Tracking</h3>
<p>We want ARGO to be able to move its head. I used pieces from a Lego Mindstorms NXT kit to build a platform for head movement. I used Mindstorms because it comes with the NXT Intelligent Brick that can be used to control NXT motors. I used two NXT motors- one for horizontal movement and another for vertical movement.</p>
<figure data-shortcode="caption" id="attachment_349" style="width: 329px" class="wp-caption aligncenter"><img data-attachment-id="349" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/2017-05-01-20-19-08/" data-orig-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-19-08.jpg?w=329&#038;h=247" data-orig-size="3264,2448" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;2.2&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;iPhone 5s&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;1493669948&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;4.15&quot;,&quot;iso&quot;:&quot;250&quot;,&quot;shutter_speed&quot;:&quot;0.041666666666667&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="2017-05-01 20.19.08" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-19-08.jpg?w=329&#038;h=247?w=300" data-large-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-19-08.jpg?w=329&#038;h=247?w=756" class="  wp-image-349 aligncenter" src="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-19-08.jpg?w=329&#038;h=247" alt="2017-05-01 20.19.08.jpg" width="329" height="247" srcset="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-19-08.jpg?w=329&amp;h=247 329w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-19-08.jpg?w=658&amp;h=494 658w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-19-08.jpg?w=150&amp;h=113 150w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-19-08.jpg?w=300&amp;h=225 300w" sizes="(max-width: 329px) 100vw, 329px" /><figcaption class="wp-caption-text">NXT Intelligent Brick.</figcaption></figure>
<p>I mounted the motors and camera on the platform. The gray and black NXT Lego piece (indicated by green box in image) allows for rotation of ARGO&#8217;s head. Movement of this piece is controlled by one NXT motor using a small gear.</p>
<figure data-shortcode="caption" id="attachment_352" style="width: 380px" class="wp-caption aligncenter"><img data-attachment-id="352" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/2017-05-01-20-20-30-2/" data-orig-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-20-301.jpg?w=380&#038;h=285" data-orig-size="3264,2448" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;2.2&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;iPhone 5s&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;1493670030&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;4.15&quot;,&quot;iso&quot;:&quot;320&quot;,&quot;shutter_speed&quot;:&quot;0.066666666666667&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="2017-05-01 20.20.30" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-20-301.jpg?w=380&#038;h=285?w=300" data-large-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-20-301.jpg?w=380&#038;h=285?w=756" class="  wp-image-352 aligncenter" src="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-20-301.jpg?w=380&#038;h=285" alt="2017-05-01 20.20.30.jpg" width="380" height="285" srcset="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-20-301.jpg?w=380&amp;h=285 380w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-20-301.jpg?w=760&amp;h=570 760w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-20-301.jpg?w=150&amp;h=113 150w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-20-301.jpg?w=300&amp;h=225 300w" sizes="(max-width: 380px) 100vw, 380px" /><figcaption class="wp-caption-text">Rotational platform for vertical and horizontal movement of ARGO.</figcaption></figure>
<h3>Facial Features</h3>
<p>ARGO has several facial features: two eyes, eyebrows, and a mouth. These features are used by ARGO to generate facial expressions that express emotion.</p>
<h4>Eyes</h4>
<p>To make the eyes, I used two white ping pong balls for the eyeballs, electrical tape for the irises, and easter eggs as eyelids. I wanted to make eyelids that could blink.</p>
<figure data-shortcode="caption" id="attachment_370" style="width: 623px" class="wp-caption aligncenter"><img data-attachment-id="370" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/2017-05-01-20-23-08-3/" data-orig-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-082.jpg?w=623&#038;h=249" data-orig-size="3215,1285" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;2.2&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;iPhone 5s&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;1493670188&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;4.15&quot;,&quot;iso&quot;:&quot;320&quot;,&quot;shutter_speed&quot;:&quot;0.066666666666667&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="2017-05-01 20.23.08" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-082.jpg?w=623&#038;h=249?w=300" data-large-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-082.jpg?w=623&#038;h=249?w=756" class="  wp-image-370 aligncenter" src="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-082.jpg?w=623&#038;h=249" alt="2017-05-01 20.23.08.jpg" width="623" height="249" srcset="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-082.jpg?w=623&amp;h=249 623w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-082.jpg?w=1246&amp;h=498 1246w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-082.jpg?w=150&amp;h=60 150w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-082.jpg?w=300&amp;h=120 300w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-082.jpg?w=768&amp;h=307 768w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-082.jpg?w=1024&amp;h=409 1024w" sizes="(max-width: 623px) 100vw, 623px" /><figcaption class="wp-caption-text">ARGO&#8217;s vision system.</figcaption></figure>
<p>To allow the eyelids to move in a blinking manner, a rod was first attached to the two eyelids. This rod acted as an axis of rotation for the eyelids. A servo motor was attached to the rod using a paperclip.</p>
<figure data-shortcode="caption" id="attachment_375" style="width: 145px" class="wp-caption aligncenter"><img data-attachment-id="375" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/2017-05-01-20-23-48/" data-orig-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-48.jpg?w=145&#038;h=153" data-orig-size="1747,1839" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;2.2&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;iPhone 5s&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;1493670228&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;4.15&quot;,&quot;iso&quot;:&quot;320&quot;,&quot;shutter_speed&quot;:&quot;0.05&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="2017-05-01 20.23.48" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-48.jpg?w=145&#038;h=153?w=285" data-large-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-48.jpg?w=145&#038;h=153?w=756" class="  wp-image-375 aligncenter" src="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-48.jpg?w=145&#038;h=153" alt="2017-05-01 20.23.48.jpg" width="145" height="153" srcset="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-48.jpg?w=145&amp;h=153 145w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-48.jpg?w=290&amp;h=306 290w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-48.jpg?w=142&amp;h=150 142w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-23-48.jpg?w=285&amp;h=300 285w" sizes="(max-width: 145px) 100vw, 145px" /><figcaption class="wp-caption-text">Ping pong eyeball.</figcaption></figure>
<figure data-shortcode="caption" id="attachment_380" style="width: 280px" class="wp-caption aligncenter"><img data-attachment-id="380" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/2017-05-01-20-24-57/" data-orig-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-24-57.jpg?w=280&#038;h=283" data-orig-size="2108,2127" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;2.2&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;iPhone 5s&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;1493670297&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;4.15&quot;,&quot;iso&quot;:&quot;320&quot;,&quot;shutter_speed&quot;:&quot;0.058823529411765&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="2017-05-01 20.24.57" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-24-57.jpg?w=280&#038;h=283?w=297" data-large-file="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-24-57.jpg?w=280&#038;h=283?w=756" class="  wp-image-380 aligncenter" src="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-24-57.jpg?w=280&#038;h=283" alt="2017-05-01 20.24.57" width="280" height="283" srcset="https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-24-57.jpg?w=280&amp;h=283 280w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-24-57.jpg?w=560&amp;h=566 560w, https://pybeebee.files.wordpress.com/2017/05/2017-05-01-20-24-57.jpg?w=297&amp;h=300 297w" sizes="(max-width: 280px) 100vw, 280px" /><figcaption class="wp-caption-text">Mounted eyeballs and eyelids.</figcaption></figure>
<h4>Eyebrows</h4>
<p>ARGO&#8217;s eyebrows are made of Lego pieces and pipe cleaners. The outer portion of each eyebrow was mounted on ARGO&#8217;s head and acted as an axis of rotation for the inner portion of each brow. One servo motor was attached to the inner portion of both brows with paperclips.</p>
<figure data-shortcode="caption" id="attachment_384" style="width: 583px" class="wp-caption aligncenter"><img data-attachment-id="384" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/screen-shot-2017-05-01-at-9-16-08-pm/" data-orig-file="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-16-08-pm.png?w=583&#038;h=87" data-orig-size="536,80" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="Screen Shot 2017-05-01 at 9.16.08 PM" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-16-08-pm.png?w=583&#038;h=87?w=300" data-large-file="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-16-08-pm.png?w=583&#038;h=87?w=536" class="  wp-image-384 aligncenter" src="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-16-08-pm.png?w=583&#038;h=87" alt="Screen Shot 2017-05-01 at 9.16.08 PM.png" width="583" height="87" srcset="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-16-08-pm.png 536w, https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-16-08-pm.png?w=150&amp;h=22 150w, https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-16-08-pm.png?w=300&amp;h=45 300w" sizes="(max-width: 583px) 100vw, 583px" /><figcaption class="wp-caption-text">Pipe cleaners (left) used to make completed eyebrows (right).</figcaption></figure>
<h4>Mouth</h4>
<p>ARGO mouth was made of a piece of insulated wire. The center of the wire was mounted on ARGO&#8217;s head. A paperclip was used to connect a servo motor to each mouth corner.</p>
<h3>In Summary</h3>
<p>Now ARGO is ready for the software! To be continued in the next post.</p>
<figure data-shortcode="caption" id="attachment_390" style="width: 454px" class="wp-caption aligncenter"><img data-attachment-id="390" data-permalink="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/screen-shot-2017-05-01-at-9-19-17-pm/" data-orig-file="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-19-17-pm.png?w=756" data-orig-size="454,369" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="Screen Shot 2017-05-01 at 9.19.17 PM" data-image-description="" data-medium-file="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-19-17-pm.png?w=756?w=300" data-large-file="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-19-17-pm.png?w=756?w=454" class=" size-full wp-image-390 aligncenter" src="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-19-17-pm.png?w=756" alt="Screen Shot 2017-05-01 at 9.19.17 PM.png" srcset="https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-19-17-pm.png 454w, https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-19-17-pm.png?w=150 150w, https://pybeebee.files.wordpress.com/2017/05/screen-shot-2017-05-01-at-9-19-17-pm.png?w=300 300w" sizes="(max-width: 454px) 100vw, 454px"   /><figcaption class="wp-caption-text">Front view (left) and side view (right) of completed ARGO.</figcaption></figure>
<h3></h3>
		<div id="wordads-preview-parent" class="wpcnt">
			<div class="wpa">
				<span class="wpa-about">Advertisements</span>
				<div class="u">
					<div class="wpa-notice">
						<p>Occasionally, some of your visitors may see an advertisement here, <br />as well as a <a href="https://en.support.wordpress.com/cookie-widget/" target="_blank">Privacy & Cookies banner</a> at the bottom of the page.<br/>You can hide ads completely by upgrading to one of our paid plans.</p>
						<p class="wpa-buttons">
							<a class="wpa-button is-primary" id="wordads-preview-more" href="https://wordpress.com/plans/72591917/?feature=no-adverts&utm_campaign=removeadsnotive" rel="nofollow" target="_blank">Upgrade now</a>
							<a class="wpa-button" id="wordads-preview-dismiss" href="#">Dismiss message</a>
						</p>
					</div>
				</div>
			</div>
		</div><div id="jp-post-flair" class="sharedaddy sharedaddy-dark sd-like-enabled sd-sharing-enabled"><div class="sharedaddy sd-sharing-enabled"><div class="robots-nocontent sd-block sd-social sd-social-icon-text sd-sharing"><h3 class="sd-title">Share this:</h3><div class="sd-content"><ul><li class="share-press-this"><a rel="nofollow noopener noreferrer" data-shared="" class="share-press-this sd-button share-icon" href="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/?share=press-this" target="_blank" title="Click to Press This!"><span>Press This</span></a></li><li class="share-twitter"><a rel="nofollow noopener noreferrer" data-shared="sharing-twitter-323" class="share-twitter sd-button share-icon" href="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/?share=twitter" target="_blank" title="Click to share on Twitter"><span>Twitter</span></a></li><li class="share-facebook"><a rel="nofollow noopener noreferrer" data-shared="sharing-facebook-323" class="share-facebook sd-button share-icon" href="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/?share=facebook" target="_blank" title="Click to share on Facebook"><span>Facebook</span></a></li><li class="share-google-plus-1"><a rel="nofollow noopener noreferrer" data-shared="sharing-google-323" class="share-google-plus-1 sd-button share-icon" href="https://pybeebee.wordpress.com/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/?share=google-plus-1" target="_blank" title="Click to share on Google+"><span>Google</span></a></li><li class="share-end"></li></ul></div></div></div><div class='sharedaddy sd-block sd-like jetpack-likes-widget-wrapper jetpack-likes-widget-unloaded' id='like-post-wrapper-72591917-323-5bcb76a75a23d' data-src='//widgets.wp.com/likes/index.html?ver=20180319#blog_id=72591917&amp;post_id=323&amp;origin=pybeebee.wordpress.com&amp;obj_id=72591917-323-5bcb76a75a23d' data-name='like-post-frame-72591917-323-5bcb76a75a23d'><h3 class='sd-title'>Like this:</h3><div class='likes-widget-placeholder post-likes-widget-placeholder' style='height: 55px;'><span class='button'><span>Like</span></span> <span class="loading">Loading...</span></div><span class='sd-text-color'></span><a class='sd-link-color'></a></div></div>							</div><!-- .entry-content -->

			<footer class="entry-footer">
				<span class="edit-link"><a class="post-edit-link" href="https://wordpress.com/post/pybeebee.wordpress.com/323">Edit</a></span>			</footer><!-- .entry-footer -->

			
<div id="comments" class="comments-area">

	
	
	
		<div id="respond" class="comment-respond">
		<h3 id="reply-title" class="comment-reply-title">Leave a Reply <small><a rel="nofollow" id="cancel-comment-reply-link" href="/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/#respond" style="display:none;">Cancel reply</a></small></h3>			<form action="https://pybeebee.wordpress.com/wp-comments-post.php" method="post" id="commentform" class="comment-form" novalidate>
				<input type="hidden" id="highlander_comment_nonce" name="highlander_comment_nonce" value="1cd75b86d6" /><input type="hidden" name="_wp_http_referer" value="/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/" />
<input type="hidden" name="hc_post_as" id="hc_post_as" value="wordpress" />

<div class="comment-form-field comment-textarea">
	<label for="comment">Enter your comment here...</label>
	<div id="comment-form-comment"><textarea id="comment" name="comment" title="Enter your comment here..."></textarea></div>
</div>

<div id="comment-form-identity">
	<div id="comment-form-nascar">
		<p>Fill in your details below or click an icon to log in:</p>
		<ul>
			<li style="display:none;">
				<a href="#comment-form-guest" id="postas-guest" class="nascar-signin-link"
                   title="Login via Guest">
									</a>
			</li>
			<li class="selected">
				<a href="#comment-form-load-service:WordPress.com" id="postas-wordpress" class="nascar-signin-link"
                   title="Login via WordPress.com">
					<svg xmlns="http://www.w3.org/2000/svg" role="presentation" viewBox="0 0 24 24" ><rect x="0" fill="none" width="24" height="24"/><g><path fill="#FFF" d="M12.158 12.786l-2.698 7.84c.806.236 1.657.365 2.54.365 1.047 0 2.05-.18 2.986-.51-.024-.037-.046-.078-.065-.123l-2.762-7.57zM3.008 12c0 3.56 2.07 6.634 5.068 8.092L3.788 8.342c-.5 1.117-.78 2.354-.78 3.658zm15.06-.454c0-1.112-.398-1.88-.74-2.48-.456-.74-.883-1.368-.883-2.11 0-.825.627-1.595 1.51-1.595.04 0 .078.006.116.008-1.598-1.464-3.73-2.36-6.07-2.36-3.14 0-5.904 1.613-7.512 4.053.21.008.41.012.58.012.94 0 2.395-.114 2.395-.114.484-.028.54.684.057.74 0 0-.487.058-1.03.086l3.275 9.74 1.968-5.902-1.4-3.838c-.485-.028-.944-.085-.944-.085-.486-.03-.43-.77.056-.742 0 0 1.484.114 2.368.114.94 0 2.397-.114 2.397-.114.486-.028.543.684.058.74 0 0-.488.058-1.03.086l3.25 9.665.897-2.997c.456-1.17.684-2.137.684-2.907zm1.82-3.86c.04.286.06.593.06.924 0 .912-.17 1.938-.683 3.22l-2.746 7.94c2.672-1.558 4.47-4.454 4.47-7.77 0-1.564-.4-3.033-1.1-4.314zM12 22C6.486 22 2 17.514 2 12S6.486 2 12 2s10 4.486 10 10-4.486 10-10 10z"/></g></svg>				</a>
			</li>
			<li>
			<iframe id="googleplus-sign-in" name="googleplus-sign-in" src="https://public-api.wordpress.com/connect/?googleplus-sign-in=https%3A%2F%2Fpybeebee.wordpress.com&#038;color_scheme=dark" width="24" height="24" scrolling="no" allowtransparency="true" seamless="seamless" frameborder="0"></iframe>
			</li>
			<li>
				<a href="#comment-form-load-service:Twitter" id="postas-twitter" class="nascar-signin-link"
                   title="Login via Twitter">
					<svg xmlns="http://www.w3.org/2000/svg" role="presentation" viewBox="0 0 24 24" ><rect x="0" fill="none" width="24" height="24"/><g><path fill="#FFF" d="M22.23 5.924c-.736.326-1.527.547-2.357.646.847-.508 1.498-1.312 1.804-2.27-.793.47-1.67.812-2.606.996C18.325 4.498 17.258 4 16.078 4c-2.266 0-4.103 1.837-4.103 4.103 0 .322.036.635.106.935-3.41-.17-6.433-1.804-8.457-4.287-.353.607-.556 1.312-.556 2.064 0 1.424.724 2.68 1.825 3.415-.673-.022-1.305-.207-1.86-.514v.052c0 1.988 1.415 3.647 3.293 4.023-.344.095-.707.145-1.08.145-.265 0-.522-.026-.773-.074.522 1.63 2.038 2.817 3.833 2.85-1.404 1.1-3.174 1.757-5.096 1.757-.332 0-.66-.02-.98-.057 1.816 1.164 3.973 1.843 6.29 1.843 7.547 0 11.675-6.252 11.675-11.675 0-.178-.004-.355-.012-.53.802-.578 1.497-1.3 2.047-2.124z"/></g></svg>				</a>
			</li>
			<li>
				<a href="#comment-form-load-service:Facebook" id="postas-facebook" class="nascar-signin-link"
                   title="Login via Facebook">
					<svg xmlns="http://www.w3.org/2000/svg" role="presentation" viewBox="0 0 24 24" ><rect x="0" fill="none" width="24" height="24"/><g><path fill="#FFF" d="M20.007 3H3.993C3.445 3 3 3.445 3 3.993v16.013c0 .55.445.994.993.994h8.62v-6.97H10.27V11.31h2.346V9.31c0-2.325 1.42-3.59 3.494-3.59.993 0 1.847.073 2.096.106v2.43h-1.438c-1.128 0-1.346.537-1.346 1.324v1.734h2.69l-.35 2.717h-2.34V21h4.587c.548 0 .993-.445.993-.993V3.993c0-.548-.445-.993-.993-.993z"/></g></svg>				</a>
			</li>
		</ul>
	</div>

	<div id="comment-form-guest" class="comment-form-service">
		<div class="comment-form-padder">
			<div class="comment-form-avatar">
<a href="https://gravatar.com/site/signup/" target="_blank">				<img src="https://1.gravatar.com/avatar/ad516503a11cd5ca435acc9bb6523536?s=25&amp;d=identicon&amp;forcedefault=y&amp;r=G" alt="Gravatar" width="25" class="no-grav" />
</a>			</div>

				<div class="comment-form-fields">
				<div class="comment-form-field comment-form-email">
					<label for="email">Email <span class="required">(required)</span> <span class="nopublish">(Address never made public)</span></label>
					<div class="comment-form-input"><input id="email" name="email" type="email" value="" /></div>
				</div>
				<div class="comment-form-field comment-form-author">
					<label for="author">Name <span class="required">(required)</span></label>
					<div class="comment-form-input"><input id="author" name="author" type="text" value="" /></div>
				</div>
				<div class="comment-form-field comment-form-url">
					<label for="url">Website</label>
					<div class="comment-form-input"><input id="url" name="url" type="url" value="" /></div>
				</div>
			</div>
			
		</div>
	</div>

	<div id="comment-form-wordpress" class="comment-form-service selected">
		<div class="comment-form-padder">
			<div class="comment-form-avatar">
				<img src="https://1.gravatar.com/avatar/7bee77b11588d6124d8d4f8079e4cc19?s=25&amp;d=https%3A%2F%2F1.gravatar.com%2Favatar%2Fad516503a11cd5ca435acc9bb6523536%3Fs%3D25%26amp%3Bd%3Didenticon%26amp%3Bforcedefault%3Dy%26amp%3Br%3DG&amp;r=G" alt="Gravatar" width="25" class="no-grav" />
			</div>

				<div class="comment-form-fields">
				<input type="hidden" name="wp_avatar" id="wordpress-avatar" class="comment-meta-wordpress" value="https://1.gravatar.com/avatar/7bee77b11588d6124d8d4f8079e4cc19?s=25&#038;d=https%3A%2F%2Fs2.wp.com%2Fwp-content%2Fmu-plugins%2Fhighlander-comments%2Fimages%2Fwplogo.png&#038;r=G" />
				<input type="hidden" name="wp_user_id" id="wordpress-user_id" class="comment-meta-wordpress" value="69428504" />
				<input type="hidden" name="wp_access_token" id="wordpress-access_token" class="comment-meta-wordpress" value="dca5ebe9488968460f80edc5a0a23977da4ac12d" />
						<p class="comment-form-posting-as pa-wordpress">
			<strong>Gabrielle Liu:</strong>
			You are commenting using your WordPress.com account.			<span class="comment-form-log-out">
				(&nbsp;<a href="javascript:HighlanderComments.doExternalLogout( 'wordpress' );">Log&nbsp;Out</a>&nbsp;/&nbsp;
				<a href="#" onclick="javascript:HighlanderComments.switchAccount();return false;">Change</a>&nbsp;)
			</span>
			<span class="pa-icon"><svg xmlns="http://www.w3.org/2000/svg" role="presentation" viewBox="0 0 24 24" ><rect x="0" fill="none" width="24" height="24"/><g><path fill="#FFF" d="M12.158 12.786l-2.698 7.84c.806.236 1.657.365 2.54.365 1.047 0 2.05-.18 2.986-.51-.024-.037-.046-.078-.065-.123l-2.762-7.57zM3.008 12c0 3.56 2.07 6.634 5.068 8.092L3.788 8.342c-.5 1.117-.78 2.354-.78 3.658zm15.06-.454c0-1.112-.398-1.88-.74-2.48-.456-.74-.883-1.368-.883-2.11 0-.825.627-1.595 1.51-1.595.04 0 .078.006.116.008-1.598-1.464-3.73-2.36-6.07-2.36-3.14 0-5.904 1.613-7.512 4.053.21.008.41.012.58.012.94 0 2.395-.114 2.395-.114.484-.028.54.684.057.74 0 0-.487.058-1.03.086l3.275 9.74 1.968-5.902-1.4-3.838c-.485-.028-.944-.085-.944-.085-.486-.03-.43-.77.056-.742 0 0 1.484.114 2.368.114.94 0 2.397-.114 2.397-.114.486-.028.543.684.058.74 0 0-.488.058-1.03.086l3.25 9.665.897-2.997c.456-1.17.684-2.137.684-2.907zm1.82-3.86c.04.286.06.593.06.924 0 .912-.17 1.938-.683 3.22l-2.746 7.94c2.672-1.558 4.47-4.454 4.47-7.77 0-1.564-.4-3.033-1.1-4.314zM12 22C6.486 22 2 17.514 2 12S6.486 2 12 2s10 4.486 10 10-4.486 10-10 10z"/></g></svg></span>
		</p>
					</div>
	
		</div>
	</div>

	<div id="comment-form-googleplus" class="comment-form-service">
		<div class="comment-form-padder">
			<div class="comment-form-avatar">
				<img src="https://1.gravatar.com/avatar/ad516503a11cd5ca435acc9bb6523536?s=25&amp;d=identicon&amp;forcedefault=y&amp;r=G" alt="Google+ photo" width="25" class="no-grav" />
			</div>

				<div class="comment-form-fields">
				<input type="hidden" name="googleplus_avatar" id="googleplus-avatar" class="comment-meta-googleplus" value="" />
				<input type="hidden" name="googleplus_user_id" id="googleplus-user_id" class="comment-meta-googleplus" value="" />
				<input type="hidden" name="googleplus_access_token" id="googleplus-access_token" class="comment-meta-googleplus" value="" />
						<p class="comment-form-posting-as pa-googleplus">
			<strong></strong>
			You are commenting using your Google+ account.			<span class="comment-form-log-out">
				(&nbsp;<a href="javascript:HighlanderComments.doExternalLogout( 'googleplus' );">Log&nbsp;Out</a>&nbsp;/&nbsp;
				<a href="#" onclick="javascript:HighlanderComments.switchAccount();return false;">Change</a>&nbsp;)
			</span>
			<span class="pa-icon"><svg xmlns="http://www.w3.org/2000/svg" role="presentation" x="0px" y="0px" viewBox="0 0 60 60" ><path fill="#FFF" d="M56.3,30c0,-1.6 -0.2,-3.4 -0.6,-5h-3.1H42.2H30v10.6h14.8C44,39.3 42,42 39.1,43.9l8.8,6.8C53,46 56.3,39 56.3,30z" /><path fill="#FFF" d="M30,57.5c6.7,0 13.1,-2.4 17.9,-6.8l-8.8,-6.8c-2.5,1.6 -5.6,2.4 -9.1,2.4c-7.2,0 -13.3,-4.7 -15.4,-11.2l-9.3,7.1C9.8,51.3 19.1,57.5 30,57.5z" /><path fill="#FFF" d="M5.3,42.2l9.3,-7.1c-0.5,-1.6 -0.8,-3.3 -0.8,-5.1s0.3,-3.5 0.8,-5.1l-9.3,-7.1C3.5,21.5 2.5,25.6 2.5,30S3.5,38.5 5.3,42.2z" /><path fill="#FFF" d="M40.1,17.4l8,-8C43.3,5.1 37,2.5 30,2.5C19.1,2.5 9.8,8.7 5.3,17.8l9.3,7.1c2.1,-6.5 8.2,-11.1 15.4,-11.1C33.9,13.7 37.4,15.1 40.1,17.4z" /></svg></span>
		</p>
					</div>
	
		</div>
	</div>

	<div id="comment-form-twitter" class="comment-form-service">
		<div class="comment-form-padder">
			<div class="comment-form-avatar">
				<img src="https://1.gravatar.com/avatar/ad516503a11cd5ca435acc9bb6523536?s=25&amp;d=identicon&amp;forcedefault=y&amp;r=G" alt="Twitter picture" width="25" class="no-grav" />
			</div>

				<div class="comment-form-fields">
				<input type="hidden" name="twitter_avatar" id="twitter-avatar" class="comment-meta-twitter" value="" />
				<input type="hidden" name="twitter_user_id" id="twitter-user_id" class="comment-meta-twitter" value="" />
				<input type="hidden" name="twitter_access_token" id="twitter-access_token" class="comment-meta-twitter" value="" />
						<p class="comment-form-posting-as pa-twitter">
			<strong></strong>
			You are commenting using your Twitter account.			<span class="comment-form-log-out">
				(&nbsp;<a href="javascript:HighlanderComments.doExternalLogout( 'twitter' );">Log&nbsp;Out</a>&nbsp;/&nbsp;
				<a href="#" onclick="javascript:HighlanderComments.switchAccount();return false;">Change</a>&nbsp;)
			</span>
			<span class="pa-icon"><svg xmlns="http://www.w3.org/2000/svg" role="presentation" viewBox="0 0 24 24" ><rect x="0" fill="none" width="24" height="24"/><g><path fill="#FFF" d="M22.23 5.924c-.736.326-1.527.547-2.357.646.847-.508 1.498-1.312 1.804-2.27-.793.47-1.67.812-2.606.996C18.325 4.498 17.258 4 16.078 4c-2.266 0-4.103 1.837-4.103 4.103 0 .322.036.635.106.935-3.41-.17-6.433-1.804-8.457-4.287-.353.607-.556 1.312-.556 2.064 0 1.424.724 2.68 1.825 3.415-.673-.022-1.305-.207-1.86-.514v.052c0 1.988 1.415 3.647 3.293 4.023-.344.095-.707.145-1.08.145-.265 0-.522-.026-.773-.074.522 1.63 2.038 2.817 3.833 2.85-1.404 1.1-3.174 1.757-5.096 1.757-.332 0-.66-.02-.98-.057 1.816 1.164 3.973 1.843 6.29 1.843 7.547 0 11.675-6.252 11.675-11.675 0-.178-.004-.355-.012-.53.802-.578 1.497-1.3 2.047-2.124z"/></g></svg></span>
		</p>
					</div>
	
		</div>
	</div>

	<div id="comment-form-facebook" class="comment-form-service">
		<div class="comment-form-padder">
			<div class="comment-form-avatar">
				<img src="https://1.gravatar.com/avatar/ad516503a11cd5ca435acc9bb6523536?s=25&amp;d=identicon&amp;forcedefault=y&amp;r=G" alt="Facebook photo" width="25" class="no-grav" />
			</div>

				<div class="comment-form-fields">
				<input type="hidden" name="fb_avatar" id="facebook-avatar" class="comment-meta-facebook" value="" />
				<input type="hidden" name="fb_user_id" id="facebook-user_id" class="comment-meta-facebook" value="" />
				<input type="hidden" name="fb_access_token" id="facebook-access_token" class="comment-meta-facebook" value="" />
						<p class="comment-form-posting-as pa-facebook">
			<strong></strong>
			You are commenting using your Facebook account.			<span class="comment-form-log-out">
				(&nbsp;<a href="javascript:HighlanderComments.doExternalLogout( 'facebook' );">Log&nbsp;Out</a>&nbsp;/&nbsp;
				<a href="#" onclick="javascript:HighlanderComments.switchAccount();return false;">Change</a>&nbsp;)
			</span>
			<span class="pa-icon"><svg xmlns="http://www.w3.org/2000/svg" role="presentation" viewBox="0 0 24 24" ><rect x="0" fill="none" width="24" height="24"/><g><path fill="#FFF" d="M20.007 3H3.993C3.445 3 3 3.445 3 3.993v16.013c0 .55.445.994.993.994h8.62v-6.97H10.27V11.31h2.346V9.31c0-2.325 1.42-3.59 3.494-3.59.993 0 1.847.073 2.096.106v2.43h-1.438c-1.128 0-1.346.537-1.346 1.324v1.734h2.69l-.35 2.717h-2.34V21h4.587c.548 0 .993-.445.993-.993V3.993c0-.548-.445-.993-.993-.993z"/></g></svg></span>
		</p>
					</div>
	
		</div>
	</div>


	<div id="comment-form-load-service" class="comment-form-service">
		<div class="comment-form-posting-as-cancel"><a href="javascript:HighlanderComments.cancelExternalWindow();">Cancel</a></div>
		<p>Connecting to %s</p>
	</div>

</div>

<script type="text/javascript">
var highlander_expando_javascript = function(){
	var input = document.createElement( 'input' ),
	    comment = jQuery( '#comment' );

	if ( 'placeholder' in input ) {
		comment.attr( 'placeholder', jQuery( '.comment-textarea label' ).remove().text() );
	}

	// Expando Mode: start small, then auto-resize on first click + text length
	jQuery( '#comment-form-identity' ).hide();
	jQuery( '#comment-form-subscribe' ).hide();
	jQuery( '#commentform .form-submit' ).hide();

	comment.css( { 'height':'10px' } ).one( 'focus', function() {
		var timer = setInterval( HighlanderComments.resizeCallback, 10 )
		jQuery( this ).animate( { 'height': HighlanderComments.initialHeight } ).delay( 100 ).queue( function(n) { clearInterval( timer ); HighlanderComments.resizeCallback(); n(); } );
		jQuery( '#comment-form-identity' ).slideDown();
		jQuery( '#comment-form-subscribe' ).slideDown();
		jQuery( '#commentform .form-submit' ).slideDown();
	});
}
jQuery(document).ready( highlander_expando_javascript );
</script>

<div id="comment-form-subscribe">
	<p class="comment-subscription-form"><input type="checkbox" name="subscribe" id="subscribe" value="subscribe" style="width: auto;"/> <label class="subscribe-label" id="subscribe-label" for="subscribe" style="display: inline;">Notify me of new comments via email.</label></p></div>

<p class="form-submit"><input name="submit" type="submit" id="comment-submit" class="submit" value="Post Comment" /> <input type='hidden' name='comment_post_ID' value='323' id='comment_post_ID' />
<input type='hidden' name='comment_parent' id='comment_parent' value='0' />
</p><p style="display: none;"><input type="hidden" id="akismet_comment_nonce" name="akismet_comment_nonce" value="6742aa9b91" /></p>
<input type="hidden" name="genseq" value="1540060839" />
<p style="display: none;"><input type="hidden" id="ak_js" name="ak_js" value="130"/></p>			</form>
			</div><!-- #respond -->
	<div style="clear: both"></div>
</div><!-- #comments -->

		</div>

		<div class="sidebar">
					</div><!-- .sidebar -->

	</article><!-- #post-## -->
			
	<nav class="navigation post-navigation" role="navigation">
		<h2 class="screen-reader-text">Post navigation</h2>
		<div class="nav-links"><div class="nav-previous"><a href="https://pybeebee.wordpress.com/2017/05/27/delivery-python-compatible-packages-for-emotion-recognition/" rel="prev">Previous Post <span class="screen-reader-text">Delivery! Python-Compatible Packages for Emotion&nbsp;Recognition</span></a></div><div class="nav-next"><a href="https://pybeebee.wordpress.com/2017/09/02/meet-argo-part-2/" rel="next">Next Post <span class="screen-reader-text">Meet ARGO! Part&nbsp;2</span></a></div></div>
	</nav>
		
		</main><!-- #main -->
	</div><!-- #primary -->


	</div><!-- #content -->

	<footer id="colophon" class="site-footer" role="contentinfo">

		<div class="site-info">
	<a href="https://wordpress.com/?ref=footer_custom_powered">Powered by WordPress.com</a>.
	
	</div><!-- .site-info -->

	</footer><!-- #colophon -->
</div><!-- #page -->

<!--  -->
	<script type="text/javascript">
	/* <![CDATA[ */
		jQuery(document).ready( function($) {
			function doFollowingHover() {
				$('#wp-admin-bar-follow > a').unbind( '.unfollow' );

				$('#wp-admin-bar-follow > a').bind( 'mouseover.unfollow', function() {

					$(this).html( "Unfollow" ).parent( 'li' ).addClass( 'unfollow' );
				});
				$('#wp-admin-bar-follow > a').bind( 'mouseout.unfollow', function() {
					$(this).html( "Following" ).parent( 'li' ).removeClass( 'unfollow' );
				});
			}
							doFollowingHover();
			
			$('#wp-admin-bar-follow > a').click( function( e ) {
				$('#wp-admin-bar-follow > a').unbind( '.unfollow' );

				e.preventDefault();

				var link = $( this ), li = $( '#wp-admin-bar-follow' ), timeout = 0;

				if ( li.hasClass( 'subscribed' ) ) {
					li.removeClass( 'subscribed' ).removeClass( 'unfollow' );
					link.html( "Follow" );

					$('body').append( $( 'div.wpcom-bubble' ).removeClass( 'fadein' ) ).off( 'click.bubble' );

					var action = 'ab_unsubscribe_from_blog';
				} else {
					li.addClass( 'subscribed' ).removeClass( 'unfollow' );
					link.html( "Following" );

						var left = 131 - link.width();
						li.append( $( 'div.wpcom-bubble' ).css( { left: '-' + left + 'px' } ) );
						$( 'div.bubble-txt', 'div.wpcom-bubble' ).html( "New posts from this blog will now appear in <a target=\"_blank\" href=\"http:\/\/wordpress.com\/\">your reader<\/a>. You can manage email alerts from your <a target=\"_blank\" href=\"http:\/\/wordpress.com\/following\/edit\/\">subscriptions page<\/a>." );

						$( 'div.wpcom-bubble.action-bubble' ).addClass( 'fadein' );

						setTimeout( function() {
							$('body').on( 'click.bubble touchstart.bubble', function(e) {
								if ( !$(e.target).hasClass('wpcom-bubble') && !$(e.target).parents( 'div.wpcom-bubble' ).length )
									hideBubble();
							});
							setTimeout( hideBubble, 15000 );
						}, 500 );

					var action = 'ab_subscribe_to_blog';
					$('#wp-admin-bar-follow > a').bind( 'mouseout.shift', function() {
						doFollowingHover();
						$(this).unbind( '.shift' );
					});
				}

				var nonce = link.attr( 'href' ).split( '_wpnonce=' );
				nonce = nonce[1];

				$.post( "https:\/\/pybeebee.wordpress.com\/wp-admin\/admin-ajax.php", {
					'action': action,
					'_wpnonce': nonce,
					'source': 'admin_bar',
					'blog_id': 72591917				});
			});
		});
	/* ]]> */
	</script>
<script type='text/javascript' src='//0.gravatar.com/js/gprofiles.js?ver=201842y'></script>
<script type='text/javascript'>
/* <![CDATA[ */
var WPGroHo = {"my_hash":"7bee77b11588d6124d8d4f8079e4cc19"};
/* ]]> */
</script>
<script type='text/javascript' src='https://s1.wp.com/wp-content/mu-plugins/gravatar-hovercards/wpgroho.js?m=1380573781h'></script>

	<script>
		//initialize and attach hovercards to all gravatars
		jQuery( document ).ready( function( $ ) {

			if (typeof Gravatar === "undefined"){
				return;
			}

			if ( typeof Gravatar.init !== "function" ) {
				return;
			}			

			Gravatar.profile_cb = function( hash, id ) {
				WPGroHo.syncProfileData( hash, id );
			};
			Gravatar.my_hash = WPGroHo.my_hash;
			Gravatar.init( 'body', '#wp-admin-bar-my-account' );
		});
	</script>

		<div style="display:none">
	</div>

	<div id="ab-reblog-box">
		<form action="" name="reblog">
			<textarea id="reblog-content" name="reblog-content" placeholder="Add your thoughts here... (optional)"></textarea>
			<label for="blogid" id="lblogid">Post to</label>

			<select name="to_blog_id" id="reblog-to-blog-id">
														<option value="72591917">pybeebee.wordpress.com</option>
														<option value="134005077">RHS Computational Biology Club</option>
							</select>

			<div class="submit">
				<span class="canceltext"><a href="" class="cancel">Cancel</a></span>
				<input type="submit" name="reblog-submit" class="button-primary" id="reblog-submit" value="Reblog Post" />
				<input type="hidden" id="original-blog-id" value="72591917" />
				<input type="hidden" id="original-post-id" value="323" />
			</div>

			<input type="hidden" id="_wpnonce" name="_wpnonce" value="ebc5099e87" /><input type="hidden" name="_wp_http_referer" value="/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/" />		</form>

		<div class="arrow"></div>
	</div>

	<script type="text/javascript">
	var wpcom_reblog = {
		request: false,
		source: 'toolbar',

		init: function() {
			// Click reblog button on post
			jQuery(document).on( 'click', '#wpadminbar .reblog', function(e) {
				e.preventDefault();
				wpcom_reblog.source = 'toolbar';

				if ( jQuery( '#wpadminbar #ab-reblog-box' ).is( ':visible' ) ) {
					wpcom_reblog.cancel_reblog();
				}
				else {
					wpcom_reblog.show_reblog_box();
				}
			} );

			// Clicked reblog button on already reblogged post.
			jQuery(document).on( 'click', '#wpadminbar .reblogged', function(e) {
				e.preventDefault();
			});

			// Click cancel reblog button
			jQuery(document).on( 'click', '#ab-reblog-box a.cancel', function(e) {
				e.preventDefault();
				wpcom_reblog.cancel_reblog();
			});

			// Submit reblog box
			jQuery(document).on( 'click', '#ab-reblog-box input[type=submit]', function(e) {
				e.preventDefault();
				wpcom_reblog.submit_reblog( jQuery(this) );
			});
		},

		show_reblog_box: function() {
			return this.show_reblog_box_here(
				'#wp-admin-bar-wpr-reblog',
				'#wpadminbar'
			);
		},

		toggle_reblog_box_flair: function( obj_id ) {
			if ( jQuery( '#jp-post-flair #ab-reblog-box' ).is( ':visible' ) ) {
				wpcom_reblog.cancel_reblog();
			}
			else {
				wpcom_reblog.show_reblog_box_flair( obj_id );
			}
		},

		show_reblog_box_flair: function( obj_id ) {
			this.source = 'post_flair';
			this.obj_id = obj_id;
			return this.show_reblog_box_here(
				'.post-likes-widget',
				'body'
			);
		},

		show_reblog_box_here: function(anchorId, parentId) {
			var jq = jQuery,
			    $anchor = jq( anchorId ),
			    $parent = jq( parentId ),
			    $window = jq( window ),
			    $scroll = jq('html, body'),
			    $reblog_box = jq( '#ab-reblog-box' ),
			    offset = $anchor.offset(),
			    left = offset.left + 'px',
			    width = '500px',
			    position,
			    top;

			if ( $parent.css( 'position' ) === 'fixed' ) {
				position = 'fixed';
				top = $parent.position().top + $parent.outerHeight();
			}
			else {
				position = 'absolute';
				top = offset.top + $anchor.outerHeight() + 'px';
			}
			$reblog_box.remove();
			$parent.append( $reblog_box );
			$anchor.addClass( 'selected' );

			if ( jq( window ).innerWidth() < offset.left + 500 ) {
				// Most likely mobile or tablet
				left = '0px';
				width = ( jq( window ).innerWidth() - 24 ) + 'px';
			}

			$reblog_box
				.find('p.response').remove().end()
				.find('div.submit, div.submit span.canceltext').show().end()
				.find('div.submit input[type=submit]').prop('disabled',false).end()
				.show()
				.css({
					top : top,
					left : left,
					width : width,
					position: position,
					'z-index': 10 // slide under twentyfourteen's fixed-positioned masthead
				});

			// Ensure we can see the whole reblog box
			var docViewTop = $window.scrollTop(),
			    windowHeight = $window.height(),
			    docViewBottom = docViewTop + windowHeight,
			    elemTop = $reblog_box.offset().top,
			    elemHeight = $reblog_box.outerHeight() + 10,
			    elemBottom = elemTop + elemHeight;
			if ( docViewTop > elemTop ) {
				// Need to scroll up
				// leave 75px for toolbar + Reblog button + margin
				$scroll.animate({scrollTop: elemTop - 75});
			}
			else if ( docViewBottom < elemBottom ) {
				// Need to scroll down
				$scroll.animate({scrollTop: elemBottom - windowHeight}, 100);
			}
		},

		submit_reblog: function( input ) {
			var jq = jQuery;
			var self = this;
			if ( typeof this.request == 'object' )
				this.request.abort();

			input.attr( 'value', 'Reblogging...' );
			input.prop( 'disabled', true );

			jq( '#ab-reblog-box div.submit span.canceltext' ).fadeOut( 150, function() {
				input.before( '<span class="spinner"></span>' );
			});

			var note = jq('#ab-reblog-box textarea').val();

			if ( jq('#default-reblog-note').val() == note )
				note = "";

			this.request = jq.get( '/wp-admin/admin-ajax.php', {
				'action': 'post_reblog',
				'original_blog_id': jq('#original-blog-id').val(),
				'original_post_id': jq('#original-post-id').val(),
				'blog_id': jq('#ab-reblog-box select').val(),
				'note': note,
				'_wpnonce': jq('#ab-reblog-box #_wpnonce').val(),
				'reblog_source': this.source
			},
			function(result, status, jqxhr) {
				if ( ! ( "type" in result ) ) {
					alert( "Error: " + jqxhr.responseText );
				}
				else if ( "error" == result.type ) {
					alert( result.message );
				}
				else {
					if ( typeof pm === 'function' ) {
						console.log(self);
						pm({
							target : window.frames['likes-master'],
							type : 'likesMessage',
							data : { event: 'didReblog', obj_id: self.obj_id },
							origin : '*'
						});
					}

					jq( '#ab-reblog-box' ).hide();
					jq( '#wp-admin-bar-wpr-reblog' ).addClass( 'reblogged' ).removeClass( 'reblog' ).find( 'a:first' ).text( 'Reblogged' );
				}
			}, 'json' );
		},

		cancel_reblog: function() {
			jQuery( '#ab-reblog-box' ).hide();
			jQuery( '#wp-admin-bar-wpr-reblog' ).removeClass( 'selected' );
		}
	};

	wpcom_reblog.init();
	</script>
<div id="report-form-window" style="display:none;"></div><script type='text/javascript'>
/* <![CDATA[ */
var HighlanderComments = {"loggingInText":"Logging In\u2026","submittingText":"Posting Comment\u2026","postCommentText":"Post Comment","connectingToText":"Connecting to %s","commentingAsText":"%1$s: You are commenting using your %2$s account.","logoutText":"Log Out","loginText":"Log In","connectURL":"https:\/\/pybeebee.wordpress.com\/public.api\/connect\/?action=request","logoutURL":"https:\/\/pybeebee.wordpress.com\/wp-login.php?action=logout&_wpnonce=0eaec1af7c","homeURL":"https:\/\/pybeebee.wordpress.com\/","postID":"323","gravDefault":"identicon","enterACommentError":"Please enter a comment","enterEmailError":"Please enter your email address here","invalidEmailError":"Invalid email address","enterAuthorError":"Please enter your name here","gravatarFromEmail":"This picture will show whenever you leave a comment. Click to customize it.","logInToExternalAccount":"Log in to use details from one of these accounts.","change":"Change","changeAccount":"Change Account","comment_registration":"0","userIsLoggedIn":"1","isJetpack":"","text_direction":"ltr"};
/* ]]> */
</script>
<script type='text/javascript' src='https://s2.wp.com/_static/??/wp-content/js/jquery/jquery.autoresize.js,/wp-content/mu-plugins/highlander-comments/script.js?m=1521806916j'></script>

	<div id="carousel-reblog-box">
		<form action="#" name="carousel-reblog">
			<textarea id="carousel-reblog-content" name="carousel-reblog-content" placeholder="Add your thoughts here... (optional)"></textarea>
			<label for="carousel-reblog-to-blog-id" id="carousel-reblog-lblogid">Post to</label>
			<select name="carousel-reblog-to-blog-id" id="carousel-reblog-to-blog-id">
							<option value="72591917"></option>
							<option value="134005077">RHS Computational Biology Club</option>
						</select>

			<div class="submit">
				<span class="canceltext"><a href="#" class="cancel">Cancel</a></span>
				<input type="submit" name="carousel-reblog-submit" class="button" id="carousel-reblog-submit" value="Reblog Post" />
				<input type="hidden" id="carousel-reblog-blog-id" value="72591917" />
				<input type="hidden" id="carousel-reblog-blog-url" value="https://pybeebee.wordpress.com" />
				<input type="hidden" id="carousel-reblog-blog-title" value="" />
				<input type="hidden" id="carousel-reblog-post-url" value="" />
				<input type="hidden" id="carousel-reblog-post-title" value="" />
			</div>

			<input type="hidden" id="_wpnonce" name="_wpnonce" value="ebc5099e87" /><input type="hidden" name="_wp_http_referer" value="/2017/07/15/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation/" />		</form>

		<div class="arrow"></div>
	</div>

	<script type="text/javascript">
		window.WPCOM_sharing_counts = {"https:\/\/pybeebee.wordpress.com\/2017\/07\/15\/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation\/":323};
	</script>
				<div class="widget widget_eu_cookie_law_widget"><div
	class="hide-on-button ads-active"
	data-hide-timeout="30"
	data-consent-expiration="180"
	id="eu-cookie-law"
>
	<form method="post">
		<input type="submit" value="Close and accept" class="accept" />

		Privacy &amp; Cookies: This site uses cookies. By continuing to use this website, you agree to their use. <br />
To find out more, including how to control cookies, see here:
		<a href="https://automattic.com/cookies" >
			Cookie Policy		</a>
 </form>
</div>
</div><link rel='stylesheet' id='all-css-0-3' href='https://s0.wp.com/wp-content/mu-plugins/carousel/jetpack-carousel.css?m=1524699534h&cssminify=yes' type='text/css' media='all' />
<!--[if lte IE 8]>
<link rel='stylesheet' id='jetpack-carousel-ie8fix-css'  href='https://s1.wp.com/wp-content/mu-plugins/carousel/jetpack-carousel-ie8fix.css?m=1412618825h&#038;ver=20121024' type='text/css' media='all' />
<![endif]-->
<script type='text/javascript'>
/* <![CDATA[ */
var thickboxL10n = {"next":"Next >","prev":"< Prev","image":"Image","of":"of","close":"Close","noiframes":"This feature requires inline frames. You have iframes disabled or your browser does not support them.","loadingAnimation":"https:\/\/s2.wp.com\/wp-includes\/js\/thickbox\/loadingAnimation.gif"};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var comment_like_text = {"loading":"Loading..."};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var wpNotesArgs = {"cacheBuster":"desktop\/2.4.0-13279-g67a63e0","iframeUrl":"https:\/\/widgets.wp.com\/notifications\/","iframeAppend":"2","iframeScroll":"no","wide":"1"};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var wpcom_tos_report_form = {"ajaxurl":"\/wp-admin\/admin-ajax.php","isLoggedoutUser":"","post_ID":"323","current_url":"https:\/\/pybeebee.wordpress.com\/2017\/07\/15\/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation","report_this_content":"Report this content"};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var wordads_preview = {"ajaxurl":"https:\/\/pybeebee.wordpress.com\/wp-admin\/admin-ajax.php","blog_id":"72591917","user":"pybeebee","nonce":"cd834374a5"};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var actionbardata = {"siteID":"72591917","siteName":"pybeebee.wordpress.com","siteURL":"http:\/\/pybeebee.wordpress.com","icon":"<img alt='' src='https:\/\/pybeebee.files.wordpress.com\/2017\/10\/cropped-mecat.jpg?w=50' class='avatar avatar-50' height='50' width='50' \/>","canManageOptions":"1","canCustomizeSite":"1","isFollowing":"1","themeSlug":"pub\/escutcheon","signupURL":"https:\/\/wordpress.com\/start\/","loginURL":"https:\/\/pybeebee.wordpress.com\/wp-login.php?redirect_to=https%3A%2F%2Fpybeebee.wordpress.com%2F2017%2F07%2F15%2Fconstructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation%2F","themeURL":"https:\/\/wordpress.com\/theme\/escutcheon\/","xhrURL":"https:\/\/pybeebee.wordpress.com\/wp-admin\/admin-ajax.php","nonce":"26fc4b9e6a","isSingular":"1","isFolded":"","isLoggedIn":"1","isMobile":"","subscribeNonce":"<input type=\"hidden\" id=\"_wpnonce\" name=\"_wpnonce\" value=\"b91193471a\" \/>","referer":"https:\/\/pybeebee.wordpress.com\/2017\/07\/15\/constructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation\/","canFollow":"1","feedID":"23301187","statusMessage":"","customizeLink":"https:\/\/pybeebee.wordpress.com\/wp-admin\/customize.php?url=https%3A%2F%2Fpybeebee.wordpress.com%2F2017%2F07%2F15%2Fconstructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation%2F","postID":"323","shortlink":"https:\/\/wp.me\/p4UAtn-5d","canEditPost":"1","editLink":"https:\/\/wordpress.com\/post\/pybeebee.wordpress.com\/323","statsLink":"https:\/\/wordpress.com\/stats\/post\/323\/pybeebee.wordpress.com","i18n":{"view":"View site","follow":"Follow","following":"Following","edit":"Edit","login":"Log in","signup":"Sign up","customize":"Customize","report":"Report this content","themeInfo":"Get help setting up your theme","shortlink":"Copy shortlink","copied":"Copied","followedText":"New posts from this site will now appear in your <a href=\"https:\/\/wordpress.com\/\">Reader<\/a>","foldBar":"Collapse this bar","unfoldBar":"Expand this bar","editSubs":"Manage subscriptions","viewReader":"View site in Reader","viewReadPost":"View post in Reader","subscribe":"Sign me up","enterEmail":"Enter your email address","followers":"","alreadyUser":"Already have a WordPress.com account? <a href=\"https:\/\/pybeebee.wordpress.com\/wp-login.php?redirect_to=https%3A%2F%2Fpybeebee.wordpress.com%2F2017%2F07%2F15%2Fconstructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation%2F\">Log in now.<\/a>","stats":"Stats"}};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var jetpackCarouselStrings = {"widths":[370,700,1000,1200,1400,2000],"is_logged_in":"1","lang":"en","ajaxurl":"https:\/\/pybeebee.wordpress.com\/wp-admin\/admin-ajax.php","nonce":"67375289f8","display_exif":"1","display_geo":"1","single_image_gallery":"1","single_image_gallery_media_file":"","background_color":"black","comment":"Comment","post_comment":"Post Comment","write_comment":"Write a Comment...","loading_comments":"Loading Comments...","download_original":"View full size <span class=\"photo-size\">{0}<span class=\"photo-size-times\">\u00d7<\/span>{1}<\/span>","no_comment_text":"Please be sure to submit some text with your comment.","no_comment_email":"Please provide an email address to comment.","no_comment_author":"Please provide your name to comment.","comment_post_error":"Sorry, but there was an error posting your comment. Please try again later.","comment_approved":"Your comment was approved.","comment_unapproved":"Your comment is in moderation.","camera":"Camera","aperture":"Aperture","shutter_speed":"Shutter Speed","focal_length":"Focal Length","copyright":"Copyright","comment_registration":"0","require_name_email":"1","login_url":"https:\/\/pybeebee.wordpress.com\/wp-login.php?redirect_to=https%3A%2F%2Fpybeebee.wordpress.com%2F2017%2F07%2F15%2Fconstructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation%2F","blog_id":"72591917","meta_data":["camera","aperture","shutter_speed","focal_length","copyright"],"local_comments_commenting_as":"<p id=\"jp-carousel-commenting-as\">Commenting as Gabrielle Liu<\/p>","reblog":"Reblog","reblogged":"Reblogged","reblog_add_thoughts":"Add your thoughts here... (optional)","reblogging":"Reblogging...","post_reblog":"Post Reblog","stats_query_args":"blog=72591917&v=wpcom&tz=-5&user=1&user_id=69428504&subd=pybeebee","is_public":"1","reblog_enabled":"1"};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var sharing_js_options = {"lang":"en","counts":"1"};
/* ]]> */
</script>
<script type='text/javascript' src='https://s1.wp.com/_static/??-eJyVU9FShDAM/CF7VW8cfXH8FKeUCIG2qU176N+bngOeJ3L6QiHZTTbboKeoLIUMIeuBdQsHtBDfdgNfaUlhsK60wDWXe7RjQ2/Lywya+b6o6EqHgbXDUUivBQr0JrQO0lpF03oMqjFpJ+dGtQUneUteffF+5wjOS0h9KhmqpEbzhBH+Q/oWOCfmHrzAYmk0sC3Z9kBBG2bIR3IwB+xMRvox2yUmjxilZxjVC9nC6gVXb2RWlyC69wseTth2tToUydKIoJyZdAYfnclwFl9rVkILiS0lOO10imhMXYsAa0ok7QtnI5NuiAxUpRyfqg5HQR1uL+KXddgGZ+LqFKUsriZ//n3ObBx1X+5Rak0roly9pOO0cygm+Wdg+tP6esMZUlVKB0gJq3FL7J8VchK7f+zkKcnW1auk5W1r9U2iwuD0ADlKZTUHtjqMyB6y2u+u9bNsgl7z8QQficVrZzBp7k3C0M2nkJ78483d/uH64X5/fzN8AFMiuD0='></script>
<script type='text/javascript'>
var windowOpen;
			jQuery( document.body ).on( 'click', 'a.share-twitter', function() {
				// If there's another sharing window open, close it.
				if ( 'undefined' !== typeof windowOpen ) {
					windowOpen.close();
				}
				windowOpen = window.open( jQuery( this ).attr( 'href' ), 'wpcomtwitter', 'menubar=1,resizable=1,width=600,height=350' );
				return false;
			});
var windowOpen;
			jQuery( document.body ).on( 'click', 'a.share-facebook', function() {
				// If there's another sharing window open, close it.
				if ( 'undefined' !== typeof windowOpen ) {
					windowOpen.close();
				}
				windowOpen = window.open( jQuery( this ).attr( 'href' ), 'wpcomfacebook', 'menubar=1,resizable=1,width=600,height=400' );
				return false;
			});
var windowOpen;
			jQuery( document.body ).on( 'click', 'a.share-google-plus-1', function() {
				// If there's another sharing window open, close it.
				if ( 'undefined' !== typeof windowOpen ) {
					windowOpen.close();
				}
				windowOpen = window.open( jQuery( this ).attr( 'href' ), 'wpcomgoogle-plus-1', 'menubar=1,resizable=1,width=480,height=550' );
				return false;
			});
</script>
<script type="text/javascript">
// <![CDATA[
(function() {
try{
  if ( window.external &&'msIsSiteMode' in window.external) {
    if (window.external.msIsSiteMode()) {
      var jl = document.createElement('script');
      jl.type='text/javascript';
      jl.async=true;
      jl.src='/wp-content/plugins/ie-sitemode/custom-jumplist.php';
      var s = document.getElementsByTagName('script')[0];
      s.parentNode.insertBefore(jl, s);
    }
  }
}catch(e){}
})();
// ]]>
</script>		<iframe src='https://widgets.wp.com/likes/master.html?ver=20180319#ver=20180319' scrolling='no' id='likes-master' name='likes-master' style='display:none;'></iframe>
		<div id='likes-other-gravatars'><div class="likes-text"><span>%d</span> bloggers like this:</div><ul class="wpl-avatars sd-like-gravatars"></ul></div>
<script src="//stats.wp.com/w.js?56" type="text/javascript" async defer></script>
<script type="text/javascript">
_tkq = window._tkq || [];
_stq = window._stq || [];
_tkq.push(['identifyUser', 69428504, 'pybeebee']);
_tkq.push(['storeContext', {'blog_id':'72591917','blog_tz':'-5','user_lang':'en','blog_lang':'en'}]);
_stq.push(['view', {'blog':'72591917','v':'wpcom','tz':'-5','user':'1','user_id':'69428504','post':'323','subd':'pybeebee'}]);
_stq.push(['extra', {'crypt':'UE40eW5QN0p8M2Y/RE1zNDZ8S252Wis9XUQyb3YrcUVIU2R0VH5TcUpqcF9NWi1bMDJfLy90VXNvY2U3ZFZ1RWlDaW8lJnxjWWh+T0pXVHw3QXd3aHBzdHcseCxud0xmSFtJOUQwLT9bVGUtZ1BFUGJJUlJiQS0laTM3ME5JPW1tLStYZCt3NV1oaGJKVWp5UG5mXVBKWjRhQ0VEJkNLVTA2UXpOdVRjWnBQRjRDbUNDQVY/JVpHZnVRWjVdbV9HNlhVN2FPby5JN00mT2R6bFZXM35HS2VLUnN4UCZdcEV1dURTLTQsa3d2bG4uR19ufGhsXWRQWF8xamgxbEF6TT9XXXdTL0pMdG9BSGNmckhmZFZuQiVUeV1dRE8ySy5uNV03NXZCSGVWVGxyY3FobytzRi8rdV0='}]);
	</script>
<noscript><img src="https://pixel.wp.com/b.gif?v=noscript" style="height:0px;width:0px;overflow:hidden" alt="" /></noscript>
		<div id="wpadminbar" class="nojq nojs ltr">
							<a class="screen-reader-shortcut" href="#wp-toolbar" tabindex="1">Skip to toolbar</a>
						<div class="quicklinks" id="wp-toolbar" role="navigation" aria-label="Toolbar" tabindex="0">
						<ul id="wp-admin-bar-root-default" class="ab-top-menu">
			
		<li id="wp-admin-bar-blog" class="menupop my-sites mb-trackable"><a class="ab-item"  aria-haspopup="true" href="https://wordpress.com/stats/pybeebee.wordpress.com">My Sites</a>			<div class="ab-sub-wrapper">		<ul id="wp-admin-bar-blog-default" class="ab-submenu">
			
		<li id="wp-admin-bar-switch-site"><a class="ab-item"  href="https://wordpress.com/sites">Switch Site</a>		</li>
		<li id="wp-admin-bar-blog-info" class="has-blavatar"><a class="ab-item"  href="https://pybeebee.wordpress.com/"><div class="ab-site-icon"><img class="avatar" src="https://pybeebee.files.wordpress.com/2017/10/cropped-mecat.jpg?w=120" alt="Current site avatar" /> </div><span class="ab-site-title">pybeebee.wordpress.c&hellip;</span><span class="ab-site-description">pybeebee.wordpress.com</span></a>		</li>
		<li id="wp-admin-bar-blog-stats" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/stats/pybeebee.wordpress.com">Stats <img style="width: 95px; margin: 0; float: right;" src="https://pybeebee.wordpress.com/wp-includes/charts/admin-bar-hours-scale-2x.php?masterbar=1" alt="Stats" title="Showing site views per hour for the last 48 hours. Click for full Site Stats." /></a>		</li>
		<li id="wp-admin-bar-activity" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/activity-log/pybeebee.wordpress.com">Activity</a>		</li>
		<li id="wp-admin-bar-plan" class="inline-action">		<div class="ab-item ab-empty-item" ><a href="https://wordpress.com/plans/pybeebee.wordpress.com" class="ab-item ab-primary mb-icon" id="wp-admin-bar-plan">Plan</a><a href="https://wordpress.com/plans/pybeebee.wordpress.com" class="ab-secondary" id="wp-admin-bar-plan-badge">Free</a></div>		</li>		</ul>
			<ul id="wp-admin-bar-publish" class="ab-submenu">
			
		<li id="wp-admin-bar-publish-header" class="ab-submenu-header">		<div class="ab-item ab-empty-item" >Manage</div>		</li>
		<li id="wp-admin-bar-new-page" class="inline-action">		<div class="ab-item ab-empty-item" ><a href="https://wordpress.com/pages/pybeebee.wordpress.com" class="ab-item ab-primary mb-icon" id="wp-admin-bar-edit-page">Site Pages</a><a href="https://wordpress.com/page/pybeebee.wordpress.com" class="ab-secondary" id="wp-admin-bar-new-page-badge">Add</a></div>		</li>
		<li id="wp-admin-bar-new-post" class="inline-action">		<div class="ab-item ab-empty-item" ><a href="https://wordpress.com/posts/pybeebee.wordpress.com" class="ab-item ab-primary mb-icon" id="wp-admin-bar-edit-post">Blog Posts</a><a href="https://wordpress.com/post/pybeebee.wordpress.com" class="ab-secondary" id="wp-admin-bar-new-post-badge">Add</a></div>		</li>
		<li id="wp-admin-bar-new-attachment" class="inline-action">		<div class="ab-item ab-empty-item" ><a href="https://wordpress.com/media/pybeebee.wordpress.com" class="ab-item ab-primary mb-icon" id="wp-admin-bar-edit-attachment">Media</a><a href="https://wordpress.com/media/pybeebee.wordpress.com" class="ab-secondary" id="wp-admin-bar-new-attachment-badge">Add</a></div>		</li>
		<li id="wp-admin-bar-new-jetpack-testimonial" class="inline-action">		<div class="ab-item ab-empty-item" ><a href="https://wordpress.com/types/jetpack-testimonial/pybeebee.wordpress.com" class="ab-item ab-primary mb-icon" id="wp-admin-bar-edit-jetpack-testimonial">Testimonials</a><a href="https://pybeebee.wordpress.com/wp-admin/post-new.php?post_type=jetpack-testimonial" class="ab-secondary" id="wp-admin-bar-new-jetpack-testimonial-badge">Add</a></div>		</li>
		<li id="wp-admin-bar-comments" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/comments/pybeebee.wordpress.com">Comments</a>		</li>		</ul>
			<ul id="wp-admin-bar-look-and-feel" class="ab-submenu">
			
		<li id="wp-admin-bar-look-and-feel-header" class="ab-submenu-header">		<div class="ab-item ab-empty-item" >Personalize</div>		</li>
		<li id="wp-admin-bar-themes" class="inline-action">		<div class="ab-item ab-empty-item" ><a href="https://pybeebee.wordpress.com/wp-admin/customize.php?url=https%3A%2F%2Fpybeebee.wordpress.com%2F2017%2F07%2F15%2Fconstructing-an-anthropomorphic-robotic-agent-for-emotion-recognition-and-generation%2F" class="ab-item ab-primary mb-icon" id="wp-admin-bar-cmz">Customize</a><a href="https://wordpress.com/themes/pybeebee.wordpress.com" class="ab-secondary" id="wp-admin-bar-themes">Themes</a></div>		</li>		</ul>
			<ul id="wp-admin-bar-configuration" class="ab-submenu">
			
		<li id="wp-admin-bar-configuration-header" class="ab-submenu-header">		<div class="ab-item ab-empty-item" >Configure</div>		</li>
		<li id="wp-admin-bar-sharing" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/sharing/pybeebee.wordpress.com">Sharing</a>		</li>
		<li id="wp-admin-bar-users-toolbar" class="inline-action">		<div class="ab-item ab-empty-item" ><a href="https://wordpress.com/people/team/pybeebee.wordpress.com" class="ab-item ab-primary mb-icon" id="wp-admin-bar-people">People</a><a href="https://wordpress.com/people/new/pybeebee.wordpress.com" class="ab-secondary" id="wp-admin-bar-people-add">Add</a></div>		</li>
		<li id="wp-admin-bar-plugins"><a class="ab-item"  href="https://wordpress.com/plugins/wpcom-masterbar-redirect/pybeebee.wordpress.com">Plugins</a>		</li>
		<li id="wp-admin-bar-domains" class="inline-action">		<div class="ab-item ab-empty-item" ><a href="https://wordpress.com/domains/pybeebee.wordpress.com" class="ab-item ab-primary mb-icon" id="wp-admin-bar-domains">Domains</a><a href="https://wordpress.com/domains/add/pybeebee.wordpress.com" class="ab-secondary" id="wp-admin-bar-domains-add">Add</a></div>		</li>
		<li id="wp-admin-bar-blog-settings" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/settings/general/pybeebee.wordpress.com">Settings</a>		</li>
		<li id="wp-admin-bar-legacy-dashboard" class="mb-icon"><a class="ab-item"  href="https://pybeebee.wordpress.com/wp-admin/">WP Admin</a>		</li>		</ul>
	</div>		</li>
		<li id="wp-admin-bar-jumptotop-button-menu"><a class="ab-item"  href="#"><div id="jumptotop"><span class="noticon noticon-top"></span></div></a>		</li>
		<li id="wp-admin-bar-newdash" class="menupop mb-trackable"><a class="ab-item"  aria-haspopup="true" href="https://wordpress.com/">Reader</a>			<div class="ab-sub-wrapper">		<ul id="wp-admin-bar-newdash-default" class="ab-submenu">
			
		<li id="wp-admin-bar-streams-header" class="ab-submenu-header">		<div class="ab-item ab-empty-item" >Streams</div>		</li>
		<li id="wp-admin-bar-following" class="inline-action">		<div class="ab-item ab-empty-item" ><a href="https://wordpress.com/" class="ab-item ab-primary mb-icon" id="wp-admin-bar-followed-sites">Followed Sites</a><a href="https://wordpress.com/following/edit" class="ab-secondary" id="wp-admin-bar-reader-followed-sites-manage">Manage</a></div>		</li>
		<li id="wp-admin-bar-conversations" class="mb-icon"><a class="ab-item"  href="http://wordpress.com/read/conversations">Conversations</a>		</li>
		<li id="wp-admin-bar-discover-discover" class="mb-icon-spacer"><a class="ab-item"  href="https://wordpress.com/discover">Discover</a>		</li>
		<li id="wp-admin-bar-discover-search" class="mb-icon-spacer"><a class="ab-item"  href="https://wordpress.com/read/search">Search</a>		</li>
		<li id="wp-admin-bar-my-activity-my-likes" class="mb-icon-spacer"><a class="ab-item"  href="https://wordpress.com/activities/likes">My Likes</a>		</li>		</ul>
	</div>		</li>		</ul>
			<ul id="wp-admin-bar-top-secondary" class="ab-top-secondary ab-top-menu">
			
		<li id="wp-admin-bar-notes" class="menupop">		<div class="ab-item ab-empty-item" ><span id="wpnt-notes-unread-count" class="wpnt-loading wpn-read"></span><span class="noticon noticon-bell"></span><span class="ab-text">Notifications</span></div><div id="wpnt-notes-panel2" style="display:none" lang="en" dir="ltr"><div class="wpnt-notes-panel-header"><span class="wpnt-notes-header"></span><span class="wpnt-notes-panel-link"></span></div></div>		</li>
		<li id="wp-admin-bar-my-account" class="menupop with-avatar mb-trackable"><a class="ab-item"  aria-haspopup="true" href="https://wordpress.com/me/"><img alt='' src='https://1.gravatar.com/avatar/7bee77b11588d6124d8d4f8079e4cc19?s=32&#038;d=mm&#038;r=G' class='avatar avatar-32' height='32' width='32' /><span class="ab-text">Me</span></a>			<div class="ab-sub-wrapper">		<ul id="wp-admin-bar-user-actions" class="ab-submenu">
			
		<li id="wp-admin-bar-user-info" class="user-info user-info-item">		<div class="ab-item ab-empty-item" tabindex="-1"><img alt='' src='https://1.gravatar.com/avatar/7bee77b11588d6124d8d4f8079e4cc19?s=128&#038;d=mm&#038;r=G' class='avatar avatar-128' height='128' width='128' /><span class="display-name">Gabrielle Liu</span><a class="username" href="http://gravatar.com/pybeebee">@pybeebee</a><form action="https://pybeebee.wordpress.com/wp-login.php?action=logout&amp;redirect_to=https%3A%2F%2Fwordpress.com%2F%3Fapppromo&amp;_wpnonce=0eaec1af7c" method="post"><button class="ab-sign-out" type="submit">Sign Out</button></form></div>		</li>
		<li id="wp-admin-bar-profile-header" class="ab-submenu-header">		<div class="ab-item ab-empty-item" >Profile</div>		</li>
		<li id="wp-admin-bar-my-profile" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/me">My Profile</a>		</li>
		<li id="wp-admin-bar-account-settings" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/me/account">Account Settings</a>		</li>
		<li id="wp-admin-bar-billing" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/me/purchases">Manage Purchases</a>		</li>
		<li id="wp-admin-bar-security" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/me/security">Security</a>		</li>
		<li id="wp-admin-bar-notifications" class="mb-icon mb-trackable"><a class="ab-item"  href="https://wordpress.com/me/notifications">Notifications</a>		</li>
		<li id="wp-admin-bar-special-header" class="ab-submenu-header">		<div class="ab-item ab-empty-item" >Special</div>		</li>
		<li id="wp-admin-bar-get-apps" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/me/get-apps">Get Apps</a>		</li>
		<li id="wp-admin-bar-help" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/help">Help</a>		</li>		</ul>
	</div>		</li>
		<li id="wp-admin-bar-ab-new-post" class="mb-trackable"><a class="ab-item"  href="https://wordpress.com/post/pybeebee.wordpress.com"><span>Write</span></a>		</li>		</ul>
				</div>
							<a class="screen-reader-shortcut" href="https://pybeebee.wordpress.com/wp-login.php?action=logout&#038;_wpnonce=0eaec1af7c">Log Out</a>
					</div>

	
<script type="text/javascript">
/* <![CDATA[ */
var clickDebugLink;

jQuery(document).ready( function($) {
	var single = true, w = 1000,
		supe = false;

	$(document.body).load(function(){ $('#wpadminbar img.grav-hashed').removeClass('grav-hashed'); }); // hack to hide the gravatar hovercard

	if ( single && supe )
		w = 1385;
	else if ( supe )
		w = 1200;

	// debug bar extra
	clickDebugLink = function( parent_id, obj ) {

		$('#'+parent_id).children('div').hide();

		document.getElementById( obj.href.substr( obj.href.indexOf( '#' ) + 1 ) ).style.display = 'block';
		$( obj.href.substr( obj.href.indexOf( '#' ) ) ).show()

		$(obj).parent().addClass('current').siblings('li').removeClass('current');

		return false;
	};

	$( '#wpadminbar #wp-admin-bar-shortlink' ).click( function() {
		$( '#adminbar-shortlink-input' ).select();
	});

	// skip tap-to-hover on site switcher for mobile
	if ( 'ontouchstart' in window ) {
		$('#wp-admin-bar-switch-site').on( 'touchstart', function( event ) {
			if ( $( window ).width() > 782 ) {
				return;
			}
			event.stopPropagation();
			$( event.target ).first( 'a' ).click();
		});
	}

});
/* ]]> */
</script>
	<div class="wpcom-bubble action-bubble">
		<div class="bubble-txt"></div>
	</div>
	<script type="text/javascript">function hideBubble() { jQuery('body').append( jQuery( 'div.wpcom-bubble' ).removeClass( 'fadein' ) ).off( 'click.bubble touchstart.bubble' ); jQuery(document).off( 'scroll.bubble' ); };</script>
		<script type="text/javascript">
	jQuery( '#wp-admin-bar-jumptotop-button-menu a' ).click( function( e ) {
		e.preventDefault();
		jQuery( 'html, body' ).animate( { scrollTop: 0 }, 'fast' );
	} );
	function hideShowTbJumpToTop() {
		var total_width = 0;
		// Calculate total width taken by items minus our button to see if it'll
		// overlap with other toolbar menus.
		jQuery( '#wp-admin-bar-root-default > li' ).each( function() {
			var self = jQuery( this );
			if ( 'wp-admin-bar-jumptotop-button-menu' != self.attr( 'id' ) )
				total_width += self.width();
		});
		if ( jQuery( '#wp-admin-bar-jumptotop-button-menu' ).position()['left'] - total_width < 10 ) {
			jQuery( '#jumptotop' ).animate( { 'top': '-50px' }, 'fast' );
		} else if (  jQuery( window ).scrollTop() >= 350 && parseInt( jQuery( '#jumptotop' ).css( 'top' ) ) < 0 ) {
			if ( jQuery( '#wp-admin-bar-jumptotop-button-menu' ).position()['left'] - total_width < 10 )
			   return;
			jQuery( '#jumptotop' ).animate( { 'top': 0 }, 'fast' );
		} else if (  jQuery( window ).scrollTop() < 1 && parseInt( jQuery( '#jumptotop' ).css( 'top' ) ) >= 0 ) {
			jQuery( '#jumptotop' ).animate( { 'top': '-50px' }, 'fast' );
		}
	}
	// handle on page load if auto scrolling to a position
	hideShowTbJumpToTop();
	// bind to scrolll event
	var jumpToTopTimer = null;
	jQuery( window ).scroll( function() {
		clearTimeout( jumpToTopTimer );
		jumpToTopTimer = setTimeout( jumpToTopRefresh, 150 );
	} );
	var jumpToTopRefresh = function() {
		hideShowTbJumpToTop();
	};
	</script>
			<script>
			jQuery( '#resend-verifyemail' ).on( 'click', function(e) {
				var link = jQuery(e.target);

				e.preventDefault();

				var r = jQuery.ajax( {
					type: 'POST',
					url: '/wp-admin/admin-ajax.php',
					data: {
						'action': 'resend_verify_email',
						'_wpnonce': link.data( 'nonce' )
					}
				} );

				setTimeout( function() {
					link.hide();
					link.after( '<strong id="email-sent">Email Sent</strong>' );
				}, 200 );

				setTimeout( function() {
					jQuery( "strong#email-sent" ).hide().remove();
					link.show();
				}, 4000 );
			} );
		</script>
	<script>
if ( 'object' === typeof wpcom_mobile_user_agent_info ) {

	wpcom_mobile_user_agent_info.init();
	var mobileStatsQueryString = "";
	
	if( false !== wpcom_mobile_user_agent_info.matchedPlatformName )
		mobileStatsQueryString += "&x_" + 'mobile_platforms' + '=' + wpcom_mobile_user_agent_info.matchedPlatformName;
	
	if( false !== wpcom_mobile_user_agent_info.matchedUserAgentName )
		mobileStatsQueryString += "&x_" + 'mobile_devices' + '=' + wpcom_mobile_user_agent_info.matchedUserAgentName;
	
	if( wpcom_mobile_user_agent_info.isIPad() )
		mobileStatsQueryString += "&x_" + 'ipad_views' + '=' + 'views';

	if( "" != mobileStatsQueryString ) {
		new Image().src = document.location.protocol + '//pixel.wp.com/g.gif?v=wpcom-no-pv' + mobileStatsQueryString + '&baba=' + Math.random();
	}
	
}
</script>
</body>
</html>
