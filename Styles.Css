 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>styles.css con botón de copiar</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;700&family=Manrope:wght@400;500;700;800&display=swap');

    :root{
      --bg:#0b1020;
      --panel:#121933;
      --panel-2:#0f1630;
      --text:#eef2ff;
      --muted:#aab4d6;
      --line:rgba(255,255,255,.12);
      --accent:#6ee7b7;
      --accent-2:#60a5fa;
      --danger:#fb7185;
      --shadow:0 20px 60px rgba(0,0,0,.35);
      --radius:22px;
    }

    *{box-sizing:border-box}
    body{
      margin:0;
      min-height:100vh;
      font-family:'Manrope',sans-serif;
      background:
        radial-gradient(circle at top left, rgba(96,165,250,.16), transparent 34%),
        radial-gradient(circle at bottom right, rgba(110,231,183,.12), transparent 30%),
        linear-gradient(180deg,#0a0f1f 0%, #0c1328 100%);
      color:var(--text);
      display:grid;
      place-items:center;
      padding:24px;
    }

    .wrap{
      width:min(980px,100%);
      background:linear-gradient(180deg, rgba(255,255,255,.03), rgba(255,255,255,.01));
      border:1px solid var(--line);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      overflow:hidden;
      backdrop-filter: blur(14px);
    }

    .top{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:16px;
      padding:18px 20px;
      border-bottom:1px solid var(--line);
      background:linear-gradient(180deg, rgba(255,255,255,.03), rgba(255,255,255,.01));
    }

    .title{
      font-family:'Space Grotesk',sans-serif;
      font-size:clamp(1.1rem, 2vw, 1.4rem);
      font-weight:700;
      letter-spacing:-.02em;
      margin:0;
    }

    .actions{
      display:flex;
      gap:10px;
      flex-wrap:wrap;
    }

    button{
      border:none;
      border-radius:14px;
      padding:12px 16px;
      font:700 .95rem 'Manrope',sans-serif;
      cursor:pointer;
      transition:.2s ease;
    }

    .copy-btn{
      background:linear-gradient(135deg,var(--accent),var(--accent-2));
      color:#06111f;
    }

    .copy-btn:hover{
      transform:translateY(-1px) scale(1.01);
      filter:brightness(1.05);
    }

    .copy-btn:active{
      transform:translateY(0) scale(.99);
    }

    .status{
      color:var(--muted);
      font-size:.92rem;
      align-self:center;
    }

    .editor{
      padding:0;
      margin:0;
      background:#0a1022;
    }

    textarea{
      width:100%;
      min-height:76vh;
      border:none;
      outline:none;
      resize:vertical;
      padding:22px;
      background:transparent;
      color:#dbe7ff;
      font:500 .95rem/1.7 ui-monospace, SFMono-Regular, Menlo, Consolas, monospace;
      tab-size:2;
    }

    @media (max-width:700px){
      .top{
        flex-direction:column;
        align-items:flex-start;
      }
      .actions{
        width:100%;
      }
      .copy-btn{
        width:100%;
      }
    }
  </style>
</head>
<body>
  <main class="wrap">
    <section class="top">
      <div>
        <h1 class="title">styles.css listo para copiar</h1>
        <div class="status" id="status">Toca el botón para copiar el código</div>
      </div>
      <div class="actions">
        <button class="copy-btn" id="copyBtn">Copiar styles.css</button>
      </div>
    </section>

    <section class="editor">
      <textarea id="code" readonly>:root {
  --bg: #f5f7fb;
  --panel: #ffffff;
  --panel-soft: #eef3ff;
  --text: #0f172a;
  --muted: #64748b;
  --line: #dbe3f0;
  --income: #22c55e;
  --expense: #ef4444;
  --accent: #2563eb;
  --accent-2: #7c3aed;
  --shadow: 0 18px 50px rgba(15, 23, 42, 0.08);
  --radius: 22px;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: 'Manrope', sans-serif;
  color: var(--text);
  background:
    radial-gradient(circle at top left, rgba(37, 99, 235, 0.08), transparent 28%),
    radial-gradient(circle at bottom right, rgba(124, 58, 237, 0.08), transparent 24%),
    var(--bg);
}

a {
  color: inherit;
  text-decoration: none;
}

.wrap {
  width: min(1120px, calc(100% - 32px));
  margin: 0 auto;
}

.topbar {
  position: sticky;
  top: 0;
  z-index: 50;
  backdrop-filter: blur(12px);
  background: rgba(245, 247, 251, 0.75);
  border-bottom: 1px solid rgba(219, 227, 240, 0.7);
}

.topbar-inner {
  min-height: 78px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 18px;
}

.brand {
  display: flex;
  align-items: center;
  gap: 12px;
}

.brand-mark {
  width: 16px;
  height: 16px;
  border-radius: 5px;
  background: linear-gradient(135deg, var(--accent), var(--accent-2));
  box-shadow: 0 0 0 6px rgba(37, 99, 235, 0.08);
}

.brand-text strong {
  display: block;
  font-family: 'Space Grotesk', sans-serif;
  font-size: 1rem;
  letter-spacing: -0.03em;
}

.brand-text span {
  display: block;
  color: var(--muted);
  font-size: 0.88rem;
}

.nav {
  display: flex;
  gap: 18px;
  flex-wrap: wrap;
}

.nav a {
  color: var(--muted);
  font-weight: 700;
  font-size: 0.95rem;
  transition: 0.2s ease;
}

.nav a:hover {
  color: var(--text);
}

.hero {
  padding: 48px 0 26px;
}

.hero-grid {
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  gap: 24px;
  align-items: stretch;
}

.hero-copy,
.hero-side,
.panel,
.form-panel,
.list-panel,
.tasks-panel {
  background: rgba(255, 255, 255, 0.76);
  border: 1px solid rgba(219, 227, 240, 0.9);
  border-radius: var(--radius);
  box-shadow: var(--shadow);
}

.hero-copy {
  padding: clamp(24px, 4vw, 42px);
}

.eyebrow {
  display: inline-flex;
  padding: 8px 12px;
  border-radius: 999px;
  background: var(--panel-soft);
  color: var(--accent);
  font-size: 0.85rem;
  font-weight: 800;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  margin-bottom: 16px;
}

.hero h1 {
  margin: 0;
  font-family: 'Space Grotesk', sans-serif;
  font-size: clamp(2.2rem, 6vw, 4.8rem);
  line-height: 0.95;
  letter-spacing: -0.06em;
}

.hero p {
  margin: 18px 0 0;
  max-width: 60ch;
  color: var(--muted);
  font-size: 1.02rem;
}

.hero-side {
  padding: 24px;
  display: grid;
  align-content: space-between;
  gap: 18px;
  background:
    linear-gradient(160deg, rgba(37, 99, 235, 0.08), rgba(124, 58, 237, 0.08)),
    rgba(255, 255, 255, 0.85);
}

.mini-kpis {
  display: grid;
  gap: 14px;
}

.kpi {
  padding: 16px;
  border-radius: 18px;
  background: rgba(255, 255, 255, 0.78);
  border: 1px solid rgba(219, 227, 240, 0.95);
}

.kpi-label {
  color: var(--muted);
  font-size: 0.86rem;
  margin-bottom: 8px;
}

.kpi-value {
  font-family: 'Space Grotesk', sans-serif;
  font-size: clamp(1.3rem, 3vw, 2rem);
  letter-spacing: -0.04em;
}

.balance {
  color: var(--accent);
}

.income {
  color: var(--income);
}

.expense {
  color: var(--expense);
}

.savings {
  color: var(--accent-2);
}

main.app {
  padding: 10px 0 56px;
}

.dashboard-grid {
  display: grid;
  grid-template-columns: 0.95fr 1.05fr;
  gap: 24px;
}

.panel-head {
  display: flex;
  align-items: end;
  justify-content: space-between;
  gap: 12px;
  margin-bottom: 18px;
}

.panel-head h2 {
  margin: 0;
  font-family: 'Space Grotesk', sans-serif;
  font-size: 1.3rem;
  letter-spacing: -0.03em;
}

.panel-head p {
  margin: 6px 0 0;
  color: var(--muted);
  font-size: 0.94rem;
}

.form-panel,
.list-panel,
.tasks-panel,
.panel {
  padding: 24px;
}

.form-grid {
  display: grid;
  gap: 14px;
}

.field {
  display: grid;
  gap: 8px;
}

label {
  font-size: 0.92rem;
  font-weight: 700;
}

input,
select,
button {
  font: inherit;
}

input,
select {
  width: 100%;
  border: 1px solid var(--line);
  background: #fff;
  color: var(--text);
  border-radius: 14px;
  padding: 14px 14px;
  outline: none;
  transition: border-color 0.2s ease, box-shadow 0.2s ease, transform 0.2s ease;
}

input:focus,
select:focus {
  border-color: rgba(37, 99, 235, 0.5);
  box-shadow: 0 0 0 4px rgba(37, 99, 235, 0.12);
}

button {
  border: none;
  border-radius: 14px;
  padding: 14px 18px;
  font-weight: 800;
  cursor: pointer;
  transition: 0.2s ease;
}

.primary-btn {
  color: white;
  background: linear-gradient(135deg, var(--accent), var(--accent-2));
  box-shadow: 0 12px 30px rgba(37, 99, 235, 0.18);
}

.primary-btn:hover {
  transform: translateY(-1px);
  filter: brightness(1.03);
}

.primary-btn:active {
  transform: translateY(0);
}

.secondary-btn {
  background: var(--panel-soft);
  color: var(--text);
}

.summary-strip {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 14px;
  margin-bottom: 18px;
}

.summary-box {
  padding: 16px;
  border-radius: 18px;
  background: #fff;
  border: 1px solid var(--line);
}

.summary-box span {
  display: block;
  color: var(--muted);
  font-size: 0.84rem;
  margin-bottom: 8px;
}

.summary-box strong {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 1.25rem;
  letter-spacing: -0.04em;
}

.transactions {
  list-style: none;
  margin: 0;
  padding: 0;
  display: grid;
  gap: 12px;
}

.transaction {
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 8px;
  align-items: center;
  padding: 14px 16px;
  border: 1px solid var(--line);
  border-radius: 18px;
  background: #fff;
}

.transaction small {
  color: var(--muted);
}

.transaction strong {
  font-size: 1rem;
}

.transaction .amount.income {
  color: var(--income);
}

.transaction .amount.expense {
  color: var(--expense);
}

.empty {
  color: var(--muted);
  text-align: center;
  padding: 20px 0;
}

.tasks {
  list-style: none;
  margin: 0;
  padding: 0;
  display: grid;
  gap: 12px;
}

.task {
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 14px 16px;
  border-radius: 18px;
  background: #fff;
  border: 1px solid var(--line);
}

.task input[type="checkbox"] {
  width: 18px;
  height: 18px;
  accent-color: var(--accent);
}

.task.done span {
  text-decoration: line-through;
  color: var(--muted);
}

.chart-panel {
  min-height: 260px;
}

.bars {
  margin-top: 18px;
  display: grid;
  gap: 14px;
}

.bar-group {
  display: grid;
  gap: 8px;
}

.bar-labels {
  display: flex;
  justify-content: space-between;
  color: var(--muted);
  font-size: 0.9rem;
}

.bar-track {
  width: 100%;
  height: 14px;
  border-radius: 999px;
  background: #e9eef9;
  overflow: hidden;
}

.bar-fill {
  height: 100%;
  border-radius: inherit;
  width: 0%;
  transition: width 0.5s ease;
}

.bar-fill.income {
  background: linear-gradient(90deg, #16a34a, #4ade80);
}

.bar-fill.expense {
  background: linear-gradient(90deg, #ef4444, #fb7185);
}

.bar-fill.savings {
  background: linear-gradient(90deg, #2563eb, #7c3aed);
}

footer {
  padding: 18px 0 38px;
  color: var(--muted);
  font-size: 0.9rem;
}

.reveal {
  opacity: 0;
  transform: translateY(18px);
  animation: rise 0.6s ease forwards;
}

.reveal.delay-1 { animation-delay: 0.08s; }
.reveal.delay-2 { animation-delay: 0.16s; }
.reveal.delay-3 { animation-delay: 0.24s; }

@keyframes rise {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@media (max-width: 940px) {
  .hero-grid,
  .dashboard-grid {
    grid-template-columns: 1fr;
  }

  .summary-strip {
    grid-template-columns: repeat(2, 1fr);
  }

  .topbar-inner {
    flex-direction: column;
    align-items: flex-start;
    padding: 14px 0;
  }
}

@media (max-width: 640px) {
  .wrap {
    width: min(100% - 20px, 1120px);
  }

  .hero {
    padding-top: 26px;
  }

  .summary-strip {
    grid-template-columns: 1fr;
  }

  .transaction {
    grid-template-columns: 1fr;
  }

  .nav {
    gap: 12px;
  }

  .form-panel,
  .list-panel,
  .tasks-panel,
  .panel,
  .hero-copy,
  .hero-side {
    padding: 18px;
    border-radius: 18px;
  }
}</textarea>
    </section>
  </main>

  <script>
    const copyBtn = document.getElementById('copyBtn');
    const code = document.getElementById('code');
    const status = document.getElementById('status');

    copyBtn.addEventListener('click', async () => {
      try {
        await navigator.clipboard.writeText(code.value);
        status.textContent = 'Copiado correctamente. Ahora pégalo en tu archivo styles.css';
        copyBtn.textContent = 'Copiado';
        setTimeout(() => {
          copyBtn.textContent = 'Copiar styles.css';
          status.textContent = 'Toca el botón para copiar el código';
        }, 2200);
      } catch (e) {
        code.select();
        document.execCommand('copy');
        status.textContent = 'Copiado correctamente. Ahora pégalo en tu archivo styles.css';
      }
    });
  </script>
</body>
</html>
 
