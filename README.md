<html><head><script>alert("sell this and I will put you in court")</script><script>(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
(function(){function e(g){this.t={};this.tick=function(h,m,f){var n=void 0!=f?f:(new Date).getTime();this.t[h]=[n,m];if(void 0==f)try{window.console.timeStamp("CSI/"+h)}catch(q){}};this.getStartTickTime=function(){return this.t.start[0]};this.tick("start",null,g)}var a;if(window.performance)var d=(a=window.performance.timing)&&a.responseStart;var p=0<d?new e(d):new e;window.jstiming={Timer:e,load:p};if(a){var b=a.navigationStart;0<b&&d>=b&&(window.jstiming.srt=d-b)}if(a){var c=window.jstiming.load;
0<b&&d>=b&&(c.tick("_wtsrt",void 0,b),c.tick("wtsrt_","_wtsrt",d),c.tick("tbsd_","wtsrt_"))}try{var k=window.top!=window.self,l=window.location.href;a=null;window.chrome&&window.chrome.csi&&(a=Math.floor(window.chrome.csi().pageT),c&&0<b&&(c.tick("_tbnd",void 0,window.chrome.csi().startE),c.tick("tbnd_","_tbnd",b)));null==a&&window.gtbExternal&&(a=k?window.gtbExternal.frameT(l):window.gtbExternal.pageT());null==a&&window.external&&(k?a=window.external.frameT(l):(a=window.external.pageT,c&&0<b&&(c.tick("_tbnd",
void 0,window.external.startE),c.tick("tbnd_","_tbnd",b))));a&&(window.jstiming.pt=a)}catch(g){}})();}).call(this);
window["__csi"]={a:false,b:false,c:"enterprise",v:"default",g:null,d:false};if(window.jstiming){window.jstiming.beaconImageReferences_={};window.jstiming.reportCounter_=1;var getTick=function(a,b,d){var c=a.t[b],e=a.t.start;if(c&&(e||d))return c=a.t[b][0],e=void 0!=d?d:e[0],a=c-e,Math.round(a)},getReportUri=function(a,b,d){var c="";window.jstiming.srt&&(c+="&srt="+window.jstiming.srt,delete window.jstiming.srt);window.jstiming.pt&&(c+="&tbsrt="+window.jstiming.pt,delete window.jstiming.pt);try{window.external&&window.external.tran?c+="&tran="+window.external.tran:window.gtbExternal&&
window.gtbExternal.tran?c+="&tran="+window.gtbExternal.tran():window.chrome&&window.chrome.csi&&(c+="&tran="+window.chrome.csi().tran)}catch(m){}var e=window.chrome;if(e&&(e=e.loadTimes)){e().wasFetchedViaSpdy&&(c+="&p=s");if(e().wasNpnNegotiated){c+="&npn=1";var f=e().npnNegotiatedProtocol;f&&(c+="&npnv="+(encodeURIComponent||escape)(f))}e().wasAlternateProtocolAvailable&&(c+="&apa=1")}var g=a.t,k=g.start;e=[];f=[];for(var l in g)if("start"!=l&&0!=l.indexOf("_")){var p=g[l][1];p?g[p]&&f.push(l+"."+
getTick(a,l,g[p][0])):k&&e.push(l+"."+getTick(a,l))}delete g.start;if(b)for(var h in b)c+="&"+h+"="+b[h];(b=d)||(b="https:"==document.location.protocol?"https://csi.gstatic.com/csi":"http://csi.gstatic.com/csi");return a=[b,"?v=3","&s="+(window.jstiming.sn||"opensocial-gadgets")+"&action=",a.name,f.length?"&it="+f.join(","):"",c,"&rt=",e.join(",")].join("")},sendReport_=function(a,b,d){a=getReportUri(a,b,d);if(!a)return"";b=new Image;var c=window.jstiming.reportCounter_++;window.jstiming.beaconImageReferences_[c]=
b;b.onload=b.onerror=function(){window.jstiming&&delete window.jstiming.beaconImageReferences_[c]};b.src=a;b=null;return a};window.jstiming.report=function(a,b,d){var c=document.visibilityState,e="visibilitychange";c||(c=document.webkitVisibilityState,e="webkitvisibilitychange");if("prerender"==c){var f=!1,g=function(){if(!f){b?b.prerender="1":b={prerender:"1"};if("prerender"==(document.visibilityState||document.webkitVisibilityState))var k=!1;else sendReport_(a,b,d),k=!0;k&&(f=!0,document.removeEventListener(e,
g,!1))}};document.addEventListener(e,g,!1);return""}return sendReport_(a,b,d)}};/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var goog=goog||{};goog.global=this||self;goog.exportPath_=function(a,b,d,c){a=a.split(".");c=c||goog.global;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var e;a.length&&(e=a.shift());)if(a.length||void 0===b)c=c[e]&&c[e]!==Object.prototype[e]?c[e]:c[e]={};else if(!d&&goog.isObject(b)&&goog.isObject(c[e]))for(var f in b)b.hasOwnProperty(f)&&(c[e][f]=b[f]);else c[e]=b};goog.define=function(a,b){return a=b};goog.FEATURESET_YEAR=2012;goog.DEBUG=!0;goog.LOCALE="en";
goog.getLocale=function(){return goog.LOCALE};goog.TRUSTED_SITE=!0;goog.DISALLOW_TEST_ONLY_CODE=!goog.DEBUG;goog.ENABLE_CHROME_APP_SAFE_SCRIPT_LOADING=!1;goog.provide=function(a){if(goog.isInModuleLoader_())throw Error("goog.provide cannot be used within a module.");goog.constructNamespace_(a)};goog.constructNamespace_=function(a,b,d){goog.exportPath_(a,b,d)};goog.NONCE_PATTERN_=/^[\w+/_-]+[=]{0,2}$/;
goog.getScriptNonce_=function(a){a=(a||goog.global).document;return(a=a.querySelector&&a.querySelector("script[nonce]"))&&(a=a.nonce||a.getAttribute("nonce"))&&goog.NONCE_PATTERN_.test(a)?a:""};goog.VALID_MODULE_RE_=/^[a-zA-Z_$][a-zA-Z0-9._$]*$/;
goog.module=function(a){if("string"!==typeof a||!a||-1==a.search(goog.VALID_MODULE_RE_))throw Error("Invalid module identifier");if(!goog.isInGoogModuleLoader_())throw Error("Module "+a+" has been loaded incorrectly. Note, modules cannot be loaded as normal scripts. They require some kind of pre-processing step. You're likely trying to load a module via a script tag or as a part of a concatenated bundle without rewriting the module. For more info see: https://github.com/google/closure-library/wiki/goog.module:-an-ES6-module-like-alternative-to-goog.provide.");if(goog.moduleLoaderState_.moduleName)throw Error("goog.module may only be called once per module.");
goog.moduleLoaderState_.moduleName=a};goog.module.get=function(){return null};goog.module.getInternal_=function(){return null};goog.ModuleType={ES6:"es6",GOOG:"goog"};goog.moduleLoaderState_=null;goog.isInModuleLoader_=function(){return goog.isInGoogModuleLoader_()||goog.isInEs6ModuleLoader_()};goog.isInGoogModuleLoader_=function(){return!!goog.moduleLoaderState_&&goog.moduleLoaderState_.type==goog.ModuleType.GOOG};
goog.isInEs6ModuleLoader_=function(){var a=!!goog.moduleLoaderState_&&goog.moduleLoaderState_.type==goog.ModuleType.ES6;return a?!0:(a=goog.global.$jscomp)?"function"!=typeof a.getCurrentModulePath?!1:!!a.getCurrentModulePath():!1};goog.module.declareLegacyNamespace=function(){goog.moduleLoaderState_.declareLegacyNamespace=!0};
goog.declareModuleId=function(a){if(goog.moduleLoaderState_)goog.moduleLoaderState_.moduleName=a;else{var b=goog.global.$jscomp;if(!b||"function"!=typeof b.getCurrentModulePath)throw Error('Module with namespace "'+a+'" has been loaded incorrectly.');b=b.require(b.getCurrentModulePath());goog.loadedModules_[a]={exports:b,type:goog.ModuleType.ES6,moduleId:a}}};
goog.setTestOnly=function(a){if(goog.DISALLOW_TEST_ONLY_CODE)throw a=a||"",Error("Importing test-only code into non-debug environment"+(a?": "+a:"."));};goog.forwardDeclare=function(){};goog.getObjectByName=function(a,b){a=a.split(".");b=b||goog.global;for(var d=0;d<a.length;d++)if(b=b[a[d]],null==b)return null;return b};goog.addDependency=function(){};goog.ENABLE_DEBUG_LOADER=!0;goog.logToConsole_=function(a){goog.global.console&&goog.global.console.error(a)};goog.require=function(){};
goog.requireType=function(){return{}};goog.basePath="";goog.nullFunction=function(){};goog.abstractMethod=function(){throw Error("unimplemented abstract method");};goog.addSingletonGetter=function(a){a.instance_=void 0;a.getInstance=function(){if(a.instance_)return a.instance_;goog.DEBUG&&(goog.instantiatedSingletons_[goog.instantiatedSingletons_.length]=a);return a.instance_=new a}};goog.instantiatedSingletons_=[];goog.LOAD_MODULE_USING_EVAL=!0;goog.SEAL_MODULE_EXPORTS=goog.DEBUG;
goog.loadedModules_={};goog.DEPENDENCIES_ENABLED=!1;goog.TRANSPILE="detect";goog.ASSUME_ES_MODULES_TRANSPILED=!1;goog.TRANSPILE_TO_LANGUAGE="";goog.TRANSPILER="transpile.js";goog.TRUSTED_TYPES_POLICY_NAME="goog";goog.hasBadLetScoping=null;
goog.loadModule=function(a){var b=goog.moduleLoaderState_;try{goog.moduleLoaderState_={moduleName:"",declareLegacyNamespace:!1,type:goog.ModuleType.GOOG};var d={},c=d;if("function"===typeof a)c=a.call(void 0,c);else if("string"===typeof a)c=goog.loadModuleFromSource_.call(void 0,c,a);else throw Error("Invalid module definition");var e=goog.moduleLoaderState_.moduleName;if("string"===typeof e&&e){goog.moduleLoaderState_.declareLegacyNamespace?(a=d!==c,goog.constructNamespace_(e,c,a)):goog.SEAL_MODULE_EXPORTS&&
Object.seal&&"object"==typeof c&&null!=c&&Object.seal(c);var f={exports:c,type:goog.ModuleType.GOOG,moduleId:goog.moduleLoaderState_.moduleName};goog.loadedModules_[e]=f}else throw Error('Invalid module name "'+e+'"');}finally{goog.moduleLoaderState_=b}};goog.loadModuleFromSource_=function(a,b){eval(goog.CLOSURE_EVAL_PREFILTER_.createScript(b));return a};
goog.normalizePath_=function(a){a=a.split("/");for(var b=0;b<a.length;)"."==a[b]?a.splice(b,1):b&&".."==a[b]&&a[b-1]&&".."!=a[b-1]?a.splice(--b,2):b++;return a.join("/")};goog.loadFileSync_=function(a){if(goog.global.CLOSURE_LOAD_FILE_SYNC)return goog.global.CLOSURE_LOAD_FILE_SYNC(a);try{var b=new goog.global.XMLHttpRequest;b.open("get",a,!1);b.send();return 0==b.status||200==b.status?b.responseText:null}catch(d){return null}};
goog.transpile_=function(a,b,d){var c=goog.global.$jscomp;c||(goog.global.$jscomp=c={});var e=c.transpile;if(!e){var f=goog.basePath+goog.TRANSPILER,g=goog.loadFileSync_(f);if(g){(function(){(0,eval)(g+"\n//# sourceURL="+f)}).call(goog.global);if(goog.global.$gwtExport&&goog.global.$gwtExport.$jscomp&&!goog.global.$gwtExport.$jscomp.transpile)throw Error('The transpiler did not properly export the "transpile" method. $gwtExport: '+JSON.stringify(goog.global.$gwtExport));goog.global.$jscomp.transpile=
goog.global.$gwtExport.$jscomp.transpile;c=goog.global.$jscomp;e=c.transpile}}if(!e){var k=" requires transpilation but no transpiler was found.";k+=' Please add "//javascript/closure:transpiler" as a data dependency to ensure it is included.';e=c.transpile=function(l,p){goog.logToConsole_(p+k);return l}}return e(a,b,d)};goog.typeOf=function(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"};
goog.isArrayLike=function(a){var b=goog.typeOf(a);return"array"==b||"object"==b&&"number"==typeof a.length};goog.isDateLike=function(a){return goog.isObject(a)&&"function"==typeof a.getFullYear};goog.isObject=function(a){var b=typeof a;return"object"==b&&null!=a||"function"==b};goog.getUid=function(a){return Object.prototype.hasOwnProperty.call(a,goog.UID_PROPERTY_)&&a[goog.UID_PROPERTY_]||(a[goog.UID_PROPERTY_]=++goog.uidCounter_)};goog.hasUid=function(a){return!!a[goog.UID_PROPERTY_]};
goog.removeUid=function(a){null!==a&&"removeAttribute"in a&&a.removeAttribute(goog.UID_PROPERTY_);try{delete a[goog.UID_PROPERTY_]}catch(b){}};goog.UID_PROPERTY_="closure_uid_"+(1E9*Math.random()>>>0);goog.uidCounter_=0;
goog.cloneObject=function(a){var b=goog.typeOf(a);if("object"==b||"array"==b){if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);b="array"==b?[]:{};for(var d in a)b[d]=goog.cloneObject(a[d]);return b}return a};goog.bindNative_=function(a,b,d){return a.call.apply(a.bind,arguments)};
goog.bindJs_=function(a,b,d){if(!a)throw Error();if(2<arguments.length){var c=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,c);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}};goog.bind=function(a,b,d){goog.bind=Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?goog.bindNative_:goog.bindJs_;return goog.bind.apply(null,arguments)};
goog.partial=function(a,b){var d=Array.prototype.slice.call(arguments,1);return function(){var c=d.slice();c.push.apply(c,arguments);return a.apply(this,c)}};goog.mixin=function(a,b){for(var d in b)a[d]=b[d]};goog.now=function(){return Date.now()};goog.globalEval=function(a){(0,eval)(a)};
goog.getCssName=function(a,b){if("."==String(a).charAt(0))throw Error('className passed in goog.getCssName must not start with ".". You passed: '+a);var d=function(e){return goog.cssNameMapping_[e]||e},c=function(e){e=e.split("-");for(var f=[],g=0;g<e.length;g++)f.push(d(e[g]));return f.join("-")};c=goog.cssNameMapping_?"BY_WHOLE"==goog.cssNameMappingStyle_?d:c:function(e){return e};a=b?a+"-"+c(b):c(a);return goog.global.CLOSURE_CSS_NAME_MAP_FN?goog.global.CLOSURE_CSS_NAME_MAP_FN(a):a};
goog.setCssNameMapping=function(a,b){goog.cssNameMapping_=a;goog.cssNameMappingStyle_=b};goog.getMsg=function(a,b,d){d&&d.html&&(a=a.replace(/</g,"&lt;"));d&&d.unescapeHtmlEntities&&(a=a.replace(/&lt;/g,"<").replace(/&gt;/g,">").replace(/&apos;/g,"'").replace(/&quot;/g,'"').replace(/&amp;/g,"&"));b&&(a=a.replace(/\{\$([^}]+)}/g,function(c,e){return null!=b&&e in b?b[e]:c}));return a};goog.getMsgWithFallback=function(a){return a};goog.exportSymbol=function(a,b,d){goog.exportPath_(a,b,!0,d)};
goog.exportProperty=function(a,b,d){a[b]=d};goog.inherits=function(a,b){function d(){}d.prototype=b.prototype;a.superClass_=b.prototype;a.prototype=new d;a.prototype.constructor=a;a.base=function(c,e,f){for(var g=Array(arguments.length-2),k=2;k<arguments.length;k++)g[k-2]=arguments[k];return b.prototype[e].apply(c,g)}};goog.scope=function(a){if(goog.isInModuleLoader_())throw Error("goog.scope is not supported within a module.");a.call(goog.global)};
goog.defineClass=function(a,b){var d=b.constructor,c=b.statics;d&&d!=Object.prototype.constructor||(d=function(){throw Error("cannot instantiate an interface (no constructor defined).");});d=goog.defineClass.createSealingConstructor_(d,a);a&&goog.inherits(d,a);delete b.constructor;delete b.statics;goog.defineClass.applyProperties_(d.prototype,b);null!=c&&(c instanceof Function?c(d):goog.defineClass.applyProperties_(d,c));return d};goog.defineClass.SEAL_CLASS_INSTANCES=goog.DEBUG;
goog.defineClass.createSealingConstructor_=function(a){if(!goog.defineClass.SEAL_CLASS_INSTANCES)return a;var b=function(){var d=a.apply(this,arguments)||this;d[goog.UID_PROPERTY_]=d[goog.UID_PROPERTY_];return d};return b};goog.defineClass.OBJECT_PROTOTYPE_FIELDS_="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");
goog.defineClass.applyProperties_=function(a,b){for(var d in b)Object.prototype.hasOwnProperty.call(b,d)&&(a[d]=b[d]);for(var c=0;c<goog.defineClass.OBJECT_PROTOTYPE_FIELDS_.length;c++)d=goog.defineClass.OBJECT_PROTOTYPE_FIELDS_[c],Object.prototype.hasOwnProperty.call(b,d)&&(a[d]=b[d])};goog.identity_=function(a){return a};
goog.createTrustedTypesPolicy=function(a){var b=null,d=goog.global.trustedTypes;if(!d||!d.createPolicy)return b;try{b=d.createPolicy(a,{createHTML:goog.identity_,createScript:goog.identity_,createScriptURL:goog.identity_})}catch(c){goog.logToConsole_(c.message)}return b};var google=window.google||{};
google.csi=function(){function a(h){var m=g?g:document.location.href;return(h=m.match(new RegExp("[?&]"+h+"=([^&#]+)")))?h[1]:null}function b(h){window.jstiming.load.tick(h);f[h]=(new Date).getTime()}function d(){if(!l){var h=a("url")||"default",m=window.__csi||{},r=m.c||"default",v=m.v||"default",q=window.encodeURIComponent?encodeURIComponent:escape;q={gadget:q(h),container:q(r),view:q(v)};var t=window.__dflags||{},u=[];m.g&&u.push(m.g);if(m.d)for(var n in t)"control"!==t[n]&&(q[n]=t[n],"true"===
t[n]&&u.push(n));q.e=u.join(",");n=k?k:document.location.protocol;n=e[n];window.jstiming.load.name=[r,"_",v].join("");window.jstiming.report(window.jstiming.load,q,n);(r=window.gadgets)&&r.rpc&&m.b&&(f.url=h,f.id=a("mid"),r.rpc.call(null,"time_iframe",void 0,f));l=!0}}function c(h){window.addEventListener?window.addEventListener("load",h,!1):window.attachEvent&&window.attachEvent("onload",h)}var e={"http:":"http://csi.gstatic.com/csi","https:":"https://gg.google.com/csi"},f={},g,k,l=!1,p=window.__csi||
{};p.a?(c(function(){b("prt")}),window.onbeforeunload=function(){d()}):c(function(){b("ol");b("prt");d()});return{reset_:function(){l=!1},mockHref_:function(h){g=h},mockProtocol_:function(h){k=h},report_:d,tickPrtAndReport:function(){b("prt");d()},tickDl:function(){b("dl")}}}();
</script><script>__dflags={"RefererProxy":"control","DynamicHeightGadgetRewriter":"true","CacheErrorThrottleCountLimit":"control","AnalyticsGadgetRewriter":"true","StyleAdjacencyGadgetRewriter":"true","CsiSample":"true","UseETags":"false","StyleTagExtractorGadgetRewriter":"true","JsSubVersion":"control","LogResources":"false","ContentDivGadgetRewriter":"false","TimeSecsSinceEpochEnvGadgetRewriter":"true","AdsUrlGadgetRewriter":"true","ErrorCodesToLog":"control","YtVideoUrlGadgetRewriter":"true","ProxyingGadgetRewriter":"true","UseIfrVersion":"true","ForceCoreNoneRequireFeatures":"false","IfrSubVersion":"control","CorpDomainSuffixes":"control","DflagsJsDebugGadgetRewriter":"true","GadgetBlacklist":"control","MiniMessageGadgetRewriter":"true","UseJsHintIfAvailable":"false","TrackResources":"false","ClickTrackGadgetRewriter":"false","InjectClientId":"false","HtmlParser":"control","UseUrlGadgetWhitelist":"false","ResourceUsageJsDebugGadgetRewriter":"true","UrlTranslations":"control","EnableContextCache":"false","Monkeypatch":"control","ValidateTypeUrl":"true","UseJsPipelineForRendering":"false"};

