(function(){var l;function ba(a,b){function c(){}
c.prototype=b.prototype;a.prototype=new c;a.prototype.constructor=a;for(var d in b)if(Object.defineProperties){var e=Object.getOwnPropertyDescriptor(b,d);e&&Object.defineProperty(a,d,e)}else a[d]=b[d]}
for(var ca="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(c.get||c.set)throw new TypeError("ES3 does not support getters and setters.");a!=Array.prototype&&a!=Object.prototype&&(a[b]=c.value)},da="undefined"!=typeof window&&window===this?this:"undefined"!=typeof global&&null!=global?global:this,fa=["String",
"prototype","startsWith"],ga=0;ga<fa.length-1;ga++){var ha=fa[ga];ha in da||(da[ha]={});da=da[ha]}
var ia=fa[fa.length-1],ja=da[ia],ma=ja?ja:function(a,b){var c;if(null==this)throw new TypeError("The 'this' value for String.prototype.startsWith must not be null or undefined");if(a instanceof RegExp)throw new TypeError("First argument to String.prototype.startsWith must not be a regular expression");c=this+"";a+="";for(var d=c.length,e=a.length,f=Math.max(0,Math.min(b|0,c.length)),g=0;g<e&&f<d;)if(c[f++]!=a[g++])return!1;return g>=e};
ma!=ja&&null!=ma&&ca(da,ia,{configurable:!0,writable:!0,value:ma});var m=this;function p(a){return void 0!==a}
function q(a,b,c){a=a.split(".");c=c||m;a[0]in c||!c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)!a.length&&p(b)?c[d]=b:c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}}
function r(a,b){for(var c=a.split("."),d=b||m,e;e=c.shift();)if(null!=d[e])d=d[e];else return null;return d}
function na(){}
function oa(a){a.la=void 0;a.getInstance=function(){return a.la?a.la:a.la=new a}}
function pa(a){var b=typeof a;if("object"==b)if(a){if(a instanceof Array)return"array";if(a instanceof Object)return b;var c=Object.prototype.toString.call(a);if("[object Window]"==c)return"object";if("[object Array]"==c||"number"==typeof a.length&&"undefined"!=typeof a.splice&&"undefined"!=typeof a.propertyIsEnumerable&&!a.propertyIsEnumerable("splice"))return"array";if("[object Function]"==c||"undefined"!=typeof a.call&&"undefined"!=typeof a.propertyIsEnumerable&&!a.propertyIsEnumerable("call"))return"function"}else return"null";
else if("function"==b&&"undefined"==typeof a.call)return"object";return b}
function qa(a){return"array"==pa(a)}
function ra(a){var b=pa(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function t(a){return"string"==typeof a}
function sa(a){return"function"==pa(a)}
function ta(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function ua(a){return a[va]||(a[va]=++wa)}
var va="closure_uid_"+(1E9*Math.random()>>>0),wa=0;function xa(a,b,c){return a.call.apply(a.bind,arguments)}
function ya(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var c=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(c,d);return a.apply(b,c)}}return function(){return a.apply(b,arguments)}}
function u(a,b,c){u=Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?xa:ya;return u.apply(null,arguments)}
function za(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var b=c.slice();b.push.apply(b,arguments);return a.apply(this,b)}}
function Aa(a,b){for(var c in b)a[c]=b[c]}
var v=Date.now||function(){return+new Date};
function w(a,b){function c(){}
c.prototype=b.prototype;a.B=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.mb=function(a,c,f){for(var d=Array(arguments.length-2),e=2;e<arguments.length;e++)d[e-2]=arguments[e];return b.prototype[c].apply(a,d)}}
;var Ba=document,x=window;var Ca=(new Date).getTime();function Da(a){if(!a)return"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));a=a.substring(0,a.indexOf("://"));if("http"!==a&&"https"!==a&&"chrome-extension"!==a&&"file"!==a&&"android-app"!==a&&"chrome-search"!==a)throw Error("Invalid URI scheme in origin");var c="",d=b.indexOf(":");if(-1!=d){var e=b.substring(d+
1),b=b.substring(0,d);if("http"===a&&"80"!==e||"https"===a&&"443"!==e)c=":"+e}return a+"://"+b+c}
;function Ea(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;A=n=0}
function b(a){for(var b=g,c=0;64>c;c+=4)b[c/4]=a[c]<<24|a[c+1]<<16|a[c+2]<<8|a[c+3];for(c=16;80>c;c++)a=b[c-3]^b[c-8]^b[c-14]^b[c-16],b[c]=(a<<1|a>>>31)&4294967295;a=e[0];for(var d=e[1],f=e[2],h=e[3],k=e[4],n,H,c=0;80>c;c++)40>c?20>c?(n=h^d&(f^h),H=1518500249):(n=d^f^h,H=1859775393):60>c?(n=d&f|h&(d|f),H=2400959708):(n=d^f^h,H=3395469782),n=((a<<5|a>>>27)&4294967295)+n+k+H+b[c]&4294967295,k=h,h=f,f=(d<<30|d>>>2)&4294967295,d=a,a=n;e[0]=e[0]+a&4294967295;e[1]=e[1]+d&4294967295;e[2]=e[2]+f&4294967295;
e[3]=e[3]+h&4294967295;e[4]=e[4]+k&4294967295}
function c(a,c){if("string"===typeof a){a=unescape(encodeURIComponent(a));for(var d=[],e=0,g=a.length;e<g;++e)d.push(a.charCodeAt(e));a=d}c||(c=a.length);d=0;if(0==n)for(;d+64<c;)b(a.slice(d,d+64)),d+=64,A+=64;for(;d<c;)if(f[n++]=a[d++],A++,64==n)for(n=0,b(f);d+64<c;)b(a.slice(d,d+64)),d+=64,A+=64}
function d(){var a=[],d=8*A;56>n?c(h,56-n):c(h,64-(n-56));for(var g=63;56<=g;g--)f[g]=d&255,d>>>=8;b(f);for(g=d=0;5>g;g++)for(var k=24;0<=k;k-=8)a[d++]=e[g]>>k&255;return a}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var n,A;a();return{reset:a,update:c,digest:d,Ga:function(){for(var a=d(),b="",c=0;c<a.length;c++)b+="0123456789ABCDEF".charAt(Math.floor(a[c]/16))+"0123456789ABCDEF".charAt(a[c]%16);return b}}}
;/*
 gapi.loader.OBJECT_CREATE_TEST_OVERRIDE &&*/
