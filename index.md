<!DOCTYPE html>
<!--[if IE 8 ]><html class="no-js oldie ie8" lang="en"> <![endif]-->
<!--[if IE 9 ]><html class="no-js oldie ie9" lang="en"> <![endif]-->
<!--[if (gte IE 9)|!(IE)]><!--><html class="no-js" lang="en"> <!--<![endif]-->
<head>

   <!--- basic page needs
   ================================================== -->
   <meta charset="utf-8">
	<title>MDC</title>
	<meta name="description" content="">  
	<meta name="author" content="">

   <!-- mobile specific metas
   ================================================== -->
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">

 	<!-- CSS
   ================================================== 
   <link rel="stylesheet" href="css/base.css">  
   <link rel="stylesheet" href="css/main.css">
	<link rel="stylesheet" href="css/vendor.css">
	
	<link rel="stylesheet" href="css/Merged.css">
	-->

   <!-- script
   ================================================== -->   
<!--<script src="js/modernizr.js"></script>-->
<script>	
;window.Modernizr=function(a,b,c){function u(a){j.cssText=a}function v(a,b){return u(prefixes.join(a+";")+(b||""))}function w(a,b){return typeof a===b}function x(a,b){return!!~(""+a).indexOf(b)}function y(a,b,d){for(var e in a){var f=b[a[e]];if(f!==c)return d===!1?a[e]:w(f,"function")?f.bind(d||b):f}return!1}var d="2.8.3",e={},f=!0,g=b.documentElement,h="modernizr",i=b.createElement(h),j=i.style,k,l={}.toString,m={},n={},o={},p=[],q=p.slice,r,s={}.hasOwnProperty,t;!w(s,"undefined")&&!w(s.call,"undefined")?t=function(a,b){return s.call(a,b)}:t=function(a,b){return b in a&&w(a.constructor.prototype[b],"undefined")},Function.prototype.bind||(Function.prototype.bind=function(b){var c=this;if(typeof c!="function")throw new TypeError;var d=q.call(arguments,1),e=function(){if(this instanceof e){var a=function(){};a.prototype=c.prototype;var f=new a,g=c.apply(f,d.concat(q.call(arguments)));return Object(g)===g?g:f}return c.apply(b,d.concat(q.call(arguments)))};return e});for(var z in m)t(m,z)&&(r=z.toLowerCase(),e[r]=m[z](),p.push((e[r]?"":"no-")+r));return e.addTest=function(a,b){if(typeof a=="object")for(var d in a)t(a,d)&&e.addTest(d,a[d]);else{a=a.toLowerCase();if(e[a]!==c)return e;b=typeof b=="function"?b():b,typeof f!="undefined"&&f&&(g.className+=" "+(b?"":"no-")+a),e[a]=b}return e},u(""),i=k=null,function(a,b){function l(a,b){var c=a.createElement("p"),d=a.getElementsByTagName("head")[0]||a.documentElement;return c.innerHTML="x<style>"+b+"</style>",d.insertBefore(c.lastChild,d.firstChild)}function m(){var a=s.elements;return typeof a=="string"?a.split(" "):a}function n(a){var b=j[a[h]];return b||(b={},i++,a[h]=i,j[i]=b),b}function o(a,c,d){c||(c=b);if(k)return c.createElement(a);d||(d=n(c));var g;return d.cache[a]?g=d.cache[a].cloneNode():f.test(a)?g=(d.cache[a]=d.createElem(a)).cloneNode():g=d.createElem(a),g.canHaveChildren&&!e.test(a)&&!g.tagUrn?d.frag.appendChild(g):g}function p(a,c){a||(a=b);if(k)return a.createDocumentFragment();c=c||n(a);var d=c.frag.cloneNode(),e=0,f=m(),g=f.length;for(;e<g;e++)d.createElement(f[e]);return d}function q(a,b){b.cache||(b.cache={},b.createElem=a.createElement,b.createFrag=a.createDocumentFragment,b.frag=b.createFrag()),a.createElement=function(c){return s.shivMethods?o(c,a,b):b.createElem(c)},a.createDocumentFragment=Function("h,f","return function(){var n=f.cloneNode(),c=n.createElement;h.shivMethods&&("+m().join().replace(/[\w\-]+/g,function(a){return b.createElem(a),b.frag.createElement(a),'c("'+a+'")'})+");return n}")(s,b.frag)}function r(a){a||(a=b);var c=n(a);return s.shivCSS&&!g&&!c.hasCSS&&(c.hasCSS=!!l(a,"article,aside,dialog,figcaption,figure,footer,header,hgroup,main,nav,section{display:block}mark{background:#FF0;color:#000}template{display:none}")),k||q(a,c),a}var c="3.7.0",d=a.html5||{},e=/^<|^(?:button|map|select|textarea|object|iframe|option|optgroup)$/i,f=/^(?:a|b|code|div|fieldset|h1|h2|h3|h4|h5|h6|i|label|li|ol|p|q|span|strong|style|table|tbody|td|th|tr|ul)$/i,g,h="_html5shiv",i=0,j={},k;(function(){try{var a=b.createElement("a");a.innerHTML="<xyz></xyz>",g="hidden"in a,k=a.childNodes.length==1||function(){b.createElement("a");var a=b.createDocumentFragment();return typeof a.cloneNode=="undefined"||typeof a.createDocumentFragment=="undefined"||typeof a.createElement=="undefined"}()}catch(c){g=!0,k=!0}})();var s={elements:d.elements||"abbr article aside audio bdi canvas data datalist details dialog figcaption figure footer header hgroup main mark meter nav output progress section summary template time video",version:c,shivCSS:d.shivCSS!==!1,supportsUnknownElements:k,shivMethods:d.shivMethods!==!1,type:"default",shivDocument:r,createElement:o,createDocumentFragment:p};a.html5=s,r(b)}(this,b),e._version=d,g.className=g.className.replace(/(^|\s)no-js(\s|$)/,"$1$2")+(f?" js "+p.join(" "):""),e}(this,this.document),function(a,b,c){function d(a){return"[object Function]"==o.call(a)}function e(a){return"string"==typeof a}function f(){}function g(a){return!a||"loaded"==a||"complete"==a||"uninitialized"==a}function h(){var a=p.shift();q=1,a?a.t?m(function(){("c"==a.t?B.injectCss:B.injectJs)(a.s,0,a.a,a.x,a.e,1)},0):(a(),h()):q=0}function i(a,c,d,e,f,i,j){function k(b){if(!o&&g(l.readyState)&&(u.r=o=1,!q&&h(),l.onload=l.onreadystatechange=null,b)){"img"!=a&&m(function(){t.removeChild(l)},50);for(var d in y[c])y[c].hasOwnProperty(d)&&y[c][d].onload()}}var j=j||B.errorTimeout,l=b.createElement(a),o=0,r=0,u={t:d,s:c,e:f,a:i,x:j};1===y[c]&&(r=1,y[c]=[]),"object"==a?l.data=c:(l.src=c,l.type=a),l.width=l.height="0",l.onerror=l.onload=l.onreadystatechange=function(){k.call(this,r)},p.splice(e,0,u),"img"!=a&&(r||2===y[c]?(t.insertBefore(l,s?null:n),m(k,j)):y[c].push(l))}function j(a,b,c,d,f){return q=0,b=b||"j",e(a)?i("c"==b?v:u,a,b,this.i++,c,d,f):(p.splice(this.i++,0,a),1==p.length&&h()),this}function k(){var a=B;return a.loader={load:j,i:0},a}var l=b.documentElement,m=a.setTimeout,n=b.getElementsByTagName("script")[0],o={}.toString,p=[],q=0,r="MozAppearance"in l.style,s=r&&!!b.createRange().compareNode,t=s?l:n.parentNode,l=a.opera&&"[object Opera]"==o.call(a.opera),l=!!b.attachEvent&&!l,u=r?"object":l?"script":"img",v=l?"script":u,w=Array.isArray||function(a){return"[object Array]"==o.call(a)},x=[],y={},z={timeout:function(a,b){return b.length&&(a.timeout=b[0]),a}},A,B;B=function(a){function b(a){var a=a.split("!"),b=x.length,c=a.pop(),d=a.length,c={url:c,origUrl:c,prefixes:a},e,f,g;for(f=0;f<d;f++)g=a[f].split("="),(e=z[g.shift()])&&(c=e(c,g));for(f=0;f<b;f++)c=x[f](c);return c}function g(a,e,f,g,h){var i=b(a),j=i.autoCallback;i.url.split(".").pop().split("?").shift(),i.bypass||(e&&(e=d(e)?e:e[a]||e[g]||e[a.split("/").pop().split("?")[0]]),i.instead?i.instead(a,e,f,g,h):(y[i.url]?i.noexec=!0:y[i.url]=1,f.load(i.url,i.forceCSS||!i.forceJS&&"css"==i.url.split(".").pop().split("?").shift()?"c":c,i.noexec,i.attrs,i.timeout),(d(e)||d(j))&&f.load(function(){k(),e&&e(i.origUrl,h,g),j&&j(i.origUrl,h,g),y[i.url]=2})))}function h(a,b){function c(a,c){if(a){if(e(a))c||(j=function(){var a=[].slice.call(arguments);k.apply(this,a),l()}),g(a,j,b,0,h);else if(Object(a)===a)for(n in m=function(){var b=0,c;for(c in a)a.hasOwnProperty(c)&&b++;return b}(),a)a.hasOwnProperty(n)&&(!c&&!--m&&(d(j)?j=function(){var a=[].slice.call(arguments);k.apply(this,a),l()}:j[n]=function(a){return function(){var b=[].slice.call(arguments);a&&a.apply(this,b),l()}}(k[n])),g(a[n],j,b,n,h))}else!c&&l()}var h=!!a.test,i=a.load||a.both,j=a.callback||f,k=j,l=a.complete||f,m,n;c(h?a.yep:a.nope,!!i),i&&c(i)}var i,j,l=this.yepnope.loader;if(e(a))g(a,0,l,0);else if(w(a))for(i=0;i<a.length;i++)j=a[i],e(j)?g(j,0,l,0):w(j)?B(j):Object(j)===j&&h(j,l);else Object(a)===a&&h(a,l)},B.addPrefix=function(a,b){z[a]=b},B.addFilter=function(a){x.push(a)},B.errorTimeout=1e4,null==b.readyState&&b.addEventListener&&(b.readyState="loading",b.addEventListener("DOMContentLoaded",A=function(){b.removeEventListener("DOMContentLoaded",A,0),b.readyState="complete"},0)),a.yepnope=k(),a.yepnope.executeStack=h,a.yepnope.injectJs=function(a,c,d,e,i,j){var k=b.createElement("script"),l,o,e=e||B.errorTimeout;k.src=a;for(o in d)k.setAttribute(o,d[o]);c=j?h:c||f,k.onreadystatechange=k.onload=function(){!l&&g(k.readyState)&&(l=1,c(),k.onload=k.onreadystatechange=null)},m(function(){l||(l=1,c(1))},e),i?k.onload():n.parentNode.insertBefore(k,n)},a.yepnope.injectCss=function(a,c,d,e,g,i){var e=b.createElement("link"),j,c=i?h:c||f;e.href=a,e.rel="stylesheet",e.type="text/css";for(j in d)e.setAttribute(j,d[j]);g||(n.parentNode.insertBefore(e,n),m(c,0))}}(this,document),Modernizr.load=function(){yepnope.apply(window,[].slice.call(arguments,0))};
</script>	
<!--<script src="js/pace.min.js"></script>-->
<script>
(function(){var a,b,c,d,e,f,g,h,i,j,k,l,m,n,o,p,q,r,s,t,u,v,w,x,y,z,A,B,C,D,E,F,G,H,I,J,K,L,M,N,O,P,Q,R,S,T,U,V,W,X=[].slice,Y={}.hasOwnProperty,Z=function(a,b){function c(){this.constructor=a}for(var d in b)Y.call(b,d)&&(a[d]=b[d]);return c.prototype=b.prototype,a.prototype=new c,a.__super__=b.prototype,a},$=[].indexOf||function(a){for(var b=0,c=this.length;c>b;b++)if(b in this&&this[b]===a)return b;return-1};for(u={catchupTime:100,initialRate:.03,minTime:250,ghostTime:100,maxProgressPerFrame:20,easeFactor:1.25,startOnPageLoad:!0,restartOnPushState:!0,restartOnRequestAfter:500,target:"body",elements:{checkInterval:100,selectors:["body"]},eventLag:{minSamples:10,sampleCount:3,lagThreshold:3},ajax:{trackMethods:["GET"],trackWebSockets:!0,ignoreURLs:[]}},C=function(){var a;return null!=(a="undefined"!=typeof performance&&null!==performance&&"function"==typeof performance.now?performance.now():void 0)?a:+new Date},E=window.requestAnimationFrame||window.mozRequestAnimationFrame||window.webkitRequestAnimationFrame||window.msRequestAnimationFrame,t=window.cancelAnimationFrame||window.mozCancelAnimationFrame,null==E&&(E=function(a){return setTimeout(a,50)},t=function(a){return clearTimeout(a)}),G=function(a){var b,c;return b=C(),(c=function(){var d;return d=C()-b,d>=33?(b=C(),a(d,function(){return E(c)})):setTimeout(c,33-d)})()},F=function(){var a,b,c;return c=arguments[0],b=arguments[1],a=3<=arguments.length?X.call(arguments,2):[],"function"==typeof c[b]?c[b].apply(c,a):c[b]},v=function(){var a,b,c,d,e,f,g;for(b=arguments[0],d=2<=arguments.length?X.call(arguments,1):[],f=0,g=d.length;g>f;f++)if(c=d[f])for(a in c)Y.call(c,a)&&(e=c[a],null!=b[a]&&"object"==typeof b[a]&&null!=e&&"object"==typeof e?v(b[a],e):b[a]=e);return b},q=function(a){var b,c,d,e,f;for(c=b=0,e=0,f=a.length;f>e;e++)d=a[e],c+=Math.abs(d),b++;return c/b},x=function(a,b){var c,d,e;if(null==a&&(a="options"),null==b&&(b=!0),e=document.querySelector("[data-pace-"+a+"]")){if(c=e.getAttribute("data-pace-"+a),!b)return c;try{return JSON.parse(c)}catch(f){return d=f,"undefined"!=typeof console&&null!==console?console.error("Error parsing inline pace options",d):void 0}}},g=function(){function a(){}return a.prototype.on=function(a,b,c,d){var e;return null==d&&(d=!1),null==this.bindings&&(this.bindings={}),null==(e=this.bindings)[a]&&(e[a]=[]),this.bindings[a].push({handler:b,ctx:c,once:d})},a.prototype.once=function(a,b,c){return this.on(a,b,c,!0)},a.prototype.off=function(a,b){var c,d,e;if(null!=(null!=(d=this.bindings)?d[a]:void 0)){if(null==b)return delete this.bindings[a];for(c=0,e=[];c<this.bindings[a].length;)e.push(this.bindings[a][c].handler===b?this.bindings[a].splice(c,1):c++);return e}},a.prototype.trigger=function(){var a,b,c,d,e,f,g,h,i;if(c=arguments[0],a=2<=arguments.length?X.call(arguments,1):[],null!=(g=this.bindings)?g[c]:void 0){for(e=0,i=[];e<this.bindings[c].length;)h=this.bindings[c][e],d=h.handler,b=h.ctx,f=h.once,d.apply(null!=b?b:this,a),i.push(f?this.bindings[c].splice(e,1):e++);return i}},a}(),j=window.Pace||{},window.Pace=j,v(j,g.prototype),D=j.options=v({},u,window.paceOptions,x()),U=["ajax","document","eventLag","elements"],Q=0,S=U.length;S>Q;Q++)K=U[Q],D[K]===!0&&(D[K]=u[K]);i=function(a){function b(){return V=b.__super__.constructor.apply(this,arguments)}return Z(b,a),b}(Error),b=function(){function a(){this.progress=0}return a.prototype.getElement=function(){var a;if(null==this.el){if(a=document.querySelector(D.target),!a)throw new i;this.el=document.createElement("div"),this.el.className="pace pace-active",document.body.className=document.body.className.replace(/pace-done/g,""),document.body.className+=" pace-running",this.el.innerHTML='<div class="pace-progress">\n  <div class="pace-progress-inner"></div>\n</div>\n<div class="pace-activity"></div>',null!=a.firstChild?a.insertBefore(this.el,a.firstChild):a.appendChild(this.el)}return this.el},a.prototype.finish=function(){var a;return a=this.getElement(),a.className=a.className.replace("pace-active",""),a.className+=" pace-inactive",document.body.className=document.body.className.replace("pace-running",""),document.body.className+=" pace-done"},a.prototype.update=function(a){return this.progress=a,this.render()},a.prototype.destroy=function(){try{this.getElement().parentNode.removeChild(this.getElement())}catch(a){i=a}return this.el=void 0},a.prototype.render=function(){var a,b,c,d,e,f,g;if(null==document.querySelector(D.target))return!1;for(a=this.getElement(),d="translate3d("+this.progress+"%, 0, 0)",g=["webkitTransform","msTransform","transform"],e=0,f=g.length;f>e;e++)b=g[e],a.children[0].style[b]=d;return(!this.lastRenderedProgress||this.lastRenderedProgress|0!==this.progress|0)&&(a.children[0].setAttribute("data-progress-text",""+(0|this.progress)+"%"),this.progress>=100?c="99":(c=this.progress<10?"0":"",c+=0|this.progress),a.children[0].setAttribute("data-progress",""+c)),this.lastRenderedProgress=this.progress},a.prototype.done=function(){return this.progress>=100},a}(),h=function(){function a(){this.bindings={}}return a.prototype.trigger=function(a,b){var c,d,e,f,g;if(null!=this.bindings[a]){for(f=this.bindings[a],g=[],d=0,e=f.length;e>d;d++)c=f[d],g.push(c.call(this,b));return g}},a.prototype.on=function(a,b){var c;return null==(c=this.bindings)[a]&&(c[a]=[]),this.bindings[a].push(b)},a}(),P=window.XMLHttpRequest,O=window.XDomainRequest,N=window.WebSocket,w=function(a,b){var c,d,e,f;f=[];for(d in b.prototype)try{e=b.prototype[d],f.push(null==a[d]&&"function"!=typeof e?a[d]=e:void 0)}catch(g){c=g}return f},A=[],j.ignore=function(){var a,b,c;return b=arguments[0],a=2<=arguments.length?X.call(arguments,1):[],A.unshift("ignore"),c=b.apply(null,a),A.shift(),c},j.track=function(){var a,b,c;return b=arguments[0],a=2<=arguments.length?X.call(arguments,1):[],A.unshift("track"),c=b.apply(null,a),A.shift(),c},J=function(a){var b;if(null==a&&(a="GET"),"track"===A[0])return"force";if(!A.length&&D.ajax){if("socket"===a&&D.ajax.trackWebSockets)return!0;if(b=a.toUpperCase(),$.call(D.ajax.trackMethods,b)>=0)return!0}return!1},k=function(a){function b(){var a,c=this;b.__super__.constructor.apply(this,arguments),a=function(a){var b;return b=a.open,a.open=function(d,e){return J(d)&&c.trigger("request",{type:d,url:e,request:a}),b.apply(a,arguments)}},window.XMLHttpRequest=function(b){var c;return c=new P(b),a(c),c};try{w(window.XMLHttpRequest,P)}catch(d){}if(null!=O){window.XDomainRequest=function(){var b;return b=new O,a(b),b};try{w(window.XDomainRequest,O)}catch(d){}}if(null!=N&&D.ajax.trackWebSockets){window.WebSocket=function(a,b){var d;return d=null!=b?new N(a,b):new N(a),J("socket")&&c.trigger("request",{type:"socket",url:a,protocols:b,request:d}),d};try{w(window.WebSocket,N)}catch(d){}}}return Z(b,a),b}(h),R=null,y=function(){return null==R&&(R=new k),R},I=function(a){var b,c,d,e;for(e=D.ajax.ignoreURLs,c=0,d=e.length;d>c;c++)if(b=e[c],"string"==typeof b){if(-1!==a.indexOf(b))return!0}else if(b.test(a))return!0;return!1},y().on("request",function(b){var c,d,e,f,g;return f=b.type,e=b.request,g=b.url,I(g)?void 0:j.running||D.restartOnRequestAfter===!1&&"force"!==J(f)?void 0:(d=arguments,c=D.restartOnRequestAfter||0,"boolean"==typeof c&&(c=0),setTimeout(function(){var b,c,g,h,i,k;if(b="socket"===f?e.readyState<2:0<(h=e.readyState)&&4>h){for(j.restart(),i=j.sources,k=[],c=0,g=i.length;g>c;c++){if(K=i[c],K instanceof a){K.watch.apply(K,d);break}k.push(void 0)}return k}},c))}),a=function(){function a(){var a=this;this.elements=[],y().on("request",function(){return a.watch.apply(a,arguments)})}return a.prototype.watch=function(a){var b,c,d,e;return d=a.type,b=a.request,e=a.url,I(e)?void 0:(c="socket"===d?new n(b):new o(b),this.elements.push(c))},a}(),o=function(){function a(a){var b,c,d,e,f,g,h=this;if(this.progress=0,null!=window.ProgressEvent)for(c=null,a.addEventListener("progress",function(a){return h.progress=a.lengthComputable?100*a.loaded/a.total:h.progress+(100-h.progress)/2},!1),g=["load","abort","timeout","error"],d=0,e=g.length;e>d;d++)b=g[d],a.addEventListener(b,function(){return h.progress=100},!1);else f=a.onreadystatechange,a.onreadystatechange=function(){var b;return 0===(b=a.readyState)||4===b?h.progress=100:3===a.readyState&&(h.progress=50),"function"==typeof f?f.apply(null,arguments):void 0}}return a}(),n=function(){function a(a){var b,c,d,e,f=this;for(this.progress=0,e=["error","open"],c=0,d=e.length;d>c;c++)b=e[c],a.addEventListener(b,function(){return f.progress=100},!1)}return a}(),d=function(){function a(a){var b,c,d,f;for(null==a&&(a={}),this.elements=[],null==a.selectors&&(a.selectors=[]),f=a.selectors,c=0,d=f.length;d>c;c++)b=f[c],this.elements.push(new e(b))}return a}(),e=function(){function a(a){this.selector=a,this.progress=0,this.check()}return a.prototype.check=function(){var a=this;return document.querySelector(this.selector)?this.done():setTimeout(function(){return a.check()},D.elements.checkInterval)},a.prototype.done=function(){return this.progress=100},a}(),c=function(){function a(){var a,b,c=this;this.progress=null!=(b=this.states[document.readyState])?b:100,a=document.onreadystatechange,document.onreadystatechange=function(){return null!=c.states[document.readyState]&&(c.progress=c.states[document.readyState]),"function"==typeof a?a.apply(null,arguments):void 0}}return a.prototype.states={loading:0,interactive:50,complete:100},a}(),f=function(){function a(){var a,b,c,d,e,f=this;this.progress=0,a=0,e=[],d=0,c=C(),b=setInterval(function(){var g;return g=C()-c-50,c=C(),e.push(g),e.length>D.eventLag.sampleCount&&e.shift(),a=q(e),++d>=D.eventLag.minSamples&&a<D.eventLag.lagThreshold?(f.progress=100,clearInterval(b)):f.progress=100*(3/(a+3))},50)}return a}(),m=function(){function a(a){this.source=a,this.last=this.sinceLastUpdate=0,this.rate=D.initialRate,this.catchup=0,this.progress=this.lastProgress=0,null!=this.source&&(this.progress=F(this.source,"progress"))}return a.prototype.tick=function(a,b){var c;return null==b&&(b=F(this.source,"progress")),b>=100&&(this.done=!0),b===this.last?this.sinceLastUpdate+=a:(this.sinceLastUpdate&&(this.rate=(b-this.last)/this.sinceLastUpdate),this.catchup=(b-this.progress)/D.catchupTime,this.sinceLastUpdate=0,this.last=b),b>this.progress&&(this.progress+=this.catchup*a),c=1-Math.pow(this.progress/100,D.easeFactor),this.progress+=c*this.rate*a,this.progress=Math.min(this.lastProgress+D.maxProgressPerFrame,this.progress),this.progress=Math.max(0,this.progress),this.progress=Math.min(100,this.progress),this.lastProgress=this.progress,this.progress},a}(),L=null,H=null,r=null,M=null,p=null,s=null,j.running=!1,z=function(){return D.restartOnPushState?j.restart():void 0},null!=window.history.pushState&&(T=window.history.pushState,window.history.pushState=function(){return z(),T.apply(window.history,arguments)}),null!=window.history.replaceState&&(W=window.history.replaceState,window.history.replaceState=function(){return z(),W.apply(window.history,arguments)}),l={ajax:a,elements:d,document:c,eventLag:f},(B=function(){var a,c,d,e,f,g,h,i;for(j.sources=L=[],g=["ajax","elements","document","eventLag"],c=0,e=g.length;e>c;c++)a=g[c],D[a]!==!1&&L.push(new l[a](D[a]));for(i=null!=(h=D.extraSources)?h:[],d=0,f=i.length;f>d;d++)K=i[d],L.push(new K(D));return j.bar=r=new b,H=[],M=new m})(),j.stop=function(){return j.trigger("stop"),j.running=!1,r.destroy(),s=!0,null!=p&&("function"==typeof t&&t(p),p=null),B()},j.restart=function(){return j.trigger("restart"),j.stop(),j.start()},j.go=function(){var a;return j.running=!0,r.render(),a=C(),s=!1,p=G(function(b,c){var d,e,f,g,h,i,k,l,n,o,p,q,t,u,v,w;for(l=100-r.progress,e=p=0,f=!0,i=q=0,u=L.length;u>q;i=++q)for(K=L[i],o=null!=H[i]?H[i]:H[i]=[],h=null!=(w=K.elements)?w:[K],k=t=0,v=h.length;v>t;k=++t)g=h[k],n=null!=o[k]?o[k]:o[k]=new m(g),f&=n.done,n.done||(e++,p+=n.tick(b));return d=p/e,r.update(M.tick(b,d)),r.done()||f||s?(r.update(100),j.trigger("done"),setTimeout(function(){return r.finish(),j.running=!1,j.trigger("hide")},Math.max(D.ghostTime,Math.max(D.minTime-(C()-a),0)))):c()})},j.start=function(a){v(D,a),j.running=!0;try{r.render()}catch(b){i=b}return document.querySelector(".pace")?(j.trigger("start"),j.go()):setTimeout(j.start,50)},"function"==typeof define&&define.amd?define(function(){return j}):"object"==typeof exports?module.exports=j:D.startOnPageLoad&&j.start()}).call(this);
</script>

   <!-- favicons
	================================================== -->
	<link rel="icon" type="image/png" href="favicon.png">

</head>

<body id="top">

<style>
/**
 * =================================================================== 
 *
 *  MDC v1.0 Stylesheet
 *  url: mattclayton.dev
 *  05-01-2021

 * ------------------------------------------------------------------- 
 */
html {
	font-family: sans-serif;
	-ms-text-size-adjust: 100%;
	-webkit-text-size-adjust: 100%;
}

body {
	margin: 0;
}

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
	display: block;
}

audio,
canvas,
progress,
video {
	display: inline-block;
	vertical-align: baseline;
}

audio:not([controls]) {
	display: none;
	height: 0;
}

[hidden],
template {
	display: none;
}

a {
	background: transparent;
}

a:active,
a:hover {
	outline: 0;
}

abbr[title] {
	border-bottom: 1px dotted;
}

b,
strong {
	font-weight: bold;
}

dfn {
	font-style: italic;
}

h1 {
	font-size: 2em;
	margin: 0.67em 0;
}

mark {
	background: #ff0;
	color: #000;
}

small {
	font-size: 80%;
}

sub,
sup {
	font-size: 75%;
	line-height: 0;
	position: relative;
	vertical-align: baseline;
}

sup {
	top: -0.5em;
}

sub {
	bottom: -0.25em;
}

img {
	border: 0;
}

svg:not(:root) {
	overflow: hidden;
}

figure {
	margin: 1em 40px;
}

hr {
	-moz-box-sizing: content-box;
	box-sizing: content-box;
	height: 0;
}

pre {
	overflow: auto;
}

code,
kbd,
pre,
samp {
	font-family: monospace, monospace;
	font-size: 1em;
}

button,
input,
optgroup,
select,
textarea {
	color: inherit;
	font: inherit;
	margin: 0;
}

button {
	overflow: visible;
}

button,
select {
	text-transform: none;
}

button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
	-webkit-appearance: button;
	cursor: pointer;
}

button[disabled],
html input[disabled] {
	cursor: default;
}

button::-moz-focus-inner,
input::-moz-focus-inner {
	border: 0;
	padding: 0;
}

input {
	line-height: normal;
}

input[type="checkbox"],
input[type="radio"] {
	box-sizing: border-box;
	padding: 0;
}

input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
	height: auto;
}

input[type="search"] {
	-webkit-appearance: textfield;
	-moz-box-sizing: content-box;
	-webkit-box-sizing: content-box;
	box-sizing: content-box;
}

input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
	-webkit-appearance: none;
}

fieldset {
	border: 1px solid #c0c0c0;
	margin: 0 2px;
	padding: 0.35em 0.625em 0.75em;
}

legend {
	border: 0;
	padding: 0;
}

textarea {
	overflow: auto;
}

optgroup {
	font-weight: bold;
}

table {
	border-collapse: collapse;
	border-spacing: 0;
}

td,
th {
	padding: 0;
}


 /*
 * ------------------------------------------------------------------- 
 */
html {
	font-size: 62.5%;
	box-sizing: border-box;
}

*,
*::before,
*::after {
	box-sizing: inherit;
}

body {
	font-weight: normal;
	line-height: 1;
	text-rendering: optimizeLegibility;
	word-wrap: break-word;
	-webkit-overflow-scrolling: touch;
	-webkit-text-size-adjust: none;
}

body,
input,
button {
	-moz-osx-font-smoothing: grayscale;
	-webkit-font-smoothing: antialiased;
}

 /*
 * ------------------------------------------------------------------- 
 */
img,
video {
	max-width: 100%;
	height: auto;
}

 /*
 * ------------------------------------------------------------------- 
 */
div,
dl,
dt,
dd,
ul,
ol,
li,
h1,
h2,
h3,
h4,
h5,
h6,
pre,
form,
p,
blockquote,
th,
td {
	margin: 0;
	padding: 0;
}

h1,
h2,
h3,
h4,
h5,
h6 {
	-webkit-font-variant-ligatures: common-ligatures;
	-moz-font-variant-ligatures: common-ligatures;
	font-variant-ligatures: common-ligatures;
	text-rendering: optimizeLegibility;
}

em,
i {
	font-style: italic;
	line-height: inherit;
}

strong,
b {
	font-weight: bold;
	line-height: inherit;
}

small {
	font-size: 60%;
	line-height: inherit;
}

ol,
ul {
	list-style: none;
}

li {
	display: block;
}

 /*
 * ------------------------------------------------------------------- 
 */
a {
	text-decoration: none;
	line-height: inherit;
}

a img {
	border: none;
}

 /*
 * ------------------------------------------------------------------- 
 */
fieldset {
	margin: 0;
	padding: 0;
}

input[type="email"],
input[type="number"],
input[type="search"],
input[type="text"],
input[type="tel"],
input[type="url"],
input[type="password"],
textarea {
	-webkit-appearance: none;
	-moz-appearance: none;
	-ms-appearance: none;
	-o-appearance: none;
	appearance: none;
}

 /*
 * ------------------------------------------------------------------- 
 */
.row {
	width: 94%;
	max-width: 1140px;
	margin: 0 auto;
}

.row:before,
.row:after {
	content: "";
	display: table;
}

.row:after {
	clear: both;
}

.row .row {
	width: auto;
	max-width: none;
	margin-left: -20px;
	margin-right: -20px;
}

[class*="col-"],
.bgrid {
	float: left;
}

[class*="col-"] + [class*="col-"].end {
	float: right;
}

[class*="col-"] {
	padding: 0 20px;
}

.col-one {
	width: 8.33333%;
}

.col-two,
.col-1-6 {
	width: 16.66667%;
}

.col-three,
.col-1-4 {
	width: 25%;
}

.col-four,
.col-1-3 {
	width: 33.33333%;
}

.col-five {
	width: 41.66667%;
}

.col-six,
.col-1-2 {
	width: 50%;
}

.col-seven {
	width: 58.33333%;
}

.col-eight,
.col-2-3 {
	width: 66.66667%;
}

.col-nine,
.col-3-4 {
	width: 75%;
}

.col-ten,
.col-5-6 {
	width: 83.33333%;
}

.col-eleven {
	width: 91.66667%;
}

.col-twelve,
.col-full {
	width: 100%;
}

 /*
 * ------------------------------------------------------------------- 
 */
@media screen and (max-width:1024px) {
	.row .row {
		margin-left: -18px;
		margin-right: -18px;
	}

	[class*="col-"] {
		padding: 0 18px;
	}

}

 /*
 * ------------------------------------------------------------------- 
 */
@media screen and (max-width:768px) {
	.row {
		width: auto;
		padding-left: 30px;
		padding-right: 30px;
	}

	.row .row {
		padding-left: 0;
		padding-right: 0;
		margin-left: -15px;
		margin-right: -15px;
	}

	[class*="col-"] {
		padding: 0 15px;
	}

	.tab-1-4 {
		width: 25%;
	}

	.tab-1-3 {
		width: 33.33333%;
	}

	.tab-1-2 {
		width: 50%;
	}

	.tab-2-3 {
		width: 66.66667%;
	}

	.tab-3-4 {
		width: 75%;
	}

	.tab-full {
		width: 100%;
	}

}

 /*
 * ------------------------------------------------------------------- 
 */
