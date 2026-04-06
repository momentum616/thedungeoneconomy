<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>The Dungeon Economy</title>
  <style>
    :root{--bg:#0c0f14;--bg-elev:#121722;--line:rgba(255,255,255,0.10);--text:#edf2f8;--muted:#aeb8ca;--accent:#8ab4ff;--accent-2:#93f0c8;}
    *{box-sizing:border-box;margin:0;padding:0;}
    body{
      color:var(--text);min-height:100vh;display:flex;align-items:center;justify-content:center;padding:2rem;
      background:radial-gradient(circle at top left,rgba(138,180,255,0.11),transparent 28%),radial-gradient(circle at top right,rgba(147,240,200,0.08),transparent 22%),var(--bg);
      font-family:Inter,ui-sans-serif,system-ui,-apple-system,sans-serif;
    }
    .card{
      background:linear-gradient(180deg,color-mix(in srgb,var(--bg-elev) 94%,transparent),var(--bg-elev));
      border:1px solid var(--line);border-radius:18px;padding:2.5rem;max-width:480px;text-align:center;
    }
    .dot{
      width:14px;height:14px;border-radius:999px;margin:0 auto 1.5rem;
      background:linear-gradient(135deg,var(--accent),var(--accent-2));
      box-shadow:0 0 0 6px rgba(138,180,255,0.12);
      animation:pulse 2s ease-in-out infinite;
    }
    @keyframes pulse{0%,100%{box-shadow:0 0 0 6px rgba(138,180,255,0.12)}50%{box-shadow:0 0 0 10px rgba(138,180,255,0.06)}}
    h1{font-size:1.75rem;font-weight:700;letter-spacing:-0.03em;margin-bottom:0.75rem;}
    p{font-size:0.95rem;color:var(--muted);line-height:1.6;}
    .chip{display:inline-flex;align-items:center;padding:6px 12px;border-radius:999px;border:1px solid var(--line);color:var(--muted);font-size:0.8rem;margin-top:1.5rem;}
  </style>
</head>
<body>
  <div class="card">
    <div class="dot"></div>
    <h1>The Dungeon Economy</h1>
    <p>A weekly brief on D&amp;D, publishing, platforms, and market signals. First issue coming soon.</p>
    <span class="chip">Where D&amp;D meets product, platform, and demand.</span>
  </div>
</body>
</html>
