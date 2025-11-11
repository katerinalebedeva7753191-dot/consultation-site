<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Личная консультация — Катерина Лебедева</title>
<meta name="description" content="Личная энергетическая консультация: 60 минут ясности, фокус на результате, оплата через Stripe. Только 3 места.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@300;400;600;800&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#0b0b0e;--text:#f7f7fb;--muted:#b6b6c1;--accent:#ff375f;--card:#141419;--edge:#23232a;
  }
  *{box-sizing:border-box}
  html,body{margin:0;padding:0;background:var(--bg);color:var(--text);
    font-family:Manrope,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;line-height:1.5}
  .wrap{max-width:1120px;margin:0 auto;padding:20px}
  /* фон */
  .aura{position:fixed;inset:0;overflow:hidden;z-index:-1;
    background:radial-gradient(1200px 800px at 50% -20%, rgba(255,55,95,.08), transparent 60%),
               linear-gradient(180deg,#0b0b0e,#0d0d12 60%)}
  .orb{position:absolute;filter:blur(70px);opacity:.6;border-radius:50%;
    background:radial-gradient(closest-side, rgba(255,55,95,.55), rgba(255,55,95,.15), transparent);
    animation:float 18s ease-in-out infinite;mix-blend-mode:screen}
  .orb.alt{background:radial-gradient(closest-side, rgba(255,140,180,.5), rgba(255,140,180,.12), transparent);animation-duration:22s}
  .orb.blue{background:radial-gradient(closest-side, rgba(120,130,255,.45), rgba(120,130,255,.12), transparent);animation-duration:26s}
  @keyframes float{0%{transform:translate3d(-10%,-5%,0) scale(1)}50%{transform:translate3d(10%,8%,0) scale(1.08)}100%{transform:translate3d(-10%,-5%,0) scale(1)}}
  .shimmer{position:absolute;inset:-30%;pointer-events:none;
    background:conic-gradient(from 0deg, rgba(255,255,255,.05), transparent 20%, rgba(255,255,255,.04), transparent 60%);
    animation:rotate 40s linear infinite;mix-blend-mode:overlay}
  @keyframes rotate{to{transform:rotate(1turn)}}
  /* блок */
  .hero{position:relative;padding:84px 20px 56px;border-radius:22px;overflow:hidden;
    background:linear-gradient(180deg, rgba(255,255,255,.02), rgba(255,255,255,0));
    border:1px solid rgba(255,255,255,.06);backdrop-filter:blur(2px)}
  .badge{display:inline-flex;align-items:center;gap:10px;background:rgba(255,55,95,.12);
    border:1px solid rgba(255,55,95,.35);padding:8px 14px;border-radius:999px;font-weight:600;letter-spacing:.2px}
  .badge .dot{width:8px;height:8px;border-radius:50%;background:var(--accent);box-shadow:0 0 16px var(--accent)}
  h1{margin:16px 0 10px;font-size:40px;line-height:1.12;letter-spacing:.2px}
  .lead{color:var(--muted);max-width:760px;font-size:18px}
  .keypoints{display:flex;flex-wrap:wrap;gap:12px;margin:24px 0}
  .pill{padding:8px 12px;border-radius:999px;background:#1b1b20;border:1px solid #26262d;font-size:14px;color:#eaeaf0}
  .cta-row{display:flex;flex-wrap:wrap;gap:14px;align-items:center;margin-top:22px}
  .btn-primary{display:inline-block;background:var(--accent);color:#fff;padding:14px 22px;border-radius:14px;
    font-weight:800;letter-spacing:.3px;text-decoration:none;box-shadow:0 0 20px rgba(255,55,95,.3), inset 0 0 20px rgba(255,255,255,.08);transition:all .35s}
  .btn-primary:hover{transform:translateY(-1px) scale(1.02);box-shadow:0 0 26px rgba(255,55,95,.5), inset 0 0 28px rgba(255,255,255,.12)}
  .btn-ghost{display:inline-block;color:var(--text);padding:12px 18px;border-radius:12px;border:1px solid #30303a;text-decoration:none}
  .grid{display:grid;grid-template-columns:1fr;gap:18px;margin-top:28px}
  @media(min-width:900px){.grid{grid-template-columns:1.2fr .8fr}}
  .card{background:var(--card);border:1px solid var(--edge);border-radius:16px;padding:20px;box-shadow:0 10px 30px rgba(0,0,0,.22)}
  .card h3{margin:0 0 10px}
  .list{margin:0;padding:0;list-style:none;display:grid;gap:10px}
  .list li{display:flex;gap:10px;align-items:flex-start;background:#1a1a20;border:1px solid #26262d;padding:12px 12px;border-radius:12px}
  .list .ok{width:10px;height:10px;border-radius:50%;background:#00d18f;margin-top:6px;box-shadow:0 0 10px rgba(0,209,143,.6)}
  .footer{margin:36px 0 12px;color:#8e8e98;font-size:13px;display:flex;flex-wrap:wrap;gap:10px;justify-content:center}
</style>
</head>
<body>
  <div class="aura">
    <div class="orb" style="width:480px;height:480px;left:-8%;top:-6%"></div>
    <div class="orb alt" style="width:520px;height:520px;right:-6%;top:10%"></div>
    <div class="orb blue" style="width:620px;height:620px;left:20%;bottom:-10%"></div>
    <div class="shimmer"></div>
  </div>

  <div class="wrap">
    <section class="hero">
      <div class="badge"><span class="dot"></span> Только 3 места · Оплата через Stripe</div>
      <h1>Личная консультация: <br>энергетическая ясность за 60 минут</h1>
      <p class="lead">Точечно находим, где утекает твоя сила, закрываем сценарии дефицита и включаем состояние Творца. Без воды — только мощное поле, ясные решения и практические шаги.</p>
      <div class="keypoints">
        <span class="pill">Онлайн · Zoom</span>
        <span class="pill">60 минут чистой фокусировки</span>
        <span class="pill">Личный разбор твоего кейса</span>
        <span class="pill">Домашний протокол на 7 дней</span>
      </div>
      <div class="cta-row">
        <a class="btn-primary" href="https://buy.stripe.com/cNiaERda8fDt1nH5Jd1sQ02" target="_blank" rel="noopener">Оплатить сейчас</a>
        <a class="btn-ghost" href="#program">Что внутри</a>
      </div>

      <div class="grid">
        <div class="card" id="program">
          <h3>Что ты получишь</h3>
          <ul class="list">
            <li><span class="ok"></span><div><b>Скан твоего состояния</b> — где именно ты теряешь энергию (деньги, отношения, самореализация).</div></li>
            <li><span class="ok"></span><div><b>Разворот из дефицита в изобилие</b> — перепрошивка ключевого сценария.</div></li>
            <li><span class="ok"></span><div><b>Решение на месте</b> — конкретные шаги и точки фокуса на ближайшие 7 дней.</div></li>
            <li><span class="ok"></span><div><b>Аудио-рекап</b> — короткое голосовое с главными инсайтами.</div></li>
          </ul>
        </div>
        <div class="card">
          <h3>Только 3 места</h3>
          <p>Слоты закрываются по мере оплаты.</p>
          <a class="btn-primary" href="https://buy.stripe.com/cNiaERda8fDt1nH5Jd1sQ02" target="_blank" rel="noopener">Оплатить сейчас</a>
          <p style="color:var(--muted);font-size:13px;margin-top:10px">После оплаты откроется форма для выбора удобного времени.</p>
        </div>
      </div>
    </section>

    <section class="wrap" style="padding:0;margin-top:28px">
      <div class="grid">
        <div class="card">
          <h3>Как проходит сессия</h3>
          <ul class="list">
            <li><span class="ok"></span><div><b>0–5 мин.</b> Быстро синхронизируем запрос и цель.</div></li>
            <li><span class="ok"></span><div><b>5–40 мин.</b> Глубокий разбор + разворот сценария.</div></li>
            <li><span class="ok"></span><div><b>40–55 мин.</b> План действий на 7 дней.</div></li>
            <li><span class="ok"></span><div><b>55–60 мин.</b> Фиксация состояния + ответы на вопросы.</div></li>
          </ul>
        </div>
        <div class="card">
          <h3>Гарантия</h3>
          <p>Если по итогам первой половины сессии (до 30-й минуты) ты не чувствуешь ценности — <b>верну оплату</b>. Для меня важен результат и честность поля.</p>
        </div>
      </div>
    </section>

    <section class="wrap" style="padding:0;margin-top:28px">
      <div class="card" style="text-align:center">
        <h3>Готов(а) войти в состояние Творца прямо сейчас?</h3>
        <p>Забронируй один из трёх слотов. После оплаты выбери удобное время.</p>
        <a class="btn-primary" href="https://buy.stripe.com/cNiaERda8fDt1nH5Jd1sQ02" target="_blank" rel="noopener">Оплатить сейчас</a>
        <p style="color:var(--muted);font-size:13px;margin-top:10px">Нужна помощь? Напиши ассистенту: <a href="https://t.me/assistant_kl" target="_blank" rel="noopener">@assistant_kl</a></p>
      </div>
    </section>

    <footer class="footer">
      <div>© 2025 Катерина Лебедева • <a href="mailto:kateryna.projects@gmail.com">kateryna.projects@gmail.com</a></div>
    </footer>
  </div>
</body>
</html>
