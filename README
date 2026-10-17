# LumiO-!DOCTYPE LumiOooreo
<html lang="en"><head><meta charset="utf-8"><title>Lumio</title>
<meta name="theme-color" content="#6d4aff"><link rel="manifest" href="manifest.json"><link rel="icon" href="icons/icon-192.png"><link rel="apple-touch-icon" href="icons/icon-192.png"><meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<style>
:root{--bg:#fafaff;--sf:#ffffff;--tx:#14122b;--mu:#6b6890;--bd:#e4e2f5;--ub:#6d4aff;--ut:#fff;--a:#6d4aff;--b:#00c2ff;color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0c0a1d;--sf:#16133a;--tx:#f1efff;--mu:#9a96c8;--bd:#2a2660;color-scheme:dark}}
:root[data-theme="dark"]{--bg:#0c0a1d;--sf:#16133a;--tx:#f1efff;--mu:#9a96c8;--bd:#2a2660;color-scheme:dark}
*{box-sizing:border-box}html,body{height:100%;margin:0}
body{background:var(--bg);color:var(--tx);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;display:flex;overflow:hidden}
#side{width:270px;background:var(--sf);border-right:1px solid var(--bd);display:flex;flex-direction:column;padding:12px;gap:8px;flex:0 0 auto;transition:transform .25s;z-index:5}
.brand{display:flex;align-items:center;gap:10px;font-weight:800;font-size:22px;letter-spacing:-.5px}
button{font:inherit;color:inherit;border:0;cursor:pointer}
.nb{background:linear-gradient(135deg,var(--a),var(--b));color:#fff;border-radius:12px;padding:11px;font-weight:600}
#list{flex:1;overflow:auto;display:flex;flex-direction:column;gap:4px}
.it{display:flex;align-items:center;border-radius:10px;padding:9px 10px;font-size:14px;background:transparent}
.it.on{background:var(--bg)}.it span{flex:1;overflow:hidden;white-space:nowrap;text-overflow:ellipsis}.it b{color:var(--mu);padding:0 4px}
#main{flex:1;display:flex;flex-direction:column;min-width:0;height:100%}
header{display:flex;align-items:center;gap:10px;padding:10px 14px;border-bottom:1px solid var(--bd);background:var(--sf)}
header button{background:none;font-size:20px;padding:4px 8px}#menu{display:none}header .t{flex:1;font-weight:600}
#msgs{flex:1;overflow:auto;padding:16px 12px}
.w{max-width:760px;margin:0 auto}
.m{display:flex;gap:10px;margin:14px 0}.m.u{justify-content:flex-end}
.bub{padding:11px 14px;border-radius:18px;max-width:88%;line-height:1.55;font-size:16px;white-space:pre-wrap;word-wrap:break-word;overflow-wrap:anywhere}
.u .bub{background:var(--ub);color:var(--ut);border-bottom-right-radius:6px}
.a .bub{background:var(--sf);border:1px solid var(--bd);border-bottom-left-radius:6px}
.av{width:30px;height:30px;flex:0 0 30px}
pre{background:#0d0b24;color:#e9e6ff;padding:12px;border-radius:12px;overflow-x:auto;white-space:pre;font-size:13px;margin:8px 0}
code{font-family:ui-monospace,Menlo,monospace;background:#8b7cff22;padding:1px 5px;border-radius:6px;font-size:.92em}pre code{background:none;padding:0}
.cp{display:block;margin-top:6px;background:none;color:var(--mu);font-size:13px;padding:0}
.hero{text-align:center;margin-top:8vh}.hero h2{font-size:30px;margin:14px 0 4px}.hero p{color:var(--mu);margin:0 0 20px}
.chips{display:flex;flex-wrap:wrap;gap:8px;justify-content:center}.chips button{background:var(--sf);border:1px solid var(--bd);border-radius:999px;padding:9px 14px;font-size:14px}
footer{padding:10px 12px 12px}.bar{max-width:760px;margin:auto;display:flex;gap:8px;align-items:flex-end;background:var(--sf);border:1px solid var(--bd);border-radius:22px;padding:8px}
textarea{flex:1;border:0;outline:0;background:transparent;color:var(--tx);font:inherit;font-size:16px;resize:none;max-height:140px;padding:8px 10px}
#send{width:40px;height:40px;border-radius:50%;background:linear-gradient(135deg,var(--a),var(--b));color:#fff;font-size:18px}
.note{text-align:center;color:var(--mu);font-size:12px;margin-top:6px}
@media(max-width:760px){#side{position:fixed;inset:0 auto 0 0;height:100%;transform:translateX(-100%)}#side.open{transform:none;box-shadow:0 0 40px #0008}#menu{display:block}}
</style></head><body>
<svg width="0" height="0" style="position:absolute"><defs><linearGradient id="lg" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#7c4dff"/><stop offset="1" stop-color="#00d4ff"/></linearGradient>
<symbol id="logo" viewBox="0 0 64 64"><rect width="64" height="64" rx="18" fill="url(#lg)"/><circle cx="32" cy="32" r="13" fill="#fff" opacity=".95"/><path d="M32 8l3 11 11 3-11 3-3 11-3-11-11-3 11-3z" fill="#fff" opacity=".0"/><path d="M47 12l1.8 5.2L54 19l-5.2 1.8L47 26l-1.8-5.2L40 19l5.2-1.8z" fill="#fff"/><circle cx="32" wait a moment and try again.":"Sorry, something went wrong. Please try again."}
busy=false;ctl=null;$("send").textContent="➤";sv();show()}
$("send").onclick=()=>busy?(ctl&&ctl.abort()):send();
$("in").addEventListener("keydown",e=>{if(e.key=="Enter"&&!e.shiftKey&&innerWidth>760){e.preventDefault();send()}});
$("in").addEventListener("input",e=>{e.target.style.height="auto";e.target.style.height=Math.min(e.target.scrollHeight,140)+"px"});
$("new").onclick=()=>{cur=null;$("side").classList.remove("open");show()};$("menu").onclick=()=>$("side").classList.toggle("open");
$("clear").onclick=()=>{chats=[];cur=null;sv();show()};
$("theme").onclick=()=>{const r=document.documentElement,d=r.dataset.theme=="dark"||(!r.dataset.theme&&matchMedia("(prefers-color-scheme:dark)").matches);r.dataset,busy=false,ctl=null;
const ld=()=>{try{chats=JSON.parse(localStorage.getItem("lumio")||"[]")}catch(e){chats=[]}};
const sv=()=>{try{localStorage.setItem("lumio",JSON.stringify(chats.slice(0,60)))}catch(e){}};
const esc=s=>s.replace(/&/g,"&amp;").replace(/</g,"&lt;").replace(/>/g,"&gt;");
function md(t){const parts=esc(t).split("```");return parts.map((p,i)=>{if(i%2){const nl=p.indexOf("\n");return"<pre><code>"+(nl>=0?p.slice(nl+1):p).replace(/\n$/,"")+"</code></pre>"}
return p.replace(/`([^`\n]+)`/g,"<code>$1</code>").replace(/\*\*([^*\n]+)\*\*/g,"<b>$1</b>").replace(/^#{1,3} (.+)$/gm,"<b>$1</b>")}).join("")}
function row(m){const d=document.createElement("div");d.className="m "+(m.r=="u"?"u":"a");
d.innerHTML=(m.r=="u"?"":'<svg class="av"><use href="#logo"/></svg>')+'<div class="bub"></div>';
const b=d.querySelector(".bub");if(m.r=="u")b.textContent=m.t;else{b.innerHTML=md(m.t||"…");const c=document.createElement("button");c.className="cp";c.textContent="Copy";c.onclick=()=>{navigator.clipboard.writeText(m.t).then(()=>{c.textContent="Copied ✓";setTimeout(()=>c.textContent="Copy",1500)}).catch(()=>{})};b.append(c)}
$("w").append(d);return b}
function show(){const w=$("w");w.innerHTML="";const c=chats.find(x=>x.id==cur);$("ttl").textContent=c?c.title:"Lumio";
if(!c||!c.m.length){w.innerHTML='<div class="hero"><svg width="84" height="84"><use href="#logo"/></svg><h2>Hi, I’m Lumio</h2><p>Ask anything. Chat in any language. No limits.</p><div class="chips"></div></div>';
SUG.forEach(s=>{const b=document.createElement("button");b.textContent=s;b.onclick=()=>send(s);w.querySelector(".chips").append(b)})}
else c.m.forEach(row);bot();list()}
const bot=()=>{$("msgs").scrollTop=$("msgs").scrollHeight};
function list(){const l=$("list");l.innerHTML="";chats.forEach(c=>{const d=document.createElement("div");d.className="it"+(c.id==cur?" on":"");d.innerHTML="<span></span><b>✕</b>";d.firstChild.textContent=c.title;
d.firstChild.onclick=()=>{cur=c.id;$("side").classList.remove("open");show()};d.lastChild.onclick=()=>{chats=chats.filter(x=>x.id!=c.id);if(cur==c.id)cur=null;sv();show()};l.append(d)})}
async function send(txt){txt=(txt||$("in").value).trim();if(!txt||busy)return;
let c=chats.find(x=>x.id==cur);if(!c){c={id:Date.now(),title:txt.slice(0,40),m:[]};chats.unshift(c);cur=c.id}
c.m.push({r:"u",t:txt});$("in").value="";$("in").style.height="auto";show();
const msg={r:"a",t:""};c.m.push(msg);const b=row(msg);b.textContent="…";bot();busy=true;$("send").textContent="■";
try{ctl=new AbortController();const hist=c.m.slice(0,-1).slice(-30).map(x=>({role:x.r=="u"?"user":"assistant",content:x.t}));const r=await fetch("/api/chat",{method:"POST",headers:{"Content-Type":"application/json"},body:JSON.stringify({messages:hist}),signal:ctl.signal});if(r.status==429)throw{code:"rate_limited"};if(!r.ok)throw 0;const j=await r.json();msg.t=j.text;b.innerHTML=md(j.text);bot()}
catch(e){if(!msg.t)msg.t=e&&e.name=="AbortError"?"Stopped.":e&&e.code=="rate_limited"?"Too many requests right now — please wait a moment and try again.":"Sorry, something went wrong. Please try again."}
busy=false;ctl=null;$("send").textContent="➤";sv();show()}
$("send").onclick=()=>busy?(ctl&&ctl.abort()):send();
$("in").addEventListener("keydown",e=>{if(e.key=="Enter"&&!e.shiftKey&&innerWidth>760){e.preventDefault();send()}});
$("in").addEventListener("input",e=>{e.target.style.height="auto";e.target.style.height=Math.min(e.target.scrollHeight,140)+"px"});
$("new").onclick=()=>{cur=null;$("side").classList.remove("open");show()};$("menu").onclick=()=>$("side").classList.toggle("open");
$("clear").onclick=()=>{chats=[];cur=null;sv();show()};
$("theme").onclick=()=>{const r=document.documentElement,d=r.dataset.theme=="dark"||(!r.dataset.theme&&matchMedia("(prefers-color-scheme:dark)").matches);r.dataset.theme=d?"light":"dark"};
ld();show();if("serviceWorker"in navigator)navigator.serviceWorker.register("sw.js").catch(()=>{});
</script></body></html>
 // Lumio сервері. ANTHROPIC_API_KEY — тек Netlify орта айнымалысында.
const H={"Content-Type":"application/json"};
const R=(c,o)=>({statusCode:c,headers:H,body:JSON.stringify(o)});
const SYS="You are Lumio, a brilliant, friendly, all-knowing AI assistant. Answer in the user's language. Be accurate, complete and clear; use short paragraphs, lists and code blocks (```) when helpful. Never refuse harmless requests. Admit uncertainty instead of guessing.";
exports.handler=async(e)=>{
  if(e.httpMethod!=="POST")return R(405,{error:"POST only"});
  try{
    const {messages}=JSON.parse(e.body||"{}");
    if(!Array.isArray(messages)||!messages.length||messages.length>30)return R(400,{error:"bad"});
    const m=messages.map(x=>({role:x.role==="assistant"?"assistant":"user",content:String(x.content||"").slice(0,8000)}));
    if(m[0].role!=="user"||m[m.length-1].role!=="user")return R(400,{error:"bad order"});
    const r=await fetch("https://api.anthropic.com/v1/messages",{method:"POST",
      headers:{"content-type":"application/json","x-api-key":process.env.ANTHROPIC_API_KEY,"anthropic-version":"2023-06-01"},
      body:JSON.stringify({model:"claude-haiku-5-5",max_tokens:2000,system:SYS,messages:m})});
    if(r.status===429)return R(429,{error:"rate"});
    const d=await r.json();
    if(!r.ok)return R(502,{error:"api"});
    return R(200,{text:(d.content||[]).map(c=>c.text||"").join("")});
  }catch(err){return R(500,{error:"server"})}
};
const C="lumio-v1";self.addEventListener("install",e=>e.waitUntil(caches.open(C).then(c=>c.addAll(["./","index.html","manifest.json"]))));
self.addEventListener("fetch",e=>{if(e.request.method!=="GET")return;e.respondWith(fetch(e.request).catch(()=>caches.match(e.request)))});
{"name":"Lumio","short_name":"Lumio","description":"Your smart AI assistant","start_url":"./index.html","display":"standalone","background_color":"#0c0a1d","theme_color":"#6d4aff","icons":[{"src":"icons/icon-192.png","sizes":"192x192","type":"image/png"},{"src":"icons/icon-512.png","sizes":"512x512","type":"image/png"},{"src":"icons/maskable-512.png","sizes":"512x512","type":"image/png","purpose":"maskable"}]}
