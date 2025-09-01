<!doctype html>
<html lang="zh-Hant">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>星夜篝火 | Minecraft 伺服器</title>
  <meta name="description" content="星夜篝火 — 一個溫馨的 Minecraft 生存/社群伺服器，建造、探險、合作與每晚的篝火聚會。伺服器 IP：agency-bathroom.gl.joinmc.link" />
  <style>
    :root{
      --bg:#071024; --card:#0b1630; --accent:#9ad3ff; --muted:#9fb6d8;
      --glass: rgba(255,255,255,0.03);
      --radius:18px;
      font-family: -apple-system,BlinkMacSystemFont,'Segoe UI','Noto Sans TC','PingFang TC', 'Microsoft JhengHei', sans-serif;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background: radial-gradient(ellipse at 10% 10%, rgba(154,211,255,0.06), transparent 10%), radial-gradient(ellipse at 90% 80%, rgba(154,211,255,0.03), transparent 10%), var(--bg); color:#eaf4ff}
    /* star field */
    .stars{position:fixed;inset:0;pointer-events:none;z-index:0;background-image: radial-gradient(2px 2px at 10% 20%, rgba(255,255,255,0.18), transparent), radial-gradient(1.4px 1.4px at 70% 40%, rgba(255,255,255,0.12), transparent), radial-gradient(1px 1px at 40% 80%, rgba(255,255,255,0.08), transparent); opacity:0.6}
    .wrap{position:relative;z-index:2;max-width:1100px;margin:40px auto;padding:28px}
    header{display:flex;gap:18px;align-items:center}
    .logo{width:88px;height:88px;border-radius:14px;background:linear-gradient(180deg,#1b2c48,#0b1630);display:flex;align-items:center;justify-content:center;box-shadow:0 6px 18px rgba(0,0,0,0.6), inset 0 -6px 18px rgba(255,255,255,0.02)}
    .logo svg{width:56px;height:56px}
    h1{margin:0;font-size:28px}
    p.lead{margin:4px 0 0;color:var(--muted)}
    main{display:grid;grid-template-columns:1fr 360px;gap:20px;margin-top:20px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);padding:18px;border-radius:14px;backdrop-filter: blur(6px);box-shadow:0 6px 24px rgba(3,8,20,0.6)}
    .hero{padding:28px;border-radius:14px}
    .features{display:grid;grid-template-columns:repeat(2,1fr);gap:10px;margin-top:14px}
    .f{background:var(--glass);padding:10px;border-radius:10px;font-size:14px}
    .join{display:flex;gap:10px;align-items:center;margin-top:18px}
    .ip{font-family:monospace;background:rgba(0,0,0,0.25);padding:8px 12px;border-radius:10px}
    button.primary{background:linear-gradient(180deg,var(--accent),#6fbfff);border:none;padding:10px 14px;border-radius:12px;color:#072033;font-weight:700;cursor:pointer}
    button.ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px 12px;border-radius:10px;color:var(--muted);cursor:pointer}
    aside .card{position:sticky;top:24px}
    .rules{font-size:14px;line-height:1.5;color:var(--muted)}
    footer{margin-top:26px;text-align:center;color:var(--muted);font-size:13px}
    .tags{display:flex;gap:8px;flex-wrap:wrap;margin-top:10px}
    .tag{padding:6px 8px;border-radius:999px;background:rgba(255,255,255,0.03);font-size:13px}
    /* gallery */
    .gallery{display:flex;gap:8px;flex-wrap:wrap;margin-top:12px}
    .shot{width:calc(33.333% - 6px);aspect-ratio:16/9;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(0,0,0,0.2));border-radius:8px}
    /* responsive */
    @media (max-width:900px){main{grid-template-columns:1fr; } .shot{width:calc(50% - 6px)} }
    @media (max-width:520px){.wrap{padding:12px} h1{font-size:20px} .logo{width:64px;height:64px}.hero{padding:16px}}
  </style>
</head>
<body>
  <div class="stars" aria-hidden></div>
  <div class="wrap">
    <header>
      <div class="logo" aria-hidden>
        <!-- simple campfire SVG -->
        <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="g" x1="0" x2="1">
              <stop offset="0" stop-color="#ffd17a"/>
              <stop offset="1" stop-color="#ff7a59"/>
            </linearGradient>
          </defs>
          <circle cx="32" cy="32" r="30" fill="#071224" />
          <path d="M40 24c0 6-6 8-8 12s-8-6-8-12 6-8 8-10 8 4 8 10z" fill="url(#g)"/>
          <rect x="18" y="44" width="28" height="6" rx="3" transform="rotate(-18 32 47)" fill="#3b2b1f"/>
          <rect x="18" y="44" width="28" height="6" rx="3" transform="rotate(18 32 47)" fill="#3b2b1f"/>
        </svg>
      </div>
      <div>
        <h1>星夜篝火 <span style="font-size:14px;color:var(--muted)">— Minecraft 伺服器</span></h1>
        <p class="lead">溫馨生存、社群建設、夜晚篝火聚會 — 與朋友一起在星空下築夢。</p>
      </div>
    </header>

    <main>
      <section>
        <div class="card hero">
          <h2>歡迎來到 星夜篝火</h2>
          <p class="lead">我們是一個注重社群與創造的 Minecraft 伺服器。無論你喜歡建造、冒險或是簡單社交，這裡都有你的位置。</p>

          <div class="features">
            <div class="f">生存模式（保護/土地系統）</div>
            <div class="f">公共建築區與玩家商店</div>
            <div class="f">每晚篝火活動與小遊戲</div>
            <div class="f">插件：經濟 / 家 / 傳送門（範例）</div>
          </div>

          <div class="join">
            <div class="ip" id="server-ip">agency-bathroom.gl.joinmc.link</div>
            <button class="primary" onclick="copyIP()">複製伺服器 IP</button>
            <button class="ghost" onclick="openDiscord()">加入 Discord</button>
          </div>

          <div class="tags">
            <div class="tag">生存</div>
            <div class="tag">社群導向</div>
            <div class="tag">中文伺服器</div>
            <div class="tag">活動頻繁</div>
          </div>

          <h3 style="margin-top:18px">伺服器特色</h3>
          <ul style="color:var(--muted);line-height:1.6">
            <li>新手保護與指引，友善的管理團隊。</li>
            <li>自訂事件（夜間篝火、探險日、建築挑戰）。</li>
            <li>定期備份，保障玩家資料安全。</li>
          </ul>

          <h3 style="margin-top:14px">畫廊</h3>
          <div class="gallery" aria-hidden>
            <div class="shot"></div>
            <div class="shot"></div>
            <div class="shot"></div>
            <div class="shot"></div>
            <div class="shot"></div>
            <div class="shot"></div>
          </div>
        </div>

        <div class="card" style="margin-top:14px">
          <h3>管理團隊</h3>
          <p class="rules">伺服器管理員：星夜團隊<br/>聯絡方式：Discord（伺服器內公告或網站右側聯絡表單）</p>
        </div>

      </section>

      <aside>
        <div class="card">
          <h3>立即加入</h3>
          <p style="margin:8px 0;color:var(--muted)">伺服器 IP（點擊複製）：</p>
          <div style="display:flex;gap:8px;align-items:center">
            <div class="ip" id="aside-ip">agency-bathroom.gl.joinmc.link</div>
            <button class="primary" onclick="copyIP()">複製</button>
          </div>

          <div style="margin-top:14px">
            <h4>伺服器規則</h4>
            <ol class="rules">
              <li>禁止不當言論與歧視。</li>
              <li>禁止破壞他人建築（未經同意）。</li>
              <li>尊重管理員與玩家，依公告指示行事。</li>
            </ol>
            <button class="ghost" style="margin-top:10px" onclick="showMoreRules()">顯示完整規則</button>
          </div>

          <div style="margin-top:12px">
            <h4>活動時間</h4>
            <p class="rules">每週五與週日（20:00 本地時間）舉辦篝火聚會與小型活動。</p>
          </div>

          <div style="margin-top:12px">
            <h4>伺服器版本</h4>
            <p class="rules">Minecraft Java 1.21.x（建議使用相同次版本）</p>
          </div>

        </div>

        <div class="card" style="margin-top:12px">
          <h4>聯絡 / 申請管理</h4>
          <p class="rules">若要回報或申請成為志工管理員，請在 Discord 傳訊管理團隊或填寫伺服器表單。</p>
          <button class="primary" style="width:100%;margin-top:10px" onclick="openDiscord()">前往 Discord</button>
        </div>

      </aside>
    </main>

    <footer>
      <div>© <span id="year"></span> 星夜篝火 — Minecraft 伺服器｜保留所有權利</div>
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
    function copyIP(){
      const ip = document.getElementById('server-ip').textContent.trim();
      navigator.clipboard?.writeText(ip).then(()=>{
        alert('已複製伺服器 IP: ' + ip);
      }).catch(()=>{prompt('請手動複製伺服器 IP', ip)});
    }
    function openDiscord(){
      // 修改為你的 Discord 邀請連結
      const url = 'https://discord.gg/f5XUsVN4j4';
      window.open(url,'_blank');
    }
    function showMoreRules(){
      alert('完整規則請至伺服器公告或 Discord 查看（例：禁止作弊、禁止廣告、尊重他人）。');
    }
  </script>
</body>
</html>