@media screen and (max-width:600px) {
	.row {
		padding-left: 25px;
		padding-right: 25px;
	}

	.row .row {
		margin-left: -10px;
		margin-right: -10px;
	}

	[class*="col-"] {
		padding: 0 10px;
	}

	.mob-1-4 {
		width: 25%;
	}

	.mob-1-2 {
		width: 50%;
	}

	.mob-3-4 {
		width: 75%;
	}

	.mob-full {
		width: 100%;
	}

}

 /*
 * ------------------------------------------------------------------- 
 */
@media screen and (max-width:400px) {
	.row .row {
		padding-left: 0;
		padding-right: 0;
		margin-left: 0;
		margin-right: 0;
	}

	[class*="col-"] {
		width: 100% !important;
		float: none !important;
		clear: both !important;
		margin-left: 0;
		margin-right: 0;
		padding: 0;
	}

	[class*="col-"] + [class*="col-"].end {
		float: none;
	}

}

 /*
 * ------------------------------------------------------------------- 
 */
[class*="block-"]:before,
[class*="block-"]:after {
	content: "";
	display: table;
}

[class*="block-"]:after {
	clear: both;
}

.block-1-6 .bgrid {
	width: 16.66667%;
}

.block-1-4 .bgrid {
	width: 25%;
}

.block-1-3 .bgrid {
	width: 33.33333%;
}

.block-1-2 .bgrid {
	width: 50%;
}

/**
 * Clearing for block grid columns. Allow columns with 
 * different heights to align properly.
 */
.block-1-6 .bgrid:nth-child(6n+1),
.block-1-4 .bgrid:nth-child(4n+1),
.block-1-3 .bgrid:nth-child(3n+1),
.block-1-2 .bgrid:nth-child(2n+1) {
	clear: both;
}

 /*
 * ------------------------------------------------------------------- 
 */
@media screen and (max-width:1024px) {
	.block-s-1-6 .bgrid {
		width: 16.66667%;
	}

	.block-s-1-4 .bgrid {
		width: 25%;
	}

	.block-s-1-3 .bgrid {
		width: 33.33333%;
	}

	.block-s-1-2 .bgrid {
		width: 50%;
	}

	.block-s-full .bgrid {
		width: 100%;
		clear: both;
	}

	[class*="block-s-"] .bgrid:nth-child(n) {
		clear: none;
	}

	.block-s-1-6 .bgrid:nth-child(6n+1),
	.block-s-1-4 .bgrid:nth-child(4n+1),
	.block-s-1-3 .bgrid:nth-child(3n+1),
	.block-s-1-2 .bgrid:nth-child(2n+1) {
		clear: both;
	}

}

 /*
 * ------------------------------------------------------------------- 
 */
@media screen and (max-width:768px) {
	.block-tab-1-6 .bgrid {
		width: 16.66667%;
	}

	.block-tab-1-4 .bgrid {
		width: 25%;
	}

	.block-tab-1-3 .bgrid {
		width: 33.33333%;
	}

	.block-tab-1-2 .bgrid {
		width: 50%;
	}

	.block-tab-full .bgrid {
		width: 100%;
		clear: both;
	}

	[class*="block-tab-"] .bgrid:nth-child(n) {
		clear: none;
	}

	.block-tab-1-6 .bgrid:nth-child(6n+1),
	.block-tab-1-4 .bgrid:nth-child(4n+1),
	.block-tab-1-3 .bgrid:nth-child(3n+1),
	.block-tab-1-2 .bgrid:nth-child(2n+1) {
		clear: both;
	}

}

 /*
 * ------------------------------------------------------------------- 
 */
@media screen and (max-width:600px) {
	.block-mob-1-6 .bgrid {
		width: 16.66667%;
	}

	.block-mob-1-4 .bgrid {
		width: 25%;
	}

	.block-mob-1-3 .bgrid {
		width: 33.33333%;
	}

	.block-mob-1-2 .bgrid {
		width: 50%;
	}

	.block-mob-full .bgrid {
		width: 100%;
		clear: both;
	}

	[class*="block-mob-"] .bgrid:nth-child(n) {
		clear: none;
	}

	.block-mob-1-6 .bgrid:nth-child(6n+1),
	.block-mob-1-4 .bgrid:nth-child(4n+1),
	.block-mob-1-3 .bgrid:nth-child(3n+1),
	.block-mob-1-2 .bgrid:nth-child(2n+1) {
		clear: both;
	}

}

 /*
 * ------------------------------------------------------------------- 
 */
@media screen and (max-width:400px) {
	.stack .bgrid {
		width: 100% !important;
		float: none !important;
		clear: both !important;
		margin-left: 0;
		margin-right: 0;
	}

}

 /*
 * ------------------------------------------------------------------- 
 */
.group:before,
.group:after {
	content: "";
	display: table;
}

.group:after {
	clear: both;
}

/**
 * Misc Helper Styles 
 */
.hide {
	display: none;
}

.invisible {
	visibility: hidden;
}

.antialiased {
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}

.remove-bottom {
	margin-bottom: 0;
}

.half-bottom {
	margin-bottom: 1.5rem !important;
}

.add-bottom {
	margin-bottom: 3rem !important;
}

.no-border {
	border: none;
}

.full-width {
	width: 100%;
}

.text-center {
	text-align: center;
}

.text-left {
	text-align: left;
}

.text-right {
	text-align: right;
}

.pull-left {
	float: left;
}

.pull-right {
	float: right;
}

.align-center {
	margin-left: auto;
	margin-right: auto;
	text-align: center;
}

 /*
 * ------------------------------------------------------------------- 
 */
html {
	font-size: 10px;
}

@media only screen and (max-width:1024px) {
	html {
		font-size: 9.411764705882353px;
	}
}
@media only screen and (max-width:768px) {
	html {
		font-size: 10px;
	}
}
@media only screen and (max-width:400px) {
	html {
		font-size: 9.411764705882353px;
	}
}

html, body {
	height: 100%;
}
body {
	background: #151515;
	font-family: "lora-regular", serif;
	font-size: 1.7rem;
	line-height: 3rem;
	color: #6e6e6e;
}

/**
 * links - (_document-setup.scss)
 * -------------------------------------------------------------------
 */ /*
 * ------------------------------------------------------------------- 
 */	-webkit-transition: all 0.3s ease-in-out;
	-ms-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}
a:hover, a:focus, a:active {
	color: #ff2f00;
	outline: 0;
}

 /*
 * ------------------------------------------------------------------- 
 */
h1, h2, h3, h4, h5, h6, .h01, .h02, .h03, .h04, .h05, .h06 {
	font-family: "poppins-semibold", sans-serif;
	color: #313131;
	font-style: normal;
	text-rendering: optimizeLegibility;
	margin-bottom: 2.1rem;
}
h3, .h03, h4, .h04 {
	margin-bottom: 1.8rem;
}
h5, .h05, h6, .h06 {
	font-family: "poppins-bold";
	margin-bottom: 1.2rem;
}
h1, .h01 {
	font-size: 3.1rem;
	line-height: 1.355;
	letter-spacing: -.1rem;
}
@media only screen and (max-width:600px) {
	h1, .h01 {
		font-size: 2.6rem;
		letter-spacing: -.07rem;
	}
}
h2, .h02 {
	font-size: 2.4rem;
	line-height: 1.25;
}
h3, .h03 {
	font-size: 2rem;
	line-height: 1.5;
}
h4, .h04 {
	font-size: 1.7rem;
	line-height: 1.765;
}
h5, .h05 {
	font-size: 1.4rem;
	line-height: 1.714;
	text-transform: uppercase;
	letter-spacing: .15rem;
}
h6, .h06 {
	font-size: 1.3rem;
	line-height: 1.846;
	text-transform: uppercase;
	letter-spacing: .15rem;
}
p img {
	margin: 0;
}
p.lead {
	font-family: "lora-regular", serif;
	font-size: 2rem;
	line-height: 1.8;
	color: #888888;
}
@media only screen and (max-width:768px) {
	p.lead {
		font-size: 1.7rem;
	}
}
em, i, strong, b {
	font-size: 1.7rem;
	line-height: 3rem;
	font-style: normal;
	font-weight: normal;
}
em, i {
	font-family: "lora-italic", serif;
}
strong, b {
	font-family: "lora-bold", serif;
}
small {
	font-size: 1.2rem;
	line-height: inherit;
}
blockquote {
	margin: 3rem 0;
	padding-left: 4rem;
	position: relative;
}
blockquote:before {
	content: "\201C";
	font-size: 8rem;
	line-height: 0px;
	margin: 0;
	color: #313131;
	font-family: arial, sans-serif;
	position: absolute;
	top: 3rem;
	left: 0;
}
blockquote p {
	font-family: georgia, serif;
	font-style: italic;
	padding: 0;
	font-size: 1.9rem;
	line-height: 1.737;
}
blockquote cite {
	display: block;
	font-size: 1.3rem;
	font-style: normal;
	line-height: 1.616;
}
blockquote cite:before {
	content: "\2014 \0020";
}
blockquote cite a, blockquote cite a:visited {
	color: #888888;
	border: none;
}
abbr {
	font-family: "poppins-bold", serif;
	font-variant: small-caps;
	text-transform: lowercase;
	letter-spacing: .05rem;
	color: #888888;
}
var, kbd, samp, code, pre {
	font-family: Consolas, "Andale Mono", Courier, "Courier New", monospace;
}
pre {
	padding: 2.4rem 3rem 3rem;
	background: #F1F1F1;
}
code {
	font-size: 1.4rem;
	margin: 0 .2rem;
	padding: .3rem .6rem;
	white-space: nowrap;
	background: #F1F1F1;
	border: 1px solid #E1E1E1;
	border-radius: 3px;
}
pre > code {
	display: block;
	white-space: pre;
	line-height: 2;
	padding: 0;
	margin: 0;
}
pre.prettyprint > code {
	border: none;
}
del {
	text-decoration: line-through;
}
abbr[title], dfn[title] {
	border-bottom: 1px dotted;
	cursor: help;
}
mark {
	background: #FFF49B;
	color: #000;
}
hr {
	border: solid #d2d2d2;
	border-width: 1px 0 0;
	clear: both;
	margin: 2.4rem 0 1.5rem;
	height: 0;
}

 /*
 * ------------------------------------------------------------------- 
 */
ol {
	list-style: decimal;
}
ul {
	list-style: disc;
}
li {
	display: list-item;
}
ol, ul {
	margin-left: 1.7rem;
}
ul li {
	padding-left: .4rem;
}
ul ul, ul ol, ol ol, ol ul {
	margin: .6rem 0 .6rem 1.7rem;
}
ul.disc li {
	display: list-item;
	list-style: none;
	padding: 0 0 0 .8rem;
	position: relative;
}
ul.disc li::before {
	content: "";
	display: inline-block;
	width: 8px;
	height: 8px;
	border-radius: 50%;
	background: #ff2f00;
	position: absolute;
	left: -17px;
	top: 11px;
	vertical-align: middle;
}
dt {
	margin: 0;
	color: #ff2f00;
}
dd {
	margin: 0 0 0 2rem;
}

 /*
 * ------------------------------------------------------------------- 
 */
table {
	border-width: 0;
	width: 100%;
	max-width: 100%;
	font-family: "lora-regular", sans-serif;
}
th, td {
	padding: 1.5rem 3rem;
	text-align: left;
	border-bottom: 1px solid #E8E8E8;
}
th {
	color: #313131;
	font-family: "poppins-bold", sans-serif;
}
td {
	line-height: 1.5;
}
th:first-child, td:first-child {
	padding-left: 0;
}
th:last-child, td:last-child {
	padding-right: 0;
}
.table-responsive {
	overflow-x: auto;
	-webkit-overflow-scrolling: touch;
}

 /*
 * ------------------------------------------------------------------- 
 */
button, .button {
	margin-bottom: 1.2;
}
fieldset {
	margin-bottom: 1.5rem;
}
input,
textarea,
select,
pre,
blockquote,
figure,
table,
p,
ul,
ol,
dl,
form,
.fluid-video-wrapper,
.ss-custom-select {
	margin-bottom: 3rem;
}

 /*
 * ------------------------------------------------------------------- 
 */
img.pull-right {
	margin: .9rem 0 0 2.4rem;
}
img.pull-left {
	margin: .9rem 2.4rem 0 0;
}

 /*
 * ------------------------------------------------------------------- 
 */
.bgrid {
	padding: 0 20px;
}
@media only screen and (max-width:1024px) {
	.bgrid {
		padding: 0 18px;
	}
}
@media only screen and (max-width:768px) {
	.bgrid {
		padding: 0 15px;
	}
}
@media only screen and (max-width:600px) {
	.bgrid {
		padding: 0 10px;
	}
}
@media only screen and (max-width:400px) {
	.bgrid {
		padding: 0;
	}
}

 /*
 * ------------------------------------------------------------------- 
 */
.pace {
	-webkit-pointer-events: none;
	pointer-events: none;
	-webkit-user-select: none;
	-moz-user-select: none;
	user-select: none;
}
.pace-inactive {
	display: none;
}
.pace .pace-progress {
	background: #ff2f00;
	position: fixed;
	z-index: 900;
	top: 0;
	right: 100%;
	width: 100%;
	height: 6px;
}

 /*
 * ------------------------------------------------------------------- 
 */
#preloader {
	position: fixed;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	background: #151515;
	z-index: 800;
	height: 100%;
	width: 100%;
}
.no-js #preloader, .oldie #preloader {
	display: none;
}
#loader {
	position: absolute;
	left: 50%;
	top: 50%;
	width: 60px;
	height: 60px;
	margin: -30px 0 0 -30px;
	padding: 0;
}
#loader:before {
	content: "";
	border-top: 11px solid rgba(255, 255, 255, 0.1);
	border-right: 11px solid rgba(255, 255, 255, 0.1);
	border-bottom: 11px solid rgba(255, 255, 255, 0.1);
	border-left: 11px solid #ff2f00;
	-webkit-animation: load 1.1s infinite linear;
	animation: load 1.1s infinite linear;
	display: block;
	border-radius: 50%;
	width: 60px;
	height: 60px;
}
@-webkit-keyframes load {
	0% {
		-webkit-transform: rotate(0deg);
		transform: rotate(0deg);
	}
	100% {
		-webkit-transform: rotate(360deg);
		transform: rotate(360deg);
	}
}
@keyframes load {
	0% {
		-webkit-transform: rotate(0deg);
		transform: rotate(0deg);
	}
	100% {
		-webkit-transform: rotate(360deg);
		transform: rotate(360deg);
	}
}

 /*
 * ------------------------------------------------------------------- 
 */
fieldset {
	border: none;
}
input[type="email"],
input[type="number"],
input[type="search"],
input[type="text"],
input[type="tel"],
input[type="url"],
input[type="password"],
textarea,
select {
	display: block;
	height: 6rem;
	padding: 1.5rem 0;
	border: 0;
	outline: none;
	vertical-align: middle;
	color: #313131;
	font-family: "poppins-regular", sans-serif;
	font-size: 1.5rem;
	line-height: 3rem;
	max-width: 100%;
	background: transparent;
	border-bottom: 1px solid rgba(0, 0, 0, 0.3);
	-moz-transition: all 0.3s ease-in-out;
	-o-transition: all 0.3s ease-in-out;
	-webkit-transition: all 0.3s ease-in-out;
	-ms-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}
.ss-custom-select {
	position: relative;
	padding: 0;
}
.ss-custom-select select {
	-webkit-appearance: none;
	-moz-appearance: none;
	-ms-appearance: none;
	-o-appearance: none;
	appearance: none;
	text-indent: 0.01px;
	text-overflow: '';
	margin: 0;
	line-height: 3rem;
	vertical-align: middle;
}
.ss-custom-select select option {
	padding-left: 2rem;
	padding-right: 2rem;
}
.ss-custom-select select::-ms-expand {
	display: none;
}
.ss-custom-select::after {
	content: '\f0d7';
	font-family: 'FontAwesome';
	position: absolute;
	top: 50%;
	right: 1.5rem;
	margin-top: -10px;
	bottom: auto;
	width: 20px;
	height: 20px;
	line-height: 20px;
	font-size: 18px;
	text-align: center;
	pointer-events: none;
	color: #252525;
}

/* IE9 and below */
.oldie .ss-custom-select::after {
	display: none;
}
textarea {
	min-height: 25rem;
}
input[type="email"]:focus,
input[type="number"]:focus,
input[type="search"]:focus,
input[type="text"]:focus,
input[type="tel"]:focus,
input[type="url"]:focus,
input[type="password"]:focus,
textarea:focus,
select:focus {
	color: #ff2f00;
	border-bottom: 1px solid #ff2f00;
}
label, legend {
	font-family: "poppins-bold", sans-serif;
	font-size: 1.4rem;
	margin-bottom: .6rem;
	color: #3b3b3b;
	display: block;
}
input[type="checkbox"], input[type="radio"] {
	display: inline;
}
label > .label-text {
	display: inline-block;
	margin-left: 1rem;
	font-family: "poppins-regular", sans-serif;
	line-height: inherit;
}
label > input[type="checkbox"], label > input[type="radio"] {
	margin: 0;
	position: relative;
	top: .15rem;
}

/**
 * Style Placeholder Text  
 * -
 */
::-webkit-input-placeholder {
	color: #a1a1a1;
}
:-moz-placeholder {
	color: #a1a1a1;  /* Firefox 18- */
}
::-moz-placeholder {
	color: #a1a1a1;  /* Firefox 19+ */
}
:-ms-input-placeholder {
	color: #a1a1a1;
}
.placeholder {
	color: #a1a1a1 !important;
}

 /*
 * ------------------------------------------------------------------- 
 */
.button,
a.button,
button,
input[type="submit"],
input[type="reset"],
input[type="button"] {
	display: inline-block;
	font-family: "poppins-bold", sans-serif;
	font-size: 1.4rem;
	text-transform: uppercase;
	letter-spacing: .3rem;
	height: 5.4rem;
	line-height: 5.4rem;
	padding: 0 3rem;
	margin: 0 .3rem 1.2rem 0;
	background: #d8d8d8;
	color: #313131;
	text-decoration: none;
	cursor: pointer;
	text-align: center;
	white-space: nowrap;
	border: none;
	-moz-transition: all 0.3s ease-in-out;
	-o-transition: all 0.3s ease-in-out;
	-webkit-transition: all 0.3s ease-in-out;
	-ms-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}
.button:hover,
a.button:hover,
button:hover,
input[type="submit"]:hover,
input[type="reset"]:hover,
input[type="button"]:hover,
.button:focus,
button:focus,
input[type="submit"]:focus,
input[type="reset"]:focus,
input[type="button"]:focus {
	background: #bebebe;
	color: #000000;
	outline: 0;
}
.button.button-primary,
a.button.button-primary,
button.button-primary,
input[type="submit"].button-primary,
input[type="reset"].button-primary,
input[type="button"].button-primary {
	background: #313131;
	color: #FFFFFF;
}
.button.button-primary:hover,
a.button.button-primary:hover,
button.button-primary:hover,
input[type="submit"].button-primary:hover,
input[type="reset"].button-primary:hover,
input[type="button"].button-primary:hover,
.button.button-primary:focus,
button.button-primary:focus,
input[type="submit"].button-primary:focus,
input[type="reset"].button-primary:focus,
input[type="button"].button-primary:focus {
	background: #1f1f1f;
}
button.full-width, .button.full-width {
	width: 100%;
	margin-right: 0;
}
button.medium, .button.medium {
	height: 5.7rem !important;
	line-height: 5.7rem !important;
	padding: 0 1.8rem !important;
}
button.large, .button.large {
	height: 6rem !important;
	line-height: 6rem !important;
	padding: 0rem 3rem !important;
}
button.stroke, .button.stroke {
	background: transparent !important;
	border: 3px solid #313131;
	line-height: 4.8rem;
}
button.stroke.medium, .button.stroke.medium {
	line-height: 5.1rem !important;
}
button.stroke.large, .button.stroke.large {
	line-height: 5.4rem !important;
}
button.stroke:hover, .button.stroke:hover {
	border: 3px solid #ff2f00;
	color: #ff2f00;
}
button::-moz-focus-inner, input::-moz-focus-inner {
	border: 0;
	padding: 0;
}


 /*
 * ------------------------------------------------------------------- 
 */
.alert-box {
	padding: 2.1rem 4rem 2.1rem 3rem;
	position: relative;
	margin-bottom: 3rem;
	border-radius: 3px;
	font-family: "poppins-regular", sans-serif;
	font-size: 1.5rem;
}
.alert-box .close {
	position: absolute;
	right: 1.8rem;
	top: 1.8rem;
	cursor: pointer;
}
.ss-error {
	background-color: #ffd1d2;
	color: #e65153;
}
.ss-success {
	background-color: #c8e675;
	color: #758c36;
}
.ss-info {
	background-color: #d7ecfb;
	color: #4a95cc;
}
.ss-notice {
	background-color: #fff099;
	color: #bba31b;
}

 /*
 * ------------------------------------------------------------------- 
 */
.drop-cap:first-letter {
	float: left;
	margin: 0;
	padding: 1.5rem .6rem 0 0;
	font-size: 8.4rem;
	font-family: "poppins-bold", sans-serif;
	line-height: 6rem;
	text-indent: 0;
	background: transparent;
	color: #313131;
}

/**
 * line definition style
 */
.lining dt, .lining dd {
	display: inline;
	margin: 0;
}
.lining dt + dt:before, .lining dd + dt:before {
	content: "\A";
	white-space: pre;
}
.lining dd + dd:before {
	content: ", ";
}
.lining dd + dd:before {
	content: ", ";
}
.lining dd:before {
	content: ": ";
	margin-left: -0.2em;
}

/**
 * dictionary definition style
 */
.dictionary-style dt {
	display: inline;
	counter-reset: definitions;
}
.dictionary-style dt + dt:before {
	content: ", ";
	margin-left: -0.2em;
}
.dictionary-style dd {
	display: block;
	counter-increment: definitions;
}
.dictionary-style dd:before {
	content: counter(definitions, decimal) ". ";
}

 /*
 * ------------------------------------------------------------------- 
 */
.pull-quote {
	position: relative;
	padding: 2.1rem 3rem 2.1rem 0px;
}
.pull-quote:before, .pull-quote:after {
	height: 1em;
	position: absolute;
	font-size: 8rem;
	font-family: Arial, Sans-Serif;
	color: #333;
}
.pull-quote:before {
	content: "\201C";
	top: 33px;
	left: 0;
}
.pull-quote:after {
	content: '\201D';
	bottom: -33px;
	right: 0;
}
.pull-quote blockquote {
	margin: 0;
}
.pull-quote blockquote:before {
	content: none;
}

 /*
 * ------------------------------------------------------------------- 
 */
.stats-tabs {
	padding: 0;
	margin: 3rem 0;
}
.stats-tabs li {
	display: inline-block;
	margin: 0 1.5rem 3rem 0;
	padding: 0 1.5rem 0 0;
	border-right: 1px solid #ccc;
}
.stats-tabs li:last-child {
	margin: 0;
	padding: 0;
	border: none;
}
.stats-tabs li a {
	display: inline-block;
	font-size: 2.5rem;
	font-family: "poppins-bold", sans-serif;
	border: none;
	color: #252525;
}
.stats-tabs li a:hover {
	color: #ff2f00;
}
.stats-tabs li a em {
	display: block;
	margin: .6rem 0 0 0;
	font-size: 1.4rem;
	font-family: "poppins-regular", sans-serif;
	color: #888888;
}

 /*
 * ------------------------------------------------------------------- 
 */
.skill-bars {
	list-style: none;
	margin: 6rem 0 3rem;
}
.skill-bars li {
	height: .6rem;
	background: #a1a1a1;
	width: 100%;
	margin-bottom: 6rem;
	padding: 0;
	position: relative;
}
.skill-bars li strong {
	position: absolute;
	left: 0;
	top: -3rem;
	font-family: "poppins-bold", sans-serif;
	color: #313131;
	text-transform: uppercase;
	letter-spacing: .2rem;
	font-size: 1.5rem;
	line-height: 2.4rem;
}
.skill-bars li .progress {
	background: #313131;
	position: relative;
	height: 100%;
}
.skill-bars li .progress span {
	position: absolute;
	right: 0;
	top: -3.6rem;
	display: block;
	font-family: "poppins-regular", sans-serif;
	color: white;
	font-size: 1.1rem;
	line-height: 1;
	background: #313131;
	padding: .6rem .6rem;
	border-radius: 3px;
}
.skill-bars li .progress span::after {
	position: absolute;
	left: 50%;
	bottom: -5px;
	margin-left: -5px;
	border-right: 5px solid transparent;
	border-left: 5px solid transparent;
	border-top: 5px solid #313131;
	content: "";
}

.skill-bars li .percent5   { width: 5%; }
.skill-bars li .percent10  { width: 10%; }
.skill-bars li .percent15  { width: 15%; }
.skill-bars li .percent20  { width: 20%; }
.skill-bars li .percent25  { width: 25%; }
.skill-bars li .percent30  { width: 30%; }
.skill-bars li .percent35  { width: 35%; }
.skill-bars li .percent40  { width: 40%; }
.skill-bars li .percent45  { width: 45%; }
.skill-bars li .percent50  { width: 50%; }
.skill-bars li .percent55  { width: 55%; }
.skill-bars li .percent60  { width: 60%; }
.skill-bars li .percent65  { width: 65%; }
.skill-bars li .percent70  { width: 70%; }
.skill-bars li .percent75  { width: 75%; }
.skill-bars li .percent80  { width: 80%; }
.skill-bars li .percent85  { width: 85%; }
.skill-bars li .percent90  { width: 90%; }
.skill-bars li .percent95  { width: 95%; }
.skill-bars li .percent100 { width: 100%; }


 /*
 * ------------------------------------------------------------------- 
 */
.grey-section {
	background: #ebebeb;
}
.grey-section p.lead {
	color: #7d7d7d;
}
.section-intro {
	max-width: 700px;
	margin-left: auto;
	margin-right: auto;
	text-align: center;
	margin-bottom: 3.6rem;
	position: relative;
}
.section-intro h1 {
	font-family: "poppins-semibold", serif;
	font-size: 3.6rem;
	color: #313131;
	line-height: 1.25;
	margin-bottom: 1.2rem;
}
.section-intro h5 {
	color: #ff2f00;
	font-size: 1.6rem;
	line-height: 1.875;
	margin-bottom: 0.3rem;
	letter-spacing: .4rem;
}

 /*
 * ------------------------------------------------------------------- 
 */
@media only screen and (max-width:768px) {
	.section-intro {
		max-width: 650px;
	}
	.section-intro h1 {
		font-size: 3rem;
	}
}
@media only screen and (max-width:600px) {
	.section-intro h1 {
		font-size: 2.6rem;
	}
	.section-intro h5 {
		font-size: 1.5rem;
		letter-spacing: .3rem;
	}
}
@media only screen and (max-width:400px) {
	.section-intro h1 {
		font-size: 2.4rem;
	}
}


 /*
 * ------------------------------------------------------------------- 
 */
header {
	position: fixed;
	width: 100%;
	min-height: 66px;
	z-index: 600;
}
header .row {
	position: relative;
	min-height: 66px;
}
header .top-bar {
	display: block;
	/*background: #000000;*/
	min-width: 220px;
	min-height: 66px;
	position: absolute;
	left: 90px;
	top: 0;
}
header .logo {
	float: left;
	margin-left: 20px;
	margin-right: 50px;
	margin-top: 25px;
	position: relative;
}
header .logo a {
	display: block;
	margin: 0;
	padding: 0;
	border: none;
	font: 0/0 a;
	text-shadow: none;
	color: transparent;
	width: 92px;
	height: 15px;
}
 /*
 * ------------------------------------------------------------------- 
 */
.menu-toggle {
	float: left;
	width: 40px;
	height: 40px;
	margin-left: 20px;
	margin-top: 13px;
	display: block;
	position: relative;
}
.menu-toggle span {
	display: block;
	background-color: #ff2f00;
	width: 24px;
	height: 3px;
	margin-top: -1.5px;
	font: 0/0 a;
	text-shadow: none;
	color: transparent;
	position: absolute;
	right: 8px;
	top: 50%;
	bottom: auto;
	left: auto;
	-moz-transition: background 0.2s ease-in-out;
	-o-transition: background 0.2s ease-in-out;
	-webkit-transition: background 0.2s ease-in-out;
	-ms-transition: background 0.2s ease-in-out;
	transition: background 0.2s ease-in-out;
}
.menu-toggle span::before, .menu-toggle span::after {
	content: '';
	width: 100%;
	height: 100%;
	background-color: inherit;
	position: absolute;
	left: 0;
	-moz-transition-duration: 0.2s, 0.2s;
	-o-transition-duration: 0.2s, 0.2s;
	-webkit-transition-duration: 0.2s, 0.2s;
	-ms-transition-duration: 0.2s, 0.2s;
	transition-duration: 0.2s, 0.2s;
	-moz-transition-delay: 0.2s, 0s;
	-o-transition-delay: 0.2s, 0s;
	-webkit-transition-delay: 0.2s, 0s;
	-ms-transition-delay: 0.2s, 0s;
	transition-delay: 0.2s, 0s;
}
.menu-toggle span::before {
	top: -8px;
	-moz-transition-property: top, transform;
	-o-transition-property: top, transform;
	-webkit-transition-property: top, transform;
	-ms-transition-property: top, transform;
	transition-property: top, transform;
}
.menu-toggle span::after {
	bottom: -8px;
	-moz-transition-property: bottom, transform;
	-o-transition-property: bottom, transform;
	-webkit-transition-property: bottom, transform;
	-ms-transition-property: bottom, transform;
	transition-property: bottom, transform;
}

/* is clicked */
.menu-toggle.is-clicked span {
	background-color: rgba(255, 0, 119, 0);
}
.menu-toggle.is-clicked span::before, .menu-toggle.is-clicked span::after {
	background-color: #ff2f00;
	-moz-transition-delay: 0s, 0.2s;
	-o-transition-delay: 0s, 0.2s;
	-webkit-transition-delay: 0s, 0.2s;
	-ms-transition-delay: 0s, 0.2s;
	transition-delay: 0s, 0.2s;
}
.menu-toggle.is-clicked span::before {
	top: 0;
	-webkit-transform: rotate(45deg);
	-ms-transform: rotate(45deg);
	transform: rotate(45deg);
}
.menu-toggle.is-clicked span::after {
	bottom: 0;
	-webkit-transform: rotate(-45deg);
	-ms-transform: rotate(-45deg);
	transform: rotate(-45deg);
}

/* navigation panel */
#main-nav-wrap {
	display: block;
	width: 100%;
	font-family: "poppins-medium", sans-serif;
	font-size: 1.5rem;
	position: absolute;
	top: 100%;
	left: 0;
}

/* dropdown nav */
.main-navigation {
	background: #000000;
	padding: 24px 30px 42px;
	margin: 0;
	width: 100%;
	height: auto;
	clear: both;
	display: none;
}
.main-navigation > li {
	display: block;
	height: auto;
	text-align: left;
	padding: 0;
}
.main-navigation li a {
	display: block;
	color: #FFFFFF;
	width: auto;
	padding: 15px 0;
	line-height: 16px;
	border: none;
}
.main-navigation li a:hover {
	color: #ff2f00;
	padding-left: 1rem;
}
.main-navigation li.current > a {
	background: none;
	color: #ff2f00;
}

 /*
 * ------------------------------------------------------------------- 
 */
@media only screen and (max-width:1024px) {
	header .top-bar {
		left: 60px;
	}
}
@media only screen and (max-width:768px) {
	header .top-bar {
		left: 50px;
	}
}
@media only screen and (max-width:600px) {
	header .top-bar {
		left: 35px;
	}
}
@media only screen and (max-width:400px) {
	header .top-bar {
		left: 25px;
	}
}


 /*
 * ------------------------------------------------------------------- 
 */
#intro {
/*	background: #151515 url(../images/jpg) no-repeat center bottom;*/
	-webkit-background-size: cover;
	-moz-background-size: cover;
	background-size: cover;
	background-attachment: fixed;
	width: 100%;
	height: 100%;
	min-height: 720px;
	display: table;
	position: relative;
	text-align: center;
}
.intro-overlay {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background: #111111;
	opacity: .85;
}