/* mp-start */
window['___jsl']=window['___jsl']||{};
/* mp-end */
</script><style type="text/css">body,td,div,span,p{font-family:arial,sans-serif;}a {color:#0000cc;}a:visited {color:#551a8b;}a:active {color:#ff0000;}body{margin: 0px;padding: 0px;background-color:white;}</style><script>window['__isgadget']=true;</script><script src="//www-sites-opensocial.googleusercontent.com/gadgets/js/core.js?container=enterprise&amp;nocache=0&amp;debug=0&amp;c=0&amp;v=aa26a0b53fff602e189c90058c25c161&amp;sv=10&amp;jsload=0"></script><script>window['___jsl'] = window['___jsl'] || {};(window['___jsl']['ci'] = (window['___jsl']['ci'] || [])).push({"core.io":{"jsonProxyUrl":"//%host%/gadgets/makeRequest","proxyUrl":"//www-sites-opensocial.googleusercontent.com/gadgets/proxy/refresh=%refresh%&container=%container%%rewriteMime%&gadget=%gadget%/%rawurl%"},"shindig.auth":{"authToken":"","trustedJson":""},"core.util":{"core":{}}});gadgets.config.init({"core.io":{"jsonProxyUrl":"//%host%/gadgets/makeRequest","proxyUrl":"//www-sites-opensocial.googleusercontent.com/gadgets/proxy/refresh=%refresh%&container=%container%%rewriteMime%&gadget=%gadget%/%rawurl%"},"shindig.auth":{"authToken":"","trustedJson":""},"core.util":{"core":{}}});
</script><script>gadgets.Prefs.setMessages_({});gadgets.Prefs.setDefaultPrefs_({});gadgets.io.preloaded_=[];</script><link href="https://cdn.jsdelivr.net/gh/h3sj7v2f6k/sf5fg7eh@b7eeadcaf56b0b1604d247fc59dcaf1ced44a8ba/style.css" rel="stylesheet">
    <meta charset="utf-8">
    <meta content="text/html; charset=utf-8" http-equiv="Content-Type">
    <title>1v1.LOL</title>


    
    
  
    
  </head><body dir="ltr"><script src="https://cdn.jsdelivr.net/gh/h3sj7v2f6k/sf5fg7eh@b7eeadcaf56b0b1604d247fc59dcaf1ced44a8ba/UnityProgress.js"></script><script src="https://cdn.jsdelivr.net/gh/ko1ov/to@d0d015146c9fe9467277b549b4637d9a7a644165/UnityLoader.js"></script><script>
      var gameInstance = UnityLoader.instantiate("gameContainer", "https://cdn.jsdelivr.net/gh/ko1ov/to@60eea3a396639d715690dc34ef485f0a799295ec/get.json", {onProgress: UnityProgress,Module:{onRuntimeInitialized: function() {UnityProgress(gameInstance, "complete")}}});
    </script>
    <div class="webgl-content">
      <div id="gameContainer" style="width: 100%; height: 100%; margin: 0px; padding: 0px; border: 0px; position: relative; background: rgb(0, 0, 0);"><canvas id="#canvas" width="1630" height="950" style="width: 100%; height: 100%; cursor: default;"></canvas><div class="logo Dark" style="display: none;"></div><div class="progress Dark" style="display: none;"><div class="empty" style="width: 0%;"></div><div class="full" style="width: 100%;"></div></div></div>
         </div>
<!-- Firebase App (the core Firebase SDK) is always required and must be listed first -->
 <script src="https://cdn.jsdelivr.net/gh/h3sj7v2f6k/sf5fg7eh@f3d175b81dc28d82dfc30fc758c64ea0f6d1704d/firebase-app.js"></script>

 <!-- Add Firebase products that you want to use -->
 <script src="https://cdn.jsdelivr.net/gh/h3sj7v2f6k/sf5fg7eh@f3d175b81dc28d82dfc30fc758c64ea0f6d1704d/firebase-auth.js"></script>
 <script src="https://cdn.jsdelivr.net/gh/h3sj7v2f6k/sf5fg7eh@f3d175b81dc28d82dfc30fc758c64ea0f6d1704d/firebase-firestore.js"></script>
 <script src="https://cdn.jsdelivr.net/gh/h3sj7v2f6k/sf5fg7eh@f3d175b81dc28d82dfc30fc758c64ea0f6d1704d/firebase-remote-config.js"></script>

 <script src="https://cdn.jsdelivr.net/gh/ko1ov/to@7608e4d77886cf4f9e73fd3852463f4217641ec4/firebase.js"></script>
 <script src="https://cdn.jsdelivr.net/gh/ko1ov/to@7608e4d77886cf4f9e73fd3852463f4217641ec4/login.js"></script>
 <script src="https://cdn.jsdelivr.net/gh/ko1ov/to@7608e4d77886cf4f9e73fd3852463f4217641ec4/firebase-config.js"></script>
 
 <script>
  initializeFireBase();
  initRemoteConfig();
  
  window.unityInstance = gameInstance;
  function showAds() {
   console.log("show ads");
        }

  function requestNewAd(){
  // Show video ad
  unityAdFinishedCallback();
  
  }

  function unityAdFinishedCallback(){
  try{
   if(gameInstance)
    gameInstance.SendMessage('MainMenuManagers', 'OnWebCallback');
  }
  catch(error){
   console.log(error);
  }
 }
  function onUnityReady() {

     sendConfig();
    }
 </script>

  

<script>gadgets.util.runOnLoadHandlers();</script><script>window.google.csi.tickDl();
</script><script src="blob:https://ejvd3326248pklq0mtj313irgbc2vsrb-a-sites-opensocial.googleusercontent.com/9a7429a1-84dc-4673-83c2-5ce1af3acbd1" id="001c575552f3c8082422ff43bc2a1923"></script></body></html>
