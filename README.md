<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Bişkin Bilişim | Teknik Servis & Bakım</title>
<meta name="description" content="Bişkin Bilişim - Yazıcı, fotokopi, konsol, modem, kamera sistemleri teknik servis ve bakım.">
<meta name="theme-color" content="#0f1a2b">
<style>
  :root {
    --bg: #0f1a2b;
    --card: #162540;
    --line: #1f3a4d;
    --teal: #2dd4bf;
    --text: #f1f5f9;
    --muted: #94a3b8;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: -apple-system, "Segoe UI", Roboto, Inter, Arial, sans-serif;
    min-height: 100vh;
    background-image:
      radial-gradient(circle at 90% 5%, rgba(45,212,191,.10), transparent 40%),
      radial-gradient(circle at 5% 95%, rgba(45,212,191,.07), transparent 40%);
  }
  .wrap { max-width: 480px; margin: 0 auto; padding: 32px 20px 40px; }

  .brand { display: flex; align-items: center; gap: 14px; margin-bottom: 28px; }
  .brand svg { width: 64px; height: 64px; flex: none; }
  .brand h1 { font-size: 26px; line-height: 1.1; }
  .brand p { color: var(--teal); letter-spacing: 2px; font-size: 12px; margin-top: 6px; font-weight: 600; }

  .owner { border-left: 4px solid var(--teal); padding-left: 14px; margin-bottom: 22px; }
  .owner .name { font-size: 22px; font-weight: 700; }
  .owner .phone { color: var(--teal); font-size: 24px; font-weight: 700; text-decoration: none; display: inline-block; margin-top: 4px; }

  .btns { display: grid; gap: 10px; margin-bottom: 30px; }
  .btn {
    display: flex; align-items: center; justify-content: center; gap: 10px;
    padding: 15px; border-radius: 14px; font-size: 16px; font-weight: 600;
    text-decoration: none; color: var(--text);
    background: var(--card); border: 1px solid var(--line);
  }
  .btn.primary { background: var(--teal); color: #06231f; border-color: var(--teal); }
  .btn svg { width: 20px; height: 20px; }
  .hidden { display: none !important; }

  h2 { color: var(--teal); letter-spacing: 3px; font-size: 14px; margin-bottom: 14px; }
  .services { display: grid; gap: 10px; }
  .service {
    display: flex; align-items: center; gap: 14px;
    background: var(--card); border: 1px solid var(--line);
    border-radius: 14px; padding: 14px 16px; font-weight: 600; line-height: 1.3;
  }
  .service svg { width: 26px; height: 26px; flex: none; stroke: var(--teal); fill: none; stroke-width: 1.8; stroke-linecap: round; stroke-linejoin: round; }

  .address { margin-top: 28px; color: var(--muted); font-size: 15px; line-height: 1.5; }
  .address strong { color: var(--text); display: block; margin-bottom: 4px; }

  footer { margin-top: 36px; text-align: center; color: var(--muted); font-size: 13px; }
  footer b { color: var(--text); } footer span { color: var(--teal); font-weight: 700; }
</style>
</head>
<body>
<div class="wrap">

  <div class="brand">
    <svg viewBox="0 0 240 240" role="img" aria-label="OB logosu"><g fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M88 12v28M120 12v28M152 12v28M88 200v28M120 200v28M152 200v28M12 88h28M12 120h28M12 152h28M200 88h28M200 120h28M200 152h28" stroke="#2EC4B6" stroke-width="8"></path><rect x="40" y="40" width="160" height="160" rx="34" stroke="#2EC4B6" stroke-width="8"></rect><ellipse cx="92" cy="120" rx="24" ry="28" stroke="#F2F5F9" stroke-width="12"></ellipse><path d="M138 92H153a13 13 0 0 1 0 26H138M138 118H157a15 15 0 0 1 0 30H138M138 92V148" stroke="#2EC4B6" stroke-width="12"></path></g><circle cx="92" cy="120" r="6" fill="#2EC4B6"></circle></svg>
    <div>
      <h1>Bişkin Bilişim</h1>
      <p>TEKNİK SERVİS &amp; BAKIM</p>
    </div>
  </div>

  <div class="owner">
    <div class="name">Osman BİŞKİN</div>
    <a class="phone" href="tel:+905312893892">0531 289 38 92</a>
  </div>

  <!-- BUTONLAR: Boş bıraktığın butonlar otomatik gizlenir (aşağıdaki AYARLAR kısmına bak) -->
  <div class="btns">
    <a class="btn primary" href="tel:+905312893892">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.9v3a2 2 0 0 1-2.2 2 19.8 19.8 0 0 1-8.6-3.1 19.5 19.5 0 0 1-6-6A19.8 19.8 0 0 1 2.1 4.2 2 2 0 0 1 4.1 2h3a2 2 0 0 1 2 1.7c.1 1 .4 1.9.7 2.8a2 2 0 0 1-.5 2.1L8 9.9a16 16 0 0 0 6 6l1.3-1.3a2 2 0 0 1 2.1-.4c.9.3 1.8.6 2.8.7a2 2 0 0 1 1.7 2z"/></svg>
      Hemen Ara
    </a>
    <a class="btn hidden" id="btn-wa" href="#">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 11.5a8.4 8.4 0 0 1-12.4 7.4L3 20.5l1.7-5.4A8.4 8.4 0 1 1 21 11.5z"/></svg>
      WhatsApp'tan Yaz
    </a>
    <a class="btn hidden" id="btn-ig" href="#">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r="1"/></svg>
      Instagram
    </a>
    <a class="btn hidden" id="btn-map" href="#">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s7-6.2 7-12a7 7 0 0 0-14 0c0 5.8 7 12 7 12z"/><circle cx="12" cy="10" r="2.5"/></svg>
      Yol Tarifi Al
    </a>
  </div>

  <h2>HİZMETLERİMİZ</h2>
  <div class="services">
    <div class="service">
      <svg viewBox="0 0 24 24"><path d="M6 9V3h12v6M6 18H4a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-2"/><rect x="6" y="14" width="12" height="7"/></svg>
      Yazıcı Fotokopi Tamiri ve Bakımı
    </div>
    <div class="service">
      <svg viewBox="0 0 24 24"><path d="M6 11h4M8 9v4M15 12h.01M18 10h.01"/><path d="M17.3 5H6.7a4 4 0 0 0-3.9 3.2l-1.3 6.3A3 3 0 0 0 4.4 18c1 0 1.9-.5 2.4-1.3L8 15h8l1.2 1.7c.5.8 1.4 1.3 2.4 1.3a3 3 0 0 0 2.9-3.5l-1.3-6.3A4 4 0 0 0 17.3 5z"/></svg>
      Xbox-Ps3-Ps4-Ps5 Tamiri ve Bakımı
    </div>
    <div class="service">
      <svg viewBox="0 0 24 24"><rect x="3" y="14" width="18" height="6" rx="2"/><path d="M7 17h.01M8 14l-2-8M16 14l2-8"/></svg>
      Modem Superbox Kurulumu
    </div>
    <div class="service">
      <svg viewBox="0 0 24 24"><rect x="2" y="7" width="15" height="9" rx="2"/><circle cx="9.5" cy="11.5" r="2"/><path d="M17 11l5-3v8l-5-3"/></svg>
      İP-Analog Kamera Sistemleri
    </div>
    <div class="service">
      <svg viewBox="0 0 24 24"><path d="M6 3h12v8a3 3 0 0 1-3 3h-6a3 3 0 0 1-3-3V3zM9 3v4M12 3v4M15 3v4M12 14v7"/></svg>
      Cat5 Cat6 Dsl Kablo Sorunları
    </div>
    <div class="service">
      <svg viewBox="0 0 24 24"><rect x="3" y="4" width="18" height="12" rx="2"/><path d="M8 20h8M12 16v4"/></svg>
      Oyun Yükleme Yazılım Sorunları
    </div>
  </div>

  <div class="address hidden" id="address-box">
    <strong>Adres</strong>
    <span id="address-text"></span>
  </div>

  <footer>© <b>Bişkin</b> <span>Bilişim</span></footer>
</div>

<script>
  // ================= AYARLAR =================
  // Aşağıdaki alanları doldur. Boş ("") bırakırsan o buton/bölüm sayfada görünmez.

  const INSTAGRAM = "biskinbilisim";   // sadece kullanıcı adı
  const WHATSAPP  = "905312893892";  // WhatsApp kullanmıyorsan "" yap
  const ADRES     = "";   // örn: "Atatürk Cad. No:12, Merkez / Şehir"
  const HARITA    = "";   // Google Haritalar'dan "Paylaş" ile aldığın link
  // ===========================================

  function show(id, href) {
    const el = document.getElementById(id);
    el.href = href;
    el.classList.remove("hidden");
  }
  if (INSTAGRAM) show("btn-ig", "https://instagram.com/" + INSTAGRAM.replace("@",""));
  if (WHATSAPP)  show("btn-wa", "https://wa.me/" + WHATSAPP);
  if (HARITA)    show("btn-map", HARITA);
  if (ADRES) {
    document.getElementById("address-text").textContent = ADRES;
    document.getElementById("address-box").classList.remove("hidden");
  }
</script>
</body>
</html>
