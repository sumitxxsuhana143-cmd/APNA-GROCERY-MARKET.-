# APNA-GROCERY-MARKET.-
SUMIT KIRANA STORE 
<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#087443">
<title>SUMIT KIRANA STORE | ऑनलाइन किराना</title>
<style>
:root{--green:#087443;--green2:#0ca65c;--light:#f2fbf5;--ink:#17231c;--muted:#647268;--line:#e1eee5}
*{box-sizing:border-box}body{margin:0;font-family:system-ui,-apple-system,"Noto Sans Devanagari",Arial,sans-serif;background:#f6f8f6;color:var(--ink)}
header{background:linear-gradient(120deg,#065b35,#0ca65c);color:white;padding:18px 16px 20px;border-radius:0 0 24px 24px}
.top,main,.hero{max-width:1000px;margin-left:auto;margin-right:auto}.top{display:flex;justify-content:space-between;align-items:center;gap:12px}.brand{font-weight:900;font-size:clamp(18px,4vw,25px)}.sub{font-size:12px;opacity:.9;margin-top:3px}.pill{background:#ffffff20;border:1px solid #ffffff45;padding:8px 11px;border-radius:999px;font-size:12px;white-space:nowrap}
.hero{margin-top:18px;background:#ffffff15;border:1px solid #ffffff35;border-radius:18px;padding:17px}.hero h1{font-size:clamp(23px,5vw,34px);line-height:1.2;margin:0 0 8px}.hero p{margin:0;color:#e9fff0;font-size:14px}.tag{display:inline-block;background:#fff;color:#087443;font-weight:800;border-radius:7px;padding:5px 9px;margin-bottom:10px;font-size:12px}
main{padding:16px 14px 95px}.notice{background:#fff8e8;border:1px solid #f5d99e;border-radius:12px;padding:12px;font-size:13px;line-height:1.5;margin-bottom:15px}.benefits{display:grid;grid-template-columns:repeat(3,1fr);gap:9px;margin-bottom:20px}.benefit{background:white;border:1px solid var(--line);border-radius:13px;padding:12px 8px;text-align:center;font-size:12px;font-weight:700}.benefit span{display:block;font-size:21px;margin-bottom:4px}
.section-title{display:flex;align-items:center;justify-content:space-between;gap:12px;margin:22px 0 12px}.section-title h2{font-size:20px;margin:0}.section-title small{color:var(--muted)}.tools{display:flex;gap:8px;margin-bottom:13px}.tools input,.tools select{min-width:0;border:1px solid #d7e5db;border-radius:12px;padding:12px;background:white;font:inherit}.tools input{flex:1}
.products{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:12px}.card{background:white;border:1px solid var(--line);border-radius:16px;overflow:hidden;box-shadow:0 3px 12px #12351a08}.product-art{height:135px;background:linear-gradient(135deg,#e4f8e8,#fff3dc);display:grid;place-items:center;font-size:58px;position:relative}.product-art img{width:100%;height:100%;object-fit:contain;background:#fff}.card-body{padding:12px}.card h3{margin:0 0 5px;font-size:16px}.desc{color:var(--muted);font-size:12px}.price{font-size:18px;font-weight:900;color:var(--green);margin:8px 0 10px}.price small{font-size:11px;font-weight:500;color:var(--muted)}.add,.primary,.secondary,.photo-label,.save-price{border:0;border-radius:10px;font:inherit;font-weight:800;cursor:pointer}.add{width:100%;background:var(--green);color:white;padding:11px;font-size:14px}.photo-label{display:block;text-align:center;background:#eef8f0;color:#075d33;padding:9px 7px;margin:8px 0;font-size:12px;border:1px solid #d6eadb}.photo-input{display:none}.price-edit{display:flex;gap:5px;align-items:center;margin:8px 0}.price-edit input{width:100%;min-width:0;border:1px solid #d7e5db;border-radius:8px;padding:8px;font:inherit}.save-price{padding:8px;background:#edf5ff;color:#174b88;font-size:12px}
.panel{background:white;border:1px solid var(--line);border-radius:17px;padding:15px;margin-top:18px}.cart-row{display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid #edf2ee}.cart-row:last-child{border-bottom:0}.cart-emoji{font-size:28px}.cart-info{flex:1;min-width:0}.cart-info strong{display:block}.cart-info small{color:var(--muted)}.qty{display:flex;align-items:center;gap:9px}.qty button{border:1px solid #d7e5db;background:#f7fbf8;border-radius:8px;width:30px;height:30px;font-size:18px;color:var(--green)}
.totals{border-top:1px dashed #d5e3d8;margin-top:10px;padding-top:10px}.total-line{display:flex;justify-content:space-between;margin:7px 0}.grand{font-size:20px;font-weight:900;color:var(--green)}.primary,.secondary{display:block;width:100%;padding:13px 12px;margin-top:10px}.primary{background:#16a34a;color:white}.secondary{background:#fff5e8;color:#854d0e;border:1px solid #ffdfb4}.hint{font-size:12px;line-height:1.6;color:var(--muted)}.contact-grid{display:grid;grid-template-columns:1fr;gap:10px}.contact-item{background:var(--light);border-radius:12px;padding:12px;font-size:14px}.contact-item strong{display:block;margin-bottom:4px}.footer{background:#073e27;color:#eaffef;padding:20px 16px;text-align:center;font-size:12px}.sticky{position:fixed;bottom:0;left:0;right:0;background:#ffffffee;backdrop-filter:blur(10px);padding:10px 14px calc(10px + env(safe-area-inset-bottom));border-top:1px solid var(--line);display:flex;justify-content:center;z-index:5}.sticky button{max-width:1000px;width:100%;background:#087443;color:white;border:0;border-radius:13px;padding:13px;font:inherit;font-weight:900}.empty{text-align:center;color:var(--muted);padding:20px}.badge{font-size:11px;background:#e8f8ed;color:#087443;padding:4px 7px;border-radius:999px;font-weight:800}
@media(min-width:600px){.products{grid-template-columns:repeat(3,minmax(0,1fr))}.product-art{height:155px}.contact-grid{grid-template-columns:1fr 1fr}.benefits{gap:14px}.benefit{font-size:14px;padding:16px}}@media(min-width:850px){.products{grid-template-columns:repeat(4,minmax(0,1fr))}.product-art{height:165px}main{padding-top:22px}}

.action-row{display:flex;gap:8px;flex-wrap:wrap;margin:14px auto 0;max-width:1000px}
.action-row button{border:1px solid #ffffff55;background:#ffffff18;color:white;border-radius:10px;padding:10px 12px;font:inherit;font-weight:800;cursor:pointer}
.form-grid{display:grid;grid-template-columns:1fr;gap:10px}
.form-grid label{display:block;font-size:13px;font-weight:700;margin-bottom:5px}
.form-grid input,.form-grid textarea,.form-grid select{width:100%;border:1px solid #d7e5db;border-radius:10px;padding:11px;font:inherit;background:white;color:var(--ink)}
.form-grid textarea{min-height:76px;resize:vertical}
.panel-head{display:flex;justify-content:space-between;align-items:center;gap:10px}
.small-btn{border:1px solid #d7e5db;background:#f7fbf8;border-radius:9px;padding:8px 10px;font:inherit;font-weight:800;color:var(--green)}
.admin-note{background:#fff8e8;border:1px solid #f5d99e;border-radius:10px;padding:10px;font-size:12px;line-height:1.5}
.hidden{display:none!important}
@media(min-width:600px){.form-grid{grid-template-columns:1fr 1fr}.form-grid .wide{grid-column:1/-1}}


.weight-label{display:block;font-size:12px;font-weight:700;margin:10px 0 5px;color:var(--muted)}
.weight-select{width:100%;border:1px solid var(--line);border-radius:10px;padding:10px;background:var(--surface);color:var(--text);font:inherit;margin-bottom:8px}

</style>
</head>
<body>
<header><div class="top"><div><div class="brand" id="storeBrand">🛒 SUMIT KIRANA STORE</div><div class="sub">हर घर की जरूरत, अब आपके मोबाइल पर</div></div><div class="pill">🏠 होम डिलीवरी</div></div>
<div class="hero"><span class="tag">ताज़ा सामान • उचित कीमत</span><h1>आपका रोज़मर्रा का सामान,<br>अब घर बैठे मँगाएँ!</h1><p>सामान चुनें, मात्रा तय करें और WhatsApp पर अपना ऑर्डर भेजें।</p></div><div class="action-row"><button type="button" onclick="togglePanel('profilePanel')">👤 मेरी प्रोफाइल</button><button type="button" onclick="togglePanel('adminPanel')">⚙️ दुकान एडमिन / सेटिंग्स</button></div></header>
<main>
<div class="notice"><b>दुकानदार के लिए:</b> हर सामान के नीचे <b>📷 फोटो चुनें</b> दबाकर अपने मोबाइल की गैलरी से असली फोटो लगाएँ। कीमत बदलकर <b>कीमत सेव करें</b> दबाएँ। बदलाव इसी ब्राउज़र में सेव होंगे। असली फोटो लगाने के लिए अपनी दुकान/पैक की फोटो सबसे बेहतर है। नए प्रोडक्ट की कीमत खाली है—एडमिन की तरह नीचे कीमत भरकर सेव करें।</div>
<div class="benefits"><div class="benefit"><span>🌿</span>रोज़मर्रा का सामान</div><div class="benefit"><span>💰</span>साफ़ कीमतें</div><div class="benefit"><span>🛵</span>होम डिलीवरी</div></div>

<section class="panel hidden" id="profilePanel">
  <div class="panel-head"><div class="section-title" style="margin:0"><h2>👤 ग्राहक प्रोफाइल</h2></div><button class="small-btn" type="button" onclick="togglePanel('profilePanel')">बंद करें ✕</button></div>
  <p class="hint">अपना नाम, मोबाइल और डिलीवरी पता सेव करें। ये जानकारी इसी ब्राउज़र में रहेगी।</p>
  <div class="form-grid">
    <div><label for="customerName">आपका नाम</label><input id="customerName" autocomplete="name" placeholder="अपना नाम लिखें"></div>
    <div><label for="customerPhone">मोबाइल नंबर</label><input id="customerPhone" inputmode="tel" autocomplete="tel" placeholder="मोबाइल नंबर"></div>
    <div class="wide"><label for="customerAddress">डिलीवरी का पूरा पता</label><textarea id="customerAddress" autocomplete="street-address" placeholder="गाँव, पोस्ट, थाना, जिला आदि"></textarea></div>
  </div>
  <button class="primary" type="button" onclick="saveProfile()">प्रोफाइल सेव करें</button>
  <p id="profileStatus" class="hint" aria-live="polite"></p>
</section>

<section class="panel hidden" id="adminPanel">
  <div class="panel-head"><div class="section-title" style="margin:0"><h2>⚙️ दुकान एडमिन और सेटिंग्स</h2></div><button class="small-btn" type="button" onclick="togglePanel('adminPanel')">बंद करें ✕</button></div>
  <div class="admin-note">यह बेसिक एडमिन पैनल है। इसकी सेटिंग्स इसी मोबाइल/ब्राउज़र में सेव होती हैं; इसमें ऑनलाइन लॉगिन या सुरक्षित पासवर्ड व्यवस्था नहीं है। सार्वजनिक ऐप में संवेदनशील जानकारी न रखें।</div>
  <div class="form-grid" style="margin-top:12px">
    <div><label for="settingStoreName">दुकान का नाम</label><input id="settingStoreName" value="SUMIT KIRANA STORE"></div>
    <div><label for="settingOwner">मालिक का नाम</label><input id="settingOwner" value="NIRANJAN SHARMA"></div>
    <div><label for="settingWhatsApp">WhatsApp नंबर (देश कोड सहित)</label><input id="settingWhatsApp" inputmode="numeric" value="918092001254" placeholder="जैसे 91XXXXXXXXXX"></div>
    <div><label for="settingTheme">मुख्य रंग</label><select id="settingTheme"><option value="green">हरा</option><option value="blue">नीला</option><option value="orange">नारंगी</option><option value="purple">बैंगनी</option></select></div>
    <div class="wide"><label for="settingAddress">दुकान का पता</label><textarea id="settingAddress">AT NAGDAHARI, POST–DHOLBAZZA BAZAR, RUPAULI, PURNEA, BIHAR</textarea></div>
  </div>
  <button class="primary" type="button" onclick="saveStoreSettings()">दुकान की सेटिंग्स सेव करें</button>
  <button class="secondary" type="button" onclick="resetStoreSettings()">दुकान की डिफ़ॉल्ट सेटिंग्स वापस करें</button>
  <p id="adminStatus" class="hint" aria-live="polite"></p>
</section>

<section id="shop"><div class="section-title"><h2>हमारे प्रोडक्ट</h2><span class="badge" id="productCount">प्रोडक्ट</span></div><div class="tools"><input id="search" type="search" placeholder="🔎 सामान खोजें..." aria-label="सामान खोजें"><select id="categoryFilter" aria-label="श्रेणी चुनें"><option value="all">सभी श्रेणियाँ</option></select><select id="sort" aria-label="कीमत के अनुसार"><option value="default">क्रम</option><option value="low">कम कीमत</option><option value="high">ज़्यादा कीमत</option></select></div><div class="products" id="products"></div></section>
<section class="panel" id="cart"><div class="section-title" style="margin-top:0"><h2>🛍️ आपका कार्ट</h2><small id="cartCount">0 सामान</small></div><div id="cartItems"><div class="empty">अभी कार्ट खाली है। ऊपर से सामान जोड़ें।</div></div><div class="totals"><div class="total-line"><span>सामान का कुल</span><strong id="subtotal">₹0</strong></div><div class="total-line"><span>डिलीवरी शुल्क</span><strong>दुकानदार बताएगा</strong></div><div class="total-line grand"><span>कुल सामान कीमत</span><span id="total">₹0</span></div><p class="hint">डिलीवरी शुल्क, उपलब्धता और अंतिम बिल की पुष्टि दुकान WhatsApp पर करेगी।</p><button class="primary" onclick="sendOrder()">🟢 WhatsApp पर ऑर्डर भेजें</button><button class="secondary" onclick="clearCart()">कार्ट खाली करें</button></div></section>
<section class="panel" id="contact"><div class="section-title" style="margin-top:0"><h2>📍 दुकान की जानकारी</h2></div><div class="contact-grid"><div class="contact-item"><strong>🏪 दुकान</strong><span id="contactStoreName">SUMIT KIRANA STORE</span><br>मालिक: <span id="contactOwner">NIRANJAN SHARMA</span></div><div class="contact-item"><strong>📞 WhatsApp / फोन</strong><a id="contactWhatsAppLink" href="https://wa.me/918092001254" target="_blank" rel="noopener">8092001254 पर संपर्क करें</a></div><div class="contact-item"><strong>📌 पता</strong><span id="contactAddress">AT NAGDAHARI, POST–DHOLBAZZA BAZAR, RUPAULI, PURNEA, BIHAR</span></div><div class="contact-item"><strong>💳 भुगतान</strong>UPI और Cash<br><span class="hint">UPI भुगतान से पहले दुकान से पुष्टि करें।</span></div></div><p class="hint">इस वेबसाइट में ऑनलाइन पेमेंट गेटवे नहीं है। ऑर्डर WhatsApp पर भेजा जाता है।</p></section>
</main><div class="sticky"><button onclick="document.getElementById('cart').scrollIntoView({behavior:'smooth'})">🛒 कार्ट देखें • <span id="stickyTotal">₹0</span></button></div><footer class="footer">© <span id="year"></span> SUMIT KIRANA STORE • धन्यवाद, फिर आइए! 💚</footer>
<script>
let WHATSAPP_NUMBER="918092001254";
const defaults=[
{id:1,name:"आटा",price:40,unit:"किलो",emoji:"🌾",desc:"गेहूँ का आटा",category:"आटा और आटा उत्पाद"},
{id:2,name:"चावल",price:50,unit:"किलो",emoji:"🍚",desc:"सामान्य चावल",category:"अनाज और चावल"},
{id:3,name:"सरसों तेल",price:210,unit:"लीटर",emoji:"🫗",desc:"सरसों का तेल",category:"तेल, घी और मीठी चीजें"},
{id:4,name:"नमक",price:20,unit:"किलो",emoji:"🧂",desc:"सादा नमक",category:"मसाले और नमक"},
{id:5,name:"बासमती चावल",price:60,unit:"किलो",emoji:"🍚",desc:"बासमती चावल",category:"अनाज और चावल"},
{id:6,name:"धनिया",price:220,unit:"किलो",emoji:"🌿",desc:"धनिया मसाला",category:"मसाले और नमक"},
{id:7,name:"मिर्च",price:260,unit:"किलो",emoji:"🌶️",desc:"मिर्च मसाला",category:"मसाले और नमक"},
{id:8,name:"गेहूँ",price:null,unit:"किलो",emoji:"🌾",desc:"गेहूँ",category:"अनाज और चावल"},
{id:9,name:"मैदा",price:null,unit:"किलो",emoji:"🌾",desc:"रिफाइंड आटा",category:"आटा और आटा उत्पाद"},
{id:10,name:"सूजी / रवा",price:null,unit:"किलो",emoji:"🌾",desc:"सूजी / रवा",category:"आटा और आटा उत्पाद"},
{id:11,name:"बेसन",price:null,unit:"किलो",emoji:"🟡",desc:"चना आटा",category:"आटा और आटा उत्पाद"},
{id:12,name:"पोहा",price:null,unit:"किलो",emoji:"🍚",desc:"चिवड़ा / पोहा",category:"अनाज और चावल"},
{id:13,name:"मक्का",price:null,unit:"किलो",emoji:"🌽",desc:"मक्का",category:"अनाज और चावल"},
{id:14,name:"बाजरा",price:null,unit:"किलो",emoji:"🌾",desc:"बाजरा",category:"अनाज और चावल"},
{id:15,name:"रागी",price:null,unit:"किलो",emoji:"🌾",desc:"रागी",category:"अनाज और चावल"},
{id:16,name:"अरहर / तूर दाल",price:null,unit:"किलो",emoji:"🫘",desc:"अरहर दाल",category:"दालें"},
{id:17,name:"चना दाल",price:null,unit:"किलो",emoji:"🫘",desc:"चना दाल",category:"दालें"},
{id:18,name:"काला चना",price:null,unit:"किलो",emoji:"🫘",desc:"काला चना",category:"दालें"},
{id:19,name:"साबुत मसूर दाल",price:null,unit:"किलो",emoji:"🫘",desc:"साबुत मसूर",category:"दालें"},
{id:20,name:"धुली मसूर दाल",price:null,unit:"किलो",emoji:"🫘",desc:"धुली मसूर",category:"दालें"},
{id:21,name:"पीली मूंग दाल",price:null,unit:"किलो",emoji:"🫘",desc:"पीली मूंग दाल",category:"दालें"},
{id:22,name:"हरी / साबुत मूंग",price:null,unit:"किलो",emoji:"🫘",desc:"हरी मूंग",category:"दालें"},
{id:23,name:"काली उड़द दाल",price:null,unit:"किलो",emoji:"🫘",desc:"काली उड़द",category:"दालें"},
{id:24,name:"सफेद उड़द दाल",price:null,unit:"किलो",emoji:"🫘",desc:"सफेद उड़द",category:"दालें"},
{id:25,name:"राजमा",price:null,unit:"किलो",emoji:"🫘",desc:"राजमा",category:"दालें"},
{id:26,name:"छोले / काबुली चना",price:null,unit:"किलो",emoji:"🫘",desc:"सफेद चना",category:"दालें"},
{id:27,name:"सफेद मटर",price:null,unit:"किलो",emoji:"🫘",desc:"सफेद मटर",category:"दालें"},
{id:28,name:"रिफाइंड तेल",price:null,unit:"लीटर",emoji:"🫗",desc:"सोयाबीन / सूरजमुखी तेल",category:"तेल, घी और मीठी चीजें"},
{id:29,name:"देसी घी",price:null,unit:"किलो",emoji:"🧈",desc:"देसी घी",category:"तेल, घी और मीठी चीजें"},
{id:30,name:"चीनी / शक्कर",price:null,unit:"किलो",emoji:"🍚",desc:"चीनी",category:"तेल, घी और मीठी चीजें"},
{id:31,name:"गुड़",price:null,unit:"किलो",emoji:"🟤",desc:"गुड़",category:"तेल, घी और मीठी चीजें"},
{id:32,name:"शहद",price:null,unit:"बोतल",emoji:"🍯",desc:"शहद",category:"तेल, घी और मीठी चीजें"},
{id:33,name:"आयोडीन नमक",price:null,unit:"पैकेट",emoji:"🧂",desc:"आयोडीन युक्त नमक",category:"मसाले और नमक"},
{id:34,name:"काला नमक",price:null,unit:"पैकेट",emoji:"🧂",desc:"काला नमक",category:"मसाले और नमक"},
{id:35,name:"हल्दी पाउडर",price:null,unit:"पैकेट",emoji:"🟡",desc:"हल्दी",category:"मसाले और नमक"},
{id:36,name:"लाल मिर्च पाउडर",price:null,unit:"पैकेट",emoji:"🌶️",desc:"लाल मिर्च पाउडर",category:"मसाले और नमक"},
{id:37,name:"जीरा",price:null,unit:"पैकेट",emoji:"🌿",desc:"जीरा",category:"मसाले और नमक"},
{id:38,name:"काली मिर्च",price:null,unit:"पैकेट",emoji:"⚫",desc:"काली मिर्च",category:"मसाले और नमक"},
{id:39,name:"गरम मसाला",price:null,unit:"पैकेट",emoji:"🌶️",desc:"गरम मसाला",category:"मसाले और नमक"},
{id:40,name:"हींग",price:null,unit:"डिब्बी",emoji:"🟡",desc:"हींग",category:"मसाले और नमक"},
{id:41,name:"सौंफ",price:null,unit:"पैकेट",emoji:"🌿",desc:"सौंफ",category:"मसाले और नमक"},
{id:42,name:"अजवाइन",price:null,unit:"पैकेट",emoji:"🌿",desc:"अजवाइन",category:"मसाले और नमक"},
{id:43,name:"मेथी दाना",price:null,unit:"पैकेट",emoji:"🌿",desc:"मेथी दाना",category:"मसाले और नमक"},
{id:44,name:"तेज पत्ता",price:null,unit:"पैकेट",emoji:"🍃",desc:"तेज पत्ता",category:"मसाले और नमक"},
{id:45,name:"दालचीनी",price:null,unit:"पैकेट",emoji:"🪵",desc:"दालचीनी",category:"मसाले और नमक"},
{id:46,name:"इलायची",price:null,unit:"पैकेट",emoji:"🌿",desc:"इलायची",category:"मसाले और नमक"},
{id:47,name:"लौंग",price:null,unit:"पैकेट",emoji:"🌿",desc:"लौंग",category:"मसाले और नमक"},
{id:48,name:"चाय पत्ती",price:null,unit:"पैकेट",emoji:"🍵",desc:"चाय पत्ती",category:"चाय, कॉफी और पेय पदार्थ"},
{id:49,name:"कॉफी",price:null,unit:"पैकेट",emoji:"☕",desc:"इंस्टेंट कॉफी",category:"चाय, कॉफी और पेय पदार्थ"},
{id:50,name:"हॉर्लिक्स",price:null,unit:"पैक",emoji:"🥛",desc:"हेल्थ ड्रिंक",category:"चाय, कॉफी और पेय पदार्थ"},
{id:51,name:"बूस्ट",price:null,unit:"पैक",emoji:"🥛",desc:"हेल्थ ड्रिंक",category:"चाय, कॉफी और पेय पदार्थ"},
{id:52,name:"बॉर्नविटा",price:null,unit:"पैक",emoji:"🥛",desc:"हेल्थ ड्रिंक",category:"चाय, कॉफी और पेय पदार्थ"},
{id:53,name:"कोल्ड ड्रिंक",price:null,unit:"बोतल",emoji:"🥤",desc:"कोल्ड ड्रिंक",category:"चाय, कॉफी और पेय पदार्थ"},
{id:54,name:"जूस",price:null,unit:"पैक",emoji:"🧃",desc:"फलों का जूस",category:"चाय, कॉफी और पेय पदार्थ"},
{id:55,name:"बादाम",price:null,unit:"किलो",emoji:"🥜",desc:"बादाम",category:"ड्राई फ्रूट्स"},
{id:56,name:"काजू",price:null,unit:"किलो",emoji:"🥜",desc:"काजू",category:"ड्राई फ्रूट्स"},
{id:57,name:"किशमिश",price:null,unit:"किलो",emoji:"🍇",desc:"किशमिश",category:"ड्राई फ्रूट्स"},
{id:58,name:"मखाना",price:null,unit:"पैक",emoji:"⚪",desc:"मखाना",category:"ड्राई फ्रूट्स"},
{id:59,name:"पिस्ता",price:null,unit:"किलो",emoji:"🥜",desc:"पिस्ता",category:"ड्राई फ्रूट्स"},
{id:60,name:"अखरोट",price:null,unit:"किलो",emoji:"🥜",desc:"अखरोट",category:"ड्राई फ्रूट्स"},
{id:61,name:"बिस्कुट",price:null,unit:"पैकेट",emoji:"🍪",desc:"बिस्कुट",category:"स्नैक्स और पैकेज्ड फूड"},
{id:62,name:"कुकीज़",price:null,unit:"पैकेट",emoji:"🍪",desc:"कुकीज़",category:"स्नैक्स और पैकेज्ड फूड"},
{id:63,name:"नमकीन",price:null,unit:"पैकेट",emoji:"🥨",desc:"नमकीन",category:"स्नैक्स और पैकेज्ड फूड"},
{id:64,name:"चिप्स",price:null,unit:"पैकेट",emoji:"🍟",desc:"चिप्स",category:"स्नैक्स और पैकेज्ड फूड"},
{id:65,name:"मैगी / नूडल्स",price:null,unit:"पैक",emoji:"🍜",desc:"इंस्टेंट नूडल्स",category:"स्नैक्स और पैकेज्ड फूड"},
{id:66,name:"टमाटर सॉस",price:null,unit:"बोतल",emoji:
