<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1">
<title>Christian Church Kolwezi — Platform</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;0,700;1,400&family=Outfit:wght@300;400;500;600;700&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
<style>
:root{
  --bg:#0F1923; --surf:#162030; --card:#1C2A3A; --card2:#243346; --bdr:#2A3D52; --dim:#354D65;
  --gold:#C9982A; --gl:#E8B84B; --gll:#F5CC6A; --gdim:rgba(201,152,42,0.14); --gdm:rgba(201,152,42,0.08);
  --txt:#EDF2F7; --sub:#B0C0D4; --mut:#7A92AA; --dim2:#4A6278;
  --grn:#2DD4A0; --gnd:rgba(45,212,160,0.13);
  --blu:#5B9EE8; --bld:rgba(91,158,232,0.13);
  --pur:#9B7FE8; --pud:rgba(155,127,232,0.13);
  --red:#E87070; --rdd:rgba(232,112,112,0.13);
  --sky:#38BDF8; --sbar:252px; --r:14px;
}
*{box-sizing:border-box;margin:0;padding:0;}
html,body{height:100%;font-size:15px;}
body{background:var(--bg);color:var(--txt);font-family:'Outfit',sans-serif;line-height:1.65;-webkit-font-smoothing:antialiased;}
::-webkit-scrollbar{width:5px;height:5px;}::-webkit-scrollbar-track{background:var(--surf);}::-webkit-scrollbar-thumb{background:var(--bdr);border-radius:10px;}

/* LAYOUT */
#wrap{display:flex;height:100vh;overflow:hidden;}
#sidebar{width:var(--sbar);flex-shrink:0;background:var(--surf);border-right:1px solid var(--bdr);display:flex;flex-direction:column;position:relative;z-index:50;transition:width .22s ease;overflow:hidden;}
#sidebar.slim{width:68px;}
#sidebar.slim .sh{display:none!important;}
#sidebar.slim .nav-item{justify-content:center;padding:10px 0;}
#main{flex:1;display:flex;flex-direction:column;overflow:hidden;}
#topbar{flex-shrink:0;background:var(--surf);border-bottom:1px solid var(--bdr);padding:0 26px;height:58px;display:flex;align-items:center;justify-content:space-between;z-index:40;}
#content{flex:1;overflow-y:auto;padding:28px 26px 80px;}

