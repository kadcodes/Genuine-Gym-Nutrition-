
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Genuine Gym Nutrition - Premium sports nutrition and gym supplements.">
<title>Genuine Gym Nutrition | Fuel Your Strength</title>
<style>
:root{
  --red:#ff1838;
  --red2:#b80020;
  --blue:#0b5cff;
  --navy:#050816;
  --card:#0b1020;
  --text:#f7f9ff;
  --muted:#a9b2c8;
  --line:rgba(255,255,255,.10);
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
  font-family:Arial,Helvetica,sans-serif;
  background:radial-gradient(circle at 80% 10%,rgba(11,92,255,.20),transparent 28%),
             radial-gradient(circle at 10% 30%,rgba(255,24,56,.15),transparent 25%),var(--navy);
  color:var(--text);line-height:1.6;
}
a{text-decoration:none;color:inherit}
.container{width:min(1180px,92%);margin:auto}
header{
  position:sticky;top:0;z-index:20;
  background:rgba(5,8,22,.88);backdrop-filter:blur(14px);
  border-bottom:1px solid var(--line)
}
.nav{height:76px;display:flex;align-items:center;justify-content:space-between}
.logo{font-weight:900;font-size:21px;letter-spacing:.5px}
.logo span{color:var(--red)}
.logo small{display:block;font-size:9px;letter-spacing:3px;color:#7fa8ff}
nav{display:flex;gap:25px;align-items:center}
nav a{color:#dce3f7;font-size:14px;font-weight:700}
nav a:hover{color:#fff}
.cart-btn,.primary{
  border:0;color:#fff;font-weight:800;cursor:pointer;border-radius:12px;
  background:linear-gradient(135deg,var(--red),var(--blue));
  box-shadow:0 10px 30px rgba(255,24,56,.18);
}
.cart-btn{padding:10px 15px}
.hero{padding:90px 0 70px;overflow:hidden}
.hero-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:55px;align-items:center}
.badge{
  display:inline-block;padding:8px 13px;border:1px solid rgba(255,24,56,.35);
  border-radius:30px;background:rgba(255,24,56,.08);color:#ff7890;font-size:12px;font-weight:800;
  letter-spacing:1.2px
}
h1{font-size:clamp(44px,7vw,82px);line-height:.98;margin:20px 0}
.gradient{background:linear-gradient(90deg,#fff 15%,#ff3754 55%,#4e8cff);-webkit-background-clip:text;background-clip:text;color:transparent}
.hero p{color:var(--muted);font-size:18px;max-width:620px}
.actions{display:flex;gap:13px;margin-top:30px;flex-wrap:wrap}
.primary{padding:14px 21px}
.secondary{padding:13px 21px;border:1px solid var(--line);border-radius:12px;font-weight:800}
.stats{display:flex;gap:35px;margin-top:38px;flex-wrap:wrap}
.stats b{font-size:25px}.stats span{display:block;color:var(--muted);font-size:12px}
.hero-card{
  min-height:470px;border-radius:30px;border:1px solid var(--line);
  background:linear-gradient(145deg,rgba(255,24,56,.16),rgba(11,92,255,.18)),#080d1d;
  position:relative;display:flex;align-items:center;justify-content:center;overflow:hidden;
  box-shadow:0 25px 80px rgba(0,0,0,.35)
}
.hero-card:before{
  content:"";width:270px;height:270px;border-radius:50%;
  background:linear-gradient(135deg,var(--red),var(--blue));
  filter:blur(2px);position:absolute;box-shadow:0 0 90px rgba(11,92,255,.45)
}
.tub{
  position:relative;width:210px;height:250px;border-radius:18px 18px 30px 30px;
  background:linear-gradient(90deg,#151b2b,#303b58,#101625);
  border:2px solid rgba(255,255,255,.2);box-shadow:0 30px 50px #0008;
  transform:rotate(-5deg)
}
.tub:before{content:"";position:absolute;top:-25px;left:15px;width:180px;height:40px;border-radius:50%;
  background:#11182a;border:2px solid #59647b}
.tub .label{position:absolute;top:62px;left:15px;right:15px;padding:18px 8px;text-align:center;
  background:linear-gradient(135deg,var(--red),var(--blue));border-radius:7px;font-weight:900}
.tub .label small{display:block;font-size:9px;letter-spacing:2px}
section{padding:75px 0}
.section-head{display:flex;justify-content:space-between;gap:20px;align-items:end;margin-bottom:30px}
.eyebrow{color:#6fa0ff;font-weight:900;letter-spacing:2px;font-size:12px}
h2{font-size:38px;line-height:1.1;margin-top:8px}
.section-head p{color:var(--muted);max-width:470px}
.products{display:grid;grid-template-columns:repeat(4,1fr);gap:18px}
.product{
  background:linear-gradient(160deg,#0e1427,#080c19);border:1px solid var(--line);
  border-radius:20px;padding:18px;transition:.25s;position:relative
}
.product:hover{transform:translateY(-6px);border-color:rgba(79,136,255,.45)}
.product-img{
  height:210px;border-radius:15px;display:flex;align-items:center;justify-content:center;
  background:radial-gradient(circle,rgba(11,92,255,.30),transparent 58%),#0a0f1f;margin-bottom:17px
}
.mini-tub{width:105px;height:135px;border-radius:12px 12px 18px 18px;background:linear-gradient(90deg,#151a27,#303a51,#111625);
  position:relative;box-shadow:0 15px 25px #0009}
.mini-tub:before{content:"";position:absolute;top:-12px;left:8px;width:89px;height:20px;border-radius:50%;background:#101522;border:1px solid #59647b}
.mini-label{position:absolute;top:38px;left:7px;right:7px;background:linear-gradient(135deg,var(--red),var(--blue));padding:8px 2px;text-align:center;font-size:10px;font-weight:900}
.product h3{font-size:17px}.product p{font-size:13px;color:var(--muted);margin:5px 0 14px}
.price{font-size:21px;font-weight:900}.price del{font-size:12px;color:#758097;margin-left:5px}
.add{width:100%;padding:11px;margin-top:13px;border:0;border-radius:10px;background:#fff;color:#070b18;font-weight:900;cursor:pointer}
.add:hover{background:#dce7ff}
.features{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.feature{padding:28px;border:1px solid var(--line);border-radius:20px;background:#080d1b}
.icon{font-size:28px}.feature h3{margin:12px 0 5px}.feature p{color:var(--muted);font-size:14px}
.offer{border-radius:28px;padding:45px;background:linear-gradient(105deg,rgba(255,24,56,.92),rgba(11,92,255,.9));
  display:flex;justify-content:space-between;gap:25px;align-items:center}
.offer h2{max-width:650px}.offer p{margin-top:8px;color:#eef3ff}.offer .primary{background:#fff;color:#091021}
.contact{display:grid;grid-template-columns:1fr 1fr;gap:25px}
.contact-card{padding:30px;border:1px solid var(--line);border-radius:22px;background:#080d1b}
form{display:grid;gap:12px}input,textarea{width:100%;padding:14px;border:1px solid var(--line);background:#050914;color:#fff;border-radius:10px;outline:none}
textarea{min-height:120px;resize:vertical}
footer{border-top:1px solid var(--line);padding:30px 0;color:#8993aa;font-size:13px}
.footer-row{display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap}
#toast{position:fixed;right:20px;bottom:20px;background:#fff;color:#07101e;padding:13px 18px;border-radius:12px;font-weight:800;transform:translateY(100px);transition:.3s;z-index:50}
#toast.show{transform:translateY(0)}
@media(max-width:900px){
  nav{display:none}.hero-grid,.contact{grid-template-columns:1fr}.products{grid-template-columns:repeat(2,1fr)}
  .hero{padding-top:55px}.hero-card{min-height:380px}.offer{display:block}.offer .primary{margin-top:20px}
}
@media(max-width:560px){
  .products,.features{grid-template-columns:1fr}.hero-card{min-height:330px}.stats{gap:20px}
  h2{font-size:31px}.nav{height:68px}.logo{font-size:18px}
}
</style>
</head>
<body>
<header>
  <div class="container nav">
    <a class="logo" href="#"><span>GENUINE</span> GYM NUTRITION<small>FUEL • TRAIN • GROW</small></a>
    <nav>
      <a href="#home">Home</a><a href="#products">Products</a><a href="#why">Why Us</a><a href="#contact">Contact</a>
    </nav>
    <button class="cart-btn" onclick="showCart()">🛒 Cart <span id="count">0</span></button>
  </div>
</header>

<main>
<section class="hero" id="home">
  <div class="container hero-grid">
    <div>
      <span class="badge">PREMIUM SPORTS NUTRITION</span>
      <h1>BUILD YOUR <span class="gradient">STRONGEST</span> SELF.</h1>
      <p>Premium gym nutrition made for serious training. Shop protein, creatine and performance essentials from Genuine Gym Nutrition.</p>
      <div class="actions">
        <a class="primary" href="#products">Shop Supplements →</a>
        <a class="secondary" href="#why">Why Genuine?</a>
      </div>
      <div class="stats">
        <div><b>100%</b><span>QUALITY FOCUS</span></div>
        <div><b>24/7</b><span>FITNESS MINDSET</span></div>
        <div><b>∞</b><span>LIMITS TO BREAK</span></div>
      </div>
    </div>
    <div class="hero-card"><div class="tub"><div class="label"><small>GENUINE</small>WHEY<br>PROTEIN</div></div></div>
  </div>
</section>

<section id="products">
<div class="container">
  <div class="section-head"><div><div class="eyebrow">SHOP THE STACK</div><h2>Top Products</h2></div><p>Upgrade your daily training routine with essentials selected for strength, recovery and performance.</p></div>
  <div class="products">
    <article class="product"><div class="product-img"><div class="mini-tub"><div class="mini-label">WHEY PRO</div></div></div><h3>Genuine Whey Protein</h3><p>High-protein daily muscle support.</p><span class="price">₹2,499 <del>₹2,999</del></span><button class="add" onclick="addToCart('Genuine Whey Protein',2499)">ADD TO CART</button></article>
    <article class="product"><div class="product-img"><div class="mini-tub"><div class="mini-label">CREATINE</div></div></div><h3>Pure Creatine Monohydrate</h3><p>Simple, focused training support.</p><span class="price">₹899 <del>₹1,099</del></span><button class="add" onclick="addToCart('Pure Creatine Monohydrate',899)">ADD TO CART</button></article>
    <article class="product"><div class="product-img"><div class="mini-tub"><div class="mini-label">PRE-WORKOUT</div></div></div><h3>Ignite Pre-Workout</h3><p>Designed for intense sessions.</p><span class="price">₹1,499 <del>₹1,799</del></span><button class="add" onclick="addToCart('Ignite Pre-Workout',1499)">ADD TO CART</button></article>
    <article class="product"><div class="product-img"><div class="mini-tub"><div class="mini-label">MASS</div></div></div><h3>Genuine Mass Gainer</h3><p>Calorie and protein support for growth.</p><span class="price">₹2,199 <del>₹2,599</del></span><button class="add" onclick="addToCart('Genuine Mass Gainer',2199)">ADD TO CART</button></article>
  </div>
</div>
</section>

<section id="why">
<div class="container">
  <div class="section-head"><div><div class="eyebrow">THE GENUINE STANDARD</div><h2>Train With Confidence.</h2></div></div>
  <div class="features">
    <div class="feature"><div class="icon">✓</div><h3>Quality First</h3><p>We focus on products and ingredients that fit a serious fitness lifestyle.</p></div>
    <div class="feature"><div class="icon">⚡</div><h3>Performance Driven</h3><p>Build a simple stack around your training goals and daily consistency.</p></div>
    <div class="feature"><div class="icon">🔥</div><h3>Built For Gym Life</h3><p>A bold brand for people who show up, work hard and keep progressing.</p></div>
  </div>
</div>
</section>

<section>
<div class="container"><div class="offer"><div><div class="eyebrow" style="color:#fff">WELCOME OFFER</div><h2>GET 10% OFF YOUR FIRST ORDER.</h2><p>Use code <b>GENUINE10</b> at checkout.</p></div><a class="primary" href="#products">Claim Offer →</a></div></div>
</section>

<section id="contact">
<div class="container">
  <div class="section-head"><div><div class="eyebrow">GET IN TOUCH</div><h2>Let's Talk Fitness.</h2></div></div>
  <div class="contact">
    <div class="contact-card"><h3>Genuine Gym Nutrition</h3><p style="color:var(--muted);margin-top:10px">Have a question about a product or your fitness stack? Send us a message.</p><p style="margin-top:20px">📞 +91 90000 00000</p><p>✉️ hello@genuinegymnutrition.com</p><p>📍 India</p></div>
    <div class="contact-card">
      <form onsubmit="sendMessage(event)">
        <input id="name" placeholder="Your name" required>
        <input id="email" type="email" placeholder="Email address" required>
        <textarea id="message" placeholder="Your message" required></textarea>
        <button class="primary" type="submit">Send Message</button>
      </form>
    </div>
  </div>
</div>
</section>
</main>

<footer><div class="container footer-row"><span>© 2026 Genuine Gym Nutrition. All rights reserved.</span><span>Train Hard • Stay Genuine</span></div></footer>
<div id="toast"></div>

<script>
let cart=JSON.parse(localStorage.getItem('genuineCart')||'[]');
function update(){document.getElementById('count').textContent=cart.length;localStorage.setItem('genuineCart',JSON.stringify(cart))}
function addToCart(name,price){cart.push({name,price});update();toast(name+' added to cart ✓')}
function showCart(){
  if(!cart.length){toast('Your cart is empty');return}
  const total=cart.reduce((s,x)=>s+x.price,0);
  alert('GENUINE GYM NUTRITION\\n\\n'+cart.map((x,i)=>(i+1)+'. '+x.name+' — ₹'+x.price).join('\\n')+'\\n\\nTotal: ₹'+total);
}
function toast(msg){const t=document.getElementById('toast');t.textContent=msg;t.classList.add('show');setTimeout(()=>t.classList.remove('show'),2200)}
function sendMessage(e){e.preventDefault();toast('Message ready — connect your email/WhatsApp to receive it.');e.target.reset()}
update();
</script>
</body>
</html>