.intro-content {
	display: table-cell;
	vertical-align: middle;
	text-align: center;
	-webkit-transform: translateY(-2.1rem);
	-ms-transform: translateY(-2.1rem);
	transform: translateY(-2.1rem);
}
.intro-content h1 {
	color: #FFFFFF;
	font-family: "poppins-medium", sans-serif;
	font-size: 8.4rem;
	line-height: 1.071;
	max-width: 900px;
	margin-top: 0;
	margin-bottom: .6rem;
	margin-left: auto;
	margin-right: auto;
	text-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
}
.intro-content h5 {
	color: #ff2f00;
	font-family: "poppins-bold", sans-serif;
	font-size: 2.3rem;
	line-height: 1.565;
	margin-bottom: 0;
	text-transform: uppercase;
	letter-spacing: .3rem;
	text-shadow: 0 0 6px rgba(0, 0, 0, 0.2);
}
.intro-content .intro-position {
	font-family: "lora-regular", serif;
	font-size: 1.7rem;
	line-height: 2.4rem;
	text-transform: uppercase;
	letter-spacing: .2rem;
	color: #FFFFFF;
	text-shadow: 0 0 6px rgba(0, 0, 0, 0.2);
}
.intro-content .intro-position span {
	display: inline-block;
}
.intro-content .intro-position span::after {
	content: "|";
	text-align: center;
	display: inline-block;
	padding: 0 8px 0 14px;
	color: rgba(255, 255, 255, 0.3);
}
.intro-content .intro-position span:first-child::before {
	content: "|";
	text-align: center;
	display: inline-block;
	padding: 0 14px 0 8px;
	color: rgba(255, 255, 255, 0.3);
}
.intro-content .button {
	color: #FFFFFF !important;
	border-color: rgba(255, 255, 255, 0.3);
	height: 6rem !important;
	line-height: 5.4rem !important;
	padding: 0 3.5rem 0 3rem !important;
	margin-top: .6rem;
	font-size: 1.3rem;
	text-transform: uppercase;
	letter-spacing: .25rem;
}
.intro-content .button:hover, .intro-content .button:focus {
	border-color: #ff2f00;
}
.intro-content .button::after {
	display: inline-block;
	content: "<";
	font-family: fontAwesome;
	font-size: 1.6rem;
	line-height: inherit;
	text-align: center;
	position: relative;
	left: 1.2rem;
}

.intro-social {
	display: block;
	position: absolute;
	width: 100%;
	left: 0;
	bottom: 7.2rem;
	font-size: 3.3rem;
	margin: 0;
	padding: 0;
}
.intro-social li {
	display: inline-block;
	margin: 0 20px;
	padding: 0;
}
.intro-social li a, .intro-social li a:visited {
	color: #FFFFFF;
}
.intro-social li a:hover, .intro-social li a:focus {
	color: #ff2f00;
}

 /*
 * ------------------------------------------------------------------- 
 */
@media only screen and (max-width:1024px) {
	.intro-content h1 {
		font-size: 7.6rem;
	}
	.intro-social {
		font-size: 3rem;
	}
	.intro-social li {
		margin: 0 15px;
	}
}
@media only screen and (max-width:768px) {
	#intro {
		min-height: 660px;
	}
	.intro-content h1 {
		font-size: 5.2rem;
	}
	.intro-content h5 {
		font-size: 1.8rem;
	}
	.intro-content .intro-position {
		font-size: 1.3rem;
	}
	.intro-social {
		font-size: 2.5rem;
	}
	.intro-social li {
		margin: 0 10px;
	}
}
@media only screen and (max-width:600px) {
	#intro {
		min-height: 600px;
	}
	.intro-content h1 {
		font-size: 4.6rem;
		margin-bottom: .6rem;
	}
	.intro-content h5 {
		font-size: 1.5rem;
		margin-bottom: .3rem;
		letter-spacing: .2rem;
	}
	.intro-content .intro-position {
		font-size: 1.2rem;
	}
	.intro-content .intro-position span {
		padding: 0 .6rem;
	}
	.intro-content .intro-position span::before, .intro-content .intro-position span::after {
		display: none !important;
	}
	.intro-social {
		font-size: 2.4rem;
	}
}


 /*
 * ------------------------------------------------------------------- 
 */
#about {
	background: #FFFFFF;
	padding-top: 12rem;
	padding-bottom: 15rem;
}
#about .section-intro {
	margin-bottom: 3rem;
}

.intro-info {
	margin-top: 4.2rem;
	margin-right: -30px;
	margin-left: -30px;
}
.intro-info img {
	height: 9rem;
	width: 9rem;
	border-radius: 50%;
	margin: .9rem 0 0 0;
	float: left;
}
.intro-info .lead {
	text-align: left;
	padding-left: 13rem;
}

.about-content {
	position: relative;
	text-align: left;
	max-width: 850px;
	margin-bottom: 3.6rem;
}
.about-content h3 {
	font-family: "poppins-bold", sans-serif;
	font-size: 1.8rem;
	text-transform: uppercase;
	letter-spacing: .25rem;
}
.about-content .info-list {
	list-style: none;
	margin-left: 0;
}
.about-content .info-list li {
	padding: 0 0 1.5rem 0;
	margin-bottom: .6rem;
}
.about-content .info-list li strong {
	font-family: "poppins-bold", sans-serif;
	color: #313131;
	text-transform: uppercase;
	letter-spacing: .2rem;
	font-size: 1.5rem;
	line-height: 3rem;
}
.about-content .info-list li span {
	display: block;
	font-family: "poppins-regular", sans-serif;
	color: #888888;
	font-size: 1.5rem;
	line-height: 1;
}
.about-content .skill-bars {
	margin-top: 6rem;
}

.button-section {
	text-align: center;
}
.button-section .button {
	width: 250px;
}
.button-section [class*="col-"] .button:first-child {
	margin-right: 4rem;
}

 /*
 * ------------------------------------------------------------------- 
 */
@media only screen and (max-width:1024px) {
	.intro-info {
		margin-right: 0;
		margin-left: 0;
	}
}
@media only screen and (max-width:768px) {
	.intro-info img {
		height: 7.8rem;
		width: 7.8rem;
	}
	.intro-info .lead {
		padding-left: 11rem;
	}
	.about-content h3 {
		text-align: center;
	}
	.about-content .info-list, .about-content .skill-bars {
		margin-bottom: 4.2rem;
	}
	.button-section .button {
		width: 100%;
		margin-bottom: 3rem;
	}
	.button-section [class*="col-"] .button:first-child {
		margin-right: 0;
	}
}
@media only screen and (max-width:600px) {
	.intro-info {
		text-align: center;
		margin-top: 3rem;
	}
	.intro-info img {
		height: 6.6rem;
		width: 6.6rem;
		float: none;
		display: inline-block;
	}
	.intro-info .lead {
		padding-left: 0;
		text-align: center;
	}
}

 /*
 * ------------------------------------------------------------------- 
 */
#resume {
	padding-top: 12rem;
	padding-bottom: 12rem;
}

#resume .resume-header {
	text-align: center;
}
#resume .resume-header h2 {
	color: #ff2f00;
}

#resume .resume-timeline {
	max-width: 980px;
}
#resume .timeline-wrap {
	position: relative;
	margin-top: 1.5rem;
	margin-bottom: 6rem;
}
#resume .timeline-wrap::before {
	content: "";
	display: block;
	width: 1px;
	height: 100%;
	background: rgba(0, 0, 0, 0.1);
	position: absolute;
	left: 35%;
	top: 0;
}
#resume .timeline-block {
	position: relative;
	padding-top: 1.5rem;
}
#resume .timeline-ico {
	height: 4.8rem;
	width: 4.8rem;
	line-height: 4.8rem;
	background: #313131;
	border-radius: 50%;
	text-align: center;
	color: #FFFFFF;
	position: absolute;
	left: 35%;
	top: .9rem;
	margin-left: -2.4rem;
}
#resume .timeline-ico i {
	position: relative;
	left: .05rem;
	top: .2rem;
}

#resume .timeline-header {
	float: left;
	width: 35%;
	padding-right: 90px;
	text-align: right;
}
#resume .timeline-header h3 {
	margin-bottom: 0;
}
#resume .timeline-header p {
	font-family: "poppins-regular", sans-serif;
	font-size: 1.6rem;
	color: #888888;
}
#resume .timeline-content {
	margin-left: 35%;
	padding-left: 60px;
}
#resume .timeline-content h4 {
	position: relative;
	padding-bottom: 1.8rem;
}
#resume .timeline-content h4::after {
	content: "";
	display: block;
	height: 3px;
	width: 50px;
	background: rgba(0, 0, 0, 0.2);
	position: absolute;
	left: 0;
	bottom: 0;
}

 /*
 * ------------------------------------------------------------------- 
 */
@media only screen and (max-width:1024px) {
	#resume .timeline-header {
		padding-right: 50px;
	}
	#resume .timeline-header h3 {
		font-size: 1.8rem;
	}
	#resume .timeline-header p {
		font-size: 1.4rem;
	}
	#resume .timeline-content {
		padding-left: 50px;
	}
}
@media only screen and (max-width:768px) {
	#resume .timeline-wrap::before {
		left: 2.4rem;
	}
	#resume .timeline-ico {
		left: 2.4rem;
	}
	#resume .timeline-header {
		float: none;
		width: auto;
		padding-right: 15px;
		text-align: left;
	}
	#resume .timeline-header h3 {
		font-size: 2rem;
	}
	#resume .timeline-header p {
		font-size: 1.5rem;
		margin-bottom: 1.5rem;
	}
	#resume .timeline-content {
		margin: 0;
	}
	#resume .timeline-content h4 {
		padding-bottom: 0;
		padding-top: 2.1rem;
		margin-bottom: .6rem;
		font-size: 1.7rem;
	}
	#resume .timeline-content h4::after {
		bottom: auto;
		top: 0;
	}
	#resume .timeline-header, #resume .timeline-content {
		padding-left: 7rem;
	}
}
@media only screen and (max-width:480px) {
	#resume .resume-header h2 {
		font-size: 2.2rem;
	}
	#resume .timeline-wrap::before {
		left: 1.8rem;
	}
	#resume .timeline-ico {
		height: 3.6rem;
		width: 3.6rem;
		line-height: 3.6rem;
		left: 1.8rem;
		margin-left: -1.8rem;
		font-size: 1.5rem;
	}
	#resume .timeline-header, #resume .timeline-content {
		padding-left: 5.5rem;
	}
}


 /*
 * ------------------------------------------------------------------- 
 */
#portfolio {
	background: #FFFFFF;
	padding-top: 12rem;
	padding-bottom: 12rem;
}
#portfolio .folio-item {
	padding: 0;
	position: relative;
	overflow: hidden;
}
#portfolio .folio-item img {
	vertical-align: middle;
	-moz-transition: all 0.5s ease-in-out;
	-o-transition: all 0.5s ease-in-out;
	-webkit-transition: all 0.5s ease-in-out;
	-ms-transition: all 0.5s ease-in-out;
	transition: all 0.5s ease-in-out;
}

#portfolio .overlay {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background: transparent;
	-moz-transition: all 0.5s ease-in-out;
	-o-transition: all 0.5s ease-in-out;
	-webkit-transition: all 0.5s ease-in-out;
	-ms-transition: all 0.5s ease-in-out;
	transition: all 0.5s ease-in-out;
}

#portfolio .folio-item-table {
	display: table;
	width: 100%;
	height: 100%;
}
#portfolio .folio-item-cell {
	display: table-cell;
	vertical-align: middle;
	text-align: center;
	-moz-transition: all 0.5s ease-in-out;
	-o-transition: all 0.5s ease-in-out;
	-webkit-transition: all 0.5s ease-in-out;
	-ms-transition: all 0.5s ease-in-out;
	transition: all 0.5s ease-in-out;
	position: relative;
	left: -100%;
}

#portfolio .folio-title {
	color: #FFFFFF;
	font-size: 3.3rem;
	padding: 0 3rem;
	margin-bottom: 0;
}
#portfolio .folio-types {
	margin: 0;
	padding: 0;
	text-transform: uppercase;
	font-family: "poppins-regular", sans-serif;
	font-size: 1.2rem;
	letter-spacing: .1rem;
	color: rgba(255, 255, 255, 0.6);
}
#portfolio .folio-item:hover .overlay {
	background: rgba(0, 0, 0, 0.8);
}
#portfolio .folio-item:hover .folio-item-cell {
	left: 0;
}
#portfolio .folio-item:hover img {
	-webkit-transform: scale(1.05);
	-ms-transform: scale(1.05);
	transform: scale(1.05);
}

 /*
 * ------------------------------------------------------------------- 
 */
@media only screen and (max-width:1024px) {
	#portfolio .folio-title {
		font-size: 3.1rem;
	}
}
@media only screen and (max-width:768px) {
	#portfolio .folio-title {
		font-size: 2.5rem;
	}
}
@media only screen and (max-width:400px) {
	#portfolio .folio-title {
		font-size: 2.2rem;
	}
}

 /*
 * ------------------------------------------------------------------- 
 */
.popup-modal {
	max-width: 550px;
	background: #FFFFFF;
	position: relative;
	margin: 0 auto;
}
.popup-modal .media {
	position: relative;
}
.popup-modal img {
	vertical-align: bottom;
}
.popup-modal .description-box {
	padding: 1.8rem 3.6rem 3rem;
}
.popup-modal .description-box h4 {
	font-family: "poppins-bold", sans-serif;
	font-size: 1.5rem;
	line-height: 2.4rem;
	margin-bottom: .6rem;
}
.popup-modal .description-box p {
	font-family: "poppins-regular", sans-serif;
	font-size: 1.4rem;
	line-height: 2.4rem;
	margin-bottom: 12px;
}
.popup-modal .categories {
	font-family: "poppins-bold", sans-serif;
	font-size: 1.1rem;
	line-height: 1.8rem;
	text-transform: uppercase;
	letter-spacing: .1rem;
	display: block;
	text-align: left;
	color: rgba(0, 0, 0, 0.5);
}
.popup-modal .link-box {
	width: 100%;
	overflow: hidden;
	background: #000000;
}
.popup-modal .link-box a {
	font-family: "poppins-bold", sans-serif;
	font-size: 1.2rem;
	line-height: 6rem;
	color: #FFFFFF;
	text-transform: uppercase;
	letter-spacing: 3px;
	cursor: pointer;
	display: block;
	text-align: center;
	float: left;
	width: 50%;
	-moz-transition: all 0.3s ease-in-out;
	-o-transition: all 0.3s ease-in-out;
	-webkit-transition: all 0.3s ease-in-out;
	-ms-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}
.popup-modal .link-box a:first-child {
	border-right: 1px solid rgba(200, 200, 200, 0.1);
}
.popup-modal .link-box a:hover {
	background: #ff2f00;
	border: none;
}
@media only screen and (max-width:600px) {
	.popup-modal {
		width: auto;
		margin: 0 20px;
	}
}

 /*
 * ------------------------------------------------------------------- 
 */
.mfp-fade.mfp-bg {
	opacity: 0;
	-moz-transition: all 0.3s ease-in-out;
	-o-transition: all 0.3s ease-in-out;
	-webkit-transition: all 0.3s ease-in-out;
	-ms-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}

/* overlay animate in */
.mfp-fade.mfp-bg.mfp-ready {
	opacity: .9;
}

/* overlay animate out */
.mfp-fade.mfp-bg.mfp-removing {
	opacity: 0;
}

/* content at start */
.mfp-fade.mfp-wrap .mfp-content {
	opacity: 0;
	-webkit-transform: translateY(-100%);
	-ms-transform: translateY(-100%);
	transform: translateY(-100%);
	-moz-transition: all 0.3s ease-in-out;
	-o-transition: all 0.3s ease-in-out;
	-webkit-transition: all 0.3s ease-in-out;
	-ms-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}

/* content animate in */
.mfp-fade.mfp-wrap.mfp-ready .mfp-content {
	opacity: 1;
	-webkit-transform: translateY(0);
	-ms-transform: translateY(0);
	transform: translateY(0);
}

/* content animate out */
.mfp-fade.mfp-wrap.mfp-removing .mfp-content {
	opacity: 0;
	-webkit-transform: translateY(-100%);
	-ms-transform: translateY(-100%);
	transform: translateY(-100%);
}

 /*
 * ------------------------------------------------------------------- 
 */
#cta {
	padding-top: 10.2rem;
	padding-bottom: 9rem;
	text-align: center;
}
#cta p.lead {
	color: #6e6e6e;
}
.cta-content {
	max-width: 640px;
}
.cta-thumb {
	display: inline-block;
	margin-bottom: 1.2rem;
}
.cta-thumb img {
	height: 7.8rem;
	width: 7.8rem;
	border-radius: 50%;
}

 /*
 * ------------------------------------------------------------------- 
 */
.section-ads h2 {
	position: relative;
	padding-bottom: 2.1rem;
}
.section-ads h2::after {
	content: "";
	display: block;
	height: 3px;
	width: 80px;
	background: rgba(0, 0, 0, 0.2);
	position: absolute;
	left: 50%;
	bottom: 0;
	margin-left: -40px;
}
.section-ads h2 a, .section-ads h2 a:visited {
	color: #313131;
}
.section-ads span {
	color: #3F0D39;
}

 /*
 * ------------------------------------------------------------------- 
 */
@media only screen and (max-width:650px) {
	.cta-content {
		max-width: 650px;
	}
	.cta-content h2 {
		font-size: 2.4rem;
	}
}


 /*
 * ------------------------------------------------------------------- 
 */
#services {
	background: #313131 url(../images/bg.jpg) no-repeat center;
	-webkit-background-size: cover;
	-moz-background-size: cover;
	background-size: cover;
	padding-top: 12rem;
	padding-bottom: 12rem;
	color: white;
	position: relative;
}
#services .overlay {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background: #151515;
	opacity: .9;
}

#services .section-intro {
	margin-bottom: 1.8rem;
}

#services .section-intro h1 {
	color: white;
}
#services .section-intro h5 {
	color: #ff2f00;
}
#services .section-intro p {
	color: rgba(255, 255, 255, 0.7);
}
.services-content {
	max-width: 1200px;
}
.services-list {
	margin-top: 1.2rem;
	text-align: center;
}
.services-list .service {
	margin-bottom: 1.2rem;
	padding: 0 30px;
}
.services-list .icon {
	display: inline-block;
	margin-bottom: 2.1rem;
}
.services-list .icon i {
	font-size: 5.4rem;
	color: #ff2f00;
}
.services-list h3 {
	color: #FFFFFF;
}
.services-list .desc {
	color: rgba(255, 255, 255, 0.6);
}

/* pagination */
.owl-pagination {
	text-align: center;
	width: 100%;
	margin: .6rem 0 0;
}
.owl-theme .owl-controls .owl-page {
	display: inline-block;
}
.owl-theme .owl-controls .owl-page span {
	display: block;
	width: 1.2rem;
	height: 1.2rem;
	margin: 1.2rem .8rem 0 .8rem;
	border-radius: 50%;
	display: inline-block;
	background: #FFFFFF;
}
.owl-theme .owl-controls .owl-page.active span {
	background: #ff2f00;
}


 /*
 * ------------------------------------------------------------------- 
 */
#stats {
	background: #990047;
	padding-top: 7.2rem;
	padding-bottom: 6rem;
	text-align: center;
}
#stats .row {
	max-width: 1440px;
}
#stats .stat {
	border-left: 1px solid rgba(255, 255, 255, 0.12);
	min-height: 17.4rem;
}
#stats .stat:first-child {
	border: none;
}
#stats .icon-part i {
	font-size: 4.8rem;
	color: #000000;
}
#stats .stat-count {
	color: #FFFFFF;
	font-size: 3.6rem;
	margin-top: 1.2rem;
	margin-bottom: 0;
	font-family: "poppins-medium", sans-serif;
	color: white;
}
#stats .stat-title {
	color: rgba(255, 255, 255, 0.5);
}

 /*
 * ------------------------------------------------------------------- 
 */
@media only screen and (max-width:1024px) {
	#stats .stat:nth-child(n) {
		border-left: 1px solid rgba(255, 255, 255, 0.12);
		padding-bottom: 1.5rem;
	}
	#stats .stat:nth-child(3n+1) {
		border: none;
	}
}
@media only screen and (max-width:768px) {
	#stats .stat:nth-child(n) {
		border-left: 1px solid rgba(255, 255, 255, 0.12);
	}
	#stats .stat:nth-child(2n+1) {
		border: none;
	}
}
@media only screen and (max-width:600px) {
	#stats .stat:nth-child(n) {
		border: none;
	}
}


 /*
 * ------------------------------------------------------------------- 
 */
#contact {
	background: #151515;
	padding-top: 12rem;
	padding-bottom: 7.2rem;
}
#contact .section-intro h1 {
	color: white;
}
#contact .section-intro h5 {
	color: #ff2f00;
}
#contact .section-intro p {
	color: rgba(255, 255, 255, 0.7);
}

/* contact form */
.contact-form {
	max-width: 740px;
}

.contact-form ::-webkit-input-placeholder {
	color: rgba(255, 255, 255, 0.3);
}
.contact-form :-moz-placeholder {
	color: rgba(255, 255, 255, 0.3);  /* Firefox 18- */
}
.contact-form ::-moz-placeholder {
	color: rgba(255, 255, 255, 0.3);  /* Firefox 19+ */
}
.contact-form :-ms-input-placeholder {
	color: rgba(255, 255, 255, 0.3);
}
.contact-form .placeholder {
	color: rgba(255, 255, 255, 0.3) !important;
}

#contact form {
	margin-top: 0;
	margin-bottom: 3rem;
}
#contact form .form-field {
	position: relative;
}
#contact form .form-field:before, #contact form .form-field:after {
	content: "";
	display: table;
}
#contact form .form-field:after {
	clear: both;
}
#contact form .form-field label {
	font-family: "poppins-bold", sans-serif;
	font-size: 1.1rem;
	line-height: 2.4rem;
	position: absolute;
	bottom: -1.2rem;
	right: .6rem;
	text-transform: uppercase;
	letter-spacing: .1rem;
	padding: 0 2rem;
	margin: 0;
	color: #FFFFFF;
	background: #ff2f00;
}
#contact form .form-field label::after {
	position: absolute;
	left: -5px;
	top: 50%;
	margin-top: -6px;
	border-top: 5px solid transparent;
	border-bottom: 5px solid transparent;
	border-right: 5px solid #ff2f00;
	content: "";
}
#contact input[type="text"],
#contact input[type="password"],
#contact input[type="email"],
#contact textarea {
	width: 100%;
	color: rgba(255, 255, 255, 0.7);
	margin-bottom: 0;
	border: none;
	border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}
#contact input[type="text"],
#contact input[type="password"],
#contact input[type="email"] {
	height: 6.6rem;
	padding: 1.8rem 2rem;
}
#contact input[type="text"]:focus,
#contact input[type="password"]:focus,
#contact input[type="email"]:focus {
	border-color: #ff2f00;
	color: #FFFFFF;
}
#contact textarea {
	min-height: 20rem;
	padding: 1.8rem 2rem;
}
#contact textarea:focus {
	border-color: #ff2f00;
	color: #FFFFFF;
}
#contact button.submitform {
	font-size: 1.5rem;
	display: block;
	letter-spacing: .2rem;
	height: 6.6rem;
	line-height: 6.6rem;
	padding: 0 3rem;
	margin-top: 4.8rem;
	width: 100%;
	background: #ff2f00;
	color: #FFFFFF;
}
#contact button.submitform:hover, #contact button.submitform:focus {
	background: #ff2f00;
}
#message-warning, #message-success {
	display: none;
	background: #0d0d0d;
	border-radius: 3px;
	padding: 3rem;
	margin-bottom: 3.6rem;
	width: 100%;
}
#message-warning {
	color: #fa0003;
}
#message-success {
	color: #ff2f00;
}
#message-warning i, #message-success i {
	margin-right: 10px;
}

/* form loader */
#submit-loader {
	display: none;
	position: relative;
	left: 0;
	top: 1.8rem;
	width: 100%;
	text-align: center;
}
#submit-loader .text-loader {
	display: none;
	font-family: "poppins-bold", sans-serif;
	color: #FFFFFF;
	letter-spacing: .3rem;
	text-transform: uppercase;
}
.oldie #submit-loader .s-loader {
	display: none;
}
.oldie #submit-loader .text-loader {
	display: block;
}
.contact-info {
	margin: 4.8rem auto 0;
	font-family: "poppins-regular", sans-serif;
	font-size: 1.5rem;
	text-align: center;
}
.contact-info .collapse {
	padding: 0;
}
.contact-info .icon {
	margin-bottom: 2.1rem;
}
.contact-info .icon i {
	font-size: 4.2rem;
	color: #FFFFFF;
}
.contact-info h5 {
	color: #ff2f00;
}

 /*
 * ------------------------------------------------------------------- 
 */
.s-loader {
	margin: 1.2rem auto 3rem;
	width: 70px;
	text-align: center;
	-webkit-transform: translateX(0.45rem);
	-ms-transform: translateX(0.45rem);
	transform: translateX(0.45rem);
}
.s-loader > div {
	width: 1rem;
	height: 1rem;
	background-color: #FFFFFF;
	border-radius: 100%;
	display: inline-block;
	margin-right: .9rem;
	-webkit-animation: sk-bouncedelay 1.4s infinite ease-in-out both;
	animation: sk-bouncedelay 1.4s infinite ease-in-out both;
}
.s-loader .bounce1 {
	-webkit-animation-delay: -0.32s;
	animation-delay: -0.32s;
}
.s-loader .bounce2 {
	-webkit-animation-delay: -0.16s;
	animation-delay: -0.16s;
}
@-webkit-keyframes sk-bouncedelay {
	0%, 80%, 100% {
		-webkit-transform: scale(0);
		-ms-transform: scale(0);
		transform: scale(0);
	}
	40% {
		-webkit-transform: scale(1);
		-ms-transform: scale(1);
		transform: scale(1);
	}
}
@keyframes sk-bouncedelay {
	0%, 80%, 100% {
		-webkit-transform: scale(0);
		-ms-transform: scale(0);
		transform: scale(0);
	}
	40% {
		-webkit-transform: scale(1);
		-ms-transform: scale(1);
		transform: scale(1);
	}
}


 /*
 * ------------------------------------------------------------------- 
 */
footer {
	padding-bottom: 3rem;
	font-size: 1.4rem;
	font-family: "poppins-regular", sans-serif;
}
footer a, footer a:visited {
	color: #FFFFFF;
}
footer a:hover, footer a:focus {
	color: #ff2f00;
}
footer .row {
	max-width: 900px;
}
footer .social {
	text-align: right;
}
footer .footer-social {
	display: inline-block;
	font-size: 2.1rem;
	margin: 0;
	padding: 0;
	position: relative;
	top: -.3rem;
}
footer .footer-social li {
	display: inline-block;
	margin: 0 12px;
	padding: 0;
}
footer .footer-social li a {
	color: #FFFFFF;
}
footer .copyright span {
	display: inline-block;
}
footer .copyright span::after {
	content: "|";
	display: inline-block;
	padding: 0 1rem 0 1.2rem;
	color: rgba(255, 255, 255, 0.1);
}
footer .copyright span:last-child::after {
	display: none;
}

 /*
 * ------------------------------------------------------------------- 
 */
@media only screen and (max-width:768px) {
	footer {
		text-align: center;
	}
	footer .social {
		display: block;
		width: 100%;
		text-align: center;
		margin-bottom: 1.5rem;
	}
	footer .copyright span {
		display: block;
	}
	footer .copyright span::after {
		display: none;
	}
}

 /*
 * ------------------------------------------------------------------- 
 */
#go-top {
	position: fixed;
	bottom: 0;
	right: 0;
	z-index: 600;
	display: none;
}
#go-top a {
	text-decoration: none;
	border: 0 none;
	display: block;
	height: 6.6rem;
	width: 6rem;
	line-height: 6.6rem;
	text-align: center;
	background: #ff2f00;
	color: #FFFFFF;
	text-align: center;
	text-transform: uppercase;
	-moz-transition: all 0.3s ease-in-out;
	-o-transition: all 0.3s ease-in-out;
	-webkit-transition: all 0.3s ease-in-out;
	-ms-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}
#go-top a i {
	font-size: 1.6rem;
	line-height: inherit;
}
#go-top a:hover {
	background: #000000;
}

 /*
 * ------------------------------------------------------------------- 
 */
.owl-carousel .owl-wrapper:after {
	content: ".";
	display: block;
	clear: both;
	visibility: hidden;
	line-height: 0;
	height: 0;
}

/* display none until init */
.owl-carousel {
	display: none;
	position: relative;
	width: 100%;
	-ms-touch-action: pan-y;
}
.owl-carousel .owl-wrapper {
	display: none;
	position: relative;
	-webkit-transform: translate3d(0px, 0px, 0px);
}
.owl-carousel .owl-wrapper-outer {
	overflow: hidden;
	position: relative;
	width: 100%;
}
.owl-carousel .owl-wrapper-outer.autoHeight {
	-webkit-transition: height 500ms ease-in-out;
	-moz-transition: height 500ms ease-in-out;
	-ms-transition: height 500ms ease-in-out;
	-o-transition: height 500ms ease-in-out;
	transition: height 500ms ease-in-out;
}
.owl-carousel .owl-item {
	float: left;
}
.owl-controls .owl-page, .owl-controls .owl-buttons div {
	cursor: pointer;
}
.owl-controls {
	-webkit-user-select: none;
	-khtml-user-select: none;
	-moz-user-select: none;
	-ms-user-select: none;
	user-select: none;
	-webkit-tap-highlight-color: transparent;
}

/* mouse grab icon */
.grabbing {
	cursor: url(grabbing.png) 8 8, move;
}

/* fix */
.owl-carousel .owl-wrapper, .owl-carousel .owl-item {
	-webkit-backface-visibility: hidden;
	-moz-backface-visibility: hidden;
	-ms-backface-visibility: hidden;
	-webkit-transform: translate3d(0, 0, 0);
	-moz-transform: translate3d(0, 0, 0);
	-ms-transform: translate3d(0, 0, 0);
}

/* 
 *  Owl Carousel CSS3 Transitions 
 *  v1.3.2
 */
.owl-origin {
	-webkit-perspective: 1200px;
	-webkit-perspective-origin-x: 50%;
	-webkit-perspective-origin-y: 50%;
	-moz-perspective: 1200px;
	-moz-perspective-origin-x: 50%;
	-moz-perspective-origin-y: 50%;
	perspective: 1200px;
}

/* fade */
.owl-fade-out {
	z-index: 10;
	-webkit-animation: fadeOut .7s both ease;
	-moz-animation: fadeOut .7s both ease;
	animation: fadeOut .7s both ease;
}
.owl-fade-in {
	-webkit-animation: fadeIn .7s both ease;
	-moz-animation: fadeIn .7s both ease;
	animation: fadeIn .7s both ease;
}

/* backSlide */
.owl-backSlide-out {
	-webkit-animation: backSlideOut 1s both ease;
	-moz-animation: backSlideOut 1s both ease;
	animation: backSlideOut 1s both ease;
}
.owl-backSlide-in {
	-webkit-animation: backSlideIn 1s both ease;
	-moz-animation: backSlideIn 1s both ease;
	animation: backSlideIn 1s both ease;
}

/* goDown */
.owl-goDown-out {
	-webkit-animation: scaleToFade .7s ease both;
	-moz-animation: scaleToFade .7s ease both;
	animation: scaleToFade .7s ease both;
}
.owl-goDown-in {
	-webkit-animation: goDown .6s ease both;
	-moz-animation: goDown .6s ease both;
	animation: goDown .6s ease both;
}

/* scaleUp */
.owl-fadeUp-in {
	-webkit-animation: scaleUpFrom .5s ease both;
	-moz-animation: scaleUpFrom .5s ease both;
	animation: scaleUpFrom .5s ease both;
}
.owl-fadeUp-out {
	-webkit-animation: scaleUpTo .5s ease both;
	-moz-animation: scaleUpTo .5s ease both;
	animation: scaleUpTo .5s ease both;
}

/* Keyframes */

