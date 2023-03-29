(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var k;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function p(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
p("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
p("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function ia(a){return a.raw=a}
function r(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if("number"==typeof a.length)return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function ja(a){if(!(a instanceof Array)){a=r(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ka(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var la="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ka(d,e)&&(a[e]=d[e])}return a};
p("Object.assign",function(a){return a||la});
var oa="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},pa=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=oa(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),qa;
if("function"==typeof Object.setPrototypeOf)qa=Object.setPrototypeOf;else{var ra;a:{var sa={a:!0},ta={};try{ta.__proto__=sa;ra=ta.a;break a}catch(a){}ra=!1}qa=ra?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var ua=qa;
function v(a,b){a.prototype=oa(b.prototype);a.prototype.constructor=a;if(ua)ua(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.va=b.prototype}
function va(){this.v=!1;this.l=null;this.i=void 0;this.h=1;this.m=this.s=0;this.ra=this.j=null}
function wa(a){if(a.v)throw new TypeError("Generator is already running");a.v=!0}
va.prototype.X=function(a){this.i=a};
function xa(a,b){a.j={nd:b,xd:!0};a.h=a.s||a.m}
va.prototype.return=function(a){this.j={return:a};this.h=this.m};
function w(a,b,c){a.h=c;return{value:b}}
va.prototype.A=function(a){this.h=a};
function ya(a,b,c){a.s=b;void 0!=c&&(a.m=c)}
function Aa(a,b){a.h=b;a.s=0}
function Ba(a){a.s=0;var b=a.j.nd;a.j=null;return b}
function Ca(a){a.ra=[a.j];a.s=0;a.m=0}
function Ea(a){var b=a.ra.splice(0)[0];(b=a.j=a.j||b)?b.xd?a.h=a.s||a.m:void 0!=b.A&&a.m<b.A?(a.h=b.A,a.j=null):a.h=a.m:a.h=0}
function Fa(a){this.h=new va;this.i=a}
function Ga(a,b){wa(a.h);var c=a.h.l;if(c)return Ha(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ia(a)}
function Ha(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.v=!1,e;var f=e.value}catch(g){return a.h.l=null,xa(a.h,g),Ia(a)}a.h.l=null;d.call(a.h,f);return Ia(a)}
function Ia(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.v=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,xa(a.h,c)}a.h.v=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.xd)throw b.nd;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ja(a){this.next=function(b){wa(a.h);a.h.l?b=Ha(a,a.h.l.next,b,a.h.X):(a.h.X(b),b=Ia(a));return b};
this.throw=function(b){wa(a.h);a.h.l?b=Ha(a,a.h.l["throw"],b,a.h.X):(xa(a.h,b),b=Ia(a));return b};
this.return=function(b){return Ga(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ka(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function x(a){return Ka(new Ja(new Fa(a)))}
function La(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
p("Reflect",function(a){return a?a:{}});
p("Reflect.construct",function(){return pa});
p("Reflect.setPrototypeOf",function(a){return a?a:ua?function(b,c){try{return ua(b,c),!0}catch(d){return!1}}:null});
p("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.v=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(l){h.reject(l)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var l=g[h];g[h]=null;try{l()}catch(m){this.l(m)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(m){return function(n){l||(l=!0,m.call(h,n))}}
var h=this,l=!1;return{resolve:g(this.T),reject:g(this.m)}};
b.prototype.T=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.Y(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.M(g):this.s(g)}};
b.prototype.M=function(g){var h=void 0;try{h=g.then}catch(l){this.m(l);return}"function"==typeof h?this.aa(h,g):this.s(g)};
b.prototype.m=function(g){this.X(2,g)};
b.prototype.s=function(g){this.X(1,g)};
b.prototype.X=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.V();this.ra()};
b.prototype.V=function(){var g=this;e(function(){if(g.H()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.H=function(){if(this.v)return!1;var g=da.CustomEvent,h=da.Event,l=da.dispatchEvent;if("undefined"===typeof l)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return l(g)};
b.prototype.ra=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.Y=function(g){var h=this.l();g.cc(h.resolve,h.reject)};
b.prototype.aa=function(g,h){var l=this.l();try{g.call(h,l.resolve,l.reject)}catch(m){l.reject(m)}};
b.prototype.then=function(g,h){function l(u,t){return"function"==typeof u?function(z){try{m(u(z))}catch(C){n(C)}}:t}
var m,n,q=new b(function(u,t){m=u;n=t});
this.cc(l(g,m),l(h,n));return q};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.cc=function(g,h){function l(){switch(m.h){case 1:g(m.j);break;case 2:h(m.j);break;default:throw Error("Unexpected state: "+m.h);}}
var m=this;null==this.i?f.i(l):this.i.push(l);this.v=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,l){l(g)})};
b.race=function(g){return new b(function(h,l){for(var m=r(g),n=m.next();!n.done;n=m.next())d(n.value).cc(h,l)})};
b.all=function(g){var h=r(g),l=h.next();return l.done?d([]):new b(function(m,n){function q(z){return function(C){u[z]=C;t--;0==t&&m(u)}}
var u=[],t=0;do u.push(void 0),t++,d(l.value).cc(q(u.length-1),n),l=h.next();while(!l.done)})};
return b});
p("WeakMap",function(a){function b(l){this.h=(h+=Math.random()+1).toString();if(l){l=r(l);for(var m;!(m=l.next()).done;)m=m.value,this.set(m[0],m[1])}}
function c(){}
function d(l){var m=typeof l;return"object"===m&&null!==l||"function"===m}
function e(l){if(!ka(l,g)){var m=new c;ba(l,g,{value:m})}}
function f(l){var m=Object[l];m&&(Object[l]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return m(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var l=Object.seal({}),m=Object.seal({}),n=new a([[l,2],[m,3]]);if(2!=n.get(l)||3!=n.get(m))return!1;n.delete(l);n.set(m,4);return!n.has(l)&&4==n.get(m)}catch(q){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(l,m){if(!d(l))throw Error("Invalid WeakMap key");e(l);if(!ka(l,g))throw Error("WeakMap key fail: "+l);l[g][this.h]=m;return this};
b.prototype.get=function(l){return d(l)&&ka(l,g)?l[g][this.h]:void 0};
b.prototype.has=function(l){return d(l)&&ka(l,g)&&ka(l[g],this.h)};
b.prototype.delete=function(l){return d(l)&&ka(l,g)&&ka(l[g],this.h)?delete l[g][this.h]:!1};
return b});
p("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,l){var m=h.h;return ea(function(){if(m){for(;m.head!=h.h;)m=m.previous;for(;m.next!=m.head;)return m=m.next,{done:!1,value:l(m)};m=null}return{done:!0,value:void 0}})}
function d(h,l){var m=l&&typeof l;"object"==m||"function"==m?f.has(l)?m=f.get(l):(m=""+ ++g,f.set(l,m)):m="p_"+l;var n=h.data_[m];if(n&&ka(h.data_,m))for(h=0;h<n.length;h++){var q=n[h];if(l!==l&&q.key!==q.key||l===q.key)return{id:m,list:n,index:h,entry:q}}return{id:m,list:n,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=r(h);for(var l;!(l=h.next()).done;)l=l.value,this.set(l[0],l[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),l=new a(r([[h,"s"]]));if("s"!=l.get(h)||1!=l.size||l.get({x:4})||l.set({x:4},"t")!=l||2!=l.size)return!1;var m=l.entries(),n=m.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=m.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!m.next().done?!1:!0}catch(q){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,l){h=0===h?0:h;var m=d(this,h);m.list||(m.list=this.data_[m.id]=[]);m.entry?m.entry.value=l:(m.entry={next:this.h,previous:this.h.previous,head:this.h,key:h,value:l},m.list.push(m.entry),this.h.previous.next=m.entry,this.h.previous=m.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,l){for(var m=this.entries(),n;!(n=m.next()).done;)n=n.value,h.call(l,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ma(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
p("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ma(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
p("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
p("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ma(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
p("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
p("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
p("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
function Na(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
p("Array.prototype.entries",function(a){return a?a:function(){return Na(this,function(b,c){return[b,c]})}});
p("Array.prototype.keys",function(a){return a?a:function(){return Na(this,function(b){return b})}});
p("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
p("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
p("Array.prototype.values",function(a){return a?a:function(){return Na(this,function(b,c){return c})}});
p("Object.setPrototypeOf",function(a){return a||ua});
p("Set",function(a){function b(c){this.h=new Map;if(c){c=r(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(r([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
p("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push([d,b[d]]);return c}});
p("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
p("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
p("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ma(this,b,"includes").indexOf(b,c||0)}});
p("globalThis",function(a){return a||da});
p("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push(b[d]);return c}});
var Oa=Oa||{},y=this||self;function A(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function B(a,b){a=a.split(".");b=b||y;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Pa(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Qa(a){var b=Pa(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Sa(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ta(a){return Object.prototype.hasOwnProperty.call(a,Ua)&&a[Ua]||(a[Ua]=++Va)}
var Ua="closure_uid_"+(1E9*Math.random()>>>0),Va=0;function Wa(a,b,c){return a.call.apply(a.bind,arguments)}
function Xa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Ya(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Ya=Wa:Ya=Xa;return Ya.apply(null,arguments)}
function Za(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function $a(a,b){function c(){}
c.prototype=b.prototype;a.va=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.rg=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function ab(a){return a}
;function bb(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,bb);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
$a(bb,Error);bb.prototype.name="CustomError";function cb(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function db(){}
function eb(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var fb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},gb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},hb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},ib=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},jb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
gb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function kb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function lb(a,b){b=fb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function mb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Qa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function nb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function ob(a){var b=pb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function qb(a){for(var b in a)return!1;return!0}
function rb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function sb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function tb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function ub(a){var b={},c;for(c in a)b[c]=a[c];return b}
function vb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=vb(a[c]);return b}
var wb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function xb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<wb.length;f++)c=wb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var yb;function zb(){if(void 0===yb){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:ab,createScript:ab,createScriptURL:ab})}catch(c){y.console&&y.console.error(c.message)}yb=a}else yb=a}return yb}
;function Ab(a,b){this.j=a===Bb&&b||""}
Ab.prototype.i=!0;Ab.prototype.h=function(){return this.j};
function Cb(a){return new Ab(Bb,a)}
var Bb={};Cb("");var Db={};function Eb(a,b){this.j=b===Db?a:"";this.i=!0}
Eb.prototype.toString=function(){return this.j.toString()};
Eb.prototype.h=function(){return this.j.toString()};function Fb(a,b){this.j=b===Gb?a:""}
Fb.prototype.toString=function(){return this.j+""};
Fb.prototype.i=!0;Fb.prototype.h=function(){return this.j.toString()};
function Hb(a){if(a instanceof Fb&&a.constructor===Fb)return a.j;Pa(a);return"type_error:TrustedResourceUrl"}
var Gb={};function Ib(a){var b=zb();a=b?b.createScriptURL(a):a;return new Fb(a,Gb)}
;var Jb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function Kb(a,b){return a<b?-1:a>b?1:0}
;function Lb(a,b){this.j=b===Mb?a:""}
Lb.prototype.toString=function(){return this.j.toString()};
Lb.prototype.i=!0;Lb.prototype.h=function(){return this.j.toString()};
function Nb(a){if(a instanceof Lb&&a.constructor===Lb)return a.j;Pa(a);return"type_error:SafeUrl"}
var Ob;try{new URL("s://g"),Ob=!0}catch(a){Ob=!1}var Pb=Ob,Mb={},Qb=new Lb("about:invalid#zClosurez",Mb);var Rb,Ub=B("CLOSURE_FLAGS"),Vb=Ub&&Ub[610401301];Rb=null!=Vb?Vb:!1;function Wb(){var a=y.navigator;return a&&(a=a.userAgent)?a:""}
var Xb,Yb=y.navigator;Xb=Yb?Yb.userAgentData||null:null;function Zb(a){return Rb?Xb?Xb.brands.some(function(b){return(b=b.brand)&&-1!=b.indexOf(a)}):!1:!1}
function D(a){return-1!=Wb().indexOf(a)}
;function $b(){return Rb?!!Xb&&0<Xb.brands.length:!1}
function ac(){return $b()?!1:D("Opera")}
function bc(){return $b()?!1:D("Trident")||D("MSIE")}
function cc(){return $b()?!1:D("Edge")}
function dc(){return $b()?Zb("Microsoft Edge"):D("Edg/")}
function ec(){return D("Firefox")||D("FxiOS")}
function fc(){return D("Safari")&&!(gc()||($b()?0:D("Coast"))||ac()||cc()||dc()||($b()?Zb("Opera"):D("OPR"))||ec()||D("Silk")||D("Android"))}
function gc(){return $b()?Zb("Chromium"):(D("Chrome")||D("CriOS"))&&!cc()||D("Silk")}
function hc(){return D("Android")&&!(gc()||ec()||ac()||D("Silk"))}
function ic(a){var b={};a.forEach(function(c){b[c[0]]=c[1]});
return function(c){return b[c.find(function(d){return d in b})]||""}}
function jc(a){var b=Wb();if("Internet Explorer"===a){if(bc())if((a=/rv: *([\d\.]*)/.exec(b))&&a[1])b=a[1];else{a="";var c=/MSIE +([\d\.]+)/.exec(b);if(c&&c[1])if(b=/Trident\/(\d.\d)/.exec(b),"7.0"==c[1])if(b&&b[1])switch(b[1]){case "4.0":a="8.0";break;case "5.0":a="9.0";break;case "6.0":a="10.0";break;case "7.0":a="11.0"}else a="7.0";else a=c[1];b=a}else b="";return b}var d=RegExp("([A-Z][\\w ]+)/([^\\s]+)\\s*(?:\\((.*?)\\))?","g");c=[];for(var e;e=d.exec(b);)c.push([e[1],e[2],e[3]||void 0]);b=ic(c);
switch(a){case "Opera":if(ac())return b(["Version","Opera"]);if($b()?Zb("Opera"):D("OPR"))return b(["OPR"]);break;case "Microsoft Edge":if(cc())return b(["Edge"]);if(dc())return b(["Edg"]);break;case "Chromium":if(gc())return b(["Chrome","CriOS","HeadlessChrome"])}return"Firefox"===a&&ec()||"Safari"===a&&fc()||"Android Browser"===a&&hc()||"Silk"===a&&D("Silk")?(b=c[2])&&b[1]||"":""}
function kc(a){if($b()&&"Silk"!==a){var b=Xb.brands.find(function(c){return c.brand===a});
if(!b||!b.version)return NaN;b=b.version.split(".")}else{b=jc(a);if(""===b)return NaN;b=b.split(".")}return 0===b.length?NaN:Number(b[0])}
;var lc={};function mc(a){this.j=lc===lc?a:"";this.i=!0}
mc.prototype.h=function(){return this.j.toString()};
mc.prototype.toString=function(){return this.j.toString()};function nc(a,b){if(!(b instanceof Lb||b instanceof Lb)){b="object"==typeof b&&b.i?b.h():String(b);b:{var c=b;if(Pb){try{var d=new URL(c)}catch(e){c="https:";break b}c=d.protocol}else c:{d=document.createElement("a");try{d.href=c}catch(e){c=void 0;break c}c=d.protocol;c=":"===c||""===c?"https:":c}}"javascript:"!==c||(b="about:invalid#zClosurez");b=new Lb(b,Mb)}a.href=Nb(b)}
function oc(a,b){a.rel="stylesheet";a.href=Hb(b).toString();(b=qc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function rc(){return qc("script[nonce]")}
var sc=/^[\w+/_-]+[=]{0,2}$/;function qc(a,b){b=(b||y).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&sc.test(a)?a:"":""}
;function tc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var uc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function vc(a){return a?decodeURI(a):a}
function wc(a,b){return b.match(uc)[a]||null}
function xc(a){return vc(wc(3,a))}
function yc(a){var b=a.match(uc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function zc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function Ac(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)Ac(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function Bc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)Ac(a[b],a[b+1],c);return c.join("&")}
function Cc(a){var b=[],c;for(c in a)Ac(c,a[c],b);return b.join("&")}
function Dc(a,b){var c=2==arguments.length?Bc(arguments[1],0):Bc(arguments,1);return zc(a,c)}
function Ec(a,b){b=Cc(b);return zc(a,b)}
function Fc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return zc(a,b+c)}
function Gc(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var Hc=/#|$/,Ic=/[?&]($|#)/;function Jc(a,b){for(var c=a.search(Hc),d=0,e,f=[];0<=(e=Gc(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(Ic,"$1")}
;function Kc(a){y.setTimeout(function(){throw a;},0)}
;function Lc(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);128>e?b[c++]=e:(2048>e?b[c++]=e>>6|192:(55296==(e&64512)&&d+1<a.length&&56320==(a.charCodeAt(d+1)&64512)?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}return b}
;function Mc(){return Rb?!!Xb&&!!Xb.platform:!1}
function Nc(){return Mc()?"Android"===Xb.platform:D("Android")}
function Oc(){return D("iPhone")&&!D("iPod")&&!D("iPad")}
function Vc(){var a=Wb(),b="";if(Mc()?"Windows"===Xb.platform:D("Windows"))b=/Windows (?:NT|Phone) ([0-9.]+)/,b=(a=b.exec(a))?a[1]:"0.0";else if(Oc()||D("iPad")||D("iPod"))b=/(?:iPhone|iPod|iPad|CPU)\s+OS\s+(\S+)/,b=(a=b.exec(a))&&a[1].replace(/_/g,".");else if(Mc()?"macOS"===Xb.platform:D("Macintosh"))b=/Mac OS X ([0-9_.]+)/,b=(a=b.exec(a))?a[1].replace(/_/g,"."):"10";else if(-1!=Wb().toLowerCase().indexOf("kaios"))b=/(?:KaiOS)\/(\S+)/i,b=(a=b.exec(a))&&a[1];else if(Nc())b=/Android\s+([^\);]+)(\)|;)/,
b=(a=b.exec(a))&&a[1];else if(Mc()?"Chrome OS"===Xb.platform:D("CrOS"))b=/(?:CrOS\s+(?:i686|x86_64)\s+([0-9.]+))/,b=(a=b.exec(a))&&a[1];a=0;b=Jb(String(b||"")).split(".");for(var c=Jb("12").split("."),d=Math.max(b.length,c.length),e=0;0==a&&e<d;e++){var f=b[e]||"",g=c[e]||"";do{f=/(\d*)(\D*)(.*)/.exec(f)||["","","",""];g=/(\d*)(\D*)(.*)/.exec(g)||["","","",""];if(0==f[0].length&&0==g[0].length)break;a=Kb(0==f[1].length?0:parseInt(f[1],10),0==g[1].length?0:parseInt(g[1],10))||Kb(0==f[2].length,0==
g[2].length)||Kb(f[2],g[2]);f=f[3];g=g[3]}while(0==a)}}
;function Wc(a){Wc[" "](a);return a}
Wc[" "]=function(){};var Xc=ac(),Yc=bc(),Zc=D("Edge"),$c=D("Gecko")&&!(-1!=Wb().toLowerCase().indexOf("webkit")&&!D("Edge"))&&!(D("Trident")||D("MSIE"))&&!D("Edge"),ad=-1!=Wb().toLowerCase().indexOf("webkit")&&!D("Edge"),bd=Nc();function cd(){var a=y.document;return a?a.documentMode:void 0}
var dd;a:{var ed="",fd=function(){var a=Wb();if($c)return/rv:([^\);]+)(\)|;)/.exec(a);if(Zc)return/Edge\/([\d\.]+)/.exec(a);if(Yc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(ad)return/WebKit\/(\S+)/.exec(a);if(Xc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
fd&&(ed=fd?fd[1]:"");if(Yc){var gd=cd();if(null!=gd&&gd>parseFloat(ed)){dd=String(gd);break a}}dd=ed}var hd=dd,id;if(y.document&&Yc){var jd=cd();id=jd?jd:parseInt(hd,10)||void 0}else id=void 0;var kd=id;var ld=Oc()||D("iPod"),md=D("iPad");hc();gc();var nd=fc()&&!(Oc()||D("iPad")||D("iPod"));var od={},pd=null;function qd(a,b){Qa(a);void 0===b&&(b=0);rd();b=od[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],l=a[e+2],m=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|l>>6];l=b[l&63];c[f++]=""+m+g+h+l}m=0;l=d;switch(a.length-e){case 2:m=a[e+1],l=b[(m&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|m>>4]+l+d}return c.join("")}
function sd(a){var b=a.length,c=3*b/4;c%3?c=Math.floor(c):-1!="=.".indexOf(a[b-1])&&(c=-1!="=.".indexOf(a[b-2])?c-2:c-1);var d=new Uint8Array(c),e=0;td(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function td(a,b){function c(l){for(;d<a.length;){var m=a.charAt(d++),n=pd[m];if(null!=n)return n;if(!/^[\s\xa0]*$/.test(m))throw Error("Unknown base64 encoding at char: "+m);}return l}
rd();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(64===h&&-1===e)break;b(e<<2|f>>4);64!=g&&(b(f<<4&240|g>>2),64!=h&&b(g<<6&192|h))}}
function rd(){if(!pd){pd={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;5>c;c++){var d=a.concat(b[c].split(""));od[c]=d;for(var e=0;e<d.length;e++){var f=d[e];void 0===pd[f]&&(pd[f]=e)}}}}
;var ud="undefined"!==typeof Uint8Array,vd=!Yc&&"function"===typeof y.btoa;function wd(a){if(!vd)return qd(a);for(var b="";10240<a.length;)b+=String.fromCharCode.apply(null,a.subarray(0,10240)),a=a.subarray(10240);b+=String.fromCharCode.apply(null,a);return btoa(b)}
var xd=/[-_.]/g,yd={"-":"+",_:"/",".":"="};function zd(a){return yd[a]||""}
function Ad(a){return ud&&null!=a&&a instanceof Uint8Array}
var Bd={};var Cd;function Dd(a){if(a!==Bd)throw Error("illegal external caller");}
function Ed(a,b){Dd(b);this.h=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
Ed.prototype.sizeBytes=function(){Dd(Bd);var a=this.h;if(null!=a&&!Ad(a))if("string"===typeof a)if(vd){xd.test(a)&&(a=a.replace(xd,zd));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=sd(a);else Pa(a),a=null;return(a=null==a?a:this.h=a)?a.length:0};var Fd="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol():void 0;function Gd(a,b){if(Fd)return a[Fd]|=b;if(void 0!==a.Ca)return a.Ca|=b;Object.defineProperties(a,{Ca:{value:b,configurable:!0,writable:!0,enumerable:!1}});return b}
function Hd(a,b){var c=F(a);(c&b)!==b&&(Object.isFrozen(a)&&(a=Array.prototype.slice.call(a)),Id(a,c|b));return a}
function Jd(a,b){Fd?a[Fd]&&(a[Fd]&=~b):void 0!==a.Ca&&(a.Ca&=~b)}
function F(a){var b;Fd?b=a[Fd]:b=a.Ca;return null==b?0:b}
function Id(a,b){Fd?a[Fd]=b:void 0!==a.Ca?a.Ca=b:Object.defineProperties(a,{Ca:{value:b,configurable:!0,writable:!0,enumerable:!1}});return a}
function Kd(a){Gd(a,1);return a}
function Ld(a,b){Id(b,(a|0)&-51)}
function Md(a,b){Id(b,(a|18)&-41)}
;var Nd={};function Rd(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var Sd,Td=Object.freeze(Id([],23));function Ud(a){if(F(a.P)&2)throw Error();}
function Vd(a){var b=a.length;(b=b?a[b-1]:void 0)&&Rd(b)?b.g=1:(b={},a.push((b.g=1,b)))}
;function Wd(a){if(null!=a&&"number"!==typeof a)throw Error("Value of float/double field must be a number|null|undefined, found "+typeof a+": "+a);return a}
function Xd(a){return a.displayName||a.name||"unknown type name"}
function Yd(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Xd(b)+" but got "+(a&&Xd(a.constructor)));return a}
function Zd(a,b){var c=F(a),d=c;0===d&&(d|=b&16);d|=b&2;d!==c&&Id(a,d)}
;function $d(a){var b=a.j+a.fb;return a.xa||(a.xa=a.P[b]={})}
function ae(a,b,c){return-1===b?null:b>=a.j?a.xa?a.xa[b]:void 0:c&&a.xa&&(c=a.xa[b],null!=c)?c:a.P[b+a.fb]}
function G(a,b,c,d){Ud(a);return be(a,b,c,d)}
function be(a,b,c,d){a.m&&(a.m=void 0);if(b>=a.j||d)return $d(a)[b]=c,a;a.P[b+a.fb]=c;(c=a.xa)&&b in c&&delete c[b];return a}
function ce(a){return void 0!==de(a,ee,11,!1)}
function fe(a,b,c,d,e){var f=ae(a,b,d);Array.isArray(f)||(f=Td);var g=F(f);g&1||Kd(f);if(e)g&2||Gd(f,18),c&1||Object.freeze(f);else{e=!(c&2);var h=g&2;c&1||!h?e&&g&16&&!h&&Jd(f,16):(f=Kd(Array.prototype.slice.call(f)),be(a,b,f,d))}return f}
function ge(a,b,c,d){Ud(a);(c=he(a,c))&&c!==b&&null!=d&&be(a,c,void 0,!1);return be(a,b,d)}
function he(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=ae(a,e)&&(0!==c&&be(a,c,void 0,!1),c=e)}return c}
function de(a,b,c,d){var e=ae(a,c,d);var f=F(a.P),g=!1;null==e||"object"!==typeof e||(g=Array.isArray(e))||e.Jc!==Nd?g?(Zd(e,f),b=new b(e)):b=void 0:b=e;b!==e&&null!=b&&be(a,c,b,d);return b}
function ie(a,b,c,d){d=void 0===d?!1:d;b=de(a,b,c,d);if(null==b)return b;if(!(F(a.P)&2)){var e=je(b);e!==b&&(b=e,be(a,c,b,d))}return b}
function ke(a,b,c,d,e){var f=!!(e&2);a.i||(a.i={});var g=a.i[c],h=fe(a,c,3,void 0,f);if(!g){var l=h;g=[];f=!!(e&2);h=!!(F(l)&2);var m=l;!f&&h&&(l=Array.prototype.slice.call(l));var n=e|(h?2:0);e=h;for(var q=0;q<l.length;q++){var u=l[q];var t=b;Array.isArray(u)?(Zd(u,n),u=new t(u)):u=void 0;void 0!==u&&(e=e||!!(2&F(u.P)),g.push(u))}a.i[c]=g;b=l;e=!e;n=F(b);l=n|33;l=e?l|8:l&-9;n!=l&&(Object.isFrozen(b)&&(b=Array.prototype.slice.call(b)),Id(b,l));l=b;m!==l&&be(a,c,l);(f||1===d&&h)&&Gd(g,18);(f||1===
d)&&Object.freeze(g);return g}if(3===d)return g;f||((f=Object.isFrozen(g),1!==d||f)?2===d&&f&&(g=Array.prototype.slice.call(g),a.i[c]=g):Object.freeze(g));return g}
function H(a,b,c,d){Ud(a);null!=d?Yd(d,b):d=void 0;return be(a,c,d)}
function le(a,b,c,d,e){Ud(a);null!=e?Yd(e,b):e=void 0;ge(a,c,d,e)}
function me(a,b,c,d,e){Ud(a);var f=null==d?Td:Kd([]);if(null!=d){for(var g=!!d.length,h=0;h<d.length;h++){var l=d[h];Yd(l,b);g=g&&!(F(l.P)&2);f[h]=l.P}f=Hd(f,(g?8:0)|1);a.i||(a.i={});a.i[c]=d}else a.i&&(a.i[c]=void 0);return be(a,c,f,e)}
function ne(a,b,c,d){var e=F(a.P);if(e&2)throw Error();e=ke(a,c,b,2,e);c=null!=d?Yd(d,c):new c;a=fe(a,b,2,void 0,!1);e.push(c);a.push(c.P);F(c.P)&2&&Jd(a,8)}
function oe(a,b,c){Pa(c);return G(a,b,c)}
function pe(){var a=new qe;return G(a,1,1)}
function re(a,b){return null==a?b:a}
function se(a,b){return re(ae(a,b),"")}
;var te;function ue(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(a)if(Array.isArray(a)){if(0!==(F(a)&128))return a=Array.prototype.slice.call(a),Vd(a),a}else{if(Ad(a))return wd(a);if(a instanceof Ed){var b=a.h;return null==b?"":"string"===typeof b?b:a.h=wd(b)}}}return a}
;function ve(a,b,c,d,e,f){if(null!=a){if(Array.isArray(a))a=e&&0==a.length&&F(a)&1?void 0:f&&F(a)&2?a:we(a,b,c,void 0!==d,e,f);else if(Rd(a)){var g={},h;for(h in a)g[h]=ve(a[h],b,c,d,e,f);a=g}else a=b(a,d);return a}}
function we(a,b,c,d,e,f){var g=F(a);d=d?!!(g&16):void 0;a=Array.prototype.slice.call(a);for(var h=0;h<a.length;h++)a[h]=ve(a[h],b,c,d,e,f);c(g,a);return a}
function xe(a){return a.Jc===Nd?a.toJSON():ue(a)}
function ye(a,b){a&128&&Vd(b)}
;function ze(a,b,c){c=void 0===c?Md:c;if(null!=a){if(ud&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=F(a);if(d&2)return a;if(b&&!(d&32)&&(d&16||0===d))return Id(a,d|18),a;a=we(a,ze,d&4?Md:c,!0,!1,!0);b=F(a);b&4&&b&2&&Object.freeze(a);return a}return a.Jc===Nd?Ae(a):a}}
function Be(a,b,c,d,e,f,g){(a=a.i&&a.i[c])?(d=0<a.length?a[0].constructor:void 0,f=F(a),f&2||(a=ib(a,Ae),Md(f,a),Object.freeze(a)),me(b,d,c,a,e)):G(b,c,ze(d,f,g),e)}
function Ae(a){if(F(a.P)&2)return a;a=Ce(a,!0);Gd(a.P,18);return a}
function Ce(a,b){var c=a.P,d=[];Gd(d,16);var e=a.constructor.h;e&&d.push(e);e=a.xa;if(e){d.length=c.length;var f={};d[d.length-1]=f}0!==(F(c)&128)&&Vd(d);b=b||F(a.P)&2?Md:Ld;f=a.constructor;F(d);te=d;d=new f(d);te=void 0;a.wd&&(d.wd=a.wd.slice());f=!!(F(c)&16);for(var g=e?c.length-1:c.length,h=0;h<g;h++)Be(a,d,h-a.fb,c[h],!1,f,b);if(e)for(var l in e)c=e[l],g=+l,Number.isNaN(g),Be(a,d,g,c,!0,f,b);return d}
function je(a){if(!(F(a.P)&2))return a;var b=Ce(a,!1);b.m=a;return b}
;function I(a,b,c,d){null==a&&(a=te);te=void 0;var e=this.constructor.h;if(null==a){a=e?[e]:[];var f=48;var g=!0;d&&(f|=128);Id(a,f)}else{if(!Array.isArray(a))throw Error();if(e&&e!==a[0])throw Error();f=Gd(a,0)|32;g=0!==(16&f);if(d){if(f|=128,0<a.length){var h=a[a.length-1];if(Rd(h)&&"g"in h){delete h.g;var l=!0,m;for(m in h){l=!1;break}l&&a.pop()}}}else if(128&f)throw Error();Id(a,f)}this.fb=e?0:-1;this.i=void 0;this.P=a;a:{f=this.P.length;e=f-1;if(f&&(f=this.P[e],Rd(f))){this.xa=f;this.j=e-this.fb;
break a}void 0!==b&&-1<b?(this.j=Math.max(b,e+1-this.fb),this.xa=void 0):this.j=Number.MAX_VALUE}if(!d&&this.xa&&"g"in this.xa)throw Error('Unexpected "g" flag in sparse object of message that is not a group type.');if(c){b=g&&!0;d=this.j;var n;for(g=0;g<c.length;g++)e=c[g],e<d?(e+=this.fb,(f=a[e])?De(f,b):a[e]=Td):(n||(n=$d(this)),(f=n[e])?De(f,b):n[e]=Td)}F(this.P)}
I.prototype.toJSON=function(){var a=this.P,b;Sd?b=a:b=we(a,xe,ye,void 0,!1,!1);return b};
function Ee(a){Sd=!0;try{return JSON.stringify(a.toJSON(),Fe)}finally{Sd=!1}}
I.prototype.clone=function(){return Ce(this,!1)};
function De(a,b){if(Array.isArray(a)){var c=F(a),d=1;!b||c&2||(d|=16);(c&d)!==d&&Id(a,c|d)}}
I.prototype.Jc=Nd;I.prototype.toString=function(){return this.P.toString()};
function Fe(a,b){return ue(b)}
;function Ge(a){this.gd=a}
;function He(a,b,c){this.i=a;this.l=b;this.h=c||[];this.sb=new Map}
k=He.prototype;k.be=function(a){var b=La.apply(1,arguments),c=this.yc(b);c?c.push(new Ge(a)):this.Kd(a,b)};
k.Kd=function(a){this.sb.set(this.pd(La.apply(1,arguments)),[new Ge(a)])};
k.yc=function(){var a=this.pd(La.apply(0,arguments));return this.sb.has(a)?this.sb.get(a):void 0};
k.se=function(){var a=this.yc(La.apply(0,arguments));return a&&a.length?a[0]:void 0};
k.clear=function(){this.sb.clear()};
k.pd=function(){var a=La.apply(0,arguments);return a?a.join(","):"key"};function Ie(a,b){He.call(this,a,3,b)}
v(Ie,He);Ie.prototype.j=function(a){var b=La.apply(1,arguments),c=0,d=this.se(b);d&&(c=d.gd);this.Kd(c+a,b)};function Je(a,b){He.call(this,a,2,b)}
v(Je,He);Je.prototype.j=function(a){this.be(a,La.apply(1,arguments))};function Ke(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function Le(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Qa(d)?Le.apply(null,d):Ke(d)}}
;function K(){this.ra=this.ra;this.X=this.X}
K.prototype.ra=!1;K.prototype.h=function(){return this.ra};
K.prototype.dispose=function(){this.ra||(this.ra=!0,this.L())};
function Me(a,b){Ne(a,Za(Ke,b))}
function Ne(a,b){a.ra?b():(a.X||(a.X=[]),a.X.push(b))}
K.prototype.L=function(){if(this.X)for(;this.X.length;)this.X.shift()()};function Oe(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Oe.prototype.stopPropagation=function(){this.j=!0};
Oe.prototype.preventDefault=function(){this.defaultPrevented=!0};function Pe(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Qe(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Re[c])c=Re[c];else{c=String(c);if(!Re[c]){var f=/function\s+([^\(]+)/m.exec(c);Re[c]=f?f[1]:"[Anonymous]"}c=Re[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function Qe(a,b){b||(b={});b[Se(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[Se(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=Qe(a,b));return c}
function Se(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Re={};var Te=function(){if(!y.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{y.addEventListener("test",function(){},b),y.removeEventListener("test",function(){},b)}catch(c){}return a}();function Ue(a,b){Oe.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
$a(Ue,Oe);var Ve={2:"touch",3:"pen",4:"mouse"};
Ue.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if($c){a:{try{Wc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Ve[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&Ue.va.preventDefault.call(this)};
Ue.prototype.stopPropagation=function(){Ue.va.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Ue.prototype.preventDefault=function(){Ue.va.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var We="closure_listenable_"+(1E6*Math.random()|0);var Xe=0;function Ye(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.hc=e;this.key=++Xe;this.Pb=this.ac=!1}
function Ze(a){a.Pb=!0;a.listener=null;a.proxy=null;a.src=null;a.hc=null}
;function $e(a){this.src=a;this.listeners={};this.h=0}
$e.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=af(a,b,d,e);-1<g?(b=a[g],c||(b.ac=!1)):(b=new Ye(b,this.src,f,!!d,e),b.ac=c,a.push(b));return b};
$e.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=af(e,b,c,d);return-1<b?(Ze(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function bf(a,b){var c=b.type;c in a.listeners&&lb(a.listeners[c],b)&&(Ze(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function af(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Pb&&f.listener==b&&f.capture==!!c&&f.hc==d)return e}return-1}
;var cf="closure_lm_"+(1E6*Math.random()|0),df={},ef=0;function ff(a,b,c,d,e){if(d&&d.once)lf(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)ff(a,b[f],c,d,e);else c=mf(c),a&&a[We]?a.La(b,c,Sa(d)?!!d.capture:!!d,e):nf(a,b,c,!1,d,e)}
function nf(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Sa(e)?!!e.capture:!!e,h=of(a);h||(a[cf]=h=new $e(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=pf();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Te||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(qf(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");ef++}}
function pf(){function a(c){return b.call(a.src,a.listener,c)}
var b=rf;return a}
function lf(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)lf(a,b[f],c,d,e);else c=mf(c),a&&a[We]?a.l.add(String(b),c,!0,Sa(d)?!!d.capture:!!d,e):nf(a,b,c,!0,d,e)}
function sf(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)sf(a,b[f],c,d,e);else(d=Sa(d)?!!d.capture:!!d,c=mf(c),a&&a[We])?a.l.remove(String(b),c,d,e):a&&(a=of(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=af(b,c,d,e)),(c=-1<a?b[a]:null)&&tf(c))}
function tf(a){if("number"!==typeof a&&a&&!a.Pb){var b=a.src;if(b&&b[We])bf(b.l,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(qf(c),d):b.addListener&&b.removeListener&&b.removeListener(d);ef--;(c=of(b))?(bf(c,a),0==c.h&&(c.src=null,b[cf]=null)):Ze(a)}}}
function qf(a){return a in df?df[a]:df[a]="on"+a}
function rf(a,b){if(a.Pb)a=!0;else{b=new Ue(b,this);var c=a.listener,d=a.hc||a.src;a.ac&&tf(a);a=c.call(d,b)}return a}
function of(a){a=a[cf];return a instanceof $e?a:null}
var uf="__closure_events_fn_"+(1E9*Math.random()>>>0);function mf(a){if("function"===typeof a)return a;a[uf]||(a[uf]=function(b){return a.handleEvent(b)});
return a[uf]}
;function vf(){K.call(this);this.l=new $e(this);this.Yd=this;this.Oa=null}
$a(vf,K);vf.prototype[We]=!0;vf.prototype.addEventListener=function(a,b,c,d){ff(this,a,b,c,d)};
vf.prototype.removeEventListener=function(a,b,c,d){sf(this,a,b,c,d)};
function wf(a,b){var c=a.Oa;if(c){var d=[];for(var e=1;c;c=c.Oa)d.push(c),++e}a=a.Yd;c=b.type||b;"string"===typeof b?b=new Oe(b,a):b instanceof Oe?b.target=b.target||a:(e=b,b=new Oe(c,a),xb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=xf(g,c,!0,b)&&e}b.j||(g=b.h=a,e=xf(g,c,!0,b)&&e,b.j||(e=xf(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=xf(g,c,!1,b)&&e}
vf.prototype.L=function(){vf.va.L.call(this);if(this.l){var a=this.l,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Ze(d[e]);delete a.listeners[c];a.h--}}this.Oa=null};
vf.prototype.La=function(a,b,c,d){return this.l.add(String(a),b,!1,c,d)};
function xf(a,b,c,d){b=a.l.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Pb&&g.capture==c){var h=g.listener,l=g.hc||g.src;g.ac&&bf(a.l,g);e=!1!==h.call(l,d)&&e}}return e&&!d.defaultPrevented}
;function yf(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
yf.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function zf(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;function Af(a,b){return a+Math.random()*(b-a)}
;function Bf(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
k=Bf.prototype;k.clone=function(){return new Bf(this.x,this.y)};
k.equals=function(a){return a instanceof Bf&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
k.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
k.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
k.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
k.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function Cf(a,b){this.width=a;this.height=b}
k=Cf.prototype;k.clone=function(){return new Cf(this.width,this.height)};
k.aspectRatio=function(){return this.width/this.height};
k.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
k.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
k.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
k.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function Df(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function Ef(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function Ff(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var Gf;function Hf(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!D("Presto")&&(a=function(){var e=Ef("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Ya(function(l){if(("*"==h||l.origin==h)&&l.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!bc()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.fd;c.fd=null;e()}};
return function(e){d.next={fd:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function If(){this.i=this.h=null}
If.prototype.add=function(a,b){var c=Jf.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
If.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Jf=new yf(function(){return new Kf},function(a){return a.reset()});
function Kf(){this.next=this.scope=this.h=null}
Kf.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Kf.prototype.reset=function(){this.next=this.scope=this.h=null};var Lf,Mf=!1,Nf=new If;function Of(a,b){Lf||Pf();Mf||(Lf(),Mf=!0);Nf.add(a,b)}
function Pf(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);Lf=function(){a.then(Qf)}}else Lf=function(){var b=Qf;
"function"!==typeof y.setImmediate||y.Window&&y.Window.prototype&&!cc()&&y.Window.prototype.setImmediate==y.setImmediate?(Gf||(Gf=Hf()),Gf(b)):y.setImmediate(b)}}
function Qf(){for(var a;a=Nf.remove();){try{a.h.call(a.scope)}catch(b){Kc(b)}zf(Jf,a)}Mf=!1}
;function Rf(a){this.h=0;this.v=void 0;this.l=this.i=this.j=null;this.m=this.s=!1;if(a!=db)try{var b=this;a.call(void 0,function(c){Sf(b,2,c)},function(c){Sf(b,3,c)})}catch(c){Sf(this,3,c)}}
function Tf(){this.next=this.context=this.i=this.j=this.h=null;this.l=!1}
Tf.prototype.reset=function(){this.context=this.i=this.j=this.h=null;this.l=!1};
var Uf=new yf(function(){return new Tf},function(a){a.reset()});
function Vf(a,b,c){var d=Uf.get();d.j=a;d.i=b;d.context=c;return d}
function Wf(a){return new Rf(function(b,c){c(a)})}
Rf.prototype.then=function(a,b,c){return Xf(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Rf.prototype.$goog_Thenable=!0;k=Rf.prototype;k.sc=function(a,b){return Xf(this,null,a,b)};
k.catch=Rf.prototype.sc;k.cancel=function(a){if(0==this.h){var b=new Yf(a);Of(function(){Zf(this,b)},this)}};
function Zf(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.l||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Zf(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):$f(c),ag(c,e,3,b)))}a.j=null}else Sf(a,3,b)}
function bg(a,b){a.i||2!=a.h&&3!=a.h||cg(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Xf(a,b,c,d){var e=Vf(null,null,null);e.h=new Rf(function(f,g){e.j=b?function(h){try{var l=b.call(d,h);f(l)}catch(m){g(m)}}:f;
e.i=c?function(h){try{var l=c.call(d,h);void 0===l&&h instanceof Yf?g(h):f(l)}catch(m){g(m)}}:g});
e.h.j=a;bg(a,e);return e.h}
k.lf=function(a){this.h=0;Sf(this,2,a)};
k.mf=function(a){this.h=0;Sf(this,3,a)};
function Sf(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.lf,f=a.mf;if(d instanceof Rf){bg(d,Vf(e||db,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(m){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Sa(d))try{var l=d.then;if("function"===typeof l){dg(d,l,e,f,a);g=!0;break a}}catch(m){f.call(a,m);g=!0;break a}g=!1}}}g||(a.v=c,a.h=b,a.j=null,cg(a),3!=b||c instanceof Yf||eg(a,c))}}
function dg(a,b,c,d,e){function f(l){h||(h=!0,d.call(e,l))}
function g(l){h||(h=!0,c.call(e,l))}
var h=!1;try{b.call(a,g,f)}catch(l){f(l)}}
function cg(a){a.s||(a.s=!0,Of(a.ne,a))}
function $f(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
k.ne=function(){for(var a;a=$f(this);)ag(this,a,this.h,this.v);this.s=!1};
function ag(a,b,c,d){if(3==c&&b.i&&!b.l)for(;a&&a.m;a=a.j)a.m=!1;if(b.h)b.h.j=null,fg(b,c,d);else try{b.l?b.j.call(b.context):fg(b,c,d)}catch(e){gg.call(null,e)}zf(Uf,b)}
function fg(a,b,c){2==b?a.j.call(a.context,c):a.i&&a.i.call(a.context,c)}
function eg(a,b){a.m=!0;Of(function(){a.m&&gg.call(null,b)})}
var gg=Kc;function Yf(a){bb.call(this,a)}
$a(Yf,bb);Yf.prototype.name="cancel";function hg(a,b){vf.call(this);this.j=a||1;this.i=b||y;this.m=Ya(this.jf,this);this.s=Date.now()}
$a(hg,vf);k=hg.prototype;k.enabled=!1;k.za=null;function ig(a,b){a.j=b;a.za&&a.enabled?(a.stop(),a.start()):a.za&&a.stop()}
k.jf=function(){if(this.enabled){var a=Date.now()-this.s;0<a&&a<.8*this.j?this.za=this.i.setTimeout(this.m,this.j-a):(this.za&&(this.i.clearTimeout(this.za),this.za=null),wf(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
k.start=function(){this.enabled=!0;this.za||(this.za=this.i.setTimeout(this.m,this.j),this.s=Date.now())};
k.stop=function(){this.enabled=!1;this.za&&(this.i.clearTimeout(this.za),this.za=null)};
k.L=function(){hg.va.L.call(this);this.stop();delete this.i};
function jg(a,b,c){if("function"===typeof a)c&&(a=Ya(a,c));else if(a&&"function"==typeof a.handleEvent)a=Ya(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:y.setTimeout(a,b||0)}
;function kg(a){K.call(this);this.H=a;this.j=new Map;this.v=new Set;this.l=0;this.m=100;this.flushInterval=3E4;this.i=new hg(this.flushInterval);this.i.La("tick",this.pb,!1,this);Me(this,this.i);this.s=!1}
v(kg,K);k=kg.prototype;k.sendIsolatedPayload=function(a){this.s=a;this.m=1};
function lg(a){a.i.enabled||a.i.start();a.l++;a.l>=a.m&&a.pb()}
k.pb=function(){var a=this.j.values();a=[].concat(ja(a)).filter(function(b){return b.sb.size});
a.length&&this.H.flush(a,this.s);mg(a);this.l=0;this.i.enabled&&this.i.stop()};
k.bd=function(a){var b=La.apply(1,arguments);this.j.has(a)||this.j.set(a,new Ie(a,b))};
k.cd=function(a){var b=La.apply(1,arguments);this.j.has(a)||this.j.set(a,new Je(a,b))};
function ng(a,b){return a.v.has(b)?void 0:a.j.get(b)}
k.uc=function(a){this.Wd.apply(this,[a,1].concat(ja(La.apply(1,arguments))))};
k.Wd=function(a,b){var c=La.apply(2,arguments),d=ng(this,a);d&&d instanceof Ie&&(d.j(b,c),lg(this))};
k.vc=function(a,b){var c=La.apply(2,arguments),d=ng(this,a);d&&d instanceof Je&&(d.j(b,c),lg(this))};
function mg(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function og(a){this.h=a;this.h.bd("/client_streamz/bg/fiec",{Lb:3,Kb:"rk"},{Lb:2,Kb:"ec"})}
function pg(a,b,c){a.h.uc("/client_streamz/bg/fiec",b,c)}
function qg(a){this.h=a;this.h.cd("/client_streamz/bg/fil",{Lb:3,Kb:"rk"})}
function rg(a){this.h=a;this.h.bd("/client_streamz/bg/fsc",{Lb:3,Kb:"rk"})}
function sg(a){this.h=a;this.h.cd("/client_streamz/bg/fsl",{Lb:3,Kb:"rk"})}
;var tg={toString:function(a){var b=[],c=0;a-=-2147483648;b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ".charAt(a%52);for(a=Math.floor(a/52);0<a;)b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".charAt(a%62),a=Math.floor(a/62);return b.join("")}};function ug(a){function b(){c-=d;c-=e;c^=e>>>13;d-=e;d-=c;d^=c<<8;e-=c;e-=d;e^=d>>>13;c-=d;c-=e;c^=e>>>12;d-=e;d-=c;d^=c<<16;e-=c;e-=d;e^=d>>>5;c-=d;c-=e;c^=e>>>3;d-=e;d-=c;d^=c<<10;e-=c;e-=d;e^=d>>>15}
a=vg(a);for(var c=2654435769,d=2654435769,e=314159265,f=a.length,g=f,h=0;12<=g;g-=12,h+=12)c+=wg(a,h),d+=wg(a,h+4),e+=wg(a,h+8),b();e+=f;switch(g){case 11:e+=a[h+10]<<24;case 10:e+=a[h+9]<<16;case 9:e+=a[h+8]<<8;case 8:d+=a[h+7]<<24;case 7:d+=a[h+6]<<16;case 6:d+=a[h+5]<<8;case 5:d+=a[h+4];case 4:c+=a[h+3]<<24;case 3:c+=a[h+2]<<16;case 2:c+=a[h+1]<<8;case 1:c+=a[h+0]}b();return tg.toString(e)}
function vg(a){for(var b=[],c=0;c<a.length;c++)b.push(a.charCodeAt(c));return b}
function wg(a,b){return a[b+0]+(a[b+1]<<8)+(a[b+2]<<16)+(a[b+3]<<24)}
;function xg(a){I.call(this,a)}
v(xg,I);var yg=[1,2,3];function zg(a){I.call(this,a)}
v(zg,I);var Ag=[1,2,3];function Bg(a){I.call(this,a,-1,Cg)}
v(Bg,I);var Cg=[1];function Dg(a){I.call(this,a,-1,Eg)}
v(Dg,I);var Eg=[3,6,4];function Fg(a){I.call(this,a,-1,Gg)}
v(Fg,I);var Gg=[1];function Hg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function Ig(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=m=0}
function b(q){for(var u=g,t=0;64>t;t+=4)u[t/4]=q[t]<<24|q[t+1]<<16|q[t+2]<<8|q[t+3];for(t=16;80>t;t++)q=u[t-3]^u[t-8]^u[t-14]^u[t-16],u[t]=(q<<1|q>>>31)&4294967295;q=e[0];var z=e[1],C=e[2],E=e[3],M=e[4];for(t=0;80>t;t++){if(40>t)if(20>t){var S=E^z&(C^E);var Q=1518500249}else S=z^C^E,Q=1859775393;else 60>t?(S=z&C|E&(z|C),Q=2400959708):(S=z^C^E,Q=3395469782);S=((q<<5|q>>>27)&4294967295)+S+M+Q+u[t]&4294967295;M=E;E=C;C=(z<<30|z>>>2)&4294967295;z=q;q=S}e[0]=e[0]+q&4294967295;e[1]=e[1]+z&4294967295;e[2]=
e[2]+C&4294967295;e[3]=e[3]+E&4294967295;e[4]=e[4]+M&4294967295}
function c(q,u){if("string"===typeof q){q=unescape(encodeURIComponent(q));for(var t=[],z=0,C=q.length;z<C;++z)t.push(q.charCodeAt(z));q=t}u||(u=q.length);t=0;if(0==m)for(;t+64<u;)b(q.slice(t,t+64)),t+=64,n+=64;for(;t<u;)if(f[m++]=q[t++],n++,64==m)for(m=0,b(f);t+64<u;)b(q.slice(t,t+64)),t+=64,n+=64}
function d(){var q=[],u=8*n;56>m?c(h,56-m):c(h,64-(m-56));for(var t=63;56<=t;t--)f[t]=u&255,u>>>=8;b(f);for(t=u=0;5>t;t++)for(var z=24;0<=z;z-=8)q[u++]=e[t]>>z&255;return q}
for(var e=[],f=[],g=[],h=[128],l=1;64>l;++l)h[l]=0;var m,n;a();return{reset:a,update:c,digest:d,je:function(){for(var q=d(),u="",t=0;t<q.length;t++)u+="0123456789ABCDEF".charAt(Math.floor(q[t]/16))+"0123456789ABCDEF".charAt(q[t]%16);return u}}}
;function Jg(a,b,c){var d=String(y.location.href);return d&&a&&b?[b,Kg(Hg(d),a,c||null)].join(" "):null}
function Kg(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],gb(d,function(h){e.push(h)}),Lg(e.join(" "));
var f=[],g=[];gb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];gb(d,function(h){e.push(h)});
a=Lg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function Lg(a){var b=Ig();b.update(a);return b.je().toLowerCase()}
;var Mg={};function Ng(a){this.h=a||{cookie:""}}
k=Ng.prototype;k.isEnabled=function(){if(!y.navigator.cookieEnabled)return!1;if(this.h.cookie)return!0;this.set("TESTCOOKIESENABLED","1",{kc:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
k.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Kg;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.kc}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
k.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Jb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
k.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{kc:0,path:b,domain:c});return d};
k.Bc=function(){return Og(this).keys};
k.clear=function(){for(var a=Og(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function Og(a){a=(a.h.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Jb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var Pg=new Ng("undefined"==typeof document?null:document);function Qg(a){return!!Mg.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function Rg(a){a=void 0===a?!1:a;var b=y.__SAPISID||y.__APISID||y.__3PSAPISID||y.__OVERRIDE_SID;Qg(a)&&(b=b||y.__1PSAPISID);if(b)return!0;var c=new Ng(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID")||c.get("OSID");Qg(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function Sg(a,b,c,d){(a=y[a])||(a=(new Ng(document)).get(b));return a?Jg(a,c,d):null}
function Tg(a,b){b=void 0===b?!1:b;var c=Hg(String(y.location.href)),d=[];if(Rg(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?y.__SAPISID:y.__APISID;e||(e=new Ng(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?Jg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&Qg(b)&&((b=Sg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=Sg("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function Ug(a){I.call(this,a,-1,Vg)}
v(Ug,I);var Vg=[2];function Wg(a){this.h=this.i=this.j=a}
Wg.prototype.reset=function(){this.h=this.i=this.j};
Wg.prototype.getValue=function(){return this.i};function Xg(a){var b=[];Yg(new Zg,a,b);return b.join("")}
function Zg(){}
function Yg(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Yg(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),$g(d,c),c.push(":"),Yg(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":$g(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var ah={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},bh=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function $g(a,b){b.push('"',a.replace(bh,function(c){var d=ah[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),ah[c]=d);return d}),'"')}
;function ch(){}
ch.prototype.h=null;ch.prototype.getOptions=function(){var a;(a=this.h)||(a={},dh(this)&&(a[0]=!0,a[1]=!0),a=this.h=a);return a};var eh;function fh(){}
$a(fh,ch);function gh(a){return(a=dh(a))?new ActiveXObject(a):new XMLHttpRequest}
function dh(a){if(!a.i&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.i=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.i}
eh=new fh;function hh(a){vf.call(this);this.headers=new Map;this.T=a||null;this.i=!1;this.M=this.F=null;this.m=this.aa="";this.j=this.Y=this.v=this.V=!1;this.s=0;this.H=null;this.ma="";this.ha=this.ia=!1}
$a(hh,vf);var ih=/^https?$/i,jh=["POST","PUT"],kh=[];function lh(a,b,c,d,e,f,g){var h=new hh;kh.push(h);b&&h.La("complete",b);h.l.add("ready",h.he,!0,void 0,void 0);f&&(h.s=Math.max(0,f));g&&(h.ia=g);h.send(a,c,d,e)}
k=hh.prototype;k.he=function(){this.dispose();lb(kh,this)};
k.send=function(a,b,c,d){if(this.F)throw Error("[goog.net.XhrIo] Object is active with another request="+this.aa+"; newUri="+a);b=b?b.toUpperCase():"GET";this.aa=a;this.m="";this.V=!1;this.i=!0;this.F=this.T?gh(this.T):gh(eh);this.M=this.T?this.T.getOptions():eh.getOptions();this.F.onreadystatechange=Ya(this.Bd,this);try{this.getStatus(),this.Y=!0,this.F.open(b,String(a),!0),this.Y=!1}catch(g){this.getStatus();mh(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=r(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=y.FormData&&a instanceof y.FormData;!(0<=fb(jh,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=r(c);for(d=b.next();!d.done;d=b.next())c=r(d.value),d=c.next().value,c=c.next().value,this.F.setRequestHeader(d,c);this.ma&&(this.F.responseType=this.ma);"withCredentials"in this.F&&this.F.withCredentials!==this.ia&&(this.F.withCredentials=this.ia);try{nh(this),0<this.s&&(this.ha=oh(this.F),this.getStatus(),this.ha?(this.F.timeout=this.s,this.F.ontimeout=Ya(this.Pd,
this)):this.H=jg(this.Pd,this.s,this)),this.getStatus(),this.v=!0,this.F.send(a),this.v=!1}catch(g){this.getStatus(),mh(this,g)}};
function oh(a){return Yc&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
k.Pd=function(){"undefined"!=typeof Oa&&this.F&&(this.m="Timed out after "+this.s+"ms, aborting",this.getStatus(),wf(this,"timeout"),this.abort(8))};
function mh(a,b){a.i=!1;a.F&&(a.j=!0,a.F.abort(),a.j=!1);a.m=b;ph(a);qh(a)}
function ph(a){a.V||(a.V=!0,wf(a,"complete"),wf(a,"error"))}
k.abort=function(){this.F&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.F.abort(),this.j=!1,wf(this,"complete"),wf(this,"abort"),qh(this))};
k.L=function(){this.F&&(this.i&&(this.i=!1,this.j=!0,this.F.abort(),this.j=!1),qh(this,!0));hh.va.L.call(this)};
k.Bd=function(){this.h()||(this.Y||this.v||this.j?rh(this):this.Ke())};
k.Ke=function(){rh(this)};
function rh(a){if(a.i&&"undefined"!=typeof Oa)if(a.M[1]&&4==sh(a)&&2==a.getStatus())a.getStatus();else if(a.v&&4==sh(a))jg(a.Bd,0,a);else if(wf(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(th(a))wf(a,"complete"),wf(a,"success");else{try{var b=2<sh(a)?a.F.statusText:""}catch(c){b=""}a.m=b+" ["+a.getStatus()+"]";ph(a)}}finally{qh(a)}}}
function qh(a,b){if(a.F){nh(a);var c=a.F,d=a.M[0]?function(){}:null;
a.F=null;a.M=null;b||wf(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function nh(a){a.F&&a.ha&&(a.F.ontimeout=null);a.H&&(y.clearTimeout(a.H),a.H=null)}
k.isActive=function(){return!!this.F};
k.isComplete=function(){return 4==sh(this)};
function th(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=wc(1,String(a.aa)),!a&&y.self&&y.self.location&&(a=y.self.location.protocol.slice(0,-1)),b=!ih.test(a?a.toLowerCase():"");c=b}return c}
function sh(a){return a.F?a.F.readyState:0}
k.getStatus=function(){try{return 2<sh(this)?this.F.status:-1}catch(a){return-1}};
k.getLastError=function(){return"string"===typeof this.m?this.m:String(this.m)};function uh(a){I.call(this,a)}
v(uh,I);function vh(a){I.call(this,a,-1,wh)}
v(vh,I);var wh=[1];function ee(a){I.call(this,a)}
v(ee,I);var xh=["platform","platformVersion","architecture","model","uaFullVersion"];new vh;function qe(a){I.call(this,a)}
v(qe,I);function yh(a){I.call(this,a,33,zh)}
v(yh,I);var zh=[3,20,27];function Ah(a){I.call(this,a,17,Bh)}
v(Ah,I);var Bh=[3,5];function Ch(a){I.call(this,a,6,Dh)}
v(Ch,I);var Dh=[5];function Eh(a){I.call(this,a)}
v(Eh,I);var Jh;Jh=new function(a,b,c){this.h=a;this.fieldName=b;this.j=c;this.isRepeated=0;this.i=ie;this.defaultValue=void 0}(175237375,{zg:0},Eh);function Kh(a,b,c,d,e,f,g,h,l,m,n){vf.call(this);var q=this;this.Y="";this.j=[];this.Yc="";this.Zc=this.qb=-1;this.Xb=!1;this.T=this.m=null;this.H=this.M=0;this.Zd=1;this.timeoutMillis=0;this.eb=!1;vf.call(this);this.Xc=b||function(){};
this.s=new Lh(a,f);this.Xd=d;this.Wb=n;this.ae=Za(Af,0,1);this.ha=e||null;this.V=c||null;this.ia=g||!1;this.pageId=l||null;this.logger=null;this.withCredentials=!h;this.Vb=f||!1;!this.Vb&&(65<=kc("Chromium")||45<=kc("Firefox")||12<=kc("Safari")||(Oc()||D("iPad")||D("iPod"))&&Vc());a=pe();Mh(this.s,a);this.v=new Wg(1E4);this.i=new hg(this.v.getValue());Me(this,this.i);m=Nh(this,m);ff(this.i,"tick",m,!1,this);this.aa=new hg(6E5);Me(this,this.aa);ff(this.aa,"tick",m,!1,this);this.ia||this.aa.start();
this.Vb||(ff(document,"visibilitychange",function(){"hidden"===document.visibilityState&&q.ma()}),ff(document,"pagehide",this.ma,!1,this))}
v(Kh,vf);function Nh(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
Kh.prototype.L=function(){this.ma();vf.prototype.L.call(this)};
function Oh(a){a.ha||(a.ha=.01>a.ae()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.ha}
function Ph(a,b){a.v=new Wg(1>b?1:b);ig(a.i,a.v.getValue())}
Kh.prototype.log=function(a){a=a.clone();var b=this.Zd++;G(a,21,b);this.Y&&G(a,26,this.Y);if(!ae(a,1)){b=a;var c=Date.now().toString();G(b,1,c)}null==ae(a,15)&&G(a,15,60*(new Date).getTimezoneOffset());this.m&&(b=this.m.clone(),H(a,Ug,16,b));for(;1E3<=this.j.length;)this.j.shift(),++this.M;this.j.push(a);wf(this,new Qh(a));this.ia||this.i.enabled||this.i.start()};
Kh.prototype.flush=function(a,b){var c=this;if(0===this.j.length)a&&a();else if(this.eb)Rh(this.s,3),Sh(this);else{var d=Date.now();if(this.Zc>d&&this.qb<d)b&&b("throttled");else{Rh(this.s,1);var e=Th(this.s,this.j,this.M,this.H);d={};var f=this.Xc();f&&(d.Authorization=f);var g=Oh(this);this.V&&(d["X-Goog-AuthUser"]=this.V,g=Fc(g,"authuser",this.V));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=Fc(g,"pageId",this.pageId));if(f&&this.Yc===f)b&&b("stale-auth-token");else{this.j=[];this.i.enabled&&
this.i.stop();this.M=0;var h=Ee(e),l;this.T&&this.T.isSupported(h.length)&&(l=this.T.compress(h));var m={url:g,body:h,ee:1,Oc:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},n=function(t){c.v.reset();ig(c.i,c.v.getValue());if(t){var z=null;try{var C=JSON.parse(t.replace(")]}'\n",""));z=new Ch(C)}catch(E){}z&&(t=Number(re(ae(z,1),"-1")),0<t&&(c.qb=Date.now(),c.Zc=c.qb+t),z=Jh.j?Jh.i(z,Jh.j,Jh.h,!0):Jh.isRepeated?Jh.i(z,Jh.h,!0):Jh.i(z,Jh.h,Jh.defaultValue,
!0))&&(z=re(ae(z,1),-1),-1!=z&&(c.Xb||Ph(c,z)))}a&&a();c.H=0},q=function(t,z){var C=F(e.P),E=!!(C&2);
C=ke(e,yh,3,E?1:2,C);var M=fe(e,3,3,void 0,E);if(!(E||F(M)&8)){for(E=0;E<C.length;E++){var S=C[E],Q=je(S);S!==Q&&(C[E]=Q,M[E]=Q.P)}Gd(M,8)}M=c.v;M.h=Math.min(3E5,2*M.h);M.i=Math.min(3E5,M.h+Math.round(.2*(Math.random()-.5)*M.h));ig(c.i,c.v.getValue());401===t&&f&&(c.Yc=f);void 0===z&&(z=500<=t&&600>t||401===t||0===t);z&&(c.j=C.concat(c.j),c.ia||c.i.enabled||c.i.start());b&&b("net-send-failed",t);++c.H},u=function(){c.Wb?c.Wb.send(m,n,q):c.Xd(m,n,q)};
l?l.then(function(t){m.Oc["Content-Encoding"]="gzip";m.Oc["Content-Type"]="application/binary";m.body=t;m.ee=2;u()},function(){u()}):u()}}}};
Kh.prototype.ma=function(){Uh(this.s,!0);this.flush();Uh(this.s,!1)};
function Sh(a){Vh(a,function(b,c){b=Fc(b,"format","json");var d=!1;try{d=window.navigator.sendBeacon(b,Ee(c))}catch(e){}a.eb&&!d&&(a.eb=!1);return d})}
function Vh(a,b){if(0!==a.j.length){var c=Jc(Oh(a),"format");c=Dc(c,"auth",a.Xc(),"authuser",a.V||"0");for(var d=0;10>d&&a.j.length;++d){var e=a.j.slice(0,32),f=Th(a.s,e,a.M,a.H);if(!b(c,f)){++a.H;break}a.M=0;a.H=0;a.j=a.j.slice(e.length)}a.i.enabled&&a.i.stop()}}
function Qh(){Oe.call(this,"event-logged",void 0)}
v(Qh,Oe);function Lh(a,b){this.i=b=void 0===b?!1:b;this.uach=this.locale=null;this.h=new Ah;G(this.h,2,a);b||(this.locale=document.documentElement.getAttribute("lang"));Mh(this,new qe)}
function Mh(a,b){H(a.h,qe,1,b);ae(b,1)||G(b,1,1);a.i||(b=Wh(a),ae(b,5)||G(b,5,a.locale));a.uach&&(b=Wh(a),ie(b,vh,9)||H(b,vh,9,a.uach))}
function Rh(a,b){ce(ie(a.h,qe,1))&&(a=Xh(a),G(a,1,b))}
function Uh(a,b){ce(ie(a.h,qe,1))&&(a=Xh(a),G(a,2,b))}
function Yh(a,b){var c=void 0===c?xh:c;b(window,c).then(function(d){a.uach=d;d=Wh(a);H(d,vh,9,a.uach);return!0}).catch(function(){return!1})}
function Wh(a){a=ie(a.h,qe,1);var b=ie(a,ee,11);b||(b=new ee,H(a,ee,11,b));return b}
function Xh(a){a=Wh(a);var b=ie(a,uh,10);b||(b=new uh,G(b,2,!1),H(a,uh,10,b));return b}
function Th(a,b,c,d){c=void 0===c?0:c;d=void 0===d?0:d;if(ce(ie(a.h,qe,1))){var e=Xh(a);oe(e,3,d)}a=a.h.clone();d=Date.now().toString();a=G(a,4,d);b=me(a,yh,3,b);c&&G(b,14,c);return b}
;function Zh(a,b,c){lh(a.url,function(d){d=d.target;if(th(d)){try{var e=d.F?d.F.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Oc,a.timeoutMillis,a.withCredentials)}
;function $h(a,b){K.call(this);this.v=a;this.T=b;this.l="https://play.google.com/log?format=json&hasfast=true";this.m=!1;this.H=Zh;this.i=""}
$a($h,K);function ai(a,b,c,d,e,f){a=void 0===a?-1:a;b=void 0===b?"":b;c=void 0===c?"":c;d=void 0===d?!1:d;e=void 0===e?"":e;K.call(this);f?a=f:(a=new $h(a,"0"),a.i=b,Me(this,a),""!=c&&(a.l=c),d&&(a.m=!0),e&&(a.j=e),b=new Kh(a.v,a.ha?a.ha:Tg,a.T,a.H,a.l,a.m,!1,a.Oa,void 0,void 0,a.M?a.M:void 0),Me(a,b),a.Y&&Mh(b.s,a.Y),a.j&&(c=a.j,d=Wh(b.s),G(d,7,c)),a.s&&(b.T=a.s),a.i&&(b.Y=a.i),a.V&&((c=a.V)?(b.m||(b.m=new Ug),c=Ee(c),G(b.m,4,c)):b.m&&G(b.m,4,void 0,!1)),a.ia&&(d=a.ia,b.m||(b.m=new Ug),c=b.m,d=null==d?Td:
Hd(d,1),G(c,2,d)),a.aa&&(c=a.aa,b.Xb=!0,Ph(b,c)),a.ma&&Yh(b.s,a.ma),a=b);this.i=a}
v(ai,K);
ai.prototype.flush=function(a){var b=a||[];if(b.length){a=new Fg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e,g=new Dg;var h=G(g,1,f.i);var l=f;g=[];for(var m=0;m<l.h.length;m++)g.push(l.h[m].Kb);if(null==g)g=G(h,3,Td);else{l=F(g);if(!(l&4)){if(l&2||Object.isFrozen(g))g=Array.prototype.slice.call(g);for(m=0;m<g.length;m++)g[m]=g[m];Id(g,l|5)}g=G(h,3,g)}h=[];l=[];m=r(f.sb.keys());for(var n=m.next();!n.done;n=m.next())l.push(n.value.split(","));for(m=0;m<l.length;m++){n=l[m];var q=f.l;for(var u=f.yc(n)||
[],t=[],z=0;z<u.length;z++){var C=u[z];C=C&&C.gd;var E=new zg;switch(q){case 3:ge(E,1,Ag,Number(C));break;case 2:ge(E,2,Ag,Wd(Number(C)))}t.push(E)}q=t;for(u=0;u<q.length;u++){t=q[u];z=new Bg;t=H(z,zg,2,t);z=n;C=[];E=f;for(var M=[],S=0;S<E.h.length;S++)M.push(E.h[S].Lb);E=M;for(M=0;M<E.length;M++){var Q=E[M],W=z[M];S=new xg;switch(Q){case 3:ge(S,1,yg,String(W));break;case 2:Q=S;W=Number(W);Pa(W);ge(Q,2,yg,W);break;case 1:ge(S,3,yg,"true"==W)}C.push(S)}me(t,xg,1,C);h.push(t)}}me(g,Bg,4,h);c.push(g);
e.clear()}me(a,Dg,1,c);b=this.i;a instanceof yh?b.log(a):(c=new yh,a=Ee(a),a=G(c,8,a),b.log(a));this.i.flush()}};function bi(a){this.v=ci();this.m=new ai(1828);this.h=new kg(this.m);this.s=new qg(this.h);this.j=new rg(this.h);this.l=new sg(this.h);this.i=new og(this.h);this.Ea=ug(a)}
function ci(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function di(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function ei(a){function b(z,C){Promise.resolve().then(function(){var E;if(null!=(E=c.ja)){var M=ci()-E.v;E.s.h.vc("/client_streamz/bg/fil",M,E.Ea)}g.resolve({ce:z,ef:C})})}
var c=this;this.i=!1;var d=a.program;var e=a.ue;if(a.Oe){var f;this.ja=null!=(f=a.ja)?f:new bi(e)}var g=new di;this.j=g.promise;if(y[e])if(y[e].a){var h;null!=(h=this.ja)&&pg(h.i,h.Ea,3)}else{var l;null!=(l=this.ja)&&pg(l.i,l.Ea,2);var m;null!=(m=this.ja)&&m.h.pb()}else{var n;null!=(n=this.ja)&&pg(n.i,n.Ea,1);var q;null!=(q=this.ja)&&q.h.pb()}try{this.l=r((0,y[e].a)(d,b,!0)).next().value,this.df=g.promise.then(function(){})}catch(z){var u;
null!=(u=this.ja)&&pg(u.i,u.Ea,4);var t;null!=(t=this.ja)&&t.h.pb();throw z;}}
ei.prototype.snapshot=function(a){var b=this;if(this.i)throw Error("Already disposed");var c=ci(),d;null!=(d=this.ja)&&d.j.h.uc("/client_streamz/bg/fsc",d.Ea);return this.j.then(function(e){var f=e.ce;return new Promise(function(g){f(function(h){var l;if(null!=(l=b.ja)){var m=ci()-c;l.l.h.vc("/client_streamz/bg/fsl",m,l.Ea)}g(h)},[a.jd,
a.ff])})})};
ei.prototype.Md=function(a){if(this.i)throw Error("Already disposed");var b=ci(),c;null!=(c=this.ja)&&c.j.h.uc("/client_streamz/bg/fsc",c.Ea);a=this.l([a.jd,a.ff]);null!=(c=this.ja)&&(b=ci()-b,c.l.h.vc("/client_streamz/bg/fsl",b,c.Ea));return a};
ei.prototype.dispose=function(){var a;null!=(a=this.ja)&&a.h.pb();this.i=!0;this.j.then(function(b){(b=b.ef)&&b()})};
ei.prototype.h=function(){return this.i};var fi=window;Cb("csi.gstatic.com");Cb("googleads.g.doubleclick.net");Cb("partner.googleadservices.com");Cb("pubads.g.doubleclick.net");Cb("securepubads.g.doubleclick.net");Cb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var gi;try{new URL("s://g"),gi=!0}catch(a){gi=!1}var hi=gi;var ii={};function ji(){}
function ki(a){this.h=a}
v(ki,ji);ki.prototype.toString=function(){return this.h};function li(a){var b="true".toString(),c=[new ki(mi[0].toLowerCase(),ii)];if(0===c.length)throw Error("");if(c.map(function(d){if(d instanceof ki)d=d.h;else throw Error("");return d}).every(function(d){return 0!=="data-loaded".indexOf(d)}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function ni(a){var b,c,d=null==(c=(b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:c.call(b,"script[nonce]");(b=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",b)}
function oi(a,b){a.src=Hb(b);ni(a)}
;function pi(a){this.Ce=a}
function qi(a){return new pi(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var ri=[qi("data"),qi("http"),qi("https"),qi("mailto"),qi("ftp"),new pi(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function si(a){var b=ti;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function ui(){var a=[];si(function(b){a.push(b)});
return a}
var ti={pf:"allow-forms",qf:"allow-modals",rf:"allow-orientation-lock",sf:"allow-pointer-lock",tf:"allow-popups",uf:"allow-popups-to-escape-sandbox",vf:"allow-presentation",wf:"allow-same-origin",xf:"allow-scripts",yf:"allow-top-navigation",zf:"allow-top-navigation-by-user-activation"},vi=eb(function(){return ui()});
function wi(){var a=xi(),b={};gb(vi(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function xi(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function yi(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var zi=(new Date).getTime();var Ai="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");ja(Ai);"undefined"!==typeof TextDecoder&&new TextDecoder;var Bi="undefined"!==typeof TextEncoder?new TextEncoder:null,Ci=Bi?function(a){return Bi.encode(a)}:function(a){a=Lc(a);
for(var b=new Uint8Array(a.length),c=0;c<b.length;c++)b[c]=a[c];return b};function Di(a){vf.call(this);var b=this;this.v=this.j=0;this.ya=null!=a?a:{ea:function(e,f){return setTimeout(e,f)},
Ba:function(e){clearTimeout(e)}};
var c,d;this.i=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.m=function(){return x(function(e){return w(e,Ei(b),0)})};
window.addEventListener("offline",this.m);window.addEventListener("online",this.m);this.v||Fi(this)}
v(Di,vf);function Gi(){var a=Hi;Di.h||(Di.h=new Di(a));return Di.h}
Di.prototype.dispose=function(){window.removeEventListener("offline",this.m);window.removeEventListener("online",this.m);this.ya.Ba(this.v);delete Di.h};
Di.prototype.oa=function(){return this.i};
function Fi(a){a.v=a.ya.ea(function(){var b;return x(function(c){if(1==c.h)return a.i?(null==(b=window.navigator)?0:b.onLine)?c.A(3):w(c,Ei(a),3):w(c,Ei(a),3);Fi(a);c.h=0})},3E4)}
function Ei(a,b){return a.s?a.s:a.s=new Promise(function(c){var d,e,f,g;return x(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,ya(h,2,3),d&&(a.j=a.ya.ea(function(){d.abort()},b||2E4)),w(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:Ca(h);a.s=void 0;a.j&&(a.ya.Ba(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?wf(a,"networkstatus-online"):wf(a,"networkstatus-offline"));c(g);Ea(h);break;case 2:Ba(h),g=!1,h.A(3)}})})}
;function Ii(){this.data_=[];this.h=-1}
Ii.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data_[a]!==b&&(this.data_[a]=b,this.h=-1)};
Ii.prototype.get=function(a){return!!this.data_[a]};
function Ji(a){-1===a.h&&(a.h=jb(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function Ki(a,b){this.h=a[y.Symbol.iterator]();this.i=b}
Ki.prototype[Symbol.iterator]=function(){return this};
Ki.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value),done:a.done}};
function Li(a,b){return new Ki(a,b)}
;function Mi(){this.blockSize=-1}
;function Ni(){this.blockSize=-1;this.blockSize=64;this.h=[];this.m=[];this.s=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
$a(Ni,Mi);Ni.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function Oi(a,b,c){c||(c=0);var d=a.s;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],l=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var m=1518500249}else f=c^g^h,m=1859775393;else 60>e?(f=c&g|h&(c|g),m=2400959708):
(f=c^g^h,m=3395469782);f=(b<<5|b>>>27)+f+l+m+d[e]&4294967295;l=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+l&4294967295}
Ni.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.m,f=this.i;d<b;){if(0==f)for(;d<=c;)Oi(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Oi(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Oi(this,e);f=0;break}}this.i=f;this.l+=b}};
Ni.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.m[c]=b&255,b/=256;Oi(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function Pi(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Qi(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Ri(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Pi(a).match(/\S+/g)||[],b=0<=fb(a,b));return b}
function Si(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Ri(a,"inverted-hdpi")&&Qi(a,Array.prototype.filter.call(a.classList?a.classList:Pi(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function Ti(){}
Ti.prototype.next=function(){return Ui};
var Ui={done:!0,value:void 0};function Vi(a){return{value:a,done:!1}}
Ti.prototype.Aa=function(){return this};function Wi(a){if(a instanceof Xi||a instanceof Yi||a instanceof Zi)return a;if("function"==typeof a.next)return new Xi(function(){return a});
if("function"==typeof a[Symbol.iterator])return new Xi(function(){return a[Symbol.iterator]()});
if("function"==typeof a.Aa)return new Xi(function(){return a.Aa()});
throw Error("Not an iterator or iterable.");}
function Xi(a){this.i=a}
Xi.prototype.Aa=function(){return new Yi(this.i())};
Xi.prototype[Symbol.iterator]=function(){return new Zi(this.i())};
Xi.prototype.h=function(){return new Zi(this.i())};
function Yi(a){this.i=a}
v(Yi,Ti);Yi.prototype.next=function(){return this.i.next()};
Yi.prototype[Symbol.iterator]=function(){return new Zi(this.i)};
Yi.prototype.h=function(){return new Zi(this.i)};
function Zi(a){Xi.call(this,function(){return a});
this.j=a}
v(Zi,Xi);Zi.prototype.next=function(){return this.j.next()};function $i(a,b){this.i={};this.h=[];this.Va=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof $i)for(c=a.Bc(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
k=$i.prototype;k.Bc=function(){aj(this);return this.h.concat()};
k.has=function(a){return bj(this.i,a)};
k.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||cj;aj(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function cj(a,b){return a===b}
k.clear=function(){this.i={};this.Va=this.size=this.h.length=0};
k.remove=function(a){return this.delete(a)};
k.delete=function(a){return bj(this.i,a)?(delete this.i[a],--this.size,this.Va++,this.h.length>2*this.size&&aj(this),!0):!1};
function aj(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];bj(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],bj(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
k.get=function(a,b){return bj(this.i,a)?this.i[a]:b};
k.set=function(a,b){bj(this.i,a)||(this.size+=1,this.h.push(a),this.Va++);this.i[a]=b};
k.forEach=function(a,b){for(var c=this.Bc(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
k.clone=function(){return new $i(this)};
k.keys=function(){return Wi(this.Aa(!0)).h()};
k.values=function(){return Wi(this.Aa(!1)).h()};
k.entries=function(){var a=this;return Li(this.keys(),function(b){return[b,a.get(b)]})};
k.Aa=function(a){aj(this);var b=0,c=this.Va,d=this,e=new Ti;e.next=function(){if(c!=d.Va)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return Ui;var f=d.h[b++];return Vi(a?f:d.i[f])};
return e};
function bj(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function dj(a){K.call(this);this.s=1;this.l=[];this.m=0;this.i=[];this.j={};this.v=!!a}
$a(dj,K);k=dj.prototype;k.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.s;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.s=e+3;d.push(e);return e};
function ej(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.Fb(b)}}
k.Fb=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=function(){}):(c&&lb(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
k.cb=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.v)for(e=0;e<c.length;e++){var g=c[e];fj(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h();e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.Fb(c)}}return 0!=e}return!1};
function fj(a,b,c){Of(function(){a.apply(b,c)})}
k.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.Fb,this),delete this.j[a])}else this.i.length=0,this.j={}};
k.L=function(){dj.va.L.call(this);this.clear();this.l.length=0};function gj(a){this.h=a}
gj.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,Xg(b))};
gj.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
gj.prototype.remove=function(a){this.h.remove(a)};function hj(a){this.h=a}
$a(hj,gj);function ij(a){this.data=a}
function jj(a){return void 0===a||a instanceof ij?a:new ij(a)}
hj.prototype.set=function(a,b){hj.va.set.call(this,a,jj(b))};
hj.prototype.i=function(a){a=hj.va.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
hj.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function kj(a){this.h=a}
$a(kj,hj);kj.prototype.set=function(a,b,c){if(b=jj(b)){if(c){if(c<Date.now()){kj.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}kj.va.set.call(this,a,b)};
kj.prototype.i=function(a){var b=kj.va.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())kj.prototype.remove.call(this,a);else return b}};function lj(){}
;function mj(){}
$a(mj,lj);mj.prototype[Symbol.iterator]=function(){return Wi(this.Aa(!0)).h()};
mj.prototype.clear=function(){var a=Array.from(this);a=r(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function nj(a){this.h=a}
$a(nj,mj);k=nj.prototype;k.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
k.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
k.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
k.remove=function(a){this.h.removeItem(a)};
k.Aa=function(a){var b=0,c=this.h,d=new Ti;d.next=function(){if(b>=c.length)return Ui;var e=c.key(b++);if(a)return Vi(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Vi(e)};
return d};
k.clear=function(){this.h.clear()};
k.key=function(a){return this.h.key(a)};function oj(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
$a(oj,nj);function pj(a,b){this.i=a;this.h=null;var c;if(c=Yc)c=!(9<=Number(kd));if(c){qj||(qj=new $i);this.h=qj.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),qj.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
$a(pj,mj);var rj={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},qj=null;function sj(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return rj[b]})}
k=pj.prototype;k.isAvailable=function(){return!!this.h};
k.set=function(a,b){this.h.setAttribute(sj(a),b);tj(this)};
k.get=function(a){a=this.h.getAttribute(sj(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
k.remove=function(a){this.h.removeAttribute(sj(a));tj(this)};
k.Aa=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new Ti;d.next=function(){if(b>=c.length)return Ui;var e=c[b++];if(a)return Vi(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Vi(e)};
return d};
k.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);tj(this)};
function tj(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function uj(a,b){this.i=a;this.h=b+"::"}
$a(uj,mj);uj.prototype.set=function(a,b){this.i.set(this.h+a,b)};
uj.prototype.get=function(a){return this.i.get(this.h+a)};
uj.prototype.remove=function(a){this.i.remove(this.h+a)};
uj.prototype.Aa=function(a){var b=this.i[Symbol.iterator](),c=this,d=new Ti;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return Vi(a?e.slice(c.h.length):c.i.get(e))};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var L={},vj="undefined"!==typeof Uint8Array&&"undefined"!==typeof Uint16Array&&"undefined"!==typeof Int32Array;L.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if("object"!==typeof c)throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
L.Rc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var wj={rb:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
od:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},xj={rb:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
od:function(a){return[].concat.apply([],a)}};
L.cf=function(){vj?(L.bb=Uint8Array,L.Fa=Uint16Array,L.Vd=Int32Array,L.assign(L,wj)):(L.bb=Array,L.Fa=Array,L.Vd=Array,L.assign(L,xj))};
L.cf();var yj=!0;try{new Uint8Array(1)}catch(a){yj=!1}for(var zj=new L.bb(256),Aj=0;256>Aj;Aj++)zj[Aj]=252<=Aj?6:248<=Aj?5:240<=Aj?4:224<=Aj?3:192<=Aj?2:1;zj[254]=zj[254]=1;
function Bj(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if(55296===(f&64512)&&b+1<d){var g=a.charCodeAt(b+1);56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=128>f?1:2048>f?2:65536>f?3:4}var h=new L.bb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),55296===(f&64512)&&b+1<d&&(g=a.charCodeAt(b+1),56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)),128>f?h[c++]=f:(2048>f?h[c++]=192|f>>>6:(65536>f?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var Cj={};Cj=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;0!==c;){f=2E3<c?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var Dj={},Ej,Fj=[],Gj=0;256>Gj;Gj++){Ej=Gj;for(var Hj=0;8>Hj;Hj++)Ej=Ej&1?3988292384^Ej>>>1:Ej>>>1;Fj[Gj]=Ej}Dj=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^Fj[(a^b[d])&255];return a^-1};var Ij={};Ij={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function Jj(a){for(var b=a.length;0<=--b;)a[b]=0}
var Kj=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],Lj=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],Mj=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],Nj=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],Oj=Array(576);Jj(Oj);var Pj=Array(60);Jj(Pj);var Qj=Array(512);Jj(Qj);var Rj=Array(256);Jj(Rj);var Sj=Array(29);Jj(Sj);var Tj=Array(30);Jj(Tj);function Uj(a,b,c,d,e){this.Nd=a;this.pe=b;this.oe=c;this.ke=d;this.Ge=e;this.sd=a&&a.length}
var Vj,Wj,Xj;function Yj(a,b){this.md=a;this.yb=0;this.Ua=b}
function Zj(a,b){a.R[a.pending++]=b&255;a.R[a.pending++]=b>>>8&255}
function ak(a,b,c){a.Z>16-c?(a.ga|=b<<a.Z&65535,Zj(a,a.ga),a.ga=b>>16-a.Z,a.Z+=c-16):(a.ga|=b<<a.Z&65535,a.Z+=c)}
function bk(a,b,c){ak(a,c[2*b],c[2*b+1])}
function ck(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(0<--b);return c>>>1}
function dk(a,b,c){var d=Array(16),e=0,f;for(f=1;15>=f;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[2*c+1],0!==e&&(a[2*c]=ck(d[e]++,e))}
function ek(a){var b;for(b=0;286>b;b++)a.ka[2*b]=0;for(b=0;30>b;b++)a.gb[2*b]=0;for(b=0;19>b;b++)a.ba[2*b]=0;a.ka[512]=1;a.Ma=a.Bb=0;a.sa=a.matches=0}
function fk(a){8<a.Z?Zj(a,a.ga):0<a.Z&&(a.R[a.pending++]=a.ga);a.ga=0;a.Z=0}
function gk(a,b,c){fk(a);Zj(a,c);Zj(a,~c);L.rb(a.R,a.window,b,c,a.pending);a.pending+=c}
function hk(a,b,c,d){var e=2*b,f=2*c;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function ik(a,b,c){for(var d=a.S[c],e=c<<1;e<=a.Ja;){e<a.Ja&&hk(b,a.S[e+1],a.S[e],a.depth)&&e++;if(hk(b,d,a.S[e],a.depth))break;a.S[c]=a.S[e];c=e;e<<=1}a.S[c]=d}
function jk(a,b,c){var d=0;if(0!==a.sa){do{var e=a.R[a.Hb+2*d]<<8|a.R[a.Hb+2*d+1];var f=a.R[a.Gc+d];d++;if(0===e)bk(a,f,b);else{var g=Rj[f];bk(a,g+256+1,b);var h=Kj[g];0!==h&&(f-=Sj[g],ak(a,f,h));e--;g=256>e?Qj[e]:Qj[256+(e>>>7)];bk(a,g,c);h=Lj[g];0!==h&&(e-=Tj[g],ak(a,e,h))}}while(d<a.sa)}bk(a,256,b)}
function kk(a,b){var c=b.md,d=b.Ua.Nd,e=b.Ua.sd,f=b.Ua.ke,g,h=-1;a.Ja=0;a.vb=573;for(g=0;g<f;g++)0!==c[2*g]?(a.S[++a.Ja]=h=g,a.depth[g]=0):c[2*g+1]=0;for(;2>a.Ja;){var l=a.S[++a.Ja]=2>h?++h:0;c[2*l]=1;a.depth[l]=0;a.Ma--;e&&(a.Bb-=d[2*l+1])}b.yb=h;for(g=a.Ja>>1;1<=g;g--)ik(a,c,g);l=f;do g=a.S[1],a.S[1]=a.S[a.Ja--],ik(a,c,1),d=a.S[1],a.S[--a.vb]=g,a.S[--a.vb]=d,c[2*l]=c[2*g]+c[2*d],a.depth[l]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[2*g+1]=c[2*d+1]=l,a.S[1]=l++,ik(a,c,1);while(2<=a.Ja);a.S[--a.vb]=
a.S[1];g=b.md;l=b.yb;d=b.Ua.Nd;e=b.Ua.sd;f=b.Ua.pe;var m=b.Ua.oe,n=b.Ua.Ge,q,u=0;for(q=0;15>=q;q++)a.Ga[q]=0;g[2*a.S[a.vb]+1]=0;for(b=a.vb+1;573>b;b++){var t=a.S[b];q=g[2*g[2*t+1]+1]+1;q>n&&(q=n,u++);g[2*t+1]=q;if(!(t>l)){a.Ga[q]++;var z=0;t>=m&&(z=f[t-m]);var C=g[2*t];a.Ma+=C*(q+z);e&&(a.Bb+=C*(d[2*t+1]+z))}}if(0!==u){do{for(q=n-1;0===a.Ga[q];)q--;a.Ga[q]--;a.Ga[q+1]+=2;a.Ga[n]--;u-=2}while(0<u);for(q=n;0!==q;q--)for(t=a.Ga[q];0!==t;)d=a.S[--b],d>l||(g[2*d+1]!==q&&(a.Ma+=(q-g[2*d+1])*g[2*d],g[2*
d+1]=q),t--)}dk(c,h,a.Ga)}
function lk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,l=4;0===f&&(h=138,l=3);b[2*(c+1)+1]=65535;for(d=0;d<=c;d++){var m=f;f=b[2*(d+1)+1];++g<h&&m===f||(g<l?a.ba[2*m]+=g:0!==m?(m!==e&&a.ba[2*m]++,a.ba[32]++):10>=g?a.ba[34]++:a.ba[36]++,g=0,e=m,0===f?(h=138,l=3):m===f?(h=6,l=3):(h=7,l=4))}}
function mk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,l=4;0===f&&(h=138,l=3);for(d=0;d<=c;d++){var m=f;f=b[2*(d+1)+1];if(!(++g<h&&m===f)){if(g<l){do bk(a,m,a.ba);while(0!==--g)}else 0!==m?(m!==e&&(bk(a,m,a.ba),g--),bk(a,16,a.ba),ak(a,g-3,2)):10>=g?(bk(a,17,a.ba),ak(a,g-3,3)):(bk(a,18,a.ba),ak(a,g-11,7));g=0;e=m;0===f?(h=138,l=3):m===f?(h=6,l=3):(h=7,l=4)}}}
function nk(a){var b=4093624447,c;for(c=0;31>=c;c++,b>>>=1)if(b&1&&0!==a.ka[2*c])return 0;if(0!==a.ka[18]||0!==a.ka[20]||0!==a.ka[26])return 1;for(c=32;256>c;c++)if(0!==a.ka[2*c])return 1;return 0}
var ok=!1;function pk(a,b,c){a.R[a.Hb+2*a.sa]=b>>>8&255;a.R[a.Hb+2*a.sa+1]=b&255;a.R[a.Gc+a.sa]=c&255;a.sa++;0===b?a.ka[2*c]++:(a.matches++,b--,a.ka[2*(Rj[c]+256+1)]++,a.gb[2*(256>b?Qj[b]:Qj[256+(b>>>7)])]++);return a.sa===a.Mb-1}
;function qk(a,b){a.msg=Ij[b];return b}
function rk(a){for(var b=a.length;0<=--b;)a[b]=0}
function sk(a){var b=a.state,c=b.pending;c>a.I&&(c=a.I);0!==c&&(L.rb(a.Nb,b.R,b.Ob,c,a.zb),a.zb+=c,b.Ob+=c,a.Sc+=c,a.I-=c,b.pending-=c,0===b.pending&&(b.Ob=0))}
function tk(a,b){var c=0<=a.na?a.na:-1,d=a.o-a.na,e=0;if(0<a.level){2===a.D.wc&&(a.D.wc=nk(a));kk(a,a.jc);kk(a,a.ec);lk(a,a.ka,a.jc.yb);lk(a,a.gb,a.ec.yb);kk(a,a.dd);for(e=18;3<=e&&0===a.ba[2*Nj[e]+1];e--);a.Ma+=3*(e+1)+14;var f=a.Ma+3+7>>>3;var g=a.Bb+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&-1!==c)ak(a,b?1:0,3),gk(a,c,d);else if(4===a.strategy||g===f)ak(a,2+(b?1:0),3),jk(a,Oj,Pj);else{ak(a,4+(b?1:0),3);c=a.jc.yb+1;d=a.ec.yb+1;e+=1;ak(a,c-257,5);ak(a,d-1,5);ak(a,e-4,4);for(f=0;f<e;f++)ak(a,a.ba[2*
Nj[f]+1],3);mk(a,a.ka,c-1);mk(a,a.gb,d-1);jk(a,a.ka,a.gb)}ek(a);b&&fk(a);a.na=a.o;sk(a.D)}
function N(a,b){a.R[a.pending++]=b}
function uk(a,b){a.R[a.pending++]=b>>>8&255;a.R[a.pending++]=b&255}
function vk(a,b){var c=a.yd,d=a.o,e=a.qa,f=a.Ad,g=a.o>a.da-262?a.o-(a.da-262):0,h=a.window,l=a.Wa,m=a.Da,n=a.o+258,q=h[d+e-1],u=h[d+e];a.qa>=a.rd&&(c>>=2);f>a.u&&(f=a.u);do{var t=b;if(h[t+e]===u&&h[t+e-1]===q&&h[t]===h[d]&&h[++t]===h[d+1]){d+=2;for(t++;h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&d<n;);t=258-(n-d);d=n-258;if(t>e){a.xb=b;e=t;if(t>=f)break;q=h[d+e-1];u=h[d+e]}}}while((b=m[b&l])>g&&0!==--c);return e<=
a.u?e:a.u}
function wk(a){var b=a.da,c;do{var d=a.Td-a.u-a.o;if(a.o>=b+(b-262)){L.rb(a.window,a.window,b,b,0);a.xb-=b;a.o-=b;a.na-=b;var e=c=a.ic;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Da[--e],a.Da[e]=f>=b?f-b:0;while(--c);d+=b}if(0===a.D.fa)break;e=a.D;c=a.window;f=a.o+a.u;var g=e.fa;g>d&&(g=d);0===g?c=0:(e.fa-=g,L.rb(c,e.input,e.jb,g,f),1===e.state.wrap?e.C=Cj(e.C,c,g,f):2===e.state.wrap&&(e.C=Dj(e.C,c,g,f)),e.jb+=g,e.mb+=g,c=g);a.u+=c;if(3<=a.u+a.la)for(d=a.o-a.la,a.G=a.window[d],
a.G=(a.G<<a.Ia^a.window[d+1])&a.Ha;a.la&&!(a.G=(a.G<<a.Ia^a.window[d+3-1])&a.Ha,a.Da[d&a.Wa]=a.head[a.G],a.head[a.G]=d,d++,a.la--,3>a.u+a.la););}while(262>a.u&&0!==a.D.fa)}
function xk(a,b){for(var c;;){if(262>a.u){wk(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.G=(a.G<<a.Ia^a.window[a.o+3-1])&a.Ha,c=a.Da[a.o&a.Wa]=a.head[a.G],a.head[a.G]=a.o);0!==c&&a.o-c<=a.da-262&&(a.J=vk(a,c));if(3<=a.J)if(c=pk(a,a.o-a.xb,a.J-3),a.u-=a.J,a.J<=a.Hc&&3<=a.u){a.J--;do a.o++,a.G=(a.G<<a.Ia^a.window[a.o+3-1])&a.Ha,a.Da[a.o&a.Wa]=a.head[a.G],a.head[a.G]=a.o;while(0!==--a.J);a.o++}else a.o+=a.J,a.J=0,a.G=a.window[a.o],a.G=(a.G<<a.Ia^a.window[a.o+1])&a.Ha;else c=pk(a,0,
a.window[a.o]),a.u--,a.o++;if(c&&(tk(a,!1),0===a.D.I))return 1}a.la=2>a.o?a.o:2;return 4===b?(tk(a,!0),0===a.D.I?3:4):a.sa&&(tk(a,!1),0===a.D.I)?1:2}
function yk(a,b){for(var c,d;;){if(262>a.u){wk(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.G=(a.G<<a.Ia^a.window[a.o+3-1])&a.Ha,c=a.Da[a.o&a.Wa]=a.head[a.G],a.head[a.G]=a.o);a.qa=a.J;a.Dd=a.xb;a.J=2;0!==c&&a.qa<a.Hc&&a.o-c<=a.da-262&&(a.J=vk(a,c),5>=a.J&&(1===a.strategy||3===a.J&&4096<a.o-a.xb)&&(a.J=2));if(3<=a.qa&&a.J<=a.qa){d=a.o+a.u-3;c=pk(a,a.o-1-a.Dd,a.qa-3);a.u-=a.qa-1;a.qa-=2;do++a.o<=d&&(a.G=(a.G<<a.Ia^a.window[a.o+3-1])&a.Ha,a.Da[a.o&a.Wa]=a.head[a.G],a.head[a.G]=a.o);
while(0!==--a.qa);a.hb=0;a.J=2;a.o++;if(c&&(tk(a,!1),0===a.D.I))return 1}else if(a.hb){if((c=pk(a,0,a.window[a.o-1]))&&tk(a,!1),a.o++,a.u--,0===a.D.I)return 1}else a.hb=1,a.o++,a.u--}a.hb&&(pk(a,0,a.window[a.o-1]),a.hb=0);a.la=2>a.o?a.o:2;return 4===b?(tk(a,!0),0===a.D.I?3:4):a.sa&&(tk(a,!1),0===a.D.I)?1:2}
function zk(a,b){for(var c,d,e,f=a.window;;){if(258>=a.u){wk(a);if(258>=a.u&&0===b)return 1;if(0===a.u)break}a.J=0;if(3<=a.u&&0<a.o&&(d=a.o-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.o+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.J=258-(e-d);a.J>a.u&&(a.J=a.u)}3<=a.J?(c=pk(a,1,a.J-3),a.u-=a.J,a.o+=a.J,a.J=0):(c=pk(a,0,a.window[a.o]),a.u--,a.o++);if(c&&(tk(a,!1),0===a.D.I))return 1}a.la=0;return 4===b?(tk(a,!0),0===a.D.I?3:4):
a.sa&&(tk(a,!1),0===a.D.I)?1:2}
function Ak(a,b){for(var c;;){if(0===a.u&&(wk(a),0===a.u)){if(0===b)return 1;break}a.J=0;c=pk(a,0,a.window[a.o]);a.u--;a.o++;if(c&&(tk(a,!1),0===a.D.I))return 1}a.la=0;return 4===b?(tk(a,!0),0===a.D.I?3:4):a.sa&&(tk(a,!1),0===a.D.I)?1:2}
function Bk(a,b,c,d,e){this.we=a;this.Fe=b;this.Je=c;this.Ee=d;this.re=e}
var Ck;Ck=[new Bk(0,0,0,0,function(a,b){var c=65535;for(c>a.ta-5&&(c=a.ta-5);;){if(1>=a.u){wk(a);if(0===a.u&&0===b)return 1;if(0===a.u)break}a.o+=a.u;a.u=0;var d=a.na+c;if(0===a.o||a.o>=d)if(a.u=a.o-d,a.o=d,tk(a,!1),0===a.D.I)return 1;if(a.o-a.na>=a.da-262&&(tk(a,!1),0===a.D.I))return 1}a.la=0;if(4===b)return tk(a,!0),0===a.D.I?3:4;a.o>a.na&&tk(a,!1);return 1}),
new Bk(4,4,8,4,xk),new Bk(4,5,16,8,xk),new Bk(4,6,32,32,xk),new Bk(4,4,16,16,yk),new Bk(8,16,32,32,yk),new Bk(8,16,128,128,yk),new Bk(8,32,128,256,yk),new Bk(32,128,258,1024,yk),new Bk(32,258,258,4096,yk)];
function Dk(){this.D=null;this.status=0;this.R=null;this.wrap=this.pending=this.Ob=this.ta=0;this.B=null;this.wa=0;this.method=8;this.wb=-1;this.Wa=this.Uc=this.da=0;this.window=null;this.Td=0;this.head=this.Da=null;this.Ad=this.rd=this.strategy=this.level=this.Hc=this.yd=this.qa=this.u=this.xb=this.o=this.hb=this.Dd=this.J=this.na=this.Ia=this.Ha=this.Cc=this.ic=this.G=0;this.ka=new L.Fa(1146);this.gb=new L.Fa(122);this.ba=new L.Fa(78);rk(this.ka);rk(this.gb);rk(this.ba);this.dd=this.ec=this.jc=
null;this.Ga=new L.Fa(16);this.S=new L.Fa(573);rk(this.S);this.vb=this.Ja=0;this.depth=new L.Fa(573);rk(this.depth);this.Z=this.ga=this.la=this.matches=this.Bb=this.Ma=this.Hb=this.sa=this.Mb=this.Gc=0}
function Ek(a,b){if(!a||!a.state||5<b||0>b)return a?qk(a,-2):-2;var c=a.state;if(!a.Nb||!a.input&&0!==a.fa||666===c.status&&4!==b)return qk(a,0===a.I?-5:-2);c.D=a;var d=c.wb;c.wb=b;if(42===c.status)if(2===c.wrap)a.C=0,N(c,31),N(c,139),N(c,8),c.B?(N(c,(c.B.text?1:0)+(c.B.Ra?2:0)+(c.B.Qa?4:0)+(c.B.name?8:0)+(c.B.comment?16:0)),N(c,c.B.time&255),N(c,c.B.time>>8&255),N(c,c.B.time>>16&255),N(c,c.B.time>>24&255),N(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),N(c,c.B.os&255),c.B.Qa&&c.B.Qa.length&&(N(c,
c.B.Qa.length&255),N(c,c.B.Qa.length>>8&255)),c.B.Ra&&(a.C=Dj(a.C,c.R,c.pending,0)),c.wa=0,c.status=69):(N(c,0),N(c,0),N(c,0),N(c,0),N(c,0),N(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),N(c,3),c.status=113);else{var e=8+(c.Uc-8<<4)<<8;e|=(2<=c.strategy||2>c.level?0:6>c.level?1:6===c.level?2:3)<<6;0!==c.o&&(e|=32);c.status=113;uk(c,e+(31-e%31));0!==c.o&&(uk(c,a.C>>>16),uk(c,a.C&65535));a.C=1}if(69===c.status)if(c.B.Qa){for(e=c.pending;c.wa<(c.B.Qa.length&65535)&&(c.pending!==c.ta||(c.B.Ra&&c.pending>
e&&(a.C=Dj(a.C,c.R,c.pending-e,e)),sk(a),e=c.pending,c.pending!==c.ta));)N(c,c.B.Qa[c.wa]&255),c.wa++;c.B.Ra&&c.pending>e&&(a.C=Dj(a.C,c.R,c.pending-e,e));c.wa===c.B.Qa.length&&(c.wa=0,c.status=73)}else c.status=73;if(73===c.status)if(c.B.name){e=c.pending;do{if(c.pending===c.ta&&(c.B.Ra&&c.pending>e&&(a.C=Dj(a.C,c.R,c.pending-e,e)),sk(a),e=c.pending,c.pending===c.ta)){var f=1;break}f=c.wa<c.B.name.length?c.B.name.charCodeAt(c.wa++)&255:0;N(c,f)}while(0!==f);c.B.Ra&&c.pending>e&&(a.C=Dj(a.C,c.R,c.pending-
e,e));0===f&&(c.wa=0,c.status=91)}else c.status=91;if(91===c.status)if(c.B.comment){e=c.pending;do{if(c.pending===c.ta&&(c.B.Ra&&c.pending>e&&(a.C=Dj(a.C,c.R,c.pending-e,e)),sk(a),e=c.pending,c.pending===c.ta)){f=1;break}f=c.wa<c.B.comment.length?c.B.comment.charCodeAt(c.wa++)&255:0;N(c,f)}while(0!==f);c.B.Ra&&c.pending>e&&(a.C=Dj(a.C,c.R,c.pending-e,e));0===f&&(c.status=103)}else c.status=103;103===c.status&&(c.B.Ra?(c.pending+2>c.ta&&sk(a),c.pending+2<=c.ta&&(N(c,a.C&255),N(c,a.C>>8&255),a.C=0,
c.status=113)):c.status=113);if(0!==c.pending){if(sk(a),0===a.I)return c.wb=-1,0}else if(0===a.fa&&(b<<1)-(4<b?9:0)<=(d<<1)-(4<d?9:0)&&4!==b)return qk(a,-5);if(666===c.status&&0!==a.fa)return qk(a,-5);if(0!==a.fa||0!==c.u||0!==b&&666!==c.status){d=2===c.strategy?Ak(c,b):3===c.strategy?zk(c,b):Ck[c.level].re(c,b);if(3===d||4===d)c.status=666;if(1===d||3===d)return 0===a.I&&(c.wb=-1),0;if(2===d&&(1===b?(ak(c,2,3),bk(c,256,Oj),16===c.Z?(Zj(c,c.ga),c.ga=0,c.Z=0):8<=c.Z&&(c.R[c.pending++]=c.ga&255,c.ga>>=
8,c.Z-=8)):5!==b&&(ak(c,0,3),gk(c,0,0),3===b&&(rk(c.head),0===c.u&&(c.o=0,c.na=0,c.la=0))),sk(a),0===a.I))return c.wb=-1,0}if(4!==b)return 0;if(0>=c.wrap)return 1;2===c.wrap?(N(c,a.C&255),N(c,a.C>>8&255),N(c,a.C>>16&255),N(c,a.C>>24&255),N(c,a.mb&255),N(c,a.mb>>8&255),N(c,a.mb>>16&255),N(c,a.mb>>24&255)):(uk(c,a.C>>>16),uk(c,a.C&65535));sk(a);0<c.wrap&&(c.wrap=-c.wrap);return 0!==c.pending?0:1}
;var Fk={};Fk=function(){this.input=null;this.mb=this.fa=this.jb=0;this.Nb=null;this.Sc=this.I=this.zb=0;this.msg="";this.state=null;this.wc=2;this.C=0};var Gk=Object.prototype.toString;
function Hk(a){if(!(this instanceof Hk))return new Hk(a);a=this.options=L.assign({level:-1,method:8,chunkSize:16384,Xa:15,He:8,strategy:0,K:""},a||{});a.raw&&0<a.Xa?a.Xa=-a.Xa:a.xe&&0<a.Xa&&16>a.Xa&&(a.Xa+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.D=new Fk;this.D.I=0;var b=this.D;var c=a.level,d=a.method,e=a.Xa,f=a.He,g=a.strategy;if(b){var h=1;-1===c&&(c=6);0>e?(h=0,e=-e):15<e&&(h=2,e-=16);if(1>f||9<f||8!==d||8>e||15<e||0>c||9<c||0>g||4<g)b=qk(b,-2);else{8===e&&(e=9);var l=new Dk;
b.state=l;l.D=b;l.wrap=h;l.B=null;l.Uc=e;l.da=1<<l.Uc;l.Wa=l.da-1;l.Cc=f+7;l.ic=1<<l.Cc;l.Ha=l.ic-1;l.Ia=~~((l.Cc+3-1)/3);l.window=new L.bb(2*l.da);l.head=new L.Fa(l.ic);l.Da=new L.Fa(l.da);l.Mb=1<<f+6;l.ta=4*l.Mb;l.R=new L.bb(l.ta);l.Hb=1*l.Mb;l.Gc=3*l.Mb;l.level=c;l.strategy=g;l.method=d;if(b&&b.state){b.mb=b.Sc=0;b.wc=2;c=b.state;c.pending=0;c.Ob=0;0>c.wrap&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.C=2===c.wrap?0:1;c.wb=0;if(!ok){d=Array(16);for(f=g=0;28>f;f++)for(Sj[f]=g,e=0;e<1<<Kj[f];e++)Rj[g++]=
f;Rj[g-1]=f;for(f=g=0;16>f;f++)for(Tj[f]=g,e=0;e<1<<Lj[f];e++)Qj[g++]=f;for(g>>=7;30>f;f++)for(Tj[f]=g<<7,e=0;e<1<<Lj[f]-7;e++)Qj[256+g++]=f;for(e=0;15>=e;e++)d[e]=0;for(e=0;143>=e;)Oj[2*e+1]=8,e++,d[8]++;for(;255>=e;)Oj[2*e+1]=9,e++,d[9]++;for(;279>=e;)Oj[2*e+1]=7,e++,d[7]++;for(;287>=e;)Oj[2*e+1]=8,e++,d[8]++;dk(Oj,287,d);for(e=0;30>e;e++)Pj[2*e+1]=5,Pj[2*e]=ck(e,5);Vj=new Uj(Oj,Kj,257,286,15);Wj=new Uj(Pj,Lj,0,30,15);Xj=new Uj([],Mj,0,19,7);ok=!0}c.jc=new Yj(c.ka,Vj);c.ec=new Yj(c.gb,Wj);c.dd=
new Yj(c.ba,Xj);c.ga=0;c.Z=0;ek(c);c=0}else c=qk(b,-2);0===c&&(b=b.state,b.Td=2*b.da,rk(b.head),b.Hc=Ck[b.level].Fe,b.rd=Ck[b.level].we,b.Ad=Ck[b.level].Je,b.yd=Ck[b.level].Ee,b.o=0,b.na=0,b.u=0,b.la=0,b.J=b.qa=2,b.hb=0,b.G=0);b=c}}else b=-2;if(0!==b)throw Error(Ij[b]);a.header&&(b=this.D)&&b.state&&2===b.state.wrap&&(b.state.B=a.header);if(a.Ib){var m;"string"===typeof a.Ib?m=Bj(a.Ib):"[object ArrayBuffer]"===Gk.call(a.Ib)?m=new Uint8Array(a.Ib):m=a.Ib;a=this.D;f=m;g=f.length;if(a&&a.state)if(m=
a.state,b=m.wrap,2===b||1===b&&42!==m.status||m.u)b=-2;else{1===b&&(a.C=Cj(a.C,f,g,0));m.wrap=0;g>=m.da&&(0===b&&(rk(m.head),m.o=0,m.na=0,m.la=0),c=new L.bb(m.da),L.rb(c,f,g-m.da,m.da,0),f=c,g=m.da);c=a.fa;d=a.jb;e=a.input;a.fa=g;a.jb=0;a.input=f;for(wk(m);3<=m.u;){f=m.o;g=m.u-2;do m.G=(m.G<<m.Ia^m.window[f+3-1])&m.Ha,m.Da[f&m.Wa]=m.head[m.G],m.head[m.G]=f,f++;while(--g);m.o=f;m.u=2;wk(m)}m.o+=m.u;m.na=m.o;m.la=m.u;m.u=0;m.J=m.qa=2;m.hb=0;a.jb=d;a.input=e;a.fa=c;m.wrap=b;b=0}else b=-2;if(0!==b)throw Error(Ij[b]);
this.og=!0}}
Hk.prototype.push=function(a,b){var c=this.D,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:!0===b?4:0;"string"===typeof a?c.input=Bj(a):"[object ArrayBuffer]"===Gk.call(a)?c.input=new Uint8Array(a):c.input=a;c.jb=0;c.fa=c.input.length;do{0===c.I&&(c.Nb=new L.bb(d),c.zb=0,c.I=d);a=Ek(c,e);if(1!==a&&0!==a)return Ik(this,a),this.ended=!0,!1;if(0===c.I||0===c.fa&&(4===e||2===e))if("string"===this.options.K){var f=L.Rc(c.Nb,c.zb);b=f;f=f.length;if(65537>f&&(b.subarray&&yj||!b.subarray))b=
String.fromCharCode.apply(null,L.Rc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=L.Rc(c.Nb,c.zb),this.chunks.push(b)}while((0<c.fa||0===c.I)&&1!==a);if(4===e)return(c=this.D)&&c.state?(d=c.state.status,42!==d&&69!==d&&73!==d&&91!==d&&103!==d&&113!==d&&666!==d?a=qk(c,-2):(c.state=null,a=113===d?qk(c,-3):0)):a=-2,Ik(this,a),this.ended=!0,0===a;2===e&&(Ik(this,0),c.I=0);return!0};
function Ik(a,b){0===b&&(a.result="string"===a.options.K?a.chunks.join(""):L.od(a.chunks));a.chunks=[];a.err=b;a.msg=a.D.msg}
function Jk(a,b){b=b||{};b.xe=!0;b=new Hk(b);b.push(a,!0);if(b.err)throw b.msg||Ij[b.err];return b.result}
;function Kk(a){return Ib(null===a?"null":void 0===a?"undefined":a)}
;function Lk(a){this.name=a}
;var Mk=new Lk("rawColdConfigGroup");var Nk=new Lk("rawHotConfigGroup");function Ok(a){I.call(this,a)}
v(Ok,I);function Pk(a,b){return oe(a,1,b)}
;function Qk(a){I.call(this,a,-1,Rk)}
v(Qk,I);var Rk=[1];function Sk(a){I.call(this,a)}
v(Sk,I);function Tk(a){I.call(this,a)}
v(Tk,I);function Uk(a){I.call(this,a)}
v(Uk,I);function Vk(a){I.call(this,a,-1,Wk)}
v(Vk,I);var Wk=[2];function Xk(a){I.call(this,a,-1,Yk)}
v(Xk,I);Xk.prototype.getPlayerType=function(){return ae(this,36)};
Xk.prototype.setHomeGroupInfo=function(a){return H(this,Vk,81,a)};
Xk.prototype.clearLocationPlayabilityToken=function(){return G(this,89,void 0,!1)};
var Yk=[9,66,24,32,86,100,101];function Zk(a){I.call(this,a)}
v(Zk,I);Zk.prototype.getKey=function(){return se(this,1)};
Zk.prototype.getValue=function(){return se(this,2===he(this,$k)?2:-1)};
var $k=[2,3,4,5,6];function al(a){I.call(this,a,-1,bl)}
v(al,I);var bl=[15,26,28];function cl(a){I.call(this,a,-1,dl)}
v(cl,I);var dl=[5];function el(a){I.call(this,a)}
v(el,I);function fl(a){I.call(this,a,-1,gl)}
v(fl,I);fl.prototype.setSafetyMode=function(a){return G(this,5,a)};
var gl=[12];function hl(a){I.call(this,a,-1,il)}
v(hl,I);hl.prototype.l=function(a){return H(this,Xk,1,a)};
var il=[12];var jl=new Lk("continuationCommand");var kl=new Lk("webCommandMetadata");var ll=new Lk("signalServiceEndpoint");var ml={Hf:"EMBEDDED_PLAYER_MODE_UNKNOWN",Ef:"EMBEDDED_PLAYER_MODE_DEFAULT",Gf:"EMBEDDED_PLAYER_MODE_PFP",Ff:"EMBEDDED_PLAYER_MODE_PFL"};var nl=new Lk("feedbackEndpoint");var El={ng:"WEB_DISPLAY_MODE_UNKNOWN",jg:"WEB_DISPLAY_MODE_BROWSER",lg:"WEB_DISPLAY_MODE_MINIMAL_UI",mg:"WEB_DISPLAY_MODE_STANDALONE",kg:"WEB_DISPLAY_MODE_FULLSCREEN"};function Fl(a){I.call(this,a)}
v(Fl,I);Fl.prototype.getKey=function(){return se(this,1)};
Fl.prototype.getValue=function(){return se(this,2)};function Gl(a){I.call(this,a,-1,Hl)}
v(Gl,I);var Hl=[4,5];function Il(a){I.call(this,a)}
v(Il,I);function Jl(a){I.call(this,a)}
v(Jl,I);var Kl=[2,3,4];function Ll(a){I.call(this,a)}
v(Ll,I);Ll.prototype.getMessage=function(){return se(this,1)};function Ml(a){I.call(this,a)}
v(Ml,I);function Nl(a){I.call(this,a)}
v(Nl,I);function Ol(a){I.call(this,a,-1,Pl)}
v(Ol,I);var Pl=[10,17];function Ql(a){I.call(this,a)}
v(Ql,I);function Rl(a){I.call(this,a)}
v(Rl,I);function Sl(a){I.call(this,a)}
v(Sl,I);function Tl(a){I.call(this,a)}
v(Tl,I);function Ul(a){I.call(this,a)}
v(Ul,I);function Vl(a){I.call(this,a,-1,Wl)}
v(Vl,I);Vl.prototype.getVideoData=function(){return ie(this,Ul,15)};
var Wl=[4];function Xl(a){I.call(this,a)}
v(Xl,I);function Yl(a,b){H(a,Sl,1,b)}
;function Zl(a){I.call(this,a)}
v(Zl,I);function $l(a,b){return H(a,Sl,1,b)}
Zl.prototype.h=function(a){return G(this,2,a)};function am(a){I.call(this,a,-1,bm)}
v(am,I);am.prototype.h=function(a){return G(this,1,a)};
function cm(a,b){return H(a,Sl,2,b)}
var bm=[3];function dm(a){I.call(this,a)}
v(dm,I);dm.prototype.h=function(a){return G(this,1,a)};function em(a){I.call(this,a)}
v(em,I);em.prototype.h=function(a){return G(this,1,a)};function fm(a){I.call(this,a)}
v(fm,I);fm.prototype.h=function(a){return G(this,1,a)};function gm(a){I.call(this,a)}
v(gm,I);gm.prototype.h=function(a){return G(this,1,a)};function hm(a){I.call(this,a)}
v(hm,I);function im(a){I.call(this,a)}
v(im,I);function jm(a){var b=new im;return G(b,1,a)}
im.prototype.getId=function(){return se(this,2)};
function km(a,b){return G(a,2,b)}
;function lm(a){I.call(this,a)}
v(lm,I);function mm(a){I.call(this,a,-1,nm)}
v(mm,I);mm.prototype.getPlayerType=function(){return re(ae(this,7),0)};
mm.prototype.setVideoId=function(a){return G(this,19,a)};
function om(a,b){ne(a,68,im,b)}
var nm=[83,68];function pm(a){I.call(this,a)}
v(pm,I);function qm(a){I.call(this,a)}
v(qm,I);function rm(a){I.call(this,a)}
v(rm,I);function sm(a){I.call(this,a,470)}
v(sm,I);
var tm=[2,3,5,6,7,11,13,20,21,22,23,24,28,32,37,45,59,72,73,74,76,78,79,80,85,91,97,100,102,105,111,117,119,126,127,136,146,148,151,156,157,158,159,163,164,168,176,177,178,179,184,188,189,190,191,193,194,195,196,197,198,199,200,201,202,203,204,205,206,208,209,215,219,222,225,226,227,229,232,233,234,240,241,244,247,248,249,251,254,255,256,257,258,259,260,261,266,270,272,278,288,291,293,300,304,308,309,310,311,313,314,319,320,321,323,324,327,328,330,331,332,334,337,338,340,344,348,350,351,352,353,354,
355,356,357,358,361,363,364,368,369,370,373,374,375,378,380,381,383,388,389,402,403,410,411,412,413,414,415,416,417,418,423,424,425,426,427,429,430,431,439,441,444,448,458,469];var um={cg:0,If:1,Of:2,Pf:4,Vf:8,Qf:16,Rf:32,ag:64,Zf:128,Kf:256,Mf:512,Tf:1024,Lf:2048,Nf:4096,Jf:8192,Sf:16384,Wf:32768,Uf:65536,Xf:131072,Yf:262144};function vm(a){I.call(this,a)}
v(vm,I);function wm(a){I.call(this,a)}
v(wm,I);wm.prototype.setVideoId=function(a){return ge(this,1,xm,a)};
wm.prototype.getPlaylistId=function(){var a=2===he(this,xm)?2:-1;return ae(this,a)};
var xm=[1,2];function ym(a){I.call(this,a,-1,zm)}
v(ym,I);var zm=[3];var Am=new Lk("webPlayerShareEntityServiceEndpoint");var Bm=new Lk("playlistEditEndpoint");var Cm=new Lk("modifyChannelNotificationPreferenceEndpoint");var Dm=new Lk("unsubscribeEndpoint");var Em=new Lk("subscribeEndpoint");function Fm(){var a=Gm;B("yt.ads.biscotti.getId_")||A("yt.ads.biscotti.getId_",a)}
function Hm(a){A("yt.ads.biscotti.lastId_",a)}
;function Im(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var Jm=y.window,Km,Lm,Mm=(null==Jm?void 0:null==(Km=Jm.yt)?void 0:Km.config_)||(null==Jm?void 0:null==(Lm=Jm.ytcfg)?void 0:Lm.data_)||{};A("yt.config_",Mm);function Nm(){Im(Mm,arguments)}
function O(a,b){return a in Mm?Mm[a]:b}
function Om(){var a=Mm.EXPERIMENT_FLAGS;return a?a.web_disable_gel_stp_ecatcher_killswitch:void 0}
;var Pm=[];function Qm(a){Pm.forEach(function(b){return b(a)})}
function Rm(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Sm(b)}}:a}
function Sm(a,b,c,d,e){var f=B("yt.logging.errors.log");f?f(a,"ERROR",b,c,d,void 0,e):(f=O("ERRORS",[]),f.push([a,"ERROR",b,c,d,void 0,e]),Nm("ERRORS",f));Qm(a)}
function Tm(a,b,c,d,e){var f=B("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=O("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),Nm("ERRORS",f))}
;var Um=/^[\w.]*$/,Vm={q:!0,search_query:!0};function Wm(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Xm(f[0]||""),h=Xm(f[1]||"");g in c?Array.isArray(c[g])?mb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(q){var l=q,m=f[0],n=String(Wm);l.args=[{key:m,value:f[1],query:a,method:Ym==n?"unchanged":n}];Vm.hasOwnProperty(m)||Tm(l)}}return c}
var Ym=String(Wm);function Zm(a){var b=[];nb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];gb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function $m(a){"?"==a.charAt(0)&&(a=a.substr(1));return Wm(a,"&")}
function an(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),$m(1<a.length?a[1]:a[0])):{}}
function bn(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=$m(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return Ec(a,e)+d}
function cn(a){if(!b)var b=window.location.href;var c=wc(1,a),d=xc(a);c&&d?(a=a.match(uc),b=b.match(uc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?xc(b)==d&&(Number(wc(4,b))||null)==(Number(wc(4,a))||null):!0;return a}
function Xm(a){return a&&a.match(Um)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function dn(a){var b=en;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=zi;e.flash="0";a:{try{var f=b.h.top.location.href}catch(J){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?fi:g;try{var h=g.history.length}catch(J){h=0}e.u_his=h;var l;e.u_h=null==(l=fi.screen)?void 0:l.height;var m;e.u_w=null==(m=fi.screen)?void 0:m.width;var n;e.u_ah=null==(n=fi.screen)?void 0:n.availHeight;var q;e.u_aw=null==
(q=fi.screen)?void 0:q.availWidth;var u;e.u_cd=null==(u=fi.screen)?void 0:u.colorDepth}catch(J){}h=b.h;try{var t=h.screenX;var z=h.screenY}catch(J){}try{var C=h.outerWidth;var E=h.outerHeight}catch(J){}try{var M=h.innerWidth;var S=h.innerHeight}catch(J){}try{var Q=h.screenLeft;var W=h.screenTop}catch(J){}try{M=h.innerWidth,S=h.innerHeight}catch(J){}try{var fa=h.screen.availWidth;var ma=h.screen.availTop}catch(J){}t=[Q,W,t,z,fa,ma,C,E,M,S];try{var Ra=(b.h.top||window).document,Da="CSS1Compat"==Ra.compatMode?
Ra.documentElement:Ra.body;var za=(new Cf(Da.clientWidth,Da.clientHeight)).round()}catch(J){za=new Cf(-12245933,-12245933)}Ra=za;za={};var na=void 0===na?y:na;Da=new Ii;na.SVGElement&&na.document.createElementNS&&Da.set(0);z=wi();z["allow-top-navigation-by-user-activation"]&&Da.set(1);z["allow-popups-to-escape-sandbox"]&&Da.set(2);na.crypto&&na.crypto.subtle&&Da.set(3);na.TextDecoder&&na.TextEncoder&&Da.set(4);na=Ji(Da);za.bc=na;za.bih=Ra.height;za.biw=Ra.width;za.brdim=t.join();b=b.i;b=(za.vis=b.prerendering?
3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,za.wgl=!!fi.WebGLRenderingContext,za);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var en=new function(){var a=window.document;this.h=window;this.i=a};
A("yt.ads_.signals_.getAdSignalsString",function(a){return Zm(dn(a))});Date.now();function P(a){a=fn(a);return"string"===typeof a&&"false"===a?!1:!!a}
function gn(a,b){a=fn(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function hn(){return O("EXPERIMENTS_TOKEN","")}
function fn(a){var b=O("EXPERIMENTS_FORCED_FLAGS",{})||{};return void 0!==b[a]?b[a]:O("EXPERIMENT_FLAGS",{})[a]}
function jn(){for(var a=[],b=O("EXPERIMENTS_FORCED_FLAGS",{}),c=r(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=O("EXPERIMENT_FLAGS",{});var e=r(Object.keys(c));for(d=e.next();!d.done;d=e.next())d=d.value,d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var kn="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function ln(){if(!kn)return null;var a=kn();return"open"in a?a:null}
function mn(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function nn(a,b){"function"===typeof a&&(a=Rm(a));return window.setTimeout(a,b)}
;var on={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},pn="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ja(Ai)),qn=!1;
function rn(a,b){b=void 0===b?{}:b;var c=cn(a),d=P("web_ajax_ignore_global_headers_if_set"),e;for(e in on){var f=O(on[e]);"X-Goog-Visitor-Id"!==e||f||(f=O("VISITOR_DATA"));!f||!c&&xc(a)||d&&void 0!==b[e]||!(P("move_vss_away_from_login_info_cookie")||"X-Goog-AuthUser"!==e&&"X-Goog-PageId"!==e)||(b[e]=f)}P("move_vss_away_from_login_info_cookie")&&c&&O("SESSION_INDEX")&&(b["X-Yt-Auth-Test"]="test");"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!xc(a))b["X-YouTube-Utc-Offset"]=
String(-(new Date).getTimezoneOffset());if(c||!xc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&xc(a)||(b["X-YouTube-Ad-Signals"]=Zm(dn()));return b}
function sn(a){var b=window.location.search,c=xc(a);P("debug_handle_relative_url_for_query_forward_killswitch")||!c&&cn(a)&&(c=document.location.hostname);var d=vc(wc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=$m(b),f={};gb(pn,function(g){e[g]&&(f[g]=e[g])});
return bn(a,f||{},!1)}
function tn(a,b){var c=b.format||"JSON";a=un(a,b);var d=vn(a,b),e=!1,f=wn(a,function(l){if(!e){e=!0;h&&window.clearTimeout(h);var m=mn(l),n=null,q=400<=l.status&&500>l.status,u=500<=l.status&&600>l.status;if(m||q||u)n=xn(a,c,l,b.convertToSafeHtml);if(m)a:if(l&&204==l.status)m=!0;else{switch(c){case "XML":m=0==parseInt(n&&n.return_code,10);break a;case "RAW":m=!0;break a}m=!!n}n=n||{};q=b.context||y;m?b.onSuccess&&b.onSuccess.call(q,l,n):b.onError&&b.onError.call(q,l,n);b.onFinish&&b.onFinish.call(q,
l,n)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=nn(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||y,f))},d)}return f}
function un(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=O("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=bn(a,b||{},!0);return a}
function vn(a,b){var c=O("XSRF_FIELD_NAME"),d=O("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=O("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||xc(a)&&!b.withCredentials&&xc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(P("ajax_parse_query_data_only_when_filled")&&f&&0<Object.keys(f).length||f)&&"string"===typeof e&&(e=$m(e),xb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?
JSON.stringify(e):Cc(e));f=e||f&&!qb(f);!qn&&f&&"POST"!=b.method&&(qn=!0,Sm(Error("AJAX request with postData should use POST")));return e}
function xn(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Tm(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?yn(a):null)e={},gb(a.getElementsByTagName("*"),function(g){e[g.tagName]=zn(g)})}d&&An(e);
return e}
function An(a){if(Sa(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b],e=zb();d=e?e.createHTML(d):d;a[c]=new mc(d)}else An(a[b])}}
function yn(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function zn(a){var b="";gb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Bn(a,b){b.method="POST";b.postParams||(b.postParams={});return tn(a,b)}
function wn(a,b,c,d,e,f,g){function h(){4==(l&&"readyState"in l?l.readyState:0)&&b&&Rm(b)(l)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var l=ln();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",h,!1):l.onreadystatechange=h;P("debug_forward_web_query_parameters")&&(a=sn(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=rn(a,e))for(var m in e)l.setRequestHeader(m,e[m]),"content-type"==m.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");l.send(d);
return l}
;var Cn=ld||md;function Dn(a){var b=Wb();return b?0<=b.toLowerCase().indexOf(a):!1}
;var En=[{Ic:function(a){return"Cannot read property '"+a.key+"'"},
lc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Ic:function(a){return"Cannot call '"+a.key+"'"},
lc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Ic:function(a){return a.key+" is not defined"},
lc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Gn={Ta:[],Pa:[{callback:Fn,weight:500}]};function Fn(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Hn(){this.Pa=[];this.Ta=[]}
var In;function Jn(){if(!In){var a=In=new Hn;a.Ta.length=0;a.Pa.length=0;Gn.Ta&&a.Ta.push.apply(a.Ta,Gn.Ta);Gn.Pa&&a.Pa.push.apply(a.Pa,Gn.Pa)}return In}
;var Kn=new dj;function Ln(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Mn(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=Mn(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=Mn(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function Mn(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Nn(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=On(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=Ln(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?On(e+".ve",f,g,h):0;d+=g;d+=On(e,a[e],b,c);if(500<d)break}}else c[b]=Pn(a),d+=c[b].length;else c[b]=Pn(a),d+=c[b].length;return d}
function On(a,b,c,d){c+="."+a;a=Pn(b);d[c]=a;return c.length+a.length}
function Pn(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function Qn(){this.gf=!0}
function Rn(){Qn.h||(Qn.h=new Qn);return Qn.h}
function Sn(a,b){a={};var c=Tg([]);c&&(a.Authorization=c,c=b=null==b?void 0:b.sessionIndex,void 0===c&&(c=Number(O("SESSION_INDEX",0)),c=isNaN(c)?0:c),P("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in Mm||(a["X-Origin"]=window.location.origin),void 0===b&&"DELEGATED_SESSION_ID"in Mm&&(a["X-Goog-PageId"]=O("DELEGATED_SESSION_ID")));return a}
;var Tn={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function Un(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function Vn(){if(!y.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return y.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":y.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":y.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":y.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function Wn(a,b,c,d,e){Pg.set(""+a,b,{kc:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function Xn(a,b,c){Pg.remove(""+a,void 0===b?"/":b,void 0===c?"youtube.com":c)}
function Yn(){if(!Pg.isEnabled())return!1;if(Pg.h.cookie)return!0;Pg.set("TESTCOOKIESENABLED","1",{kc:60});if("1"!==Pg.get("TESTCOOKIESENABLED"))return!1;Pg.remove("TESTCOOKIESENABLED");return!0}
;var Zn=B("ytglobal.prefsUserPrefsPrefs_")||{};A("ytglobal.prefsUserPrefsPrefs_",Zn);function $n(){this.h=O("ALT_PREF_COOKIE_NAME","PREF");this.i=O("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Pg.get(""+this.h,void 0);a&&this.parse(a)}
var ao;function bo(){ao||(ao=new $n);return ao}
k=$n.prototype;k.get=function(a,b){co(a);eo(a);a=void 0!==Zn[a]?Zn[a].toString():null;return null!=a?a:b?b:""};
k.set=function(a,b){co(a);eo(a);if(null==b)throw Error("ExpectedNotNull");Zn[a]=b.toString()};
function fo(a){return!!((go("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
k.remove=function(a){co(a);eo(a);delete Zn[a]};
k.clear=function(){for(var a in Zn)delete Zn[a]};
function eo(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function co(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function go(a){a=void 0!==Zn[a]?Zn[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
k.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Zn[d]=c.toString())}};var ho={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},io={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},jo={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},ko={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function lo(){var a=y.navigator;return a?a.connection:void 0}
function mo(){var a=lo();if(a){var b=ho[a.type||"unknown"]||"CONN_UNKNOWN";a=ho[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function no(){var a=lo();if(null!=a&&a.effectiveType)return ko.hasOwnProperty(a.effectiveType)?ko[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function R(a){var b=La.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ja(b))}
v(R,Error);function oo(){try{return po(),!0}catch(a){return!1}}
function po(a){if(void 0!==O("DATASYNC_ID"))return O("DATASYNC_ID");throw new R("Datasync ID not set",void 0===a?"unknown":a);}
;function qo(){}
function ro(a,b){return so(a,0,b)}
qo.prototype.ea=function(a,b){return so(a,1,b)};
function to(a){var b=B("yt.scheduler.instance.addImmediateJob");b?b(a):a()}
;function uo(){qo.apply(this,arguments)}
v(uo,qo);function vo(){uo.h||(uo.h=new uo);return uo.h}
function so(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):nn(a,c||0)}
uo.prototype.Ba=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=B("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
uo.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};
uo.prototype.pause=function(){var a=B("yt.scheduler.instance.pause");a&&a()};
var Hi=vo();function wo(a){var b=new oj;(b=b.isAvailable()?a?new uj(b,a):b:null)||(a=new pj(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new kj(a):null;this.i=document.domain||window.location.hostname}
wo.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(Xg(b))}catch(f){return}else e=escape(b);Wn(a,e,c,this.i)};
wo.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Pg.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
wo.prototype.remove=function(a){this.h&&this.h.remove(a);Xn(a,"/",this.i)};var xo=function(){var a;return function(){a||(a=new wo("ytidb"));return a}}();
function yo(){var a;return null==(a=xo())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var zo=[],Ao,Bo=!1;function Co(){var a={};for(Ao=new Do(void 0===a.handleError?Eo:a.handleError,void 0===a.logEvent?Fo:a.logEvent);0<zo.length;)switch(a=zo.shift(),a.type){case "ERROR":Ao.handleError(a.payload);break;case "EVENT":Ao.logEvent(a.eventType,a.payload)}}
function Go(a){Bo||(Ao?Ao.handleError(a):(zo.push({type:"ERROR",payload:a}),10<zo.length&&zo.shift()))}
function Ho(a,b){Bo||(Ao?Ao.logEvent(a,b):(zo.push({type:"EVENT",eventType:a,payload:b}),10<zo.length&&zo.shift()))}
;function Io(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function Jo(a){return a.substr(0,a.indexOf(":"))||a}
;var Ko={},Lo=(Ko.AUTH_INVALID="No user identifier specified.",Ko.EXPLICIT_ABORT="Transaction was explicitly aborted.",Ko.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Ko.MISSING_INDEX="Index not created.",Ko.MISSING_OBJECT_STORES="Object stores not created.",Ko.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",Ko.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",Ko.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
Ko.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",Ko.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Ko.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",Ko.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",Ko),Mo={},No=(Mo.AUTH_INVALID="ERROR",Mo.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Mo.EXPLICIT_ABORT="IGNORED",Mo.IDB_NOT_SUPPORTED="ERROR",Mo.MISSING_INDEX=
"WARNING",Mo.MISSING_OBJECT_STORES="ERROR",Mo.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",Mo.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",Mo.QUOTA_EXCEEDED="WARNING",Mo.QUOTA_MAYBE_EXCEEDED="WARNING",Mo.UNKNOWN_ABORT="WARNING",Mo.INCOMPATIBLE_DB_VERSION="WARNING",Mo),Oo={},Po=(Oo.AUTH_INVALID=!1,Oo.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Oo.EXPLICIT_ABORT=!1,Oo.IDB_NOT_SUPPORTED=!1,Oo.MISSING_INDEX=!1,Oo.MISSING_OBJECT_STORES=!1,Oo.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Oo.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Oo.QUOTA_EXCEEDED=!1,Oo.QUOTA_MAYBE_EXCEEDED=!0,Oo.UNKNOWN_ABORT=!0,Oo.INCOMPATIBLE_DB_VERSION=!1,Oo);function Qo(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?Lo[a]:c;d=void 0===d?No[a]:d;e=void 0===e?Po[a]:e;R.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Qo.prototype)}
v(Qo,R);function Ro(a,b){Qo.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},Lo.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Ro.prototype)}
v(Ro,Qo);function So(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,So.prototype)}
v(So,Error);var To=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Uo(a,b,c,d){b=Jo(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Qo)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new Qo("QUOTA_EXCEEDED",a);if(nd&&"UnknownError"===e.name)return new Qo("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof So)return new Qo("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&To.some(function(f){return e.message.includes(f)}))return new Qo("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new Qo("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",Cd:e.name})];e.level="WARNING";return e}
function Vo(a,b,c){var d=yo();return new Qo("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function Wo(a){if(!a)throw Error();throw a;}
function Xo(a){return a}
function Yo(a){this.h=a}
function Zo(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=r(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=r(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Zo.all=function(a){return new Zo(new Yo(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={nb:0};f.nb<a.length;f={nb:f.nb},++f.nb)Zo.resolve(a[f.nb]).then(function(g){return function(h){d[g.nb]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
Zo.resolve=function(a){return new Zo(new Yo(function(b,c){a instanceof Zo?a.then(b,c):b(a)}))};
Zo.reject=function(a){return new Zo(new Yo(function(b,c){c(a)}))};
Zo.prototype.then=function(a,b){var c=this,d=null!=a?a:Xo,e=null!=b?b:Wo;return new Zo(new Yo(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){$o(c,c,d,f,g)}),c.i.push(function(){ap(c,c,e,f,g)})):"FULFILLED"===c.state.status?$o(c,c,d,f,g):"REJECTED"===c.state.status&&ap(c,c,e,f,g)}))};
Zo.prototype.catch=function(a){return this.then(void 0,a)};
function $o(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Zo?bp(a,b,f,d,e):d(f)}catch(g){e(g)}}
function ap(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Zo?bp(a,b,f,d,e):d(f)}catch(g){e(g)}}
function bp(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Zo?bp(a,b,f,d,e):d(f)},function(f){e(f)})}
;function cp(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function dp(a){return new Promise(function(b,c){cp(a,b,c)})}
function ep(a){return new Zo(new Yo(function(b,c){cp(a,b,c)}))}
;function fp(a,b){return new Zo(new Yo(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var gp=window,T=gp.ytcsi&&gp.ytcsi.now?gp.ytcsi.now:gp.performance&&gp.performance.timing&&gp.performance.now&&gp.performance.timing.navigationStart?function(){return gp.performance.timing.navigationStart+gp.performance.now()}:function(){return(new Date).getTime()};function hp(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(T());this.i=!1}
k=hp.prototype;k.add=function(a,b,c){return ip(this,[a],{mode:"readwrite",ca:!0},function(d){return d.objectStore(a).add(b,c)})};
k.clear=function(a){return ip(this,[a],{mode:"readwrite",ca:!0},function(b){return b.objectStore(a).clear()})};
k.close=function(){this.h.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
k.count=function(a,b){return ip(this,[a],{mode:"readonly",ca:!0},function(c){return c.objectStore(a).count(b)})};
function jp(a,b,c){a=a.h.createObjectStore(b,c);return new kp(a)}
k.delete=function(a,b){return ip(this,[a],{mode:"readwrite",ca:!0},function(c){return c.objectStore(a).delete(b)})};
k.get=function(a,b){return ip(this,[a],{mode:"readonly",ca:!0},function(c){return c.objectStore(a).get(b)})};
function lp(a,b,c){return ip(a,[b],{mode:"readwrite",ca:!0},function(d){d=d.objectStore(b);return ep(d.h.put(c,void 0))})}
k.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function ip(a,b,c,d){var e,f,g,h,l,m,n,q,u,t,z,C;return x(function(E){switch(E.h){case 1:var M={mode:"readonly",ca:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?M.mode=c:Object.assign(M,c);e=M;a.transactionCount++;f=e.ca?3:1;g=0;case 2:if(h){E.A(3);break}g++;l=Math.round(T());ya(E,4);m=a.h.transaction(b,e.mode);M=new mp(m);M=np(M,d);return w(E,M,6);case 6:return n=E.i,q=Math.round(T()),op(a,l,q,g,void 0,b.join(),e),E.return(n);case 4:u=Ba(E);t=Math.round(T());z=Uo(u,a.h.name,b.join(),
a.h.version);if((C=z instanceof Qo&&!z.h)||g>=f)op(a,l,t,g,z,b.join(),e),h=z;E.A(2);break;case 3:return E.return(Promise.reject(h))}})}
function op(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Qo&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&Ho("QUOTA_EXCEEDED",{dbName:Jo(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Qo&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),Ho("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),pp(a,!1,d,f,b,g.tag),Go(e)):pp(a,!0,d,f,b,g.tag)}
function pp(a,b,c,d,e,f){Ho("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
k.getName=function(){return this.h.name};
function kp(a){this.h=a}
k=kp.prototype;k.add=function(a,b){return ep(this.h.add(a,b))};
k.autoIncrement=function(){return this.h.autoIncrement};
k.clear=function(){return ep(this.h.clear()).then(function(){})};
function qp(a,b,c){a.h.createIndex(b,c,{unique:!1})}
k.count=function(a){return ep(this.h.count(a))};
function rp(a,b){return sp(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
k.delete=function(a){return a instanceof IDBKeyRange?rp(this,a):ep(this.h.delete(a))};
k.get=function(a){return ep(this.h.get(a))};
k.index=function(a){try{return new tp(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new So(a,this.h.name);throw b;}};
k.getName=function(){return this.h.name};
k.keyPath=function(){return this.h.keyPath};
function sp(a,b,c){a=a.h.openCursor(b.query,b.direction);return up(a).then(function(d){return fp(d,c)})}
function mp(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=Qo;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var l=f.item(h);if(null===l)throw Error("Invariant: item in DOMStringList is null");g.push(l)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function np(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return r(d).next().value})}
mp.prototype.abort=function(){this.h.abort();this.i=!0;throw new Qo("EXPLICIT_ABORT");};
mp.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new kp(a),this.j.set(a,b));return b};
function tp(a){this.h=a}
k=tp.prototype;k.count=function(a){return ep(this.h.count(a))};
k.delete=function(a){return vp(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
k.get=function(a){return ep(this.h.get(a))};
k.getKey=function(a){return ep(this.h.getKey(a))};
k.keyPath=function(){return this.h.keyPath};
k.unique=function(){return this.h.unique};
function vp(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return up(a).then(function(d){return fp(d,c)})}
function wp(a,b){this.request=a;this.cursor=b}
function up(a){return ep(a).then(function(b){return b?new wp(a,b):null})}
k=wp.prototype;k.advance=function(a){this.cursor.advance(a);return up(this.request)};
k.continue=function(a){this.cursor.continue(a);return up(this.request)};
k.delete=function(){return ep(this.cursor.delete()).then(function(){})};
k.getKey=function(){return this.cursor.key};
k.getValue=function(){return this.cursor.value};
k.update=function(a){return ep(this.cursor.update(a))};function xp(a,b,c){return new Promise(function(d,e){function f(){u||(u=new hp(g.result,{closed:q}));return u}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.de,l=c.blocking,m=c.hf,n=c.upgrade,q=c.closed,u;g.addEventListener("upgradeneeded",function(t){try{if(null===t.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&"none"!==t.dataLoss&&Ho("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:Jo(a)});var z=f(),C=new mp(g.transaction);
n&&n(z,function(E){return t.oldVersion<E&&t.newVersion>=E},C);
C.done.catch(function(E){e(E)})}catch(E){e(E)}});
g.addEventListener("success",function(){var t=g.result;l&&t.addEventListener("versionchange",function(){l(f())});
t.addEventListener("close",function(){Ho("IDB_UNEXPECTEDLY_CLOSED",{dbName:Jo(a),dbVersion:t.version});m&&m()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function yp(a,b,c){c=void 0===c?{}:c;return xp(a,b,c)}
function zp(a,b){b=void 0===b?{}:b;var c,d,e,f;return x(function(g){if(1==g.h)return ya(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.de)&&c.addEventListener("blocked",function(){e()}),w(g,dp(c),4);
if(2!=g.h)return Aa(g,0);f=Ba(g);throw Uo(f,a,"",-1);})}
;function Ap(a,b){this.name=a;this.options=b;this.j=!0;this.m=this.l=0}
Ap.prototype.i=function(a,b,c){c=void 0===c?{}:c;return yp(a,b,c)};
Ap.prototype.delete=function(a){a=void 0===a?{}:a;return zp(this.name,a)};
function Bp(a,b){return new Qo("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function Cp(a,b){if(!b)throw Vo("openWithToken",Jo(a.name));return Dp(a)}
function Dp(a){function b(){var f,g,h,l,m,n,q,u,t,z;return x(function(C){switch(C.h){case 1:return g=null!=(f=Error().stack)?f:"",ya(C,2),w(C,a.i(a.name,a.options.version,d),4);case 4:h=C.i;for(var E=a.options,M=[],S=r(Object.keys(E.Ab)),Q=S.next();!Q.done;Q=S.next()){Q=Q.value;var W=E.Ab[Q],fa=void 0===W.Pe?Number.MAX_VALUE:W.Pe;!(h.h.version>=W.Gb)||h.h.version>=fa||h.h.objectStoreNames.contains(Q)||M.push(Q)}l=M;if(0===l.length){C.A(5);break}m=Object.keys(a.options.Ab);n=h.objectStoreNames();if(a.m<
gn("ytidb_reopen_db_retries",0))return a.m++,h.close(),Go(new Qo("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:n})),C.return(b());if(!(a.l<gn("ytidb_remake_db_retries",1))){C.A(6);break}a.l++;return w(C,a.delete(),7);case 7:return Go(new Qo("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:n})),C.return(b());case 6:throw new Ro(n,m);case 5:return C.return(h);case 2:q=Ba(C);if(q instanceof DOMException?"VersionError"!==
q.name:"DOMError"in self&&q instanceof DOMError?"VersionError"!==q.name:!(q instanceof Object&&"message"in q)||"An attempt was made to open a database using a lower version than the existing version."!==q.message){C.A(8);break}return w(C,a.i(a.name,void 0,Object.assign({},d,{upgrade:void 0})),9);case 9:u=C.i;t=u.h.version;if(void 0!==a.options.version&&t>a.options.version+1)throw u.close(),a.j=!1,Bp(a,t);return C.return(u);case 8:throw c(),q instanceof Error&&!P("ytidb_async_stack_killswitch")&&(q.stack=
q.stack+"\n"+g.substring(g.indexOf("\n")+1)),Uo(q,a.name,"",null!=(z=a.options.version)?z:-1);}})}
function c(){a.h===e&&(a.h=void 0)}
if(!a.j)throw Bp(a);if(a.h)return a.h;var d={blocking:function(f){f.close()},
closed:c,hf:c,upgrade:a.options.upgrade};var e=b();a.h=e;return a.h}
;var Ep=new Ap("YtIdbMeta",{Ab:{databases:{Gb:1}},upgrade:function(a,b){b(1)&&jp(a,"databases",{keyPath:"actualName"})}});
function Fp(a,b){var c;return x(function(d){if(1==d.h)return w(d,Cp(Ep,b),2);c=d.i;return d.return(ip(c,["databases"],{ca:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return ep(f.h.put(a,void 0)).then(function(){})})}))})}
function Gp(a,b){var c;return x(function(d){if(1==d.h)return a?w(d,Cp(Ep,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function Hp(a,b){var c,d;return x(function(e){return 1==e.h?(c=[],w(e,Cp(Ep,b),2)):3!=e.h?(d=e.i,w(e,ip(d,["databases"],{ca:!0,mode:"readonly"},function(f){c.length=0;return sp(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function Ip(a){return Hp(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function Jp(a,b,c){return Hp(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function Kp(a){var b,c;return x(function(d){if(1==d.h)return b=po("YtIdbMeta hasAnyMeta other"),w(d,Hp(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(0<c.length)})}
;var Lp,Mp=new function(){}(new function(){});
function Np(){var a,b,c,d;return x(function(e){switch(e.h){case 1:a=yo();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=Cn)f=/WebKit\/([0-9]+)/.exec(Wb()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Wb()),f=!(f&&602<=parseInt(f[1],10)));if(f||Zc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
ya(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return w(e,Fp(d,Mp),4);case 4:return w(e,Gp("yt-idb-test-do-not-use",Mp),5);case 5:return e.return(!0);case 2:return Ba(e),e.return(!1)}})}
function Op(){if(void 0!==Lp)return Lp;Bo=!0;return Lp=Np().then(function(a){Bo=!1;var b;if(null!=(b=xo())&&b.h){var c;b={hasSucceededOnce:(null==(c=yo())?void 0:c.hasSucceededOnce)||a};var d;null==(d=xo())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Pp(){return B("ytglobal.idbToken_")||void 0}
function Qp(){var a=Pp();return a?Promise.resolve(a):Op().then(function(b){(b=b?Mp:void 0)&&A("ytglobal.idbToken_",b);return b})}
;var Rp=0;function Sp(a,b){Rp||(Rp=Hi.ea(function(){var c,d,e,f,g;return x(function(h){switch(h.h){case 1:return w(h,Qp(),2);case 2:c=h.i;if(!c)return h.return();d=!0;ya(h,3);return w(h,Jp(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.A(6);break}f=e[0];return w(h,zp(f.actualName),7);case 7:return w(h,Gp(f.actualName,c),6);case 6:Aa(h,4);break;case 3:g=Ba(h),Go(g),d=!1;case 4:Hi.Ba(Rp),Rp=0,d&&Sp(a,b),h.h=0}})}))}
function Tp(){var a;return x(function(b){return 1==b.h?w(b,Qp(),2):(a=b.i)?b.return(Kp(a)):b.return(!1)})}
new di;function Up(a){if(!oo())throw a=new Qo("AUTH_INVALID",{dbName:a}),Go(a),a;var b=po();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Vp(a,b,c,d){var e,f,g,h,l,m;return x(function(n){switch(n.h){case 1:return f=null!=(e=Error().stack)?e:"",w(n,Qp(),2);case 2:g=n.i;if(!g)throw h=Vo("openDbImpl",a,b),P("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),Go(h),h;Io(a);l=c?{actualName:a,publicName:a,userIdentifier:void 0}:Up(a);ya(n,3);return w(n,Fp(l,g),5);case 5:return w(n,yp(l.actualName,b,d),6);case 6:return n.return(n.i);case 3:return m=Ba(n),ya(n,7),w(n,Gp(l.actualName,g),9);case 9:Aa(n,
8);break;case 7:Ba(n);case 8:throw m;}})}
function Wp(a,b,c){c=void 0===c?{}:c;return Vp(a,b,!1,c)}
function Xp(a,b,c){c=void 0===c?{}:c;return Vp(a,b,!0,c)}
function Yp(a,b){b=void 0===b?{}:b;var c,d;return x(function(e){if(1==e.h)return w(e,Qp(),2);if(3!=e.h){c=e.i;if(!c)return e.return();Io(a);d=Up(a);return w(e,zp(d.actualName,b),3)}return w(e,Gp(d.actualName,c),0)})}
function Zp(a,b,c){a=a.map(function(d){return x(function(e){return 1==e.h?w(e,zp(d.actualName,b),2):w(e,Gp(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function $p(){var a=void 0===a?{}:a;var b,c;return x(function(d){if(1==d.h)return w(d,Qp(),2);if(3!=d.h){b=d.i;if(!b)return d.return();Io("LogsDatabaseV2");return w(d,Ip(b),3)}c=d.i;return w(d,Zp(c,a,b),0)})}
function aq(a,b){b=void 0===b?{}:b;var c;return x(function(d){if(1==d.h)return w(d,Qp(),2);if(3!=d.h){c=d.i;if(!c)return d.return();Io(a);return w(d,zp(a,b),3)}return w(d,Gp(a,c),0)})}
;function bq(a,b){Ap.call(this,a,b);this.options=b;Io(a)}
v(bq,Ap);function cq(a,b){var c;return function(){c||(c=new bq(a,b));return c}}
bq.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.qc?Xp:Wp)(a,b,Object.assign({},c))};
bq.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.qc?aq:Yp)(this.name,a)};
function dq(a,b){return cq(a,b)}
;var eq={},fq=dq("ytGcfConfig",{Ab:(eq.coldConfigStore={Gb:1},eq.hotConfigStore={Gb:1},eq),qc:!1,upgrade:function(a,b){b(1)&&(qp(jp(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),qp(jp(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function gq(a){return Cp(fq(),a)}
function hq(a,b,c){var d,e,f;return x(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:T()},w(g,gq(c),2);case 2:return e=g.i,w(g,e.clear("hotConfigStore"),3);case 3:return w(g,lp(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function iq(a,b,c,d){var e,f,g;return x(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:T()},w(h,gq(d),2);case 2:return f=h.i,w(h,f.clear("coldConfigStore"),3);case 3:return w(h,lp(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function jq(a){var b,c;return x(function(d){return 1==d.h?w(d,gq(a),2):3!=d.h?(b=d.i,c=void 0,w(d,ip(b,["coldConfigStore"],{mode:"readwrite",ca:!0},function(e){return vp(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function kq(a){var b,c;return x(function(d){return 1==d.h?w(d,gq(a),2):3!=d.h?(b=d.i,c=void 0,w(d,ip(b,["hotConfigStore"],{mode:"readwrite",ca:!0},function(e){return vp(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function lq(){this.h=0}
function mq(a,b,c){var d,e,f;return x(function(g){if(1==g.h){if(!P("update_log_event_config"))return g.A(0);c&&(a.i=c,A("yt.gcf.config.hotConfigGroup",a.i));a.hotHashData=b;A("yt.gcf.config.hotHashData",a.hotHashData);return(d=Pp())?c?g.A(4):w(g,kq(d),5):g.A(0)}4!=g.h&&(e=g.i,c=null==(f=e)?void 0:f.config);return w(g,hq(c,b,d),0)})}
function nq(a,b,c){var d,e,f,g;return x(function(h){if(1==h.h){if(!P("update_log_event_config"))return h.A(0);a.coldHashData=b;A("yt.gcf.config.coldHashData",a.coldHashData);return(d=Pp())?c?h.A(4):w(h,jq(d),5):h.A(0)}4!=h.h&&(e=h.i,c=null==(f=e)?void 0:f.config);if(!c)return h.A(0);g=c.configData;return w(h,iq(c,b,g,d),0)})}
;function oq(){return"INNERTUBE_API_KEY"in Mm&&"INNERTUBE_API_VERSION"in Mm}
function pq(){return{innertubeApiKey:O("INNERTUBE_API_KEY"),innertubeApiVersion:O("INNERTUBE_API_VERSION"),Dc:O("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),td:O("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),ye:O("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:O("INNERTUBE_CONTEXT_CLIENT_VERSION"),vd:O("INNERTUBE_CONTEXT_HL"),ud:O("INNERTUBE_CONTEXT_GL"),ze:O("INNERTUBE_HOST_OVERRIDE")||"",Be:!!O("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Ae:!!O("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:O("SERIALIZED_CLIENT_CONFIG_DATA")}}
function qq(a){var b={client:{hl:a.vd,gl:a.ud,clientName:a.td,clientVersion:a.innertubeContextClientVersion,configInfo:a.Dc}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=y.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=hn();""!==c&&(b.client.experimentsToken=c);c=jn();0<c.length&&(b.request={internalExperimentFlags:c});rq(a,void 0,b);sq(void 0,b);tq(void 0,b);uq(a,void 0,b);vq(void 0,b);P("start_sending_config_hash")&&wq(void 0,b);O("DELEGATED_SESSION_ID")&&
!P("pageid_as_header_web")&&(b.user={onBehalfOfUser:O("DELEGATED_SESSION_ID")});a=Object;c=a.assign;for(var d=b.client,e={},f=r(Object.entries($m(O("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=r(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function xq(a){var b=new hl,c=new Xk;G(c,1,a.vd);G(c,2,a.ud);G(c,16,a.ye);G(c,17,a.innertubeContextClientVersion);if(a.Dc){var d=a.Dc,e=new Tk;d.coldConfigData&&G(e,1,d.coldConfigData);d.appInstallData&&G(e,6,d.appInstallData);d.coldHashData&&G(e,3,d.coldHashData);d.hotHashData&&G(e,5,d.hotHashData);H(c,Tk,62,e)}(d=y.devicePixelRatio)&&1!=d&&G(c,65,Wd(d));d=hn();""!==d&&G(c,54,d);d=jn();if(0<d.length){e=new al;for(var f=0;f<d.length;f++){var g=new Zk;G(g,1,d[f].key);ge(g,2,$k,d[f].value);ne(e,15,
Zk,g)}H(b,al,5,e)}rq(a,c);sq(b);tq(c);uq(a,c);vq(c);P("start_sending_config_hash")&&wq(c);O("DELEGATED_SESSION_ID")&&!P("pageid_as_header_web")&&(a=new fl,G(a,3,O("DELEGATED_SESSION_ID")));a=r(Object.entries($m(O("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=r(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?G(c,12,e):"cmodel"===d?G(c,13,e):"cbr"===d?G(c,87,e):"cbrver"===d?G(c,88,e):"cos"===d?G(c,18,e):"cosver"===d?G(c,19,e):"cplatform"===d&&G(c,42,e);b.l(c);return b}
function rq(a,b,c){a=a.td;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=ie(b,Uk,96)||new Uk;var d=Vn();d=Object.keys(El).indexOf(d);d=-1===d?null:d;null!==d&&G(c,3,d);H(b,Uk,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=Vn())}
function sq(a,b){var c=B("yt.embedded_player.embed_url");c&&(a?(b=ie(a,cl,7)||new cl,G(b,4,c),H(a,cl,7,b)):b&&(b.thirdParty={embedUrl:c}))}
function tq(a,b){var c;if(P("web_log_memory_total_kbytes")&&(null==(c=y.navigator)?0:c.deviceMemory)){var d;c=null==(d=y.navigator)?void 0:d.deviceMemory;a?G(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function uq(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=ie(b,Tk,62))?d:new Tk;G(c,6,a.appInstallData);H(b,Tk,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function vq(a,b){var c=mo();c&&(a?G(a,61,io[c]):b&&(b.client.connectionType=c));P("web_log_effective_connection_type")&&(c=no())&&(a?G(a,94,jo[c]):b&&(b.client.effectiveConnectionType=c))}
function yq(a,b,c){c=void 0===c?{}:c;var d={};O("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":O("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||O("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.qg||O("AUTHORIZATION");b||(a?b="Bearer "+B("gapi.auth.getToken")().pg:(a=Sn(Rn()),P("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
function wq(a,b){lq.h||(lq.h=new lq);var c=lq.h;var d=T()-c.h;if(0!==c.h&&d<gn("send_config_hash_timer"))c=void 0;else{d=B("yt.gcf.config.coldConfigData");var e=B("yt.gcf.config.hotHashData"),f=B("yt.gcf.config.coldHashData");d&&e&&f&&(c.h=T());c={coldConfigData:d,hotHashData:e,coldHashData:f}}if(e=c)if(c=e.coldConfigData,d=e.coldHashData,e=e.hotHashData,c&&d&&e)if(a){var g;b=null!=(g=ie(a,Tk,62))?g:new Tk;G(b,1,c);G(b,3,d);G(b,5,e);H(a,Tk,62,b)}else b&&(b.client.configInfo=b.client.configInfo||{},
b.client.configInfo.coldConfigData=c,b.client.configInfo.coldHashData=d,b.client.configInfo.hotHashData=e)}
;function zq(a,b){this.version=a;this.args=b}
;function Aq(a,b){this.topic=a;this.h=b}
Aq.prototype.toString=function(){return this.topic};var Bq=B("ytPubsub2Pubsub2Instance")||new dj;dj.prototype.subscribe=dj.prototype.subscribe;dj.prototype.unsubscribeByKey=dj.prototype.Fb;dj.prototype.publish=dj.prototype.cb;dj.prototype.clear=dj.prototype.clear;A("ytPubsub2Pubsub2Instance",Bq);var Cq=B("ytPubsub2Pubsub2SubscribedKeys")||{};A("ytPubsub2Pubsub2SubscribedKeys",Cq);var Dq=B("ytPubsub2Pubsub2TopicToKeys")||{};A("ytPubsub2Pubsub2TopicToKeys",Dq);var Eq=B("ytPubsub2Pubsub2IsAsync")||{};A("ytPubsub2Pubsub2IsAsync",Eq);
A("ytPubsub2Pubsub2SkipSubKey",null);function Fq(a,b){var c=Gq();c&&c.publish.call(c,a.toString(),a,b)}
function Hq(a){var b=Iq,c=Gq();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=B("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(Cq[d])try{if(f&&b instanceof Aq&&b!=e)try{var h=b.h,l=f;if(!l.args||!l.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Va){var m=new h;h.Va=m.version}var n=h.Va}catch(E){}if(!n||l.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{n=Reflect;var q=n.construct;
var u=l.args,t=u.length;if(0<t){var z=Array(t);for(l=0;l<t;l++)z[l]=u[l];var C=z}else C=[];f=q.call(n,h,C)}catch(E){throw E.message="yt.pubsub2.Data.deserialize(): "+E.message,E;}}catch(E){throw E.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+E.message,E;}a.call(window,f)}catch(E){Sm(E)}},Eq[b.toString()]?B("yt.scheduler.instance")?Hi.ea(g):nn(g,0):g())});
Cq[d]=!0;Dq[b.toString()]||(Dq[b.toString()]=[]);Dq[b.toString()].push(d);return d}
function Jq(){var a=Kq,b=Hq(function(c){a.apply(void 0,arguments);Lq(b)});
return b}
function Lq(a){var b=Gq();b&&("number"===typeof a&&(a=[a]),gb(a,function(c){b.unsubscribeByKey(c);delete Cq[c]}))}
function Gq(){return B("ytPubsub2Pubsub2Instance")}
;function Mq(a,b,c){c=void 0===c?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&Fq("meta_logging_csi_event",{timerName:a,Qg:b})}
;var Nq=gn("max_body_size_to_compress",5E5),Oq=gn("min_body_size_to_compress",500),Pq=!0,Qq=0,Rq=0,Sq=gn("compression_performance_threshold",250),Tq=gn("slow_compressions_before_abandon_count",10);
function Uq(a,b,c,d){var e=T(),f={startTime:e},g={startTime:e,ticks:{},infos:{}};if(Pq&&void 0!==Jk)try{var h=Vq(b);if(!(h>Nq||h<Oq)){var l=Jk(Ci(b)),m=T();f.endTime=m;g.ticks.gelc=m;Rq++;P("disable_compression_due_to_performance_degredation")&&m-e>=Sq&&(Qq++,P("abandon_compression_after_N_slow_zips")?Rq===gn("compression_disable_point")&&Qq>Tq&&(Pq=!1):Pq=!1);Wq(g,f);if(Xq(l,b)||!P("only_compress_gel_if_smaller"))c.headers||(c.headers={}),c.headers["Content-Encoding"]="gzip",c.postBody=l,c.postParams=
void 0}d(a,c)}catch(n){Tm(n),d(a,c)}else d(a,c)}
function Yq(a){var b=void 0===b?!1:b;var c=T(),d={startTime:c};c={startTime:c,ticks:{},infos:{}};if(void 0!==Jk){if(!a.body)return a;try{var e="string"===typeof a.body?a.body:JSON.stringify(a.body),f=Vq(e);if(f>Nq||f<Oq)return a;var g=Jk(Ci(e)),h=T();d.endTime=h;c.ticks.gelc=h;if(!Xq(g,e)&&P("only_compress_gel_if_smaller"))return a;b&&Wq(c,d);a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=g;return a}catch(l){return Tm(l),a}}else return a}
function Xq(a,b){if(!window.Blob)return!0;var c=a.length<Vq(b);c||Sm(new R("Compressed req body is larger than uncompressed","original size: "+Vq(b),"compressed size: "+a.length));return c}
function Vq(a){return(new Blob(a.split(""))).size}
function Wq(a,b){P("gel_compression_csi_killswitch")||!P("log_gel_compression_latency")&&!P("log_gel_compression_latency_lr")||(P("use_new_cml")?Mq("gel_compression",a,{sampleRate:.1}):.001>=Math.random()&&Fq("gel_compression_latency_payload",b))}
;function Zq(a){a=Object.assign({},a);delete a.Authorization;var b=Tg();if(b){var c=new Ni;c.update(O("INNERTUBE_API_KEY"));c.update(b);a.hash=qd(c.digest(),3)}return a}
;var $q;function ar(){$q||($q=new wo("yt.innertube"));return $q}
function br(a,b,c,d){if(d)return null;d=ar().get("nextId",!0)||1;var e=ar().get("requests",!0)||{};e[d]={method:a,request:b,authState:Zq(c),requestTime:Math.round(T())};ar().set("nextId",d+1,86400,!0);ar().set("requests",e,86400,!0);return d}
function cr(a){var b=ar().get("requests",!0)||{};delete b[a];ar().set("requests",b,86400,!0)}
function dr(a){var b=ar().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(T())-d.requestTime)){var e=d.authState,f=Zq(yq(!1));tb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(T())),er(a,d.method,e,{}));delete b[c]}}ar().set("requests",b,86400,!0)}}
;function fr(a){this.Zb=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.ub=function(){};
this.now=Date.now;this.Jb=!1;var b;this.Od=null!=(b=a.Od)?b:100;var c;this.Id=null!=(c=a.Id)?c:1;var d;this.Gd=null!=(d=a.Gd)?d:2592E6;var e;this.Ed=null!=(e=a.Ed)?e:12E4;var f;this.Hd=null!=(f=a.Hd)?f:5E3;var g;this.N=null!=(g=a.N)?g:void 0;this.fc=!!a.fc;var h;this.dc=null!=(h=a.dc)?h:.1;var l;this.mc=null!=(l=a.mc)?l:10;a.handleError&&(this.handleError=a.handleError);a.ub&&(this.ub=a.ub);a.Jb&&(this.Jb=a.Jb);a.Zb&&(this.Zb=a.Zb);this.O=a.O;this.ya=a.ya;this.W=a.W;this.U=a.U;this.Na=a.Na;this.Lc=
a.Lc;this.Kc=a.Kc;gr(this)&&(!this.O||this.O("networkless_logging"))&&hr(this)}
function hr(a){gr(a)&&!a.Jb&&(a.h=!0,a.fc&&Math.random()<=a.dc&&a.W.ge(a.N),ir(a),a.U.oa()&&a.Rb(),a.U.La(a.Lc,a.Rb.bind(a)),a.U.La(a.Kc,a.ed.bind(a)))}
k=fr.prototype;k.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(gr(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.W.set(d,this.N).then(function(e){d.id=e;c.U.oa()&&jr(c,d)}).catch(function(e){jr(c,d);
kr(c,e)})}else this.Na(a,b)};
k.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(gr(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.O&&this.O("nwl_skip_retry")&&(e.skipRetry=c);if(this.U.oa()||this.O&&this.O("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return x(function(l){if(1==l.h)return w(l,d.W.set(e,d.N).catch(function(m){kr(d,m)}),2);
f(g,h);l.h=0})}}this.Na(a,b,e.skipRetry)}else this.W.set(e,this.N).catch(function(g){d.Na(a,b,e.skipRetry);
kr(d,g)})}else this.Na(a,b,this.O&&this.O("nwl_skip_retry")&&c)};
k.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(gr(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.W.tb(d.id,c.N):e=!0;c.U.ib&&c.O&&c.O("vss_network_hint")&&c.U.ib(!0);f(g,h)};
this.Na(d.url,d.options);this.W.set(d,this.N).then(function(g){d.id=g;e&&c.W.tb(d.id,c.N)}).catch(function(g){kr(c,g)})}else this.Na(a,b)};
k.Rb=function(){var a=this;if(!gr(this))throw Vo("throttleSend");this.i||(this.i=this.ya.ea(function(){var b;return x(function(c){if(1==c.h)return w(c,a.W.qd("NEW",a.N),2);if(3!=c.h)return b=c.i,b?w(c,jr(a,b),3):(a.ed(),c.return());a.i&&(a.i=0,a.Rb());c.h=0})},this.Od))};
k.ed=function(){this.ya.Ba(this.i);this.i=0};
function jr(a,b){var c,d;return x(function(e){switch(e.h){case 1:if(!gr(a))throw c=Vo("immediateSend"),c;if(void 0===b.id){e.A(2);break}return w(e,a.W.De(b.id,a.N),3);case 3:(d=e.i)||a.ub(Error("The request cannot be found in the database."));case 2:if(lr(a,b,a.Gd)){e.A(4);break}a.ub(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.A(5);break}return w(e,a.W.tb(b.id,a.N),5);case 5:return e.return();case 4:b.skipRetry||(b=mr(a,b));if(!b){e.A(0);break}if(!b.skipRetry||
void 0===b.id){e.A(8);break}return w(e,a.W.tb(b.id,a.N),8);case 8:a.Na(b.url,b.options,!!b.skipRetry),e.h=0}})}
function mr(a,b){if(!gr(a))throw Vo("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,l,m;return x(function(n){switch(n.h){case 1:g=nr(f);(h=or(f))&&a.O&&a.O("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.O&&a.O("nwl_consider_error_code")&&g||a.O&&!a.O("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.mc)){n.A(2);break}if(!a.U.pc){n.A(3);break}return w(n,a.U.pc(),3);case 3:if(a.U.oa()){n.A(2);break}c(e,f);if(!a.O||!a.O("nwl_consider_error_code")||void 0===(null==(l=b)?void 0:l.id)){n.A(6);
break}return w(n,a.W.Pc(b.id,a.N,!1),6);case 6:return n.return();case 2:if(a.O&&a.O("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.mc)return n.return();a.potentialEsfErrorCounter++;if(void 0===(null==(m=b)?void 0:m.id)){n.A(8);break}return b.sendCount<a.Id?w(n,a.W.Pc(b.id,a.N,!0,h?!1:void 0),12):w(n,a.W.tb(b.id,a.N),8);case 12:a.ya.ea(function(){a.U.oa()&&a.Rb()},a.Hd);
case 8:c(e,f),n.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return x(function(h){if(1==h.h)return void 0===(null==(g=b)?void 0:g.id)?h.A(2):w(h,a.W.tb(b.id,a.N),2);a.U.ib&&a.O&&a.O("vss_network_hint")&&a.U.ib(!0);d(e,f);h.h=0})};
return b}
function lr(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function ir(a){if(!gr(a))throw Vo("retryQueuedRequests");a.W.qd("QUEUED",a.N).then(function(b){b&&!lr(a,b,a.Ed)?a.ya.ea(function(){return x(function(c){if(1==c.h)return void 0===b.id?c.A(2):w(c,a.W.Pc(b.id,a.N),2);ir(a);c.h=0})}):a.U.oa()&&a.Rb()})}
function kr(a,b){a.Ud&&!a.U.oa()?a.Ud(b):a.handleError(b)}
function gr(a){return!!a.N||a.Zb}
function nr(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
function or(a){var b;a=null==a?void 0:null==(b=a.error)?void 0:b.code;return!(400!==a&&415!==a)}
;var pr;
function qr(){if(pr)return pr();var a={};pr=dq("LogsDatabaseV2",{Ab:(a.LogsRequestsStore={Gb:2},a),qc:!1,upgrade:function(b,c,d){c(2)&&jp(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),qp(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return pr()}
;function rr(a){return Cp(qr(),a)}
function sr(a,b){var c,d,e,f,g;return x(function(h){if(1==h.h)return c={startTime:T(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},d={startTime:T(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},w(h,rr(b),2);if(3!=h.h)return e=h.i,f=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:O("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),w(h,lp(e,"LogsRequestsStore",f),3);g=h.i;c.kf=T();d.ticks.tc=T();tr(d,c);return h.return(g)})}
function ur(a,b){var c,d,e,f,g,h,l,m;return x(function(n){if(1==n.h)return c={startTime:T(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},d={startTime:T(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},w(n,rr(b),2);if(3!=n.h)return e=n.i,f=O("INNERTUBE_CONTEXT_CLIENT_NAME",0),g=[a,f,0],h=[a,f,T()],l=IDBKeyRange.bound(g,h),m=void 0,w(n,ip(e,["LogsRequestsStore"],{mode:"readwrite",ca:!0},function(q){return vp(q.objectStore("LogsRequestsStore").index("newRequestV2"),{query:l,direction:"prev"},
function(u){u.getValue()&&(m=u.getValue(),"NEW"===a&&(m.status="QUEUED",u.update(m)))})}),3);
c.kf=T();d.ticks.tc=T();tr(d,c);return n.return(m)})}
function Br(a,b){var c;return x(function(d){if(1==d.h)return w(d,rr(b),2);c=d.i;return d.return(ip(c,["LogsRequestsStore"],{mode:"readwrite",ca:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",ep(f.h.put(g,void 0)).then(function(){return g})})}))})}
function Fr(a,b,c,d){c=void 0===c?!0:c;var e;return x(function(f){if(1==f.h)return w(f,rr(b),2);e=f.i;return f.return(ip(e,["LogsRequestsStore"],{mode:"readwrite",ca:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(l){return l?(l.status="NEW",c&&(l.sendCount+=1),void 0!==d&&(l.options.compress=d),ep(h.h.put(l,void 0)).then(function(){return l})):Zo.resolve(void 0)})}))})}
function Yr(a,b){var c;return x(function(d){if(1==d.h)return w(d,rr(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function Zr(a){var b,c;return x(function(d){if(1==d.h)return w(d,rr(a),2);b=d.i;c=T()-2592E6;return w(d,ip(b,["LogsRequestsStore"],{mode:"readwrite",ca:!0},function(e){return sp(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function $r(){x(function(a){return w(a,$p(),0)})}
function tr(a,b){P("nwl_csi_killswitch")||(P("use_new_cml")?Mq("networkless_performance",a,{sampleRate:1}):.01>=Math.random()&&Fq("nwl_transaction_latency_payload",b))}
;var as={},bs=dq("ServiceWorkerLogsDatabase",{Ab:(as.SWHealthLog={Gb:1},as),qc:!0,upgrade:function(a,b){b(1)&&qp(jp(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function cs(a){return Cp(bs(),a)}
function ds(a){var b,c;x(function(d){if(1==d.h)return w(d,cs(a),2);b=d.i;c=T()-2592E6;return w(d,ip(b,["SWHealthLog"],{mode:"readwrite",ca:!0},function(e){return sp(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function es(a){var b;return x(function(c){if(1==c.h)return w(c,cs(a),2);b=c.i;return w(c,b.clear("SWHealthLog"),0)})}
;var fs={},gs=0;function hs(a){var b=new Image,c=""+gs++;fs[c]=b;b.onload=b.onerror=function(){delete fs[c]};
b.src=a}
;function is(){this.h=new Map;this.i=!1}
function js(){if(!is.h){var a=B("yt.networkRequestMonitor.instance")||new is;A("yt.networkRequestMonitor.instance",a);is.h=a}return is.h}
is.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
is.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:!1===a&&this.i?!0:null};
is.prototype.removeParams=function(a){return a.split("?")[0]};
is.prototype.removeParams=is.prototype.removeParams;is.prototype.isEndpointCFR=is.prototype.isEndpointCFR;is.prototype.requestComplete=is.prototype.requestComplete;is.getInstance=js;var ks;function ls(){ks||(ks=new wo("yt.offline"));return ks}
function ms(a){if(P("offline_error_handling")){var b=ls().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);ls().set("errors",b,2592E3,!0)}}
;function ns(){vf.call(this);var a=this;this.j=!1;this.i=Gi();this.i.La("networkstatus-online",function(){if(a.j&&P("offline_error_handling")){var b=ls().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new R(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;Sm(d)}ls().set("errors",{},2592E3,!0)}}})}
v(ns,vf);function os(){if(!ns.h){var a=B("yt.networkStatusManager.instance")||new ns;A("yt.networkStatusManager.instance",a);ns.h=a}return ns.h}
k=ns.prototype;k.oa=function(){return this.i.oa()};
k.ib=function(a){this.i.i=a};
k.te=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
k.le=function(){this.j=!0};
k.La=function(a,b){return this.i.La(a,b)};
k.pc=function(a){a=Ei(this.i,a);a.then(function(b){P("use_cfr_monitor")&&js().requestComplete("generate_204",b)});
return a};
ns.prototype.sendNetworkCheckRequest=ns.prototype.pc;ns.prototype.listen=ns.prototype.La;ns.prototype.enableErrorFlushing=ns.prototype.le;ns.prototype.getWindowStatus=ns.prototype.te;ns.prototype.networkStatusHint=ns.prototype.ib;ns.prototype.isNetworkAvailable=ns.prototype.oa;ns.getInstance=os;function ps(a){a=void 0===a?{}:a;vf.call(this);var b=this;this.i=this.s=0;this.j=os();var c=B("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.oc?(this.oc=a.oc,c("networkstatus-online",function(){qs(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){qs(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){wf(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){wf(b,"publicytnetworkstatus-offline")})))}
v(ps,vf);ps.prototype.oa=function(){var a=B("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
ps.prototype.ib=function(a){var b=B("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
ps.prototype.pc=function(a){var b=this,c;return x(function(d){c=B("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return P("skip_network_check_if_cfr")&&js().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.ib((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.oa())})):c?d.return(c(a)):d.return(!0)})};
function qs(a,b){a.oc?a.i?(Hi.Ba(a.s),a.s=Hi.ea(function(){a.m!==b&&(wf(a,b),a.m=b,a.i=T())},a.oc-(T()-a.i))):(wf(a,b),a.m=b,a.i=T()):wf(a,b)}
;var rs;function ss(){var a=fr.call;rs||(rs=new ps({Cg:!0,wg:!0}));a.call(fr,this,{W:{ge:Zr,tb:Yr,qd:ur,De:Br,Pc:Fr,set:sr},U:rs,handleError:function(b,c,d){var e,f=null==d?void 0:null==(e=d.error)?void 0:e.code;if(400===f||415===f){var g;Sm(new R(b.message,c,null==d?void 0:null==(g=d.error)?void 0:g.code),void 0,void 0,void 0,!0)}else Sm(b)},
ub:Tm,Na:ts,now:T,Ud:ms,ya:vo(),Lc:"publicytnetworkstatus-online",Kc:"publicytnetworkstatus-offline",fc:!0,dc:.1,mc:gn("potential_esf_error_limit",10),O:P,Jb:!(oo()&&us())});this.j=new di;P("networkless_immediately_drop_all_requests")&&$r();aq("LogsDatabaseV2")}
v(ss,fr);function vs(){var a=B("yt.networklessRequestController.instance");a||(a=new ss,A("yt.networklessRequestController.instance",a),P("networkless_logging")&&Qp().then(function(b){a.N=b;hr(a);a.j.resolve();a.fc&&Math.random()<=a.dc&&a.N&&ds(a.N);P("networkless_immediately_drop_sw_health_store")&&ws(a)}));
return a}
ss.prototype.writeThenSend=function(a,b){b||(b={});oo()||(this.h=!1);fr.prototype.writeThenSend.call(this,a,b)};
ss.prototype.sendThenWrite=function(a,b,c){b||(b={});oo()||(this.h=!1);fr.prototype.sendThenWrite.call(this,a,b,c)};
ss.prototype.sendAndWrite=function(a,b){b||(b={});oo()||(this.h=!1);fr.prototype.sendAndWrite.call(this,a,b)};
ss.prototype.awaitInitialization=function(){return this.j.promise};
function ws(a){var b;x(function(c){if(!a.N)throw b=Vo("clearSWHealthLogsDb"),b;return c.return(es(a.N).catch(function(d){a.handleError(d)}))})}
function ts(a,b,c){P("use_cfr_monitor")&&xs(a,b);if(P("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(T())));else{var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(T())}if(c&&0===Object.keys(b).length){var e=void 0===e?"":e;var f=void 0===f?!1:f;if(a)if(e)wn(a,void 0,"POST",e);else if(O("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))wn(a,void 0,"GET","",void 0,void 0,f);else{b:{try{var g=new cb({url:a});if(g.j&&g.i||
g.l){var h=vc(wc(5,a)),l;if(!(l=!h||!h.endsWith("/aclk"))){var m=a.search(Hc),n=Gc(a,0,"ri",m);if(0>n)var q=null;else{var u=a.indexOf("&",n);if(0>u||u>m)u=m;q=decodeURIComponent(a.slice(n+3,-1!==u?u:0).replace(/\+/g," "))}l="1"!==q}var t=!l;break b}}catch(C){}t=!1}if(t){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var z=!0;break b}}catch(C){}z=!1}c=z?!0:!1}else c=!1;c||hs(a)}}else b.compress?b.postBody?("string"!==typeof b.postBody&&(b.postBody=JSON.stringify(b.postBody)),
Uq(a,b.postBody,b,tn)):Uq(a,JSON.stringify(b.postParams),b,Bn):tn(a,b)}
function xs(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){js().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){js().requestComplete(a,!0);d(e,f)}}
function us(){return"www.youtube-nocookie.com"!==xc(document.location.toString())}
;var ys=!1,zs=y.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:ys};A("ytNetworklessLoggingInitializationOptions",zs);function As(){var a;x(function(b){if(1==b.h)return w(b,Qp(),2);a=b.i;if(!a||!oo()&&!P("nwl_init_require_datasync_id_killswitch")||!us())return b.A(0);ys=!0;zs.isNwlInitialized=ys;return w(b,vs().awaitInitialization(),0)})}
;function Bs(a){var b=this;this.config_=null;a?this.config_=a:oq()&&(this.config_=pq());ro(function(){dr(b)},5E3)}
Bs.prototype.isReady=function(){!this.config_&&oq()&&(this.config_=pq());return!!this.config_};
function er(a,b,c,d){function e(z){z=void 0===z?!1:z;var C;if(d.retry&&"www.youtube-nocookie.com"!=h&&(z||P("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(C=br(b,c,m,l)),C)){var E=g.onSuccess,M=g.onFetchSuccess;g.onSuccess=function(Q,W){cr(C);E(Q,W)};
c.onFetchSuccess=function(Q,W){cr(C);M(Q,W)}}try{if(z&&d.retry&&!d.zd.bypassNetworkless)g.method="POST",d.zd.writeThenSend?vs().writeThenSend(t,g):vs().sendAndWrite(t,g);
else if(d.compress)if(g.postBody){var S=g.postBody;"string"!==typeof S&&(S=JSON.stringify(g.postBody));Uq(t,S,g,tn)}else Uq(t,JSON.stringify(g.postParams),g,Bn);else P("web_all_payloads_via_jspb")?tn(t,g):Bn(t,g)}catch(Q){if("InvalidAccessError"==Q.name)C&&(cr(C),C=0),Tm(Error("An extension is blocking network request."));else throw Q;}C&&ro(function(){dr(a)},5E3)}
!O("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Tm(new R("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new R("innertube xhrclient not ready",b,c,d);Sm(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(z,C){if(d.onSuccess)d.onSuccess(C)},
onFetchSuccess:function(z){if(d.onSuccess)d.onSuccess(z)},
onError:function(z,C){if(d.onError)d.onError(C)},
onFetchError:function(z){if(d.onError)d.onError(z)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.ze)&&(h=f);var l=a.config_.Be||!1,m=yq(l,h,d);Object.assign(g.headers,m);(f=g.headers.Authorization)&&!h&&l&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,q={alt:"json"},u=a.config_.Ae&&f;u=u&&f.startsWith("Bearer");u||(q.key=a.config_.innertubeApiKey);var t=bn(""+h+n,q||{},!0);(B("ytNetworklessLoggingInitializationOptions")?
zs.isNwlInitialized:ys)?Op().then(function(z){e(z)}):e(!1)}
;var Cs=0,Ds=ad?"webkit":$c?"moz":Yc?"ms":Xc?"o":"";A("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++Cs});var Es={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Fs(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Es||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Gs(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Fs.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Fs.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Fs.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var pb=y.ytEventsEventsListeners||{};A("ytEventsEventsListeners",pb);var Hs=y.ytEventsEventsCounter||{count:0};A("ytEventsEventsCounter",Hs);
function Is(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return ob(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Sa(e[4])&&Sa(d)&&tb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Js=eb(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Ks(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Is(a,b,c,d);if(e)return e;e=++Hs.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Fs(h);if(!Ff(h.relatedTarget,function(l){return l==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Fs(h);
h.currentTarget=a;return c.call(a,h)};
g=Rm(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Js()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);pb[e]=[a,b,c,g,d];return e}
function Ls(a){a&&("string"==typeof a&&(a=[a]),gb(a,function(b){if(b in pb){var c=pb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Js()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete pb[b]}}))}
;function Ms(a){this.H=a;this.i=null;this.m=0;this.v=null;this.s=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.T=Ks(window,"mousemove",Ya(this.V,this));a=Ya(this.M,this);"function"===typeof a&&(a=Rm(a));this.Y=window.setInterval(a,25)}
$a(Ms,K);Ms.prototype.V=function(a){void 0===a.h&&Gs(a);var b=a.h;void 0===a.i&&Gs(a);this.i=new Bf(b,a.i)};
Ms.prototype.M=function(){if(this.i){var a=T();if(0!=this.m){var b=this.v,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.s)/this.s)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.H();this.s=d}this.m=a;this.v=this.i;this.l=(this.l+1)%4}};
Ms.prototype.L=function(){window.clearInterval(this.Y);Ls(this.T)};var Ns={};
function Os(a){var b=void 0===a?{}:a;a=void 0===b.Me?!1:b.Me;b=void 0===b.me?!0:b.me;if(null==B("_lact",window)){var c=parseInt(O("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;A("_lact",c,window);A("_fact",c,window);-1==c&&Ps();Ks(document,"keydown",Ps);Ks(document,"keyup",Ps);Ks(document,"mousedown",Ps);Ks(document,"mouseup",Ps);a?Ks(window,"touchmove",function(){Qs("touchmove",200)},{passive:!0}):(Ks(window,"resize",function(){Qs("resize",200)}),b&&Ks(window,"scroll",function(){Qs("scroll",200)}));
new Ms(function(){Qs("mouse",100)});
Ks(document,"touchstart",Ps,{passive:!0});Ks(document,"touchend",Ps,{passive:!0})}}
function Qs(a,b){Ns[a]||(Ns[a]=!0,Hi.ea(function(){Ps();Ns[a]=!1},b))}
function Ps(){null==B("_lact",window)&&Os();var a=Date.now();A("_lact",a,window);-1==B("_fact",window)&&A("_fact",a,window);(a=B("ytglobal.ytUtilActivityCallback_"))&&a()}
function Rs(){var a=B("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var Ss=y.ytPubsubPubsubInstance||new dj,Ts=y.ytPubsubPubsubSubscribedKeys||{},Us=y.ytPubsubPubsubTopicToKeys||{},Vs=y.ytPubsubPubsubIsSynchronous||{};function Ws(a,b){var c=Xs();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Ts[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Vs[a]?f():nn(f,0)}catch(g){Sm(g)}},void 0);
Ts[d]=!0;Us[a]||(Us[a]=[]);Us[a].push(d);return d}return 0}
function Ys(a){var b=Xs();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),gb(a,function(c){b.unsubscribeByKey(c);delete Ts[c]}))}
function Zs(a,b){var c=Xs();c&&c.publish.apply(c,arguments)}
function $s(a){var b=Xs();if(b)if(b.clear(a),a)at(a);else for(var c in Us)at(c)}
function Xs(){return y.ytPubsubPubsubInstance}
function at(a){Us[a]&&(a=Us[a],gb(a,function(b){Ts[b]&&delete Ts[b]}),a.length=0)}
dj.prototype.subscribe=dj.prototype.subscribe;dj.prototype.unsubscribeByKey=dj.prototype.Fb;dj.prototype.publish=dj.prototype.cb;dj.prototype.clear=dj.prototype.clear;A("ytPubsubPubsubInstance",Ss);A("ytPubsubPubsubTopicToKeys",Us);A("ytPubsubPubsubIsSynchronous",Vs);A("ytPubsubPubsubSubscribedKeys",Ts);var bt=Symbol("injectionDeps");function ct(a){this.name=a}
ct.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function dt(a){this.key=a}
function et(){this.h=new Map;this.i=new Map}
et.prototype.resolve=function(a){return a instanceof dt?ft(this,a.key,[],!0):ft(this,a,[])};
function ft(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.h.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.h.get(b);c.push(b);if(void 0!==d.Rd)var e=d.Rd;else if(d.nf)e=d[bt]?gt(a,d[bt],c):[],e=d.nf.apply(d,ja(e));else if(d.Qd){e=d.Qd;var f=e[bt]?gt(a,e[bt],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ja(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Og||a.i.set(b,e);return e}
function gt(a,b,c){return b?b.map(function(d){return d instanceof dt?ft(a,d.key,c,!0):ft(a,d,c)}):[]}
;var ht;function jt(){ht||(ht=new et);return ht}
;function kt(){this.store={};this.h={}}
kt.prototype.storePayload=function(a,b){a=lt(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
kt.prototype.extractMatchingEntries=function(a){a=mt(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,ja(this.store[a[c]])),delete this.store[a[c]]);return b};
kt.prototype.getSequenceCount=function(a){a=mt(this,a);for(var b=0,c=0;c<a.length;c++)b+=this.store[a[c]].length||0;return b};
function mt(a,b){var c=lt(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(1>=d.length&&lt(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(nt(b.auth,g[0])){var h=b.isJspb;nt(void 0===h?"undefined":h?"true":"false",g[1])&&nt(b.cttAuthInfo,g[2])&&e.push(d[f])}}return a.h[c]=e}
function nt(a,b){return void 0===a||"undefined"===a?!0:a===b}
kt.prototype.getSequenceCount=kt.prototype.getSequenceCount;kt.prototype.extractMatchingEntries=kt.prototype.extractMatchingEntries;kt.prototype.storePayload=kt.prototype.storePayload;function lt(a){return[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo].join("/")}
;function ot(a,b){if(a)return a[b.name]}
;var pt=gn("initial_gel_batch_timeout",2E3),qt=gn("gel_queue_timeout_max_ms",6E4),rt=Math.pow(2,16)-1,st=void 0;function tt(){this.j=this.h=this.i=0}
var ut=new tt,vt=new tt,wt,xt=!0,zt=y.ytLoggingTransportTokensToCttTargetIds_||{};A("ytLoggingTransportTokensToCttTargetIds_",zt);var At=y.ytLoggingTransportTokensToJspbCttTargetIds_||{};A("ytLoggingTransportTokensToJspbCttTargetIds_",At);var Bt={};function Ct(){var a=B("yt.logging.ims");a||(a=new kt,A("yt.logging.ims",a));return a}
function Dt(a,b){P("web_all_payloads_via_jspb")&&Tm(new R("transport.log called for JSON in JSPB only experiment"));if("log_event"===a.endpoint){Et(a);var c=Ft(a);Bt[c]=!0;var d={cttAuthInfo:c,isJspb:!1};Ct().storePayload(d,a.payload);Gt(b,c,!1,d)}}
function Ht(a,b){if("log_event"===a.endpoint){Et(void 0,a);var c=Ft(a,!0);Bt[c]=!0;var d={cttAuthInfo:c,isJspb:!0};Ct().storePayload(d,a.payload.toJSON());Gt(b,c,!0,d)}}
function Gt(a,b,c,d){c=void 0===c?!1:c;a&&(st=new a);a=gn("tvhtml5_logging_max_batch_ads_fork")||gn("tvhtml5_logging_max_batch")||gn("web_logging_max_batch")||100;var e=T(),f=c?vt.j:ut.j,g=0;d&&(g=Ct().getSequenceCount(d));g>=a?wt||(wt=It(function(){Jt({writeThenSend:!0},P("flush_only_full_queue")?b:void 0,c);wt=void 0},0)):10<=e-f&&(Kt(c),c?vt.j=e:ut.j=e)}
function Lt(a,b){P("web_all_payloads_via_jspb")&&Tm(new R("transport.logIsolatedGelPayload called in JSPB only experiment"));if("log_event"===a.endpoint){Et(a);var c=Ft(a),d=new Map;d.set(c,[a.payload]);b&&(st=new b);return new Rf(function(e,f){st&&st.isReady()?Mt(d,st,e,f,{bypassNetworkless:!0},!0):e()})}}
function Nt(a,b){if("log_event"===a.endpoint){Et(void 0,a);var c=Ft(a,!0),d=new Map;d.set(c,[a.payload.toJSON()]);b&&(st=new b);return new Rf(function(e){st&&st.isReady()?Ot(d,st,e,{bypassNetworkless:!0},!0):e()})}}
function Ft(a,b){var c="";if(a.dangerousLogToVisitorSession)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new wm;c.videoId?d.setVideoId(c.videoId):c.playlistId&&ge(d,2,xm,c.playlistId);At[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),zt[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function Jt(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;!c&&P("web_all_payloads_via_jspb")&&Tm(new R("transport.flushLogs called for JSON in JSPB only experiment"));new Rf(function(d,e){c?(Pt(vt.i),Pt(vt.h),vt.h=0):(Pt(ut.i),Pt(ut.h),ut.h=0);if(st&&st.isReady()){var f=a,g=c,h=st;f=void 0===f?{}:f;g=void 0===g?!1:g;var l=new Map,m=new Map;if(void 0!==b)g?(e=Ct().extractMatchingEntries({isJspb:g,cttAuthInfo:b}),l.set(b,e),Ot(l,h,d,f)):(l=Ct().extractMatchingEntries({isJspb:g,cttAuthInfo:b}),m.set(b,
l),Mt(m,h,d,e,f));else if(g){e=r(Object.keys(Bt));for(g=e.next();!g.done;g=e.next())m=g.value,g=Ct().extractMatchingEntries({isJspb:!0,cttAuthInfo:m}),0<g.length&&l.set(m,g),delete Bt[m];Ot(l,h,d,f)}else{l=r(Object.keys(Bt));for(g=l.next();!g.done;g=l.next()){g=g.value;var n=Ct().extractMatchingEntries({isJspb:!1,cttAuthInfo:g});0<n.length&&m.set(g,n);delete Bt[g]}Mt(m,h,d,e,f)}}else Kt(c),d()})}
function Kt(a){a=void 0===a?!1:a;if(P("web_gel_timeout_cap")&&(!a&&!ut.h||a&&!vt.h)){var b=It(function(){Jt({writeThenSend:!0},void 0,a)},qt);
a?vt.h=b:ut.h=b}Pt(a?vt.i:ut.i);b=O("LOGGING_BATCH_TIMEOUT",gn("web_gel_debounce_ms",1E4));P("shorten_initial_gel_batch_timeout")&&xt&&(b=pt);b=It(function(){Jt({writeThenSend:!0},void 0,a)},b);
a?vt.i=b:ut.i=b}
function Mt(a,b,c,d,e,f){e=void 0===e?{}:e;var g=Math.round(T()),h=a.size,l={};a=r(a);for(var m=a.next();!m.done;l={Sb:l.Sb,Ya:l.Ya,Db:l.Db,Ub:l.Ub,Tb:l.Tb},m=a.next()){var n=r(m.value);m=n.next().value;n=n.next().value;l.Ya=vb({context:qq(b.config_||pq())});if(!Qa(n)&&!P("throw_err_when_logevent_malformed_killswitch")){d();break}l.Ya.events=n;(n=zt[m])&&Qt(l.Ya,m,n);delete zt[m];l.Db="visitorOnlyApprovedKey"===m;Rt(l.Ya,g,l.Db);St(e);l.Ub=function(q){P("update_log_event_config")&&Hi.ea(function(){return x(function(u){return w(u,
Tt(q),0)})});
h--;h||c()};
l.Sb=0;l.Tb=function(q){return function(){q.Sb++;if(e.bypassNetworkless&&1===q.Sb)try{er(b,"log_event",q.Ya,Ut({writeThenSend:!0},q.Db,q.Ub,q.Tb,f)),xt=!1}catch(u){Sm(u),d()}h--;h||c()}}(l);
try{er(b,"log_event",l.Ya,Ut(e,l.Db,l.Ub,l.Tb,f)),xt=!1}catch(q){Sm(q),d()}}}
function Ot(a,b,c,d,e){d=void 0===d?{}:d;var f=Math.round(T()),g=a.size,h=new Map([].concat(ja(a)));h=r(h);for(var l=h.next();!l.done;l=h.next()){var m=r(l.value).next().value,n=a.get(m);l=new ym;var q=xq(b.config_||pq());H(l,hl,1,q);n=n?Vt(n):[];n=r(n);for(q=n.next();!q.done;q=n.next())ne(l,3,sm,q.value);(n=At[m])&&Wt(l,m,n);delete At[m];m="visitorOnlyApprovedKey"===m;Xt(l,f,m);St(d);l=Ee(l);m=Ut(d,m,function(u){P("update_log_event_config")&&Hi.ea(function(){return x(function(t){return w(t,Tt(u),
0)})});
g--;g||c()},function(){g--;
g||c()},e);
m.headers["Content-Type"]="application/json+protobuf";m.postBodyFormat="JSPB";m.postBody=l;er(b,"log_event","",m);xt=!1}}
function St(a){P("always_send_and_write")&&(a.writeThenSend=!1)}
function Ut(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,zd:a,dangerousLogToVisitorSession:b,sg:!!e,headers:{},postBodyFormat:"",postBody:"",compress:P("compress_gel")||P("compress_gel_lr")};Yt()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(T())));return a}
function Rt(a,b,c){Yt()||(a.requestTimeMs=String(b));P("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=O("EVENT_ID"))&&(c=Zt(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Xt(a,b,c){Yt()||G(a,2,b);if(!c&&(b=O("EVENT_ID"))){c=Zt();var d=new vm;G(d,1,b);G(d,2,c);H(a,vm,5,d)}}
function Zt(){var a=O("BATCH_CLIENT_COUNTER")||0;a||(a=Math.floor(Math.random()*rt/2));a++;a>rt&&(a=1);Nm("BATCH_CLIENT_COUNTER",a);return a}
function Qt(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Wt(a,b,c){var d=1===he(c,xm)?1:-1;if(ae(c,d))d=1;else if(c.getPlaylistId())d=2;else return;H(a,wm,4,c);a=ie(a,hl,1)||new hl;c=ie(a,fl,3)||new fl;var e=new el;G(e,2,b);G(e,1,d);ne(c,12,el,e);H(a,fl,3,c)}
function Vt(a){for(var b=[],c=0;c<a.length;c++)try{b.push(new sm(a[c]))}catch(d){Sm(new R("Transport failed to deserialize "+String(a[c])))}return b}
function Et(a,b){if(B("yt.logging.transport.enableScrapingForTest")){var c=B("yt.logging.transport.scrapedPayloadsForTesting"),d=B("yt.logging.transport.payloadToScrape");b&&(b=B("yt.logging.transport.getScrapedPayloadFromClientEventsFunction").bind(b.payload)())&&c.push(b);if(d&&1<=d.length)for(b=0;b<d.length;b++)if(a&&a.payload[d[b]]){var e=void 0;c.push((null==(e=a)?void 0:e.payload)[d[b]])}A("yt.logging.transport.scrapedPayloadsForTesting",c)}}
function Yt(){return P("use_request_time_ms_header")||P("lr_use_request_time_ms_header")}
function It(a,b){return P("transport_use_scheduler")?ro(a,b):nn(a,b)}
function Pt(a){P("transport_use_scheduler")?Hi.Ba(a):window.clearTimeout(a)}
function Tt(a){var b,c,d,e,f,g,h,l,m,n;return x(function(q){return 1==q.h?(d=null==(b=a)?void 0:null==(c=b.responseContext)?void 0:c.globalConfigGroup,e=ot(d,Nk),g=null==(f=d)?void 0:f.hotHashData,h=ot(d,Mk),m=null==(l=d)?void 0:l.coldHashData,(n=jt().resolve(new dt(lq)))?g?e?w(q,mq(n,g,e),2):w(q,mq(n,g),2):q.A(2):q.return()):m?h?w(q,nq(n,m,h),0):w(q,nq(n,m),0):q.A(0)})}
;var $t=y.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",$t);
function au(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||T());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;P("enable_unknown_lact_fix_on_html5")&&Os();a=Rs();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};P("log_sequence_info_on_gel_web")&&d.sequenceGroup&&(a=e.context,b=d.sequenceGroup,b={index:bu(b),groupKey:b},a.sequence=b,d.endOfSequence&&delete $t[d.sequenceGroup]);(d.sendIsolatedPayload?Lt:Dt)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,
dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},c)}
function cu(a){Jt(void 0,void 0,void 0===a?!1:a)}
function bu(a){$t[a]=a in $t?$t[a]+1:0;return $t[a]}
;var du=[];function Fo(a,b,c){c=void 0===c?{}:c;var d=Bs;O("ytLoggingEventsDefaultDisabled",!1)&&Bs===Bs&&(d=null);P("web_all_payloads_via_jspb")?(c.timestamp||(c.timestamp=T()),du.push({Mc:a,payload:b,options:c})):au(a,b,d,c)}
;var eu=y.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",eu);
function fu(a,b,c){c=void 0===c?{}:c;var d=Math.round(c.timestamp||T());G(a,1,d<Number.MAX_SAFE_INTEGER?d:0);var e=Rs();d=new rm;G(d,1,c.timestamp||!isFinite(e)?-1:e);if(P("log_sequence_info_on_gel_web")&&c.sequenceGroup){e=c.sequenceGroup;var f=bu(e),g=new qm;G(g,2,f);G(g,1,e);H(d,qm,3,g);c.endOfSequence&&delete eu[c.sequenceGroup]}H(a,rm,33,d);(c.sendIsolatedPayload?Nt:Ht)({endpoint:"log_event",payload:a,cttAuthInfo:c.cttAuthInfo,dangerousLogToVisitorSession:c.dangerousLogToVisitorSession},b)}
;function gu(a,b){b=void 0===b?{}:b;var c=!1;O("ytLoggingEventsDefaultDisabled",!1)&&(c=!0);fu(a,c?null:Bs,b)}
;function hu(a,b,c){var d=new sm;le(d,fm,72,tm,a);c?fu(d,c,b):gu(d,b)}
function iu(a,b,c){var d=new sm;le(d,em,73,tm,a);c?fu(d,c,b):gu(d,b)}
function ju(a,b,c){var d=new sm;le(d,dm,78,tm,a);c?fu(d,c,b):gu(d,b)}
function ku(a,b,c){var d=new sm;le(d,gm,208,tm,a);c?fu(d,c,b):gu(d,b)}
function lu(a,b,c){var d=new sm;le(d,Zl,156,tm,a);c?fu(d,c,b):gu(d,b)}
function mu(a,b,c){var d=new sm;le(d,am,215,tm,a);c?fu(d,c,b):gu(d,b)}
;var nu=new Set,ou=0,pu=0,qu=0,ru=[],su=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function Eo(a){tu(a)}
function uu(a){tu(a,"WARNING")}
function tu(a,b,c,d,e,f,g){f=void 0===f?{}:f;f.name=c||O("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||O("INNERTUBE_CONTEXT_CLIENT_VERSION");var h=f,l=void 0===b?"ERROR":b,m=void 0===g?!1:g;l=void 0===l?"ERROR":l;m=void 0===m?!1:m;if(a){a.hasOwnProperty("level")&&a.level&&(l=a.level);if(P("console_log_js_exceptions")){var n=[];n.push("Name: "+a.name);n.push("Message: "+a.message);a.hasOwnProperty("params")&&n.push("Error Params: "+JSON.stringify(a.params));a.hasOwnProperty("args")&&n.push("Error args: "+
JSON.stringify(a.args));n.push("File name: "+a.fileName);n.push("Stacktrace: "+a.stack);window.console.log(n.join("\n"),a)}if(!(5<=ou)){var q=ru,u=Pe(a),t=u.message||"Unknown Error",z=u.name||"UnknownError",C=u.stack||a.i||"Not available";if(C.startsWith(z+": "+t)){var E=C.split("\n");E.shift();C=E.join("\n")}var M=u.lineNumber||"Not available",S=u.fileName||"Not available",Q=C,W=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var fa=0;fa<a.args.length&&!(W=Nn(a.args[fa],"params."+fa,h,W),
500<=W);fa++);else if(a.hasOwnProperty("params")&&a.params){var ma=a.params;if("object"===typeof a.params)for(var Ra in ma){if(ma[Ra]){var Da="params."+Ra,za=Pn(ma[Ra]);h[Da]=za;W+=Da.length+za.length;if(500<W)break}}else h.params=Pn(ma)}if(q.length)for(var na=0;na<q.length&&!(W=Nn(q[na],"params.context."+na,h,W),500<=W);na++);navigator.vendor&&!h.hasOwnProperty("vendor")&&(h["device.vendor"]=navigator.vendor);var J={message:t,name:z,lineNumber:M,fileName:S,stack:Q,params:h,sampleWeight:1},Pc=Number(a.columnNumber);
isNaN(Pc)||(J.lineNumber=J.lineNumber+":"+Pc);if("IGNORED"===a.level)var Qc=0;else a:{for(var gf=Jn(),hf=r(gf.Ta),ha=hf.next();!ha.done;ha=hf.next()){var Fh=ha.value;if(J.message&&J.message.match(Fh.Dg)){Qc=Fh.weight;break a}}for(var Gh=r(gf.Pa),ol=Gh.next();!ol.done;ol=Gh.next()){var vr=ol.value;if(vr.callback(J)){Qc=vr.weight;break a}}Qc=1}J.sampleWeight=Qc;for(var wr=r(En),pl=wr.next();!pl.done;pl=wr.next()){var ql=pl.value;if(ql.lc[J.name])for(var xr=r(ql.lc[J.name]),rl=xr.next();!rl.done;rl=
xr.next()){var yr=rl.value,Hh=J.message.match(yr.regexp);if(Hh){J.params["params.error.original"]=Hh[0];for(var sl=yr.groups,zr={},Od=0;Od<sl.length;Od++)zr[sl[Od]]=Hh[Od+1],J.params["params.error."+sl[Od]]=Hh[Od+1];J.message=ql.Ic(zr);break}}}J.params||(J.params={});var Ar=Jn();J.params["params.errorServiceSignature"]="msg="+Ar.Ta.length+"&cb="+Ar.Pa.length;J.params["params.serviceWorker"]="false";y.document&&y.document.querySelectorAll&&(J.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));
Cb("sample").constructor!==Ab&&(J.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(J);if(0!==J.sampleWeight&&!nu.has(J.message)){if(m&&P("web_enable_error_204"))vu(void 0===l?"ERROR":l,J);else{var Rc=l;Rc=void 0===Rc?"ERROR":Rc;if("ERROR"===Rc){Kn.cb("handleError",J);if(P("record_app_crashed_web")&&0===qu&&1===J.sampleWeight)if(qu++,P("errors_via_jspb")){var sy=new Ql;var Cr=G(sy,1,1);if(!P("report_client_error_with_app_crash_ks")){var ty=new Ol,uy=new Nl,
vy=new Ml,wy=new Ll;var xy=G(wy,1,J.message);var yy=H(vy,Ll,3,xy);var zy=H(uy,Ml,5,yy);var Ay=H(ty,Nl,9,zy);H(Cr,Ol,4,Ay)}var Dr=new sm;le(Dr,Ql,20,tm,Cr);gu(Dr)}else{var Er={appCrashType:"APP_CRASH_TYPE_BREAKPAD"};P("report_client_error_with_app_crash_ks")||(Er.systemHealth={crashData:{clientError:{logMessage:{message:J.message}}}});Fo("appCrashed",Er)}pu++}else"WARNING"===Rc&&Kn.cb("handleWarning",J);if(P("kevlar_gel_error_routing"))a:{var jf=Rc;if(P("errors_via_jspb")){if(wu())var Gr=void 0;else{var Pd=
new Il;G(Pd,1,J.stack);J.fileName&&G(Pd,4,J.fileName);var Sb=J.lineNumber&&J.lineNumber.split?J.lineNumber.split(":"):[];0!==Sb.length&&(1!==Sb.length||isNaN(Number(Sb[0]))?2!==Sb.length||isNaN(Number(Sb[0]))||isNaN(Number(Sb[1]))||(oe(Pd,2,Number(Sb[0])),oe(Pd,3,Number(Sb[1]))):oe(Pd,2,Number(Sb[0])));var Sc=new Ll;G(Sc,1,J.message);G(Sc,3,J.name);oe(Sc,6,J.sampleWeight);"ERROR"===jf?G(Sc,2,2):"WARNING"===jf?G(Sc,2,1):G(Sc,2,0);var tl=new Jl;G(tl,1,!0);le(tl,Il,3,Kl,Pd);var pc=new Gl;G(pc,3,window.location.href);
for(var Hr=O("FEXP_EXPERIMENTS",[]),ul=0;ul<Hr.length;ul++){var By=Hr[ul];Ud(pc);fe(pc,5,2,!1,!1).push(By)}var vl=O("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Om()&&vl)for(var Ir=r(Object.keys(vl)),Tc=Ir.next();!Tc.done;Tc=Ir.next()){var Jr=Tc.value,wl=new Fl;G(wl,1,Jr);G(wl,2,String(vl[Jr]));ne(pc,4,Fl,wl)}var xl=J.params;if(xl){var Kr=r(Object.keys(xl));for(Tc=Kr.next();!Tc.done;Tc=Kr.next()){var Lr=Tc.value,yl=new Fl;G(yl,1,"client."+Lr);G(yl,2,String(xl[Lr]));ne(pc,4,Fl,yl)}}var Mr=O("SERVER_NAME"),
Nr=O("SERVER_VERSION");if(Mr&&Nr){var zl=new Fl;G(zl,1,"server.name");G(zl,2,Mr);ne(pc,4,Fl,zl);var Al=new Fl;G(Al,1,"server.version");G(Al,2,Nr);ne(pc,4,Fl,Al)}var Ih=new Ml;H(Ih,Gl,1,pc);H(Ih,Jl,2,tl);H(Ih,Ll,3,Sc);Gr=Ih}var Or=Gr;if(!Or)break a;var Pr=new sm;le(Pr,Ml,163,tm,Or);gu(Pr)}else{if(wu())var Qr=void 0;else{var kf={stackTrace:J.stack};J.fileName&&(kf.filename=J.fileName);var Tb=J.lineNumber&&J.lineNumber.split?J.lineNumber.split(":"):[];0!==Tb.length&&(1!==Tb.length||isNaN(Number(Tb[0]))?
2!==Tb.length||isNaN(Number(Tb[0]))||isNaN(Number(Tb[1]))||(kf.lineNumber=Number(Tb[0]),kf.columnNumber=Number(Tb[1])):kf.lineNumber=Number(Tb[0]));var Bl={level:"ERROR_LEVEL_UNKNOWN",message:J.message,errorClassName:J.name,sampleWeight:J.sampleWeight};"ERROR"===jf?Bl.level="ERROR_LEVEL_ERROR":"WARNING"===jf&&(Bl.level="ERROR_LEVEL_WARNNING");var Cy={isObfuscated:!0,browserStackInfo:kf},Qd={pageUrl:window.location.href,kvPairs:[]};O("FEXP_EXPERIMENTS")&&(Qd.experimentIds=O("FEXP_EXPERIMENTS"));var Cl=
O("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Om()&&Cl)for(var Rr=r(Object.keys(Cl)),Uc=Rr.next();!Uc.done;Uc=Rr.next()){var Sr=Uc.value;Qd.kvPairs.push({key:Sr,value:String(Cl[Sr])})}var Dl=J.params;if(Dl){var Tr=r(Object.keys(Dl));for(Uc=Tr.next();!Uc.done;Uc=Tr.next()){var Ur=Uc.value;Qd.kvPairs.push({key:"client."+Ur,value:String(Dl[Ur])})}}var Vr=O("SERVER_NAME"),Wr=O("SERVER_VERSION");Vr&&Wr&&(Qd.kvPairs.push({key:"server.name",value:Vr}),Qd.kvPairs.push({key:"server.version",value:Wr}));
Qr={errorMetadata:Qd,stackTrace:Cy,logMessage:Bl}}var Xr=Qr;if(!Xr)break a;Fo("clientError",Xr)}if("ERROR"===jf||P("errors_flush_gel_always_killswitch"))b:{if(P("web_fp_via_jspb")&&(cu(!0),!P("web_fp_via_jspb_and_json")))break b;cu()}}P("suppress_error_204_logging")||vu(Rc,J)}try{nu.add(J.message)}catch(oA){}ou++}}}}
function wu(){for(var a=r(su),b=a.next();!b.done;b=a.next())if(Dn(b.value.toLowerCase()))return!0;return!1}
function vu(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:O("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=r(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=O("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=r(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];c=O("SERVER_NAME");b=O("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}tn(O("ECATCHER_REPORT_HOST","")+"/error_204",a)}
function xu(a){var b=La.apply(1,arguments);a.args||(a.args=[]);a.args.push.apply(a.args,ja(b))}
;function yu(){this.register=new Map}
function zu(a){a=r(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Ig("ABORTED")}
yu.prototype.clear=function(){zu(this);this.register.clear()};
var Au=new yu;var Bu=Date.now().toString();function Cu(){for(var a=Array(16),b=0;16>b;b++){for(var c=Date.now(),d=0;d<c%23;d++)a[b]=Math.random();a[b]=Math.floor(256*Math.random())}if(Bu)for(b=1,c=0;c<Bu.length;c++)a[b%16]=a[b%16]^a[(b-1)%16]/4^Bu.charCodeAt(c),b++;return a}
function Du(){if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];return a}catch(d){}return Cu()}
function Eu(){for(var a=Du(),b=[],c=0;c<a.length;c++)b.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(a[c]&63));return b.join("")}
;var Fu=y.ytLoggingDocDocumentNonce_;Fu||(Fu=Eu(),A("ytLoggingDocDocumentNonce_",Fu));var Gu=Fu;var Hu={Cf:0,Af:1,Bf:2,dg:3,Df:4,ig:5,eg:6,hg:7,fg:8,gg:9,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE",8:"PUSH_NOTIFICATIONS",9:"RICH_GRID_WATCH"};function Iu(a){this.h=a}
function Ju(a){return new Iu({trackingParams:a})}
Iu.prototype.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
Iu.prototype.getAsJspb=function(){var a=new Sl;if(void 0!==this.h.trackingParams){var b=this.h.trackingParams;if(null!=b)if("string"===typeof b)b=b?new Ed(b,Bd):Cd||(Cd=new Ed(null,Bd));else if(b.constructor!==Ed)if(Ad(b))b instanceof Uint8Array||Array.isArray(b),b=b.length?new Ed(new Uint8Array(b),Bd):Cd||(Cd=new Ed(null,Bd));else throw Error();G(a,1,b)}else void 0!==this.h.veType&&oe(a,2,this.h.veType),void 0!==this.h.veCounter&&oe(a,6,this.h.veCounter),void 0!==this.h.elementIndex&&oe(a,3,this.h.elementIndex),
this.h.isCounterfactual&&G(a,5,!0);void 0!==this.h.dataElement&&(b=this.h.dataElement.getAsJspb(),H(a,Sl,7,b));void 0!==this.h.youtubeData&&H(a,Sk,8,this.h.jspbYoutubeData);return a};
Iu.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
Iu.prototype.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};function Ku(a){a=void 0===a?0:a;return 0===a?"client-screen-nonce":"client-screen-nonce."+a}
function Lu(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Mu(a){return O(Lu(void 0===a?0:a))}
A("yt_logging_screen.getRootVeType",Mu);function Nu(a){return(a=Mu(void 0===a?0:a))?new Iu({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null}
function Ou(){var a=O("csn-to-ctt-auth-info");a||(a={},Nm("csn-to-ctt-auth-info",a));return a}
function Pu(a){a=O(Ku(void 0===a?0:a));if(!a&&!O("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
A("yt_logging_screen.getCurrentCsn",Pu);function Qu(a){for(var b=r(Object.values(Hu)),c=b.next();!c.done;c=b.next())if(Pu(c.value)===a)return!0;return!1}
function Ru(a,b,c){var d=Ou();(c=Pu(c))&&delete d[c];b&&(d[a]=b)}
function Su(a){return Ou()[a]}
A("yt_logging_screen.getCttAuthInfo",Su);function Tu(a,b,c,d){c=void 0===c?0:c;if(a!==O(Ku(c))||b!==O(Lu(c)))if(Ru(a,d,c),Nm(Ku(c),a),Nm(Lu(c),b),b=function(){setTimeout(function(){if(a)if(P("web_time_via_jspb")){var e=new Tl;G(e,1,Gu);G(e,2,a);var f=new sm;le(f,Tl,111,tm,e);gu(f)}else Fo("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:Gu,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()}
A("yt_logging_screen.setCurrentScreen",Tu);var Uu=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};A("yt.msgs_",Uu);function Vu(a){Im(Uu,arguments)}
;var Wu=[3611,27686,85013,23462,157557,42016,26926,51236,79148,50160,77504,153587,87907,18630,177018,177023,54445,80935,152172,105675,150723,37521,147285,47786,98349,168271,168954,168277,168273,168270,123695,6827,29434,171388,7282,124448,32276,76278,147868,147869,93911,106531,27259,27262,27263,21759,160866,177957,171243,160789,171244,171241,171245,171242,177958,177565,175492,175493,175494,175495,175496,175497,38408,175498,175503,175504,175505,175506,175507,175508,80637,68727,68728,80353,80356,74610,
45707,83962,83970,46713,166591,89711,74612,155792,93265,74611,131380,128979,139311,128978,131391,105350,139312,134800,131392,113533,93252,99357,94521,114252,113532,94522,94583,88E3,139580,93253,93254,94387,94388,93255,97424,72502,110111,76019,117092,117093,89431,110466,77240,60508,148123,148124,137401,137402,137046,73393,113534,92098,131381,84517,83759,162711,162712,80357,86113,72598,168413,72733,107349,124275,118203,133275,160157,152569,156651,133274,160159,160158,133272,133273,133276,144507,143247,
175994,156652,143248,143249,143250,143251,156653,144401,117431,133797,153964,128572,133405,117429,117430,174734,117432,173996,173995,174953,173994,173997,120080,117259,156655,156654,121692,145656,156656,145655,145653,145654,145657,132972,133051,133658,132971,97615,143359,143356,143361,143358,143360,143357,142303,143353,172859,143354,144479,143355,31402,133624,146477,133623,133622,133621,84774,160801,95117,172721,150497,98930,98931,98932,153320,153321,43347,129889,149123,45474,100352,98443,117985,
74613,155911,74614,64502,136032,74615,74616,122224,74617,77820,74618,93278,93274,93275,93276,22110,29433,133798,132295,120541,82047,113550,75836,75837,42352,84512,76065,75989,51879,16623,32594,27240,32633,74858,156999,3945,16989,45520,25488,25492,25494,55760,14057,18451,57204,57203,17897,18198,17898,17909,43980,46220,11721,147994,49954,96369,3854,151633,56251,159108,25624,152036,16906,99999,68172,47973,72773,26970,26971,96805,17752,73233,109512,22256,14115,22696,89278,89277,109513,43278,43459,43464,
89279,43717,55764,22255,147912,89281,40963,43277,43442,91824,120137,96367,36850,72694,37414,36851,124863,121343,73491,54473,166861,43375,46674,143815,139095,144402,149968,149969,32473,72901,72906,50612,50613,50942,84938,84943,84939,84941,84944,84940,84942,35585,51926,79983,18921,57893,41182,135732,33424,22207,36229,22206,22205,44763,33427,67793,22182,37091,34650,50617,22287,25144,97917,62397,150871,150874,125598,137935,36961,108035,27426,27857,27846,27854,69692,61411,39299,38696,62520,36382,108701,
50663,36387,14908,37533,105443,61635,62274,161670,133818,65702,65703,65701,76256,166382,37671,49953,36216,28237,173718,39553,29222,26107,38050,26108,120745,26109,26110,66881,28236,14586,160598,57929,74723,44098,173689,44099,23528,61699,134104,134103,59149,173191,173192,173193,101951,171502,97346,118051,95102,64882,119505,63595,63349,95101,75240,27039,68823,21537,83464,75707,170215,83113,101952,101953,79610,125755,24402,24400,32925,57173,156421,122502,145268,138480,64423,64424,33986,100828,129089,
21409,135155,135156,135157,135158,158225,135159,135160,167651,135161,135162,135163,158226,158227,135164,135165,135166,11070,11074,17880,30709,30707,30711,30710,30708,146143,63648,63649,111059,5754,20445,151308,151152,130975,130976,167637,110386,113746,66557,17310,28631,21589,164817,168011,154946,68012,162617,60480,138664,141121,164502,31571,141978,150105,150106,150107,150108,76980,41577,45469,38669,13768,13777,141842,62985,4724,59369,43927,43928,12924,100355,56219,27669,10337,47896,122629,139723,
139722,121258,107598,127991,96639,107536,130169,96661,145188,96658,116646,159428,168611,168612,121122,96660,127738,127083,155281,162959,163566,147842,104443,96659,147595,106442,162776,134840,63667,63668,63669,130686,147036,78314,147799,174049,148649,55761,127098,134841,96368,67374,48992,146176,176105,49956,31961,26388,23811,5E4,126250,96370,47355,47356,37935,45521,21760,83769,49977,49974,93497,93498,34325,140759,115803,123707,100081,35309,68314,25602,100339,170873,143516,59018,18248,50625,9729,37168,
37169,21667,16749,18635,39305,18046,53969,8213,93926,102852,110099,22678,69076,137575,139224,100856,154430,17736,3832,147111,55759,64031,93044,93045,170701,170702,34388,167841,170419,17657,17655,39579,39578,170412,77448,8196,11357,69877,8197,168501,156512,161613,156509,161612,161614,82039];function Xu(){var a=ub(Yu),b;return(new Rf(function(c,d){a.onSuccess=function(e){mn(e)?c(new Zu(e)):d(new $u("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new $u("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new $u("Request timed out","net.timeout",e))};
b=tn("//googleads.g.doubleclick.net/pagead/id",a)})).sc(function(c){c instanceof Yf&&b.abort();
return Wf(c)})}
function $u(a,b,c){bb.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
v($u,bb);function Zu(a){this.xhr=a}
;function av(){this.i=0;this.h=null}
av.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.h))&&"function"===typeof a.then?a:bv(a):2===this.i&&b?(a=b.call(c,this.h))&&"function"===typeof a.then?a:cv(a):this};
av.prototype.getValue=function(){return this.h};
av.prototype.$goog_Thenable=!0;function cv(a){var b=new av;a=void 0===a?null:a;b.i=2;b.h=void 0===a?null:a;return b}
function bv(a){var b=new av;a=void 0===a?null:a;b.i=1;b.h=void 0===a?null:a;return b}
;function dv(a,b){var c=void 0===c?{}:c;a={method:void 0===b?"POST":b,mode:cn(a)?"same-origin":"cors",credentials:cn(a)?"same-origin":"include"};b={};for(var d=r(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);0<Object.keys(b).length&&(a.headers=b);return a}
;function ev(){return Rg()||(ld||md)&&Dn("applewebkit")&&!Dn("version")&&(!Dn("safari")||Dn("gsa/"))||bd&&Dn("version/")?!0:O("EOM_VISITOR_DATA")?!1:!0}
;function fv(a){a:{var b=a.raw_embedded_player_response;if(!b&&(a=a.embedded_player_response))try{b=JSON.parse(a)}catch(d){b="EMBEDDED_PLAYER_MODE_UNKNOWN";break a}if(b)b:{for(var c in ml)if(ml[c]==b.embeddedPlayerMode){b=ml[c];break b}b="EMBEDDED_PLAYER_MODE_UNKNOWN"}else b="EMBEDDED_PLAYER_MODE_UNKNOWN"}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function gv(a){bb.call(this,a.message||a.description||a.name);this.isMissing=a instanceof hv;this.isTimeout=a instanceof $u&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Yf}
v(gv,bb);gv.prototype.name="BiscottiError";function hv(){bb.call(this,"Biscotti ID is missing from server")}
v(hv,bb);hv.prototype.name="BiscottiMissingError";var Yu={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},iv=null;function jv(){if(P("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!ev())return Error("User has not consented - not fetching biscotti id.");var a=O("PLAYER_VARS",{});if("1"==sb(a))return Error("Biscotti ID is not available in private embed mode");if(fv(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Gm(){var a=jv();if(void 0!==a)return Wf(a);iv||(iv=Xu().then(kv).sc(function(b){return lv(2,b)}));
return iv}
function kv(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new hv;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new hv;a=a.id;Hm(a);iv=bv(a);mv(18E5,2);return a}
function lv(a,b){b=new gv(b);Hm("");iv=cv(b);0<a&&mv(12E4,a-1);throw b;}
function mv(a,b){nn(function(){Xu().then(kv,function(c){return lv(b,c)}).sc(db)},a)}
function nv(){try{var a=B("yt.ads.biscotti.getId_");return a?a():Gm()}catch(b){return Wf(b)}}
;function ov(a){if("1"!=sb(O("PLAYER_VARS",{}))){a&&Fm();try{nv().then(function(){},function(){}),nn(ov,18E5)}catch(b){Sm(b)}}}
;function pv(){var a=bo(),b=fo(119),c=1<window.devicePixelRatio;if(document.body&&Ri(document.body,"exp-invert-logo"))if(c&&!Ri(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Ri(d,"inverted-hdpi")){var e=Pi(d);Qi(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Ri(document.body,"inverted-hdpi")&&Si();if(b!=c){b="f"+(Math.floor(119/31)+1);d=go(b)||0;d=c?d|67108864:d&-67108865;0===d?delete Zn[b]:(c=d.toString(16),Zn[b]=c.toString());
c=!0;P("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(var f in Zn)Zn.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(Zn[f])));Wn(b,d.join("&"),63072E3,a.i,c)}}
;var qv=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function rv(){var a=void 0===a?window.location.href:a;if(P("kevlar_disable_theme_param"))return null;vc(wc(5,a));try{var b=an(a).theme;return qv.get(b)||null}catch(c){}return null}
;function sv(){this.h={};if(this.i=Yn()){var a=Pg.get("CONSISTENCY",void 0);a&&tv(this,{encryptedTokenJarContents:a})}}
sv.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.Ka.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=r(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];tv(this,a)}};
function tv(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},1E3*c);
a.i&&Wn("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var uv=window.location.hostname.split(".").slice(-2).join(".");function vv(){var a=O("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===O("INNERTUBE_CLIENT_NAME")&&(this.h=wv(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var xv;function yv(){xv=B("yt.clientLocationService.instance");xv||(xv=new vv,A("yt.clientLocationService.instance",xv));return xv}
k=vv.prototype;k.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.i?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.i.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.i.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
k.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.i=void 0,"TVHTML5"===O("INNERTUBE_CLIENT_NAME")?(this.h=wv(this))&&this.h.set("yt-location-playability-token",a,15552E3):Wn("YT_CL",JSON.stringify({loctok:a}),15552E3,uv,!0))};
function wv(a){return void 0===a.h?new wo("yt-client-location"):a.h}
k.clearLocationPlayabilityToken=function(a){"TVHTML5"===a?(this.h=wv(this))&&this.h.remove("yt-location-playability-token"):Xn("YT_CL")};
k.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;"MWEB"===O("INNERTUBE_CLIENT_NAME")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
k.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};function zv(a,b){var c,d=null==(c=ot(a,ll))?void 0:c.signal;if(d&&b.Qb&&(c=b.Qb[d]))return c();var e;if((c=null==(e=ot(a,jl))?void 0:e.request)&&b.ie&&(e=b.ie[c]))return e();for(var f in a)if(b.hd[f]&&(a=b.hd[f]))return a()}
;function Av(a){return function(){return new a}}
;var Bv={},Cv=(Bv.WEB_UNPLUGGED="^unplugged/",Bv.WEB_UNPLUGGED_ONBOARDING="^unplugged/",Bv.WEB_UNPLUGGED_OPS="^unplugged/",Bv.WEB_UNPLUGGED_PUBLIC="^unplugged/",Bv.WEB_CREATOR="^creator/",Bv.WEB_KIDS="^kids/",Bv.WEB_EXPERIMENTS="^experiments/",Bv.WEB_MUSIC="^music/",Bv.WEB_REMIX="^music/",Bv.WEB_MUSIC_EMBEDDED_PLAYER="^music/",Bv.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",Bv);
function Dv(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=Cv[b];if(c){var d=new RegExp(c),e=r(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(Cv).forEach(function(g){var h=r(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=r(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function Ev(){}
Ev.prototype.m=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?Tn:c;var d=a.clickTrackingParams,e=this.l,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=O("INNERTUBE_CONTEXT");if(g){g=vb(g);P("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=O("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var l=void 0===l?!1:l;bo();var m="USER_INTERFACE_THEME_LIGHT";fo(165)?m="USER_INTERFACE_THEME_DARK":fo(174)?m="USER_INTERFACE_THEME_LIGHT":!P("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(m="USER_INTERFACE_THEME_DARK");l=l?m:rv()||m;h.userInterfaceTheme=l;if(!f){if(l=mo())h.connectionType=
l;P("web_log_effective_connection_type")&&(l=no())&&(g.client.effectiveConnectionType=l)}var n;if(P("web_log_memory_total_kbytes")&&(null==(n=y.navigator)?0:n.deviceMemory)){var q;n=null==(q=y.navigator)?void 0:q.deviceMemory;g.client.memoryTotalKbytes=""+1E6*n}q=an(y.location.href);!P("web_populate_internal_geo_killswitch")&&q.internalcountrycode&&(h.internalGeo=q.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:y.location.href},P("kevlar_woffle")&&Un.h&&
(q=Un.h,h.mainAppWebInfo.pwaInstallabilityStatus=!q.h&&q.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=Vn(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):"TVHTML5"===h.clientName&&(!P("web_lr_app_quality_killswitch")&&(q=O("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:q})),q=O("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{certificationScope:q}));
if(!P("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var u=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(ma){}u=void 0}u&&(h.timeZone=u)}(u=hn())?h.experimentsToken=u:delete h.experimentsToken;u=jn();sv.h||(sv.h=new sv);h=sv.h.h;q=[];n=0;for(var t in h)q[n++]=h[t];g.request=Object.assign({},g.request,{internalExperimentFlags:u,consistencyTokenJars:q});!P("web_prequest_context_killswitch")&&(t=O("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(g.request.externalPrequestContext=
t);u=bo();t=fo(58);u=u.get("gsml","");g.user=Object.assign({},g.user);t&&(g.user.enableSafetyMode=t);u&&(g.user.lockedSafetyMode=!0);P("warm_op_csn_cleanup")?e&&(f=Pu())&&(g.clientScreenNonce=f):!f&&(f=Pu())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=B("yt.mdx.remote.remoteClient_"))g.remoteClient=d;yv().setLocationOnInnerTubeContext(g);try{var z=dn(),C=z.bid;delete z.bid;g.adSignalsInfo={params:[],bid:C};var E=r(Object.entries(z));for(var M=E.next();!M.done;M=E.next()){var S=
r(M.value),Q=S.next().value,W=S.next().value;z=Q;C=W;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:z,value:""+C})}}catch(ma){tu(ma)}E=g}else tu(Error("Error: No InnerTubeContext shell provided in ytconfig.")),E={};E={context:E};if(M=this.h(a)){this.i(E,M,b);var fa;b="/youtubei/v1/"+Dv(this.j());(M=null==(fa=ot(a.commandMetadata,kl))?void 0:fa.apiUrl)&&(b=M);fa=b;(b=O("INNERTUBE_HOST_OVERRIDE"))&&(fa=String(b)+String(yc(fa)));b={};b.key=O("INNERTUBE_API_KEY");P("json_condensed_response")&&
(b.prettyPrint="false");fa=bn(fa,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:fa,kb:dv(fa),Ka:E,config:a};a.config.Yb?a.config.Yb.identity=c:a.config.Yb={identity:c};return a}tu(new R("Error: Failed to create Request from Command.",a))};
da.Object.defineProperties(Ev.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});function Fv(){}
v(Fv,Ev);Fv.prototype.m=function(){return{input:"/getDatasyncIdsEndpoint",kb:dv("/getDatasyncIdsEndpoint","GET"),Ka:{}}};
Fv.prototype.j=function(){return[]};
Fv.prototype.h=function(){};
Fv.prototype.i=function(){};var Gv={},Hv=(Gv.GET_DATASYNC_IDS=Av(Fv),Gv);function Iv(a){var b=La.apply(1,arguments);if(!Jv(a)||b.some(function(d){return!Jv(d)}))throw Error("Only objects may be merged.");
b=r(b);for(var c=b.next();!c.done;c=b.next())Kv(a,c.value);return a}
function Kv(a,b){for(var c in b)if(Jv(b[c])){if(c in a&&!Jv(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Kv(a[c],b[c])}else if(Lv(b[c])){if(c in a&&!Lv(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);Mv(a[c],b[c])}else a[c]=b[c];return a}
function Mv(a,b){b=r(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Jv(c)?a.push(Kv({},c)):Lv(c)?a.push(Mv([],c)):a.push(c);return a}
function Jv(a){return"object"===typeof a&&!Array.isArray(a)}
function Lv(a){return"object"===typeof a&&Array.isArray(a)}
;function Nv(a){var b;(b=B("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},A("ytcsi."+(a||"")+"data_",b));return b}
function Ov(){var a=Nv();a.info||(a.info={});return a.info}
function Pv(a){a=Nv(a);a.metadata||(a.metadata={});return a.metadata}
function Qv(a){a=Nv(a);a.tick||(a.tick={});return a.tick}
function Rv(a){a=Nv(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function Sv(a){a=Rv(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function Tv(a){var b=Nv(a).nonce;b||(b=Eu(),Nv(a).nonce=b);return b}
;function Uv(){var a=B("ytcsi.debug");a||(a=[],A("ytcsi.debug",a),A("ytcsi.reference",{}));return a}
function Vv(a){a=a||"";var b=B("ytcsi.reference");b||(Uv(),b=B("ytcsi.reference"));if(b[a])return b[a];var c=Uv(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var U={},Wv=(U.auto_search="LATENCY_ACTION_AUTO_SEARCH",U.ad_to_ad="LATENCY_ACTION_AD_TO_AD",U.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",U["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",U.app_startup="LATENCY_ACTION_APP_STARTUP",U["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",U["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",U["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",U["asset.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS",
U["asset.composition"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION",U["asset.embeds"]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS",U["asset.issues"]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES",U["asset.licenses"]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES",U["asset.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA",U["asset.ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP",U["asset.policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY",U["asset.references"]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES",
U["asset.sound_recordings"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS",U["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",U.browse="LATENCY_ACTION_BROWSE",U.cast_splash="LATENCY_ACTION_CAST_SPLASH",U.channels="LATENCY_ACTION_CHANNELS",U.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",U["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",U["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",U["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",
U["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",U["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",U["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",U["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",U["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",U["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",U["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",U["channel.translations"]=
"LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",U["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",U["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",U.chips="LATENCY_ACTION_CHIPS",U["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",U["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",U["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",U.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",U.embed="LATENCY_ACTION_EMBED",
U.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",U.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",U.explore="LATENCY_ACTION_EXPLORE",U.home="LATENCY_ACTION_HOME",U.library="LATENCY_ACTION_LIBRARY",U.live="LATENCY_ACTION_LIVE",U.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",U.onboarding="LATENCY_ACTION_ONBOARDING",U.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",U["owner.allowlist"]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST",U["owner.analytics"]=
"LATENCY_ACTION_CREATOR_CMS_ANALYTICS",U["owner.art_tracks"]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS",U["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",U["owner.asset_groups"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS",U["owner.campaigns"]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS",U["owner.channels"]="LATENCY_ACTION_CREATOR_CMS_CHANNELS",U["owner.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",U["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",U["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",
U["owner.delivery"]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",U["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",U["owner.licenses"]="LATENCY_ACTION_CREATOR_CMS_LICENSES",U["owner.pitch_music"]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC",U["owner.policies"]="LATENCY_ACTION_CREATOR_CMS_POLICIES",U["owner.releases"]="LATENCY_ACTION_CREATOR_CMS_RELEASES",U["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",U["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",U.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",
U.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",U.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",U.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",U["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",U["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",U.prebuffer="LATENCY_ACTION_PREBUFFER",U.prefetch="LATENCY_ACTION_PREFETCH",U.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",U.profile_switcher="LATENCY_ACTION_LOGIN",U.reel_watch="LATENCY_ACTION_REEL_WATCH",
U.results="LATENCY_ACTION_RESULTS",U["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",U.search_ui="LATENCY_ACTION_SEARCH_UI",U.search_suggest="LATENCY_ACTION_SUGGEST",U.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",U.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",U.seek="LATENCY_ACTION_PLAYER_SEEK",U.settings="LATENCY_ACTION_SETTINGS",U.store="LATENCY_ACTION_STORE",U.tenx="LATENCY_ACTION_TENX",U.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",U.watch="LATENCY_ACTION_WATCH",U.watch_it_again=
"LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",U["watch,watch7"]="LATENCY_ACTION_WATCH",U["watch,watch7_html5"]="LATENCY_ACTION_WATCH",U["watch,watch7ad"]="LATENCY_ACTION_WATCH",U["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",U.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",U.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",U["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",U["video.claims"]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS",U["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",U["video.copyright"]=
"LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT",U["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",U["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",U["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",U["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",U["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",U["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",U["video.policy"]="LATENCY_ACTION_CREATOR_VIDEO_POLICY",U["video.rights_management"]=
"LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT",U["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",U.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",U.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",U.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",U.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",U),V={},Xv=(V.ad_allowed="adTypesAllowed",V.yt_abt="adBreakType",V.ad_cpn="adClientPlaybackNonce",V.ad_docid="adVideoId",V.yt_ad_an="adNetworks",
V.ad_at="adType",V.aida="appInstallDataAgeMs",V.browse_id="browseId",V.p="httpProtocol",V.t="transportProtocol",V.cs="commandSource",V.cpn="clientPlaybackNonce",V.ccs="creatorInfo.creatorCanaryState",V.ctop="creatorInfo.topEntityType",V.csn="clientScreenNonce",V.docid="videoId",V.GetHome_rid="requestIds",V.GetSearch_rid="requestIds",V.GetPlayer_rid="requestIds",V.GetWatchNext_rid="requestIds",V.GetBrowse_rid="requestIds",V.GetLibrary_rid="requestIds",V.is_continuation="isContinuation",V.is_nav="isNavigation",
V.b_p="kabukiInfo.browseParams",V.is_prefetch="kabukiInfo.isPrefetch",V.is_secondary_nav="kabukiInfo.isSecondaryNav",V.nav_type="kabukiInfo.navigationType",V.prev_browse_id="kabukiInfo.prevBrowseId",V.query_source="kabukiInfo.querySource",V.voz_type="kabukiInfo.vozType",V.yt_lt="loadType",V.mver="creatorInfo.measurementVersion",V.yt_ad="isMonetized",V.nr="webInfo.navigationReason",V.nrsu="navigationRequestedSameUrl",V.pnt="performanceNavigationTiming",V.prt="playbackRequiresTap",V.plt="playerInfo.playbackType",
V.pis="playerInfo.playerInitializedState",V.paused="playerInfo.isPausedOnLoad",V.yt_pt="playerType",V.fmt="playerInfo.itag",V.yt_pl="watchInfo.isPlaylist",V.yt_pre="playerInfo.preloadType",V.yt_ad_pr="prerollAllowed",V.pa="previousAction",V.yt_red="isRedSubscriber",V.rce="mwebInfo.responseContentEncoding",V.rc="resourceInfo.resourceCache",V.scrh="screenHeight",V.scrw="screenWidth",V.st="serverTimeMs",V.ssdm="shellStartupDurationMs",V.br_trs="tvInfo.bedrockTriggerState",V.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",
V.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",V.label="tvInfo.label",V.is_mdx="tvInfo.isMdx",V.preloaded="tvInfo.isPreloaded",V.aac_type="tvInfo.authAccessCredentialType",V.upg_player_vis="playerInfo.visibilityState",V.query="unpluggedInfo.query",V.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",V.yt_vst="videoStreamType",V.vph="viewportHeight",V.vpw="viewportWidth",V.yt_vis="isVisible",V.rcl="mwebInfo.responseContentLength",V.GetSettings_rid="requestIds",V.GetTrending_rid="requestIds",
V.GetMusicSearchSuggestions_rid="requestIds",V.REQUEST_ID="requestIds",V),Yv="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),Zv={},$v=(Zv.ccs="CANARY_STATE_",Zv.mver="MEASUREMENT_VERSION_",Zv.pis="PLAYER_INITIALIZED_STATE_",
Zv.yt_pt="LATENCY_PLAYER_",Zv.pa="LATENCY_ACTION_",Zv.ctop="TOP_ENTITY_TYPE_",Zv.yt_vst="VIDEO_STREAM_TYPE_",Zv),aw="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function bw(a){return Wv[a]||"LATENCY_ACTION_UNKNOWN"}
function cw(a,b,c){c=Rv(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in Xv){c=Xv[a];0<=fb(Yv,c)&&(b=!!b);a in $v&&"string"===typeof b&&(b=$v[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Iv({},d)}0<=fb(aw,a)||uu(new R("Unknown label logged with GEL CSI",a))}
;var X={LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING:179,LATENCY_ACTION_KIDS_PROFILE_SWITCHER:90,LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER:100,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC:46,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR:37,LATENCY_ACTION_SPINNER_DISPLAYED:14,LATENCY_ACTION_PLAYABILITY_CHECK:10,LATENCY_ACTION_PROCESS:9,LATENCY_ACTION_APP_STARTUP:5,LATENCY_ACTION_GEL_COMPRESSION:215,LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE:204,LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC:203,LATENCY_ACTION_COMMERCE_TRANSACTION:184,
LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC:173,LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC:172,LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC:171,LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC:170,LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC:169,LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC:168,LATENCY_ACTION_GET_OFFERS_RPC:167,LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC:166,LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC:165,LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC:164,LATENCY_ACTION_GET_OFFER_DETAILS_RPC:163,
LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC:162,LATENCY_ACTION_GET_TIP_MODULE_RPC:161,LATENCY_ACTION_HANDLE_TRANSACTION_RPC:160,LATENCY_ACTION_COMPLETE_TRANSACTION_RPC:159,LATENCY_ACTION_GET_CART_RPC:158,LATENCY_ACTION_THUMBNAIL_FETCH:156,LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK:154,LATENCY_ACTION_SHARE_VIDEO:153,LATENCY_ACTION_AD_TO_VIDEO_INT:152,LATENCY_ACTION_ABANDONED_BROWSE:151,LATENCY_ACTION_PLAYER_ROTATION:150,LATENCY_ACTION_GENERIC_WEB_VIEW:183,LATENCY_ACTION_SHOPPING_IN_APP:124,LATENCY_ACTION_PLAYER_ATTESTATION:121,
LATENCY_ACTION_PLAYER_SEEK:119,LATENCY_ACTION_SUPER_STICKER_BUY_FLOW:114,LATENCY_ACTION_DOWNLOADS_DATA_ACCESS:180,LATENCY_ACTION_BLOCKS_PERFORMANCE:148,LATENCY_ACTION_ASSISTANT_QUERY:138,LATENCY_ACTION_ASSISTANT_SETTINGS:137,LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF:129,LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF:128,LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE:127,LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION:123,LATENCY_ACTION_NETWORKLESS_PERFORMANCE:122,LATENCY_ACTION_DOWNLOADS_EXPANSION:133,LATENCY_ACTION_ENTITY_TRANSFORM:131,
LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER:96,LATENCY_ACTION_EMBEDS_SET_VIDEO:95,LATENCY_ACTION_SETTINGS:93,LATENCY_ACTION_ABANDONED_STARTUP:81,LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY:80,LATENCY_ACTION_MEDIA_BROWSER_SEARCH:79,LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE:78,LATENCY_ACTION_WHO_IS_WATCHING:77,LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH:76,LATENCY_ACTION_LITE_SWITCH_ACCOUNT:73,LATENCY_ACTION_ELEMENTS_PERFORMANCE:70,LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION:69,LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION:65,
LATENCY_ACTION_OFFLINE_STORE_START:61,LATENCY_ACTION_REEL_EDITOR:58,LATENCY_ACTION_CHANNEL_SUBSCRIBE:56,LATENCY_ACTION_CHANNEL_PREVIEW:55,LATENCY_ACTION_PREFETCH:52,LATENCY_ACTION_ABANDONED_WATCH:45,LATENCY_ACTION_LOAD_COMMENT_REPLIES:26,LATENCY_ACTION_LOAD_COMMENTS:25,LATENCY_ACTION_EDIT_COMMENT:24,LATENCY_ACTION_NEW_COMMENT:23,LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING:19,LATENCY_ACTION_EMBED:18,LATENCY_ACTION_MDX_LAUNCH:15,LATENCY_ACTION_RESOLVE_URL:13,LATENCY_ACTION_CAST_SPLASH:149,LATENCY_ACTION_MDX_CONNECT_TO_SESSION:190,
LATENCY_ACTION_MDX_STREAM_TRANSFER:178,LATENCY_ACTION_MDX_CAST:120,LATENCY_ACTION_MDX_COMMAND:12,LATENCY_ACTION_MOBILE_LIVE_NAV_MDE:231,LATENCY_ACTION_REEL_SELECT_SEGMENT:136,LATENCY_ACTION_ACCELERATED_EFFECTS:145,LATENCY_ACTION_SHORTS_LOAD_PROJECT:234,LATENCY_ACTION_SHORTS_TRIM_TO_EDITOR_TRANSCODING:229,LATENCY_ACTION_EDIT_AUDIO_GEN:182,LATENCY_ACTION_UPLOAD_AUDIO_MIXER:147,LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING:157,LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING:146,LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK:130,
LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD:125,LATENCY_ACTION_SHORTS_CAMERA_AUDIO_DOWNLOAD:240,LATENCY_ACTION_SHORTS_VIDEO_INGESTION:155,LATENCY_ACTION_SHORTS_GALLERY:107,LATENCY_ACTION_SHORTS_TRIM:105,LATENCY_ACTION_SHORTS_EDIT:104,LATENCY_ACTION_SHORTS_CAMERA:103,LATENCY_ACTION_NON_CREATION_MODES_GLOBAL_ENTRYPOINT:239,LATENCY_ACTION_CREATION_MODES_MODE_SWITCH:236,LATENCY_ACTION_CREATION_MODES_GLOBAL_ENTRYPOINT:235,LATENCY_ACTION_MEDIA_ENGINE_DISPLAY_FIRST_FRAME:242,LATENCY_ACTION_MEDIA_ENGINE_EXPORT:241,
LATENCY_ACTION_PRODUCER_IMPORT_LOCAL_MEDIA:233,LATENCY_ACTION_PRODUCER_EXPORT_PROJECT:193,LATENCY_ACTION_PRODUCER_EDITOR:192,LATENCY_ACTION_PARENT_TOOLS_DASHBOARD:102,LATENCY_ACTION_PARENT_TOOLS_COLLECTION:101,LATENCY_ACTION_MUSIC_OFFLINE_PLAYLIST_DETAIL:238,LATENCY_ACTION_MUSIC_OFFLINE_ALBUM_DETAIL:237,LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS:116,LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS:115,LATENCY_ACTION_MUSIC_ALBUM_DETAIL:72,LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL:71,LATENCY_ACTION_STORE:175,
LATENCY_ACTION_CHIPS:68,LATENCY_ACTION_SEARCH_ZERO_STATE:67,LATENCY_ACTION_LIVE_PAGINATION:117,LATENCY_ACTION_LIVE:20,LATENCY_ACTION_PREBUFFER:40,LATENCY_ACTION_TENX:39,LATENCY_ACTION_KIDS_PROFILE_SETTINGS:94,LATENCY_ACTION_KIDS_WATCH_IT_AGAIN:92,LATENCY_ACTION_KIDS_SECRET_CODE:91,LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS:89,LATENCY_ACTION_KIDS_ONBOARDING:88,LATENCY_ACTION_KIDS_VOICE_SEARCH:82,LATENCY_ACTION_KIDS_CURATED_COLLECTION:62,LATENCY_ACTION_KIDS_LIBRARY:53,LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS:38,
LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT:219,LATENCY_ACTION_CREATOR_VIDEO_POLICY:217,LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION:74,LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING:141,LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS:142,LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC:51,LATENCY_ACTION_CREATOR_VIDEO_EDITOR:50,LATENCY_ACTION_CREATOR_VIDEO_EDIT:36,LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT:218,LATENCY_ACTION_CREATOR_VIDEO_COMMENTS:34,LATENCY_ACTION_CREATOR_VIDEO_CLAIMS:216,LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS:33,
LATENCY_ACTION_CREATOR_SONG_ANALYTICS:176,LATENCY_ACTION_CREATOR_PROMOTION_LIST:186,LATENCY_ACTION_CREATOR_PROMOTION_EDIT:185,LATENCY_ACTION_CREATOR_POST_LIST:112,LATENCY_ACTION_CREATOR_POST_EDIT:110,LATENCY_ACTION_CREATOR_POST_COMMENTS:111,LATENCY_ACTION_CREATOR_LIVE_STREAMING:108,LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT:174,LATENCY_ACTION_CREATOR_DIALOG_UPLOADS:86,LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES:87,LATENCY_ACTION_CREATOR_CMS_VIDEOS:202,LATENCY_ACTION_CREATOR_CMS_REPORTS:201,
LATENCY_ACTION_CREATOR_CMS_RELEASES:226,LATENCY_ACTION_CREATOR_CMS_POLICIES:225,LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC:224,LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING:200,LATENCY_ACTION_CREATOR_CMS_LICENSES:223,LATENCY_ACTION_CREATOR_CMS_ISSUES:191,LATENCY_ACTION_CREATOR_CMS_DASHBOARD:199,LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY:198,LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS:197,LATENCY_ACTION_CREATOR_CMS_CHANNELS:196,LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS:222,LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS:214,
LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES:209,LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY:208,LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP:207,LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA:205,LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES:212,LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES:206,LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS:221,LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS:210,LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION:213,LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS:211,LATENCY_ACTION_CREATOR_CMS_ASSETS:195,
LATENCY_ACTION_CREATOR_CMS_ART_TRACKS:220,LATENCY_ACTION_CREATOR_CMS_ANALYTICS:194,LATENCY_ACTION_CREATOR_CMS_ALLOWLIST:227,LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS:32,LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS:48,LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS:139,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT:177,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC:99,LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION:43,LATENCY_ACTION_CREATOR_CHANNEL_EDITING:113,LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD:49,LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT:44,
LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS:66,LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS:31,LATENCY_ACTION_CREATOR_ARTIST_PROFILE:85,LATENCY_ACTION_CREATOR_ARTIST_CONCERTS:84,LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS:83,LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE:140,LATENCY_ACTION_EXPERIMENTAL_WATCH_UI:181,LATENCY_ACTION_FINE_SCRUBBING_THUMBNAILS:228,LATENCY_ACTION_STORYBOARD_THUMBNAILS:118,LATENCY_ACTION_SEARCH_THUMBNAILS:59,LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD:54,LATENCY_ACTION_VOICE_ASSISTANT:47,LATENCY_ACTION_SEARCH_UI:35,
LATENCY_ACTION_SUGGEST:30,LATENCY_ACTION_AUTO_SEARCH:126,LATENCY_ACTION_DOWNLOADS:98,LATENCY_ACTION_EXPLORE:75,LATENCY_ACTION_VIDEO_LIST:63,LATENCY_ACTION_HOME_RESUME:60,LATENCY_ACTION_SUBSCRIPTIONS_LIST:57,LATENCY_ACTION_THUMBNAIL_LOAD:42,LATENCY_ACTION_FIRST_THUMBNAIL_LOAD:29,LATENCY_ACTION_SUBSCRIPTIONS_FEED:109,LATENCY_ACTION_SUBSCRIPTIONS:28,LATENCY_ACTION_TRENDING:27,LATENCY_ACTION_LIBRARY:21,LATENCY_ACTION_VIDEO_THUMBNAIL:8,LATENCY_ACTION_SHOW_MORE:7,LATENCY_ACTION_VIDEO_PREVIEW:6,LATENCY_ACTION_AD_TO_AD:22,
LATENCY_ACTION_VIDEO_TO_AD:17,LATENCY_ACTION_AD_TO_VIDEO:16,LATENCY_ACTION_DIRECT_PLAYBACK:132,LATENCY_ACTION_PREBUFFER_VIDEO:144,LATENCY_ACTION_PREFETCH_VIDEO:143,LATENCY_ACTION_STARTUP:106,LATENCY_ACTION_INLINE_TO_WATCH:232,LATENCY_ACTION_MUSIC_IMMERSIVE_WATCH:230,LATENCY_ACTION_ONBOARDING:135,LATENCY_ACTION_LOGIN:97,LATENCY_ACTION_REEL_WATCH:41,LATENCY_ACTION_WATCH:3,LATENCY_ACTION_RESULTS:2,LATENCY_ACTION_CHANNELS:4,LATENCY_ACTION_HOME:1,LATENCY_ACTION_BROWSE:11,LATENCY_ACTION_USER_ACTION:189,
LATENCY_ACTION_INFRASTRUCTURE:188,LATENCY_ACTION_PAGE_NAVIGATION:187,LATENCY_ACTION_UNKNOWN:0};X[X.LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING";X[X.LATENCY_ACTION_KIDS_PROFILE_SWITCHER]="LATENCY_ACTION_KIDS_PROFILE_SWITCHER";X[X.LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER]="LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER";X[X.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC";
X[X.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR";X[X.LATENCY_ACTION_SPINNER_DISPLAYED]="LATENCY_ACTION_SPINNER_DISPLAYED";X[X.LATENCY_ACTION_PLAYABILITY_CHECK]="LATENCY_ACTION_PLAYABILITY_CHECK";X[X.LATENCY_ACTION_PROCESS]="LATENCY_ACTION_PROCESS";X[X.LATENCY_ACTION_APP_STARTUP]="LATENCY_ACTION_APP_STARTUP";X[X.LATENCY_ACTION_GEL_COMPRESSION]="LATENCY_ACTION_GEL_COMPRESSION";X[X.LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE]="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE";
X[X.LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC]="LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC";X[X.LATENCY_ACTION_COMMERCE_TRANSACTION]="LATENCY_ACTION_COMMERCE_TRANSACTION";X[X.LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC]="LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC";X[X.LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC]="LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC";X[X.LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC]="LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC";
X[X.LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC]="LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC";X[X.LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC]="LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC";X[X.LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC]="LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC";X[X.LATENCY_ACTION_GET_OFFERS_RPC]="LATENCY_ACTION_GET_OFFERS_RPC";X[X.LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC";X[X.LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC";
X[X.LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC]="LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC";X[X.LATENCY_ACTION_GET_OFFER_DETAILS_RPC]="LATENCY_ACTION_GET_OFFER_DETAILS_RPC";X[X.LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC]="LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC";X[X.LATENCY_ACTION_GET_TIP_MODULE_RPC]="LATENCY_ACTION_GET_TIP_MODULE_RPC";X[X.LATENCY_ACTION_HANDLE_TRANSACTION_RPC]="LATENCY_ACTION_HANDLE_TRANSACTION_RPC";
X[X.LATENCY_ACTION_COMPLETE_TRANSACTION_RPC]="LATENCY_ACTION_COMPLETE_TRANSACTION_RPC";X[X.LATENCY_ACTION_GET_CART_RPC]="LATENCY_ACTION_GET_CART_RPC";X[X.LATENCY_ACTION_THUMBNAIL_FETCH]="LATENCY_ACTION_THUMBNAIL_FETCH";X[X.LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK]="LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK";X[X.LATENCY_ACTION_SHARE_VIDEO]="LATENCY_ACTION_SHARE_VIDEO";X[X.LATENCY_ACTION_AD_TO_VIDEO_INT]="LATENCY_ACTION_AD_TO_VIDEO_INT";X[X.LATENCY_ACTION_ABANDONED_BROWSE]="LATENCY_ACTION_ABANDONED_BROWSE";
X[X.LATENCY_ACTION_PLAYER_ROTATION]="LATENCY_ACTION_PLAYER_ROTATION";X[X.LATENCY_ACTION_GENERIC_WEB_VIEW]="LATENCY_ACTION_GENERIC_WEB_VIEW";X[X.LATENCY_ACTION_SHOPPING_IN_APP]="LATENCY_ACTION_SHOPPING_IN_APP";X[X.LATENCY_ACTION_PLAYER_ATTESTATION]="LATENCY_ACTION_PLAYER_ATTESTATION";X[X.LATENCY_ACTION_PLAYER_SEEK]="LATENCY_ACTION_PLAYER_SEEK";X[X.LATENCY_ACTION_SUPER_STICKER_BUY_FLOW]="LATENCY_ACTION_SUPER_STICKER_BUY_FLOW";X[X.LATENCY_ACTION_DOWNLOADS_DATA_ACCESS]="LATENCY_ACTION_DOWNLOADS_DATA_ACCESS";
X[X.LATENCY_ACTION_BLOCKS_PERFORMANCE]="LATENCY_ACTION_BLOCKS_PERFORMANCE";X[X.LATENCY_ACTION_ASSISTANT_QUERY]="LATENCY_ACTION_ASSISTANT_QUERY";X[X.LATENCY_ACTION_ASSISTANT_SETTINGS]="LATENCY_ACTION_ASSISTANT_SETTINGS";X[X.LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF";X[X.LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF";X[X.LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE]="LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE";
X[X.LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION]="LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION";X[X.LATENCY_ACTION_NETWORKLESS_PERFORMANCE]="LATENCY_ACTION_NETWORKLESS_PERFORMANCE";X[X.LATENCY_ACTION_DOWNLOADS_EXPANSION]="LATENCY_ACTION_DOWNLOADS_EXPANSION";X[X.LATENCY_ACTION_ENTITY_TRANSFORM]="LATENCY_ACTION_ENTITY_TRANSFORM";X[X.LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER]="LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER";X[X.LATENCY_ACTION_EMBEDS_SET_VIDEO]="LATENCY_ACTION_EMBEDS_SET_VIDEO";
X[X.LATENCY_ACTION_SETTINGS]="LATENCY_ACTION_SETTINGS";X[X.LATENCY_ACTION_ABANDONED_STARTUP]="LATENCY_ACTION_ABANDONED_STARTUP";X[X.LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY]="LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY";X[X.LATENCY_ACTION_MEDIA_BROWSER_SEARCH]="LATENCY_ACTION_MEDIA_BROWSER_SEARCH";X[X.LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE]="LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE";X[X.LATENCY_ACTION_WHO_IS_WATCHING]="LATENCY_ACTION_WHO_IS_WATCHING";X[X.LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH]="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH";
X[X.LATENCY_ACTION_LITE_SWITCH_ACCOUNT]="LATENCY_ACTION_LITE_SWITCH_ACCOUNT";X[X.LATENCY_ACTION_ELEMENTS_PERFORMANCE]="LATENCY_ACTION_ELEMENTS_PERFORMANCE";X[X.LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION]="LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION";X[X.LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION]="LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION";X[X.LATENCY_ACTION_OFFLINE_STORE_START]="LATENCY_ACTION_OFFLINE_STORE_START";X[X.LATENCY_ACTION_REEL_EDITOR]="LATENCY_ACTION_REEL_EDITOR";
X[X.LATENCY_ACTION_CHANNEL_SUBSCRIBE]="LATENCY_ACTION_CHANNEL_SUBSCRIBE";X[X.LATENCY_ACTION_CHANNEL_PREVIEW]="LATENCY_ACTION_CHANNEL_PREVIEW";X[X.LATENCY_ACTION_PREFETCH]="LATENCY_ACTION_PREFETCH";X[X.LATENCY_ACTION_ABANDONED_WATCH]="LATENCY_ACTION_ABANDONED_WATCH";X[X.LATENCY_ACTION_LOAD_COMMENT_REPLIES]="LATENCY_ACTION_LOAD_COMMENT_REPLIES";X[X.LATENCY_ACTION_LOAD_COMMENTS]="LATENCY_ACTION_LOAD_COMMENTS";X[X.LATENCY_ACTION_EDIT_COMMENT]="LATENCY_ACTION_EDIT_COMMENT";
X[X.LATENCY_ACTION_NEW_COMMENT]="LATENCY_ACTION_NEW_COMMENT";X[X.LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING]="LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING";X[X.LATENCY_ACTION_EMBED]="LATENCY_ACTION_EMBED";X[X.LATENCY_ACTION_MDX_LAUNCH]="LATENCY_ACTION_MDX_LAUNCH";X[X.LATENCY_ACTION_RESOLVE_URL]="LATENCY_ACTION_RESOLVE_URL";X[X.LATENCY_ACTION_CAST_SPLASH]="LATENCY_ACTION_CAST_SPLASH";X[X.LATENCY_ACTION_MDX_CONNECT_TO_SESSION]="LATENCY_ACTION_MDX_CONNECT_TO_SESSION";
X[X.LATENCY_ACTION_MDX_STREAM_TRANSFER]="LATENCY_ACTION_MDX_STREAM_TRANSFER";X[X.LATENCY_ACTION_MDX_CAST]="LATENCY_ACTION_MDX_CAST";X[X.LATENCY_ACTION_MDX_COMMAND]="LATENCY_ACTION_MDX_COMMAND";X[X.LATENCY_ACTION_MOBILE_LIVE_NAV_MDE]="LATENCY_ACTION_MOBILE_LIVE_NAV_MDE";X[X.LATENCY_ACTION_REEL_SELECT_SEGMENT]="LATENCY_ACTION_REEL_SELECT_SEGMENT";X[X.LATENCY_ACTION_ACCELERATED_EFFECTS]="LATENCY_ACTION_ACCELERATED_EFFECTS";X[X.LATENCY_ACTION_SHORTS_LOAD_PROJECT]="LATENCY_ACTION_SHORTS_LOAD_PROJECT";
X[X.LATENCY_ACTION_SHORTS_TRIM_TO_EDITOR_TRANSCODING]="LATENCY_ACTION_SHORTS_TRIM_TO_EDITOR_TRANSCODING";X[X.LATENCY_ACTION_EDIT_AUDIO_GEN]="LATENCY_ACTION_EDIT_AUDIO_GEN";X[X.LATENCY_ACTION_UPLOAD_AUDIO_MIXER]="LATENCY_ACTION_UPLOAD_AUDIO_MIXER";X[X.LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING]="LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING";X[X.LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING]="LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING";X[X.LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK]="LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK";
X[X.LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD]="LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD";X[X.LATENCY_ACTION_SHORTS_CAMERA_AUDIO_DOWNLOAD]="LATENCY_ACTION_SHORTS_CAMERA_AUDIO_DOWNLOAD";X[X.LATENCY_ACTION_SHORTS_VIDEO_INGESTION]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION";X[X.LATENCY_ACTION_SHORTS_GALLERY]="LATENCY_ACTION_SHORTS_GALLERY";X[X.LATENCY_ACTION_SHORTS_TRIM]="LATENCY_ACTION_SHORTS_TRIM";X[X.LATENCY_ACTION_SHORTS_EDIT]="LATENCY_ACTION_SHORTS_EDIT";X[X.LATENCY_ACTION_SHORTS_CAMERA]="LATENCY_ACTION_SHORTS_CAMERA";
X[X.LATENCY_ACTION_NON_CREATION_MODES_GLOBAL_ENTRYPOINT]="LATENCY_ACTION_NON_CREATION_MODES_GLOBAL_ENTRYPOINT";X[X.LATENCY_ACTION_CREATION_MODES_MODE_SWITCH]="LATENCY_ACTION_CREATION_MODES_MODE_SWITCH";X[X.LATENCY_ACTION_CREATION_MODES_GLOBAL_ENTRYPOINT]="LATENCY_ACTION_CREATION_MODES_GLOBAL_ENTRYPOINT";X[X.LATENCY_ACTION_MEDIA_ENGINE_DISPLAY_FIRST_FRAME]="LATENCY_ACTION_MEDIA_ENGINE_DISPLAY_FIRST_FRAME";X[X.LATENCY_ACTION_MEDIA_ENGINE_EXPORT]="LATENCY_ACTION_MEDIA_ENGINE_EXPORT";
X[X.LATENCY_ACTION_PRODUCER_IMPORT_LOCAL_MEDIA]="LATENCY_ACTION_PRODUCER_IMPORT_LOCAL_MEDIA";X[X.LATENCY_ACTION_PRODUCER_EXPORT_PROJECT]="LATENCY_ACTION_PRODUCER_EXPORT_PROJECT";X[X.LATENCY_ACTION_PRODUCER_EDITOR]="LATENCY_ACTION_PRODUCER_EDITOR";X[X.LATENCY_ACTION_PARENT_TOOLS_DASHBOARD]="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD";X[X.LATENCY_ACTION_PARENT_TOOLS_COLLECTION]="LATENCY_ACTION_PARENT_TOOLS_COLLECTION";X[X.LATENCY_ACTION_MUSIC_OFFLINE_PLAYLIST_DETAIL]="LATENCY_ACTION_MUSIC_OFFLINE_PLAYLIST_DETAIL";
X[X.LATENCY_ACTION_MUSIC_OFFLINE_ALBUM_DETAIL]="LATENCY_ACTION_MUSIC_OFFLINE_ALBUM_DETAIL";X[X.LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS";X[X.LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS";X[X.LATENCY_ACTION_MUSIC_ALBUM_DETAIL]="LATENCY_ACTION_MUSIC_ALBUM_DETAIL";X[X.LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL]="LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL";X[X.LATENCY_ACTION_STORE]="LATENCY_ACTION_STORE";
X[X.LATENCY_ACTION_CHIPS]="LATENCY_ACTION_CHIPS";X[X.LATENCY_ACTION_SEARCH_ZERO_STATE]="LATENCY_ACTION_SEARCH_ZERO_STATE";X[X.LATENCY_ACTION_LIVE_PAGINATION]="LATENCY_ACTION_LIVE_PAGINATION";X[X.LATENCY_ACTION_LIVE]="LATENCY_ACTION_LIVE";X[X.LATENCY_ACTION_PREBUFFER]="LATENCY_ACTION_PREBUFFER";X[X.LATENCY_ACTION_TENX]="LATENCY_ACTION_TENX";X[X.LATENCY_ACTION_KIDS_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PROFILE_SETTINGS";X[X.LATENCY_ACTION_KIDS_WATCH_IT_AGAIN]="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN";
X[X.LATENCY_ACTION_KIDS_SECRET_CODE]="LATENCY_ACTION_KIDS_SECRET_CODE";X[X.LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS";X[X.LATENCY_ACTION_KIDS_ONBOARDING]="LATENCY_ACTION_KIDS_ONBOARDING";X[X.LATENCY_ACTION_KIDS_VOICE_SEARCH]="LATENCY_ACTION_KIDS_VOICE_SEARCH";X[X.LATENCY_ACTION_KIDS_CURATED_COLLECTION]="LATENCY_ACTION_KIDS_CURATED_COLLECTION";X[X.LATENCY_ACTION_KIDS_LIBRARY]="LATENCY_ACTION_KIDS_LIBRARY";
X[X.LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS";X[X.LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT";X[X.LATENCY_ACTION_CREATOR_VIDEO_POLICY]="LATENCY_ACTION_CREATOR_VIDEO_POLICY";X[X.LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION";X[X.LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING";
X[X.LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS";X[X.LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC";X[X.LATENCY_ACTION_CREATOR_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR";X[X.LATENCY_ACTION_CREATOR_VIDEO_EDIT]="LATENCY_ACTION_CREATOR_VIDEO_EDIT";X[X.LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT";X[X.LATENCY_ACTION_CREATOR_VIDEO_COMMENTS]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS";
X[X.LATENCY_ACTION_CREATOR_VIDEO_CLAIMS]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS";X[X.LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS";X[X.LATENCY_ACTION_CREATOR_SONG_ANALYTICS]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS";X[X.LATENCY_ACTION_CREATOR_PROMOTION_LIST]="LATENCY_ACTION_CREATOR_PROMOTION_LIST";X[X.LATENCY_ACTION_CREATOR_PROMOTION_EDIT]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT";X[X.LATENCY_ACTION_CREATOR_POST_LIST]="LATENCY_ACTION_CREATOR_POST_LIST";
X[X.LATENCY_ACTION_CREATOR_POST_EDIT]="LATENCY_ACTION_CREATOR_POST_EDIT";X[X.LATENCY_ACTION_CREATOR_POST_COMMENTS]="LATENCY_ACTION_CREATOR_POST_COMMENTS";X[X.LATENCY_ACTION_CREATOR_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_LIVE_STREAMING";X[X.LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT";X[X.LATENCY_ACTION_CREATOR_DIALOG_UPLOADS]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS";X[X.LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES";
X[X.LATENCY_ACTION_CREATOR_CMS_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_VIDEOS";X[X.LATENCY_ACTION_CREATOR_CMS_REPORTS]="LATENCY_ACTION_CREATOR_CMS_REPORTS";X[X.LATENCY_ACTION_CREATOR_CMS_RELEASES]="LATENCY_ACTION_CREATOR_CMS_RELEASES";X[X.LATENCY_ACTION_CREATOR_CMS_POLICIES]="LATENCY_ACTION_CREATOR_CMS_POLICIES";X[X.LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC";X[X.LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING";
X[X.LATENCY_ACTION_CREATOR_CMS_LICENSES]="LATENCY_ACTION_CREATOR_CMS_LICENSES";X[X.LATENCY_ACTION_CREATOR_CMS_ISSUES]="LATENCY_ACTION_CREATOR_CMS_ISSUES";X[X.LATENCY_ACTION_CREATOR_CMS_DASHBOARD]="LATENCY_ACTION_CREATOR_CMS_DASHBOARD";X[X.LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY";X[X.LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS";X[X.LATENCY_ACTION_CREATOR_CMS_CHANNELS]="LATENCY_ACTION_CREATOR_CMS_CHANNELS";
X[X.LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP]="LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP";
X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION";
X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS";X[X.LATENCY_ACTION_CREATOR_CMS_ASSETS]="LATENCY_ACTION_CREATOR_CMS_ASSETS";X[X.LATENCY_ACTION_CREATOR_CMS_ART_TRACKS]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS";X[X.LATENCY_ACTION_CREATOR_CMS_ANALYTICS]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS";X[X.LATENCY_ACTION_CREATOR_CMS_ALLOWLIST]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST";X[X.LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS";
X[X.LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS";X[X.LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS";X[X.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT";X[X.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC";X[X.LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION";
X[X.LATENCY_ACTION_CREATOR_CHANNEL_EDITING]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING";X[X.LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD]="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD";X[X.LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT";X[X.LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS";X[X.LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS";X[X.LATENCY_ACTION_CREATOR_ARTIST_PROFILE]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE";
X[X.LATENCY_ACTION_CREATOR_ARTIST_CONCERTS]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS";X[X.LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS";X[X.LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE";X[X.LATENCY_ACTION_EXPERIMENTAL_WATCH_UI]="LATENCY_ACTION_EXPERIMENTAL_WATCH_UI";X[X.LATENCY_ACTION_FINE_SCRUBBING_THUMBNAILS]="LATENCY_ACTION_FINE_SCRUBBING_THUMBNAILS";X[X.LATENCY_ACTION_STORYBOARD_THUMBNAILS]="LATENCY_ACTION_STORYBOARD_THUMBNAILS";
X[X.LATENCY_ACTION_SEARCH_THUMBNAILS]="LATENCY_ACTION_SEARCH_THUMBNAILS";X[X.LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD]="LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD";X[X.LATENCY_ACTION_VOICE_ASSISTANT]="LATENCY_ACTION_VOICE_ASSISTANT";X[X.LATENCY_ACTION_SEARCH_UI]="LATENCY_ACTION_SEARCH_UI";X[X.LATENCY_ACTION_SUGGEST]="LATENCY_ACTION_SUGGEST";X[X.LATENCY_ACTION_AUTO_SEARCH]="LATENCY_ACTION_AUTO_SEARCH";X[X.LATENCY_ACTION_DOWNLOADS]="LATENCY_ACTION_DOWNLOADS";X[X.LATENCY_ACTION_EXPLORE]="LATENCY_ACTION_EXPLORE";
X[X.LATENCY_ACTION_VIDEO_LIST]="LATENCY_ACTION_VIDEO_LIST";X[X.LATENCY_ACTION_HOME_RESUME]="LATENCY_ACTION_HOME_RESUME";X[X.LATENCY_ACTION_SUBSCRIPTIONS_LIST]="LATENCY_ACTION_SUBSCRIPTIONS_LIST";X[X.LATENCY_ACTION_THUMBNAIL_LOAD]="LATENCY_ACTION_THUMBNAIL_LOAD";X[X.LATENCY_ACTION_FIRST_THUMBNAIL_LOAD]="LATENCY_ACTION_FIRST_THUMBNAIL_LOAD";X[X.LATENCY_ACTION_SUBSCRIPTIONS_FEED]="LATENCY_ACTION_SUBSCRIPTIONS_FEED";X[X.LATENCY_ACTION_SUBSCRIPTIONS]="LATENCY_ACTION_SUBSCRIPTIONS";
X[X.LATENCY_ACTION_TRENDING]="LATENCY_ACTION_TRENDING";X[X.LATENCY_ACTION_LIBRARY]="LATENCY_ACTION_LIBRARY";X[X.LATENCY_ACTION_VIDEO_THUMBNAIL]="LATENCY_ACTION_VIDEO_THUMBNAIL";X[X.LATENCY_ACTION_SHOW_MORE]="LATENCY_ACTION_SHOW_MORE";X[X.LATENCY_ACTION_VIDEO_PREVIEW]="LATENCY_ACTION_VIDEO_PREVIEW";X[X.LATENCY_ACTION_AD_TO_AD]="LATENCY_ACTION_AD_TO_AD";X[X.LATENCY_ACTION_VIDEO_TO_AD]="LATENCY_ACTION_VIDEO_TO_AD";X[X.LATENCY_ACTION_AD_TO_VIDEO]="LATENCY_ACTION_AD_TO_VIDEO";
X[X.LATENCY_ACTION_DIRECT_PLAYBACK]="LATENCY_ACTION_DIRECT_PLAYBACK";X[X.LATENCY_ACTION_PREBUFFER_VIDEO]="LATENCY_ACTION_PREBUFFER_VIDEO";X[X.LATENCY_ACTION_PREFETCH_VIDEO]="LATENCY_ACTION_PREFETCH_VIDEO";X[X.LATENCY_ACTION_STARTUP]="LATENCY_ACTION_STARTUP";X[X.LATENCY_ACTION_INLINE_TO_WATCH]="LATENCY_ACTION_INLINE_TO_WATCH";X[X.LATENCY_ACTION_MUSIC_IMMERSIVE_WATCH]="LATENCY_ACTION_MUSIC_IMMERSIVE_WATCH";X[X.LATENCY_ACTION_ONBOARDING]="LATENCY_ACTION_ONBOARDING";X[X.LATENCY_ACTION_LOGIN]="LATENCY_ACTION_LOGIN";
X[X.LATENCY_ACTION_REEL_WATCH]="LATENCY_ACTION_REEL_WATCH";X[X.LATENCY_ACTION_WATCH]="LATENCY_ACTION_WATCH";X[X.LATENCY_ACTION_RESULTS]="LATENCY_ACTION_RESULTS";X[X.LATENCY_ACTION_CHANNELS]="LATENCY_ACTION_CHANNELS";X[X.LATENCY_ACTION_HOME]="LATENCY_ACTION_HOME";X[X.LATENCY_ACTION_BROWSE]="LATENCY_ACTION_BROWSE";X[X.LATENCY_ACTION_USER_ACTION]="LATENCY_ACTION_USER_ACTION";X[X.LATENCY_ACTION_INFRASTRUCTURE]="LATENCY_ACTION_INFRASTRUCTURE";X[X.LATENCY_ACTION_PAGE_NAVIGATION]="LATENCY_ACTION_PAGE_NAVIGATION";
X[X.LATENCY_ACTION_UNKNOWN]="LATENCY_ACTION_UNKNOWN";var dw={LATENCY_NETWORK_MOBILE:2,LATENCY_NETWORK_WIFI:1,LATENCY_NETWORK_UNKNOWN:0};dw[dw.LATENCY_NETWORK_MOBILE]="LATENCY_NETWORK_MOBILE";dw[dw.LATENCY_NETWORK_WIFI]="LATENCY_NETWORK_WIFI";dw[dw.LATENCY_NETWORK_UNKNOWN]="LATENCY_NETWORK_UNKNOWN";
var Y={CONN_INVALID:31,CONN_CELLULAR_5G_NSA:12,CONN_CELLULAR_5G_SA:11,CONN_WIFI_METERED:10,CONN_CELLULAR_5G:9,CONN_DISCO:8,CONN_CELLULAR_UNKNOWN:7,CONN_CELLULAR_4G:6,CONN_CELLULAR_3G:5,CONN_CELLULAR_2G:4,CONN_WIFI:3,CONN_NONE:2,CONN_UNKNOWN:1,CONN_DEFAULT:0};Y[Y.CONN_INVALID]="CONN_INVALID";Y[Y.CONN_CELLULAR_5G_NSA]="CONN_CELLULAR_5G_NSA";Y[Y.CONN_CELLULAR_5G_SA]="CONN_CELLULAR_5G_SA";Y[Y.CONN_WIFI_METERED]="CONN_WIFI_METERED";Y[Y.CONN_CELLULAR_5G]="CONN_CELLULAR_5G";Y[Y.CONN_DISCO]="CONN_DISCO";
Y[Y.CONN_CELLULAR_UNKNOWN]="CONN_CELLULAR_UNKNOWN";Y[Y.CONN_CELLULAR_4G]="CONN_CELLULAR_4G";Y[Y.CONN_CELLULAR_3G]="CONN_CELLULAR_3G";Y[Y.CONN_CELLULAR_2G]="CONN_CELLULAR_2G";Y[Y.CONN_WIFI]="CONN_WIFI";Y[Y.CONN_NONE]="CONN_NONE";Y[Y.CONN_UNKNOWN]="CONN_UNKNOWN";Y[Y.CONN_DEFAULT]="CONN_DEFAULT";
var Z={DETAILED_NETWORK_TYPE_NR_NSA:126,DETAILED_NETWORK_TYPE_NR_SA:125,DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED:124,DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT:123,DETAILED_NETWORK_TYPE_DISCONNECTED:122,DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN:121,DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN:120,DETAILED_NETWORK_TYPE_WIMAX:119,DETAILED_NETWORK_TYPE_ETHERNET:118,DETAILED_NETWORK_TYPE_BLUETOOTH:117,DETAILED_NETWORK_TYPE_WIFI:116,DETAILED_NETWORK_TYPE_LTE:115,DETAILED_NETWORK_TYPE_HSPAP:114,DETAILED_NETWORK_TYPE_EHRPD:113,
DETAILED_NETWORK_TYPE_EVDO_B:112,DETAILED_NETWORK_TYPE_UMTS:111,DETAILED_NETWORK_TYPE_IDEN:110,DETAILED_NETWORK_TYPE_HSUPA:109,DETAILED_NETWORK_TYPE_HSPA:108,DETAILED_NETWORK_TYPE_HSDPA:107,DETAILED_NETWORK_TYPE_EVDO_A:106,DETAILED_NETWORK_TYPE_EVDO_0:105,DETAILED_NETWORK_TYPE_CDMA:104,DETAILED_NETWORK_TYPE_1_X_RTT:103,DETAILED_NETWORK_TYPE_GPRS:102,DETAILED_NETWORK_TYPE_EDGE:101,DETAILED_NETWORK_TYPE_UNKNOWN:0};Z[Z.DETAILED_NETWORK_TYPE_NR_NSA]="DETAILED_NETWORK_TYPE_NR_NSA";
Z[Z.DETAILED_NETWORK_TYPE_NR_SA]="DETAILED_NETWORK_TYPE_NR_SA";Z[Z.DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED]="DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED";Z[Z.DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT]="DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT";Z[Z.DETAILED_NETWORK_TYPE_DISCONNECTED]="DETAILED_NETWORK_TYPE_DISCONNECTED";Z[Z.DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN";Z[Z.DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN";
Z[Z.DETAILED_NETWORK_TYPE_WIMAX]="DETAILED_NETWORK_TYPE_WIMAX";Z[Z.DETAILED_NETWORK_TYPE_ETHERNET]="DETAILED_NETWORK_TYPE_ETHERNET";Z[Z.DETAILED_NETWORK_TYPE_BLUETOOTH]="DETAILED_NETWORK_TYPE_BLUETOOTH";Z[Z.DETAILED_NETWORK_TYPE_WIFI]="DETAILED_NETWORK_TYPE_WIFI";Z[Z.DETAILED_NETWORK_TYPE_LTE]="DETAILED_NETWORK_TYPE_LTE";Z[Z.DETAILED_NETWORK_TYPE_HSPAP]="DETAILED_NETWORK_TYPE_HSPAP";Z[Z.DETAILED_NETWORK_TYPE_EHRPD]="DETAILED_NETWORK_TYPE_EHRPD";Z[Z.DETAILED_NETWORK_TYPE_EVDO_B]="DETAILED_NETWORK_TYPE_EVDO_B";
Z[Z.DETAILED_NETWORK_TYPE_UMTS]="DETAILED_NETWORK_TYPE_UMTS";Z[Z.DETAILED_NETWORK_TYPE_IDEN]="DETAILED_NETWORK_TYPE_IDEN";Z[Z.DETAILED_NETWORK_TYPE_HSUPA]="DETAILED_NETWORK_TYPE_HSUPA";Z[Z.DETAILED_NETWORK_TYPE_HSPA]="DETAILED_NETWORK_TYPE_HSPA";Z[Z.DETAILED_NETWORK_TYPE_HSDPA]="DETAILED_NETWORK_TYPE_HSDPA";Z[Z.DETAILED_NETWORK_TYPE_EVDO_A]="DETAILED_NETWORK_TYPE_EVDO_A";Z[Z.DETAILED_NETWORK_TYPE_EVDO_0]="DETAILED_NETWORK_TYPE_EVDO_0";Z[Z.DETAILED_NETWORK_TYPE_CDMA]="DETAILED_NETWORK_TYPE_CDMA";
Z[Z.DETAILED_NETWORK_TYPE_1_X_RTT]="DETAILED_NETWORK_TYPE_1_X_RTT";Z[Z.DETAILED_NETWORK_TYPE_GPRS]="DETAILED_NETWORK_TYPE_GPRS";Z[Z.DETAILED_NETWORK_TYPE_EDGE]="DETAILED_NETWORK_TYPE_EDGE";Z[Z.DETAILED_NETWORK_TYPE_UNKNOWN]="DETAILED_NETWORK_TYPE_UNKNOWN";var ew={LATENCY_PLAYER_RTSP:7,LATENCY_PLAYER_HTML5_INLINE:6,LATENCY_PLAYER_HTML5_FULLSCREEN:5,LATENCY_PLAYER_HTML5:4,LATENCY_PLAYER_FRAMEWORK:3,LATENCY_PLAYER_FLASH:2,LATENCY_PLAYER_EXO:1,LATENCY_PLAYER_UNKNOWN:0};ew[ew.LATENCY_PLAYER_RTSP]="LATENCY_PLAYER_RTSP";
ew[ew.LATENCY_PLAYER_HTML5_INLINE]="LATENCY_PLAYER_HTML5_INLINE";ew[ew.LATENCY_PLAYER_HTML5_FULLSCREEN]="LATENCY_PLAYER_HTML5_FULLSCREEN";ew[ew.LATENCY_PLAYER_HTML5]="LATENCY_PLAYER_HTML5";ew[ew.LATENCY_PLAYER_FRAMEWORK]="LATENCY_PLAYER_FRAMEWORK";ew[ew.LATENCY_PLAYER_FLASH]="LATENCY_PLAYER_FLASH";ew[ew.LATENCY_PLAYER_EXO]="LATENCY_PLAYER_EXO";ew[ew.LATENCY_PLAYER_UNKNOWN]="LATENCY_PLAYER_UNKNOWN";
var fw={LATENCY_AD_BREAK_TYPE_POSTROLL:3,LATENCY_AD_BREAK_TYPE_MIDROLL:2,LATENCY_AD_BREAK_TYPE_PREROLL:1,LATENCY_AD_BREAK_TYPE_UNKNOWN:0};fw[fw.LATENCY_AD_BREAK_TYPE_POSTROLL]="LATENCY_AD_BREAK_TYPE_POSTROLL";fw[fw.LATENCY_AD_BREAK_TYPE_MIDROLL]="LATENCY_AD_BREAK_TYPE_MIDROLL";fw[fw.LATENCY_AD_BREAK_TYPE_PREROLL]="LATENCY_AD_BREAK_TYPE_PREROLL";fw[fw.LATENCY_AD_BREAK_TYPE_UNKNOWN]="LATENCY_AD_BREAK_TYPE_UNKNOWN";var gw={LATENCY_ACTION_ERROR_STARTUP_TIMEOUT:1,LATENCY_ACTION_ERROR_UNSPECIFIED:0};
gw[gw.LATENCY_ACTION_ERROR_STARTUP_TIMEOUT]="LATENCY_ACTION_ERROR_STARTUP_TIMEOUT";gw[gw.LATENCY_ACTION_ERROR_UNSPECIFIED]="LATENCY_ACTION_ERROR_UNSPECIFIED";var hw={LIVE_STREAM_MODE_WINDOW:5,LIVE_STREAM_MODE_POST:4,LIVE_STREAM_MODE_LP:3,LIVE_STREAM_MODE_LIVE:2,LIVE_STREAM_MODE_DVR:1,LIVE_STREAM_MODE_UNKNOWN:0};hw[hw.LIVE_STREAM_MODE_WINDOW]="LIVE_STREAM_MODE_WINDOW";hw[hw.LIVE_STREAM_MODE_POST]="LIVE_STREAM_MODE_POST";hw[hw.LIVE_STREAM_MODE_LP]="LIVE_STREAM_MODE_LP";
hw[hw.LIVE_STREAM_MODE_LIVE]="LIVE_STREAM_MODE_LIVE";hw[hw.LIVE_STREAM_MODE_DVR]="LIVE_STREAM_MODE_DVR";hw[hw.LIVE_STREAM_MODE_UNKNOWN]="LIVE_STREAM_MODE_UNKNOWN";var iw={VIDEO_STREAM_TYPE_VOD:3,VIDEO_STREAM_TYPE_DVR:2,VIDEO_STREAM_TYPE_LIVE:1,VIDEO_STREAM_TYPE_UNSPECIFIED:0};iw[iw.VIDEO_STREAM_TYPE_VOD]="VIDEO_STREAM_TYPE_VOD";iw[iw.VIDEO_STREAM_TYPE_DVR]="VIDEO_STREAM_TYPE_DVR";iw[iw.VIDEO_STREAM_TYPE_LIVE]="VIDEO_STREAM_TYPE_LIVE";iw[iw.VIDEO_STREAM_TYPE_UNSPECIFIED]="VIDEO_STREAM_TYPE_UNSPECIFIED";
var jw={YT_IDB_TRANSACTION_TYPE_READ:2,YT_IDB_TRANSACTION_TYPE_WRITE:1,YT_IDB_TRANSACTION_TYPE_UNKNOWN:0};jw[jw.YT_IDB_TRANSACTION_TYPE_READ]="YT_IDB_TRANSACTION_TYPE_READ";jw[jw.YT_IDB_TRANSACTION_TYPE_WRITE]="YT_IDB_TRANSACTION_TYPE_WRITE";jw[jw.YT_IDB_TRANSACTION_TYPE_UNKNOWN]="YT_IDB_TRANSACTION_TYPE_UNKNOWN";var kw={PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN:2,PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT:1,PLAYER_ROTATION_TYPE_UNKNOWN:0};kw[kw.PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN]="PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN";
kw[kw.PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT]="PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT";kw[kw.PLAYER_ROTATION_TYPE_UNKNOWN]="PLAYER_ROTATION_TYPE_UNKNOWN";var lw="actionVisualElement spinnerInfo resourceInfo playerInfo commentInfo mdxInfo watchInfo thumbnailLoadInfo creatorInfo unpluggedInfo reelInfo subscriptionsFeedInfo requestIds mediaBrowserActionInfo musicLoadActionInfo shoppingInfo webViewInfo prefetchInfo accelerationSession commerceInfo inlineToWatchInfo webInfo tvInfo kabukiInfo mwebInfo musicInfo transcodingContext creationModesContext".split(" ");function mw(a,b){zq.call(this,1,arguments);this.timer=b}
v(mw,zq);var nw=new Aq("aft-recorded",mw);var ow=y.ytLoggingLatencyUsageStats_||{};A("ytLoggingLatencyUsageStats_",ow);function pw(){this.h=0}
function qw(){pw.h||(pw.h=new pw);return pw.h}
pw.prototype.tick=function(a,b,c,d){rw(this,"tick_"+a+"_"+b)||(c={timestamp:c,cttAuthInfo:d},P("web_csi_via_jspb")?(d=new pm,G(d,1,a),G(d,2,b),a=new sm,le(a,pm,5,tm,d),gu(a,c)):Fo("latencyActionTicked",{tickName:a,clientActionNonce:b},c))};
pw.prototype.info=function(a,b,c){var d=Object.keys(a).join("");rw(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,Fo("latencyActionInfo",a,{cttAuthInfo:c}))};
pw.prototype.jspbInfo=function(a,b,c){for(var d="",e=0;e<a.toJSON().length;e++)void 0!==a.toJSON()[e]&&(d=0===e?d.concat(""+e):d.concat("_"+e));rw(this,"info_"+d+"_"+b)||(G(a,2,b),b={cttAuthInfo:c},c=new sm,le(c,mm,7,tm,a),gu(c,b))};
pw.prototype.span=function(a,b,c){var d=Object.keys(a).join("");rw(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,Fo("latencyActionSpan",a,{cttAuthInfo:c}))};
function rw(a,b){ow[b]=ow[b]||{count:0};var c=ow[b];c.count++;c.time=T();a.h||(a.h=ro(function(){var d=T(),e;for(e in ow)ow[e]&&6E4<d-ow[e].time&&delete ow[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new R("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||uu(c)),!0):!1}
;var sw=window;function tw(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function uw(){var a;if(P("csi_use_performance_navigation_timing")||P("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==vw?void 0:null==(a=vw.getEntriesByType)?void 0:null==(b=a.call(vw,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=ww(e.requestStart),e.responseEnd=ww(e.responseEnd),e.redirectStart=ww(e.redirectStart),e.redirectEnd=ww(e.redirectEnd),e.domainLookupEnd=ww(e.domainLookupEnd),e.connectStart=ww(e.connectStart),e.connectEnd=
ww(e.connectEnd),e.responseStart=ww(e.responseStart),e.secureConnectionStart=ww(e.secureConnectionStart),e.domainLookupStart=ww(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=vw.timing}else a=vw.timing;return a}
function ww(a){return Math.round(xw()+a)}
function xw(){return(P("csi_use_time_origin")||P("csi_use_time_origin_tvhtml5"))&&vw.timeOrigin?Math.floor(vw.timeOrigin):vw.timing.navigationStart}
var vw=sw.performance||sw.mozPerformance||sw.msPerformance||sw.webkitPerformance||new tw;var yw=!1,zw={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Ya(vw.clearResourceTimings||vw.webkitClearResourceTimings||vw.mozClearResourceTimings||vw.msClearResourceTimings||vw.oClearResourceTimings||db,vw);function Aw(a,b,c,d){if(null!==b){if("yt_lt"===a){var e="string"===typeof b?b:""+b;Pv(c).loadType=e}(a=cw(a,b,c))&&Bw(a,c,d)}}
function Bw(a,b,c){if(!P("web_csi_via_jspb")||(void 0===c?0:c))c=Vv(b||""),Iv(c.info,a),a.loadType&&(c=a.loadType,Pv(b).loadType=c),Iv(Sv(b),a),c=Tv(b),b=Nv(b).cttAuthInfo,qw().info(a,c,b);else{c=new mm;var d=Object.keys(a);a=Object.values(a);for(var e=0;e<d.length;e++){var f=d[e];try{switch(f){case "actionType":G(c,1,X[a[e]]);break;case "clientActionNonce":G(c,2,a[e]);break;case "clientScreenNonce":G(c,4,a[e]);break;case "loadType":G(c,3,a[e]);break;case "isPrewarmedLaunch":G(c,92,a[e]);break;case "isFirstInstall":G(c,
55,a[e]);break;case "networkType":G(c,5,dw[a[e]]);break;case "connectionType":G(c,26,Y[a[e]]);break;case "detailedConnectionType":G(c,27,Z[a[e]]);break;case "isVisible":G(c,6,a[e]);break;case "playerType":G(c,7,ew[a[e]]);break;case "clientPlaybackNonce":G(c,8,a[e]);break;case "adClientPlaybackNonce":G(c,28,a[e]);break;case "previousCpn":G(c,77,a[e]);break;case "targetCpn":G(c,76,a[e]);break;case "isMonetized":G(c,9,a[e]);break;case "isPrerollAllowed":G(c,16,a[e]);break;case "isPrerollShown":G(c,17,
a[e]);break;case "adType":G(c,12,a[e]);break;case "adTypesAllowed":G(c,36,a[e]);break;case "adNetworks":G(c,37,a[e]);break;case "previousAction":G(c,13,X[a[e]]);break;case "isRedSubscriber":G(c,14,a[e]);break;case "serverTimeMs":oe(c,15,a[e]);break;case "videoId":c.setVideoId(a[e]);break;case "adVideoId":G(c,20,a[e]);break;case "targetVideoId":G(c,78,a[e]);break;case "adBreakType":G(c,21,fw[a[e]]);break;case "isNavigation":G(c,25,a[e]);break;case "viewportHeight":oe(c,29,a[e]);break;case "viewportWidth":oe(c,
30,a[e]);break;case "screenHeight":oe(c,84,a[e]);break;case "screenWidth":oe(c,85,a[e]);break;case "browseId":G(c,31,a[e]);break;case "isCacheHit":G(c,32,a[e]);break;case "httpProtocol":G(c,33,a[e]);break;case "transportProtocol":G(c,34,a[e]);break;case "searchQuery":G(c,41,a[e]);break;case "isContinuation":G(c,42,a[e]);break;case "availableProcessors":oe(c,43,a[e]);break;case "sdk":G(c,44,a[e]);break;case "isLocalStream":G(c,45,a[e]);break;case "navigationRequestedSameUrl":G(c,64,a[e]);break;case "shellStartupDurationMs":oe(c,
70,a[e]);break;case "appInstallDataAgeMs":oe(c,73,a[e]);break;case "latencyActionError":G(c,71,gw[a[e]]);break;case "actionStep":oe(c,79,a[e]);break;case "jsHeapSizeLimit":G(c,80,a[e]);break;case "totalJsHeapSize":G(c,81,a[e]);break;case "usedJsHeapSize":G(c,82,a[e]);break;case "sourceVideoDurationMs":G(c,90,a[e]);break;case "videoOutputFrames":G(c,93,a[e]);break;case "isResume":G(c,104,a[e]);break;case "debugTicksExcluded":G(c,105,a[e]);break;case "adPrebufferedTimeSecs":oe(c,39,a[e]);break;case "isLivestream":G(c,
47,a[e]);break;case "liveStreamMode":G(c,91,hw[a[e]]);break;case "adCpn2":G(c,48,a[e]);break;case "adDaiDriftMillis":G(c,49,a[e]);break;case "videoStreamType":G(c,53,iw[a[e]]);break;case "playbackRequiresTap":G(c,56,a[e]);break;case "performanceNavigationTiming":G(c,67,a[e]);break;case "transactionType":G(c,74,jw[a[e]]);break;case "playerRotationType":G(c,101,kw[a[e]]);break;case "allowedPreroll":G(c,10,a[e]);break;case "shownPreroll":G(c,11,a[e]);break;case "getHomeRequestId":G(c,57,a[e]);break;
case "getSearchRequestId":G(c,60,a[e]);break;case "getPlayerRequestId":G(c,61,a[e]);break;case "getWatchNextRequestId":G(c,62,a[e]);break;case "getBrowseRequestId":G(c,63,a[e]);break;case "getLibraryRequestId":G(c,66,a[e]);break;case "isTransformerEnabledForFeature":G(c,106,a[e]);break;case "sourceVideoFrameCount":G(c,109,a[e]);break;default:lw.includes(f)&&Sm(new R("Codegen laipb translator asked to translate message field",""+f))}}catch(g){Sm(Error("Codegen laipb translator failed to set "+f))}}Cw(c,
b)}}
function Cw(a,b){var c=se(a,3);c&&(Pv(b).loadType=c);Vv(b||"").jspbInfo.push(a);c=Tv(b);b=Nv(b).cttAuthInfo;qw().jspbInfo(a,c,b)}
function Dw(a,b,c){if(!b&&"_"!==a[0]){var d=a;vw.mark&&(0==d.lastIndexOf("mark_",0)||(d="mark_"+d),c&&(d+=" ("+c+")"),vw.mark(d))}d=Vv(c||"");d.tick[a]=b||T();if(d.callback&&d.callback[a]){d=r(d.callback[a]);for(var e=d.next();!e.done;e=d.next())e=e.value,e()}d=Rv(c);d.gelTicks&&(d.gelTicks[a]=!0);e=Qv(c);d=b||T();P("log_repeated_ytcsi_ticks")?a in e||(e[a]=d):e[a]=d;e=Tv(c);var f=Nv(c).cttAuthInfo;"_start"===a?(a=qw(),rw(a,"baseline_"+e)||(b={timestamp:b,cttAuthInfo:f},P("web_csi_via_jspb")?(a=new hm,
G(a,1,e),e=new sm,le(e,hm,6,tm,a),gu(e,b)):Fo("latencyActionBaselined",{clientActionNonce:e},b))):qw().tick(a,e,b,f);Ew(c);return d}
function Fw(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=Ds+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Gw(a){var b=uw(),c=xw(),d=O("CSI_START_TIMESTAMP_MILLIS",0);0<d&&!P("embeds_web_enable_csi_start_override_killswitch")&&(c=d);c&&(Dw("srt",b.responseStart),1!==a.prerender&&Dw("_start",c,void 0));a=Hw();0<a&&Dw("fpt",a);a=uw();a.isPerformanceNavigationTiming&&Bw({performanceNavigationTiming:!0},void 0);Dw("nreqs",a.requestStart,void 0);Dw("nress",a.responseStart,void 0);Dw("nrese",a.responseEnd,void 0);0<a.redirectEnd-a.redirectStart&&(Dw("nrs",a.redirectStart,void 0),Dw("nre",a.redirectEnd,
void 0));0<a.domainLookupEnd-a.domainLookupStart&&(Dw("ndnss",a.domainLookupStart,void 0),Dw("ndnse",a.domainLookupEnd,void 0));0<a.connectEnd-a.connectStart&&(Dw("ntcps",a.connectStart,void 0),Dw("ntcpe",a.connectEnd,void 0));a.secureConnectionStart>=xw()&&0<a.connectEnd-a.secureConnectionStart&&(Dw("nstcps",a.secureConnectionStart,void 0),Dw("ntcpe",a.connectEnd,void 0));vw&&"getEntriesByType"in vw&&Iw()}
function Jw(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);rc()&&a.setAttribute("nonce",rc());return c?(a=vw.getEntriesByName(c))&&a[0]&&(a=a[0],c=xw(),Dw("rsf_"+b,c+Math.round(a.fetchStart)),Dw("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Kw(){var a=[];if(document.querySelector&&vw&&vw.getEntriesByName)for(var b in zw)if(zw.hasOwnProperty(b)){var c=zw[b];Jw(b,c)&&a.push(c)}return a}
function Iw(){var a=window.location.protocol,b=vw.getEntriesByType("resource");b=hb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=jb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Dw("wffs",ww(b.startTime)),Dw("wffe",ww(b.responseEnd)))}
function Lw(a){var b=Mw("aft",a);if(b)return b;b=O((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Mw(b[d],a);if(e)return e}return NaN}
function Mw(a,b){if(a=Qv(b)[a])return"number"===typeof a?a:a[a.length-1]}
function Ew(a){var b=Mw("_start",a),c=Lw(a);b&&c&&!yw&&(Fq(nw,new mw(Math.round(c-b),a)),yw=!0)}
function Nw(a,b){for(var c=r(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!Nw(a[d],b[d]))return!1;return!0}
function Hw(){if(vw.getEntriesByType){var a=vw.getEntriesByType("paint");if(a=kb(a,function(b){return"first-paint"===b.name}))return ww(a.startTime)}a=vw.timing;
return a.Ie?Math.max(0,a.Ie):0}
;function Ow(a,b){Rm(function(){Vv("").info.actionType=a;b&&Nm("TIMING_AFT_KEYS",b);Nm("TIMING_ACTION",a);if(P("web_csi_via_jspb")){var c=O("TIMING_INFO",{}),d=new mm;c=r(Object.entries(c));for(var e=c.next();!e.done;e=c.next()){var f=r(e.value);e=f.next().value;f=f.next().value;switch(e){case "GetBrowse_rid":om(d,km(jm(e),String(f)));break;case "GetGuide_rid":om(d,km(jm(e),String(f)));break;case "GetHome_rid":om(d,km(jm(e),String(f)));break;case "GetPlayer_rid":om(d,km(jm(e),String(f)));break;case "GetSearch_rid":om(d,
km(jm(e),String(f)));break;case "GetSettings_rid":om(d,km(jm(e),String(f)));break;case "GetTrending_rid":om(d,km(jm(e),String(f)));break;case "GetWatchNext_rid":om(d,km(jm(e),String(f)));break;case "yt_red":G(d,14,!!f);break;case "yt_ad":G(d,9,!!f)}}Cw(d);d=new mm;d=G(d,25,!0);d=G(d,1,X[bw(O("TIMING_ACTION"))]);(c=O("PREVIOUS_ACTION"))&&G(d,13,X[bw(c)]);(c=O("CLIENT_PROTOCOL"))&&G(d,33,c);(c=O("CLIENT_TRANSPORT"))&&G(d,34,c);(c=Pu())&&"UNDEFINED_CSN"!==c&&G(d,4,c);c=Fw();1!==c&&-1!==c||G(d,6,!0);
c=Ov();Pv();G(d,3,"cold");Gw(c);c=Kw();if(0<c.length)for(c=r(c),e=c.next();!e.done;e=c.next())e=e.value,f=new lm,G(f,1,e),ne(d,83,lm,f);Cw(d)}else{d=O("TIMING_INFO",{});for(c in d)d.hasOwnProperty(c)&&Aw(c,d[c]);d={isNavigation:!0,actionType:bw(O("TIMING_ACTION"))};if(c=O("PREVIOUS_ACTION"))d.previousAction=bw(c);if(c=O("CLIENT_PROTOCOL"))d.httpProtocol=c;if(c=O("CLIENT_TRANSPORT"))d.transportProtocol=c;(c=Pu())&&"UNDEFINED_CSN"!==c&&(d.clientScreenNonce=c);c=Fw();if(1===c||-1===c)d.isVisible=!0;
Pv();Ov();d.loadType="cold";Gw(Ov());c=Kw();if(0<c.length)for(d.resourceInfo=[],c=r(c),e=c.next();!e.done;e=c.next())d.resourceInfo.push({resourceCache:e.value});Bw(d)}d=Ov();c=Sv();if("cold"===Pv().loadType&&("cold"===d.yt_lt||"cold"===c.loadType)){e=Qv();f=Rv();f=f.gelTicks?f.gelTicks:f.gelTicks={};for(var g in e)if(!(g in f))if("number"===typeof e[g])Dw(g,Mw(g));else if(P("log_repeated_ytcsi_ticks"))for(var h=r(e[g]),l=h.next();!l.done;l=h.next())Dw(g.slice(1),l.value);g={};e=!1;f=r(Object.keys(d));
for(h=f.next();!h.done;h=f.next())h=h.value,(h=cw(h,d[h]))&&!Nw(Sv(),h)&&(Iv(c,h),Iv(g,h),e=!0);e&&Bw(g)}A("ytglobal.timingready_",!0);g=O("TIMING_ACTION");B("ytglobal.timingready_")&&g&&Pw()&&Lw()&&Ew()})()}
function Qw(a,b,c,d){Rm(Aw)(a,b,c,d)}
function Rw(a,b,c){return Rm(Dw)(a,b,c)}
function Pw(){return Rm(function(){return"_start"in Qv()})()}
function Sw(){Rm(function(){var a=Tv();requestAnimationFrame(function(){setTimeout(function(){a===Tv()&&Rw("ol",void 0,void 0)},0)})})()}
var Tw=window;Tw.ytcsi&&(Tw.ytcsi.info=Qw,Tw.ytcsi.tick=Rw);var Uw="tokens consistency mss client_location entities response_received_commands store PLAYER_PRELOAD".split(" "),Vw=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function Ww(a,b,c,d){this.m=a;this.U=b;this.l=c;this.j=d;this.i=void 0;this.h=new Map;a.Qb||(a.Qb={});a.Qb=Object.assign({},Hv,a.Qb)}
function Xw(a,b,c,d){if(void 0!==Ww.h){if(d=Ww.h,a=[a!==d.m,b!==d.U,c!==d.l,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new R("InnerTubeTransportService is already initialized",a);
}else Ww.h=new Ww(a,b,c,d)}
function Yw(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?Tn:c;var d=zv(b,a.m);if(!d)return Wf(new R("Error: No request builder found for command.",b));var e=d.m(b,void 0,c);return e?new Rf(function(f){var g,h,l;return x(function(m){if(1==m.h){h="cors"===(null==(g=e.kb)?void 0:g.mode)?"cors":void 0;if(a.l.gf){var n=e.config,q;n=null==n?void 0:null==(q=n.Yb)?void 0:q.sessionIndex;q=Sn(0,{sessionIndex:n});l=Object.assign({},Zw(h),q);return m.A(2)}return w(m,$w(e.config,
h),3)}2!=m.h&&(l=m.i);f(ax(a,e,l));m.h=0})}):Wf(new R("Error: Failed to build request for command.",b))}
function bx(a,b,c){var d;if(b&&!(null==b?0:null==(d=b.Lg)?0:d.Pg)&&a.j){d=r(Uw);for(var e=d.next();!e.done;e=d.next())e=e.value,a.j[e]&&a.j[e].handleResponse(b,c)}}
function ax(a,b,c){var d,e,f,g,h,l,m,n,q,u,t,z,C,E,M,S,Q,W,fa,ma,Ra,Da,za,na,J,Pc,Qc,gf,hf;return x(function(ha){switch(ha.h){case 1:ha.A(2);break;case 3:if((d=ha.i)&&!d.isExpired())return ha.return(Promise.resolve(d.h()));case 2:if(!(null==(e=b)?0:null==(f=e.Ka)?0:f.context)){ha.A(4);break}g=b.Ka.context;if(!P("web_async_context_processor")){h=r([]);for(l=h.next();!l.done;l=h.next())m=l.value,m.Hg(g);ha.A(4);break}return w(ha,[].reduce(function(Fh,Gh){return Fh.then(function(){return Gh.Gg(g)})},
Promise.resolve()),4);
case 4:if(null==(n=a.i)||!n.Mg(b.input,b.Ka)){ha.A(7);break}return w(ha,a.i.Bg(b.input,b.Ka),8);case 8:return q=ha.i,P("kevlar_process_local_innertube_responses_killswitch")||bx(a,q,b),ha.return(q);case 7:return(z=null==(t=b.config)?void 0:t.Ea)&&a.h.has(z)&&P("web_memoize_inflight_requests")?u=a.h.get(z):(C=JSON.stringify(b.Ka),S=null!=(M=null==(E=b.kb)?void 0:E.headers)?M:{},b.kb=Object.assign({},b.kb,{headers:Object.assign({},S,c)}),Q=Object.assign({},b.kb),"POST"===b.kb.method&&(Q=Object.assign({},
Q,{body:C})),(null==(W=b.config)?0:W.Qe)&&Rw(b.config.Qe),fa=function(){return a.U.fetch(b.input,Q,b.config)},u=fa(),z&&a.h.set(z,u)),w(ha,u,9);
case 9:if((ma=ha.i)&&"error"in ma&&(null==(Ra=ma)?0:null==(Da=Ra.error)?0:Da.details))for(za=ma.error.details,na=r(za),J=na.next();!J.done;J=na.next())Pc=J.value,(Qc=Pc["@type"])&&-1<Vw.indexOf(Qc)&&(delete Pc["@type"],ma=Pc);z&&a.h.has(z)&&a.h.delete(z);(null==(gf=b.config)?0:gf.Re)&&Rw(b.config.Re);if(ma||null==(hf=a.i)||!hf.tg(b.input,b.Ka)){ha.A(10);break}return w(ha,a.i.Ag(b.input,b.Ka),11);case 11:ma=ha.i;case 10:return bx(a,ma,b),ha.return(ma||void 0)}})}
function $w(a,b){var c,d,e,f;return x(function(g){if(1==g.h){e=null==(c=a)?void 0:null==(d=c.Yb)?void 0:d.sessionIndex;var h=Sn(0,{sessionIndex:e});if(!(h instanceof Rf)){var l=new Rf(db);Sf(l,2,h);h=l}return w(g,h,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},Zw(b),f)))})}
function Zw(a){var b={"Content-Type":"application/json"};O("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=O("EOM_VISITOR_DATA"):O("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=O("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=O("LOGGED_IN",!1);"cors"!==a&&((a=O("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=O("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=O("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=a),(a=O("DOMAIN_ADMIN_STATE"))&&
(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var cx=new ct("INNERTUBE_TRANSPORT_TOKEN");var dx=["share/get_web_player_share_panel"],ex=["feedback"],fx=["notification/modify_channel_preference"],gx=["browse/edit_playlist"],hx=["subscription/subscribe"],ix=["subscription/unsubscribe"];function jx(){}
v(jx,Ev);jx.prototype.j=function(){return hx};
jx.prototype.h=function(a){return ot(a,Em)||void 0};
jx.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
da.Object.defineProperties(jx.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function kx(){}
v(kx,Ev);kx.prototype.j=function(){return ix};
kx.prototype.h=function(a){return ot(a,Dm)||void 0};
kx.prototype.i=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
da.Object.defineProperties(kx.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function lx(){}
v(lx,Ev);lx.prototype.j=function(){return ex};
lx.prototype.h=function(a){return ot(a,nl)||void 0};
lx.prototype.i=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
da.Object.defineProperties(lx.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function mx(){}
v(mx,Ev);mx.prototype.j=function(){return fx};
mx.prototype.h=function(a){return ot(a,Cm)||void 0};
mx.prototype.i=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function nx(){}
v(nx,Ev);nx.prototype.j=function(){return gx};
nx.prototype.h=function(a){return ot(a,Bm)||void 0};
nx.prototype.i=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function ox(){}
v(ox,Ev);ox.prototype.j=function(){return dx};
ox.prototype.h=function(a){return ot(a,Am)};
ox.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var px=new ct("NETWORK_SLI_TOKEN");function qx(a){this.h=a}
qx.prototype.fetch=function(a,b){var c=this,d,e,f;return x(function(g){c.h&&(d=vc(wc(5,Jc(a,"key")))||"/UNKNOWN_PATH",c.h.start(d));e=b;P("wug_networking_gzip_request")&&(e=Yq(b));f=new window.Request(a,e);return P("web_fetch_promise_cleanup_killswitch")?g.return(Promise.resolve(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){uu(h)}))):g.return(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){uu(h)}))})};
qx.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.xg(),b=b.then(function(c){uu(new R("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
qx[bt]=[new dt(px)];var rx=new ct("NETWORK_MANAGER_TOKEN");var sx;function tx(a){a=void 0===a||a?Du():Cu();for(var b=[],c=0;c<a.length;c++)b.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(a[c]&63));return b.join("")}
;function ux(a){zq.call(this,1,arguments);this.csn=a}
v(ux,zq);var Iq=new Aq("screen-created",ux),vx=[],xx=wx,yx=0;function zx(a,b,c,d,e,f,g,h){function l(){uu(new R("newScreen() parent element does not have a VE - rootVe",b))}
var m=xx(),n=new Iu({veType:b,youtubeData:f,jspbYoutubeData:void 0});f={sequenceGroup:m};e&&(f.cttAuthInfo=e);if(P("il_via_jspb")){e=$l((new Zl).h(m),n.getAsJspb());c&&c.visualElement?(n=new Xl,c.clientScreenNonce&&G(n,2,c.clientScreenNonce),Yl(n,c.visualElement.getAsJspb()),g&&G(n,4,um[g]),H(e,Xl,5,n)):c&&l();d&&G(e,3,d);if(P("expectation_logging")&&h&&h.screenCreatedLoggingExpectations){c=new Qk;h=r(h.screenCreatedLoggingExpectations.expectedParentScreens||[]);for(d=h.next();!d.done;d=h.next())d=
d.value,d.screenVeType&&(d=Pk(new Ok,d.screenVeType),ne(c,1,Ok,d));H(e,Qk,7,c)}lu(e,f,a)}else e={csn:m,pageVe:n.getAsJson()},P("expectation_logging")&&h&&h.screenCreatedLoggingExpectations&&(e.screenCreatedLoggingExpectations=h.screenCreatedLoggingExpectations),c&&c.visualElement?(e.implicitGesture={parentCsn:c.clientScreenNonce,gesturedVe:c.visualElement.getAsJson()},g&&(e.implicitGesture.gestureType=g)):c&&l(),d&&(e.cloneCsn=d),a?au("screenCreated",e,a,f):Fo("screenCreated",e,f);Fq(Iq,new ux(m));
return m}
function Ax(a,b,c,d){var e=d.filter(function(l){l.csn!==b?(l.csn=b,l=!0):l=!1;return l}),f={cttAuthInfo:Su(b)||void 0,
sequenceGroup:b};d=r(d);for(var g=d.next();!g.done;g=d.next())g=g.value.getAsJson(),(qb(g)||!g.trackingParams&&!g.veType)&&uu(Error("Child VE logged with no data"));if(P("il_via_jspb")){var h=cm((new am).h(b),c.getAsJspb());ib(e,function(l){l=l.getAsJspb();ne(h,3,Sl,l)});
"UNDEFINED_CSN"===b?Bx("visualElementAttached",f,void 0,h):mu(h,f,a)}else c={csn:b,parentVe:c.getAsJson(),childVes:ib(e,function(l){return l.getAsJson()})},"UNDEFINED_CSN"===b?Bx("visualElementAttached",f,c):a?au("visualElementAttached",c,a,f):Fo("visualElementAttached",c,f)}
function Cx(a,b,c,d,e,f){d={cttAuthInfo:Su(b)||void 0,sequenceGroup:b};P("il_via_jspb")?(e=(new fm).h(b),c=c.getAsJspb(),c=H(e,Sl,2,c),c=G(c,4,1),f&&H(c,Vl,3,f),"UNDEFINED_CSN"===b?Bx("visualElementShown",d,void 0,c):hu(c,d,a)):(f={csn:b,ve:c.getAsJson(),eventType:1},e&&(f.clientData=e),"UNDEFINED_CSN"===b?Bx("visualElementShown",d,f):a?au("visualElementShown",f,a,d):Fo("visualElementShown",f,d))}
function Dx(a,b,c){var d=!0,e=(d=void 0===d?!1:d)?16:8,f={cttAuthInfo:Su(b)||void 0,sequenceGroup:b,endOfSequence:d};P("il_via_jspb")?(e=(new em).h(b),c=c.getAsJspb(),c=H(e,Sl,2,c),G(c,4,d?16:8),"UNDEFINED_CSN"===b?Bx("visualElementHidden",f,void 0,c):iu(c,f,a)):(d={csn:b,ve:c.getAsJson(),eventType:e},"UNDEFINED_CSN"===b?Bx("visualElementHidden",f,d):a?au("visualElementHidden",d,a,f):Fo("visualElementHidden",d,f))}
function wx(){var a;P("enable_web_96_bit_csn")?a=tx():P("enable_web_96_bit_csn_no_crypto")?a=tx(!1):a=qd(Lc(Math.random()+""),3);return a}
function Bx(a,b,c,d){vx.push({Mc:a,payload:c,Sa:d,options:b});yx||(yx=Jq())}
function Kq(a){if(vx){for(var b=r(vx),c=b.next();!c.done;c=b.next())if(c=c.value,P("il_via_jspb")&&c.Sa)switch(c.Sa.h(a.csn),c.Mc){case "screenCreated":lu(c.Sa,c.options);break;case "visualElementAttached":mu(c.Sa,c.options);break;case "visualElementShown":hu(c.Sa,c.options);break;case "visualElementHidden":iu(c.Sa,c.options);break;case "visualElementGestured":ju(c.Sa,c.options);break;case "visualElementStateChanged":ku(c.Sa,c.options);break;default:uu(new R("flushQueue unable to map payloadName to JSPB setter"))}else c.payload&&
(c.payload.csn=a.csn,Fo(c.Mc,c.payload,c.options));vx.length=0}yx=0}
;function Ex(){this.j=new Set;this.i=new Set;this.m=new Map;this.client=void 0;this.csn=null}
function Fx(){Ex.h||(Ex.h=new Ex);return Ex.h}
Ex.prototype.l=function(a){this.client=a};
Ex.prototype.h=function(){this.clear();this.csn=Pu()};
Ex.prototype.clear=function(){this.j.clear();this.i.clear();this.m.clear();this.csn=null};function Gx(){}
Gx.prototype.l=function(a){Rm(Fx().l).bind(Fx())(a)};
Gx.prototype.clear=function(){Rm(Fx().clear).bind(Fx())()};function Hx(){this.s=[];this.v=[];this.h=[];this.ra=[];this.m=[];this.X=[];this.i=new Set;this.H=new Map}
Hx.prototype.l=function(a){this.client=a};
function Ix(){Hx.h||(Hx.h=new Hx);var a=Hx.h;var b=16623;var c=void 0===c?{}:c;Rm(function(){Wu.includes(b)||(uu(new R("createClientScreen() called with a non-page VE",b)),b=83769);c.isHistoryNavigation||(a.ra=[],a.h.push({rootVe:b,key:c.key||""}));a.s=[];a.v=[];c.ld?Jx(a,b,c):Kx(a,b,c)})()}
function Lx(a,b,c){c=void 0===c?0:c;Rm(function(){b.then(function(d){a.i.has(c)&&a.j&&a.j();var e=Pu(c),f=Nu(c);if(e&&f){var g;(null==d?0:null==(g=d.response)?0:g.trackingParams)&&Ax(a.client,e,f,[Ju(d.response.trackingParams)]);var h;(null==d?0:null==(h=d.playerResponse)?0:h.trackingParams)&&Ax(a.client,e,f,[Ju(d.playerResponse.trackingParams)])}})})()}
function Mx(a,b,c,d){d=void 0===d?0:d;Rm(function(){if(a.i.has(d))return a.s.push([b,c]),!0;var e=Pu(d),f=c||Nu(d);return e&&f?(Ax(a.client,e,f,[b]),!0):!1})()}
Hx.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=Pu(void 0===c?0:c)){a=this.client;var e=Ju(d);d={cttAuthInfo:Su(c)||void 0,sequenceGroup:c};P("il_via_jspb")?(b=(new dm).h(c),e=e.getAsJspb(),b=H(b,Sl,2,e),G(b,4,um.INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK),"UNDEFINED_CSN"===c?Bx("visualElementGestured",d,void 0,b):ju(b,d,a)):(e={csn:c,ve:e.getAsJson(),gestureType:"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK"},b&&(e.clientData=b),"UNDEFINED_CSN"===
c?Bx("visualElementGestured",d,e):a?au("visualElementGestured",e,a,d):Fo("visualElementGestured",e,d));b=!0}else b=!1;else b=!1;return b};
Hx.prototype.visualElementStateChanged=function(a,b,c){c=void 0===c?0:c;0===c&&this.i.has(c)?this.v.push([a,b]):Nx(this,a,b,c)};
function Nx(a,b,c,d){d=void 0===d?0:d;var e=Pu(d);d=b||Nu(d);e&&d&&(a=a.client,b={cttAuthInfo:Su(e)||void 0,sequenceGroup:e},P("il_via_jspb")?(c=new gm,c.h(e),d=d.getAsJspb(),H(c,Sl,2,d),"UNDEFINED_CSN"===e?Bx("visualElementStateChanged",b,void 0,c):ku(c,b,a)):(c={csn:e,ve:d.getAsJson(),clientData:c},"UNDEFINED_CSN"===e?Bx("visualElementStateChanged",b,c):a?au("visualElementStateChanged",c,a,b):Fo("visualElementStateChanged",c,b)))}
function Jx(a,b,c){c=void 0===c?{}:c;a.i.add(c.layer||0);a.j=function(){Kx(a,b,c);var f=Nu(c.layer);if(f){for(var g=r(a.s),h=g.next();!h.done;h=g.next())h=h.value,Mx(a,h[0],h[1]||f,c.layer);f=r(a.v);for(g=f.next();!g.done;g=f.next())g=g.value,Nx(a,g[0],g[1])}};
Pu(c.layer)||a.j();if(c.ld)for(var d=r(c.ld),e=d.next();!e.done;e=d.next())Lx(a,e.value,c.layer);else tu(Error("Delayed screen needs a data promise."))}
function Kx(a,b,c){c=void 0===c?{}:c;var d=void 0;c.layer||(c.layer=0);d=void 0!==c.Le?c.Le:c.layer;var e=Pu(d);d=Nu(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=O("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var l=zx(a.client,b,f,c.kd,c.cttAuthInfo,g,c.yg,c.loggingExpectations)}catch(q){xu(q,{Jg:b,rootVe:d,Fg:void 0,ug:e,Eg:f,kd:c.kd});tu(q);
return}Tu(l,b,c.layer,c.cttAuthInfo);e&&"UNDEFINED_CSN"!==e&&d&&!Qu(e)&&Dx(a.client,e,d);a.h[a.h.length-1]&&!a.h[a.h.length-1].csn&&(a.h[a.h.length-1].csn=l||"");Rm(Bw)({clientScreenNonce:l},void 0,!1);Gx.h||(Gx.h=new Gx);Rm(Fx().h).bind(Fx())();var m=Nu(c.layer);e&&"UNDEFINED_CSN"!==e&&m&&(P("web_mark_root_visible")||P("music_web_mark_root_visible"))&&Rm(Cx)(void 0,l,m,void 0,void 0,void 0);a.i.delete(c.layer||0);a.j=void 0;var n;null==(n=a.H.get(c.layer))||n.forEach(function(q,u){q?Mx(a,u,q,c.layer):
m&&Mx(a,u,m,c.layer)});
Ox(a)}
function Ox(a){for(var b=0;b<a.m.length;b++){var c=a.m[b];try{c()}catch(d){tu(d)}}for(b=a.m.length=0;b<a.X.length;b++){c=a.X[b];try{c()}catch(d){tu(d)}}}
;function Px(){var a,b,c;return x(function(d){if(1==d.h)return a=jt().resolve(cx),a?w(d,Yw(a),2):(uu(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return uu(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.vg;return d.return(c)}uu(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;var Qx=y.caches,Rx;function Sx(a){var b=a.indexOf(":");return-1===b?{Cd:a}:{Cd:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Tx(){return x(function(a){if(void 0!==Rx)return a.return(Rx);Rx=new Promise(function(b){var c;return x(function(d){switch(d.h){case 1:return ya(d,2),w(d,Qx.open("test-only"),4);case 4:return w(d,Qx.delete("test-only"),5);case 5:Aa(d,3);break;case 2:if(c=Ba(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(Rx)})}
function Ux(a){var b,c,d,e,f,g,h;x(function(l){if(1==l.h)return w(l,Tx(),2);if(3!=l.h){if(!l.i)return l.return(!1);b=[];return w(l,Qx.keys(),3)}c=l.i;d=r(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Sx(f),h=g.datasyncId,!h||a.includes(h)||b.push(Qx.delete(f));return l.return(Promise.all(b).then(function(m){return m.some(function(n){return n})}))})}
function Vx(){var a,b,c,d,e,f,g;return x(function(h){if(1==h.h)return w(h,Tx(),2);if(3!=h.h){if(!h.i)return h.return(!1);a=po("cache contains other");return w(h,Qx.keys(),3)}b=h.i;c=r(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Sx(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Wx(){try{return!!self.localStorage}catch(a){return!1}}
;function Xx(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function Yx(a){if(Wx()){var b=Object.keys(window.localStorage);b=r(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Xx(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function Zx(){if(!Wx())return!1;var a=po(),b=Object.keys(window.localStorage);b=r(b);for(var c=b.next();!c.done;c=b.next())if(c=Xx(c.value),void 0!==c&&c!==a)return!0;return!1}
;function $x(){Px().then(function(a){a&&(Sp(a),Ux(a),Yx(a))})}
function ay(){var a=new ps;Hi.ea(function(){var b,c,d,e;return x(function(f){switch(f.h){case 1:if(P("ytidb_clear_optimizations_killswitch")){f.A(2);break}b=po("clear");if(b.startsWith("V")){var g=[b];Sp(g);Ux(g);Yx(g);return f.return()}c=Zx();return w(f,Vx(),3);case 3:return d=f.i,w(f,Tp(),4);case 4:if(e=f.i,!c&&!d&&!e)return f.return();case 2:a.oa()?$x():a.l.add("publicytnetworkstatus-online",$x,!0,void 0,void 0),f.h=0}})})}
;var mi=ia(["data-"]);function by(a){a&&(a.dataset?a.dataset[cy("loaded")]="true":li(a))}
function dy(a,b){return a?a.dataset?a.dataset[cy(b)]:a.getAttribute("data-"+b):null}
var ey={};function cy(a){return ey[a]||(ey[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var fy=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,gy=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function hy(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(fy,""),c=c.replace(gy,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else iy(a,b,c)}
function iy(a,b,c){c=void 0===c?null:c;var d=jy(a),e=document.getElementById(d),f=e&&dy(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=Ws(d,b),b=""+Ta(b),ky[b]=f),g||(e=ly(a,d,function(){dy(e,"loaded")||(by(e),Zs(d),nn(Za($s,d),0))},c)))}
function ly(a,b,c,d){d=void 0===d?null:d;var e=Ef("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);oi(e,Kk(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function my(a){a=jy(a);var b=document.getElementById(a);b&&($s(a),b.parentNode.removeChild(b))}
function ny(a,b){a&&b&&(a=""+Ta(b),(a=ky[a])&&Ys(a))}
function jy(a){var b=document.createElement("a");nc(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+tc(a)}
var ky={};var oy=[],py=!1;function qy(){if(!P("disable_biscotti_fetch_for_ad_blocker_detection")&&!P("disable_biscotti_fetch_entirely_for_all_web_clients")&&ev()){var a=O("PLAYER_VARS",{});if("1"!=sb(a)&&!fv(a)){var b=function(){py=!0;"google_ad_status"in window?Nm("DCLKSTAT",1):Nm("DCLKSTAT",2)};
try{hy("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}oy.push(Hi.ea(function(){if(!(py||"google_ad_status"in window)){try{ny("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}py=!0;Nm("DCLKSTAT",3)}},5E3))}}}
function ry(){var a=Number(O("DCLKSTAT",0));return isNaN(a)?0:a}
;var Dy=window,Ey,Fy=P("web_enable_lifecycle_monitoring")&&(null==(Ey=Dy.performance)?void 0:Ey.measure);function Gy(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?vo():d;this.l=c;this.i=d;this.j=new di;this.h=a;for(a={Za:0};a.Za<this.h.length;a={Eb:a.Eb,Za:a.Za},a.Za++)a.Eb=this.h[a.Za],c=function(e){return function(){e.Eb.Fc();b.h[e.Za].nc=!0;b.h.every(function(f){return!0===f.nc})&&b.j.resolve()}}(a),d=so(c,Hy(this,a.Eb)),this.h[a.Za]=Object.assign({},a.Eb,{Fc:c,
jobId:d})}
function Iy(a){var b=Array.from(a.h.keys()).sort(function(d,e){return Hy(a,a.h[e])-Hy(a,a.h[d])});
b=r(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],void 0===c.jobId||c.nc||(a.i.Ba(c.jobId),so(c.Fc,10))}
Gy.prototype.cancel=function(){for(var a=r(this.h),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.jobId||b.nc||this.i.Ba(b.jobId),b.nc=!0;this.j.resolve()};
function Hy(a,b){var c;return null!=(c=b.priority)?c:a.l}
;function Jy(a){this.state=a;this.plugins=[];this.s=void 0;this.v={};Fy&&window.performance.mark(this.state+"-start")}
k=Jy.prototype;k.install=function(a){this.plugins.push(a);return this};
k.uninstall=function(){var a=this;La.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);-1<b&&a.plugins.splice(b,1)})};
k.transition=function(a,b){var c=this;Ky(this);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.K===a}):f.from===c.state&&f.K===a});
if(d){this.j&&(Iy(this.j),this.j=void 0);Ly(this,a,b);this.state=a;Fy&&window.performance.mark(this.state+"-start");d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(My(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function My(a,b){var c=b.filter(function(e){return 10===Ny(a,e)}),d=b.filter(function(e){return 10!==Ny(a,e)});
return a.v.Ng?function(){var e=La.apply(0,arguments);return x(function(f){if(1==f.h)return w(f,a.Se.apply(a,[c].concat(ja(e))),2);a.Ld.apply(a,[d].concat(ja(e)));f.h=0})}:function(){var e=La.apply(0,arguments);
a.Te.apply(a,[c].concat(ja(e)));a.Ld.apply(a,[d].concat(ja(e)))}}
k.Te=function(a){var b=La.apply(1,arguments);vo();for(var c={},d=r(a),e=d.next();!e.done;c={ob:c.ob},e=d.next())c.ob=e.value,to(function(f){return function(){Oy(f.ob.name);f.ob.callback.apply(f.ob,ja(b));Py(f.ob.name)}}(c))};
k.Se=function(a){var b=La.apply(1,arguments),c,d,e,f;return x(function(g){1==g.h&&(vo(),c={},d=r(a),e=d.next());if(3!=g.h){if(e.done)return g.A(0);c.ab=e.value;c.Cb=void 0;f=function(h){return function(){Oy(h.ab.name);var l=h.ab.callback.apply(h.ab,ja(b));"function"===typeof(null==l?void 0:l.then)?h.Cb=l.then(function(){Py(h.ab.name)}):Py(h.ab.name)}}(c);
to(f);return c.Cb?w(g,c.Cb,3):g.A(3)}c={ab:c.ab,Cb:c.Cb};e=d.next();return g.A(2)})};
k.Ld=function(a){var b=La.apply(1,arguments),c=this,d=a.map(function(e){return{Fc:function(){Oy(e.name);e.callback.apply(e,ja(b));Py(e.name)},
priority:Ny(c,e)}});
d.length&&(this.j=new Gy(d))};
function Ny(a,b){var c,d;return null!=(d=null!=(c=a.s)?c:b.priority)?d:0}
function Ky(a){if(Fy){var b=a.state+"-start",c=a.state+"-end";window.performance.mark(c);window.performance.measure(a.state,b,c)}}
function Oy(a){Fy&&a&&window.performance.mark(a+"-start")}
function Py(a){if(Fy&&a){var b=a+"-start",c=a+"-end";window.performance.mark(c);window.performance.measure(a,b,c)}}
function Ly(a,b,c){Fy&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
da.Object.defineProperties(Jy.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function Qy(a){Jy.call(this,void 0===a?"document_active":a);var b=this;this.s=10;this.h=new Map;this.transitions=[{from:"document_active",K:"document_disposed_preventable",action:this.X},{from:"document_active",K:"document_disposed",action:this.l},{from:"document_disposed_preventable",K:"document_disposed",action:this.l},{from:"document_disposed_preventable",K:"flush_logs",action:this.m},{from:"document_disposed_preventable",K:"document_active",action:this.i},{from:"document_disposed",K:"flush_logs",
action:this.m},{from:"document_disposed",K:"document_active",action:this.i},{from:"document_disposed",K:"document_disposed",action:function(){}},
{from:"flush_logs",K:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
v(Qy,Jy);Qy.prototype.X=function(a,b){if(!this.h.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
Qy.prototype.l=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
Qy.prototype.m=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
Qy.prototype.i=function(){this.h=new Map};function Ry(a){Jy.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",K:"document_visible",action:this.i},{from:"document_visibility_unknown",K:"document_hidden",action:this.h},{from:"document_visibility_unknown",K:"document_foregrounded",action:this.m},{from:"document_visibility_unknown",K:"document_backgrounded",action:this.l},{from:"document_visible",K:"document_hidden",action:this.h},{from:"document_visible",K:"document_foregrounded",
action:this.m},{from:"document_visible",K:"document_visible",action:this.i},{from:"document_foregrounded",K:"document_visible",action:this.i},{from:"document_foregrounded",K:"document_hidden",action:this.h},{from:"document_foregrounded",K:"document_foregrounded",action:this.m},{from:"document_hidden",K:"document_visible",action:this.i},{from:"document_hidden",K:"document_backgrounded",action:this.l},{from:"document_hidden",K:"document_hidden",action:this.h},{from:"document_backgrounded",K:"document_hidden",
action:this.h},{from:"document_backgrounded",K:"document_backgrounded",action:this.l},{from:"document_backgrounded",K:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
P("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
v(Ry,Jy);Ry.prototype.i=function(a,b){a(null==b?void 0:b.event);P("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Ry.prototype.h=function(a,b){a(null==b?void 0:b.event);P("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Ry.prototype.l=function(a,b){a(null==b?void 0:b.event)};
Ry.prototype.m=function(a,b){a(null==b?void 0:b.event)};function Sy(){this.j=new Qy;this.l=new Ry}
Sy.prototype.install=function(){var a=La.apply(0,arguments),b=this;a.forEach(function(c){b.j.install(c)});
a.forEach(function(c){b.l.install(c)})};function Ty(){Sy.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));a={};this.install((a.flush_logs={callback:this.i},a))}
v(Ty,Sy);Ty.prototype.i=function(){if(P("web_fp_via_jspb")){var a=new Rl,b=Pu();b&&G(a,1,b);b=new sm;le(b,Rl,380,tm,a);gu(b);P("web_fp_via_jspb_and_json")&&Fo("finalPayload",{csn:Pu()})}else Fo("finalPayload",{csn:Pu()})};
Ty.prototype.h=function(){zu(Au)};function Uy(){}
function Vy(){var a=B("ytglobal.storage_");a||(a=new Uy,A("ytglobal.storage_",a));return a}
Uy.prototype.estimate=function(){var a,b,c;return x(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(Wy()):d.return()})};
function Wy(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
A("ytglobal.storageClass_",Uy);function Do(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=gn("ytidb_transaction_ended_event_rate_limit_session",.2)}
Do.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":P("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":P("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":Xy(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=gn("ytidb_transaction_ended_event_rate_limit_transaction",.1)&&this.h("idbTransactionEnded",
b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function Xy(a,b){Vy().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:Yy(null==c?void 0:c.usage),deviceStorageQuotaMbytes:Yy(null==c?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function Yy(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function Zy(a,b,c){K.call(this);var d=this;c=c||O("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.l=b||null;this.targetOrigin="*";this.m=c;this.sessionId=null;this.i="widget";this.M=!!a;this.H=function(e){a:if(!("*"!=d.m&&e.origin!=d.m||d.l&&e.source!=d.l||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.M&&(d.sessionId&&d.sessionId!=f.id||d.i&&d.i!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.m=d.targetOrigin=e.origin);d.l=e.source;d.sessionId=f.id;d.j&&(d.j(),d.j=null);break;case "command":d.s&&(!d.v||0<=fb(d.v,f.func))&&d.s(f.func,f.args,e.origin)}}};
this.v=this.j=this.s=null;window.addEventListener("message",this.H)}
v(Zy,K);Zy.prototype.sendMessage=function(a,b){if(b=b||this.l){this.sessionId&&(a.id=this.sessionId);this.i&&(a.channel=this.i);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){Tm(d)}}};
Zy.prototype.L=function(){window.removeEventListener("message",this.H);K.prototype.L.call(this)};function $y(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new Zy(!!O("WIDGET_ID_ENFORCE")),b=this.Ne.bind(this);a.s=b;a.v=null;this.h.i="widget";if(a=O("WIDGET_ID"))this.h.sessionId=a}
k=$y.prototype;k.Ne=function(a,b,c){"addEventListener"===a&&b?this.Ec(b[0],c):this.Vc(a,b,c)};
k.Vc=function(){};
k.xc=function(a){var b=this;return function(c){return b.sendMessage(a,c)}};
k.Ec=function(a,b){this.j[a]||"onReady"===a||(this.addEventListener(a,this.xc(a,b)),this.j[a]=!0)};
k.addEventListener=function(){};
k.qe=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Ac());this.sendMessage("onReady");gb(this.i,this.Jd,this);this.i=[]};
k.Ac=function(){return null};
function az(a,b){a.sendMessage("infoDelivery",b)}
k.Jd=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
k.sendMessage=function(a,b){this.Jd({event:a,info:void 0===b?null:b})};
k.dispose=function(){this.h=null};var bz={},cz=(bz["api.invalidparam"]=2,bz.auth=150,bz["drm.auth"]=150,bz["heartbeat.net"]=150,bz["heartbeat.servererror"]=150,bz["heartbeat.stop"]=150,bz["html5.unsupportedads"]=5,bz["fmt.noneavailable"]=5,bz["fmt.decode"]=5,bz["fmt.unplayable"]=5,bz["html5.missingapi"]=5,bz["html5.unsupportedlive"]=5,bz["drm.unavailable"]=5,bz["mrm.blocked"]=151,bz);var dz=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function ez(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function fz(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=r(dz);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function gz(a,b,c,d){if(Sa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function hz(a){$y.call(this);this.listeners=[];this.l=!1;this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.Ze.bind(this));this.addEventListener("onVolumeChange",this.af.bind(this));this.addEventListener("onApiChange",this.Ue.bind(this));this.addEventListener("onPlaybackQualityChange",this.We.bind(this));this.addEventListener("onPlaybackRateChange",this.Xe.bind(this));this.addEventListener("onStateChange",this.Ye.bind(this));this.addEventListener("onWebglSettingsChanged",
this.bf.bind(this))}
v(hz,$y);k=hz.prototype;
k.Vc=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&ez(a)){var d=b;if(Sa(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=fz(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=fz(e);break;case "loadPlaylist":case "cuePlaylist":e=gz(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);ez(a)&&az(this,this.Ac())}};
k.Ec=function(a,b){"onReady"===a?this.api.logApiCall(a+" invocation",b):"onError"===a&&this.l&&(this.api.logApiCall(a+" invocation",b,this.errorCode),this.errorCode=void 0);this.api.logApiCall(a+" registration",b);$y.prototype.Ec.call(this,a,b)};
k.xc=function(a,b){var c=this,d=$y.prototype.xc.call(this,a,b);return function(e){"onError"===a?c.api.logApiCall(a+" invocation",b,e):c.api.logApiCall(a+" invocation",b);d(e)}};
k.onReady=function(){var a=this.qe.bind(this);this.h.j=a;a=this.api.getVideoData();if(!a.isPlayable){this.l=!0;a=a.errorCode;var b=void 0===b?5:b;this.errorCode=a?cz[a]||b:b;this.sendMessage("onError",this.errorCode.toString())}};
k.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
k.Ac=function(){if(!this.api)return null;var a=this.api.getApiInterface();lb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
k.Ye=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());az(this,a)};
k.We=function(a){az(this,{playbackQuality:a})};
k.Xe=function(a){az(this,{playbackRate:a})};
k.Ue=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var l=f[g],m=this.api.getOption(e,l);b[e][l]=m}}this.sendMessage("apiInfoDelivery",b)};
k.af=function(){az(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
k.Ze=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());az(this,a)};
k.bf=function(){var a={sphericalProperties:this.api.getSphericalProperties()};az(this,a)};
k.dispose=function(){$y.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function iz(a){K.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.Fd,this)}
v(iz,K);k=iz.prototype;k.start=function(){this.started||this.h()||(this.started=!0,this.connection.lb("RECEIVING"))};
k.lb=function(a,b){this.started&&!this.h()&&this.connection.lb(a,b)};
k.Fd=function(a,b,c){if(this.started&&!this.h()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=jz(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=kz(a,c))&&this.lb(a,c))}}};
k.addListener=function(a){if(!(a in this.i)){var b=this.Ve.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
k.Ve=function(a,b){this.started&&!this.h()&&this.connection.lb(a,this.zc(a,b))};
k.zc=function(a,b){if(null!=b)return{value:b}};
k.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
k.L=function(){var a=this.connection;a.h()||ej(a.i,"command",this.Fd,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);K.prototype.L.call(this)};function lz(a,b){iz.call(this,b);this.api=a;this.start()}
v(lz,iz);lz.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
lz.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function jz(a,b){switch(a){case "loadVideoById":return a=fz(b),[a];case "cueVideoById":return a=fz(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=gz(b),[a];case "cuePlaylist":return a=gz(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function kz(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
lz.prototype.zc=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return iz.prototype.zc.call(this,a,b)};
lz.prototype.L=function(){iz.prototype.L.call(this);delete this.api};function mz(a){a=void 0===a?!1:a;K.call(this);this.i=new dj(a);Me(this,this.i)}
$a(mz,K);mz.prototype.subscribe=function(a,b,c){return this.h()?0:this.i.subscribe(a,b,c)};
mz.prototype.m=function(a,b){this.h()||this.i.cb.apply(this.i,arguments)};function nz(a,b,c){mz.call(this);this.l=a;this.j=b;this.id=c}
v(nz,mz);nz.prototype.lb=function(a,b){this.h()||this.l.lb(this.j,this.id,a,b)};
nz.prototype.L=function(){this.j=this.l=null;mz.prototype.L.call(this)};function oz(a,b,c){K.call(this);this.i=a;this.origin=c;this.j=Ks(window,"message",this.l.bind(this));this.connection=new nz(this,a,b);Me(this,this.connection)}
v(oz,K);oz.prototype.lb=function(a,b,c,d){this.h()||a!==this.i||(a={id:b,command:c},d&&(a.data=d),this.i.postMessage(JSON.stringify(a),this.origin))};
oz.prototype.l=function(a){if(!this.h()&&a.origin===this.origin){var b=a.data;if("string"===typeof b){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.h()||c.m("command",b.command,b.data,a.origin)}}}};
oz.prototype.L=function(){Ls(this.j);this.i=null;K.prototype.L.call(this)};function pz(){this.state=1;this.h=null}
k=pz.prototype;k.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterUrl)?d:null;if(a.interpreterSafeScript){d=a.interpreterSafeScript.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var f=zb();d=f?f.createScript(d):d;d=new Eb(d,Db)}else d=null!=(f=a.interpreterScript)?f:null;a.interpreterSafeUrl&&(e=a.interpreterSafeUrl,Cb("From proto message. b/166824318"),e=Ib(e.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());qz(this,d,e,a.program,b,c)}else uu(Error("Cannot initialize botguard without program"))};
function qz(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,hy(c,function(){window[g]?rz(a,d,g,e):(a.state=3,my(c),uu(new R("Unable to load Botguard","from "+c)))},f)):b?(f=Ef("SCRIPT"),b instanceof Eb?(b instanceof Eb&&b.constructor===Eb?b=b.j:(Pa(b),b="type_error:SafeScript"),f.textContent=b,ni(f)):f.textContent=b,f.nonce=rc(),document.head.appendChild(f),document.head.removeChild(f),window[g]?rz(a,d,g,e):(a.state=4,uu(new R("Unable to load Botguard from JS")))):uu(new R("Unable to load VM; no url or JS provided"))}
function rz(a,b,c,d){a.state=5;try{var e=new ei({program:b,ue:c,Oe:P("att_web_record_metrics")});e.df.then(function(){a.state=6;d&&d(b)});
a.Qc(e)}catch(f){a.state=7,f instanceof Error&&uu(f)}}
k.invoke=function(a){a=void 0===a?{}:a;return this.Tc()?this.Sd({jd:a}):null};
k.dispose=function(){this.Wc()};
k.Wc=function(){this.Qc(null);this.state=8};
k.Tc=function(){return!!this.h};
k.Sd=function(a){return this.h.Md(a)};
k.Qc=function(a){Ke(this.h);this.h=a};function sz(){var a=B("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function tz(){pz.apply(this,arguments)}
v(tz,pz);tz.prototype.Wc=function(){this.state=8};
tz.prototype.Qc=function(a){var b;null==(b=sz())||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.Md.bind(a)},A("yt.abuse.playerAttLoader",b),A("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(A("yt.abuse.playerAttLoader",null),A("yt.abuse.playerAttLoaderRun",null))};
tz.prototype.Tc=function(){return!!sz()};
tz.prototype.Sd=function(a){return sz().bgvmc(a)};var uz=new tz;function vz(){return uz.Tc()}
function wz(a){a=void 0===a?{}:a;return uz.invoke(a)}
;function xz(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||ub(b);this.assets=a.assets||{};this.attrs=a.attrs||ub(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
xz.prototype.clone=function(){var a=new xz,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Pa(c)?a[b]=ub(c):a[b]=c}return a};var yz=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function zz(a){a=a||"";if(window.spf){var b=a.match(yz);spf.style.load(a,b?b[1]:"",void 0)}else Az(a)}
function Az(a){var b=Bz(a),c=document.getElementById(b),d=c&&dy(c,"loaded");d||c&&!d||(c=Cz(a,b,function(){dy(c,"loaded")||(by(c),Zs(b),nn(Za($s,b),0))}))}
function Cz(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Kk(a);oc(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function Bz(a){var b=Ef("A");nc(b,new Lb(a,Mb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+tc(a)}
;function Dz(){K.call(this);this.i=[]}
v(Dz,K);Dz.prototype.L=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.callback,void 0)}K.prototype.L.call(this)};function Ez(){Dz.apply(this,arguments)}
v(Ez,Dz);function Fz(a,b,c,d,e){K.call(this);var f=this;this.v=b;this.webPlayerContextConfig=d;this.Vb=e;this.Oa=!1;this.api={};this.ha=this.s=null;this.T=new dj;this.i={};this.Y=this.ia=this.elementId=this.eb=this.config=null;this.V=!1;this.l=this.H=null;this.ma={};this.Wb=["onReady"];this.lastError=null;this.qb=NaN;this.M={};this.Xb=new Ez(this);this.aa=0;this.j=this.m=a;Me(this,this.T);Gz(this);Hz(this);Me(this,this.Xb);c?this.aa=nn(function(){f.loadNewVideoConfig(c)},0):d&&(Iz(this),Jz(this))}
v(Fz,K);k=Fz.prototype;k.getId=function(){return this.v};
k.loadNewVideoConfig=function(a){if(!this.h()){this.aa&&(window.clearTimeout(this.aa),this.aa=0);var b=a||{};b instanceof xz||(b=new xz(b));this.config=b;this.setConfig(a);Jz(this);this.isReady()&&Kz(this)}};
function Iz(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.v,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.v:a.config.attrs.id=a.v);var c;(null==(c=a.j)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
k.setConfig=function(a){this.eb=a;this.config=Lz(a);Iz(this);if(!this.ia){var b;this.ia=Mz(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.j&&(this.j.style.width=yi(Number(b)||b)),(a=a.height)&&this.j&&(this.j.style.height=yi(Number(a)||a))};
function Kz(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function Nz(a){var b=!0,c=Oz(a);c&&a.config&&(a=Pz(a),b=dy(c,"version")===a);return b&&!!B("yt.player.Application.create")}
function Jz(a){if(!a.h()&&!a.V){var b=Nz(a);if(b&&"html5"===(Oz(a)?"html5":null))a.Y="html5",a.isReady()||Qz(a);else if(Rz(a),a.Y="html5",b&&a.l&&a.m)a.m.appendChild(a.l),Qz(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.H=function(){c=!0;var d=Sz(a,"player_bootstrap_method")?B("yt.player.Application.createAlternate")||B("yt.player.Application.create"):B("yt.player.Application.create");var e=a.config?Lz(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig,a.Vb);Qz(a)};
a.V=!0;b?a.H():(hy(Pz(a),a.H),(b=Tz(a))&&zz(b),Uz(a)&&!c&&A("yt.player.Application.create",null))}}}
function Oz(a){var b=Df(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function Qz(a){if(!a.h()){var b=Oz(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.V=!1;if(!Sz(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}Vz(a)}else a.qb=nn(function(){Qz(a)},50)}}
function Vz(a){Gz(a);a.Oa=!0;var b=Oz(a);if(b){a.s=Wz(a,b,"addEventListener");a.ha=Wz(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=Wz(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.s&&a.s(g,a.i[g]);Kz(a);a.ia&&a.ia(a.api);a.T.cb("onReady",a.api)}
function Wz(a,b,c){var d=b[c];return function(){var e=La.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,uu(f))}}}
function Gz(a){a.Oa=!1;if(a.ha)for(var b in a.i)a.i.hasOwnProperty(b)&&a.ha(b,a.i[b]);for(var c in a.M)a.M.hasOwnProperty(c)&&window.clearTimeout(Number(c));a.M={};a.s=null;a.ha=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.eb};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
k.isReady=function(){return this.Oa};
function Hz(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){Zs("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){Zs("WATCH_LATER_VIDEO_REMOVED",b)})}
k.addEventListener=function(a,b){var c=this,d=Mz(this,b);d&&(0<=fb(this.Wb,a)||this.i[a]||(b=Xz(this,a),this.s&&this.s(a,b)),this.T.subscribe(a,d),"onReady"===a&&this.isReady()&&nn(function(){d(c.api)},0))};
k.removeEventListener=function(a,b){this.h()||(b=Mz(this,b))&&ej(this.T,a,b)};
function Mz(a,b){var c=b;if("string"===typeof b){if(a.ma[b])return a.ma[b];c=function(){var d=La.apply(0,arguments),e=B(b);if(e)try{e.apply(y,d)}catch(f){tu(f)}};
a.ma[b]=c}return c?c:null}
function Xz(a,b){var c="ytPlayer"+b+a.v;a.i[b]=c;y[c]=function(d){var e=nn(function(){if(!a.h()){try{a.T.cb(b,null!=d?d:void 0)}catch(h){uu(new R("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.v,data:d}))}var f=a.M,g=String(e);g in f&&delete f[g]}},0);
rb(a.M,String(e))};
return c}
k.getPlayerType=function(){return this.Y||(Oz(this)?"html5":null)};
k.getLastError=function(){return this.lastError};
function Rz(a){a.cancel();Gz(a);a.Y=null;a.config&&(a.config.loaded=!1);var b=Oz(a);b&&(Nz(a)||!Uz(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
k.cancel=function(){this.H&&ny(Pz(this),this.H);window.clearTimeout(this.qb);this.V=!1};
k.L=function(){Rz(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){tu(b)}this.ma=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(y[this.i[a]]=null);this.eb=this.config=this.api=null;delete this.m;delete this.j;K.prototype.L.call(this)};
function Uz(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function Pz(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Tz(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Sz(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===Wm(c||"","&")[b]}
function Lz(a){for(var b={},c=r(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?ub(e):e}return b}
;var Yz={},Zz="player_uid_"+(1E9*Math.random()>>>0);function $z(a,b){var c="player",d=!1;d=void 0===d?!0:d;c="string"===typeof c?Df(c):c;var e=Zz+"_"+Ta(c),f=Yz[e];if(f&&d)return aA(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Fz(c,e,a,b,void 0);Yz[e]=f;Zs("player-added",f.api);Ne(f,function(){delete Yz[f.getId()]});
return f.api}
function aA(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var bA=null,cA=null,dA=null;function eA(){fA()}
function gA(){fA()}
function fA(){var a=bA.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function hA(){bA&&bA.sendAbandonmentPing&&bA.sendAbandonmentPing();O("PL_ATT")&&uz.dispose();for(var a=Hi,b=0,c=oy.length;b<c;b++)a.Ba(oy[b]);oy.length=0;my("//static.doubleclick.net/instream/ad_status.js");py=!1;Nm("DCLKSTAT",0);Le(dA,cA);bA&&(bA.removeEventListener("onVideoDataChange",eA),bA.destroy())}
;function iA(a,b,c){a="ST-"+tc(a).toString(36);b=b?Cc(b):"";c=c||5;ev()&&Wn(a,b,c)}
;function jA(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=O("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=O("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=xc(window.location.href);g&&f.push(g);g=xc(d);if(0<=fb(f,g)||!g&&0==d.lastIndexOf("/",0))if(P("autoescape_tempdata_url")&&(f=document.createElement("a"),nc(f,d),d=f.href),d&&(d=yc(d),f=d.indexOf("#"),d=0>f?d:d.slice(0,f)))if(e&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:Pu()},b)),h){var h=parseInt(h,10);isFinite(h)&&0<h&&
iA(d,b,h)}else iA(d,b)}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var l=void 0===l?{}:l;var m=void 0===m?"":m;var n=void 0===n?window:n;c=n.location;a=Ec(a,l)+m;var q=void 0===q?ri:q;a:{q=void 0===q?ri:q;for(l=0;l<q.length;++l)if(m=q[l],m instanceof pi&&m.Ce(a)){q=new Lb(a,Mb);break a}q=void 0}q=q||Qb;if(q instanceof Lb)var u=Nb(q);else{b:if(hi){try{u=new URL(q)}catch(t){u="https:";break b}u=u.protocol}else c:{u=document.createElement("a");try{u.href=q}catch(t){u=void 0;break c}u=
u.protocol;u=":"===u||""===u?"https:":u}u="javascript:"!==u?q:void 0}void 0!==u&&(c.href=u)}return!0}
;A("yt.setConfig",Nm);A("yt.config.set",Nm);A("yt.setMsg",Vu);A("yt.msgs.set",Vu);A("yt.logging.errors.log",tu);
A("writeEmbed",function(){var a=O("PLAYER_CONFIG");if(!a){var b=O("PLAYER_VARS");b&&(a={args:b})}ov(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=O("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);Ow("embed",["ol"]);c=O("WEB_PLAYER_CONTEXT_CONFIGS").WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=an(window.location.href);
d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}var e;(null==(e=a.args)?0:e.autoplay)&&Ow("watch",["pbs","pbu","pbp"]);bA=$z(a,c);bA.addEventListener("onVideoDataChange",eA);bA.addEventListener("onReady",gA);a=O("POST_MESSAGE_ID","player");O("ENABLE_JS_API")?dA=new hz(bA):O("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(cA=new oz(window.parent,a,b),dA=new lz(bA,cA.connection));qy();P("ytidb_create_logger_embed_killswitch")||Co();a={};Ty.h||(Ty.h=new Ty);
Ty.h.install((a.flush_logs={callback:function(){Jt()}},a));
As();P("ytidb_clear_embedded_player")&&Hi.ea(function(){var f,g;if(!sx){var h=jt(),l={Nc:rx,Qd:qx};h.h.set(l.Nc,l);l={hd:{feedbackEndpoint:Av(lx),modifyChannelNotificationPreferenceEndpoint:Av(mx),playlistEditEndpoint:Av(nx),subscribeEndpoint:Av(jx),unsubscribeEndpoint:Av(kx),webPlayerShareEntityServiceEndpoint:Av(ox)}};var m=yv(),n={};m&&(n.client_location=m);void 0===f&&(f=Rn());void 0===g&&(g=h.resolve(rx));Xw(l,g,f,n);f={Nc:cx,Rd:Ww.h};h.h.set(f.Nc,f);sx=h.resolve(cx)}ay()})});
var kA=Rm(function(){Sw();pv();P("embeds_web_enable_ve_logging_unification")||Ix()}),lA=Rm(function(a){a.persisted||(Sw(),pv())}),mA=Rm(function(a){P("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?hA():a.persisted||hA()}),nA=Rm(hA);
window.addEventListener?(window.addEventListener("load",kA),window.addEventListener("pageshow",lA),window.addEventListener("pagehide",mA)):window.attachEvent&&(window.attachEvent("onload",kA),window.attachEvent("onunload",nA));A("yt.abuse.player.botguardInitialized",B("yt.abuse.player.botguardInitialized")||vz);A("yt.abuse.player.invokeBotguard",B("yt.abuse.player.invokeBotguard")||wz);A("yt.abuse.dclkstatus.checkDclkStatus",B("yt.abuse.dclkstatus.checkDclkStatus")||ry);
A("yt.player.exports.navigate",B("yt.player.exports.navigate")||jA);A("yt.util.activity.init",B("yt.util.activity.init")||Os);A("yt.util.activity.getTimeSinceActive",B("yt.util.activity.getTimeSinceActive")||Rs);A("yt.util.activity.setTimestamp",B("yt.util.activity.setTimestamp")||Ps);}).call(this);
