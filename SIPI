<!doctype html>  
<html lang="fa" dir="rtl">  
<head>  
  <meta charset="utf-8" />  
  <meta name="viewport" content="width=device-width, initial-scale=1" />  
  <title>کاستوم‌ها</title>  
  <style>  
    body {  
      margin: 0;  
      height: 100vh;  
      background: linear-gradient(180deg, #0b1220, #061220);  
      font-family: Tahoma, sans-serif;  
      color: #e6eef6;  
      display: flex;  
      justify-content: center;  
      align-items: center;  
      text-align: center;  
      position: relative;  
      padding-bottom: 60px;  
    }  
    a.button {  
      display: inline-block;  
      padding: 14px 28px;  
      border-radius: 12px;  
      background: linear-gradient(90deg, #06b6d4, #7c3aed);  
      color: #022;  
      font-weight: bold;  
      text-decoration: none;  
      box-shadow: 0 8px 24px rgba(6, 182, 212, 0.25);  
      transition: opacity 0.3s ease;  
      font-size: 18px;  
      cursor: pointer;  
      user-select: none;  
    }  
    a.button:hover {  
      opacity: 0.9;  
    }  
    /* دکمه‌ها بالا */  
    .top-btn {  
      position: fixed;  
      top: 15px;  
      padding: 10px 16px;  
      border-radius: 8px;  
      background: linear-gradient(90deg, #7c3aed, #06b6d4);  
      color: #e6eef6;  
      font-weight: bold;  
      box-shadow: 0 6px 18px rgba(124, 58, 237, 0.4);  
      cursor: pointer;  
      text-decoration: none;  
      z-index: 1000;  
      user-select: none;  
      font-size: 14px;  
      transition: opacity 0.3s ease;  
    }  
    .top-btn:hover {  
      opacity: 0.85;  
    }  
    .top-left-btn { left: 15px; }  
    .top-center-btn { left: 50%; transform: translateX(-50%); }  
    .top-right-btn { right: 15px; }  
  
    /* استایل پاپ‌آپ */  
    .modal {  
      display: none;  
      position: fixed;  
      z-index: 2000;  
      left: 0; top: 0;  
      width: 100%; height: 100%;  
      background-color: rgba(0,0,0,0.6);  
      justify-content: center;  
      align-items: center;  
      padding: 10px;  
    }  
    .modal-content {  
      background: #122038;  
      border-radius: 12px;  
      padding: 25px 30px;  
      max-width: 350px;  
      color: #e6eef6;  
      text-align: center;  
      box-shadow: 0 8px 30px rgba(124, 58, 237, 0.5);  
      position: relative;  
      font-size: 16px;  
      line-height: 1.7;  
    }  
    .modal-content h2 {  
      margin-top: 0;  
      margin-bottom: 15px;  
    }  
    .close-btn {  
      position: absolute;  
      top: 12px;  
      right: 15px;  
      background: transparent;  
      border: none;  
      color: #e6eef6;  
      font-size: 24px;  
      cursor: pointer;  
      font-weight: bold;  
      line-height: 1;  
      user-select: none;  
    }  
    .close-btn:hover {  
      color: #7c3aed;  
    }  
    .rubika-btn {  
      display: inline-block;  
      margin-top: 10px;  
      padding: 10px 18px;  
      border-radius: 8px;  
      background: linear-gradient(90deg, #06b6d4, #7c3aed);  
      color: #022;  
      font-weight: bold;  
      text-decoration: none;  
      box-shadow: 0 6px 18px rgba(6, 182, 212, 0.3);  
      transition: opacity 0.3s ease;  
      display: block;  
    }  
    .rubika-btn:hover {  
      opacity: 0.9;  
    }  
  </style>  
</head>  
<body>  
  <!-- دکمه‌ها بالا -->  
  <a href="#" class="top-btn top-left-btn" id="openModalBtn">درباره ما و ادمین‌ها</a>  
  <a href="#" class="top-btn top-center-btn" id="channelsBtn">ورود به چنل روبیکا</a>  
  <a href="#" class="top-btn top-right-btn" id="buyCpBtn">خرید سی‌پی</a>  
  
  <!-- دکمه پایین -->  
  <a href="#" class="button" id="customsBtn" style="position: fixed; bottom: 20px; left: 50%; transform: translateX(-50%); max-width: 300px;">  
    کاستوم‌های موجود  
  </a>  
  
  <!-- پاپ‌آپ درباره ما -->  
  <div class="modal" id="modal">  
    <div class="modal-content">  
      <button class="close-btn" id="closeModalBtn">&times;</button>  
      <h2>ادمین‌های ما</h2>  
      <p>بزودی کاستوم‌های جدیدی قرار می‌گذارند 🤗</p>  
    </div>  
  </div>  
  
  <!-- پاپ‌آپ کاستوم‌ها -->  
  <div class="modal" id="customModal">  
    <div class="modal-content">  
      <button class="close-btn" id="closeCustomModalBtn">&times;</button>  
      <h2>کاستوم‌های موجود</h2>  
      <p>کاستومی وجود ندارد😭</p>  
    </div>  
  </div>  
  
  <!-- پاپ‌آپ خرید سی‌پی -->  
  <div class="modal" id="buyCpModal">  
    <div class="modal-content">  
      <button class="close-btn" id="closeBuyCpModalBtn">&times;</button>  
      <h2>خرید سی‌پی</h2>  
      <p>  
        80CP — 90T<br>  
        160CP — 171T<br>  
        240CP — 252T<br>  
        500CP — 510T  
      </p>  
      <p>  
        اگر مقدار سی‌پی شما بیشتر بود، به آیدی زیر در روبیکا پیام دهید.<br>  
        شماره کارت: <b>5022291538200393</b><br>  
        حسین سیمیاری  
      </p>  
      <p style="color:#ff6b6b;">از رسید فیک خودداری کنید.</p>  
      <a href="https://rubika.ir/Gosettaki" target="_blank" class="rubika-btn">روبیکا من</a>  
    </div>  
  </div>  
  
  <!-- پاپ‌آپ کانال‌ها -->  
  <div class="modal" id="channelsModal">  
    <div class="modal-content">  
      <button class="close-btn" id="closeChannelsModalBtn">&times;</button>  
      <h2>ورود به چنل روبیکا</h2>  
      <a href="https://rubika.ir/joinc/DJJCAGAJ0YWATAKEWMPDSSRTJKFNHQGD" target="_blank" class="rubika-btn">چنل اعتماد</a>  
      <a href="https://rubika.ir/Granion" target="_blank" class="rubika-btn">چنل روبیکا</a>  
      <a href="https://rubika.ir/joing/IGGCEEDC0EMGUHYGYCBPSKKEDZDYHIOD" target="_blank" class="rubika-btn">گپ</a>  
    </div>  
  </div>  
  
  <script>  
    // درباره ما  
    const modal = document.getElementById('modal');  
    document.getElementById('openModalBtn').onclick = e => { e.preventDefault(); modal.style.display = 'flex'; };  
    document.getElementById('closeModalBtn').onclick = () => modal.style.display = 'none';  
  
    // کاستوم‌ها  
    const customModal = document.getElementById('customModal');  
    document.getElementById('customsBtn').onclick = e => { e.preventDefault(); customModal.style.display = 'flex'; };  
    document.getElementById('closeCustomModalBtn').onclick = () => customModal.style.display = 'none';  
  
    // خرید سی‌پی  
    const buyCpModal = document.getElementById('buyCpModal');  
    document.getElementById('buyCpBtn').onclick = e => { e.preventDefault(); buyCpModal.style.display = 'flex'; };  
    document.getElementById('closeBuyCpModalBtn').onclick = () => buyCpModal.style.display = 'none';  
  
    // کانال‌ها  
    const channelsModal = document.getElementById('channelsModal');  
    document.getElementById('channelsBtn').onclick = e => { e.preventDefault(); channelsModal.style.display = 'flex'; };  
    document.getElementById('closeChannelsModalBtn').onclick = () => channelsModal.style.display = 'none';  
  
    // بستن وقتی بیرون کلیک شد  
    window.onclick = e => {  
      if (e.target === modal) modal.style.display = 'none';  
      if (e.target === customModal) customModal.style.display = 'none';  
      if (e.target === buyCpModal) buyCpModal.style.display = 'none';  
      if (e.target === channelsModal) channelsModal.style.display = 'none';  
    };  
  </script>  
</body>  
</html>