/*empty*/
@-webkit-keyframes empty {
	0% {
		opacity: 1;
	}
}
@-moz-keyframes empty {
	0% {
		opacity: 1;
	}
}
@keyframes empty {
	0% {
		opacity: 1;
	}
}
@-webkit-keyframes fadeIn {
	0% {
		opacity: 0;
	}
	100% {
		opacity: 1;
	}
}
@-moz-keyframes fadeIn {
	0% {
		opacity: 0;
	}
	100% {
		opacity: 1;
	}
}
@keyframes fadeIn {
	0% {
		opacity: 0;
	}
	100% {
		opacity: 1;
	}
}
@-webkit-keyframes fadeOut {
	0% {
		opacity: 1;
	}
	100% {
		opacity: 0;
	}
}
@-moz-keyframes fadeOut {
	0% {
		opacity: 1;
	}
	100% {
		opacity: 0;
	}
}
@keyframes fadeOut {
	0% {
		opacity: 1;
	}
	100% {
		opacity: 0;
	}
}
@-webkit-keyframes backSlideOut {
	25% {
		opacity: .5;
		-webkit-transform: translateZ(-500px);
	}
	75% {
		opacity: .5;
		-webkit-transform: translateZ(-500px) translateX(-200%);
	}
	100% {
		opacity: .5;
		-webkit-transform: translateZ(-500px) translateX(-200%);
	}
}
@-moz-keyframes backSlideOut {
	25% {
		opacity: .5;
		-moz-transform: translateZ(-500px);
	}
	75% {
		opacity: .5;
		-moz-transform: translateZ(-500px) translateX(-200%);
	}
	100% {
		opacity: .5;
		-moz-transform: translateZ(-500px) translateX(-200%);
	}
}
@keyframes backSlideOut {
	25% {
		opacity: .5;
		transform: translateZ(-500px);
	}
	75% {
		opacity: .5;
		transform: translateZ(-500px) translateX(-200%);
	}
	100% {
		opacity: .5;
		transform: translateZ(-500px) translateX(-200%);
	}
}
@-webkit-keyframes backSlideIn {
	0%, 25% {
		opacity: .5;
		-webkit-transform: translateZ(-500px) translateX(200%);
	}
	75% {
		opacity: .5;
		-webkit-transform: translateZ(-500px);
	}
	100% {
		opacity: 1;
		-webkit-transform: translateZ(0) translateX(0);
	}
}
@-moz-keyframes backSlideIn {
	0%, 25% {
		opacity: .5;
		-moz-transform: translateZ(-500px) translateX(200%);
	}
	75% {
		opacity: .5;
		-moz-transform: translateZ(-500px);
	}
	100% {
		opacity: 1;
		-moz-transform: translateZ(0) translateX(0);
	}
}
@keyframes backSlideIn {
	0%, 25% {
		opacity: .5;
		transform: translateZ(-500px) translateX(200%);
	}
	75% {
		opacity: .5;
		transform: translateZ(-500px);
	}
	100% {
		opacity: 1;
		transform: translateZ(0) translateX(0);
	}
}
@-webkit-keyframes scaleToFade {
	to {
		opacity: 0;
		-webkit-transform: scale(0.8);
	}
}
@-moz-keyframes scaleToFade {
	to {
		opacity: 0;
		-moz-transform: scale(0.8);
	}
}
@keyframes scaleToFade {
	to {
		opacity: 0;
		transform: scale(0.8);
	}
}
@-webkit-keyframes goDown {
	from {
		-webkit-transform: translateY(-100%);
	}
}
@-moz-keyframes goDown {
	from {
		-moz-transform: translateY(-100%);
	}
}
@keyframes goDown {
	from {
		transform: translateY(-100%);
	}
}
@-webkit-keyframes scaleUpFrom {
	from {
		opacity: 0;
		-webkit-transform: scale(1.5);
	}
}
@-moz-keyframes scaleUpFrom {
	from {
		opacity: 0;
		-moz-transform: scale(1.5);
	}
}
@keyframes scaleUpFrom {
	from {
		opacity: 0;
		transform: scale(1.5);
	}
}
@-webkit-keyframes scaleUpTo {
	to {
		opacity: 0;
		-webkit-transform: scale(1.5);
	}
}
@-moz-keyframes scaleUpTo {
	to {
		opacity: 0;
		-moz-transform: scale(1.5);
	}
}
@keyframes scaleUpTo {
	to {
		opacity: 0;
		transform: scale(1.5);
	}
}


/* 
 *  02. Magnific Popup CSS
 */
.mfp-bg {
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	z-index: 1042;
	overflow: hidden;
	position: fixed;
	background: #0b0b0b;
	opacity: 0.8;
	filter: alpha(opacity=80);
}
.mfp-wrap {
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	z-index: 1043;
	position: fixed;
	outline: none !important;
	-webkit-backface-visibility: hidden;
}
.mfp-container {
	text-align: center;
	position: absolute;
	width: 100%;
	height: 100%;
	left: 0;
	top: 0;
	padding: 0 8px;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}
.mfp-container:before {
	content: '';
	display: inline-block;
	height: 100%;
	vertical-align: middle;
}
.mfp-align-top .mfp-container:before {
	display: none;
}
.mfp-content {
	position: relative;
	display: inline-block;
	vertical-align: middle;
	margin: 0 auto;
	text-align: left;
	z-index: 1045;
}
.mfp-inline-holder .mfp-content, .mfp-ajax-holder .mfp-content {
	width: 100%;
	cursor: auto;
}
.mfp-ajax-cur {
	cursor: progress;
}
.mfp-zoom-out-cur, .mfp-zoom-out-cur .mfp-image-holder .mfp-close {
	cursor: -moz-zoom-out;
	cursor: -webkit-zoom-out;
	cursor: zoom-out;
}
.mfp-zoom {
	cursor: pointer;
	cursor: -webkit-zoom-in;
	cursor: -moz-zoom-in;
	cursor: zoom-in;
}
.mfp-auto-cursor .mfp-content {
	cursor: auto;
}
.mfp-close, .mfp-arrow, .mfp-preloader, .mfp-counter {
	-webkit-user-select: none;
	-moz-user-select: none;
	user-select: none;
}
.mfp-loading.mfp-figure {
	display: none;
}
.mfp-hide {
	display: none !important;
}
.mfp-preloader {
	color: #CCC;
	position: absolute;
	top: 50%;
	width: auto;
	text-align: center;
	margin-top: -0.8em;
	left: 8px;
	right: 8px;
	z-index: 1044;
}
.mfp-preloader a {
	color: #CCC;
}
.mfp-preloader a:hover {
	color: #FFF;
}
.mfp-s-ready .mfp-preloader {
	display: none;
}
.mfp-s-error .mfp-content {
	display: none;
}
button.mfp-close, button.mfp-arrow {
	overflow: visible;
	cursor: pointer;
	background: transparent;
	border: 0;
	-webkit-appearance: none;
	display: block;
	outline: none;
	padding: 0;
	z-index: 1046;
	-webkit-box-shadow: none;
	box-shadow: none;
}
button::-moz-focus-inner {
	padding: 0;
	border: 0;
}
.mfp-close {
	width: 44px;
	height: 44px;
	line-height: 44px;
	position: absolute;
	right: 0;
	top: 0;
	text-decoration: none;
	text-align: center;
	opacity: 0.65;
	filter: alpha(opacity=65);
	padding: 0 0 18px 10px;
	color: #FFF;
	font-style: normal;
	font-size: 28px;
	font-family: Arial, Baskerville, monospace;
}
.mfp-close:hover, .mfp-close:focus {
	opacity: 1;
	filter: alpha(opacity=100);
}
.mfp-close:active {
	top: 1px;
}
.mfp-close-btn-in .mfp-close {
	color: #333;
}
.mfp-image-holder .mfp-close, .mfp-iframe-holder .mfp-close {
	color: #FFF;
	right: -6px;
	text-align: right;
	padding-right: 6px;
	width: 100%;
}
.mfp-counter {
	position: absolute;
	top: 0;
	right: 0;
	color: #CCC;
	font-size: 12px;
	line-height: 18px;
	white-space: nowrap;
}
.mfp-arrow {
	position: absolute;
	opacity: 0.65;
	filter: alpha(opacity=65);
	margin: 0;
	top: 50%;
	margin-top: -55px;
	padding: 0;
	width: 90px;
	height: 110px;
	-webkit-tap-highlight-color: transparent;
}
.mfp-arrow:active {
	margin-top: -54px;
}
.mfp-arrow:hover, .mfp-arrow:focus {
	opacity: 1;
	filter: alpha(opacity=100);
}
.mfp-arrow:before, .mfp-arrow:after, .mfp-arrow .mfp-b, .mfp-arrow .mfp-a {
	content: '';
	display: block;
	width: 0;
	height: 0;
	position: absolute;
	left: 0;
	top: 0;
	margin-top: 35px;
	margin-left: 35px;
	border: medium inset transparent;
}
.mfp-arrow:after, .mfp-arrow .mfp-a {
	border-top-width: 13px;
	border-bottom-width: 13px;
	top: 8px;
}
.mfp-arrow:before, .mfp-arrow .mfp-b {
	border-top-width: 21px;
	border-bottom-width: 21px;
	opacity: 0.7;
}
.mfp-arrow-left {
	left: 0;
}
.mfp-arrow-left:after, .mfp-arrow-left .mfp-a {
	border-right: 17px solid #FFF;
	margin-left: 31px;
}
.mfp-arrow-left:before, .mfp-arrow-left .mfp-b {
	margin-left: 25px;
	border-right: 27px solid #3F3F3F;
}
.mfp-arrow-right {
	right: 0;
}
.mfp-arrow-right:after, .mfp-arrow-right .mfp-a {
	border-left: 17px solid #FFF;
	margin-left: 39px;
}
.mfp-arrow-right:before, .mfp-arrow-right .mfp-b {
	border-left: 27px solid #3F3F3F;
}
.mfp-iframe-holder {
	padding-top: 40px;
	padding-bottom: 40px;
}
.mfp-iframe-holder .mfp-content {
	line-height: 0;
	width: 100%;
	max-width: 900px;
}
.mfp-iframe-holder .mfp-close {
	top: -40px;
}
.mfp-iframe-scaler {
	width: 100%;
	height: 0;
	overflow: hidden;
	padding-top: 56.25%;
}
.mfp-iframe-scaler iframe {
	position: absolute;
	display: block;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	box-shadow: 0 0 8px rgba(0, 0, 0, 0.6);
	background: #000;
}

/* Main image in popup */
img.mfp-img {
	width: auto;
	max-width: 100%;
	height: auto;
	display: block;
	line-height: 0;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
	padding: 40px 0 40px;
	margin: 0 auto;
}

/* The shadow behind the image */
.mfp-figure {
	line-height: 0;
}
.mfp-figure:after {
	content: '';
	position: absolute;
	left: 0;
	top: 40px;
	bottom: 40px;
	display: block;
	right: 0;
	width: auto;
	height: auto;
	z-index: -1;
	box-shadow: 0 0 8px rgba(0, 0, 0, 0.6);
	background: #444;
}
.mfp-figure small {
	color: #BDBDBD;
	display: block;
	font-size: 12px;
	line-height: 14px;
}
.mfp-figure figure {
	margin: 0;
}
.mfp-bottom-bar {
	margin-top: -36px;
	position: absolute;
	top: 100%;
	left: 0;
	width: 100%;
	cursor: auto;
}
.mfp-title {
	text-align: left;
	line-height: 18px;
	color: #F3F3F3;
	word-wrap: break-word;
	padding-right: 36px;
}
.mfp-image-holder .mfp-content {
	max-width: 100%;
}
.mfp-gallery .mfp-image-holder .mfp-figure {
	cursor: pointer;
}
@media screen and (max-width:800px) and (orientation:landscape), screen and (max-height:300px) {

	/**
	     * Remove all paddings around the image on small screen
	     */
	.mfp-img-mobile .mfp-image-holder {
		padding-left: 0;
		padding-right: 0;
	}
	.mfp-img-mobile img.mfp-img {
		padding: 0;
	}
	.mfp-img-mobile .mfp-figure:after {
		top: 0;
		bottom: 0;
	}
	.mfp-img-mobile .mfp-figure small {
		display: inline;
		margin-left: 5px;
	}
	.mfp-img-mobile .mfp-bottom-bar {
		background: rgba(0, 0, 0, 0.6);
		bottom: 0;
		margin: 0;
		top: auto;
		padding: 3px 5px;
		position: fixed;
		-webkit-box-sizing: border-box;
		-moz-box-sizing: border-box;
		box-sizing: border-box;
	}
	.mfp-img-mobile .mfp-bottom-bar:empty {
		padding: 0;
	}
	.mfp-img-mobile .mfp-counter {
		right: 5px;
		top: 3px;
	}
	.mfp-img-mobile .mfp-close {
		top: 0;
		right: 0;
		width: 35px;
		height: 35px;
		line-height: 35px;
		background: rgba(0, 0, 0, 0.6);
		position: fixed;
		text-align: center;
		padding: 0;
	}
}
@media all and (max-width:900px) {
	.mfp-arrow {
		-webkit-transform: scale(0.75);
		transform: scale(0.75);
	}
	.mfp-arrow-left {
		-webkit-transform-origin: 0;
		transform-origin: 0;
	}
	.mfp-arrow-right {
		-webkit-transform-origin: 100%;
		transform-origin: 100%;
	}
	.mfp-container {
		padding-left: 6px;
		padding-right: 6px;
	}
}
.mfp-ie7 .mfp-img {
	padding: 0;
}
.mfp-ie7 .mfp-bottom-bar {
	width: 600px;
	left: 50%;
	margin-left: -300px;
	margin-top: 5px;
	padding-bottom: 5px;
}
.mfp-ie7 .mfp-container {
	padding: 0;
}
.mfp-ie7 .mfp-content {
	padding-top: 44px;
}
.mfp-ie7 .mfp-close {
	top: 0;
	right: 0;
	padding-top: 0;
}

 /*
 * End----------------------------------- 
 */
</style>
	<!-- header 
   ================================================== -->
   <header>   	
   	<div class="row">

   		<div class="top-bar">
   			<a class="menu-toggle" href="#"><span>Menu</span></a>

	   		<div class="logo">
		         <a href="index.html">MDC</a>
		      </div>		      

		   	<nav id="main-nav-wrap">
					<ul class="main-navigation">
						<li class="current"><a class="smoothscroll"  href="#intro" title="">Home</a></li>
						<li><a class="smoothscroll"  href="#about" title="">About</a></li>
						<li><a class="smoothscroll"  href="#resume" title="">Resume</a></li>
						<li><a class="smoothscroll"  href="#contact" title="">Contact</a></li>	
					</ul>
				</nav>    		
   		</div> <!-- /top-bar --> 
   		
   	</div> <!-- /row --> 		
   </header> <!-- /header -->

	<!-- intro section
   ================================================== -->
   <section id="intro">   

   	<div class="intro-overlay"></div>	

   	<div class="intro-content">
   		<div class="row">

   			<div class="col-twelve">

	   			<h5>Ayyyy,</h5>
	   			<h1>Matt Clayton</h1><p>
				<p class="intro-position">
				<strong>Software Development, Support & Design</strong>
				</p>
	   			<p class="intro-position">
				<span>Embedded</span>
				<span>Web</span>
				<span>Mobile</span>
	   			</p>
				


	   			<a class="button stroke smoothscroll" href="#about" title="">More About Me</a>

	   		</div>  
   			
   		</div>   		 		
   	</div> <!-- /intro-content --> 

   </section> <!-- /intro -->


   <!-- about section
   ================================================== -->
   <section id="about">  

   	<div class="row section-intro">
   		<div class="col-twelve">

   			<h5>About</h5>
   			<h1>Allow myself, to introduce... myself.</h1>

   			<div class="intro-info">

   				<img src="data:image/png;base64,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" alt="Profile Picture">

   				<p class="lead">Curiosity is my super power and I have a wide array of interests in many curious things.
				I am an engineer at the root, and I love to build, fix and create... I'm no stranger to taking things apart, on occasion I will reverse engineer software and devices to understand how they work.  
				I am most comfortable in the space between the software and the tangible electronics but, being curious, I'm always looking for a new niche. 
				I'm comfortable working in different spaces, from bare metal assembly code and firmware...to the servers, OS and database level... to the UX\UI design. I'm also pretty well rounded in the fabrication and assembly department.  I regualrly solder components, TIG weld mockups and prototype on my 3d printer at home. It wouldn't be much of a stretch to say I enjoy all aspects of how dynamic systems work and interact. 
				
				 </p>
   			</div>  			

   		</div>   		
   	</div> <!-- /section-intro -->

   	<div class="row about-content">

   		<div class="col-six tab-full">

   			<h3>Life</h3>
   			<p>I am the proud father of two incredible preschoolers.  I spend the bulk of my freetime with them going on adventures, finding unique parks, swimming, gaming and reading with them.  <br> On the off chance i get time in the morning and at night, I try to stay healthy and fit, mainly to keep up with them, which is often a challenge. I'm an avid runner and try to get to the gym a few days a week when time permits. <br>My most recent fascination are vertical gardens, specifically, aeroponic vegitable gardens. I am currently researching the best way to build a High Pressure (HP) aeroponic system on a budget. </p>

   			<ul class="info-list">
   				<li>
   					<strong>Fullname:</strong>
   					<span>Matthew Clayton</span>
   				</li>
   				<li>
   					<strong>Birth Date:</strong>
   					<span>June 17, 1983</span>
   				</li>
   				<li>
   					<strong>Job:</strong>
   					<span>Development, Support, Test, Design</span>
   				</li>
   				<li>
   					<strong>Website:</strong>
   					<span>www.MattClayton.dev</span>
   				</li>
   				<li>
   					<strong>Email:</strong>
   					<span>me@mattclayton.dev</span>
   				</li>

   			</ul> <!-- /info-list -->

   		</div>

   		<div class="col-six tab-full">

   			<h3>Skills</h3>
   			<p>I have a wide ranging skillset that I've developed over my lifetime of working with systems in industries including Finance, Energy, Retail and Robotics.<br>
			   I have a deep interest in computer vision and machine learning as well as the applications involving these technologies, including Augmented Reality(AR), Robotic navigation, Monocular SLAM, Image/facial recognition and visual object recognition.</p>

				<ul class="info-list">
				   <li>
				   	<strong>Languages</strong>
					<span>C++, C, C#, Centura, VB</span>
					<span>SQL, Python, Powershell, Bash, SQR, JS</span>
					<span>HTML, XML, JSON </span>
				   </li>
				   <li>
				   	<strong>Enterprise Applications</strong>
					<span>Visual Studio, SSMS, MS TFS, IIS</span>
				   </li>
				    <li>
				   	<strong>Enterprise Operating Systems</strong>
					<span>Windows, MS Server 2008-2016, Azure, Linux</span>
				   </li>
				   <li>
				   	<strong>Other Applications / OS</strong>
					<span>Fusion 360, Unity, Sketchup, Blender, Cura, Adobe Creative Suite</span> 
					<span>Arduino, QT, CMake, Wireshark, IDA Disassembler, HexWorkshop, WinSCP, WinDbg</span>
					<span>ROS, QNX, FreeRTOS</span>
				   </li>
				   <li>
				   	<strong>Other Skills</strong>
					<span>Microcontrollers, Analog/Digital Circuits, AC/DC wiring</span>
					<span>AC/DC motors (Servo, Stepper, BLDC)  </span>
					<span>AC/DC Tungsten(TIG) welding, Soldering, Brazing</span>
					<span>CNC, Lathe, Mill, 3d Printing, Sheet Metal Fabrication</span>
				   </li>
				 
					
      
				</ul> <!-- /skill-bars -->		

   		</div>

   	</div>


   </section> <!-- /process-->    


   <!-- resume Section
   ================================================== -->
	<section id="resume" class="grey-section">

		<div class="row section-intro">
   		<div class="col-twelve">

   			<h5>Resume</h5>
   			<h1>Creds</h1>
<div class="intro-info">

   				<img src="data:image/png;base64,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" alt="Profile Picture">

   				<p class="lead">My work experience with software/hardware development and support has spanned multiple industries including Finance, Energy, Retail and Robotics,each requiring a different skillset and software stack for their implementations. Currently I am seeking a challenging support or development opportunity with an innovative software firm.</p>
   			</div>  			
   				
   			

   		</div>   		
   	</div> <!-- /section-intro--> 

   	<div class="row resume-timeline">

   		<div class="col-twelve resume-header">

   			<h2>Work Experience</h2>

   		</div> <!-- /resume-header -->

   		<div class="col-twelve">

   			<div class="timeline-wrap">

   				<div class="timeline-block">

	   				<div class="timeline-ico">
	   					<i class="fa">></i>
	   				</div>

	   				<div class="timeline-header">
	   					<h3>Software Support Engineer</h3>
	   					<p>Oct 2014 - Present</p>
	   				</div>

	   				<div class="timeline-content">
	   					<h4>Finastra
						<br><i>International Financial Software</i></h4>
	   					
						<ul>
						<li>Fin Tech Enterprise software deployment, support and development.
						<li>Troubleshooting within highly secure production software/DB environments. 
						<li>High priority and critical support issue resolution within 60 min SLA/SLO.
						<li>Debug stored procedures, C#, SQL, SQR, XML and Centura code. 
						<li>Pre deployment beta testing and reporting.
						<li>Product defect identification, submission and workaround.
						<li>Installed and maintained QA testing environments.
						<li>Client support in multiple secure server/database environments in-house and Azure Cloud.
						<li>Create, update and maintain internal and client facing documentation.
						<li>New hire training. 
						</ul>
					</div>

	   			</div> <!-- /timeline-block -->

	   			<div class="timeline-block">

	   				<div class="timeline-ico">
	   					<i class="fa">></i>
	   				</div>

	   				<div class="timeline-header">
	   					<h3>Software Product Engineer</h3>
	   					<p>Apr 2016 - Apr 2017</p>
	   				</div>

	   				<div class="timeline-content">
	   					<h4>Mineware Inc.
						<br><i>Semi-Autonomous Software for Dragline Mining Operations</i></h4>
	   					<ul>
						<li>Mineware software deployment, support and development.
						<li>Software integration with PLC, Modbus TCP/IP and embedded SQL database environments.
						<li>Troubleshooting embedded windows/linux hardware, wireless/wired networks and GPS.
						<li>Debug C/C++ and C# code. 
						</ul>
					</div>

	   			</div> <!-- /timeline-block -->

	   			<div class="timeline-block">

	   				<div class="timeline-ico">
	   					<i class="fa">></i>
	   				</div>

	   				<div class="timeline-header">
	   					<h3>Software Development, Web Development, DBA</h3>
	   					<p>Apr 2013 - Oct 2014</p>
	   				</div>

	   				<div class="timeline-content">
	   					<h4>Camping Connection
						<br><i>Sales and Service of RV equipment</i></h4>
	   					<ul>
						<li>Designed, coded and maintained multiple websites in C#.
						<li>Created and maintained SQL database of more than 14k products.
						<li>Customized and deployed API???s for Amazon, UPS, FedEx, USPS and Ebay.
						<li>Worked with team to update Fox Pro database and POS system to SQL and .Net environment.
						</ul>
					</div>

	   			</div> <!-- /timeline-block -->

   			</div> <!-- /timeline-wrap -->   			

   		</div> <!-- /col-twelve -->
   		
   	</div> <!-- /resume-timeline -->
   	
   	<div class="row resume-timeline">

   		<div class="col-twelve resume-header">

   			<h2>Education</h2>

   		</div> <!-- /resume-header -->

   		<div class="col-twelve">

   			<div class="timeline-wrap">

   				<div class="timeline-block">

	   				<div class="timeline-ico">
	   					<i class="fa">></i>
	   				</div>

	   				<div class="timeline-header">
	   					<h3>Associates Degree</h3>
	   					<p>Sep 2010 - Jun 2013</p>
	   				</div>

	   				<div class="timeline-content">
	   					<h4>Palm Beach State College</h4>
	   					<p>AA Honors Degree with High Honors
<ul><li>Palm Beach State College Math and Science Institute (MSI)
<li>MSI program Geographic Information Systems, Esri GIS</ul></div>



   			</div> <!-- /timeline-wrap -->   			

   		</div> <!-- /col-twelve -->
   		
   	</div> <!-- /resume-timeline -->
		
	</section> <!-- /features -->




   <!-- contact
   ================================================== -->
	<section id="contact">

		<div class="row section-intro">
   		<div class="col-twelve">

   			<h5>Contact</h5>
   			<h1>Let's work on something</h1>
   		</div> 


   	<div class="row contact-info">

   		<div class="col-four tab-full">

   			<div class="icon">
   				<i class="icon-pin"></i>
   			</div>

   			<h5>Locale</h5>

   			<p>
            West Palm Beach, FL<br>
            33412 US
            </p>

   		</div>

   		<div class="col-four tab-full collapse">

   			<div class="icon">
   				<i class="icon-mail"></i>
   			</div>

   			<h5>Email</h5>

   			<p>&#109;&#101;&#064;&#109;&#097;&#116;&#116;&#099;&#108;&#097;&#121;&#116;&#111;&#110;&#046;&#100;&#101;&#118;
			   </p>

   		</div>
   		
   	</div> <!-- /contact-info -->
		
	</section> <!-- /contact -->


   <!-- footer
   ================================================== -->

   <footer>
     	<div class="row">



	      	<div id="go-top">
		         <a class="smoothscroll" title="Back to Top" href="#top"><i class="fa">^</i></a>
		      </div>

      	</div> <!-- /row -->     	
   </footer>  

   <div id="preloader"> 
    	<div id="loader"></div>
   </div> 

   <!-- Java Script
   ================================================== --> 
   <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
   <!--<script src="js/plugins.js"></script>-->
   <script>
   /** 
 * ===================================================================
 * javascript plugins
 *
 * ------------------------------------------------------------------- 
 */

/* HTML5 Placeholder jQuery Plugin - v2.1.2
 * Copyright (c)2015 Mathias Bynens
 * 2015-06-09
 */
!function(a){"function"==typeof define&&define.amd?define(["jquery"],a):a("object"==typeof module&&module.exports?require("jquery"):jQuery)}(function(a){function b(b){var c={},d=/^jQuery\d+$/;return a.each(b.attributes,function(a,b){b.specified&&!d.test(b.name)&&(c[b.name]=b.value)}),c}function c(b,c){var d=this,f=a(d);if(d.value==f.attr("placeholder")&&f.hasClass(m.customClass))if(f.data("placeholder-password")){if(f=f.hide().nextAll('input[type="password"]:first').show().attr("id",f.removeAttr("id").data("placeholder-id")),b===!0)return f[0].value=c;f.focus()}else d.value="",f.removeClass(m.customClass),d==e()&&d.select()}function d(){var d,e=this,f=a(e),g=this.id;if(""===e.value){if("password"===e.type){if(!f.data("placeholder-textinput")){try{d=f.clone().prop({type:"text"})}catch(h){d=a("<input>").attr(a.extend(b(this),{type:"text"}))}d.removeAttr("name").data({"placeholder-password":f,"placeholder-id":g}).bind("focus.placeholder",c),f.data({"placeholder-textinput":d,"placeholder-id":g}).before(d)}f=f.removeAttr("id").hide().prevAll('input[type="text"]:first').attr("id",g).show()}f.addClass(m.customClass),f[0].value=f.attr("placeholder")}else f.removeClass(m.customClass)}function e(){try{return document.activeElement}catch(a){}}var f,g,h="[object OperaMini]"==Object.prototype.toString.call(window.operamini),i="placeholder"in document.createElement("input")&&!h,j="placeholder"in document.createElement("textarea")&&!h,k=a.valHooks,l=a.propHooks;if(i&&j)g=a.fn.placeholder=function(){return this},g.input=g.textarea=!0;else{var m={};g=a.fn.placeholder=function(b){var e={customClass:"placeholder"};m=a.extend({},e,b);var f=this;return f.filter((i?"textarea":":input")+"[placeholder]").not("."+m.customClass).bind({"focus.placeholder":c,"blur.placeholder":d}).data("placeholder-enabled",!0).trigger("blur.placeholder"),f},g.input=i,g.textarea=j,f={get:function(b){var c=a(b),d=c.data("placeholder-password");return d?d[0].value:c.data("placeholder-enabled")&&c.hasClass(m.customClass)?"":b.value},set:function(b,f){var g=a(b),h=g.data("placeholder-password");return h?h[0].value=f:g.data("placeholder-enabled")?(""===f?(b.value=f,b!=e()&&d.call(b)):g.hasClass(m.customClass)?c.call(b,!0,f)||(b.value=f):b.value=f,g):b.value=f}},i||(k.input=f,l.value=f),j||(k.textarea=f,l.value=f),a(function(){a(document).delegate("form","submit.placeholder",function(){var b=a("."+m.customClass,this).each(c);setTimeout(function(){b.each(d)},10)})}),a(window).bind("beforeunload.placeholder",function(){a("."+m.customClass).each(function(){this.value=""})})}});


/* jshint browser:true 
 * !
 * FitVids 1.1
 *
 * Copyright 2013, Chris Coyier - http://css-tricks.com + Dave Rupert - http://daverupert.com
 * Credit to Thierry Koblentz - http://www.alistapart.com/articles/creating-intrinsic-ratios-for-video/
 * Released under the WTFPL license - http://sam.zoy.org/wtfpl/
 *
 */
!function(a){"use strict";a.fn.fitVids=function(b){var c={customSelector:null,ignore:null};if(!document.getElementById("fit-vids-style")){var d=document.head||document.getElementsByTagName("head")[0],e=".fluid-width-video-wrapper{width:100%;position:relative;padding:0;}.fluid-width-video-wrapper iframe,.fluid-width-video-wrapper object,.fluid-width-video-wrapper embed {position:absolute;top:0;left:0;width:100%;height:100%;}",f=document.createElement("div");f.innerHTML='<p>x</p><style id="fit-vids-style">'+e+"</style>",d.appendChild(f.childNodes[1])}return b&&a.extend(c,b),this.each(function(){var b=['iframe[src*="player.vimeo.com"]','iframe[src*="youtube.com"]','iframe[src*="youtube-nocookie.com"]','iframe[src*="kickstarter.com"][src*="video.html"]',"object","embed"];c.customSelector&&b.push(c.customSelector);var d=".fitvidsignore";c.ignore&&(d=d+", "+c.ignore);var e=a(this).find(b.join(","));e=e.not("object object"),e=e.not(d),e.each(function(b){var c=a(this);if(!(c.parents(d).length>0||"embed"===this.tagName.toLowerCase()&&c.parent("object").length||c.parent(".fluid-width-video-wrapper").length)){c.css("height")||c.css("width")||!isNaN(c.attr("height"))&&!isNaN(c.attr("width"))||(c.attr("height",9),c.attr("width",16));var e="object"===this.tagName.toLowerCase()||c.attr("height")&&!isNaN(parseInt(c.attr("height"),10))?parseInt(c.attr("height"),10):c.height(),f=isNaN(parseInt(c.attr("width"),10))?c.width():parseInt(c.attr("width"),10),g=e/f;if(!c.attr("id")){var h="fitvid"+b;c.attr("id",h)}c.wrap('<div class="fluid-width-video-wrapper"></div>').parent(".fluid-width-video-wrapper").css("padding-top",100*g+"%"),c.removeAttr("height").removeAttr("width")}})})}}(window.jQuery||window.Zepto);


/* global jQuery 
 * !
 * FitText.js 1.2
 *
 * Copyright 2011, Dave Rupert http://daverupert.com
 * Released under the WTFPL license
 * http://sam.zoy.org/wtfpl/
 *
 * Date: Thu May 05 14:23:00 2011 -0600
 */
(function( $ ){

  $.fn.fitText = function( kompressor, options ) {

    // Setup options
    var compressor = kompressor || 1,
        settings = $.extend({
          'minFontSize' : Number.NEGATIVE_INFINITY,
          'maxFontSize' : Number.POSITIVE_INFINITY
        }, options);

    return this.each(function(){

      // Store the object
      var $this = $(this);

      // Resizer() resizes items based on the object width divided by the compressor * 10
      var resizer = function () {
        $this.css('font-size', Math.max(Math.min($this.width() / (compressor*10), parseFloat(settings.maxFontSize)), parseFloat(settings.minFontSize)));
      };

      // Call once to set.
      resizer();

      // Call on resize. Opera debounces their resize by default.
      $(window).on('resize.fittext orientationchange.fittext', resizer);

    });

  };

})( jQuery );


/* jQuery OwlCarousel v1.3.3
 *
 * Copyright (c) 2013 Bartosz Wojciechowski
 * http://www.owlgraphic.com/owlcarousel/
 *
 * Licensed under MIT
 *
 */