/* SIDEBAR */
.sb-hdr{padding:17px 16px 13px;border-bottom:1px solid var(--bdr);display:flex;align-items:center;justify-content:space-between;flex-shrink:0;}
.sb-logo{width:38px;height:38px;border-radius:10px;flex-shrink:0;background:linear-gradient(145deg,#C9982A,#A07420);display:flex;align-items:center;justify-content:center;font-size:19px;box-shadow:0 2px 10px rgba(201,152,42,0.3);}
.sb-name{font-family:'Cormorant Garamond',serif;font-size:15px;font-weight:700;line-height:1.2;letter-spacing:.01em;margin-left:11px;}
.sb-loc{font-size:10px;color:var(--mut);letter-spacing:.06em;margin-top:1px;margin-left:11px;}
.sb-tog{background:none;border:none;color:var(--mut);cursor:pointer;font-size:17px;padding:5px;opacity:.7;flex-shrink:0;}
.sb-tog:hover{opacity:1;color:var(--txt);}
.sb-pastors{padding:13px 16px;border-bottom:1px solid var(--bdr);}
.p-row{display:flex;align-items:center;gap:9px;margin-bottom:8px;}
.p-row:last-of-type{margin-bottom:0;}
.pav{width:30px;height:30px;border-radius:50%;flex-shrink:0;background:var(--gdim);border:1.5px solid var(--gold);display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:700;color:var(--gold);font-family:'DM Mono',monospace;}
.pnm{font-size:11px;font-weight:600;line-height:1.2;}
.prl{font-size:9px;color:var(--mut);margin-top:1px;}
.phase-pill{margin-top:10px;background:var(--gdim);border:1px solid rgba(201,152,42,.35);border-radius:6px;padding:5px 10px;font-size:10px;color:var(--gl);font-weight:600;text-align:center;letter-spacing:.03em;}
.sb-nav{flex:1;overflow-y:auto;padding:8px 0;}
.nav-item{display:flex;align-items:center;gap:11px;padding:9px 16px;margin:1px 8px;border-radius:9px;cursor:pointer;border-left:2.5px solid transparent;transition:all .15s;}
.nav-item:hover{background:rgba(255,255,255,.04);}
.nav-item.active{background:var(--gdm);border-left-color:var(--gold);}
.ni{font-size:17px;flex-shrink:0;width:20px;text-align:center;}
.nl{font-size:13px;font-weight:500;color:var(--sub);white-space:nowrap;}
.nav-item.active .nl{color:var(--gl);font-weight:600;}
.sb-foot{padding:12px 16px;border-top:1px solid var(--bdr);}
.sb-dlbl{font-size:9px;color:var(--mut);text-transform:uppercase;letter-spacing:.08em;font-weight:700;margin-bottom:7px;font-family:'DM Mono',monospace;}
.doc-lnk{display:flex;align-items:center;gap:7px;padding:5px 4px;font-size:11px;color:var(--mut);text-decoration:none;border-radius:6px;transition:.15s;}
.doc-lnk:hover{color:var(--gl);}

/* TOPBAR */
.tb-l{display:flex;align-items:center;gap:12px;}
.tb-hbg{display:none;background:none;border:none;color:var(--mut);cursor:pointer;font-size:21px;padding:4px;}
.tb-ttl{font-family:'Cormorant Garamond',serif;font-size:19px;font-weight:700;letter-spacing:.01em;}
.tb-r{display:flex;align-items:center;gap:14px;}

/* LANGUAGE SWITCHER */
.lang-sw{display:flex;align-items:center;background:var(--card2);border:1px solid var(--bdr);border-radius:8px;padding:3px;gap:2px;}
.lo{padding:5px 14px;border-radius:6px;font-size:12px;font-weight:700;cursor:pointer;border:none;background:transparent;color:var(--mut);font-family:'DM Mono',monospace;transition:all .18s;letter-spacing:.05em;line-height:1;}
.lo.on{background:var(--gold);color:#0C1620;box-shadow:0 1px 6px rgba(201,152,42,0.4);}
.lo:not(.on):hover{color:var(--txt);}
.tb-av{width:34px;height:34px;border-radius:9px;background:var(--gdim);border:1.5px solid var(--gold);display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:700;color:var(--gl);font-family:'DM Mono',monospace;}

/* MOBILE */
#mob-ov{display:none;position:fixed;inset:0;background:rgba(0,0,0,.55);z-index:200;}
#mob-ov.on{display:block;}
#bot-nav{display:none;position:fixed;bottom:0;left:0;right:0;z-index:180;background:var(--surf);border-top:1px solid var(--bdr);padding:6px 0 max(8px,env(safe-area-inset-bottom));}
.bi{display:flex;flex-direction:column;align-items:center;gap:3px;cursor:pointer;min-width:52px;padding:4px 6px;color:var(--mut);transition:color .15s;}
.bi.active,.bi:hover{color:var(--gl);}
.bi-ico{font-size:19px;line-height:1;}.bi-lbl{font-size:9px;font-weight:600;text-transform:uppercase;letter-spacing:.04em;}

@media(max-width:900px){:root{--sbar:68px;} #sidebar .sh{display:none!important;} #sidebar .nav-item{justify-content:center;padding:10px 0;}}
@media(max-width:680px){
  #wrap{flex-direction:column;} #sidebar{display:none;} #main{width:100%;}
  .tb-hbg{display:block;} #bot-nav{display:block;} #content{padding:16px 14px 90px;}
  .g4{grid-template-columns:1fr 1fr!important;} .g1{grid-template-columns:1fr!important;}
  .g2{grid-template-columns:1fr!important;} .g21{grid-template-columns:1fr!important;}
  .phbody{grid-template-columns:1fr!important;} .ph34b{grid-template-columns:1fr!important;}
  .pricing-g{grid-template-columns:1fr!important;} .ks-grid{grid-template-columns:1fr!important;}
  h1.h1{font-size:22px!important;} .ph-hdr{flex-direction:column!important;}
  .ph-act .btnp{width:100%;} .ksh{flex-direction:column!important;gap:16px!important;}
  .ks-pkg{grid-template-columns:1fr!important;}
}

/* PAGES */
.page{display:none;}.page.on{display:block;}
.ph-hdr{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:26px;gap:12px;}
.ph-ttl h1{font-family:'Cormorant Garamond',serif;font-size:26px;font-weight:700;letter-spacing:.01em;margin-bottom:3px;}
.ph-ttl p{color:var(--mut);font-size:13px;}
.ph-act{flex-shrink:0;}

/* BUTTONS */
.btnp{padding:9px 18px;border-radius:9px;font-size:13px;font-family:'Outfit',sans-serif;font-weight:600;cursor:pointer;border:none;transition:all .15s;display:inline-flex;align-items:center;gap:6px;}
.bg{background:var(--gold);color:#0C1620;box-shadow:0 2px 10px rgba(201,152,42,0.3);}
.bg:hover{background:var(--gl);transform:translateY(-1px);}
.bgh{background:transparent;color:var(--gold);border:1.5px solid rgba(201,152,42,0.5)!important;}
.bgh:hover{background:var(--gdim);border-color:var(--gold)!important;}
.bsm{padding:5px 12px;font-size:12px;border-radius:7px;}

/* METRICS */
.mrow{display:grid;grid-template-columns:repeat(4,1fr);gap:13px;margin-bottom:22px;}
.mc{background:var(--card);border:1px solid var(--bdr);border-radius:var(--r);padding:17px 19px;border-top:2.5px solid;position:relative;overflow:hidden;}
.mc-lbl{font-size:10px;color:var(--mut);text-transform:uppercase;letter-spacing:.07em;font-weight:600;margin-bottom:6px;}
.mc-val{font-family:'Cormorant Garamond',serif;font-size:28px;font-weight:700;line-height:1;margin-bottom:4px;}
.mc-sub{font-size:11px;color:var(--grn);}
.mc-ico{position:absolute;top:14px;right:16px;font-size:22px;opacity:.45;}

/* CARDS */
.card{background:var(--card);border:1px solid var(--bdr);border-radius:var(--r);padding:20px 22px;}
.ct{font-family:'Cormorant Garamond',serif;font-size:17px;font-weight:700;margin-bottom:14px;letter-spacing:.01em;}
.sl{font-size:10px;font-weight:700;color:var(--gold);text-transform:uppercase;letter-spacing:.08em;margin:14px 0 9px;font-family:'DM Mono',monospace;}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:14px;}
.g21{display:grid;grid-template-columns:2fr 1fr;gap:14px;}
.g3{display:grid;grid-template-columns:repeat(3,1fr);gap:13px;}
.g4{display:grid;grid-template-columns:repeat(4,1fr);gap:11px;}
.bdg{display:inline-flex;align-items:center;padding:3px 9px;border-radius:20px;font-size:11px;font-weight:600;}
.pt{background:var(--card2);border-radius:4px;height:5px;overflow:hidden;}
.pf{height:100%;border-radius:4px;transition:width .4s;}
.ch{position:relative;width:100%;height:210px;} .chsm{position:relative;width:100%;height:170px;} .chp{position:relative;width:100%;height:155px;}
input.srch{width:100%;padding:10px 14px;background:var(--card2);border:1px solid var(--bdr);border-radius:9px;color:var(--txt);font-size:13px;font-family:'Outfit',sans-serif;outline:none;margin-bottom:14px;}
input.srch:focus{border-color:var(--gold);}
table{width:100%;border-collapse:collapse;font-size:13px;}
th{text-align:left;padding:8px 11px;font-size:10px;color:var(--mut);text-transform:uppercase;letter-spacing:.06em;border-bottom:1px solid var(--bdr);font-weight:600;}
td{padding:10px 11px;border-bottom:1px solid var(--bdr);vertical-align:middle;}
tr:last-child td{border-bottom:none;}
tr:hover td{background:rgba(255,255,255,.015);}
.tw{overflow-x:auto;}

/* ── ROADMAP ── */
.rp-wrap{display:flex;align-items:center;background:var(--card);border:1px solid var(--bdr);border-radius:var(--r);padding:18px 22px;margin-bottom:28px;}
.rp-step{flex:1;display:flex;flex-direction:column;align-items:center;position:relative;}
.rp-step::after{content:'';position:absolute;top:13px;left:50%;width:100%;height:2px;background:var(--bdr);z-index:0;}
.rp-step:last-child::after{display:none;}
.rp-dot{width:26px;height:26px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:700;z-index:1;border:2px solid;font-family:'DM Mono',monospace;}
.rp-dot.done{background:var(--grn);border-color:var(--grn);color:#0C1620;}
.rp-dot.active{background:var(--gdim);border-color:var(--gold);color:var(--gold);animation:rpp 2.2s infinite;}
.rp-dot.up{background:var(--card2);border-color:var(--dim);color:var(--mut);}
@keyframes rpp{0%,100%{box-shadow:0 0 0 0 rgba(201,152,42,.4)}50%{box-shadow:0 0 0 8px rgba(201,152,42,0)}}
.rp-lbl{font-size:10px;color:var(--mut);margin-top:6px;text-align:center;font-weight:600;letter-spacing:.04em;text-transform:uppercase;line-height:1.3;}
.rp-range{font-size:9px;color:var(--dim);font-weight:400;margin-top:1px;}

/* Phase open */
.poc{background:var(--card);border:1px solid var(--bdr);border-radius:var(--r);margin-bottom:14px;overflow:hidden;}
.poc-stripe{height:3px;}
.poc-body{padding:22px 24px;position:relative;}
.poc-num{font-family:'Cormorant Garamond',serif;font-size:64px;font-weight:700;line-height:1;opacity:.1;position:absolute;right:22px;top:10px;}
.poc-lbl{font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:.08em;font-family:'DM Mono',monospace;margin-bottom:5px;}
.poc-title{font-family:'Cormorant Garamond',serif;font-size:24px;font-weight:700;letter-spacing:.01em;margin-bottom:3px;}
.poc-range{font-size:14px;color:var(--mut);}
.poc-right{display:flex;flex-direction:column;align-items:flex-end;gap:8px;flex-shrink:0;}
.bud{background:var(--gdim);border:1px solid rgba(201,152,42,.3);border-radius:9px;padding:10px 14px;text-align:center;}
.bud-lbl{font-size:9px;color:var(--mut);font-family:'DM Mono',monospace;letter-spacing:.05em;text-transform:uppercase;margin-bottom:2px;}
.bud-val{font-family:'Cormorant Garamond',serif;font-size:18px;font-weight:700;color:var(--gl);}
.phbody{display:grid;grid-template-columns:2fr 1fr 1fr;gap:20px;}
.pbt{font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:.08em;font-family:'DM Mono',monospace;margin-bottom:11px;}
.si{display:flex;align-items:flex-start;gap:9px;padding:7px 0;border-bottom:1px solid var(--bdr);}
.si:last-child{border-bottom:none;}
.scb{width:18px;height:18px;border-radius:5px;border:1.5px solid var(--bdr);flex-shrink:0;margin-top:2px;display:flex;align-items:center;justify-content:center;font-size:10px;cursor:pointer;transition:.15s;}
.scb.chk{background:var(--grn);border-color:var(--grn);color:#0C1620;}
.stxt{font-size:12px;color:var(--sub);line-height:1.55;}
.kchip{background:var(--card2);border-radius:7px;padding:7px 11px;margin-bottom:6px;font-size:12px;color:var(--sub);border-left:2px solid;}
.trow{display:flex;align-items:center;gap:6px;font-size:11px;color:var(--mut);padding:4px 0;border-bottom:1px solid var(--bdr);}
.trow:last-child{border-bottom:none;}

/* Phase accordion */
.pacc{background:var(--card);border:1px solid var(--bdr);border-radius:var(--r);margin-bottom:14px;overflow:hidden;transition:border-color .2s;}
.pacc.open{border-color:var(--dim);}
.pa-hdr{display:flex;align-items:center;gap:14px;padding:18px 22px;cursor:pointer;user-select:none;transition:background .15s;}
.pa-hdr:hover{background:rgba(255,255,255,.025);}
.pa-numbox{width:44px;height:44px;border-radius:10px;display:flex;align-items:center;justify-content:center;font-family:'Cormorant Garamond',serif;font-size:20px;font-weight:700;flex-shrink:0;}
.pa-inf{flex:1;}
.pa-lbl{font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:.08em;font-family:'DM Mono',monospace;margin-bottom:3px;}
.pa-ttl{font-family:'Cormorant Garamond',serif;font-size:20px;font-weight:700;letter-spacing:.01em;}
.pa-range{font-size:13px;color:var(--mut);margin-left:8px;}
.pa-hint{font-size:11px;color:var(--mut);}
.pa-arr{font-size:18px;color:var(--mut);transition:transform .3s;flex-shrink:0;}
.pacc.open .pa-arr{transform:rotate(180deg);}
.pa-body{display:none;padding:0 22px 22px;border-top:1px solid var(--bdr);animation:fi .2s ease;}
.pacc.open .pa-body{display:block;}
@keyframes fi{from{opacity:0;transform:translateY(-4px)}to{opacity:1;transform:translateY(0)}}
.ph34b{display:grid;grid-template-columns:2fr 1fr 1fr;gap:20px;padding-top:20px;}

/* tech */
.tg{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;}
.tc{background:var(--card2);border:1px solid var(--bdr);border-radius:10px;padding:13px;}
.tcat{font-size:10px;font-weight:700;color:var(--gold);text-transform:uppercase;letter-spacing:.07em;margin-bottom:8px;font-family:'DM Mono',monospace;}
.ti{font-size:11px;color:var(--mut);padding:3px 0;border-bottom:1px solid rgba(42,61,82,.7);}
.ti:last-child{border-bottom:none;}

/* PRICING */
.billing-row{display:inline-flex;background:var(--card2);border:1px solid var(--bdr);border-radius:9px;padding:3px;gap:2px;margin-bottom:24px;}
.bo{padding:6px 18px;border-radius:7px;font-size:12px;font-weight:600;cursor:pointer;border:none;background:transparent;color:var(--mut);font-family:'DM Mono',monospace;transition:.18s;letter-spacing:.03em;}
.bo.on{background:var(--gold);color:#0C1620;box-shadow:0 1px 6px rgba(201,152,42,.35);}
.pricing-g{display:grid;grid-template-columns:repeat(3,1fr);gap:17px;margin-bottom:32px;}
.plan-card{background:var(--card);border:1.5px solid var(--bdr);border-radius:16px;padding:24px 20px;position:relative;transition:border-color .2s,transform .2s;}
.plan-card:hover{transform:translateY(-2px);}
.plan-card.pop{border-color:var(--gold);box-shadow:0 0 30px rgba(201,152,42,.12);}
.plan-rec{position:absolute;top:-11px;left:50%;transform:translateX(-50%);background:var(--gold);color:#0C1620;font-size:10px;font-weight:700;padding:3px 14px;border-radius:20px;white-space:nowrap;font-family:'DM Mono',monospace;letter-spacing:.04em;}
.pf2{font-size:12px;color:var(--sub);padding:5px 0;border-bottom:1px solid var(--bdr);display:flex;align-items:flex-start;gap:7px;}
.pf2:last-of-type{border-bottom:none;}
.pbn{width:100%;margin-top:16px;padding:11px;border-radius:9px;font-size:13px;font-family:'Outfit',sans-serif;font-weight:700;cursor:pointer;border:none;transition:all .15s;}
.cmp-table{width:100%;border-collapse:collapse;font-size:13px;min-width:540px;}
.cmp-table th{padding:9px 13px;font-size:10px;color:var(--mut);text-transform:uppercase;letter-spacing:.06em;border-bottom:2px solid var(--bdr);text-align:left;}
.cmp-table td{padding:10px 13px;border-bottom:1px solid var(--bdr);}
.cmp-table tr:last-child td{border-bottom:none;}
.chl td{background:var(--bld)!important;}.chl td:first-child{color:var(--blu);font-weight:700;}
.cy{color:var(--grn)!important;font-weight:700;}.cn{color:var(--red)!important;}

/* ════════════════════════════════════════
   KICKSTART / UPFRONT SECTION
════════════════════════════════════════ */
.ks-hero{
  background:linear-gradient(135deg,#0D1C2E 0%,#162030 60%,#0F2238 100%);
  border:1px solid var(--bdr);border-radius:var(--r);
  padding:32px 30px;margin-bottom:28px;
  position:relative;overflow:hidden;
}
.ks-hero::before{content:'';position:absolute;top:-60px;right:-60px;width:240px;height:240px;border-radius:50%;background:radial-gradient(circle,rgba(201,152,42,.08),transparent 70%);pointer-events:none;}
.ks-eyebrow{display:inline-flex;align-items:center;gap:7px;background:var(--gdim);border:1px solid rgba(201,152,42,.35);border-radius:20px;padding:5px 14px;font-size:11px;color:var(--gl);font-weight:700;font-family:'DM Mono',monospace;letter-spacing:.05em;margin-bottom:16px;}
.ks-title{font-family:'Cormorant Garamond',serif;font-size:32px;font-weight:700;letter-spacing:.01em;margin-bottom:10px;line-height:1.15;}
.ks-title span{color:var(--gold);}
.ks-desc{font-size:14px;color:var(--sub);max-width:620px;line-height:1.7;margin-bottom:22px;}
.ks-why{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:22px;}
.ks-why-item{background:rgba(255,255,255,.03);border:1px solid var(--bdr);border-radius:10px;padding:14px 16px;}
.ks-why-icon{font-size:22px;margin-bottom:8px;}
.ks-why-title{font-size:13px;font-weight:600;margin-bottom:4px;}
.ks-why-desc{font-size:11px;color:var(--mut);line-height:1.55;}

.ks-divider{display:flex;align-items:center;gap:14px;margin:28px 0;}
.ks-divider-line{flex:1;height:1px;background:var(--bdr);}
.ks-divider-label{font-size:11px;font-weight:700;color:var(--mut);text-transform:uppercase;letter-spacing:.08em;font-family:'DM Mono',monospace;white-space:nowrap;}

/* UPFRONT PACKAGES */
.ks-pkg{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-bottom:28px;}
.kp-card{
  background:var(--card);border:1.5px solid var(--bdr);border-radius:16px;
  padding:24px 20px;position:relative;transition:all .2s;
}
.kp-card:hover{transform:translateY(-3px);border-color:var(--dim);}
.kp-card.featured{border-color:var(--gold);box-shadow:0 4px 30px rgba(201,152,42,.15);}
.kp-feat-badge{position:absolute;top:-11px;left:50%;transform:translateX(-50%);background:var(--gold);color:#0C1620;font-size:10px;font-weight:700;padding:3px 14px;border-radius:20px;white-space:nowrap;font-family:'DM Mono',monospace;letter-spacing:.04em;}
.kp-plan-link{display:inline-block;margin-bottom:12px;padding:4px 10px;border-radius:20px;font-size:10px;font-weight:700;font-family:'DM Mono',monospace;letter-spacing:.04em;}
.kp-name{font-family:'Cormorant Garamond',serif;font-size:20px;font-weight:700;margin-bottom:4px;}
.kp-subtitle{font-size:12px;color:var(--mut);margin-bottom:18px;line-height:1.4;}
.kp-price-block{margin-bottom:20px;}
.kp-price-label{font-size:10px;color:var(--mut);text-transform:uppercase;letter-spacing:.07em;font-family:'DM Mono',monospace;margin-bottom:4px;}
.kp-price{font-family:'Cormorant Garamond',serif;font-size:42px;font-weight:700;line-height:1;}
.kp-price-note{font-size:12px;color:var(--mut);margin-top:4px;}
.kp-divider{border:none;border-top:1px solid var(--bdr);margin:18px 0;}
.kp-includes-lbl{font-size:10px;font-weight:700;color:var(--mut);text-transform:uppercase;letter-spacing:.07em;font-family:'DM Mono',monospace;margin-bottom:10px;}
.kp-feat{display:flex;align-items:flex-start;gap:8px;font-size:12px;color:var(--sub);padding:5px 0;border-bottom:1px solid var(--bdr);}
.kp-feat:last-of-type{border-bottom:none;}
.kp-feat .ck{color:var(--grn);flex-shrink:0;margin-top:1px;font-size:13px;}
.kp-cta{width:100%;margin-top:18px;padding:12px;border-radius:10px;font-size:14px;font-family:'Outfit',sans-serif;font-weight:700;cursor:pointer;border:none;transition:all .15s;letter-spacing:.01em;}

/* TERMS BOX */
.ks-terms{background:var(--card2);border:1px solid var(--bdr);border-radius:var(--r);padding:22px 24px;margin-bottom:28px;}
.kt-title{font-family:'Cormorant Garamond',serif;font-size:18px;font-weight:700;margin-bottom:14px;}
.kt-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;}
.kt-item{display:flex;align-items:flex-start;gap:10px;padding:12px 14px;background:var(--card);border:1px solid var(--bdr);border-radius:10px;}
.kt-icon{font-size:20px;flex-shrink:0;margin-top:2px;}
.kt-label{font-size:13px;font-weight:600;margin-bottom:3px;}
.kt-desc{font-size:11px;color:var(--mut);line-height:1.5;}

/* CTA BANNER */
.ks-cta-banner{
  background:linear-gradient(135deg,#1A2C1A,#0D2018);
  border:1px solid rgba(45,212,160,.25);border-radius:var(--r);
  padding:26px 28px;display:flex;align-items:center;justify-content:space-between;gap:20px;
}
.ks-cta-text h3{font-family:'Cormorant Garamond',serif;font-size:22px;font-weight:700;margin-bottom:5px;}
.ks-cta-text p{font-size:13px;color:var(--sub);max-width:480px;}
.ks-cta-btns{display:flex;gap:10px;flex-shrink:0;flex-wrap:wrap;}
.ks-wa-btn{background:#25D366;color:#fff;padding:10px 20px;border-radius:9px;font-size:13px;font-weight:700;cursor:pointer;border:none;font-family:'Outfit',sans-serif;transition:all .15s;display:flex;align-items:center;gap:7px;}
.ks-wa-btn:hover{background:#22C55E;transform:translateY(-1px);}
.ks-email-btn{background:transparent;color:var(--grn);border:1.5px solid rgba(45,212,160,.4)!important;padding:10px 20px;border-radius:9px;font-size:13px;font-weight:700;cursor:pointer;font-family:'Outfit',sans-serif;transition:all .15s;}
.ks-email-btn:hover{background:var(--gnd);}

/* SERMON / VOL / etc */
.ser-card{background:var(--card);border:1px solid var(--bdr);border-radius:var(--r);padding:16px;cursor:pointer;transition:border-color .2s,transform .2s;}
.ser-card:hover{border-color:var(--gold);transform:translateY(-2px);}
.ser-thumb{height:88px;background:var(--card2);border-radius:9px;display:flex;align-items:center;justify-content:center;font-size:34px;margin-bottom:12px;border:1px solid var(--bdr);}
.vcrd{display:flex;align-items:center;gap:12px;padding:13px 15px;background:var(--card);border:1px solid var(--bdr);border-radius:11px;transition:border-color .15s;}
.vcrd:hover{border-color:var(--dim);}
.grpcrd,.prcrd,.evcrd{background:var(--card);border:1px solid var(--bdr);border-radius:var(--r);padding:17px 19px;transition:border-color .15s;}
.grpcrd:hover,.prcrd:hover{border-color:var(--dim);}
.evcrd{border-left-width:3.5px;}
</style>
</head>
<body>
<div id="wrap">

<!-- ══════ SIDEBAR ══════ -->
<aside id="sidebar">
  <div class="sb-hdr">
    <div style="display:flex;align-items:center;overflow:hidden">
      <div class="sb-logo">⛪</div>
      <div class="sh">
        <div class="sb-name">Christian Church</div>
        <div class="sb-loc">Kolwezi · RD Congo</div>
      </div>
    </div>
    <button class="sb-tog sh" onclick="toggleSB()">‹</button>
  </div>
  <div class="sb-pastors sh">
    <div class="p-row"><div class="pav">DT</div><div><div class="pnm">Pasteur Djo Tshibal</div><div class="prl" id="pr1">Pasteur Principal</div></div></div>
    <div class="p-row"><div class="pav">PT</div><div><div class="pnm">Maman Patricia Tshibal</div><div class="prl" id="pr2">Pasteure Co-Fondatrice</div></div></div>
    <div class="phase-pill" id="ppill">Phase 2 · 601 Membres</div>
  </div>
  <nav class="sb-nav" id="sbnav"></nav>
  <div class="sb-foot sh">
    <div class="sb-dlbl" id="dlbl">Docs Stratégiques</div>
    <a href="growth-phase-1-2.html" target="_blank" class="doc-lnk">📄 Phase 1 &amp; 2</a>
    <a href="growth-phase-3-4.html" target="_blank" class="doc-lnk">📄 Phase 3 &amp; 4</a>
  </div>
</aside>

<!-- ══════ MAIN ══════ -->
<div id="main">
  <div id="topbar">
    <div class="tb-l">
      <button class="tb-hbg" onclick="openMob()">☰</button>
      <span class="tb-ttl" id="tbtitle">Tableau de Bord</span>
    </div>
    <div class="tb-r">
      <div class="lang-sw" title="Langue / Language">
        <button class="lo on" id="lo-fr" onclick="setLang('fr')">FR</button>
        <button class="lo" id="lo-en" onclick="setLang('en')">EN</button>
      </div>
      <div class="tb-av">DT</div>
    </div>
  </div>
  <div id="content"></div>
</div>
</div>

<div id="mob-ov" onclick="closeMob()"></div>
<nav id="bot-nav"><div style="display:flex;justify-content:space-around" id="botnav"></div></nav>

<script>
/* ══════════ TRANSLATIONS ══════════ */
const L={
fr:{
  pages:['dashboard','members','sermons','giving','groups','events','prayer','campaigns','volunteers','roadmap','pricing','kickstart'],
  nav:['Tableau de Bord','Membres','Sermons','Dons','Cellules','Événements','Prière','Campagnes','Bénévoles','Croissance','Tarification','Démarrage'],
  icons:['⛪','👥','🎙️','💰','🤝','📅','🙏','📣','🌟','🗺️','💎','🚀'],
  pr1:'Pasteur Principal',pr2:'Pasteure Co-Fondatrice',ppill:'Phase 2 · 601 Membres',dlbl:'Docs Stratégiques',
  dashSub:'Christian Church — Kolwezi, RDC',
  m1:'Total Membres',m2:'Spectateurs En Ligne',m3:'Dons du Mois',m4:'Cellules Actives',
  s1:'↑ 18% ce mois',s2:'↑ 32% ce mois',s3:'↑ 22% vs dernier',s4:'89 membres',
  al:['Croissance Présence — 2024','Santé de la Congrégation','Dons & Offrandes — 2024','Actions de la Semaine'],
  aa:['6 premiers visiteurs à relancer','Campagne de Noël — brouillon prêt','12 nouvelles demandes de prière','Cellule Jeunes Pros : capacité atteinte','Dons fin d\'année — 3 semaines restantes','Sermon : 3 100 vues — boostez-le !'],
  rl:['Piliers','Réguliers','Occasionnels','Nouveaux'],
  memberSub:'601 membres — Kolwezi & Diaspora mondiale',addM:'+ Ajouter Membre',
  srchPh:'🔍  Chercher par nom, statut ou étiquette...',
  mCols:['Membre','Depuis','Statut','Cellules','Dons','Étiquettes'],
  stmap:{'Core Leader':'Pilier','Active':'Actif','Growing':'En Croissance','New Convert':'Nouveau Converti','New Visitor':'Premier Visiteur'},
  serSub:'Bibliothèque de sermons & podcasts',upBtn:'+ Charger Sermon',
  givSub:'Orange Money · Airtel Money · PayPal · Espèces',ncBtn:'+ Nouvelle Campagne',
  topM:'Méthodes de Don',topD:'Principaux Donateurs',
  grpSub:'Moteur de discipulat et de croissance',ngBtn:'+ Nouvelle Cellule',led:'Dirigé par',
  evtSub:'Calendrier — gérez tous les événements',neBtn:'+ Créer Événement',reg:'inscrits',
  pryBg:'🙏 Prier',pryDn:'✓ Prié',pSub:'Intercession communautaire',npBtn:'+ Soumettre',
  campSub:'Email · SMS WhatsApp · Notifications push',ncBtn2:'+ Nouvelle Campagne',
  cCols:['Campagne','Canal','Statut','Envoyés','Ouverture','Clics'],
  volSub:'Construire et déployer vos équipes de service',avBtn:'+ Ajouter Bénévole',
  roadSub:'Kolwezi → Katanga → Continent',
  curM:'Membres Actuels',ph2G:'Objectif Phase 2',tl:'Horizon 10K',rt:'Outils',
  techT:'🛠️ Stack Technologique Complet — Optimisé RDC',
  phDone:'✓ Complété',phAct:'● En Cours',phUp:'À venir',c2e:'Cliquer pour développer',
  kS:'Étapes Clés',kK:'Indicateurs',kT:'Outils',kB:'Budget estimé',
  priceSub:'Conçu pour l\'Afrique — qualité mondiale, prix accessibles',
  priceNote:'💡 Économisez 2 mois avec le paiement annuel · Orange Money · Airtel · PayPal · Visa',
  monthly:'Mensuel',yearly:'Annuel (−2 mois)',perMo:'/ mois',perYr:'/ an',
  choosePlan:'Choisir Ce Plan',popL:'⭐ Recommandé',incl:'Inclus :',
  cmpT:'Comparaison internationale',cmpN:'USA/Canada équivalent : $500–$800/mois. Économisez jusqu\'à 81%.',
  cmpCols:['Solution','Prix/mois','ChMS','App','Orange Money','Dons','Coaching'],
  vw:'Voir',shr:'Partager',hlt:'Santé',
  // KICKSTART
  ksTtl:'Investissement Requis <span>Avant de Commencer</span>',
  ksDesc:'Avant de démarrer votre projet, un paiement initial unique est requis. Ce montant couvre la stratégie, la configuration complète de la plateforme, la formation de votre équipe et les 30 premiers jours d\'accompagnement intensif. Aucune surprise — tout est inclus.',
  ksEy:'Paiement Unique · Avant Démarrage',
  ksWhy1T:'Stratégie incluse',ksWhy1D:'Session de 2h pour définir votre plan des 90 premiers jours.',
  ksWhy2T:'Configuration complète',ksWhy2D:'Nous configurons tout — site, dons, WhatsApp, email, outils.',
  ksWhy3T:'Formation de l\'équipe',ksWhy3D:'Vos leaders sont formés et opérationnels avant notre départ.',
  ksUpT:'Choisissez Votre Forfait de Démarrage',
  ksUpN:'Paiement unique avant démarrage des travaux',
  kp1Name:'Forfait Semence',kp1Sub:'Pour les petites églises qui démarrent leur présence numérique.',
  kp1PL:'Paiement unique',kp1PN:'Pour les plans de 50–300 membres',
  kp1F:['Audit complet de votre situation actuelle','Configuration site web bilingue (FR/EN)','Page de dons mobiles (Orange Money, Airtel)','Mise en place WhatsApp Business','Configuration YouTube + réseaux sociaux','Formation de 2 admins (4h en ligne ou présentiel)','30 jours de support prioritaire inclus','Documentation complète remise à l\'équipe'],
  kp1CTA:'Démarrer avec Semence',
  kp2Name:'Forfait Récolte',kp2Sub:'Pour les églises en croissance qui veulent un système complet.',
  kp2PL:'Paiement unique',kp2PN:'Pour les plans de 300–1 500 membres',
  kp2F:['Tout du Forfait Semence','Configuration ChMS (Breeze ou Planning Center)','Importation des données membres existantes','Configuration des dons récurrents automatiques','Mise en place des campagnes email & WhatsApp','Configuration bibliothèque sermons + podcast','Formation complète de l\'équipe (8h)','60 jours de support prioritaire inclus','Appel coaching mensuel (3 mois inclus)'],
  kp2CTA:'Démarrer avec Récolte',
  kp3Name:'Forfait Mouvement',kp3Sub:'Pour les grandes églises qui veulent une transformation complète.',
  kp3PL:'Paiement unique',kp3PN:'Pour les plans de 1 500–10 000+ membres',
  kp3F:['Tout du Forfait Récolte','Configuration application mobile (iOS & Android)','Mise en place gestion multi-sites','Configuration studio de diffusion en direct','Portail membres diaspora internationale','Formation complète équipe staff (16h)','90 jours de support dédié inclus','Appel coaching hebdomadaire (3 mois inclus)','Rapport de performance mensuel'],
  kp3CTA:'Démarrer avec Mouvement',
  kpFeatBadge:'⭐ Le Plus Choisi',
  ktT:'Conditions de Paiement & Engagements',
  kt1T:'Paiement sécurisé',kt1D:'Orange Money, Airtel Money, PayPal, virement bancaire, Visa. Reçu officiel émis immédiatement.',
  kt2T:'Démarrage sous 48h',kt2D:'Une fois le paiement confirmé, les travaux démarrent dans les 48 heures ouvrables.',
  kt3T:'Garantie 14 jours',kt3D:'Si vous n\'êtes pas satisfait après la livraison, nous remboursons intégralement. Aucune question posée.',
  kt4T:'Propriété totale',kt4D:'Tout ce que nous construisons vous appartient à 100%. Codes, accès, domaines — tout est transféré.',
  ksCTA_T:'Prêt à Démarrer ?',ksCTA_D:'Envoyez-nous un message et nous vous envoyons votre devis personnalisé dans les 24 heures.',
  ksWA:'WhatsApp',ksEM:'Email',
},
en:{
  pages:['dashboard','members','sermons','giving','groups','events','prayer','campaigns','volunteers','roadmap','pricing','kickstart'],
  nav:['Dashboard','Members','Sermons','Giving','Groups','Events','Prayer','Campaigns','Volunteers','Growth','Pricing','Get Started'],
  icons:['⛪','👥','🎙️','💰','🤝','📅','🙏','📣','🌟','🗺️','💎','🚀'],
  pr1:'Lead Pastor',pr2:'Co-Founding Pastor',ppill:'Phase 2 · 601 Members',dlbl:'Strategy Docs',
  dashSub:'Christian Church — Kolwezi, DRC',
  m1:'Total Members',m2:'Online Viewers',m3:'Monthly Giving',m4:'Active Groups',
  s1:'↑ 18% this month',s2:'↑ 32% this month',s3:'↑ 22% vs last',s4:'89 members',
  al:['Attendance Growth — 2024','Congregation Health','Giving Overview — 2024','This Week\'s Actions'],
  aa:['6 first-time visitors to follow up','Christmas campaign — draft ready','12 new prayer requests this week','Young Professionals group at capacity','Year-end giving push — 3 weeks left','Sermon at 3,100 views — boost it!'],
  rl:['Core Leaders','Regular','Occasional','New'],
  memberSub:'601 total members — Kolwezi & Global Diaspora',addM:'+ Add Member',
  srchPh:'🔍  Search by name, stage, or tag...',
  mCols:['Member','Since','Stage','Groups','Giving','Tags'],
  stmap:{'Core Leader':'Core Leader','Active':'Active','Growing':'Growing','New Convert':'New Convert','New Visitor':'New Visitor'},
  serSub:'Sermon library & podcast hub',upBtn:'+ Upload Sermon',
  givSub:'Orange Money · Airtel Money · PayPal · Cash',ncBtn:'+ New Campaign',
  topM:'Top Giving Methods',topD:'Top Donors This Month',
  grpSub:'Discipleship and growth engine',ngBtn:'+ New Group',led:'Led by',
  evtSub:'Calendar — manage all church events',neBtn:'+ Create Event',reg:'registered',
  pryBg:'🙏 Pray',pryDn:'✓ Prayed',pSub:'Community intercession',npBtn:'+ Submit',
  campSub:'Email · WhatsApp SMS · Push notifications',ncBtn2:'+ New Campaign',
  cCols:['Campaign','Channel','Status','Sent','Opened','Clicks'],
  volSub:'Build and deploy your serve teams',avBtn:'+ Add Volunteer',
  roadSub:'Kolwezi → Katanga → Continent',
  curM:'Current Members',ph2G:'Phase 2 Goal',tl:'10K Timeline',rt:'Tools',
  techT:'🛠️ Full Tech Stack — DRC Optimized',
  phDone:'✓ Complete',phAct:'● Active',phUp:'Upcoming',c2e:'Click to expand',
  kS:'Key Steps',kK:'KPI Targets',kT:'Tools',kB:'Est. budget',
  priceSub:'Designed for Africa — world-class quality, accessible prices',
  priceNote:'💡 Save 2 months with annual billing · Orange Money · Airtel · PayPal · Visa',
  monthly:'Monthly',yearly:'Annual (save 2mo)',perMo:'/ month',perYr:'/ year',
  choosePlan:'Choose This Plan',popL:'⭐ Recommended',incl:'Included:',
  cmpT:'International comparison',cmpN:'USA/Canada equivalent: $500–$800/month. Save up to 81%.',
  cmpCols:['Solution','Price/mo','ChMS','App','Orange Money','Giving','Coaching'],
  vw:'View',shr:'Share',hlt:'Health',
  ksTtl:'Required Investment <span>Before We Begin</span>',
  ksDesc:'Before your project starts, a one-time upfront payment is required. This covers strategy, full platform setup, team training, and the first 30 days of intensive support. No surprises — everything is included.',
  ksEy:'One-Time Payment · Before Work Begins',
  ksWhy1T:'Strategy included',ksWhy1D:'2-hour session to map your first 90-day action plan.',
  ksWhy2T:'Full setup done',ksWhy2D:'We configure everything — website, giving, WhatsApp, email, tools.',
  ksWhy3T:'Team trained',ksWhy3D:'Your leaders are trained and operational before we hand over.',
  ksUpT:'Choose Your Kickstart Package',
  ksUpN:'One-time payment required before work begins',
  kp1Name:'Seed Kickstart',kp1Sub:'For small churches launching their digital presence.',
  kp1PL:'One-time payment',kp1PN:'For 50–300 member plans',
  kp1F:['Full audit of your current situation','Bilingual website setup (FR/EN)','Mobile giving page (Orange Money, Airtel)','WhatsApp Business setup','YouTube + social media setup','Training for 2 admins (4h online or in-person)','30 days priority support included','Full documentation handed to your team'],
  kp1CTA:'Start with Seed',
  kp2Name:'Harvest Kickstart',kp2Sub:'For growing churches that want a complete system.',
  kp2PL:'One-time payment',kp2PN:'For 300–1,500 member plans',
  kp2F:['Everything in Seed Kickstart','ChMS setup (Breeze or Planning Center)','Existing member data import','Recurring giving automation setup','Email & WhatsApp campaign setup','Sermon library + podcast configuration','Full team training (8h)','60 days priority support included','Monthly coaching call (3 months included)'],
  kp2CTA:'Start with Harvest',
  kp3Name:'Movement Kickstart',kp3Sub:'For large churches seeking a full transformation.',
  kp3PL:'One-time payment',kp3PN:'For 1,500–10,000+ member plans',
  kp3F:['Everything in Harvest Kickstart','Mobile app setup (iOS & Android)','Multi-site management setup','Live streaming studio configuration','International diaspora member portal','Full staff team training (16h)','90 days dedicated support included','Weekly coaching call (3 months included)','Monthly performance report'],
  kp3CTA:'Start with Movement',
  kpFeatBadge:'⭐ Most Popular',
  ktT:'Payment Terms & Commitments',
  kt1T:'Secure payment',kt1D:'Orange Money, Airtel Money, PayPal, wire transfer, Visa. Official receipt issued immediately.',
  kt2T:'Work starts within 48h',kt2D:'Once payment is confirmed, work begins within 48 business hours.',
  kt3T:'14-day guarantee',kt3D:'If you\'re not satisfied after delivery, we refund in full. No questions asked.',
  kt4T:'Full ownership',kt4D:'Everything we build is 100% yours. Code, access, domains — all transferred to you.',
  ksCTA_T:'Ready to Start?',ksCTA_D:'Send us a message and we\'ll send your personalized quote within 24 hours.',
  ksWA:'WhatsApp',ksEM:'Email',
}};

/* KICKSTART PRICES (shown in each currency block) */
const KS_PRICES={ seed:597, harvest:997, movement:1997 };

/* ══════════════════════════════════════
   STATIC DATA
══════════════════════════════════════ */
const MBR=[
  {n:'Marcus & Priya Johnson',j:'2021',s:'Core Leader',g:2,giv:'$680/mo',tags:['Dîme','Leader'],av:'MJ'},
  {n:'DeShawn Williams',j:'2022',s:'Active',g:1,giv:'$220/mo',tags:['Jeunesse','En ligne'],av:'DW'},
  {n:'Amara Kabongo',j:'2023',s:'New Convert',g:1,giv:'$80/mo',tags:['Baptisé'],av:'AK'},
  {n:'Roberto & Ana Fuentes',j:'2020',s:'Core Leader',g:3,giv:'$1 100/mo',tags:['Dîme','Diacre'],av:'RF'},
  {n:'Aisha Okonkwo',j:'2023',s:'Growing',g:2,giv:'$150/mo',tags:['Cellule'],av:'AO'},
  {n:'Jean-Paul & Marie Mukendi',j:'2024',s:'New Visitor',g:0,giv:'$0',tags:['1ère Visite'],av:'JM'},
  {n:'Grace Nakamura',j:'2022',s:'Active',g:1,giv:'$340/mo',tags:['Enfants','Dîme'],av:'GN'},
  {n:'James Osei',j:'2021',s:'Core Leader',g:2,giv:'$520/mo',tags:['Ancien','Dîme'],av:'JO'},
];
const SRM=[
  {title:'Foi Inébranlable',series:'Bâti pour Durer',date:'8 Déc',views:2841,dur:'42:18',icon:'🔥'},
  {title:'La Vie en Abondance',series:'Plus que Suffisant',date:'1 Déc',views:2214,dur:'38:44',icon:'💧'},
  {title:'Rêve à Nouveau',series:'Éveillé',date:'24 Nov',views:3102,dur:'45:09',icon:'⭐'},
  {title:'Marcher dans le But',series:'Éveillé',date:'17 Nov',views:1987,dur:'39:22',icon:'🚶'},
  {title:'Le Pouvoir d\'une Voix',series:'Impact',date:'10 Nov',views:2673,dur:'41:55',icon:'🎯'},
  {title:'Enraciné & Fondé',series:'Bâti pour Durer',date:'3 Nov',views:1843,dur:'36:40',icon:'🌳'},
];
const GRP=[
  {n:'Cellule Nord Kolwezi',l:'Past. Mike',m:14,mt:'Mar 19h',t:'Quartier',h:92},
  {n:'Jeunes Professionnels',l:'Aisha O.',m:11,mt:'Mer 18h30',t:'Âge',h:88},
  {n:'Couples Mariés',l:'Roberto F.',m:16,mt:'Ven 19h',t:'Vie',h:95},
  {n:'Hommes Valeureux',l:'James O.',m:9,mt:'Sam 7h',t:'Genre',h:79},
  {n:'Femmes de Grâce',l:'Grace N.',m:18,mt:'Jeu 18h',t:'Genre',h:91},
  {n:'Campus En Ligne',l:'DeShawn W.',m:34,mt:'Dim 12h',t:'Digital',h:74},
];
const EVT=[
  {t:'Culte Dominical',d:'15 Déc',h:'9h & 11h',type:'Hebdomadaire',r:312,cap:400,c:'#C9982A'},
  {t:'Service de Noël',d:'24 Déc',h:'17h & 19h',type:'Spécial',r:487,cap:600,c:'#2DD4A0'},
  {t:'Nuit du Nouvel An',d:'31 Déc',h:'22h',type:'Spécial',r:203,cap:350,c:'#9B7FE8'},
  {t:'Petit-Déjeuner Hommes',d:'21 Déc',h:'8h',type:'Ministère',r:42,cap:60,c:'#5B9EE8'},
  {t:'Nuit de Louange',d:'19 Déc',h:'19h',type:'Spécial',r:156,cap:250,c:'#E87070'},
  {t:'Classe Nouveaux Membres',d:'22 Déc',h:'14h',type:'Croissance',r:28,cap:40,c:'#E8B84B'},
];
const PRY=[
  {n:'Sarah K.',req:'Guérison pour la chirurgie de ma mère la semaine prochaine.',t:'2h',cat:'Guérison',p:24},
  {n:'Anonyme',req:'Que Dieu ouvre une porte d\'emploi. Au chômage depuis 4 mois.',t:'4h',cat:'Provision',p:41},
  {n:'Jean-Paul M.',req:'Première visite — cette église ressemble à la maison.',t:'6h',cat:'Connexion',p:18},
  {n:'Marcus J.',req:'Percée pour la nouvelle initiative d\'évangélisation.',t:'1j',cat:'Ministère',p:67},
  {n:'DeShawn W.',req:'Protection pour notre jeunesse face aux pressions.',t:'1j',cat:'Jeunesse',p:53},
  {n:'Aisha O.',req:'Faveur de Dieu sur mon entreprise. Lancement le 1er février.',t:'2j',cat:'Business',p:39},
];
const CAM=[
  {n:'Série Invitation de Noël',s:'Actif',sent:1243,open:67,clk:31,ch:'Email + SMS'},
  {n:'Accueil Nouveaux Membres',s:'Actif',sent:28,open:89,clk:72,ch:'Séquence Email'},
  {n:'Don de Fin d\'Année',s:'Brouillon',sent:0,open:0,clk:0,ch:'Email + WhatsApp'},
  {n:'Suivi Premier Visiteur',s:'Actif',sent:156,open:78,clk:44,ch:'SMS + Email'},
  {n:'Dimanche Vision Janvier',s:'Planifié',sent:0,open:0,clk:0,ch:'Tous Canaux'},
];
const VOL=[
  {n:'Roberto F.',team:'Louange',role:"Chef d'Adoration",hrs:18,rat:98,badge:'⭐'},
  {n:'Grace N.',team:'Enfants',role:'Dir. Enfants',hrs:22,rat:96,badge:'⭐'},
  {n:'DeShawn W.',team:'Médias',role:'Livestream',hrs:14,rat:91,badge:null},
  {n:'Aisha O.',team:'Accueil',role:'Exp. Visiteur',hrs:10,rat:94,badge:null},
  {n:'James O.',team:'Sécurité',role:'Chef Sécurité',hrs:8,rat:89,badge:null},
  {n:'Marcus J.',team:'Évangélisation',role:'Chef Outreach',hrs:16,rat:97,badge:'⭐'},
  {n:'Sarah K.',team:'Prière',role:'Équipe Prière',hrs:6,rat:95,badge:null},
  {n:'Jean-Paul M.',team:'Accueil',role:'Accueillant',hrs:4,rat:87,badge:'🌱'},
];
const PHS=[
  {ph:'Phase 1',range:'100 → 300',color:'#5B9EE8',cdim:'rgba(91,158,232,0.14)',done:true,
   tFr:'Fondation',tEn:'Foundation',tmFr:'Mois 1–6',tmEn:'Months 1–6',
   dFr:'Construire une présence numérique solide et activer les premières cellules.',
   dEn:'Build a solid digital presence and launch first small groups.',
   fr:['Lancer le site web bilingue (WordPress FR/EN)','Activer les dons mobiles (Orange Money, Airtel, PayPal)','Chaîne YouTube + Podcast (Spotify, Apple)','WhatsApp Business — annonces & prière','Liste email Mailchimp (100 → 500 abonnés)','4–6 premières cellules (quartier, âge, genre)','Suivi automatique des nouveaux visiteurs (24h)','Facebook + Instagram + TikTok actifs'],
   en:['Launch bilingual website (WordPress FR/EN)','Activate mobile giving (Orange Money, Airtel, PayPal)','YouTube channel + Podcast (Spotify, Apple)','Community WhatsApp Business — announcements & prayer','Free Mailchimp email list (100 → 500 subscribers)','4–6 first small groups (neighborhood, age, gender)','First-timer follow-up automation (within 24h)','Facebook + Instagram + TikTok active'],
   kpFr:['Présence : 300/semaine','YouTube : 1 000 abonnés','Cellules : 4–6 actives','Rétention : 70%+'],
   kpEn:['Attendance: 300/week','YouTube: 1,000 subscribers','Groups: 4–6 active','Retention: 70%+'],
   tools:['WordPress + Hostinger ($3/mo)','Orange Money (Gratuit)','Airtel Money (Gratuit)','Mailchimp (Gratuit)','OBS + YouTube Live (Gratuit)','Google Workspace ($6/mo)'],
   budget:'$9 – $18 / mois'},
  {ph:'Phase 2',range:'300 → 1 000',color:'#C9982A',cdim:'rgba(201,152,42,0.14)',active:true,
   tFr:'Moteur de Croissance',tEn:'Growth Engine',tmFr:'Mois 7–18 · EN COURS',tmEn:'Months 7–18 · ACTIVE',
   dFr:'Systématiser, automatiser, scaler : ChMS, campus en ligne, contenu viral, dons récurrents.',
   dEn:'Systemize, automate, scale: ChMS, online campus, viral content, recurring giving.',
   fr:['Déployer un ChMS (Breeze ou Planning Center)','Lancer le campus en ligne — 500+ membres réguliers','Premier sermon viral — objectif 100 000 vues','Dons récurrents mensuels automatiques','2 grands événements par an','50+ bénévoles formés et déployés (8 équipes)','Ministère enfants & jeunesse structuré','École de leadership interne lancée','Programme de partenariat mensuel (VIP)'],
   en:['Deploy ChMS (Breeze or Planning Center)','Launch online campus — 500+ regular members','First viral sermon — target 100,000 views','Automatic monthly recurring giving','2 major events/year (Night of Power, Vision Day)','50+ volunteers trained & deployed (8 teams)','Children & youth ministry structure','Internal leadership school launched','Monthly partnership program (VIP)'],
   kpFr:['Membres : 1 000','Campus en ligne : 500','Taux de dîme : 35%+','Budget : $5 000+/mo'],
   kpEn:['Members: 1,000','Online campus: 500','Tithe rate: 35%+','Budget: $5,000+/mo'],
   tools:['Breeze ChMS ($72/mo)','StreamYard ($49/mo)','Tithe.ly ($29/mo)','CapCut Pro ($10/mo)','Buffer ($18/mo)','Zapier ($20/mo)'],
   budget:'$200 – $400 / mois'},
  {ph:'Phase 3',range:'1 000 → 3 000',color:'#2DD4A0',cdim:'rgba(45,212,160,0.14)',
   tFr:'Préparation Multi-Sites',tEn:'Multi-Site Preparation',tmFr:'Mois 19–36',tmEn:'Months 19–36',
   dFr:'Embaucher une équipe, lancer un 2e service, conquérir la diaspora, lancer l\'application.',
   dEn:'Hire a team, launch 2nd service, reach global diaspora, launch mobile app.',
   fr:['Recruter pasteur associé + équipe (5–8 personnes)','Lancer un 2e service dominical','Lancer l\'application mobile (Subsplash)','Clips de sermons à 1M+ vues cumulées','Campagne du Fonds de Construction','École de Ministère formelle','Repérage du 2e site (Lubumbashi, Likasi…)','Studio de production professionnel'],
   en:['Hire associate pastor + team (5–8 people)','Launch 2nd Sunday service','Launch church mobile app (Subsplash)','Sermon clips at 1M+ cumulative views','Building Fund campaign','Formal Ministry School','Scout 2nd location (Lubumbashi, Likasi…)','Professional production studio'],
   kpFr:['Membres : 3 000','Staff : 5–8 temps plein','App : 10K téléchargements','YouTube : 100K vues/mo'],
   kpEn:['Members: 3,000','Staff: 5–8 full-time','App: 10K downloads','YouTube: 100K views/mo'],
   tools:['Subsplash App ($199/mo)','Planning Center ($199/mo)','DaVinci Resolve (Gratuit)','Adobe Premiere ($55/mo)','Blackmagic ATEM (~$1K)','Hootsuite ($99/mo)'],
   budget:'$600 – $1 000 / mois'},
  {ph:'Phase 4',range:'3 000 → 10 000+',color:'#9B7FE8',cdim:'rgba(155,127,232,0.14)',
   tFr:'Le Mouvement',tEn:'The Movement',tmFr:'Mois 37–60',tmEn:'Months 37–60',
   dFr:'Devenir une force nationale et continentale : multi-sites, conférence annuelle, impact sur les nations.',
   dEn:'Become a national and continental force: multi-site, annual conference, impact on nations.',
   fr:['Lancer 2–4 sites multi-sites (villes du Katanga)','Présence médiatique nationale (TV, radio)','Livre du Pasteur Djo publié (FR & EN)','Conférence annuelle — 1 000+ participants','Réseau d\'églises planté','Application à 50K téléchargements','Staff : 20–35 personnes','Impact social : ONG, école, clinique','Christian Church = marque spirituelle nationale'],
   en:['Launch 2–4 multi-site locations (Katanga cities)','National media presence (TV, Christian radio)','Pastor Djo\'s book published (FR & EN)','Annual conference — 1,000+ attendees','Church planting network','App reaches 50K downloads','Staff team of 20–35 people','Social impact: NGO, school, clinic','Christian Church = national spiritual brand'],
   kpFr:['Membres : 10 000+','Sites : 2–4 villes','App : 50K téléchargements','Abonnés en ligne : 500K'],
   kpEn:['Members: 10,000+','Locations: 2–4 cities','App: 50K downloads','Online followers: 500K'],
   tools:['Planning Center Multi-Site ($299/mo)','Subsplash Pro ($299/mo)','Salesforce NPSP (Gratuit)','Zoom Webinar ($149/mo)','Custom API ($5K+)','QuickBooks ($30/mo)'],
   budget:'$1 500 – $3 000 / mois'},
];
const PLANS={
fr:[
  {icon:'🌱',name:'Plan SEMENCE',range:'50–300 membres',price:29,priceY:290,color:'#5B9EE8',cdim:'rgba(91,158,232,0.15)',
   f:['Site web bilingue (WordPress)','Dons mobiles (Orange Money, Airtel)','WhatsApp Business communautaire','YouTube + Facebook Live','Newsletter email (500 abonnés)','Calendrier d\'événements','2 comptes admins','5 Go de stockage médias','Support par email']},
  {icon:'🌾',name:'Plan RÉCOLTE',range:'300–1 500 membres',price:79,priceY:790,color:'#C9982A',cdim:'rgba(201,152,42,0.15)',pop:true,
   f:['Tout du Plan Semence','Logiciel de gestion (ChMS)','Campagnes SMS & WhatsApp','Dons récurrents automatiques','Bibliothèque sermons + podcast','Mur de prière communautaire','Gestion cellules & bénévoles','10 comptes admins','50 Go de stockage','Support prioritaire + coaching/mois']},
  {icon:'🏛️',name:'Plan MOUVEMENT',range:'1 500–10 000+ membres',price:149,priceY:1490,color:'#9B7FE8',cdim:'rgba(155,127,232,0.15)',
   f:['Tout du Plan Récolte','Application mobile (iOS & Android)','Gestion multi-sites','Diffusion HD en direct','Portail diaspora international','Analytique avancée','API illimitées','Admins illimités','500 Go de stockage','Responsable dédié + coaching hebdo']},
],
en:[
  {icon:'🌱',name:'SEED Plan',range:'50–300 members',price:29,priceY:290,color:'#5B9EE8',cdim:'rgba(91,158,232,0.15)',
   f:['Bilingual website (WordPress)','Mobile giving (Orange Money, Airtel)','Community WhatsApp Business','YouTube + Facebook Live','Monthly email newsletter (500)','Online events calendar','2 admin accounts','5 GB media storage','Email support']},
  {icon:'🌾',name:'HARVEST Plan',range:'300–1,500 members',price:79,priceY:790,color:'#C9982A',cdim:'rgba(201,152,42,0.15)',pop:true,
   f:['Everything in Seed Plan','Church management software (ChMS)','SMS & WhatsApp campaigns','Automatic recurring giving','Sermon library + podcast','Community prayer wall','Groups & volunteer management','10 admin accounts','50 GB storage','Priority support + coaching/month']},
  {icon:'🏛️',name:'MOVEMENT Plan',range:'1,500–10,000+ members',price:149,priceY:1490,color:'#9B7FE8',cdim:'rgba(155,127,232,0.15)',
   f:['Everything in Harvest Plan','Custom mobile app (iOS & Android)','Multi-site management','HD live streaming','International diaspora portal','Advanced analytics','Unlimited API integrations','Unlimited admins','500 GB storage','Dedicated manager + weekly coaching']},
],};
const TECH=[
  {cat:'Site Web / Website',tools:['WordPress + Hostinger','Google My Business','Yoast SEO','Google Analytics']},
  {cat:'Dons / Giving',tools:['Orange Money','Airtel Money','PayPal (diaspora)','Tithe.ly (Phase 2+)']},
  {cat:'Communication',tools:['WhatsApp Business','Mailchimp','SMS campaigns','Facebook/Instagram']},
  {cat:'Contenu / Content',tools:['YouTube','Spotify Podcasts','TikTok','OBS Studio']},
  {cat:'Gestion / ChMS',tools:['Breeze ChMS','Planning Center','Rock RMS','Google Workspace']},
  {cat:'Médias / Media',tools:['CapCut Pro','DaVinci Resolve','Buzzsprout','StreamYard']},
  {cat:'App Mobile',tools:['Subsplash','Church App','React Native','Discord']},
  {cat:'Automatisation',tools:['Zapier','Make (Integromat)','Google Analytics','Facebook Pixel']},
];
const SC={'Core Leader':{bg:'rgba(201,152,42,0.18)',c:'#E8B84B'},'Active':{bg:'rgba(45,212,160,0.13)',c:'#2DD4A0'},'Growing':{bg:'rgba(91,158,232,0.13)',c:'#5B9EE8'},'New Convert':{bg:'rgba(155,127,232,0.13)',c:'#9B7FE8'},'New Visitor':{bg:'rgba(232,112,112,0.13)',c:'#E87070'}};

/* ══════════════════════════════════════
   STATE
══════════════════════════════════════ */
let lang='fr',page='dashboard',billing='monthly',prayedSet=new Set(),steps={},charts={};

/* ══════════════════════════════════════
   UTILS
══════════════════════════════════════ */
const t=()=>L[lang];
const fK=n=>n>=1000?`$${(n/1e3).toFixed(1)}k`:`$${n}`;
function bdg(txt,bg,c,x=''){return`<span class="bdg" style="background:${bg};color:${c};${x}">${txt}</span>`;}
function prg(pct,col){return`<div class="pt"><div class="pf" style="width:${Math.min(pct,100)}%;background:${col}"></div></div>`;}
function mcard(label,val,sub,col,ico){return`<div class="mc" style="border-top-color:${col}"><div class="mc-ico">${ico}</div><div class="mc-lbl">${label}</div><div class="mc-val">${val}</div>${sub?`<div class="mc-sub">${sub}</div>`:''}</div>`;}
function phdr(title,sub,btn){return`<div class="ph-hdr"><div class="ph-ttl"><h1 class="h1" style="font-family:'Cormorant Garamond',serif;font-size:26px;font-weight:700;letter-spacing:.01em;margin-bottom:3px">${title}</h1>${sub?`<p style="color:var(--mut);font-size:13px">${sub}</p>`:''}</div>${btn?`<div class="ph-act"><button class="btnp bg">${btn}</button></div>`:''}</div>`;}

/* ══════════════════════════════════════
   SIDEBAR & MOBILE
══════════════════════════════════════ */
function buildNav(){
  const tr=t();
  document.getElementById('sbnav').innerHTML=tr.nav.map((l,i)=>`
    <div class="nav-item${tr.pages[i]===page?' active':''}" onclick="go('${tr.pages[i]}')">
      <span class="ni">${tr.icons[i]}</span>
      <span class="nl sh">${l}</span>
    </div>`).join('');
  const bi=[0,1,3,11,10];
  document.getElementById('botnav').innerHTML=bi.map(i=>`
    <div class="bi${tr.pages[i]===page?' active':''}" onclick="go('${tr.pages[i]}')">
      <span class="bi-ico">${tr.icons[i]}</span>
      <span class="bi-lbl">${tr.nav[i]}</span>
    </div>`).join('');
}
function toggleSB(){document.getElementById('sidebar').classList.toggle('slim');}
function openMob(){
  const s=document.getElementById('sidebar');
  s.style.cssText='display:flex!important;position:fixed;top:0;left:0;bottom:0;z-index:300;width:252px;';
  document.getElementById('mob-ov').classList.add('on');
}
function closeMob(){
  document.getElementById('sidebar').style.cssText='';
  document.getElementById('mob-ov').classList.remove('on');
}
function go(p){
  page=p;killCharts();buildNav();
  const tr=t();const i=tr.pages.indexOf(p);
  document.getElementById('tbtitle').textContent=i>=0?tr.nav[i]:'';
  render();closeMob();window.scrollTo(0,0);
}

/* ══════════════════════════════════════
   LANGUAGE
══════════════════════════════════════ */
function setLang(l){
  lang=l;
  document.getElementById('lo-fr').classList.toggle('on',l==='fr');
  document.getElementById('lo-en').classList.toggle('on',l==='en');
  const tr=t();
  document.getElementById('pr1').textContent=tr.pr1;
  document.getElementById('pr2').textContent=tr.pr2;
  document.getElementById('ppill').textContent=tr.ppill;
  document.getElementById('dlbl').textContent=tr.dlbl;
  const i=tr.pages.indexOf(page);
  document.getElementById('tbtitle').textContent=i>=0?tr.nav[i]:'';
  buildNav();killCharts();render();
}

/* ══════════════════════════════════════
   CHARTS
══════════════════════════════════════ */
function killCharts(){Object.values(charts).forEach(c=>{try{c.destroy();}catch(e){}});charts={};}
const CD={plugins:{legend:{display:false},tooltip:{backgroundColor:'#1C2A3A',borderColor:'#2A3D52',borderWidth:1,padding:10,titleColor:'#EDF2F7',bodyColor:'#B0C0D4'}},scales:{x:{grid:{color:'rgba(42,61,82,.6)'},ticks:{color:'#7A92AA',font:{size:10,family:'Outfit'}}},y:{grid:{color:'rgba(42,61,82,.6)'},ticks:{color:'#7A92AA',font:{size:10,family:'Outfit'}}}}};
function mkLine(id){
  const ctx=document.getElementById(id);if(!ctx)return;
  charts[id]=new Chart(ctx,{type:'line',data:{labels:['Jan','Fév','Mar','Avr','Mai','Jun','Jul','Aoû','Sep','Oct','Nov','Déc'],datasets:[{label:lang==='fr'?'Présence':'Attendance',data:[112,128,145,163,188,224,267,312,378,441,512,601],borderColor:'#C9982A',backgroundColor:'rgba(201,152,42,0.1)',fill:true,tension:.4,borderWidth:2,pointRadius:3,pointBackgroundColor:'#C9982A'},{label:'Online',data:[45,62,80,95,118,145,172,203,241,289,334,390],borderColor:'#5B9EE8',backgroundColor:'rgba(91,158,232,0.08)',fill:true,tension:.4,borderWidth:2,pointRadius:3,pointBackgroundColor:'#5B9EE8'}]},options:{...CD,responsive:true,maintainAspectRatio:false,plugins:{...CD.plugins,legend:{display:true,position:'top',labels:{color:'#7A92AA',font:{size:11},boxWidth:10,padding:16}}}}});
}
function mkBar(id){
  const ctx=document.getElementById(id);if(!ctx)return;
  charts[id]=new Chart(ctx,{type:'bar',data:{labels:['Jan','Fév','Mar','Avr','Mai','Jun'],datasets:[{label:lang==='fr'?'Dîmes':'Tithes',data:[8200,9100,10400,11800,13200,15600],backgroundColor:'#C9982A',borderRadius:5},{label:lang==='fr'?'Offrandes':'Offerings',data:[2100,2600,3100,3400,3900,4200],backgroundColor:'#5B9EE8',borderRadius:5}]},options:{...CD,responsive:true,maintainAspectRatio:false,plugins:{...CD.plugins,legend:{display:true,position:'top',labels:{color:'#7A92AA',font:{size:11},boxWidth:10,padding:16}}},scales:{...CD.scales,y:{...CD.scales.y,ticks:{...CD.scales.y.ticks,callback:fK}}}}});
}
function mkDough(id){
  const ctx=document.getElementById(id);if(!ctx)return;
  const tr=t();
  charts[id]=new Chart(ctx,{type:'doughnut',data:{labels:tr.rl,datasets:[{data:[38,27,22,13],backgroundColor:['#C9982A','#2DD4A0','#5B9EE8','#9B7FE8'],borderWidth:0,hoverOffset:4}]},options:{responsive:true,maintainAspectRatio:false,cutout:'66%',plugins:{legend:{display:true,position:'bottom',labels:{color:'#7A92AA',font:{size:10},padding:10,boxWidth:9}}}}});
}

/* ══════════════════════════════════════
   RENDER ROUTER
══════════════════════════════════════ */
function render(){
  const el=document.getElementById('content');
  const map={dashboard:rDash,members:rMembers,sermons:rSermons,giving:rGiving,groups:rGroups,events:rEvents,prayer:rPrayer,campaigns:rCampaigns,volunteers:rVols,roadmap:rRoadmap,pricing:rPricing,kickstart:rKickstart};
  el.innerHTML=(map[page]||rDash)();
  if(page==='dashboard')setTimeout(()=>{mkLine('ca');mkDough('cp');mkBar('cg');},30);
  if(page==='giving')setTimeout(()=>mkBar('cg2'),30);
}

/* ──────────────────── DASHBOARD ──────────────────── */
function rDash(){
  const tr=t();
  return`${phdr(tr.nav[0],tr.dashSub)}
<div class="mrow g4">
  ${mcard(tr.m1,'601',tr.s1,'#C9982A','⛪')}
  ${mcard(tr.m2,'390',tr.s2,'#5B9EE8','📱')}
  ${mcard(tr.m3,'$38 400',tr.s3,'#2DD4A0','💰')}
  ${mcard(tr.m4,'6',tr.s4,'#9B7FE8','🤝')}
</div>
<div class="g21 g1" style="margin-bottom:14px">
  <div class="card"><div class="ct">${tr.al[0]}</div><div class="ch"><canvas id="ca"></canvas></div></div>
  <div class="card"><div class="ct">${tr.al[1]}</div><div class="chp"><canvas id="cp"></canvas></div></div>
</div>
<div class="g2 g1">
  <div class="card"><div class="ct">${tr.al[2]}</div><div class="chsm"><canvas id="cg"></canvas></div></div>
  <div class="card"><div class="ct">${tr.al[3]}</div>
    ${tr.aa.map((a,i)=>`<div style="display:flex;align-items:center;gap:10px;padding:8px 0;border-bottom:${i<5?'1px solid var(--bdr)':'none'}"><span style="font-size:16px;width:22px;text-align:center">${['🔔','📧','🙏','👥','💰','📹'][i]}</span><span style="font-size:12px;color:var(--sub);flex:1;line-height:1.4">${a}</span><div style="width:7px;height:7px;border-radius:50%;background:${'#C9982A,#5B9EE8,#9B7FE8,#2DD4A0,#E87070,#E8B84B'.split(',')[i]};flex-shrink:0"></div></div>`).join('')}
  </div>
</div>`;
}

/* ──────────────────── MEMBERS ──────────────────── */
function rMembers(){
  const tr=t();
  const av=`style="width:32px;height:32px;border-radius:8px;background:var(--gdim);border:1.5px solid var(--gold);display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:700;color:var(--gl);font-family:'DM Mono',monospace;flex-shrink:0"`;
  const rows=MBR.map(m=>{const s=SC[m.s]||{bg:'#333',c:'#aaa'};return`<tr><td><div style="display:flex;align-items:center;gap:10px"><div ${av}>${m.av}</div><span style="font-weight:500">${m.n}</span></div></td><td style="color:var(--mut)">${m.j}</td><td>${bdg(tr.stmap[m.s]||m.s,s.bg,s.c)}</td><td style="color:${m.g>0?'#2DD4A0':'#E87070'};font-weight:600">${m.g}</td><td style="color:${m.giv!=='$0'?'#E8B84B':'var(--mut)'};font-weight:${m.giv!=='$0'?700:400}">${m.giv}</td><td>${m.tags.map(g=>bdg(g,'var(--card2)','var(--mut)','margin-right:3px')).join('')}</td></tr>`;}).join('');
  return`${phdr(tr.nav[1],tr.memberSub,tr.addM)}
<div class="mrow g4" style="margin-bottom:18px">
  ${mcard(tr.m1,'601','↑ 89 ce mois','#C9982A','👥')}
  ${mcard(lang==='fr'?'Nouveaux':'New This Month','28','17 visiteurs','#2DD4A0','🌱')}
  ${mcard(lang==='fr'?'Dîmeurs':'Tithers','187','31%','#5B9EE8','💎')}
  ${mcard(lang==='fr'?'En Cellules':'In Groups','89','14%','#9B7FE8','🤝')}
</div>
<input class="srch" placeholder="${tr.srchPh}" oninput="fM(this.value)">
<div class="card tw"><table><thead><tr>${tr.mCols.map(h=>`<th>${h}</th>`).join('')}</tr></thead><tbody id="mb">${rows}</tbody></table></div>`;
}
function fM(q){
  const tr=t();const av=`style="width:32px;height:32px;border-radius:8px;background:var(--gdim);border:1.5px solid var(--gold);display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:700;color:var(--gl);font-family:'DM Mono',monospace;flex-shrink:0"`;
  document.getElementById('mb').innerHTML=MBR.filter(m=>m.n.toLowerCase().includes(q.toLowerCase())).map(m=>{const s=SC[m.s]||{bg:'#333',c:'#aaa'};return`<tr><td><div style="display:flex;align-items:center;gap:10px"><div ${av}>${m.av}</div><span style="font-weight:500">${m.n}</span></div></td><td style="color:var(--mut)">${m.j}</td><td>${bdg(tr.stmap[m.s]||m.s,s.bg,s.c)}</td><td style="color:${m.g>0?'#2DD4A0':'#E87070'};font-weight:600">${m.g}</td><td style="color:${m.giv!=='$0'?'#E8B84B':'var(--mut)'};font-weight:${m.giv!=='$0'?700:400}">${m.giv}</td><td>${m.tags.map(g=>bdg(g,'var(--card2)','var(--mut)','margin-right:3px')).join('')}</td></tr>`;}).join('');
}

/* ──────────────────── SERMONS ──────────────────── */
function rSermons(){const tr=t();return`${phdr(tr.nav[2],tr.serSub,tr.upBtn)}<div class="mrow g4">${mcard('Total Sermons','142','12 séries','#C9982A','🎙️')}${mcard(lang==='fr'?'Vues Totales':'Total Views','48.2K','↑ 34%','#5B9EE8','👁️')}${mcard('Podcast','2 841','↑ 412','#2DD4A0','🎧')}${mcard('YouTube','1 203','↑ 187','#9B7FE8','▶️')}</div><div class="g3 g1">${SRM.map(s=>`<div class="ser-card"><div class="ser-thumb">${s.icon}</div><div style="font-size:10px;color:var(--mut);margin-bottom:3px;font-family:'DM Mono',monospace">${s.series}</div><div style="font-family:'Cormorant Garamond',serif;font-size:16px;font-weight:700;margin-bottom:8px;line-height:1.3">${s.title}</div><div style="display:flex;justify-content:space-between;font-size:11px"><span style="color:var(--mut)">${s.date}</span><span style="color:var(--gold);font-family:'DM Mono',monospace">⏱ ${s.dur}</span></div><div style="display:flex;gap:10px;margin-top:10px;padding-top:10px;border-top:1px solid var(--bdr)"><span style="font-size:11px;color:var(--mut)">👁️ ${s.views.toLocaleString()}</span><button class="btnp bgh bsm" style="margin-left:auto">${tr.shr}</button></div></div>`).join('')}</div>`;}

/* ──────────────────── GIVING ──────────────────── */
function rGiving(){const tr=t();const meth=[{m:'📱 Orange Money',p:38,a:'$14 592'},{m:'📱 Airtel Money',p:26,a:'$9 984'},{m:`💵 ${lang==='fr'?'Espèces':'Cash'}`,p:23,a:'$8 832'},{m:'💳 PayPal',p:13,a:'$4 992'}];return`${phdr(tr.nav[3],tr.givSub,tr.ncBtn)}<div class="mrow g4">${mcard(lang==='fr'?'Ce Mois':'This Month','$38 400','↑ 22%','#C9982A','💰')}${mcard(lang==='fr'?'Total Annuel':'YTD Total','$287 600','↑ 34%','#2DD4A0','📈')}${mcard(lang==='fr'?'En Ligne':'Online %','64%','of all','#5B9EE8','📱')}${mcard(lang==='fr'?'Récurrents':'Recurring','187','$22 400/mo','#9B7FE8','🔄')}</div><div class="g21 g1"><div class="card"><div class="ct">${tr.al?tr.al[2]:''}</div><div class="ch"><canvas id="cg2"></canvas></div></div><div class="card"><div class="sl">${tr.topM}</div>${meth.map(it=>`<div style="margin-bottom:12px"><div style="display:flex;justify-content:space-between;margin-bottom:5px;font-size:12px"><span>${it.m}</span><span style="color:#E8B84B;font-weight:700">${it.a}</span></div>${prg(it.p,'#C9982A')}</div>`).join('')}</div></div>`;}

/* ──────────────────── GROUPS ──────────────────── */
function rGroups(){const tr=t();return`${phdr(tr.nav[4],tr.grpSub,tr.ngBtn)}<div class="mrow g4">${mcard(lang==='fr'?'Cellules Actives':'Active Groups','6',lang==='fr'?'Obj: 20':'Goal: 20','#C9982A','🤝')}${mcard(lang==='fr'?'Total':'Total in Groups','102','17%','#2DD4A0','👥')}${mcard(lang==='fr'?'Taille Moy':'Avg Size','14',null,'#5B9EE8','📊')}${mcard(lang==='fr'?'Santé Moy':'Avg Health','87%',null,'#9B7FE8','❤️')}</div><div class="g2 g1">${GRP.map(g=>{const hc=g.h>=90?'#2DD4A0':g.h>=80?'#C9982A':'#E87070';return`<div class="grpcrd"><div style="display:flex;justify-content:space-between;margin-bottom:10px"><div><div style="font-family:'Cormorant Garamond',serif;font-size:17px;font-weight:700">${g.n}</div><div style="font-size:11px;color:var(--mut);margin-top:2px">${tr.led} ${g.l} · ${g.t}</div></div><div style="text-align:right"><div style="font-size:20px;font-weight:700;color:${hc};font-family:'Cormorant Garamond',serif">${g.h}%</div><div style="font-size:9px;color:var(--mut);text-transform:uppercase;letter-spacing:.06em">${tr.hlt}</div></div></div>${prg(g.h,hc)}<div style="display:flex;gap:14px;font-size:11px;color:var(--mut);margin-top:8px"><span>👥 ${g.m}</span><span>📅 ${g.mt}</span></div></div>`;}).join('')}</div>`;}

/* ──────────────────── EVENTS ──────────────────── */
function rEvents(){const tr=t();return`${phdr(tr.nav[5],tr.evtSub,tr.neBtn)}<div class="mrow g4">${mcard(lang==='fr'?'Ce Mois':'This Month','8',null,'#C9982A','📅')}${mcard('RSVPs','1 228','↑ 44%','#2DD4A0','✅')}${mcard(lang==='fr'?'Remplissage':'Fill Rate','78%',null,'#5B9EE8','🏟️')}${mcard('Livestream','390',null,'#9B7FE8','📺')}</div><div class="g2 g1">${EVT.map(ev=>{const f=Math.round((ev.r/ev.cap)*100),fc=f>=80?'#E87070':f>=60?'#C9982A':'#2DD4A0';return`<div class="evcrd" style="border-left-color:${ev.c}"><div style="display:flex;justify-content:space-between;margin-bottom:8px"><div><div style="font-family:'Cormorant Garamond',serif;font-size:17px;font-weight:700">${ev.t}</div><div style="font-size:11px;color:var(--mut);margin-top:2px">${ev.d} · ${ev.h}</div></div>${bdg(ev.type,ev.c+'22',ev.c)}</div><div style="display:flex;justify-content:space-between;font-size:11px;color:var(--mut);margin-bottom:6px"><span>${ev.r}/${ev.cap} ${tr.reg}</span><span style="color:${fc};font-weight:700">${f}%</span></div>${prg(f,fc)}</div>`;}).join('')}</div>`;}

/* ──────────────────── PRAYER ──────────────────── */
function rPrayer(){const tr=t();return`${phdr(tr.nav[6],tr.pSub,tr.npBtn)}<div class="mrow g4">${mcard(lang==='fr'?'Actives':'Active Requests','64',lang==='fr'?'12 nouvelles':'12 new','#C9982A','🙏')}${mcard(lang==='fr'?'Prières Offertes':'Prayers Given','2 841',null,'#2DD4A0','❤️')}${mcard(lang==='fr'?'Exaucées':'Answered','18',null,'#5B9EE8','✅')}${mcard(lang==='fr'?'Intercesseurs':'Intercessors','42',null,'#9B7FE8','🕊️')}</div><div class="g2 g1">${PRY.map((p,i)=>`<div class="prcrd"><div style="display:flex;justify-content:space-between;margin-bottom:10px"><div style="display:flex;align-items:center;gap:9px"><div style="width:32px;height:32px;border-radius:50%;background:var(--gdim);display:flex;align-items:center;justify-content:center;font-size:14px;flex-shrink:0">🙏</div><div><div style="font-size:13px;font-weight:600">${p.n}</div><div style="font-size:10px;color:var(--mut)">${p.t}</div></div></div>${bdg(p.cat,'var(--pud)','#9B7FE8')}</div><p style="font-size:12px;color:var(--sub);line-height:1.65;margin:0 0 12px">${p.req}</p><div style="display:flex;justify-content:space-between;align-items:center"><span style="font-size:11px;color:var(--mut)" id="pc${i}">🙏 ${p.p}</span><button class="btnp bsm ${prayedSet.has(i)?'bg':'bgh'}" id="pb${i}" onclick="doPray(${i},${p.p})">${prayedSet.has(i)?tr.pryDn:tr.pryBg}</button></div></div>`).join('')}</div>`;}
function doPray(i,b){const tr=t();prayedSet.has(i)?prayedSet.delete(i):prayedSet.add(i);const btn=document.getElementById('pb'+i),cnt=document.getElementById('pc'+i);if(btn){btn.textContent=prayedSet.has(i)?tr.pryDn:tr.pryBg;btn.className='btnp bsm '+(prayedSet.has(i)?'bg':'bgh');}if(cnt)cnt.textContent='🙏 '+(b+(prayedSet.has(i)?1:0));}

/* ──────────────────── CAMPAIGNS ──────────────────── */
function rCampaigns(){const tr=t();const sb=s=>{const a=s==='Actif'||s==='Active',d=s==='Brouillon'||s==='Draft';return bdg(s,a?'var(--gnd)':d?'var(--gdim)':'var(--bld)',a?'#2DD4A0':d?'#C9982A':'#5B9EE8');};return`${phdr(tr.nav[7],tr.campSub,tr.ncBtn2)}<div class="mrow g4">${mcard(lang==='fr'?'Abonnés Email':'Email Subs','1 843','↑ 214','#C9982A','📧')}${mcard('WhatsApp/SMS','912','49% opt-in','#2DD4A0','💬')}${mcard(lang==='fr'?'Taux Ouverture':'Open Rate','71%','US avg 22%','#5B9EE8','📬')}${mcard(lang==='fr'?'Taux Clics':'Click Rate','38%','US avg 6%','#9B7FE8','🖱️')}</div><div class="card tw"><table><thead><tr>${tr.cCols.map(h=>`<th>${h}</th>`).join('')}<th></th></tr></thead><tbody>${CAM.map(c=>`<tr><td style="font-weight:500">${c.n}</td><td style="font-size:11px;color:var(--mut)">${c.ch}</td><td>${sb(c.s)}</td><td style="font-family:'DM Mono',monospace;font-size:12px">${c.sent.toLocaleString()}</td><td style="color:${c.open>60?'#2DD4A0':c.open>0?'#C9982A':'var(--mut)'};font-family:'DM Mono',monospace;font-size:12px">${c.sent>0?c.open+'%':'—'}</td><td style="color:${c.clk>30?'#2DD4A0':c.clk>0?'#C9982A':'var(--mut)'};font-family:'DM Mono',monospace;font-size:12px">${c.sent>0?c.clk+'%':'—'}</td><td><button class="btnp bgh bsm">${tr.vw}</button></td></tr>`).join('')}</tbody></table></div>`;}

/* ──────────────────── VOLUNTEERS ──────────────────── */
function rVols(){const tr=t();return`${phdr(tr.nav[8],tr.volSub,tr.avBtn)}<div class="mrow g4">${mcard(lang==='fr'?'Total':'Total Volunteers','87',lang==='fr'?'8 équipes':'8 teams','#C9982A','🌟')}${mcard(lang==='fr'?'Heures':'Hours This Month','624','↑ 18%','#2DD4A0','⏱️')}${mcard(lang==='fr'?'Satisfaction':'Satisfaction','93%',null,'#5B9EE8','😊')}${mcard(lang==='fr'?'Postes Ouverts':'Open Positions','12',null,'#E87070','🚨')}</div><div class="g2 g1">${VOL.map(v=>`<div class="vcrd"><div style="width:38px;height:38px;border-radius:9px;background:var(--gdim);border:1.5px solid var(--gold);display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:700;color:var(--gl);font-family:'DM Mono',monospace;flex-shrink:0">${v.n.split(' ').slice(0,2).map(x=>x[0]).join('')}</div><div style="flex:1"><div style="display:flex;align-items:center;gap:5px"><span style="font-size:13px;font-weight:600">${v.n}</span>${v.badge?`<span style="font-size:12px">${v.badge}</span>`:''}</div><div style="font-size:11px;color:var(--mut)">${v.role} · ${v.team}</div></div><div style="text-align:right"><div style="font-size:14px;font-weight:700;color:${v.rat>=95?'#2DD4A0':'#C9982A'};font-family:'Cormorant Garamond',serif">${v.rat}%</div><div style="font-size:10px;color:var(--mut)">${v.hrs}h</div></div></div>`).join('')}</div>`;}

/* ──────────────────── ROADMAP ──────────────────── */
function pocCard(idx){
  const tr=t(),ph=PHS[idx],col=ph.color;
  const items=lang==='fr'?ph.fr:ph.en,kpis=lang==='fr'?ph.kpFr:ph.kpEn;
  const title=lang==='fr'?ph.tFr:ph.tEn,time=lang==='fr'?ph.tmFr:ph.tmEn;
  const sb=ph.done?bdg(tr.phDone,'var(--gnd)','#2DD4A0'):ph.active?bdg(tr.phAct,'var(--gdim)','#C9982A'):bdg(tr.phUp,'var(--card2)','var(--mut)');
  return`<div class="poc" style="border-color:${col}33"><div class="poc-stripe" style="background:linear-gradient(90deg,${col},${col}66)"></div><div class="poc-body"><span class="poc-num" style="color:${col}">${idx+1}</span><div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:18px;flex-wrap:wrap;gap:12px"><div><div class="poc-lbl" style="color:${col}">${ph.ph} · ${time}</div><div class="poc-title">${title}</div><div class="poc-range">${ph.range}</div></div><div class="poc-right">${sb}<div class="bud"><div class="bud-lbl">${tr.kB}</div><div class="bud-val">${ph.budget}</div></div></div></div><div class="phbody"><div><div class="pbt" style="color:${col}">${tr.kS}</div>${items.map((it,j)=>`<div class="si"><div class="scb${steps[idx+'_'+j]?' chk':''}" id="sc${idx}_${j}" onclick="ts(${idx},${j})">${steps[idx+'_'+j]?'✓':''}</div><span class="stxt">${it}</span></div>`).join('')}</div><div><div class="pbt" style="color:var(--gold)">${tr.kK}</div>${kpis.map(k=>`<div class="kchip" style="border-left-color:${col}">${k}</div>`).join('')}</div><div><div class="pbt" style="color:var(--blu)">${tr.kT}</div>${ph.tools.map(t=>`<div class="trow"><span style="color:var(--grn);font-size:11px">✓</span>${t}</div>`).join('')}</div></div></div></div>`;
}
function paccCard(idx){
  const tr=t(),ph=PHS[idx],col=ph.color;
  const items=lang==='fr'?ph.fr:ph.en,kpis=lang==='fr'?ph.kpFr:ph.kpEn;
  const title=lang==='fr'?ph.tFr:ph.tEn,time=lang==='fr'?ph.tmFr:ph.tmEn;
  return`<div class="pacc" id="pa${idx}"><div class="pa-hdr" onclick="tAcc(${idx})"><div class="pa-numbox" style="background:${ph.cdim};border:1.5px solid ${col}44;color:${col}">${idx+1}</div><div class="pa-inf"><div class="pa-lbl" style="color:${col}">${ph.ph} · ${time}</div><div><span class="pa-ttl">${title}</span><span class="pa-range">${ph.range}</span></div></div><span class="pa-hint">${tr.c2e}</span><div class="pa-arr">▾</div></div><div class="pa-body"><div class="ph34b"><div><div class="pbt" style="color:${col}">${tr.kS}</div>${items.map((it,j)=>`<div class="si"><div class="scb${steps[idx+'_'+j]?' chk':''}" id="sc${idx}_${j}" onclick="ts(${idx},${j})">${steps[idx+'_'+j]?'✓':''}</div><span class="stxt">${it}</span></div>`).join('')}</div><div><div class="pbt" style="color:var(--gold)">${tr.kK}</div>${kpis.map(k=>`<div class="kchip" style="border-left-color:${col}">${k}</div>`).join('')}<div class="bud" style="margin-top:10px"><div class="bud-lbl">${tr.kB}</div><div class="bud-val">${ph.budget}</div></div></div><div><div class="pbt" style="color:var(--blu)">${tr.kT}</div>${ph.tools.map(t=>`<div class="trow"><span style="color:var(--grn);font-size:11px">✓</span>${t}</div>`).join('')}</div></div></div></div>`;
}
function rRoadmap(){
  const tr=t();
  const rpDots=PHS.map((ph,i)=>`<div class="rp-step"><div class="rp-dot ${ph.done?'done':ph.active?'active':'up'}">${ph.done?'✓':i+1}</div><div class="rp-lbl">${lang==='fr'?ph.tFr:ph.tEn}<div class="rp-range">${ph.range}</div></div></div>`).join('');
  const techH=TECH.map(c=>`<div class="tc"><div class="tcat">${c.cat}</div>${c.tools.map(tt=>`<div class="ti">• ${tt}</div>`).join('')}</div>`).join('');
  return`${phdr(tr.nav[9],tr.roadSub)}<div class="mrow g4">${mcard(tr.curM,'601','Phase 2','#C9982A','📍')}${mcard(tr.ph2G,'1 000',lang==='fr'?'~8 mois':'~8 months','#2DD4A0','🎯')}${mcard(tr.tl,'~5 ans',null,'#5B9EE8','📅')}${mcard(tr.rt,'24+',null,'#9B7FE8','🛠️')}</div><div class="rp-wrap">${rpDots}</div>${pocCard(0)}${pocCard(1)}${paccCard(2)}${paccCard(3)}<div style="margin-top:26px"><div class="sl">${tr.techT}</div><div class="tg g1" style="grid-template-columns:repeat(4,1fr)">${techH}</div></div>`;
}
function tAcc(idx){document.getElementById('pa'+idx)?.classList.toggle('open');}
function ts(pi,j){const k=pi+'_'+j;steps[k]=!steps[k];const el=document.getElementById('sc'+pi+'_'+j);if(el){el.classList.toggle('chk',steps[k]);el.textContent=steps[k]?'✓':''}}

/* ──────────────────── PRICING ──────────────────── */
function rPricing(){
  const tr=t(),plans=PLANS[lang];
  const cards=plans.map(pl=>`<div class="plan-card${pl.pop?' pop':''}" style="${pl.pop?'border-color:'+pl.color:''}">${pl.pop?`<div class="plan-rec">${tr.popL}</div>`:''}<div style="font-size:26px;margin-bottom:12px">${pl.icon}</div><div style="font-family:'Cormorant Garamond',serif;font-size:19px;font-weight:700;margin-bottom:4px">${pl.name}</div><div style="display:flex;align-items:baseline;gap:3px;margin-bottom:3px"><span style="font-family:'Cormorant Garamond',serif;font-size:36px;font-weight:700;color:${pl.color};line-height:1">$${billing==='monthly'?pl.price:Math.round(pl.priceY/12)}</span><span style="font-size:13px;color:var(--mut)">${tr.perMo}</span></div>${billing==='yearly'?`<div style="font-size:11px;color:var(--grn);margin-bottom:4px">$${pl.priceY}${tr.perYr}</div>`:''}<div style="font-size:12px;color:var(--mut);margin-bottom:16px">${pl.range}</div><div style="font-size:10px;font-weight:700;color:var(--mut);text-transform:uppercase;letter-spacing:.07em;font-family:'DM Mono',monospace;margin-bottom:8px">${tr.incl}</div>${pl.f.map(f=>`<div class="pf2"><span style="color:var(--grn);flex-shrink:0;margin-top:1px">✓</span>${f}</div>`).join('')}<button class="pbn" style="${pl.pop?`background:${pl.color};color:#0C1620;box-shadow:0 2px 12px ${pl.color}44`:`background:transparent;color:${pl.color};border:1.5px solid ${pl.color}55`}" onclick="go('kickstart')">${tr.choosePlan}</button></div>`).join('');
  const cmpRows=[['Christian Church OS','$29–$149','✓','✓','✓','✓','✓'],['Planning Center','$199+','✓','✗','✗','✓','✗'],['Subsplash','$199+','✓','✗','✗','✓','✗'],['Tithe.ly','$89+','✗','✗','✓','✗','✗'],['Rock RMS','$0','✓','✗','✗','✓','✗']];
  return`${phdr(tr.nav[10],tr.priceSub)}<div style="background:var(--gdim);border:1px solid rgba(201,152,42,.35);border-radius:10px;padding:11px 17px;margin-bottom:22px;font-size:12px;color:var(--gl)">${tr.priceNote}</div><div class="billing-row"><button class="bo${billing==='monthly'?' on':''}" onclick="setBill('monthly')">${tr.monthly}</button><button class="bo${billing==='yearly'?' on':''}" onclick="setBill('yearly')">${tr.yearly}</button></div><div class="pricing-g g1">${cards}</div><div class="card"><div style="font-family:'Cormorant Garamond',serif;font-size:18px;font-weight:700;margin-bottom:4px">${tr.cmpT}</div><div style="font-size:12px;color:var(--mut);margin-bottom:16px">${tr.cmpN}</div><div class="tw"><table class="cmp-table"><thead><tr>${tr.cmpCols.map(h=>`<th>${h}</th>`).join('')}</tr></thead><tbody>${cmpRows.map((row,ri)=>`<tr class="${ri===0?'chl':''}">${row.map(cell=>`<td class="${cell==='✓'?'cy':cell==='✗'?'cn':''}">${cell}</td>`).join('')}</tr>`).join('')}</tbody></table></div></div>`;
}
function setBill(v){billing=v;if(page==='pricing')render();}

/* ══════════════════════════════════════════════════
   KICKSTART — UPFRONT INVESTMENT PAGE
══════════════════════════════════════════════════ */
function rKickstart(){
  const tr=t();
  const pkg=[
    {key:'seed',color:'#5B9EE8',cdim:'rgba(91,158,232,0.15)',planLink:lang==='fr'?'Plan SEMENCE':'SEED Plan',price:KS_PRICES.seed,name:tr.kp1Name,sub:tr.kp1Sub,pLabel:tr.kp1PL,pNote:tr.kp1PN,feats:tr.kp1F,cta:tr.kp1CTA},
    {key:'harvest',color:'#C9982A',cdim:'rgba(201,152,42,0.15)',planLink:lang==='fr'?'Plan RÉCOLTE':'HARVEST Plan',price:KS_PRICES.harvest,name:tr.kp2Name,sub:tr.kp2Sub,pLabel:tr.kp2PL,pNote:tr.kp2PN,feats:tr.kp2F,cta:tr.kp2CTA,featured:true},
    {key:'movement',color:'#9B7FE8',cdim:'rgba(155,127,232,0.15)',planLink:lang==='fr'?'Plan MOUVEMENT':'MOVEMENT Plan',price:KS_PRICES.movement,name:tr.kp3Name,sub:tr.kp3Sub,pLabel:tr.kp3PL,pNote:tr.kp3PN,feats:tr.kp3F,cta:tr.kp3CTA},
  ];
  const cards=pkg.map(p=>`
    <div class="kp-card${p.featured?' featured':''}">
      ${p.featured?`<div class="kp-feat-badge">${tr.kpFeatBadge}</div>`:''}
      <span class="kp-plan-link" style="background:${p.cdim};color:${p.color};border:1px solid ${p.color}44">${p.planLink}</span>
      <div class="kp-name">${p.name}</div>
      <div class="kp-subtitle">${p.sub}</div>
      <div class="kp-price-block">
        <div class="kp-price-label">${p.pLabel}</div>
        <div class="kp-price" style="color:${p.color}">$${p.price.toLocaleString()}</div>
        <div class="kp-price-note">${p.pNote}</div>
      </div>
      <hr class="kp-divider">
      <div class="kp-includes-lbl">${tr.incl}</div>
      ${p.feats.map(f=>`<div class="kp-feat"><span class="ck">✓</span>${f}</div>`).join('')}
      <button class="kp-cta" style="${p.featured?`background:${p.color};color:#0C1620;box-shadow:0 3px 16px ${p.color}44`:`background:${p.cdim};color:${p.color};border:1.5px solid ${p.color}55!important`}" onclick="alert('${lang==="fr"?"Contactez-nous via WhatsApp ou email pour commencer.":"Contact us via WhatsApp or email to get started."}')">${p.cta} →</button>
    </div>`).join('');

  const terms=[
    {i:'🔒',t:tr.kt1T,d:tr.kt1D},
    {i:'⚡',t:tr.kt2T,d:tr.kt2D},
    {i:'🛡️',t:tr.kt3T,d:tr.kt3D},
    {i:'🔑',t:tr.kt4T,d:tr.kt4D},
  ];

  return`
${phdr(tr.nav[11])}

<!-- HERO -->
<div class="ks-hero">
  <div class="ks-eyebrow">🚀 ${tr.ksEy}</div>
  <h1 class="ks-title" style="font-family:'Cormorant Garamond',serif">${tr.ksTtl}</h1>
  <p class="ks-desc">${tr.ksDesc}</p>
  <div class="ks-why g1" style="display:grid;grid-template-columns:repeat(3,1fr);gap:12px">
    <div class="ks-why-item"><div class="ks-why-icon">🎯</div><div class="ks-why-title">${tr.ksWhy1T}</div><div class="ks-why-desc">${tr.ksWhy1D}</div></div>
    <div class="ks-why-item"><div class="ks-why-icon">⚙️</div><div class="ks-why-title">${tr.ksWhy2T}</div><div class="ks-why-desc">${tr.ksWhy2D}</div></div>
    <div class="ks-why-item"><div class="ks-why-icon">🎓</div><div class="ks-why-title">${tr.ksWhy3T}</div><div class="ks-why-desc">${tr.ksWhy3D}</div></div>
  </div>
</div>

<!-- DIVIDER -->
<div class="ks-divider"><div class="ks-divider-line"></div><div class="ks-divider-label">${tr.ksUpT}</div><div class="ks-divider-line"></div></div>
<div style="font-size:12px;color:var(--mut);text-align:center;margin:-16px 0 22px;font-family:'DM Mono',monospace">${tr.ksUpN}</div>

<!-- PACKAGES -->
<div class="ks-pkg">${cards}</div>

<!-- TERMS -->
<div class="ks-terms">
  <div class="kt-title">${tr.ktT}</div>
  <div class="kt-grid g1" style="display:grid;grid-template-columns:repeat(2,1fr);gap:12px">
    ${terms.map(it=>`<div class="kt-item"><div class="kt-icon">${it.i}</div><div><div class="kt-label">${it.t}</div><div class="kt-desc">${it.d}</div></div></div>`).join('')}
  </div>
</div>

<!-- CTA BANNER -->
<div class="ks-cta-banner">
  <div class="ks-cta-text">
    <h3>${tr.ksCTA_T}</h3>
    <p>${tr.ksCTA_D}</p>
  </div>
  <div class="ks-cta-btns">
    <button class="ks-wa-btn" onclick="window.open('https://wa.me/','_blank')">
      <span style="font-size:17px">💬</span> ${tr.ksWA}
    </button>
    <button class="ks-email-btn" onclick="window.open('mailto:contact@christianchurchkolwezi.com','_blank')">
      ✉️ ${tr.ksEM}
    </button>
  </div>
</div>`;
}

/* ══════════════════════════════════════
   BOOT
══════════════════════════════════════ */
document.addEventListener('DOMContentLoaded',()=>{buildNav();render();});
</script>
</body>
</html>