var Fa=window,Ga=document,Ha=Fa.location;function Ia(){}
var Ja=/\[native code\]/;function y(a,b,c){return a[b]=a[b]||c}
function Ka(a){for(var b=0;b<this.length;b++)if(this[b]===a)return b;return-1}
function La(a){a=a.sort();for(var b=[],c=void 0,d=0;d<a.length;d++){var e=a[d];e!=c&&b.push(e);c=e}return b}
function z(){var a;if((a=Object.create)&&Ja.test(a))a=a(null);else{a={};for(var b in a)a[b]=void 0}return a}
var Ma=y(Fa,"gapi",{});function Na(a,b,c){this.i=c;this.g=a;this.j=b;this.f=0;this.b=null}
Na.prototype.get=function(){var a;0<this.f?(this.f--,a=this.b,this.b=a.next,a.next=null):a=this.g();return a};
function Oa(a,b){a.j(b);a.f<a.i&&(a.f++,b.next=a.b,a.b=b)}
;function Pa(a){if(Error.captureStackTrace)Error.captureStackTrace(this,Pa);else{var b=Error().stack;b&&(this.stack=b)}a&&(this.message=String(a))}
w(Pa,Error);Pa.prototype.name="CustomError";function Qa(a){return/^\s*$/.test(a)?!1:/^[\],:{}\s\u2028\u2029]*$/.test(a.replace(/\\["\\\/bfnrtu]/g,"@").replace(/(?:"[^"\\\n\r\u2028\u2029\x00-\x08\x0a-\x1f]*"|true|false|null|-?\d+(?:\.\d*)?(?:[eE][+\-]?\d+)?)[\s\u2028\u2029]*(?=:|,|]|}|$)/g,"]").replace(/(?:^|:|,)(?:[\s\u2028\u2029]*\[)+/g,""))}
function Ra(a){a=String(a);if(Qa(a))try{return eval("("+a+")")}catch(b){}throw Error("Invalid JSON string: "+a);}
function Sa(a){return eval("("+a+")")}
function Ta(a){var b=[];Ua(new Va,a,b);return b.join("")}
function Va(){}
function Ua(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(qa(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),e=d[f],Ua(a,e,c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");f="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(e=b[d],"function"!=typeof e&&(c.push(f),Wa(d,c),c.push(":"),Ua(a,e,c),f=","));c.push("}");return}}switch(typeof b){case "string":Wa(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Xa={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\x0B":"\\u000b"},Ya=/\uffff/.test("\uffff")?/[\\\"\x00-\x1f\x7f-\uffff]/g:/[\\\"\x00-\x1f\x7f-\xff]/g;function Wa(a,b){b.push('"',a.replace(Ya,function(a){var b=Xa[a];b||(b="\\u"+(a.charCodeAt(0)|65536).toString(16).substr(1),Xa[a]=b);return b}),'"')}
;function Za(a,b){this.width=a;this.height=b}
l=Za.prototype;l.aspectRatio=function(){return this.width/this.height};
l.isEmpty=function(){return!(this.width*this.height)};
l.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
l.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
l.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};function $a(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function ab(a){var b=bb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function cb(){var a=db,b;for(b in a)return!1;return!0}
function eb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function fb(a){var b={},c;for(c in a)b[c]=a[c];return b}
var gb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function hb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<gb.length;f++)c=gb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;function ib(a){a.prototype.then=a.prototype.then;a.prototype.$goog_Thenable=!0}
;function jb(a){jb[" "](a);return a}
jb[" "]=na;function kb(a,b){var c=lb;return Object.prototype.hasOwnProperty.call(c,a)?c[a]:c[a]=b(a)}
;function mb(){}
;var nb=String.prototype.trim?function(a){return a.trim()}:function(a){return a.replace(/^[\s\xa0]+|[\s\xa0]+$/g,"")};
function ob(a,b){return a<b?-1:a>b?1:0}
function pb(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var qb=function(){var a=!1;try{var b=Object.defineProperty({},"passive",{get:function(){a=!0}});
m.addEventListener("test",null,b)}catch(c){}return a}();var rb={};function sb(a){return rb[a]||(rb[a]=String(a).replace(/\-([a-z])/g,function(a,c){return c.toUpperCase()}))}
function tb(a,b){return a?a.dataset?a.dataset[sb(b)]:a.getAttribute("data-"+b):null}
function ub(a){a&&(a.dataset?a.dataset[sb("loaded")]="true":a.setAttribute("data-loaded","true"))}
;function vb(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.shiftKey=this.ctrlKey=this.altKey=!1;this.clientY=this.clientX=0;this.changedTouches=this.touches=null;if(a=a||window.event){this.event=a;for(var b in a)b in wb||(this[b]=a[b]);(b=a.target||a.srcElement)&&3==b.nodeType&&(b=b.parentNode);this.target=b;if(b=a.relatedTarget)try{b=b.nodeName?b:null}catch(c){b=null}else"mouseover"==this.type?b=a.fromElement:
"mouseout"==this.type&&(b=a.toElement);this.relatedTarget=b;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey}}
vb.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
vb.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
vb.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};
var wb={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};var xb=window.performance&&window.performance.timing&&window.performance.now?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()},yb="Microsoft Internet Explorer"==navigator.appName;
function zb(a,b){if(1<b.length)a[b[0]]=b[1];else{var c=b[0],d;for(d in c)a[d]=c[d]}}
;function Ab(a,b,c,d){this.f=a;this.i=b;this.g=c;this.b=d}
var Bb=1;function Cb(a){var b={};void 0!==a.f?b.trackingParams=a.f:(b.veType=a.i,null!=a.g&&(b.veCounter=a.g));void 0!==a.b&&(b.dataElement=Cb(a.b));return b}
;var Db=null;"undefined"!=typeof XMLHttpRequest?Db=function(){return new XMLHttpRequest}:"undefined"!=typeof ActiveXObject&&(Db=function(){return new ActiveXObject("Microsoft.XMLHTTP")});
function Eb(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function B(a,b){this.version=a;this.args=b}
function Fb(a){if(!a.Aa){var b={};a.call(b);a.Aa=b.version}return a.Aa}
function Gb(a,b){function c(){a.apply(this,b.args)}
if(!b.args||!b.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");var d;try{d=Fb(a)}catch(e){}if(!d||b.version!=d)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");c.prototype=a.prototype;try{return new c}catch(e){throw e.message="yt.pubsub2.Data.deserialize(): "+e.message,e;}}
function C(a,b){this.topic=a;this.b=b}
C.prototype.toString=function(){return this.topic};var Hb=window.performance||window.mozPerformance||window.msPerformance||window.webkitPerformance||{};function D(){this.f=this.f;this.G=this.G}
D.prototype.f=!1;D.prototype.dispose=function(){this.f||(this.f=!0,this.o())};
function Ib(a,b){a.f?p(void 0)?b.call(void 0):b():(a.G||(a.G=[]),a.G.push(p(void 0)?u(b,void 0):b))}
D.prototype.o=function(){if(this.G)for(;this.G.length;)this.G.shift()()};
function Jb(a){a&&"function"==typeof a.dispose&&a.dispose()}
function Kb(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];ra(d)?Kb.apply(null,d):Jb(d)}}
;var E;a:{var Lb=m.navigator;if(Lb){var Mb=Lb.userAgent;if(Mb){E=Mb;break a}}E=""}function F(a){return-1!=E.indexOf(a)}
;function Nb(a){this.b=a||{cookie:""}}
l=Nb.prototype;l.isEnabled=function(){return navigator.cookieEnabled};
l.set=function(a,b,c,d,e,f){if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');p(c)||(c=-1);e=e?";domain="+e:"";d=d?";path="+d:"";f=f?";secure":"";c=0>c?"":0==c?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(v()+1E3*c)).toUTCString();this.b.cookie=a+"="+b+e+d+c+f};
l.get=function(a,b){for(var c=a+"=",d=(this.b.cookie||"").split(";"),e=0,f;e<d.length;e++){f=nb(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
l.remove=function(a,b,c){var d=p(this.get(a));this.set(a,"",0,b,c);return d};
l.isEmpty=function(){return!this.b.cookie};
l.clear=function(){for(var a=(this.b.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=nb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var Ob=new Nb("undefined"==typeof document?null:document);Ob.f=3950;function Pb(a){this.b=a}
Pb.prototype.set=function(a,b){p(b)?this.b.set(a,Ta(b)):this.b.remove(a)};
Pb.prototype.get=function(a){var b;try{b=this.b.get(a)}catch(c){return}if(null!==b)try{return Ra(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Pb.prototype.remove=function(a){this.b.remove(a)};var Qb=!1,Rb="";function Sb(a){a=a.match(/[\d]+/g);if(!a)return"";a.length=3;return a.join(".")}
(function(){if(navigator.plugins&&navigator.plugins.length){var a=navigator.plugins["Shockwave Flash"];if(a&&(Qb=!0,a.description)){Rb=Sb(a.description);return}if(navigator.plugins["Shockwave Flash 2.0"]){Qb=!0;Rb="2.0.0.11";return}}if(navigator.mimeTypes&&navigator.mimeTypes.length&&(a=navigator.mimeTypes["application/x-shockwave-flash"],Qb=!(!a||!a.enabledPlugin))){Rb=Sb(a.enabledPlugin.description);return}try{var b=new ActiveXObject("ShockwaveFlash.ShockwaveFlash.7");Qb=!0;Rb=Sb(b.GetVariable("$version"));
return}catch(c){}try{b=new ActiveXObject("ShockwaveFlash.ShockwaveFlash.6");Qb=!0;Rb="6.0.21";return}catch(c){}try{b=new ActiveXObject("ShockwaveFlash.ShockwaveFlash"),Qb=!0,Rb=Sb(b.GetVariable("$version"))}catch(c){}})();
var Tb=Qb,Ub=Rb;function Vb(a,b,c){var d=Wb();this.label=a;this.type=b;this.eventId=c;this.value=d;this.duration=0}
;var Xb=window.yt&&window.yt.config_||window.ytcfg&&window.ytcfg.data_||{};q("yt.config_",Xb,void 0);function G(a){zb(Xb,arguments)}
function I(a,b){return a in Xb?Xb[a]:b}
;function Yb(a){a=a||{};this.url=a.url||"";this.urlV9As2=a.url_v9as2||"";this.args=a.args||fb(Zb);this.assets=a.assets||{};this.attrs=a.attrs||fb($b);this.params=a.params||fb(ac);this.minVersion=a.min_version||"8.0.0";this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
var Zb={enablejsapi:1},$b={},ac={allowscriptaccess:"always",allowfullscreen:"true",bgcolor:"#000000"};function bc(a){a instanceof Yb||(a=new Yb(a));return a}
function cc(a){var b=new Yb,c;for(c in a)if(a.hasOwnProperty(c)){var d=a[c];b[c]="object"==pa(d)?fb(d):d}return b}
;var dc={"api.invalidparam":2,auth:150,"drm.auth":150,"heartbeat.net":150,"heartbeat.servererror":150,"heartbeat.stop":150,"html5.unsupportedads":5,"fmt.noneavailable":5,"fmt.decode":5,"fmt.unplayable":5,"html5.missingapi":5,"html5.unsupportedlive":5,"drm.unavailable":5};function ec(a){B.call(this,1,arguments)}
w(ec,B);var fc=new C("timing-sent",ec);function gc(a){B.call(this,1,arguments);this.ga=a}
w(gc,B);function hc(a,b){B.call(this,2,arguments);this.f=a;this.b=b}
w(hc,B);function ic(a,b,c,d){B.call(this,1,arguments);this.b=b;this.f=c||null;this.itemId=d||null}
w(ic,B);function jc(a,b){B.call(this,1,arguments);this.f=a;this.b=b||null}
w(jc,B);function kc(a){B.call(this,1,arguments)}
w(kc,B);var lc=new C("ypc-core-load",gc),mc=new C("ypc-guide-sync-success",hc),nc=new C("ypc-purchase-success",ic),oc=new C("ypc-subscription-cancel",kc),pc=new C("ypc-subscription-cancel-success",jc),qc=new C("ypc-init-subscription",kc);var J;J=y(Fa,"___jsl",z());y(J,"I",0);y(J,"hel",10);function rc(){var a=Ha.href,b;if(J.dpo)b=J.h;else{b=J.h;var c=RegExp("([#].*&|[#])jsh=([^&#]*)","g"),d=RegExp("([?#].*&|[?#])jsh=([^&#]*)","g");if(a=a&&(c.exec(a)||d.exec(a)))try{b=decodeURIComponent(a[2])}catch(e){}}return b}
function sc(a){var b=y(J,"PQ",[]);J.PQ=[];var c=b.length;if(0===c)a();else for(var d=0,e=function(){++d===c&&a()},f=0;f<c;f++)b[f](e)}
function tc(a){return y(y(J,"H",z()),a,z())}
;var uc=Array.prototype.indexOf?function(a,b,c){return Array.prototype.indexOf.call(a,b,c)}:function(a,b,c){c=null==c?0:0>c?Math.max(0,a.length+c):c;
if(t(a))return t(b)&&1==b.length?a.indexOf(b,c):-1;for(;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},K=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e=t(a)?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},vc=Array.prototype.map?function(a,b,c){return Array.prototype.map.call(a,b,c)}:function(a,b,c){for(var d=a.length,e=Array(d),f=t(a)?a.split(""):a,g=0;g<d;g++)g in f&&(e[g]=b.call(c,f[g],g,a));
return e};
function wc(a,b){var c;a:{c=a.length;for(var d=t(a)?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){c=e;break a}c=-1}return 0>c?null:t(a)?a.charAt(c):a[c]}
function xc(a,b){var c=uc(a,b);0<=c&&Array.prototype.splice.call(a,c,1)}
function yc(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function zc(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(ra(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
function Ac(a,b,c,d){return Array.prototype.splice.apply(a,Bc(arguments,1))}
function Bc(a,b,c){return 2>=arguments.length?Array.prototype.slice.call(a,b):Array.prototype.slice.call(a,b,c)}
;function Cc(){this.f=this.b=null}
var Fc=new Na(function(){return new Dc},function(a){a.reset()},100);
Cc.prototype.remove=function(){var a=null;this.b&&(a=this.b,this.b=this.b.next,this.b||(this.f=null),a.next=null);return a};
function Dc(){this.next=this.scope=this.b=null}
Dc.prototype.set=function(a,b){this.b=a;this.scope=b;this.next=null};
Dc.prototype.reset=function(){this.next=this.scope=this.b=null};function Gc(){return F("iPhone")&&!F("iPod")&&!F("iPad")}
;function Hc(a){this.b=a}
w(Hc,Pb);function Ic(a){this.data=a}
function Jc(a){return!p(a)||a instanceof Ic?a:new Ic(a)}
Hc.prototype.set=function(a,b){Hc.B.set.call(this,a,Jc(b))};
Hc.prototype.f=function(a){a=Hc.B.get.call(this,a);if(!p(a)||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Hc.prototype.get=function(a){if(a=this.f(a)){if(a=a.data,!p(a))throw"Storage: Invalid value was encountered";}else a=void 0;return a};var Kc=/^(?:([^:/?#.]+):)?(?:\/\/(?:([^/?#]*)@)?([^/#?]*?)(?::([0-9]+))?(?=[/#?]|$))?([^?#]+)?(?:\?([^#]*))?(?:#([\s\S]*))?$/;function L(a){return a.match(Kc)}
function Lc(a){return a?decodeURI(a):a}
function Mc(a){if(a[1]){var b=a[0],c=b.indexOf("#");0<=c&&(a.push(b.substr(c)),a[0]=b=b.substr(0,c));c=b.indexOf("?");0>c?a[1]="?":c==b.length-1&&(a[1]=void 0)}return a.join("")}
function Nc(a,b,c){if(qa(b))for(var d=0;d<b.length;d++)Nc(a,String(b[d]),c);else null!=b&&c.push("&",a,""===b?"":"=",encodeURIComponent(String(b)))}
function Oc(a,b,c){for(c=c||0;c<b.length;c+=2)Nc(b[c],b[c+1],a);return a}
function Pc(a,b){for(var c in b)Nc(c,b[c],a);return a}
function Qc(a,b){return Mc(2==arguments.length?Oc([a],arguments[1],0):Oc([a],arguments,1))}
;function M(a,b){var c=r("yt.logging.errors.log");c?c(a,b,void 0,void 0,void 0):(c=I("ERRORS",[]),c.push([a,b,void 0,void 0,void 0]),G("ERRORS",c))}
function Rc(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){M(b)}}:a}
;function N(a){return I("EXPERIMENT_FLAGS",{})[a]}
;var Sc=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};q("yt.msgs_",Sc,void 0);function Tc(a){zb(Sc,arguments)}
;function Uc(a){a={client:{hl:a.Oa,gl:a.Na,clientName:a.Ma,clientVersion:a.innertubeContextClientVersion}};I("DELEGATED_SESSION_ID")&&(a.user={onBehalfOfUser:I("DELEGATED_SESSION_ID")});return a}
function Vc(){return{apiaryHost:I("APIARY_HOST",void 0),Ea:I("APIARY_HOST_FIRSTPARTY",void 0),gapiHintOverride:!!I("GAPI_HINT_OVERRIDE",void 0),gapiHintParams:I("GAPI_HINT_PARAMS",void 0),innertubeApiKey:I("INNERTUBE_API_KEY",void 0),innertubeApiVersion:I("INNERTUBE_API_VERSION",void 0),Ma:I("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),innertubeContextClientVersion:I("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),Oa:I("INNERTUBE_CONTEXT_HL",void 0),Na:I("INNERTUBE_CONTEXT_GL",void 0),kb:I("XHR_APIARY_HOST",
void 0)}}
;function Wc(a){D.call(this);this.g=a;this.g.subscribe("command",this.xa,this);this.i={};this.j=!1}
w(Wc,D);l=Wc.prototype;l.start=function(){this.j||this.f||(this.j=!0,Xc(this.g,"RECEIVING"))};
l.xa=function(a,b){if(this.j&&!this.f){var c=b||{};switch(a){case "addEventListener":if(t(c.event)&&(c=c.event,!(c in this.i))){var d=u(this.bb,this,c);this.i[c]=d;this.addEventListener(c,d)}break;case "removeEventListener":t(c.event)&&Yc(this,c.event);break;default:this.b.isReady()&&this.b[a]&&(c=Zc(a,b||{}),c=this.b[a].apply(this.b,c),(c=$c(a,c))&&this.j&&!this.f&&Xc(this.g,a,c))}}};
l.bb=function(a,b){this.j&&!this.f&&Xc(this.g,a,this.ha(a,b))};
l.ha=function(a,b){if(null!=b)return{value:b}};
function Yc(a,b){b in a.i&&(a.removeEventListener(b,a.i[b]),delete a.i[b])}
l.o=function(){var a=this.g;a.f||ad(a.b,"command",this.xa,this);this.g=null;for(var b in this.i)Yc(this,b);Wc.B.o.call(this)};function bd(a,b,c){var d=[],e=[];if(1==(qa(c)?2:1))return e=[b,a],K(d,function(a){e.push(a)}),cd(e.join(" "));
var f=[],g=[];K(c,function(a){g.push(a.key);f.push(a.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];K(d,function(a){e.push(a)});
a=cd(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function cd(a){var b=Ea();b.update(a);return b.Ga().toLowerCase()}
;var dd=y(J,"perf",z());y(dd,"g",z());var ed=y(dd,"i",z());y(dd,"r",[]);z();z();function fd(a,b,c){b&&0<b.length&&(b=gd(b),c&&0<c.length&&(b+="___"+gd(c)),28<b.length&&(b=b.substr(0,28)+(b.length-28)),c=b,b=y(ed,"_p",z()),y(b,c,z())[a]=(new Date).getTime(),b=dd.r,"function"===typeof b?b(a,"_p",c):b.push([a,"_p",c]))}
function gd(a){return a.join("__").replace(/\./g,"_").replace(/\-/g,"_").replace(/\,/g,"_")}
;function hd(){this.b="";this.f=id}
hd.prototype.ka=!0;hd.prototype.ja=function(){return this.b};
var id={};function jd(){return(F("Chrome")||F("CriOS"))&&!F("Edge")}
;function kd(a){this.b=a}
w(kd,Hc);kd.prototype.set=function(a,b,c){if(b=Jc(b)){if(c){if(c<v()){kd.prototype.remove.call(this,a);return}b.expiration=c}b.creation=v()}kd.B.set.call(this,a,b)};
kd.prototype.f=function(a,b){var c=kd.B.f.call(this,a);if(c){var d;if(d=!b){d=c.creation;var e=c.expiration;d=!!e&&e<v()||!!d&&d>v()}if(d)kd.prototype.remove.call(this,a);else return c}};function ld(){var a=md;try{var b;if(b=!!a&&null!=a.location.href)a:{try{jb(a.foo);b=!0;break a}catch(c){}b=!1}return b}catch(c){return!1}}
function nd(a,b,c){for(var d in a)Object.prototype.hasOwnProperty.call(a,d)&&b.call(c,a[d],d,a)}
;function od(){this.b=I("ALT_PREF_COOKIE_NAME","PREF");var a=Ob.get(""+this.b,void 0);if(a)for(var a=unescape(a).split("&"),b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(O[d]=c.toString())}}
oa(od);var O=r("yt.prefs.UserPrefs.prefs_")||{};q("yt.prefs.UserPrefs.prefs_",O,void 0);function pd(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function qd(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function rd(a){a=void 0!==O[a]?O[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
od.prototype.get=function(a,b){qd(a);pd(a);var c=void 0!==O[a]?O[a].toString():null;return null!=c?c:b?b:""};
od.prototype.set=function(a,b){qd(a);pd(a);if(null==b)throw Error("ExpectedNotNull");O[a]=b.toString()};
od.prototype.remove=function(a){qd(a);pd(a);delete O[a]};
od.prototype.clear=function(){O={}};function P(a,b){sa(a)&&(a=Rc(a));return window.setTimeout(a,b)}
;function sd(a){"?"==a.charAt(0)&&(a=a.substr(1));a=a.split("&");for(var b={},c=0,d=a.length;c<d;c++){var e=a[c].split("=");if(1==e.length&&e[0]||2==e.length){var f=decodeURIComponent((e[0]||"").replace(/\+/g," ")),e=decodeURIComponent((e[1]||"").replace(/\+/g," "));f in b?qa(b[f])?zc(b[f],e):b[f]=[b[f],e]:b[f]=e}}return b}
function td(a,b){var c=a.split("#",2);a=c[0];var c=1<c.length?"#"+c[1]:"",d=a.split("?",2);a=d[0];var d=sd(d[1]||""),e;for(e in b)d[e]=b[e];return Mc(Pc([a],d))+c}
function ud(a){a=Pc([],a);a[0]="";return a.join("")}
;var vd=v().toString();var wd=z(),xd=[];function Q(a){throw Error("Bad hint"+(a?": "+a:""));}
xd.push(["jsl",function(a){for(var b in a)if(Object.prototype.hasOwnProperty.call(a,b)){var c=a[b];"object"==typeof c?J[b]=y(J,b,[]).concat(c):y(J,b,c)}if(b=a.u)a=y(J,"us",[]),a.push(b),(b=/^https:(.*)$/.exec(b))&&a.push("http:"+b[1])}]);
var yd=/^(\/[a-zA-Z0-9_\-]+)+$/,zd=[/\/amp\//,/\/amp$/,/^\/amp$/],Ad=/^[a-zA-Z0-9\-_\.,!]+$/,Bd=/^gapi\.loaded_[0-9]+$/,Cd=/^[a-zA-Z0-9,._-]+$/;function Dd(a,b,c,d){var e=a.split(";"),f=e.shift(),g=wd[f],h=null;g?h=g(e,b,c,d):Q("no hint processor for: "+f);h||Q("failed to generate load url");b=h;c=b.match(Ed);(d=b.match(Fd))&&1===d.length&&Gd.test(b)&&c&&1===c.length||Q("failed sanity: "+a);return h}
function Hd(a,b,c,d){function e(a){return encodeURIComponent(a).replace(/%2C/g,",")}
a=Id(a);Bd.test(c)||Q("invalid_callback");b=Jd(b);d=d&&d.length?Jd(d):null;return[encodeURIComponent(a.Ya).replace(/%2C/g,",").replace(/%2F/g,"/"),"/k=",e(a.version),"/m=",e(b),d?"/exm="+e(d):"","/rt=j/sv=1/d=1/ed=1",a.ra?"/am="+e(a.ra):"",a.ya?"/rs="+e(a.ya):"",a.Ca?"/t="+e(a.Ca):"","/cb=",e(c)].join("")}
function Id(a){"/"!==a.charAt(0)&&Q("relative path");for(var b=a.substring(1).split("/"),c=[];b.length;){a=b.shift();if(!a.length||0==a.indexOf("."))Q("empty/relative directory");else if(0<a.indexOf("=")){b.unshift(a);break}c.push(a)}a={};for(var d=0,e=b.length;d<e;++d){var f=b[d].split("="),g=decodeURIComponent(f[0]),h=decodeURIComponent(f[1]);2==f.length&&g&&h&&(a[g]=a[g]||h)}b="/"+c.join("/");yd.test(b)||Q("invalid_prefix");c=0;for(d=zd.length;c<d;++c)zd[c].test(b)&&Q("invalid_prefix");c=Kd(a,
"k",!0);d=Kd(a,"am");e=Kd(a,"rs");a=Kd(a,"t");return{Ya:b,version:c,ra:d,ya:e,Ca:a}}
function Jd(a){for(var b=[],c=0,d=a.length;c<d;++c){var e=a[c].replace(/\./g,"_").replace(/-/g,"_");Cd.test(e)&&b.push(e)}return b.join(",")}
function Kd(a,b,c){a=a[b];!a&&c&&Q("missing: "+b);if(a){if(Ad.test(a))return a;Q("invalid: "+b)}return null}
var Gd=/^https?:\/\/[a-z0-9_.-]+\.google\.com(:\d+)?\/[a-zA-Z0-9_.,!=\-\/]+$/,Fd=/\/cb=/g,Ed=/\/\//g;function Ld(){var a=rc();if(!a)throw Error("Bad hint");return a}
wd.m=function(a,b,c,d){(a=a[0])||Q("missing_hint");return"https://apis.google.com"+Hd(a,b,c,d)};
var Md=decodeURI("%73cript"),Nd=/^[-+_0-9\/A-Za-z]+={0,2}$/;function Od(a,b){for(var c=[],d=0;d<a.length;++d){var e=a[d];e&&0>Ka.call(b,e)&&c.push(e)}return c}
function Pd(){var a=J.nonce;if(void 0!==a)return a&&a===String(a)&&a.match(Nd)?a:J.nonce=null;var b=y(J,"us",[]);if(!b||!b.length)return J.nonce=null;for(var c=Ga.getElementsByTagName(Md),d=0,e=c.length;d<e;++d){var f=c[d];if(f.src&&(a=String(f.nonce||f.getAttribute("nonce")||"")||null)){for(var g=0,h=b.length;g<h&&b[g]!==f.src;++g);if(g!==h&&a&&a===String(a)&&a.match(Nd))return J.nonce=a}}return null}
function Qd(a){if("loading"!=Ga.readyState)Rd(a);else{var b=Pd(),c="";null!==b&&(c=' nonce="'+b+'"');Ga.write("<"+Md+' src="'+encodeURI(a)+'"'+c+"></"+Md+">")}}
function Rd(a){var b=Ga.createElement(Md);b.setAttribute("src",a);a=Pd();null!==a&&b.setAttribute("nonce",a);b.async="true";(a=Ga.getElementsByTagName(Md)[0])?a.parentNode.insertBefore(b,a):(Ga.head||Ga.body||Ga.documentElement).appendChild(b)}
function Sd(a,b){var c=b&&b._c;if(c)for(var d=0;d<xd.length;d++){var e=xd[d][0],f=xd[d][1];f&&Object.prototype.hasOwnProperty.call(c,e)&&f(c[e],a,b)}}
function Td(a,b,c){Ud(function(){var c;c=b===rc()?y(Ma,"_",z()):z();c=y(tc(b),"_",c);a(c)},c)}
function Vd(a,b){var c=b||{};"function"==typeof b&&(c={},c.callback=b);Sd(a,c);var d=a?a.split(":"):[],e=c.h||Ld(),f=y(J,"ah",z());if(f["::"]&&d.length){for(var g=[],h=null;h=d.shift();){var k=h.split("."),k=f[h]||f[k[1]&&"ns:"+k[0]||""]||e,n=g.length&&g[g.length-1]||null,A=n;n&&n.hint==k||(A={hint:k,features:[]},g.push(A));A.features.push(h)}var H=g.length;if(1<H){var ea=c.callback;ea&&(c.callback=function(){0==--H&&ea()})}for(;d=g.shift();)Wd(d.features,c,d.hint)}else Wd(d||[],c,e)}
function Wd(a,b,c){function d(a,b){if(H)return 0;Fa.clearTimeout(A);ea.push.apply(ea,aa);var d=((Ma||{}).config||{}).update;d?d(f):f&&y(J,"cu",[]).push(f);if(b){fd("me0",a,Z);try{Td(b,c,n)}finally{fd("me1",a,Z)}}return 1}
a=La(a)||[];var e=b.callback,f=b.config,g=b.timeout,h=b.ontimeout,k=b.onerror,n=void 0;"function"==typeof k&&(n=k);var A=null,H=!1;if(g&&!h||!g&&h)throw"Timeout requires both the timeout parameter and ontimeout parameter to be set";var k=y(tc(c),"r",[]).sort(),ea=y(tc(c),"L",[]).sort(),Z=[].concat(k);0<g&&(A=Fa.setTimeout(function(){H=!0;h()},g));
var aa=Od(a,ea);if(aa.length){var aa=Od(a,k),ka=y(J,"CP",[]),la=ka.length;ka[la]=function(a){function b(){var a=ka[la+1];a&&a()}
function c(b){ka[la]=null;d(aa,a)&&sc(function(){e&&e();b()})}
if(!a)return 0;fd("ml1",aa,Z);0<la&&ka[la-1]?ka[la]=function(){c(b)}:c(b)};
if(aa.length){var Ec="loaded_"+J.I++;Ma[Ec]=function(a){ka[la](a);Ma[Ec]=null};
a=Dd(c,aa,"gapi."+Ec,k);k.push.apply(k,aa);fd("ml0",aa,Z);b.sync||Fa.___gapisync?Qd(a):Rd(a)}else ka[la](Ia)}else d(aa)&&e&&e()}
function Ud(a,b){if(J.hee&&0<J.hel)try{return a()}catch(c){b&&b(c),J.hel--,Vd("debug_error",function(){try{window.___jsl.hefn(c)}catch(d){throw c;}})}else try{return a()}catch(c){throw b&&b(c),c;
}}
Ma.load=function(a,b){return Ud(function(){return Vd(a,b)})};function Xd(a){m.setTimeout(function(){throw a;},0)}
var Yd;
function Zd(){var a=m.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!F("Presto")&&(a=function(){var a=document.createElement("IFRAME");a.style.display="none";a.src="";document.documentElement.appendChild(a);var b=a.contentWindow,a=b.document;a.open();a.write("");a.close();var c="callImmediate"+Math.random(),d="file:"==b.location.protocol?"*":b.location.protocol+"//"+b.location.host,a=u(function(a){if(("*"==d||a.origin==d)&&a.data==
c)this.port1.onmessage()},this);
b.addEventListener("message",a,!1);this.port1={};this.port2={postMessage:function(){b.postMessage(c,d)}}});
if("undefined"!==typeof a&&!F("Trident")&&!F("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(p(c.next)){c=c.next;var a=c.sa;c.sa=null;a()}};
return function(a){d.next={sa:a};d=d.next;b.port2.postMessage(0)}}return"undefined"!==typeof document&&"onreadystatechange"in document.createElement("SCRIPT")?function(a){var b=document.createElement("SCRIPT");
b.onreadystatechange=function(){b.onreadystatechange=null;b.parentNode.removeChild(b);b=null;a();a=null};
document.documentElement.appendChild(b)}:function(a){m.setTimeout(a,0)}}
;function $d(){this.b="";this.f=ae}
$d.prototype.ka=!0;$d.prototype.ja=function(){return this.b};
function be(a){return a instanceof $d&&a.constructor===$d&&a.f===ae?a.b:"type_error:SafeUrl"}
var ce=/^(?:(?:https?|mailto|ftp):|[^&:/?#]*(?:[/?#]|$))/i;function de(a){if(a instanceof $d)return a;a=a.ka?a.ja():String(a);ce.test(a)||(a="about:invalid#zClosurez");return ee(a)}
var ae={};function ee(a){var b=new $d;b.b=a;return b}
ee("about:blank");var fe="StopIteration"in m?m.StopIteration:{message:"StopIteration",stack:""};function ge(){}
ge.prototype.next=function(){throw fe;};
ge.prototype.ba=function(){return this};
function he(a){if(a instanceof ge)return a;if("function"==typeof a.ba)return a.ba(!1);if(ra(a)){var b=0,c=new ge;c.next=function(){for(;;){if(b>=a.length)throw fe;if(b in a)return a[b++];b++}};
return c}throw Error("Not implemented");}
function ie(a,b){if(ra(a))try{K(a,b,void 0)}catch(c){if(c!==fe)throw c;}else{a=he(a);try{for(;;)b.call(void 0,a.next(),void 0,a)}catch(c){if(c!==fe)throw c;}}}
function je(a){if(ra(a))return yc(a);a=he(a);var b=[];ie(a,function(a){b.push(a)});
return b}
;function ke(a,b){this.b=p(a)?a:0;this.f=p(b)?b:0}
ke.prototype.equals=function(a){return a instanceof ke&&(this==a?!0:this&&a?this.b==a.b&&this.f==a.f:!1)};
ke.prototype.ceil=function(){this.b=Math.ceil(this.b);this.f=Math.ceil(this.f);return this};
ke.prototype.floor=function(){this.b=Math.floor(this.b);this.f=Math.floor(this.f);return this};
ke.prototype.round=function(){this.b=Math.round(this.b);this.f=Math.round(this.f);return this};var le=F("Opera"),R=F("Trident")||F("MSIE"),me=F("Edge"),ne=F("Gecko")&&!(-1!=E.toLowerCase().indexOf("webkit")&&!F("Edge"))&&!(F("Trident")||F("MSIE"))&&!F("Edge"),oe=-1!=E.toLowerCase().indexOf("webkit")&&!F("Edge"),pe=F("Macintosh"),qe=F("Windows"),re=F("Android"),se=Gc(),te=F("iPad"),ue=F("iPod");function ve(){var a=m.document;return a?a.documentMode:void 0}
var we;a:{var xe="",ye=function(){var a=E;if(ne)return/rv\:([^\);]+)(\)|;)/.exec(a);if(me)return/Edge\/([\d\.]+)/.exec(a);if(R)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(oe)return/WebKit\/(\S+)/.exec(a);if(le)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
ye&&(xe=ye?ye[1]:"");if(R){var ze=ve();if(null!=ze&&ze>parseFloat(xe)){we=String(ze);break a}}we=xe}var Ae=we,lb={};
function S(a){return kb(a,function(){for(var b=0,c=nb(String(Ae)).split("."),d=nb(String(a)).split("."),e=Math.max(c.length,d.length),f=0;0==b&&f<e;f++){var g=c[f]||"",h=d[f]||"";do{g=/(\d*)(\D*)(.*)/.exec(g)||["","","",""];h=/(\d*)(\D*)(.*)/.exec(h)||["","","",""];if(0==g[0].length&&0==h[0].length)break;b=ob(0==g[1].length?0:parseInt(g[1],10),0==h[1].length?0:parseInt(h[1],10))||ob(0==g[2].length,0==h[2].length)||ob(g[2],h[2]);g=g[3];h=h[3]}while(0==b)}return 0<=b})}
var Be;var Ce=m.document;Be=Ce&&R?ve()||("CSS1Compat"==Ce.compatMode?parseInt(Ae,10):5):void 0;function De(a,b){this.events=[];this.j={};this.b={};this.g=b||m;b&&(b.google_js_reporting_queue=b.google_js_reporting_queue||[],this.events=b.google_js_reporting_queue);this.f=null!=this.g.b?this.g.b:Math.random()<a}
function Wb(){var a=m.performance;return a&&a.now?a.now():v()}
function Ee(a){return"goog_"+a.label+"_"+a.type+"_"+a.eventId}
function Fe(a,b){var c=a.g;c.performance&&c.performance.mark&&c.performance.mark(b)}
function Ge(){var a=He;K(a.events,a.i,a);nd(a.b,function(a){K(a,this.i,this)},a);
a.b={};a.events.length=0;a.f=!1}
De.prototype.i=function(a){a=Ee(a);var b=this.g.performance;b&&b.clearMarks&&(b.clearMarks(a+"_start"),b.clearMarks(a+"_end"))};
De.prototype.start=function(a,b){if(!this.f)return null;var c=(this.j[a]||0)+1;this.j[a]=c;var c=new Vb(a,b,c),d=a+"_"+b;this.b[d]?this.b[d].push(c):this.b[d]=[c];Fe(this,Ee(c)+"_start");return c};
De.prototype.end=function(a,b){if(this.f){var c=a+"_"+b,d=this.b[c];d&&d.length&&(c=this.b[c].pop(),c.duration=Wb()-c.value,Fe(this,Ee(c)+"_end"),this.events.push(c))}};function Ie(a,b,c){isNaN(c)&&(c=void 0);var d=r("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):P(a,c||0)}
function Je(a,b){return Ie(a,1,b)}
;function Ke(a,b){Le||Me();Ne||(Le(),Ne=!0);var c=Oe,d=Fc.get();d.set(a,b);c.f?c.f.next=d:c.b=d;c.f=d}
var Le;function Me(){if(-1!=String(m.Promise).indexOf("[native code]")){var a=m.Promise.resolve(void 0);Le=function(){a.then(Pe)}}else Le=function(){var a=Pe;
!sa(m.setImmediate)||m.Window&&m.Window.prototype&&!F("Edge")&&m.Window.prototype.setImmediate==m.setImmediate?(Yd||(Yd=Zd()),Yd(a)):m.setImmediate(a)}}
var Ne=!1,Oe=new Cc;function Pe(){for(var a;a=Oe.remove();){try{a.b.call(a.scope)}catch(b){Xd(b)}Oa(Fc,a)}Ne=!1}
;!ne&&!R||R&&9<=Number(Be)||ne&&S("1.9.1");R&&S("9");R&&S("9");!oe||S("528");ne&&S("1.9b")||R&&S("8")||le&&S("9.5")||oe&&S("528");ne&&!S("8")||R&&S("9");function Qe(){this.b=""}
Qe.prototype.ka=!0;Qe.prototype.ja=function(){return this.b};
function Re(a){var b=new Qe;b.b=a;return b}
Re("<!DOCTYPE html>");Re("");Re("<br>");function Se(a){this.b=a}
w(Se,kd);function Te(){}
w(Te,mb);Te.prototype.clear=function(){var a=je(this.ba(!0)),b=this;K(a,function(a){b.remove(a)})};(function(){var a;return qe?(a=/Windows NT ([0-9.]+)/,(a=a.exec(E))?a[1]:"0"):pe?(a=/10[_.][0-9_.]+/,(a=a.exec(E))?a[0].replace(/_/g,"."):"10"):re?(a=/Android\s+([^\);]+)(\)|;)/,(a=a.exec(E))?a[1]:""):se||te||ue?(a=/(?:iPhone|CPU)\s+OS\s+(\S+)/,(a=a.exec(E))?a[1].replace(/_/g,"."):""):""})();var Ue=F("Firefox"),Ve=Gc()||F("iPod"),We=F("iPad"),Xe=F("Android")&&!(jd()||F("Firefox")||F("Opera")||F("Silk")),Ye=jd(),Ze=F("Safari")&&!(jd()||F("Coast")||F("Opera")||F("Edge")||F("Silk")||F("Android"))&&!(Gc()||F("iPad")||F("iPod"));function $e(){this.g=this.f=this.b=0;this.i="";var a=r("window.navigator.plugins"),b=r("window.navigator.mimeTypes"),a=a&&a["Shockwave Flash"],b=b&&b["application/x-shockwave-flash"],b=a&&b&&b.enabledPlugin&&a.description||"";if(a=b){var c=a.indexOf("Shockwave Flash");0<=c&&(a=a.substr(c+15));for(var c=a.split(" "),d="",a="",e=0,f=c.length;e<f;e++)if(d)if(a)break;else a=c[e];else d=c[e];d=d.split(".");c=parseInt(d[0],10)||0;d=parseInt(d[1],10)||0;e=0;if("r"==a.charAt(0)||"d"==a.charAt(0))e=parseInt(a.substr(1),
10)||0;a=[c,d,e]}else a=[0,0,0];this.i=b;b=a;this.b=b[0];this.f=b[1];this.g=b[2];if(0>=this.b){var g,h,k,n;if(yb)try{g=new ActiveXObject("ShockwaveFlash.ShockwaveFlash")}catch(A){g=null}else k=document.body,n=document.createElement("object"),n.setAttribute("type","application/x-shockwave-flash"),g=k.appendChild(n);if(g&&"GetVariable"in g)try{h=g.GetVariable("$version")}catch(A){h=""}k&&n&&k.removeChild(n);(g=h||"")?(g=g.split(" ")[1].split(","),g=[parseInt(g[0],10)||0,parseInt(g[1],10)||0,parseInt(g[2],
10)||0]):g=[0,0,0];this.b=g[0];this.f=g[1];this.g=g[2]}}
oa($e);function af(a,b,c,d){b="string"==typeof b?b.split("."):[b,c,d];b[0]=parseInt(b[0],10)||0;b[1]=parseInt(b[1],10)||0;b[2]=parseInt(b[2],10)||0;return a.b>b[0]||a.b==b[0]&&a.f>b[1]||a.b==b[0]&&a.f==b[1]&&a.g>=b[2]}
;var bf;var cf=E,cf=cf.toLowerCase();if(-1!=cf.indexOf("android")){var df=cf.match(/android\D*(\d\.\d)[^\;|\)]*[\;\)]/);if(df)bf=Number(df[1]);else{var ef={cupcake:1.5,donut:1.6,eclair:2,froyo:2.2,gingerbread:2.3,honeycomb:3,"ice cream sandwich":4,jellybean:4.1,kitkat:4.4,lollipop:5.1,marshmallow:6,nougat:7.1},ff=[],gf=0,hf;for(hf in ef)ff[gf++]=hf;var jf=cf.match("("+ff.join("|")+")");bf=jf?ef[jf[0]]:0}}else bf=void 0;function kf(a,b){var c;c=b instanceof $d?b:de(b);a.href=be(c)}
;function lf(a){mf();var b=new hd;b.b=a;return b}
var mf=na;function T(a,b){this.b=0;this.w=void 0;this.i=this.f=this.g=null;this.j=this.l=!1;if(a!=na)try{var c=this;a.call(b,function(a){nf(c,2,a)},function(a){nf(c,3,a)})}catch(d){nf(this,3,d)}}
function of(){this.next=this.context=this.f=this.g=this.b=null;this.i=!1}
of.prototype.reset=function(){this.context=this.f=this.g=this.b=null;this.i=!1};
var pf=new Na(function(){return new of},function(a){a.reset()},100);
function qf(a,b,c){var d=pf.get();d.g=a;d.f=b;d.context=c;return d}
function rf(a){if(a instanceof T)return a;var b=new T(na);nf(b,2,a);return b}
function sf(a){return new T(function(b,c){c(a)})}
T.prototype.then=function(a,b,c){return tf(this,sa(a)?a:null,sa(b)?b:null,c)};
ib(T);T.prototype.cancel=function(a){0==this.b&&Ke(function(){var b=new uf(a);vf(this,b)},this)};
function vf(a,b){if(0==a.b)if(a.g){var c=a.g;if(c.f){for(var d=0,e=null,f=null,g=c.f;g&&(g.i||(d++,g.b==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.b&&1==d?vf(c,b):(f?(d=f,d.next==c.i&&(c.i=d),d.next=d.next.next):wf(c),xf(c,e,3,b)))}a.g=null}else nf(a,3,b)}
function yf(a,b){a.f||2!=a.b&&3!=a.b||zf(a);a.i?a.i.next=b:a.f=b;a.i=b}
function tf(a,b,c,d){var e=qf(null,null,null);e.b=new T(function(a,g){e.g=b?function(c){try{var e=b.call(d,c);a(e)}catch(n){g(n)}}:a;
e.f=c?function(b){try{var e=c.call(d,b);!p(e)&&b instanceof uf?g(b):a(e)}catch(n){g(n)}}:g});
e.b.g=a;yf(a,e);return e.b}
T.prototype.C=function(a){this.b=0;nf(this,2,a)};
T.prototype.G=function(a){this.b=0;nf(this,3,a)};
function nf(a,b,c){if(0==a.b){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.b=1;var d;a:{var e=c,f=a.C,g=a.G;if(e instanceof T)yf(e,qf(f||na,g||null,a)),d=!0;else{var h;if(e)try{h=!!e.$goog_Thenable}catch(n){h=!1}else h=!1;if(h)e.then(f,g,a),d=!0;else{if(ta(e))try{var k=e.then;if(sa(k)){Af(e,k,f,g,a);d=!0;break a}}catch(n){g.call(a,n);d=!0;break a}d=!1}}}d||(a.w=c,a.b=b,a.g=null,zf(a),3!=b||c instanceof uf||Bf(a,c))}}
function Af(a,b,c,d,e){function f(a){h||(h=!0,d.call(e,a))}
function g(a){h||(h=!0,c.call(e,a))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function zf(a){a.l||(a.l=!0,Ke(a.D,a))}
function wf(a){var b=null;a.f&&(b=a.f,a.f=b.next,b.next=null);a.f||(a.i=null);return b}
T.prototype.D=function(){for(var a;a=wf(this);)xf(this,a,this.b,this.w);this.l=!1};
function xf(a,b,c,d){if(3==c&&b.f&&!b.i)for(;a&&a.j;a=a.g)a.j=!1;if(b.b)b.b.g=null,Cf(b,c,d);else try{b.i?b.g.call(b.context):Cf(b,c,d)}catch(e){Df.call(null,e)}Oa(pf,b)}
function Cf(a,b,c){2==b?a.g.call(a.context,c):a.f&&a.f.call(a.context,c)}
function Bf(a,b){a.j=!0;Ke(function(){a.j&&Df.call(null,b)})}
var Df=Xd;function uf(a){Pa.call(this,a)}
w(uf,Pa);uf.prototype.name="cancel";function U(a){D.call(this);this.l=1;this.i=[];this.j=0;this.b=[];this.g={};this.w=!!a}
w(U,D);l=U.prototype;l.subscribe=function(a,b,c){var d=this.g[a];d||(d=this.g[a]=[]);var e=this.l;this.b[e]=a;this.b[e+1]=b;this.b[e+2]=c;this.l=e+3;d.push(e);return e};
function ad(a,b,c,d){if(b=a.g[b]){var e=a.b;(b=wc(b,function(a){return e[a+1]==c&&e[a+2]==d}))&&a.L(b)}}
l.L=function(a){var b=this.b[a];if(b){var c=this.g[b];0!=this.j?(this.i.push(a),this.b[a+1]=na):(c&&xc(c,a),delete this.b[a],delete this.b[a+1],delete this.b[a+2])}return!!b};
l.V=function(a,b){var c=this.g[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.w)for(e=0;e<c.length;e++){var g=c[e];Ef(this.b[g+1],this.b[g+2],d)}else{this.j++;try{for(e=0,f=c.length;e<f;e++)g=c[e],this.b[g+1].apply(this.b[g+2],d)}finally{if(this.j--,0<this.i.length&&0==this.j)for(;c=this.i.pop();)this.L(c)}}return 0!=e}return!1};
function Ef(a,b,c){Ke(function(){a.apply(b,c)})}
l.clear=function(a){if(a){var b=this.g[a];b&&(K(b,this.L,this),delete this.g[a])}else this.b.length=0,this.g={}};
l.o=function(){U.B.o.call(this);this.clear();this.i.length=0};function Ff(a){this.b=a}
w(Ff,Te);l=Ff.prototype;l.isAvailable=function(){if(!this.b)return!1;try{return this.b.setItem("__sak","1"),this.b.removeItem("__sak"),!0}catch(a){return!1}};
l.set=function(a,b){try{this.b.setItem(a,b)}catch(c){if(0==this.b.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
l.get=function(a){a=this.b.getItem(a);if(!t(a)&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.b.removeItem(a)};
l.ba=function(a){var b=0,c=this.b,d=new ge;d.next=function(){if(b>=c.length)throw fe;var d=c.key(b++);if(a)return d;d=c.getItem(d);if(!t(d))throw"Storage mechanism: Invalid value was encountered";return d};
return d};
l.clear=function(){this.b.clear()};
l.key=function(a){return this.b.key(a)};function Gf(a){return(a=a.exec(E))?a[1]:""}
(function(){if(Ue)return Gf(/Firefox\/([0-9.]+)/);if(R||me||le)return Ae;if(Ye)return Gf(/Chrome\/([0-9.]+)/);if(Ze&&!(Gc()||F("iPad")||F("iPod")))return Gf(/Version\/([0-9.]+)/);if(Ve||We){var a=/Version\/(\S+).*Mobile\/(\S+)/.exec(E);if(a)return a[1]+"."+a[2]}else if(Xe)return(a=Gf(/Android\s+([0-9.]+)/))?a:Gf(/Version\/([0-9.]+)/);return""})();function Hf(a,b,c,d){D.call(this);this.i=b||null;this.C="*";this.j=c||null;this.b=null;this.channel=d||null;this.K=!!a;this.D=u(this.J,this);window.addEventListener("message",this.D)}
ba(Hf,D);Hf.prototype.J=function(a){if(!("*"!=this.j&&a.origin!=this.j||this.i&&a.source!=this.i)&&t(a.data)){var b;try{b=Ra(a.data)}catch(c){return}if(!(null==b||this.K&&(this.b&&this.b!=b.id||this.channel&&this.channel!=b.channel))&&b)switch(b.event){case "listening":"null"!=a.origin?this.j=this.C=a.origin:M(Error("MessageEvent origin is null"),"WARNING");this.i=a.source;this.b=b.id;this.g&&(this.g(),this.g=null);break;case "command":this.l&&(this.w&&!(0<=uc(this.w,b.func))||this.l(b.func,b.args))}}};
Hf.prototype.sendMessage=function(a,b){var c=b||this.i;if(c){this.b&&(a.id=this.b);this.channel&&(a.channel=this.channel);try{var d=Ta(a);c.postMessage(d,this.C)}catch(e){M(e,"WARNING")}}};
Hf.prototype.o=function(){window.removeEventListener("message",this.D);D.prototype.o.call(this)};var If;var Jf=E,Kf=Jf.match(/\((iPad|iPhone|iPod)( Simulator)?;/);if(!Kf||2>Kf.length)If=void 0;else{var Lf=Jf.match(/\((iPad|iPhone|iPod)( Simulator)?; (U; )?CPU (iPhone )?OS (\d+_\d)[_ ]/);If=Lf&&6==Lf.length?Number(Lf[5].replace("_",".")):0}0<=If&&0<=E.search("Safari")&&E.search("Version");function Mf(a){var b=document;return t(a)?b.getElementById(a):a}
function Nf(a){if(!a)return null;if(a.firstChild)return a.firstChild;for(;a&&!a.nextSibling;)a=a.parentNode;return a?a.nextSibling:null}
function Of(a){if(!a)return null;if(!a.previousSibling)return a.parentNode;for(a=a.previousSibling;a&&a.lastChild;)a=a.lastChild;return a}
function Pf(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Qf(){var a=null;try{a=window.localStorage||null}catch(b){}this.b=a}
w(Qf,Ff);function Rf(){var a=null;try{a=window.sessionStorage||null}catch(b){}this.b=a}
w(Rf,Ff);function Sf(a){this.b=a||Vc();Tf||(Tf=Uf(this.b))}
function Uf(a){return(new T(function(b){try{var c={gapiHintOverride:a.gapiHintOverride,_c:{jsl:{h:a.gapiHintParams}},callback:b},d=sa(c)?{callback:c}:c||{};d._c&&d._c.jsl&&d._c.jsl.h||hb(d,{_c:{jsl:{h:I("GAPI_HINT_PARAMS",void 0)}}});if(d.gapiHintOverride||I("GAPI_HINT_OVERRIDE")){var e;var f=document.location.href;if(-1!=f.indexOf("?")){var f=(f||"").split("#")[0],g=f.split("?",2);e=sd(1<g.length?g[1]:g[0])}else e={};var h=e.gapi_jsh;h&&hb(d,{_c:{jsl:{h:h}}})}Vd("client",d)}catch(k){M(k)}})).then(function(){})}
Sf.prototype.i=function(){var a=r("gapi.config.update");a("googleapis.config/auth/useFirstPartyAuth",!0);var b=this.b.apiaryHost;/^[\s\xa0]*$/.test(null==b?"":String(b))||a("googleapis.config/root",(-1==b.indexOf("://")?"//":"")+b);b=this.b.Ea;/^[\s\xa0]*$/.test(null==b?"":String(b))||a("googleapis.config/root-1p",(-1==b.indexOf("://")?"//":"")+b);b=I("SESSION_INDEX");a("googleapis.config/sessionIndex",b);r("gapi.client.setApiKey")(this.b.innertubeApiKey)};
Sf.prototype.f=function(){return{context:Uc(this.b)}};
Sf.prototype.g=function(a,b,c){var d,e=!1;0<c.timeout&&(d=P(function(){e||(e=!0,c.N&&c.N())},c.timeout));
Vf(this,a,b,function(a){if(!e)if(e=!0,d&&window.clearTimeout(d),a)c.F&&c.F(a);else if(c.onError)c.onError()})};
function Vf(a,b,c,d){var e={path:"/youtubei/"+a.b.innertubeApiVersion+"/"+b,headers:{"X-Goog-Visitor-Id":I("VISITOR_DATA")},method:"POST",body:Ta(c)},f=u(a.i,a);Tf.then(function(){f();r("gapi.client.request")(e).execute(d||na)})}
var Tf=null;function Wf(){D.call(this);this.b=new U;Ib(this,za(Jb,this.b))}
w(Wf,D);Wf.prototype.subscribe=function(a,b,c){return this.f?0:this.b.subscribe(a,b,c)};
Wf.prototype.L=function(a){return this.f?!1:this.b.L(a)};
Wf.prototype.l=function(a,b){this.f||this.b.V.apply(this.b,arguments)};var Xf=r("yt.pubsub.instance_")||new U;U.prototype.subscribe=U.prototype.subscribe;U.prototype.unsubscribeByKey=U.prototype.L;U.prototype.publish=U.prototype.V;U.prototype.clear=U.prototype.clear;q("yt.pubsub.instance_",Xf,void 0);var Yf=r("yt.pubsub.subscribedKeys_")||{};q("yt.pubsub.subscribedKeys_",Yf,void 0);var Zf=r("yt.pubsub.topicToKeys_")||{};q("yt.pubsub.topicToKeys_",Zf,void 0);var $f=r("yt.pubsub.isSynchronous_")||{};q("yt.pubsub.isSynchronous_",$f,void 0);
var ag=r("yt.pubsub.skipSubId_")||null;q("yt.pubsub.skipSubId_",ag,void 0);function bg(a,b){var c=cg();if(c){var d=c.subscribe(a,function(){if(!ag||ag!=d){var c=arguments,f;f=function(){Yf[d]&&b.apply(window,c)};
try{$f[a]?f():P(f,0)}catch(g){M(g)}}},void 0);
Yf[d]=!0;Zf[a]||(Zf[a]=[]);Zf[a].push(d);return d}return 0}
function dg(a){var b=cg();b&&("number"==typeof a?a=[a]:"string"==typeof a&&(a=[parseInt(a,10)]),K(a,function(a){b.unsubscribeByKey(a);delete Yf[a]}))}
function eg(a,b){var c=cg();return c?c.publish.apply(c,arguments):!1}
function fg(a){Zf[a]&&(a=Zf[a],K(a,function(a){Yf[a]&&delete Yf[a]}),a.length=0)}
function gg(a){var b=cg();if(b)if(b.clear(a),a)fg(a);else for(var c in Zf)fg(c)}
function cg(){return r("yt.pubsub.instance_")}
;var hg=r("yt.pubsub2.instance_")||new U;U.prototype.subscribe=U.prototype.subscribe;U.prototype.unsubscribeByKey=U.prototype.L;U.prototype.publish=U.prototype.V;U.prototype.clear=U.prototype.clear;q("yt.pubsub2.instance_",hg,void 0);var ig=r("yt.pubsub2.subscribedKeys_")||{};q("yt.pubsub2.subscribedKeys_",ig,void 0);var jg=r("yt.pubsub2.topicToKeys_")||{};q("yt.pubsub2.topicToKeys_",jg,void 0);var kg=r("yt.pubsub2.isAsync_")||{};q("yt.pubsub2.isAsync_",kg,void 0);q("yt.pubsub2.skipSubKey_",null,void 0);
function V(a,b){var c=lg();c&&c.publish.call(c,a.toString(),a,b)}
function W(a,b){var c=lg();if(!c)return 0;var d=c.subscribe(a.toString(),function(c,f){if(!window.yt.pubsub2.skipSubKey_||window.yt.pubsub2.skipSubKey_!=d){var e=function(){if(ig[d])try{if(f&&a instanceof C&&a!=c)try{f=Gb(a.b,f)}catch(h){throw h.message="yt.pubsub2 cross-binary conversion error for "+a.toString()+": "+h.message,h;}b.call(window,f)}catch(h){M(h)}};
kg[a.toString()]?r("yt.scheduler.instance")?Je(e):P(e,0):e()}});
ig[d]=!0;jg[a.toString()]||(jg[a.toString()]=[]);jg[a.toString()].push(d);return d}
function mg(a){var b=lg();b&&("number"==typeof a&&(a=[a]),K(a,function(a){b.unsubscribeByKey(a);delete ig[a]}))}
function lg(){return r("yt.pubsub2.instance_")}
;function ng(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var og=0,pg=r("yt.dom.dom.getNextId")||function(){return++og};
q("yt.dom.dom.getNextId",pg,void 0);function qg(a,b,c){Hf.call(this,a,b,c||I("POST_MESSAGE_ORIGIN",void 0)||window.document.location.protocol+"//"+window.document.location.hostname,"widget");this.w=this.g=this.l=null}
ba(qg,Hf);var rg={log_event:"events",log_interaction:"interactions"},sg={},tg={},ug=0,db=r("yt.logging.transport.logsQueue_")||{};q("yt.logging.transport.logsQueue_",db,void 0);function vg(a,b){db[a.endpoint]=db[a.endpoint]||[];var c=db[a.endpoint];c.push(a.va);tg[a.endpoint]=b;var d=Number(N("web_logging_max_batch")||0)||20;c.length>=d?wg():xg()}
function wg(){window.clearTimeout(ug);if(!cb()){for(var a in db){var b=sg[a];if(!b){b=tg[a];if(!b)continue;b=new b;sg[a]=b}var c=b.f();c.requestTimeMs=Math.round(xb());c[rg[a]]=db[a];b.g(a,c,{});delete db[a]}cb()||xg()}}
function xg(){window.clearTimeout(ug);ug=P(wg,I("LOGGING_BATCH_TIMEOUT",1E4))}
;var yg=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,zg=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Ag(a,b){var c=Bg(a),d=document.getElementById(c),e=d&&tb(d,"loaded"),f=d&&!e;if(e)b&&b();else{if(b){var e=bg(c,b),g=""+ua(b);Cg[g]=e}f||(d=Dg(a,c,function(){tb(d,"loaded")||(ub(d),eg(c),P(za(gg,c),0))}))}}
function Dg(a,b,c){var d=document.createElement("script");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
d.onreadystatechange=function(){switch(d.readyState){case "loaded":case "complete":d.onload()}};
d.src=a;a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(d,a.firstChild);return d}
function Eg(a,b){if(a&&b){var c=""+ua(b);(c=Cg[c])&&dg(c)}}
function Bg(a){var b=document.createElement("a");kf(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+pb(a)}
var Cg={};function Fg(a,b){if(window.spf){var c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(yg,""),c=c.replace(zg,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Ag(a,b)}
;var Gg=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function Hg(a){if(window.spf){var b=a.match(Gg);spf.style.load(a,b?b[1]:"",void 0)}else Ig(a)}
function Ig(a){var b=Jg(a),c=document.getElementById(b),d=c&&tb(c,"loaded");d||c&&!d||(c=Kg(a,b,function(){tb(c,"loaded")||(ub(c),eg(b),P(za(gg,b),0))}))}
function Kg(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=lf(a);d.rel="stylesheet";d.href=a instanceof hd&&a.constructor===hd&&a.f===id?a.b:"type_error:TrustedResourceUrl";(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function Jg(a){var b=document.createElement("a");kf(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+pb(a)}
;function Lg(){if(!Mg&&!Ng||!window.JSON)return null;var a;try{a=Mg.get("yt-player-two-stage-token")}catch(b){}if(!t(a))try{a=Ng.get("yt-player-two-stage-token")}catch(b){}if(!t(a))return null;try{a=JSON.parse(a,void 0)}catch(b){}return a}
var Ng,Og=new Qf;Ng=Og.isAvailable()?new Se(Og):null;var Mg,Pg=new Rf;Mg=Pg.isAvailable()?new Se(Pg):null;function Qg(a,b,c){Wf.call(this);this.g=a;this.i=b;this.j=c}
w(Qg,Wf);function Xc(a,b,c){if(!a.f){var d=a.g;d.f||a.i!=d.b||(a={id:a.j,command:b},c&&(a.data=c),d.b.postMessage(Ta(a),d.i))}}
Qg.prototype.o=function(){this.i=this.g=null;Qg.B.o.call(this)};function Rg(a){var b=Qc("/signin?context=popup","next",document.location.protocol+"//"+document.domain+"/post_login"),b=Qc(b,"feature","sub_button");if(b=window.open(b,"loginPopup","width=375,height=440,resizable=yes,scrollbars=yes",!0)){var c=bg("LOGGED_IN",function(b){dg(I("LOGGED_IN_PUBSUB_KEY",void 0));G("LOGGED_IN",!0);a(b)});
G("LOGGED_IN_PUBSUB_KEY",c);b.moveTo((screen.width-375)/2,(screen.height-440)/2)}}
q("yt.pubsub.publish",eg,void 0);var Sg=!!window.google_async_iframe_id,md=Sg&&window.parent||window;var Tg=null;function Ug(){var a=I("BG_I",null),b=I("BG_IU",null),c=I("BG_P",void 0);b?Fg(b,function(){Tg=new botguard.bg(c)}):a&&(eval(a),Tg=new botguard.bg(c))}
function Vg(){return null!=Tg}
function Wg(){return Tg?Tg.invoke():null}
;var Xg=[],Yg=!1;function Zg(){function a(){Yg=!0;"google_ad_status"in window?G("DCLKSTAT",1):G("DCLKSTAT",2)}
Fg("//static.doubleclick.net/instream/ad_status.js",a);Xg.push(Je(function(){Yg||"google_ad_status"in window||(Eg("//static.doubleclick.net/instream/ad_status.js",a),G("DCLKSTAT",3))},5E3))}
function $g(){return parseInt(I("DCLKSTAT",0),10)}
;var bb=r("yt.events.events.listeners_")||{};q("yt.events.events.listeners_",bb,void 0);var ah=r("yt.events.events.counter_")||{count:0};q("yt.events.events.counter_",ah,void 0);function bh(a,b,c){a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return ab(function(d){return d[0]==a&&d[1]==b&&d[2]==c&&0==d[4]})}
function ch(a,b,c){if(!a||!a.addEventListener&&!a.attachEvent)return"";var d=bh(a,b,c);if(d)return d;var d=++ah.count+"",e=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document),f;f=e?function(d){d=new vb(d);if(!Pf(d.relatedTarget,function(b){return b==a}))return d.currentTarget=a,d.type=b,c.call(a,d)}:function(b){b=new vb(b);
b.currentTarget=a;return c.call(a,b)};
f=Rc(f);a.addEventListener?("mouseenter"==b&&e?b="mouseover":"mouseleave"==b&&e?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),a.addEventListener(b,f,!1)):a.attachEvent("on"+b,f);bb[d]=[a,b,c,f,!1];return d}
function dh(a){a&&("string"==typeof a&&(a=[a]),K(a,function(a){if(a in bb){var b=bb[a],d=b[0],e=b[1],f=b[3],b=b[4];d.removeEventListener?d.removeEventListener(e,f,b):d.detachEvent&&d.detachEvent("on"+e,f);delete bb[a]}}))}
;function eh(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Rc(b)(k)}
var k=Db&&Db();if(!("open"in k))return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;c=(c||"GET").toUpperCase();d=d||"";k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);f="POST"==c;if(e=fh(a,e))for(var n in e)k.setRequestHeader(n,e[n]),"content-type"==n.toLowerCase()&&(f=!1);f&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);return k}
function fh(a,b){b=b||{};var c;c=void 0;c=window.location.href;var d=L(a)[1]||null,e=Lc(L(a)[3]||null);d&&e?(d=c,c=L(a),d=L(d),c=c[3]==d[3]&&c[1]==d[1]&&c[4]==d[4]):c=e?Lc(L(c)[3]||null)==e&&(Number(L(c)[4]||null)||null)==(Number(L(a)[4]||null)||null):!0;for(var f in gh){if((e=d=I(gh[f]))&&!(e=c)){var g=a,e=f,h=I("CORS_HEADER_WHITELIST")||{};e=(g=Lc(L(g)[3]||null))?(h=h[g])?0<=uc(h,e):!1:!0}e&&(b[f]=d)}return b}
function hh(a,b){b.method="POST";b.A||(b.A={});ih(a,b)}
function jh(a,b){var c=I("XSRF_FIELD_NAME",void 0),d;b.headers&&(d=b.headers["Content-Type"]);return!b.ob&&(!Lc(L(a)[3]||null)||b.withCredentials||Lc(L(a)[3]||null)==document.location.hostname)&&"POST"==b.method&&(!d||"application/x-www-form-urlencoded"==d)&&!(b.A&&b.A[c])}
function ih(a,b){var c=b.format||"JSON";b.La&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var d=I("XSRF_FIELD_NAME",void 0),e=I("XSRF_TOKEN",void 0),f=b.na;f&&(f[d]&&delete f[d],a=td(a,f||{}));var g=b.postBody||"",f=b.A;jh(a,b)&&(f||(f={}),f[d]=e);f&&t(g)&&(d=sd(g),hb(d,f),g=b.wa&&"JSON"==b.wa?JSON.stringify(d):ud(d));var h=!1,k,n=eh(a,function(a){if(!h){h=!0;k&&window.clearTimeout(k);var d=Eb(a),e=null;if(d||400<=a.status&&
500>a.status)e=kh(c,a,b.nb);if(d)a:if(204==a.status)d=!0;else{switch(c){case "XML":d=0==parseInt(e&&e.return_code,10);break a;case "RAW":d=!0;break a}d=!!e}var e=e||{},f=b.context||m;d?b.F&&b.F.call(f,a,e):b.onError&&b.onError.call(f,a,e);b.ma&&b.ma.call(f,a,e)}},b.method,g,b.headers,b.responseType,b.withCredentials);
b.N&&0<b.timeout&&(k=P(function(){h||(h=!0,n.abort(),window.clearTimeout(k),b.N.call(b.context||m,n))},b.timeout))}
function kh(a,b,c){var d=null;switch(a){case "JSON":a=b.responseText;b=b.getResponseHeader("Content-Type")||"";a&&0<=b.indexOf("json")&&(d=Sa(a));break;case "XML":if(b=(b=b.responseXML)?lh(b):null)d={},K(b.getElementsByTagName("*"),function(a){d[a.tagName]=mh(a)})}c&&nh(d);
return d}
function nh(a){if(ta(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d;d=Re(a[b]);a[c]=d}else nh(a[b])}}
function lh(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function mh(a){var b="";K(a.childNodes,function(a){b+=a.nodeValue});
return b}
var gh={"X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"};var oh=['video/mp4; codecs="avc1.42001E, mp4a.40.2"','video/webm; codecs="vp8.0, vorbis"'],ph=['audio/mp4; codecs="mp4a.40.2"'];function qh(){var a=!!I("WIDGET_ID_ENFORCE"),a=this.f=new qg(a),b=u(this.Za,this);a.l=b;a.w=null;this.f.channel="widget";if(a=I("WIDGET_ID"))this.f.b=a;this.i=[];this.l=!1;this.j={}}
l=qh.prototype;l.Za=function(a,b){if("addEventListener"==a&&b){var c=b[0];this.j[c]||"onReady"==c||(this.addEventListener(c,rh(this,c)),this.j[c]=!0)}else this.Ba(a,b)};
l.Ba=function(){};
function rh(a,b){return u(function(a){this.sendMessage(b,a)},a)}
l.addEventListener=function(){};
l.Ha=function(){this.l=!0;this.sendMessage("initialDelivery",this.ia());this.sendMessage("onReady");K(this.i,this.za,this);this.i=[]};
l.ia=function(){return null};
function sh(a,b){a.sendMessage("infoDelivery",b)}
l.za=function(a){this.l?this.f.sendMessage(a):this.i.push(a)};
l.sendMessage=function(a,b){this.za({event:a,info:void 0==b?null:b})};
l.dispose=function(){this.f=null};var th;if(Sg&&!ld()){var uh="."+Ba.domain;try{for(;2<uh.split(".").length&&!ld();)Ba.domain=uh=uh.substr(uh.indexOf(".")+1),md=window.parent}catch(a){}ld()||(md=window)}th=md;var He=new De(1,th);if("complete"==th.document.readyState)th.b||Ge();else if(He.f){var vh=function(){th.b||Ge()};
th.addEventListener?th.addEventListener("load",vh,qb?void 0:!1):th.attachEvent&&th.attachEvent("onload",vh)};function wh(a,b,c,d,e){c={name:c||I("INNERTUBE_CONTEXT_CLIENT_NAME",1),version:d||I("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0)};e=window&&window.yterr||e||!1;if(a&&e&&!(5<=xh)){e=a.stacktrace;d=a.columnNumber;var f=r("window.location.href");if(t(a))a={message:a,name:"Unknown error",lineNumber:"Not available",fileName:f,stack:"Not available"};else{var g,h,k=!1;try{g=a.lineNumber||a.line||"Not available"}catch(H){g="Not available",k=!0}try{h=a.fileName||a.filename||a.sourceURL||m.$googDebugFname||f}catch(H){h=
"Not available",k=!0}a=!k&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name?a:{message:a.message||"Not available",name:a.name||"UnknownError",lineNumber:g,fileName:h,stack:a.stack||"Not available"}}e=e||a.stack;g=a.lineNumber.toString();isNaN(g)||isNaN(d)||(g=g+":"+d);if(!(yh[a.message]||0<=e.indexOf("/YouTubeCenter.js")||0<=e.indexOf("/mytube.js"))){h=a.fileName;b={na:{a:"logerror",t:"jserror",type:a.name,msg:a.message.substr(0,1E3),line:g,level:b||"ERROR"},A:{url:I("PAGE_NAME",window.location.href),
file:h},method:"POST"};e&&(b.A.stack=e);for(var n in c)b.A["client."+n]=c[n];if(n=I("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(var A in n)b.A[A]=n[A];ih("/error_204",b);yh[a.message]=!0;xh++}}}
var yh={},xh=0;function zh(){this.b=Vc()}
zh.prototype.f=function(){return{context:Uc(this.b)}};
zh.prototype.g=function(a,b,c){b={headers:{"Content-Type":"application/json","X-Goog-Visitor-Id":I("VISITOR_DATA")},A:b,wa:"JSON",N:c.N,F:c.F,onError:c.onError,timeout:c.timeout,withCredentials:!0};a:{c=[];var d=Da(String(m.location.href)),e=m.__OVERRIDE_SID;null==e&&(e=(new Nb(document)).get("SID"));if(e&&(d=(e=0==d.indexOf("https:")||0==d.indexOf("chrome-extension:"))?m.__SAPISID:m.__APISID,null==d&&(d=(new Nb(document)).get(e?"SAPISID":"APISID")),d)){var e=e?"SAPISIDHASH":"APISIDHASH",f=String(m.location.href);
c=f&&d&&e?[e,bd(Da(f),d,c||null)].join(" "):null;break a}c=null}c&&(b.headers.Authorization=c,b.headers["X-Goog-AuthUser"]=I("SESSION_INDEX",0));c=this.b.kb;c.startsWith("http")||(c="//"+c);hh(""+c+("/youtubei/"+this.b.innertubeApiVersion+"/"+a)+"?alt=json&key="+this.b.innertubeApiKey,b)};var Ah={},Bh=0;function Ch(a,b){a&&(I("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)?eh(a,b):Dh(a,b))}
function Dh(a,b){var c=new Image,d=""+Bh++;Ah[d]=c;c.onload=c.onerror=function(){b&&Ah[d]&&b();delete Ah[d]};
c.src=a}
;function Eh(){var a=fb(Fh);return new T(function(b,c){a.F=function(a){Eb(a)?b(a):c(new Gh("Request failed, status="+a.status,"net.badstatus"))};
a.onError=function(){c(new Gh("Unknown request error","net.unknown"))};
a.N=function(){c(new Gh("Request timed out","net.timeout"))};
ih("//googleads.g.doubleclick.net/pagead/id",a)})}
function Gh(a,b){Pa.call(this,a+", errorCode="+b);this.errorCode=b;this.name="PromiseAjaxError"}
ba(Gh,Pa);function Hh(a){return(0==a.search("cue")||0==a.search("load"))&&"loadModule"!=a}
function Ih(a,b,c){t(a)&&(a={mediaContentUrl:a,startSeconds:b,suggestedQuality:c});b=/\/([ve]|embed)\/([^#?]+)/.exec(a.mediaContentUrl);a.videoId=b&&b[2]?b[2]:null;return Jh(a)}
function Jh(a,b,c){if(ta(a)){b="endSeconds startSeconds mediaContentUrl suggestedQuality videoId two_stage_token".split(" ");c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}return{videoId:a,startSeconds:b,suggestedQuality:c}}
function Kh(a,b,c,d){if(ta(a)&&!qa(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}c={index:b,startSeconds:c,suggestedQuality:d};t(a)&&16==a.length?c.list="PL"+a:c.playlist=a;return c}
function Lh(a){var b=a.video_id||a.videoId;if(t(b)){var c=Lg()||{},d=Lg()||{};p(void 0)?d[b]=void 0:delete d[b];var e=v()+3E5,f=Ng;if(f&&window.JSON){t(d)||(d=JSON.stringify(d,void 0));try{f.set("yt-player-two-stage-token",d,e)}catch(g){f.remove("yt-player-two-stage-token")}}(b=c[b])&&(a.two_stage_token=b)}}
;function Mh(){if(null==r("_lact",window)){var a=parseInt(I("LACT"),10),a=isFinite(a)?v()-Math.max(a,0):-1;q("_lact",a,window);-1==a&&Nh();ch(document,"keydown",Nh);ch(document,"keyup",Nh);ch(document,"mousedown",Nh);ch(document,"mouseup",Nh);bg("page-mouse",Nh);bg("page-scroll",Nh);bg("page-resize",Nh)}}
function Nh(){null==r("_lact",window)&&(Mh(),r("_lact",window));var a=v();q("_lact",a,window);eg("USER_ACTIVE")}
function Oh(){var a=r("_lact",window);return null==a?-1:Math.max(v()-a,0)}
;function Ph(a,b,c){D.call(this);this.b=a;this.i=c;this.j=ch(window,"message",u(this.l,this));this.g=new Qg(this,a,b);Ib(this,za(Jb,this.g))}
w(Ph,D);Ph.prototype.l=function(a){var b;if(b=!this.f)if(b=a.origin==this.i)a:{b=this.b;do{var c;b:{c=a.source;do{if(c==b){c=!0;break b}if(c==c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(a=a.data,t(a))){try{a=Ra(a)}catch(d){return}a.command&&(b=this.g,b.f||b.l("command",a.command,a.data))}};
Ph.prototype.o=function(){dh(this.j);this.b=null;Ph.B.o.call(this)};function Qh(a){for(var b=0;b<a.length;b++){var c=a[b];"send_follow_on_ping_action"==c.name&&c.data&&c.data.follow_on_url&&Ch(c.data.follow_on_url)}}
;function Rh(a,b,c,d){var e={};e.eventTimeMs=Math.round(d||xb());e[a]=b;N("web_gel_lact")&&(e.context={lastActivityMs:Oh()});vg({endpoint:"log_event",va:e},c)}
;function Sh(a,b,c,d){Th(a,{attachChild:{csn:b,parentVisualElement:Cb(c),visualElements:[Cb(d)]}},void 0)}
function Uh(a,b,c){c=vc(c,function(a){return Cb(a)});
Th(a,{visibilityUpdate:{csn:b,visualElements:c}})}
function Th(a,b,c){b.eventTimeMs=Math.round(xb());b.lactMs=Oh();c&&(b.clientData=Vh(c));vg({endpoint:"log_interaction",va:b},a)}
function Vh(a){var b={};a.analyticsChannelData&&(b.analyticsDatas=vc(a.analyticsChannelData,function(a){return{tabName:a.tabName,cardName:a.cardName,isChannelScreen:a.isChannelScreen,insightId:a.insightId,externalChannelId:a.externalChannelId,externalContentOwnerId:a.externalContentOwnerId}}));
return{playbackData:{clientPlaybackNonce:a.clientPlaybackNonce},analyticsChannelData:b,externalLinkData:a.externalLinkData}}
;function Wh(a,b){Wc.call(this,b);this.b=a;this.start()}
w(Wh,Wc);Wh.prototype.addEventListener=function(a,b){this.b.addEventListener(a,b)};
Wh.prototype.removeEventListener=function(a,b){this.b.removeEventListener(a,b)};
function Zc(a,b){switch(a){case "loadVideoById":return b=Jh(b),Lh(b),[b];case "cueVideoById":return b=Jh(b),Lh(b),[b];case "loadVideoByPlayerVars":return Lh(b),[b];case "cueVideoByPlayerVars":return Lh(b),[b];case "loadPlaylist":return b=Kh(b),Lh(b),[b];case "cuePlaylist":return b=Kh(b),Lh(b),[b];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];
case "setLoop":return[b.loopPlaylists];case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey]}return[]}
function $c(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Wh.prototype.ha=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Wh.B.ha.call(this,a,b)};
Wh.prototype.o=function(){Wh.B.o.call(this);delete this.b};function Xh(a){qh.call(this);this.b=a;this.g=[];this.addEventListener("onReady",u(this.Va,this));this.addEventListener("onVideoProgress",u(this.gb,this));this.addEventListener("onVolumeChange",u(this.hb,this));this.addEventListener("onApiChange",u(this.ab,this));this.addEventListener("onPlaybackQualityChange",u(this.cb,this));this.addEventListener("onPlaybackRateChange",u(this.eb,this));this.addEventListener("onStateChange",u(this.fb,this))}
w(Xh,qh);l=Xh.prototype;l.Ba=function(a,b){if(this.b[a]){b=b||[];if(0<b.length&&Hh(a)){var c;c=b;if(ta(c[0])&&!qa(c[0]))c=c[0];else{var d={};switch(a){case "loadVideoById":case "cueVideoById":d=Jh.apply(window,c);break;case "loadVideoByUrl":case "cueVideoByUrl":d=Ih.apply(window,c);break;case "loadPlaylist":case "cuePlaylist":d=Kh.apply(window,c)}c=d}Lh(c);b.length=1;b[0]=c}this.b[a].apply(this.b,b);Hh(a)&&sh(this,this.ia())}};
l.Va=function(){var a=u(this.Ha,this);this.f.g=a};
l.addEventListener=function(a,b){this.g.push({eventType:a,listener:b});this.b.addEventListener(a,b)};
l.ia=function(){if(!this.b)return null;var a=this.b.getApiInterface();xc(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c],f=e;if(0==f.search("get")||0==f.search("is")){var f=e,g=0;0==f.search("get")?g=3:0==f.search("is")&&(g=2);f=f.charAt(g).toLowerCase()+f.substr(g+1);try{var h=this.b[e]();b[f]=h}catch(k){}}}b.videoData=this.b.getVideoData();b.currentTimeLastUpdated_=v()/1E3;return b};
l.fb=function(a){a={playerState:a,currentTime:this.b.getCurrentTime(),duration:this.b.getDuration(),videoData:this.b.getVideoData(),videoStartBytes:0,videoBytesTotal:this.b.getVideoBytesTotal(),videoLoadedFraction:this.b.getVideoLoadedFraction(),playbackQuality:this.b.getPlaybackQuality(),availableQualityLevels:this.b.getAvailableQualityLevels(),videoUrl:this.b.getVideoUrl(),playlist:this.b.getPlaylist(),playlistIndex:this.b.getPlaylistIndex(),currentTimeLastUpdated_:v()/1E3,playbackRate:this.b.getPlaybackRate(),
mediaReferenceTime:this.b.getMediaReferenceTime()};this.b.getProgressState&&(a.progressState=this.b.getProgressState());this.b.getStoryboardFormat&&(a.storyboardFormat=this.b.getStoryboardFormat());sh(this,a)};
l.cb=function(a){sh(this,{playbackQuality:a})};
l.eb=function(a){sh(this,{playbackRate:a})};
l.ab=function(){for(var a=this.b.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.b.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],n=this.b.getOption(e,k);b[e][k]=n}}this.sendMessage("apiInfoDelivery",b)};
l.hb=function(){sh(this,{muted:this.b.isMuted(),volume:this.b.getVolume()})};
l.gb=function(a){a={currentTime:a,videoBytesLoaded:this.b.getVideoBytesLoaded(),videoLoadedFraction:this.b.getVideoLoadedFraction(),currentTimeLastUpdated_:v()/1E3,playbackRate:this.b.getPlaybackRate(),mediaReferenceTime:this.b.getMediaReferenceTime()};this.b.getProgressState&&(a.progressState=this.b.getProgressState());sh(this,a)};
l.dispose=function(){Xh.B.dispose.call(this);for(var a=0;a<this.g.length;a++){var b=this.g[a];this.b.removeEventListener(b.eventType,b.listener)}this.g=[]};function Yh(a){Pa.call(this,a.message||a.description||a.name);this.b=a instanceof uf}
w(Yh,Pa);Yh.prototype.name="BiscottiError";function Zh(a,b){this.f=a;this.b=b}
Zh.prototype.then=function(a,b,c){try{if(p(this.f))return a?rf(a.call(c,this.f)):rf(this.f);if(p(this.b)){if(!b)return sf(this.b);var d=b.call(c,this.b);return!p(d)&&this.b.b?sf(this.b):rf(d)}throw Error("Invalid Result_ state");}catch(e){return sf(e)}};
ib(Zh);var Fh={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},$h=null;function ai(){if(!$h){var a=u(bi,m,2);$h=Eh().then(ci,a)}return $h}
function ci(a){a=a.responseText;if(0!=a.lastIndexOf(")]}'",0))return di(""),$h=new Zh(""),"";a=JSON.parse(a.substr(4)).id;di(a);$h=new Zh(a);ei(18E5,2);return a}
function bi(a,b){var c=new Yh(b);di("");$h=new Zh(void 0,c);0<a&&ei(12E4,a-1);throw c;}
function ei(a,b){P(function(){var a=u(bi,m,b),a=Eh().then(ci,a);tf(a,null,na,void 0)},a)}
function di(a){q("yt.www.ads.biscotti.lastId_",a,void 0)}
;function fi(){return N("enable_youtubei_innertube")?zh:Sf}
;var gi=r("yt.logging.latency.usageStats_")||{};q("yt.logging.latency.usageStats_",gi,void 0);var hi=0;function ii(a){gi[a]=gi[a]||{count:0};var b=gi[a];b.count++;b.time=xb();hi||(hi=Ie(ji,0,5E3));return 10<b.count?(11==b.count&&wh(Error("CSI data exceeded logging limit with key: "+a)),!0):!1}
function ji(){var a=xb(),b;for(b in gi)6E4<a-gi[b].time&&delete gi[b];hi=0}
;function ki(){var a=I("ROOT_VE_TYPE",void 0);return a?new Ab(void 0,a,void 0):null}
function li(){var a=I("client-screen-nonce",void 0);a||(a=I("EVENT_ID",void 0));return a}
;function mi(a){D.call(this);this.b=[];this.g=a||this}
w(mi,D);function ni(a,b,c,d){d=Rc(u(d,a.g));d={target:b,name:c,ga:d};b.addEventListener(c,d.ga,void 0);a.b.push(d)}
function oi(a){for(;a.b.length;){var b=a.b.pop();b.target.removeEventListener(b.name,b.ga)}}
mi.prototype.o=function(){oi(this);mi.B.o.call(this)};var pi={vc:!0},qi={ad_at:"adType",cpn:"clientPlaybackNonce",csn:"clientScreenNonce",is_nav:"isNavigation",yt_lt:"loadType",yt_ad:"isMonetized",yt_ad_pr:"prerollAllowed",yt_red:"isRedSubscriber",yt_vis:"isVisible",docid:"videoId",plid:"videoId"},ri="ap c cver ei yt_fss yt_li".split(" "),si=["isNavigation","isMonetized","prerollAllowed","isRedSubscriber","isVisible"],ti=u(Hb.clearResourceTimings||Hb.webkitClearResourceTimings||Hb.mozClearResourceTimings||Hb.msClearResourceTimings||Hb.oClearResourceTimings||
na,Hb);
function ui(a){if("_"!=a[0]){var b=a;Hb.mark&&(0==b.lastIndexOf("mark_",0)||(b="mark_"+b),Hb.mark(b))}var b=vi(),c=xb();b[a]&&(b["_"+a]=b["_"+a]||[b[a]],b["_"+a].push(c));b[a]=c;wi()["tick_"+a]=void 0;xb();N("csi_on_gel")?(b=xi(),"_start"==a?ii("baseline_"+b)||Rh("latencyActionBaselined",{clientActionNonce:b},zh,void 0):ii("tick_"+a+"_"+b)||Rh("latencyActionTicked",{tickName:a,clientActionNonce:b},zh,void 0),a=!0):a=!1;if(a=!a)a=!r("yt.timing.pingSent_");if(a&&(b=I("TIMING_ACTION",void 0),a=vi(),
r("yt.timing.ready_")&&b&&a._start&&yi())){b=!0;c=I("TIMING_WAIT",[]);if(c.length)for(var d=0,e=c.length;d<e;++d)if(!(c[d]in a)){b=!1;break}b&&zi()}}
function Ai(){var a=Bi().info.yt_lt="hot_bg";wi().info_yt_lt=a;if(N("csi_on_gel"))if("yt_lt"in qi){var b={},c=qi.yt_lt;0<=uc(si,c)&&(a=!!a);b[c]=a;a=xi();c=Object.keys(b).join("");ii("info_"+c+"_"+a)||(b.clientActionNonce=a,Rh("latencyActionInfo",b,zh))}else"yt_lt"in ri||M(Error("Unknown label yt_lt logged with GEL CSI."))}
function yi(){var a=vi();if(a.aft)return a.aft;for(var b=I("TIMING_AFT_KEYS",["ol"]),c=b.length,d=0;d<c;d++){var e=a[b[d]];if(e)return e}return NaN}
function zi(){if(!N("csi_on_gel")){var a=vi(),b=Bi().info,c=a._start,d;for(d in a)if(0==d.lastIndexOf("_",0)&&qa(a[d])){var e=d.slice(1);if(e in pi){var f=vc(a[d],function(a){return Math.round(a-c)});
b["all_"+e]=f.join()}delete a[d]}e=!!b.ap;if(f=r("yt.timing.reportbuilder_")){if(f=f(a,b,void 0))Ci(f,e),Di(),ti(),Ei(!1,void 0),I("TIMING_ACTION")&&G("PREVIOUS_ACTION",I("TIMING_ACTION")),G("TIMING_ACTION","")}else{var g=I("CSI_SERVICE_NAME","youtube"),f={v:2,s:g,action:I("TIMING_ACTION",void 0)},h=b.srt;void 0!==a.srt&&delete b.srt;if(b.h5jse){var k=window.location.protocol+r("ytplayer.config.assets.js");(k=Hb.getEntriesByName?Hb.getEntriesByName(k)[0]:null)?b.h5jse=Math.round(b.h5jse-k.responseEnd):
delete b.h5jse}a.aft=yi();Fi()&&"youtube"==g&&(Ai(),g=a.vc,k=a.pbs,delete a.aft,b.aft=Math.round(k-g));for(var n in b)"_"!=n.charAt(0)&&(f[n]=b[n]);a.ps=xb();b={};n=[];for(d in a)"_"!=d.charAt(0)&&(g=Math.round(a[d]-c),b[d]=g,n.push(d+"."+g));f.rt=n.join(",");(a=r("ytdebug.logTiming"))&&a(f,b);Ci(f,e,void 0);V(fc,new ec(b.aft+(h||0)))}}}
function Ci(a,b,c){if(N("debug_csi_data")){var d=r("yt.timing.csiData");d||(d=[],q("yt.timing.csiData",d,void 0));d.push({page:location.href,time:new Date,args:a})}var d="",e;for(e in a)d+="&"+e+"="+a[e];a="/csi_204?"+d.substring(1);if(window.navigator&&window.navigator.sendBeacon&&b)try{window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")||Ch(a,void 0)}catch(f){Ch(a,void 0)}else Ch(a);Ei(!0,c)}
function xi(){var a=Bi().nonce;if(!a){var b;a:{if(window.crypto&&window.crypto.getRandomValues)try{var c=Array(16),d=new Uint8Array(16);window.crypto.getRandomValues(d);for(a=0;a<c.length;a++)c[a]=d[a];b=c;break a}catch(e){}b=Array(16);for(c=0;16>c;c++){d=v();for(a=0;a<d%23;a++)b[c]=Math.random();b[c]=Math.floor(256*Math.random())}if(vd)for(c=1,d=0;d<vd.length;d++)b[c%16]=b[c%16]^b[(c-1)%16]/4^vd.charCodeAt(d),c++}c=[];for(d=0;d<b.length;d++)c.push("abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789-_".charAt(b[d]&
63));a=c.join("");Bi().nonce=a}return a}
function vi(){return Bi().tick}
function wi(){var a=Bi();"gel"in a||(a.gel={});return a.gel}
function Bi(){return r("ytcsi.data_")||Di()}
function Di(){var a={tick:{},info:{}};q("ytcsi.data_",a,void 0);return a}
function Ei(a,b){q("yt.timing."+(b||"")+"pingSent_",a,void 0)}
function Fi(){var a=vi(),b=a.pbr,c=a.vc,a=a.pbs;return b&&c&&a&&b<c&&c<a&&1==Bi().info.yt_pvis}
;function Gi(a,b){D.call(this);this.w=this.l=a;this.T=b;this.C=!1;this.g={};this.Z=this.S=null;this.U=new U;Ib(this,za(Jb,this.U));this.j={};this.J=this.$=this.i=this.fa=this.b=null;this.W=!1;this.K=this.D=this.P=this.R=null;this.aa={};this.Da=["onReady"];this.X=new mi(this);Ib(this,za(Jb,this.X));this.da=null;this.pa=NaN;this.Y={};Hi(this);this.H("onDetailedError",u(this.Sa,this));this.H("onTabOrderChange",u(this.Fa,this));this.H("onTabAnnounce",u(this.qa,this));this.H("WATCH_LATER_VIDEO_ADDED",u(this.Ta,
this));this.H("WATCH_LATER_VIDEO_REMOVED",u(this.Ua,this));Ue||(this.H("onMouseWheelCapture",u(this.Qa,this)),this.H("onMouseWheelRelease",u(this.Ra,this)));this.H("onAdAnnounce",u(this.qa,this));this.M=new mi(this);Ib(this,za(Jb,this.M));this.ea=!1;this.ca=null}
w(Gi,D);var Ii=["drm.unavailable","fmt.noneavailable","html5.missingapi","html5.unsupportedads","html5.unsupportedlive"];l=Gi.prototype;l.oa=function(a,b){this.f||(Ji(this,a),Ki(this,b),this.C&&Li(this))};
function Ji(a,b){a.fa=b;a.b=cc(b);a.i=a.b.attrs.id||a.i;"video-player"==a.i&&(a.i=a.T,a.b.attrs.id=a.T);a.w.id==a.i&&(a.i+="-player",a.b.attrs.id=a.i);a.b.args.enablejsapi="1";a.b.args.playerapiid=a.T;a.$||(a.$=Mi(a,a.b.args.jsapicallback||"onYouTubePlayerReady"));a.b.args.jsapicallback=null;var c=a.b.attrs.width;c&&(a.w.style.width=ng(Number(c)||c));if(c=a.b.attrs.height)a.w.style.height=ng(Number(c)||c)}
l.Ia=function(){return this.fa};
function Li(a){a.b.loaded||(a.b.loaded=!0,"0"!=a.b.args.autoplay?a.g.loadVideoByPlayerVars(a.b.args):a.g.cueVideoByPlayerVars(a.b.args))}
function Ni(a){if(!p(a.b.disable.flash)){var b=a.b.disable,c;c=af($e.getInstance(),a.b.minVersion);b.flash=!c}return!a.b.disable.flash}
function Oi(a,b){if((!b||(5!=(dc[b.errorCode]||5)?0:-1!=Ii.indexOf(b.errorCode)))&&Ni(a)){var c=Pi(a);c&&c.stopVideo&&c.stopVideo();var d=a.b;c&&c.getUpdatedConfigurationData&&(c=c.getUpdatedConfigurationData(),d=bc(c));d.args.autoplay=1;d.args.html5_unavailable="1";Ji(a,d);Ki(a,"flash")}}
function Ki(a,b){if(!a.f){if(!b){var c;if(!(c=!a.b.html5&&Ni(a))){if(!p(a.b.disable.html5)){var d;c=!0;void 0!=a.b.args.deviceHasDisplay&&(c=a.b.args.deviceHasDisplay);if(2.2==bf)d=!0;else{a:{var e=c;c=r("yt.player.utils.videoElement_");c||(c=document.createElement("VIDEO"),q("yt.player.utils.videoElement_",c,void 0));try{if(c.canPlayType)for(var e=e?oh:ph,f=0;f<e.length;f++)if(c.canPlayType(e[f])){d=null;break a}d="fmt.noneavailable"}catch(g){d="html5.missingapi"}}d=!d}d&&(d=Qi(a)||a.b.assets.js);
a.b.disable.html5=!d;d||(a.b.args.html5_unavailable="1")}c=!!a.b.disable.html5}b=c?Ni(a)?"flash":"unsupported":"html5"}("flash"==b?a.ib:a.jb).call(a)}}
function Qi(a){var b=!0,c=Pi(a);c&&a.b&&(a=a.b,b=tb(c,"version")==a.assets.js);return b&&!!r("yt.player.Application.create")}
l.jb=function(){if(!this.W){var a=Qi(this);a&&"html5"==Ri(this)?(this.J="html5",this.C||this.O()):(Si(this),this.J="html5",a&&this.P?(this.l.appendChild(this.P),this.O()):(this.b.loaded=!0,this.R=u(function(){var a=this.l,c=cc(this.b);r("yt.player.Application.create")(a,c);this.O()},this),this.W=!0,a?this.R():(Fg(this.b.assets.js,this.R),Hg(this.b.assets.css))))}};
l.ib=function(){var a=cc(this.b);if(!this.D){var b=Pi(this);b&&(this.D=document.createElement("SPAN"),this.D.tabIndex=0,ni(this.X,this.D,"focus",this.ta),this.K=document.createElement("SPAN"),this.K.tabIndex=0,ni(this.X,this.K,"focus",this.ta),b.parentNode&&b.parentNode.insertBefore(this.D,b),b.parentNode&&b.parentNode.insertBefore(this.K,b.nextSibling))}a.attrs.width=a.attrs.width||"100%";a.attrs.height=a.attrs.height||"100%";if("flash"==Ri(this))this.J="flash",this.C||this.O();else{Si(this);this.J=
"flash";this.b.loaded=!0;var b=$e.getInstance(),c=(-1<b.i.indexOf("Gnash")&&-1==b.i.indexOf("AVM2")||9==b.b&&1==b.f||9==b.b&&0==b.f&&1==b.g?0:9<=b.b)||-1<navigator.userAgent.indexOf("Sony/COM2")&&!af(b,9,1,58)?a.url:a.urlV9As2;window!=window.top&&document.referrer&&(a.args.framer=document.referrer.substring(0,128));b=this.l;if(c){var b=t(b)?Mf(b):b,d=fb(a.attrs);d.tabindex=0;var e=fb(a.params);e.flashvars=ud(a.args);if(yb){d.classid="clsid:D27CDB6E-AE6D-11cf-96B8-444553540000";e.movie=c;var a=document.createElement("object"),
f;for(f in d)a.setAttribute(f,d[f]);for(var g in e)f=document.createElement("param"),f.setAttribute("name",g),f.setAttribute("value",e[g]),a.appendChild(f)}else{d.type="application/x-shockwave-flash";d.src=c;a=document.createElement("embed");a.setAttribute("name",d.id);for(var h in d)a.setAttribute(h,d[h]);for(var k in e)a.setAttribute(k,e[k])}g=document.createElement("div");g.appendChild(a);b.innerHTML=g.innerHTML}this.O()}};
l.ta=function(){Pi(this).focus()};
function Pi(a){var b=Mf(a.i);!b&&a.w&&a.w.querySelector&&(b=a.w.querySelector("#"+a.i));return b}
l.O=function(){if(!this.f){var a=Pi(this),b=!1;try{a&&a.getApiInterface&&a.getApiInterface()&&(b=!0)}catch(f){}if(b)if(this.W=!1,a.isNotServable&&a.isNotServable(this.b.args.video_id))Oi(this);else{Hi(this);this.C=!0;a=Pi(this);a.addEventListener&&(this.S=Ti(this,a,"addEventListener"));a.removeEventListener&&(this.Z=Ti(this,a,"removeEventListener"));for(var b=a.getApiInterface(),b=b.concat(a.getInternalApiInterface()),c=0;c<b.length;c++){var d=b[c];this.g[d]||(this.g[d]=Ti(this,a,d))}for(var e in this.j)this.S(e,
this.j[e]);Li(this);this.$&&this.$(this.g);this.U.V("onReady",this.g)}else this.pa=P(u(this.O,this),50)}};
function Ti(a,b,c){var d=b[c];return function(){try{return a.da=null,d.apply(b,arguments)}catch(e){"Bad NPObject as private data!"!=e.message&&"sendAbandonmentPing"!=c&&(e.message+=" ("+c+")",a.da=e,M(e,"WARNING"))}}}
function Hi(a){a.C=!1;if(a.Z)for(var b in a.j)a.Z(b,a.j[b]);for(var c in a.Y)window.clearTimeout(parseInt(c,10));a.Y={};a.S=null;a.Z=null;for(var d in a.g)a.g[d]=null;a.g.addEventListener=u(a.H,a);a.g.removeEventListener=u(a.$a,a);a.g.destroy=u(a.dispose,a);a.g.getLastError=u(a.Ja,a);a.g.getPlayerType=u(a.Ka,a);a.g.getCurrentVideoConfig=u(a.Ia,a);a.g.loadNewVideoConfig=u(a.oa,a);a.g.isReady=u(a.lb,a)}
l.lb=function(){return this.C};
l.H=function(a,b){if(!this.f){var c=Mi(this,b);if(c){if(!(0<=uc(this.Da,a)||this.j[a])){var d=Ui(this,a);this.S&&this.S(a,d)}this.U.subscribe(a,c);"onReady"==a&&this.C&&P(za(c,this.g),0)}}};
l.$a=function(a,b){if(!this.f){var c=Mi(this,b);c&&ad(this.U,a,c)}};
function Mi(a,b){var c=b;if("string"==typeof b){if(a.aa[b])return a.aa[b];c=function(){var a=r(b);a&&a.apply(m,arguments)};
a.aa[b]=c}return c?c:null}
function Ui(a,b){var c="ytPlayer"+b+a.T;a.j[b]=c;m[c]=function(c){var d=P(function(){if(!a.f){a.U.V(b,c);var e=a.Y,g=String(d);g in e&&delete e[g]}},0);
eb(a.Y,String(d))};
return c}
l.Fa=function(a){a=a?Of:Nf;for(var b=a(document.activeElement);b&&(1!=b.nodeType||b==this.D||b==this.K||(b.focus(),b!=document.activeElement));)b=a(b)};
l.qa=function(a){eg("a11y-announce",a)};
l.Sa=function(a){Oi(this,a)};
l.Ta=function(a){eg("WATCH_LATER_VIDEO_ADDED",a)};
l.Ua=function(a){eg("WATCH_LATER_VIDEO_REMOVED",a)};
l.Qa=function(){if(!this.ea){if(Ye){var a=document,b=a.scrollingElement?a.scrollingElement:oe||"CSS1Compat"!=a.compatMode?a.body||a.documentElement:a.documentElement,a=a.parentWindow||a.defaultView;this.ca=R&&S("10")&&a.pageYOffset!=b.scrollTop?new ke(b.scrollLeft,b.scrollTop):new ke(a.pageXOffset||b.scrollLeft,a.pageYOffset||b.scrollTop);ni(this.M,window,"scroll",this.Xa);ni(this.M,this.l,"touchmove",this.Wa)}else ni(this.M,this.l,"mousewheel",this.ua),ni(this.M,this.l,"wheel",this.ua);this.ea=!0}};
l.Ra=function(){oi(this.M);this.ea=!1};
l.ua=function(a){a=a||window.event;a.returnValue=!1;a.preventDefault&&a.preventDefault()};
l.Xa=function(){window.scrollTo(this.ca.b,this.ca.f)};
l.Wa=function(a){a.preventDefault()};
l.Ka=function(){return this.J||Ri(this)};
l.Ja=function(){return this.da};
function Ri(a){return(a=Pi(a))?"div"==a.tagName.toLowerCase()?"html5":"flash":null}
function Si(a){ui("dcp");a.cancel();Hi(a);a.J=null;a.b&&(a.b.loaded=!1);var b=Pi(a);"html5"==Ri(a)?a.P=b:b&&b.destroy&&b.destroy();for(var b=a.l,c;c=b.firstChild;)b.removeChild(c);oi(a.X);a.D=null;a.K=null}
l.cancel=function(){this.R&&Eg(this.b.assets.js,this.R);window.clearTimeout(this.pa);this.W=!1};
l.o=function(){Si(this);if(this.P&&this.b)try{this.P.destroy()}catch(b){M(b)}this.aa=null;for(var a in this.j)m[this.j[a]]=null;this.fa=this.b=this.g=null;delete this.l;delete this.w;Gi.B.o.call(this)};function Vi(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=I("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){var d=a,e=I("VALID_SESSION_TEMPDATA_DOMAINS",[]),f=Lc(L(window.location.href)[3]||null);f&&e.push(f);f=Lc(L(d)[3]||null);if(0<=uc(e,f)||!f&&0==d.lastIndexOf("/",0))if(N("autoescape_tempdata_url")&&(e=document.createElement("a"),kf(e,d),d=e.href),d){var f=L(d),d=f[5],e=f[6],f=f[7],g="";d&&(g+=d);e&&(g+="?"+e);f&&(g+="#"+f);d=g;e=d.indexOf("#");if(d=0>e?d:d.substr(0,e)){if(b.itct||b.ved)b.csn=b.csn||
li();d="ST-"+pb(d).toString(36);e=b?ud(b):"";Ob.set(""+d,e,5,"/","youtube.com");b&&(b=b.itct||b.ved,d=r("yt.logging.screen.storeParentElement"),b&&d&&d(new Ab(b)))}}}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var h,k;h=void 0===h?{}:h;k=void 0===k?"":k;c=window.location;a=Mc(Pc([a],h))+k;a=a instanceof $d?a:de(a);c.href=be(a)}return!0}
;function Wi(a){N("desktop_polymer")&&M(a)}
function Xi(a){a&&!r("yt.www.ads.biscotti.getId_")&&q("yt.www.ads.biscotti.getId_",ai,void 0);try{var b;try{var c=r("yt.www.ads.biscotti.getId_");b=c?c():ai()}catch(d){b=sf(d)}b.then(Yi,Wi);P(Xi,18E5)}catch(d){M(d)}}
var Zi=0;
function Yi(a){var b;a:{try{b=window.top.location.href}catch(Z){b=2;break a}b=null!=b?b==window.document.location.href?0:1:2}b={dt:Ca,flash:Ub||"0",frm:b};b.u_tz=-(new Date).getTimezoneOffset();var c;try{c=x.history.length}catch(Z){c=0}b.u_his=c;b.u_java=!!x.navigator&&"unknown"!==typeof x.navigator.javaEnabled&&!!x.navigator.javaEnabled&&x.navigator.javaEnabled();x.screen&&(b.u_h=x.screen.height,b.u_w=x.screen.width,b.u_ah=x.screen.availHeight,b.u_aw=x.screen.availWidth,b.u_cd=x.screen.colorDepth);x.navigator&&
x.navigator.plugins&&(b.u_nplug=x.navigator.plugins.length);x.navigator&&x.navigator.mimeTypes&&(b.u_nmime=x.navigator.mimeTypes.length);b.bid=a;b.ca_type=Tb?"flash":"image";if(N("enable_server_side_search_pyv")||N("enable_server_side_mweb_search_pyv")){var d;a=window;try{d=a.screenX;var e=a.screenY}catch(Z){}try{var f=a.outerWidth,g=a.outerHeight}catch(Z){}try{var h=a.innerWidth,k=a.innerHeight}catch(Z){}d=[a.screenLeft,a.screenTop,d,e,a.screen?a.screen.availWidth:void 0,a.screen?a.screen.availTop:
void 0,f,g,h,k];var n;e=window.top||x;try{var A;if(e.document&&!e.document.body)A=new Za(-1,-1);else{var H=(e||window).document,ea="CSS1Compat"==H.compatMode?H.documentElement:H.body;A=(new Za(ea.clientWidth,ea.clientHeight)).round()}n=A}catch(Z){n=new Za(-12245933,-12245933)}A=0;window.SVGElement&&document.createElementNS&&(A|=1);Aa(b,{bc:A,bih:n.height,biw:n.width,brdim:d.join(),vis:{visible:1,hidden:2,prerender:3,preview:4}[Ba.webkitVisibilityState||Ba.mozVisibilityState||Ba.visibilityState||""]||
0,wgl:!!x.WebGLRenderingContext})}b.bsq=Zi++;hh("//www.youtube.com/ad_data_204",{La:!1,A:b})}
;function $i(a){B.call(this,1,arguments);this.b=a}
w($i,B);function X(a){B.call(this,1,arguments);this.b=a}
w(X,B);function aj(a,b,c){B.call(this,3,arguments);this.g=a;this.f=b;this.b=null!=c?!!c:null}
w(aj,B);function bj(a,b,c,d,e){B.call(this,2,arguments);this.f=a;this.b=b;this.i=c||null;this.g=d||null;this.source=e||null}
w(bj,B);function cj(a,b,c){B.call(this,1,arguments);this.b=a;this.subscriptionId=b}
w(cj,B);function dj(a,b,c,d,e,f,g){B.call(this,1,arguments);this.f=a;this.subscriptionId=b;this.b=c;this.i=e||null;this.g=f||null;this.source=g||null}
w(dj,B);
var ej=new C("subscription-batch-subscribe",$i),fj=new C("subscription-batch-unsubscribe",$i),gj=new C("subscription-subscribe",bj),hj=new C("subscription-subscribe-loading",X),ij=new C("subscription-subscribe-loaded",X),jj=new C("subscription-subscribe-success",cj),kj=new C("subscription-subscribe-external",bj),lj=new C("subscription-unsubscribe",dj),mj=new C("subscription-unsubscirbe-loading",X),nj=new C("subscription-unsubscribe-loaded",X),oj=new C("subscription-unsubscribe-success",X),pj=new C("subscription-external-unsubscribe",
dj),qj=new C("subscription-enable-ypc",X),rj=new C("subscription-prefs",aj),sj=new C("subscription-prefs-success",aj),tj=new C("subscription-prefs-failure",aj);var uj={},vj="player_uid_"+(1E9*Math.random()>>>0);function wj(a,b){a=t(a)?Mf(a):a;b=bc(b);var c=vj+"_"+ua(a),d=uj[c];if(d)return d.oa(b),d.g;d=new Gi(a,c);uj[c]=d;eg("player-added",d.g);Ib(d,za(xj,d));P(function(){d.oa(b)},0);
return d.g}
function xj(a){uj[a.T]=null}
function yj(a){a=Mf(a);if(!a)return null;var b=vj+"_"+ua(a),c=uj[b];c||(c=new Gi(a,b),uj[b]=c);return c.g}
;var Y=null,zj=[];function Aj(a){return{externalChannelId:a.externalChannelId,Pa:!!a.isChannelPaid,source:a.source,subscriptionId:a.subscriptionId}}
function Bj(a){a&&a.externalChannelId&&Cj(Aj(a))}
function Cj(a){var b=I("PLAYER_CONFIG");b&&b.args&&void 0!==b.args.authuser||I("SESSION_INDEX")||I("LOGGED_IN")?(V(gj,new bj(a.externalChannelId,a.Pa?{itemType:"U",itemId:a.externalChannelId}:null)),a=ud({event:"subscribe",source:a.source}),Ch("/gen_204?"+a,void 0)):Dj(a)}
function Dj(a){Rg(function(b){b.subscription_ajax&&Cj(a)})}
function Ej(a){a=Aj(a);V(lj,new dj(a.externalChannelId,a.subscriptionId,null));a=ud({event:"unsubscribe",source:a.source});Ch("/gen_204?"+a,void 0)}
function Fj(a){Y&&Y.channelSubscribed(a.b,a.subscriptionId)}
function Gj(a){Y&&Y.channelUnsubscribed(a.b)}
;var Hj=!1,Ij=[],Jj=[];function Kj(a){a.b?Hj?V(kj,a):V(lc,new gc(function(){V(qc,new kc(a.b))})):Lj(a.f,a.i,a.g,a.source)}
function Mj(a){a.b?Hj?V(pj,a):V(lc,new gc(function(){V(oc,new kc(a.b))})):Nj(a.f,a.subscriptionId,a.i,a.g,a.source)}
function Oj(a){Pj(yc(a.b))}
function Qj(a){Rj(yc(a.b))}
function Sj(a){Tj(a.g,a.f,a.b)}
function Uj(a){var b=a.itemId,c=a.b.subscriptionId;b&&c&&V(jj,new cj(b,c,a.b.channelInfo))}
function Vj(a){var b=a.b;$a(a.f,function(a,d){V(jj,new cj(d,a,b[d]))})}
function Wj(a){V(oj,new X(a.f.itemId));a.b&&a.b.length&&(Xj(a.b,oj),Xj(a.b,qj))}
function Lj(a,b,c,d){var e=new X(a);V(hj,e);var f={};f.c=a;c&&(f.eurl=c);d&&(f.source=d);c={};(d=I("PLAYBACK_ID"))&&(c.plid=d);(d=I("EVENT_ID"))&&(c.ei=d);b&&Yj(b,c);ih("/subscription_ajax?action_create_subscription_to_channel=1",{method:"POST",na:f,A:c,F:function(b,c){var d=c.response;V(jj,new cj(a,d.id,d.channel_info));d.show_feed_privacy_dialog&&eg("SHOW-FEED-PRIVACY-SUBSCRIBE-DIALOG",a);d.actions&&Qh(d.actions)},
ma:function(){V(ij,e)}})}
function Nj(a,b,c,d,e){var f=new X(a);V(mj,f);var g={};d&&(g.eurl=d);e&&(g.source=e);d={};d.c=a;d.s=b;(a=I("PLAYBACK_ID"))&&(d.plid=a);(a=I("EVENT_ID"))&&(d.ei=a);c&&Yj(c,d);ih("/subscription_ajax?action_remove_subscriptions=1",{method:"POST",na:g,A:d,F:function(a,b){var c=b.response;V(oj,f);c.actions&&Qh(c.actions)},
ma:function(){V(nj,f)}})}
function Tj(a,b,c){if(a){var d={};d.channel_id=a;switch(b){case "receive-all-updates":d.receive_all_updates=!0;break;case "receive-no-updates":d.receive_no_updates=!0;d.receive_post_updates=!1;break;case "receive-highlight-updates":d.receive_all_updates=!1;d.receive_no_updates=!1;break;default:return}null===c||d.receive_no_updates||(d.receive_post_updates=c);var e=new aj(a,b,c);ih("/subscription_ajax?action_update_subscription_preferences=1",{method:"POST",A:d,onError:function(){V(tj,e)},
F:function(){V(sj,e)}})}}
function Pj(a){if(a.length){var b=Ac(a,0,40);V("subscription-batch-subscribe-loading");Xj(b,hj);var c={};c.a=b.join(",");var d=function(){V("subscription-batch-subscribe-loaded");Xj(b,ij)};
ih("/subscription_ajax?action_create_subscription_to_all=1",{method:"POST",A:c,F:function(c,f){d();var e=f.response,h=e.id;if(qa(h)&&h.length==b.length){var k=e.channel_info_map;K(h,function(a,c){var d=b[c];V(jj,new cj(d,a,k[d]))});
a.length?Pj(a):V("subscription-batch-subscribe-finished")}},
onError:function(){d();V("subscription-batch-subscribe-failure")}})}}
function Rj(a){if(a.length){var b=Ac(a,0,40);V("subscription-batch-unsubscribe-loading");Xj(b,mj);var c={};c.c=b.join(",");var d=function(){V("subscription-batch-unsubscribe-loaded");Xj(b,nj)};
ih("/subscription_ajax?action_remove_subscriptions=1",{method:"POST",A:c,F:function(){d();Xj(b,oj);a.length&&Rj(a)},
onError:function(){d()}})}}
function Xj(a,b){K(a,function(a){V(b,new X(a))})}
function Yj(a,b){var c=sd(a);Aa(b,c)}
;var Zj=r("yt.abuse.botguardInitialized")||Vg;q("yt.abuse.botguardInitialized",Zj,void 0);var ak=r("yt.abuse.invokeBotguard")||Wg;q("yt.abuse.invokeBotguard",ak,void 0);var bk=r("yt.abuse.dclkstatus.checkDclkStatus")||$g;q("yt.abuse.dclkstatus.checkDclkStatus",bk,void 0);var ck=r("yt.player.exports.navigate")||Vi;q("yt.player.exports.navigate",ck,void 0);var dk=r("yt.player.embed")||wj;q("yt.player.embed",dk,void 0);var ek=r("yt.player.getPlayerByElement")||yj;q("yt.player.getPlayerByElement",ek,void 0);
var fk=r("yt.util.activity.init")||Mh;q("yt.util.activity.init",fk,void 0);var gk=r("yt.util.activity.getTimeSinceActive")||Oh;q("yt.util.activity.getTimeSinceActive",gk,void 0);var hk=r("yt.util.activity.setTimestamp")||Nh;q("yt.util.activity.setTimestamp",hk,void 0);var ik=null,jk=null,kk=null,lk={};function mk(a){Rh(a.payload_name,a.payload,N("enable_youtubei_innertube")?zh:Sf,void 0)}
function nk(a){var b=a.id;a=a.ve_type;var c=Bb++;a=new Ab(void 0,a,c,void 0);lk[b]=a;b=li();c=ki();b&&c&&Sh(fi(),b,c,a)}
function ok(a){var b=a.csn;a=a.root_ve_type;if(b&&a&&(G("client-screen-nonce",b),G("ROOT_VE_TYPE",a),a=ki()))for(var c in lk){var d=b,e=a,f=lk[c];Sh(fi(),d,e,f)}}
function pk(a){lk[a.id]=new Ab(a.tracking_params)}
function qk(a){var b=li();a=lk[a.id];if(b&&a){var c=fi();Th(c,{click:{csn:b,visualElement:Cb(a)}},void 0)}}
function rk(a){a=a.ids;var b=li();if(b){for(var c=[],d=0;d<a.length;d++){var e=lk[a[d]];e&&c.push(e)}c.length&&Uh(fi(),b,c)}}
function sk(){var a=ik;a&&a.startInteractionLogging&&a.startInteractionLogging()}
;q("yt.setConfig",G,void 0);q("yt.config.set",G,void 0);q("yt.setMsg",Tc,void 0);q("yt.msgs.set",Tc,void 0);q("yt.logging.errors.log",wh,void 0);
q("writeEmbed",function(){var a=I("PLAYER_CONFIG",void 0);"1"!=a.privembed&&Xi(!0);"gvn"==a.args.ps&&(document.body.style.backgroundColor="transparent");var b=document.referrer,c=I("POST_MESSAGE_ORIGIN");window!=window.top&&b&&b!=document.URL&&(a.args.loaderUrl=b);I("LIGHTWEIGHT_AUTOPLAY")&&(a.args.autoplay="1");a.args.autoplay&&Lh(a.args);ik=a=wj("player",a);a.addEventListener("onScreenChanged",ok);a.addEventListener("onLogClientVeCreated",nk);a.addEventListener("onLogServerVeCreated",pk);a.addEventListener("onLogToGel",
mk);a.addEventListener("onLogVeClicked",qk);a.addEventListener("onLogVesShown",rk);a.addEventListener("onReady",sk);b=I("POST_MESSAGE_ID","player");I("ENABLE_JS_API")?kk=new Xh(a):I("ENABLE_POST_API")&&t(b)&&t(c)&&(jk=new Ph(window.parent,b,c),kk=new Wh(a,jk.g));I("BG_P")&&(I("BG_I")||I("BG_IU"))&&Ug();Zg();Y=a;Y.addEventListener("SUBSCRIBE",Bj);Y.addEventListener("UNSUBSCRIBE",Ej);zj.push(W(jj,Fj),W(oj,Gj))},void 0);
q("yt.www.watch.ads.restrictioncookie.spr",function(a){Ch(a+"mac_204?action_fcts=1");return!0},void 0);
var tk=Rc(function(){ui("ol");Hj=!0;Jj.push(W(gj,Kj),W(lj,Mj));Hj||Jj.push(W(kj,Kj),W(pj,Mj),W(ej,Oj),W(fj,Qj),W(rj,Sj),W(nc,Uj),W(pc,Wj),W(mc,Vj));var a=od.getInstance(),b=1<window.devicePixelRatio;if(!!((rd("f"+(Math.floor(119/31)+1))||0)&67108864)!=b){var c="f"+(Math.floor(119/31)+1),d=rd(c)||0,d=b?d|67108864:d&-67108865;0==d?delete O[c]:O[c]=d.toString(16).toString();var a=a.b,b=[],e;for(e in O)b.push(e+"="+escape(O[e]));Ob.set(""+a,b.join("&"),63072E3,"/","youtube.com")}}),uk=Rc(function(){var a=
ik;
a&&a.sendAbandonmentPing&&a.sendAbandonmentPing();I("PL_ATT")&&(Tg=null);for(var a=0,b=Xg.length;a<b;a++){var c=Xg[a];if(!isNaN(c)){var d=r("yt.scheduler.instance.cancelJob");d?d(c):window.clearTimeout(c)}}Xg.length=0;a=Bg("//static.doubleclick.net/instream/ad_status.js");if(b=document.getElementById(a))gg(a),b.parentNode.removeChild(b);Yg=!1;G("DCLKSTAT",0);dg(Ij);Ij.length=0;mg(Jj);Jj.length=0;Hj=!1;Y&&(Y.removeEventListener("SUBSCRIBE",Cj),Y.removeEventListener("UNSUBSCRIBE",Ej));Y=null;mg(zj);
zj.length=0;Kb(kk,jk);if(a=ik)a.removeEventListener("onScreenChanged",ok),a.removeEventListener("onLogClientVeCreated",nk),a.removeEventListener("onLogServerVeCreated",pk),a.removeEventListener("onLogToGel",mk),a.removeEventListener("onLogVeClicked",qk),a.removeEventListener("onLogVesShown",rk),a.removeEventListener("onReady",sk),a.destroy();lk={}});
window.addEventListener?(window.addEventListener("load",tk),window.addEventListener("unload",uk)):window.attachEvent&&(window.attachEvent("onload",tk),window.attachEvent("onunload",uk));}).call(this);