"function"!==typeof Object.create&&(Object.create=function(f){function g(){}g.prototype=f;return new g});
(function(f,g,k){var l={init:function(a,b){this.$elem=f(b);this.options=f.extend({},f.fn.owlCarousel.options,this.$elem.data(),a);this.userOptions=a;this.loadContent()},loadContent:function(){function a(a){var d,e="";if("function"===typeof b.options.jsonSuccess)b.options.jsonSuccess.apply(this,[a]);else{for(d in a.owl)a.owl.hasOwnProperty(d)&&(e+=a.owl[d].item);b.$elem.html(e)}b.logIn()}var b=this,e;"function"===typeof b.options.beforeInit&&b.options.beforeInit.apply(this,[b.$elem]);"string"===typeof b.options.jsonPath?
(e=b.options.jsonPath,f.getJSON(e,a)):b.logIn()},logIn:function(){this.$elem.data("owl-originalStyles",this.$elem.attr("style"));this.$elem.data("owl-originalClasses",this.$elem.attr("class"));this.$elem.css({opacity:0});this.orignalItems=this.options.items;this.checkBrowser();this.wrapperWidth=0;this.checkVisible=null;this.setVars()},setVars:function(){if(0===this.$elem.children().length)return!1;this.baseClass();this.eventTypes();this.$userItems=this.$elem.children();this.itemsAmount=this.$userItems.length;
this.wrapItems();this.$owlItems=this.$elem.find(".owl-item");this.$owlWrapper=this.$elem.find(".owl-wrapper");this.playDirection="next";this.prevItem=0;this.prevArr=[0];this.currentItem=0;this.customEvents();this.onStartup()},onStartup:function(){this.updateItems();this.calculateAll();this.buildControls();this.updateControls();this.response();this.moveEvents();this.stopOnHover();this.owlStatus();!1!==this.options.transitionStyle&&this.transitionTypes(this.options.transitionStyle);!0===this.options.autoPlay&&
(this.options.autoPlay=5E3);this.play();this.$elem.find(".owl-wrapper").css("display","block");this.$elem.is(":visible")?this.$elem.css("opacity",1):this.watchVisibility();this.onstartup=!1;this.eachMoveUpdate();"function"===typeof this.options.afterInit&&this.options.afterInit.apply(this,[this.$elem])},eachMoveUpdate:function(){!0===this.options.lazyLoad&&this.lazyLoad();!0===this.options.autoHeight&&this.autoHeight();this.onVisibleItems();"function"===typeof this.options.afterAction&&this.options.afterAction.apply(this,
[this.$elem])},updateVars:function(){"function"===typeof this.options.beforeUpdate&&this.options.beforeUpdate.apply(this,[this.$elem]);this.watchVisibility();this.updateItems();this.calculateAll();this.updatePosition();this.updateControls();this.eachMoveUpdate();"function"===typeof this.options.afterUpdate&&this.options.afterUpdate.apply(this,[this.$elem])},reload:function(){var a=this;g.setTimeout(function(){a.updateVars()},0)},watchVisibility:function(){var a=this;if(!1===a.$elem.is(":visible"))a.$elem.css({opacity:0}),
g.clearInterval(a.autoPlayInterval),g.clearInterval(a.checkVisible);else return!1;a.checkVisible=g.setInterval(function(){a.$elem.is(":visible")&&(a.reload(),a.$elem.animate({opacity:1},200),g.clearInterval(a.checkVisible))},500)},wrapItems:function(){this.$userItems.wrapAll('<div class="owl-wrapper">').wrap('<div class="owl-item"></div>');this.$elem.find(".owl-wrapper").wrap('<div class="owl-wrapper-outer">');this.wrapperOuter=this.$elem.find(".owl-wrapper-outer");this.$elem.css("display","block")},
baseClass:function(){var a=this.$elem.hasClass(this.options.baseClass),b=this.$elem.hasClass(this.options.theme);a||this.$elem.addClass(this.options.baseClass);b||this.$elem.addClass(this.options.theme)},updateItems:function(){var a,b;if(!1===this.options.responsive)return!1;if(!0===this.options.singleItem)return this.options.items=this.orignalItems=1,this.options.itemsCustom=!1,this.options.itemsDesktop=!1,this.options.itemsDesktopSmall=!1,this.options.itemsTablet=!1,this.options.itemsTabletSmall=
!1,this.options.itemsMobile=!1;a=f(this.options.responsiveBaseWidth).width();a>(this.options.itemsDesktop[0]||this.orignalItems)&&(this.options.items=this.orignalItems);if(!1!==this.options.itemsCustom)for(this.options.itemsCustom.sort(function(a,b){return a[0]-b[0]}),b=0;b<this.options.itemsCustom.length;b+=1)this.options.itemsCustom[b][0]<=a&&(this.options.items=this.options.itemsCustom[b][1]);else a<=this.options.itemsDesktop[0]&&!1!==this.options.itemsDesktop&&(this.options.items=this.options.itemsDesktop[1]),
a<=this.options.itemsDesktopSmall[0]&&!1!==this.options.itemsDesktopSmall&&(this.options.items=this.options.itemsDesktopSmall[1]),a<=this.options.itemsTablet[0]&&!1!==this.options.itemsTablet&&(this.options.items=this.options.itemsTablet[1]),a<=this.options.itemsTabletSmall[0]&&!1!==this.options.itemsTabletSmall&&(this.options.items=this.options.itemsTabletSmall[1]),a<=this.options.itemsMobile[0]&&!1!==this.options.itemsMobile&&(this.options.items=this.options.itemsMobile[1]);this.options.items>this.itemsAmount&&
!0===this.options.itemsScaleUp&&(this.options.items=this.itemsAmount)},response:function(){var a=this,b,e;if(!0!==a.options.responsive)return!1;e=f(g).width();a.resizer=function(){f(g).width()!==e&&(!1!==a.options.autoPlay&&g.clearInterval(a.autoPlayInterval),g.clearTimeout(b),b=g.setTimeout(function(){e=f(g).width();a.updateVars()},a.options.responsiveRefreshRate))};f(g).resize(a.resizer)},updatePosition:function(){this.jumpTo(this.currentItem);!1!==this.options.autoPlay&&this.checkAp()},appendItemsSizes:function(){var a=
this,b=0,e=a.itemsAmount-a.options.items;a.$owlItems.each(function(c){var d=f(this);d.css({width:a.itemWidth}).data("owl-item",Number(c));if(0===c%a.options.items||c===e)c>e||(b+=1);d.data("owl-roundPages",b)})},appendWrapperSizes:function(){this.$owlWrapper.css({width:this.$owlItems.length*this.itemWidth*2,left:0});this.appendItemsSizes()},calculateAll:function(){this.calculateWidth();this.appendWrapperSizes();this.loops();this.max()},calculateWidth:function(){this.itemWidth=Math.round(this.$elem.width()/
this.options.items)},max:function(){var a=-1*(this.itemsAmount*this.itemWidth-this.options.items*this.itemWidth);this.options.items>this.itemsAmount?this.maximumPixels=a=this.maximumItem=0:(this.maximumItem=this.itemsAmount-this.options.items,this.maximumPixels=a);return a},min:function(){return 0},loops:function(){var a=0,b=0,e,c;this.positionsInArray=[0];this.pagesInArray=[];for(e=0;e<this.itemsAmount;e+=1)b+=this.itemWidth,this.positionsInArray.push(-b),!0===this.options.scrollPerPage&&(c=f(this.$owlItems[e]),
c=c.data("owl-roundPages"),c!==a&&(this.pagesInArray[a]=this.positionsInArray[e],a=c))},buildControls:function(){if(!0===this.options.navigation||!0===this.options.pagination)this.owlControls=f('<div class="owl-controls"/>').toggleClass("clickable",!this.browser.isTouch).appendTo(this.$elem);!0===this.options.pagination&&this.buildPagination();!0===this.options.navigation&&this.buildButtons()},buildButtons:function(){var a=this,b=f('<div class="owl-buttons"/>');a.owlControls.append(b);a.buttonPrev=
f("<div/>",{"class":"owl-prev",html:a.options.navigationText[0]||""});a.buttonNext=f("<div/>",{"class":"owl-next",html:a.options.navigationText[1]||""});b.append(a.buttonPrev).append(a.buttonNext);b.on("touchstart.owlControls mousedown.owlControls",'div[class^="owl"]',function(a){a.preventDefault()});b.on("touchend.owlControls mouseup.owlControls",'div[class^="owl"]',function(b){b.preventDefault();f(this).hasClass("owl-next")?a.next():a.prev()})},buildPagination:function(){var a=this;a.paginationWrapper=
f('<div class="owl-pagination"/>');a.owlControls.append(a.paginationWrapper);a.paginationWrapper.on("touchend.owlControls mouseup.owlControls",".owl-page",function(b){b.preventDefault();Number(f(this).data("owl-page"))!==a.currentItem&&a.goTo(Number(f(this).data("owl-page")),!0)})},updatePagination:function(){var a,b,e,c,d,g;if(!1===this.options.pagination)return!1;this.paginationWrapper.html("");a=0;b=this.itemsAmount-this.itemsAmount%this.options.items;for(c=0;c<this.itemsAmount;c+=1)0===c%this.options.items&&
(a+=1,b===c&&(e=this.itemsAmount-this.options.items),d=f("<div/>",{"class":"owl-page"}),g=f("<span></span>",{text:!0===this.options.paginationNumbers?a:"","class":!0===this.options.paginationNumbers?"owl-numbers":""}),d.append(g),d.data("owl-page",b===c?e:c),d.data("owl-roundPages",a),this.paginationWrapper.append(d));this.checkPagination()},checkPagination:function(){var a=this;if(!1===a.options.pagination)return!1;a.paginationWrapper.find(".owl-page").each(function(){f(this).data("owl-roundPages")===
f(a.$owlItems[a.currentItem]).data("owl-roundPages")&&(a.paginationWrapper.find(".owl-page").removeClass("active"),f(this).addClass("active"))})},checkNavigation:function(){if(!1===this.options.navigation)return!1;!1===this.options.rewindNav&&(0===this.currentItem&&0===this.maximumItem?(this.buttonPrev.addClass("disabled"),this.buttonNext.addClass("disabled")):0===this.currentItem&&0!==this.maximumItem?(this.buttonPrev.addClass("disabled"),this.buttonNext.removeClass("disabled")):this.currentItem===
this.maximumItem?(this.buttonPrev.removeClass("disabled"),this.buttonNext.addClass("disabled")):0!==this.currentItem&&this.currentItem!==this.maximumItem&&(this.buttonPrev.removeClass("disabled"),this.buttonNext.removeClass("disabled")))},updateControls:function(){this.updatePagination();this.checkNavigation();this.owlControls&&(this.options.items>=this.itemsAmount?this.owlControls.hide():this.owlControls.show())},destroyControls:function(){this.owlControls&&this.owlControls.remove()},next:function(a){if(this.isTransition)return!1;
this.currentItem+=!0===this.options.scrollPerPage?this.options.items:1;if(this.currentItem>this.maximumItem+(!0===this.options.scrollPerPage?this.options.items-1:0))if(!0===this.options.rewindNav)this.currentItem=0,a="rewind";else return this.currentItem=this.maximumItem,!1;this.goTo(this.currentItem,a)},prev:function(a){if(this.isTransition)return!1;this.currentItem=!0===this.options.scrollPerPage&&0<this.currentItem&&this.currentItem<this.options.items?0:this.currentItem-(!0===this.options.scrollPerPage?
this.options.items:1);if(0>this.currentItem)if(!0===this.options.rewindNav)this.currentItem=this.maximumItem,a="rewind";else return this.currentItem=0,!1;this.goTo(this.currentItem,a)},goTo:function(a,b,e){var c=this;if(c.isTransition)return!1;"function"===typeof c.options.beforeMove&&c.options.beforeMove.apply(this,[c.$elem]);a>=c.maximumItem?a=c.maximumItem:0>=a&&(a=0);c.currentItem=c.owl.currentItem=a;if(!1!==c.options.transitionStyle&&"drag"!==e&&1===c.options.items&&!0===c.browser.support3d)return c.swapSpeed(0),
!0===c.browser.support3d?c.transition3d(c.positionsInArray[a]):c.css2slide(c.positionsInArray[a],1),c.afterGo(),c.singleItemTransition(),!1;a=c.positionsInArray[a];!0===c.browser.support3d?(c.isCss3Finish=!1,!0===b?(c.swapSpeed("paginationSpeed"),g.setTimeout(function(){c.isCss3Finish=!0},c.options.paginationSpeed)):"rewind"===b?(c.swapSpeed(c.options.rewindSpeed),g.setTimeout(function(){c.isCss3Finish=!0},c.options.rewindSpeed)):(c.swapSpeed("slideSpeed"),g.setTimeout(function(){c.isCss3Finish=!0},
c.options.slideSpeed)),c.transition3d(a)):!0===b?c.css2slide(a,c.options.paginationSpeed):"rewind"===b?c.css2slide(a,c.options.rewindSpeed):c.css2slide(a,c.options.slideSpeed);c.afterGo()},jumpTo:function(a){"function"===typeof this.options.beforeMove&&this.options.beforeMove.apply(this,[this.$elem]);a>=this.maximumItem||-1===a?a=this.maximumItem:0>=a&&(a=0);this.swapSpeed(0);!0===this.browser.support3d?this.transition3d(this.positionsInArray[a]):this.css2slide(this.positionsInArray[a],1);this.currentItem=
this.owl.currentItem=a;this.afterGo()},afterGo:function(){this.prevArr.push(this.currentItem);this.prevItem=this.owl.prevItem=this.prevArr[this.prevArr.length-2];this.prevArr.shift(0);this.prevItem!==this.currentItem&&(this.checkPagination(),this.checkNavigation(),this.eachMoveUpdate(),!1!==this.options.autoPlay&&this.checkAp());"function"===typeof this.options.afterMove&&this.prevItem!==this.currentItem&&this.options.afterMove.apply(this,[this.$elem])},stop:function(){this.apStatus="stop";g.clearInterval(this.autoPlayInterval)},
checkAp:function(){"stop"!==this.apStatus&&this.play()},play:function(){var a=this;a.apStatus="play";if(!1===a.options.autoPlay)return!1;g.clearInterval(a.autoPlayInterval);a.autoPlayInterval=g.setInterval(function(){a.next(!0)},a.options.autoPlay)},swapSpeed:function(a){"slideSpeed"===a?this.$owlWrapper.css(this.addCssSpeed(this.options.slideSpeed)):"paginationSpeed"===a?this.$owlWrapper.css(this.addCssSpeed(this.options.paginationSpeed)):"string"!==typeof a&&this.$owlWrapper.css(this.addCssSpeed(a))},
addCssSpeed:function(a){return{"-webkit-transition":"all "+a+"ms ease","-moz-transition":"all "+a+"ms ease","-o-transition":"all "+a+"ms ease",transition:"all "+a+"ms ease"}},removeTransition:function(){return{"-webkit-transition":"","-moz-transition":"","-o-transition":"",transition:""}},doTranslate:function(a){return{"-webkit-transform":"translate3d("+a+"px, 0px, 0px)","-moz-transform":"translate3d("+a+"px, 0px, 0px)","-o-transform":"translate3d("+a+"px, 0px, 0px)","-ms-transform":"translate3d("+
a+"px, 0px, 0px)",transform:"translate3d("+a+"px, 0px,0px)"}},transition3d:function(a){this.$owlWrapper.css(this.doTranslate(a))},css2move:function(a){this.$owlWrapper.css({left:a})},css2slide:function(a,b){var e=this;e.isCssFinish=!1;e.$owlWrapper.stop(!0,!0).animate({left:a},{duration:b||e.options.slideSpeed,complete:function(){e.isCssFinish=!0}})},checkBrowser:function(){var a=k.createElement("div");a.style.cssText="  -moz-transform:translate3d(0px, 0px, 0px); -ms-transform:translate3d(0px, 0px, 0px); -o-transform:translate3d(0px, 0px, 0px); -webkit-transform:translate3d(0px, 0px, 0px); transform:translate3d(0px, 0px, 0px)";
a=a.style.cssText.match(/translate3d\(0px, 0px, 0px\)/g);this.browser={support3d:null!==a&&1===a.length,isTouch:"ontouchstart"in g||g.navigator.msMaxTouchPoints}},moveEvents:function(){if(!1!==this.options.mouseDrag||!1!==this.options.touchDrag)this.gestures(),this.disabledEvents()},eventTypes:function(){var a=["s","e","x"];this.ev_types={};!0===this.options.mouseDrag&&!0===this.options.touchDrag?a=["touchstart.owl mousedown.owl","touchmove.owl mousemove.owl","touchend.owl touchcancel.owl mouseup.owl"]:
!1===this.options.mouseDrag&&!0===this.options.touchDrag?a=["touchstart.owl","touchmove.owl","touchend.owl touchcancel.owl"]:!0===this.options.mouseDrag&&!1===this.options.touchDrag&&(a=["mousedown.owl","mousemove.owl","mouseup.owl"]);this.ev_types.start=a[0];this.ev_types.move=a[1];this.ev_types.end=a[2]},disabledEvents:function(){this.$elem.on("dragstart.owl",function(a){a.preventDefault()});this.$elem.on("mousedown.disableTextSelect",function(a){return f(a.target).is("input, textarea, select, option")})},
gestures:function(){function a(a){if(void 0!==a.touches)return{x:a.touches[0].pageX,y:a.touches[0].pageY};if(void 0===a.touches){if(void 0!==a.pageX)return{x:a.pageX,y:a.pageY};if(void 0===a.pageX)return{x:a.clientX,y:a.clientY}}}function b(a){"on"===a?(f(k).on(d.ev_types.move,e),f(k).on(d.ev_types.end,c)):"off"===a&&(f(k).off(d.ev_types.move),f(k).off(d.ev_types.end))}function e(b){b=b.originalEvent||b||g.event;d.newPosX=a(b).x-h.offsetX;d.newPosY=a(b).y-h.offsetY;d.newRelativeX=d.newPosX-h.relativePos;
"function"===typeof d.options.startDragging&&!0!==h.dragging&&0!==d.newRelativeX&&(h.dragging=!0,d.options.startDragging.apply(d,[d.$elem]));(8<d.newRelativeX||-8>d.newRelativeX)&&!0===d.browser.isTouch&&(void 0!==b.preventDefault?b.preventDefault():b.returnValue=!1,h.sliding=!0);(10<d.newPosY||-10>d.newPosY)&&!1===h.sliding&&f(k).off("touchmove.owl");d.newPosX=Math.max(Math.min(d.newPosX,d.newRelativeX/5),d.maximumPixels+d.newRelativeX/5);!0===d.browser.support3d?d.transition3d(d.newPosX):d.css2move(d.newPosX)}
function c(a){a=a.originalEvent||a||g.event;var c;a.target=a.target||a.srcElement;h.dragging=!1;!0!==d.browser.isTouch&&d.$owlWrapper.removeClass("grabbing");d.dragDirection=0>d.newRelativeX?d.owl.dragDirection="left":d.owl.dragDirection="right";0!==d.newRelativeX&&(c=d.getNewPosition(),d.goTo(c,!1,"drag"),h.targetElement===a.target&&!0!==d.browser.isTouch&&(f(a.target).on("click.disable",function(a){a.stopImmediatePropagation();a.stopPropagation();a.preventDefault();f(a.target).off("click.disable")}),
a=f._data(a.target,"events").click,c=a.pop(),a.splice(0,0,c)));b("off")}var d=this,h={offsetX:0,offsetY:0,baseElWidth:0,relativePos:0,position:null,minSwipe:null,maxSwipe:null,sliding:null,dargging:null,targetElement:null};d.isCssFinish=!0;d.$elem.on(d.ev_types.start,".owl-wrapper",function(c){c=c.originalEvent||c||g.event;var e;if(3===c.which)return!1;if(!(d.itemsAmount<=d.options.items)){if(!1===d.isCssFinish&&!d.options.dragBeforeAnimFinish||!1===d.isCss3Finish&&!d.options.dragBeforeAnimFinish)return!1;
!1!==d.options.autoPlay&&g.clearInterval(d.autoPlayInterval);!0===d.browser.isTouch||d.$owlWrapper.hasClass("grabbing")||d.$owlWrapper.addClass("grabbing");d.newPosX=0;d.newRelativeX=0;f(this).css(d.removeTransition());e=f(this).position();h.relativePos=e.left;h.offsetX=a(c).x-e.left;h.offsetY=a(c).y-e.top;b("on");h.sliding=!1;h.targetElement=c.target||c.srcElement}})},getNewPosition:function(){var a=this.closestItem();a>this.maximumItem?a=this.currentItem=this.maximumItem:0<=this.newPosX&&(this.currentItem=
a=0);return a},closestItem:function(){var a=this,b=!0===a.options.scrollPerPage?a.pagesInArray:a.positionsInArray,e=a.newPosX,c=null;f.each(b,function(d,g){e-a.itemWidth/20>b[d+1]&&e-a.itemWidth/20<g&&"left"===a.moveDirection()?(c=g,a.currentItem=!0===a.options.scrollPerPage?f.inArray(c,a.positionsInArray):d):e+a.itemWidth/20<g&&e+a.itemWidth/20>(b[d+1]||b[d]-a.itemWidth)&&"right"===a.moveDirection()&&(!0===a.options.scrollPerPage?(c=b[d+1]||b[b.length-1],a.currentItem=f.inArray(c,a.positionsInArray)):
(c=b[d+1],a.currentItem=d+1))});return a.currentItem},moveDirection:function(){var a;0>this.newRelativeX?(a="right",this.playDirection="next"):(a="left",this.playDirection="prev");return a},customEvents:function(){var a=this;a.$elem.on("owl.next",function(){a.next()});a.$elem.on("owl.prev",function(){a.prev()});a.$elem.on("owl.play",function(b,e){a.options.autoPlay=e;a.play();a.hoverStatus="play"});a.$elem.on("owl.stop",function(){a.stop();a.hoverStatus="stop"});a.$elem.on("owl.goTo",function(b,e){a.goTo(e)});
a.$elem.on("owl.jumpTo",function(b,e){a.jumpTo(e)})},stopOnHover:function(){var a=this;!0===a.options.stopOnHover&&!0!==a.browser.isTouch&&!1!==a.options.autoPlay&&(a.$elem.on("mouseover",function(){a.stop()}),a.$elem.on("mouseout",function(){"stop"!==a.hoverStatus&&a.play()}))},lazyLoad:function(){var a,b,e,c,d;if(!1===this.options.lazyLoad)return!1;for(a=0;a<this.itemsAmount;a+=1)b=f(this.$owlItems[a]),"loaded"!==b.data("owl-loaded")&&(e=b.data("owl-item"),c=b.find(".lazyOwl"),"string"!==typeof c.data("src")?
b.data("owl-loaded","loaded"):(void 0===b.data("owl-loaded")&&(c.hide(),b.addClass("loading").data("owl-loaded","checked")),(d=!0===this.options.lazyFollow?e>=this.currentItem:!0)&&e<this.currentItem+this.options.items&&c.length&&this.lazyPreload(b,c)))},lazyPreload:function(a,b){function e(){a.data("owl-loaded","loaded").removeClass("loading");b.removeAttr("data-src");"fade"===d.options.lazyEffect?b.fadeIn(400):b.show();"function"===typeof d.options.afterLazyLoad&&d.options.afterLazyLoad.apply(this,
[d.$elem])}function c(){f+=1;d.completeImg(b.get(0))||!0===k?e():100>=f?g.setTimeout(c,100):e()}var d=this,f=0,k;"DIV"===b.prop("tagName")?(b.css("background-image","url("+b.data("src")+")"),k=!0):b[0].src=b.data("src");c()},autoHeight:function(){function a(){var a=f(e.$owlItems[e.currentItem]).height();e.wrapperOuter.css("height",a+"px");e.wrapperOuter.hasClass("autoHeight")||g.setTimeout(function(){e.wrapperOuter.addClass("autoHeight")},0)}function b(){d+=1;e.completeImg(c.get(0))?a():100>=d?g.setTimeout(b,
100):e.wrapperOuter.css("height","")}var e=this,c=f(e.$owlItems[e.currentItem]).find("img"),d;void 0!==c.get(0)?(d=0,b()):a()},completeImg:function(a){return!a.complete||"undefined"!==typeof a.naturalWidth&&0===a.naturalWidth?!1:!0},onVisibleItems:function(){var a;!0===this.options.addClassActive&&this.$owlItems.removeClass("active");this.visibleItems=[];for(a=this.currentItem;a<this.currentItem+this.options.items;a+=1)this.visibleItems.push(a),!0===this.options.addClassActive&&f(this.$owlItems[a]).addClass("active");
this.owl.visibleItems=this.visibleItems},transitionTypes:function(a){this.outClass="owl-"+a+"-out";this.inClass="owl-"+a+"-in"},singleItemTransition:function(){var a=this,b=a.outClass,e=a.inClass,c=a.$owlItems.eq(a.currentItem),d=a.$owlItems.eq(a.prevItem),f=Math.abs(a.positionsInArray[a.currentItem])+a.positionsInArray[a.prevItem],g=Math.abs(a.positionsInArray[a.currentItem])+a.itemWidth/2;a.isTransition=!0;a.$owlWrapper.addClass("owl-origin").css({"-webkit-transform-origin":g+"px","-moz-perspective-origin":g+
"px","perspective-origin":g+"px"});d.css({position:"relative",left:f+"px"}).addClass(b).on("webkitAnimationEnd oAnimationEnd MSAnimationEnd animationend",function(){a.endPrev=!0;d.off("webkitAnimationEnd oAnimationEnd MSAnimationEnd animationend");a.clearTransStyle(d,b)});c.addClass(e).on("webkitAnimationEnd oAnimationEnd MSAnimationEnd animationend",function(){a.endCurrent=!0;c.off("webkitAnimationEnd oAnimationEnd MSAnimationEnd animationend");a.clearTransStyle(c,e)})},clearTransStyle:function(a,
b){a.css({position:"",left:""}).removeClass(b);this.endPrev&&this.endCurrent&&(this.$owlWrapper.removeClass("owl-origin"),this.isTransition=this.endCurrent=this.endPrev=!1)},owlStatus:function(){this.owl={userOptions:this.userOptions,baseElement:this.$elem,userItems:this.$userItems,owlItems:this.$owlItems,currentItem:this.currentItem,prevItem:this.prevItem,visibleItems:this.visibleItems,isTouch:this.browser.isTouch,browser:this.browser,dragDirection:this.dragDirection}},clearEvents:function(){this.$elem.off(".owl owl mousedown.disableTextSelect");
f(k).off(".owl owl");f(g).off("resize",this.resizer)},unWrap:function(){0!==this.$elem.children().length&&(this.$owlWrapper.unwrap(),this.$userItems.unwrap().unwrap(),this.owlControls&&this.owlControls.remove());this.clearEvents();this.$elem.attr("style",this.$elem.data("owl-originalStyles")||"").attr("class",this.$elem.data("owl-originalClasses"))},destroy:function(){this.stop();g.clearInterval(this.checkVisible);this.unWrap();this.$elem.removeData()},reinit:function(a){a=f.extend({},this.userOptions,
a);this.unWrap();this.init(a,this.$elem)},addItem:function(a,b){var e;if(!a)return!1;if(0===this.$elem.children().length)return this.$elem.append(a),this.setVars(),!1;this.unWrap();e=void 0===b||-1===b?-1:b;e>=this.$userItems.length||-1===e?this.$userItems.eq(-1).after(a):this.$userItems.eq(e).before(a);this.setVars()},removeItem:function(a){if(0===this.$elem.children().length)return!1;a=void 0===a||-1===a?-1:a;this.unWrap();this.$userItems.eq(a).remove();this.setVars()}};f.fn.owlCarousel=function(a){return this.each(function(){if(!0===
f(this).data("owl-init"))return!1;f(this).data("owl-init",!0);var b=Object.create(l);b.init(a,this);f.data(this,"owlCarousel",b)})};f.fn.owlCarousel.options={items:5,itemsCustom:!1,itemsDesktop:[1199,4],itemsDesktopSmall:[979,3],itemsTablet:[768,2],itemsTabletSmall:!1,itemsMobile:[479,1],singleItem:!1,itemsScaleUp:!1,slideSpeed:200,paginationSpeed:800,rewindSpeed:1E3,autoPlay:!1,stopOnHover:!1,navigation:!1,navigationText:["prev","next"],rewindNav:!0,scrollPerPage:!1,pagination:!0,paginationNumbers:!1,
responsive:!0,responsiveRefreshRate:200,responsiveBaseWidth:g,baseClass:"owl-carousel",theme:"owl-theme",lazyLoad:!1,lazyFollow:!0,lazyEffect:"fade",autoHeight:!1,jsonPath:!1,jsonSuccess:!1,dragBeforeAnimFinish:!0,mouseDrag:!0,touchDrag:!0,addClassActive:!1,transitionStyle:!1,beforeUpdate:!1,afterUpdate:!1,beforeInit:!1,afterInit:!1,beforeMove:!1,afterMove:!1,afterAction:!1,startDragging:!1,afterLazyLoad:!1}})(jQuery,window,document);


/* ! jQuery Validation Plugin - v1.14.0 - 6/30/2015
 * http://jqueryvalidation.org/
 * Copyright (c) 2015 J??rn Zaefferer; Licensed MIT */
