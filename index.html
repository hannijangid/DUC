# DUC<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>3D AI UGC & Creative Studio</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; -webkit-user-select: none; user-select: none; }
        input, textarea { -webkit-user-select: text; user-select: text; }
        body { background-color: #050811; color: #f8fafc; line-height: 1.5; padding-bottom: 85px; overflow-x: hidden; }
        
        /* HERO SECTION WITH 3D TILT ELEMENTS */
        header { position: relative; text-align: center; padding: 55px 18px 45px; background: radial-gradient(circle at top, #172554 0%, #050811 75%); border-bottom: 1px solid rgba(56, 189, 248, 0.25); overflow: hidden; }
        
        /* 3D Floating AI Elements (Move with Phone Tilt) */
        .ai-3d-stage { position: absolute; top: 0; left: 0; width: 100%; height: 100%; pointer-events: none; z-index: 0; overflow: hidden; }
        .ai-orb { position: absolute; border-radius: 24px; background: linear-gradient(135deg, rgba(56,189,248,0.22), rgba(168,85,247,0.18)); border: 1px solid rgba(56,189,248,0.45); box-shadow: 0 10px 30px rgba(56,189,248,0.25), inset 0 0 15px rgba(255,255,255,0.15); backdrop-filter: blur(4px); transition: transform 0.12s ease-out; display: flex; align-items: center; justify-content: center; font-size: 22px; }
        .orb-1 { width: 65px; height: 65px; top: 18px; left: 8%; transform: rotate(15deg); }
        .orb-2 { width: 55px; height: 55px; top: 25px; right: 10%; border-radius: 50%; transform: rotate(-15deg); }
        .orb-3 { width: 50px; height: 50px; bottom: 20px; left: 12%; transform: rotate(25deg); }
        .orb-4 { width: 60px; height: 60px; bottom: 22px; right: 8%; border-radius: 16px; transform: rotate(-20deg); }

        .hero-content { position: relative; z-index: 2; }
        .badge { background: rgba(56, 189, 248, 0.15); color: #38bdf8; padding: 6px 16px; border-radius: 30px; font-size: 12px; font-weight: 700; display: inline-block; margin-bottom: 14px; border: 1px solid rgba(56, 189, 248, 0.45); box-shadow: 0 0 15px rgba(56, 189, 248, 0.25); }
        h1 { font-size: 28px; margin-bottom: 12px; line-height: 1.25; }
        h1 span { background: linear-gradient(90deg, #38bdf8, #a855f7); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        p.subtitle { color: #94a3b8; max-width: 600px; margin: 0 auto 24px; font-size: 14px; }
        
        .cta-group { display: flex; justify-content: center; gap: 12px; flex-wrap: wrap; }
        .btn { padding: 13px 22px; border-radius: 12px; text-decoration: none; font-weight: 700; font-size: 14px; display: inline-flex; align-items: center; gap: 8px; cursor: pointer; border: none; transition: 0.25s; }
        .btn-call { background: linear-gradient(135deg, #38bdf8, #0284c7); color: #050811; box-shadow: 0 6px 20px rgba(56, 189, 248, 0.35); }
        .btn-whatsapp { background: linear-gradient(135deg, #22c55e, #16a34a); color: #ffffff; box-shadow: 0 6px 20px rgba(34, 197, 94, 0.35); }

        /* LIVE INQUIRY & TRUST COUNTER BAR */
        .trust-bar { max-width: 900px; margin: 20px auto 0; padding: 0 15px; display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; text-align: center; }
        .trust-box { background: linear-gradient(145deg, #111827, #0b101d); border: 1px solid rgba(56, 189, 248, 0.25); padding: 14px 8px; border-radius: 14px; }
        .trust-num { font-size: 20px; font-weight: 800; color: #38bdf8; }
        .trust-label { font-size: 11px; color: #94a3b8; margin-top: 2px; }
        .live-dot { display: inline-block; width: 8px; height: 8px; background: #22c55e; border-radius: 50%; margin-right: 4px; animation: pulse 1.2s infinite; }
        @keyframes pulse { 0% { opacity: 1; } 50% { opacity: 0.3; } 100% { opacity: 1; } }

        /* Container & Headings */
        .container { max-width: 1120px; margin: 0 auto; padding: 38px 16px 8px; }
        .section-title { font-size: 23px; margin-bottom: 5px; text-align: center; font-weight: 800; }
        .section-desc { text-align: center; color: #94a3b8; margin-bottom: 22px; font-size: 13px; }

        /* 3D Futuristic Card */
        .card-3d { background: linear-gradient(145deg, #111827, #0a0f1c); border: 1px solid rgba(56, 189, 248, 0.22); border-radius: 14px; box-shadow: 0 10px 25px rgba(0,0,0,0.6); transition: 0.25s; }

        /* COMPACT 7 VIDEOS GRID (Smaller size for mobile) */
        .video-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 12px; }
        .video-card { padding: 8px; text-align: center; }
        .video-card video { width: 100%; height: 220px; border-radius: 10px; background: #000; object-fit: cover; border: 1px solid #1e293b; }
        .video-tag { margin-top: 6px; font-weight: 700; font-size: 13px; }
        .video-sub { font-size: 11px; color: #38bdf8; }

        /* CHARACTER FILTER TABS & SELECTABLE AVATARS */
        .filter-tabs { display: flex; justify-content: center; gap: 8px; flex-wrap: wrap; margin-bottom: 18px; }
        .tab-btn { background: #111827; color: #94a3b8; border: 1px solid #1e293b; padding: 7px 14px; border-radius: 20px; font-size: 12px; font-weight: 600; cursor: pointer; }
        .tab-btn.active { background: #38bdf8; color: #050811; border-color: #38bdf8; }

        .avatar-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(140px, 1fr)); gap: 12px; }
        .avatar-card { padding: 8px; text-align: center; cursor: pointer; position: relative; }
        .avatar-card.selected-char { border: 2px solid #22c55e; box-shadow: 0 0 18px rgba(34, 197, 94, 0.45); transform: scale(1.02); }
        .select-badge { position: absolute; top: 14px; right: 14px; background: #22c55e; color: #fff; font-size: 10px; font-weight: 800; padding: 3px 8px; border-radius: 10px; display: none; }
        .avatar-card.selected-char .select-badge { display: block; }
        .avatar-card img { width: 100%; height: 155px; object-fit: cover; border-radius: 10px; background: #1e293b; margin-bottom: 7px; }
        .avatar-name { font-weight: 700; font-size: 13px; color: #f8fafc; }
        .avatar-role { font-size: 11px; color: #38bdf8; }

        /* MONTHLY OFFER PACKAGES */
        .offer-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(270px, 1fr)); gap: 16px; }
        .offer-card { padding: 20px; position: relative; overflow: hidden; border: 2px solid #818cf8; }
        .offer-ribbon { position: absolute; top: 12px; right: -30px; background: linear-gradient(90deg, #f59e0b, #ef4444); color: #fff; font-size: 10px; font-weight: 800; padding: 4px 34px; transform: rotate(35deg); }
        .offer-title { font-size: 18px; font-weight: 800; margin-bottom: 5px; }
        .offer-price { font-size: 25px; font-weight: 800; color: #38bdf8; margin-bottom: 10px; }
        .offer-price del { font-size: 14px; color: #64748b; margin-right: 5px; }
        .offer-list { list-style: none; font-size: 12px; color: #cbd5e1; margin-bottom: 14px; }
        .offer-list li { margin-bottom: 6px; }

        /* CUSTOM PACKAGE BUILDER */
        .builder-box { background: linear-gradient(145deg, #0f172a, #080c17); border: 2px solid #38bdf8; border-radius: 18px; padding: 22px 16px; }
        .form-group { margin-bottom: 20px; }
        .form-label { display: block; font-weight: 700; font-size: 15px; margin-bottom: 8px; color: #38bdf8; }
        
        .selected-char-display { background: rgba(34, 197, 94, 0.12); border: 1px solid #22c55e; padding: 12px; border-radius: 10px; color: #4ade80; font-weight: 700; font-size: 14px; display: flex; justify-content: space-between; align-items: center; }
        .change-char-link { color: #38bdf8; font-size: 12px; text-decoration: underline; cursor: pointer; }

        .service-check { display: flex; justify-content: space-between; align-items: center; background: #1e293b; padding: 12px; border-radius: 10px; margin-bottom: 9px; cursor: pointer; border: 1px solid #334155; }
        .service-check.offer-highlight { border: 1px solid #f59e0b; background: rgba(245, 158, 11, 0.08); }
        .service-left { display: flex; align-items: center; gap: 9px; font-size: 13px; font-weight: 600; }
        .service-left input { width: 17px; height: 17px; accent-color: #22c55e; }
        .service-price { font-weight: 800; color: #22c55e; font-size: 14px; }
        .offer-tag { background: #ef4444; color: #fff; font-size: 9px; padding: 2px 6px; border-radius: 5px; margin-left: 4px; }

        .text-input { width: 100%; padding: 12px 14px; border-radius: 10px; border: 1px solid #334155; background: #050811; color: #fff; font-size: 14px; margin-bottom: 10px; }

        .total-bar { background: #050811; padding: 15px; border-radius: 12px; border: 1px solid #38bdf8; display: flex; justify-content: space-between; align-items: center; margin-bottom: 15px; }
        .total-amount { font-size: 26px; font-weight: 800; color: #38bdf8; }

        .book-btn { width: 100%; padding: 15px; font-size: 16px; font-weight: 800; background: linear-gradient(135deg, #22c55e, #15803d); color: #fff; border: none; border-radius: 12px; cursor: pointer; box-shadow: 0 8px 20px rgba(34, 197, 94, 0.4); }

        /* CLIENT RESPONSE / FEEDBACK SECTION */
        .feedback-box { padding: 20px; }
        .review-list { margin-top: 18px; display: grid; gap: 10px; }
        .review-item { background: #111827; border-left: 3px solid #38bdf8; padding: 12px; border-radius: 8px; }
        .review-author { font-weight: 700; font-size: 13px; color: #38bdf8; }
        .review-text { font-size: 13px; color: #cbd5e1; margin-top: 3px; }

        /* Floating Bar */
        .floating-bar { position: fixed; bottom: 12px; left: 50%; transform: translateX(-50%); background: rgba(15, 23, 42, 0.95); backdrop-filter: blur(10px); padding: 8px 14px; border-radius: 50px; border: 1px solid rgba(56, 189, 248, 0.4); display: flex; gap: 10px; z-index: 100; }
        .floating-bar a { text-decoration: none; font-weight: 700; font-size: 12px; padding: 8px 14px; border-radius: 25px; }
    </style>
</head>
<body oncontextmenu="return false;">

    <!-- HERO SECTION WITH 3D PHONE-TILT AI ELEMENTS -->
    <header>
        <div class="ai-3d-stage" id="tiltStage">
            <div class="ai-orb orb-1" data-speed="25">🤖</div>
            <div class="ai-orb orb-2" data-speed="-30">🎬</div>
            <div class="ai-orb orb-3" data-speed="20">⚡</div>
            <div class="ai-orb orb-4" data-speed="-25">🎙️</div>
        </div>

        <div class="hero-content">
            <div class="badge">⚡ 3D NEXT-GEN AI UGC STUDIO</div>
            <h1>High-Converting <span>AI UGC Videos</span> For Your Business</h1>
            <p class="subtitle">Apna pasandida AI Character select karein, Monthly Offer ya Custom Package banayein aur seedha WhatsApp par order book karein.</p>
            <div class="cta-group">
                <a href="tel:+917597145560" class="btn btn-call">📞 Direct Call Now</a>
                <a href="#builder" class="btn btn-whatsapp">⚡ Select Package & Book</a>
            </div>
        </div>
    </header>

    <!-- LIVE 5,400+ INQUIRIES & TRUST COUNTER -->
    <div class="trust-bar">
        <div class="trust-box">
            <div class="trust-num"><span id="inquiryCount">5,482</span>+</div>
            <div class="trust-label"><span class="live-dot"></span>Live Inquiries</div>
        </div>
        <div class="trust-box">
            <div class="trust-num">1,250+</div>
            <div class="trust-label">Brands Served</div>
        </div>
        <div class="trust-box">
            <div class="trust-num">4.9 ★</div>
            <div class="trust-label">Client Rating</div>
        </div>
    </div>

    <!-- 1. 7 SAMPLE VIDEOS SECTION (COMPACT SIZE) -->
    <div class="container">
        <h2 class="section-title">Our AI UGC Portfolio (7 Samples)</h2>
        <p class="section-desc">Realistic lip-sync, natural voice aur scroll-stopping hooks</p>
        <div class="video-grid">
            <div class="video-card card-3d"><video src="video1.mp4" controls playsinline></video><div class="video-tag">Sample #1</div><div class="video-sub">E-Commerce Ad</div></div>
            <div class="video-card card-3d"><video src="video2.mp4" controls playsinline></video><div class="video-tag">Sample #2</div><div class="video-sub">Real Estate Tour</div></div>
            <div class="video-card card-3d"><video src="video3.mp4" controls playsinline></video><div class="video-tag">Sample #3</div><div class="video-sub">Skincare Review</div></div>
            <div class="video-card card-3d"><video src="video4.mp4" controls playsinline></video><div class="video-tag">Sample #4</div><div class="video-sub">App / Service Promo</div></div>
            <div class="video-card card-3d"><video src="video5.mp4" controls playsinline></video><div class="video-tag">Sample #5</div><div class="video-sub">Fitness & Health</div></div>
            <div class="video-card card-3d"><video src="video6.mp4" controls playsinline></video><div class="video-tag">Sample #6</div><div class="video-sub">Fashion & Lifestyle</div></div>
            <div class="video-card card-3d"><video src="video7.mp4" controls playsinline></video><div class="video-tag">Sample #7</div><div class="video-sub">Local Business Ad</div></div>
        </div>
    </div>

    <!-- 2. SELECTABLE AI CHARACTERS (6 MEN + 6 GIRLS + 6 BUSINESS) -->
    <div class="container" id="characters">
        <h2 class="section-title">Tap to Select Your AI Character</h2>
        <p class="section-desc">Kisi bhi character par click karein — woh aapke package mein automatically add ho jayega</p>
        
        <div class="filter-tabs">
            <button class="tab-btn active" onclick="filterAvatars('all', this)">All (18)</button>
            <button class="tab-btn" onclick="filterAvatars('men', this)">👨 Men (6)</button>
            <button class="tab-btn" onclick="filterAvatars('girls', this)">👩 Girls (6)</button>
            <button class="tab-btn" onclick="filterAvatars('business', this)">🏢 Business (6)</button>
        </div>

        <div class="avatar-grid">
            <!-- 6 MEN CHARACTERS -->
            <div class="avatar-card card-3d selected-char" data-cat="men" onclick="pickCharacter(this, 'Men #1 - Aarav (Tech/Fitness)')"><span class="select-badge">✓ SELECTED</span><img src="men1.jpg" alt="Men 1"><div class="avatar-name">Men #1 - Aarav</div><div class="avatar-role">Tech & Fitness</div></div>
            <div class="avatar-card card-3d" data-cat="men" onclick="pickCharacter(this, 'Men #2 - Kabir (Lifestyle)')"><span class="select-badge">✓ SELECTED</span><img src="men2.jpg" alt="Men 2"><div class="avatar-name">Men #2 - Kabir</div><div class="avatar-role">Casual & Lifestyle</div></div>
            <div class="avatar-card card-3d" data-cat="men" onclick="pickCharacter(this, 'Men #3 - Rohan (Finance)')"><span class="select-badge">✓ SELECTED</span><img src="men3.jpg" alt="Men 3"><div class="avatar-name">Men #3 - Rohan</div><div class="avatar-role">Corporate & Finance</div></div>
            <div class="avatar-card card-3d" data-cat="men" onclick="pickCharacter(this, 'Men #4 - Dev (Fashion)')"><span class="select-badge">✓ SELECTED</span><img src="men4.jpg" alt="Men 4"><div class="avatar-name">Men #4 - Dev</div><div class="avatar-role">Fashion & Grooming</div></div>
            <div class="avatar-card card-3d" data-cat="men" onclick="pickCharacter(this, 'Men #5 - Aryan (Youth/Gaming)')"><span class="select-badge">✓ SELECTED</span><img src="men5.jpg" alt="Men 5"><div class="avatar-name">Men #5 - Aryan</div><div class="avatar-role">Youth & Gadgets</div></div>
            <div class="avatar-card card-3d" data-cat="men" onclick="pickCharacter(this, 'Men #6 - Alex (Global English)')"><span class="select-badge">✓ SELECTED</span><img src="men6.jpg" alt="Men 6"><div class="avatar-name">Men #6 - Alex</div><div class="avatar-role">International Ads</div></div>

            <!-- 6 GIRLS CHARACTERS -->
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #1 - Ananya (Skincare)')"><span class="select-badge">✓ SELECTED</span><img src="girl1.jpg" alt="Girl 1"><div class="avatar-name">Girl #1 - Ananya</div><div class="avatar-role">Skincare & Beauty</div></div>
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #2 - Meera (Fashion)')"><span class="select-badge">✓ SELECTED</span><img src="girl2.jpg" alt="Girl 2"><div class="avatar-name">Girl #2 - Meera</div><div class="avatar-role">Fashion & E-Com</div></div>
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #3 - Kiara (Lifestyle)')"><span class="select-badge">✓ SELECTED</span><img src="girl3.jpg" alt="Girl 3"><div class="avatar-name">Girl #3 - Kiara</div><div class="avatar-role">Daily Vlog Style</div></div>
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #4 - Riya (Apps/Tech)')"><span class="select-badge">✓ SELECTED</span><img src="girl4.jpg" alt="Girl 4"><div class="avatar-name">Girl #4 - Riya</div><div class="avatar-role">App & Service Promo</div></div>
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #5 - Naina (Wellness)')"><span class="select-badge">✓ SELECTED</span><img src="girl5.jpg" alt="Girl 5"><div class="avatar-name">Girl #5 - Naina</div><div class="avatar-role">Health & Nutrition</div></div>
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #6 - Sophia (Global)')"><span class="select-badge">✓ SELECTED</span><img src="girl6.jpg" alt="Girl 6"><div class="avatar-name">Girl #6 - Sophia</div><div class="avatar-role">International Brands</div></div>

            <!-- 6 BUSINESS / REAL ESTATE CHARACTERS -->
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #1 - Vikram (Real Estate)')"><span class="select-badge">✓ SELECTED</span><img src="biz1.jpg" alt="Biz 1"><div class="avatar-name">Biz #1 - Vikram</div><div class="avatar-role">Luxury Real Estate</div></div>
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #2 - Priya (Property Host)')"><span class="select-badge">✓ SELECTED</span><img src="biz2.jpg" alt="Biz 2"><div class="avatar-name">Biz #2 - Priya</div><div class="avatar-role">Property Walkthrough</div></div>
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #3 - Rajeev (Consultant)')"><span class="select-badge">✓ SELECTED</span><img src="biz3.jpg" alt="Biz 3"><div class="avatar-name">Biz #3 - Rajeev</div><div class="avatar-role">Business & B2B</div></div>
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #4 - Sneha (Anchor)')"><span class="select-badge">✓ SELECTED</span><img src="biz4.jpg" alt="Biz 4"><div class="avatar-name">Biz #4 - Sneha</div><div class="avatar-role">News & Explainer</div></div>
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #5 - Karan (Showroom)')"><span class="select-badge">✓ SELECTED</span><img src="biz5.jpg" alt="Biz 5"><div class="avatar-name">Biz #5 - Karan</div><div class="avatar-role">Auto & Retail Ads</div></div>
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #6 - Neha (Education)')"><span class="select-badge">✓ SELECTED</span><img src="biz6.jpg" alt="Biz 6"><div class="avatar-name">Biz #6 - Neha</div><div class="avatar-role">Coaching & Courses</div></div>
        </div>
    </div>

    <!-- 3. MONTHLY SPECIAL OFFER PACKAGES -->
    <div class="container">
        <h2 class="section-title">🔥 Monthly Spe<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>3D AI UGC & Creative Studio</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; -webkit-user-select: none; user-select: none; }
        input, textarea { -webkit-user-select: text; user-select: text; }
        body { background-color: #050811; color: #f8fafc; line-height: 1.5; padding-bottom: 85px; overflow-x: hidden; }
        
        /* HERO SECTION WITH 3D TILT ELEMENTS */
        header { position: relative; text-align: center; padding: 55px 18px 45px; background: radial-gradient(circle at top, #172554 0%, #050811 75%); border-bottom: 1px solid rgba(56, 189, 248, 0.25); overflow: hidden; }
        
        /* 3D Floating AI Elements (Move with Phone Tilt) */
        .ai-3d-stage { position: absolute; top: 0; left: 0; width: 100%; height: 100%; pointer-events: none; z-index: 0; overflow: hidden; }
        .ai-orb { position: absolute; border-radius: 24px; background: linear-gradient(135deg, rgba(56,189,248,0.22), rgba(168,85,247,0.18)); border: 1px solid rgba(56,189,248,0.45); box-shadow: 0 10px 30px rgba(56,189,248,0.25), inset 0 0 15px rgba(255,255,255,0.15); backdrop-filter: blur(4px); transition: transform 0.12s ease-out; display: flex; align-items: center; justify-content: center; font-size: 22px; }
        .orb-1 { width: 65px; height: 65px; top: 18px; left: 8%; transform: rotate(15deg); }
        .orb-2 { width: 55px; height: 55px; top: 25px; right: 10%; border-radius: 50%; transform: rotate(-15deg); }
        .orb-3 { width: 50px; height: 50px; bottom: 20px; left: 12%; transform: rotate(25deg); }
        .orb-4 { width: 60px; height: 60px; bottom: 22px; right: 8%; border-radius: 16px; transform: rotate(-20deg); }

        .hero-content { position: relative; z-index: 2; }
        .badge { background: rgba(56, 189, 248, 0.15); color: #38bdf8; padding: 6px 16px; border-radius: 30px; font-size: 12px; font-weight: 700; display: inline-block; margin-bottom: 14px; border: 1px solid rgba(56, 189, 248, 0.45); box-shadow: 0 0 15px rgba(56, 189, 248, 0.25); }
        h1 { font-size: 28px; margin-bottom: 12px; line-height: 1.25; }
        h1 span { background: linear-gradient(90deg, #38bdf8, #a855f7); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        p.subtitle { color: #94a3b8; max-width: 600px; margin: 0 auto 24px; font-size: 14px; }
        
        .cta-group { display: flex; justify-content: center; gap: 12px; flex-wrap: wrap; }
        .btn { padding: 13px 22px; border-radius: 12px; text-decoration: none; font-weight: 700; font-size: 14px; display: inline-flex; align-items: center; gap: 8px; cursor: pointer; border: none; transition: 0.25s; }
        .btn-call { background: linear-gradient(135deg, #38bdf8, #0284c7); color: #050811; box-shadow: 0 6px 20px rgba(56, 189, 248, 0.35); }
        .btn-whatsapp { background: linear-gradient(135deg, #22c55e, #16a34a); color: #ffffff; box-shadow: 0 6px 20px rgba(34, 197, 94, 0.35); }

        /* LIVE INQUIRY & TRUST COUNTER BAR */
        .trust-bar { max-width: 900px; margin: 20px auto 0; padding: 0 15px; display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; text-align: center; }
        .trust-box { background: linear-gradient(145deg, #111827, #0b101d); border: 1px solid rgba(56, 189, 248, 0.25); padding: 14px 8px; border-radius: 14px; }
        .trust-num { font-size: 20px; font-weight: 800; color: #38bdf8; }
        .trust-label { font-size: 11px; color: #94a3b8; margin-top: 2px; }
        .live-dot { display: inline-block; width: 8px; height: 8px; background: #22c55e; border-radius: 50%; margin-right: 4px; animation: pulse 1.2s infinite; }
        @keyframes pulse { 0% { opacity: 1; } 50% { opacity: 0.3; } 100% { opacity: 1; } }

        /* Container & Headings */
        .container { max-width: 1120px; margin: 0 auto; padding: 38px 16px 8px; }
        .section-title { font-size: 23px; margin-bottom: 5px; text-align: center; font-weight: 800; }
        .section-desc { text-align: center; color: #94a3b8; margin-bottom: 22px; font-size: 13px; }

        /* 3D Futuristic Card */
        .card-3d { background: linear-gradient(145deg, #111827, #0a0f1c); border: 1px solid rgba(56, 189, 248, 0.22); border-radius: 14px; box-shadow: 0 10px 25px rgba(0,0,0,0.6); transition: 0.25s; }

        /* COMPACT 7 VIDEOS GRID (Smaller size for mobile) */
        .video-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 12px; }
        .video-card { padding: 8px; text-align: center; }
        .video-card video { width: 100%; height: 220px; border-radius: 10px; background: #000; object-fit: cover; border: 1px solid #1e293b; }
        .video-tag { margin-top: 6px; font-weight: 700; font-size: 13px; }
        .video-sub { font-size: 11px; color: #38bdf8; }

        /* CHARACTER FILTER TABS & SELECTABLE AVATARS */
        .filter-tabs { display: flex; justify-content: center; gap: 8px; flex-wrap: wrap; margin-bottom: 18px; }
        .tab-btn { background: #111827; color: #94a3b8; border: 1px solid #1e293b; padding: 7px 14px; border-radius: 20px; font-size: 12px; font-weight: 600; cursor: pointer; }
        .tab-btn.active { background: #38bdf8; color: #050811; border-color: #38bdf8; }

        .avatar-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(140px, 1fr)); gap: 12px; }
        .avatar-card { padding: 8px; text-align: center; cursor: pointer; position: relative; }
        .avatar-card.selected-char { border: 2px solid #22c55e; box-shadow: 0 0 18px rgba(34, 197, 94, 0.45); transform: scale(1.02); }
        .select-badge { position: absolute; top: 14px; right: 14px; background: #22c55e; color: #fff; font-size: 10px; font-weight: 800; padding: 3px 8px; border-radius: 10px; display: none; }
        .avatar-card.selected-char .select-badge { display: block; }
        .avatar-card img { width: 100%; height: 155px; object-fit: cover; border-radius: 10px; background: #1e293b; margin-bottom: 7px; }
        .avatar-name { font-weight: 700; font-size: 13px; color: #f8fafc; }
        .avatar-role { font-size: 11px; color: #38bdf8; }

        /* MONTHLY OFFER PACKAGES */
        .offer-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(270px, 1fr)); gap: 16px; }
        .offer-card { padding: 20px; position: relative; overflow: hidden; border: 2px solid #818cf8; }
        .offer-ribbon { position: absolute; top: 12px; right: -30px; background: linear-gradient(90deg, #f59e0b, #ef4444); color: #fff; font-size: 10px; font-weight: 800; padding: 4px 34px; transform: rotate(35deg); }
        .offer-title { font-size: 18px; font-weight: 800; margin-bottom: 5px; }
        .offer-price { font-size: 25px; font-weight: 800; color: #38bdf8; margin-bottom: 10px; }
        .offer-price del { font-size: 14px; color: #64748b; margin-right: 5px; }
        .offer-list { list-style: none; font-size: 12px; color: #cbd5e1; margin-bottom: 14px; }
        .offer-list li { margin-bottom: 6px; }

        /* CUSTOM PACKAGE BUILDER */
        .builder-box { background: linear-gradient(145deg, #0f172a, #080c17); border: 2px solid #38bdf8; border-radius: 18px; padding: 22px 16px; }
        .form-group { margin-bottom: 20px; }
        .form-label { display: block; font-weight: 700; font-size: 15px; margin-bottom: 8px; color: #38bdf8; }
        
        .selected-char-display { background: rgba(34, 197, 94, 0.12); border: 1px solid #22c55e; padding: 12px; border-radius: 10px; color: #4ade80; font-weight: 700; font-size: 14px; display: flex; justify-content: space-between; align-items: center; }
        .change-char-link { color: #38bdf8; font-size: 12px; text-decoration: underline; cursor: pointer; }

        .service-check { display: flex; justify-content: space-between; align-items: center; background: #1e293b; padding: 12px; border-radius: 10px; margin-bottom: 9px; cursor: pointer; border: 1px solid #334155; }
        .service-check.offer-highlight { border: 1px solid #f59e0b; background: rgba(245, 158, 11, 0.08); }
        .service-left { display: flex; align-items: center; gap: 9px; font-size: 13px; font-weight: 600; }
        .service-left input { width: 17px; height: 17px; accent-color: #22c55e; }
        .service-price { font-weight: 800; color: #22c55e; font-size: 14px; }
        .offer-tag { background: #ef4444; color: #fff; font-size: 9px; padding: 2px 6px; border-radius: 5px; margin-left: 4px; }

        .text-input { width: 100%; padding: 12px 14px; border-radius: 10px; border: 1px solid #334155; background: #050811; color: #fff; font-size: 14px; margin-bottom: 10px; }

        .total-bar { background: #050811; padding: 15px; border-radius: 12px; border: 1px solid #38bdf8; display: flex; justify-content: space-between; align-items: center; margin-bottom: 15px; }
        .total-amount { font-size: 26px; font-weight: 800; color: #38bdf8; }

        .book-btn { width: 100%; padding: 15px; font-size: 16px; font-weight: 800; background: linear-gradient(135deg, #22c55e, #15803d); color: #fff; border: none; border-radius: 12px; cursor: pointer; box-shadow: 0 8px 20px rgba(34, 197, 94, 0.4); }

        /* CLIENT RESPONSE / FEEDBACK SECTION */
        .feedback-box { padding: 20px; }
        .review-list { margin-top: 18px; display: grid; gap: 10px; }
        .review-item { background: #111827; border-left: 3px solid #38bdf8; padding: 12px; border-radius: 8px; }
        .review-author { font-weight: 700; font-size: 13px; color: #38bdf8; }
        .review-text { font-size: 13px; color: #cbd5e1; margin-top: 3px; }

        /* Floating Bar */
        .floating-bar { position: fixed; bottom: 12px; left: 50%; transform: translateX(-50%); background: rgba(15, 23, 42, 0.95); backdrop-filter: blur(10px); padding: 8px 14px; border-radius: 50px; border: 1px solid rgba(56, 189, 248, 0.4); display: flex; gap: 10px; z-index: 100; }
        .floating-bar a { text-decoration: none; font-weight: 700; font-size: 12px; padding: 8px 14px; border-radius: 25px; }
    </style>
</head>
<body oncontextmenu="return false;">

    <!-- HERO SECTION WITH 3D PHONE-TILT AI ELEMENTS -->
    <header>
        <div class="ai-3d-stage" id="tiltStage">
            <div class="ai-orb orb-1" data-speed="25">🤖</div>
            <div class="ai-orb orb-2" data-speed="-30">🎬</div>
            <div class="ai-orb orb-3" data-speed="20">⚡</div>
            <div class="ai-orb orb-4" data-speed="-25">🎙️</div>
        </div>

        <div class="hero-content">
            <div class="badge">⚡ 3D NEXT-GEN AI UGC STUDIO</div>
            <h1>High-Converting <span>AI UGC Videos</span> For Your Business</h1>
            <p class="subtitle">Apna pasandida AI Character select karein, Monthly Offer ya Custom Package banayein aur seedha WhatsApp par order book karein.</p>
            <div class="cta-group">
                <a href="tel:+917597145560" class="btn btn-call">📞 Direct Call Now</a>
                <a href="#builder" class="btn btn-whatsapp">⚡ Select Package & Book</a>
            </div>
        </div>
    </header>

    <!-- LIVE 5,400+ INQUIRIES & TRUST COUNTER -->
    <div class="trust-bar">
        <div class="trust-box">
            <div class="trust-num"><span id="inquiryCount">5,482</span>+</div>
            <div class="trust-label"><span class="live-dot"></span>Live Inquiries</div>
        </div>
        <div class="trust-box">
            <div class="trust-num">1,250+</div>
            <div class="trust-label">Brands Served</div>
        </div>
        <div class="trust-box">
            <div class="trust-num">4.9 ★</div>
            <div class="trust-label">Client Rating</div>
        </div>
    </div>

    <!-- 1. 7 SAMPLE VIDEOS SECTION (COMPACT SIZE) -->
    <div class="container">
        <h2 class="section-title">Our AI UGC Portfolio (7 Samples)</h2>
        <p class="section-desc">Realistic lip-sync, natural voice aur scroll-stopping hooks</p>
        <div class="video-grid">
            <div class="video-card card-3d"><video src="video1.mp4" controls playsinline></video><div class="video-tag">Sample #1</div><div class="video-sub">E-Commerce Ad</div></div>
            <div class="video-card card-3d"><video src="video2.mp4" controls playsinline></video><div class="video-tag">Sample #2</div><div class="video-sub">Real Estate Tour</div></div>
            <div class="video-card card-3d"><video src="video3.mp4" controls playsinline></video><div class="video-tag">Sample #3</div><div class="video-sub">Skincare Review</div></div>
            <div class="video-card card-3d"><video src="video4.mp4" controls playsinline></video><div class="video-tag">Sample #4</div><div class="video-sub">App / Service Promo</div></div>
            <div class="video-card card-3d"><video src="video5.mp4" controls playsinline></video><div class="video-tag">Sample #5</div><div class="video-sub">Fitness & Health</div></div>
            <div class="video-card card-3d"><video src="video6.mp4" controls playsinline></video><div class="video-tag">Sample #6</div><div class="video-sub">Fashion & Lifestyle</div></div>
            <div class="video-card card-3d"><video src="video7.mp4" controls playsinline></video><div class="video-tag">Sample #7</div><div class="video-sub">Local Business Ad</div></div>
        </div>
    </div>

    <!-- 2. SELECTABLE AI CHARACTERS (6 MEN + 6 GIRLS + 6 BUSINESS) -->
    <div class="container" id="characters">
        <h2 class="section-title">Tap to Select Your AI Character</h2>
        <p class="section-desc">Kisi bhi character par click karein — woh aapke package mein automatically add ho jayega</p>
        
        <div class="filter-tabs">
            <button class="tab-btn active" onclick="filterAvatars('all', this)">All (18)</button>
            <button class="tab-btn" onclick="filterAvatars('men', this)">👨 Men (6)</button>
            <button class="tab-btn" onclick="filterAvatars('girls', this)">👩 Girls (6)</button>
            <button class="tab-btn" onclick="filterAvatars('business', this)">🏢 Business (6)</button>
        </div>

        <div class="avatar-grid">
            <!-- 6 MEN CHARACTERS -->
            <div class="avatar-card card-3d selected-char" data-cat="men" onclick="pickCharacter(this, 'Men #1 - Aarav (Tech/Fitness)')"><span class="select-badge">✓ SELECTED</span><img src="men1.jpg" alt="Men 1"><div class="avatar-name">Men #1 - Aarav</div><div class="avatar-role">Tech & Fitness</div></div>
            <div class="avatar-card card-3d" data-cat="men" onclick="pickCharacter(this, 'Men #2 - Kabir (Lifestyle)')"><span class="select-badge">✓ SELECTED</span><img src="men2.jpg" alt="Men 2"><div class="avatar-name">Men #2 - Kabir</div><div class="avatar-role">Casual & Lifestyle</div></div>
            <div class="avatar-card card-3d" data-cat="men" onclick="pickCharacter(this, 'Men #3 - Rohan (Finance)')"><span class="select-badge">✓ SELECTED</span><img src="men3.jpg" alt="Men 3"><div class="avatar-name">Men #3 - Rohan</div><div class="avatar-role">Corporate & Finance</div></div>
            <div class="avatar-card card-3d" data-cat="men" onclick="pickCharacter(this, 'Men #4 - Dev (Fashion)')"><span class="select-badge">✓ SELECTED</span><img src="men4.jpg" alt="Men 4"><div class="avatar-name">Men #4 - Dev</div><div class="avatar-role">Fashion & Grooming</div></div>
            <div class="avatar-card card-3d" data-cat="men" onclick="pickCharacter(this, 'Men #5 - Aryan (Youth/Gaming)')"><span class="select-badge">✓ SELECTED</span><img src="men5.jpg" alt="Men 5"><div class="avatar-name">Men #5 - Aryan</div><div class="avatar-role">Youth & Gadgets</div></div>
            <div class="avatar-card card-3d" data-cat="men" onclick="pickCharacter(this, 'Men #6 - Alex (Global English)')"><span class="select-badge">✓ SELECTED</span><img src="men6.jpg" alt="Men 6"><div class="avatar-name">Men #6 - Alex</div><div class="avatar-role">International Ads</div></div>

            <!-- 6 GIRLS CHARACTERS -->
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #1 - Ananya (Skincare)')"><span class="select-badge">✓ SELECTED</span><img src="girl1.jpg" alt="Girl 1"><div class="avatar-name">Girl #1 - Ananya</div><div class="avatar-role">Skincare & Beauty</div></div>
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #2 - Meera (Fashion)')"><span class="select-badge">✓ SELECTED</span><img src="girl2.jpg" alt="Girl 2"><div class="avatar-name">Girl #2 - Meera</div><div class="avatar-role">Fashion & E-Com</div></div>
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #3 - Kiara (Lifestyle)')"><span class="select-badge">✓ SELECTED</span><img src="girl3.jpg" alt="Girl 3"><div class="avatar-name">Girl #3 - Kiara</div><div class="avatar-role">Daily Vlog Style</div></div>
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #4 - Riya (Apps/Tech)')"><span class="select-badge">✓ SELECTED</span><img src="girl4.jpg" alt="Girl 4"><div class="avatar-name">Girl #4 - Riya</div><div class="avatar-role">App & Service Promo</div></div>
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #5 - Naina (Wellness)')"><span class="select-badge">✓ SELECTED</span><img src="girl5.jpg" alt="Girl 5"><div class="avatar-name">Girl #5 - Naina</div><div class="avatar-role">Health & Nutrition</div></div>
            <div class="avatar-card card-3d" data-cat="girls" onclick="pickCharacter(this, 'Girl #6 - Sophia (Global)')"><span class="select-badge">✓ SELECTED</span><img src="girl6.jpg" alt="Girl 6"><div class="avatar-name">Girl #6 - Sophia</div><div class="avatar-role">International Brands</div></div>

            <!-- 6 BUSINESS / REAL ESTATE CHARACTERS -->
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #1 - Vikram (Real Estate)')"><span class="select-badge">✓ SELECTED</span><img src="biz1.jpg" alt="Biz 1"><div class="avatar-name">Biz #1 - Vikram</div><div class="avatar-role">Luxury Real Estate</div></div>
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #2 - Priya (Property Host)')"><span class="select-badge">✓ SELECTED</span><img src="biz2.jpg" alt="Biz 2"><div class="avatar-name">Biz #2 - Priya</div><div class="avatar-role">Property Walkthrough</div></div>
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #3 - Rajeev (Consultant)')"><span class="select-badge">✓ SELECTED</span><img src="biz3.jpg" alt="Biz 3"><div class="avatar-name">Biz #3 - Rajeev</div><div class="avatar-role">Business & B2B</div></div>
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #4 - Sneha (Anchor)')"><span class="select-badge">✓ SELECTED</span><img src="biz4.jpg" alt="Biz 4"><div class="avatar-name">Biz #4 - Sneha</div><div class="avatar-role">News & Explainer</div></div>
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #5 - Karan (Showroom)')"><span class="select-badge">✓ SELECTED</span><img src="biz5.jpg" alt="Biz 5"><div class="avatar-name">Biz #5 - Karan</div><div class="avatar-role">Auto & Retail Ads</div></div>
            <div class="avatar-card card-3d" data-cat="business" onclick="pickCharacter(this, 'Biz #6 - Neha (Education)')"><span class="select-badge">✓ SELECTED</span><img src="biz6.jpg" alt="Biz 6"><div class="avatar-name">Biz #6 - Neha</div><div class="avatar-role">Coaching & Courses</div></div>
        </div>
    </div>

    <!-- 3. MONTHLY SPECIAL OFFER PACKAGES -->
    <div class="container">
        <h2 class="section-title">🔥 Monthly Special Offer Plans</h2>
        <p class="section-desc">Limited time discounted packages for regular social media growth</p>
        <div class="offer-grid">
            <div class="offer-card card-3d">
                <div class="offer-ribbon">25% OFF</div>
                <div class="offer-title">🚀 15 Reels Monthly Offer</div>
                <div class="offer-price"><del>₹14,999</del> ₹10,999 <span style="font-size:12px; color:#94a3b8;">/ month</span></div>
                <ul class="offer-list">
                    <li>✅ 15 High-Converting AI UGC Reels</li>
                    <li>✅ Multiple Men & Girls AI Characters</li>
                    <li>✅ Viral Hook Scripts + Trending Subtitles</li>
                </ul>
                <a href="#builder" onclick="selectMonthlyOffer('offer15')" class="btn btn-call" style="width:100%; justify-content:center;">Select 15 Reels Offer</a>
            </div>

            <div class="offer-card card-3d" style="border-color: #22c55e;">
                <div class="offer-ribbon">35% OFF</div>
                <div class="offer-title">👑 30 Reels Monthly Mega Offer</div>
                <div class="offer-price"><del>₹29,999</del> ₹18,999 <span style="font-size:12px; color:#94a3b8;">/ month</span></div>
                <ul class="offer-list">
                    <li>✅ 30 AI UGC Reels (Daily 1 Video)</li>
                    <li>✅ Custom Brand Avatar Free Included</li>
                    <li>✅ A/B Testing Hooks + Priority Delivery</li>
                </ul>
                <a href="#builder" onclick="selectMonthlyOffer('offer30')" class="btn btn-whatsapp" style="width:100%; justify-content:center;">Select 30 Reels Offer</a>
            </div>
        </div>
    </div>

    <!-- 4. INTERACTIVE PACKAGE BUILDER -->
    <div class="container" id="builder">
        <h2 class="section-title">Build Your Custom Package</h2>
        <p class="section-desc">Selected character aur services check karein, price dekhein aur book karein</p>

        <div class="builder-box">
            <!-- Selected Character Display -->
            <div class="form-group">
                <label class="form-label">1. Selected AI Character / Model:</label>
                <div class="selected-char-display">
                    <span id="chosenCharText">Men #1 - Aarav (Tech/Fitness)</span>
                    <a href="#characters" class="change-char-link">Change Model ↑</a>
                </div>
            </div>

            <!-- Select Services -->
            <div class="form-group">
                <label class="form-label">2. Select Package or Services:</label>
                
                <label class="service-check offer-highlight">
                    <span class="service-left"><input type="checkbox" id="offer15" class="srv" data-name="15 Reels Monthly Offer Plan" value="10999" onchange="calculateTotal()"> 15 Reels Monthly Plan <span class="offer-tag">OFFER</span></span>
                    <span class="service-price">₹10,999</span>
                </label>

                <label class="service-check offer-highlight">
                    <span class="service-left"><input type="checkbox" id="offer30" class="srv" data-name="30 Reels Monthly Mega Offer Plan" value="18999" onchange="calculateTotal()"> 30 Reels Monthly Plan <span class="offer-tag">BEST OFFER</span></span>
                    <span class="service-price">₹18,999</span>
                </label>

                <label class="service-check">
                    <span class="service-left"><input type="checkbox" class="srv" data-name="1 Single AI UGC Video (30 Sec)" value="999" checked onchange="calculateTotal()"> 1 Single AI UGC Video (30 Sec)</span>
                    <span class="service-price">₹999</span>
                </label>

                <label class="service-check">
                    <span class="service-left"><input type="checkbox" class="srv" data-name="3 AI UGC Videos Starter Bundle" value="2499" onchange="calculateTotal()"> 3 AI UGC Videos Bundle</span>
                    <span class="service-price">₹2,499</span>
                </label>

                <label class="service-check">
                    <span class="service-left"><input type="checkbox" class="srv" data-name="Real Estate / Property Promo Video" value="1499" onchange="calculateTotal()"> Real Estate / Property Promo Video</span>
                    <span class="service-price">₹1,499</span>
                </label>

                <label class="service-check">
                    <span class="service-left"><input type="checkbox" class="srv" data-name="Viral Script + 2 Extra Hooks" value="499" onchange="calculateTotal()"> Viral Script + 2 Extra Hooks</span>
                    <span class="service-price">₹499</span>
                </label>

                <label class="service-check">
                    <span class="service-left"><input type="checkbox" class="srv" data-name="Custom AI Avatar Creation" value="1999" onchange="calculateTotal()"> Custom AI Avatar (Apna Face/Model)</span>
                    <span class="service-price">₹1,999</span>
                </label>
            </div>

            <!-- Client Details -->
            <div class="form-group">
                <label class="form-label">3. Your Details:</label>
                <input type="text" id="clientName" class="text-input" placeholder="Aapka Naam / Brand Name *" required>
                <input type="text" id="clientNote" class="text-input" placeholder="Koi special note ya product detail (Optional)">
            </div>

            <!-- Live Total -->
            <div class="total-bar">
                <span style="color:#94a3b8; font-weight:600;">Estimated Total:</span>
                <span class="total-amount">₹<span id="totalPrice">999</span></span>
            </div>

            <!-- Direct WhatsApp Book Now Button -->
            <button class="book-btn" onclick="bookNow()">🚀 Book Now on WhatsApp</button>
        </div>
    </div>

    <!-- 5. CLIENT FEEDBACK & RESPONSE SECTION -->
    <div class="container">
        <h2 class="section-title">Client Reviews & Share Your Response</h2>
        <p class="section-desc">Apna feedback ya experience yahan share karein</p>
        <div class="feedback-box card-3d">
            <input type="text" id="revName" class="text-input" placeholder="Aapka Naam / Business Name">
            <textarea id="revMsg" class="text-input" rows="2" placeholder="Apna review ya message likhein..."></textarea>
            <button class="btn btn-call" style="width:100%; justify-content:center;" onclick="addReview()">💬 Submit Response</button>

            <div class="review-list" id="reviewList">
                <div class="review-item">
                    <div class="review-author">★★★★★ Rahul Sharma (E-Commerce Owner)</div>
                    <div class="review-text">Bahut hi realistic AI videos banaye hain, hamare Facebook ads ki cost half ho gayi!</div>
                </div>
                <div class="review-item">
                    <div class="review-author">★★★★★ Amit Real Estate Jaipur</div>
                    <div class="review-text">24 ghante mein property walkthrough video mil gaya, super fast service.</div>
                </div>
            </div>
        </div>
    </div>

    <!-- FLOATING CONTACT BAR -->
    <div class="floating-bar">
        <a href="tel:+917597145560" style="background:#38bdf8; color:#050811;">📞 Call Now</a>
        <a href="#builder" style="background:#22c55e; color:#fff;">⚡ Book Package</a>
    </div>

    <!-- SCRIPTS -->
    <script>
        let chosenCharacter = "Men #1 - Aarav (Tech/Fitness)";

        // 1. Phone Tilt (Gyroscope) 3D Movement
        window.addEventListener('deviceorientation', function(event) {
            const gamma = event.gamma || 0; // Left-Right tilt (-90 to 90)
            const beta = event.beta || 0;   // Front-Back tilt (-180 to 180)
            const orbs = document.querySelectorAll('.ai-orb');
            orbs.forEach(orb => {
                const speed = parseFloat(orb.getAttribute('data-speed')) || 20;
                const x = (gamma / 45) * speed;
                const y = ((beta - 45) / 45) * speed;
                orb.style.transform = `translate3d(${x}px, ${y}px, 0) rotate(${x}deg)`;
            });
        });

        // 2. Live Inquiry Counter (5,482+ growing smoothly)
        let baseInquiry = 5482;
        setInterval(() => {
            if (baseInquiry < 5990) {
                baseInquiry += 1;
                document.getElementById('inquiryCount').innerText = baseInquiry.toLocaleString('en-IN');
            }
        }, 6500);

        // 3. Filter Characters
        function filterAvatars(category, btn) {
            document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
            btn.classList.add('active');
            document.querySelectorAll('.avatar-card').forEach(card => {
                card.style.display = (category === 'all' || card.getAttribute('data-cat') === category) ? 'block' : 'none';
            });
        }

        // 4. Pick Character & Mention in Package
        function pickCharacter(cardElement, charName) {
            document.querySelectorAll('.avatar-card').forEach(c => c.classList.remove('selected-char'));
            cardElement.classList.add('selected-char');
            chosenCharacter = charName;
            document.getElementById('chosenCharText').innerText = charName;
        }

        // 5. Select Monthly Offer
        function selectMonthlyOffer(offerId) {
            document.querySelectorAll('.srv').forEach(box => box.checked = false);
            document.getElementById(offerId).checked = true;
            calculateTotal();
        }

        // 6. Calculate Total
        function calculateTotal() {
            let total = 0;
            document.querySelectorAll('.srv:checked').forEach((box) => {
                total += parseInt(box.value);
            });
            document.getElementById('totalPrice').innerText = total.toLocaleString('en-IN');
        }

        // 7. Clean Direct WhatsApp Link (Fixes back button issue completely)
        function bookNow() {
            const myWhatsAppNumber = "917597145560";
            const name = document.getElementById('clientName').value.trim();
            if (!name) {
                alert("Kripya pehle apna Naam ya Brand Name likhein!");
                return;
            }

            const note = document.getElementById('clientNote').value.trim() || "None";
            const total = document.getElementById('totalPrice').innerText;

            let selectedServices = [];
            document.querySelectorAll('.srv:checked').forEach((box) => {
                selectedServices.push("• " + box.getAttribute('data-name') + " (₹" + box.value + ")");
            });

            if (selectedServices.length === 0) {
                alert("Kripya kam se kam ek service select karein!");
                return;
            }

            const message = `*🔥 NEW AI UGC ORDER BOOKING 🔥*\n\n` +
                            `*👤 Client Name:* ${name}\n` +
                            `*🎭 Selected AI Model:* ${chosenCharacter}\n\n` +
                            `*📦 Selected Services:*\n${selectedServices.join('\n')}\n\n` +
                            `*💰 Total Estimated Price:* ₹${total}\n` +
                            `*📝 Note:* ${note}`;

            const cleanUrl = `https://wa.me/${myWhatsAppNumber}?text=${encodeURIComponent(message)}`;
            window.location.assign(cleanUrl);
        }

        // 8. Public Client Response / Review Submit
        function addReview() {
            const rName = document.getElementById('revName').value.trim();
            const rMsg = document.getElementById('revMsg').value.trim();
            if (!rName || !rMsg) {
                alert("Kripya apna naam aur message dono likhein!");
                return;
            }
            const list = document.getElementById('reviewList');
            const newItem = document.createElement('div');
            newItem.className = 'review-item';
            newItem.innerHTML = `<div class="review-author">★★★★★ ${rName} (Just Now)</div><div class="review-text">${rMsg}</div>`;
            list.prepend(newItem);
            document.getElementById('revName').value = '';
            document.getElementById('revMsg').value = '';
        }

        // 9. Basic Anti-Inspect / Anti-Copy Security
        document.addEventListener('keydown', function(e) {
            if (e.key === 'F12' || (e.ctrlKey && e.shiftKey && (e.key === 'I' || e.key === 'J' || e.key === 'C')) || (e.ctrlKey && e.key === 'u')) {
                e.preventDefault();
            }
        });
    </script>
</body>
</html>
