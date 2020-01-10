(function(){/* 
 
 Copyright The Closure Library Authors. 
 SPDX-License-Identifier: Apache-2.0 
*/ 
'use strict';var b=document;class e{constructor(){const c=b.head,f=c.querySelectorAll("link[data-reload-stylesheet][as=style][rel=preload]");for(let d=0;d<f.length;d++){const h=f[d];var a="link",g=document;a=String(a);"application/xhtml+xml"===g.contentType&&(a=a.toLowerCase());a=g.createElement(a);a.setAttribute("rel","stylesheet");a.setAttribute("href",h.getAttribute("href"));c.appendChild(a)}}};(function(){const c=()=>{new e};"complete"===b.readyState||"interactive"===b.readyState?new e:b.addEventListener&&b.addEventListener("DOMContentLoaded",c,!1)})();}).call(this);