!function(a){"function"==typeof define&&define.amd?define(["jquery"],a):a(jQuery)}(function(a){a.extend(a.fn,{validate:function(b){if(!this.length)return void(b&&b.debug&&window.console&&console.warn("Nothing selected, can't validate, returning nothing."));var c=a.data(this[0],"validator");return c?c:(this.attr("novalidate","novalidate"),c=new a.validator(b,this[0]),a.data(this[0],"validator",c),c.settings.onsubmit&&(this.on("click.validate",":submit",function(b){c.settings.submitHandler&&(c.submitButton=b.target),a(this).hasClass("cancel")&&(c.cancelSubmit=!0),void 0!==a(this).attr("formnovalidate")&&(c.cancelSubmit=!0)}),this.on("submit.validate",function(b){function d(){var d,e;return c.settings.submitHandler?(c.submitButton&&(d=a("<input type='hidden'/>").attr("name",c.submitButton.name).val(a(c.submitButton).val()).appendTo(c.currentForm)),e=c.settings.submitHandler.call(c,c.currentForm,b),c.submitButton&&d.remove(),void 0!==e?e:!1):!0}return c.settings.debug&&b.preventDefault(),c.cancelSubmit?(c.cancelSubmit=!1,d()):c.form()?c.pendingRequest?(c.formSubmitted=!0,!1):d():(c.focusInvalid(),!1)})),c)},valid:function(){var b,c,d;return a(this[0]).is("form")?b=this.validate().form():(d=[],b=!0,c=a(this[0].form).validate(),this.each(function(){b=c.element(this)&&b,d=d.concat(c.errorList)}),c.errorList=d),b},rules:function(b,c){var d,e,f,g,h,i,j=this[0];if(b)switch(d=a.data(j.form,"validator").settings,e=d.rules,f=a.validator.staticRules(j),b){case"add":a.extend(f,a.validator.normalizeRule(c)),delete f.messages,e[j.name]=f,c.messages&&(d.messages[j.name]=a.extend(d.messages[j.name],c.messages));break;case"remove":return c?(i={},a.each(c.split(/\s/),function(b,c){i[c]=f[c],delete f[c],"required"===c&&a(j).removeAttr("aria-required")}),i):(delete e[j.name],f)}return g=a.validator.normalizeRules(a.extend({},a.validator.classRules(j),a.validator.attributeRules(j),a.validator.dataRules(j),a.validator.staticRules(j)),j),g.required&&(h=g.required,delete g.required,g=a.extend({required:h},g),a(j).attr("aria-required","true")),g.remote&&(h=g.remote,delete g.remote,g=a.extend(g,{remote:h})),g}}),a.extend(a.expr[":"],{blank:function(b){return!a.trim(""+a(b).val())},filled:function(b){return!!a.trim(""+a(b).val())},unchecked:function(b){return!a(b).prop("checked")}}),a.validator=function(b,c){this.settings=a.extend(!0,{},a.validator.defaults,b),this.currentForm=c,this.init()},a.validator.format=function(b,c){return 1===arguments.length?function(){var c=a.makeArray(arguments);return c.unshift(b),a.validator.format.apply(this,c)}:(arguments.length>2&&c.constructor!==Array&&(c=a.makeArray(arguments).slice(1)),c.constructor!==Array&&(c=[c]),a.each(c,function(a,c){b=b.replace(new RegExp("\\{"+a+"\\}","g"),function(){return c})}),b)},a.extend(a.validator,{defaults:{messages:{},groups:{},rules:{},errorClass:"error",validClass:"valid",errorElement:"label",focusCleanup:!1,focusInvalid:!0,errorContainer:a([]),errorLabelContainer:a([]),onsubmit:!0,ignore:":hidden",ignoreTitle:!1,onfocusin:function(a){this.lastActive=a,this.settings.focusCleanup&&(this.settings.unhighlight&&this.settings.unhighlight.call(this,a,this.settings.errorClass,this.settings.validClass),this.hideThese(this.errorsFor(a)))},onfocusout:function(a){this.checkable(a)||!(a.name in this.submitted)&&this.optional(a)||this.element(a)},onkeyup:function(b,c){var d=[16,17,18,20,35,36,37,38,39,40,45,144,225];9===c.which&&""===this.elementValue(b)||-1!==a.inArray(c.keyCode,d)||(b.name in this.submitted||b===this.lastElement)&&this.element(b)},onclick:function(a){a.name in this.submitted?this.element(a):a.parentNode.name in this.submitted&&this.element(a.parentNode)},highlight:function(b,c,d){"radio"===b.type?this.findByName(b.name).addClass(c).removeClass(d):a(b).addClass(c).removeClass(d)},unhighlight:function(b,c,d){"radio"===b.type?this.findByName(b.name).removeClass(c).addClass(d):a(b).removeClass(c).addClass(d)}},setDefaults:function(b){a.extend(a.validator.defaults,b)},messages:{required:"This field is required.",remote:"Please fix this field.",email:"Please enter a valid email address.",url:"Please enter a valid URL.",date:"Please enter a valid date.",dateISO:"Please enter a valid date ( ISO ).",number:"Please enter a valid number.",digits:"Please enter only digits.",creditcard:"Please enter a valid credit card number.",equalTo:"Please enter the same value again.",maxlength:a.validator.format("Please enter no more than {0} characters."),minlength:a.validator.format("Please enter at least {0} characters."),rangelength:a.validator.format("Please enter a value between {0} and {1} characters long."),range:a.validator.format("Please enter a value between {0} and {1}."),max:a.validator.format("Please enter a value less than or equal to {0}."),min:a.validator.format("Please enter a value greater than or equal to {0}.")},autoCreateRanges:!1,prototype:{init:function(){function b(b){var c=a.data(this.form,"validator"),d="on"+b.type.replace(/^validate/,""),e=c.settings;e[d]&&!a(this).is(e.ignore)&&e[d].call(c,this,b)}this.labelContainer=a(this.settings.errorLabelContainer),this.errorContext=this.labelContainer.length&&this.labelContainer||a(this.currentForm),this.containers=a(this.settings.errorContainer).add(this.settings.errorLabelContainer),this.submitted={},this.valueCache={},this.pendingRequest=0,this.pending={},this.invalid={},this.reset();var c,d=this.groups={};a.each(this.settings.groups,function(b,c){"string"==typeof c&&(c=c.split(/\s/)),a.each(c,function(a,c){d[c]=b})}),c=this.settings.rules,a.each(c,function(b,d){c[b]=a.validator.normalizeRule(d)}),a(this.currentForm).on("focusin.validate focusout.validate keyup.validate",":text, [type='password'], [type='file'], select, textarea, [type='number'], [type='search'], [type='tel'], [type='url'], [type='email'], [type='datetime'], [type='date'], [type='month'], [type='week'], [type='time'], [type='datetime-local'], [type='range'], [type='color'], [type='radio'], [type='checkbox']",b).on("click.validate","select, option, [type='radio'], [type='checkbox']",b),this.settings.invalidHandler&&a(this.currentForm).on("invalid-form.validate",this.settings.invalidHandler),a(this.currentForm).find("[required], [data-rule-required], .required").attr("aria-required","true")},form:function(){return this.checkForm(),a.extend(this.submitted,this.errorMap),this.invalid=a.extend({},this.errorMap),this.valid()||a(this.currentForm).triggerHandler("invalid-form",[this]),this.showErrors(),this.valid()},checkForm:function(){this.prepareForm();for(var a=0,b=this.currentElements=this.elements();b[a];a++)this.check(b[a]);return this.valid()},element:function(b){var c=this.clean(b),d=this.validationTargetFor(c),e=!0;return this.lastElement=d,void 0===d?delete this.invalid[c.name]:(this.prepareElement(d),this.currentElements=a(d),e=this.check(d)!==!1,e?delete this.invalid[d.name]:this.invalid[d.name]=!0),a(b).attr("aria-invalid",!e),this.numberOfInvalids()||(this.toHide=this.toHide.add(this.containers)),this.showErrors(),e},showErrors:function(b){if(b){a.extend(this.errorMap,b),this.errorList=[];for(var c in b)this.errorList.push({message:b[c],element:this.findByName(c)[0]});this.successList=a.grep(this.successList,function(a){return!(a.name in b)})}this.settings.showErrors?this.settings.showErrors.call(this,this.errorMap,this.errorList):this.defaultShowErrors()},resetForm:function(){a.fn.resetForm&&a(this.currentForm).resetForm(),this.submitted={},this.lastElement=null,this.prepareForm(),this.hideErrors();var b,c=this.elements().removeData("previousValue").removeAttr("aria-invalid");if(this.settings.unhighlight)for(b=0;c[b];b++)this.settings.unhighlight.call(this,c[b],this.settings.errorClass,"");else c.removeClass(this.settings.errorClass)},numberOfInvalids:function(){return this.objectLength(this.invalid)},objectLength:function(a){var b,c=0;for(b in a)c++;return c},hideErrors:function(){this.hideThese(this.toHide)},hideThese:function(a){a.not(this.containers).text(""),this.addWrapper(a).hide()},valid:function(){return 0===this.size()},size:function(){return this.errorList.length},focusInvalid:function(){if(this.settings.focusInvalid)try{a(this.findLastActive()||this.errorList.length&&this.errorList[0].element||[]).filter(":visible").focus().trigger("focusin")}catch(b){}},findLastActive:function(){var b=this.lastActive;return b&&1===a.grep(this.errorList,function(a){return a.element.name===b.name}).length&&b},elements:function(){var b=this,c={};return a(this.currentForm).find("input, select, textarea").not(":submit, :reset, :image, :disabled").not(this.settings.ignore).filter(function(){return!this.name&&b.settings.debug&&window.console&&console.error("%o has no name assigned",this),this.name in c||!b.objectLength(a(this).rules())?!1:(c[this.name]=!0,!0)})},clean:function(b){return a(b)[0]},errors:function(){var b=this.settings.errorClass.split(" ").join(".");return a(this.settings.errorElement+"."+b,this.errorContext)},reset:function(){this.successList=[],this.errorList=[],this.errorMap={},this.toShow=a([]),this.toHide=a([]),this.currentElements=a([])},prepareForm:function(){this.reset(),this.toHide=this.errors().add(this.containers)},prepareElement:function(a){this.reset(),this.toHide=this.errorsFor(a)},elementValue:function(b){var c,d=a(b),e=b.type;return"radio"===e||"checkbox"===e?this.findByName(b.name).filter(":checked").val():"number"===e&&"undefined"!=typeof b.validity?b.validity.badInput?!1:d.val():(c=d.val(),"string"==typeof c?c.replace(/\r/g,""):c)},check:function(b){b=this.validationTargetFor(this.clean(b));var c,d,e,f=a(b).rules(),g=a.map(f,function(a,b){return b}).length,h=!1,i=this.elementValue(b);for(d in f){e={method:d,parameters:f[d]};try{if(c=a.validator.methods[d].call(this,i,b,e.parameters),"dependency-mismatch"===c&&1===g){h=!0;continue}if(h=!1,"pending"===c)return void(this.toHide=this.toHide.not(this.errorsFor(b)));if(!c)return this.formatAndAdd(b,e),!1}catch(j){throw this.settings.debug&&window.console&&console.log("Exception occurred when checking element "+b.id+", check the '"+e.method+"' method.",j),j instanceof TypeError&&(j.message+=".  Exception occurred when checking element "+b.id+", check the '"+e.method+"' method."),j}}if(!h)return this.objectLength(f)&&this.successList.push(b),!0},customDataMessage:function(b,c){return a(b).data("msg"+c.charAt(0).toUpperCase()+c.substring(1).toLowerCase())||a(b).data("msg")},customMessage:function(a,b){var c=this.settings.messages[a];return c&&(c.constructor===String?c:c[b])},findDefined:function(){for(var a=0;a<arguments.length;a++)if(void 0!==arguments[a])return arguments[a];return void 0},defaultMessage:function(b,c){return this.findDefined(this.customMessage(b.name,c),this.customDataMessage(b,c),!this.settings.ignoreTitle&&b.title||void 0,a.validator.messages[c],"<strong>Warning: No message defined for "+b.name+"</strong>")},formatAndAdd:function(b,c){var d=this.defaultMessage(b,c.method),e=/\$?\{(\d+)\}/g;"function"==typeof d?d=d.call(this,c.parameters,b):e.test(d)&&(d=a.validator.format(d.replace(e,"{$1}"),c.parameters)),this.errorList.push({message:d,element:b,method:c.method}),this.errorMap[b.name]=d,this.submitted[b.name]=d},addWrapper:function(a){return this.settings.wrapper&&(a=a.add(a.parent(this.settings.wrapper))),a},defaultShowErrors:function(){var a,b,c;for(a=0;this.errorList[a];a++)c=this.errorList[a],this.settings.highlight&&this.settings.highlight.call(this,c.element,this.settings.errorClass,this.settings.validClass),this.showLabel(c.element,c.message);if(this.errorList.length&&(this.toShow=this.toShow.add(this.containers)),this.settings.success)for(a=0;this.successList[a];a++)this.showLabel(this.successList[a]);if(this.settings.unhighlight)for(a=0,b=this.validElements();b[a];a++)this.settings.unhighlight.call(this,b[a],this.settings.errorClass,this.settings.validClass);this.toHide=this.toHide.not(this.toShow),this.hideErrors(),this.addWrapper(this.toShow).show()},validElements:function(){return this.currentElements.not(this.invalidElements())},invalidElements:function(){return a(this.errorList).map(function(){return this.element})},showLabel:function(b,c){var d,e,f,g=this.errorsFor(b),h=this.idOrName(b),i=a(b).attr("aria-describedby");g.length?(g.removeClass(this.settings.validClass).addClass(this.settings.errorClass),g.html(c)):(g=a("<"+this.settings.errorElement+">").attr("id",h+"-error").addClass(this.settings.errorClass).html(c||""),d=g,this.settings.wrapper&&(d=g.hide().show().wrap("<"+this.settings.wrapper+"/>").parent()),this.labelContainer.length?this.labelContainer.append(d):this.settings.errorPlacement?this.settings.errorPlacement(d,a(b)):d.insertAfter(b),g.is("label")?g.attr("for",h):0===g.parents("label[for='"+h+"']").length&&(f=g.attr("id").replace(/(:|\.|\[|\]|\$)/g,"\\$1"),i?i.match(new RegExp("\\b"+f+"\\b"))||(i+=" "+f):i=f,a(b).attr("aria-describedby",i),e=this.groups[b.name],e&&a.each(this.groups,function(b,c){c===e&&a("[name='"+b+"']",this.currentForm).attr("aria-describedby",g.attr("id"))}))),!c&&this.settings.success&&(g.text(""),"string"==typeof this.settings.success?g.addClass(this.settings.success):this.settings.success(g,b)),this.toShow=this.toShow.add(g)},errorsFor:function(b){var c=this.idOrName(b),d=a(b).attr("aria-describedby"),e="label[for='"+c+"'], label[for='"+c+"'] *";return d&&(e=e+", #"+d.replace(/\s+/g,", #")),this.errors().filter(e)},idOrName:function(a){return this.groups[a.name]||(this.checkable(a)?a.name:a.id||a.name)},validationTargetFor:function(b){return this.checkable(b)&&(b=this.findByName(b.name)),a(b).not(this.settings.ignore)[0]},checkable:function(a){return/radio|checkbox/i.test(a.type)},findByName:function(b){return a(this.currentForm).find("[name='"+b+"']")},getLength:function(b,c){switch(c.nodeName.toLowerCase()){case"select":return a("option:selected",c).length;case"input":if(this.checkable(c))return this.findByName(c.name).filter(":checked").length}return b.length},depend:function(a,b){return this.dependTypes[typeof a]?this.dependTypes[typeof a](a,b):!0},dependTypes:{"boolean":function(a){return a},string:function(b,c){return!!a(b,c.form).length},"function":function(a,b){return a(b)}},optional:function(b){var c=this.elementValue(b);return!a.validator.methods.required.call(this,c,b)&&"dependency-mismatch"},startRequest:function(a){this.pending[a.name]||(this.pendingRequest++,this.pending[a.name]=!0)},stopRequest:function(b,c){this.pendingRequest--,this.pendingRequest<0&&(this.pendingRequest=0),delete this.pending[b.name],c&&0===this.pendingRequest&&this.formSubmitted&&this.form()?(a(this.currentForm).submit(),this.formSubmitted=!1):!c&&0===this.pendingRequest&&this.formSubmitted&&(a(this.currentForm).triggerHandler("invalid-form",[this]),this.formSubmitted=!1)},previousValue:function(b){return a.data(b,"previousValue")||a.data(b,"previousValue",{old:null,valid:!0,message:this.defaultMessage(b,"remote")})},destroy:function(){this.resetForm(),a(this.currentForm).off(".validate").removeData("validator")}},classRuleSettings:{required:{required:!0},email:{email:!0},url:{url:!0},date:{date:!0},dateISO:{dateISO:!0},number:{number:!0},digits:{digits:!0},creditcard:{creditcard:!0}},addClassRules:function(b,c){b.constructor===String?this.classRuleSettings[b]=c:a.extend(this.classRuleSettings,b)},classRules:function(b){var c={},d=a(b).attr("class");return d&&a.each(d.split(" "),function(){this in a.validator.classRuleSettings&&a.extend(c,a.validator.classRuleSettings[this])}),c},normalizeAttributeRule:function(a,b,c,d){/min|max/.test(c)&&(null===b||/number|range|text/.test(b))&&(d=Number(d),isNaN(d)&&(d=void 0)),d||0===d?a[c]=d:b===c&&"range"!==b&&(a[c]=!0)},attributeRules:function(b){var c,d,e={},f=a(b),g=b.getAttribute("type");for(c in a.validator.methods)"required"===c?(d=b.getAttribute(c),""===d&&(d=!0),d=!!d):d=f.attr(c),this.normalizeAttributeRule(e,g,c,d);return e.maxlength&&/-1|2147483647|524288/.test(e.maxlength)&&delete e.maxlength,e},dataRules:function(b){var c,d,e={},f=a(b),g=b.getAttribute("type");for(c in a.validator.methods)d=f.data("rule"+c.charAt(0).toUpperCase()+c.substring(1).toLowerCase()),this.normalizeAttributeRule(e,g,c,d);return e},staticRules:function(b){var c={},d=a.data(b.form,"validator");return d.settings.rules&&(c=a.validator.normalizeRule(d.settings.rules[b.name])||{}),c},normalizeRules:function(b,c){return a.each(b,function(d,e){if(e===!1)return void delete b[d];if(e.param||e.depends){var f=!0;switch(typeof e.depends){case"string":f=!!a(e.depends,c.form).length;break;case"function":f=e.depends.call(c,c)}f?b[d]=void 0!==e.param?e.param:!0:delete b[d]}}),a.each(b,function(d,e){b[d]=a.isFunction(e)?e(c):e}),a.each(["minlength","maxlength"],function(){b[this]&&(b[this]=Number(b[this]))}),a.each(["rangelength","range"],function(){var c;b[this]&&(a.isArray(b[this])?b[this]=[Number(b[this][0]),Number(b[this][1])]:"string"==typeof b[this]&&(c=b[this].replace(/[\[\]]/g,"").split(/[\s,]+/),b[this]=[Number(c[0]),Number(c[1])]))}),a.validator.autoCreateRanges&&(null!=b.min&&null!=b.max&&(b.range=[b.min,b.max],delete b.min,delete b.max),null!=b.minlength&&null!=b.maxlength&&(b.rangelength=[b.minlength,b.maxlength],delete b.minlength,delete b.maxlength)),b},normalizeRule:function(b){if("string"==typeof b){var c={};a.each(b.split(/\s/),function(){c[this]=!0}),b=c}return b},addMethod:function(b,c,d){a.validator.methods[b]=c,a.validator.messages[b]=void 0!==d?d:a.validator.messages[b],c.length<3&&a.validator.addClassRules(b,a.validator.normalizeRule(b))},methods:{required:function(b,c,d){if(!this.depend(d,c))return"dependency-mismatch";if("select"===c.nodeName.toLowerCase()){var e=a(c).val();return e&&e.length>0}return this.checkable(c)?this.getLength(b,c)>0:b.length>0},email:function(a,b){return this.optional(b)||/^[a-zA-Z0-9.!#$%&'*+\/=?^_`{|}~-]+@[a-zA-Z0-9](?:[a-zA-Z0-9-]{0,61}[a-zA-Z0-9])?(?:\.[a-zA-Z0-9](?:[a-zA-Z0-9-]{0,61}[a-zA-Z0-9])?)*$/.test(a)},url:function(a,b){return this.optional(b)||/^(?:(?:(?:https?|ftp):)?\/\/)(?:\S+(?::\S*)?@)?(?:(?!(?:10|127)(?:\.\d{1,3}){3})(?!(?:169\.254|192\.168)(?:\.\d{1,3}){2})(?!172\.(?:1[6-9]|2\d|3[0-1])(?:\.\d{1,3}){2})(?:[1-9]\d?|1\d\d|2[01]\d|22[0-3])(?:\.(?:1?\d{1,2}|2[0-4]\d|25[0-5])){2}(?:\.(?:[1-9]\d?|1\d\d|2[0-4]\d|25[0-4]))|(?:(?:[a-z\u00a1-\uffff0-9]-*)*[a-z\u00a1-\uffff0-9]+)(?:\.(?:[a-z\u00a1-\uffff0-9]-*)*[a-z\u00a1-\uffff0-9]+)*(?:\.(?:[a-z\u00a1-\uffff]{2,})).?)(?::\d{2,5})?(?:[/?#]\S*)?$/i.test(a)},date:function(a,b){return this.optional(b)||!/Invalid|NaN/.test(new Date(a).toString())},dateISO:function(a,b){return this.optional(b)||/^\d{4}[\/\-](0?[1-9]|1[012])[\/\-](0?[1-9]|[12][0-9]|3[01])$/.test(a)},number:function(a,b){return this.optional(b)||/^(?:-?\d+|-?\d{1,3}(?:,\d{3})+)?(?:\.\d+)?$/.test(a)},digits:function(a,b){return this.optional(b)||/^\d+$/.test(a)},creditcard:function(a,b){if(this.optional(b))return"dependency-mismatch";if(/[^0-9 \-]+/.test(a))return!1;var c,d,e=0,f=0,g=!1;if(a=a.replace(/\D/g,""),a.length<13||a.length>19)return!1;for(c=a.length-1;c>=0;c--)d=a.charAt(c),f=parseInt(d,10),g&&(f*=2)>9&&(f-=9),e+=f,g=!g;return e%10===0},minlength:function(b,c,d){var e=a.isArray(b)?b.length:this.getLength(b,c);return this.optional(c)||e>=d},maxlength:function(b,c,d){var e=a.isArray(b)?b.length:this.getLength(b,c);return this.optional(c)||d>=e},rangelength:function(b,c,d){var e=a.isArray(b)?b.length:this.getLength(b,c);return this.optional(c)||e>=d[0]&&e<=d[1]},min:function(a,b,c){return this.optional(b)||a>=c},max:function(a,b,c){return this.optional(b)||c>=a},range:function(a,b,c){return this.optional(b)||a>=c[0]&&a<=c[1]},equalTo:function(b,c,d){var e=a(d);return this.settings.onfocusout&&e.off(".validate-equalTo").on("blur.validate-equalTo",function(){a(c).valid()}),b===e.val()},remote:function(b,c,d){if(this.optional(c))return"dependency-mismatch";var e,f,g=this.previousValue(c);return this.settings.messages[c.name]||(this.settings.messages[c.name]={}),g.originalMessage=this.settings.messages[c.name].remote,this.settings.messages[c.name].remote=g.message,d="string"==typeof d&&{url:d}||d,g.old===b?g.valid:(g.old=b,e=this,this.startRequest(c),f={},f[c.name]=b,a.ajax(a.extend(!0,{mode:"abort",port:"validate"+c.name,dataType:"json",data:f,context:e.currentForm,success:function(d){var f,h,i,j=d===!0||"true"===d;e.settings.messages[c.name].remote=g.originalMessage,j?(i=e.formSubmitted,e.prepareElement(c),e.formSubmitted=i,e.successList.push(c),delete e.invalid[c.name],e.showErrors()):(f={},h=d||e.defaultMessage(c,"remote"),f[c.name]=g.message=a.isFunction(h)?h(b):h,e.invalid[c.name]=!0,e.showErrors(f)),g.valid=j,e.stopRequest(c,j)}},d)),"pending")}}});var b,c={};a.ajaxPrefilter?a.ajaxPrefilter(function(a,b,d){var e=a.port;"abort"===a.mode&&(c[e]&&c[e].abort(),c[e]=d)}):(b=a.ajax,a.ajax=function(d){var e=("mode"in d?d:a.ajaxSettings).mode,f=("port"in d?d:a.ajaxSettings).port;return"abort"===e?(c[f]&&c[f].abort(),c[f]=b.apply(this,arguments),c[f]):b.apply(this,arguments)})});


/*!
Waypoints - 4.0.0
Copyright ?? 2011-2015 Caleb Troughton
Licensed under the MIT license.
https://github.com/imakewebthings/waypoints/blog/master/licenses.txt
*/
!function(){"use strict";function t(o){if(!o)throw new Error("No options passed to Waypoint constructor");if(!o.element)throw new Error("No element option passed to Waypoint constructor");if(!o.handler)throw new Error("No handler option passed to Waypoint constructor");this.key="waypoint-"+e,this.options=t.Adapter.extend({},t.defaults,o),this.element=this.options.element,this.adapter=new t.Adapter(this.element),this.callback=o.handler,this.axis=this.options.horizontal?"horizontal":"vertical",this.enabled=this.options.enabled,this.triggerPoint=null,this.group=t.Group.findOrCreate({name:this.options.group,axis:this.axis}),this.context=t.Context.findOrCreateByElement(this.options.context),t.offsetAliases[this.options.offset]&&(this.options.offset=t.offsetAliases[this.options.offset]),this.group.add(this),this.context.add(this),i[this.key]=this,e+=1}var e=0,i={};t.prototype.queueTrigger=function(t){this.group.queueTrigger(this,t)},t.prototype.trigger=function(t){this.enabled&&this.callback&&this.callback.apply(this,t)},t.prototype.destroy=function(){this.context.remove(this),this.group.remove(this),delete i[this.key]},t.prototype.disable=function(){return this.enabled=!1,this},t.prototype.enable=function(){return this.context.refresh(),this.enabled=!0,this},t.prototype.next=function(){return this.group.next(this)},t.prototype.previous=function(){return this.group.previous(this)},t.invokeAll=function(t){var e=[];for(var o in i)e.push(i[o]);for(var n=0,r=e.length;r>n;n++)e[n][t]()},t.destroyAll=function(){t.invokeAll("destroy")},t.disableAll=function(){t.invokeAll("disable")},t.enableAll=function(){t.invokeAll("enable")},t.refreshAll=function(){t.Context.refreshAll()},t.viewportHeight=function(){return window.innerHeight||document.documentElement.clientHeight},t.viewportWidth=function(){return document.documentElement.clientWidth},t.adapters=[],t.defaults={context:window,continuous:!0,enabled:!0,group:"default",horizontal:!1,offset:0},t.offsetAliases={"bottom-in-view":function(){return this.context.innerHeight()-this.adapter.outerHeight()},"right-in-view":function(){return this.context.innerWidth()-this.adapter.outerWidth()}},window.Waypoint=t}(),function(){"use strict";function t(t){window.setTimeout(t,1e3/60)}function e(t){this.element=t,this.Adapter=n.Adapter,this.adapter=new this.Adapter(t),this.key="waypoint-context-"+i,this.didScroll=!1,this.didResize=!1,this.oldScroll={x:this.adapter.scrollLeft(),y:this.adapter.scrollTop()},this.waypoints={vertical:{},horizontal:{}},t.waypointContextKey=this.key,o[t.waypointContextKey]=this,i+=1,this.createThrottledScrollHandler(),this.createThrottledResizeHandler()}var i=0,o={},n=window.Waypoint,r=window.onload;e.prototype.add=function(t){var e=t.options.horizontal?"horizontal":"vertical";this.waypoints[e][t.key]=t,this.refresh()},e.prototype.checkEmpty=function(){var t=this.Adapter.isEmptyObject(this.waypoints.horizontal),e=this.Adapter.isEmptyObject(this.waypoints.vertical);t&&e&&(this.adapter.off(".waypoints"),delete o[this.key])},e.prototype.createThrottledResizeHandler=function(){function t(){e.handleResize(),e.didResize=!1}var e=this;this.adapter.on("resize.waypoints",function(){e.didResize||(e.didResize=!0,n.requestAnimationFrame(t))})},e.prototype.createThrottledScrollHandler=function(){function t(){e.handleScroll(),e.didScroll=!1}var e=this;this.adapter.on("scroll.waypoints",function(){(!e.didScroll||n.isTouch)&&(e.didScroll=!0,n.requestAnimationFrame(t))})},e.prototype.handleResize=function(){n.Context.refreshAll()},e.prototype.handleScroll=function(){var t={},e={horizontal:{newScroll:this.adapter.scrollLeft(),oldScroll:this.oldScroll.x,forward:"right",backward:"left"},vertical:{newScroll:this.adapter.scrollTop(),oldScroll:this.oldScroll.y,forward:"down",backward:"up"}};for(var i in e){var o=e[i],n=o.newScroll>o.oldScroll,r=n?o.forward:o.backward;for(var s in this.waypoints[i]){var a=this.waypoints[i][s],l=o.oldScroll<a.triggerPoint,h=o.newScroll>=a.triggerPoint,p=l&&h,u=!l&&!h;(p||u)&&(a.queueTrigger(r),t[a.group.id]=a.group)}}for(var c in t)t[c].flushTriggers();this.oldScroll={x:e.horizontal.newScroll,y:e.vertical.newScroll}},e.prototype.innerHeight=function(){return this.element==this.element.window?n.viewportHeight():this.adapter.innerHeight()},e.prototype.remove=function(t){delete this.waypoints[t.axis][t.key],this.checkEmpty()},e.prototype.innerWidth=function(){return this.element==this.element.window?n.viewportWidth():this.adapter.innerWidth()},e.prototype.destroy=function(){var t=[];for(var e in this.waypoints)for(var i in this.waypoints[e])t.push(this.waypoints[e][i]);for(var o=0,n=t.length;n>o;o++)t[o].destroy()},e.prototype.refresh=function(){var t,e=this.element==this.element.window,i=e?void 0:this.adapter.offset(),o={};this.handleScroll(),t={horizontal:{contextOffset:e?0:i.left,contextScroll:e?0:this.oldScroll.x,contextDimension:this.innerWidth(),oldScroll:this.oldScroll.x,forward:"right",backward:"left",offsetProp:"left"},vertical:{contextOffset:e?0:i.top,contextScroll:e?0:this.oldScroll.y,contextDimension:this.innerHeight(),oldScroll:this.oldScroll.y,forward:"down",backward:"up",offsetProp:"top"}};for(var r in t){var s=t[r];for(var a in this.waypoints[r]){var l,h,p,u,c,d=this.waypoints[r][a],f=d.options.offset,w=d.triggerPoint,y=0,g=null==w;d.element!==d.element.window&&(y=d.adapter.offset()[s.offsetProp]),"function"==typeof f?f=f.apply(d):"string"==typeof f&&(f=parseFloat(f),d.options.offset.indexOf("%")>-1&&(f=Math.ceil(s.contextDimension*f/100))),l=s.contextScroll-s.contextOffset,d.triggerPoint=y+l-f,h=w<s.oldScroll,p=d.triggerPoint>=s.oldScroll,u=h&&p,c=!h&&!p,!g&&u?(d.queueTrigger(s.backward),o[d.group.id]=d.group):!g&&c?(d.queueTrigger(s.forward),o[d.group.id]=d.group):g&&s.oldScroll>=d.triggerPoint&&(d.queueTrigger(s.forward),o[d.group.id]=d.group)}}return n.requestAnimationFrame(function(){for(var t in o)o[t].flushTriggers()}),this},e.findOrCreateByElement=function(t){return e.findByElement(t)||new e(t)},e.refreshAll=function(){for(var t in o)o[t].refresh()},e.findByElement=function(t){return o[t.waypointContextKey]},window.onload=function(){r&&r(),e.refreshAll()},n.requestAnimationFrame=function(e){var i=window.requestAnimationFrame||window.mozRequestAnimationFrame||window.webkitRequestAnimationFrame||t;i.call(window,e)},n.Context=e}(),function(){"use strict";function t(t,e){return t.triggerPoint-e.triggerPoint}function e(t,e){return e.triggerPoint-t.triggerPoint}function i(t){this.name=t.name,this.axis=t.axis,this.id=this.name+"-"+this.axis,this.waypoints=[],this.clearTriggerQueues(),o[this.axis][this.name]=this}var o={vertical:{},horizontal:{}},n=window.Waypoint;i.prototype.add=function(t){this.waypoints.push(t)},i.prototype.clearTriggerQueues=function(){this.triggerQueues={up:[],down:[],left:[],right:[]}},i.prototype.flushTriggers=function(){for(var i in this.triggerQueues){var o=this.triggerQueues[i],n="up"===i||"left"===i;o.sort(n?e:t);for(var r=0,s=o.length;s>r;r+=1){var a=o[r];(a.options.continuous||r===o.length-1)&&a.trigger([i])}}this.clearTriggerQueues()},i.prototype.next=function(e){this.waypoints.sort(t);var i=n.Adapter.inArray(e,this.waypoints),o=i===this.waypoints.length-1;return o?null:this.waypoints[i+1]},i.prototype.previous=function(e){this.waypoints.sort(t);var i=n.Adapter.inArray(e,this.waypoints);return i?this.waypoints[i-1]:null},i.prototype.queueTrigger=function(t,e){this.triggerQueues[e].push(t)},i.prototype.remove=function(t){var e=n.Adapter.inArray(t,this.waypoints);e>-1&&this.waypoints.splice(e,1)},i.prototype.first=function(){return this.waypoints[0]},i.prototype.last=function(){return this.waypoints[this.waypoints.length-1]},i.findOrCreate=function(t){return o[t.axis][t.name]||new i(t)},n.Group=i}(),function(){"use strict";function t(t){this.$element=e(t)}var e=window.jQuery,i=window.Waypoint;e.each(["innerHeight","innerWidth","off","offset","on","outerHeight","outerWidth","scrollLeft","scrollTop"],function(e,i){t.prototype[i]=function(){var t=Array.prototype.slice.call(arguments);return this.$element[i].apply(this.$element,t)}}),e.each(["extend","inArray","isEmptyObject"],function(i,o){t[o]=e[o]}),i.adapters.push({name:"jquery",Adapter:t}),i.Adapter=t}(),function(){"use strict";function t(t){return function(){var i=[],o=arguments[0];return t.isFunction(arguments[0])&&(o=t.extend({},arguments[1]),o.handler=arguments[0]),this.each(function(){var n=t.extend({},o,{element:this});"string"==typeof n.context&&(n.context=t(this).closest(n.context)[0]),i.push(new e(n))}),i}}var e=window.Waypoint;window.jQuery&&(window.jQuery.fn.waypoint=t(window.jQuery)),window.Zepto&&(window.Zepto.fn.waypoint=t(window.Zepto))}();


/* ! Magnific Popup - v1.0.0 - 2015-09-17
 * http://dimsemenov.com/plugins/magnific-popup/
 * Copyright (c) 2015 Dmitry Semenov; 
 */
!function(a){"function"==typeof define&&define.amd?define(["jquery"],a):a("object"==typeof exports?require("jquery"):window.jQuery||window.Zepto)}(function(a){var b,c,d,e,f,g,h="Close",i="BeforeClose",j="AfterClose",k="BeforeAppend",l="MarkupParse",m="Open",n="Change",o="mfp",p="."+o,q="mfp-ready",r="mfp-removing",s="mfp-prevent-close",t=function(){},u=!!window.jQuery,v=a(window),w=function(a,c){b.ev.on(o+a+p,c)},x=function(b,c,d,e){var f=document.createElement("div");return f.className="mfp-"+b,d&&(f.innerHTML=d),e?c&&c.appendChild(f):(f=a(f),c&&f.appendTo(c)),f},y=function(c,d){b.ev.triggerHandler(o+c,d),b.st.callbacks&&(c=c.charAt(0).toLowerCase()+c.slice(1),b.st.callbacks[c]&&b.st.callbacks[c].apply(b,a.isArray(d)?d:[d]))},z=function(c){return c===g&&b.currTemplate.closeBtn||(b.currTemplate.closeBtn=a(b.st.closeMarkup.replace("%title%",b.st.tClose)),g=c),b.currTemplate.closeBtn},A=function(){a.magnificPopup.instance||(b=new t,b.init(),a.magnificPopup.instance=b)},B=function(){var a=document.createElement("p").style,b=["ms","O","Moz","Webkit"];if(void 0!==a.transition)return!0;for(;b.length;)if(b.pop()+"Transition"in a)return!0;return!1};t.prototype={constructor:t,init:function(){var c=navigator.appVersion;b.isIE7=-1!==c.indexOf("MSIE 7."),b.isIE8=-1!==c.indexOf("MSIE 8."),b.isLowIE=b.isIE7||b.isIE8,b.isAndroid=/android/gi.test(c),b.isIOS=/iphone|ipad|ipod/gi.test(c),b.supportsTransition=B(),b.probablyMobile=b.isAndroid||b.isIOS||/(Opera Mini)|Kindle|webOS|BlackBerry|(Opera Mobi)|(Windows Phone)|IEMobile/i.test(navigator.userAgent),d=a(document),b.popupsCache={}},open:function(c){var e;if(c.isObj===!1){b.items=c.items.toArray(),b.index=0;var g,h=c.items;for(e=0;e<h.length;e++)if(g=h[e],g.parsed&&(g=g.el[0]),g===c.el[0]){b.index=e;break}}else b.items=a.isArray(c.items)?c.items:[c.items],b.index=c.index||0;if(b.isOpen)return void b.updateItemHTML();b.types=[],f="",c.mainEl&&c.mainEl.length?b.ev=c.mainEl.eq(0):b.ev=d,c.key?(b.popupsCache[c.key]||(b.popupsCache[c.key]={}),b.currTemplate=b.popupsCache[c.key]):b.currTemplate={},b.st=a.extend(!0,{},a.magnificPopup.defaults,c),b.fixedContentPos="auto"===b.st.fixedContentPos?!b.probablyMobile:b.st.fixedContentPos,b.st.modal&&(b.st.closeOnContentClick=!1,b.st.closeOnBgClick=!1,b.st.showCloseBtn=!1,b.st.enableEscapeKey=!1),b.bgOverlay||(b.bgOverlay=x("bg").on("click"+p,function(){b.close()}),b.wrap=x("wrap").attr("tabindex",-1).on("click"+p,function(a){b._checkIfClose(a.target)&&b.close()}),b.container=x("container",b.wrap)),b.contentContainer=x("content"),b.st.preloader&&(b.preloader=x("preloader",b.container,b.st.tLoading));var i=a.magnificPopup.modules;for(e=0;e<i.length;e++){var j=i[e];j=j.charAt(0).toUpperCase()+j.slice(1),b["init"+j].call(b)}y("BeforeOpen"),b.st.showCloseBtn&&(b.st.closeBtnInside?(w(l,function(a,b,c,d){c.close_replaceWith=z(d.type)}),f+=" mfp-close-btn-in"):b.wrap.append(z())),b.st.alignTop&&(f+=" mfp-align-top"),b.fixedContentPos?b.wrap.css({overflow:b.st.overflowY,overflowX:"hidden",overflowY:b.st.overflowY}):b.wrap.css({top:v.scrollTop(),position:"absolute"}),(b.st.fixedBgPos===!1||"auto"===b.st.fixedBgPos&&!b.fixedContentPos)&&b.bgOverlay.css({height:d.height(),position:"absolute"}),b.st.enableEscapeKey&&d.on("keyup"+p,function(a){27===a.keyCode&&b.close()}),v.on("resize"+p,function(){b.updateSize()}),b.st.closeOnContentClick||(f+=" mfp-auto-cursor"),f&&b.wrap.addClass(f);var k=b.wH=v.height(),n={};if(b.fixedContentPos&&b._hasScrollBar(k)){var o=b._getScrollbarSize();o&&(n.marginRight=o)}b.fixedContentPos&&(b.isIE7?a("body, html").css("overflow","hidden"):n.overflow="hidden");var r=b.st.mainClass;return b.isIE7&&(r+=" mfp-ie7"),r&&b._addClassToMFP(r),b.updateItemHTML(),y("BuildControls"),a("html").css(n),b.bgOverlay.add(b.wrap).prependTo(b.st.prependTo||a(document.body)),b._lastFocusedEl=document.activeElement,setTimeout(function(){b.content?(b._addClassToMFP(q),b._setFocus()):b.bgOverlay.addClass(q),d.on("focusin"+p,b._onFocusIn)},16),b.isOpen=!0,b.updateSize(k),y(m),c},close:function(){b.isOpen&&(y(i),b.isOpen=!1,b.st.removalDelay&&!b.isLowIE&&b.supportsTransition?(b._addClassToMFP(r),setTimeout(function(){b._close()},b.st.removalDelay)):b._close())},_close:function(){y(h);var c=r+" "+q+" ";if(b.bgOverlay.detach(),b.wrap.detach(),b.container.empty(),b.st.mainClass&&(c+=b.st.mainClass+" "),b._removeClassFromMFP(c),b.fixedContentPos){var e={marginRight:""};b.isIE7?a("body, html").css("overflow",""):e.overflow="",a("html").css(e)}d.off("keyup"+p+" focusin"+p),b.ev.off(p),b.wrap.attr("class","mfp-wrap").removeAttr("style"),b.bgOverlay.attr("class","mfp-bg"),b.container.attr("class","mfp-container"),!b.st.showCloseBtn||b.st.closeBtnInside&&b.currTemplate[b.currItem.type]!==!0||b.currTemplate.closeBtn&&b.currTemplate.closeBtn.detach(),b._lastFocusedEl&&a(b._lastFocusedEl).focus(),b.currItem=null,b.content=null,b.currTemplate=null,b.prevHeight=0,y(j)},updateSize:function(a){if(b.isIOS){var c=document.documentElement.clientWidth/window.innerWidth,d=window.innerHeight*c;b.wrap.css("height",d),b.wH=d}else b.wH=a||v.height();b.fixedContentPos||b.wrap.css("height",b.wH),y("Resize")},updateItemHTML:function(){var c=b.items[b.index];b.contentContainer.detach(),b.content&&b.content.detach(),c.parsed||(c=b.parseEl(b.index));var d=c.type;if(y("BeforeChange",[b.currItem?b.currItem.type:"",d]),b.currItem=c,!b.currTemplate[d]){var f=b.st[d]?b.st[d].markup:!1;y("FirstMarkupParse",f),f?b.currTemplate[d]=a(f):b.currTemplate[d]=!0}e&&e!==c.type&&b.container.removeClass("mfp-"+e+"-holder");var g=b["get"+d.charAt(0).toUpperCase()+d.slice(1)](c,b.currTemplate[d]);b.appendContent(g,d),c.preloaded=!0,y(n,c),e=c.type,b.container.prepend(b.contentContainer),y("AfterChange")},appendContent:function(a,c){b.content=a,a?b.st.showCloseBtn&&b.st.closeBtnInside&&b.currTemplate[c]===!0?b.content.find(".mfp-close").length||b.content.append(z()):b.content=a:b.content="",y(k),b.container.addClass("mfp-"+c+"-holder"),b.contentContainer.append(b.content)},parseEl:function(c){var d,e=b.items[c];if(e.tagName?e={el:a(e)}:(d=e.type,e={data:e,src:e.src}),e.el){for(var f=b.types,g=0;g<f.length;g++)if(e.el.hasClass("mfp-"+f[g])){d=f[g];break}e.src=e.el.attr("data-mfp-src"),e.src||(e.src=e.el.attr("href"))}return e.type=d||b.st.type||"inline",e.index=c,e.parsed=!0,b.items[c]=e,y("ElementParse",e),b.items[c]},addGroup:function(a,c){var d=function(d){d.mfpEl=this,b._openClick(d,a,c)};c||(c={});var e="click.magnificPopup";c.mainEl=a,c.items?(c.isObj=!0,a.off(e).on(e,d)):(c.isObj=!1,c.delegate?a.off(e).on(e,c.delegate,d):(c.items=a,a.off(e).on(e,d)))},_openClick:function(c,d,e){var f=void 0!==e.midClick?e.midClick:a.magnificPopup.defaults.midClick;if(f||!(2===c.which||c.ctrlKey||c.metaKey||c.altKey||c.shiftKey)){var g=void 0!==e.disableOn?e.disableOn:a.magnificPopup.defaults.disableOn;if(g)if(a.isFunction(g)){if(!g.call(b))return!0}else if(v.width()<g)return!0;c.type&&(c.preventDefault(),b.isOpen&&c.stopPropagation()),e.el=a(c.mfpEl),e.delegate&&(e.items=d.find(e.delegate)),b.open(e)}},updateStatus:function(a,d){if(b.preloader){c!==a&&b.container.removeClass("mfp-s-"+c),d||"loading"!==a||(d=b.st.tLoading);var e={status:a,text:d};y("UpdateStatus",e),a=e.status,d=e.text,b.preloader.html(d),b.preloader.find("a").on("click",function(a){a.stopImmediatePropagation()}),b.container.addClass("mfp-s-"+a),c=a}},_checkIfClose:function(c){if(!a(c).hasClass(s)){var d=b.st.closeOnContentClick,e=b.st.closeOnBgClick;if(d&&e)return!0;if(!b.content||a(c).hasClass("mfp-close")||b.preloader&&c===b.preloader[0])return!0;if(c===b.content[0]||a.contains(b.content[0],c)){if(d)return!0}else if(e&&a.contains(document,c))return!0;return!1}},_addClassToMFP:function(a){b.bgOverlay.addClass(a),b.wrap.addClass(a)},_removeClassFromMFP:function(a){this.bgOverlay.removeClass(a),b.wrap.removeClass(a)},_hasScrollBar:function(a){return(b.isIE7?d.height():document.body.scrollHeight)>(a||v.height())},_setFocus:function(){(b.st.focus?b.content.find(b.st.focus).eq(0):b.wrap).focus()},_onFocusIn:function(c){return c.target===b.wrap[0]||a.contains(b.wrap[0],c.target)?void 0:(b._setFocus(),!1)},_parseMarkup:function(b,c,d){var e;d.data&&(c=a.extend(d.data,c)),y(l,[b,c,d]),a.each(c,function(a,c){if(void 0===c||c===!1)return!0;if(e=a.split("_"),e.length>1){var d=b.find(p+"-"+e[0]);if(d.length>0){var f=e[1];"replaceWith"===f?d[0]!==c[0]&&d.replaceWith(c):"img"===f?d.is("img")?d.attr("src",c):d.replaceWith('<img src="'+c+'" class="'+d.attr("class")+'" />'):d.attr(e[1],c)}}else b.find(p+"-"+a).html(c)})},_getScrollbarSize:function(){if(void 0===b.scrollbarSize){var a=document.createElement("div");a.style.cssText="width: 99px; height: 99px; overflow: scroll; position: absolute; top: -9999px;",document.body.appendChild(a),b.scrollbarSize=a.offsetWidth-a.clientWidth,document.body.removeChild(a)}return b.scrollbarSize}},a.magnificPopup={instance:null,proto:t.prototype,modules:[],open:function(b,c){return A(),b=b?a.extend(!0,{},b):{},b.isObj=!0,b.index=c||0,this.instance.open(b)},close:function(){return a.magnificPopup.instance&&a.magnificPopup.instance.close()},registerModule:function(b,c){c.options&&(a.magnificPopup.defaults[b]=c.options),a.extend(this.proto,c.proto),this.modules.push(b)},defaults:{disableOn:0,key:null,midClick:!1,mainClass:"",preloader:!0,focus:"",closeOnContentClick:!1,closeOnBgClick:!0,closeBtnInside:!0,showCloseBtn:!0,enableEscapeKey:!0,modal:!1,alignTop:!1,removalDelay:0,prependTo:null,fixedContentPos:"auto",fixedBgPos:"auto",overflowY:"auto",closeMarkup:'<button title="%title%" type="button" class="mfp-close">&#215;</button>',tClose:"Close (Esc)",tLoading:"Loading..."}},a.fn.magnificPopup=function(c){A();var d=a(this);if("string"==typeof c)if("open"===c){var e,f=u?d.data("magnificPopup"):d[0].magnificPopup,g=parseInt(arguments[1],10)||0;f.items?e=f.items[g]:(e=d,f.delegate&&(e=e.find(f.delegate)),e=e.eq(g)),b._openClick({mfpEl:e},d,f)}else b.isOpen&&b[c].apply(b,Array.prototype.slice.call(arguments,1));else c=a.extend(!0,{},c),u?d.data("magnificPopup",c):d[0].magnificPopup=c,b.addGroup(d,c);return d};var C,D,E,F="inline",G=function(){E&&(D.after(E.addClass(C)).detach(),E=null)};a.magnificPopup.registerModule(F,{options:{hiddenClass:"hide",markup:"",tNotFound:"Content not found"},proto:{initInline:function(){b.types.push(F),w(h+"."+F,function(){G()})},getInline:function(c,d){if(G(),c.src){var e=b.st.inline,f=a(c.src);if(f.length){var g=f[0].parentNode;g&&g.tagName&&(D||(C=e.hiddenClass,D=x(C),C="mfp-"+C),E=f.after(D).detach().removeClass(C)),b.updateStatus("ready")}else b.updateStatus("error",e.tNotFound),f=a("<div>");return c.inlineElement=f,f}return b.updateStatus("ready"),b._parseMarkup(d,{},c),d}}});var H,I="ajax",J=function(){H&&a(document.body).removeClass(H)},K=function(){J(),b.req&&b.req.abort()};a.magnificPopup.registerModule(I,{options:{settings:null,cursor:"mfp-ajax-cur",tError:'<a href="%url%">The content</a> could not be loaded.'},proto:{initAjax:function(){b.types.push(I),H=b.st.ajax.cursor,w(h+"."+I,K),w("BeforeChange."+I,K)},getAjax:function(c){H&&a(document.body).addClass(H),b.updateStatus("loading");var d=a.extend({url:c.src,success:function(d,e,f){var g={data:d,xhr:f};y("ParseAjax",g),b.appendContent(a(g.data),I),c.finished=!0,J(),b._setFocus(),setTimeout(function(){b.wrap.addClass(q)},16),b.updateStatus("ready"),y("AjaxContentAdded")},error:function(){J(),c.finished=c.loadError=!0,b.updateStatus("error",b.st.ajax.tError.replace("%url%",c.src))}},b.st.ajax.settings);return b.req=a.ajax(d),""}}});var L,M=function(c){if(c.data&&void 0!==c.data.title)return c.data.title;var d=b.st.image.titleSrc;if(d){if(a.isFunction(d))return d.call(b,c);if(c.el)return c.el.attr(d)||""}return""};a.magnificPopup.registerModule("image",{options:{markup:'<div class="mfp-figure"><div class="mfp-close"></div><figure><div class="mfp-img"></div><figcaption><div class="mfp-bottom-bar"><div class="mfp-title"></div><div class="mfp-counter"></div></div></figcaption></figure></div>',cursor:"mfp-zoom-out-cur",titleSrc:"title",verticalFit:!0,tError:'<a href="%url%">The image</a> could not be loaded.'},proto:{initImage:function(){var c=b.st.image,d=".image";b.types.push("image"),w(m+d,function(){"image"===b.currItem.type&&c.cursor&&a(document.body).addClass(c.cursor)}),w(h+d,function(){c.cursor&&a(document.body).removeClass(c.cursor),v.off("resize"+p)}),w("Resize"+d,b.resizeImage),b.isLowIE&&w("AfterChange",b.resizeImage)},resizeImage:function(){var a=b.currItem;if(a&&a.img&&b.st.image.verticalFit){var c=0;b.isLowIE&&(c=parseInt(a.img.css("padding-top"),10)+parseInt(a.img.css("padding-bottom"),10)),a.img.css("max-height",b.wH-c)}},_onImageHasSize:function(a){a.img&&(a.hasSize=!0,L&&clearInterval(L),a.isCheckingImgSize=!1,y("ImageHasSize",a),a.imgHidden&&(b.content&&b.content.removeClass("mfp-loading"),a.imgHidden=!1))},findImageSize:function(a){var c=0,d=a.img[0],e=function(f){L&&clearInterval(L),L=setInterval(function(){return d.naturalWidth>0?void b._onImageHasSize(a):(c>200&&clearInterval(L),c++,void(3===c?e(10):40===c?e(50):100===c&&e(500)))},f)};e(1)},getImage:function(c,d){var e=0,f=function(){c&&(c.img[0].complete?(c.img.off(".mfploader"),c===b.currItem&&(b._onImageHasSize(c),b.updateStatus("ready")),c.hasSize=!0,c.loaded=!0,y("ImageLoadComplete")):(e++,200>e?setTimeout(f,100):g()))},g=function(){c&&(c.img.off(".mfploader"),c===b.currItem&&(b._onImageHasSize(c),b.updateStatus("error",h.tError.replace("%url%",c.src))),c.hasSize=!0,c.loaded=!0,c.loadError=!0)},h=b.st.image,i=d.find(".mfp-img");if(i.length){var j=document.createElement("img");j.className="mfp-img",c.el&&c.el.find("img").length&&(j.alt=c.el.find("img").attr("alt")),c.img=a(j).on("load.mfploader",f).on("error.mfploader",g),j.src=c.src,i.is("img")&&(c.img=c.img.clone()),j=c.img[0],j.naturalWidth>0?c.hasSize=!0:j.width||(c.hasSize=!1)}return b._parseMarkup(d,{title:M(c),img_replaceWith:c.img},c),b.resizeImage(),c.hasSize?(L&&clearInterval(L),c.loadError?(d.addClass("mfp-loading"),b.updateStatus("error",h.tError.replace("%url%",c.src))):(d.removeClass("mfp-loading"),b.updateStatus("ready")),d):(b.updateStatus("loading"),c.loading=!0,c.hasSize||(c.imgHidden=!0,d.addClass("mfp-loading"),b.findImageSize(c)),d)}}});var N,O=function(){return void 0===N&&(N=void 0!==document.createElement("p").style.MozTransform),N};a.magnificPopup.registerModule("zoom",{options:{enabled:!1,easing:"ease-in-out",duration:300,opener:function(a){return a.is("img")?a:a.find("img")}},proto:{initZoom:function(){var a,c=b.st.zoom,d=".zoom";if(c.enabled&&b.supportsTransition){var e,f,g=c.duration,j=function(a){var b=a.clone().removeAttr("style").removeAttr("class").addClass("mfp-animated-image"),d="all "+c.duration/1e3+"s "+c.easing,e={position:"fixed",zIndex:9999,left:0,top:0,"-webkit-backface-visibility":"hidden"},f="transition";return e["-webkit-"+f]=e["-moz-"+f]=e["-o-"+f]=e[f]=d,b.css(e),b},k=function(){b.content.css("visibility","visible")};w("BuildControls"+d,function(){if(b._allowZoom()){if(clearTimeout(e),b.content.css("visibility","hidden"),a=b._getItemToZoom(),!a)return void k();f=j(a),f.css(b._getOffset()),b.wrap.append(f),e=setTimeout(function(){f.css(b._getOffset(!0)),e=setTimeout(function(){k(),setTimeout(function(){f.remove(),a=f=null,y("ZoomAnimationEnded")},16)},g)},16)}}),w(i+d,function(){if(b._allowZoom()){if(clearTimeout(e),b.st.removalDelay=g,!a){if(a=b._getItemToZoom(),!a)return;f=j(a)}f.css(b._getOffset(!0)),b.wrap.append(f),b.content.css("visibility","hidden"),setTimeout(function(){f.css(b._getOffset())},16)}}),w(h+d,function(){b._allowZoom()&&(k(),f&&f.remove(),a=null)})}},_allowZoom:function(){return"image"===b.currItem.type},_getItemToZoom:function(){return b.currItem.hasSize?b.currItem.img:!1},_getOffset:function(c){var d;d=c?b.currItem.img:b.st.zoom.opener(b.currItem.el||b.currItem);var e=d.offset(),f=parseInt(d.css("padding-top"),10),g=parseInt(d.css("padding-bottom"),10);e.top-=a(window).scrollTop()-f;var h={width:d.width(),height:(u?d.innerHeight():d[0].offsetHeight)-g-f};return O()?h["-moz-transform"]=h.transform="translate("+e.left+"px,"+e.top+"px)":(h.left=e.left,h.top=e.top),h}}});var P="iframe",Q="//about:blank",R=function(a){if(b.currTemplate[P]){var c=b.currTemplate[P].find("iframe");c.length&&(a||(c[0].src=Q),b.isIE8&&c.css("display",a?"block":"none"))}};a.magnificPopup.registerModule(P,{options:{markup:'<div class="mfp-iframe-scaler"><div class="mfp-close"></div><iframe class="mfp-iframe" src="//about:blank" frameborder="0" allowfullscreen></iframe></div>',srcAction:"iframe_src",patterns:{youtube:{index:"youtube.com",id:"v=",src:"//www.youtube.com/embed/%id%?autoplay=1"},vimeo:{index:"vimeo.com/",id:"/",src:"//player.vimeo.com/video/%id%?autoplay=1"},gmaps:{index:"//maps.google.",src:"%id%&output=embed"}}},proto:{initIframe:function(){b.types.push(P),w("BeforeChange",function(a,b,c){b!==c&&(b===P?R():c===P&&R(!0))}),w(h+"."+P,function(){R()})},getIframe:function(c,d){var e=c.src,f=b.st.iframe;a.each(f.patterns,function(){return e.indexOf(this.index)>-1?(this.id&&(e="string"==typeof this.id?e.substr(e.lastIndexOf(this.id)+this.id.length,e.length):this.id.call(this,e)),e=this.src.replace("%id%",e),!1):void 0});var g={};return f.srcAction&&(g[f.srcAction]=e),b._parseMarkup(d,g,c),b.updateStatus("ready"),d}}});var S=function(a){var c=b.items.length;return a>c-1?a-c:0>a?c+a:a},T=function(a,b,c){return a.replace(/%curr%/gi,b+1).replace(/%total%/gi,c)};a.magnificPopup.registerModule("gallery",{options:{enabled:!1,arrowMarkup:'<button title="%title%" type="button" class="mfp-arrow mfp-arrow-%dir%"></button>',preload:[0,2],navigateByImgClick:!0,arrows:!0,tPrev:"Previous (Left arrow key)",tNext:"Next (Right arrow key)",tCounter:"%curr% of %total%"},proto:{initGallery:function(){var c=b.st.gallery,e=".mfp-gallery",g=Boolean(a.fn.mfpFastClick);return b.direction=!0,c&&c.enabled?(f+=" mfp-gallery",w(m+e,function(){c.navigateByImgClick&&b.wrap.on("click"+e,".mfp-img",function(){return b.items.length>1?(b.next(),!1):void 0}),d.on("keydown"+e,function(a){37===a.keyCode?b.prev():39===a.keyCode&&b.next()})}),w("UpdateStatus"+e,function(a,c){c.text&&(c.text=T(c.text,b.currItem.index,b.items.length))}),w(l+e,function(a,d,e,f){var g=b.items.length;e.counter=g>1?T(c.tCounter,f.index,g):""}),w("BuildControls"+e,function(){if(b.items.length>1&&c.arrows&&!b.arrowLeft){var d=c.arrowMarkup,e=b.arrowLeft=a(d.replace(/%title%/gi,c.tPrev).replace(/%dir%/gi,"left")).addClass(s),f=b.arrowRight=a(d.replace(/%title%/gi,c.tNext).replace(/%dir%/gi,"right")).addClass(s),h=g?"mfpFastClick":"click";e[h](function(){b.prev()}),f[h](function(){b.next()}),b.isIE7&&(x("b",e[0],!1,!0),x("a",e[0],!1,!0),x("b",f[0],!1,!0),x("a",f[0],!1,!0)),b.container.append(e.add(f))}}),w(n+e,function(){b._preloadTimeout&&clearTimeout(b._preloadTimeout),b._preloadTimeout=setTimeout(function(){b.preloadNearbyImages(),b._preloadTimeout=null},16)}),void w(h+e,function(){d.off(e),b.wrap.off("click"+e),b.arrowLeft&&g&&b.arrowLeft.add(b.arrowRight).destroyMfpFastClick(),b.arrowRight=b.arrowLeft=null})):!1},next:function(){b.direction=!0,b.index=S(b.index+1),b.updateItemHTML()},prev:function(){b.direction=!1,b.index=S(b.index-1),b.updateItemHTML()},goTo:function(a){b.direction=a>=b.index,b.index=a,b.updateItemHTML()},preloadNearbyImages:function(){var a,c=b.st.gallery.preload,d=Math.min(c[0],b.items.length),e=Math.min(c[1],b.items.length);for(a=1;a<=(b.direction?e:d);a++)b._preloadItem(b.index+a);for(a=1;a<=(b.direction?d:e);a++)b._preloadItem(b.index-a)},_preloadItem:function(c){if(c=S(c),!b.items[c].preloaded){var d=b.items[c];d.parsed||(d=b.parseEl(c)),y("LazyLoad",d),"image"===d.type&&(d.img=a('<img class="mfp-img" />').on("load.mfploader",function(){d.hasSize=!0}).on("error.mfploader",function(){d.hasSize=!0,d.loadError=!0,y("LazyLoadError",d)}).attr("src",d.src)),d.preloaded=!0}}}});var U="retina";a.magnificPopup.registerModule(U,{options:{replaceSrc:function(a){return a.src.replace(/\.\w+$/,function(a){return"@2x"+a})},ratio:1},proto:{initRetina:function(){if(window.devicePixelRatio>1){var a=b.st.retina,c=a.ratio;c=isNaN(c)?c():c,c>1&&(w("ImageHasSize."+U,function(a,b){b.img.css({"max-width":b.img[0].naturalWidth/c,width:"100%"})}),w("ElementParse."+U,function(b,d){d.src=a.replaceSrc(d,c)}))}}}}),function(){var b=1e3,c="ontouchstart"in window,d=function(){v.off("touchmove"+f+" touchend"+f)},e="mfpFastClick",f="."+e;a.fn.mfpFastClick=function(e){return a(this).each(function(){var g,h=a(this);if(c){var i,j,k,l,m,n;h.on("touchstart"+f,function(a){l=!1,n=1,m=a.originalEvent?a.originalEvent.touches[0]:a.touches[0],j=m.clientX,k=m.clientY,v.on("touchmove"+f,function(a){m=a.originalEvent?a.originalEvent.touches:a.touches,n=m.length,m=m[0],(Math.abs(m.clientX-j)>10||Math.abs(m.clientY-k)>10)&&(l=!0,d())}).on("touchend"+f,function(a){d(),l||n>1||(g=!0,a.preventDefault(),clearTimeout(i),i=setTimeout(function(){g=!1},b),e())})})}h.on("click"+f,function(){g||e()})})},a.fn.destroyMfpFastClick=function(){a(this).off("touchstart"+f+" click"+f),c&&v.off("touchmove"+f+" touchend"+f)}}(),A()});


/*!
 * Masonry PACKAGED v4.0.0
 * Cascading grid layout library
 * http://masonry.desandro.com
 * MIT License
 * by David DeSandro
 */

!function(t,e){"use strict";"function"==typeof define&&define.amd?define("jquery-bridget/jquery-bridget",["jquery"],function(i){e(t,i)}):"object"==typeof module&&module.exports?module.exports=e(t,require("jquery")):t.jQueryBridget=e(t,t.jQuery)}(window,function(t,e){"use strict";function i(i,r,a){function h(t,e,n){var o,r="$()."+i+'("'+e+'")';return t.each(function(t,h){var u=a.data(h,i);if(!u)return void s(i+" not initialized. Cannot call methods, i.e. "+r);var d=u[e];if(!d||"_"==e.charAt(0))return void s(r+" is not a valid method");var c=d.apply(u,n);o=void 0===o?c:o}),void 0!==o?o:t}function u(t,e){t.each(function(t,n){var o=a.data(n,i);o?(o.option(e),o._init()):(o=new r(n,e),a.data(n,i,o))})}a=a||e||t.jQuery,a&&(r.prototype.option||(r.prototype.option=function(t){a.isPlainObject(t)&&(this.options=a.extend(!0,this.options,t))}),a.fn[i]=function(t){if("string"==typeof t){var e=o.call(arguments,1);return h(this,t,e)}return u(this,t),this},n(a))}function n(t){!t||t&&t.bridget||(t.bridget=i)}var o=Array.prototype.slice,r=t.console,s="undefined"==typeof r?function(){}:function(t){r.error(t)};return n(e||t.jQuery),i}),function(t,e){"function"==typeof define&&define.amd?define("ev-emitter/ev-emitter",e):"object"==typeof module&&module.exports?module.exports=e():t.EvEmitter=e()}(this,function(){function t(){}var e=t.prototype;return e.on=function(t,e){if(t&&e){var i=this._events=this._events||{},n=i[t]=i[t]||[];return-1==n.indexOf(e)&&n.push(e),this}},e.once=function(t,e){if(t&&e){this.on(t,e);var i=this._onceEvents=this._onceEvents||{},n=i[t]=i[t]||[];return n[e]=!0,this}},e.off=function(t,e){var i=this._events&&this._events[t];if(i&&i.length){var n=i.indexOf(e);return-1!=n&&i.splice(n,1),this}},e.emitEvent=function(t,e){var i=this._events&&this._events[t];if(i&&i.length){var n=0,o=i[n];e=e||[];for(var r=this._onceEvents&&this._onceEvents[t];o;){var s=r&&r[o];s&&(this.off(t,o),delete r[o]),o.apply(this,e),n+=s?0:1,o=i[n]}return this}},t}),function(t,e){"use strict";"function"==typeof define&&define.amd?define("get-size/get-size",[],function(){return e()}):"object"==typeof module&&module.exports?module.exports=e():t.getSize=e()}(window,function(){"use strict";function t(t){var e=parseFloat(t),i=-1==t.indexOf("%")&&!isNaN(e);return i&&e}function e(){}function i(){for(var t={width:0,height:0,innerWidth:0,innerHeight:0,outerWidth:0,outerHeight:0},e=0;u>e;e++){var i=h[e];t[i]=0}return t}function n(t){var e=getComputedStyle(t);return e||a("Style returned "+e+". Are you running this code in a hidden iframe on Firefox? See http://bit.ly/getsizebug1"),e}function o(){if(!d){d=!0;var e=document.createElement("div");e.style.width="200px",e.style.padding="1px 2px 3px 4px",e.style.borderStyle="solid",e.style.borderWidth="1px 2px 3px 4px",e.style.boxSizing="border-box";var i=document.body||document.documentElement;i.appendChild(e);var o=n(e);r.isBoxSizeOuter=s=200==t(o.width),i.removeChild(e)}}function r(e){if(o(),"string"==typeof e&&(e=document.querySelector(e)),e&&"object"==typeof e&&e.nodeType){var r=n(e);if("none"==r.display)return i();var a={};a.width=e.offsetWidth,a.height=e.offsetHeight;for(var d=a.isBorderBox="border-box"==r.boxSizing,c=0;u>c;c++){var l=h[c],f=r[l],m=parseFloat(f);a[l]=isNaN(m)?0:m}var p=a.paddingLeft+a.paddingRight,g=a.paddingTop+a.paddingBottom,y=a.marginLeft+a.marginRight,v=a.marginTop+a.marginBottom,_=a.borderLeftWidth+a.borderRightWidth,E=a.borderTopWidth+a.borderBottomWidth,z=d&&s,b=t(r.width);b!==!1&&(a.width=b+(z?0:p+_));var x=t(r.height);return x!==!1&&(a.height=x+(z?0:g+E)),a.innerWidth=a.width-(p+_),a.innerHeight=a.height-(g+E),a.outerWidth=a.width+y,a.outerHeight=a.height+v,a}}var s,a="undefined"==typeof console?e:function(t){console.error(t)},h=["paddingLeft","paddingRight","paddingTop","paddingBottom","marginLeft","marginRight","marginTop","marginBottom","borderLeftWidth","borderRightWidth","borderTopWidth","borderBottomWidth"],u=h.length,d=!1;return r}),function(t,e){"use strict";"function"==typeof define&&define.amd?define("matches-selector/matches-selector",e):"object"==typeof module&&module.exports?module.exports=e():t.matchesSelector=e()}(window,function(){"use strict";var t=function(){var t=Element.prototype;if(t.matches)return"matches";if(t.matchesSelector)return"matchesSelector";for(var e=["webkit","moz","ms","o"],i=0;i<e.length;i++){var n=e[i],o=n+"MatchesSelector";if(t[o])return o}}();return function(e,i){return e[t](i)}}),function(t,e){"use strict";"function"==typeof define&&define.amd?define("fizzy-ui-utils/utils",["matches-selector/matches-selector"],function(i){return e(t,i)}):"object"==typeof module&&module.exports?module.exports=e(t,require("desandro-matches-selector")):t.fizzyUIUtils=e(t,t.matchesSelector)}(window,function(t,e){var i={};i.extend=function(t,e){for(var i in e)t[i]=e[i];return t},i.modulo=function(t,e){return(t%e+e)%e},i.makeArray=function(t){var e=[];if(Array.isArray(t))e=t;else if(t&&"number"==typeof t.length)for(var i=0;i<t.length;i++)e.push(t[i]);else e.push(t);return e},i.removeFrom=function(t,e){var i=t.indexOf(e);-1!=i&&t.splice(i,1)},i.getParent=function(t,i){for(;t!=document.body;)if(t=t.parentNode,e(t,i))return t},i.getQueryElement=function(t){return"string"==typeof t?document.querySelector(t):t},i.handleEvent=function(t){var e="on"+t.type;this[e]&&this[e](t)},i.filterFindElements=function(t,n){t=i.makeArray(t);var o=[];return t.forEach(function(t){if(t instanceof HTMLElement){if(!n)return void o.push(t);e(t,n)&&o.push(t);for(var i=t.querySelectorAll(n),r=0;r<i.length;r++)o.push(i[r])}}),o},i.debounceMethod=function(t,e,i){var n=t.prototype[e],o=e+"Timeout";t.prototype[e]=function(){var t=this[o];t&&clearTimeout(t);var e=arguments,r=this;this[o]=setTimeout(function(){n.apply(r,e),delete r[o]},i||100)}},i.docReady=function(t){"complete"==document.readyState?t():document.addEventListener("DOMContentLoaded",t)},i.toDashed=function(t){return t.replace(/(.)([A-Z])/g,function(t,e,i){return e+"-"+i}).toLowerCase()};var n=t.console;return i.htmlInit=function(e,o){i.docReady(function(){var r=i.toDashed(o),s="data-"+r,a=document.querySelectorAll("["+s+"]"),h=document.querySelectorAll(".js-"+r),u=i.makeArray(a).concat(i.makeArray(h)),d=s+"-options",c=t.jQuery;u.forEach(function(t){var i,r=t.getAttribute(s)||t.getAttribute(d);try{i=r&&JSON.parse(r)}catch(a){return void(n&&n.error("Error parsing "+s+" on "+t.className+": "+a))}var h=new e(t,i);c&&c.data(t,o,h)})})},i}),function(t,e){"function"==typeof define&&define.amd?define("outlayer/item",["ev-emitter/ev-emitter","get-size/get-size"],function(i,n){return e(t,i,n)}):"object"==typeof module&&module.exports?module.exports=e(t,require("ev-emitter"),require("get-size")):(t.Outlayer={},t.Outlayer.Item=e(t,t.EvEmitter,t.getSize))}(window,function(t,e,i){"use strict";function n(t){for(var e in t)return!1;return e=null,!0}function o(t,e){t&&(this.element=t,this.layout=e,this.position={x:0,y:0},this._create())}function r(t){return t.replace(/([A-Z])/g,function(t){return"-"+t.toLowerCase()})}var s=document.documentElement.style,a="string"==typeof s.transition?"transition":"WebkitTransition",h="string"==typeof s.transform?"transform":"WebkitTransform",u={WebkitTransition:"webkitTransitionEnd",transition:"transitionend"}[a],d=[h,a,a+"Duration",a+"Property"],c=o.prototype=Object.create(e.prototype);c.constructor=o,c._create=function(){this._transn={ingProperties:{},clean:{},onEnd:{}},this.css({position:"absolute"})},c.handleEvent=function(t){var e="on"+t.type;this[e]&&this[e](t)},c.getSize=function(){this.size=i(this.element)},c.css=function(t){var e=this.element.style;for(var i in t){var n=d[i]||i;e[n]=t[i]}},c.getPosition=function(){var t=getComputedStyle(this.element),e=this.layout._getOption("originLeft"),i=this.layout._getOption("originTop"),n=t[e?"left":"right"],o=t[i?"top":"bottom"],r=this.layout.size,s=-1!=n.indexOf("%")?parseFloat(n)/100*r.width:parseInt(n,10),a=-1!=o.indexOf("%")?parseFloat(o)/100*r.height:parseInt(o,10);s=isNaN(s)?0:s,a=isNaN(a)?0:a,s-=e?r.paddingLeft:r.paddingRight,a-=i?r.paddingTop:r.paddingBottom,this.position.x=s,this.position.y=a},c.layoutPosition=function(){var t=this.layout.size,e={},i=this.layout._getOption("originLeft"),n=this.layout._getOption("originTop"),o=i?"paddingLeft":"paddingRight",r=i?"left":"right",s=i?"right":"left",a=this.position.x+t[o];e[r]=this.getXValue(a),e[s]="";var h=n?"paddingTop":"paddingBottom",u=n?"top":"bottom",d=n?"bottom":"top",c=this.position.y+t[h];e[u]=this.getYValue(c),e[d]="",this.css(e),this.emitEvent("layout",[this])},c.getXValue=function(t){var e=this.layout._getOption("horizontal");return this.layout.options.percentPosition&&!e?t/this.layout.size.width*100+"%":t+"px"},c.getYValue=function(t){var e=this.layout._getOption("horizontal");return this.layout.options.percentPosition&&e?t/this.layout.size.height*100+"%":t+"px"},c._transitionTo=function(t,e){this.getPosition();var i=this.position.x,n=this.position.y,o=parseInt(t,10),r=parseInt(e,10),s=o===this.position.x&&r===this.position.y;if(this.setPosition(t,e),s&&!this.isTransitioning)return void this.layoutPosition();var a=t-i,h=e-n,u={};u.transform=this.getTranslate(a,h),this.transition({to:u,onTransitionEnd:{transform:this.layoutPosition},isCleaning:!0})},c.getTranslate=function(t,e){var i=this.layout._getOption("originLeft"),n=this.layout._getOption("originTop");return t=i?t:-t,e=n?e:-e,"translate3d("+t+"px, "+e+"px, 0)"},c.goTo=function(t,e){this.setPosition(t,e),this.layoutPosition()},c.moveTo=c._transitionTo,c.setPosition=function(t,e){this.position.x=parseInt(t,10),this.position.y=parseInt(e,10)},c._nonTransition=function(t){this.css(t.to),t.isCleaning&&this._removeStyles(t.to);for(var e in t.onTransitionEnd)t.onTransitionEnd[e].call(this)},c._transition=function(t){if(!parseFloat(this.layout.options.transitionDuration))return void this._nonTransition(t);var e=this._transn;for(var i in t.onTransitionEnd)e.onEnd[i]=t.onTransitionEnd[i];for(i in t.to)e.ingProperties[i]=!0,t.isCleaning&&(e.clean[i]=!0);if(t.from){this.css(t.from);var n=this.element.offsetHeight;n=null}this.enableTransition(t.to),this.css(t.to),this.isTransitioning=!0};var l="opacity,"+r(d.transform||"transform");c.enableTransition=function(){this.isTransitioning||(this.css({transitionProperty:l,transitionDuration:this.layout.options.transitionDuration}),this.element.addEventListener(u,this,!1))},c.transition=o.prototype[a?"_transition":"_nonTransition"],c.onwebkitTransitionEnd=function(t){this.ontransitionend(t)},c.onotransitionend=function(t){this.ontransitionend(t)};var f={"-webkit-transform":"transform"};c.ontransitionend=function(t){if(t.target===this.element){var e=this._transn,i=f[t.propertyName]||t.propertyName;if(delete e.ingProperties[i],n(e.ingProperties)&&this.disableTransition(),i in e.clean&&(this.element.style[t.propertyName]="",delete e.clean[i]),i in e.onEnd){var o=e.onEnd[i];o.call(this),delete e.onEnd[i]}this.emitEvent("transitionEnd",[this])}},c.disableTransition=function(){this.removeTransitionStyles(),this.element.removeEventListener(u,this,!1),this.isTransitioning=!1},c._removeStyles=function(t){var e={};for(var i in t)e[i]="";this.css(e)};var m={transitionProperty:"",transitionDuration:""};return c.removeTransitionStyles=function(){this.css(m)},c.removeElem=function(){this.element.parentNode.removeChild(this.element),this.css({display:""}),this.emitEvent("remove",[this])},c.remove=function(){return a&&parseFloat(this.layout.options.transitionDuration)?(this.once("transitionEnd",function(){this.removeElem()}),void this.hide()):void this.removeElem()},c.reveal=function(){delete this.isHidden,this.css({display:""});var t=this.layout.options,e={},i=this.getHideRevealTransitionEndProperty("visibleStyle");e[i]=this.onRevealTransitionEnd,this.transition({from:t.hiddenStyle,to:t.visibleStyle,isCleaning:!0,onTransitionEnd:e})},c.onRevealTransitionEnd=function(){this.isHidden||this.emitEvent("reveal")},c.getHideRevealTransitionEndProperty=function(t){var e=this.layout.options[t];if(e.opacity)return"opacity";for(var i in e)return i},c.hide=function(){this.isHidden=!0,this.css({display:""});var t=this.layout.options,e={},i=this.getHideRevealTransitionEndProperty("hiddenStyle");e[i]=this.onHideTransitionEnd,this.transition({from:t.visibleStyle,to:t.hiddenStyle,isCleaning:!0,onTransitionEnd:e})},c.onHideTransitionEnd=function(){this.isHidden&&(this.css({display:"none"}),this.emitEvent("hide"))},c.destroy=function(){this.css({position:"",left:"",right:"",top:"",bottom:"",transition:"",transform:""})},o}),function(t,e){"use strict";"function"==typeof define&&define.amd?define("outlayer/outlayer",["ev-emitter/ev-emitter","get-size/get-size","fizzy-ui-utils/utils","./item"],function(i,n,o,r){return e(t,i,n,o,r)}):"object"==typeof module&&module.exports?module.exports=e(t,require("ev-emitter"),require("get-size"),require("fizzy-ui-utils"),require("./item")):t.Outlayer=e(t,t.EvEmitter,t.getSize,t.fizzyUIUtils,t.Outlayer.Item)}(window,function(t,e,i,n,o){"use strict";function r(t,e){var i=n.getQueryElement(t);if(!i)return void(a&&a.error("Bad element for "+this.constructor.namespace+": "+(i||t)));this.element=i,h&&(this.$element=h(this.element)),this.options=n.extend({},this.constructor.defaults),this.option(e);var o=++d;this.element.outlayerGUID=o,c[o]=this,this._create();var r=this._getOption("initLayout");r&&this.layout()}function s(t){function e(){t.apply(this,arguments)}return e.prototype=Object.create(t.prototype),e.prototype.constructor=e,e}var a=t.console,h=t.jQuery,u=function(){},d=0,c={};r.namespace="outlayer",r.Item=o,r.defaults={containerStyle:{position:"relative"},initLayout:!0,originLeft:!0,originTop:!0,resize:!0,resizeContainer:!0,transitionDuration:"0.4s",hiddenStyle:{opacity:0,transform:"scale(0.001)"},visibleStyle:{opacity:1,transform:"scale(1)"}};var l=r.prototype;return n.extend(l,e.prototype),l.option=function(t){n.extend(this.options,t)},l._getOption=function(t){var e=this.constructor.compatOptions[t];return e&&void 0!==this.options[e]?this.options[e]:this.options[t]},r.compatOptions={initLayout:"isInitLayout",horizontal:"isHorizontal",layoutInstant:"isLayoutInstant",originLeft:"isOriginLeft",originTop:"isOriginTop",resize:"isResizeBound",resizeContainer:"isResizingContainer"},l._create=function(){this.reloadItems(),this.stamps=[],this.stamp(this.options.stamp),n.extend(this.element.style,this.options.containerStyle);var t=this._getOption("resize");t&&this.bindResize()},l.reloadItems=function(){this.items=this._itemize(this.element.children)},l._itemize=function(t){for(var e=this._filterFindItemElements(t),i=this.constructor.Item,n=[],o=0;o<e.length;o++){var r=e[o],s=new i(r,this);n.push(s)}return n},l._filterFindItemElements=function(t){return n.filterFindElements(t,this.options.itemSelector)},l.getItemElements=function(){return this.items.map(function(t){return t.element})},l.layout=function(){this._resetLayout(),this._manageStamps();var t=this._getOption("layoutInstant"),e=void 0!==t?t:!this._isLayoutInited;this.layoutItems(this.items,e),this._isLayoutInited=!0},l._init=l.layout,l._resetLayout=function(){this.getSize()},l.getSize=function(){this.size=i(this.element)},l._getMeasurement=function(t,e){var n,o=this.options[t];o?("string"==typeof o?n=this.element.querySelector(o):o instanceof HTMLElement&&(n=o),this[t]=n?i(n)[e]:o):this[t]=0},l.layoutItems=function(t,e){t=this._getItemsForLayout(t),this._layoutItems(t,e),this._postLayout()},l._getItemsForLayout=function(t){return t.filter(function(t){return!t.isIgnored})},l._layoutItems=function(t,e){if(this._emitCompleteOnItems("layout",t),t&&t.length){var i=[];t.forEach(function(t){var n=this._getItemLayoutPosition(t);n.item=t,n.isInstant=e||t.isLayoutInstant,i.push(n)},this),this._processLayoutQueue(i)}},l._getItemLayoutPosition=function(){return{x:0,y:0}},l._processLayoutQueue=function(t){t.forEach(function(t){this._positionItem(t.item,t.x,t.y,t.isInstant)},this)},l._positionItem=function(t,e,i,n){n?t.goTo(e,i):t.moveTo(e,i)},l._postLayout=function(){this.resizeContainer()},l.resizeContainer=function(){var t=this._getOption("resizeContainer");if(t){var e=this._getContainerSize();e&&(this._setContainerMeasure(e.width,!0),this._setContainerMeasure(e.height,!1))}},l._getContainerSize=u,l._setContainerMeasure=function(t,e){if(void 0!==t){var i=this.size;i.isBorderBox&&(t+=e?i.paddingLeft+i.paddingRight+i.borderLeftWidth+i.borderRightWidth:i.paddingBottom+i.paddingTop+i.borderTopWidth+i.borderBottomWidth),t=Math.max(t,0),this.element.style[e?"width":"height"]=t+"px"}},l._emitCompleteOnItems=function(t,e){function i(){o.dispatchEvent(t+"Complete",null,[e])}function n(){s++,s==r&&i()}var o=this,r=e.length;if(!e||!r)return void i();var s=0;e.forEach(function(e){e.once(t,n)})},l.dispatchEvent=function(t,e,i){var n=e?[e].concat(i):i;if(this.emitEvent(t,n),h)if(this.$element=this.$element||h(this.element),e){var o=h.Event(e);o.type=t,this.$element.trigger(o,i)}else this.$element.trigger(t,i)},l.ignore=function(t){var e=this.getItem(t);e&&(e.isIgnored=!0)},l.unignore=function(t){var e=this.getItem(t);e&&delete e.isIgnored},l.stamp=function(t){t=this._find(t),t&&(this.stamps=this.stamps.concat(t),t.forEach(this.ignore,this))},l.unstamp=function(t){t=this._find(t),t&&t.forEach(function(t){n.removeFrom(this.stamps,t),this.unignore(t)},this)},l._find=function(t){return t?("string"==typeof t&&(t=this.element.querySelectorAll(t)),t=n.makeArray(t)):void 0},l._manageStamps=function(){this.stamps&&this.stamps.length&&(this._getBoundingRect(),this.stamps.forEach(this._manageStamp,this))},l._getBoundingRect=function(){var t=this.element.getBoundingClientRect(),e=this.size;this._boundingRect={left:t.left+e.paddingLeft+e.borderLeftWidth,top:t.top+e.paddingTop+e.borderTopWidth,right:t.right-(e.paddingRight+e.borderRightWidth),bottom:t.bottom-(e.paddingBottom+e.borderBottomWidth)}},l._manageStamp=u,l._getElementOffset=function(t){var e=t.getBoundingClientRect(),n=this._boundingRect,o=i(t),r={left:e.left-n.left-o.marginLeft,top:e.top-n.top-o.marginTop,right:n.right-e.right-o.marginRight,bottom:n.bottom-e.bottom-o.marginBottom};return r},l.handleEvent=n.handleEvent,l.bindResize=function(){t.addEventListener("resize",this),this.isResizeBound=!0},l.unbindResize=function(){t.removeEventListener("resize",this),this.isResizeBound=!1},l.onresize=function(){this.resize()},n.debounceMethod(r,"onresize",100),l.resize=function(){this.isResizeBound&&this.needsResizeLayout()&&this.layout()},l.needsResizeLayout=function(){var t=i(this.element),e=this.size&&t;return e&&t.innerWidth!==this.size.innerWidth},l.addItems=function(t){var e=this._itemize(t);return e.length&&(this.items=this.items.concat(e)),e},l.appended=function(t){var e=this.addItems(t);e.length&&(this.layoutItems(e,!0),this.reveal(e))},l.prepended=function(t){var e=this._itemize(t);if(e.length){var i=this.items.slice(0);this.items=e.concat(i),this._resetLayout(),this._manageStamps(),this.layoutItems(e,!0),this.reveal(e),this.layoutItems(i)}},l.reveal=function(t){this._emitCompleteOnItems("reveal",t),t&&t.length&&t.forEach(function(t){t.reveal()})},l.hide=function(t){this._emitCompleteOnItems("hide",t),t&&t.length&&t.forEach(function(t){t.hide()})},l.revealItemElements=function(t){var e=this.getItems(t);this.reveal(e)},l.hideItemElements=function(t){var e=this.getItems(t);this.hide(e)},l.getItem=function(t){for(var e=0;e<this.items.length;e++){var i=this.items[e];if(i.element==t)return i}},l.getItems=function(t){t=n.makeArray(t);var e=[];return t.forEach(function(t){var i=this.getItem(t);i&&e.push(i)},this),e},l.remove=function(t){var e=this.getItems(t);this._emitCompleteOnItems("remove",e),e&&e.length&&e.forEach(function(t){t.remove(),n.removeFrom(this.items,t)},this)},l.destroy=function(){var t=this.element.style;t.height="",t.position="",t.width="",this.items.forEach(function(t){t.destroy()}),this.unbindResize();var e=this.element.outlayerGUID;delete c[e],delete this.element.outlayerGUID,h&&h.removeData(this.element,this.constructor.namespace)},r.data=function(t){t=n.getQueryElement(t);var e=t&&t.outlayerGUID;return e&&c[e]},r.create=function(t,e){var i=s(r);return i.defaults=n.extend({},r.defaults),n.extend(i.defaults,e),i.compatOptions=n.extend({},r.compatOptions),i.namespace=t,i.data=r.data,i.Item=s(o),n.htmlInit(i,t),h&&h.bridget&&h.bridget(t,i),i},r.Item=o,r}),function(t,e){"function"==typeof define&&define.amd?define(["outlayer/outlayer","get-size/get-size"],e):"object"==typeof module&&module.exports?module.exports=e(require("outlayer"),require("get-size")):t.Masonry=e(t.Outlayer,t.getSize)}(window,function(t,e){var i=t.create("masonry");return i.compatOptions.fitWidth="isFitWidth",i.prototype._resetLayout=function(){this.getSize(),this._getMeasurement("columnWidth","outerWidth"),this._getMeasurement("gutter","outerWidth"),this.measureColumns(),this.colYs=[];for(var t=0;t<this.cols;t++)this.colYs.push(0);this.maxY=0},i.prototype.measureColumns=function(){if(this.getContainerWidth(),!this.columnWidth){var t=this.items[0],i=t&&t.element;this.columnWidth=i&&e(i).outerWidth||this.containerWidth}var n=this.columnWidth+=this.gutter,o=this.containerWidth+this.gutter,r=o/n,s=n-o%n,a=s&&1>s?"round":"floor";r=Math[a](r),this.cols=Math.max(r,1)},i.prototype.getContainerWidth=function(){var t=this._getOption("fitWidth"),i=t?this.element.parentNode:this.element,n=e(i);this.containerWidth=n&&n.innerWidth},i.prototype._getItemLayoutPosition=function(t){t.getSize();var e=t.size.outerWidth%this.columnWidth,i=e&&1>e?"round":"ceil",n=Math[i](t.size.outerWidth/this.columnWidth);n=Math.min(n,this.cols);for(var o=this._getColGroup(n),r=Math.min.apply(Math,o),s=o.indexOf(r),a={x:this.columnWidth*s,y:r},h=r+t.size.outerHeight,u=this.cols+1-o.length,d=0;u>d;d++)this.colYs[s+d]=h;return a},i.prototype._getColGroup=function(t){if(2>t)return this.colYs;for(var e=[],i=this.cols+1-t,n=0;i>n;n++){var o=this.colYs.slice(n,n+t);e[n]=Math.max.apply(Math,o)}return e},i.prototype._manageStamp=function(t){var i=e(t),n=this._getElementOffset(t),o=this._getOption("originLeft"),r=o?n.left:n.right,s=r+i.outerWidth,a=Math.floor(r/this.columnWidth);a=Math.max(0,a);var h=Math.floor(s/this.columnWidth);h-=s%this.columnWidth?0:1,h=Math.min(this.cols-1,h);for(var u=this._getOption("originTop"),d=(u?n.top:n.bottom)+i.outerHeight,c=a;h>=c;c++)this.colYs[c]=Math.max(d,this.colYs[c])},i.prototype._getContainerSize=function(){this.maxY=Math.max.apply(Math,this.colYs);var t={height:this.maxY};return this._getOption("fitWidth")&&(t.width=this._getContainerFitWidth()),t},i.prototype._getContainerFitWidth=function(){for(var t=0,e=this.cols;--e&&0===this.colYs[e];)t++;return(this.cols-t)*this.columnWidth-this.gutter},i.prototype.needsResizeLayout=function(){var t=this.containerWidth;return this.getContainerWidth(),t!=this.containerWidth},i});


/*!
 * imagesLoaded PACKAGED v3.2.0
 * JavaScript is all like "You images are done yet or what?"
 * MIT License
 */
(function(){"use strict";function e(){}function t(e,t){for(var n=e.length;n--;)if(e[n].listener===t)return n;return-1}function n(e){return function(){return this[e].apply(this,arguments)}}var i=e.prototype,r=this,s=r.EventEmitter;i.getListeners=function(e){var t,n,i=this._getEvents();if("object"==typeof e){t={};for(n in i)i.hasOwnProperty(n)&&e.test(n)&&(t[n]=i[n])}else t=i[e]||(i[e]=[]);return t},i.flattenListeners=function(e){var t,n=[];for(t=0;t<e.length;t+=1)n.push(e[t].listener);return n},i.getListenersAsObject=function(e){var t,n=this.getListeners(e);return n instanceof Array&&(t={},t[e]=n),t||n},i.addListener=function(e,n){var i,r=this.getListenersAsObject(e),s="object"==typeof n;for(i in r)r.hasOwnProperty(i)&&-1===t(r[i],n)&&r[i].push(s?n:{listener:n,once:!1});return this},i.on=n("addListener"),i.addOnceListener=function(e,t){return this.addListener(e,{listener:t,once:!0})},i.once=n("addOnceListener"),i.defineEvent=function(e){return this.getListeners(e),this},i.defineEvents=function(e){for(var t=0;t<e.length;t+=1)this.defineEvent(e[t]);return this},i.removeListener=function(e,n){var i,r,s=this.getListenersAsObject(e);for(r in s)s.hasOwnProperty(r)&&(i=t(s[r],n),-1!==i&&s[r].splice(i,1));return this},i.off=n("removeListener"),i.addListeners=function(e,t){return this.manipulateListeners(!1,e,t)},i.removeListeners=function(e,t){return this.manipulateListeners(!0,e,t)},i.manipulateListeners=function(e,t,n){var i,r,s=e?this.removeListener:this.addListener,o=e?this.removeListeners:this.addListeners;if("object"!=typeof t||t instanceof RegExp)for(i=n.length;i--;)s.call(this,t,n[i]);else for(i in t)t.hasOwnProperty(i)&&(r=t[i])&&("function"==typeof r?s.call(this,i,r):o.call(this,i,r));return this},i.removeEvent=function(e){var t,n=typeof e,i=this._getEvents();if("string"===n)delete i[e];else if("object"===n)for(t in i)i.hasOwnProperty(t)&&e.test(t)&&delete i[t];else delete this._events;return this},i.removeAllListeners=n("removeEvent"),i.emitEvent=function(e,t){var n,i,r,s,o=this.getListenersAsObject(e);for(r in o)if(o.hasOwnProperty(r))for(i=o[r].length;i--;)n=o[r][i],n.once===!0&&this.removeListener(e,n.listener),s=n.listener.apply(this,t||[]),s===this._getOnceReturnValue()&&this.removeListener(e,n.listener);return this},i.trigger=n("emitEvent"),i.emit=function(e){var t=Array.prototype.slice.call(arguments,1);return this.emitEvent(e,t)},i.setOnceReturnValue=function(e){return this._onceReturnValue=e,this},i._getOnceReturnValue=function(){return this.hasOwnProperty("_onceReturnValue")?this._onceReturnValue:!0},i._getEvents=function(){return this._events||(this._events={})},e.noConflict=function(){return r.EventEmitter=s,e},"function"==typeof define&&define.amd?define("eventEmitter/EventEmitter",[],function(){return e}):"object"==typeof module&&module.exports?module.exports=e:this.EventEmitter=e}).call(this),function(e){function t(t){var n=e.event;return n.target=n.target||n.srcElement||t,n}var n=document.documentElement,i=function(){};n.addEventListener?i=function(e,t,n){e.addEventListener(t,n,!1)}:n.attachEvent&&(i=function(e,n,i){e[n+i]=i.handleEvent?function(){var n=t(e);i.handleEvent.call(i,n)}:function(){var n=t(e);i.call(e,n)},e.attachEvent("on"+n,e[n+i])});var r=function(){};n.removeEventListener?r=function(e,t,n){e.removeEventListener(t,n,!1)}:n.detachEvent&&(r=function(e,t,n){e.detachEvent("on"+t,e[t+n]);try{delete e[t+n]}catch(i){e[t+n]=void 0}});var s={bind:i,unbind:r};"function"==typeof define&&define.amd?define("eventie/eventie",s):e.eventie=s}(this),function(e,t){"use strict";"function"==typeof define&&define.amd?define(["eventEmitter/EventEmitter","eventie/eventie"],function(n,i){return t(e,n,i)}):"object"==typeof module&&module.exports?module.exports=t(e,require("wolfy87-eventemitter"),require("eventie")):e.imagesLoaded=t(e,e.EventEmitter,e.eventie)}(window,function(e,t,n){function i(e,t){for(var n in t)e[n]=t[n];return e}function r(e){return"[object Array]"==f.call(e)}function s(e){var t=[];if(r(e))t=e;else if("number"==typeof e.length)for(var n=0;n<e.length;n++)t.push(e[n]);else t.push(e);return t}function o(e,t,n){if(!(this instanceof o))return new o(e,t,n);"string"==typeof e&&(e=document.querySelectorAll(e)),this.elements=s(e),this.options=i({},this.options),"function"==typeof t?n=t:i(this.options,t),n&&this.on("always",n),this.getImages(),u&&(this.jqDeferred=new u.Deferred);var r=this;setTimeout(function(){r.check()})}function h(e){this.img=e}function a(e,t){this.url=e,this.element=t,this.img=new Image}var u=e.jQuery,c=e.console,f=Object.prototype.toString;o.prototype=new t,o.prototype.options={},o.prototype.getImages=function(){this.images=[];for(var e=0;e<this.elements.length;e++){var t=this.elements[e];this.addElementImages(t)}},o.prototype.addElementImages=function(e){"IMG"==e.nodeName&&this.addImage(e),this.options.background===!0&&this.addElementBackgroundImages(e);var t=e.nodeType;if(t&&d[t]){for(var n=e.querySelectorAll("img"),i=0;i<n.length;i++){var r=n[i];this.addImage(r)}if("string"==typeof this.options.background){var s=e.querySelectorAll(this.options.background);for(i=0;i<s.length;i++){var o=s[i];this.addElementBackgroundImages(o)}}}};var d={1:!0,9:!0,11:!0};o.prototype.addElementBackgroundImages=function(e){for(var t=m(e),n=/url\(['"]*([^'"\)]+)['"]*\)/gi,i=n.exec(t.backgroundImage);null!==i;){var r=i&&i[1];r&&this.addBackground(r,e),i=n.exec(t.backgroundImage)}};var m=e.getComputedStyle||function(e){return e.currentStyle};return o.prototype.addImage=function(e){var t=new h(e);this.images.push(t)},o.prototype.addBackground=function(e,t){var n=new a(e,t);this.images.push(n)},o.prototype.check=function(){function e(e,n,i){setTimeout(function(){t.progress(e,n,i)})}var t=this;if(this.progressedCount=0,this.hasAnyBroken=!1,!this.images.length)return void this.complete();for(var n=0;n<this.images.length;n++){var i=this.images[n];i.once("progress",e),i.check()}},o.prototype.progress=function(e,t,n){this.progressedCount++,this.hasAnyBroken=this.hasAnyBroken||!e.isLoaded,this.emit("progress",this,e,t),this.jqDeferred&&this.jqDeferred.notify&&this.jqDeferred.notify(this,e),this.progressedCount==this.images.length&&this.complete(),this.options.debug&&c&&c.log("progress: "+n,e,t)},o.prototype.complete=function(){var e=this.hasAnyBroken?"fail":"done";if(this.isComplete=!0,this.emit(e,this),this.emit("always",this),this.jqDeferred){var t=this.hasAnyBroken?"reject":"resolve";this.jqDeferred[t](this)}},h.prototype=new t,h.prototype.check=function(){var e=this.getIsImageComplete();return e?void this.confirm(0!==this.img.naturalWidth,"naturalWidth"):(this.proxyImage=new Image,n.bind(this.proxyImage,"load",this),n.bind(this.proxyImage,"error",this),n.bind(this.img,"load",this),n.bind(this.img,"error",this),void(this.proxyImage.src=this.img.src))},h.prototype.getIsImageComplete=function(){return this.img.complete&&void 0!==this.img.naturalWidth},h.prototype.confirm=function(e,t){this.isLoaded=e,this.emit("progress",this,this.img,t)},h.prototype.handleEvent=function(e){var t="on"+e.type;this[t]&&this[t](e)},h.prototype.onload=function(){this.confirm(!0,"onload"),this.unbindEvents()},h.prototype.onerror=function(){this.confirm(!1,"onerror"),this.unbindEvents()},h.prototype.unbindEvents=function(){n.unbind(this.proxyImage,"load",this),n.unbind(this.proxyImage,"error",this),n.unbind(this.img,"load",this),n.unbind(this.img,"error",this)},a.prototype=new h,a.prototype.check=function(){n.bind(this.img,"load",this),n.bind(this.img,"error",this),this.img.src=this.url;var e=this.getIsImageComplete();e&&(this.confirm(0!==this.img.naturalWidth,"naturalWidth"),this.unbindEvents())},a.prototype.unbindEvents=function(){n.unbind(this.img,"load",this),n.unbind(this.img,"error",this)},a.prototype.confirm=function(e,t){this.isLoaded=e,this.emit("progress",this,this.element,t)},o.makeJQueryPlugin=function(t){t=t||e.jQuery,t&&(u=t,u.fn.imagesLoaded=function(e,t){var n=new o(this,e,t);return n.jqDeferred.promise(u(this))})},o.makeJQueryPlugin(),o});



 
   </script>
   <!--<script src="js/main.js"></script>-->
   <script>
   /** 
 * ===================================================================
 * main js
 *
 * ------------------------------------------------------------------- 
 */ 

(function($) {

	"use strict";

	/*---------------------------------------------------- */
	/* Preloader
	------------------------------------------------------ */ 
   $(window).load(function() {

      // will first fade out the loading animation 
    	$("#loader").fadeOut("slow", function(){

        // will fade out the whole DIV that covers the website.
        $("#preloader").delay(300).fadeOut("slow");

      });       

  	})


  	/*---------------------------------------------------- */
  	/* FitText Settings
  	------------------------------------------------------ */
  	setTimeout(function() {

   	$('#intro h1').fitText(1, { minFontSize: '42px', maxFontSize: '84px' });

  	}, 100);


	/*---------------------------------------------------- */
	/* FitVids
	------------------------------------------------------ */ 
  	$(".fluid-video-wrapper").fitVids();


	/*---------------------------------------------------- */
	/* Owl Carousel
	------------------------------------------------------ */ 
	$("#owl-slider").owlCarousel({
        navigation: false,
        pagination: true,
        itemsCustom : [
	        [0, 1],
	        [700, 2],
	        [960, 3]
	     ],
        navigationText: false
    });


	/*----------------------------------------------------- */
	/* Alert Boxes
  	------------------------------------------------------- */
	$('.alert-box').on('click', '.close', function() {
	  $(this).parent().fadeOut(500);
	});	


	/*----------------------------------------------------- */
	/* Stat Counter
  	------------------------------------------------------- */
   var statSection = $("#stats"),
       stats = $(".stat-count");

   statSection.waypoint({

   	handler: function(direction) {

      	if (direction === "down") {       		

			   stats.each(function () {
				   var $this = $(this);

				   $({ Counter: 0 }).animate({ Counter: $this.text() }, {
				   	duration: 4000,
				   	easing: 'swing',
				   	step: function (curValue) {
				      	$this.text(Math.ceil(curValue));
				    	}
				  	});
				});

       	} 

       	// trigger once only
       	this.destroy();      	

		},
			
		offset: "90%"
	
	});	


	/*---------------------------------------------------- */
	/*	Masonry
	------------------------------------------------------ */
	var containerProjects = $('#folio-wrapper');

	containerProjects.imagesLoaded( function() {

		containerProjects.masonry( {		  
		  	itemSelector: '.folio-item',
		  	resize: true 
		});

	});


	/*----------------------------------------------------*/
	/*	Modal Popup
	------------------------------------------------------*/
   $('.item-wrap a').magnificPopup({

      type:'inline',
      fixedContentPos: false,
      removalDelay: 300,
      showCloseBtn: false,
      mainClass: 'mfp-fade'

   });

   $(document).on('click', '.popup-modal-dismiss', function (e) {
   	e.preventDefault();
   	$.magnificPopup.close();
   });

	
	/*-----------------------------------------------------*/
  	/* Navigation Menu
   ------------------------------------------------------ */  
   var toggleButton = $('.menu-toggle'),
       nav = $('.main-navigation');

   // toggle button
   toggleButton.on('click', function(e) {

		e.preventDefault();
		toggleButton.toggleClass('is-clicked');
		nav.slideToggle();

	});

   // nav items
  	nav.find('li a').on("click", function() {   

   	// update the toggle button 		
   	toggleButton.toggleClass('is-clicked'); 
   	// fadeout the navigation panel
   	nav.fadeOut();   		
   	     
  	});


   /*---------------------------------------------------- */
  	/* Highlight the current section in the navigation bar
  	------------------------------------------------------ */
	var sections = $("section"),
	navigation_links = $("#main-nav-wrap li a");	

	sections.waypoint( {

       handler: function(direction) {

		   var active_section;

			active_section = $('section#' + this.element.id);

			if (direction === "up") active_section = active_section.prev();

			var active_link = $('#main-nav-wrap a[href="#' + active_section.attr("id") + '"]');			

         navigation_links.parent().removeClass("current");
			active_link.parent().addClass("current");

		}, 

		offset: '25%'
	});


	/*---------------------------------------------------- */
  	/* Smooth Scrolling
  	------------------------------------------------------ */
  	$('.smoothscroll').on('click', function (e) {
	 	
	 	e.preventDefault();

   	var target = this.hash,
    	$target = $(target);

    	$('html, body').stop().animate({
       	'scrollTop': $target.offset().top
      }, 800, 'swing', function () {
      	window.location.hash = target;
      });

  	});  
  

   /*---------------------------------------------------- */
	/*  Placeholder Plugin Settings
	------------------------------------------------------ */ 
	$('input, textarea, select').placeholder()  


  	/*---------------------------------------------------- */
	/*	contact form
	------------------------------------------------------ */

	/* local validation */
	$('#contactForm').validate({

		/* submit via ajax */
		submitHandler: function(form) {

			var sLoader = $('#submit-loader');

			$.ajax({      	

		      type: "POST",
		      url: "inc/sendEmail.php",
		      data: $(form).serialize(),
		      beforeSend: function() { 

		      	sLoader.fadeIn(); 

		      },
		      success: function(msg) {

	            // Message was sent
	            if (msg == 'OK') {
	            	sLoader.fadeOut(); 
	               $('#message-warning').hide();
	               $('#contactForm').fadeOut();
	               $('#message-success').fadeIn();   
	            }
	            // There was an error
	            else {
	            	sLoader.fadeOut(); 
	               $('#message-warning').html(msg);
		            $('#message-warning').fadeIn();
	            }

		      },
		      error: function() {

		      	sLoader.fadeOut(); 
		      	$('#message-warning').html("Something went wrong. Please try again.");
		         $('#message-warning').fadeIn();

		      }

	      });     		
  		}

	});


 	/*----------------------------------------------------- */
  	/* Back to top
   ------------------------------------------------------- */ 
	var pxShow = 300; // height on which the button will show
	var fadeInTime = 400; // how slow/fast you want the button to show
	var fadeOutTime = 400; // how slow/fast you want the button to hide
	var scrollSpeed = 300; // how slow/fast you want the button to scroll to top. can be a value, 'slow', 'normal' or 'fast'

   // Show or hide the sticky footer button
	jQuery(window).scroll(function() {

		if (!( $("#header-search").hasClass('is-visible'))) {

			if (jQuery(window).scrollTop() >= pxShow) {
				jQuery("#go-top").fadeIn(fadeInTime);
			} else {
				jQuery("#go-top").fadeOut(fadeOutTime);
			}

		}		

	});		

})(jQuery);
   </script>

</body>

</html>
