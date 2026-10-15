<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>منيو الحلويات 🧁</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@500;700;900&family=Lalezar&display=swap" rel="stylesheet">
<style>
:root{--bg1:#ffe3ec;--bg2:#fff3e6;--bg3:#d9f5e8;--ink:#4a2a2a;--mut:#8a6a6a;--card:#fffffff0;--pink:#e8366b;--pink2:#ff7aa2;--line:#f3d3dc;--gold:#ffd36e;--sp1:#ff7aa2;--sp2:#6fcfb0;--sp3:#ffc247;--sp4:#8a7bff;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg1:#3a1a28;--bg2:#2c1c1c;--bg3:#16302a;--ink:#ffeef3;--mut:#d3aab5;--card:#3b2430f0;--line:#5a3646}}
:root[data-theme="dark"]{--bg1:#3a1a28;--bg2:#2c1c1c;--bg3:#16302a;--ink:#ffeef3;--mut:#d3aab5;--card:#3b2430f0;--line:#5a3646}
*{box-sizing:border-box}html{scroll-padding-top:70px}
body{margin:0;font-family:Cairo,Tahoma,sans-serif;color:var(--ink);min-height:100vh;
background:
radial-gradient(circle at 12% 8%,var(--sp1) 0 3px,transparent 4px),
radial-gradient(circle at 70% 30%,var(--sp2) 0 3px,transparent 4px),
radial-gradient(circle at 35% 75%,var(--sp3) 0 3px,transparent 4px),
radial-gradient(circle at 88% 85%,var(--sp4) 0 3px,transparent 4px),
linear-gradient(160deg,var(--bg1),var(--bg2) 50%,var(--bg3));
background-size:90px 90px,130px 130px,110px 110px,150px 150px,100% 100%;background-attachment:fixed}
.hero{text-align:center;padding:34px 16px 18px}
.hero h1{font-family:Lalezar,Cairo,sans-serif;font-weight:400;font-size:clamp(40px,10vw,64px);margin:0;color:var(--pink);line-height:1.15;text-shadow:3px 3px 0 var(--gold)}
.hero p{margin:6px 0 0;color:var(--mut);font-weight:700}
.promo{margin:12px auto 0;display:inline-block;background:var(--pink);color:#fff;padding:6px 16px;border-radius:99px;font-weight:900;font-size:14px}
.tabs{position:sticky;top:env(safe-area-inset-top,0px);z-index:20;display:flex;gap:8px;overflow-x:auto;padding:10px 14px;background:var(--card);backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
.tab{flex:none;border:2px solid var(--line);background:transparent;color:var(--ink);font:700 15px Cairo,sans-serif;padding:7px 16px;border-radius:99px;cursor:pointer}
.tab.on{background:var(--pink);border-color:var(--pink);color:#fff}
main{max-width:980px;margin:0 auto;padding:14px 12px 120px}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
@media(min-width:640px){.grid{grid-template-columns:repeat(3,1fr);gap:16px}}
@media(min-width:900px){.grid{grid-template-columns:repeat(4,1fr)}}
.card{position:relative;background:var(--card);border-radius:18px;overflow:hidden;box-shadow:0 6px 18px #e8366b22;display:flex;flex-direction:column}
.pic{position:relative;aspect-ratio:1;display:grid;place-items:center;font-size:64px;background:linear-gradient(135deg,#ffd1de,#ffe9b8);overflow:hidden}
.pic img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover}
.badge{position:absolute;top:8px;inset-inline-start:8px;background:var(--pink);color:#fff;font-weight:900;font-size:12px;padding:3px 9px;border-radius:99px;z-index:2}
.hot{background:#ff8a00}
.info{padding:10px 11px 12px;display:flex;flex-direction:column;gap:4px;flex:1}
.name{font-weight:900;font-size:15px;line-height:1.35}
.desc{font-size:12px;color:var(--mut);line-height:1.4}
.pr{display:flex;align-items:baseline;gap:6px;margin-top:auto}
.now{font-weight:900;color:var(--pink);font-size:18px}.old{text-decoration:line-through;color:var(--mut);font-size:12px}
.add{margin-top:6px;border:0;background:var(--pink);color:#fff;font:900 14px Cairo,sans-serif;padding:9px;border-radius:12px;cursor:pointer}
.add:active{transform:scale(.96)}
.edit input[type=text],.edit input[type=number]{width:100%;font:700 13px Cairo,sans-serif;padding:5px 7px;border:1px solid var(--line);border-radius:8px;background:transparent;color:var(--ink)}
.up{position:absolute;bottom:6px;inset-inline:6px;z-index:3;background:#000a;color:#fff;text-align:center;font-weight:700;font-size:12px;padding:5px;border-radius:9px;cursor:pointer}
.up input{display:none}
.del{background:none;border:0;color:#d33;font:700 12px Cairo,sans-serif;cursor:pointer;text-align:start}
.bar{position:fixed;inset-inline:0;bottom:0;z-index:30;padding:10px 14px calc(10px + env(safe-area-inset-bottom,0px));display:flex;gap:10px;align-items:center;background:var(--card);backdrop-filter:blur(10px);border-top:1px solid var(--line)}
.cartbtn{flex:1;border:0;background:linear-gradient(90deg,var(--pink),var(--pink2));color:#fff;font:900 16px Cairo,sans-serif;padding:13px;border-radius:14px;cursor:pointer;display:flex;justify-content:space-between;align-items:center}
.cnt{background:#fff;color:var(--pink);border-radius:99px;min-width:24px;padding:0 7px;font-size:14px;text-align:center}
.gear{border:2px solid var(--line);background:transparent;color:var(--ink);border-radius:14px;padding:11px 13px;font-size:18px;cursor:pointer}
.sheet{position:fixed;inset:0;z-index:40;background:#0008;display:none;align-items:flex-end;justify-content:center}
.sheet.open{display:flex}
.panel{width:100%;max-width:520px;max-height:88vh;overflow:auto;background:var(--bg2);border-radius:22px 22px 0 0;padding:16px 16px calc(16px + env(safe-area-inset-bottom,0px))}
.panel h2{font-family:Lalezar,Cairo,sans-serif;font-weight:400;font-size:26px;margin:0 0 10px;color:var(--pink)}
.row{display:flex;gap:10px;align-items:center;padding:9px 0;border-bottom:1px dashed var(--line)}
.th{width:54px;height:54px;border-radius:12px;background:linear-gradient(135deg,#ffd1de,#ffe9b8);display:grid;place-items:center;font-size:28px;overflow:hidden;flex:none}
.th img{width:100%;height:100%;object-fit:cover}
.rn{flex:1;font-weight:700;font-size:14px}.rn small{display:block;color:var(--pink);font-weight:900}
.q{display:flex;align-items:center;gap:8px}.q button{width:30px;height:30px;border-radius:50%;border:2px solid var(--pink);background:transparent;color:var(--pink);font:900 16px Cairo;cursor:pointer}
.tot{display:flex;justify-content:space-between;font-weight:900;font-size:18px;margin:12px 0}
.f{width:100%;font:600 14px Cairo,sans-serif;padding:10px;margin-bottom:8px;border:1px solid var(--line);border-radius:10px;background:var(--card);color:var(--ink)}
.wa{display:block;text-align:center;text-decoration:none;background:#25d366;color:#fff;font:900 16px Cairo,sans-serif;padding:13px;border-radius:14px;border:0;width:100%;cursor:pointer}
.ghost{background:none;border:0;color:var(--mut);font:700 13px Cairo;cursor:pointer;margin-top:6px}
.toast{position:fixed;bottom:84px;inset-inline:0;margin:auto;width:max-content;max-width:90%;background:var(--ink);color:var(--bg2);padding:9px 16px;border-radius:99px;font-weight:700;font-size:14px;z-index:50;opacity:0;pointer-events:none;transition:opacity .2s}
.toast.on{opacity:1}
.note{font-size:12px;color:var(--mut);margin:6px 0}
@media(prefers-reduced-motion:reduce){*{transition:none!important}}
</style>
</head>
<body>
<header class="hero">
  <h1 id="shopName">حلويات البيت 🧁</h1>
  <p>كب كيك · سينابون · دونات — طازة كل يوم</p>
</header>
<main><div class="grid" id="grid"></div></main>

<div class="bar">
  <button class="gear" id="gear" aria-label="وضع التعديل">⚙️</button>
  <button class="cartbtn" id="openCart"><span>🛒 سلة التسوق</span><span><span class="cnt" id="cnt">0</span> &nbsp; <span id="barTot">0.00</span> د.أ</span></button>
</div>

<div class="sheet" id="cartSheet"><div class="panel">
  <h2>سلتك 🛍️</h2>
  <div id="cartList"></div>
  <div class="tot"><span>المجموع</span><span><span id="sum">0.00</span> د.أ</span></div>
  <input class="f" id="cName" placeholder="اسمك">
  <input class="f" id="cAddr" placeholder="العنوان / المنطقة">
  <input class="f" id="cNote" placeholder="ملاحظات (اختياري)">
  <button class="wa" id="send">📲 أرسل الطلب عبر واتساب</button>
  <button class="ghost" id="closeCart">رجوع للمنيو</button>
</div></div>

<div class="sheet" id="setSheet"><div class="panel">
  <h2>وضع صاحبة المحل ⚙️</h2>
  <label class="note">اسم المحل</label>
  <input class="f" id="sName">
  <label class="note">رقم الواتساب (مثال: 0791234567)</label>
  <input class="f" id="sPhone" inputmode="tel" placeholder="07XXXXXXXX">
  <button class="wa" id="editToggle" style="background:var(--pink)">✏️ تعديل المنتجات والصور</button>
  <p class="note">التعديلات تنحفظ على هذا الجهاز فقط. للتثبيت النهائي للجميع، ارجعي لـ Claude وأعطيه الأسعار والصور ليحدّث الصفحة.</p>
  <button class="ghost" id="closeSet">إغلاق</button>
</div></div>
<div class="toast" id="toast"></div>

<script>
var DEF=[
{id:1,cat:'cup',name:'كب كيك فانيلا كريمي',desc:'كريمة زبدة وسبرنكلز',price:1.5,old:2,emoji:'🧁'},
{id:2,cat:'cup',name:'كب كيك شوكولاتة',desc:'قلب شوكولاتة سايحة',price:1.75,emoji:'🧁',hot:1},
{id:3,cat:'cup',name:'كب كيك ريد فيلفت',desc:'كريمة تشيز ناعمة',price:2,old:2.5,emoji:'🧁'},
{id:4,cat:'cup',name:'بوكس 6 كب كيك',desc:'تشكيلة منوعة',price:8.5,old:10.5,emoji:'🎂',hot:1},
{id:5,cat:'cin',name:'سينابون كلاسيك',desc:'قرفة وكريمة جبنة',price:2.5,emoji:'🥐',hot:1},
{id:6,cat:'cin',name:'سينابون لوتس',desc:'صوص لوتس وبسكويت',price:3,old:3.75,emoji:'🥐'},
{id:7,cat:'cin',name:'بوكس 4 سينابون',desc:'دافي من الفرن',price:9,old:11,emoji:'📦'},
{id:8,cat:'don',name:'دونات سكر وقرفة',desc:'كلاسيكي وطري',price:1,emoji:'🍩'},
{id:9,cat:'don',name:'دونات وردي مغطى',desc:'غلازور فراولة',price:1.25,emoji:'🍩',hot:1},
{id:10,cat:'don',name:'دونات نوتيلا',desc:'محشي نوتيلا',price:1.75,old:2.25,emoji:'🍩'},
{id:11,cat:'don',name:'بوكس 6 دونات',desc:'نكهات مشكلة',price:6,old:7.5,emoji:'🍩'}];
var CATS=[['all','الكل ✨'],['cup','كب كيك 🧁'],['cin','سينابون 🥐'],['don','دونات 🍩']];
var S={items:DEF,cart:{},phone:'',name:'حلويات البيت 🧁'},cat='all',editing=false;
try{var r=localStorage.getItem('bk1');if(r){var o=JSON.parse(r);S.items=o.items||DEF;S.phone=o.phone||'';S.name=o.name||S.name;S.cart=o.cart||{}}}catch(e){}
function save(){try{localStorage.setItem('bk1',JSON.stringify(S))}catch(e){toast('المساحة ممتلئة، جرّبي صور أصغر')}}
function $(i){return document.getElementById(i)}
function esc(t){return String(t==null?'':t).replace(/[&<>"]/g,function(c){return{'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]})}
function money(n){return Number(n).toFixed(2)}
function toast(m){var t=$('toast');t.textContent=m;t.classList.add('on');clearTimeout(toast.h);toast.h=setTimeout(function(){t.classList.remove('on')},1400)}
function picHtml(p){return p.img?'<img src="'+p.img+'" alt="'+esc(p.name)+'">':p.emoji||'🧁'}
function tabs(){return;$('tabs').innerHTML=CATS.map(function(c){return'<button class="tab'+(c[0]==cat?' on':'')+'" data-c="'+c[0]+'">'+c[1]+'</button>'}).join('')}
function grid(){
  var l=S.items.filter(function(p){return cat=='all'||p.cat==cat});
  $('shopName').textContent=S.name;
  $('grid').innerHTML=l.map(function(p){
    var off=p.old&&p.old>p.price?Math.round((1-p.price/p.old)*100):0;
    var bd=off?'<span class="badge">-'+off+'%</span>':(p.hot?'<span class="badge hot">🔥 الأكثر طلبًا</span>':'');
    if(editing)return'<div class="card edit" data-id="'+p.id+'"><div class="pic">'+picHtml(p)+'<label class="up">📷 صورة منتجك<input type="file" accept="image/*" data-f="'+p.id+'"></label></div><div class="info"><input type="text" data-k="name" value="'+esc(p.name)+'"><input type="text" data-k="desc" value="'+esc(p.desc)+'"><input type="number" step="0.05" data-k="price" value="'+p.price+'" placeholder="السعر"><input type="number" step="0.05" data-k="old" value="'+(p.old||'')+'" placeholder="السعر قبل الخصم"><button class="del" data-d="'+p.id+'">🗑️ حذف</button></div></div>';
    return'<div class="card"><div class="pic">'+bd+picHtml(p)+'</div><div class="info"><div class="name">'+esc(p.name)+'</div><div class="desc">'+esc(p.desc)+'</div><div class="pr"><span class="now">'+money(p.price)+' د.أ</span>'+(off?'<span class="old">'+money(p.old)+'</span>':'')+'</div><button class="add" data-a="'+p.id+'">أضف للسلة 🛒</button></div></div>'}).join('')
  +(editing?'<button class="add" id="newP" style="min-height:120px">➕ منتج جديد</button>':'');
}
function find(id){return S.items.filter(function(p){return p.id==id})[0]}
function cartUI(){
  var n=0,t=0,h='';
  Object.keys(S.cart).forEach(function(id){var p=find(id),q=S.cart[id];if(!p){delete S.cart[id];return}n+=q;t+=q*p.price;
    h+='<div class="row"><div class="th">'+picHtml(p)+'</div><div class="rn">'+esc(p.name)+'<small>'+money(p.price*q)+' د.أ</small></div><div class="q"><button data-m="'+id+'">−</button><b>'+q+'</b><button data-p="'+id+'">+</button></div></div>'});
  $('cartList').innerHTML=h||'<p class="note" style="text-align:center;padding:24px 0">السلة فاضية — ضيفي أول حبة 🍩</p>';
  $('cnt').textContent=n;$('barTot').textContent=money(t);$('sum').textContent=money(t);save();
}
function resize(file,cb){var rd=new FileReader();rd.onload=function(){var im=new Image();im.onload=function(){var m=640,s=Math.min(1,m/Math.max(im.width,im.height)),c=document.createElement('canvas');c.width=im.width*s;c.height=im.height*s;c.getContext('2d').drawImage(im,0,0,c.width,c.height);cb(c.toDataURL('image/jpeg',.8))};im.src=rd.result};rd.readAsDataURL(file)}
document.addEventListener('click',function(e){
  var t=e.target,d=t.dataset||{};
  if(d.c){cat=d.c;tabs();grid()}
  if(d.a){S.cart[d.a]=(S.cart[d.a]||0)+1;cartUI();toast('تمت الإضافة للسلة ✅')}
  if(d.p){S.cart[d.p]++;cartUI()}
  if(d.m){S.cart[d.m]--;if(S.cart[d.m]<=0)delete S.cart[d.m];cartUI()}
  if(d.d){S.items=S.items.filter(function(p){return p.id!=d.d});save();grid()}
  if(t.id=='newP'){S.items.push({id:Date.now(),cat:cat=='all'?'cup':cat,name:'منتج جديد',desc:'',price:1,emoji:'🧁'});save();grid()}
});
document.addEventListener('input',function(e){
  var t=e.target,c=t.closest&&t.closest('.edit');if(!c||!t.dataset.k)return;
  var p=find(c.dataset.id),k=t.dataset.k;p[k]=(k=='price'||k=='old')?(parseFloat(t.value)||0):t.value;if(k=='old'&&!p.old)delete p.old;save();cartUI()
});
document.addEventListener('change',function(e){
  var t=e.target;if(!t.dataset.f)return;var f=t.files[0];if(!f)return;
  resize(f,function(u){find(t.dataset.f).img=u;save();grid();toast('تم تغيير الصورة 📷')})
});
$('openCart').onclick=function(){$('cartSheet').classList.add('open')};
$('closeCart').onclick=function(){$('cartSheet').classList.remove('open')};
$('gear').onclick=function(){$('sName').value=S.name;$('sPhone').value=S.phone;$('setSheet').classList.add('open')};
$('closeSet').onclick=function(){S.name=$('sName').value||S.name;S.phone=$('sPhone').value;save();$('setSheet').classList.remove('open');grid()};
$('editToggle').onclick=function(){editing=!editing;this.textContent=editing?'✅ إنهاء التعديل':'✏️ تعديل المنتجات والصور';S.name=$('sName').value||S.name;S.phone=$('sPhone').value;save();grid();$('setSheet').classList.remove('open')};
$('send').onclick=function(){
  var ids=Object.keys(S.cart);if(!ids.length){toast('السلة فاضية');return}
  var ph=(S.phone||'').replace(/\D/g,'');if(!ph){toast('أضيفي رقم الواتساب من ⚙️ أولًا');return}
  if(ph.charAt(0)=='0')ph='962'+ph.slice(1);
  var t=0,m='🧁 *طلب جديد*\n\n';
  ids.forEach(function(id){var p=find(id),q=S.cart[id];t+=q*p.price;m+='• '+p.name+' × '+q+' = '+money(q*p.price)+' د.أ\n'});
  m+='\n*المجموع: '+money(t)+' د.أ*\n';
  if($('cName').value)m+='الاسم: '+$('cName').value+'\n';
  if($('cAddr').value)m+='العنوان: '+$('cAddr').value+'\n';
  if($('cNote').value)m+='ملاحظات: '+$('cNote').value+'\n';
  var a=document.createElement('a');a.href='https://wa.me/'+ph+'?text='+encodeURIComponent(m);a.target='_blank';a.rel='noopener';document.body.appendChild(a);a.click();a.remove()
};
tabs();grid();cartUI();
</script>
</body>
</html>
