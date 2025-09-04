# teachers-day-wishes
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Happy Teachers' Day — Shilpa Ma’am</title>
  <meta name="description" content="A heartfelt Teachers' Day message for Shilpa Ma’am, Biology Teacher." />
  <style>
    :root {
      --bg1: #f2fff6;      /* soft mint */
      --bg2: #e7f7ff;      /* pale sky */
      --ink: #0f172a;      /* slate-900 */
      --muted: #475569;    /* slate-600 */
      --brand: #0ea5a4;    /* teal */
      --accent: #22c55e;   /* green */
      --card: #ffffff;     /* white */
      --ring: rgba(34, 197, 94, 0.2);
      --shadow: 0 10px 30px rgba(2, 40, 31, 0.08);
    }

    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
      color: var(--ink);
      background: radial-gradient(1300px 700px at 10% 10%, var(--bg2), transparent 60%),
                  radial-gradient(1300px 700px at 90% 90%, var(--bg1), transparent 60%),
                  linear-gradient(180deg, #ffffff, #f7fffb 40%, #ffffff);
      display: grid;
      place-items: center;
      padding: 24px;
    }

    .container {
      width: min(900px, 100%);
      position: relative;
    }

    .card {
      background: var(--card);
      border-radius: 24px;
      box-shadow: var(--shadow);
      overflow: hidden;
      position: relative;
      isolation: isolate;
      border: 1px solid rgba(15, 23, 42, 0.05);
    }

    /* Subtle biology/DNA background */
    .card::before, .card::after {
      content: "";
      position: absolute;
      inset: 0;
      background-image:
        radial-gradient(circle at 15% 20%, rgba(14,165,164,0.07) 0 120px, transparent 120px),
        radial-gradient(circle at 85% 80%, rgba(34,197,94,0.08) 0 150px, transparent 150px);
      z-index: 0;
    }
    .card::after {
      mask: linear-gradient(180deg, rgba(0,0,0,0.12), transparent 50%);
      opacity: .8;
    }

    header {
      position: relative;
      z-index: 1;
      padding: clamp(20px, 5vw, 36px) clamp(20px, 6vw, 48px) 0;
      display: flex;
      align-items: center;
      gap: 18px;
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      background: #f0fdf4;
      color: #065f46;
      border: 1px solid #bbf7d0;
      padding: 10px 14px;
      border-radius: 999px;
      font-weight: 600;
      letter-spacing: .2px;
      box-shadow: 0 4px 14px rgba(34,197,94,.15);
    }

    h1 {
      font-size: clamp(28px, 4.2vw, 44px);
      line-height: 1.15;
      margin: 14px 0 8px;
      letter-spacing: .2px;
    }

    .sub {
      margin: 0 0 28px;
      color: var(--muted);
      font-size: clamp(14px, 2vw, 18px);
    }

    .content {
      position: relative;
      z-index: 1;
      padding: 0 clamp(20px, 6vw, 48px) clamp(24px, 5vw, 42px);
    }

    .quote {
      background: linear-gradient(180deg, #ffffff, #f8fff9);
      border: 1px solid rgba(34,197,94,0.18);
      border-radius: 20px;
      padding: clamp(16px, 3.6vw, 28px);
      box-shadow: 0 8px 24px rgba(16, 185, 129, 0.08);
      font-size: clamp(16px, 2.4vw, 20px);
      line-height: 1.7;
    }

    .signature {
      margin-top: 22px;
      color: var(--muted);
      font-weight: 600;
    }

    /* Decorative DNA helix (SVG) */
    .dna {
      position: absolute;
      right: -20px;
      bottom: -30px;
      width: clamp(160px, 28vw, 260px);
      opacity: 0.12;
      pointer-events: none;
    }

    footer {
      padding: 0 clamp(20px, 6vw, 48px) clamp(18px, 5vw, 32px);
      color: var(--muted);
      font-size: 14px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 12px;
    }

    .chips { display: flex; flex-wrap: wrap; gap: 8px; }
    .chip {
      padding: 6px 10px;
      border-radius: 999px;
      background: #f0f9ff;
      border: 1px solid #bae6fd;
      font-size: 12px;
      font-weight: 700;
      color: #075985;
    }

    /* Print styles */
    @media print {
      body { background: white; }
      footer { display: none !important; }
      .card { box-shadow: none; border: 1px solid #ddd; }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <header>
        <span class="badge" aria-label="Teachers' Day">
          <!-- leaf icon -->
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" aria-hidden="true">
            <path d="M4 20c8 0 12-6 12-12 2 0 4 .5 6 2-1 8-8 12-18 10Z" stroke="#059669" stroke-width="2" fill="#a7f3d0"/>
          </svg>
          Happy Teachers' Day
        </span>
      </header>

      <div class="content">
        <h1>With gratitude to <span style="color:var(--brand)">Shilpa Ma’am</span></h1>
        <p class="sub">Our beloved Biology Teacher</p>

        <div class="quote">
          <p>
            Your passion turns cells, genes, and ecosystems into living stories. Thank you for nurturing our curiosity, guiding us with patience, and showing us that learning is a journey of discovery.
          </p>
          <p>
            Wishing you good health, happiness, and endless joy as you inspire young minds—today and always.
          </p>
          <p class="signature">— With respect and warm wishes from your students</p>
        </div>
      </div>

      <!-- Decorative DNA -->
      <svg class="dna" viewBox="0 0 200 400" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <defs>
          <linearGradient id="g" x1="0" x2="1">
            <stop offset="0%" stop-color="#22c55e"/>
            <stop offset="100%" stop-color="#0ea5a4"/>
          </linearGradient>
        </defs>
        <!-- Two helices -->
        <path d="M40,0 C110,50 90,150 160,200 C110,250 90,350 40,400" fill="none" stroke="url(#g)" stroke-width="6"/>
        <path d="M160,0 C90,50 110,150 40,200 C90,250 110,350 160,400" fill="none" stroke="url(#g)" stroke-width="6" opacity="0.7"/>
        <!-- Rungs -->
        <g opacity="0.5">
          <line x1="60" y1="20" x2="140" y2="10" stroke="#10b981" stroke-width="4"/>
          <line x1="75" y1="60" x2="125" y2="50" stroke="#14b8a6" stroke-width="4"/>
          <line x1="90" y1="100" x2="110" y2="90" stroke="#10b981" stroke-width="4"/>
          <line x1="100" y1="140" x2="100" y2="130" stroke="#14b8a6" stroke-width="4"/>
          <line x1="90" y1="180" x2="110" y2="170" stroke="#10b981" stroke-width="4"/>
          <line x1="75" y1="220" x2="125" y2="210" stroke="#14b8a6" stroke-width="4"/>
          <line x1="60" y1="260" x2="140" y2="250" stroke="#10b981" stroke-width="4"/>
          <line x1="75" y1="300" x2="125" y2="290" stroke="#14b8a6" stroke-width="4"/>
          <line x1="90" y1="340" x2="110" y2="330" stroke="#10b981" stroke-width="4"/>
        </g>
      </svg>

      <footer>
        <div class="chips" aria-label="tags">
          <span class="chip">Biology</span>
          <span class="chip">Gratitude</span>
          <span class="chip">Inspiration</span>
        </div>
        <small>Designed by your student • 5 September</small>
      </footer>
    </div>
  </div>
</body>
</html>
