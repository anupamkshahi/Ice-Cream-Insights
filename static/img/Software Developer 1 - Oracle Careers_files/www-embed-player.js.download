(function(){'use strict';var r;function ba(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ca=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ea(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var fa=ea(this);function u(a,b){if(b)a:{var c=fa;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&b!=null&&ca(c,a,{configurable:!0,writable:!0,value:b})}}
u("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ca(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(Math.random()*1E9>>>0)+"_",e=0;return b});
u("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=fa[b[c]];typeof d==="function"&&typeof d.prototype[a]!="function"&&ca(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ha(ba(this))}})}return a});
function ha(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
var ia=typeof Object.create=="function"?Object.create:function(a){function b(){}
b.prototype=a;return new b},ka=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if(typeof Reflect!="undefined"&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){e===void 0&&(e=c);
e=ia(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),la;
if(typeof Object.setPrototypeOf=="function")la=Object.setPrototypeOf;else{var ma;a:{var na={a:!0},oa={};try{oa.__proto__=na;ma=oa.a;break a}catch(a){}ma=!1}la=ma?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var pa=la;
function w(a,b){a.prototype=ia(b.prototype);a.prototype.constructor=a;if(pa)pa(a,b);else for(var c in b)if(c!="prototype")if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Aa=b.prototype}
function y(a){var b=typeof Symbol!="undefined"&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if(typeof a.length=="number")return{next:ba(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function z(a){if(!(a instanceof Array)){a=y(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function qa(a){return ra(a,a)}
function ra(a,b){a.raw=b;Object.freeze&&(Object.freeze(a),Object.freeze(b));return a}
function sa(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ta=typeof Object.assign=="function"?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)sa(d,e)&&(a[e]=d[e])}return a};
u("Object.assign",function(a){return a||ta});
function ua(){this.D=!1;this.u=null;this.i=void 0;this.h=1;this.o=this.M=0;this.P=this.j=null}
function va(a){if(a.D)throw new TypeError("Generator is already running");a.D=!0}
ua.prototype.G=function(a){this.i=a};
function wa(a,b){a.j={exception:b,wd:!0};a.h=a.M||a.o}
ua.prototype.return=function(a){this.j={return:a};this.h=this.o};
ua.prototype.yield=function(a,b){this.h=b;return{value:a}};
ua.prototype.A=function(a){this.h=a};
function xa(a,b,c){a.M=b;c!=void 0&&(a.o=c)}
function ya(a,b){a.h=b;a.M=0}
function za(a){a.M=0;var b=a.j.exception;a.j=null;return b}
function Aa(a){var b=a.P.splice(0)[0];(b=a.j=a.j||b)?b.wd?a.h=a.M||a.o:b.A!=void 0&&a.o<b.A?(a.h=b.A,a.j=null):a.h=a.o:a.h=0}
function Ba(a){this.h=new ua;this.i=a}
function Ca(a,b){va(a.h);var c=a.h.u;if(c)return Da(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ea(a)}
function Da(a,b,c,d){try{var e=b.call(a.h.u,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.D=!1,e;var f=e.value}catch(g){return a.h.u=null,wa(a.h,g),Ea(a)}a.h.u=null;d.call(a.h,f);return Ea(a)}
function Ea(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.D=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,wa(a.h,c)}a.h.D=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.wd)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Fa(a){this.next=function(b){va(a.h);a.h.u?b=Da(a,a.h.u.next,b,a.h.G):(a.h.G(b),b=Ea(a));return b};
this.throw=function(b){va(a.h);a.h.u?b=Da(a,a.h.u["throw"],b,a.h.G):(wa(a.h,b),b=Ea(a));return b};
this.return=function(b){return Ca(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ga(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function B(a){return Ga(new Fa(new Ba(a)))}
function C(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
u("globalThis",function(a){return a||fa});
u("Reflect",function(a){return a?a:{}});
u("Reflect.construct",function(){return ka});
u("Reflect.setPrototypeOf",function(a){return a?a:pa?function(b,c){try{return pa(b,c),!0}catch(d){return!1}}:null});
u("Promise",function(a){function b(g){this.X=0;this.ab=void 0;this.h=[];this.u=!1;var h=this.i();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(this.h==null){this.h=[];var h=this;this.j(function(){h.u()})}this.h.push(g)};
var e=fa.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.u=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.o(l)}}}this.h=null};
c.prototype.o=function(g){this.j(function(){throw g;})};
b.prototype.i=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.U),reject:g(this.j)}};
b.prototype.U=function(g){if(g===this)this.j(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.Z(g);else{a:switch(typeof g){case "object":var h=g!=null;break a;case "function":h=!0;break a;default:h=!1}h?this.P(g):this.o(g)}};
b.prototype.P=function(g){var h=void 0;try{h=g.then}catch(k){this.j(k);return}typeof h=="function"?this.ha(h,g):this.o(g)};
b.prototype.j=function(g){this.M(2,g)};
b.prototype.o=function(g){this.M(1,g)};
b.prototype.M=function(g,h){if(this.X!=0)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.X);this.X=g;this.ab=h;this.X===2&&this.Y();this.D()};
b.prototype.Y=function(){var g=this;e(function(){if(g.G()){var h=fa.console;typeof h!=="undefined"&&h.error(g.ab)}},1)};
b.prototype.G=function(){if(this.u)return!1;var g=fa.CustomEvent,h=fa.Event,k=fa.dispatchEvent;if(typeof k==="undefined")return!0;typeof g==="function"?g=new g("unhandledrejection",{cancelable:!0}):typeof h==="function"?g=new h("unhandledrejection",{cancelable:!0}):(g=fa.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.ab;return k(g)};
b.prototype.D=function(){if(this.h!=null){for(var g=0;g<this.h.length;++g)f.i(this.h[g]);this.h=null}};
var f=new c;b.prototype.Z=function(g){var h=this.i();g.ic(h.resolve,h.reject)};
b.prototype.ha=function(g,h){var k=this.i();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(p,t){return typeof p=="function"?function(v){try{l(p(v))}catch(x){m(x)}}:t}
var l,m,n=new b(function(p,t){l=p;m=t});
this.ic(k(g,l),k(h,m));return n};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.ic=function(g,h){function k(){switch(l.X){case 1:g(l.ab);break;case 2:h(l.ab);break;default:throw Error("Unexpected state: "+l.X);}}
var l=this;this.h==null?f.i(k):this.h.push(k);this.u=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=y(g),m=l.next();!m.done;m=l.next())d(m.value).ic(h,k)})};
b.all=function(g){var h=y(g),k=h.next();return k.done?d([]):new b(function(l,m){function n(v){return function(x){p[v]=x;t--;t==0&&l(p)}}
var p=[],t=0;do p.push(void 0),t++,d(k.value).ic(n(p.length-1),m),k=h.next();while(!k.done)})};
return b});
u("Object.setPrototypeOf",function(a){return a||pa});
u("Symbol.dispose",function(a){return a?a:Symbol("Symbol.dispose")});
u("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=y(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return l==="object"&&k!==null||l==="function"}
function e(k){if(!sa(k,g)){var l=new c;ca(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(m.get(k)!=2||m.get(l)!=3)return!1;m.delete(k);m.set(l,4);return!m.has(k)&&m.get(l)==4}catch(n){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!sa(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&sa(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&sa(k,g)&&sa(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&sa(k,g)&&sa(k[g],this.h)?delete k[g][this.h]:!1};
return b});
u("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return ha(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;l=="object"||l=="function"?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h[0][l];if(m&&sa(h[0],l))for(h=0;h<m.length;h++){var n=m[h];if(k!==k&&n.key!==n.key||k===n.key)return{id:l,list:m,index:h,entry:n}}return{id:l,list:m,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=y(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var h=Object.seal({x:4}),k=new a(y([[h,"s"]]));if(k.get(h)!="s"||k.size!=1||k.get({x:4})||k.set({x:4},"t")!=k||k.size!=2)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||m.value[1]!="s")return!1;m=l.next();return m.done||m.value[0].x!=4||m.value[1]!="t"||!l.next().done?!1:!0}catch(n){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=h===0?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
u("Set",function(a){function b(c){this.h=new Map;if(c){c=y(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var c=Object.seal({x:4}),d=new a(y([c]));if(!d.has(c)||d.size!=1||d.add(c)!=d||d.size!=1||d.add({x:4})!=d||d.size!=2)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||f.value[0].x!=4||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=c===0?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
function Ja(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
u("Array.prototype.entries",function(a){return a?a:function(){return Ja(this,function(b,c){return[b,c]})}});
u("Array.prototype.keys",function(a){return a?a:function(){return Ja(this,function(b){return b})}});
function Ka(a,b,c){if(a==null)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
u("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ka(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
u("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ka(this,b,"endsWith");b+="";c===void 0&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;e>0&&c>0;)if(d[--c]!=b[--e])return!1;return e<=0}});
u("Number.isFinite",function(a){return a?a:function(b){return typeof b!=="number"?!1:!isNaN(b)&&b!==Infinity&&b!==-Infinity}});
u("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
u("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)sa(b,d)&&c.push(b[d]);return c}});
u("Object.is",function(a){return a?a:function(b,c){return b===c?b!==0||1/b===1/c:b!==b&&c!==c}});
u("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(c<0&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
u("String.prototype.includes",function(a){return a?a:function(b,c){return Ka(this,b,"includes").indexOf(b,c||0)!==-1}});
u("Array.from",function(a){return a?a:function(b,c,d){c=c!=null?c:function(h){return h};
var e=[],f=typeof Symbol!="undefined"&&Symbol.iterator&&b[Symbol.iterator];if(typeof f=="function"){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
u("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)sa(b,d)&&c.push([d,b[d]]);return c}});
u("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
u("Number.MIN_SAFE_INTEGER",function(){return-9007199254740991});
u("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
u("Number.isSafeInteger",function(a){return a?a:function(b){return Number.isInteger(b)&&Math.abs(b)<=Number.MAX_SAFE_INTEGER}});
u("Math.trunc",function(a){return a?a:function(b){b=Number(b);if(isNaN(b)||b===Infinity||b===-Infinity||b===0)return b;var c=Math.floor(Math.abs(b));return b<0?-c:c}});
u("Number.isNaN",function(a){return a?a:function(b){return typeof b==="number"&&isNaN(b)}});
u("Array.prototype.values",function(a){return a?a:function(){return Ja(this,function(b,c){return c})}});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var La=La||{},D=this||self;function E(a,b,c){a=a.split(".");c=c||D;for(var d;a.length&&(d=a.shift());)a.length||b===void 0?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function F(a,b){a=a.split(".");b=b||D;for(var c=0;c<a.length;c++)if(b=b[a[c]],b==null)return null;return b}
function Ma(a){var b=typeof a;return b!="object"?b:a?Array.isArray(a)?"array":b:"null"}
function Na(a){var b=Ma(a);return b=="array"||b=="object"&&typeof a.length=="number"}
function Oa(a){var b=typeof a;return b=="object"&&a!=null||b=="function"}
function Ra(a){return Object.prototype.hasOwnProperty.call(a,Sa)&&a[Sa]||(a[Sa]=++Ta)}
var Sa="closure_uid_"+(Math.random()*1E9>>>0),Ta=0;function Ua(a,b,c){return a.call.apply(a.bind,arguments)}
function Va(a,b,c){if(!a)throw Error();if(arguments.length>2){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Wa(a,b,c){Wa=Function.prototype.bind&&Function.prototype.bind.toString().indexOf("native code")!=-1?Ua:Va;return Wa.apply(null,arguments)}
function Xa(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function $a(){return Date.now()}
function ab(a,b){function c(){}
c.prototype=b.prototype;a.Aa=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
;function bb(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,bb);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));b!==void 0&&(this.cause=b)}
ab(bb,Error);bb.prototype.name="CustomError";var cb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};/*

 Copyright Google LLC
 SPDX-License-Identifier: Apache-2.0
*/
var db=globalThis.trustedTypes,eb;function fb(){var a=null;if(!db)return a;try{var b=function(c){return c};
a=db.createPolicy("goog#html",{createHTML:b,createScript:b,createScriptURL:b})}catch(c){}return a}
function gb(){eb===void 0&&(eb=fb());return eb}
;function hb(a){this.h=a}
hb.prototype.toString=function(){return this.h+""};
function ib(a){var b=gb();return new hb(b?b.createScriptURL(a):a)}
function jb(a){if(a instanceof hb)return a.h;throw Error("");}
;var kb=qa([""]),lb=ra(["\x00"],["\\0"]),mb=ra(["\n"],["\\n"]),nb=ra(["\x00"],["\\u0000"]);function ob(a){return a.toString().indexOf("`")===-1}
ob(function(a){return a(kb)})||ob(function(a){return a(lb)})||ob(function(a){return a(mb)})||ob(function(a){return a(nb)});function pb(a){this.h=a}
pb.prototype.toString=function(){return this.h};
var qb=new pb("about:invalid#zClosurez");function rb(a){this.Fe=a}
function sb(a){return new rb(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var tb=[sb("data"),sb("http"),sb("https"),sb("mailto"),sb("ftp"),new rb(function(a){return/^[^:]*([/?#]|$)/.test(a)})],ub=/^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
function vb(a){if(a instanceof pb)if(a instanceof pb)a=a.h;else throw Error("");else a=ub.test(a)?a:void 0;return a}
;function wb(a,b){b=vb(b);b!==void 0&&(a.href=b)}
;function xb(a,b){throw Error(b===void 0?"unexpected value "+a+"!":b);}
;function zb(a){this.h=a}
zb.prototype.toString=function(){return this.h+""};function Ab(a){a=a===void 0?document:a;var b,c;a=(c=(b=a).querySelector)==null?void 0:c.call(b,"script[nonce]");return a==null?"":a.nonce||a.getAttribute("nonce")||""}
;function Bb(a){this.h=a}
Bb.prototype.toString=function(){return this.h+""};
function Cb(a){var b=gb();return new Bb(b?b.createScript(a):a)}
function Db(a){if(a instanceof Bb)return a.h;throw Error("");}
;function Eb(a){var b=Ab(a.ownerDocument);b&&a.setAttribute("nonce",b)}
function Fb(a,b){a.src=jb(b);Eb(a)}
;function Gb(){this.h=Hb[0].toLowerCase()}
Gb.prototype.toString=function(){return this.h};function Ib(a){var b="true".toString(),c=[new Gb];if(c.length===0)throw Error("");if(c.map(function(d){if(d instanceof Gb)d=d.h;else throw Error("");return d}).every(function(d){return"data-loaded".indexOf(d)!==0}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;var Jb="alternate author bookmark canonical cite help icon license modulepreload next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");function Kb(a,b){if(b instanceof hb)a.href=jb(b).toString(),a.rel="stylesheet";else{if(Jb.indexOf("stylesheet")===-1)throw Error('TrustedResourceUrl href attribute required with rel="stylesheet"');b=vb(b);b!==void 0&&(a.href=b,a.rel="stylesheet")}}
;var Lb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if(typeof a==="string")return typeof b!=="string"||b.length!=1?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},Mb=Array.prototype.forEach?function(a,b){Array.prototype.forEach.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)e in d&&b.call(void 0,d[e],e,a)},Ob=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f=typeof a==="string"?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},Pb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e=typeof a==="string"?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},Qb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
Mb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Rb(a,b){a:{for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return b<0?null:typeof a==="string"?a.charAt(b):a[b]}
function Sb(a,b){b=Lb(a,b);var c;(c=b>=0)&&Array.prototype.splice.call(a,b,1);return c}
function Tb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Na(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function Ub(a,b){a.__closure__error__context__984382||(a.__closure__error__context__984382={});a.__closure__error__context__984382.severity=b}
;function Vb(a){var b=F("window.location.href");a==null&&(a='Unknown Error of type "null/undefined"');if(typeof a==="string")return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||D.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Wb(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(c==
null){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Xb[c])c=Xb[c];else{c=String(c);if(!Xb[c]){var f=/function\s+([^\(]+)/m.exec(c);Xb[c]=f?f[1]:"[Anonymous]"}c=Xb[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";typeof a.toString==="function"&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}return{message:a.message,
name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:b}}
function Wb(a,b){b||(b={});b[Yb(a)]=!0;var c=a.stack||"",d=a.cause;d&&!b[Yb(d)]&&(c+="\nCaused by: ",d.stack&&d.stack.indexOf(d.toString())==0||(c+=typeof d==="string"?d:d.message+"\n"),c+=Wb(d,b));a=a.errors;if(Array.isArray(a)){d=1;var e;for(e=0;e<a.length&&!(d>4);e++)b[Yb(a[e])]||(c+="\nInner error "+d++ +": ",a[e].stack&&a[e].stack.indexOf(a[e].toString())==0||(c+=typeof a[e]==="string"?a[e]:a[e].message+"\n"),c+=Wb(a[e],b));e<a.length&&(c+="\n... "+(a.length-e)+" more inner errors")}return c}
function Yb(a){var b="";typeof a.toString==="function"&&(b=""+a);return b+a.stack}
var Xb={};function Zb(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var $b=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function ac(a){return a?decodeURI(a):a}
function bc(a,b){return b.match($b)[a]||null}
function cc(a){return ac(bc(3,a))}
function dc(a){var b=a.match($b);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function ec(a){var b=a.indexOf("#");return b<0?a:a.slice(0,b)}
function fc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)fc(a,String(b[d]),c);else b!=null&&c.push(a+(b===""?"":"="+encodeURIComponent(String(b))))}
function hc(a){var b=[],c;for(c in a)fc(c,a[c],b);return b.join("&")}
function ic(a,b){b=hc(b);if(b){var c=a.indexOf("#");c<0&&(c=a.length);var d=a.indexOf("?");if(d<0||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
function jc(a,b,c,d){for(var e=c.length;(b=a.indexOf(c,b))>=0&&b<d;){var f=a.charCodeAt(b-1);if(f==38||f==63)if(f=a.charCodeAt(b+e),!f||f==61||f==38||f==35)return b;b+=e+1}return-1}
var kc=/#|$/,lc=/[?&]($|#)/;function mc(a,b){for(var c=a.search(kc),d=0,e,f=[];(e=jc(a,d,b,c))>=0;)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(lc,"$1")}
;var nc=(new Date("2024-01-01T00:00:00Z")).getTime();function oc(a){var b=C.apply(1,arguments).filter(function(d){return d}).join("&");
if(!b)return a;var c=a.match(/[?&]adurl=/);return c?a.slice(0,c.index+1)+b+"&"+a.slice(c.index+1):a+(a.indexOf("?")===-1?"?":"&")+b}
function pc(a){var b=a.url;a=a.Zh;this.j=b;this.D=a;a=/[?&]dsh=1(&|$)/.test(b);this.u=!a&&/[?&]ae=1(&|$)/.test(b);this.M=!a&&/[?&]ae=2(&|$)/.test(b);if((this.h=/[?&]adurl=([^&]*)/.exec(b))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}this.o=(new Date).getTime()-nc}
function qc(a){a=a.D;if(!a)return"";var b="";a.platform&&(b+="&uap="+encodeURIComponent(a.platform));a.platformVersion&&(b+="&uapv="+encodeURIComponent(a.platformVersion));a.uaFullVersion&&(b+="&uafv="+encodeURIComponent(a.uaFullVersion));a.architecture&&(b+="&uaa="+encodeURIComponent(a.architecture));a.model&&(b+="&uam="+encodeURIComponent(a.model));a.bitness&&(b+="&uab="+encodeURIComponent(a.bitness));a.fullVersionList&&(b+="&uafvl="+encodeURIComponent(a.fullVersionList.map(function(c){return encodeURIComponent(c.brand)+
";"+encodeURIComponent(c.version)}).join("|")));
typeof a.wow64!=="undefined"&&(b+="&uaw="+Number(a.wow64));return b.substring(1)}
;function rc(){try{var a,b;return!!((a=window)==null?0:(b=a.top)==null?0:b.location.href)&&!1}catch(c){return!0}}
;function sc(a){a&&typeof a.dispose=="function"&&a.dispose()}
;function tc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Na(d)?tc.apply(null,d):sc(d)}}
;function G(){this.ea=this.ea;this.M=this.M}
G.prototype.ea=!1;G.prototype.dispose=function(){this.ea||(this.ea=!0,this.ba())};
G.prototype[Symbol.dispose]=function(){this.dispose()};
function uc(a,b){a.addOnDisposeCallback(Xa(sc,b))}
G.prototype.addOnDisposeCallback=function(a,b){this.ea?b!==void 0?a.call(b):a():(this.M||(this.M=[]),b&&(a=a.bind(b)),this.M.push(a))};
G.prototype.ba=function(){if(this.M)for(;this.M.length;)this.M.shift()()};function vc(){var a=wc();a=a===void 0?"bevasrsg":a;return new Promise(function(b){var c=window===window.top?window:rc()?window:window.top,d=c[a],e;((e=d)==null?0:e.bevasrs)?b(new xc(d.bevasrs)):(d||(d={},d=(d.nqfbel=[],d),c[a]=d),d.nqfbel.push(function(f){b(new xc(f))}))})}
function xc(a){G.call(this);var b=this;this.vm=a;this.i="keydown keypress keyup input focusin focusout select copy cut paste change click dblclick auxclick pointerover pointerdown pointerup pointermove pointerout dragenter dragleave drag dragend mouseover mousedown mouseup mousemove mouseout touchstart touchend touchmove wheel".split(" ");this.h=void 0;this.Yc=this.vm.p;this.j=this.o.bind(this);this.addOnDisposeCallback(function(){return void yc(b)})}
w(xc,G);xc.prototype.snapshot=function(a){return this.vm.s(Object.assign({},a.wb&&{c:a.wb},a.bd&&{s:a.bd},a.cd!==void 0&&{p:a.cd}))};
xc.prototype.o=function(a){this.vm.e(a)};
function yc(a){a.h!==void 0&&(a.i.forEach(function(b){var c;(c=a.h)==null||c.removeEventListener(b,a.j)}),a.h=void 0)}
;function zc(a){var b=b===void 0?48:b;var c=[];Ac(a,Bc,6).forEach(function(d){Cc(d,2)<=b&&c.push(Cc(d,1))});
return c}
function Dc(a){var b=b===void 0?48:b;var c=[];Ac(a,Bc,6).forEach(function(d){Cc(d,2)>b&&c.push(Cc(d,1))});
return c}
;var Ec;function Fc(){G.apply(this,arguments);this.j=1;this[Ec]=this.dispose}
w(Fc,G);Fc.prototype.share=function(){if(this.ea)throw Error("E:AD");this.j++;return this};
Fc.prototype.dispose=function(){--this.j||G.prototype.dispose.call(this)};
Ec=Symbol.dispose;function Gc(a){return{fieldType:2,fieldName:a}}
function Hc(a){return{fieldType:3,fieldName:a}}
;function Ic(a){this.h=a;a.Hc("/client_streamz/bg/frs",Hc("mk"))}
Ic.prototype.record=function(a,b){this.h.record("/client_streamz/bg/frs",a,b)};
function Jc(a){this.h=a;a.Hc("/client_streamz/bg/wrl",Hc("mn"),Gc("ac"),Gc("sc"),Hc("rk"),Hc("mk"))}
Jc.prototype.record=function(a,b,c,d,e,f){this.h.record("/client_streamz/bg/wrl",a,b,c,d,e,f)};
function Kc(a){this.h=a;a.Mb("/client_streamz/bg/ec",Hc("en"),Hc("mk"))}
Kc.prototype.kb=function(a,b){this.h.Jb("/client_streamz/bg/ec",a,b)};
function Lc(a){this.h=a;a.Hc("/client_streamz/bg/el",Hc("en"),Hc("rk"),Hc("mk"))}
Lc.prototype.record=function(a,b,c,d){this.h.record("/client_streamz/bg/el",a,b,c,d)};
function Mc(a){this.h=a;a.Mb("/client_streamz/bg/cec",Gc("ec"),Hc("rk"),Hc("mk"))}
Mc.prototype.kb=function(a,b,c){this.h.Jb("/client_streamz/bg/cec",a,b,c)};
function Nc(a){this.h=a;a.Mb("/client_streamz/bg/po/csc",Gc("cs"),Hc("rk"),Hc("mk"))}
Nc.prototype.kb=function(a,b,c){this.h.Jb("/client_streamz/bg/po/csc",a,b,c)};
function Oc(a){this.h=a;a.Mb("/client_streamz/bg/po/ctav",Hc("av"),Hc("rk"),Hc("mk"))}
Oc.prototype.kb=function(a,b,c){this.h.Jb("/client_streamz/bg/po/ctav",a,b,c)};
function Pc(a){this.h=a;a.Mb("/client_streamz/bg/po/cwsc",Hc("su"),Hc("rk"),Hc("mk"))}
Pc.prototype.kb=function(a,b,c){this.h.Jb("/client_streamz/bg/po/cwsc",a,b,c)};function Qc(a){D.setTimeout(function(){throw a;},0)}
;var Rc,Sc=F("CLOSURE_FLAGS"),Tc=Sc&&Sc[610401301];Rc=Tc!=null?Tc:!1;function Uc(){var a=D.navigator;return a&&(a=a.userAgent)?a:""}
var Vc,Wc=D.navigator;Vc=Wc?Wc.userAgentData||null:null;function Xc(a){if(!Rc||!Vc)return!1;for(var b=0;b<Vc.brands.length;b++){var c=Vc.brands[b].brand;if(c&&c.indexOf(a)!=-1)return!0}return!1}
function I(a){return Uc().indexOf(a)!=-1}
;function Yc(){return Rc?!!Vc&&Vc.brands.length>0:!1}
function Zc(){return Yc()?!1:I("Opera")}
function $c(){return I("Firefox")||I("FxiOS")}
function ad(){return Yc()?Xc("Chromium"):(I("Chrome")||I("CriOS"))&&!(Yc()?0:I("Edge"))||I("Silk")}
;function bd(){return Rc?!!Vc&&!!Vc.platform:!1}
function cd(){return I("iPhone")&&!I("iPod")&&!I("iPad")}
;function dd(a){dd[" "](a);return a}
dd[" "]=function(){};var ed=Zc(),fd=Yc()?!1:I("Trident")||I("MSIE"),gd=I("Edge"),hd=I("Gecko")&&!(Uc().toLowerCase().indexOf("webkit")!=-1&&!I("Edge"))&&!(I("Trident")||I("MSIE"))&&!I("Edge"),id=Uc().toLowerCase().indexOf("webkit")!=-1&&!I("Edge");id&&I("Mobile");bd()||I("Macintosh");bd()||I("Windows");(bd()?Vc.platform==="Linux":I("Linux"))||bd()||I("CrOS");var jd=bd()?Vc.platform==="Android":I("Android");cd();I("iPad");I("iPod");cd()||I("iPad")||I("iPod");Uc().toLowerCase().indexOf("kaios");$c();var kd=cd()||I("iPod"),ld=I("iPad");!I("Android")||ad()||$c()||Zc()||I("Silk");ad();var md=I("Safari")&&!(ad()||(Yc()?0:I("Coast"))||Zc()||(Yc()?0:I("Edge"))||(Yc()?Xc("Microsoft Edge"):I("Edg/"))||(Yc()?Xc("Opera"):I("OPR"))||$c()||I("Silk")||I("Android"))&&!(cd()||I("iPad")||I("iPod"));var nd={},od=null;function pd(a,b){Na(a);b===void 0&&(b=0);qd();b=nd[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function rd(a){var b=a.length,c=b*3/4;c%3?c=Math.floor(c):"=.".indexOf(a[b-1])!=-1&&(c="=.".indexOf(a[b-2])!=-1?c-2:c-1);var d=new Uint8Array(c),e=0;sd(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function sd(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),m=od[l];if(m!=null)return m;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
qd();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(h===64&&e===-1)break;b(e<<2|f>>4);g!=64&&(b(f<<4&240|g>>2),h!=64&&b(g<<6&192|h))}}
function qd(){if(!od){od={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;c<5;c++){var d=a.concat(b[c].split(""));nd[c]=d;for(var e=0;e<d.length;e++){var f=d[e];od[f]===void 0&&(od[f]=e)}}}}
;var td=typeof Uint8Array!=="undefined",ud=!fd&&typeof btoa==="function",vd=/[-_.]/g,wd={"-":"+",_:"/",".":"="};function xd(a){return wd[a]||""}
var yd={};function zd(a,b){Ad(b);this.h=a;if(a!=null&&a.length===0)throw Error("ByteString should be constructed with non-empty values");}
zd.prototype.sizeBytes=function(){Ad(yd);var a=this.h;if(!(a==null||td&&a!=null&&a instanceof Uint8Array))if(typeof a==="string")if(ud){vd.test(a)&&(a=a.replace(vd,xd));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=rd(a);else Ma(a),a=null;return(a=a==null?a:this.h=a)?a.length:0};
var Bd;function Ad(a){if(a!==yd)throw Error("illegal external caller");}
;var Cd=void 0;function Dd(a){a=Error(a);Ub(a,"warning");return a}
function Ed(a,b){if(a!=null){var c;var d=(c=Cd)!=null?c:Cd={};c=d[a]||0;c>=b||(d[a]=c+1,a=Error(),Ub(a,"incident"),Qc(a))}}
;var Fd=typeof Symbol==="function"&&typeof Symbol()==="symbol";function Gd(a,b,c){return typeof Symbol==="function"&&typeof Symbol()==="symbol"?(c===void 0?0:c)&&Symbol.for&&a?Symbol.for(a):a!=null?Symbol(a):Symbol():b}
var Hd=Gd("jas",void 0,!0),Id=Gd(void 0,"1oa"),Jd=Gd(void 0,"0actk"),Kd=Gd("m_m","Lh",!0),Ld=Gd(void 0,"mrtk"),Md=Gd(void 0,"vps");Math.max.apply(Math,z(Object.values({mh:1,lh:2,kh:4,ph:8,oh:16,nh:32,Nf:64,rh:128,ih:256,hh:512,Tf:1024,qh:2048,Uf:4096,Of:8192,jh:16384})));var Nd={Ee:{value:0,configurable:!0,writable:!0,enumerable:!1}},Od=Object.defineProperties,J=Fd?Hd:"Ee",Pd,Qd=[];Rd(Qd,55);Pd=Object.freeze(Qd);function Sd(a,b){Fd||J in a||Od(a,Nd);a[J]|=b}
function Rd(a,b){Fd||J in a||Od(a,Nd);a[J]=b}
;var Td=typeof Kd==="symbol",Ud={};function L(a){a=a[Kd];var b=a===Ud;Td&&a&&!b&&Ed(Ld,3);return b}
function Vd(a){return a!==null&&typeof a==="object"&&!Array.isArray(a)&&a.constructor===Object}
function Wd(a){if(a&2)throw Error();}
var Xd=Object.freeze({}),Yd={};function Zd(){return typeof BigInt==="function"}
;function $d(a){a.Gh=!0;return a}
;var ae=$d(function(a){return typeof a==="number"}),be=$d(function(a){return typeof a==="string"}),ce=$d(function(a){return typeof a==="boolean"});
function de(){var a=ee;return $d(function(b){for(var c in a)if(b===a[c]&&!/^[0-9]+$/.test(c))return!0;return!1})}
var fe=$d(function(a){return a!=null&&typeof a==="object"&&typeof a.then==="function"});var ge=typeof D.BigInt==="function"&&typeof D.BigInt(0)==="bigint";function he(a){var b=a;if(be(b)){if(!/^\s*(?:-?[1-9]\d*|0)?\s*$/.test(b))throw Error(String(b));}else if(ae(b)&&!Number.isSafeInteger(b))throw Error(String(b));return ge?BigInt(a):a=ce(a)?a?"1":"0":be(a)?a.trim()||"0":String(a)}
var ne=$d(function(a){return ge?a>=ie&&a<=je:a[0]==="-"?ke(a,le):ke(a,me)}),le=Number.MIN_SAFE_INTEGER.toString(),ie=ge?BigInt(Number.MIN_SAFE_INTEGER):void 0,me=Number.MAX_SAFE_INTEGER.toString(),je=ge?BigInt(Number.MAX_SAFE_INTEGER):void 0;
function ke(a,b){if(a.length>b.length)return!1;if(a.length<b.length||a===b)return!0;for(var c=0;c<a.length;c++){var d=a[c],e=b[c];if(d>e)return!1;if(d<e)return!0}}
;var oe=0,pe=0;function qe(a){var b=a>>>0;oe=b;pe=(a-b)/4294967296>>>0}
function re(a){if(a<0){qe(0-a);var b=y(se(oe,pe));a=b.next().value;b=b.next().value;oe=a>>>0;pe=b>>>0}else qe(a)}
function te(a,b){b>>>=0;a>>>=0;if(b<=2097151)var c=""+(4294967296*b+a);else Zd()?c=""+(BigInt(b)<<BigInt(32)|BigInt(a)):(c=(a>>>24|b<<8)&16777215,b=b>>16&65535,a=(a&16777215)+c*6777216+b*6710656,c+=b*8147497,b*=2,a>=1E7&&(c+=a/1E7>>>0,a%=1E7),c>=1E7&&(b+=c/1E7>>>0,c%=1E7),c=b+ue(c)+ue(a));return c}
function ue(a){a=String(a);return"0000000".slice(a.length)+a}
function ve(){var a=oe,b=pe;b&2147483648?Zd()?a=""+(BigInt(b|0)<<BigInt(32)|BigInt(a>>>0)):(b=y(se(a,b)),a=b.next().value,b=b.next().value,a="-"+te(a,b)):a=te(a,b);return a}
function se(a,b){b=~b;a?a=~a+1:b+=1;return[a,b]}
;function we(a){return Array.prototype.slice.call(a)}
;var xe=typeof BigInt==="function"?BigInt.asIntN:void 0,ye=Number.isSafeInteger,ze=Number.isFinite,Ae=Math.trunc;function Be(a){return a.displayName||a.name||"unknown type name"}
function Ce(a){if(a!=null&&typeof a!=="boolean")throw Error("Expected boolean but got "+Ma(a)+": "+a);return a}
var De=/^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;function Ee(a){switch(typeof a){case "bigint":return!0;case "number":return ze(a);case "string":return De.test(a);default:return!1}}
function Fe(a){if(typeof a!=="number")throw Dd("int32");if(!ze(a))throw Dd("int32");return a|0}
function Ge(a){return a==null?a:Fe(a)}
function He(a){if(a==null)return a;if(typeof a==="string"&&a)a=+a;else if(typeof a!=="number")return;return ze(a)?a|0:void 0}
function Ie(a){var b=0;b=b===void 0?0:b;if(!Ee(a))throw Dd("int64");var c=typeof a;switch(b){case 2048:switch(c){case "string":return Je(a);case "bigint":return String(xe(64,a));default:return Ke(a)}case 4096:switch(c){case "string":return Le(a);case "bigint":return he(xe(64,a));default:return Me(a)}case 0:switch(c){case "string":return Je(a);case "bigint":return he(xe(64,a));default:return Ne(a)}default:return xb(b,"Unknown format requested type for int64")}}
function Oe(a){return a==null?a:Ie(a)}
function Pe(a){var b=a.length;return a[0]==="-"?b<20?!0:b===20&&Number(a.substring(0,7))>-922337:b<19?!0:b===19&&Number(a.substring(0,6))<922337}
function Qe(a){a.indexOf(".");if(Pe(a))return a;if(a.length<16)re(Number(a));else if(Zd())a=BigInt(a),oe=Number(a&BigInt(4294967295))>>>0,pe=Number(a>>BigInt(32)&BigInt(4294967295));else{var b=+(a[0]==="-");pe=oe=0;for(var c=a.length,d=0+b,e=(c-b)%6+b;e<=c;d=e,e+=6)d=Number(a.slice(d,e)),pe*=1E6,oe=oe*1E6+d,oe>=4294967296&&(pe+=Math.trunc(oe/4294967296),pe>>>=0,oe>>>=0);b&&(b=y(se(oe,pe)),a=b.next().value,b=b.next().value,oe=a,pe=b)}return ve()}
function Ne(a){Ee(a);a=Ae(a);if(!ye(a)){re(a);var b=oe,c=pe;if(a=c&2147483648)b=~b+1>>>0,c=~c>>>0,b==0&&(c=c+1>>>0);var d=c*4294967296+(b>>>0);b=Number.isSafeInteger(d)?d:te(b,c);a=typeof b==="number"?a?-b:b:a?"-"+b:b}return a}
function Ke(a){Ee(a);a=Ae(a);if(ye(a))a=String(a);else{var b=String(a);Pe(b)?a=b:(re(a),a=ve())}return a}
function Je(a){Ee(a);var b=Ae(Number(a));if(ye(b))return String(b);b=a.indexOf(".");b!==-1&&(a=a.substring(0,b));return Qe(a)}
function Le(a){var b=Ae(Number(a));if(ye(b))return he(b);b=a.indexOf(".");b!==-1&&(a=a.substring(0,b));return Zd()?he(xe(64,BigInt(a))):he(Qe(a))}
function Me(a){return ye(a)?he(Ne(a)):he(Ke(a))}
function Re(a){if(typeof a!=="string")throw Error();return a}
function Se(a){if(a!=null&&typeof a!=="string")throw Error();return a}
function Te(a){return a==null||typeof a==="string"?a:void 0}
function Ue(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Be(b)+" but got "+(a&&Be(a.constructor)));}
function Ve(a,b,c){if(a!=null&&typeof a==="object"&&L(a))return a;if(Array.isArray(a)){var d=a[J]|0,e=d;e===0&&(e|=c&32);e|=c&2;e!==d&&Rd(a,e);return new b(a)}}
;var We={};function Xe(a){return a}
;function Ye(a,b,c,d,e){d=d?!!(b&32):void 0;var f=[],g=a.length,h=!1;if(b&64){if(b&256){g--;var k=a[g];var l=g;Vd(k)}else l=4294967295,k=void 0,g&&Vd(a[g-1]);if(!(e||b&512)){h=!0;var m;var n=((m=Ze)!=null?m:Xe)(k?l- -1:b>>15&1023||536870912,-1,a,k);l=n+-1}}else l=4294967295,b&1||(k=g&&a[g-1],Vd(k)?(g--,l=g,n=0):k=void 0);m=void 0;for(var p=0;p<g;p++){var t=a[p];if(t!=null&&(t=c(t,d))!=null)if(p>=l){var v=void 0;((v=m)!=null?v:m={})[p- -1]=t}else f[p]=t}if(k)for(var x in k)a=k[x],a!=null&&(a=c(a,d))!=
null&&(g=+x,g<n?f[g+-1]=a:(g=void 0,((g=m)!=null?g:m={})[x]=a));m&&(h?f.push(m):f[l]=m);e&&Rd(f,b&33522241|(m!=null?290:34));return f}
function $e(a){switch(typeof a){case "number":return Number.isFinite(a)?a:""+a;case "bigint":return ne(a)?Number(a):""+a;case "boolean":return a?1:0;case "object":if(Array.isArray(a)){var b=a[J]|0;return a.length===0&&b&1?void 0:Ye(a,b,$e,!1,!1)}if(L(a))return af(a);if(a instanceof zd){b=a.h;if(b==null)a="";else if(typeof b==="string")a=b;else{if(ud){for(var c="",d=0,e=b.length-10240;d<e;)c+=String.fromCharCode.apply(null,b.subarray(d,d+=10240));c+=String.fromCharCode.apply(null,d?b.subarray(d):b);
b=btoa(c)}else b=pd(b);a=a.h=b}return a}return}return a}
var Ze;function bf(a,b){if(b){Ze=b==null||b===Xe||b[Md]!==We?Xe:b;try{return af(a)}finally{Ze=void 0}}return af(a)}
function af(a){L(a);a=a.F;return Ye(a,a[J]|0,$e,void 0,!1)}
;function M(a,b,c){if(a==null){var d=96;c?(a=[c],d|=512):a=[];b&&(d=d&-33521665|(b&1023)<<15)}else{if(!Array.isArray(a))throw Error("narr");d=a[J]|0;8192&d||!(64&d)||2&d||cf();if(d&1024)throw Error("farr");if(d&64)return d&16384||Rd(a,d|16384),a;d|=64;if(c&&(d|=512,c!==a[0]))throw Error("mid");a:{c=a;var e=c.length;if(e){var f=e-1,g=c[f];if(Vd(g)){d|=256;b=d&512?0:-1;f-=b;if(f>=1024)throw Error("pvtlmt");for(var h in g)e=+h,e<f&&(c[e+b]=g[h],delete g[h]);d=d&-33521665|(f&1023)<<15;break a}}if(b){h=
Math.max(b,e-(d&512?0:-1));if(h>1024)throw Error("spvt");d=d&-33521665|(h&1023)<<15}}}Rd(a,d|16384);return a}
function cf(){Ed(Jd,5)}
;function df(a,b){if(typeof a!=="object")return a;if(Array.isArray(a)){var c=a[J]|0;if(a.length===0&&c&1)return;if(c&2)return a;var d;if(d=b)d=c===0||!!(c&32)&&!(c&64||!(c&16));return d?(Sd(a,34),c&4&&Object.freeze(a),a):Ye(a,c,df,b!==void 0,!0)}if(L(a))return L(a),L(a),b=a.F,c=b[J]|0,c&2?a:Ye(b,c,df,!0,!0);if(a instanceof zd)return a}
function ef(a){var b=a;L(b);b=b.F;if(!((b[J]|0)&2))return a;b=a=new a.constructor(Ye(b,b[J]|0,df,!0,!0));L(b);b=b.F;b[J]&=-3;return a}
;var ff=he(0);function gf(a,b){Object.isExtensible(a);L(a);a=a.F;return hf(a,a[J]|0,b)}
function hf(a,b,c){if(c===-1)return null;var d=c+(b&512?0:-1),e=a.length-1;if(d>=e&&b&256)a=a[e][c];else if(d<=e)a=a[d];else return;return a}
function jf(a,b,c){L(a);var d=a.F;var e=d[J]|0;Wd(e);kf(d,e,b,c);return a}
function kf(a,b,c,d){var e=b&512?0:-1,f=c+e,g=a.length-1;if(f>=g&&b&256)return a[g][c]=d,b;if(f<=g)return a[f]=d,b;d!==void 0&&(g=b>>15&1023||536870912,c>=g?d!=null&&(f={},a[g+e]=(f[c]=d,f),b|=256,Rd(a,b)):a[f]=d);return b}
function lf(a){return!!(2&a)&&!!(4&a)||!!(1024&a)}
function mf(a,b,c){L(a);var d=a.F;var e=d[J]|0;Wd(e);if(b==null)return kf(d,e,3),a;if(!Array.isArray(b))throw Dd();var f=b[J]|0,g=f,h=lf(f),k=h||Object.isFrozen(b);h||(f=0);k||(b=we(b),g=0,f=nf(f,e),f=of(f,e,!0),k=!1);f|=21;h=4&f?2048&f?2048:4096&f?4096:0:void 0;h=h!=null?h:0;for(var l=0;l<b.length;l++){var m=b[l],n=c(m,h);Object.is(m,n)||(k&&(b=we(b),g=0,f=nf(f,e),f=of(f,e,!0),k=!1),b[l]=n)}f!==g&&(k&&(b=we(b),f=nf(f,e),f=of(f,e,!0)),Rd(b,f));kf(d,e,3,b);return a}
function pf(a,b,c,d){L(a);a=a.F;var e=a[J]|0;Wd(e);if(d==null){var f=qf(a);if(rf(f,a,e,c)===b)f.set(c,0);else return}else{c.includes(b);f=qf(a);var g=rf(f,a,e,c);g!==b&&(g&&(e=kf(a,e,g)),f.set(c,b))}kf(a,e,b,d)}
function qf(a){if(Fd){var b;return(b=a[Id])!=null?b:a[Id]=new Map}if(Id in a)return a[Id];b=new Map;Object.defineProperty(a,Id,{value:b});return b}
function rf(a,b,c,d){var e=a.get(d);if(e!=null)return e;for(var f=e=0;f<d.length;f++){var g=d[f];hf(b,c,g)!=null&&(e!==0&&(c=kf(b,c,e)),e=g)}a.set(d,e);return e}
function sf(a,b,c){L(a);a=a.F;var d=a[J]|0,e=hf(a,d,c);b=Ve(e,b,d);b!==e&&b!=null&&kf(a,d,c,b);return b}
function tf(a,b,c){b=sf(a,b,c);if(b==null)return b;L(a);a=a.F;var d=a[J]|0;if(!(d&2)){var e=ef(b);e!==b&&(b=e,kf(a,d,c,b))}return b}
function Ac(a,b,c){var d=void 0===Xd?2:4;L(a);var e=a.F[J]|0,f=e,g=!(2&e);e=!1;L(a);a=a.F;var h=!!(2&f),k=h?1:d;e=!!e;g&&(g=!h);d=hf(a,f,c);d=Array.isArray(d)?d:Pd;var l=d[J]|0;h=!!(4&l);if(!h){var m=l;m===0&&(m=nf(m,f),m|=16);l=d;m|=1;var n=f,p=!!(2&m);p&&(n|=2);for(var t=!p,v=!0,x=0,A=0;x<l.length;x++){var H=Ve(l[x],b,n);if(H instanceof b){if(!p){L(H);var K=!!((H.F[J]|0)&2);t&&(t=!K);v&&(v=K)}l[A++]=H}}A<x&&(l.length=A);m|=4;m=v?m|16:m&-17;m=t?m|8:m&-9;Rd(l,m);p&&Object.freeze(l);l=m}if(g&&!(8&
l||!d.length&&(k===1||k===4&&32&l))){lf(l)&&(d=we(d),l=nf(l,f),f=kf(a,f,c,d));b=d;g=l;for(l=0;l<b.length;l++)m=b[l],n=ef(m),m!==n&&(b[l]=n);g|=8;g=b.length?g&-17:g|16;Rd(b,g);l=g}k===1||k===4&&32&l?lf(l)||(f=l,c=!!(32&l),l|=!d.length||16&l&&(!h||c)?2:1024,l!==f&&Rd(d,l),Object.freeze(d)):(k===2&&lf(l)&&(d=we(d),l=nf(l,f),l=of(l,f,e),Rd(d,l),f=kf(a,f,c,d)),lf(l)||(c=l,l=of(l,f,e),l!==c&&Rd(d,l)));return d}
function uf(a,b,c,d){d!=null?Ue(d,b):d=void 0;return jf(a,c,d)}
function vf(a,b,c,d){L(a);var e=a.F;var f=e[J]|0;Wd(f);if(d==null)return kf(e,f,c),a;if(!Array.isArray(d))throw Dd();for(var g=d[J]|0,h=g,k=lf(g),l=k||Object.isFrozen(d),m=!0,n=!0,p=0;p<d.length;p++){var t=d[p];Ue(t,b);k||(L(t),t=!!((t.F[J]|0)&2),m&&(m=!t),n&&(n=t))}k||(g=m?13:5,g=n?g|16:g&-17);l&&g===h||(d=we(d),h=0,g=nf(g,f),g=of(g,f,!0));g!==h&&Rd(d,g);kf(e,f,c,d);return a}
function nf(a,b){2&a&&(a|=16);a=(2&b?a|2:a&-3)|32;return a&=-1025}
function of(a,b,c){32&b&&c||(a&=-33);return a}
function Cc(a,b,c){c=c===void 0?0:c;var d;return(d=He(gf(a,b)))!=null?d:c}
function wf(a,b,c){c=c===void 0?ff:c;a=gf(a,b);b=typeof a;a=a==null?a:b==="bigint"?he(xe(64,a)):Ee(a)?b==="string"?Le(a):Me(a):void 0;return a!=null?a:c}
function xf(a,b){var c=c===void 0?"":c;var d;return(d=Te(gf(a,b)))!=null?d:c}
function yf(a){var b=b===void 0?0:b;a=gf(a,1);a=a==null?a:ze(a)?a|0:void 0;return a!=null?a:b}
function zf(a,b,c){return jf(a,b,Se(c))}
function Af(a,b,c){c=Se(c);L(a);a=a.F;var d=a[J]|0;Wd(d);kf(a,d,b,c===""?void 0:c)}
function Bf(a,b,c){if(c!=null){if(!ze(c))throw Dd("enum");c|=0}return jf(a,b,c)}
;function N(a,b,c){a=M(a,b,c);L(this);this.F=a}
N.prototype.toJSON=function(){return bf(this)};
N.prototype.serialize=function(a){return JSON.stringify(bf(this,a))};
function Cf(a,b){if(b==null||b=="")return new a;b=JSON.parse(b);if(!Array.isArray(b))throw Error("dnarr");Sd(b,32);return new a(b)}
N.prototype.clone=function(){var a=this;L(a);var b=a;L(b);b=b.F;b=a=new a.constructor(Ye(b,b[J]|0,df,!0,!0));L(b);b=b.F;b[J]&=-3;return a};
N.prototype[Kd]=Ud;N.prototype.toString=function(){L(this);return this.F.toString()};function Df(){var a=Ef;this.ctor=Ff;this.isRepeated=0;this.h=tf;this.defaultValue=void 0;this.i=a.Le!=null?Yd:void 0}
Df.prototype.register=function(){dd(this)};function Gf(a){return function(b){return Cf(a,b)}}
;function Hf(a){a=M(a);L(this);this.F=a}
w(Hf,N);function If(a,b){return mf(a,b,Fe)}
;function Jf(a){a=M(a);L(this);this.F=a}
w(Jf,N);var Kf=[1,2,3];function Lf(a){a=M(a);L(this);this.F=a}
w(Lf,N);var Mf=[1,2,3];function Nf(a){a=M(a);L(this);this.F=a}
w(Nf,N);function Of(a){a=M(a);L(this);this.F=a}
w(Of,N);function Pf(a){a=M(a);L(this);this.F=a}
w(Pf,N);function Qf(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.indexOf("blob:")===0&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();a.indexOf("//")==0&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");c!=-1&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if(c!=="http"&&c!=="https"&&c!=="chrome-extension"&&
c!=="moz-extension"&&c!=="file"&&c!=="android-app"&&c!=="chrome-search"&&c!=="chrome-untrusted"&&c!=="chrome"&&c!=="app"&&c!=="devtools")throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(d!=-1){var e=b.substring(d+1);b=b.substring(0,d);if(c==="http"&&e!=="80"||c==="https"&&e!=="443")a=":"+e}return c+"://"+b+a}
;function Rf(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(n){for(var p=g,t=0;t<64;t+=4)p[t/4]=n[t]<<24|n[t+1]<<16|n[t+2]<<8|n[t+3];for(t=16;t<80;t++)n=p[t-3]^p[t-8]^p[t-14]^p[t-16],p[t]=(n<<1|n>>>31)&4294967295;n=e[0];var v=e[1],x=e[2],A=e[3],H=e[4];for(t=0;t<80;t++){if(t<40)if(t<20){var K=A^v&(x^A);var aa=1518500249}else K=v^x^A,aa=1859775393;else t<60?(K=v&x|A&(v|x),aa=2400959708):(K=v^x^A,aa=3395469782);K=((n<<5|n>>>27)&4294967295)+K+H+aa+p[t]&4294967295;H=A;A=x;x=(v<<30|v>>>2)&4294967295;v=n;n=K}e[0]=e[0]+n&4294967295;e[1]=e[1]+v&4294967295;
e[2]=e[2]+x&4294967295;e[3]=e[3]+A&4294967295;e[4]=e[4]+H&4294967295}
function c(n,p){if(typeof n==="string"){n=unescape(encodeURIComponent(n));for(var t=[],v=0,x=n.length;v<x;++v)t.push(n.charCodeAt(v));n=t}p||(p=n.length);t=0;if(l==0)for(;t+64<p;)b(n.slice(t,t+64)),t+=64,m+=64;for(;t<p;)if(f[l++]=n[t++],m++,l==64)for(l=0,b(f);t+64<p;)b(n.slice(t,t+64)),t+=64,m+=64}
function d(){var n=[],p=m*8;l<56?c(h,56-l):c(h,64-(l-56));for(var t=63;t>=56;t--)f[t]=p&255,p>>>=8;b(f);for(t=p=0;t<5;t++)for(var v=24;v>=0;v-=8)n[p++]=e[t]>>v&255;return n}
for(var e=[],f=[],g=[],h=[128],k=1;k<64;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,he:function(){for(var n=d(),p="",t=0;t<n.length;t++)p+="0123456789ABCDEF".charAt(Math.floor(n[t]/16))+"0123456789ABCDEF".charAt(n[t]%16);return p}}}
;function Sf(a,b,c){var d=String(D.location.href);return d&&a&&b?[b,Tf(Qf(d),a,c||null)].join(" "):null}
function Tf(a,b,c){var d=[],e=[];if((Array.isArray(c)?2:1)==1)return e=[b,a],Mb(d,function(h){e.push(h)}),Uf(e.join(" "));
var f=[],g=[];Mb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=f.length==0?[c,b,a]:[f.join(":"),c,b,a];Mb(d,function(h){e.push(h)});
a=Uf(e.join(" "));a=[c,a];g.length==0||a.push(g.join(""));return a.join("_")}
function Uf(a){var b=Rf();b.update(a);return b.he().toLowerCase()}
;function Vf(a){this.h=a||{cookie:""}}
r=Vf.prototype;r.isEnabled=function(){if(!D.navigator.cookieEnabled)return!1;if(this.h.cookie)return!0;this.set("TESTCOOKIESENABLED","1",{Vb:60});if(this.get("TESTCOOKIESENABLED")!=="1")return!1;this.remove("TESTCOOKIESENABLED");return!0};
r.set=function(a,b,c){var d=!1;if(typeof c==="object"){var e=c.bf;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Vb}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');h===void 0&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=h<0?"":h==0?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+h*1E3)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(e!=null?";samesite="+
e:"")};
r.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=cb(d[e]);if(f.lastIndexOf(c,0)==0)return f.slice(c.length);if(f==a)return""}return b};
r.remove=function(a,b,c){var d=this.get(a)!==void 0;this.set(a,"",{Vb:0,path:b,domain:c});return d};
r.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=cb(a[f]),d=e.indexOf("="),d==-1?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;a>=0;a--)this.remove(b[a])};
var Wf=new Vf(typeof document=="undefined"?null:document);function Xf(){var a=D.__SAPISID||D.__APISID||D.__3PSAPISID||D.__1PSAPISID||D.__OVERRIDE_SID;if(a)return!0;typeof document!=="undefined"&&(a=new Vf(document),a=a.get("SAPISID")||a.get("APISID")||a.get("__Secure-3PAPISID")||a.get("__Secure-1PAPISID"));return!!a}
function Yf(a,b,c,d){(a=D[a])||typeof document==="undefined"||(a=(new Vf(document)).get(b));return a?Sf(a,c,d):null}
function Zf(a){var b=Qf(String(D.location.href)),c=[];if(Xf()){b=b.indexOf("https:")==0||b.indexOf("chrome-extension:")==0||b.indexOf("chrome-untrusted://new-tab-page")==0||b.indexOf("moz-extension:")==0;var d=b?D.__SAPISID:D.__APISID;d||typeof document==="undefined"||(d=new Vf(document),d=d.get(b?"SAPISID":"APISID")||d.get("__Secure-3PAPISID"));(d=d?Sf(d,b?"SAPISIDHASH":"APISIDHASH",a):null)&&c.push(d);b&&((b=Yf("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&c.push(b),(a=Yf("__3PSAPISID",
"__Secure-3PAPISID","SAPISID3PHASH",a))&&c.push(a))}return c.length==0?null:c.join(" ")}
;function $f(){}
$f.prototype.compress=function(a){var b,c,d,e;return B(function(f){switch(f.h){case 1:return b=new CompressionStream("gzip"),c=(new Response(b.readable)).arrayBuffer(),d=b.writable.getWriter(),f.yield(d.write((new TextEncoder).encode(a)),2);case 2:return f.yield(d.close(),3);case 3:return e=Uint8Array,f.yield(c,4);case 4:return f.return(new e(f.i))}})};
$f.prototype.isSupported=function(a){return a<1024?!1:typeof CompressionStream!=="undefined"};function ag(a){a=M(a);L(this);this.F=a}
w(ag,N);function bg(a,b){this.intervalMs=a;this.callback=b;this.enabled=!1;this.h=function(){return $a()};
this.i=this.h()}
bg.prototype.setInterval=function(a){this.intervalMs=a;this.timer&&this.enabled?(this.stop(),this.start()):this.timer&&this.stop()};
bg.prototype.start=function(){var a=this;this.enabled=!0;this.timer||(this.timer=setTimeout(function(){a.tick()},this.intervalMs),this.i=this.h())};
bg.prototype.stop=function(){this.enabled=!1;this.timer&&(clearTimeout(this.timer),this.timer=void 0)};
bg.prototype.tick=function(){var a=this;if(this.enabled){var b=Math.max(this.h()-this.i,0);b<this.intervalMs*.8?this.timer=setTimeout(function(){a.tick()},this.intervalMs-b):(this.timer&&(clearTimeout(this.timer),this.timer=void 0),this.callback(),this.enabled&&(this.stop(),this.start()))}else this.timer=void 0};function cg(a){a=M(a);L(this);this.F=a}
w(cg,N);function dg(a){a=M(a);L(this);this.F=a}
w(dg,N);function eg(a,b){this.x=a!==void 0?a:0;this.y=b!==void 0?b:0}
r=eg.prototype;r.clone=function(){return new eg(this.x,this.y)};
r.equals=function(a){return a instanceof eg&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
r.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
r.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
r.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
r.scale=function(a,b){this.x*=a;this.y*=typeof b==="number"?b:a;return this};function fg(a,b){this.width=a;this.height=b}
r=fg.prototype;r.clone=function(){return new fg(this.width,this.height)};
r.aspectRatio=function(){return this.width/this.height};
r.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
r.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
r.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
r.scale=function(a,b){this.width*=a;this.height*=typeof b==="number"?b:a;return this};function gg(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function hg(a){var b=ig,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function jg(a){for(var b in a)return!1;return!0}
function kg(a,b){if(a!==null&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function lg(a){return a!==null&&"privembed"in a?a.privembed:!1}
function mg(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function ng(a){var b={},c;for(c in a)b[c]=a[c];return b}
function og(a){if(!a||typeof a!=="object")return a;if(typeof a.clone==="function")return a.clone();if(typeof Map!=="undefined"&&a instanceof Map)return new Map(a);if(typeof Set!=="undefined"&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:typeof ArrayBuffer!=="function"||typeof ArrayBuffer.isView!=="function"||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=og(a[c]);return b}
var pg="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function qg(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<pg.length;f++)c=pg[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;function rg(a,b){this.h=a===sg&&b||""}
rg.prototype.toString=function(){return this.h};
var sg={};new rg(sg,"");"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON",
"INPUT"]);function tg(a){var b=document;return typeof a==="string"?b.getElementById(a):a}
function ug(a){var b=document;a=String(a);b.contentType==="application/xhtml+xml"&&(a=a.toLowerCase());return b.createElement(a)}
function vg(a){a&&a.parentNode&&a.parentNode.removeChild(a)}
function wg(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function xg(a){a=M(a);L(this);this.F=a}
w(xg,N);xg.prototype.oc=function(){return yf(this)};function yg(a){a=M(a);L(this);this.F=a}
w(yg,N);function zg(a){a=M(a);L(this);this.F=a}
w(zg,N);function Ag(a,b){vf(a,yg,1,b)}
;function Bg(a){a=M(a);L(this);this.F=a}
w(Bg,N);var Cg=["platform","platformVersion","architecture","model","uaFullVersion"],Dg=new zg,Eg=null;function Fg(a,b){b=b===void 0?Cg:b;if(!Eg){var c;a=(c=a.navigator)==null?void 0:c.userAgentData;if(!a||typeof a.getHighEntropyValues!=="function"||a.brands&&typeof a.brands.map!=="function")return Promise.reject(Error("UACH unavailable"));c=(a.brands||[]).map(function(e){var f=new yg;f=zf(f,1,e.brand);return zf(f,2,e.version)});
Ag(jf(Dg,2,Ce(a.mobile)),c);Eg=a.getHighEntropyValues(b)}var d=new Set(b);return Eg.then(function(e){var f=Dg.clone();d.has("platform")&&zf(f,3,e.platform);d.has("platformVersion")&&zf(f,4,e.platformVersion);d.has("architecture")&&zf(f,5,e.architecture);d.has("model")&&zf(f,6,e.model);d.has("uaFullVersion")&&zf(f,7,e.uaFullVersion);return f}).catch(function(){return Dg.clone()})}
;function Gg(a){a=M(a);L(this);this.F=a}
w(Gg,N);function Hg(a){a=M(a,4);L(this);this.F=a}
w(Hg,N);function Ig(a){a=M(a,36);L(this);this.F=a}
w(Ig,N);function Jg(a){a=M(a,19);L(this);this.F=a}
w(Jg,N);Jg.prototype.Yb=function(a){return Bf(this,2,a)};function Kg(a,b){this.Wa=b=b===void 0?!1:b;this.j=this.locale=null;this.i=0;this.isFinal=!1;this.h=new Jg;Number.isInteger(a)&&this.h.Yb(a);b||(this.locale=document.documentElement.getAttribute("lang"));Lg(this,new Gg)}
Kg.prototype.Yb=function(a){this.h.Yb(a);return this};
function Lg(a,b){uf(a.h,Gg,1,b);yf(b)||Bf(b,1,1);a.Wa||(b=Mg(a),xf(b,5)||zf(b,5,a.locale));a.j&&(b=Mg(a),tf(b,zg,9)||uf(b,zg,9,a.j))}
function Ng(a,b){a.i=b}
function Og(a){var b=b===void 0?Cg:b;var c=a.Wa?void 0:window;c?Fg(c,b).then(function(d){a.j=d;d=Mg(a);uf(d,zg,9,a.j);return!0}).catch(function(){return!1}):Promise.resolve(!1)}
function Mg(a){a=tf(a.h,Gg,1);var b=tf(a,Bg,11);b||(b=new Bg,uf(a,Bg,11,b));return b}
function Pg(a,b,c,d,e,f,g){c=c===void 0?0:c;d=d===void 0?0:d;e=e===void 0?null:e;f=f===void 0?0:f;g=g===void 0?0:g;if(sf(tf(a.h,Gg,1),Bg,11)!==void 0){var h=Mg(a);var k=new xg;k=Bf(k,1,a.i);k=jf(k,2,Ce(a.isFinal));d=jf(k,3,Ge(d>0?d:void 0));d=jf(d,4,Ge(f>0?f:void 0));d=jf(d,5,Ge(g>0?g:void 0));L(d);f=d.F;g=f[J]|0;d=g&2?d:new d.constructor(Ye(f,g,df,!0,!0));uf(h,xg,10,d)}a=a.h.clone();h=Date.now().toString();a=jf(a,4,Oe(h));b=b.slice();b=vf(a,Ig,3,b);e&&(a=new cg,e=jf(a,13,Ge(e)),a=new dg,e=uf(a,cg,
2,e),a=new Hg,e=uf(a,dg,1,e),e=Bf(e,2,9),uf(b,Hg,18,e));c&&jf(b,14,Oe(c));return b}
;var Qg=function(){if(!D.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
D.addEventListener("test",c,b);D.removeEventListener("test",c,b)}catch(d){}return a}();function Rg(a){this.h=this.i=this.j=a}
Rg.prototype.reset=function(){this.h=this.i=this.j};
Rg.prototype.getValue=function(){return this.i};function Ef(a){a=M(a,8);L(this);this.F=a}
w(Ef,N);var Sg=Gf(Ef);function Ff(a){a=M(a);L(this);this.F=a}
w(Ff,N);var Tg=new Df;function Ug(a){G.call(this);var b=this;this.componentId="";this.h=[];this.Qa="";this.pageId=null;this.eb=this.ma=-1;this.G=this.experimentIds=null;this.D=this.o=0;this.U=null;this.Z=this.ha=0;this.Kb=1;this.timeoutMillis=0;this.xa=!1;this.logSource=a.logSource;this.ib=a.ib||function(){};
this.j=new Kg(a.logSource,a.Wa);this.network=a.network||null;this.ob=a.ob||null;this.bufferSize=1E3;this.P=a.zf||null;this.sessionIndex=a.sessionIndex||null;this.Qb=a.Qb||!1;this.logger=null;this.withCredentials=!a.pd;this.Wa=a.Wa||!1;this.Y=!this.Wa&&!!window&&!!window.navigator&&window.navigator.sendBeacon!==void 0;this.Pa=typeof URLSearchParams!=="undefined"&&!!(new URL(Vg())).searchParams&&!!(new URL(Vg())).searchParams.set;var c=Bf(new Gg,1,1);Lg(this.j,c);this.u=new Rg(1E4);a=Wg(this,a.kd);
this.i=new bg(this.u.getValue(),a);this.Fa=new bg(6E5,a);this.Qb||this.Fa.start();this.Wa||(document.addEventListener("visibilitychange",function(){if(document.visibilityState==="hidden"){Xg(b);var d;(d=b.U)==null||d.flush()}}),document.addEventListener("pagehide",function(){Xg(b);
var d;(d=b.U)==null||d.flush()}))}
w(Ug,G);function Wg(a,b){return a.Pa?b?function(){b().then(function(){a.flush()})}:function(){a.flush()}:function(){}}
Ug.prototype.ba=function(){Xg(this);this.i.stop();this.Fa.stop();G.prototype.ba.call(this)};
function Yg(a){a.P||(a.P=Vg());try{return(new URL(a.P)).toString()}catch(b){return(new URL(a.P,window.location.origin)).toString()}}
function Zg(a,b,c){a.U&&a.U.kb(b,c)}
Ug.prototype.log=function(a){Zg(this,2,1);if(this.Pa){a=a.clone();var b=this.Kb++;a=jf(a,21,Oe(b));this.componentId&&zf(a,26,this.componentId);b=a;var c=gf(b,1);var d=d===void 0?!1:d;var e=typeof c;d=c==null?c:e==="bigint"?String(xe(64,c)):Ee(c)?e==="string"?Je(c):d?Ke(c):Ne(c):void 0;d==null&&(d=Date.now(),d=Number.isFinite(d)?d.toString():"0",jf(b,1,Oe(d)));d=gf(b,15);d!=null&&(typeof d==="bigint"?ne(d)?d=Number(d):(d=xe(64,d),d=ne(d)?Number(d):String(d)):d=Ee(d)?typeof d==="number"?Ne(d):Je(d):
void 0);d==null&&jf(b,15,Oe((new Date).getTimezoneOffset()*60));this.experimentIds&&(d=this.experimentIds.clone(),uf(b,ag,16,d));Zg(this,1,1);b=this.h.length-this.bufferSize+1;b>0&&(this.h.splice(0,b),this.o+=b,Zg(this,3,b));this.h.push(a);this.Qb||this.i.enabled||this.i.start()}};
Ug.prototype.flush=function(a,b){var c=this;if(this.h.length===0)a&&a();else if(this.xa&&this.Y)this.j.i=3,$g(this);else{var d=Date.now();if(this.eb>d&&this.ma<d)b&&b("throttled");else{this.network&&(typeof this.network.oc==="function"?Ng(this.j,this.network.oc()):this.j.i=0);var e=this.h.length,f=Pg(this.j,this.h,this.o,this.D,this.ob,this.ha,this.Z),g=this.ib();if(g&&this.Qa===g)b&&b("stale-auth-token");else{this.h=[];this.i.enabled&&this.i.stop();this.o=0;d=f.serialize();var h;this.G&&this.G.isSupported(d.length)&&
(h=this.G.compress(d));var k=ah(this,d,g),l=function(p){c.u.reset();c.i.setInterval(c.u.getValue());if(p){var t=null;try{var v=JSON.stringify(JSON.parse(p.replace(")]}'\n","")));t=Sg(v)}catch(x){}t&&(p=Number(wf(t,1,he("-1"))),p>0&&(c.ma=Date.now(),c.eb=c.ma+p),L(t),t=Tg.ctor?Tg.h(t,Tg.ctor,175237375,Tg.i):Tg.h(t,175237375,null,Tg.i),t=t===null?void 0:t)&&(t=Cc(t,1,-1),t!==-1&&(c.u=new Rg(t<1?1:t),c.i.setInterval(c.u.getValue())))}a&&a();c.D=0},m=function(p,t){var v=Ac(f,Ig,3);
var x=Number(wf(f,14)),A=c.u;A.h=Math.min(3E5,A.h*2);A.i=Math.min(3E5,A.h+Math.round(.1*(Math.random()-.5)*2*A.h));c.i.setInterval(c.u.getValue());p===401&&g&&(c.Qa=g);x&&(c.o+=x);t===void 0&&(t=c.isRetryable(p));t&&(c.h=v.concat(c.h),c.Qb||c.i.enabled||c.i.start());Zg(c,7,1);b&&b("net-send-failed",p);++c.D},n=function(){c.network&&c.network.send(k,l,m)};
h?h.then(function(p){Zg(c,5,e);k.Dc["Content-Encoding"]="gzip";k.Dc["Content-Type"]="application/binary";k.body=p;k.be=2;n()},function(){Zg(c,6,e);
n()}):n()}}}};
function ah(a,b,c){c=c===void 0?a.ib():c;var d=d===void 0?a.withCredentials:d;var e={},f=new URL(Yg(a));c&&(e.Authorization=c);a.sessionIndex&&(e["X-Goog-AuthUser"]=a.sessionIndex,f.searchParams.set("authuser",a.sessionIndex));a.pageId&&(Object.defineProperty(e,"X-Goog-PageId",{value:a.pageId}),f.searchParams.set("pageId",a.pageId));return{url:f.toString(),body:b,be:1,Dc:e,requestType:"POST",withCredentials:d,timeoutMillis:a.timeoutMillis}}
function Xg(a){a.j.isFinal=!0;a.flush();a.j.isFinal=!1}
function $g(a){bh(a,function(b,c){b=new URL(b);b.searchParams.set("format","json");var d=!1;try{d=window.navigator.sendBeacon(b.toString(),c.serialize())}catch(e){}d||(a.Y=!1);return d})}
function bh(a,b){if(a.h.length!==0){var c=new URL(Yg(a));c.searchParams.delete("format");var d=a.ib();d&&c.searchParams.set("auth",d);c.searchParams.set("authuser",a.sessionIndex||"0");for(d=0;d<10&&a.h.length;++d){var e=a.h.slice(0,32),f=Pg(a.j,e,a.o,a.D,a.ob,a.ha,a.Z);if(!b(c.toString(),f)){++a.D;break}a.o=0;a.D=0;a.ha=0;a.Z=0;a.h=a.h.slice(e.length)}a.i.enabled&&a.i.stop()}}
Ug.prototype.isRetryable=function(a){return 500<=a&&a<600||a===401||a===0};
function Vg(){return"https://play.google.com/log?format=json&hasfast=true"}
;function ch(){this.Vd=typeof AbortController!=="undefined"}
ch.prototype.send=function(a,b,c){var d=this,e,f,g,h,k,l,m,n,p,t;return B(function(v){switch(v.h){case 1:return f=(e=d.Vd?new AbortController:void 0)?setTimeout(function(){e.abort()},a.timeoutMillis):void 0,xa(v,2,3),g=Object.assign({},{method:a.requestType,
headers:Object.assign({},a.Dc)},a.body&&{body:a.body},a.withCredentials&&{credentials:"include"},{signal:a.timeoutMillis&&e?e.signal:null}),v.yield(fetch(a.url,g),5);case 5:h=v.i;if(h.status!==200){(k=c)==null||k(h.status);v.A(3);break}if((l=b)==null){v.A(7);break}return v.yield(h.text(),8);case 8:l(v.i);case 7:case 3:v.P=[v.j];v.M=0;v.o=0;clearTimeout(f);Aa(v);break;case 2:m=za(v);switch((n=m)==null?void 0:n.name){case "AbortError":(p=c)==null||p(408);break;default:(t=c)==null||t(400)}v.A(3)}})};
ch.prototype.oc=function(){return 4};function dh(a,b){G.call(this);this.logSource=a;this.sessionIndex=b;this.Ua="https://play.google.com/log?format=json&hasfast=true";this.i=null;this.o=!1;this.network=null;this.componentId="";this.h=this.ob=null;this.j=!1;this.pageId=null;this.bufferSize=void 0}
w(dh,G);function eh(a,b){a.i=b;return a}
function gh(a,b){a.network=b;return a}
function hh(a,b){a.h=b}
function ih(a){a.j=!0;return a}
dh.prototype.pd=function(){this.u=!0;return this};
function jh(a){a.network||(a.network=new ch);var b=new Ug({logSource:a.logSource,ib:a.ib?a.ib:Zf,sessionIndex:a.sessionIndex,zf:a.Ua,Wa:a.o,Qb:!1,pd:a.u,kd:a.kd,network:a.network});uc(a,b);if(a.i){var c=a.i,d=Mg(b.j);zf(d,7,c)}b.G=new $f;a.componentId&&(b.componentId=a.componentId);a.ob&&(b.ob=a.ob);a.pageId&&(b.pageId=a.pageId);a.h&&((d=a.h)?(b.experimentIds||(b.experimentIds=new ag),c=b.experimentIds,d=d.serialize(),zf(c,4,d)):b.experimentIds&&jf(b.experimentIds,4));a.j&&(b.xa=b.Y);Og(b.j);a.bufferSize&&
(b.bufferSize=a.bufferSize);a.network.Yb&&a.network.Yb(a.logSource);a.network.nf&&a.network.nf(b);return b}
;function kh(a,b,c,d,e,f,g){a=a===void 0?-1:a;b=b===void 0?"":b;c=c===void 0?"":c;d=d===void 0?!1:d;e=e===void 0?"":e;G.call(this);this.logSource=a;this.componentId=b;f?b=f:(a=new dh(a,"0"),a.componentId=b,uc(this,a),c!==""&&(a.Ua=c),d&&(a.o=!0),e&&eh(a,e),g&&gh(a,g),b=jh(a));this.h=b}
w(kh,G);
kh.prototype.flush=function(a){var b=a||[];if(b.length){a=new Pf;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=new Of;f=zf(f,1,e.i);var g=lh(e);f=mf(f,g,Re);g=[];var h=[];for(var k=y(e.h.keys()),l=k.next();!l.done;l=k.next())h.push(l.value.split(","));for(k=0;k<h.length;k++){l=h[k];var m=e.o;for(var n=e.Kc(l)||[],p=[],t=0;t<n.length;t++){var v=n[t],x=v&&v.h;v=new Lf;switch(m){case 3:x=Number(x);Number.isFinite(x)&&pf(v,1,Mf,Oe(x));break;case 2:x=Number(x);if(x!=null&&typeof x!=="number")throw Error("Value of float/double field must be a number, found "+typeof x+
": "+x);pf(v,2,Mf,x)}p.push(v)}m=p;for(n=0;n<m.length;n++){p=m[n];t=new Nf;p=uf(t,Lf,2,p);t=l;v=[];x=mh(e);for(var A=0;A<x.length;A++){var H=x[A],K=t[A],aa=new Jf;switch(H){case 3:pf(aa,1,Kf,Se(String(K)));break;case 2:H=Number(K);Number.isFinite(H)&&pf(aa,2,Kf,Ge(H));break;case 1:pf(aa,3,Kf,Ce(K==="true"))}v.push(aa)}vf(p,Jf,1,v);g.push(p)}}vf(f,Nf,4,g);c.push(f);e.clear()}vf(a,Of,1,c);b=this.h;if(a instanceof Ig)b.log(a);else try{var da=new Ig,Pa=a.serialize();var Nb=zf(da,8,Pa);b.log(Nb)}catch(Ya){Zg(b,
4,1)}this.h.flush()}};function nh(a){this.h=a}
;function oh(a,b,c){this.i=a;this.o=b;this.fields=c||[];this.h=new Map}
function mh(a){return a.fields.map(function(b){return b.fieldType})}
function lh(a){return a.fields.map(function(b){return b.fieldName})}
r=oh.prototype;r.Wd=function(a){var b=C.apply(1,arguments),c=this.Kc(b);c?c.push(new nh(a)):this.Hd(a,b)};
r.Hd=function(a){var b=this.jd(C.apply(1,arguments));this.h.set(b,[new nh(a)])};
r.Kc=function(){var a=this.jd(C.apply(0,arguments));return this.h.has(a)?this.h.get(a):void 0};
r.ue=function(){var a=this.Kc(C.apply(0,arguments));return a&&a.length?a[0]:void 0};
r.clear=function(){this.h.clear()};
r.jd=function(){var a=C.apply(0,arguments);return a?a.join(","):"key"};function ph(a,b){oh.call(this,a,3,b)}
w(ph,oh);ph.prototype.j=function(a){var b=C.apply(1,arguments),c=0,d=this.ue(b);d&&(c=d.h);this.Hd(c+a,b)};function qh(a,b){oh.call(this,a,2,b)}
w(qh,oh);qh.prototype.record=function(a){this.Wd(a,C.apply(1,arguments))};function rh(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
rh.prototype.stopPropagation=function(){this.j=!0};
rh.prototype.preventDefault=function(){this.defaultPrevented=!0};function sh(a,b){rh.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
ab(sh,rh);
sh.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;b=a.relatedTarget;b||(c=="mouseover"?b=a.fromElement:c=="mouseout"&&(b=a.toElement));this.relatedTarget=b;d?(this.clientX=d.clientX!==void 0?d.clientX:d.pageX,this.clientY=d.clientY!==void 0?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||0):(this.clientX=a.clientX!==void 0?a.clientX:a.pageX,this.clientY=a.clientY!==
void 0?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||(c=="keypress"?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType=a.pointerType;this.state=a.state;this.i=a;a.defaultPrevented&&sh.Aa.preventDefault.call(this)};
sh.prototype.stopPropagation=function(){sh.Aa.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
sh.prototype.preventDefault=function(){sh.Aa.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var th="closure_listenable_"+(Math.random()*1E6|0);var uh=0;function vh(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.qc=e;this.key=++uh;this.Xb=this.hc=!1}
function wh(a){a.Xb=!0;a.listener=null;a.proxy=null;a.src=null;a.qc=null}
;function xh(a){this.src=a;this.listeners={};this.h=0}
xh.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=yh(a,b,d,e);g>-1?(b=a[g],c||(b.hc=!1)):(b=new vh(b,this.src,f,!!d,e),b.hc=c,a.push(b));return b};
xh.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=yh(e,b,c,d);return b>-1?(wh(e[b]),Array.prototype.splice.call(e,b,1),e.length==0&&(delete this.listeners[a],this.h--),!0):!1};
function zh(a,b){var c=b.type;c in a.listeners&&Sb(a.listeners[c],b)&&(wh(b),a.listeners[c].length==0&&(delete a.listeners[c],a.h--))}
function yh(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Xb&&f.listener==b&&f.capture==!!c&&f.qc==d)return e}return-1}
;var Ah="closure_lm_"+(Math.random()*1E6|0),Bh={},Ch=0;function Dh(a,b,c,d,e){if(d&&d.once)Eh(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Dh(a,b[f],c,d,e);else c=Fh(c),a&&a[th]?a.listen(b,c,Oa(d)?!!d.capture:!!d,e):Gh(a,b,c,!1,d,e)}
function Gh(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Oa(e)?!!e.capture:!!e,h=Hh(a);h||(a[Ah]=h=new xh(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Ih();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Qg||(e=g),e===void 0&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Jh(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Ch++}}
function Ih(){function a(c){return b.call(a.src,a.listener,c)}
var b=Kh;return a}
function Eh(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Eh(a,b[f],c,d,e);else c=Fh(c),a&&a[th]?Lh(a,b,c,Oa(d)?!!d.capture:!!d,e):Gh(a,b,c,!0,d,e)}
function Mh(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Mh(a,b[f],c,d,e);else(d=Oa(d)?!!d.capture:!!d,c=Fh(c),a&&a[th])?a.i.remove(String(b),c,d,e):a&&(a=Hh(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=yh(b,c,d,e)),(c=a>-1?b[a]:null)&&Nh(c))}
function Nh(a){if(typeof a!=="number"&&a&&!a.Xb){var b=a.src;if(b&&b[th])zh(b.i,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Jh(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Ch--;(c=Hh(b))?(zh(c,a),c.h==0&&(c.src=null,b[Ah]=null)):wh(a)}}}
function Jh(a){return a in Bh?Bh[a]:Bh[a]="on"+a}
function Kh(a,b){if(a.Xb)a=!0;else{b=new sh(b,this);var c=a.listener,d=a.qc||a.src;a.hc&&Nh(a);a=c.call(d,b)}return a}
function Hh(a){a=a[Ah];return a instanceof xh?a:null}
var Oh="__closure_events_fn_"+(Math.random()*1E9>>>0);function Fh(a){if(typeof a==="function")return a;a[Oh]||(a[Oh]=function(b){return a.handleEvent(b)});
return a[Oh]}
;function Ph(){G.call(this);this.i=new xh(this);this.xa=this;this.Z=null}
ab(Ph,G);Ph.prototype[th]=!0;r=Ph.prototype;r.addEventListener=function(a,b,c,d){Dh(this,a,b,c,d)};
r.removeEventListener=function(a,b,c,d){Mh(this,a,b,c,d)};
function Qh(a,b){var c=a.Z;if(c){var d=[];for(var e=1;c;c=c.Z)d.push(c),++e}a=a.xa;c=b.type||b;typeof b==="string"?b=new rh(b,a):b instanceof rh?b.target=b.target||a:(e=b,b=new rh(c,a),qg(b,e));e=!0;var f;if(d)for(f=d.length-1;!b.j&&f>=0;f--){var g=b.h=d[f];e=Rh(g,c,!0,b)&&e}b.j||(g=b.h=a,e=Rh(g,c,!0,b)&&e,b.j||(e=Rh(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=Rh(g,c,!1,b)&&e}
r.ba=function(){Ph.Aa.ba.call(this);this.removeAllListeners();this.Z=null};
r.listen=function(a,b,c,d){return this.i.add(String(a),b,!1,c,d)};
function Lh(a,b,c,d,e){a.i.add(String(b),c,!0,d,e)}
r.removeAllListeners=function(a){if(this.i){var b=this.i;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,wh(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function Rh(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Xb&&g.capture==c){var h=g.listener,k=g.qc||g.src;g.hc&&zh(a.i,g);e=h.call(k,d)!==!1&&e}}return e&&!d.defaultPrevented}
;var Sh=typeof AsyncContext!=="undefined"&&typeof AsyncContext.Snapshot==="function"?function(a){return a&&AsyncContext.Snapshot.wrap(a)}:function(a){return a};function Th(a,b){this.j=a;this.o=b;this.i=0;this.h=null}
Th.prototype.get=function(){if(this.i>0){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Uh(a,b){a.o(b);a.i<100&&(a.i++,b.next=a.h,a.h=b)}
;function Vh(){this.i=this.h=null}
Vh.prototype.add=function(a,b){var c=Wh.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Vh.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Wh=new Th(function(){return new Xh},function(a){return a.reset()});
function Xh(){this.next=this.scope=this.h=null}
Xh.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Xh.prototype.reset=function(){this.next=this.scope=this.h=null};var Yh,Zh=!1,$h=new Vh;function ai(a,b){Yh||bi();Zh||(Yh(),Zh=!0);$h.add(a,b)}
function bi(){var a=Promise.resolve(void 0);Yh=function(){a.then(ci)}}
function ci(){for(var a;a=$h.remove();){try{a.h.call(a.scope)}catch(b){Qc(b)}Uh(Wh,a)}Zh=!1}
;function di(){}
function ei(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;function fi(a){this.X=0;this.ab=void 0;this.vb=this.Sa=this.parent_=null;this.pc=this.Jc=!1;if(a!=di)try{var b=this;a.call(void 0,function(c){gi(b,2,c)},function(c){gi(b,3,c)})}catch(c){gi(this,3,c)}}
function hi(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
hi.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var ii=new Th(function(){return new hi},function(a){a.reset()});
function ji(a,b,c){var d=ii.get();d.i=a;d.h=b;d.context=c;return d}
function ki(a){return new fi(function(b,c){c(a)})}
fi.prototype.then=function(a,b,c){return li(this,Sh(typeof a==="function"?a:null),Sh(typeof b==="function"?b:null),c)};
fi.prototype.$goog_Thenable=!0;function mi(a,b,c,d){ni(a,ji(b||di,c||null,d))}
r=fi.prototype;r.finally=function(a){var b=this;a=Sh(a);return new Promise(function(c,d){mi(b,function(e){a();c(e)},function(e){a();
d(e)})})};
r.Fc=function(a,b){return li(this,null,Sh(a),b)};
r.catch=fi.prototype.Fc;r.cancel=function(a){if(this.X==0){var b=new oi(a);ai(function(){pi(this,b)},this)}};
function pi(a,b){if(a.X==0)if(a.parent_){var c=a.parent_;if(c.Sa){for(var d=0,e=null,f=null,g=c.Sa;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&d>1)));g=g.next)e||(f=g);e&&(c.X==0&&d==1?pi(c,b):(f?(d=f,d.next==c.vb&&(c.vb=d),d.next=d.next.next):qi(c),ri(c,e,3,b)))}a.parent_=null}else gi(a,3,b)}
function ni(a,b){a.Sa||a.X!=2&&a.X!=3||si(a);a.vb?a.vb.next=b:a.Sa=b;a.vb=b}
function li(a,b,c,d){var e=ji(null,null,null);e.child=new fi(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);k===void 0&&h instanceof oi?g(h):f(k)}catch(l){g(l)}}:g});
e.child.parent_=a;ni(a,e);return e.child}
r.xf=function(a){this.X=0;gi(this,2,a)};
r.yf=function(a){this.X=0;gi(this,3,a)};
function gi(a,b,c){if(a.X==0){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.X=1;a:{var d=c,e=a.xf,f=a.yf;if(d instanceof fi){mi(d,e,f,a);var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Oa(d))try{var k=d.then;if(typeof k==="function"){ti(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.ab=c,a.X=b,a.parent_=null,si(a),b!=3||c instanceof oi||ui(a,c))}}
function ti(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function si(a){a.Jc||(a.Jc=!0,ai(a.pe,a))}
function qi(a){var b=null;a.Sa&&(b=a.Sa,a.Sa=b.next,b.next=null);a.Sa||(a.vb=null);return b}
r.pe=function(){for(var a;a=qi(this);)ri(this,a,this.X,this.ab);this.Jc=!1};
function ri(a,b,c,d){if(c==3&&b.h&&!b.j)for(;a&&a.pc;a=a.parent_)a.pc=!1;if(b.child)b.child.parent_=null,vi(b,c,d);else try{b.j?b.i.call(b.context):vi(b,c,d)}catch(e){wi.call(null,e)}Uh(ii,b)}
function vi(a,b,c){b==2?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function ui(a,b){a.pc=!0;ai(function(){a.pc&&wi.call(null,b)})}
var wi=Qc;function oi(a){bb.call(this,a)}
ab(oi,bb);oi.prototype.name="cancel";function xi(a,b){Ph.call(this);this.j=a||1;this.h=b||D;this.o=Wa(this.tf,this);this.u=$a()}
ab(xi,Ph);r=xi.prototype;r.enabled=!1;r.Ea=null;r.setInterval=function(a){this.j=a;this.Ea&&this.enabled?(this.stop(),this.start()):this.Ea&&this.stop()};
r.tf=function(){if(this.enabled){var a=$a()-this.u;a>0&&a<this.j*.8?this.Ea=this.h.setTimeout(this.o,this.j-a):(this.Ea&&(this.h.clearTimeout(this.Ea),this.Ea=null),Qh(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
r.start=function(){this.enabled=!0;this.Ea||(this.Ea=this.h.setTimeout(this.o,this.j),this.u=$a())};
r.stop=function(){this.enabled=!1;this.Ea&&(this.h.clearTimeout(this.Ea),this.Ea=null)};
r.ba=function(){xi.Aa.ba.call(this);this.stop();delete this.h};function yi(a){G.call(this);this.G=a;this.j=0;this.o=100;this.u=!1;this.i=new Map;this.D=new Set;this.flushInterval=3E4;this.h=new xi(this.flushInterval);this.h.listen("tick",this.ac,!1,this);uc(this,this.h)}
w(yi,G);r=yi.prototype;r.sendIsolatedPayload=function(a){this.u=a;this.o=1};
function zi(a){a.h.enabled||a.h.start();a.j++;a.j>=a.o&&a.ac()}
r.ac=function(){var a=this.i.values();a=[].concat(z(a)).filter(function(b){return b.h.size});
a.length&&this.G.flush(a,this.u);Ai(a);this.j=0;this.h.enabled&&this.h.stop()};
r.Mb=function(a){var b=C.apply(1,arguments);this.i.has(a)||this.i.set(a,new ph(a,b))};
r.Hc=function(a){var b=C.apply(1,arguments);this.i.has(a)||this.i.set(a,new qh(a,b))};
function Bi(a,b){return a.D.has(b)?void 0:a.i.get(b)}
r.Jb=function(a){this.Ud(a,1,C.apply(1,arguments))};
r.Ud=function(a,b){var c=C.apply(2,arguments),d=Bi(this,a);d&&d instanceof ph&&(d.j(b,c),zi(this))};
r.record=function(a,b){var c=C.apply(2,arguments),d=Bi(this,a);d&&d instanceof qh&&(d.record(b,c),zi(this))};
function Ai(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Ci(){}
Ci.prototype.serialize=function(a){var b=[];Di(this,a,b);return b.join("")};
function Di(a,b,c){if(b==null)c.push("null");else{if(typeof b=="object"){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Di(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],typeof f!="function"&&(c.push(e),Ei(d,c),c.push(":"),Di(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Ei(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Fi={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Gi=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Ei(a,b){b.push('"',a.replace(Gi,function(c){var d=Fi[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Fi[c]=d);return d}),'"')}
;function Hi(){Ph.call(this);this.headers=new Map;this.h=!1;this.J=null;this.o=this.Y="";this.j=this.U=this.D=this.P=!1;this.G=0;this.u=null;this.ma="";this.ha=!1}
ab(Hi,Ph);var Ii=/^https?$/i,Ji=["POST","PUT"],Ki=[];function Li(a,b,c,d,e,f,g){var h=new Hi;Ki.push(h);b&&h.listen("complete",b);Lh(h,"ready",h.de);f&&(h.G=Math.max(0,f));g&&(h.ha=g);h.send(a,c,d,e)}
r=Hi.prototype;r.de=function(){this.dispose();Sb(Ki,this)};
r.send=function(a,b,c,d){if(this.J)throw Error("[goog.net.XhrIo] Object is active with another request="+this.Y+"; newUri="+a);b=b?b.toUpperCase():"GET";this.Y=a;this.o="";this.P=!1;this.h=!0;this.J=new XMLHttpRequest;this.J.onreadystatechange=Sh(Wa(this.Ad,this));try{this.getStatus(),this.U=!0,this.J.open(b,String(a),!0),this.U=!1}catch(g){this.getStatus();Mi(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,d[e]);else if(typeof d.keys===
"function"&&typeof d.get==="function"){e=y(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=D.FormData&&a instanceof D.FormData;!(Lb(Ji,b)>=0)||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=y(c);for(d=b.next();!d.done;d=b.next())c=y(d.value),d=c.next().value,c=c.next().value,this.J.setRequestHeader(d,c);this.ma&&(this.J.responseType=this.ma);"withCredentials"in this.J&&this.J.withCredentials!==this.ha&&(this.J.withCredentials=this.ha);try{this.u&&(clearTimeout(this.u),this.u=null),this.G>0&&(this.getStatus(),this.u=setTimeout(this.wf.bind(this),this.G)),
this.getStatus(),this.D=!0,this.J.send(a),this.D=!1}catch(g){this.getStatus(),Mi(this,g)}};
r.wf=function(){typeof La!="undefined"&&this.J&&(this.o="Timed out after "+this.G+"ms, aborting",this.getStatus(),Qh(this,"timeout"),this.abort(8))};
function Mi(a,b){a.h=!1;a.J&&(a.j=!0,a.J.abort(),a.j=!1);a.o=b;Ni(a);Oi(a)}
function Ni(a){a.P||(a.P=!0,Qh(a,"complete"),Qh(a,"error"))}
r.abort=function(){this.J&&this.h&&(this.getStatus(),this.h=!1,this.j=!0,this.J.abort(),this.j=!1,Qh(this,"complete"),Qh(this,"abort"),Oi(this))};
r.ba=function(){this.J&&(this.h&&(this.h=!1,this.j=!0,this.J.abort(),this.j=!1),Oi(this,!0));Hi.Aa.ba.call(this)};
r.Ad=function(){this.ea||(this.U||this.D||this.j?Pi(this):this.Ne())};
r.Ne=function(){Pi(this)};
function Pi(a){if(a.h&&typeof La!="undefined")if(a.D&&(a.J?a.J.readyState:0)==4)setTimeout(a.Ad.bind(a),0);else if(Qh(a,"readystatechange"),a.isComplete()){a.getStatus();a.h=!1;try{if(Qi(a))Qh(a,"complete"),Qh(a,"success");else{try{var b=(a.J?a.J.readyState:0)>2?a.J.statusText:""}catch(c){b=""}a.o=b+" ["+a.getStatus()+"]";Ni(a)}}finally{Oi(a)}}}
function Oi(a,b){if(a.J){a.u&&(clearTimeout(a.u),a.u=null);var c=a.J;a.J=null;b||Qh(a,"ready");try{c.onreadystatechange=null}catch(d){}}}
r.isActive=function(){return!!this.J};
r.isComplete=function(){return(this.J?this.J.readyState:0)==4};
function Qi(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=b===0)a=bc(1,String(a.Y)),!a&&D.self&&D.self.location&&(a=D.self.location.protocol.slice(0,-1)),b=!Ii.test(a?a.toLowerCase():"");c=b}return c}
r.getStatus=function(){try{return(this.J?this.J.readyState:0)>2?this.J.status:-1}catch(a){return-1}};
r.getLastError=function(){return typeof this.o==="string"?this.o:String(this.o)};function Ri(){}
Ri.prototype.send=function(a,b,c){b=b===void 0?function(){}:b;
c=c===void 0?function(){}:c;
Li(a.url,function(d){d=d.target;if(Qi(d)){try{var e=d.J?d.J.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Dc,a.timeoutMillis,a.withCredentials)};
Ri.prototype.oc=function(){return 1};function Si(a,b){this.logger=a;this.event=b;this.startTime=Ti()}
Si.prototype.done=function(){this.logger.Ub(this.event,Ti()-this.startTime)};
function Ui(){Fc.apply(this,arguments)}
w(Ui,Fc);function Vi(a,b){var c=Ti();b=b();a.Ub("n",Ti()-c);return b}
function Wi(){Ui.apply(this,arguments)}
w(Wi,Ui);r=Wi.prototype;r.Oc=function(){};
r.Cb=function(){};
r.Ub=function(){};
r.Ha=function(){};
r.Cc=function(){};
r.Md=function(){};
function Xi(a){return{rf:new Ic(a),errorCount:new Mc(a),eventCount:new Kc(a),oe:new Lc(a),ci:new Jc(a),fi:new Nc(a),vh:new Oc(a),di:new Pc(a)}}
function Yi(a,b,c,d){a=ih(gh(eh(new dh(1828,"0"),a),new Ri));b.length&&hh(a,If(new Hf,b));d!==void 0&&(a.Ua=d);var e=new kh(1828,"","",!1,"",jh(a));uc(e,a);var f=new yi({flush:function(g){try{e.flush(g)}catch(h){c(h)}}});
f.addOnDisposeCallback(function(){setTimeout(function(){try{f.ac()}finally{e.dispose()}})});
f.o=1E5;f.flushInterval=3E4;f.h.setInterval(3E4);return f}
function Zi(a,b){G.call(this);var c=this;this.callback=a;this.i=b;this.h=-b;this.addOnDisposeCallback(function(){return void clearTimeout(c.timer)})}
w(Zi,G);function $i(a){if(a.timer===void 0){var b=Math.max(0,a.h+a.i-Ti());a.timer=setTimeout(function(){try{a.callback()}finally{a.h=Ti(),a.timer=void 0}},b)}}
function aj(a,b,c){Ui.call(this);this.metrics=a;this.Da=b;this.qb=c}
w(aj,Ui);aj.prototype.Oc=function(a){this.metrics.rf.record(a,this.Da)};
aj.prototype.Cb=function(a){this.metrics.eventCount.kb(a,this.Da)};
aj.prototype.Ub=function(a,b){this.metrics.oe.record(b,a,this.qb,this.Da)};
aj.prototype.Ha=function(a){this.metrics.errorCount.kb(a,this.qb,this.Da)};
function bj(a,b){b=b===void 0?[]:b;var c={Da:a.Da||"_",qb:a.qb||"",nc:a.nc||[],vc:a.vc|0,Ua:a.Ua,wc:a.wc||function(){},
Ib:a.Ib||function(e,f){return Yi(e,f,c.wc,c.Ua)}};
b=c.Ib("48",c.nc.concat(b));aj.call(this,Xi(b),c.Da,c.qb);var d=this;this.options=c;this.service=b;this.i=!a.Ib;this.h=new Zi(function(){return void d.service.ac()},c.vc);
this.addOnDisposeCallback(function(){d.h.dispose();d.i&&d.service.dispose()})}
w(bj,aj);bj.prototype.Md=function(a){var b=this;this.h.dispose();this.i&&this.service.dispose();this.service=this.options.Ib("48",this.options.nc.concat(a));this.h=new Zi(function(){return void b.service.ac()},this.options.vc);
this.metrics=Xi(this.service)};
bj.prototype.Cc=function(){$i(this.h)};
function Ti(){var a,b,c;return(c=(a=globalThis.performance)==null?void 0:(b=a.now)==null?void 0:b.call(a))!=null?c:Date.now()}
;function cj(a){a=M(a);L(this);this.F=a}
w(cj,N);function dj(a){a=M(a);L(this);this.F=a}
w(dj,N);function ej(a){a=M(a,0,"bfkj");L(this);this.F=a}
w(ej,N);var fj=function(a){return $d(function(b){var c;if(c=b instanceof a)L(b),c=!((b.F[J]|0)&2);return c})}(ej);
ej.Le="bfkj";function Bc(a){a=M(a);L(this);this.F=a}
w(Bc,N);function gj(a){a=M(a);L(this);this.F=a}
w(gj,N);var hj=Gf(gj);function ij(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function jj(a,b,c){if(a.disable)return new Wi;b=b?zc(b):[];if(c)return c.Md(b),c.share();a={Da:a.Da,qb:a.qb,nc:a.Ch,vc:a.Nh,Ua:a.Ua,wc:a.wc,Ib:a.Ib};c=b;c=c===void 0?[]:c;return new bj(a,c)}
function kj(a){function b(v,x,A,H){Promise.resolve().then(function(){k.done();h.Cc();h.dispose();g.resolve({Yd:v,qf:x,Re:A,xh:H})})}
function c(v,x,A,H){if(!d.logger.ea){var K="k";x?K="h":A&&(K="u");K!=="k"?H!==0&&(d.logger.Cb(K),d.logger.Ub(K,v)):d.i<=0?(d.logger.Cb(K),d.logger.Ub(K,v),d.i=Math.floor(Math.random()*200)):d.i--}}
G.call(this);var d=this;this.i=Math.floor(Math.random()*200);this.h=new gj;if("challenge"in a&&fj(a.challenge)){var e=xf(a.challenge,4);var f=xf(a.challenge,5);xf(a.challenge,7)&&(this.h=hj(xf(a.challenge,7)))}else e=a.program,f=a.globalName;this.addOnDisposeCallback(function(){var v,x,A;return B(function(H){if(H.h==1)return H.yield(d.j,2);v=H.i;x=v.qf;(A=x)==null||A();H.h=0})});
this.logger=jj(a.yd||{},this.h,a.yh);uc(this,this.logger);var g=new ij;this.j=g.promise;this.logger.Cb("t");var h=this.logger.share(),k=new Si(h,"t");if(!D[f])throw this.logger.Ha(25),Error("EGOU");if(!D[f].a)throw this.logger.Ha(26),Error("ELIU");try{var l=D[f].a;f=[];for(var m=[],n=zc(this.h),p=0;p<n.length;p++)f.push(n[p]),m.push(1);var t=Dc(this.h);for(n=0;n<t.length;n++)f.push(t[n]),m.push(2);this.u=y(l(e,b,!0,a.bi,c,[f,m],xf(this.h,5))).next().value;this.Yc=g.promise.then(function(){})}catch(v){throw this.logger.Ha(28),
v;
}}
w(kj,G);kj.prototype.snapshot=function(a){if(this.ea)throw Error("Already disposed");this.logger.Cb("n");var b=this.logger.share();return this.j.then(function(c){var d=c.Yd;return new Promise(function(e){var f=new Si(b,"n");d(function(g){f.done();b.Oc(g.length);b.Cc();b.dispose();e(g)},[a.wb,
a.bd,a.Bf,a.cd])})})};
kj.prototype.dd=function(a){var b=this;if(this.ea)throw Error("Already disposed");this.logger.Cb("n");var c=Vi(this.logger,function(){return b.u([a.wb,a.bd,a.Bf,a.cd])});
this.logger.Oc(c.length);this.logger.Cc();return c};
kj.prototype.o=function(a){this.j.then(function(b){var c;(c=b.Re)==null||c(a)})};function lj(a){if(!a)return null;a=Te(gf(a,4));return a===null||a===void 0?null:ib(a)}
;function mj(){this.promises={};this.h=null}
function nj(){mj.instance||(mj.instance=new mj);return mj.instance}
function oj(a,b){return pj(a,tf(b,cj,1,Yd),tf(b,dj,2,Yd),xf(b,3))}
function pj(a,b,c,d){if(!b&&!c)return Promise.resolve();if(!d)return qj(b,c);var e;(e=a.promises)[d]||(e[d]=new Promise(function(f,g){qj(b,c).then(function(){a.h=d;f()},function(h){delete a.promises[d];
g(h)})}));
return a.promises[d]}
function qj(a,b){return b?rj(b):a?sj(a):Promise.resolve()}
function rj(a){return new Promise(function(b,c){var d=ug("SCRIPT"),e=lj(a);Fb(d,e);d.onload=function(){vg(d);b()};
d.onerror=function(){vg(d);c(Error("EWLS"))};
(document.getElementsByTagName("HEAD")[0]||document.documentElement).appendChild(d)})}
function sj(a){return new Promise(function(b){var c=ug("SCRIPT");if(a){var d=Te(gf(a,6));d=d===null||d===void 0?null:Cb(d)}else d=null;c.textContent=Db(d);Eb(c);(document.getElementsByTagName("HEAD")[0]||document.documentElement).appendChild(c);vg(c);b()})}
;var tj=window;function uj(a){var b=vj;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function wj(){var a=[];uj(function(b){a.push(b)});
return a}
var vj={Cf:"allow-forms",Df:"allow-modals",Ef:"allow-orientation-lock",Ff:"allow-pointer-lock",Gf:"allow-popups",Hf:"allow-popups-to-escape-sandbox",If:"allow-presentation",Jf:"allow-same-origin",Kf:"allow-scripts",Lf:"allow-top-navigation",Mf:"allow-top-navigation-by-user-activation"},xj=ei(function(){return wj()});
function yj(){var a=zj(),b={};Mb(xj(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function zj(){var a=a===void 0?document:a;return a.createElement("iframe")}
;function Aj(a){typeof a=="number"&&(a=Math.round(a)+"px");return a}
;var Bj=(new Date).getTime();function Cj(a){Ph.call(this);var b=this;this.D=this.j=0;this.Ca=a!=null?a:{pa:function(e,f){return setTimeout(e,f)},
qa:function(e){clearTimeout(e)}};
var c,d;this.h=(d=(c=window.navigator)==null?void 0:c.onLine)!=null?d:!0;this.o=function(){return B(function(e){return e.yield(Dj(b),0)})};
window.addEventListener("offline",this.o);window.addEventListener("online",this.o);this.D||Ej(this)}
w(Cj,Ph);function Fj(){var a=Gj;Cj.instance||(Cj.instance=new Cj(a));return Cj.instance}
Cj.prototype.dispose=function(){window.removeEventListener("offline",this.o);window.removeEventListener("online",this.o);this.Ca.qa(this.D);delete Cj.instance};
Cj.prototype.ta=function(){return this.h};
function Ej(a){a.D=a.Ca.pa(function(){var b;return B(function(c){if(c.h==1)return a.h?((b=window.navigator)==null?0:b.onLine)?c.A(3):c.yield(Dj(a),3):c.yield(Dj(a),3);Ej(a);c.h=0})},3E4)}
function Dj(a,b){return a.u?a.u:a.u=new Promise(function(c){var d,e,f,g;return B(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=(e=d)==null?void 0:e.signal,g=!1,xa(h,2,3),d&&(a.j=a.Ca.pa(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.P=[h.j];h.M=0;h.o=0;a.u=void 0;a.j&&(a.Ca.qa(a.j),a.j=0);g!==a.h&&(a.h=g,a.h?Qh(a,"networkstatus-online"):Qh(a,"networkstatus-offline"));c(g);Aa(h);break;case 2:za(h),g=!1,h.A(3)}})})}
;function Hj(){this.data=[];this.h=-1}
Hj.prototype.set=function(a,b){b=b===void 0?!0:b;0<=a&&a<52&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
Hj.prototype.get=function(a){return!!this.data[a]};
function Ij(a){a.h===-1&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function Jj(){this.blockSize=-1}
;function Kj(){this.blockSize=-1;this.blockSize=64;this.h=[];this.u=[];this.M=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.o=this.i=0;this.reset()}
ab(Kj,Jj);Kj.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.o=this.i=0};
function Lj(a,b,c){c||(c=0);var d=a.M;if(typeof b==="string")for(var e=0;e<16;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;e<16;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(b=16;b<80;b++)c=d[b-3]^d[b-8]^d[b-14]^d[b-16],d[b]=(c<<1|c>>>31)&4294967295;b=a.h[0];c=a.h[1];e=a.h[2];for(var f=a.h[3],g=a.h[4],h,k,l=0;l<80;l++)l<40?l<20?(h=f^c&(e^f),k=1518500249):(h=c^e^f,k=1859775393):l<60?(h=c&e|f&(c|e),k=2400959708):(h=c^e^f,k=3395469782),
h=(b<<5|b>>>27)+h+g+k+d[l]&4294967295,g=f,f=e,e=(c<<30|c>>>2)&4294967295,c=b,b=h;a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+e&4294967295;a.h[3]=a.h[3]+f&4294967295;a.h[4]=a.h[4]+g&4294967295}
Kj.prototype.update=function(a,b){if(a!=null){b===void 0&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.u,f=this.i;d<b;){if(f==0)for(;d<=c;)Lj(this,a,d),d+=this.blockSize;if(typeof a==="string")for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Lj(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Lj(this,e);f=0;break}}this.i=f;this.o+=b}};
Kj.prototype.digest=function(){var a=[],b=this.o*8;this.i<56?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;c>=56;c--)this.u[c]=b&255,b/=256;Lj(this,this.u);for(c=b=0;c<5;c++)for(var d=24;d>=0;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function Mj(a){return typeof a.className=="string"?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Nj(a,b){typeof a.className=="string"?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Oj(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Mj(a).match(/\S+/g)||[],b=Lb(a,b)>=0);return b}
function Pj(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Oj(a,"inverted-hdpi")&&Nj(a,Array.prototype.filter.call(a.classList?a.classList:Mj(a).match(/\S+/g)||[],function(b){return b!="inverted-hdpi"}).join(" "))}
;function Qj(){}
Qj.prototype.next=function(){return Rj};
var Rj={done:!0,value:void 0};Qj.prototype.tb=function(){return this};function Sj(a){if(a instanceof Tj||a instanceof Uj||a instanceof Vj)return a;if(typeof a.next=="function")return new Tj(function(){return a});
if(typeof a[Symbol.iterator]=="function")return new Tj(function(){return a[Symbol.iterator]()});
if(typeof a.tb=="function")return new Tj(function(){return a.tb()});
throw Error("Not an iterator or iterable.");}
function Tj(a){this.h=a}
Tj.prototype.tb=function(){return new Uj(this.h())};
Tj.prototype[Symbol.iterator]=function(){return new Vj(this.h())};
Tj.prototype.i=function(){return new Vj(this.h())};
function Uj(a){this.h=a}
w(Uj,Qj);Uj.prototype.next=function(){return this.h.next()};
Uj.prototype[Symbol.iterator]=function(){return new Vj(this.h)};
Uj.prototype.i=function(){return new Vj(this.h)};
function Vj(a){Tj.call(this,function(){return a});
this.j=a}
w(Vj,Tj);Vj.prototype.next=function(){return this.j.next()};function O(a){G.call(this);this.u=1;this.j=[];this.o=0;this.h=[];this.i={};this.D=!!a}
ab(O,G);r=O.prototype;r.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.u;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.u=e+3;d.push(e);return e};
r.unsubscribe=function(a,b,c){if(a=this.i[a]){var d=this.h;if(a=a.find(function(e){return d[e+1]==b&&d[e+2]==c}))return this.dc(a)}return!1};
r.dc=function(a){var b=this.h[a];if(b){var c=this.i[b];this.o!=0?(this.j.push(a),this.h[a+1]=function(){}):(c&&Sb(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
r.sb=function(a,b){var c=this.i[a];if(c){var d=Array(arguments.length-1),e=arguments.length,f;for(f=1;f<e;f++)d[f-1]=arguments[f];if(this.D)for(f=0;f<c.length;f++)e=c[f],Wj(this.h[e+1],this.h[e+2],d);else{this.o++;try{for(f=0,e=c.length;f<e&&!this.ea;f++){var g=c[f];this.h[g+1].apply(this.h[g+2],d)}}finally{if(this.o--,this.j.length>0&&this.o==0)for(;c=this.j.pop();)this.dc(c)}}return f!=0}return!1};
function Wj(a,b,c){ai(function(){a.apply(b,c)})}
r.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.dc,this),delete this.i[a])}else this.h.length=0,this.i={}};
r.ba=function(){O.Aa.ba.call(this);this.clear();this.j.length=0};function Xj(a){this.h=a}
Xj.prototype.set=function(a,b){b===void 0?this.h.remove(a):this.h.set(a,(new Ci).serialize(b))};
Xj.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(b!==null)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Xj.prototype.remove=function(a){this.h.remove(a)};function Yj(a){this.h=a}
ab(Yj,Xj);function Zj(a){this.data=a}
function ak(a){return a===void 0||a instanceof Zj?a:new Zj(a)}
Yj.prototype.set=function(a,b){Yj.Aa.set.call(this,a,ak(b))};
Yj.prototype.i=function(a){a=Yj.Aa.get.call(this,a);if(a===void 0||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Yj.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,a===void 0)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function bk(a){this.h=a}
ab(bk,Yj);bk.prototype.set=function(a,b,c){if(b=ak(b)){if(c){if(c<$a()){bk.prototype.remove.call(this,a);return}b.expiration=c}b.creation=$a()}bk.Aa.set.call(this,a,b)};
bk.prototype.i=function(a){var b=bk.Aa.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<$a()||c&&c>$a())bk.prototype.remove.call(this,a);else return b}};function ck(){}
;function dk(){}
ab(dk,ck);dk.prototype[Symbol.iterator]=function(){return Sj(this.tb(!0)).i()};
dk.prototype.clear=function(){var a=Array.from(this);a=y(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function ek(a){this.h=a;this.i=null}
ab(ek,dk);r=ek.prototype;r.isAvailable=function(){var a=this.h;if(a)try{a.setItem("__sak","1");a.removeItem("__sak");var b=!0}catch(c){b=c instanceof DOMException&&(c.name==="QuotaExceededError"||c.code===22||c.code===1014||c.name==="NS_ERROR_DOM_QUOTA_REACHED")&&a&&a.length!==0}else b=!1;return this.i=b};
r.set=function(a,b){fk(this);try{this.h.setItem(a,b)}catch(c){if(this.h.length==0)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
r.get=function(a){fk(this);a=this.h.getItem(a);if(typeof a!=="string"&&a!==null)throw"Storage mechanism: Invalid value was encountered";return a};
r.remove=function(a){fk(this);this.h.removeItem(a)};
r.tb=function(a){fk(this);var b=0,c=this.h,d=new Qj;d.next=function(){if(b>=c.length)return Rj;var e=c.key(b++);if(a)return{value:e,done:!1};e=c.getItem(e);if(typeof e!=="string")throw"Storage mechanism: Invalid value was encountered";return{value:e,done:!1}};
return d};
r.clear=function(){fk(this);this.h.clear()};
r.key=function(a){fk(this);return this.h.key(a)};
function fk(a){if(a.h==null)throw Error("Storage mechanism: Storage unavailable");var b;((b=a.i)!=null?b:a.isAvailable())||Qc(Error("Storage mechanism: Storage unavailable"))}
;function gk(){var a=null;try{a=D.localStorage||null}catch(b){}ek.call(this,a)}
ab(gk,ek);function hk(a,b){this.i=a;this.h=b+"::"}
ab(hk,dk);hk.prototype.set=function(a,b){this.i.set(this.h+a,b)};
hk.prototype.get=function(a){return this.i.get(this.h+a)};
hk.prototype.remove=function(a){this.i.remove(this.h+a)};
hk.prototype.tb=function(a){var b=this.i[Symbol.iterator](),c=this,d=new Qj;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return{value:a?e.slice(c.h.length):c.i.get(e),done:!1}};
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
var P={},ik=typeof Uint8Array!=="undefined"&&typeof Uint16Array!=="undefined"&&typeof Int32Array!=="undefined";P.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if(typeof c!=="object")throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
P.Zc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var jk={ub:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
rd:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},kk={ub:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
rd:function(a){return[].concat.apply([],a)}};
P.pf=function(){ik?(P.rb=Uint8Array,P.Ja=Uint16Array,P.Td=Int32Array,P.assign(P,jk)):(P.rb=Array,P.Ja=Array,P.Td=Array,P.assign(P,kk))};
P.pf();var lk=!0;try{new Uint8Array(1)}catch(a){lk=!1}
function mk(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if((f&64512)===55296&&b+1<d){var g=a.charCodeAt(b+1);(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=f<128?1:f<2048?2:f<65536?3:4}var h=new P.rb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),(f&64512)===55296&&b+1<d&&(g=a.charCodeAt(b+1),(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)),f<128?h[c++]=f:(f<2048?h[c++]=192|f>>>6:(f<65536?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var nk={};nk=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;c!==0;){f=c>2E3?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var ok={},pk,qk=[],rk=0;rk<256;rk++){pk=rk;for(var sk=0;sk<8;sk++)pk=pk&1?3988292384^pk>>>1:pk>>>1;qk[rk]=pk}ok=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^qk[(a^b[d])&255];return a^-1};var tk={};tk={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function uk(a){for(var b=a.length;--b>=0;)a[b]=0}
var vk=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],wk=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],xk=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],yk=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],zk=Array(576);uk(zk);var Ak=Array(60);uk(Ak);var Bk=Array(512);uk(Bk);var Ck=Array(256);uk(Ck);var Dk=Array(29);uk(Dk);var Ek=Array(30);uk(Ek);function Fk(a,b,c,d,e){this.Jd=a;this.se=b;this.re=c;this.ke=d;this.Ke=e;this.ud=a&&a.length}
var Gk,Hk,Ik;function Jk(a,b){this.qd=a;this.Eb=0;this.bb=b}
function Kk(a,b){a.aa[a.pending++]=b&255;a.aa[a.pending++]=b>>>8&255}
function Lk(a,b,c){a.ia>16-c?(a.oa|=b<<a.ia&65535,Kk(a,a.oa),a.oa=b>>16-a.ia,a.ia+=c-16):(a.oa|=b<<a.ia&65535,a.ia+=c)}
function Mk(a,b,c){Lk(a,c[b*2],c[b*2+1])}
function Nk(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(--b>0);return c>>>1}
function Ok(a,b,c){var d=Array(16),e=0,f;for(f=1;f<=15;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[c*2+1],e!==0&&(a[c*2]=Nk(d[e]++,e))}
function Pk(a){var b;for(b=0;b<286;b++)a.ra[b*2]=0;for(b=0;b<30;b++)a.gb[b*2]=0;for(b=0;b<19;b++)a.ja[b*2]=0;a.ra[512]=1;a.Oa=a.Hb=0;a.ya=a.matches=0}
function Qk(a){a.ia>8?Kk(a,a.oa):a.ia>0&&(a.aa[a.pending++]=a.oa);a.oa=0;a.ia=0}
function Rk(a,b,c){Qk(a);Kk(a,c);Kk(a,~c);P.ub(a.aa,a.window,b,c,a.pending);a.pending+=c}
function Sk(a,b,c,d){var e=b*2,f=c*2;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function Tk(a,b,c){for(var d=a.da[c],e=c<<1;e<=a.Na;){e<a.Na&&Sk(b,a.da[e+1],a.da[e],a.depth)&&e++;if(Sk(b,d,a.da[e],a.depth))break;a.da[c]=a.da[e];c=e;e<<=1}a.da[c]=d}
function Uk(a,b,c){var d=0;if(a.ya!==0){do{var e=a.aa[a.Pb+d*2]<<8|a.aa[a.Pb+d*2+1];var f=a.aa[a.Nc+d];d++;if(e===0)Mk(a,f,b);else{var g=Ck[f];Mk(a,g+256+1,b);var h=vk[g];h!==0&&(f-=Dk[g],Lk(a,f,h));e--;g=e<256?Bk[e]:Bk[256+(e>>>7)];Mk(a,g,c);h=wk[g];h!==0&&(e-=Ek[g],Lk(a,e,h))}}while(d<a.ya)}Mk(a,256,b)}
function Vk(a,b){var c=b.qd,d=b.bb.Jd,e=b.bb.ud,f=b.bb.ke,g,h=-1;a.Na=0;a.zb=573;for(g=0;g<f;g++)c[g*2]!==0?(a.da[++a.Na]=h=g,a.depth[g]=0):c[g*2+1]=0;for(;a.Na<2;){var k=a.da[++a.Na]=h<2?++h:0;c[k*2]=1;a.depth[k]=0;a.Oa--;e&&(a.Hb-=d[k*2+1])}b.Eb=h;for(g=a.Na>>1;g>=1;g--)Tk(a,c,g);k=f;do g=a.da[1],a.da[1]=a.da[a.Na--],Tk(a,c,1),d=a.da[1],a.da[--a.zb]=g,a.da[--a.zb]=d,c[k*2]=c[g*2]+c[d*2],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[g*2+1]=c[d*2+1]=k,a.da[1]=k++,Tk(a,c,1);while(a.Na>=
2);a.da[--a.zb]=a.da[1];g=b.qd;k=b.Eb;d=b.bb.Jd;e=b.bb.ud;f=b.bb.se;var l=b.bb.re,m=b.bb.Ke,n,p=0;for(n=0;n<=15;n++)a.Ka[n]=0;g[a.da[a.zb]*2+1]=0;for(b=a.zb+1;b<573;b++){var t=a.da[b];n=g[g[t*2+1]*2+1]+1;n>m&&(n=m,p++);g[t*2+1]=n;if(!(t>k)){a.Ka[n]++;var v=0;t>=l&&(v=f[t-l]);var x=g[t*2];a.Oa+=x*(n+v);e&&(a.Hb+=x*(d[t*2+1]+v))}}if(p!==0){do{for(n=m-1;a.Ka[n]===0;)n--;a.Ka[n]--;a.Ka[n+1]+=2;a.Ka[m]--;p-=2}while(p>0);for(n=m;n!==0;n--)for(t=a.Ka[n];t!==0;)d=a.da[--b],d>k||(g[d*2+1]!==n&&(a.Oa+=(n-g[d*
2+1])*g[d*2],g[d*2+1]=n),t--)}Ok(c,h,a.Ka)}
function Wk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);b[(c+1)*2+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];++g<h&&l===f||(g<k?a.ja[l*2]+=g:l!==0?(l!==e&&a.ja[l*2]++,a.ja[32]++):g<=10?a.ja[34]++:a.ja[36]++,g=0,e=l,f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function Xk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];if(!(++g<h&&l===f)){if(g<k){do Mk(a,l,a.ja);while(--g!==0)}else l!==0?(l!==e&&(Mk(a,l,a.ja),g--),Mk(a,16,a.ja),Lk(a,g-3,2)):g<=10?(Mk(a,17,a.ja),Lk(a,g-3,3)):(Mk(a,18,a.ja),Lk(a,g-11,7));g=0;e=l;f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function Yk(a){var b=4093624447,c;for(c=0;c<=31;c++,b>>>=1)if(b&1&&a.ra[c*2]!==0)return 0;if(a.ra[18]!==0||a.ra[20]!==0||a.ra[26]!==0)return 1;for(c=32;c<256;c++)if(a.ra[c*2]!==0)return 1;return 0}
var Zk=!1;function $k(a,b,c){a.aa[a.Pb+a.ya*2]=b>>>8&255;a.aa[a.Pb+a.ya*2+1]=b&255;a.aa[a.Nc+a.ya]=c&255;a.ya++;b===0?a.ra[c*2]++:(a.matches++,b--,a.ra[(Ck[c]+256+1)*2]++,a.gb[(b<256?Bk[b]:Bk[256+(b>>>7)])*2]++);return a.ya===a.Tb-1}
;function al(a,b){a.msg=tk[b];return b}
function bl(a){for(var b=a.length;--b>=0;)a[b]=0}
function cl(a){var b=a.state,c=b.pending;c>a.S&&(c=a.S);c!==0&&(P.ub(a.output,b.aa,b.Wb,c,a.Fb),a.Fb+=c,b.Wb+=c,a.ed+=c,a.S-=c,b.pending-=c,b.pending===0&&(b.Wb=0))}
function dl(a,b){var c=a.va>=0?a.va:-1,d=a.v-a.va,e=0;if(a.level>0){a.K.Ic===2&&(a.K.Ic=Yk(a));Vk(a,a.uc);Vk(a,a.kc);Wk(a,a.ra,a.uc.Eb);Wk(a,a.gb,a.kc.Eb);Vk(a,a.md);for(e=18;e>=3&&a.ja[yk[e]*2+1]===0;e--);a.Oa+=3*(e+1)+5+5+4;var f=a.Oa+3+7>>>3;var g=a.Hb+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&c!==-1)Lk(a,b?1:0,3),Rk(a,c,d);else if(a.strategy===4||g===f)Lk(a,2+(b?1:0),3),Uk(a,zk,Ak);else{Lk(a,4+(b?1:0),3);c=a.uc.Eb+1;d=a.kc.Eb+1;e+=1;Lk(a,c-257,5);Lk(a,d-1,5);Lk(a,e-4,4);for(f=0;f<e;f++)Lk(a,
a.ja[yk[f]*2+1],3);Xk(a,a.ra,c-1);Xk(a,a.gb,d-1);Uk(a,a.ra,a.gb)}Pk(a);b&&Qk(a);a.va=a.v;cl(a.K)}
function R(a,b){a.aa[a.pending++]=b}
function el(a,b){a.aa[a.pending++]=b>>>8&255;a.aa[a.pending++]=b&255}
function fl(a,b){var c=a.xd,d=a.v,e=a.wa,f=a.zd,g=a.v>a.la-262?a.v-(a.la-262):0,h=a.window,k=a.cb,l=a.Ia,m=a.v+258,n=h[d+e-1],p=h[d+e];a.wa>=a.td&&(c>>=2);f>a.B&&(f=a.B);do{var t=b;if(h[t+e]===p&&h[t+e-1]===n&&h[t]===h[d]&&h[++t]===h[d+1]){d+=2;for(t++;h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&d<m;);t=258-(m-d);d=m-258;if(t>e){a.Db=b;e=t;if(t>=f)break;n=h[d+e-1];p=h[d+e]}}}while((b=l[b&k])>g&&--c!==0);return e<=
a.B?e:a.B}
function gl(a){var b=a.la,c;do{var d=a.Rd-a.B-a.v;if(a.v>=b+(b-262)){P.ub(a.window,a.window,b,b,0);a.Db-=b;a.v-=b;a.va-=b;var e=c=a.sc;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ia[--e],a.Ia[e]=f>=b?f-b:0;while(--c);d+=b}if(a.K.na===0)break;e=a.K;c=a.window;f=a.v+a.B;var g=e.na;g>d&&(g=d);g===0?c=0:(e.na-=g,P.ub(c,e.input,e.nb,g,f),e.state.wrap===1?e.I=nk(e.I,c,g,f):e.state.wrap===2&&(e.I=ok(e.I,c,g,f)),e.nb+=g,e.pb+=g,c=g);a.B+=c;if(a.B+a.sa>=3)for(d=a.v-a.sa,a.R=a.window[d],
a.R=(a.R<<a.Ma^a.window[d+1])&a.La;a.sa&&!(a.R=(a.R<<a.Ma^a.window[d+3-1])&a.La,a.Ia[d&a.cb]=a.head[a.R],a.head[a.R]=d,d++,a.sa--,a.B+a.sa<3););}while(a.B<262&&a.K.na!==0)}
function hl(a,b){for(var c;;){if(a.B<262){gl(a);if(a.B<262&&b===0)return 1;if(a.B===0)break}c=0;a.B>=3&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,c=a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v);c!==0&&a.v-c<=a.la-262&&(a.T=fl(a,c));if(a.T>=3)if(c=$k(a,a.v-a.Db,a.T-3),a.B-=a.T,a.T<=a.Pc&&a.B>=3){a.T--;do a.v++,a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v;while(--a.T!==0);a.v++}else a.v+=a.T,a.T=0,a.R=a.window[a.v],a.R=(a.R<<a.Ma^a.window[a.v+1])&a.La;else c=$k(a,0,
a.window[a.v]),a.B--,a.v++;if(c&&(dl(a,!1),a.K.S===0))return 1}a.sa=a.v<2?a.v:2;return b===4?(dl(a,!0),a.K.S===0?3:4):a.ya&&(dl(a,!1),a.K.S===0)?1:2}
function il(a,b){for(var c,d;;){if(a.B<262){gl(a);if(a.B<262&&b===0)return 1;if(a.B===0)break}c=0;a.B>=3&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,c=a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v);a.wa=a.T;a.Cd=a.Db;a.T=2;c!==0&&a.wa<a.Pc&&a.v-c<=a.la-262&&(a.T=fl(a,c),a.T<=5&&(a.strategy===1||a.T===3&&a.v-a.Db>4096)&&(a.T=2));if(a.wa>=3&&a.T<=a.wa){d=a.v+a.B-3;c=$k(a,a.v-1-a.Cd,a.wa-3);a.B-=a.wa-1;a.wa-=2;do++a.v<=d&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v);
while(--a.wa!==0);a.lb=0;a.T=2;a.v++;if(c&&(dl(a,!1),a.K.S===0))return 1}else if(a.lb){if((c=$k(a,0,a.window[a.v-1]))&&dl(a,!1),a.v++,a.B--,a.K.S===0)return 1}else a.lb=1,a.v++,a.B--}a.lb&&($k(a,0,a.window[a.v-1]),a.lb=0);a.sa=a.v<2?a.v:2;return b===4?(dl(a,!0),a.K.S===0?3:4):a.ya&&(dl(a,!1),a.K.S===0)?1:2}
function jl(a,b){for(var c,d,e,f=a.window;;){if(a.B<=258){gl(a);if(a.B<=258&&b===0)return 1;if(a.B===0)break}a.T=0;if(a.B>=3&&a.v>0&&(d=a.v-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.v+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.T=258-(e-d);a.T>a.B&&(a.T=a.B)}a.T>=3?(c=$k(a,1,a.T-3),a.B-=a.T,a.v+=a.T,a.T=0):(c=$k(a,0,a.window[a.v]),a.B--,a.v++);if(c&&(dl(a,!1),a.K.S===0))return 1}a.sa=0;return b===4?(dl(a,!0),a.K.S===0?3:4):
a.ya&&(dl(a,!1),a.K.S===0)?1:2}
function kl(a,b){for(var c;;){if(a.B===0&&(gl(a),a.B===0)){if(b===0)return 1;break}a.T=0;c=$k(a,0,a.window[a.v]);a.B--;a.v++;if(c&&(dl(a,!1),a.K.S===0))return 1}a.sa=0;return b===4?(dl(a,!0),a.K.S===0?3:4):a.ya&&(dl(a,!1),a.K.S===0)?1:2}
function ll(a,b,c,d,e){this.xe=a;this.Je=b;this.Me=c;this.Ie=d;this.te=e}
var ml;ml=[new ll(0,0,0,0,function(a,b){var c=65535;for(c>a.za-5&&(c=a.za-5);;){if(a.B<=1){gl(a);if(a.B===0&&b===0)return 1;if(a.B===0)break}a.v+=a.B;a.B=0;var d=a.va+c;if(a.v===0||a.v>=d)if(a.B=a.v-d,a.v=d,dl(a,!1),a.K.S===0)return 1;if(a.v-a.va>=a.la-262&&(dl(a,!1),a.K.S===0))return 1}a.sa=0;if(b===4)return dl(a,!0),a.K.S===0?3:4;a.v>a.va&&dl(a,!1);return 1}),
new ll(4,4,8,4,hl),new ll(4,5,16,8,hl),new ll(4,6,32,32,hl),new ll(4,4,16,16,il),new ll(8,16,32,32,il),new ll(8,16,128,128,il),new ll(8,32,128,256,il),new ll(32,128,258,1024,il),new ll(32,258,258,4096,il)];
function nl(){this.K=null;this.status=0;this.aa=null;this.wrap=this.pending=this.Wb=this.za=0;this.H=null;this.Ba=0;this.method=8;this.Bb=-1;this.cb=this.hd=this.la=0;this.window=null;this.Rd=0;this.head=this.Ia=null;this.zd=this.td=this.strategy=this.level=this.Pc=this.xd=this.wa=this.B=this.Db=this.v=this.lb=this.Cd=this.T=this.va=this.Ma=this.La=this.Lc=this.sc=this.R=0;this.ra=new P.Ja(1146);this.gb=new P.Ja(122);this.ja=new P.Ja(78);bl(this.ra);bl(this.gb);bl(this.ja);this.md=this.kc=this.uc=
null;this.Ka=new P.Ja(16);this.da=new P.Ja(573);bl(this.da);this.zb=this.Na=0;this.depth=new P.Ja(573);bl(this.depth);this.ia=this.oa=this.sa=this.matches=this.Hb=this.Oa=this.Pb=this.ya=this.Tb=this.Nc=0}
function ol(a,b){if(!a||!a.state||b>5||b<0)return a?al(a,-2):-2;var c=a.state;if(!a.output||!a.input&&a.na!==0||c.status===666&&b!==4)return al(a,a.S===0?-5:-2);c.K=a;var d=c.Bb;c.Bb=b;if(c.status===42)if(c.wrap===2)a.I=0,R(c,31),R(c,139),R(c,8),c.H?(R(c,(c.H.text?1:0)+(c.H.Va?2:0)+(c.H.extra?4:0)+(c.H.name?8:0)+(c.H.comment?16:0)),R(c,c.H.time&255),R(c,c.H.time>>8&255),R(c,c.H.time>>16&255),R(c,c.H.time>>24&255),R(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),R(c,c.H.os&255),c.H.extra&&c.H.extra.length&&
(R(c,c.H.extra.length&255),R(c,c.H.extra.length>>8&255)),c.H.Va&&(a.I=ok(a.I,c.aa,c.pending,0)),c.Ba=0,c.status=69):(R(c,0),R(c,0),R(c,0),R(c,0),R(c,0),R(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),R(c,3),c.status=113);else{var e=8+(c.hd-8<<4)<<8;e|=(c.strategy>=2||c.level<2?0:c.level<6?1:c.level===6?2:3)<<6;c.v!==0&&(e|=32);c.status=113;el(c,e+(31-e%31));c.v!==0&&(el(c,a.I>>>16),el(c,a.I&65535));a.I=1}if(c.status===69)if(c.H.extra){for(e=c.pending;c.Ba<(c.H.extra.length&65535)&&(c.pending!==c.za||
(c.H.Va&&c.pending>e&&(a.I=ok(a.I,c.aa,c.pending-e,e)),cl(a),e=c.pending,c.pending!==c.za));)R(c,c.H.extra[c.Ba]&255),c.Ba++;c.H.Va&&c.pending>e&&(a.I=ok(a.I,c.aa,c.pending-e,e));c.Ba===c.H.extra.length&&(c.Ba=0,c.status=73)}else c.status=73;if(c.status===73)if(c.H.name){e=c.pending;do{if(c.pending===c.za&&(c.H.Va&&c.pending>e&&(a.I=ok(a.I,c.aa,c.pending-e,e)),cl(a),e=c.pending,c.pending===c.za)){var f=1;break}f=c.Ba<c.H.name.length?c.H.name.charCodeAt(c.Ba++)&255:0;R(c,f)}while(f!==0);c.H.Va&&c.pending>
e&&(a.I=ok(a.I,c.aa,c.pending-e,e));f===0&&(c.Ba=0,c.status=91)}else c.status=91;if(c.status===91)if(c.H.comment){e=c.pending;do{if(c.pending===c.za&&(c.H.Va&&c.pending>e&&(a.I=ok(a.I,c.aa,c.pending-e,e)),cl(a),e=c.pending,c.pending===c.za)){f=1;break}f=c.Ba<c.H.comment.length?c.H.comment.charCodeAt(c.Ba++)&255:0;R(c,f)}while(f!==0);c.H.Va&&c.pending>e&&(a.I=ok(a.I,c.aa,c.pending-e,e));f===0&&(c.status=103)}else c.status=103;c.status===103&&(c.H.Va?(c.pending+2>c.za&&cl(a),c.pending+2<=c.za&&(R(c,
a.I&255),R(c,a.I>>8&255),a.I=0,c.status=113)):c.status=113);if(c.pending!==0){if(cl(a),a.S===0)return c.Bb=-1,0}else if(a.na===0&&(b<<1)-(b>4?9:0)<=(d<<1)-(d>4?9:0)&&b!==4)return al(a,-5);if(c.status===666&&a.na!==0)return al(a,-5);if(a.na!==0||c.B!==0||b!==0&&c.status!==666){d=c.strategy===2?kl(c,b):c.strategy===3?jl(c,b):ml[c.level].te(c,b);if(d===3||d===4)c.status=666;if(d===1||d===3)return a.S===0&&(c.Bb=-1),0;if(d===2&&(b===1?(Lk(c,2,3),Mk(c,256,zk),c.ia===16?(Kk(c,c.oa),c.oa=0,c.ia=0):c.ia>=
8&&(c.aa[c.pending++]=c.oa&255,c.oa>>=8,c.ia-=8)):b!==5&&(Lk(c,0,3),Rk(c,0,0),b===3&&(bl(c.head),c.B===0&&(c.v=0,c.va=0,c.sa=0))),cl(a),a.S===0))return c.Bb=-1,0}if(b!==4)return 0;if(c.wrap<=0)return 1;c.wrap===2?(R(c,a.I&255),R(c,a.I>>8&255),R(c,a.I>>16&255),R(c,a.I>>24&255),R(c,a.pb&255),R(c,a.pb>>8&255),R(c,a.pb>>16&255),R(c,a.pb>>24&255)):(el(c,a.I>>>16),el(c,a.I&65535));cl(a);c.wrap>0&&(c.wrap=-c.wrap);return c.pending!==0?0:1}
;var pl={};pl=function(){this.input=null;this.pb=this.na=this.nb=0;this.output=null;this.ed=this.S=this.Fb=0;this.msg="";this.state=null;this.Ic=2;this.I=0};var ql=Object.prototype.toString;
function rl(a){if(!(this instanceof rl))return new rl(a);a=this.options=P.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&a.windowBits>0?a.windowBits=-a.windowBits:a.gzip&&a.windowBits>0&&a.windowBits<16&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.K=new pl;this.K.S=0;var b=this.K;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;c===-1&&(c=6);e<0?(h=0,e=-e):e>15&&(h=2,e-=16);if(f<1||f>
9||d!==8||e<8||e>15||c<0||c>9||g<0||g>4)b=al(b,-2);else{e===8&&(e=9);var k=new nl;b.state=k;k.K=b;k.wrap=h;k.H=null;k.hd=e;k.la=1<<k.hd;k.cb=k.la-1;k.Lc=f+7;k.sc=1<<k.Lc;k.La=k.sc-1;k.Ma=~~((k.Lc+3-1)/3);k.window=new P.rb(k.la*2);k.head=new P.Ja(k.sc);k.Ia=new P.Ja(k.la);k.Tb=1<<f+6;k.za=k.Tb*4;k.aa=new P.rb(k.za);k.Pb=1*k.Tb;k.Nc=3*k.Tb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.pb=b.ed=0;b.Ic=2;c=b.state;c.pending=0;c.Wb=0;c.wrap<0&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.I=c.wrap===2?
0:1;c.Bb=0;if(!Zk){d=Array(16);for(f=g=0;f<28;f++)for(Dk[f]=g,e=0;e<1<<vk[f];e++)Ck[g++]=f;Ck[g-1]=f;for(f=g=0;f<16;f++)for(Ek[f]=g,e=0;e<1<<wk[f];e++)Bk[g++]=f;for(g>>=7;f<30;f++)for(Ek[f]=g<<7,e=0;e<1<<wk[f]-7;e++)Bk[256+g++]=f;for(e=0;e<=15;e++)d[e]=0;for(e=0;e<=143;)zk[e*2+1]=8,e++,d[8]++;for(;e<=255;)zk[e*2+1]=9,e++,d[9]++;for(;e<=279;)zk[e*2+1]=7,e++,d[7]++;for(;e<=287;)zk[e*2+1]=8,e++,d[8]++;Ok(zk,287,d);for(e=0;e<30;e++)Ak[e*2+1]=5,Ak[e*2]=Nk(e,5);Gk=new Fk(zk,vk,257,286,15);Hk=new Fk(Ak,
wk,0,30,15);Ik=new Fk([],xk,0,19,7);Zk=!0}c.uc=new Jk(c.ra,Gk);c.kc=new Jk(c.gb,Hk);c.md=new Jk(c.ja,Ik);c.oa=0;c.ia=0;Pk(c);c=0}else c=al(b,-2);c===0&&(b=b.state,b.Rd=2*b.la,bl(b.head),b.Pc=ml[b.level].Je,b.td=ml[b.level].xe,b.zd=ml[b.level].Me,b.xd=ml[b.level].Ie,b.v=0,b.va=0,b.B=0,b.sa=0,b.T=b.wa=2,b.lb=0,b.R=0);b=c}}else b=-2;if(b!==0)throw Error(tk[b]);a.header&&(b=this.K)&&b.state&&b.state.wrap===2&&(b.state.H=a.header);if(a.dictionary){var l;typeof a.dictionary==="string"?l=mk(a.dictionary):
ql.call(a.dictionary)==="[object ArrayBuffer]"?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.K;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,b===2||b===1&&l.status!==42||l.B)b=-2;else{b===1&&(a.I=nk(a.I,f,g,0));l.wrap=0;g>=l.la&&(b===0&&(bl(l.head),l.v=0,l.va=0,l.sa=0),c=new P.rb(l.la),P.ub(c,f,g-l.la,l.la,0),f=c,g=l.la);c=a.na;d=a.nb;e=a.input;a.na=g;a.nb=0;a.input=f;for(gl(l);l.B>=3;){f=l.v;g=l.B-2;do l.R=(l.R<<l.Ma^l.window[f+3-1])&l.La,l.Ia[f&l.cb]=l.head[l.R],l.head[l.R]=f,f++;while(--g);
l.v=f;l.B=2;gl(l)}l.v+=l.B;l.va=l.v;l.sa=l.B;l.B=0;l.T=l.wa=2;l.lb=0;a.nb=d;a.input=e;a.na=c;l.wrap=b;b=0}else b=-2;if(b!==0)throw Error(tk[b]);this.sh=!0}}
rl.prototype.push=function(a,b){var c=this.K,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:b===!0?4:0;typeof a==="string"?c.input=mk(a):ql.call(a)==="[object ArrayBuffer]"?c.input=new Uint8Array(a):c.input=a;c.nb=0;c.na=c.input.length;do{c.S===0&&(c.output=new P.rb(d),c.Fb=0,c.S=d);a=ol(c,e);if(a!==1&&a!==0)return sl(this,a),this.ended=!0,!1;if(c.S===0||c.na===0&&(e===4||e===2))if(this.options.to==="string"){var f=P.Zc(c.output,c.Fb);b=f;f=f.length;if(f<65537&&(b.subarray&&lk||!b.subarray))b=
String.fromCharCode.apply(null,P.Zc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=P.Zc(c.output,c.Fb),this.chunks.push(b)}while((c.na>0||c.S===0)&&a!==1);if(e===4)return(c=this.K)&&c.state?(d=c.state.status,d!==42&&d!==69&&d!==73&&d!==91&&d!==103&&d!==113&&d!==666?a=al(c,-2):(c.state=null,a=d===113?al(c,-3):0)):a=-2,sl(this,a),this.ended=!0,a===0;e===2&&(sl(this,0),c.S=0);return!0};
function sl(a,b){b===0&&(a.result=a.options.to==="string"?a.chunks.join(""):P.rd(a.chunks));a.chunks=[];a.err=b;a.msg=a.K.msg}
function tl(a,b){b=b||{};b.gzip=!0;b=new rl(b);b.push(a,!0);if(b.err)throw b.msg||tk[b.err];return b.result}
;function ul(a){return a?(a=a.privateDoNotAccessOrElseSafeScriptWrappedValue)?Cb(a):null:null}
function vl(a){return a?(a=a.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue)?ib(a):null:null}
;function wl(a){return ib(a===null?"null":a===void 0?"undefined":a)}
;function xl(a){this.name=a}
;var yl=new xl("rawColdConfigGroup");var zl=new xl("rawHotConfigGroup");function Al(a){a=M(a);L(this);this.F=a}
w(Al,N);function Bl(a){a=M(a);L(this);this.F=a}
w(Bl,N);Bl.prototype.setTrackingParams=function(a){if(a!=null)if(typeof a==="string")a=a?new zd(a,yd):Bd||(Bd=new zd(null,yd));else if(a.constructor!==zd)if(td&&a!=null&&a instanceof Uint8Array)a instanceof Uint8Array||Array.isArray(a),a=a.length?new zd(new Uint8Array(a),yd):Bd||(Bd=new zd(null,yd));else throw Error();return jf(this,1,a)};var Cl=new xl("continuationCommand");var Dl=new xl("webCommandMetadata");var El=new xl("signalServiceEndpoint");var Fl={Sf:"EMBEDDED_PLAYER_MODE_UNKNOWN",Pf:"EMBEDDED_PLAYER_MODE_DEFAULT",Rf:"EMBEDDED_PLAYER_MODE_PFP",Qf:"EMBEDDED_PLAYER_MODE_PFL"};var Gl=new xl("feedbackEndpoint");var ee={Vg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNKNOWN",pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_FOR_TESTING",Gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_RESUME_TO_HOME_TTL",Ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_START_TO_SHORTS_ANALYSIS_SLICE",eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DEVICE_LAYER_SLICE",Ug:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNIFIED_LAYER_SLICE",Xg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_VISITOR_LAYER_SLICE",Mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SHOW_SHEET_COMMAND_HANDLER_BLOCK",
Zg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_MIGRATED_COMPONENT",Yg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_CHANNEL_NAME_TOOLTIP",Jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATION_LOCK_SUPPORTED",Pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_THEATER_MODE_ENABLED",eh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_PIN_SUGGESTION",dh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_LONG_PRESS_EDU_TOAST",bh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_AMBIENT",Qg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TIME_WATCHED_PANEL",
Lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SEARCH_FROM_SEARCH_BAR_OVERLAY",fh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_VOICE_SEARCH_EDU_TOAST",Og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SUGGESTED_LANGUAGE_SELECTED",gh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_TRIGGER_SHORTS_PIP",wg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IN_ZP_VOICE_CRASHY_SET",Cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_SUPPRESSED",Bg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_ALLOWED",Eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_PULL_TO_REFRESH_ATTEMPT",
ah:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_BLOCK_KABUKI",Fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_TALL_SCREEN",Dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_NORMAL_SCREEN",Wf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_ENABLED",Vf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_DISABLED",Xf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_AUTOPLAY_ENABLED",Yf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_CAST_MATCH_OCCURRED",ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_ELIGIBLE",lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ENDSCREEN_TRIGGERED",
Ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_TRIGGERED",zg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_LACT_THRESHOLD_EXCEEDED",qg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MATCHED_ON_REMOTE_CONNECTION",sg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHABLE_ON_REMOTE_CONNECTION",rg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MISATTRIBUTED_ON_REMOTE_CONNECTION",vg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_TV_IS_SIGNED_IN_ON_REMOTE_CONNECTION",Sg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_COLD_ON_REMOTE_CONNECTION",
Tg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_NON_COLD_ON_REMOTE_CONNECTION",yg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ON_REMOTE_CONNECTION",dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_VALID",ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_INVALID",cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_UNDEFINED",Zf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_DEFINED",xg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_LACT_THRESHOLD_EXCEEDED",
Kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROUND_TRIP_HANDLING_ON_REMOTE_CONNECTION",ug:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHED_ON_REMOTE_CONNECTION_BEFORE_APP_RELOAD",tg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHED_ON_REMOTE_CONNECTION_AFTER_APP_RELOAD",jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_INELIGIBLE",Rg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TVHTML5_MID_ROLL_THRESHOLD_REACHED",ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_PENDING",
mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_ACTIVATED",kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_M2_ELIGIBLE",Hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATE_DEVICE_TO_LANDSCAPE",Ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATE_DEVICE_TO_PORTRAIT",hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMBEDS_FACEOFF_UI_EVENT",og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_RECEIVED",gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ELIGIBLE_TO_SUPPRESS_TRANSPORT_CONTROLS_BUTTONS",
Wg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_USER_HAS_THEATER_MODE_COOKIE_ENABLED",fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DOCUMENT_PICTURE_IN_PICTURE_SUPPORTED"};var Hl=new xl("shareEndpoint"),Il=new xl("shareEntityEndpoint"),Jl=new xl("shareEntityServiceEndpoint"),Kl=new xl("webPlayerShareEntityServiceEndpoint");var Ll=new xl("playlistEditEndpoint");var Ml=new xl("modifyChannelNotificationPreferenceEndpoint");var Nl=new xl("unsubscribeEndpoint");var Ol=new xl("subscribeEndpoint");function Pl(){var a=Ql;F("yt.ads.biscotti.getId_")||E("yt.ads.biscotti.getId_",a)}
function Rl(a){E("yt.ads.biscotti.lastId_",a)}
;function Sl(a,b){b.length>1?a[b[0]]=b[1]:b.length===1&&Object.assign(a,b[0])}
;var Tl=D.window,Ul,Vl,Wl=(Tl==null?void 0:(Ul=Tl.yt)==null?void 0:Ul.config_)||(Tl==null?void 0:(Vl=Tl.ytcfg)==null?void 0:Vl.data_)||{};E("yt.config_",Wl);function Xl(){Sl(Wl,arguments)}
function S(a,b){return a in Wl?Wl[a]:b}
function Yl(a){var b=Wl.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var Zl=[];function $l(a){Zl.forEach(function(b){return b(a)})}
function am(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){bm(b)}}:a}
function bm(a){var b=F("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=S("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),Xl("ERRORS",b));$l(a)}
function cm(a,b,c,d,e){var f=F("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=S("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),Xl("ERRORS",f))}
;var dm=/^[\w.]*$/,em={q:!0,search_query:!0};function fm(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(f.length===1&&f[0]||f.length===2)try{var g=gm(f[0]||""),h=gm(f[1]||"");if(g in c){var k=c[g];Array.isArray(k)?Tb(k,h):c[g]=[k,h]}else c[g]=h}catch(p){var l=p,m=f[0],n=String(fm);l.args=[{key:m,value:f[1],query:a,method:hm===n?"unchanged":n}];em.hasOwnProperty(m)||cm(l)}}return c}
var hm=String(fm);function im(a){var b=[];gg(a,function(c,d){var e=encodeURIComponent(String(d));c=Array.isArray(c)?c:[c];Mb(c,function(f){f==""?b.push(e):b.push(e+"="+encodeURIComponent(String(f)))})});
return b.join("&")}
function jm(a){a.charAt(0)==="?"&&(a=a.substring(1));return fm(a,"&")}
function km(a){return a.indexOf("?")!==-1?(a=(a||"").split("#")[0],a=a.split("?",2),jm(a.length>1?a[1]:a[0])):{}}
function lm(a,b){return mm(a,b||{},!0)}
function mm(a,b,c){var d=a.split("#",2);a=d[0];d=d.length>1?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=jm(e[1]||"");for(var f in b)!c&&e!==null&&f in e||(e[f]=b[f]);return ic(a,e)+d}
function nm(a){if(!b)var b=window.location.href;var c=bc(1,a),d=cc(a);c&&d?(a=a.match($b),b=b.match($b),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?cc(b)===d&&(Number(bc(4,b))||null)===(Number(bc(4,a))||null):!0;return a}
function gm(a){return a&&a.match(dm)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function om(a){var b=pm;a=a===void 0?F("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Bj;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ha){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=g===void 0?tj:g;try{var h=g.history.length}catch(Ha){h=0}e.u_his=h;var k;e.u_h=(k=tj.screen)==null?void 0:k.height;var l;e.u_w=(l=tj.screen)==null?void 0:l.width;var m;e.u_ah=(m=tj.screen)==null?void 0:m.availHeight;var n;e.u_aw=
(n=tj.screen)==null?void 0:n.availWidth;var p;e.u_cd=(p=tj.screen)==null?void 0:p.colorDepth}catch(Ha){}var t;h=b.h;try{var v=h.screenX;var x=h.screenY}catch(Ha){}try{var A=h.outerWidth;var H=h.outerHeight}catch(Ha){}try{var K=h.innerWidth;var aa=h.innerHeight}catch(Ha){}try{var da=h.screenLeft;var Pa=h.screenTop}catch(Ha){}try{K=h.innerWidth,aa=h.innerHeight}catch(Ha){}try{var Nb=h.screen.availWidth;var Ya=h.screen.availTop}catch(Ha){}v=[da,Pa,v,x,Nb,Ya,A,H,K,aa];try{var yb=(b.h.top||window).document,
Za=yb.compatMode=="CSS1Compat"?yb.documentElement:yb.body;var Qa=(new fg(Za.clientWidth,Za.clientHeight)).round()}catch(Ha){Qa=new fg(-12245933,-12245933)}yb=Qa;Qa={};var Ia=Ia===void 0?D:Ia;Za=new Hj;"SVGElement"in Ia&&"createElementNS"in Ia.document&&Za.set(0);x=yj();x["allow-top-navigation-by-user-activation"]&&Za.set(1);x["allow-popups-to-escape-sandbox"]&&Za.set(2);Ia.crypto&&Ia.crypto.subtle&&Za.set(3);"TextDecoder"in Ia&&"TextEncoder"in Ia&&Za.set(4);Ia=Ij(Za);Qa.bc=Ia;Qa.bih=yb.height;Qa.biw=
yb.width;Qa.brdim=v.join();b=b.i;b=b.prerendering?3:(t={visible:1,hidden:2,prerender:3,preview:4,unloaded:5,"":0}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""])!=null?t:0;t=(Qa.vis=b,Qa.wgl=!!tj.WebGLRenderingContext,Qa);c=d.call(c,e,t);c.ca_type="image";a&&(c.bid=a);return c}
var pm=new function(){var a=window.document;this.h=window;this.i=a};
E("yt.ads_.signals_.getAdSignalsString",function(a){return im(om(a))});$a();navigator.userAgent.indexOf(" (CrKey ");var qm="XMLHttpRequest"in D?function(){return new XMLHttpRequest}:null;
function rm(){if(!qm)return null;var a=qm();return"open"in a?a:null}
function sm(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function tm(a,b){typeof a==="function"&&(a=am(a));return window.setTimeout(a,b)}
;var um="client_dev_domain client_dev_expflag client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(z(um),["client_dev_set_cookie"]);function T(a){a=wm(a);return typeof a==="string"&&a==="false"?!1:!!a}
function xm(a,b){a=wm(a);return a===void 0&&b!==void 0?b:Number(a||0)}
function wm(a){return S("EXPERIMENT_FLAGS",{})[a]}
function ym(){for(var a=[],b=S("EXPERIMENTS_FORCED_FLAGS",{}),c=y(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=S("EXPERIMENT_FLAGS",{});d=y(Object.keys(c));for(var e=d.next();!e.done;e=d.next())e=e.value,e.startsWith("force_")&&b[e]===void 0&&a.push({key:e,value:String(c[e])});return a}
;var zm={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},Am="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(z(um)),Bm=!1;function Cm(a,b,c,d,e,f,g,h){function k(){(l&&"readyState"in l?l.readyState:0)===4&&b&&am(b)(l)}
c=c===void 0?"GET":c;d=d===void 0?"":d;h=h===void 0?!1:h;var l=rm();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;T("debug_forward_web_query_parameters")&&(a=Dm(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c=c==="POST"&&(window.FormData===void 0||!(d instanceof FormData));if(e=Em(a,e))for(var m in e)l.setRequestHeader(m,e[m]),"content-type"===m.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
if(h&&"setAttributionReporting"in XMLHttpRequest.prototype){a={eventSourceEligible:!0,triggerEligible:!1};try{l.setAttributionReporting(a)}catch(n){cm(n)}}l.send(d);return l}
function Em(a,b){b=b===void 0?{}:b;var c=nm(a),d=S("INNERTUBE_CLIENT_NAME"),e=T("web_ajax_ignore_global_headers_if_set"),f;for(f in zm){var g=S(zm[f]),h=f==="X-Goog-AuthUser"||f==="X-Goog-PageId";f!=="X-Goog-Visitor-Id"||g||(g=S("VISITOR_DATA"));var k;if(!(k=!g)){if(!(k=c||(cc(a)?!1:!0))){k=a;var l;if(l=T("add_auth_headers_to_remarketing_google_dot_com_ping")&&f==="Authorization"&&(d==="TVHTML5"||d==="TVHTML5_UNPLUGGED"||d==="TVHTML5_SIMPLY"))l=cc(k),l=l!==null?l.split(".").reverse():null,l=l===null?
!1:l[1]==="google"?!0:l[2]==="google"?l[0]==="au"&&l[1]==="com"?!0:l[0]==="uk"&&l[1]==="co"?!0:!1:!1;l&&(k=ac(bc(5,k))||"",k=k.split("/"),k="/"+(k.length>1?k[1]:""),l=k==="/pagead");k=l?!0:!1}k=!k}k||e&&b[f]!==void 0||d==="TVHTML5_UNPLUGGED"&&h||(b[f]=g)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!cc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!cc(a)){try{var m=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(n){}m&&
(b["X-YouTube-Time-Zone"]=m)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&cc(a)||(b["X-YouTube-Ad-Signals"]=im(om()));return b}
function Fm(a,b){b.method="POST";b.postParams||(b.postParams={});return Gm(a,b)}
function Gm(a,b){var c=b.format||"JSON";a=Hm(a,b);var d=Im(a,b),e=!1,f=Jm(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=sm(k),m=null,n=400<=k.status&&k.status<500,p=500<=k.status&&k.status<600;if(l||n||p)m=Km(a,c,k,b.convertToSafeHtml);l&&(l=Lm(c,k,m));m=m||{};n=b.context||D;l?b.onSuccess&&b.onSuccess.call(n,k,m):b.onError&&b.onError.call(n,k,m);b.onFinish&&b.onFinish.call(n,k,m)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&d>0){var g=b.onTimeout;var h=tm(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||D,f))},d)}return f}
function Hm(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=S("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=lm(a,b);return a}
function Im(a,b){var c=S("XSRF_FIELD_NAME"),d=S("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=S("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||cc(a)&&!b.withCredentials&&cc(a)!==document.location.hostname||b.method!=="POST"||h&&h!=="application/x-www-form-urlencoded"||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(T("ajax_parse_query_data_only_when_filled")&&f&&Object.keys(f).length>0||f)&&typeof e==="string"&&(e=jm(e),qg(e,f),e=b.postBodyFormat&&b.postBodyFormat===
"JSON"?JSON.stringify(e):hc(e));f=e||f&&!jg(f);!Bm&&f&&b.method!=="POST"&&(Bm=!0,bm(Error("AJAX request with postData should use POST")));return e}
function Km(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,cm(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&a.indexOf("json")>=0&&(f.substring(0,5)===")]}'\n"&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Mm(a):null)e={},Mb(a.getElementsByTagName("*"),function(g){e[g.tagName]=Nm(g)})}d&&Om(e);
return e}
function Om(a){if(Oa(a))for(var b in a){var c;(c=b==="html_content")||(c=b.length-5,c=c>=0&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b];var e=gb();d=new zb(e?e.createHTML(d):d);a[c]=d}else Om(a[b])}}
function Lm(a,b,c){if(b&&b.status===204)return!0;switch(a){case "JSON":return!!c;case "XML":return Number(c&&c.return_code)===0;case "RAW":return!0;default:return!!c}}
function Mm(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&a.length>0?a[0]:null:null}
function Nm(a){var b="";Mb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Dm(a){var b=window.location.search,c=cc(a);T("debug_handle_relative_url_for_query_forward_killswitch")||!c&&nm(a)&&(c=document.location.hostname);var d=ac(bc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=jm(b),f={};Mb(Am,function(g){e[g]&&(f[g]=e[g])});
return mm(a,f||{},!1)}
var Jm=Cm;var Pm=[{Qc:function(a){return"Cannot read property '"+a.key+"'"},
xc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Qc:function(a){return"Cannot call '"+a.key+"'"},
xc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Qc:function(a){return a.key+" is not defined"},
xc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Rm={Ya:[],Ta:[{callback:Qm,weight:500}]};function Qm(a){if(a.name==="JavaException")return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Sm(){this.Ta=[];this.Ya=[]}
var Tm;function Um(){if(!Tm){var a=Tm=new Sm;a.Ya.length=0;a.Ta.length=0;Rm.Ya&&a.Ya.push.apply(a.Ya,Rm.Ya);Rm.Ta&&a.Ta.push.apply(a.Ta,Rm.Ta)}return Tm}
;var Vm=new O;function Wm(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Xm(b);if(e===Infinity)break;var f=e>>3;switch(e&7){case 0:e=Xm(b);if(f===2)return e;break;case 1:if(f===2)return;d+=8;break;case 2:e=Xm(b);if(f===2)return a.substr(d,e);d+=e;break;case 5:if(f===2)return;d+=4;break;default:return}}while(d<c)}
function Xm(a){var b=a(),c=b&127;if(b<128)return c;b=a();c|=(b&127)<<7;if(b<128)return c;b=a();c|=(b&127)<<14;if(b<128)return c;b=a();return b<128?c|(b&127)<<21:Infinity}
;function Ym(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Zm(d,a[d],b,c),e>500));d++);d=e}else if(typeof a==="object")for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f=typeof g!=="string"||f!=="clickTrackingParams"&&f!=="trackingParams"?0:(g=Wm(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?Zm(f+".ve",g,h,k):0;d+=f;d+=Zm(e,a[e],b,c);if(d>500)break}}else c[b]=$m(a),d+=c[b].length;else c[b]=$m(a),d+=c[b].length;return d}
function Zm(a,b,c,d){c+="."+a;a=$m(b);d[c]=a;return c.length+a.length}
function $m(a){try{return(typeof a==="string"?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function an(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function bn(){if(!D.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return D.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":D.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":D.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":D.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function cn(){this.Kd=!0}
function dn(){cn.instance||(cn.instance=new cn);return cn.instance}
function en(a,b){a={};var c=[];"USER_SESSION_ID"in Wl&&c.push({key:"u",value:S("USER_SESSION_ID")});if(c=Zf(c))a.Authorization=c,c=b=b==null?void 0:b.sessionIndex,c===void 0&&(c=Number(S("SESSION_INDEX",0)),c=isNaN(c)?0:c),T("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in Wl||(a["X-Origin"]=window.location.origin),b===void 0&&"DELEGATED_SESSION_ID"in Wl&&(a["X-Goog-PageId"]=S("DELEGATED_SESSION_ID"));return a}
;var fn={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function gn(a,b,c,d,e){Wf.set(""+a,b,{Vb:c,path:"/",domain:d===void 0?"youtube.com":d,secure:e===void 0?!1:e})}
function hn(a){return Wf.get(""+a,void 0)}
function jn(a,b,c){Wf.remove(""+a,b===void 0?"/":b,c===void 0?"youtube.com":c)}
function kn(){if(T("embeds_web_enable_cookie_detection_fix")){if(!D.navigator.cookieEnabled)return!1}else if(!Wf.isEnabled())return!1;if(Wf.h.cookie)return!0;T("embeds_web_enable_cookie_detection_fix")?Wf.set("TESTCOOKIESENABLED","1",{Vb:60,bf:"none",secure:!0}):Wf.set("TESTCOOKIESENABLED","1",{Vb:60});if(Wf.get("TESTCOOKIESENABLED")!=="1")return!1;Wf.remove("TESTCOOKIESENABLED");return!0}
;var ln=F("ytglobal.prefsUserPrefsPrefs_")||{};E("ytglobal.prefsUserPrefsPrefs_",ln);function mn(){this.h=S("ALT_PREF_COOKIE_NAME","PREF");this.i=S("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=hn(this.h);a&&this.parse(a)}
var nn;function on(){nn||(nn=new mn);return nn}
r=mn.prototype;r.get=function(a,b){pn(a);qn(a);a=ln[a]!==void 0?ln[a].toString():null;return a!=null?a:b?b:""};
r.set=function(a,b){pn(a);qn(a);if(b==null)throw Error("ExpectedNotNull");ln[a]=b.toString()};
function rn(a){return!!((sn("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
r.remove=function(a){pn(a);qn(a);delete ln[a]};
r.clear=function(){for(var a in ln)delete ln[a]};
function qn(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function pn(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function sn(a){a=ln[a]!==void 0?ln[a].toString():null;return a!=null&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
r.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(ln[d]=c.toString())}};var tn={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},un={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function vn(){var a=D.navigator;return a?a.connection:void 0}
function wn(){var a=vn();if(a){var b=tn[a.type||"unknown"]||"CONN_UNKNOWN";a=tn[a.effectiveType||"unknown"]||"CONN_UNKNOWN";b==="CONN_CELLULAR_UNKNOWN"&&a!=="CONN_UNKNOWN"&&(b=a);if(b!=="CONN_UNKNOWN")return b;if(a!=="CONN_UNKNOWN")return a}}
function xn(){var a=vn();if(a!=null&&a.effectiveType)return un.hasOwnProperty(a.effectiveType)?un[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function U(a){var b=C.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(z(b));Object.setPrototypeOf(this,this.constructor.prototype)}
w(U,Error);function yn(){try{return zn(),!0}catch(a){return!1}}
function zn(a){if(S("DATASYNC_ID")!==void 0)return S("DATASYNC_ID");throw new U("Datasync ID not set",a===void 0?"unknown":a);}
;function An(){}
function Bn(a,b){return Gj.Ra(a,0,b)}
An.prototype.pa=function(a,b){return this.Ra(a,1,b)};
An.prototype.Lb=function(a){var b=F("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var Cn=xm("web_emulated_idle_callback_delay",300),Dn=1E3/60-3,En=[8,5,4,3,2,1,0];
function Fn(a){a=a===void 0?{}:a;G.call(this);this.i=[];this.j={};this.Z=this.h=0;this.Y=this.u=!1;this.P=[];this.U=this.ha=!1;for(var b=y(En),c=b.next();!c.done;c=b.next())this.i[c.value]=[];this.o=0;this.Gc=a.timeout||1;this.G=Dn;this.D=0;this.xa=this.Oe.bind(this);this.Kb=this.uf.bind(this);this.Pa=this.Xd.bind(this);this.Qa=this.ye.bind(this);this.eb=this.Ve.bind(this);this.Fa=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!T("disable_scheduler_requestIdleCallback");(this.ma=a.useRaf!==
!1&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.xa)}
w(Fn,G);r=Fn.prototype;r.Lb=function(a){var b=$a();Gn(this,a);a=$a()-b;this.u||(this.G-=a)};
r.Ra=function(a,b,c){++this.Z;if(b===10)return this.Lb(a),this.Z;var d=this.Z;this.j[d]=a;this.u&&!c?this.P.push({id:d,priority:b}):(this.i[b].push(d),this.Y||this.u||(this.h!==0&&Hn(this)!==this.D&&this.stop(),this.start()));return d};
r.qa=function(a){delete this.j[a]};
function In(a){a.P.length=0;for(var b=5;b>=0;b--)a.i[b].length=0;a.i[8].length=0;a.j={};a.stop()}
r.isHidden=function(){return!!document.hidden||!1};
function Jn(a){return!a.isHidden()&&a.ma}
function Hn(a){if(a.i[8].length){if(a.U)return 4;if(Jn(a))return 3}for(var b=5;b>=a.o;b--)if(a.i[b].length>0)return b>0?Jn(a)?3:2:1;return 0}
r.Ha=function(a){var b=F("yt.logging.errors.log");b&&b(a)};
function Gn(a,b){try{b()}catch(c){a.Ha(c)}}
function Kn(a){for(var b=y(En),c=b.next();!c.done;c=b.next())if(a.i[c.value].length)return!0;return!1}
r.ye=function(a){var b=void 0;a&&(b=a.timeRemaining());this.ha=!0;Ln(this,b);this.ha=!1};
r.uf=function(){Ln(this)};
r.Xd=function(){Mn(this)};
r.Ve=function(a){this.U=!0;var b=Hn(this);b===4&&b!==this.D&&(this.stop(),this.start());Ln(this,void 0,a);this.U=!1};
r.Oe=function(){this.isHidden()||Mn(this);this.h&&(this.stop(),this.start())};
function Mn(a){a.stop();a.u=!0;for(var b=$a(),c=a.i[8];c.length;){var d=c.shift(),e=a.j[d];delete a.j[d];e&&Gn(a,e)}Nn(a);a.u=!1;Kn(a)&&a.start();b=$a()-b;a.G-=b}
function Nn(a){for(var b=0,c=a.P.length;b<c;b++){var d=a.P[b];a.i[d.priority].push(d.id)}a.P.length=0}
function Ln(a,b,c){a.U&&a.D===4&&a.h||a.stop();a.u=!0;b=$a()+(b||a.G);for(var d=a.i[5];d.length;){var e=d.shift(),f=a.j[e];delete a.j[e];if(f){e=a;try{f(c)}catch(l){e.Ha(l)}}}for(d=a.i[4];d.length;)c=d.shift(),f=a.j[c],delete a.j[c],f&&Gn(a,f);d=a.ha?0:1;d=a.o>d?a.o:d;if(!($a()>=b)){do{a:{c=a;f=d;for(e=3;e>=f;e--)for(var g=c.i[e];g.length;){var h=g.shift(),k=c.j[h];delete c.j[h];if(k){c=k;break a}}c=null}c&&Gn(a,c)}while(c&&$a()<b)}a.u=!1;Nn(a);a.G=Dn;Kn(a)&&a.start()}
r.start=function(){this.Y=!1;if(this.h===0)switch(this.D=Hn(this),this.D){case 1:var a=this.Qa;this.h=this.Fa?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,Cn);break;case 2:this.h=window.setTimeout(this.Kb,this.Gc);break;case 3:this.h=window.requestAnimationFrame(this.eb);break;case 4:this.h=window.setTimeout(this.Pa,0)}};
r.pause=function(){this.stop();this.Y=!0};
r.stop=function(){if(this.h){switch(this.D){case 1:var a=this.h;this.Fa?window.cancelIdleCallback(a):window.clearTimeout(a);break;case 2:case 4:window.clearTimeout(this.h);break;case 3:window.cancelAnimationFrame(this.h)}this.h=0}};
r.ba=function(){In(this);this.stop();this.ma&&document.removeEventListener("visibilitychange",this.xa);G.prototype.ba.call(this)};var On=F("yt.scheduler.instance.timerIdMap_")||{},Pn=xm("kevlar_tuner_scheduler_soft_state_timer_ms",800),Qn=0,Rn=0;function Sn(){var a=F("ytglobal.schedulerInstanceInstance_");if(!a||a.ea)a=new Fn(S("scheduler")||{}),E("ytglobal.schedulerInstanceInstance_",a);return a}
function Tn(){Un();var a=F("ytglobal.schedulerInstanceInstance_");a&&(sc(a),E("ytglobal.schedulerInstanceInstance_",null))}
function Un(){In(Sn());for(var a in On)On.hasOwnProperty(a)&&delete On[Number(a)]}
function Vn(a,b,c){if(!c)return c=c===void 0,-Sn().Ra(a,b,c);var d=window.setTimeout(function(){var e=Sn().Ra(a,b);On[d]=e},c);
return d}
function Wn(a){Sn().Lb(a)}
function Xn(a){var b=Sn();if(a<0)b.qa(-a);else{var c=On[a];c?(b.qa(c),delete On[a]):window.clearTimeout(a)}}
function Yn(){Zn()}
function Zn(){window.clearTimeout(Qn);Sn().start()}
function $n(){Sn().pause();window.clearTimeout(Qn);Qn=window.setTimeout(Yn,Pn)}
function ao(){window.clearTimeout(Rn);Rn=window.setTimeout(function(){bo(0)},Pn)}
function bo(a){ao();var b=Sn();b.o=a;b.start()}
function co(a){ao();var b=Sn();b.o>a&&(b.o=a,b.start())}
function eo(){window.clearTimeout(Rn);var a=Sn();a.o=0;a.start()}
;function fo(){An.apply(this,arguments)}
w(fo,An);function go(){fo.instance||(fo.instance=new fo);return fo.instance}
fo.prototype.Ra=function(a,b,c){c!==void 0&&Number.isNaN(Number(c))&&(c=void 0);var d=F("yt.scheduler.instance.addJob");return d?d(a,b,c):c===void 0?(a(),NaN):tm(a,c||0)};
fo.prototype.qa=function(a){if(a===void 0||!Number.isNaN(Number(a))){var b=F("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
fo.prototype.start=function(){var a=F("yt.scheduler.instance.start");a&&a()};
fo.prototype.pause=function(){var a=F("yt.scheduler.instance.pause");a&&a()};
var Gj=go();
T("web_scheduler_auto_init")&&!F("yt.scheduler.initialized")&&(E("yt.scheduler.instance.dispose",Tn),E("yt.scheduler.instance.addJob",Vn),E("yt.scheduler.instance.addImmediateJob",Wn),E("yt.scheduler.instance.cancelJob",Xn),E("yt.scheduler.instance.cancelAllJobs",Un),E("yt.scheduler.instance.start",Zn),E("yt.scheduler.instance.pause",$n),E("yt.scheduler.instance.setPriorityThreshold",bo),E("yt.scheduler.instance.enablePriorityThreshold",co),E("yt.scheduler.instance.clearPriorityThreshold",eo),E("yt.scheduler.initialized",
!0));function ho(a){var b=new gk;this.h=(a=b.isAvailable()?a?new hk(b,a):b:null)?new bk(a):null;this.i=document.domain||window.location.hostname}
ho.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+c*1E3);return}catch(f){}var e="";if(d)try{e=escape((new Ci).serialize(b))}catch(f){return}else e=escape(b);gn(a,e,c,this.i)};
ho.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=hn(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
ho.prototype.remove=function(a){this.h&&this.h.remove(a);jn(a,"/",this.i)};var io=function(){var a;return function(){a||(a=new ho("ytidb"));return a}}();
function jo(){var a;return(a=io())==null?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var ko=[],lo,mo=!1;function no(){var a={};for(lo=new oo(a.handleError===void 0?po:a.handleError,a.logEvent===void 0?qo:a.logEvent);ko.length>0;)switch(a=ko.shift(),a.type){case "ERROR":lo.Ha(a.payload);break;case "EVENT":lo.logEvent(a.eventType,a.payload)}}
function ro(a){mo||(lo?lo.Ha(a):(ko.push({type:"ERROR",payload:a}),ko.length>10&&ko.shift()))}
function so(a,b){mo||(lo?lo.logEvent(a,b):(ko.push({type:"EVENT",eventType:a,payload:b}),ko.length>10&&ko.shift()))}
;function to(a){if(a.indexOf(":")>=0)throw Error("Database name cannot contain ':'");}
function uo(a){return a.substr(0,a.indexOf(":"))||a}
;var vo=kd||ld;function wo(a){var b=Uc();return b?b.toLowerCase().indexOf(a)>=0:!1}
;var xo={},yo=(xo.AUTH_INVALID="No user identifier specified.",xo.EXPLICIT_ABORT="Transaction was explicitly aborted.",xo.IDB_NOT_SUPPORTED="IndexedDB is not supported.",xo.MISSING_INDEX="Index not created.",xo.MISSING_OBJECT_STORES="Object stores not created.",xo.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",xo.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",xo.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
xo.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",xo.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",xo.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",xo.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",xo),zo={},Ao=(zo.AUTH_INVALID="ERROR",zo.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",zo.EXPLICIT_ABORT="IGNORED",zo.IDB_NOT_SUPPORTED="ERROR",zo.MISSING_INDEX=
"WARNING",zo.MISSING_OBJECT_STORES="ERROR",zo.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",zo.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",zo.QUOTA_EXCEEDED="WARNING",zo.QUOTA_MAYBE_EXCEEDED="WARNING",zo.UNKNOWN_ABORT="WARNING",zo.INCOMPATIBLE_DB_VERSION="WARNING",zo),Bo={},Co=(Bo.AUTH_INVALID=!1,Bo.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Bo.EXPLICIT_ABORT=!1,Bo.IDB_NOT_SUPPORTED=!1,Bo.MISSING_INDEX=!1,Bo.MISSING_OBJECT_STORES=!1,Bo.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Bo.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Bo.QUOTA_EXCEEDED=!1,Bo.QUOTA_MAYBE_EXCEEDED=!0,Bo.UNKNOWN_ABORT=!0,Bo.INCOMPATIBLE_DB_VERSION=!1,Bo);function Do(a,b,c,d,e){b=b===void 0?{}:b;c=c===void 0?yo[a]:c;d=d===void 0?Ao[a]:d;e=e===void 0?Co[a]:e;U.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:self.document===void 0,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Do.prototype)}
w(Do,U);function Eo(a,b){Do.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},yo.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Eo.prototype)}
w(Eo,Do);function Fo(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Fo.prototype)}
w(Fo,Error);var Go=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Ho(a,b,c,d){b=uo(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Do)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if(e.name==="QuotaExceededError")return new Do("QUOTA_EXCEEDED",a);if(md&&e.name==="UnknownError")return new Do("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Fo)return new Do("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if(e.name==="InvalidStateError"&&Go.some(function(f){return e.message.includes(f)}))return new Do("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if(e.name==="AbortError")return new Do("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",Bd:e.name})];e.level="WARNING";return e}
function Io(a,b,c){var d=jo();return new Do("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:d==null?void 0:d.hasSucceededOnce}})}
;function Jo(a){if(!a)throw Error();throw a;}
function Ko(a){return a}
function Lo(a){this.h=a}
function Mo(a){function b(e){if(d.state.status==="PENDING"){d.state={status:"REJECTED",reason:e};e=y(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if(d.state.status==="PENDING"){d.state={status:"FULFILLED",value:e};e=y(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Mo.all=function(a){return new Mo(new Lo(function(b,c){var d=[],e=a.length;e===0&&b(d);for(var f={Ab:0};f.Ab<a.length;f={Ab:f.Ab},++f.Ab)Mo.resolve(a[f.Ab]).then(function(g){return function(h){d[g.Ab]=h;e--;e===0&&b(d)}}(f)).catch(function(g){c(g)})}))};
Mo.resolve=function(a){return new Mo(new Lo(function(b,c){a instanceof Mo?a.then(b,c):b(a)}))};
Mo.reject=function(a){return new Mo(new Lo(function(b,c){c(a)}))};
Mo.prototype.then=function(a,b){var c=this,d=a!=null?a:Ko,e=b!=null?b:Jo;return new Mo(new Lo(function(f,g){c.state.status==="PENDING"?(c.h.push(function(){No(c,c,d,f,g)}),c.i.push(function(){Oo(c,c,e,f,g)})):c.state.status==="FULFILLED"?No(c,c,d,f,g):c.state.status==="REJECTED"&&Oo(c,c,e,f,g)}))};
Mo.prototype.catch=function(a){return this.then(void 0,a)};
function No(a,b,c,d,e){try{if(a.state.status!=="FULFILLED")throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Mo?Po(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Oo(a,b,c,d,e){try{if(a.state.status!=="REJECTED")throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Mo?Po(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Po(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Mo?Po(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Qo(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Ro(a){return new Promise(function(b,c){Qo(a,b,c)})}
function So(a){return new Mo(new Lo(function(b,c){Qo(a,b,c)}))}
;function To(a,b){return new Mo(new Lo(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var Uo=window,V=Uo.ytcsi&&Uo.ytcsi.now?Uo.ytcsi.now:Uo.performance&&Uo.performance.timing&&Uo.performance.now&&Uo.performance.timing.navigationStart?function(){return Uo.performance.timing.navigationStart+Uo.performance.now()}:function(){return(new Date).getTime()};function Vo(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(V());this.i=!1}
r=Vo.prototype;r.add=function(a,b,c){return Wo(this,[a],{mode:"readwrite",ka:!0},function(d){return d.objectStore(a).add(b,c)})};
r.clear=function(a){return Wo(this,[a],{mode:"readwrite",ka:!0},function(b){return b.objectStore(a).clear()})};
r.close=function(){this.h.close();var a;((a=this.options)==null?0:a.closed)&&this.options.closed()};
r.count=function(a,b){return Wo(this,[a],{mode:"readonly",ka:!0},function(c){return c.objectStore(a).count(b)})};
function Xo(a,b,c){a=a.h.createObjectStore(b,c);return new Yo(a)}
r.delete=function(a,b){return Wo(this,[a],{mode:"readwrite",ka:!0},function(c){return c.objectStore(a).delete(b)})};
r.get=function(a,b){return Wo(this,[a],{mode:"readonly",ka:!0},function(c){return c.objectStore(a).get(b)})};
function Zo(a,b,c){return Wo(a,[b],{mode:"readwrite",ka:!0},function(d){d=d.objectStore(b);return So(d.h.put(c,void 0))})}
r.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Wo(a,b,c,d){var e,f,g,h,k,l,m,n,p,t,v,x;return B(function(A){switch(A.h){case 1:var H={mode:"readonly",ka:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};typeof c==="string"?H.mode=c:Object.assign(H,c);e=H;a.transactionCount++;f=e.ka?3:1;g=0;case 2:if(h){A.A(4);break}g++;k=Math.round(V());xa(A,5);l=a.h.transaction(b,e.mode);H=A.yield;var K=new $o(l);K=ap(K,d);return H.call(A,K,7);case 7:return m=A.i,n=Math.round(V()),bp(a,k,n,g,void 0,b.join(),e),A.return(m);case 5:p=za(A);t=Math.round(V());v=Ho(p,
a.h.name,b.join(),a.h.version);if((x=v instanceof Do&&!v.h)||g>=f)bp(a,k,t,g,v,b.join(),e),h=v;A.A(2);break;case 4:return A.return(Promise.reject(h))}})}
function bp(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Do&&(e.type==="QUOTA_EXCEEDED"||e.type==="QUOTA_MAYBE_EXCEEDED")&&so("QUOTA_EXCEEDED",{dbName:uo(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Do&&e.type==="UNKNOWN_ABORT"&&(c-=a.j,c<0&&c>=2147483648&&(c=0),so("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),cp(a,!1,d,f,b,g.tag),ro(e)):cp(a,!0,d,f,b,g.tag)}
function cp(a,b,c,d,e,f){so("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:f===void 0?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
r.getName=function(){return this.h.name};
function Yo(a){this.h=a}
r=Yo.prototype;r.add=function(a,b){return So(this.h.add(a,b))};
r.autoIncrement=function(){return this.h.autoIncrement};
r.clear=function(){return So(this.h.clear()).then(function(){})};
function dp(a,b,c){a.h.createIndex(b,c,{unique:!1})}
r.count=function(a){return So(this.h.count(a))};
function ep(a,b){return fp(a,{query:b},function(c){return c.delete().then(function(){return gp(c)})}).then(function(){})}
r.delete=function(a){return a instanceof IDBKeyRange?ep(this,a):So(this.h.delete(a))};
r.get=function(a){return So(this.h.get(a))};
r.index=function(a){try{return new hp(this.h.index(a))}catch(b){if(b instanceof Error&&b.name==="NotFoundError")throw new Fo(a,this.h.name);throw b;}};
r.getName=function(){return this.h.name};
r.keyPath=function(){return this.h.keyPath};
function fp(a,b,c){a=a.h.openCursor(b.query,b.direction);return ip(a).then(function(d){return To(d,c)})}
function $o(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=Do;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(k===null)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function ap(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return y(d).next().value})}
$o.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new Do("EXPLICIT_ABORT");};
$o.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new Yo(a),this.i.set(a,b));return b};
function hp(a){this.h=a}
r=hp.prototype;r.count=function(a){return So(this.h.count(a))};
r.delete=function(a){return jp(this,{query:a},function(b){return b.delete().then(function(){return gp(b)})})};
r.get=function(a){return So(this.h.get(a))};
r.keyPath=function(){return this.h.keyPath};
r.unique=function(){return this.h.unique};
function jp(a,b,c){a=a.h.openCursor(b.query===void 0?null:b.query,b.direction===void 0?"next":b.direction);return ip(a).then(function(d){return To(d,c)})}
function kp(a,b){this.request=a;this.cursor=b}
function ip(a){return So(a).then(function(b){return b?new kp(a,b):null})}
function gp(a){a.cursor.continue(void 0);return ip(a.request)}
kp.prototype.delete=function(){return So(this.cursor.delete()).then(function(){})};
kp.prototype.getValue=function(){return this.cursor.value};
kp.prototype.update=function(a){return So(this.cursor.update(a))};function lp(a,b,c){return new Promise(function(d,e){function f(){p||(p=new Vo(g.result,{closed:n}));return p}
var g=b!==void 0?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.ae,k=c.blocking,l=c.sf,m=c.upgrade,n=c.closed,p;g.addEventListener("upgradeneeded",function(t){try{if(t.newVersion===null)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(g.transaction===null)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&t.dataLoss!=="none"&&so("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:uo(a)});var v=f(),x=new $o(g.transaction);
m&&m(v,function(A){return t.oldVersion<A&&t.newVersion>=A},x);
x.done.catch(function(A){e(A)})}catch(A){e(A)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){so("IDB_UNEXPECTEDLY_CLOSED",{dbName:uo(a),dbVersion:t.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function mp(a,b,c){c=c===void 0?{}:c;return lp(a,b,c)}
function np(a,b){b=b===void 0?{}:b;var c,d,e,f;return B(function(g){if(g.h==1)return xa(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.ae)&&c.addEventListener("blocked",function(){e()}),g.yield(Ro(c),4);
if(g.h!=2)return ya(g,0);f=za(g);throw Ho(f,a,"",-1);})}
;function op(a,b){this.name=a;this.options=b;this.j=!0;this.u=this.o=0}
op.prototype.i=function(a,b,c){c=c===void 0?{}:c;return mp(a,b,c)};
op.prototype.delete=function(a){a=a===void 0?{}:a;return np(this.name,a)};
function pp(a,b){return new Do("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function qp(a,b){if(!b)throw Io("openWithToken",uo(a.name));return a.open()}
op.prototype.open=function(){function a(){var f,g,h,k,l,m,n,p,t,v;return B(function(x){switch(x.h){case 1:return g=(f=Error().stack)!=null?f:"",xa(x,2),x.yield(c.i(c.name,c.options.version,e),4);case 4:for(var A=h=x.i,H=c.options,K=[],aa=y(Object.keys(H.Gb)),da=aa.next();!da.done;da=aa.next()){da=da.value;var Pa=H.Gb[da],Nb=Pa.We===void 0?Number.MAX_VALUE:Pa.We;!(A.h.version>=Pa.Nb)||A.h.version>=Nb||A.h.objectStoreNames.contains(da)||K.push(da)}k=K;if(k.length===0){x.A(5);break}l=Object.keys(c.options.Gb);
m=h.objectStoreNames();if(c.u<xm("ytidb_reopen_db_retries",0))return c.u++,h.close(),ro(new Do("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());if(!(c.o<xm("ytidb_remake_db_retries",1))){x.A(6);break}c.o++;return x.yield(c.delete(),7);case 7:return ro(new Do("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());case 6:throw new Eo(m,l);case 5:return x.return(h);case 2:n=za(x);
if(n instanceof DOMException?n.name!=="VersionError":"DOMError"in self&&n instanceof DOMError?n.name!=="VersionError":!(n instanceof Object&&"message"in n)||n.message!=="An attempt was made to open a database using a lower version than the existing version."){x.A(8);break}return x.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:p=x.i;t=p.h.version;if(c.options.version!==void 0&&t>c.options.version+1)throw p.close(),c.j=!1,pp(c,t);return x.return(p);case 8:throw b(),n instanceof
Error&&!T("ytidb_async_stack_killswitch")&&(n.stack=n.stack+"\n"+g.substring(g.indexOf("\n")+1)),Ho(n,c.name,"",(v=c.options.version)!=null?v:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw pp(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,sf:b,upgrade:this.options.upgrade};return this.h=d=a()};var rp=new op("YtIdbMeta",{Gb:{databases:{Nb:1}},upgrade:function(a,b){b(1)&&Xo(a,"databases",{keyPath:"actualName"})}});
function sp(a,b){var c;return B(function(d){if(d.h==1)return d.yield(qp(rp,b),2);c=d.i;return d.return(Wo(c,["databases"],{ka:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return So(f.h.put(a,void 0)).then(function(){})})}))})}
function tp(a,b){var c;return B(function(d){if(d.h==1)return a?d.yield(qp(rp,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function up(a,b){var c,d;return B(function(e){return e.h==1?(c=[],e.yield(qp(rp,b),2)):e.h!=3?(d=e.i,e.yield(Wo(d,["databases"],{ka:!0,mode:"readonly"},function(f){c.length=0;return fp(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return gp(g)})}),3)):e.return(c)})}
function vp(a){return up(function(b){return b.publicName==="LogsDatabaseV2"&&b.userIdentifier!==void 0},a)}
function wp(a,b,c){return up(function(d){return c?d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)},b)}
function xp(a){var b,c;return B(function(d){if(d.h==1)return b=zn("YtIdbMeta hasAnyMeta other"),d.yield(up(function(e){return e.userIdentifier!==void 0&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(c.length>0)})}
;var yp,zp=new function(){}(new function(){});
function Ap(){var a,b,c,d;return B(function(e){switch(e.h){case 1:a=jo();if((b=a)==null?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=vo)f=/WebKit\/([0-9]+)/.exec(Uc()),f=!!(f&&parseInt(f[1],10)>=600);f&&(f=/WebKit\/([0-9]+)/.exec(Uc()),f=!(f&&parseInt(f[1],10)>=602));if(f||gd)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
xa(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(sp(d,zp),4);case 4:return e.yield(tp("yt-idb-test-do-not-use",zp),5);case 5:return e.return(!0);case 2:return za(e),e.return(!1)}})}
function Bp(){if(yp!==void 0)return yp;mo=!0;return yp=Ap().then(function(a){mo=!1;var b;if((b=io())!=null&&b.h){var c;b={hasSucceededOnce:((c=jo())==null?void 0:c.hasSucceededOnce)||a};var d;(d=io())==null||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Cp(){return F("ytglobal.idbToken_")||void 0}
function Dp(){var a=Cp();return a?Promise.resolve(a):Bp().then(function(b){(b=b?zp:void 0)&&E("ytglobal.idbToken_",b);return b})}
;var Ep=0;function Fp(a,b){Ep||(Ep=Gj.pa(function(){var c,d,e,f,g;return B(function(h){switch(h.h){case 1:return h.yield(Dp(),2);case 2:c=h.i;if(!c)return h.return();d=!0;xa(h,3);return h.yield(wp(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.A(6);break}f=e[0];return h.yield(np(f.actualName),7);case 7:return h.yield(tp(f.actualName,c),6);case 6:ya(h,4);break;case 3:g=za(h),ro(g),d=!1;case 4:Gj.qa(Ep),Ep=0,d&&Fp(a,b),h.h=0}})}))}
function Gp(){var a;return B(function(b){return b.h==1?b.yield(Dp(),2):(a=b.i)?b.return(xp(a)):b.return(!1)})}
new ij;function Hp(a){if(!yn())throw a=new Do("AUTH_INVALID",{dbName:a}),ro(a),a;var b=zn();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Ip(a,b,c,d){var e,f,g,h,k,l;return B(function(m){switch(m.h){case 1:return f=(e=Error().stack)!=null?e:"",m.yield(Dp(),2);case 2:g=m.i;if(!g)throw h=Io("openDbImpl",a,b),T("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),ro(h),h;to(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Hp(a);xa(m,3);return m.yield(sp(k,g),5);case 5:return m.yield(mp(k.actualName,b,d),6);case 6:return m.return(m.i);case 3:return l=za(m),xa(m,7),m.yield(tp(k.actualName,
g),9);case 9:ya(m,8);break;case 7:za(m);case 8:throw l;}})}
function Jp(a,b,c){c=c===void 0?{}:c;return Ip(a,b,!1,c)}
function Kp(a,b,c){c=c===void 0?{}:c;return Ip(a,b,!0,c)}
function Lp(a,b){b=b===void 0?{}:b;var c,d;return B(function(e){if(e.h==1)return e.yield(Dp(),2);if(e.h!=3){c=e.i;if(!c)return e.return();to(a);d=Hp(a);return e.yield(np(d.actualName,b),3)}return e.yield(tp(d.actualName,c),0)})}
function Mp(a,b,c){a=a.map(function(d){return B(function(e){return e.h==1?e.yield(np(d.actualName,b),2):e.yield(tp(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Np(){var a=a===void 0?{}:a;var b,c;return B(function(d){if(d.h==1)return d.yield(Dp(),2);if(d.h!=3){b=d.i;if(!b)return d.return();to("LogsDatabaseV2");return d.yield(vp(b),3)}c=d.i;return d.yield(Mp(c,a,b),0)})}
function Op(a,b){b=b===void 0?{}:b;var c;return B(function(d){if(d.h==1)return d.yield(Dp(),2);if(d.h!=3){c=d.i;if(!c)return d.return();to(a);return d.yield(np(a,b),3)}return d.yield(tp(a,c),0)})}
;function Pp(a,b){op.call(this,a,b);this.options=b;to(a)}
w(Pp,op);function Qp(a,b){var c;return function(){c||(c=new Pp(a,b));return c}}
Pp.prototype.i=function(a,b,c){c=c===void 0?{}:c;return(this.options.shared?Kp:Jp)(a,b,Object.assign({},c))};
Pp.prototype.delete=function(a){a=a===void 0?{}:a;return(this.options.shared?Op:Lp)(this.name,a)};
function Rp(a,b){return Qp(a,b)}
;var Sp={},Tp=Rp("ytGcfConfig",{Gb:(Sp.coldConfigStore={Nb:1},Sp.hotConfigStore={Nb:1},Sp),shared:!1,upgrade:function(a,b){b(1)&&(dp(Xo(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),dp(Xo(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function Up(a){return qp(Tp(),a)}
function Vp(a,b,c){var d,e,f;return B(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:V()},g.yield(Up(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(Zo(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function Wp(a,b,c,d){var e,f,g;return B(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:V()},h.yield(Up(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(Zo(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function Xp(a){var b,c;return B(function(d){return d.h==1?d.yield(Up(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Wo(b,["coldConfigStore"],{mode:"readwrite",ka:!0},function(e){return jp(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function Yp(a){var b,c;return B(function(d){return d.h==1?d.yield(Up(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Wo(b,["hotConfigStore"],{mode:"readwrite",ka:!0},function(e){return jp(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function Zp(){G.call(this);this.i=[];this.h=[];var a=F("yt.gcf.config.hotUpdateCallbacks");a?(this.i=[].concat(z(a)),this.h=a):(this.h=[],E("yt.gcf.config.hotUpdateCallbacks",this.h))}
w(Zp,G);Zp.prototype.ba=function(){for(var a=y(this.i),b=a.next();!b.done;b=a.next()){var c=this.h;b=c.indexOf(b.value);b>=0&&c.splice(b,1)}this.i.length=0;G.prototype.ba.call(this)};function $p(){this.h=0;this.i=new Zp}
function aq(){var a;return(a=F("yt.gcf.config.hotConfigGroup"))!=null?a:S("RAW_HOT_CONFIG_GROUP")}
function bq(a,b,c){var d,e,f;return B(function(g){switch(g.h){case 1:if(!T("start_client_gcf")){g.A(0);break}c&&(a.j=c,E("yt.gcf.config.hotConfigGroup",a.j||null));a.o(b);d=Cp();if(!d){g.A(3);break}if(c){g.A(4);break}return g.yield(Yp(d),5);case 5:e=g.i,c=(f=e)==null?void 0:f.config;case 4:return g.yield(Vp(c,b,d),3);case 3:if(c)for(var h=c,k=y(a.i.h),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function cq(a,b,c){var d,e,f,g;return B(function(h){if(h.h==1){if(!T("start_client_gcf"))return h.A(0);a.coldHashData=b;E("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=Cp())?c?h.A(4):h.yield(Xp(d),5):h.A(0)}h.h!=4&&(e=h.i,c=(f=e)==null?void 0:f.config);if(!c)return h.A(0);g=c.configData;return h.yield(Wp(c,b,g,d),0)})}
function dq(){if(!$p.instance){var a=new $p;$p.instance=a}a=$p.instance;var b=V()-a.h;if(!(a.h!==0&&b<xm("send_config_hash_timer"))){b=F("yt.gcf.config.coldConfigData");var c=F("yt.gcf.config.hotHashData"),d=F("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=V());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
$p.prototype.o=function(a){this.hotHashData=a;E("yt.gcf.config.hotHashData",this.hotHashData||null)};function eq(){return"INNERTUBE_API_KEY"in Wl&&"INNERTUBE_API_VERSION"in Wl}
function fq(){return{innertubeApiKey:S("INNERTUBE_API_KEY"),innertubeApiVersion:S("INNERTUBE_API_VERSION"),ze:S("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),vd:S("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Eh:S("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:S("INNERTUBE_CONTEXT_CLIENT_VERSION"),Be:S("INNERTUBE_CONTEXT_HL"),Ae:S("INNERTUBE_CONTEXT_GL"),Ce:S("INNERTUBE_HOST_OVERRIDE")||"",De:!!S("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Fh:!!S("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:S("SERIALIZED_CLIENT_CONFIG_DATA")}}
function gq(a){var b={client:{hl:a.Be,gl:a.Ae,clientName:a.vd,clientVersion:a.innertubeContextClientVersion,configInfo:a.ze}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=D.devicePixelRatio;c&&c!=1&&(b.client.screenDensityFloat=String(c));c=S("EXPERIMENTS_TOKEN","");c!==""&&(b.client.experimentsToken=c);c=ym();c.length>0&&(b.request={internalExperimentFlags:c});c=a.vd;if((c==="WEB"||c==="MWEB"||c===1||c===2)&&b){var d;b.client.mainAppWebInfo=(d=b.client.mainAppWebInfo)!=
null?d:{};b.client.mainAppWebInfo.webDisplayMode=bn()}(d=F("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(T("web_log_memory_total_kbytes")&&((e=D.navigator)==null?0:e.deviceMemory)){var f;e=(f=D.navigator)==null?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+e*1E6)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=wn())&&b&&(b.client.connectionType=a);T("web_log_effective_connection_type")&&
(a=xn())&&b&&(b.client.effectiveConnectionType=a);T("start_client_gcf")&&(e=dq())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,b&&(b.client.configInfo=b.client.configInfo||{},a&&(b.client.configInfo.coldConfigData=a),f&&(b.client.configInfo.coldHashData=f),e&&(b.client.configInfo.hotHashData=e)));S("DELEGATED_SESSION_ID")&&!T("pageid_as_header_web")&&(b.user={onBehalfOfUser:S("DELEGATED_SESSION_ID")});!T("fill_delegate_context_in_gel_killswitch")&&(a=S("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=S("INNERTUBE_CONTEXT");var g;if(T("enable_persistent_device_token")&&(a==null?0:(g=a.client)==null?0:g.rolloutToken)){var h;b.client.rolloutToken=a==null?void 0:(h=a.client)==null?void 0:h.rolloutToken}g=Object;h=g.assign;a=b.client;f={};e=y(Object.entries(jm(S("DEVICE",""))));for(d=e.next();!d.done;d=e.next())c=y(d.value),d=c.next().value,c=c.next().value,d==="cbrand"?f.deviceMake=c:d==="cmodel"?f.deviceModel=c:d==="cbr"?f.browserName=
c:d==="cbrver"?f.browserVersion=c:d==="cos"?f.osName=c:d==="cosver"?f.osVersion=c:d==="cplatform"&&(f.platform=c);b.client=h.call(g,a,f);return b}
function hq(a,b,c){c=c===void 0?{}:c;var d={};S("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":S("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||S("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||S("AUTHORIZATION");b||(a?b="Bearer "+F("gapi.auth.getToken")().th:(a=en(dn()),T("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;var iq=typeof TextEncoder!=="undefined"?new TextEncoder:null,jq=iq?function(a){return iq.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
e<128?b[c++]=e:(e<2048?b[c++]=e>>6|192:((e&64512)==55296&&d+1<a.length&&(a.charCodeAt(d+1)&64512)==56320?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};var kq={next:"wn_s",browse:"br_s",search:"sr_s",reel:"r_wrs",player:"ps_s"},lq={next:"wn_r",browse:"br_r",search:"sr_r",reel:"r_wrr",player:"ps_r"};function mq(a,b){this.version=a;this.args=b}
mq.prototype.serialize=function(){return{version:this.version,args:this.args}};function nq(a,b){this.topic=a;this.h=b}
nq.prototype.toString=function(){return this.topic};var oq=F("ytPubsub2Pubsub2Instance")||new O;O.prototype.subscribe=O.prototype.subscribe;O.prototype.unsubscribeByKey=O.prototype.dc;O.prototype.publish=O.prototype.sb;O.prototype.clear=O.prototype.clear;E("ytPubsub2Pubsub2Instance",oq);var pq=F("ytPubsub2Pubsub2SubscribedKeys")||{};E("ytPubsub2Pubsub2SubscribedKeys",pq);var qq=F("ytPubsub2Pubsub2TopicToKeys")||{};E("ytPubsub2Pubsub2TopicToKeys",qq);var rq=F("ytPubsub2Pubsub2IsAsync")||{};E("ytPubsub2Pubsub2IsAsync",rq);
E("ytPubsub2Pubsub2SkipSubKey",null);function sq(a,b){var c=tq();c&&c.publish.call(c,a.toString(),a,b)}
function uq(a){var b=vq,c=tq();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=F("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(pq[d])try{if(f&&b instanceof nq&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Pd){var l=new h;h.Pd=l.version}var m=h.Pd}catch(A){}if(!m||k.version!=m)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{m=Reflect;var n=m.construct;
var p=k.args,t=p.length;if(t>0){var v=Array(t);for(k=0;k<t;k++)v[k]=p[k];var x=v}else x=[];f=n.call(m,h,x)}catch(A){throw A.message="yt.pubsub2.Data.deserialize(): "+A.message,A;}}catch(A){throw A.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+A.message,A;}a.call(window,f)}catch(A){bm(A)}},rq[b.toString()]?F("yt.scheduler.instance")?Gj.pa(g):tm(g,0):g())});
pq[d]=!0;qq[b.toString()]||(qq[b.toString()]=[]);qq[b.toString()].push(d);return d}
function wq(){var a=xq,b=uq(function(c){a.apply(void 0,arguments);yq(b)});
return b}
function yq(a){var b=tq();b&&(typeof a==="number"&&(a=[a]),Mb(a,function(c){b.unsubscribeByKey(c);delete pq[c]}))}
function tq(){return F("ytPubsub2Pubsub2Instance")}
;function zq(a,b,c){c=c===void 0?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&sq("meta_logging_csi_event",{timerName:a,Yh:b})}
;var Aq=void 0,Bq=void 0;function Cq(){Bq||(Bq=vl(S("WORKER_SERIALIZATION_URL")));return Bq||void 0}
function Dq(){var a=Cq();Aq||a===void 0||(Aq=new Worker(jb(a),void 0));return Aq}
;var Eq=xm("max_body_size_to_compress",5E5),Fq=xm("min_body_size_to_compress",500),Gq=!0,Hq=0,Iq=0,Jq=xm("compression_performance_threshold_lr",250),Kq=xm("slow_compressions_before_abandon_count",4),Lq=!1,Mq=new Map,Nq=1,Oq=!0;function Pq(){if(typeof Worker==="function"&&Cq()&&!Lq){var a=function(c){c=c.data;if(c.op==="gzippedGelBatch"){var d=Mq.get(c.key);d&&(Qq(c.gzippedBatch,d.latencyPayload,d.url,d.options,d.sendFn),Mq.delete(c.key))}},b=Dq();
b&&(b.addEventListener("message",a),b.onerror=function(){Mq.clear()},Lq=!0)}}
function Rq(a,b,c,d,e){e=e===void 0?!1:e;var f={startTime:V(),ticks:{},infos:{}};if(Gq)try{var g=Sq(b);if(g!=null&&(g>Eq||g<Fq))d(a,c);else{if(T("gzip_gel_with_worker")&&(T("initial_gzip_use_main_thread")&&!Oq||!T("initial_gzip_use_main_thread"))){Lq||Pq();var h=Dq();if(h&&!e){Mq.set(Nq,{latencyPayload:f,url:a,options:c,sendFn:d});h.postMessage({op:"gelBatchToGzip",serializedBatch:b,key:Nq});Nq++;return}}var k=tl(jq(b));Qq(k,f,a,c,d)}}catch(l){cm(l),d(a,c)}else d(a,c)}
function Qq(a,b,c,d,e){Oq=!1;var f=V();b.ticks.gelc=f;Iq++;T("disable_compression_due_to_performance_degredation")&&f-b.startTime>=Jq&&(Hq++,T("abandon_compression_after_N_slow_zips")?Iq===xm("compression_disable_point")&&Hq>Kq&&(Gq=!1):Gq=!1);Tq(b);d.headers||(d.headers={});d.headers["Content-Encoding"]="gzip";d.postBody=a;d.postParams=void 0;e(c,d)}
function Uq(a){var b=b===void 0?!1:b;var c=c===void 0?!1:c;var d=V(),e={startTime:d,ticks:{},infos:{}},f=b?F("yt.logging.gzipForFetch",!1):!0;if(Gq&&f){if(!a.body)return a;try{var g=c?a.body:typeof a.body==="string"?a.body:JSON.stringify(a.body);f=g;if(!c&&typeof g==="string"){var h=Sq(g);if(h!=null&&(h>Eq||h<Fq))return a;c=b?{level:1}:void 0;f=tl(jq(g),c);var k=V();e.ticks.gelc=k;if(b){Iq++;if((T("disable_compression_due_to_performance_degredation")||T("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=Jq)if(Hq++,T("abandon_compression_after_N_slow_zips")||T("abandon_compression_after_N_slow_zips_lr")){b=Hq/Iq;var l=Kq/xm("compression_disable_point");Iq>0&&Iq%xm("compression_disable_point")===0&&b>=l&&(Gq=!1)}else Gq=!1;Tq(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(m){return cm(m),a}}else return a}
function Sq(a){try{return(new Blob(a.split(""))).size}catch(b){return cm(b),null}}
function Tq(a){T("gel_compression_csi_killswitch")||!T("log_gel_compression_latency")&&!T("log_gel_compression_latency_lr")||zq("gel_compression",a,{sampleRate:.1})}
;function Vq(a){a=Object.assign({},a);delete a.Authorization;var b=Zf();if(b){var c=new Kj;c.update(S("INNERTUBE_API_KEY"));c.update(b);a.hash=pd(c.digest(),3)}return a}
;var Wq;function Xq(){Wq||(Wq=new ho("yt.innertube"));return Wq}
function Yq(a,b,c,d){if(d)return null;d=Xq().get("nextId",!0)||1;var e=Xq().get("requests",!0)||{};e[d]={method:a,request:b,authState:Vq(c),requestTime:Math.round(V())};Xq().set("nextId",d+1,86400,!0);Xq().set("requests",e,86400,!0);return d}
function Zq(a){var b=Xq().get("requests",!0)||{};delete b[a];Xq().set("requests",b,86400,!0)}
function $q(a){var b=Xq().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(Math.round(V())-d.requestTime<6E4)){var e=d.authState,f=Vq(hq(!1));mg(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(V())),ar(a,d.method,e,{}));delete b[c]}}Xq().set("requests",b,86400,!0)}}
;function br(a){this.fc=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.yb=function(){};
this.now=Date.now;this.Rb=!1;var b;this.Ld=(b=a.Ld)!=null?b:100;var c;this.Gd=(c=a.Gd)!=null?c:1;var d;this.Ed=(d=a.Ed)!=null?d:2592E6;var e;this.Dd=(e=a.Dd)!=null?e:12E4;var f;this.Fd=(f=a.Fd)!=null?f:5E3;var g;this.V=(g=a.V)!=null?g:void 0;this.lc=!!a.lc;var h;this.jc=(h=a.jc)!=null?h:.1;var k;this.zc=(k=a.zc)!=null?k:10;a.handleError&&(this.handleError=a.handleError);a.yb&&(this.yb=a.yb);a.Rb&&(this.Rb=a.Rb);a.fc&&(this.fc=a.fc);this.W=a.W;this.Ca=a.Ca;this.ga=a.ga;this.fa=a.fa;this.sendFn=a.sendFn;
this.Vc=a.Vc;this.Sc=a.Sc;cr(this)&&(!this.W||this.W("networkless_logging"))&&dr(this)}
function dr(a){cr(a)&&!a.Rb&&(a.h=!0,a.lc&&Math.random()<=a.jc&&a.ga.ce(a.V),er(a),a.fa.ta()&&a.cc(),a.fa.listen(a.Vc,a.cc.bind(a)),a.fa.listen(a.Sc,a.nd.bind(a)))}
r=br.prototype;r.writeThenSend=function(a,b){var c=this;b=b===void 0?{}:b;if(cr(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.ga.set(d,this.V).then(function(e){d.id=e;c.fa.ta()&&fr(c,d)}).catch(function(e){fr(c,d);
gr(c,e)})}else this.sendFn(a,b)};
r.sendThenWrite=function(a,b,c){var d=this;b=b===void 0?{}:b;if(cr(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.W&&this.W("nwl_skip_retry")&&(e.skipRetry=c);if(this.fa.ta()||this.W&&this.W("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return B(function(k){if(k.h==1)return k.yield(d.ga.set(e,d.V).catch(function(l){gr(d,l)}),2);
f(g,h);k.h=0})}}this.sendFn(a,b,e.skipRetry)}else this.ga.set(e,this.V).catch(function(g){d.sendFn(a,b,e.skipRetry);
gr(d,g)})}else this.sendFn(a,b,this.W&&this.W("nwl_skip_retry")&&c)};
r.sendAndWrite=function(a,b){var c=this;b=b===void 0?{}:b;if(cr(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){d.id!==void 0?c.ga.xb(d.id,c.V):e=!0;c.fa.mb&&c.W&&c.W("vss_network_hint")&&c.fa.mb(!0);f(g,h)};
this.sendFn(d.url,d.options,void 0,!0);this.ga.set(d,this.V).then(function(g){d.id=g;e&&c.ga.xb(d.id,c.V)}).catch(function(g){gr(c,g)})}else this.sendFn(a,b,void 0,!0)};
r.cc=function(){var a=this;if(!cr(this))throw Error("IndexedDB is not supported: throttleSend");this.i||(this.i=this.Ca.pa(function(){var b;return B(function(c){if(c.h==1)return c.yield(a.ga.sd("NEW",a.V),2);if(c.h!=3)return b=c.i,b?c.yield(fr(a,b),3):(a.nd(),c.return());a.i&&(a.i=0,a.cc());c.h=0})},this.Ld))};
r.nd=function(){this.Ca.qa(this.i);this.i=0};
function fr(a,b){var c;return B(function(d){switch(d.h){case 1:if(!cr(a))throw Error("IndexedDB is not supported: immediateSend");if(b.id===void 0){d.A(2);break}return d.yield(a.ga.He(b.id,a.V),3);case 3:(c=d.i)||a.yb(Error("The request cannot be found in the database."));case 2:if(hr(a,b,a.Ed)){d.A(4);break}a.yb(Error("Networkless Logging: Stored logs request expired age limit"));if(b.id===void 0){d.A(5);break}return d.yield(a.ga.xb(b.id,a.V),5);case 5:return d.return();case 4:b.skipRetry||(b=ir(a,
b));if(!b){d.A(0);break}if(!b.skipRetry||b.id===void 0){d.A(8);break}return d.yield(a.ga.xb(b.id,a.V),8);case 8:a.sendFn(b.url,b.options,!!b.skipRetry),d.h=0}})}
function ir(a,b){if(!cr(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return B(function(m){switch(m.h){case 1:g=jr(f);(h=kr(f))&&a.W&&a.W("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.W&&a.W("nwl_consider_error_code")&&g||a.W&&!a.W("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.zc)){m.A(2);break}if(!a.fa.Ec){m.A(3);break}return m.yield(a.fa.Ec(),3);case 3:if(a.fa.ta()){m.A(2);break}c(e,f);if(!a.W||!a.W("nwl_consider_error_code")||((k=b)==null?void 0:k.id)===void 0){m.A(6);
break}return m.yield(a.ga.Wc(b.id,a.V,!1),6);case 6:return m.return();case 2:if(a.W&&a.W("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.zc)return m.return();a.potentialEsfErrorCounter++;if(((l=b)==null?void 0:l.id)===void 0){m.A(8);break}return b.sendCount<a.Gd?m.yield(a.ga.Wc(b.id,a.V,!0,h?!1:void 0),12):m.yield(a.ga.xb(b.id,a.V),8);case 12:a.Ca.pa(function(){a.fa.ta()&&a.cc()},a.Fd);
case 8:c(e,f),m.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return B(function(h){if(h.h==1)return((g=b)==null?void 0:g.id)===void 0?h.A(2):h.yield(a.ga.xb(b.id,a.V),2);a.fa.mb&&a.W&&a.W("vss_network_hint")&&a.fa.mb(!0);d(e,f);h.h=0})};
return b}
function hr(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function er(a){if(!cr(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.ga.sd("QUEUED",a.V).then(function(b){b&&!hr(a,b,a.Dd)?a.Ca.pa(function(){return B(function(c){if(c.h==1)return b.id===void 0?c.A(2):c.yield(a.ga.Wc(b.id,a.V),2);er(a);c.h=0})}):a.fa.ta()&&a.cc()})}
function gr(a,b){a.Sd&&!a.fa.ta()?a.Sd(b):a.handleError(b)}
function cr(a){return!!a.V||a.fc}
function jr(a){var b;return(a=a==null?void 0:(b=a.error)==null?void 0:b.code)&&a>=400&&a<=599?!1:!0}
function kr(a){var b;a=a==null?void 0:(b=a.error)==null?void 0:b.code;return!(a!==400&&a!==415)}
;var lr;
function mr(){if(lr)return lr();var a={};lr=Rp("LogsDatabaseV2",{Gb:(a.LogsRequestsStore={Nb:2},a),shared:!1,upgrade:function(b,c,d){c(2)&&Xo(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),dp(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return lr()}
;function nr(a){return qp(mr(),a)}
function or(a,b){var c,d,e,f;return B(function(g){if(g.h==1)return c={startTime:V(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(nr(b),2);if(g.h!=3)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:S("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(Zo(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=V();pr(c);return g.return(f)})}
function qr(a,b){var c,d,e,f,g,h,k,l;return B(function(m){if(m.h==1)return c={startTime:V(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},m.yield(nr(b),2);if(m.h!=3)return d=m.i,e=S("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,V()],h=IDBKeyRange.bound(f,g),k="prev",T("use_fifo_for_networkless")&&(k="next"),l=void 0,m.yield(Wo(d,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(n){return jp(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:k},
function(p){p.getValue()&&(l=p.getValue(),a==="NEW"&&(l.status="QUEUED",p.update(l)))})}),3);
c.ticks.tc=V();pr(c);return m.return(l)})}
function rr(a,b){var c;return B(function(d){if(d.h==1)return d.yield(nr(b),2);c=d.i;return d.return(Wo(c,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",So(f.h.put(g,void 0)).then(function(){return g})})}))})}
function sr(a,b,c,d){c=c===void 0?!0:c;var e;return B(function(f){if(f.h==1)return f.yield(nr(b),2);e=f.i;return f.return(Wo(e,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),d!==void 0&&(k.options.compress=d),So(h.h.put(k,void 0)).then(function(){return k})):Mo.resolve(void 0)})}))})}
function tr(a,b){var c;return B(function(d){if(d.h==1)return d.yield(nr(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function ur(a){var b,c;return B(function(d){if(d.h==1)return d.yield(nr(a),2);b=d.i;c=V()-2592E6;return d.yield(Wo(b,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(e){return fp(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return gp(f)})})}),0)})}
function vr(){B(function(a){return a.yield(Np(),0)})}
function pr(a){T("nwl_csi_killswitch")||zq("networkless_performance",a,{sampleRate:1})}
;var wr={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrCowatchPartyEvent:492,vrCowatchUserStartOrJoinEvent:504,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,
mbsConnectionInitiated:138,mbsPlaybackInitiated:139,mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,
kidsParentalGateTracking:168,kidsSignedOutSettingsStatus:437,kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,
transactionFlowPaymentSubmitted:460,transactionFlowPaymentSucceeded:329,transactionFlowSucceeded:178,transactionFlowFailed:179,transactionFlowPlayBillingConnectionStartEvent:428,transactionFlowSecondaryDeviceSuccess:458,transactionFlowErrorEvent:411,liteVideoQualityChanged:180,watchBreakEnablementSettingEvent:181,watchBreakFrequencySettingEvent:182,videoEffectsCameraPerformanceMetrics:183,adNotify:184,startupTelemetry:185,playbackOfflineFallbackUsed:186,outOfMemory:187,ypcPauseFlowStarted:188,ypcPauseFlowCancelled:189,
ypcPauseFlowSucceeded:190,ypcPauseFlowFailed:191,uploadFileSelected:192,ypcResumeFlowStarted:193,ypcResumeFlowCancelled:194,ypcResumeFlowSucceeded:195,ypcResumeFlowFailed:196,adsClientStateChange:197,ypcCancelFlowStarted:198,ypcCancelFlowCancelled:199,ypcCancelFlowSucceeded:200,ypcCancelFlowFailed:201,ypcCancelFlowGoToPaymentProcessor:402,ypcDeactivateFlowStarted:320,ypcRedeemFlowStarted:203,ypcRedeemFlowCancelled:204,ypcRedeemFlowSucceeded:205,ypcRedeemFlowFailed:206,ypcFamilyCreateFlowStarted:258,
ypcFamilyCreateFlowCancelled:259,ypcFamilyCreateFlowSucceeded:260,ypcFamilyCreateFlowFailed:261,ypcFamilyManageFlowStarted:262,ypcFamilyManageFlowCancelled:263,ypcFamilyManageFlowSucceeded:264,ypcFamilyManageFlowFailed:265,restoreContextEvent:207,embedsAdEvent:327,autoplayTriggered:209,clientDataErrorEvent:210,experimentalVssValidation:211,tvhtml5TriggeredEvent:212,tvhtml5FrameworksFieldTrialResult:216,tvhtml5FrameworksFieldTrialStart:220,musicOfflinePreferences:218,watchTimeSegment:219,appWidthLayoutError:221,
accountRegistryChange:226,userMentionAutoCompleteBoxEvent:227,downloadRecommendationEnablementSettingEvent:228,musicPlaybackContentModeChangeEvent:231,offlineDbOpenCompleted:232,kidsFlowEvent:233,kidsFlowCorpusSelectedEvent:234,videoEffectsEvent:235,unpluggedOpsEogAnalyticsEvent:236,playbackAudioRouteEvent:237,interactionLoggingDebugModeError:238,offlineYtbRefreshed:239,kidsFlowError:240,musicAutoplayOnLaunchAttempted:242,deviceContextActivityEvent:243,deviceContextEvent:244,templateResolutionException:245,
musicSideloadedPlaylistServiceCalled:246,embedsStorageAccessNotChecked:247,embedsHasStorageAccessResult:248,embedsItpPlayedOnReload:249,embedsRequestStorageAccessResult:250,embedsShouldRequestStorageAccessResult:251,embedsRequestStorageAccessState:256,embedsRequestStorageAccessFailedState:257,embedsItpWatchLaterResult:266,searchSuggestDecodingPayloadFailure:252,siriShortcutActivated:253,tvhtml5KeyboardPerformance:254,latencyActionSpan:255,elementsLog:267,ytbFileOpened:268,tfliteModelError:269,apiTest:270,
yongleUsbSetup:271,touStrikeInterstitialEvent:272,liteStreamToSave:274,appBundleClientEvent:275,ytbFileCreationFailed:276,adNotifyFailure:278,ytbTransferFailed:280,blockingRequestFailed:281,liteAccountSelector:282,liteAccountUiCallbacks:283,dummyPayload:284,browseResponseValidationEvent:285,entitiesError:286,musicIosBackgroundFetch:287,mdxNotificationEvent:289,layersValidationError:290,musicPwaInstalled:291,liteAccountCleanup:292,html5PlayerHealthEvent:293,watchRestoreAttempt:294,liteAccountSignIn:296,
notaireEvent:298,kidsVoiceSearchEvent:299,adNotifyFilled:300,delayedEventDropped:301,analyticsSearchEvent:302,systemDarkThemeOptOutEvent:303,flowEvent:304,networkConnectivityBaselineEvent:305,ytbFileImported:306,downloadStreamUrlExpired:307,directSignInEvent:308,lyricImpressionEvent:309,accessibilityStateEvent:310,tokenRefreshEvent:311,genericAttestationExecution:312,tvhtml5VideoSeek:313,unpluggedAutoPause:314,scrubbingEvent:315,bedtimeReminderEvent:317,tvhtml5UnexpectedRestart:319,tvhtml5StabilityTraceEvent:478,
tvhtml5OperationHealth:467,tvhtml5WatchKeyEvent:321,voiceLanguageChanged:322,tvhtml5LiveChatStatus:323,parentToolsCorpusSelectedEvent:324,offerAdsEnrollmentInitiated:325,networkQualityIntervalEvent:326,deviceStartupMetrics:328,heartbeatActionPlayerTransitioned:330,tvhtml5Lifecycle:331,heartbeatActionPlayerHalted:332,adaptiveInlineMutedSettingEvent:333,mainAppLibraryLoadingState:334,thirdPartyLogMonitoringEvent:336,appShellAssetLoadReport:337,tvhtml5AndroidAttestation:338,tvhtml5StartupSoundEvent:340,
iosBackgroundRefreshTask:342,iosBackgroundProcessingTask:343,sliEventBatch:344,postImpressionEvent:346,musicSideloadedPlaylistExport:347,idbUnexpectedlyClosed:348,voiceSearchEvent:349,mdxSessionCastEvent:350,idbQuotaExceeded:351,idbTransactionEnded:352,idbTransactionAborted:353,tvhtml5KeyboardLogging:354,idbIsSupportedCompleted:355,creatorStudioMobileEvent:356,idbDataCorrupted:357,parentToolsAppChosenEvent:358,webViewBottomSheetResized:359,activeStateControllerScrollPerformanceSummary:360,navigatorValidation:361,
mdxSessionHeartbeat:362,clientHintsPolyfillDiagnostics:363,clientHintsPolyfillEvent:364,proofOfOriginTokenError:365,kidsAddedAccountSummary:366,musicWearableDevice:367,ypcRefundFlowEvent:368,tvhtml5PlaybackMeasurementEvent:369,tvhtml5WatermarkMeasurementEvent:370,clientExpGcfPropagationEvent:371,mainAppReferrerIntent:372,leaderLockEnded:373,leaderLockAcquired:374,googleHatsEvent:375,persistentLensLaunchEvent:376,parentToolsChildWelcomeChosenEvent:378,browseThumbnailPreloadEvent:379,finalPayload:380,
mdxDialAdditionalDataUpdateEvent:381,webOrchestrationTaskLifecycleRecord:382,startupSignalEvent:384,accountError:385,gmsDeviceCheckEvent:386,accountSelectorEvent:388,accountUiCallbacks:389,mdxDialAdditionalDataProbeEvent:390,downloadsSearchIcingApiStats:391,downloadsSearchIndexUpdatedEvent:397,downloadsSearchIndexSnapshot:398,dataPushClientEvent:392,kidsCategorySelectedEvent:393,mdxDeviceManagementSnapshotEvent:394,prefetchRequested:395,prefetchableCommandExecuted:396,gelDebuggingEvent:399,webLinkTtsPlayEnd:400,
clipViewInvalid:401,persistentStorageStateChecked:403,cacheWipeoutEvent:404,playerEvent:410,sfvEffectPipelineStartedEvent:412,sfvEffectPipelinePausedEvent:429,sfvEffectPipelineEndedEvent:413,sfvEffectChosenEvent:414,sfvEffectLoadedEvent:415,sfvEffectUserInteractionEvent:465,sfvEffectFirstFrameProcessedLatencyEvent:416,sfvEffectAggregatedFramesProcessedLatencyEvent:417,sfvEffectAggregatedFramesDroppedEvent:418,sfvEffectPipelineErrorEvent:430,sfvEffectGraphFrozenEvent:419,sfvEffectGlThreadBlockedEvent:420,
mdeQosEvent:510,mdeVideoChangedEvent:442,mdePlayerPerformanceMetrics:472,mdeExporterEvent:497,genericClientExperimentEvent:423,homePreloadTaskScheduled:424,homePreloadTaskExecuted:425,homePreloadCacheHit:426,polymerPropertyChangedInObserver:427,applicationStarted:431,networkCronetRttBatch:432,networkCronetRttSummary:433,repeatChapterLoopEvent:436,seekCancellationEvent:462,lockModeTimeoutEvent:483,externalVideoShareToYoutubeAttempt:501,parentCodeEvent:502,offlineTransferStarted:4,musicOfflineMixtapePreferencesChanged:16,
mangoDailyNewVideosNotificationAttempt:40,mangoDailyNewVideosNotificationError:77,dtwsPlaybackStarted:112,dtwsTileFetchStarted:113,dtwsTileFetchCompleted:114,dtwsTileFetchStatusChanged:145,dtwsKeyframeDecoderBufferSent:115,dtwsTileUnderflowedOnNonkeyframe:116,dtwsBackfillFetchStatusChanged:143,dtwsBackfillUnderflowed:117,dtwsAdaptiveLevelChanged:128,blockingVisitorIdTimeout:277,liteSocial:18,mobileJsInvocation:297,biscottiBasedDetection:439,coWatchStateChange:440,embedsVideoDataDidChange:441,shortsFirst:443,
cruiseControlEvent:445,qoeClientLoggingContext:446,atvRecommendationJobExecuted:447,tvhtml5UserFeedback:448,producerProjectCreated:449,producerProjectOpened:450,producerProjectDeleted:451,producerProjectElementAdded:453,producerProjectElementRemoved:454,producerAppStateChange:509,producerProjectDiskInsufficientExportFailure:516,tvhtml5ShowClockEvent:455,deviceCapabilityCheckMetrics:456,youtubeClearcutEvent:461,offlineBrowseFallbackEvent:463,getCtvTokenEvent:464,startupDroppedFramesSummary:466,screenshotEvent:468,
miniAppPlayEvent:469,elementsDebugCounters:470,fontLoadEvent:471,webKillswitchReceived:473,webKillswitchExecuted:474,cameraOpenEvent:475,manualSmoothnessMeasurement:476,tvhtml5AppQualityEvent:477,polymerPropertyAccessEvent:479,miniAppSdkUsage:480,cobaltTelemetryEvent:481,crossDevicePlayback:482,channelCreatedWithObakeImage:484,channelEditedWithObakeImage:485,offlineDeleteEvent:486,crossDeviceNotificationTransfer:487,androidIntentEvent:488,unpluggedAmbientInterludesCounterfactualEvent:489,keyPlaysPlayback:490,
shortsCreationFallbackEvent:493,vssData:491,castMatch:494,miniAppPerformanceMetrics:495,userFeedbackEvent:496,kidsGuestSessionMismatch:498,musicSideloadedPlaylistMigrationEvent:499,sleepTimerSessionFinishEvent:500,watchEpPromoConflict:503,innertubeResponseCacheMetrics:505,miniAppAdEvent:506,dataPlanUpsellEvent:507,producerProjectRenamed:508,producerMediaSelectionEvent:511,embedsAutoplayStatusChanged:512,remoteConnectEvent:513,connectedSessionMisattributionEvent:514,producerProjectElementModified:515};var xr={},yr=Rp("ServiceWorkerLogsDatabase",{Gb:(xr.SWHealthLog={Nb:1},xr),shared:!0,upgrade:function(a,b){b(1)&&dp(Xo(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function zr(a){return qp(yr(),a)}
function Ar(a){var b,c;B(function(d){if(d.h==1)return d.yield(zr(a),2);b=d.i;c=V()-2592E6;return d.yield(Wo(b,["SWHealthLog"],{mode:"readwrite",ka:!0},function(e){return fp(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return gp(f)})})}),0)})}
function Br(a){var b;return B(function(c){if(c.h==1)return c.yield(zr(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var Cr={},Dr=0;function Er(a){var b=b===void 0?{}:b;var c=new Image,d=""+Dr++;Cr[d]=c;c.onload=c.onerror=function(){delete Cr[d]};
b.Uh&&(c.referrerPolicy="no-referrer");c.src=a}
;var Fr;function Gr(){Fr||(Fr=new ho("yt.offline"));return Fr}
function Hr(a){if(T("offline_error_handling")){var b=Gr().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Gr().set("errors",b,2592E3,!0)}}
;function Ir(){this.h=new Map;this.i=!1}
function Jr(){if(!Ir.instance){var a=F("yt.networkRequestMonitor.instance")||new Ir;E("yt.networkRequestMonitor.instance",a);Ir.instance=a}return Ir.instance}
Ir.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Ir.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:a===!1&&this.i?!0:null};
Ir.prototype.removeParams=function(a){return a.split("?")[0]};
Ir.prototype.removeParams=Ir.prototype.removeParams;Ir.prototype.isEndpointCFR=Ir.prototype.isEndpointCFR;Ir.prototype.requestComplete=Ir.prototype.requestComplete;Ir.getInstance=Jr;function Kr(){Ph.call(this);var a=this;this.j=!1;this.h=Fj();this.h.listen("networkstatus-online",function(){if(a.j&&T("offline_error_handling")){var b=Gr().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new U(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;bm(d)}Gr().set("errors",{},2592E3,!0)}}})}
w(Kr,Ph);function Lr(){if(!Kr.instance){var a=F("yt.networkStatusManager.instance")||new Kr;E("yt.networkStatusManager.instance",a);Kr.instance=a}return Kr.instance}
r=Kr.prototype;r.ta=function(){return this.h.ta()};
r.mb=function(a){this.h.h=a};
r.we=function(){var a=window.navigator.onLine;return a===void 0?!0:a};
r.le=function(){this.j=!0};
r.listen=function(a,b){return this.h.listen(a,b)};
r.Ec=function(a){a=Dj(this.h,a);a.then(function(b){T("use_cfr_monitor")&&Jr().requestComplete("generate_204",b)});
return a};
Kr.prototype.sendNetworkCheckRequest=Kr.prototype.Ec;Kr.prototype.listen=Kr.prototype.listen;Kr.prototype.enableErrorFlushing=Kr.prototype.le;Kr.prototype.getWindowStatus=Kr.prototype.we;Kr.prototype.networkStatusHint=Kr.prototype.mb;Kr.prototype.isNetworkAvailable=Kr.prototype.ta;Kr.getInstance=Lr;function Mr(a){a=a===void 0?{}:a;Ph.call(this);var b=this;this.h=this.u=0;this.j=Lr();var c=F("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.rateLimit?(this.rateLimit=a.rateLimit,c("networkstatus-online",function(){Nr(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Nr(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){Qh(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Qh(b,"publicytnetworkstatus-offline")})))}
w(Mr,Ph);Mr.prototype.ta=function(){var a=F("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
Mr.prototype.mb=function(a){var b=F("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Mr.prototype.Ec=function(a){var b=this,c;return B(function(d){c=F("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return T("skip_network_check_if_cfr")&&Jr().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.mb(((f=window.navigator)==null?void 0:f.onLine)||!0);e(b.ta())})):c?d.return(c(a)):d.return(!0)})};
function Nr(a,b){a.rateLimit?a.h?(Gj.qa(a.u),a.u=Gj.pa(function(){a.o!==b&&(Qh(a,b),a.o=b,a.h=V())},a.rateLimit-(V()-a.h))):(Qh(a,b),a.o=b,a.h=V()):Qh(a,b)}
;var Or;function Pr(){var a=br.call;Or||(Or=new Mr({Kh:!0,Bh:!0}));a.call(br,this,{ga:{ce:ur,xb:tr,sd:qr,He:rr,Wc:sr,set:or},fa:Or,handleError:function(b,c,d){var e,f=d==null?void 0:(e=d.error)==null?void 0:e.code;if(f===400||f===415){var g;cm(new U(b.message,c,d==null?void 0:(g=d.error)==null?void 0:g.code),void 0,void 0,void 0,!0)}else bm(b)},
yb:cm,sendFn:Qr,now:V,Sd:Hr,Ca:go(),Vc:"publicytnetworkstatus-online",Sc:"publicytnetworkstatus-offline",lc:!0,jc:.1,zc:xm("potential_esf_error_limit",10),W:T,Rb:!(yn()&&Rr())});this.j=new ij;T("networkless_immediately_drop_all_requests")&&vr();Op("LogsDatabaseV2")}
w(Pr,br);function Sr(){var a=F("yt.networklessRequestController.instance");a||(a=new Pr,E("yt.networklessRequestController.instance",a),T("networkless_logging")&&Dp().then(function(b){a.V=b;dr(a);a.j.resolve();a.lc&&Math.random()<=a.jc&&a.V&&Ar(a.V);T("networkless_immediately_drop_sw_health_store")&&Tr(a)}));
return a}
Pr.prototype.writeThenSend=function(a,b){b||(b={});b=Ur(a,b);yn()||(this.h=!1);br.prototype.writeThenSend.call(this,a,b)};
Pr.prototype.sendThenWrite=function(a,b,c){b||(b={});b=Ur(a,b);yn()||(this.h=!1);br.prototype.sendThenWrite.call(this,a,b,c)};
Pr.prototype.sendAndWrite=function(a,b){b||(b={});b=Ur(a,b);yn()||(this.h=!1);br.prototype.sendAndWrite.call(this,a,b)};
Pr.prototype.awaitInitialization=function(){return this.j.promise};
function Tr(a){var b;B(function(c){if(!a.V)throw b=Io("clearSWHealthLogsDb"),b;return c.return(Br(a.V).catch(function(d){a.handleError(d)}))})}
function Qr(a,b,c,d){d=d===void 0?!1:d;b=T("web_fp_via_jspb")?Object.assign({},b):b;T("use_cfr_monitor")&&Vr(a,b);if(T("use_request_time_ms_header"))b.headers&&nm(a)&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(V())));else{var e;if((e=b.postParams)==null?0:e.requestTimeMs)b.postParams.requestTimeMs=Math.round(V())}if(c&&Object.keys(b).length===0){var f=f===void 0?"":f;var g=g===void 0?!1:g;var h=h===void 0?!1:h;if(a)if(f)Cm(a,void 0,"POST",f,void 0);else if(S("USE_NET_AJAX_FOR_PING_TRANSPORT",
!1)||h)Cm(a,void 0,"GET","",void 0,void 0,g,h);else{b:{try{var k=new pc({url:a});if(k.u?typeof k.i!=="string"||k.i.length===0?0:{version:3,je:k.i,Zd:oc(k.j,"act=1","ri=1",qc(k))}:k.M&&{version:4,je:oc(k.j,"dct=1","suid="+k.o,""),Zd:oc(k.j,"act=1","ri=1","suid="+k.o)}){var l=ac(bc(5,a)),m;if(!(m=!l||!l.endsWith("/aclk"))){var n=a.search(kc),p=jc(a,0,"ri",n);if(p<0)var t=null;else{var v=a.indexOf("&",p);if(v<0||v>n)v=n;t=decodeURIComponent(a.slice(p+3,v!==-1?v:0).replace(/\+/g," "))}m=t!=="1"}var x=
!m;break b}}catch(H){}x=!1}if(x){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var A=!0;break b}}catch(H){}A=!1}c=A?!0:!1}else c=!1;c||Er(a)}}else b.compress?b.postBody?(typeof b.postBody!=="string"&&(b.postBody=JSON.stringify(b.postBody)),Rq(a,b.postBody,b,Gm,d)):Rq(a,JSON.stringify(b.postParams),b,Fm,d):Gm(a,b)}
function Ur(a,b){T("use_event_time_ms_header")&&nm(a)&&(b.headers||(b.headers={}),b.headers["X-Goog-Event-Time"]=JSON.stringify(Math.round(V())));return b}
function Vr(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Jr().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Jr().requestComplete(a,!0);d(e,f)}}
function Rr(){return cc(document.location.toString())!=="www.youtube-nocookie.com"}
;var Wr=!1,Xr=D.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Wr};E("ytNetworklessLoggingInitializationOptions",Xr);function Yr(){var a;B(function(b){if(b.h==1)return b.yield(Dp(),2);a=b.i;if(!a||!yn()&&!T("nwl_init_require_datasync_id_killswitch")||!Rr())return b.A(0);Wr=!0;Xr.isNwlInitialized=Wr;return b.yield(Sr().awaitInitialization(),0)})}
;function Zr(a){var b=this;this.config_=null;a?this.config_=a:eq()&&(this.config_=fq());Bn(function(){$q(b)},5E3)}
Zr.prototype.isReady=function(){!this.config_&&eq()&&(this.config_=fq());return!!this.config_};
function ar(a,b,c,d){function e(n){n=n===void 0?!1:n;var p;if(d.retry&&h!="www.youtube-nocookie.com"&&(n||T("skip_ls_gel_retry")||g.headers["Content-Type"]!=="application/json"||(p=Yq(b,c,l,k)),p)){var t=g.onSuccess,v=g.onFetchSuccess;g.onSuccess=function(H,K){Zq(p);t(H,K)};
c.onFetchSuccess=function(H,K){Zq(p);v(H,K)}}try{if(n&&d.retry&&!d.networklessOptions.bypassNetworkless)g.method="POST",d.networklessOptions.writeThenSend?Sr().writeThenSend(m,g):Sr().sendAndWrite(m,g);
else if(d.compress){var x=!d.networklessOptions.writeThenSend;if(g.postBody){var A=g.postBody;typeof A!=="string"&&(A=JSON.stringify(g.postBody));Rq(m,A,g,Gm,x)}else Rq(m,JSON.stringify(g.postParams),g,Fm,x)}else T("web_all_payloads_via_jspb")?Gm(m,g):Fm(m,g)}catch(H){if(H.name==="InvalidAccessError")p&&(Zq(p),p=0),cm(Error("An extension is blocking network request."));else throw H;}p&&Bn(function(){$q(a)},5E3)}
!S("VISITOR_DATA")&&b!=="visitor_id"&&Math.random()<.01&&cm(new U("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new U("innertube xhrclient not ready",b,c,d);bm(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(n,p){if(d.onSuccess)d.onSuccess(p)},
onFetchSuccess:function(n){if(d.onSuccess)d.onSuccess(n)},
onError:function(n,p){if(d.onError)d.onError(p)},
onFetchError:function(n){if(d.onError)d.onError(n)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.Ce)&&(h=f);var k=a.config_.De||!1,l=hq(k,h,d);Object.assign(g.headers,l);g.headers.Authorization&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var m=lm(""+h+("/youtubei/"+a.config_.innertubeApiVersion+"/"+b),{alt:"json"});(F("ytNetworklessLoggingInitializationOptions")?Xr.isNwlInitialized:Wr)?Bp().then(function(n){e(n)}):e(!1)}
;var $r=0,as=id?"webkit":hd?"moz":fd?"ms":ed?"o":"";E("ytDomDomGetNextId",F("ytDomDomGetNextId")||function(){return++$r});var bs={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function cs(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in bs||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&c.nodeType==3&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else this.type=="mouseover"?d=a.fromElement:this.type=="mouseout"&&(d=a.toElement);this.relatedTarget=d;this.clientX=a.clientX!=void 0?a.clientX:a.pageX;this.clientY=a.clientY!=void 0?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||(this.type=="keypress"?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function ds(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
cs.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
cs.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
cs.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var ig=D.ytEventsEventsListeners||{};E("ytEventsEventsListeners",ig);var es=D.ytEventsEventsCounter||{count:0};E("ytEventsEventsCounter",es);
function gs(a,b,c,d){d=d===void 0?{}:d;a.addEventListener&&(b!="mouseenter"||"onmouseenter"in document?b!="mouseleave"||"onmouseenter"in document?b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return hg(function(e){var f=typeof e[4]==="boolean"&&e[4]==!!d,g=Oa(e[4])&&Oa(d)&&mg(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function hs(a,b,c,d){d=d===void 0?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=gs(a,b,c,d);if(e)return e;e=++es.count+"";var f=!(b!="mouseenter"&&b!="mouseleave"||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new cs(h);if(!wg(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new cs(h);
h.currentTarget=a;return c.call(a,h)};
g=am(g);a.addEventListener?(b=="mouseenter"&&f?b="mouseover":b=="mouseleave"&&f?b="mouseout":b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),is()||typeof d==="boolean"?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);ig[e]=[a,b,c,g,d];return e}
function js(a){a&&(typeof a=="string"&&(a=[a]),Mb(a,function(b){if(b in ig){var c=ig[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?is()||typeof c==="boolean"?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete ig[b]}}))}
var is=ei(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});function ps(a){this.G=a;this.h=null;this.o=0;this.D=null;this.u=0;this.i=[];for(a=0;a<4;a++)this.i.push(0);this.j=0;this.U=hs(window,"mousemove",Wa(this.Y,this));a=Wa(this.P,this);typeof a==="function"&&(a=am(a));this.Z=window.setInterval(a,25)}
ab(ps,G);ps.prototype.Y=function(a){a.h===void 0&&ds(a);var b=a.h;a.i===void 0&&ds(a);this.h=new eg(b,a.i)};
ps.prototype.P=function(){if(this.h){var a=V();if(this.o!=0){var b=this.D,c=this.h,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.o);this.i[this.j]=Math.abs((d-this.u)/this.u)>.5?1:0;for(c=b=0;c<4;c++)b+=this.i[c]||0;b>=3&&this.G();this.u=d}this.o=a;this.D=this.h;this.j=(this.j+1)%4}};
ps.prototype.ba=function(){window.clearInterval(this.Z);js(this.U)};var qs={};
function rs(a){var b=a===void 0?{}:a;a=b.Te===void 0?!1:b.Te;b=b.ne===void 0?!0:b.ne;if(F("_lact",window)==null){var c=parseInt(S("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;E("_lact",c,window);E("_fact",c,window);c==-1&&ss();hs(document,"keydown",ss);hs(document,"keyup",ss);hs(document,"mousedown",ss);hs(document,"mouseup",ss);a?hs(window,"touchmove",function(){ts("touchmove",200)},{passive:!0}):(hs(window,"resize",function(){ts("resize",200)}),b&&hs(window,"scroll",function(){ts("scroll",200)}));
new ps(function(){ts("mouse",100)});
hs(document,"touchstart",ss,{passive:!0});hs(document,"touchend",ss,{passive:!0})}}
function ts(a,b){qs[a]||(qs[a]=!0,Gj.pa(function(){ss();qs[a]=!1},b))}
function ss(){F("_lact",window)==null&&rs();var a=Date.now();E("_lact",a,window);F("_fact",window)==-1&&E("_fact",a,window);(a=F("ytglobal.ytUtilActivityCallback_"))&&a()}
function us(){var a=F("_lact",window);return a==null?-1:Math.max(Date.now()-a,0)}
;var vs=D.ytPubsubPubsubInstance||new O,ws=D.ytPubsubPubsubSubscribedKeys||{},xs=D.ytPubsubPubsubTopicToKeys||{},ys=D.ytPubsubPubsubIsSynchronous||{};function zs(a,b){var c=As();if(c&&b){var d=c.subscribe(a,function(){function e(){ws[d]&&b.apply&&typeof b.apply=="function"&&b.apply(window,f)}
var f=arguments;try{ys[a]?e():tm(e,0)}catch(g){bm(g)}},void 0);
ws[d]=!0;xs[a]||(xs[a]=[]);xs[a].push(d);return d}return 0}
function Bs(a){var b=As();b&&(typeof a==="number"?a=[a]:typeof a==="string"&&(a=[parseInt(a,10)]),Mb(a,function(c){b.unsubscribeByKey(c);delete ws[c]}))}
function Cs(a,b){var c=As();c&&c.publish.apply(c,arguments)}
function Ds(a){var b=As();if(b)if(b.clear(a),a)Es(a);else for(var c in xs)Es(c)}
function As(){return D.ytPubsubPubsubInstance}
function Es(a){xs[a]&&(a=xs[a],Mb(a,function(b){ws[b]&&delete ws[b]}),a.length=0)}
O.prototype.subscribe=O.prototype.subscribe;O.prototype.unsubscribeByKey=O.prototype.dc;O.prototype.publish=O.prototype.sb;O.prototype.clear=O.prototype.clear;E("ytPubsubPubsubInstance",vs);E("ytPubsubPubsubTopicToKeys",xs);E("ytPubsubPubsubIsSynchronous",ys);E("ytPubsubPubsubSubscribedKeys",ws);var Fs=Symbol("injectionDeps");function Gs(a){this.name=a}
Gs.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Hs(a){this.key=a}
function Is(a){return new Hs(a)}
function Js(){this.i=new Map;this.j=new Map;this.h=new Map}
function Ks(a,b){a.i.set(b.Bc,b);var c=a.j.get(b.Bc);if(c)try{c.Th(a.resolve(b.Bc))}catch(d){c.Rh(d)}}
Js.prototype.resolve=function(a){return a instanceof Hs?Ls(this,a.key,[],!0):Ls(this,a,[])};
function Ls(a,b,c,d){d=d===void 0?!1:d;if(c.indexOf(b)>-1)throw Error("Deps cycle for: "+b);if(a.h.has(b))return a.h.get(b);if(!a.i.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.i.get(b);c.push(b);if(d.Od!==void 0)var e=d.Od;else if(d.Af)e=d[Fs]?Ms(a,d[Fs],c):[],e=d.Af.apply(d,z(e));else if(d.Nd){e=d.Nd;var f=e[Fs]?Ms(a,e[Fs],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(z(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Xh||a.h.set(b,e);return e}
function Ms(a,b,c){return b?b.map(function(d){return d instanceof Hs?Ls(a,d.key,c,!0):Ls(a,d,c)}):[]}
;var Ns;function Os(){Ns||(Ns=new Js);return Ns}
;var Ps=window;function Qs(){var a,b;return"h5vcc"in Ps&&((a=Ps.h5vcc.traceEvent)==null?0:a.traceBegin)&&((b=Ps.h5vcc.traceEvent)==null?0:b.traceEnd)?1:"performance"in Ps&&Ps.performance.mark&&Ps.performance.measure?2:0}
function Rs(a){var b=Qs();switch(b){case 1:Ps.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:Ps.performance.mark(a+"-start");break;case 0:break;default:xb(b,"unknown trace type")}}
function Ss(a){var b=Qs();switch(b){case 1:Ps.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:b=a+"-start";var c=a+"-end";Ps.performance.mark(c);Ps.performance.measure(a,b,c);break;case 0:break;default:xb(b,"unknown trace type")}}
;var Ts=T("web_enable_lifecycle_monitoring")&&Qs()!==0,Us=T("web_enable_lifecycle_monitoring");function Vs(a){var b,c;(c=(b=window).onerror)==null||c.call(b,a.message,"",0,0,a)}
;function Ws(a){var b=this;var c=c===void 0?0:c;var d=d===void 0?go():d;this.j=c;this.scheduler=d;this.i=new ij;this.h=a;for(a={jb:0};a.jb<this.h.length;a={yc:void 0,jb:a.jb},a.jb++)a.yc=this.h[a.jb],c=function(e){return function(){e.yc.Mc();b.h[e.jb].Ac=!0;b.h.every(function(f){return f.Ac===!0})&&b.i.resolve()}}(a),d=this.getPriority(a.yc),d=this.scheduler.Ra(c,d),this.h[a.jb]=Object.assign({},a.yc,{Mc:c,
jobId:d})}
function Xs(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=y(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],c.jobId===void 0||c.Ac||(a.scheduler.qa(c.jobId),a.scheduler.Ra(c.Mc,10))}
Ws.prototype.cancel=function(){for(var a=y(this.h),b=a.next();!b.done;b=a.next())b=b.value,b.jobId===void 0||b.Ac||this.scheduler.qa(b.jobId),b.Ac=!0;this.i.resolve()};
Ws.prototype.getPriority=function(a){var b;return(b=a.priority)!=null?b:this.j};function Ys(a){this.state=a;this.plugins=[];this.o=void 0;this.D={};Ts&&Rs(this.state)}
r=Ys.prototype;r.install=function(a){this.plugins.push(a);return this};
r.uninstall=function(){var a=this;C.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);b>-1&&a.plugins.splice(b,1)})};
r.transition=function(a,b){var c=this;Ts&&Ss(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(Xs(this.j),this.j=void 0);Zs(this,a,b);this.state=a;Ts&&Rs(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d($s(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function $s(a,b){var c=b.filter(function(e){return at(a,e)===10}),d=b.filter(function(e){return at(a,e)!==10});
return a.D.Wh?function(){var e=C.apply(0,arguments);return B(function(f){if(f.h==1)return f.yield(a.Ze.apply(a,[c].concat(z(e))),2);a.Id.apply(a,[d].concat(z(e)));f.h=0})}:function(){var e=C.apply(0,arguments);
a.af.apply(a,[c].concat(z(e)));a.Id.apply(a,[d].concat(z(e)))}}
r.af=function(a){for(var b=C.apply(1,arguments),c=go(),d=y(a),e=d.next(),f={};!e.done;f={Sb:void 0},e=d.next())f.Sb=e.value,c.Lb(function(g){return function(){bt(g.Sb.name);ct(function(){return g.Sb.callback.apply(g.Sb,z(b))});
dt(g.Sb.name)}}(f))};
r.Ze=function(a){var b=C.apply(1,arguments),c,d,e,f,g;return B(function(h){h.h==1&&(c=go(),d=y(a),e=d.next(),f={});if(h.h!=3){if(e.done)return h.A(0);f.Xa=e.value;f.ec=void 0;g=function(k){return function(){bt(k.Xa.name);var l=ct(function(){return k.Xa.callback.apply(k.Xa,z(b))});
fe(l)?k.ec=T("web_lifecycle_error_handling_killswitch")?l.then(function(){dt(k.Xa.name)}):l.then(function(){dt(k.Xa.name)},function(m){Vs(m);
dt(k.Xa.name)}):dt(k.Xa.name)}}(f);
c.Lb(g);return f.ec?h.yield(f.ec,3):h.A(3)}f={Xa:void 0,ec:void 0};e=d.next();return h.A(2)})};
r.Id=function(a){var b=C.apply(1,arguments),c=this,d=a.map(function(e){return{Mc:function(){bt(e.name);ct(function(){return e.callback.apply(e,z(b))});
dt(e.name)},
priority:at(c,e)}});
d.length&&(this.j=new Ws(d))};
function at(a,b){var c,d;return(d=(c=a.o)!=null?c:b.priority)!=null?d:0}
function bt(a){Ts&&a&&Rs(a)}
function dt(a){Ts&&a&&Ss(a)}
function Zs(a,b,c){Us&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
fa.Object.defineProperties(Ys.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});
function ct(a){if(T("web_lifecycle_error_handling_killswitch"))return a();try{return a()}catch(b){Vs(b)}}
;function et(a){Ys.call(this,a===void 0?"none":a);this.h=null;this.o=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.u},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var ft;w(et,Ys);et.prototype.i=function(a,b){var c=this;this.h=Bn(function(){c.currentState==="application_navigating"&&c.transition("none")},5E3);
a(b==null?void 0:b.event)};
et.prototype.u=function(a,b){this.h&&(Gj.qa(this.h),this.h=null);a(b==null?void 0:b.event)};
function gt(){ft||(ft=new et);return ft}
;var ht=[];E("yt.logging.transport.getScrapedGelPayloads",function(){return ht});function jt(){this.store={};this.h={}}
jt.prototype.storePayload=function(a,b){a=kt(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);T("more_accurate_gel_parser")&&(b=new CustomEvent("TRANSPORTING_NEW_EVENT"),window.dispatchEvent(b));return a};
jt.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=lt(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,z(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,z(this.store[b[d]].splice(0,a.sizeLimit))));(a==null?0:a.sizeLimit)&&c.length<(a==null?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,z(this.smartExtractMatchingEntries(a))));return c};
jt.prototype.extractMatchingEntries=function(a){a=lt(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,z(this.store[a[c]])),delete this.store[a[c]]);return b};
jt.prototype.getSequenceCount=function(a){a=lt(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=((d=this.store[a[c]])==null?void 0:d.length)||0}return b};
function lt(a,b){var c=kt(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(d.length<=1&&kt(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(mt(b.auth,g[0])){var h=b.isJspb;mt(h===void 0?"undefined":h?"true":"false",g[1])&&mt(b.cttAuthInfo,g[2])&&(h=b.tier,h=h===void 0?"undefined":JSON.stringify(h),mt(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function mt(a,b){return a===void 0||a==="undefined"?!0:a===b}
jt.prototype.getSequenceCount=jt.prototype.getSequenceCount;jt.prototype.extractMatchingEntries=jt.prototype.extractMatchingEntries;jt.prototype.smartExtractMatchingEntries=jt.prototype.smartExtractMatchingEntries;jt.prototype.storePayload=jt.prototype.storePayload;function kt(a){return[a.auth===void 0?"undefined":a.auth,a.isJspb===void 0?"undefined":a.isJspb,a.cttAuthInfo===void 0?"undefined":a.cttAuthInfo,a.tier===void 0?"undefined":a.tier].join("/")}
;function nt(a,b){if(a)return a[b.name]}
;var ot=xm("initial_gel_batch_timeout",2E3),pt=xm("gel_queue_timeout_max_ms",6E4),qt=xm("gel_min_batch_size",5),rt=void 0;function st(){this.o=this.h=this.i=0;this.j=!1}
var tt=new st,ut=new st,vt=new st,wt=new st,xt,zt=!0,At=D.ytLoggingTransportTokensToCttTargetIds_||{};E("ytLoggingTransportTokensToCttTargetIds_",At);var Bt={};function Ct(){var a=F("yt.logging.ims");a||(a=new jt,E("yt.logging.ims",a));return a}
function Dt(a,b){if(a.endpoint==="log_event"){Et();var c=Ft(a),d=Gt(a.payload)||"";a:{if(T("enable_web_tiered_gel")){var e=wr[d||""];var f,g,h,k=Os().resolve(Is($p))==null?void 0:(f=aq())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.eventLoggingConfig)==null?void 0:h.payloadPolicies;if(k)for(f=0;f<k.length;f++)if(k[f].payloadNumber===e){e=k[f];break a}}e=void 0}k=200;if(e){if(e.enabled===!1&&!T("web_payload_policy_disabled_killswitch"))return;k=Ht(e.tier);if(k===400){It(a,b);return}}Bt[c]=
!0;c={cttAuthInfo:c,isJspb:!1,tier:k};Ct().storePayload(c,a.payload);Jt(b,c,d==="gelDebuggingEvent")}}
function Jt(a,b,c){function d(){Kt({writeThenSend:!0},void 0,e,b.tier)}
var e=!1;e=e===void 0?!1:e;c=c===void 0?!1:c;a&&(rt=new a);a=xm("tvhtml5_logging_max_batch_ads_fork")||xm("tvhtml5_logging_max_batch")||xm("web_logging_max_batch")||100;var f=V(),g=Lt(e,b.tier),h=g.o;c&&(g.j=!0);c=0;b&&(c=Ct().getSequenceCount(b));c>=1E3?d():c>=a?xt||(xt=Mt(function(){d();xt=void 0},0)):f-h>=10&&(Nt(e,b.tier),g.o=f)}
function It(a,b){if(a.endpoint==="log_event"){T("more_accurate_gel_parser")&&Ct().storePayload({isJspb:!1},a.payload);Et();var c=Ft(a),d=new Map;d.set(c,[a.payload]);var e=Gt(a.payload)||"";b&&(rt=new b);return new fi(function(f,g){rt&&rt.isReady()?Ot(d,rt,f,g,{bypassNetworkless:!0},!0,e==="gelDebuggingEvent"):f()})}}
function Ft(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);At[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function Kt(a,b,c,d){a=a===void 0?{}:a;c=c===void 0?!1:c;new fi(function(e,f){var g=Lt(c,d),h=g.j;g.j=!1;Pt(g.i);Pt(g.h);g.h=0;rt&&rt.isReady()?d===void 0&&T("enable_web_tiered_gel")?Qt(e,f,a,b,c,300,h):Qt(e,f,a,b,c,d,h):(Nt(c,d),e())})}
function Qt(a,b,c,d,e,f,g){var h=rt;c=c===void 0?{}:c;e=e===void 0?!1:e;f=f===void 0?200:f;g=g===void 0?!1:g;var k=new Map,l={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(d!==void 0)f=T("enable_web_tiered_gel")?Ct().smartExtractMatchingEntries({keys:[l,e],sizeLimit:1E3}):Ct().extractMatchingEntries(e),k.set(d,f);else for(d=y(Object.keys(Bt)),l=d.next();!l.done;l=d.next())l=l.value,e=T("enable_web_tiered_gel")?Ct().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:l,tier:f},
{isJspb:!1,cttAuthInfo:l}],sizeLimit:1E3}):Ct().extractMatchingEntries({isJspb:!1,cttAuthInfo:l}),e.length>0&&k.set(l,e),(T("web_fp_via_jspb_and_json")&&c.writeThenSend||!T("web_fp_via_jspb_and_json"))&&delete Bt[l];Ot(k,h,a,b,c,!1,g)}
function Nt(a,b){function c(){Kt({writeThenSend:!0},void 0,a,b)}
a=a===void 0?!1:a;b=b===void 0?200:b;var d=Lt(a,b),e=d===wt||d===vt?5E3:pt;T("web_gel_timeout_cap")&&!d.h&&(e=Mt(function(){c()},e),d.h=e);
Pt(d.i);e=S("LOGGING_BATCH_TIMEOUT",xm("web_gel_debounce_ms",1E4));T("shorten_initial_gel_batch_timeout")&&zt&&(e=ot);e=Mt(function(){xm("gel_min_batch_size")>0?Ct().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=qt&&c():c()},e);
d.i=e}
function Ot(a,b,c,d,e,f,g){e=e===void 0?{}:e;var h=Math.round(V()),k=a.size,l=(g===void 0?0:g)&&T("vss_through_gel_video_stats")?"video_stats":"log_event";a=y(a);var m=a.next();for(g={};!m.done;g={Rc:void 0,batchRequest:void 0,dangerousLogToVisitorSession:void 0,Uc:void 0,Tc:void 0},m=a.next()){var n=y(m.value);m=n.next().value;n=n.next().value;g.batchRequest=og({context:gq(b.config_||fq())});if(!Na(n)&&!T("throw_err_when_logevent_malformed_killswitch")){d();break}g.batchRequest.events=n;(n=At[m])&&
Rt(g.batchRequest,m,n);delete At[m];g.dangerousLogToVisitorSession=m==="visitorOnlyApprovedKey";St(g.batchRequest,h,g.dangerousLogToVisitorSession);T("always_send_and_write")&&(e.writeThenSend=!1);g.Uc=function(p){T("start_client_gcf")&&Gj.pa(function(){return B(function(t){return t.yield(Tt(p),0)})});
k--;k||c()};
g.Rc=0;g.Tc=function(p){return function(){p.Rc++;if(e.bypassNetworkless&&p.Rc===1)try{ar(b,l,p.batchRequest,Ut({writeThenSend:!0},p.dangerousLogToVisitorSession,p.Uc,p.Tc,f)),zt=!1}catch(t){bm(t),d()}k--;k||c()}}(g);
try{ar(b,l,g.batchRequest,Ut(e,g.dangerousLogToVisitorSession,g.Uc,g.Tc,f)),zt=!1}catch(p){bm(p),d()}}}
function Ut(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,networklessOptions:a,dangerousLogToVisitorSession:b,uh:!!e,headers:{},postBodyFormat:"",postBody:"",compress:T("compress_gel")||T("compress_gel_lr")};Vt()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(V())));return a}
function St(a,b,c){Vt()||(a.requestTimeMs=String(b));T("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=S("EVENT_ID"))&&((c=S("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*65535/2)),c++,c>65535&&(c=1),Xl("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Rt(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Et(){var a;(a=F("yt.logging.transport.enableScrapingForTest"))||(a=wm("il_payload_scraping"),a=(a!==void 0?String(a):"")!=="enable_il_payload_scraping");a||(ht=[],E("yt.logging.transport.enableScrapingForTest",!0),E("yt.logging.transport.scrapedPayloadsForTesting",ht),E("yt.logging.transport.payloadToScrape","visualElementShown visualElementHidden visualElementAttached screenCreated visualElementGestured visualElementStateChanged".split(" ")),E("yt.logging.transport.getScrapedPayloadFromClientEventsFunction"),
E("yt.logging.transport.scrapeClientEvent",!0))}
function Vt(){return T("use_request_time_ms_header")||T("lr_use_request_time_ms_header")}
function Mt(a,b){return T("transport_use_scheduler")===!1?tm(a,b):T("logging_avoid_blocking_during_navigation")||T("lr_logging_avoid_blocking_during_navigation")?Bn(function(){if(gt().currentState==="none")a();else{var c={};gt().install((c.none={callback:a},c))}},b):Bn(a,b)}
function Pt(a){T("transport_use_scheduler")?Gj.qa(a):window.clearTimeout(a)}
function Tt(a){var b,c,d,e,f,g,h,k,l,m;return B(function(n){return n.h==1?(d=(b=a)==null?void 0:(c=b.responseContext)==null?void 0:c.globalConfigGroup,e=nt(d,zl),g=(f=d)==null?void 0:f.hotHashData,h=nt(d,yl),l=(k=d)==null?void 0:k.coldHashData,(m=Os().resolve(Is($p)))?g?e?n.yield(bq(m,g,e),2):n.yield(bq(m,g),2):n.A(2):n.return()):l?h?n.yield(cq(m,l,h),0):n.yield(cq(m,l),0):n.A(0)})}
function Lt(a,b){b=b===void 0?200:b;return a?b===300?wt:ut:b===300?vt:tt}
function Gt(a){a=Object.keys(a);a=y(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,wr[b])return b}
function Ht(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var Wt=D.ytLoggingGelSequenceIdObj_||{};E("ytLoggingGelSequenceIdObj_",Wt);
function Xt(a,b,c,d){d=d===void 0?{}:d;var e={},f=Math.round(d.timestamp||V());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=us();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!T("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,Wt[b]=b in Wt?Wt[b]+1:0,a.sequence={index:Wt[b],groupKey:b},d.endOfSequence&&delete Wt[d.sequenceGroup]);(d.sendIsolatedPayload?It:Dt)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function qo(a,b,c){c=c===void 0?{}:c;var d=Zr;S("ytLoggingEventsDefaultDisabled",!1)&&Zr===Zr&&(d=null);Xt(a,b,d,c)}
;function Yt(a){return a.slice(0,void 0).map(function(b){return b.name}).join(" > ")}
;var Zt=new Set,$t=0,au=0,bu=0,cu=[],du=[],eu=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function po(a){fu(a)}
function W(a){fu(a,"WARNING")}
function gu(a){a instanceof Error?fu(a):(a=Oa(a)?JSON.stringify(a):String(a),a=new U(a),a.name="RejectedPromiseError",W(a))}
function fu(a,b,c,d,e,f,g,h){f=f===void 0?{}:f;f.name=c||S("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||S("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),T("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!($t>=5))){d=[];e=y(du);for(f=e.next();!f.done;f=e.next()){f=f.value;try{f()&&d.push(f())}catch(A){}}d=[].concat(z(cu),z(d));var k=Vb(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var m=l.split("\n");m.shift();l=m.join("\n")}m=k.lineNumber||"Not available";k=k.fileName||"Not available";var n=0;if(a.hasOwnProperty("args")&&
a.args&&a.args.length)for(var p=0;p<a.args.length&&!(n=Ym(a.args[p],"params."+p,c,n),n>=500);p++);else if(a.hasOwnProperty("params")&&a.params){var t=a.params;if(typeof a.params==="object")for(p in t){if(t[p]){var v="params."+p,x=$m(t[p]);c[v]=x;n+=v.length+x.length;if(n>500)break}}else c.params=$m(t)}if(d.length)for(p=0;p<d.length&&!(n=Ym(d[p],"params.context."+p,c,n),n>=500);p++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);p={message:e,name:f,lineNumber:m,
fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(p.lineNumber=p.lineNumber+":"+c);if(a.level==="IGNORED")a=0;else a:{a=Um();c=y(a.Ya);for(d=c.next();!d.done;d=c.next())if(d=d.value,p.message&&p.message.match(d.Mh)){a=d.weight;break a}a=y(a.Ta);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(p)){a=c.weight;break a}a=1}p.sampleWeight=a;a=y(Pm);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.xc[p.name])for(e=y(c.xc[p.name]),d=e.next();!d.done;d=e.next())if(f=
d.value,d=p.message.match(f.regexp)){p.params["params.error.original"]=d[0];e=f.groups;f={};for(m=0;m<e.length;m++)f[e[m]]=d[m+1],p.params["params.error."+e[m]]=d[m+1];p.message=c.Qc(f);break}p.params||(p.params={});a=Um();p.params["params.errorServiceSignature"]="msg="+a.Ya.length+"&cb="+a.Ta.length;p.params["params.serviceWorker"]="false";D.document&&D.document.querySelectorAll&&(p.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));(new rg(sg,"sample")).constructor!==
rg&&(p.params["params.fconst"]="true");window.yterr&&typeof window.yterr==="function"&&window.yterr(p);if(p.sampleWeight!==0&&!Zt.has(p.message)){if(g&&T("web_enable_error_204"))hu(b===void 0?"ERROR":b,p);else{b=b===void 0?"ERROR":b;b==="ERROR"?(Vm.sb("handleError",p),T("record_app_crashed_web")&&bu===0&&p.sampleWeight===1&&(bu++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},T("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:p.message}}}}),qo("appCrashed",
g)),au++):b==="WARNING"&&Vm.sb("handleWarning",p);if(T("kevlar_gel_error_routing")){g=b;h=h===void 0?{}:h;b:{a=y(eu);for(c=a.next();!c.done;c=a.next())if(wo(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:p.stack};p.fileName&&(c.filename=p.fileName);a=p.lineNumber&&p.lineNumber.split?p.lineNumber.split(":"):[];a.length!==0&&(a.length!==1||isNaN(Number(a[0]))?a.length!==2||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=
Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:p.message,errorClassName:p.name,sampleWeight:p.sampleWeight};g==="ERROR"?a.level="ERROR_LEVEL_ERROR":g==="WARNING"&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];S("FEXP_EXPERIMENTS")&&(h.experimentIds=S("FEXP_EXPERIMENTS"));d=S("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Yl("web_disable_gel_stp_ecatcher_killswitch")&&d)for(e=y(Object.keys(d)),f=e.next();!f.done;f=e.next())f=
f.value,h.kvPairs.push({key:f,value:String(d[f])});if(d=p.params)for(e=y(Object.keys(d)),f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:"client."+f,value:String(d[f])});d=S("SERVER_NAME");e=S("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&(qo("clientError",h),(g==="ERROR"||T("errors_flush_gel_always_killswitch"))&&Kt(void 0,void 0,!1))}T("suppress_error_204_logging")||
hu(b,p)}try{Zt.add(p.message)}catch(A){}$t++}}}
function hu(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:S("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=y(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=S("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=y(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];(c=S("LAVA_VERSION"))&&(a.postParams["lava.version"]=c);c=S("SERVER_NAME");b=S("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}Gm(S("ECATCHER_REPORT_HOST","")+"/error_204",a)}
function iu(a){var b=C.apply(1,arguments);a.args||(a.args=[]);Array.isArray(a.args)&&a.args.push.apply(a.args,z(b))}
;function ju(){this.register=new Map}
function ku(a){a=y(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Qh("ABORTED")}
ju.prototype.clear=function(){ku(this);this.register.clear()};
var lu=new ju;var mu=Date.now().toString();
function nu(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;a<16;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(Math.random()*256)}if(mu)for(a=1,b=0;b<mu.length;b++)d[a%16]^=d[(a-1)%16]/4^mu.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var ou,pu=D.ytLoggingDocDocumentNonce_;pu||(pu=nu(),E("ytLoggingDocDocumentNonce_",pu));ou=pu;function qu(a){this.h=a}
r=qu.prototype;r.getAsJson=function(){var a={};this.h.trackingParams!==void 0?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,this.h.veCounter!==void 0&&(a.veCounter=this.h.veCounter),this.h.elementIndex!==void 0&&(a.elementIndex=this.h.elementIndex));this.h.dataElement!==void 0&&(a.dataElement=this.h.dataElement.getAsJson());this.h.youtubeData!==void 0&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
r.getAsJspb=function(){var a=new Bl;this.h.trackingParams!==void 0?a.setTrackingParams(this.h.trackingParams):(this.h.veType!==void 0&&jf(a,2,Ge(this.h.veType)),this.h.veCounter!==void 0&&jf(a,6,Ge(this.h.veCounter)),this.h.elementIndex!==void 0&&jf(a,3,Ge(this.h.elementIndex)),this.h.isCounterfactual&&jf(a,5,Ce(!0)));if(this.h.dataElement!==void 0){var b=this.h.dataElement.getAsJspb();uf(a,Bl,7,b)}this.h.youtubeData!==void 0&&uf(a,Al,8,this.h.jspbYoutubeData);return a};
r.toString=function(){return JSON.stringify(this.getAsJson())};
r.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
r.getLoggingDirectives=function(){return this.h.loggingDirectives};function ru(a){return S("client-screen-nonce-store",{})[a===void 0?0:a]}
function su(a,b){b=b===void 0?0:b;var c=S("client-screen-nonce-store");c||(c={},Xl("client-screen-nonce-store",c));c[b]=a}
function tu(a){a=a===void 0?0:a;return a===0?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function uu(a){return S(tu(a===void 0?0:a))}
E("yt_logging_screen.getRootVeType",uu);function vu(){var a=S("csn-to-ctt-auth-info");a||(a={},Xl("csn-to-ctt-auth-info",a));return a}
function wu(){return Object.values(S("client-screen-nonce-store",{})).filter(function(a){return a!==void 0})}
function xu(a){a=ru(a===void 0?0:a);if(!a&&!S("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
E("yt_logging_screen.getCurrentCsn",xu);function yu(a,b,c){var d=vu();(c=xu(c))&&delete d[c];b&&(d[a]=b)}
function zu(a){return vu()[a]}
E("yt_logging_screen.getCttAuthInfo",zu);E("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=c===void 0?0:c;if(a!==ru(c)||b!==S(tu(c)))if(yu(a,d,c),su(a,c),Xl(tu(c),b),b=function(){setTimeout(function(){a&&qo("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:ou,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});function Au(){var a=ng(Bu),b;return(new fi(function(c,d){a.onSuccess=function(e){sm(e)?c(new Cu(e)):d(new Du("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Du("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Du("Request timed out","net.timeout",e))};
b=Gm("//googleads.g.doubleclick.net/pagead/id",a)})).Fc(function(c){if(c instanceof oi){var d;
(d=b)==null||d.abort()}return ki(c)})}
function Du(a,b,c){bb.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
w(Du,bb);function Cu(a){this.xhr=a}
;function Eu(){this.X=0;this.h=null}
Eu.prototype.then=function(a,b,c){return this.X===1&&a?(a=a.call(c,this.h))&&typeof a.then==="function"?a:Fu(a):this.X===2&&b?(a=b.call(c,this.h))&&typeof a.then==="function"?a:Gu(a):this};
Eu.prototype.getValue=function(){return this.h};
Eu.prototype.isRejected=function(){return this.X==2};
Eu.prototype.$goog_Thenable=!0;function Gu(a){var b=new Eu;a=a===void 0?null:a;b.X=2;b.h=a===void 0?null:a;return b}
function Fu(a){var b=new Eu;a=a===void 0?null:a;b.X=1;b.h=a===void 0?null:a;return b}
;function Hu(a){var b=S("INNERTUBE_HOST_OVERRIDE");b&&(a=String(b)+String(dc(a)));return a}
function Iu(a){var b={};T("json_condensed_response")&&(b.prettyPrint="false");return a=mm(a,b||{},!1)}
function Ju(a,b){var c=c===void 0?{}:c;a={method:b===void 0?"POST":b,mode:nm(a)?"same-origin":"cors",credentials:nm(a)?"same-origin":"include"};b={};for(var d=y(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);Object.keys(b).length>0&&(a.headers=b);return a}
;function Ku(){return Xf()||(kd||ld)&&wo("applewebkit")&&!wo("version")&&(!wo("safari")||wo("gsa/"))||jd&&wo("version/")?!0:S("EOM_VISITOR_DATA")?!1:!0}
;function Lu(a){var b=a.docid||a.video_id||a.videoId||a.id;if(b)return b;b=a.raw_player_response;b||(a=a.player_response)&&(b=JSON.parse(a));return b&&b.videoDetails&&b.videoDetails.videoId||null}
;function Mu(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in Fl)if(Fl[d]==c.embeddedPlayerMode){b=Fl[d];break b}}return b==="EMBEDDED_PLAYER_MODE_PFL"}
;function Nu(a){bb.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Ou;this.isTimeout=a instanceof Du&&a.errorCode=="net.timeout";this.isCanceled=a instanceof oi}
w(Nu,bb);Nu.prototype.name="BiscottiError";function Ou(){bb.call(this,"Biscotti ID is missing from server")}
w(Ou,bb);Ou.prototype.name="BiscottiMissingError";var Bu={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Pu=null;function Qu(){if(T("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!Ku())return Error("User has not consented - not fetching biscotti id.");var a=S("PLAYER_VARS",{});if(lg(a)=="1")return Error("Biscotti ID is not available in private embed mode");if(Mu(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Ql(){var a=Qu();if(a!==void 0)return ki(a);Pu||(Pu=Au().then(Ru).Fc(function(b){return Su(2,b)}));
return Pu}
function Ru(a){a=a.xhr.responseText;if(a.lastIndexOf(")]}'",0)!=0)throw new Ou;a=JSON.parse(a.substr(4));if((a.type||1)>1)throw new Ou;a=a.id;Rl(a);Pu=Fu(a);Tu(18E5,2);return a}
function Su(a,b){b=new Nu(b);Rl("");Pu=Gu(b);a>0&&Tu(12E4,a-1);throw b;}
function Tu(a,b){tm(function(){Au().then(Ru,function(c){return Su(b,c)}).Fc(di)},a)}
function Uu(){try{var a=F("yt.ads.biscotti.getId_");return a?a():Ql()}catch(b){return ki(b)}}
;var Hb=qa(["data-"]);function Vu(a){a&&(a.dataset?a.dataset[Wu()]="true":Ib(a))}
function Xu(a){return a?a.dataset?a.dataset[Wu()]:a.getAttribute("data-loaded"):null}
var Yu={};function Wu(){return Yu.loaded||(Yu.loaded="loaded".replace(/\-([a-z])/g,function(a,b){return b.toUpperCase()}))}
;function Zu(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||ng(b);this.assets=a.assets||{};this.attrs=a.attrs||ng(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Zu.prototype.clone=function(){var a=new Zu,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];Ma(c)=="object"?a[b]=ng(c):a[b]=c}return a};var $u=["att/get"],av=["share/get_share_panel"],bv=["share/get_web_player_share_panel"],cv=["feedback"],dv=["notification/modify_channel_preference"],ev=["browse/edit_playlist"],fv=["subscription/subscribe"],gv=["subscription/unsubscribe"];var hv=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};E("yt.msgs_",hv);function iv(a){Sl(hv,arguments)}
;function jv(a,b,c){kv(a,b,c===void 0?null:c)}
function lv(a){a=mv(a);var b=document.getElementById(a);b&&(Ds(a),b.parentNode.removeChild(b))}
function nv(a,b){a&&b&&(a=""+Ra(b),(a=ov[a])&&Bs(a))}
function kv(a,b,c){c=c===void 0?null:c;var d=mv(a),e=document.getElementById(d),f=e&&Xu(e),g=e&&!f;f?b&&b():(b&&(f=zs(d,b),b=""+Ra(b),ov[b]=f),g||(e=pv(a,d,function(){Xu(e)||(Vu(e),Cs(d),tm(function(){Ds(d)},0))},c)))}
function pv(a,b,c,d){d=d===void 0?null:d;var e=ug("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Fb(e,wl(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function mv(a){var b=document.createElement("a");wb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+Zb(a)}
var ov={};function qv(a){var b=rv(a),c=document.getElementById(b),d=c&&Xu(c);d||c&&!d||(c=sv(a,b,function(){if(!Xu(c)){Vu(c);Cs(b);var e=Xa(Ds,b);tm(e,0)}}))}
function sv(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=wl(a);Kb(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function rv(a){var b=ug("A");wb(b,new pb(a));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+Zb(a)}
;function tv(a){var b=C.apply(1,arguments);if(!uv(a)||b.some(function(d){return!uv(d)}))throw Error("Only objects may be merged.");
b=y(b);for(var c=b.next();!c.done;c=b.next())vv(a,c.value)}
function vv(a,b){for(var c in b)if(uv(b[c])){if(c in a&&!uv(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});vv(a[c],b[c])}else if(wv(b[c])){if(c in a&&!wv(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);xv(a[c],b[c])}else a[c]=b[c];return a}
function xv(a,b){b=y(b);for(var c=b.next();!c.done;c=b.next())c=c.value,uv(c)?a.push(vv({},c)):wv(c)?a.push(xv([],c)):a.push(c);return a}
function uv(a){return typeof a==="object"&&!Array.isArray(a)}
function wv(a){return typeof a==="object"&&Array.isArray(a)}
;var yv="absolute_experiments app conditional_experiments debugcss debugjs expflag forced_experiments pbj pbjreload sbb spf spfreload sr_bns_address sttick".split(" ");
function zv(a,b){var c=c===void 0?!0:c;var d=S("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=cc(window.location.href);e&&d.push(e);e=cc(a);if(Lb(d,e)>=0||!e&&a.lastIndexOf("/",0)==0)if(d=document.createElement("a"),wb(d,a),a=d.href)if(a=dc(a),a=ec(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:xu()},b)),f){var f=parseInt(f,10);isFinite(f)&&f>0&&Av(a,b,f)}else Av(a,b)}
function Av(a,b,c){a=Bv(a);b=b?hc(b):"";c=c||5;Ku()&&gn(a,b,c)}
function Bv(a){for(var b=y(yv),c=b.next();!c.done;c=b.next())a=mc(a,c.value);return"ST-"+Zb(a).toString(36)}
;function Cv(a){mq.call(this,1,arguments);this.csn=a}
w(Cv,mq);var vq=new nq("screen-created",Cv),Dv=[],Ev=0,Fv=new Map,Gv=new Map,Hv=new Map;
function Iv(a,b,c,d,e){e=e===void 0?!1:e;for(var f=Jv({cttAuthInfo:zu(b)||void 0},b),g=y(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(jg(k)||!k.trackingParams&&!k.veType)&&W(Error("Child VE logged with no data"));if(T("no_client_ve_attach_unless_shown")){var l=Kv(h,b);if(k.veType&&!Gv.has(l)&&!Hv.has(l)&&!e){if(!T("il_attach_cache_limit")||Fv.size<1E3){Fv.set(l,[a,b,c,h]);return}T("il_attach_cache_limit")&&Fv.size>1E3&&W(new U("IL Attach cache exceeded limit"))}h=Kv(c,b);Fv.has(h)?
Lv(c,b):Hv.set(h,!0)}}d=d.filter(function(m){m.csn!==b?(m.csn=b,m=!0):m=!1;return m});
c={csn:b,parentVe:c.getAsJson(),childVes:Pb(d,function(m){return m.getAsJson()})};
b==="UNDEFINED_CSN"?Mv("visualElementAttached",f,c):a?Xt("visualElementAttached",c,a,f):qo("visualElementAttached",c,f)}
function Mv(a,b,c){Dv.push({Se:a,payload:c,Hh:void 0,options:b});Ev||(Ev=wq())}
function xq(a){if(Dv){for(var b=y(Dv),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,qo(c.Se,c.payload,c.options));Dv.length=0}Ev=0}
function Kv(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function Lv(a,b){a=Kv(a,b);Fv.has(a)&&(b=Fv.get(a)||[],Iv(b[0],b[1],b[2],[b[3]],!0),Fv.delete(a))}
function Jv(a,b){T("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function Nv(){try{return!!self.localStorage}catch(a){return!1}}
;function Ov(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Pv(a){if(Nv()){var b=Object.keys(window.localStorage);b=y(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Ov(c);d===void 0||a.includes(d)||self.localStorage.removeItem(c)}}}
function Qv(){if(!Nv())return!1;var a=zn(),b=Object.keys(window.localStorage);b=y(b);for(var c=b.next();!c.done;c=b.next())if(c=Ov(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Rv(){var a=!1;try{a=!!window.sessionStorage.getItem("session_logininfo")}catch(b){a=!0}return(S("INNERTUBE_CLIENT_NAME")==="WEB"||S("INNERTUBE_CLIENT_NAME")==="WEB_CREATOR")&&a}
function Sv(a){if(S("LOGGED_IN",!0)&&Rv()){var b=S("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=cc(window.location.href);c&&b.push(c);c=cc(a);Lb(b,c)>=0||!c&&a.lastIndexOf("/",0)==0?(b=dc(a),(b=ec(b))?(b=Bv(b),b=(b=hn(b)||null)?jm(b):{}):b=null):b=null;b==null&&(b={});c=b;var d=void 0;Rv()?(d||(d=S("LOGIN_INFO")),d?(c.session_logininfo=d,c=!0):c=!1):c=!1;c&&zv(a,b)}}
;function Tv(a,b,c){b=b===void 0?{}:b;c=c===void 0?!1:c;var d=S("EVENT_ID");d&&(b.ei||(b.ei=d));b&&zv(a,b);if(c)return!1;Sv(a);var e=e===void 0?{}:e;var f=f===void 0?"":f;var g=g===void 0?window:g;b=ic(a,e);Sv(b);a=void 0;a=a===void 0?tb:a;a:if(f=b+f,a=a===void 0?tb:a,!(f instanceof pb)){for(b=0;b<a.length;++b)if(c=a[b],c instanceof rb&&c.Fe(f)){f=new pb(f);break a}f=void 0}g=g.location;f=vb(f||qb);f!==void 0&&(g.href=f);return!0}
;function Uv(a){if(lg(S("PLAYER_VARS",{}))!="1"){a&&Pl();try{Uu().then(function(){},function(){}),tm(Uv,18E5)}catch(b){bm(b)}}}
;var Vv=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Wv(){var a=a===void 0?window.location.href:a;if(T("kevlar_disable_theme_param"))return null;var b=ac(bc(5,a));if(T("enable_dark_theme_only_on_shorts")&&b!=null&&b.startsWith("/shorts/"))return"USER_INTERFACE_THEME_DARK";try{var c=km(a).theme;return Vv.get(c)||null}catch(d){}return null}
;function Xv(){this.h={};if(this.i=kn()){var a=hn("CONSISTENCY");a&&Yv(this,{encryptedTokenJarContents:a})}}
Xv.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=((c=b.Ga.context)==null?void 0:(d=c.request)==null?void 0:d.consistencyTokenJars)||[];var e;if(a=(e=a.responseContext)==null?void 0:e.consistencyTokenJar){e=y(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];Yv(this,a)}};
function Yv(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,typeof b.expirationSeconds==="string")){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},c*1E3);
a.i&&gn("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Zv=window.location.hostname.split(".").slice(-2).join(".");function $v(){this.j=-1;var a=S("LOCATION_PLAYABILITY_TOKEN");S("INNERTUBE_CLIENT_NAME")==="TVHTML5"&&(this.h=aw(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var bw;function cw(){bw=F("yt.clientLocationService.instance");bw||(bw=new $v,E("yt.clientLocationService.instance",bw));return bw}
r=$v.prototype;
r.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});if(this.i)a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(this.i.coords.latitude*1E7),a.client.locationInfo.longitudeE7=Math.floor(this.i.coords.longitude*1E7),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0;else if(this.o||this.locationPlayabilityToken)a.client.locationPlayabilityToken=this.o||
this.locationPlayabilityToken};
r.handleResponse=function(a){var b;a=(b=a.responseContext)==null?void 0:b.locationPlayabilityToken;a!==void 0&&(this.locationPlayabilityToken=a,this.i=void 0,S("INNERTUBE_CLIENT_NAME")==="TVHTML5"?(this.h=aw(this))&&this.h.set("yt-location-playability-token",a,15552E3):gn("YT_CL",JSON.stringify({loctok:a}),15552E3,Zv,!0))};
function aw(a){return a.h===void 0?new ho("yt-client-location"):a.h}
r.clearLocationPlayabilityToken=function(a){a==="TVHTML5"?(this.h=aw(this))&&this.h.remove("yt-location-playability-token"):jn("YT_CL");this.o=void 0;this.j!==-1&&(clearTimeout(this.j),this.j=-1)};
r.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;S("INNERTUBE_CLIENT_NAME")==="MWEB"&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
r.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);if(a==null?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};
r.createLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);return b};function dw(a,b,c){b=b===void 0?!1:b;c=c===void 0?!1:c;var d=S("INNERTUBE_CONTEXT");if(!d)return fu(Error("Error: No InnerTubeContext shell provided in ytconfig.")),{};d=og(d);T("web_no_tracking_params_in_shell_killswitch")||delete d.clickTracking;d.client||(d.client={});var e=d.client;e.clientName==="MWEB"&&e.clientFormFactor!=="AUTOMOTIVE_FORM_FACTOR"&&(e.clientFormFactor=S("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");e.screenWidthPoints=window.innerWidth;e.screenHeightPoints=window.innerHeight;
e.screenPixelDensity=Math.round(window.devicePixelRatio||1);e.screenDensityFloat=window.devicePixelRatio||1;e.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var f=f===void 0?!1:f;on();var g="USER_INTERFACE_THEME_LIGHT";rn(165)?g="USER_INTERFACE_THEME_DARK":rn(174)?g="USER_INTERFACE_THEME_LIGHT":!T("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(g="USER_INTERFACE_THEME_DARK");
f=f?g:Wv()||g;e.userInterfaceTheme=f;if(!b){if(f=wn())e.connectionType=f;T("web_log_effective_connection_type")&&(f=xn())&&(d.client.effectiveConnectionType=f)}var h;if(T("web_log_memory_total_kbytes")&&((h=D.navigator)==null?0:h.deviceMemory)){var k;h=(k=D.navigator)==null?void 0:k.deviceMemory;d.client.memoryTotalKbytes=""+h*1E6}T("web_gcf_hashes_innertube")&&(f=dq())&&(k=f.coldConfigData,h=f.coldHashData,f=f.hotHashData,d.client.configInfo=d.client.configInfo||{},k&&(d.client.configInfo.coldConfigData=
k),h&&(d.client.configInfo.coldHashData=h),f&&(d.client.configInfo.hotHashData=f));k=km(D.location.href);!T("web_populate_internal_geo_killswitch")&&k.internalcountrycode&&(e.internalGeo=k.internalcountrycode);e.clientName==="MWEB"||e.clientName==="WEB"?(e.mainAppWebInfo={graftUrl:D.location.href},T("kevlar_woffle")&&an.instance&&(k=an.instance,e.mainAppWebInfo.pwaInstallabilityStatus=!k.h&&k.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),e.mainAppWebInfo.webDisplayMode=
bn(),e.mainAppWebInfo.isWebNativeShareAvailable=navigator&&navigator.share!==void 0):e.clientName==="TVHTML5"&&(!T("web_lr_app_quality_killswitch")&&(k=S("LIVING_ROOM_APP_QUALITY"))&&(e.tvAppInfo=Object.assign(e.tvAppInfo||{},{appQuality:k})),k=S("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(e.tvAppInfo=Object.assign(e.tvAppInfo||{},{certificationScope:k}));if(!T("web_populate_time_zone_itc_killswitch")){a:{if(typeof Intl!=="undefined")try{var l=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break a}catch(Pa){}l=
void 0}l&&(e.timeZone=l)}(l=S("EXPERIMENTS_TOKEN",""))?e.experimentsToken=l:delete e.experimentsToken;l=ym();Xv.instance||(Xv.instance=new Xv);e=Xv.instance.h;k=[];h=0;for(var m in e)k[h++]=e[m];d.request=Object.assign({},d.request,{internalExperimentFlags:l,consistencyTokenJars:k});!T("web_prequest_context_killswitch")&&(m=S("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(d.request.externalPrequestContext=m);l=on();m=rn(58);l=l.get("gsml","");d.user=Object.assign({},d.user);m&&(d.user.enableSafetyMode=
m);l&&(d.user.lockedSafetyMode=!0);T("warm_op_csn_cleanup")?c&&(b=xu())&&(d.clientScreenNonce=b):!b&&(b=xu())&&(d.clientScreenNonce=b);a&&(d.clickTracking={clickTrackingParams:a});if(a=F("yt.mdx.remote.remoteClient_"))d.remoteClient=a;cw().setLocationOnInnerTubeContext(d);try{var n=om(),p=n.bid;delete n.bid;d.adSignalsInfo={params:[],bid:p};for(var t=y(Object.entries(n)),v=t.next();!v.done;v=t.next()){var x=y(v.value),A=x.next().value,H=x.next().value;n=A;p=H;a=void 0;(a=d.adSignalsInfo.params)==
null||a.push({key:n,value:""+p})}var K,aa;if(((K=d.client)==null?void 0:K.clientName)==="TVHTML5"||((aa=d.client)==null?void 0:aa.clientName)==="TVHTML5_UNPLUGGED"){var da=S("INNERTUBE_CONTEXT");da.adSignalsInfo&&(d.adSignalsInfo.advertisingId=da.adSignalsInfo.advertisingId,d.adSignalsInfo.advertisingIdSignalType="DEVICE_ID_TYPE_CONNECTED_TV_IFA",d.adSignalsInfo.limitAdTracking=da.adSignalsInfo.limitAdTracking)}}catch(Pa){fu(Pa)}return d}
;function ew(a){var b={"Content-Type":"application/json"};S("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=S("EOM_VISITOR_DATA"):S("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=S("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=S("LOGGED_IN",!1);S("DEBUG_SETTINGS_METADATA")&&(b["X-Debug-Settings-Metadata"]=S("DEBUG_SETTINGS_METADATA"));a!=="cors"&&((a=S("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=S("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=S("CHROME_CONNECTED_HEADER"))&&
(b["X-Youtube-Chrome-Connected"]=a),(a=S("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a),S("ENABLE_LAVA_HEADER_ON_IT_EXPANSION")&&(a=S("SERIALIZED_LAVA_DEVICE_CONTEXT"))&&(b["X-YouTube-Lava-Device-Context"]=a));return b}
;function fw(){this.h={}}
fw.prototype.contains=function(a){return Object.prototype.hasOwnProperty.call(this.h,a)};
fw.prototype.get=function(a){if(this.contains(a))return this.h[a]};
fw.prototype.set=function(a,b){this.h[a]=b};
fw.prototype.remove=function(a){delete this.h[a]};function gw(){this.mappings=new fw}
gw.prototype.getModuleId=function(a){return a.serviceId.getModuleId()};
gw.prototype.get=function(a){a:{var b=this.mappings.get(a.toString());switch(b.type){case "mapping":a=b.value;break a;case "factory":b=b.value();this.mappings.set(a.toString(),{type:"mapping",value:b});a=b;break a;default:a=xb(b)}}return a};
new gw;function hw(a){return function(){return new a}}
;var iw={},jw=(iw.WEB_UNPLUGGED="^unplugged/",iw.WEB_UNPLUGGED_ONBOARDING="^unplugged/",iw.WEB_UNPLUGGED_OPS="^unplugged/",iw.WEB_UNPLUGGED_PUBLIC="^unplugged/",iw.WEB_CREATOR="^creator/",iw.WEB_KIDS="^kids/",iw.WEB_EXPERIMENTS="^experiments/",iw.WEB_MUSIC="^music/",iw.WEB_REMIX="^music/",iw.WEB_MUSIC_EMBEDDED_PLAYER="^music/",iw.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",iw);
function kw(a){var b=b===void 0?"UNKNOWN_INTERFACE":b;if(a.length===1)return a[0];var c=jw[b];if(c){c=new RegExp(c);for(var d=y(a),e=d.next();!e.done;e=d.next())if(e=e.value,c.exec(e))return e}var f=[];Object.entries(jw).forEach(function(g){var h=y(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
c=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
d=y(a);for(e=d.next();!e.done;e=d.next())if(e=e.value,!c.exec(e))return e;return a[0]}
;function lw(){}
lw.prototype.u=function(a,b,c){b=b===void 0?{}:b;c=c===void 0?fn:c;var d={context:dw(a.clickTrackingParams,!1,this.o)};var e=this.i(a);if(e){this.h(d,e,b);var f;b="/youtubei/v1/"+kw(this.j());(e=(f=nt(a.commandMetadata,Dl))==null?void 0:f.apiUrl)&&(b=e);f=Iu(Hu(b));a=Object.assign({},{command:a},void 0);d={input:f,Za:Ju(f),Ga:d,config:a};d.config.Ob?d.config.Ob.identity=c:d.config.Ob={identity:c};return d}fu(new U("Error: Failed to create Request from Command.",a))};
fa.Object.defineProperties(lw.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!1}}});
function mw(){}
w(mw,lw);function nw(){}
w(nw,mw);nw.prototype.u=function(){return{input:"/getDatasyncIdsEndpoint",Za:Ju("/getDatasyncIdsEndpoint","GET"),Ga:{}}};
nw.prototype.j=function(){return[]};
nw.prototype.i=function(){};
nw.prototype.h=function(){};var ow={},pw=(ow.GET_DATASYNC_IDS=hw(nw),ow);function qw(a){var b;(b=F("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},E("ytcsi."+(a||"")+"data_",b));return b}
function rw(){var a=qw();a.info||(a.info={});return a.info}
function sw(a){a=qw(a);a.metadata||(a.metadata={});return a.metadata}
function tw(a){a=qw(a);a.tick||(a.tick={});return a.tick}
function uw(a){a=qw(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function vw(a){a=uw(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function ww(a){var b=qw(a).nonce;b||(b=nu(),qw(a).nonce=b);return b}
;function xw(){var a=F("ytcsi.debug");a||(a=[],E("ytcsi.debug",a),E("ytcsi.reference",{}));return a}
function yw(a){a=a||"";var b=F("ytcsi.reference");b||(xw(),b=F("ytcsi.reference"));if(b[a])return b[a];var c=xw(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var X={},zw=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X.app_startup="LATENCY_ACTION_APP_STARTUP",X.browse="LATENCY_ACTION_BROWSE",X.cast_splash="LATENCY_ACTION_CAST_SPLASH",X.channel_activity="LATENCY_ACTION_KIDS_CHANNEL_ACTIVITY",X.channels="LATENCY_ACTION_CHANNELS",X.chips="LATENCY_ACTION_CHIPS",X.commerce_transaction="LATENCY_ACTION_COMMERCE_TRANSACTION",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",X.editor=
"LATENCY_ACTION_EDITOR",X.embed="LATENCY_ACTION_EMBED",X.embed_no_video="LATENCY_ACTION_EMBED_NO_VIDEO",X.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.favorites="LATENCY_ACTION_FAVORITES",X.home="LATENCY_ACTION_HOME",X.inboarding="LATENCY_ACTION_INBOARDING",X.landing="LATENCY_ACTION_LANDING",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",
X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",X.management="LATENCY_ACTION_MANAGEMENT",X.mini_app="LATENCY_ACTION_MINI_APP_PLAY",X.notification_settings="LATENCY_ACTION_KIDS_NOTIFICATION_SETTINGS",X.onboarding="LATENCY_ACTION_ONBOARDING",X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X.prebuffer=
"LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.projects="LATENCY_ACTION_PROJECTS",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X.red="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.premium="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.privacy_policy="LATENCY_ACTION_KIDS_PRIVACY_POLICY",X.review="LATENCY_ACTION_REVIEW",X.search_overview_answer="LATENCY_ACTION_SEARCH_OVERVIEW_ANSWER",
X.search_ui="LATENCY_ACTION_SEARCH_UI",X.search_suggest="LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.store="LATENCY_ACTION_STORE",X.supervision_dashboard="LATENCY_ACTION_KIDS_SUPERVISION_DASHBOARD",X.tenx="LATENCY_ACTION_TENX",X.video_preview="LATENCY_ACTION_VIDEO_PREVIEW",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",
X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",
X.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",X.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",X.attestation_challenge_fetch="LATENCY_ACTION_ATTESTATION_CHALLENGE_FETCH",X);function Aw(a,b){mq.call(this,1,arguments);this.timer=b}
w(Aw,mq);var Bw=new nq("aft-recorded",Aw);E("ytLoggingGelSequenceIdObj_",D.ytLoggingGelSequenceIdObj_||{});var Cw=D.ytLoggingLatencyUsageStats_||{};E("ytLoggingLatencyUsageStats_",Cw);function Dw(){this.h=0}
function Ew(){Dw.instance||(Dw.instance=new Dw);return Dw.instance}
Dw.prototype.tick=function(a,b,c,d){Fw(this,"tick_"+a+"_"+b)||qo("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
Dw.prototype.info=function(a,b,c){var d=Object.keys(a).join("");Fw(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,qo("latencyActionInfo",a,{cttAuthInfo:c}))};
Dw.prototype.jspbInfo=function(){};
Dw.prototype.span=function(a,b,c){var d=Object.keys(a).join("");Fw(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,qo("latencyActionSpan",a,{cttAuthInfo:c}))};
function Fw(a,b){Cw[b]=Cw[b]||{count:0};var c=Cw[b];c.count++;c.time=V();a.h||(a.h=Bn(function(){var d=V(),e;for(e in Cw)Cw[e]&&d-Cw[e].time>6E4&&delete Cw[e];a&&(a.h=0)},5E3));
return c.count>5?(c.count===6&&Math.random()*1E5<1&&(c=new U("CSI data exceeded logging limit with key",b.split("_")),b.indexOf("plev")>=0||W(c)),!0):!1}
;var Gw=window;function Hw(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function Iw(){var a;if(T("csi_use_performance_navigation_timing")||T("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=Y==null?void 0:(a=Y.getEntriesByType)==null?void 0:(b=a.call(Y,"navigation"))==null?void 0:(c=b[0])==null?void 0:(d=c.toJSON)==null?void 0:d.call(c);e?(e.requestStart=Jw(e.requestStart),e.responseEnd=Jw(e.responseEnd),e.redirectStart=Jw(e.redirectStart),e.redirectEnd=Jw(e.redirectEnd),e.domainLookupEnd=Jw(e.domainLookupEnd),e.connectStart=Jw(e.connectStart),e.connectEnd=
Jw(e.connectEnd),e.responseStart=Jw(e.responseStart),e.secureConnectionStart=Jw(e.secureConnectionStart),e.domainLookupStart=Jw(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=Y.timing}else a=T("csi_performance_timing_to_object")?JSON.parse(JSON.stringify(Y.timing)):Y.timing;return a}
function Jw(a){return Math.round(Kw()+a)}
function Kw(){return(T("csi_use_time_origin")||T("csi_use_time_origin_tvhtml5"))&&Y.timeOrigin?Math.floor(Y.timeOrigin):Y.timing.navigationStart}
var Y=Gw.performance||Gw.mozPerformance||Gw.msPerformance||Gw.webkitPerformance||new Hw;var Lw=!1,Mw=!1,Nw={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj",'script[name="embed_client"]':"ecj",'link[rel="stylesheet"][name="embed-ui"]':"ecc"};Wa(Y.clearResourceTimings||Y.webkitClearResourceTimings||Y.mozClearResourceTimings||Y.msClearResourceTimings||Y.oClearResourceTimings||di,Y);function Ow(a,b){if(!T("web_csi_action_sampling_enabled")||!qw(b).actionDisabled){var c=yw(b||"");tv(c.info,a);a.loadType&&(c=a.loadType,sw(b).loadType=c);tv(vw(b),a);c=ww(b);b=qw(b).cttAuthInfo;Ew().info(a,c,b)}}
function Pw(){var a,b,c,d;return((d=Os().resolve(Is($p))==null?void 0:(a=aq())==null?void 0:(b=a.loggingHotConfig)==null?void 0:(c=b.csiConfig)==null?void 0:c.debugTicks)!=null?d:[]).map(function(e){return Object.values(e)[0]})}
function Z(a,b,c){if(!T("web_csi_action_sampling_enabled")||!qw(c).actionDisabled){var d=ww(c),e;if(e=T("web_csi_debug_sample_enabled")&&d){(Os().resolve(Is($p))==null?0:aq())&&!Mw&&(Mw=!0,Z("gcfl",V(),c));var f,g,h;e=(Os().resolve(Is($p))==null?void 0:(f=aq())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.csiConfig)==null?void 0:h.debugSampleWeight)||0;if(f=e!==0)b:{f=Pw();if(f.length>0)for(g=0;g<f.length;g++)if(a===f[g]){f=!0;break b}f=!1}if(f){for(g=f=0;g<d.length;g++)f=f*31+d.charCodeAt(g),
g<d.length-1&&(f%=0x800000000000);e=f%1E5%e!==0;qw(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,Ow(f,c));qw(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){if(a[0]!=="_"&&(e=a,f=b,Y.mark))if(e.startsWith("mark_")||(e="mark_"+e),c&&(e+=" ("+c+")"),f===void 0||T("web_csi_disable_alt_time_performance_mark"))Y.mark(e);else{f=T("csi_use_performance_navigation_timing")||T("csi_use_performance_navigation_timing_tvhtml5")?f-Y.timeOrigin:f-(Y.timeOrigin||Y.timing.navigationStart);try{Y.mark(e,
{startTime:f})}catch(k){}}e=yw(c||"");e.tick[a]=b||V();if(e.callback&&e.callback[a])for(e=y(e.callback[a]),f=e.next();!f.done;f=e.next())f=f.value,f();e=uw(c);e.gelTicks&&(e.gelTicks[a]=!0);f=tw(c);e=b||V();T("log_repeated_ytcsi_ticks")?a in f||(f[a]=e):f[a]=e;f=qw(c).cttAuthInfo;a==="_start"?(a=Ew(),Fw(a,"baseline_"+d)||qo("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):Ew().tick(a,d,b,f);Qw(c);return e}}}
function Rw(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=as+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Sw(){function a(f,g,h){g=g.match("_rid")?g.split("_rid")[0]:g;typeof h==="number"&&(h=JSON.stringify(h));f.requestIds?f.requestIds.push({endpoint:g,id:h}):f.requestIds=[{endpoint:g,id:h}]}
for(var b={},c=y(Object.entries(S("TIMING_INFO",{}))),d=c.next();!d.done;d=c.next()){var e=y(d.value);d=e.next().value;e=e.next().value;switch(d){case "GetBrowse_rid":a(b,d,e);break;case "GetGuide_rid":a(b,d,e);break;case "GetHome_rid":a(b,d,e);break;case "GetPlayer_rid":a(b,d,e);break;case "GetSearch_rid":a(b,d,e);break;case "GetSettings_rid":a(b,d,e);break;case "GetTrending_rid":a(b,d,e);break;case "GetWatchNext_rid":a(b,d,e);break;case "yt_red":b.isRedSubscriber=!!e;break;case "yt_ad":b.isMonetized=
!!e}}return b}
function Tw(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;d==="SCRIPT"?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):d==="LINK"&&(c=a.href);Ab(document)&&a.setAttribute("nonce",Ab(document));return c?(a=Y.getEntriesByName(c))&&a[0]&&(a=a[0],c=Kw(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),a.transferSize!==void 0&&a.transferSize===0)?!0:!1:!1}
function Uw(){var a=window.location.protocol,b=Y.getEntriesByType("resource");b=Ob(b,function(c){return c.name.indexOf(a+"//fonts.gstatic.com/s/")===0});
(b=Qb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&b.startTime>0&&b.responseEnd>0&&(Z("wffs",Jw(b.startTime)),Z("wffe",Jw(b.responseEnd)))}
function Vw(a){var b=Ww("aft",a);if(b)return b;b=S((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Ww(b[d],a);if(e)return e}return NaN}
function Ww(a,b){if(a=tw(b)[a])return typeof a==="number"?a:a[a.length-1]}
function Qw(a){var b=Ww("_start",a),c=Vw(a),d=T("enable_cow_info_csi")||!Lw;b&&c&&d&&(sq(Bw,new Aw(Math.round(c-b),a)),Lw=!0)}
function Xw(){if(Y.getEntriesByType){var a=Y.getEntriesByType("paint");if(a=Rb(a,function(c){return c.name==="first-paint"}))return Jw(a.startTime)}var b;
T("csi_use_performance_navigation_timing")||T("csi_use_performance_navigation_timing_tvhtml5")?b=Y.getEntriesByType("first-paint")[0].startTime:b=Y.timing.Oh;return b?Math.max(0,b):0}
;function Yw(a,b){am(function(){yw("").info.actionType=a;b&&Xl("TIMING_AFT_KEYS",b);Xl("TIMING_ACTION",a);var c=Sw();Object.keys(c).length>0&&Ow(c);c={isNavigation:!0,actionType:zw[S("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};var d=S("PREVIOUS_ACTION");d&&(c.previousAction=zw[d]||"LATENCY_ACTION_UNKNOWN");if(d=S("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=S("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=xu())&&d!=="UNDEFINED_CSN"&&(c.clientScreenNonce=d);d=Rw();if(d===1||d===-1)c.isVisible=!0;sw();rw();
c.loadType="cold";d=rw();var e=Iw(),f=Kw(),g=S("CSI_START_TIMESTAMP_MILLIS",0);g>0&&!T("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(Z("srt",e.responseStart),d.prerender!==1&&Z("_start",f,void 0));d=Xw();d>0&&Z("fpt",d);d=Iw();d.isPerformanceNavigationTiming&&Ow({performanceNavigationTiming:!0},void 0);Z("nreqs",d.requestStart,void 0);Z("nress",d.responseStart,void 0);Z("nrese",d.responseEnd,void 0);d.redirectEnd-d.redirectStart>0&&(Z("nrs",d.redirectStart,void 0),Z("nre",d.redirectEnd,
void 0));d.domainLookupEnd-d.domainLookupStart>0&&(Z("ndnss",d.domainLookupStart,void 0),Z("ndnse",d.domainLookupEnd,void 0));d.connectEnd-d.connectStart>0&&(Z("ntcps",d.connectStart,void 0),Z("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=Kw()&&d.connectEnd-d.secureConnectionStart>0&&(Z("nstcps",d.secureConnectionStart,void 0),Z("ntcpe",d.connectEnd,void 0));Y&&"getEntriesByType"in Y&&Uw();d=[];if(document.querySelector&&Y&&Y.getEntriesByName)for(var h in Nw)Nw.hasOwnProperty(h)&&(e=Nw[h],
Tw(h,e)&&d.push(e));if(d.length>0)for(c.resourceInfo=[],h=y(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});Ow(c);c=uw();c.preLoggedGelInfos||(c.preLoggedGelInfos=[]);h=c.preLoggedGelInfos;c=vw();d=void 0;for(e=0;e<h.length;e++)if(f=h[e],f.loadType){d=f.loadType;break}if(sw().loadType==="cold"&&(c.loadType==="cold"||d==="cold")){d=tw();e=uw();e=e.gelTicks?e.gelTicks:e.gelTicks={};for(var k in d)if(!(k in e))if(typeof d[k]==="number")Z(k,Ww(k));else if(T("log_repeated_ytcsi_ticks"))for(f=
y(d[k]),g=f.next();!g.done;g=f.next())g=g.value,Z(k.slice(1),g);k={};d=!1;h=y(h);for(e=h.next();!e.done;e=h.next())d=e.value,tv(c,d),tv(k,d),d=!0;d&&Ow(k)}E("ytglobal.timingready_",!0);k=S("TIMING_ACTION");F("ytglobal.timingready_")&&k&&Zw()&&Vw()&&Qw()})()}
function Zw(a){return am(function(){return $w("_start",a)})()}
function ax(a,b,c){am(Ow)(a,b,c===void 0?!1:c)}
function bx(a,b,c){return am(Z)(a,b,c)}
function $w(a,b){return am(function(){var c=tw(b);return a in c})()}
function cx(a){if(!T("universal_csi_network_ticks"))return"";a=ac(bc(5,a))||"";for(var b=Object.keys(kq),c=0;c<b.length;c++){var d=b[c];if(a.includes(d))return d}return""}
function dx(a){if(!T("universal_csi_network_ticks"))return function(){};
var b=kq[a];return b?(ex(b),function(){var c=T("universal_csi_network_ticks")?(c=lq[a])?ex(c):!1:!1;return c}):function(){}}
function ex(a){return am(function(){if($w(a))return!1;bx(a,void 0,void 0);return!0})()}
function fx(a){am(function(){if(!Zw("attestation_challenge_fetch")||$w(a,"attestation_challenge_fetch"))return!1;bx(a,void 0,"attestation_challenge_fetch");return!0})()}
function gx(){am(function(){var a=ww();requestAnimationFrame(function(){setTimeout(function(){a===ww()&&bx("ol",void 0,void 0)},0)})})()}
var hx=window;hx.ytcsi&&(hx.ytcsi.infoGel=ax,hx.ytcsi.tick=bx);var ix="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD shorts_prefetch".split(" "),jx=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse","type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.PlayerResponse"];function kx(a,b,c,d){this.u=a;this.fa=b;this.j=c;this.o=d;this.i=void 0;this.h=new Map;a.Zb||(a.Zb={});a.Zb=Object.assign({},pw,a.Zb)}
function lx(a,b,c,d){if(kx.instance!==void 0){if(d=kx.instance,a=[a!==d.u,b!==d.fa,c!==d.j,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new U("InnerTubeTransportService is already initialized",a);
}else kx.instance=new kx(a,b,c,d)}
function mx(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=c===void 0?fn:c;var d=nx(a,b);return d?new fi(function(e,f){var g,h,k,l,m;return B(function(n){switch(n.h){case 1:return n.yield(d,2);case 2:g=n.i;h=g.u(b,void 0,c);if(!h){f(new U("Error: Failed to build request for command.",b));n.A(0);break}Sv(h.input);l=((k=h.Za)==null?void 0:k.mode)==="cors"?"cors":void 0;if(a.j.Kd){m=ox(h.config,l);n.A(4);break}return n.yield(px(h.config,l),5);case 5:m=n.i;case 4:e(qx(a,h,m)),n.h=
0}})}):ki(new U("Error: No request builder found for command.",b))}
function rx(a,b){function c(){}
var d="/youtubei/v1/"+kw($u);var e=e===void 0?{Ob:{identity:fn}}:e;var f=f===void 0?!0:f;c=dx(cx(d));b.context||(b.context=dw(void 0,f));return new fi(function(g){var h,k,l,m,n;return B(function(p){if(p.h==1)return h=Hu(d),k=nm(h)?"same-origin":"cors",a.j.Kd?(l=ox(e,k),p.A(2)):p.yield(px(e,k),3);p.h!=2&&(l=p.i);m=Iu(Hu(d));n={input:m,Za:Ju(m),Ga:b,config:e};g(qx(a,n,l,c));p.h=0})})}
function sx(a,b,c){var d;if(b&&!(b==null?0:(d=b.sequenceMetaData)==null?0:d.skipProcessing)&&a.o){d=y(ix);for(var e=d.next();!e.done;e=d.next())e=e.value,a.o[e]&&a.o[e].handleResponse(b,c)}}
function qx(a,b,c,d){d=d===void 0?function(){}:d;
var e,f,g,h,k,l,m,n,p,t,v,x,A,H,K,aa,da,Pa,Nb,Ya,yb,Za,Qa,Ia,Ha,fh,ks,ls,ms,ns;return B(function(ja){switch(ja.h){case 1:ja.A(2);break;case 3:if((e=ja.i)&&!e.isExpired())return ja.return(Promise.resolve(e.h()));case 2:if(!((f=b)==null?0:(g=f.Ga)==null?0:g.context)){ja.A(4);break}h=b.Ga.context;ja.A(5);break;case 5:k=y([]),l=k.next();case 8:if(l.done){ja.A(4);break}m=l.value;return ja.yield(m.Ph(h),9);case 9:l=k.next();ja.A(8);break;case 4:if((n=a.i)==null||!n.Vh(b.input,b.Ga)){ja.A(12);break}return ja.yield(a.i.Jh(b.input,
b.Ga),13);case 13:return p=ja.i,sx(a,p,b),ja.return(p);case 12:return(x=(v=b.config)==null?void 0:v.Sh)&&a.h.has(x)?t=a.h.get(x):(A=JSON.stringify(b.Ga),aa=(K=(H=b.Za)==null?void 0:H.headers)!=null?K:{},b.Za=Object.assign({},b.Za,{headers:Object.assign({},aa,c)}),da=Object.assign({},b.Za),b.Za.method==="POST"&&(da=Object.assign({},da,{body:A})),((Pa=b.config)==null?0:Pa.Xe)&&bx(b.config.Xe),Nb=function(){return a.fa.fetch(b.input,da,b.config)},t=Nb(),x&&a.h.set(x,t)),ja.yield(t,14);
case 14:if((Ya=ja.i)&&"error"in Ya&&((yb=Ya)==null?0:(Za=yb.error)==null?0:Za.details))for(Qa=Ya.error.details,Ia=y(Qa),Ha=Ia.next();!Ha.done;Ha=Ia.next())fh=Ha.value,(ks=fh["@type"])&&jx.indexOf(ks)>-1&&(delete fh["@type"],Ya=fh);x&&a.h.has(x)&&a.h.delete(x);((ls=b.config)==null?0:ls.Ye)&&bx(b.config.Ye);if(Ya||(ms=a.i)==null||!ms.wh(b.input,b.Ga)){ja.A(15);break}return ja.yield(a.i.Ih(b.input,b.Ga),16);case 16:Ya=ja.i;case 15:return sx(a,Ya,b),((ns=b.config)==null?0:ns.Ue)&&bx(b.config.Ue),d(),
ja.return(Ya||void 0)}})}
function nx(a,b){a:{a=a.u;var c,d=(c=nt(b,El))==null?void 0:c.signal;if(d&&a.Zb&&(c=a.Zb[d])){var e=c();break a}var f;if((c=(f=nt(b,Cl))==null?void 0:f.request)&&a.ge&&(f=a.ge[c])){e=f();break a}for(e in b)if(a.od[e]&&(b=a.od[e])){e=b();break a}e=void 0}if(e!==void 0)return Promise.resolve(e)}
function px(a,b){var c,d,e,f;return B(function(g){if(g.h==1){e=(c=a)==null?void 0:(d=c.Ob)==null?void 0:d.sessionIndex;var h=g.yield;var k=en(0,{sessionIndex:e});if(!(k instanceof fi)){var l=new fi(di);gi(l,2,k);k=l}return h.call(g,k,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},ew(b),f)))})}
function ox(a,b){var c;a=a==null?void 0:(c=a.Ob)==null?void 0:c.sessionIndex;c=en(0,{sessionIndex:a});return Object.assign({},ew(b),c)}
;var tx=new Gs("INNERTUBE_TRANSPORT_TOKEN");function ux(){}
w(ux,mw);ux.prototype.j=function(){return fv};
ux.prototype.i=function(a){return nt(a,Ol)||void 0};
ux.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
fa.Object.defineProperties(ux.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function vx(){}
w(vx,mw);vx.prototype.j=function(){return gv};
vx.prototype.i=function(a){return nt(a,Nl)||void 0};
vx.prototype.h=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
fa.Object.defineProperties(vx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});var wx=new Gs("SHARE_CLIENT_PARAMS_PROVIDER_TOKEN");function xx(a){this.M=a}
w(xx,mw);xx.prototype.j=function(){return av};
xx.prototype.i=function(a){return nt(a,Il)||nt(a,Jl)||nt(a,Hl)};
xx.prototype.h=function(a,b){b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);if(b.clientParamIdentifier){var c;if((c=this.M)==null?0:c.h(b.clientParamIdentifier))a.clientParams=this.M.i(b.clientParamIdentifier)}};
xx[Fs]=[wx];function yx(){}
w(yx,mw);yx.prototype.j=function(){return cv};
yx.prototype.i=function(a){return nt(a,Gl)||void 0};
yx.prototype.h=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
fa.Object.defineProperties(yx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function zx(){}
w(zx,mw);zx.prototype.j=function(){return dv};
zx.prototype.i=function(a){return nt(a,Ml)||void 0};
zx.prototype.h=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function Ax(){}
w(Ax,mw);Ax.prototype.j=function(){return ev};
Ax.prototype.i=function(a){return nt(a,Ll)||void 0};
Ax.prototype.h=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function Bx(){}
w(Bx,mw);Bx.prototype.j=function(){return bv};
Bx.prototype.i=function(a){return nt(a,Kl)};
Bx.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var Cx=new Gs("FETCH_FN_TOKEN"),Dx=new Gs("PARSE_FN_TOKEN"),Ex=new Gs("WINDOW_REQUEST_TOKEN");function Fx(a,b){var c=C.apply(2,arguments);a=a===void 0?0:a;U.call(this,b,c);this.errorType=a;Object.setPrototypeOf(this,this.constructor.prototype)}
w(Fx,U);var Gx=new Gs("NETWORK_SLI_TOKEN");function Hx(a,b,c,d){this.h=a;this.i=b;this.j=c;this.o=d}
Hx.prototype.fetch=function(a,b,c){var d=this,e,f,g;return B(function(h){e=Ix(d,a,b);g=(f=d.i)!=null?f:fetch;return h.return(g(e).then(function(k){return d.handleResponse(k,c)}).catch(function(k){W(k);
if((c==null?0:c.qe)&&k instanceof Fx&&k.errorType===1)return Promise.reject(k)}))})};
function Ix(a,b,c){if(a.h){var d=ac(bc(5,mc(b,"key")))||"/UNKNOWN_PATH";a.h.start(d)}d=c;T("wug_networking_gzip_request")&&(d=Uq(c));var e;return new ((e=a.o)!=null?e:window.Request)(b,d)}
Hx.prototype.handleResponse=function(a,b){var c,d=(c=this.j)!=null?c:JSON.parse;c=a.text().then(function(e){if((b==null?0:b.Ge)&&a.ok)return Cf(b.Ge,e);e=e.replace(")]}'","");if((b==null?0:b.qe)&&e)try{var f=d(e)}catch(h){throw new Fx(1,"JSON parsing failed after fetch");}var g;return(g=f)!=null?g:d(e)});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Dh(),c=c.then(function(e){W(new U("Error: API fetch failed",a.status,a.url,e));return Object.assign({},e,{errorMetadata:{status:a.status}})}));
return c};
Hx[Fs]=[Is(Gx),Is(Cx),Is(Dx),Is(Ex)];var Jx=new Gs("NETWORK_MANAGER_TOKEN");var Kx;function Lx(){var a,b;if(!Kx){var c=Os();Ks(c,{Bc:Jx,Nd:Hx});var d={od:{feedbackEndpoint:hw(yx),modifyChannelNotificationPreferenceEndpoint:hw(zx),playlistEditEndpoint:hw(Ax),shareEntityEndpoint:hw(xx),subscribeEndpoint:hw(ux),unsubscribeEndpoint:hw(vx),webPlayerShareEntityServiceEndpoint:hw(Bx)}},e=cw(),f={};e&&(f.client_location=e);a===void 0&&(a=dn());b===void 0&&(b=c.resolve(Jx));lx(d,b,a,f);Ks(c,{Bc:tx,Od:kx.instance});Kx=c.resolve(tx)}return Kx}
;function Mx(a){var b=new ej;if(a.interpreterJavascript){var c=ul(a.interpreterJavascript);c=Db(c).toString();var d=new cj;zf(d,6,c);uf(b,cj,1,d)}else a.interpreterUrl&&(c=vl(a.interpreterUrl),c=jb(c).toString(),d=new dj,zf(d,4,c),uf(b,dj,2,d));a.interpreterHash&&Af(b,3,a.interpreterHash);a.program&&Af(b,4,a.program);a.globalName&&Af(b,5,a.globalName);a.clientExperimentsStateBlob&&Af(b,7,a.clientExperimentsStateBlob);return b}
function Nx(a){var b={};a=y(a.split("&"));for(var c=a.next();!c.done;c=a.next())c=c.value.split("="),c.length===2&&(b[c[0]]=c[1]);return b}
;function wc(){if(T("bg_st_hr"))return"havuokmhhs-0";var a,b=((a=performance)==null?void 0:a.timeOrigin)||0;return"havuokmhhs-"+Math.floor(b)}
function Ox(a){this.h=a}
Ox.prototype.bindInnertubeChallengeFetcher=function(a){this.h.bicf(a)};
Ox.prototype.registerChallengeFetchedCallback=function(a){this.h.bcr(a)};
Ox.prototype.getLatestChallengeResponse=function(){return this.h.blc()};
function Px(){return new Promise(function(a){var b=window.top;b.ntpevasrs!==void 0?a(new Ox(b.ntpevasrs)):(b.ntpqfbel===void 0&&(b.ntpqfbel=[]),b.ntpqfbel.push(function(c){a(new Ox(c))}))})}
;var Qx=[],Rx=!1;function Sx(){if(!T("disable_biscotti_fetch_for_ad_blocker_detection")&&!T("disable_biscotti_fetch_entirely_for_all_web_clients")&&Ku()){var a=S("PLAYER_VARS",{});if(lg(a)!="1"&&!Mu(a)){var b=function(){Rx=!0;"google_ad_status"in window?Xl("DCLKSTAT",1):Xl("DCLKSTAT",2)};
try{jv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Qx.push(Gj.pa(function(){if(!(Rx||"google_ad_status"in window)){try{nv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Rx=!0;Xl("DCLKSTAT",3)}},5E3))}}}
function Tx(){var a=Number(S("DCLKSTAT",0));return isNaN(a)?0:a}
;function Ux(a){this.h=a}
[new Ux("b.f_"),new Ux("j.s_"),new Ux("r.s_"),new Ux("e.h_"),new Ux("i.s_"),new Ux("s.t_"),new Ux("p.h_"),new Ux("s.i_"),new Ux("f.i_"),new Ux("a.b_"),new Ux("a.o_"),new Ux("g.o_"),new Ux("p.i_"),new Ux("p.m_"),new Ux("n.k_"),new Ux("i.f_"),new Ux("a.s_"),new Ux("m.c_"),new Ux("n.h_"),new Ux("o.p_")].reduce(function(a,b){a[b.h]=b;return a},{});function Vx(a,b,c){var d=this;this.network=a;this.options=b;this.o=c;this.h=null;if(b.ai){var e=new ij;this.h=e.promise;D.ytAtRC&&Gj.Ra(function(){var f,g;return B(function(h){if(h.h==1){if(!D.ytAtRC)return h.return();f=Wx(null);return h.yield(d.hb(f),2)}g=h.i;D.ytAtRC&&D.ytAtRC(JSON.stringify(g));h.h=0})},2);
Px().then(function(f){var g,h,k,l;return B(function(m){if(m.h==1)return f.bindInnertubeChallengeFetcher(function(n){return d.hb(Wx(n))}),m.yield(vc(),2);
g=m.i;h=f.getLatestChallengeResponse();k=h.challenge;if(!k)throw Error("BGE_MACIL");l={challenge:k,fb:Nx(k),vm:g,bgChallenge:new ej};e.resolve(l);f.registerChallengeFetchedCallback(function(n){n=n.challenge;if(!n)throw Error("BGE_MACR");n={challenge:n,fb:Nx(n),vm:g,bgChallenge:new ej};d.h=Promise.resolve(n)});
m.h=0})})}else b.preload&&Xx(this,new Promise(function(f){Bn(function(){f(Yx(d))},0)}))}
Vx.prototype.j=function(){var a=this;return B(function(b){return b.h==1?b.yield(Promise.race([a.h,null]),2):b.return(!!b.i)})};
Vx.prototype.i=function(a,b,c){var d=this,e,f,g;return B(function(h){d.h===null&&Xx(d,Yx(d));e=!1;f={};g=function(){var k,l,m;return B(function(n){switch(n.h){case 1:return n.yield(d.h,2);case 2:k=n.i;f.challenge=k.challenge;if(!k.vm){"c1a"in k.fb&&(f.error="ATTESTATION_ERROR_VM_NOT_INITIALIZED");n.A(3);break}l=Object.assign({},{c:k.challenge,e:a},b);xa(n,4);e=!0;if(T("attbs")&&!T("attmusi")){m=k.vm.dd({wb:l});n.A(6);break}return n.yield(k.vm.snapshot({wb:l}),7);case 7:m=n.i;case 6:m?f.webResponse=
m:f.error="ATTESTATION_ERROR_VM_NO_RESPONSE";ya(n,3);break;case 4:za(n),f.error="ATTESTATION_ERROR_VM_INTERNAL_ERROR";case 3:if(a==="ENGAGEMENT_TYPE_PLAYBACK"){var p=k.fb,t={};p.c6a&&(t.reportingStatus=String(Number(p.c)^Tx()));p.c6b&&(t.broadSpectrumDetectionResult=String(Number(p.c)^Number(S("CATSTAT",0))));f.adblockReporting=t}return n.return(f)}})};
return h.return(Promise.race([g(),Zx(c,function(){var k=Object.assign({},f);e&&(k.error="ATTESTATION_ERROR_VM_TIMEOUT");return k})]))})};
function Wx(a){var b={engagementType:"ENGAGEMENT_TYPE_UNBOUND"};a&&(b.interpreterHash=a);return b}
function Yx(a,b){b=b===void 0?0:b;var c,d,e,f,g,h,k,l,m,n,p,t;return B(function(v){switch(v.h){case 1:c=Wx(nj().h);if(T("att_fet_ks"))return xa(v,7),v.yield(a.hb(c),9);xa(v,4);return v.yield($x(a,c),6);case 6:g=v.i;e=g.Pe;f=g.Qe;d=g;ya(v,3);break;case 4:return za(v),W(Error("Failed to fetch attestation challenge after "+(b+" attempts; not retrying for 24h."))),ay(a,864E5),v.return({challenge:"",fb:{},vm:void 0,bgChallenge:void 0});case 9:d=v.i;if(!d)throw Error("Fetching Attestation challenge returned falsy");
if(!d.challenge)throw Error("Missing Attestation challenge");e=d.challenge;f=Nx(e);if("c1a"in f&&(!d.bgChallenge||!d.bgChallenge.program))throw Error("Expected bg challenge but missing.");ya(v,3);break;case 7:h=za(v);W(h);b++;if(b>=5)return W(Error("Failed to fetch attestation challenge after "+(b+" attempts; not retrying for 24h."))),ay(a,864E5),v.return({challenge:"",fb:{},vm:void 0,bgChallenge:void 0});k=1E3*Math.pow(2,b-1)+Math.random()*1E3;return v.return(new Promise(function(x){Bn(function(){x(Yx(a,
b))},k)}));
case 3:l=Number(f.t)||7200;ay(a,l*1E3);m=void 0;if(!("c1a"in f&&d.bgChallenge)){v.A(10);break}n=Mx(d.bgChallenge);xa(v,11);return v.yield(oj(nj(),n),13);case 13:ya(v,12);break;case 11:return p=za(v),W(p),v.return({challenge:e,fb:f,vm:m,bgChallenge:n});case 12:return xa(v,14),m=new kj({challenge:n,yd:{Da:"aGIf"}}),v.yield(m.Yc,16);case 16:ya(v,10);break;case 14:t=za(v),W(t),m=void 0;case 10:return v.return({challenge:e,fb:f,vm:m,bgChallenge:n})}})}
Vx.prototype.hb=function(a){var b=this,c;return B(function(d){c=b.o;if(!c||c.ta())return d.return(b.network.hb(a));fx("att_pna");return d.return(new Promise(function(e){Lh(c,"publicytnetworkstatus-online",function(){b.network.hb(a).then(e)})}))})};
function by(a){if(!a)throw Error("Fetching Attestation challenge returned falsy");if(!a.challenge)throw Error("Missing Attestation challenge");var b=a.challenge,c=Nx(b);if("c1a"in c&&(!a.bgChallenge||!a.bgChallenge.program))throw Error("Expected bg challenge but missing.");return Object.assign({},a,{Pe:b,Qe:c})}
function $x(a,b){var c,d,e,f,g;return B(function(h){switch(h.h){case 1:c=void 0,d=0,e={};case 2:if(!(d<5)){h.A(4);break}if(!(d>0)){h.A(5);break}e.ld=1E3*Math.pow(2,d-1)+Math.random()*1E3;return h.yield(new Promise(function(k){return function(l){Bn(function(){l(void 0)},k.ld)}}(e)),5);
case 5:return xa(h,7),h.yield(a.hb(b),9);case 9:return f=h.i,h.return(by(f));case 7:c=g=za(h),g instanceof Error&&W(g);case 8:d++;e={ld:void 0};h.A(2);break;case 4:throw c;}})}
function Xx(a,b){a.h=b}
function cy(a){var b,c,d;return B(function(e){if(e.h==1)return e.yield(Promise.race([a.h,null]),2);b=e.i;var f=Yx(a);a.h=f;(c=b)==null||(d=c.vm)==null||d.dispose();e.h=0})}
function ay(a,b){function c(){var e;return B(function(f){e=d-Date.now();return e<1E3?f.yield(cy(a),0):(Bn(c,Math.min(e,6E4)),f.A(0))})}
var d=Date.now()+b;c()}
function Zx(a,b){return new Promise(function(c){Bn(function(){c(b())},a)})}
;function dy(){this.h=Lx()}
dy.prototype.hb=function(a){fx("att_fsr");return rx(this.h,a).then(function(b){fx("att_frr");return b})};function ey(){var a,b,c;return B(function(d){if(d.h==1)return a=Os().resolve(tx),a?d.yield(mx(a),2):(W(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return W(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.zh;return d.return(c)}W(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;function fy(){var a;return(a=S("WEB_PLAYER_CONTEXT_CONFIGS"))==null?void 0:a.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER}
;var gy=D.caches,hy;function iy(a){var b=a.indexOf(":");return b===-1?{Bd:a}:{Bd:a.substring(0,b),datasyncId:a.substring(b+1)}}
function jy(){return B(function(a){if(hy!==void 0)return a.return(hy);hy=new Promise(function(b){var c;return B(function(d){switch(d.h){case 1:return xa(d,2),d.yield(gy.open("test-only"),4);case 4:return d.yield(gy.delete("test-only"),5);case 5:ya(d,3);break;case 2:if(c=za(d),c instanceof Error&&c.name==="SecurityError")return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(hy)})}
function ky(a){var b,c,d,e,f,g,h;B(function(k){if(k.h==1)return k.yield(jy(),2);if(k.h!=3){if(!k.i)return k.return(!1);b=[];return k.yield(gy.keys(),3)}c=k.i;d=y(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=iy(f),h=g.datasyncId,!h||a.includes(h)||b.push(gy.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(m){return m})}))})}
function ly(){var a,b,c,d,e,f,g;return B(function(h){if(h.h==1)return h.yield(jy(),2);if(h.h!=3){if(!h.i)return h.return(!1);a=zn("cache contains other");return h.yield(gy.keys(),3)}b=h.i;c=y(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=iy(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function my(){try{return!!self.sessionStorage}catch(a){return!1}}
;function ny(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function oy(a){if(my()){var b=Object.keys(window.sessionStorage);b=y(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=ny(c);d===void 0||a.includes(d)||self.sessionStorage.removeItem(c)}}}
function py(){if(!my())return!1;var a=zn(),b=Object.keys(window.sessionStorage);b=y(b);for(var c=b.next();!c.done;c=b.next())if(c=ny(c.value),c!==void 0&&c!==a)return!0;return!1}
;function qy(){ey().then(function(a){a&&(Fp(a),ky(a),Pv(a),oy(a))})}
function ry(){var a=new Mr;Gj.pa(function(){var b,c,d,e,f;return B(function(g){switch(g.h){case 1:if(T("ytidb_clear_optimizations_killswitch")){g.A(2);break}b=zn("clear");if(b.startsWith("V")&&b.endsWith("||")){var h=[b];Fp(h);ky(h);Pv(h);oy(h);return g.return()}c=Qv();d=py();return g.yield(ly(),3);case 3:return e=g.i,g.yield(Gp(),4);case 4:if(f=g.i,!(c||d||e||f))return g.return();case 2:a.ta()?qy():Lh(a,"publicytnetworkstatus-online",qy),g.h=0}})})}
;var sy=["www.youtube-nocookie.com","www.youtubeeducation.com","youtube.googleapis.com"];function ty(){this.state=1;this.vm=null;this.h=void 0}
r=ty.prototype;r.initialize=function(a,b,c,d){this.h=d;if(a.program){var e;d=(e=a.interpreterUrl)!=null?e:null;if(a.interpreterSafeScript)e=ul(a.interpreterSafeScript);else{var f;e=(f=a.interpreterScript)!=null?f:null}a.interpreterSafeUrl&&(d=vl(a.interpreterSafeUrl).toString());uy(this,e,d,a.program,b,c)}else W(Error("BL:CIP"))};
function uy(a,b,c,d,e,f){var g=g===void 0?"trayride":g;c?(a.state=2,jv(c,function(){window[g]?vy(a,d,g,e):(a.state=3,lv(c),W(new U("BL:ULB",""+c)))},f)):b?(f=ug("SCRIPT"),b instanceof Bb?(f.textContent=Db(b),Eb(f)):f.textContent=b,f.nonce=Ab(document),document.head.appendChild(f),document.head.removeChild(f),window[g]?vy(a,d,g,e):(a.state=4,W(new U("BL:ULBJ")))):W(new U("BL:ULV"))}
r.isLoading=function(){return this.state===2};
function vy(a,b,c,d){a.state=5;var e=!!a.h&&sy.includes(cc(a.h)||"");try{var f=new kj({program:b,globalName:c,yd:{disable:!T("att_web_record_metrics")||!T("att_skip_metrics_for_cookieless_domains_ks")&&e,Da:"aGIf"}});f.Yc.then(function(){a.state=6;d&&d(b)});
a.Xc(f)}catch(g){a.state=7,g instanceof Error&&W(g)}}
r.invoke=function(a){a=a===void 0?{}:a;return this.gd()?this.Qd({wb:a}):null};
r.dispose=function(){this.Xc(null);this.state=8};
r.gd=function(){return!!this.vm};
r.Qd=function(a){return this.vm.dd(a)};
r.Xc=function(a){sc(this.vm);this.vm=a};function wy(){var a=F("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function xy(){ty.apply(this,arguments)}
w(xy,ty);xy.prototype.Xc=function(a){var b;(b=wy())==null||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.dd.bind(a)},E("yt.abuse.playerAttLoader",b),E("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(E("yt.abuse.playerAttLoader",null),E("yt.abuse.playerAttLoaderRun",null))};
xy.prototype.gd=function(){return!!wy()};
xy.prototype.Qd=function(a){return wy().bgvmc(a)};function yy(a){Ys.call(this,a===void 0?"document_active":a);var b=this;this.o=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.G},{from:"document_active",to:"document_disposed",action:this.u},{from:"document_disposed_preventable",to:"document_disposed",action:this.u},{from:"document_disposed_preventable",to:"flush_logs",action:this.M},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.M},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
w(yy,Ys);yy.prototype.G=function(a,b){if(!this.h.get("document_disposed_preventable")){a(b==null?void 0:b.event);var c,d;if((b==null?0:(c=b.event)==null?0:c.defaultPrevented)||(b==null?0:(d=b.event)==null?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
yy.prototype.u=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(b==null?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
yy.prototype.M=function(a,b){a(b==null?void 0:b.event);this.transition("document_active")};
yy.prototype.i=function(){this.h=new Map};function zy(a){Ys.call(this,a===void 0?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.M},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.u},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.M},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.M},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.u},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.u},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){document.visibilityState==="visible"?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
T("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
w(zy,Ys);zy.prototype.i=function(a,b){a(b==null?void 0:b.event);T("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
zy.prototype.h=function(a,b){a(b==null?void 0:b.event);T("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
zy.prototype.u=function(a,b){a(b==null?void 0:b.event)};
zy.prototype.M=function(a,b){a(b==null?void 0:b.event)};function Ay(){this.o=new yy;this.u=new zy}
Ay.prototype.install=function(){var a=C.apply(0,arguments),b=this;a.forEach(function(c){b.o.install(c)});
a.forEach(function(c){b.u.install(c)})};function By(){this.o=[];this.i=new Map;this.h=new Map;this.j=new Set}
By.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=c===void 0?0:c;if(d)if(c=xu(c===void 0?0:c)){a=this.client;d=new qu({trackingParams:d});var e=void 0;if(T("no_client_ve_attach_unless_shown")){var f=Kv(d,c);Gv.set(f,!0);Lv(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=Jv({cttAuthInfo:zu(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);c==="UNDEFINED_CSN"?Mv("visualElementGestured",f,d):a?Xt("visualElementGestured",d,a,f):qo("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
By.prototype.stateChanged=function(a,b,c){this.visualElementStateChanged(new qu({trackingParams:a}),b,c===void 0?0:c)};
By.prototype.visualElementStateChanged=function(a,b,c){c=c===void 0?0:c;if(c===0&&this.j.has(c))this.o.push([a,b]);else{var d=c;d=d===void 0?0:d;c=xu(d);a||(a=(a=uu(d===void 0?0:d))?new qu({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=Jv({cttAuthInfo:zu(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},c==="UNDEFINED_CSN"?Mv("visualElementStateChanged",d,b):a?Xt("visualElementStateChanged",b,a,d):qo("visualElementStateChanged",b,d))}};
function Cy(a,b){if(b===void 0)for(var c=wu(),d=0;d<c.length;d++)c[d]!==void 0&&Cy(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&Iv(a.client,b,f,e)}),a.i.clear(),a.h.clear()}
;function Dy(){Ay.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));T("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a));T("web_log_cfg_cee_ks")||Bn(Ey)}
w(Dy,Ay);Dy.prototype.j=function(){qo("finalPayload",{csn:xu()})};
Dy.prototype.h=function(){ku(lu)};
Dy.prototype.i=function(){var a=Cy;By.instance||(By.instance=new By);a(By.instance)};
function Ey(){var a=S("CLIENT_EXPERIMENT_EVENTS");if(a){var b=de();a=y(a);for(var c=a.next();!c.done;c=a.next())c=c.value,b(c)&&qo("genericClientExperimentEvent",{eventType:c});delete Wl.CLIENT_EXPERIMENT_EVENTS}}
;function Fy(){}
function Gy(){var a=F("ytglobal.storage_");a||(a=new Fy,E("ytglobal.storage_",a));return a}
Fy.prototype.estimate=function(){var a,b,c;return B(function(d){a=navigator;return((b=a.storage)==null?0:b.estimate)?d.return(a.storage.estimate()):((c=a.webkitTemporaryStorage)==null?0:c.queryUsageAndQuota)?d.return(Hy()):d.return()})};
function Hy(){var a=navigator;return new Promise(function(b,c){var d;(d=a.webkitTemporaryStorage)!=null&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
E("ytglobal.storageClass_",Fy);function oo(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;self.document===void 0||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=.2}
oo.prototype.Ha=function(a){this.handleError(a)};
oo.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":T("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":T("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":Iy(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=.1&&this.h("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=
Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function Iy(a,b){Gy().estimate().then(function(c){c=Object.assign({},b,{isSw:self.document===void 0,isIframe:self!==self.top,deviceStorageUsageMbytes:Jy(c==null?void 0:c.usage),deviceStorageQuotaMbytes:Jy(c==null?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function Jy(a){return typeof a==="undefined"?"-1":String(Math.ceil(a/1048576))}
;var Ky={},Ly=(Ky["api.invalidparam"]=2,Ky.auth=150,Ky["drm.auth"]=150,Ky["heartbeat.net"]=150,Ky["heartbeat.servererror"]=150,Ky["heartbeat.stop"]=150,Ky["html5.unsupportedads"]=5,Ky["fmt.noneavailable"]=5,Ky["fmt.decode"]=5,Ky["fmt.unplayable"]=5,Ky["html5.missingapi"]=5,Ky["html5.unsupportedlive"]=5,Ky["drm.unavailable"]=5,Ky["mrm.blocked"]=151,Ky["embedder.identity.denied"]=152,Ky);var My=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn playmuted muted_autoplay_duration_mode".split(" "));function Ny(a){return(a.search("cue")===0||a.search("load")===0)&&a!=="loadModule"}
function Oy(a,b,c){if(typeof a==="string")return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=y(My);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function Py(a,b,c,d){if(Oa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};typeof a==="string"&&a.length===16?b.list="PL"+a:b.playlist=a;return b}
;function Qy(a){G.call(this);var b=this;this.api=a;this.Y=this.u=!1;this.D=[];this.P={};this.j=[];this.i=[];this.Z=!1;this.sessionId=this.h=null;this.targetOrigin="*";this.U=T("web_player_split_event_bus_iframe");this.o=S("POST_MESSAGE_ORIGIN")||document.location.protocol+"//"+document.location.hostname;this.G=function(c){a:if(!(b.o!=="*"&&c.origin!==b.o||b.h&&c.source!==b.h||typeof c.data!=="string")){try{var d=JSON.parse(c.data)}catch(h){break a}if(d)switch(d.event){case "listening":var e=c.source;
c=c.origin;d=d.id;c!=="null"&&(b.o=b.targetOrigin=c);b.h=e;b.sessionId=d;if(b.u){b.Y=!0;b.u=!1;b.sendMessage("initialDelivery",Ry(b));b.sendMessage("onReady");e=y(b.D);for(d=e.next();!d.done;d=e.next())Sy(b,d.value);b.D=[]}break;case "command":if(e=d.func,d=d.args,e==="addEventListener"&&d)e=d[0],d=c.origin,e==="onReady"?b.api.logApiCall(e+" invocation",d):e==="onError"&&b.Z&&(b.api.logApiCall(e+" invocation",d,b.errorCode),b.errorCode=void 0),b.api.logApiCall(e+" registration",d),b.P[e]||e==="onReady"||
(c=Ty(b,e,d),b.i.push({eventType:e,listener:c,origin:d}),b.U?b.api.handleExternalCall("addEventListener",[e,c],d):b.api.addEventListener(e,c),b.P[e]=!0);else if(c=c.origin,b.api.isExternalMethodAvailable(e,c)){d=d||[];if(d.length>0&&Ny(e)){var f=d;if(Oa(f[0])&&!Array.isArray(f[0]))var g=f[0];else switch(g={},e){case "loadVideoById":case "cueVideoById":g=Oy(f[0],f[1]!==void 0?Number(f[1]):void 0,f[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":g=f[0];typeof g==="string"&&(g={mediaContentUrl:g,
startSeconds:f[1]!==void 0?Number(f[1]):void 0,suggestedQuality:f[2]});c:{if((f=g.mediaContentUrl)&&(f=/\/([ve]|embed)\/([^#?]+)/.exec(f))&&f[2]){f=f[2];break c}f=null}g.videoId=f;g=Oy(g);break;case "loadPlaylist":case "cuePlaylist":g=Py(f[0],f[1],f[2],f[3])}d.length=1;d[0]=g}b.api.handleExternalCall(e,d,c);Ny(e)&&Uy(b,Ry(b))}}}};
Vy.addEventListener("message",this.G);if(a=S("WIDGET_ID"))this.sessionId=a;Wy(this,"onReady",function(){b.u=!0;var c=b.api.getVideoData();if(!c.isPlayable){b.Z=!0;c=c.errorCode;var d=d===void 0?5:d;b.errorCode=c?Ly[c]||d:d;b.sendMessage("onError",Number(b.errorCode))}});
Wy(this,"onVideoProgress",this.kf.bind(this));Wy(this,"onVolumeChange",this.lf.bind(this));Wy(this,"onApiChange",this.cf.bind(this));Wy(this,"onPlaybackQualityChange",this.gf.bind(this));Wy(this,"onPlaybackRateChange",this.hf.bind(this));Wy(this,"onStateChange",this.jf.bind(this));Wy(this,"onWebglSettingsChanged",this.mf.bind(this));Wy(this,"onCaptionsTrackListChanged",this.df.bind(this));Wy(this,"captionssettingschanged",this.ef.bind(this))}
w(Qy,G);function Uy(a,b){a.sendMessage("infoDelivery",b)}
r=Qy.prototype;r.sendMessage=function(a,b){a={event:a,info:b===void 0?null:b};this.Y?Sy(this,a):this.D.push(a)};
function Ty(a,b,c){return function(d){b==="onError"?a.api.logApiCall(b+" invocation",c,d):a.api.logApiCall(b+" invocation",c);a.sendMessage(b,d)}}
function Wy(a,b,c){a.j.push({eventType:b,listener:c});a.api.addEventListener(b,c)}
function Ry(a){if(!a.api)return null;var b=a.api.getApiInterface();Sb(b,"getVideoData");for(var c={apiInterface:b},d=0,e=b.length;d<e;d++){var f=b[d];if(f.search("get")===0||f.search("is")===0){var g=0;f.search("get")===0?g=3:f.search("is")===0&&(g=2);g=f.charAt(g).toLowerCase()+f.substring(g+1);try{var h=a.api[f]();c[g]=h}catch(k){}}}c.videoData=a.api.getVideoData();c.currentTimeLastUpdated_=Date.now()/1E3;return c}
r.jf=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&!T("embeds_enable_vfsyb")&&(a.storyboardFormat=this.api.getStoryboardFormat());Uy(this,a)};
r.gf=function(a){a={playbackQuality:a};this.api.getAvailableQualityLevels&&(a.availableQualityLevels=this.api.getAvailableQualityLevels());this.api.getPreferredQuality&&(a.preferredQuality=this.api.getPreferredQuality());Uy(this,a)};
r.hf=function(a){Uy(this,{playbackRate:a})};
r.cf=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
r.lf=function(){Uy(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
r.kf=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Uy(this,a)};
r.mf=function(){Uy(this,{sphericalProperties:this.api.getSphericalProperties()})};
r.df=function(){if(this.api.getCaptionTracks){var a={captionTracks:this.api.getCaptionTracks()};Uy(this,a)}};
r.ef=function(){if(this.api.getSubtitlesUserSettings){var a={subtitlesUserSettings:this.api.getSubtitlesUserSettings()};Uy(this,a)}};
function Sy(a,b){if(a.h){b.channel="widget";a.sessionId&&(b.id=a.sessionId);try{var c=JSON.stringify(b);a.h.postMessage(c,a.targetOrigin)}catch(d){W(d)}}}
r.ba=function(){G.prototype.ba.call(this);Vy.removeEventListener("message",this.G);for(var a=0;a<this.j.length;a++){var b=this.j[a];this.api.removeEventListener(b.eventType,b.listener)}this.j=[];for(a=0;a<this.i.length;a++)b=this.i[a],this.U?this.api.handleExternalCall("removeEventListener",[b.eventType,b.listener],b.origin):this.api.removeEventListener(b.eventType,b.listener);this.i=[]};
var Vy=window;function Xy(a,b,c){G.call(this);var d=this;this.api=a;this.id=b;this.origin=c;this.h={};this.j=T("web_player_split_event_bus_iframe");this.i=function(e){a:if(e.origin===d.origin){var f=e.data;if(typeof f==="string"){try{f=JSON.parse(f)}catch(k){break a}if(f.command){var g=f.command;f=f.data;e=e.origin;if(!d.ea){var h=f||{};switch(g){case "addEventListener":typeof h.event==="string"&&d.addListener(h.event,e);break;case "removeEventListener":typeof h.event==="string"&&d.removeListener(h.event,e);break;
default:d.api.isReady()&&d.api.isExternalMethodAvailable(g,e||null)&&(f=Yy(g,f||{}),f=d.api.handleExternalCall(g,f,e||null),(f=Zy(g,f))&&$y(d,g,f))}}}}}};
az.addEventListener("message",this.i);$y(this,"RECEIVING")}
w(Xy,G);r=Xy.prototype;r.addListener=function(a,b){if(!(a in this.h)){var c=this.ff.bind(this,a);this.h[a]=c;this.addEventListener(a,c,b)}};
r.ff=function(a,b){this.ea||$y(this,a,bz(a,b))};
r.removeListener=function(a,b){a in this.h&&(this.removeEventListener(a,this.h[a],b),delete this.h[a])};
r.addEventListener=function(a,b,c){this.j?a==="onReady"?this.api.addEventListener(a,b):this.api.handleExternalCall("addEventListener",[a,b],c||null):this.api.addEventListener(a,b)};
r.removeEventListener=function(a,b,c){this.j?a==="onReady"?this.api.removeEventListener(a,b):this.api.handleExternalCall("removeEventListener",[a,b],c||null):this.api.removeEventListener(a,b)};
function Yy(a,b){switch(a){case "loadVideoById":return[Oy(b)];case "cueVideoById":return[Oy(b)];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return[Py(b)];case "cuePlaylist":return[Py(b)];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];case "setShuffle":return[b.shufflePlaylist];
case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Zy(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
function bz(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}if(b!=null)return{value:b}}
function $y(a,b,c){a.ea||(b={id:a.id,command:b},c&&(b.data=c),cz.postMessage(JSON.stringify(b),a.origin))}
r.ba=function(){az.removeEventListener("message",this.i);for(var a in this.h)this.h.hasOwnProperty(a)&&this.removeListener(a);G.prototype.ba.call(this)};
var az=window,cz=window.parent;var dz=new xy;function ez(){return dz.gd()}
function fz(a){a=a===void 0?{}:a;return dz.invoke(a)}
;function gz(a,b,c,d,e){G.call(this);var f=this;this.D=b;this.webPlayerContextConfig=d;this.Kb=e;this.Pa=!1;this.api={};this.ma=this.u=null;this.U=new O;this.h={};this.Z=this.xa=this.elementId=this.Qa=this.config=null;this.Y=!1;this.j=this.G=null;this.Fa={};this.Gc=["onReady"];this.lastError=null;this.eb=NaN;this.P={};this.ha=0;this.i=this.o=a;uc(this,this.U);hz(this);c?this.ha=setTimeout(function(){f.loadNewVideoConfig(c)},0):d&&(iz(this),jz(this))}
w(gz,G);r=gz.prototype;r.getId=function(){return this.D};
r.loadNewVideoConfig=function(a){if(!this.ea){this.ha&&(clearTimeout(this.ha),this.ha=0);var b=a||{};b instanceof Zu||(b=new Zu(b));this.config=b;this.setConfig(a);jz(this);this.isReady()&&kz(this)}};
function iz(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;a.elementId==="video-player"&&(a.elementId=a.D,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.D:a.config.attrs.id=a.D);var c;((c=a.i)==null?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
r.setConfig=function(a){this.Qa=a;this.config=lz(a);iz(this);if(!this.xa){var b;this.xa=mz(this,((b=this.config.args)==null?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if((c=this.config)==null?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.i&&(this.i.style.width=Aj(Number(b)||b)),(a=a.height)&&this.i&&(this.i.style.height=Aj(Number(a)||a))};
function kz(a){if(a.config&&a.config.loaded!==!0)if(a.config.loaded=!0,!a.config.args||a.config.args.autoplay!=="0"&&a.config.args.autoplay!==0&&a.config.args.autoplay!==!1){var b;a.api.loadVideoByPlayerVars((b=a.config.args)!=null?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function nz(a){var b=!0,c=oz(a);c&&a.config&&(b=c.dataset.version===pz(a));return b&&!!F("yt.player.Application.create")}
function jz(a){if(!a.ea&&!a.Y){var b=nz(a);if(b&&(oz(a)?"html5":null)==="html5")a.Z="html5",a.isReady()||qz(a);else if(rz(a),a.Z="html5",b&&a.j&&a.o)a.o.appendChild(a.j),qz(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.G=function(){c=!0;var d=sz(a,"player_bootstrap_method")?F("yt.player.Application.createAlternate")||F("yt.player.Application.create"):F("yt.player.Application.create");var e=a.config?lz(a.config):void 0;d&&d(a.o,e,a.webPlayerContextConfig,a.Kb);qz(a)};
a.Y=!0;b?a.G():(jv(pz(a),a.G),(b=tz(a))&&qv(b||""),uz(a)&&!c&&E("yt.player.Application.create",null))}}}
function oz(a){var b=tg(a.elementId);!b&&a.i&&a.i.querySelector&&(b=a.i.querySelector("#"+a.elementId));return b}
function qz(a){if(!a.ea){var b=oz(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.Y=!1;if(!sz(a,"html5_remove_not_servable_check_killswitch")){var d;if((b==null?0:b.isNotServable)&&a.config&&(b==null?0:b.isNotServable((d=a.config.args)==null?void 0:d.video_id)))return}vz(a)}else a.eb=setTimeout(function(){qz(a)},50)}}
function vz(a){hz(a);a.Pa=!0;var b=oz(a);if(b){a.u=wz(a,b,"addEventListener");a.ma=wz(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=wz(a,b,f))}}for(var g in a.h)a.h.hasOwnProperty(g)&&a.u&&a.u(g,a.h[g]);kz(a);a.xa&&a.xa(a.api);a.U.sb("onReady",a.api)}
function wz(a,b,c){var d=b[c];return function(){var e=C.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){if(c!=="sendAbandonmentPing")throw f.params=c,a.lastError=f,e=new U("PlayerProxy error in method call",{error:f,method:c,playerId:a.D}),e.level="WARNING",e;}}}
function hz(a){a.Pa=!1;if(a.ma)for(var b in a.h)a.h.hasOwnProperty(b)&&a.ma(b,a.h[b]);for(var c in a.P)a.P.hasOwnProperty(c)&&clearTimeout(Number(c));a.P={};a.u=null;a.ma=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Qa};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
r.isReady=function(){return this.Pa};
r.addEventListener=function(a,b){var c=this,d=mz(this,b);d&&(Lb(this.Gc,a)>=0||this.h[a]||(b=xz(this,a),this.u&&this.u(a,b)),this.U.subscribe(a,d),a==="onReady"&&this.isReady()&&setTimeout(function(){d(c.api)},0))};
r.removeEventListener=function(a,b){this.ea||(b=mz(this,b))&&this.U.unsubscribe(a,b)};
function mz(a,b){var c=b;if(typeof b==="string"){if(a.Fa[b])return a.Fa[b];c=function(){var d=C.apply(0,arguments),e=F(b);if(e)try{e.apply(D,d)}catch(f){throw d=new U("PlayerProxy error when executing callback",{error:f}),d.level="ERROR",d;}};
a.Fa[b]=c}return c?c:null}
function xz(a,b){function c(d){function e(){if(!a.ea)try{a.U.sb(b,d!=null?d:void 0)}catch(h){var g=new U("PlayerProxy error when creating global callback",{error:h.message,event:b,playerId:a.D,data:d,originalStack:h.stack,componentStack:h.ee});g.level="WARNING";throw g;}}
if(sz(a,"web_player_publish_events_immediately"))e();else{var f=setTimeout(function(){e();var g=a.P,h=String(f);h in g&&delete g[h]},0);
kg(a.P,String(f))}}
return a.h[b]=c}
r.getPlayerType=function(){return this.Z||(oz(this)?"html5":null)};
r.getLastError=function(){return this.lastError};
function rz(a){a.cancel();hz(a);a.Z=null;a.config&&(a.config.loaded=!1);var b=oz(a);b&&(nz(a)||!uz(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));if(a.o)for(a=a.o;b=a.firstChild;)a.removeChild(b)}
r.cancel=function(){this.G&&nv(pz(this),this.G);clearTimeout(this.eb);this.Y=!1};
r.ba=function(){rz(this);if(this.j&&this.config&&this.j.destroy)try{this.j.destroy()}catch(b){var a=new U("PlayerProxy error during disposal",{error:b});a.level="ERROR";throw a;}this.Fa=null;for(a in this.h)this.h.hasOwnProperty(a)&&delete this.h[a];this.Qa=this.config=this.api=null;delete this.o;delete this.i;G.prototype.ba.call(this)};
function uz(a){var b,c;a=(b=a.config)==null?void 0:(c=b.args)==null?void 0:c.fflags;return!!a&&a.indexOf("player_destroy_old_version=true")!==-1}
function pz(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function tz(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function sz(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if((d=a.config)==null?0:d.args)c=a.config.args.fflags}return(c||"").split("&").includes(b+"=true")}
function lz(a){for(var b={},c=y(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]=typeof e==="object"?ng(e):e}return b}
;var yz={},zz="player_uid_"+(Math.random()*1E9>>>0);function Az(a,b){var c="player",d=!1;d=d===void 0?!0:d;c=typeof c==="string"?tg(c):c;var e=zz+"_"+Ra(c),f=yz[e];if(f&&d)return Bz(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new gz(c,e,a,b,void 0);yz[e]=f;f.addOnDisposeCallback(function(){delete yz[f.getId()]});
return f.api}
function Bz(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Cz=null,Dz=null;
function Ez(){gx();var a=on(),b=rn(119),c=window.devicePixelRatio>1;if(document.body&&Oj(document.body,"exp-invert-logo"))if(c&&!Oj(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Oj(d,"inverted-hdpi")){var e=Mj(d);Nj(d,e+(e.length>0?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Oj(document.body,"inverted-hdpi")&&Pj();if(b!=c){b="f"+(Math.floor(119/31)+1);d=sn(b)||0;d=c?d|67108864:d&-67108865;d===0?delete ln[b]:(c=d.toString(16),ln[b]=c.toString());
c=!0;T("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in ln)ln.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(ln[f])));var f=d.join("&");gn(b,f,63072E3,a.i,c)}}
function Fz(){Gz()}
function Hz(){bx("ep_init_pr");Gz()}
function Gz(){var a=Cz.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function Iz(){Cz&&Cz.sendAbandonmentPing&&Cz.sendAbandonmentPing();S("PL_ATT")&&dz.dispose();for(var a=Gj,b=0,c=Qx.length;b<c;b++)a.qa(Qx[b]);Qx.length=0;lv("//static.doubleclick.net/instream/ad_status.js");Rx=!1;Xl("DCLKSTAT",0);tc(Dz);Cz&&(Cz.removeEventListener("onVideoDataChange",Fz),Cz.destroy())}
;bx("ep_init_eps");E("yt.setConfig",Xl);E("yt.config.set",Xl);E("yt.setMsg",iv);E("yt.msgs.set",iv);E("yt.logging.errors.log",fu);
E("writeEmbed",function(){bx("ep_init_wes");var a=S("PLAYER_CONFIG");if(!a){var b=S("PLAYER_VARS");b&&(a={args:b})}Uv(!0);a.args.ps==="gvn"&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=S("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);c=fy();if(!c.serializedForcedExperimentIds){var d=km(window.location.href);d.forced_experiments&&(c.serializedForcedExperimentIds=
d.forced_experiments)}var e;((e=a.args)==null?0:e.autoplay)?Yw("watch",["pbs","pbu","pbp"]):a.args&&Lu(a.args)?Yw("video_preview",["ol"]):Yw("embed_no_video",["ep_init_pr"]);Cz=Az(a,c);Cz.addEventListener("onVideoDataChange",Fz);Cz.addEventListener("onReady",Hz);a=S("POST_MESSAGE_ID","player");S("ENABLE_JS_API")?Dz=new Qy(Cz):S("ENABLE_POST_API")&&typeof a==="string"&&typeof b==="string"&&(Dz=new Xy(Cz,a,b));Sx();T("ytidb_create_logger_embed_killswitch")||no();a={};Dy.h||(Dy.h=new Dy);Dy.h.install((a.flush_logs=
{callback:function(){Kt()}},a));
Yr();T("ytidb_clear_embedded_player")&&Gj.pa(function(){Lx();ry()});
T("enable_rta_manager")&&Bn(function(){var f=new dy;var g={preload:!T("enable_rta_npi")},h=!1;if(typeof g==="boolean")var k={preload:g};else typeof g==="undefined"?k={preload:!0}:(k=g,h=!!g.Ah);g=h?void 0:new Mr;Vx.instance=new Vx(f,k,g);f=Vx.instance;k=f.i.bind(f);E("yt.aba.att",k);f=f.j.bind(f);E("yt.aba.att2",f)});
bx("ep_init_wee")});
E("yt.abuse.player.botguardInitialized",F("yt.abuse.player.botguardInitialized")||ez);E("yt.abuse.player.invokeBotguard",F("yt.abuse.player.invokeBotguard")||fz);E("yt.abuse.dclkstatus.checkDclkStatus",F("yt.abuse.dclkstatus.checkDclkStatus")||Tx);E("yt.player.exports.navigate",F("yt.player.exports.navigate")||Tv);E("yt.util.activity.init",F("yt.util.activity.init")||rs);E("yt.util.activity.getTimeSinceActive",F("yt.util.activity.getTimeSinceActive")||us);
E("yt.util.activity.setTimestamp",F("yt.util.activity.setTimestamp")||ss);window.addEventListener("load",am(function(){Ez()}));
window.addEventListener("pageshow",am(function(a){a.persisted||Ez()}));
window.addEventListener("pagehide",am(function(a){T("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?Iz():a.persisted||Iz()}));
window.onerror=function(a,b,c,d,e){var f;b=b===void 0?"Unknown file":b;c=c===void 0?0:c;var g=!1,h=Yl("log_window_onerror_fraction");if(h&&Math.random()<h)g=!0;else{h=document.getElementsByTagName("script");for(var k=0,l=h.length;k<l;k++)if(h[k].src.indexOf("/debug-")>0){g=!0;break}}if(g){g=!1;e?g=!0:(typeof a==="string"?h=a:ErrorEvent&&a instanceof ErrorEvent?(g=!0,h=a.message,b=a.filename,c=a.lineno,d=a.colno):(h="Unknown error",b="Unknown file",c=0),e=new U(h),e.name="UnhandledWindowError",e.message=
h,e.fileName=b,e.lineNumber=c,isNaN(d)?delete e.columnNumber:e.columnNumber=d);if(!T("wiz_enable_component_stack_propagation_killswitch")){a=e;var m;if((m=f)==null||!m.componentStack)if(m=a.ee)f||(f={}),f.componentStack=Yt(m)}f&&iu(e,f);g?fu(e):W(e)}};
wi=gu;window.addEventListener("unhandledrejection",function(a){gu(a.reason)});
Mb(S("ERRORS")||[],function(a){fu.apply(null,a)});
Xl("ERRORS",[]);bx("ep_init_epe");}).call(this);
