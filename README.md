# Luxury-Mobile-Shop-Dajal
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<meta name="description" content="Luxury Mobile Shop — Premium smartphones, accessories and repair service.">
<title>Luxury Mobile Shop</title>
<style>
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",Arial,sans-serif;background:#030405;color:#fff;overflow-x:hidden}
:root{--gold:#d7ad55;--gold2:#ffe8a6;--gold3:#8d6a2b;--line:#332717;--muted:#9b9b9b;--panel:#0d0e10}
body:before{content:"";position:fixed;inset:0;pointer-events:none;background:
radial-gradient(circle at 8% 8%,#d7ad5518,transparent 25%),
radial-gradient(circle at 92% 22%,#8b5cff12,transparent 23%),
radial-gradient(circle at 50% 90%,#d7ad550b,transparent 28%);
z-index:-2}
body:after{content:"";position:fixed;inset:0;pointer-events:none;opacity:.16;background-image:linear-gradient(#ffffff08 1px,transparent 1px),linear-gradient(90deg,#ffffff08 1px,transparent 1px);background-size:44px 44px;mask-image:linear-gradient(to bottom,black,transparent 80%);z-index:-1}
body:before{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(circle at 10% 10%,#d4a94f0c,transparent 28%),radial-gradient(circle at 90% 20%,#fff0b00a,transparent 25%);z-index:-1}
header{position:sticky;top:0;z-index:20;background:#050505ed;backdrop-filter:blur(15px);border-bottom:1px solid var(--line);padding:12px 5%;display:flex;align-items:center;justify-content:space-between;gap:12px}
.brand{display:flex;align-items:center;gap:11px}.logo{width:54px;height:54px;border-radius:50%;display:grid;place-items:center;border:2px solid var(--gold);background:radial-gradient(circle,#4a3516,#090909 65%);box-shadow:0 0 25px #d4a94f35,inset 0 0 15px #d4a94f22}.logo span{font-weight:900;color:var(--gold2);letter-spacing:-1px}.brand h2{font-size:17px;letter-spacing:1.3px;margin:0}.brand small{color:#999}
nav{display:flex;gap:7px;flex-wrap:wrap;justify-content:flex-end}.btn{display:inline-block;text-decoration:none;border:1px solid #ffffff12;background:linear-gradient(180deg,#151619,#0d0e10);color:#fff;border-radius:12px;padding:10px 14px;font-weight:750;cursor:pointer;transition:.2s;box-shadow:0 8px 25px #0006}.btn:hover{transform:translateY(-2px);border-color:#d7ad5555}.goldbtn{background:linear-gradient(135deg,#8e6725,#ffe8a6 52%,#bd8d32);color:#111;border:0;box-shadow:0 10px 28px #d4a94f30}
.hero{min-height:560px;padding:90px 7%;display:flex;align-items:center;position:relative;overflow:hidden;background:radial-gradient(circle at 78% 35%,#d7ad5524,transparent 23%),radial-gradient(circle at 86% 68%,#704cff14,transparent 25%),linear-gradient(135deg,#040506,#11100c 55%,#050506)}
.hero:before{content:"✦";position:absolute;right:12%;top:15%;font-size:130px;color:#d4a94f12}.hero:after{content:"LUXURY";position:absolute;right:-35px;bottom:-75px;font-size:145px;font-weight:900;letter-spacing:12px;color:#fff04}
.heroInner{position:relative;z-index:1}.eyebrow{color:var(--gold2);font-weight:800;letter-spacing:4px;font-size:12px}.hero h1{font-size:clamp(43px,7vw,78px);line-height:.98;margin:15px 0}.gold{color:var(--gold2);text-shadow:0 0 30px #d4a94f35}.hero p{max-width:650px;color:#b8b8b8;line-height:1.8;font-size:17px}.heroBtns{display:flex;gap:10px;flex-wrap:wrap;margin-top:25px}
.wrap{max-width:1150px;margin:auto;padding:48px 5%}.title{text-align:center;margin-bottom:28px}.title h2{font-size:34px;margin:0 0 7px}.title p{color:#888}
.search{width:100%;padding:15px 17px;border-radius:14px;border:1px solid var(--line);background:#101010;color:white;outline:none;margin-bottom:22px}.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(245px,1fr));gap:19px}
.card{background:linear-gradient(145deg,#151619,#090a0b);border:1px solid #ffffff10;border-radius:22px;overflow:hidden;box-shadow:0 18px 55px #000b, inset 0 1px #ffffff08;transition:.28s}.card:hover{transform:translateY(-7px);border-color:#d7ad5550;box-shadow:0 22px 65px #000d,0 0 35px #d7ad5510}.media{height:255px;background:radial-gradient(circle,#25231d,#0a0b0d 70%);position:relative;display:flex;align-items:center;justify-content:center;color:#777;overflow:hidden}.media img,.media video{width:100%;height:100%;object-fit:cover}.media:after{content:"";position:absolute;inset:0;pointer-events:none;background:linear-gradient(to top,#0008,transparent 45%)}.videoBadge{position:absolute;top:10px;right:10px;background:#000b;border:1px solid #fff3;padding:7px 9px;border-radius:9px;font-size:12px}.info{padding:17px}.info h3{margin:0 0 8px;font-size:20px}.price{color:var(--gold2);font-size:22px;font-weight:900}.meta{display:flex;justify-content:space-between;gap:8px;margin-top:9px;color:#8fd18f;font-size:13px}.desc{color:#aaa;line-height:1.6;margin:12px 0;min-height:50px}.full{width:100%;text-align:center;margin-top:5px}
.service{display:grid;grid-template-columns:repeat(auto-fit,minmax(245px,1fr));gap:18px}.serviceCard{border:1px solid var(--line);background:linear-gradient(145deg,#19140c,#0e0e0e);padding:25px;border-radius:19px}.serviceCard .icon{font-size:35px}.serviceCard h3{color:var(--gold2)}.serviceCard p{color:#aaa;line-height:1.7}
.contacts{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:15px}.contact{border:1px solid var(--line);background:#101010;border-radius:17px;padding:21px}.contact a{color:var(--gold2);text-decoration:none;font-weight:800}
footer{text-align:center;border-top:1px solid var(--line);padding:28px 5%;color:#777}
.modal{display:none;position:fixed;inset:0;background:#000e;z-index:50;padding:18px;overflow:auto;backdrop-filter:blur(12px)}.panel{max-width:760px;margin:25px auto;background:linear-gradient(145deg,#15130f,#090a0c);border:1px solid #d7ad5540;border-radius:25px;padding:23px;box-shadow:0 20px 90px #000}.close{float:right;background:none;border:0;color:#fff;font-size:28px;cursor:pointer}.panel input,.panel textarea{width:100%;padding:12px;margin:7px 0 13px;border-radius:10px;border:1px solid #3d301b;background:#141414;color:#fff}.loginBox{max-width:420px;margin:65px auto;text-align:center}.loginBox h2{color:var(--gold2)}.err{color:#ff7777;min-height:20px;font-size:13px}.save{border:0;border-radius:10px;padding:13px 18px;background:linear-gradient(135deg,#b9872d,#ffe7a3);font-weight:800;cursor:pointer}.row{display:flex;justify-content:space-between;align-items:center;gap:10px;padding:12px 0;border-bottom:1px solid #2a2a2a}.del{background:#7d2727;color:white;border:0;border-radius:8px;padding:7px 10px;cursor:pointer}

.ai-launch{position:fixed;right:20px;bottom:20px;z-index:40;width:62px;height:62px;border-radius:50%;border:1px solid #ffe8a688;background:linear-gradient(145deg,#ffe8a6,#9b722b);color:#111;font-size:25px;font-weight:900;box-shadow:0 12px 35px #000,0 0 35px #d7ad5530;cursor:pointer;transition:.2s}.ai-launch:hover{transform:scale(1.06)}
.ai-window{display:none;position:fixed;right:20px;bottom:92px;width:min(390px,calc(100vw - 28px));height:min(600px,calc(100vh - 120px));z-index:45;border:1px solid #d7ad5545;border-radius:24px;overflow:hidden;background:#090a0c;box-shadow:0 25px 90px #000e,0 0 45px #d7ad5515}
.ai-head{padding:16px 17px;background:linear-gradient(135deg,#17130b,#0c0d10);border-bottom:1px solid #ffffff10;display:flex;align-items:center;justify-content:space-between}.ai-brand{display:flex;align-items:center;gap:11px}.ai-orb{width:39px;height:39px;border-radius:13px;display:grid;place-items:center;background:linear-gradient(135deg,#ffe8a6,#8d6728);color:#111;font-weight:900}.ai-head strong{display:block}.ai-head small{color:#929292}.ai-close{background:none;border:0;color:#aaa;font-size:24px;cursor:pointer}
.ai-body{height:calc(100% - 132px);overflow:auto;padding:15px;background:radial-gradient(circle at 80% 10%,#d7ad5509,transparent 35%)}.ai-msg{max-width:88%;padding:11px 13px;border-radius:15px;margin:8px 0;line-height:1.5;font-size:14px;white-space:pre-line}.ai-msg.bot{background:#15171a;border:1px solid #ffffff0d;color:#eee;border-top-left-radius:5px}.ai-msg.user{margin-left:auto;background:linear-gradient(135deg,#b88731,#ffe8a6);color:#111;border-top-right-radius:5px}.ai-quick{display:flex;gap:7px;flex-wrap:wrap;margin:8px 0 12px}.ai-quick button{background:#121417;color:#ddd;border:1px solid #ffffff12;border-radius:999px;padding:7px 10px;cursor:pointer;font-size:12px}.ai-input{height:68px;padding:10px;border-top:1px solid #ffffff10;display:flex;gap:7px;background:#0d0e10}.ai-input input{min-width:0;flex:1;border:1px solid #ffffff12;border-radius:12px;background:#151619;color:#fff;padding:0 12px;outline:none}.ai-send{width:48px;border:0;border-radius:12px;background:linear-gradient(135deg,#b88731,#ffe8a6);font-weight:900;cursor:pointer}
.stock-pill{display:inline-flex;padding:5px 8px;border-radius:999px;background:#1c2b1c;color:#9be19b;border:1px solid #4b8d4b55;font-size:11px;font-weight:800}.out-pill{background:#2b1c1c;color:#ff9a9a;border-color:#8d4b4b55}

@media(max-width:700px){header{align-items:flex-start}.logo{width:44px;height:44px}.brand h2{font-size:14px}.brand small{font-size:9px}nav .btn{font-size:11px;padding:8px}.hero{min-height:470px;padding:65px 5%}}
</style>
</head>
<body>
<header>
<div class="brand"><div class="logo"><span>LM</span></div><div><h2>LUXURY MOBILE SHOP</h2><small>Premium Mobiles • Accessories • Repair</small></div></div>
<nav><a class="btn" href="#products">Shop</a><a class="btn" href="#repair">Repair</a><a class="btn" href="#help">Help</a><button class="btn goldbtn" onclick="openAdmin()">⚙ Admin</button></nav>
</header>

<section class="hero"><div class="heroInner"><div class="eyebrow">PREMIUM MOBILE EXPERIENCE</div><h1>Luxury in Every <span class="gold">Device.</span></h1><p>Explore our latest mobile stock with complete product details, photos and videos. Choose your device and contact Luxury Mobile Shop directly on WhatsApp.</p><div class="heroBtns"><a class="btn goldbtn" href="#products">Explore Stock</a><a class="btn" target="_blank" href="https://wa.me/923716686383?text=Hello%20Luxury%20Mobile%20Shop%2C%20I%20want%20to%20ask%20about%20your%20stock.">💬 WhatsApp Us</a></div></div></section>

<section id="products" class="wrap"><div class="title"><h2>Latest <span class="gold">Stock</span></h2><p>Product photos, videos, prices and details</p></div><input id="search" class="search" placeholder="🔎 Search your desired mobile..." oninput="render()"><div id="grid" class="grid"></div></section>

<section id="repair" class="wrap"><div class="title"><h2>🔧 Repair <span class="gold">Service</span></h2><p>Professional device care from diagnostics to repair.</p></div><div class="service">
<div class="serviceCard"><div class="icon">📱</div><h3>Screen & Display</h3><p>Display, touch and screen-related diagnostics and replacement service.</p></div>
<div class="serviceCard"><div class="icon">🔋</div><h3>Battery Service</h3><p>Battery diagnostics and replacement for supported mobile devices.</p></div>
<div class="serviceCard"><div class="icon">⚡</div><h3>Charging & Software</h3><p>Charging-port checks, software troubleshooting and device diagnostics.</p></div></div>
<div style="text-align:center;margin-top:22px"><a class="btn goldbtn" href="#help">Repair Details & Contact</a></div></section>

<section id="help" class="wrap"><div class="title"><h2>💬 Help <span class="gold">Center</span></h2><p>Order help, stock questions and repair support</p></div><div class="contacts">
<div class="contact"><h3>📞 Contact Number</h3><a href="tel:03312084336">0331 2084336</a></div>
<div class="contact"><h3>📞 Contact Number</h3><a href="tel:03358722470">0335 8722470</a></div>
<div class="contact"><h3>💚 WhatsApp</h3><a target="_blank" href="https://wa.me/923716686383">0371 6686383</a></div></div></section>


<button class="ai-launch" onclick="toggleAI()" aria-label="Open AI Stock Assistant">✦</button>
<div id="aiWindow" class="ai-window">
  <div class="ai-head">
    <div class="ai-brand"><div class="ai-orb">AI</div><div><strong>Luxury AI Assistant</strong><small>Live stock & product help</small></div></div>
    <button class="ai-close" onclick="toggleAI()">×</button>
  </div>
  <div id="aiBody" class="ai-body"></div>
  <div class="ai-input"><input id="aiInput" placeholder="e.g. iPhone 15 ka price?" onkeydown="if(event.key==='Enter')askAI()"><button class="ai-send" onclick="askAI()">➤</button></div>
</div>

<footer>© 2026 Luxury Mobile Shop • Premium Mobiles & Repair</footer>

<div id="modal" class="modal"><div class="panel"><button class="close" onclick="closeAdmin()">×</button><div id="adminArea"></div></div></div>

<script>
const ADMIN_USER="khurshaidshabeer";
const ADMIN_PASS="khurshaidshabeer@12";
let products=JSON.parse(localStorage.getItem("luxuryProducts")||"[]");
function save(){localStorage.setItem("luxuryProducts",JSON.stringify(products))}
function openAdmin(){document.getElementById("modal").style.display="block";showLogin()}
function closeAdmin(){document.getElementById("modal").style.display="none"}
function showLogin(){document.getElementById("adminArea").innerHTML=`<div class="loginBox"><div class="logo" style="margin:auto auto 18px"><span>LM</span></div><h2>Luxury Admin Login</h2><p style="color:#888">Authorized access only</p><input id="au" placeholder="Username"><input id="ap" type="password" placeholder="Password"><div id="err" class="err"></div><button class="save" onclick="login()">🔐 Login to Dashboard</button></div>`}
function login(){let u=document.getElementById("au").value,p=document.getElementById("ap").value;if(u===ADMIN_USER&&p===ADMIN_PASS)showDashboard();else document.getElementById("err").textContent="Incorrect username or password."}
function fileData(input){return new Promise(r=>{let f=input.files[0];if(!f)return r("");let x=new FileReader();x.onload=()=>r(x.result);x.readAsDataURL(f)})}
function showDashboard(){document.getElementById("adminArea").innerHTML=`<h2>⚙ Luxury Admin Dashboard</h2><p style="color:#999">Only the authorized admin can add or remove products.</p><input id="name" placeholder="Product name"><input id="price" placeholder="Price (e.g. Rs. 249,999)"><input id="stock" type="number" placeholder="Stock quantity"><textarea id="desc" placeholder="Full product details / specifications"></textarea><label>Product picture <input id="image" type="file" accept="image/*"></label><label>Product video <input id="video" type="file" accept="video/*"></label><br><button class="save" onclick="addProduct()">＋ Add Product</button><div id="adminList"></div>`;renderAdmin()}
async function addProduct(){let name=document.getElementById("name").value.trim();if(!name)return alert("Product name required");let p={id:Date.now(),name,price:document.getElementById("price").value||"Contact for price",stock:document.getElementById("stock").value||0,desc:document.getElementById("desc").value||"Premium mobile available at Luxury Mobile Shop.",image:await fileData(document.getElementById("image")),video:await fileData(document.getElementById("video"))};products.unshift(p);save();render();renderAdmin();alert("Product added successfully!")}
function render(){let q=document.getElementById("search").value.toLowerCase(),a=products.filter(p=>p.name.toLowerCase().includes(q)),g=document.getElementById("grid");g.innerHTML=a.length?a.map(p=>`<article class="card"><div class="media">${p.image?`<img src="${p.image}" alt="${p.name}">`:p.video?`<video src="${p.video}" controls></video>`:"No media"}${p.video&&p.image?`<span class="videoBadge">🎥 Video available</span>`:""}</div>${p.video&&p.image?`<div style="padding:10px 14px 0;background:#0b0c0e"><video src="${p.video}" controls preload="metadata" style="width:100%;height:150px;object-fit:cover;border-radius:12px;border:1px solid #ffffff10;background:#000"></video></div>`:""}<div class="info"><h3>${p.name}</h3><div class="price">${p.price}</div><div class="meta"><span>● ${Number(p.stock)>0?"In Stock":"Out of Stock"}</span><span>Qty: ${p.stock}</span></div><p class="desc">${p.desc}</p><a class="btn goldbtn full" target="_blank" href="https://wa.me/923716686383?text=${encodeURIComponent("Hello Luxury Mobile Shop, I want to buy/ask about: "+p.name+" | Price: "+p.price)}">💬 Choose & WhatsApp</a></div></article>`).join(""):`<div class="empty" style="grid-column:1/-1;padding:45px;text-align:center;border:1px dashed #d7ad5530;border-radius:20px;color:#999;background:#0c0d0f">No products found. Admin can add products from the Admin Dashboard.</div>`}
function renderAdmin(){let e=document.getElementById("adminList");if(!e)return;e.innerHTML="<h3 style='margin-top:25px'>Current Stock</h3>"+(products.length?products.map(p=>`<div class="row"><span>${p.name}<br><small style="color:#999">${p.price} • Stock ${p.stock}</small></span><button class="del" onclick="removeProduct(${p.id})">Delete</button></div>`).join(""):"<p style='color:#777'>No products added.</p>")}
function removeProduct(id){if(confirm("Delete this product?")){products=products.filter(p=>p.id!==id);save();render();renderAdmin()}}

function toggleAI(){
  const w=document.getElementById("aiWindow");
  const opening=w.style.display!=="block";
  w.style.display=opening?"block":"none";
  if(opening && !document.getElementById("aiBody").dataset.ready) initAI();
}
function initAI(){
  const b=document.getElementById("aiBody");
  b.dataset.ready="1";
  aiBot("Assalam-o-Alaikum 👋 Main Luxury AI Assistant hoon. Main current website stock se product ka price, quantity, availability aur details bata sakta hoon.");
  const q=document.createElement("div");q.className="ai-quick";
  ["All stock batao","iPhone ka stock?","Sab se sasta mobile?","Available products?"].forEach(x=>{
    const bt=document.createElement("button");bt.textContent=x;bt.onclick=()=>{document.getElementById("aiInput").value=x;askAI()};q.appendChild(bt);
  });b.appendChild(q);b.scrollTop=b.scrollHeight;
}
function aiBot(t){const b=document.getElementById("aiBody"),d=document.createElement("div");d.className="ai-msg bot";d.textContent=t;b.appendChild(d);b.scrollTop=b.scrollHeight}
function aiUser(t){const b=document.getElementById("aiBody"),d=document.createElement("div");d.className="ai-msg user";d.textContent=t;b.appendChild(d);b.scrollTop=b.scrollHeight}
function norm(s){return s.toLowerCase().replace(/[^\w\s]/g," ").replace(/\s+/g," ").trim()}
function productText(p){return norm([p.name,p.desc,p.price].join(" "))}
function askAI(){
  const inp=document.getElementById("aiInput"),q=inp.value.trim();if(!q)return;
  if(!document.getElementById("aiBody").dataset.ready)initAI();
  aiUser(q);inp.value="";
  const nq=norm(q), available=products.filter(p=>Number(p.stock)>0);
  if(!products.length){aiBot("Abhi website par koi stock add nahi hua. Admin Dashboard se products add karne ke baad main unki details customers ko bata dunga.");return;}
  if(/^(hi|hello|salam|assalam|aoa|hey)\b/.test(nq)){aiBot("Walaikum Assalam! 😊 Aap kisi mobile ka naam, price, stock ya details pooch sakte hain.");return;}
  if(/all stock|sab.*stock|available products|kon.*available|kons.*available|what.*available/.test(nq)){
    aiBot(available.length?available.map((p,i)=>`${i+1}. ${p.name} — ${p.price} — Qty: ${p.stock}`).join("\n"):"Is waqt koi product in stock nahi hai.");
    return;
  }
  if(/cheap|sasta|kam.*price|lowest/.test(nq)){
    const list=products.filter(p=>Number(p.stock)>0).map(p=>({p,n:parseFloat(String(p.price).replace(/[^\d.]/g,""))||Infinity})).sort((a,b)=>a.n-b.n);
    aiBot(list.length?`Sab se kam listed price: ${list[0].p.name}\nPrice: ${list[0].p.price}\nStock: ${list[0].p.stock}`:"Is waqt available stock nahi hai.");return;
  }
  const matches=products.filter(p=>{
    const words=nq.split(/\s+/).filter(x=>x.length>2);
    return words.some(w=>productText(p).includes(w));
  });
  if(matches.length){
    const p=matches[0],status=Number(p.stock)>0?`In Stock (${p.stock} available)`:"Out of Stock";
    aiBot(`📱 ${p.name}\n💰 Price: ${p.price}\n📦 ${status}\n\n${p.desc}\n\nAap is product ko neeche product card se WhatsApp par select karke order/inquiry kar sakte hain.`);
  }else{
    aiBot("Mujhe is naam ka product current stock mein nahi mila. Product ka exact naam/model likhein, ya “All stock batao” likh kar current inventory dekh lein.");
  }
}

render();
</script>
</body>
</html>
