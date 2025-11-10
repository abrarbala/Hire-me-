:root{
  --bg: #0e1726;
  --panel: #121c2f;
  --ink: #eef2f6;
  --muted: #b7c2d0;
  --line: #23314f;
  --btn: #16233b;
  --accent: #00d9a6;
  --accent-ink: #00281f;
}

*{ box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  color: var(--ink);
  background: linear-gradient(135deg,#0e1726 0%,#172338 100%);
  font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
  line-height: 1.45;
}

.wrap {
  max-width: 1100px;
  margin: 0 auto;
  padding: 40px 24px 64px;
}

.site-header {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 16px;
  justify-content: space-between;
  margin-bottom: 12px;
}

.title {
  margin: 0 0 4px;
  font-size: clamp(24px, 3vw, 36px);
  font-weight: 800;
  letter-spacing: .3px;
}

.subtitle {
  margin: 0;
  color: var(--muted);
}

.section-title {
  margin: 28px 0 12px;
  font-size: clamp(20px, 2.2vw, 26px);
}

.cta {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
}

.btn {
  display: inline-block;
  text-decoration: none;
  color: var(--ink);
  background: var(--btn);
  border: 1px solid #2a3957;
  padding: 10px 16px;
  border-radius: 10px;
  font-weight: 600;
  transition: transform .08s ease, background .2s ease, border-color .2s ease;
  cursor: pointer;
}

.btn:hover { transform: translateY(-1px); }
.btn:active { transform: translateY(0); }

.btn.accent {
  background: var(--accent);
  color: var(--accent-ink);
  border: none;
}

.btn.secondary {
  background: #0f1a2e;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px,1fr));
  gap: 18px;
  margin-top: 18px;
}

.card {
  background: var(--panel);
  border: 1px solid var(--line);
  border-radius: 16px;
  padding: 18px;
}

.name {
  margin: 0 0 4px;
  font-size: 18px;
  font-weight: 700;
}

.role {
  margin: 0 0 8px;
  color: var(--muted);
  font-size: 14px;
}

.tags { margin: 0 0 10px; }
.pill {
  display: inline-block;
  margin: 2px 6px 0 0;
  padding: 4px 10px;
  border-radius: 20px;
  border: 1px solid #2a3957;
  color: var(--muted);
  font-size: 12px;
}

.links { display: flex; flex-wrap: wrap; gap: 8px; margin: 0; }

.qrbox {
  display: flex;
  flex-wrap: wrap;
  gap: 24px;
  align-items: center;
  background: rgba(18,28,47,.6);
  border: 1px solid var(--line);
  border-radius: 16px;
  padding: 20px;
}

#qrcode {
  width: 180px; height: 180px;
  background: #fff; padding: 6px; border-radius: 8px;
}

code {
  background: #0b1424; color: #d6e3ff; padding: 2px 6px; border-radius: 6px;
}

.howto-list {
  margin: 8px 0 0 18px;
}

.site-footer {
  margin-top: 48px;
  color: var(--muted);
  font-size: 13px;
  text-wrap: balance;
}

/* Print-friendly tweak (e.g., for poster QR) */
@media print {
  .wrap { padding: 0; }
  .cta, .howto-list { display: none; }
  body { background: #fff; color: #111; }
  #qrcode { width: 220px; height: 220px; }
}