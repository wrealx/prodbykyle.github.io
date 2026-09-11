<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>ProdByKyle — Producer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800;900&family=Space+Grotesk:wght@400;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#0a0a0f;
    --bg-2:#12121a;
    --accent:#a855f7;
    --accent-2:#22d3ee;
    --text:#f5f5f7;
    --muted:#9ca3af;
    --card:rgba(255,255,255,0.04);
    --border:rgba(255,255,255,0.08);
  }

  *{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent;}

  html{scroll-behavior:smooth;}

  body{
    font-family:'Inter',sans-serif;
    background:var(--bg);
    color:var(--text);
    overflow-x:hidden;
    min-height:100vh;
    position:relative;
  }

  /* Ambient background glow */
  body::before{
    content:'';
    position:fixed;
    inset:0;
    background:
      radial-gradient(circle at 15% 20%, rgba(168,85,247,0.18), transparent 45%),
      radial-gradient(circle at 85% 75%, rgba(34,211,238,0.14), transparent 45%),
      radial-gradient(circle at 50% 50%, rgba(168,85,247,0.05), transparent 60%);
    z-index:-2;
    pointer-events:none;
  }

  body::after{
    content:'';
    position:fixed;
    inset:0;
    background-image:
      linear-gradient(rgba(255,255,255,0.02) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,0.02) 1px, transparent 1px);
    background-size:60px 60px;
    z-index:-1;
    pointer-events:none;
    mask-image:radial-gradient(circle at 50% 40%, black, transparent 80%);
    -webkit-mask-image:radial-gradient(circle at 50% 40%, black, transparent 80%);
  }

  /* ============ FLOATING SOCIAL DOCK ============ */
  .social-dock{
    position:fixed;
    z-index:999;
    bottom:0;
    left:0;
    right:0;
    display:flex;
    justify-content:center;
    align-items:center;
    gap:14px;
    padding:16px 18px calc(16px + env(safe-area-inset-bottom));
    background:linear-gradient(to top, rgba(10,10,15,0.95), rgba(10,10,15,0.6) 60%, transparent);
    backdrop-filter:blur(14px);
    -webkit-backdrop-filter:blur(14px);
    border-top:1px solid var(--border);
    flex-wrap:wrap;
  }

  .social-dock a{
    width:46px;
    height:46px;
    display:flex;
    align-items:center;
    justify-content:center;
    border-radius:14px;
    background:var(--card);
    border:1px solid var(--border);
    transition:all .3s cubic-bezier(.4,0,.2,1);
    position:relative;
    overflow:hidden;
  }

  .social-dock a svg{
    width:22px;
    height:22px;
    fill:#fff;
    transition:transform .3s ease;
  }

  .social-dock a::before{
    content:'';
    position:absolute;
    inset:0;
    background:linear-gradient(135deg, var(--accent), var(--accent-2));
    opacity:0;
    transition:opacity .3s ease;
    z-index:-1;
  }

  .social-dock a:hover{
    transform:translateY(-6px) scale(1.08);
    border-color:transparent;
    box-shadow:0 10px 30px rgba(168,85,247,0.4);
  }

  .social-dock a:hover::before{opacity:1;}
  .social-dock a:hover svg{transform:scale(1.15);}

  /* Desktop: floating on sides too */
  @media(min-width:900px){
    .social-dock{
      top:50%;
      bottom:auto;
      left:auto;
      right:24px;
      transform:translateY(-50%);
      flex-direction:column;
      width:auto;
      padding:18px 14px;
      border-radius:22px;
      border:1px solid var(--border);
      background:rgba(18,18,26,0.7);
    }
    .social-dock a{width:52px;height:52px;}
    .social-dock a svg{width:24px;height:24px;}
  }

  /* ============ HERO ============ */
  .hero{
    min-height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:40px 22px 140px;
    position:relative;
  }

  .badge{
    display:inline-flex;
    align-items:center;
    gap:8px;
    padding:8px 16px;
    border-radius:100px;
    background:var(--card);
    border:1px solid var(--border);
    font-size:13px;
    color:var(--muted);
    letter-spacing:0.5px;
    margin-bottom:28px;
    animation:fadeUp .8s ease both;
  }

  .badge span.dot{
    width:8px;height:8px;
    border-radius:50%;
    background:#22c55e;
    box-shadow:0 0 10px #22c55e;
    animation:pulse 2s infinite;
  }

  @keyframes pulse{
    0%,100%{opacity:1;}
    50%{opacity:0.4;}
  }

  .hero h1{
    font-family:'Space Grotesk',sans-serif;
    font-size:clamp(3rem,12vw,7rem);
    font-weight:700;
    line-height:0.95;
    letter-spacing:-0.04em;
    background:linear-gradient(135deg,#fff 0%, #a855f7 50%, #22d3ee 100%);
    -webkit-background-clip:text;
    background-clip:text;
    -webkit-text-fill-color:transparent;
    animation:fadeUp .9s ease .1s both;
    margin-bottom:20px;
  }

  .hero p.tagline{
    font-size:clamp(1rem,2.5vw,1.25rem);
    color:var(--muted);
    max-width:520px;
    line-height:1.6;
    animation:fadeUp 1s ease .2s both;
    margin-bottom:40px;
  }

  .cta-row{
    display:flex;
    gap:14px;
    flex-wrap:wrap;
    justify-content:center;
    animation:fadeUp 1.1s ease .3s both;
  }

  .btn{
    display:inline-flex;
    align-items:center;
    gap:10px;
    padding:16px 30px;
    border-radius:100px;
    font-weight:600;
    font-size:15px;
    text-decoration:none;
    transition:all .3s ease;
    border:none;
    cursor:pointer;
    font-family:'Inter',sans-serif;
  }

  .btn-primary{
    background:linear-gradient(135deg,var(--accent),var(--accent-2));
    color:#fff;
    box-shadow:0 10px 40px rgba(168,85,247,0.35);
  }

  .btn-primary:hover{
    transform:translateY(-3px);
    box-shadow:0 16px 50px rgba(168,85,247,0.55);
  }

  .btn-ghost{
    background:var(--card);
    color:var(--text);
    border:1px solid var(--border);
  }

  .btn-ghost:hover{
    background:rgba(255,255,255,0.08);
    transform:translateY(-3px);
  }

  @keyframes fadeUp{
    from{opacity:0;transform:translateY(24px);}
    to{opacity:1;transform:translateY(0);}
  }

  /* ============ SECTION ============ */
  section.content{
    padding:80px 22px 140px;
    max-width:1100px;
    margin:0 auto;
  }

  .section-title{
    font-family:'Space Grotesk',sans-serif;
    font-size:clamp(1.8rem,5vw,2.6rem);
    font-weight:700;
    letter-spacing:-0.02em;
    margin-bottom:12px;
    text-align:center;
  }

  .section-sub{
    color:var(--muted);
    text-align:center;
    margin-bottom:50px;
    font-size:15px;
    max-width:480px;
    margin-left:auto;
    margin-right:auto;
    line-height:1.6;
  }

  .grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:18px;
  }

  .card{
    background:var(--card);
    border:1px solid var(--border);
    border-radius:22px;
    padding:30px 26px;
    text-decoration:none;
    color:var(--text);
    transition:all .35s cubic-bezier(.4,0,.2,1);
    position:relative;
    overflow:hidden;
    display:flex;
    flex-direction:column;
    gap:14px;
  }

  .card::after{
    content:'';
    position:absolute;
    top:0;left:0;right:0;
    height:2px;
    background:linear-gradient(90deg,var(--accent),var(--accent-2));
    transform:scaleX(0);
    transform-origin:left;
    transition:transform .4s ease;
  }

  .card:hover{
    transform:translateY(-6px);
    border-color:rgba(168,85,247,0.4);
    background:rgba(255,255,255,0.06);
    box-shadow:0 20px 50px rgba(0,0,0,0.4);
  }

  .card:hover::after{transform:scaleX(1);}

  .card-icon{
    width:52px;height:52px;
    border-radius:14px;
    display:flex;
    align-items:center;
    justify-content:center;
    background:linear-gradient(135deg, rgba(168,85,247,0.2), rgba(34,211,238,0.15));
    border:1px solid var(--border);
  }

  .card-icon svg{width:26px;height:26px;fill:#fff;}

  .card h3{
    font-family:'Space Grotesk',sans-serif;
    font-size:1.15rem;
    font-weight:600;
    letter-spacing:-0.01em;
  }

  .card p{
    color:var(--muted);
    font-size:14px;
    line-height:1.5;
  }

  .card .arrow{
    margin-top:auto;
    color:var(--accent);
    font-size:14px;
    font-weight:600;
    display:flex;
    align-items:center;
    gap:6px;
  }

  /* ============ FOOTER ============ */
  footer{
    text-align:center;
    padding:40px 22px 140px;
    color:var(--muted);
    font-size:13px;
    border-top:1px solid var(--border);
  }

  footer strong{
    color:var(--text);
    font-weight:600;
  }

  /* Mobile view: socials full width, evenly spaced */
  @media(max-width:600px){
    .social-dock{
      gap:10px;
      padding:14px 12px calc(14px + env(safe-area-inset-bottom));
    }
    .social-dock a{
      width:calc((100% - 50px)/6);
      min-width:44px;
      max-width:56px;
      height:44px;
      border-radius:12px;
    }
    .social-dock a svg{width:20px;height:20px;}
    .hero{padding-bottom:120px;}
    footer{padding-bottom:120px;}
  }

  /* Reduce motion */
  @media (prefers-reduced-motion: reduce){
    *{animation:none!important;transition:none!important;}
  }
</style>
</head>
<body>

<!-- ============ FLOATING SOCIAL DOCK ============ -->
<nav class="social-dock" aria-label="Social links">
  <!-- Airbit -->
  <a href="https://airbit.com/prodbykyle" target="_blank" rel="noopener" title="Airbit" aria-label="Airbit">
    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2Zm0 18a8 8 0 1 1 8-8 8 8 0 0 1-8 8Zm-1-5.5v-5l4 2.5Z"/></svg>
  </a>
  <!-- YouTube -->
  <a href="https://youtube.com/@cursedclips999" target="_blank" rel="noopener" title="YouTube" aria-label="YouTube">
    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M23.5 6.2a3 3 0 0 0-2.1-2.1C19.5 3.5 12 3.5 12 3.5s-7.5 0-9.4.6A3 3 0 0 0 .5 6.2 31 31 0 0 0 0 12a31 31 0 0 0 .5 5.8 3 3 0 0 0 2.1 2.1c1.9.6 9.4.6 9.4.6s7.5 0 9.4-.6a3 3 0 0 0 2.1-2.1A31 31 0 0 0 24 12a31 31 0 0 0-.5-5.8ZM9.6 15.6V8.4l6.2 3.6Z"/></svg>
  </a>
  <!-- TikTok -->
  <a href="https://tiktok.com/@prod.by.kyle" target="_blank" rel="noopener" title="TikTok" aria-label="TikTok">
    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M19.6 6.7a5.5 5.5 0 0 1-3.3-1.1 5.5 5.5 0 0 1-2-3.1H10.9v12.8a2.9 2.9 0 1 1-2.4-2.85V8.9a6.4 6.4 0 1 0 5.9 6.4V9.9a8.6 8.6 0 0 0 5 1.6V8.05a5.4 5.4 0 0 1 0-1.35Z"/></svg>
  </a>
  <!-- Instagram -->
  <a href="https://instagram.com/cursedfan87" target="_blank" rel="noopener" title="Instagram" aria-label="Instagram">
    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2.2c3.2 0 3.6 0 4.85.07a6.6 6.6 0 0 1 2.23.41 3.9 3.9 0 0 1 2.24 2.24 6.6 6.6 0 0 1 .41 2.23C21.8 8.4 21.8 8.8 21.8 12s0 3.6-.07 4.85a6.6 6.6 0 0 1-.41 2.23 3.9 3.9 0 0 1-2.24 2.24 6.6 6.6 0 0 1-2.23.41C15.6 21.8 15.2 21.8 12 21.8s-3.6 0-4.85-.07a6.6 6.6 0 0 1-2.23-.41 3.9 3.9 0 0 1-2.24-2.24 6.6 6.6 0 0 1-.41-2.23C2.2 15.6 2.2 15.2 2.2 12s0-3.6.07-4.85a6.6 6.6 0 0 1 .41-2.23A3.9 3.9 0 0 1 4.92 2.68a6.6 6.6 0 0 1 2.23-.41C8.4 2.2 8.8 2.2 12 2.2Zm0 1.8c-3.15 0-3.5 0-4.73.07a4.8 4.8 0 0 0-1.7.31 2.1 2.1 0 0 0-1.19 1.19 4.8 4.8 0 0 0-.31 1.7C4 8.5 4 8.85 4 12s0 3.5.07 4.73a4.8 4.8 0 0 0 .31 1.7 2.1 2.1 0 0 0 1.19 1.19 4.8 4.8 0 0 0 1.7.31C8.5 20 8.85 20 12 20s3.5 0 4.73-.07a4.8 4.8 0 0 0 1.7-.31 2.1 2.1 0 0 0 1.19-1.19 4.8 4.8 0 0 0 .31-1.7C20 15.5 20 15.15 20 12s0-3.5-.07-4.73a4.8 4.8 0 0 0-.31-1.7 2.1 2.1 0 0 0-1.19-1.19 4.8 4.8 0 0 0-1.7-.31C15.5 4 15.15 4 12 4Zm0 3.1a4.9 4.9 0 1 1 0 9.8 4.9 4.9 0 0 1 0-9.8Zm0 1.8a3.1 3.1 0 1 0 0 6.2 3.1 3.1 0 0 0 0-6.2Zm5.1-2a1.15 1.15 0 1 1 0 2.3 1.15 1.15 0 0 1 0-2.3Z"/></svg>
  </a>
  <!-- SoundCloud -->
  <a href="https://soundcloud.com/wrealx/sets/cursed-on-a-daily" target="_blank" rel="noopener" title="SoundCloud" aria-label="SoundCloud">
    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M1.2 12.6c-.06 0-.1.03-.1.08l-.12 1.7.12 1.7c0 .05.04.08.1.08s.1-.03.1-.08l.14-1.7-.14-1.7c0-.05-.04-.08-.1-.08Zm1.02-1.1c-.07 0-.12.04-.13.1l-.16 2.8.16 2.74c0 .06.06.1.13.1s.12-.04.13-.1l.18-2.75-.18-2.8c0-.05-.06-.1-.13-.1Zm1.06-.55c-.08 0-.14.05-.15.12l-.15 3.34.15 3.24c0 .07.07.12.15.12s.14-.05.15-.12l.17-3.24-.17-3.34c0-.07-.07-.12-.15-.12Zm1.09-.4c-.09 0-.16.06-.17.14l-.14 3.74.14 3.62c0 .08.08.14.17.14s.16-.06.17-.14l.16-3.62-.16-3.74c-.01-.08-.08-.14-.17-.14Zm1.14-.25c-.1 0-.18.07-.19.16l-.13 4-.13 3.94c0 .09.09.16.19.16s.18-.07.19-.16l.15-3.94-.15-4c-.01-.09-.09-.16-.19-.16Zm1.16-.07c-.11 0-.2.08-.2.18l-.12 4.06.12 3.98c0 .1.09.18.2.18s.2-.08.2-.18l.14-3.98-.14-4.06c0-.1-.09-.18-.2-.18Zm1.19-.02c-.12 0-.21.09-.22.2l-.11 4.08.11 3.98c0 .11.1.2.22.2s.21-.09.22-.2l.12-3.98-.12-4.08c-.01-.11-.1-.2-.22-.2Zm1.2.07c-.13 0-.23.1-.23.22l-.1 4 .1 3.96c0 .12.1.22.23.22s.23-.1.23-.22l.12-3.96-.12-4c0-.12-.1-.22-.23-.22Zm1.24.1c-.14 0-.25.11-.26.24l-.1 3.9.1 3.92c0 .13.12.24.26.24s.25-.11.26-.24l.11-3.92-.11-3.9c-.01-.13-.12-.24-.26-.24Zm1.28.2c-.15 0-.27.12-.27.26l-.09 3.72.09 3.86c0 .14.12.26.27.26s.27-.12.27-.26l.1-3.86-.1-3.72c0-.14-.12-.26-.27-.26Zm1.32.35c-.16 0-.29.13-.29.28l-.08 3.4.08 3.8c0 .15.13.28.29.28s.29-.13.29-.28l.09-3.8-.09-3.4c0-.15-.13-.28-.29-.28Zm1.38.55c-.17 0-.31.14-.31.3l-.07 2.85.07 3.74c0 .16.14.3.31.3s.31-.14.31-.3l.08-3.74-.08-2.85c0-.16-.14-.3-.31-.3Zm1.45.9c-.18 0-.33.15-.33.32l-.06 1.95.06 3.68c0 .17.15.32.33.32s.33-.15.33-.32l.07-3.68-.07-1.95c0-.17-.15-.32-.33-.32Zm1.55.6c-.19 0-.35.16-.35.35v5c0 .19.16.35.35.35s.35-.16.35-.35v-5c0-.19-.16-.35-.35-.35Zm1.65-.6c-.2 0-.37.17-.37.37v5.6c0 .2.17.37.37.37s.37-.17.37-.37v-5.6c0-.2-.17-.37-.37-.37Zm1.75.4c-.21 0-.39.18-.39.39v4.8c0 .21.18.39.39.39s.39-.18.39-.39v-4.8c0-.21-.18-.39-.39-.39Zm1.9-2.2a3.4 3.4 0 0 0-2.4 1 3.6 3.6 0 0 0-1.05 2.55v.2a3.4 3.4 0 0 0-.8-.1 3.3 3.3 0 0 0-1.2.22 5 5 0 0 0-5-4.4 4.9 4.9 0 0 0-3.7 1.7.5.5 0 0 0-.2.4v6.7a.5.5 0 0 0 .5.5h13.85a3.9 3.9 0 0 0 3.9-3.9 3.9 3.9 0 0 0-3.9-3.85Z"/></svg>
  </a>
  <!-- Spotify -->
  <a href="https://open.spotify.com/playlist/77MWMnYu9oPIVptXMbq1Zc" target="_blank" rel="noopener" title="Spotify" aria-label="Spotify">
    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2Zm4.6 14.4a.6.6 0 0 1-.83.2 11 11 0 0 0-6.9-.85.6.6 0 1 1-.33-1.16 12.3 12.3 0 0 1 7.68 1 .6.6 0 0 1 .18.81Zm1.23-2.74a.75.75 0 0 1-1.03.25 13.8 13.8 0 0 0-8.47-1.5.75.75 0 0 1-.32-1.47 15.3 15.3 0 0 1 9.4 1.7.75.75 0 0 1 .22 1.02Zm.11-2.86A16.6 16.6 0 0 0 7.7 9.1a.9.9 0 1 1-.52-1.72 18.4 18.4 0 0 1 11.3 2.03.9.9 0 1 1-.92 1.55Z"/></svg>
  </a>
  <!-- Facebook -->
  <a href="https://www.facebook.com/chol.hassen" target="_blank" rel="noopener" title="Facebook" aria-label="Facebook">
    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M22 12a10 10 0 1 0-11.6 9.9v-7H7.9V12h2.5V9.8c0-2.5 1.5-3.9 3.8-3.9 1.1 0 2.2.2 2.2.2v2.4h-1.2c-1.2 0-1.6.75-1.6 1.5V12h2.7l-.4 2.9h-2.3v7A10 10 0 0 0 22 12Z"/></svg>
  </a>
</nav>

<!-- ============ HERO ============ -->
<header class="hero">
  <div class="badge"><span class="dot"></span> Available for placements</div>
  <h1>ProdByKyle</h1>
  <p class="tagline">Producer &amp; beatmaker. Crafting soundscapes that hit different. Listen, license, create.</p>
  <div class="cta-row">
    <a href="https://airbit.com/prodbykyle" class="btn btn-primary" target="_blank" rel="noopener">
      🎧 Listen on Airbit
    </a>
    <a href="#connect" class="btn btn-ghost">
      All platforms →
    </a>
  </div>
</header>

<!-- ============ CONNECT ============ -->
<section class="content" id="connect">
  <h2 class="section-title">Connect &amp; Listen</h2>
  <p class="section-sub">Everywhere you can find ProdByKyle. Tap a card to open.</p>

  <div class="grid">
    <!-- Airbit -->
    <a class="card" href="https://airbit.com/prodbykyle" target="_blank" rel="noopener">
      <div class="card-icon">
        <svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2Zm0 18a8 8 0 1 1 8-8 8 8 0 0 1-8 8Zm-1-5.5v-5l4 2.5Z"/></svg>
      </div>
      <h3>Airbit Store</h3>
      <p>Buy licenses — Basic, Premium, Unlimited &amp; Exclusive. Main beat store.</p>
      <span class="arrow">Open store →</span>
    </a>

    <!-- SoundCloud -->
    <a class="card" href="https://soundcloud.com/wrealx/sets/cursed-on-a-daily" target="_blank" rel="noopener">
      <div class="card-icon">
        <svg viewBox="0 0 24 24"><path d="M1.2 12.6c-.06 0-.1.03-.1.08l-.12 1.7.12 1.7c0 .05.04.08.1.08s.1-.03.1-.08l.14-1.7-.14-1.7c0-.05-.04-.08-.1-.08Zm1.02-1.1c-.07 0-.12.04-.13.1l-.16 2.8.16 2.74c0 .06.06.1.13.1s.12-.04.13-.1l.18-2.75-.18-2.8c0-.05-.06-.1-.13-.1Zm1.06-.55c-.08 0-.14.05-.15.12l-.15 3.34.15 3.24c0 .07.07.12.15.12s.14-.05.15-.12l.17-3.24-.17-3.34c0-.07-.07-.12-.15-.12Zm1.09-.4c-.09 0-.16.06-.17.14l-.14 3.74.14 3.62c0 .08.08.14.17.14s.16-.06.17-.14l.16-3.62-.16-3.74c-.01-.08-.08-.14-.17-.14Zm1.14-.25c-.1 0-.18.07-.19.16l-.13 4-.13 3.94c0 .09.09.16.19.16s.18-.07.19-.16l.15-3.94-.15-4c-.01-.09-.09-.16-.19-.16Zm1.16-.07c-.11 0-.2.08-.2.18l-.12 4.06.12 3.98c0 .1.09.18.2.18s.2-.08.2-.18l.14-3.98-.14-4.06c0-.1-.09-.18-.2-.18Zm1.19-.02c-.12 0-.21.09-.22.2l-.11 4.08.11 3.98c0 .11.1.2.22.2s.21-.09.22-.2l.12-3.98-.12-4.08c-.01-.11-.1-.2-.22-.2Zm1.2.07c-.13 0-.23.1-.23.22l-.1 4 .1 3.96c0 .12.1.22.23.22s.23-.1.23-.22l.12-3.96-.12-4c0-.12-.1-.22-.23-.22Zm1.24.1c-.14 0-.25.11-.26.24l-.1 3.9.1 3.92c0 .13.12.24.26.24s.25-.11.26-.24l.11-3.92-.11-3.9c-.01-.13-.12-.24-.26-.24Zm1.28.2c-.15 0-.27.12-.27.26l-.09 3.72.09 3.86c0 .14.12.26.27.26s.27-.12.27-.26l.1-3.86-.1-3.72c0-.14-.12-.26-.27-.26Zm1.32.35c-.16 0-.29.13-.29.28l-.08 3.4.08 3.8c0 .15.13.28.29.28s.29-.13.29-.28l.09-3.8-.09-3.4c0-.15-.13-.28-.29-.28Zm1.38.55c-.17 0-.31.14-.31.3l-.07 2.85.07 3.74c0 .16.14.3.31.3s.31-.14.31-.3l.08-3.74-.08-2.85c0-.16-.14-.3-.31-.3Zm1.45.9c-.18 0-.33.15-.33.32l-.06 1.95.06 3.68c0 .17.15.32.33.32s.33-.15.33-.32l.07-3.68-.07-1.95c0-.17-.15-.32-.33-.32Zm1.55.6c-.19 0-.35.16-.35.35v5c0 .19.16.35.35.35s.35-.16.35-.35v-5c0-.19-.16-.35-.35-.35Zm1.65-.6c-.2 0-.37.17-.37.37v5.6c0 .2.17.37.37.37s.37-.17.37-.37v-5.6c0-.2-.17-.37-.37-.37Zm1.75.4c-.21 0-.39.18-.39.39v4.8c0 .21.18.39.39.39s.39-.18.39-.39v-4.8c0-.21-.18-.39-.39-.39Zm1.9-2.2a3.4 3.4 0 0 0-2.4 1 3.6 3.6 0 0 0-1.05 2.55v.2a3.4 3.4 0 0 0-.8-.1 3.3 3.3 0 0 0-1.2.22 5 5 0 0 0-5-4.4 4.9 4.9 0 0 0-3.7 1.7.5.5 0 0 0-.2.4v6.7a.5.5 0 0 0 .5.5h13.85a3.9 3.9 0 0 0 3.9-3.9 3.9 3.9 0 0 0-3.9-3.85Z"/></svg>
      </div>
      <h3>SoundCloud</h3>
      <p>"Cursed on a Daily" playlist — stream the latest beats &amp; flips.</p>
      <span class="arrow">Stream now →</span>
    </a>

    <!-- Spotify -->
    <a class="card" href="https://open.spotify.com/playlist/77MWMnYu9oPIVptXMbq1Zc" target="_blank" rel="noopener">
      <div class="card-icon">
        <svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2Zm4.6 14.4a.6.6 0 0 1-.83.2 11 11 0 0 0-6.9-.85.6.6 0 1 1-.33-1.16 12.3 12.3 0 0 1 7.68 1 .6.6 0 0 1 .18.81Zm1.23-2.74a.75.75 0 0 1-1.03.25 13.8 13.8 0 0 0-8.47-1.5.75.75 0 0 1-.32-1.47 15.3 15.3 0 0 1 9.4 1.7.75.75 0 0 1 .22 1.02Zm.11-2.86A16.6 16.6 0 0 0 7.7 9.1a.9.9 0 1 1-.52-1.72 18.4 18.4 0 0 1 11.3 2.03.9.9 0 1 1-.92 1.55Z"/></svg>
      </div>
      <h3>Spotify</h3>
      <p>Curated playlist — follow and save to catch every new drop.</p>
      <span class="arrow">Play on Spotify →</span>
    </a>

    <!-- YouTube -->
    <a class="card" href="https://youtube.com/@cursedclips999" target="_blank" rel="noopener">
      <div class="card-icon">
        <svg viewBox="0 0 24 24"><path d="M23.5 6.2a3 3 0 0 0-2.1-2.1C19.5 3.5 12 3.5 12 3.5s-7.5 0-9.4.6A3 3 0 0 0 .5 6.2 31 31 0 0 0 0 12a31 31 0 0 0 .5 5.8 3 3 0 0 0 2.1 2.1c1.9.6 9.4.6 9.4.6s7.5 0 9.4-.6a3 3 0 0 0 2.1-2.1A31 31 0 0 0 24 12a31 31 0 0 0-.5-5.8ZM9.6 15.6V8.4l6.2 3.6Z"/></svg>
      </div>
      <h3>YouTube</h3>
      <p>Type beats, visuals &amp; clips. Subscribe for new uploads.</p>
      <span class="arrow">Subscribe →</span>
    </a>

    <!-- TikTok -->
    <a class="card" href="http
