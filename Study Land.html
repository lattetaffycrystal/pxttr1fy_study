<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Study Land</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&family=Playfair+Display:ital,wght@1,500&family=Gaegu:wght@400;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#1c2330;--ink:#4a4a4a;--card:#f4f4f4;--tile:#e4e4e4;--pink:#f3b9c6}
@media (prefers-color-scheme:dark){:root{--bg:#10141c}}
:root[data-theme="light"]{--bg:#dfe6ee}
*{box-sizing:border-box}
html,body{margin:0}
body{background:var(--bg);font-family:Roboto,Arial,sans-serif;color:var(--ink);padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);display:flex;flex-direction:column;align-items:center}
.tools{padding:10px;display:flex;gap:8px;flex-wrap:wrap;justify-content:center}
.tools button{font:500 13px Roboto;padding:7px 12px;border-radius:999px;border:1px solid #fff8;background:#fff;color:#333;cursor:pointer}
#wrap{width:100%;overflow:hidden}
#canvas{position:relative;width:736px;height:1307px;transform-origin:0 0;overflow:hidden;
 background:linear-gradient(#b9cde6 0%,#d7e2ef 35%,#a9b4c2 60%,#8f98a3 100%);background-size:cover;background-position:center}
.abs{position:absolute}
[contenteditable]{outline:none}
[contenteditable]:focus{background:#ffe9f0;border-radius:4px}
.tab{cursor:text;z-index:5}.tab.on{background:var(--pink);color:#fff}
.bar{z-index:4}
.panel{display:none;left:22px;top:104px;width:692px;height:420px;z-index:20;background:#fff;border-radius:16px;box-shadow:0 8px 24px #0006;padding:22px 26px;font-size:19px;line-height:1.6}
.panel h2{margin:0 0 10px;font-size:26px}
.panel .body{height:320px;overflow:auto;white-space:pre-wrap}
.panel .x{position:absolute;right:14px;top:10px;width:34px;height:34px;border-radius:50%;border:0;background:#eee;font-size:20px;cursor:pointer}
/* browser bar */
.tab{top:16px;height:33px;background:#f4f4f4;border:2px solid #fff;border-bottom:0;border-radius:6px 6px 0 0;font-size:17px;letter-spacing:1px;text-align:center;line-height:32px;box-shadow:0 2px 6px #0003}
.bar{left:0;top:48px;width:100%;height:46px;background:#fff;border-bottom:2px solid #ccd;box-shadow:0 3px 8px #0003}
.dots{left:26px;top:20px;font-size:26px;letter-spacing:2px;line-height:10px}
.url{left:143px;top:6px;width:451px;height:34px;border:2px solid #555;border-radius:10px;background:#f6f6f6;text-align:center;font-style:italic;font-size:16px;line-height:30px;letter-spacing:.5px}
.home{right:48px;top:14px;font-weight:700;font-size:17px;letter-spacing:1px}
.pill{left:398px;top:116px;width:294px;height:34px;border-radius:999px;background:#f7f7f7;border:2px solid #fff;box-shadow:0 2px 6px #0003;text-align:center;line-height:30px;font-size:19px;letter-spacing:.5px}
/* side card */
.side{left:22px;top:171px;width:288px;height:887px;background:var(--card);border-radius:18px;box-shadow:0 4px 14px #0004;padding:18px 14px}
.head{display:flex;gap:12px;align-items:center;margin-left:8px}
.head b{display:block;font-size:22px;font-weight:700;color:#444}
.head small{font-size:14px;color:#777}
.greet{font-size:15px;color:#555;margin:14px 6px 12px;line-height:1.35}
.tile{height:172px;background:var(--tile);border-radius:6px;margin-bottom:17px;border:1px solid #d2d2d2;box-shadow:inset 0 0 0 2px #f0f0f0;padding:10px 12px;position:relative}
.tile h3{margin:2px 0 8px;text-align:center;font-size:21px;font-weight:700;color:#4d4d4d}
.tile .ic{position:absolute;left:16px;top:60px;width:118px;height:96px;display:flex;align-items:center;justify-content:center;font-size:74px;filter:drop-shadow(0 4px 4px #0003)}
.tile p{position:absolute;left:152px;top:52px;width:112px;margin:0;font-size:13.5px;line-height:1.3;color:#555}
.ic,.cambar{cursor:pointer}.ic img{width:100%;height:100%;object-fit:contain}.cambar img{height:38px;width:auto;object-fit:contain}
/* photos */
.title{left:338px;top:176px;width:340px;font-family:'Playfair Display',serif;font-style:italic;font-weight:500;font-size:62px;color:#fff;text-shadow:0 2px 0 #9ab,0 4px 10px #0005;line-height:1;transform:rotate(-3deg)}
.sub{left:366px;top:243px;width:248px;height:50px;background:var(--pink);font-family:'Playfair Display',serif;font-style:italic;font-size:34px;color:#fff;text-align:center;line-height:50px;transform:rotate(-2deg);z-index:3;box-shadow:0 2px 6px #0003}
.slot{background:#e9e0e4;border:6px solid #fff;box-shadow:0 6px 16px #0005;cursor:pointer;overflow:hidden;display:flex;align-items:center;justify-content:center;text-align:center;color:#a07a86;font-weight:500}
.slot img{width:100%;height:100%;object-fit:cover;display:block}
.slot span{font-size:17px;line-height:1.5;padding:10px}
.p1{left:345px;top:252px;width:350px;height:430px;transform:rotate(1deg);z-index:2}
.p2{left:352px;top:688px;width:350px;height:398px;transform:rotate(1deg);z-index:2}
.tape{left:340px;top:340px;width:22px;height:340px;background:repeating-linear-gradient(#222 0 10px,#fff 10px 20px);border:2px solid #fff;z-index:1;opacity:.9}
.paper{left:356px;top:668px;width:296px;height:44px;background:#fff;transform:rotate(1deg);box-shadow:0 2px 6px #0003;z-index:1}
.cap{font-family:Gaegu,cursive;font-weight:700;color:#fff;font-size:21px;line-height:1.15;text-align:center;text-shadow:0 1px 3px #000a;z-index:4;width:110px}
/* bottom */
.cambar{left:0;top:1106px;width:100%;height:50px;background:#fff;border-top:2px solid #ddd;display:flex;align-items:center;justify-content:center;font-size:30px;box-shadow:0 -3px 8px #0003}
.strip{left:0;top:1156px;width:100%;height:151px;background:#fff;display:flex;gap:11px;padding:12px 24px}
.th{flex:1;border:5px solid #f0f0f0;border-radius:8px;height:92px;box-shadow:0 3px 7px #0004;background:#e6e1e4;overflow:hidden;cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:26px;color:#b49aa5}
.th img{width:100%;height:100%;object-fit:cover}
</style>
</head>
<body>
<div class="tools">
 <button id="bgBtn">Change background</button>
 <button id="resetBg">Reset background</button>
 <button id="curBtn">Custom cursor</button>
 <button id="curReset">Reset cursor</button>
 <input type="file" id="curFile" accept="image/*" hidden>
 <button id="thm">Toggle light/dark page</button>
 <span style="color:#9ab;font-size:13px;align-self:center">Click any photo to upload · click any text to edit</span>
</div>
<div id="wrap"><div id="canvas">
 <div class="abs tab" data-p="p1" style="left:27px;width:110px" contenteditable="true">notes</div>
 <div class="abs tab" data-p="p2" style="left:164px;width:110px" contenteditable="true">goals</div>
 <div class="abs bar">
  <div class="abs dots">•••</div>
  <div class="abs url"><span contenteditable="true">www.study space, focus.com</span></div>
  <div class="abs home">HOME</div>
 </div>
 <div class="abs pill" contenteditable="true">my study dumps</div>
 <div class="abs panel" id="p1"><button class="x">×</button><h2 contenteditable="true">my notes</h2><div class="body" contenteditable="true">• Chapter 4 summary
• Key formulas to memorise
• Questions to ask my teacher</div></div>
 <div class="abs panel" id="p2"><button class="x">×</button><h2 contenteditable="true">my goals</h2><div class="body" contenteditable="true">• Finish revision by Friday
• Study 2 hours every day
• Get 90% on the next test</div></div>

 <div class="abs side">
  <div class="head"><span style="font-size:34px">📍</span><div><b contenteditable="true">Study Land</b><small contenteditable="true">focus in your zone</small></div></div>
  <div class="greet" contenteditable="true">ⓘ&nbsp; good evening to all of you! how is studying today? is your focus going well?</div>
  <div class="tile"><h3 contenteditable="true">pink notebook for today</h3><label class="ic"><span>📓</span><input type="file" accept="image/*" hidden></label><p contenteditable="true">today I have a big exam to prepare for! so I'm filling this notebook with neat notes. how about you? ready to review?</p></div>
  <div class="tile"><h3 contenteditable="true">a strawberry break</h3><label class="ic"><span>🍰</span><input type="file" accept="image/*" hidden></label><p contenteditable="true">after 45 minutes of focus I reward myself with a slice of cake with my study buddy! deserve it? yes!</p></div>
  <div class="tile"><h3 contenteditable="true">iced coffee for me</h3><label class="ic"><span>🧋</span><input type="file" accept="image/*" hidden></label><p contenteditable="true">I really need caffeine to get through my reading list! sip, then flip the page. so good for focus!</p></div>
  <div class="tile"><h3 contenteditable="true">highlighters &amp; stickers</h3><label class="ic"><span>🖍️</span><input type="file" accept="image/*" hidden></label><p contenteditable="true">phew, I always carry my highlighters because key ideas must be marked all the time!</p></div>
 </div>

 <div class="abs title" contenteditable="true">wednesday</div>
 <div class="abs sub" contenteditable="true">study with me</div>
 <div class="abs tape"></div><div class="abs paper"></div>
 <label class="abs slot p1"><span>＋<br>upload photo 1</span><input type="file" accept="image/*" hidden></label>
 <label class="abs slot p2"><span>＋<br>upload photo 2</span><input type="file" accept="image/*" hidden></label>
 <div class="abs cap" style="left:398px;top:365px" contenteditable="true">my desk setup for finals week!!</div>
 <div class="abs cap" style="left:372px;top:800px" contenteditable="true">look at my study notes, so neat right?!</div>

 <label class="abs cambar"><span>📷</span><input type="file" accept="image/*" hidden></label>
 <div class="abs strip">
  <label class="th">＋<input type="file" accept="image/*" hidden></label>
  <label class="th">＋<input type="file" accept="image/*" hidden></label>
  <label class="th">＋<input type="file" accept="image/*" hidden></label>
  <label class="th">＋<input type="file" accept="image/*" hidden></label>
  <label class="th">＋<input type="file" accept="image/*" hidden></label>
 </div>
</div></div>
<input type="file" id="bgFile" accept="image/*" hidden>
<script>
const cv=document.getElementById('canvas'),wrap=document.getElementById('wrap');
function fit(){const s=Math.min(1,wrap.clientWidth/736);cv.style.transform='scale('+s+')';wrap.style.height=(1307*s)+'px';wrap.style.width=Math.min(736,innerWidth)+'px'}
addEventListener('resize',fit);fit();
document.querySelectorAll('input[type=file]:not(#bgFile):not(#curFile)').forEach(i=>i.addEventListener('change',e=>{
 const f=e.target.files[0];if(!f)return;
 const r=new FileReader();r.onload=()=>{const l=i.parentElement;l.querySelectorAll('img,span').forEach(n=>n.remove());
  if(l.classList.contains('th'))l.firstChild.textContent='';
  const im=new Image();im.src=r.result;l.appendChild(im)};r.readAsDataURL(f)}));
const bgFile=document.getElementById('bgFile');
document.getElementById('bgBtn').onclick=()=>bgFile.click();
bgFile.onchange=e=>{const f=e.target.files[0];if(!f)return;const r=new FileReader();r.onload=()=>{cv.style.backgroundImage='url('+r.result+')'};r.readAsDataURL(f)};
document.getElementById('resetBg').onclick=()=>{cv.style.backgroundImage=''};
document.getElementById('thm').onclick=()=>{const d=document.documentElement;d.dataset.theme=d.dataset.theme==='light'?'':'light'};
const curStyle=document.createElement('style');document.head.appendChild(curStyle);
const curFile=document.getElementById('curFile');
document.getElementById('curBtn').onclick=()=>curFile.click();
curFile.onchange=e=>{const f=e.target.files[0];if(!f)return;const r=new FileReader();r.onload=()=>{const im=new Image();im.onload=()=>{
 const c=document.createElement('canvas');c.width=c.height=48;const x=c.getContext('2d');
 const k=Math.min(48/im.width,48/im.height),w=im.width*k,h=im.height*k;x.drawImage(im,(48-w)/2,(48-h)/2,w,h);
 curStyle.textContent='*,*:hover{cursor:url('+c.toDataURL('image/png')+') 24 24,auto !important}'};im.src=r.result};r.readAsDataURL(f);e.target.value=''};
document.getElementById('curReset').onclick=()=>{curStyle.textContent=''};
document.querySelectorAll('.tab[data-p]').forEach(t=>t.addEventListener('click',()=>{
 document.querySelectorAll('.panel').forEach(x=>x.style.display='none');
 document.querySelectorAll('.tab').forEach(x=>x.classList.remove('on'));
 document.getElementById(t.dataset.p).style.display='block';t.classList.add('on')}));
document.querySelectorAll('.panel .x').forEach(b=>b.onclick=()=>{b.parentElement.style.display='none';document.querySelectorAll('.tab').forEach(x=>x.classList.remove('on'))});
</script>
</body>
</html>
