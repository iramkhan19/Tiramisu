<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Iramisu — Artisan Tiramisu by Iram · Halifax</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,900;1,400;1,700;1,900&family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;1,300;1,400;1,500&family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;1,9..40,300&display=swap" rel="stylesheet">
<style>
:root{
  --cr:#f5ead8;--esp:#1a0f07;--car:#c8824a;--gld:#d4a853;
  --coc:#3d1a00;--moc:#6b3a1f;--mut:rgba(245,234,216,0.52);
  --card:rgba(255,255,255,0.035);--border:rgba(200,130,74,0.13);
}
*{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{background:var(--esp);color:var(--cr);font-family:'DM Sans',sans-serif;overflow-x:hidden;cursor:none;}

/* CURSOR */
#cur{position:fixed;width:14px;height:14px;background:var(--car);border-radius:50%;pointer-events:none;z-index:9999;transform:translate(-50%,-50%);transition:width .15s,height .15s,opacity .2s;mix-blend-mode:difference;}
#cur.big{width:36px;height:36px;opacity:.35;}

/* CLICK PARTICLE CANVAS */
#clickCanvas{position:fixed;inset:0;pointer-events:none;z-index:9998;}

/* LOADER */
#loader{position:fixed;inset:0;background:var(--esp);z-index:9000;display:flex;flex-direction:column;align-items:center;justify-content:center;transition:opacity .9s;}
#loader.out{opacity:0;pointer-events:none;}
.ld-wrap{position:relative;width:240px;height:220px;margin-bottom:2rem;}
.ld-dish{position:absolute;bottom:0;left:50%;transform:translateX(-50%);width:220px;height:34px;background:linear-gradient(180deg,#c8a07a,#7a4a1a);border-radius:0 0 50px 50px;border:2px solid #d4b896;}
.ld-layer{position:absolute;left:50%;transform:translateX(-50%) scaleY(0);transform-origin:bottom;border-radius:6px;opacity:0;transition:transform .55s cubic-bezier(.34,1.56,.64,1),opacity .3s;}
.ld-l1{width:200px;height:30px;bottom:30px;background:linear-gradient(90deg,#5c2d0a,#8b4513,#5c2d0a);}
.ld-l2{width:196px;height:28px;bottom:58px;background:linear-gradient(90deg,#ede6d8,#f8f3ec,#ede6d8);}
.ld-l3{width:192px;height:30px;bottom:84px;background:linear-gradient(90deg,#4a220a,#7a3c10,#4a220a);}
.ld-l4{width:188px;height:26px;bottom:112px;background:linear-gradient(90deg,#f0ece4,#faf8f4,#f0ece4);}
.ld-l5{width:184px;height:18px;bottom:136px;background:#2a1205;border-radius:6px 6px 3px 3px;}
.ld-layer.on{transform:translateX(-50%) scaleY(1);opacity:1;}
.ld-face{position:absolute;bottom:132px;left:50%;transform:translateX(-50%);font-size:36px;opacity:0;transition:opacity .5s;animation:flt 1.8s ease-in-out infinite;}
.ld-face.on{opacity:1;}
@keyframes flt{0%,100%{transform:translateX(-50%) translateY(0)}50%{transform:translateX(-50%) translateY(-7px)}}
.ld-title{font-family:'Playfair Display',serif;font-style:italic;font-size:38px;color:var(--car);letter-spacing:3px;margin-bottom:.4rem;}
.ld-sub{font-size:11px;color:var(--mut);letter-spacing:5px;text-transform:uppercase;margin-bottom:1.8rem;}
.ld-bar-wrap{width:200px;height:2px;background:rgba(200,130,74,.15);border-radius:2px;}
.ld-bar{height:100%;width:0;background:var(--car);border-radius:2px;transition:width .5s ease;}

/* NAV */
nav{position:fixed;top:0;left:0;right:0;z-index:800;padding:1.2rem 3rem;display:flex;align-items:center;justify-content:space-between;background:linear-gradient(180deg,rgba(26,15,7,.97) 0%,transparent 100%);backdrop-filter:blur(10px);transition:background .3s;}
nav.scrolled{background:rgba(26,15,7,.98);}
.nav-logo{font-family:'Playfair Display',serif;font-style:italic;font-size:26px;color:var(--car);cursor:pointer;letter-spacing:1px;transition:opacity .2s;}
.nav-logo:hover{opacity:.8;}
.nav-links{display:flex;gap:2.2rem;list-style:none;}
.nav-links a{font-size:11px;letter-spacing:3px;text-transform:uppercase;color:var(--mut);cursor:pointer;transition:color .2s;text-decoration:none;}
.nav-links a:hover,.nav-links a.active{color:var(--car);}
.nav-btn{background:var(--car);color:var(--esp);padding:.6rem 1.5rem;border-radius:2px;font-size:11px;letter-spacing:3px;text-transform:uppercase;font-weight:500;border:none;cursor:pointer;transition:background .2s,transform .1s;}
.nav-btn:hover{background:var(--gld);transform:translateY(-1px);}
.nav-cart{position:relative;background:transparent;border:1px solid var(--border);color:var(--cr);padding:.6rem 1.2rem;border-radius:2px;font-size:11px;letter-spacing:2px;text-transform:uppercase;cursor:pointer;transition:border-color .2s;display:flex;align-items:center;gap:.5rem;}
.nav-cart:hover{border-color:var(--car);color:var(--car);}
#cartNum{background:var(--car);color:var(--esp);border-radius:50%;width:18px;height:18px;font-size:10px;font-weight:700;display:inline-flex;align-items:center;justify-content:center;}

/* PAGES */
.pg{display:none;min-height:100vh;}.pg.active{display:block;}

/* ── HOME ── */
.hero{position:relative;min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;overflow:hidden;padding:8rem 2rem 3rem;}
.hero-bg{position:absolute;inset:0;background:radial-gradient(ellipse at 25% 60%,rgba(101,55,15,.38) 0%,transparent 55%),radial-gradient(ellipse at 78% 30%,rgba(60,25,5,.45) 0%,transparent 50%),linear-gradient(155deg,#0d0803 0%,#1a0f07 50%,#1e1108 100%);}
.hero-parts{position:absolute;inset:0;overflow:hidden;}
.hpt{position:absolute;border-radius:50%;animation:hdrift linear infinite;}
@keyframes hdrift{0%{transform:translateY(110vh) rotate(0);opacity:0}10%{opacity:1}90%{opacity:.3}100%{transform:translateY(-120px) rotate(720deg);opacity:0}}
.hero-content{position:relative;z-index:2;text-align:center;max-width:800px;}
.eyebrow{font-size:11px;letter-spacing:6px;text-transform:uppercase;color:var(--car);margin-bottom:1.5rem;opacity:0;animation:fadeUp .8s .3s forwards;}
.hero-title{font-family:'Playfair Display',serif;font-size:clamp(72px,13vw,148px);font-style:italic;line-height:.88;letter-spacing:-3px;opacity:0;animation:fadeUp 1s .5s forwards;}
.hero-title .iI{color:var(--car);}
.hero-title .iR{color:var(--cr);font-weight:400;}
.hero-tag{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:clamp(18px,2.5vw,26px);color:var(--mut);margin-top:1.3rem;letter-spacing:1px;opacity:0;animation:fadeUp .8s .8s forwards;}
.hero-ctas{display:flex;gap:1rem;justify-content:center;margin-top:2.8rem;opacity:0;animation:fadeUp .8s 1.1s forwards;flex-wrap:wrap;}
@keyframes fadeUp{from{opacity:0;transform:translateY(22px)}to{opacity:1;transform:translateY(0)}}
.btn-p{background:var(--car);color:var(--esp);padding:.95rem 2.4rem;border:none;font-size:11px;letter-spacing:3px;text-transform:uppercase;font-weight:500;cursor:pointer;border-radius:2px;transition:background .2s,transform .15s;}
.btn-p:hover{background:var(--gld);transform:translateY(-2px);}
.btn-g{background:transparent;color:var(--cr);padding:.95rem 2.4rem;border:1px solid rgba(245,234,216,.22);font-size:11px;letter-spacing:3px;text-transform:uppercase;cursor:pointer;border-radius:2px;transition:all .2s;}
.btn-g:hover{border-color:var(--car);color:var(--car);transform:translateY(-2px);}
.hero-art{position:absolute;right:6%;top:50%;transform:translateY(-50%);opacity:0;animation:fadeUp 1s 1.3s forwards;}

/* MARQUEE */
.mq-wrap{border-top:1px solid rgba(200,130,74,.1);border-bottom:1px solid rgba(200,130,74,.1);padding:1rem 0;overflow:hidden;background:rgba(200,130,74,.03);}
.mq-inner{display:flex;animation:mq 28s linear infinite;white-space:nowrap;}
@keyframes mq{0%{transform:translateX(0)}100%{transform:translateX(-50%)}}
.mq-item{font-family:'Playfair Display',serif;font-style:italic;font-size:14px;color:var(--car);padding:0 2rem;letter-spacing:2px;}

/* STATS */
.stats{display:flex;justify-content:center;gap:4rem;padding:3rem 2rem;flex-wrap:wrap;}
.stat-n{font-family:'Playfair Display',serif;font-size:44px;color:var(--car);font-style:italic;}
.stat-l{font-size:10px;letter-spacing:3px;text-transform:uppercase;color:var(--mut);margin-top:.2rem;}

/* ABOUT STRIP */
.about-strip{padding:6rem 3rem;max-width:1100px;margin:0 auto;display:grid;grid-template-columns:1fr 1fr;gap:5rem;align-items:center;}
.sec-eye{font-size:10px;letter-spacing:5px;text-transform:uppercase;color:var(--car);margin-bottom:1rem;}
.sec-title{font-family:'Playfair Display',serif;font-style:italic;font-size:clamp(28px,4vw,48px);line-height:1.2;margin-bottom:1.5rem;}
.sec-body{font-family:'Cormorant Garamond',serif;font-size:18px;line-height:1.95;color:var(--mut);}
.about-canvas-wrap canvas{border-radius:6px;display:block;width:100%;}

/* FEATURED */
.featured{padding:5rem 3rem;text-align:center;border-top:1px solid var(--border);}
.feat-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1.2rem;max-width:1000px;margin:2.5rem auto 0;}
.feat-card{background:var(--card);border:1px solid var(--border);border-radius:6px;padding:1.5rem;text-align:left;cursor:pointer;transition:all .3s;}
.feat-card:hover{border-color:rgba(200,130,74,.4);transform:translateY(-5px);}
.feat-name{font-family:'Playfair Display',serif;font-style:italic;font-size:20px;color:var(--cr);margin-bottom:.3rem;}
.feat-sub{font-size:12px;color:var(--mut);letter-spacing:1px;}
.feat-price{font-family:'Playfair Display',serif;font-size:22px;color:var(--car);margin-top:1rem;}

/* TESTIMONIALS */
.testi{padding:5rem 3rem;text-align:center;background:rgba(200,130,74,.025);}
.testi-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1.2rem;max-width:1000px;margin:2.5rem auto 0;}
.tc{background:var(--card);border:1px solid var(--border);border-radius:6px;padding:2rem;text-align:left;transition:all .3s;}
.tc:hover{border-color:rgba(200,130,74,.35);transform:translateY(-4px);}
.tc-stars{color:var(--gld);font-size:12px;letter-spacing:2px;margin-bottom:.8rem;}
.tc-text{font-family:'Cormorant Garamond',serif;font-style:italic;font-size:17px;line-height:1.75;color:var(--cr);margin-bottom:1rem;}
.tc-auth{font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--mut);}

/* CTA BAND */
.cta-band{background:rgba(200,130,74,.06);border-top:1px solid var(--border);border-bottom:1px solid var(--border);padding:5rem 2rem;text-align:center;}

/* ── MENU ── */
#menu{padding-top:5rem;}
.menu-hero{text-align:center;padding:5rem 2rem 2rem;}
.filters{display:flex;gap:.5rem;justify-content:center;flex-wrap:wrap;margin:2rem auto;max-width:700px;}
.fb{padding:.45rem 1.3rem;border:1px solid rgba(200,130,74,.22);background:transparent;color:var(--mut);font-size:10px;letter-spacing:2px;text-transform:uppercase;cursor:pointer;border-radius:2px;transition:all .2s;}
.fb.on,.fb:hover{background:var(--car);color:var(--esp);border-color:var(--car);}
.menu-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(285px,1fr));gap:1.4rem;max-width:1200px;margin:0 auto;padding:1rem 3rem 6rem;}
.mc{background:var(--card);border:1px solid var(--border);border-radius:8px;overflow:hidden;cursor:pointer;transition:all .3s;position:relative;}
.mc:hover{border-color:rgba(200,130,74,.45);transform:translateY(-6px);box-shadow:0 20px 60px rgba(0,0,0,.45);}
.mc-art{width:100%;height:185px;display:block;}
.mc-badge{position:absolute;top:12px;right:12px;background:var(--car);color:var(--esp);font-size:9px;letter-spacing:2px;text-transform:uppercase;padding:.3rem .7rem;border-radius:2px;font-weight:500;}
.mc-body{padding:1.4rem;}
.mc-name{font-family:'Playfair Display',serif;font-style:italic;font-size:22px;color:var(--cr);margin-bottom:.3rem;}
.mc-sub{font-size:12px;color:var(--mut);letter-spacing:.5px;margin-bottom:.8rem;line-height:1.6;}
.mc-foot{display:flex;justify-content:space-between;align-items:center;}
.mc-price{font-family:'Playfair Display',serif;font-size:24px;color:var(--car);}
.mc-sz{font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--mut);margin-top:2px;}
.mc-add{width:36px;height:36px;background:var(--car);color:var(--esp);border:none;border-radius:50%;font-size:20px;cursor:pointer;display:flex;align-items:center;justify-content:center;transition:background .2s,transform .15s;line-height:1;}
.mc-add:hover{background:var(--gld);transform:scale(1.12) rotate(90deg);}

/* MODAL */
.mo{position:fixed;inset:0;background:rgba(0,0,0,.88);z-index:2000;display:none;align-items:center;justify-content:center;padding:2rem;backdrop-filter:blur(5px);}
.mo.open{display:flex;}
.mo-box{background:#1e1008;border:1px solid rgba(200,130,74,.28);border-radius:10px;max-width:480px;width:100%;padding:2.5rem;position:relative;animation:moin .3s cubic-bezier(.34,1.56,.64,1);}
@keyframes moin{from{transform:scale(.85);opacity:0}to{transform:scale(1);opacity:1}}
.mo-close{position:absolute;top:1rem;right:1.2rem;background:none;border:none;color:var(--mut);font-size:22px;cursor:pointer;transition:color .2s;}
.mo-close:hover{color:var(--cr);}
.mo-name{font-family:'Playfair Display',serif;font-style:italic;font-size:30px;color:var(--car);margin-bottom:.4rem;}
.mo-desc{font-family:'Cormorant Garamond',serif;font-size:17px;line-height:1.8;color:var(--mut);margin-bottom:1.2rem;font-style:italic;}
.mo-layers-t{font-size:10px;letter-spacing:3px;text-transform:uppercase;color:var(--car);margin-bottom:.7rem;}
.mo-pill{display:inline-block;background:rgba(200,130,74,.1);border:1px solid rgba(200,130,74,.2);color:var(--cr);font-size:12px;padding:.3rem .8rem;border-radius:2px;margin:.2rem;}
.mo-sizes{display:flex;gap:.7rem;margin:1.2rem 0;}
.sz{flex:1;border:1px solid rgba(200,130,74,.2);background:transparent;color:var(--cr);padding:.75rem;border-radius:4px;cursor:pointer;text-align:center;transition:all .2s;font-size:13px;}
.sz.sel{background:var(--car);color:var(--esp);border-color:var(--car);}
.mo-add{width:100%;background:var(--car);color:var(--esp);border:none;padding:1.1rem;font-size:11px;letter-spacing:3px;text-transform:uppercase;font-weight:500;cursor:pointer;border-radius:4px;transition:background .2s;margin-top:.5rem;}
.mo-add:hover{background:var(--gld);}

/* ── ABOUT ── */
#about{padding-top:8rem;}
.about-pg-hero{text-align:center;padding:4rem 2rem 4rem;}
.about-grid{max-width:980px;margin:0 auto;padding:0 3rem 6rem;display:grid;grid-template-columns:1fr 1fr;gap:1.4rem;}
.acard{background:var(--card);border:1px solid var(--border);border-radius:8px;padding:2rem;}
.acard-icon{font-size:30px;margin-bottom:.8rem;}
.acard-t{font-family:'Playfair Display',serif;font-style:italic;font-size:21px;color:var(--car);margin-bottom:.6rem;}
.acard-b{font-size:15px;line-height:1.85;color:var(--mut);}

/* ── GAME ── */
#game{padding-top:8rem;}
.game-wrap{max-width:680px;margin:0 auto;padding:3rem 2rem 5rem;text-align:center;}
.game-stats{display:flex;gap:3rem;justify-content:center;margin-bottom:1.5rem;}
.gs-n{font-family:'Playfair Display',serif;font-size:30px;color:var(--car);font-style:italic;}
.gs-l{font-size:10px;letter-spacing:3px;text-transform:uppercase;color:var(--mut);}
.gc-wrap{background:rgba(255,255,255,.03);border:1px solid rgba(200,130,74,.2);border-radius:10px;overflow:hidden;position:relative;}
#gc{display:block;width:100%;touch-action:none;}
.g-btns{display:flex;gap:.8rem;justify-content:center;margin-top:1rem;flex-wrap:wrap;}
.gbtn{padding:.75rem 2rem;border:1px solid rgba(200,130,74,.3);background:transparent;color:var(--cr);font-size:11px;letter-spacing:2px;text-transform:uppercase;cursor:pointer;border-radius:2px;transition:all .2s;}
.gbtn.p{background:var(--car);color:var(--esp);border-color:var(--car);}
.gbtn:hover{border-color:var(--car);color:var(--car);}
.gbtn.p:hover{background:var(--gld);}
.g-tip{background:rgba(200,130,74,.06);border:1px solid rgba(200,130,74,.12);border-radius:6px;padding:1.2rem 1.5rem;margin-top:1.2rem;text-align:left;font-size:13px;color:var(--mut);line-height:1.8;}
.g-tip strong{color:var(--car);}

/* ── CONTACT ── */
#contact{padding-top:8rem;}
.contact-wrap{max-width:580px;margin:0 auto;padding:4rem 3rem 6rem;}
.fi{margin-bottom:1.4rem;}
.fl{display:block;font-size:10px;letter-spacing:3px;text-transform:uppercase;color:var(--car);margin-bottom:.55rem;}
.finp,.ftxt,.fsel{width:100%;background:rgba(255,255,255,.04);border:1px solid rgba(200,130,74,.2);color:var(--cr);padding:.85rem 1.1rem;font-size:15px;border-radius:4px;font-family:'Cormorant Garamond',serif;outline:none;transition:border-color .2s;}
.finp:focus,.ftxt:focus,.fsel:focus{border-color:var(--car);}
.ftxt{min-height:120px;resize:vertical;}
.fsel option{background:#1e1008;}
.fsub{width:100%;background:var(--car);color:var(--esp);border:none;padding:1.2rem;font-size:11px;letter-spacing:4px;text-transform:uppercase;font-weight:500;cursor:pointer;border-radius:4px;margin-top:.8rem;transition:background .2s;}
.fsub:hover{background:var(--gld);}

/* FOOTER */
footer{border-top:1px solid var(--border);padding:2.5rem 3rem;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:1rem;}
.fl-logo{font-family:'Playfair Display',serif;font-style:italic;font-size:22px;color:var(--car);}
.fl-links{display:flex;gap:2rem;list-style:none;}
.fl-links a{font-size:11px;letter-spacing:2px;text-transform:uppercase;color:var(--mut);cursor:pointer;text-decoration:none;transition:color .2s;}
.fl-links a:hover{color:var(--car);}
.fl-copy{font-size:11px;color:rgba(245,234,216,.22);letter-spacing:1px;}

/* TOAST */
#toast{position:fixed;bottom:5.5rem;right:2rem;background:#1e1008;border:1px solid rgba(200,130,74,.3);color:var(--cr);padding:.85rem 1.4rem;border-radius:4px;font-size:13px;z-index:700;transform:translateY(16px);opacity:0;transition:all .3s;pointer-events:none;max-width:280px;}
#toast.on{transform:translateY(0);opacity:1;}

/* CART DRAWER */
#cartDrawer{position:fixed;right:-340px;top:0;bottom:0;width:320px;background:#1a0d06;border-left:1px solid var(--border);z-index:1500;transition:right .35s cubic-bezier(.4,0,.2,1);padding:2rem 1.5rem;overflow-y:auto;}
#cartDrawer.open{right:0;}
.cd-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:1.5rem;}
.cd-title{font-family:'Playfair Display',serif;font-style:italic;font-size:22px;color:var(--car);}
.cd-close{background:none;border:none;color:var(--mut);font-size:22px;cursor:pointer;}
.cd-item{border-bottom:1px solid var(--border);padding:.9rem 0;display:flex;gap:1rem;align-items:flex-start;}
.cd-item-name{font-family:'Playfair Display',serif;font-style:italic;font-size:16px;color:var(--cr);}
.cd-item-det{font-size:12px;color:var(--mut);margin-top:.2rem;}
.cd-item-price{margin-left:auto;font-family:'Playfair Display',serif;font-size:18px;color:var(--car);}
.cd-rm{background:none;border:none;color:var(--mut);cursor:pointer;font-size:14px;margin-top:.3rem;transition:color .2s;}
.cd-rm:hover{color:#e86060;}
.cd-total{margin-top:1.5rem;text-align:right;}
.cd-total-n{font-family:'Playfair Display',serif;font-size:26px;color:var(--cr);}
.cd-total-l{font-size:10px;letter-spacing:3px;text-transform:uppercase;color:var(--mut);}
.cd-checkout{width:100%;background:var(--car);color:var(--esp);border:none;padding:1rem;font-size:11px;letter-spacing:3px;text-transform:uppercase;font-weight:500;cursor:pointer;border-radius:4px;margin-top:1rem;transition:background .2s;}
.cd-checkout:hover{background:var(--gld);}
.cd-empty{text-align:center;padding:3rem 1rem;color:var(--mut);font-family:'Cormorant Garamond',serif;font-style:italic;font-size:18px;}

/* CART FAB */
#cartFab{position:fixed;bottom:2rem;right:2rem;background:var(--car);color:var(--esp);width:52px;height:52px;border-radius:50%;display:flex;flex-direction:column;align-items:center;justify-content:center;cursor:pointer;z-index:700;box-shadow:0 4px 18px rgba(200,130,74,.4);transition:transform .2s;font-size:20px;border:none;}
#cartFab:hover{transform:scale(1.1);}
#cartFab span{font-size:10px;font-weight:700;line-height:1;}

/* IDEAS SECTION */
.ideas{padding:5rem 3rem;text-align:center;background:rgba(200,130,74,.02);}
.ideas-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:1rem;max-width:1000px;margin:2.5rem auto 0;}
.idea-card{background:var(--card);border:1px solid var(--border);border-radius:8px;padding:1.8rem;text-align:left;transition:all .3s;}
.idea-card:hover{border-color:rgba(200,130,74,.4);transform:translateY(-4px);}
.idea-icon{font-size:26px;margin-bottom:.8rem;}
.idea-t{font-family:'Playfair Display',serif;font-style:italic;font-size:18px;color:var(--car);margin-bottom:.5rem;}
.idea-b{font-size:13px;line-height:1.75;color:var(--mut);}

@media(max-width:768px){
  nav{padding:1rem 1.2rem;}
  .nav-links{display:none;}
  .hero-art{display:none;}
  .stats{gap:1.5rem;}
  .about-strip{grid-template-columns:1fr;gap:2rem;}
  .testi-grid{grid-template-columns:1fr;}
  .about-grid{grid-template-columns:1fr;}
  .menu-grid{padding:1rem 1rem 4rem;}
  footer{flex-direction:column;text-align:center;}
}
</style>
</head>
<body>
<div id="cur"></div>
<canvas id="clickCanvas"></canvas>
<div id="toast"></div>

<!-- CART FAB -->
<button id="cartFab" onclick="toggleCart()">🛒<span id="cartNum">0</span></button>

<!-- CART DRAWER -->
<div id="cartDrawer">
  <div class="cd-head">
    <div class="cd-title">Your Order</div>
    <button class="cd-close" onclick="toggleCart()">✕</button>
  </div>
  <div id="cartItems"></div>
  <div class="cd-total" id="cartTotal" style="display:none">
    <div class="cd-total-l">Total</div>
    <div class="cd-total-n" id="cartTotalNum"></div>
    <button class="cd-checkout" onclick="checkout()">Place Order via Email</button>
  </div>
</div>

<!-- LOADER -->
<div id="loader">
  <div class="ld-wrap">
    <div class="ld-dish"></div>
    <div class="ld-layer ld-l1" id="ll1"></div>
    <div class="ld-layer ld-l2" id="ll2"></div>
    <div class="ld-layer ld-l3" id="ll3"></div>
    <div class="ld-layer ld-l4" id="ll4"></div>
    <div class="ld-layer ld-l5" id="ll5"></div>
    <div class="ld-face" id="lface">😋</div>
  </div>
  <div class="ld-title">Iramisu</div>
  <div class="ld-sub" id="lsub">soaking the ladyfingers…</div>
  <div class="ld-bar-wrap"><div class="ld-bar" id="lbar"></div></div>
</div>

<!-- NAV -->
<nav id="nav">
  <div class="nav-logo" onclick="go('home')"><span style="color:var(--cr)">I</span>ramisu</div>
  <ul class="nav-links">
    <li><a onclick="go('home')" id="nl-home" class="active">Home</a></li>
    <li><a onclick="go('menu')" id="nl-menu">Menu</a></li>
    <li><a onclick="go('game')" id="nl-game">Play</a></li>
    <li><a onclick="go('about')" id="nl-about">Story</a></li>
    <li><a onclick="go('contact')" id="nl-contact">Order</a></li>
  </ul>
  <div style="display:flex;gap:.7rem;">
    <button class="nav-cart" onclick="toggleCart()">🛒 Cart <span id="cartNumNav">0</span></button>
    <button class="nav-btn" onclick="go('contact')">Order Now</button>
  </div>
</nav>

<!-- ═══ HOME ═══ -->
<div id="home" class="pg active">
  <section class="hero" id="heroSec">
    <div class="hero-bg"></div>
    <div class="hero-parts" id="heroParts"></div>
    <div class="hero-content">
      <p class="eyebrow">✦ &nbsp;Artisan Tiramisu &nbsp;✦ &nbsp;Halifax NS&nbsp; ✦</p>
      <h1 class="hero-title"><span class="iI">I</span><span class="iR">ramisu</span></h1>
      <p class="hero-tag">Handcrafted layers of love, one jar at a time.<br>No eggs. No rush. Just real ingredients.</p>
      <div class="hero-ctas">
        <button class="btn-p" onclick="go('menu')">Explore Flavours</button>
        <button class="btn-g" onclick="go('game')">Play the Game 🎮</button>
        <button class="btn-g" onclick="go('about')">Our Story</button>
      </div>
    </div>
    <div class="hero-art"><canvas id="heroC" width="200" height="280"></canvas></div>
  </section>

  <div class="mq-wrap"><div class="mq-inner" id="mq"></div></div>

  <div class="stats">
    <div class="stat"><div class="stat-n">12+</div><div class="stat-l">Flavours</div></div>
    <div class="stat"><div class="stat-n">100%</div><div class="stat-l">Egg-Free</div></div>
    <div class="stat"><div class="stat-n">500+</div><div class="stat-l">Happy Jars</div></div>
    <div class="stat"><div class="stat-n">0</div><div class="stat-l">Regrets</div></div>
  </div>

  <div class="about-strip">
    <div class="about-canvas-wrap"><canvas id="aboutC" width="460" height="320"></canvas></div>
    <div>
      <p class="sec-eye">Made with love</p>
      <h2 class="sec-title">Every layer<br>tells <em>a story</em></h2>
      <p class="sec-body">Iramisu was born in a Halifax kitchen with one big dream — reinvent tiramisu with bold flavours, keeping it completely egg-free so everyone can enjoy it.<br><br>Each jar is assembled by hand, set overnight, and delivered fresh. Small batch. Big flavour. Always made by Iram.</p>
      <button class="btn-p" style="margin-top:1.8rem;" onclick="go('about')">Read Our Story</button>
    </div>
  </div>

  <div class="featured">
    <p class="sec-eye">On the menu</p>
    <h2 class="sec-title">This week's favourites</h2>
    <div class="feat-grid" id="featGrid"></div>
    <button class="btn-p" style="margin-top:2.5rem;" onclick="go('menu')">View Full Menu</button>
  </div>

  <!-- IDEAS SECTION -->
  <div class="ideas">
    <p class="sec-eye">Coming soon & ideas</p>
    <h2 class="sec-title">What's brewing ☕</h2>
    <div class="ideas-grid">
      <div class="idea-card"><div class="idea-icon">🎂</div><div class="idea-t">Tiramisu Tasting Boxes</div><div class="idea-b">A curated 4-jar box of seasonal flavours — the perfect gift or way to try everything at once.</div></div>
      <div class="idea-card"><div class="idea-icon">💌</div><div class="idea-t">Custom Order Messages</div><div class="idea-b">Add a handwritten note to your order for birthdays, anniversaries, or just because.</div></div>
      <div class="idea-card"><div class="idea-icon">🫙</div><div class="idea-t">Jar Return Discount</div><div class="idea-b">Return your glass jar, get $1 off your next order. Good for your wallet, good for the planet.</div></div>
      <div class="idea-card"><div class="idea-icon">📍</div><div class="idea-t">Pop-Up Markets</div><div class="idea-b">Watch this space — Iramisu will be appearing at Halifax farmers markets and events soon.</div></div>
      <div class="idea-card"><div class="idea-icon">🎓</div><div class="idea-t">Mini Tiramisu Workshop</div><div class="idea-b">Small-group workshops where you layer your own jar to take home. DM us to register interest.</div></div>
      <div class="idea-card"><div class="idea-icon">🔔</div><div class="idea-t">Flavour Drops Newsletter</div><div class="idea-b">New seasonal flavours announced first by email. Sign up via the contact form.</div></div>
    </div>
  </div>

  <div class="testi">
    <p class="sec-eye">What people say</p>
    <h2 class="sec-title">Sweet reviews</h2>
    <div class="testi-grid">
      <div class="tc"><div class="tc-stars">★★★★★</div><p class="tc-text">"The Chaimisu is everything. Cardamom, cream, espresso — warm and dreamy. I ordered three jars."</p><div class="tc-auth">— Fatima A., Halifax</div></div>
      <div class="tc"><div class="tc-stars">★★★★★</div><p class="tc-text">"Egg-free and you genuinely cannot tell. The Matchamisu is addictive. Iram is incredibly talented."</p><div class="tc-auth">— James K., Dartmouth</div></div>
      <div class="tc"><div class="tc-stars">★★★★★</div><p class="tc-text">"Ordered the Mangomisu for my mum's birthday. She called it the best dessert she's ever had."</p><div class="tc-auth">— Priya S., Halifax</div></div>
    </div>
  </div>

  <div class="cta-band">
    <p class="sec-eye">Ready to indulge?</p>
    <h2 class="sec-title" style="max-width:500px;margin:0 auto 1.5rem;">Order your jars today</h2>
    <p style="color:var(--mut);font-family:'Cormorant Garamond',serif;font-size:18px;margin-bottom:2rem;">Pickup in Halifax · Delivery within HRM · 48hr notice appreciated</p>
    <button class="btn-p" onclick="go('contact')">Place an Order</button>
  </div>

  <footer>
    <div class="fl-logo">Iramisu</div>
    <ul class="fl-links"><li><a onclick="go('menu')">Menu</a></li><li><a onclick="go('game')">Play</a></li><li><a onclick="go('about')">Story</a></li><li><a onclick="go('contact')">Order</a></li></ul>
    <div class="fl-copy">© 2025 Iramisu by Iram · Halifax, NS</div>
  </footer>
</div>

<!-- ═══ MENU ═══ -->
<div id="menu" class="pg">
  <div class="menu-hero">
    <p class="sec-eye">The Collection</p>
    <h1 class="sec-title" style="font-size:clamp(34px,6vw,58px);">Our Flavours</h1>
    <p style="color:var(--mut);font-family:'Cormorant Garamond',serif;font-size:18px;max-width:480px;margin:.8rem auto 0;">Every flavour is egg-free, made in small batches, layered by hand.</p>
    <div class="filters">
      <button class="fb on" data-f="all">All</button>
      <button class="fb" data-f="classic">Classic</button>
      <button class="fb" data-f="chai">Chai & Spice</button>
      <button class="fb" data-f="earthy">Earthy</button>
      <button class="fb" data-f="fruity">Fruity</button>
      <button class="fb" data-f="floral">Floral</button>
      <button class="fb" data-f="indian">Indian</button>
      <button class="fb" data-f="limited">Limited</button>
    </div>
  </div>
  <div class="menu-grid" id="menuGrid"></div>
  <footer>
    <div class="fl-logo">Iramisu</div>
    <ul class="fl-links"><li><a onclick="go('home')">Home</a></li><li><a onclick="go('contact')">Order</a></li></ul>
    <div class="fl-copy">© 2025 Iramisu · Halifax</div>
  </footer>
</div>

<!-- FLAVOR MODAL -->
<div class="mo" id="mo" onclick="closeMo(event)">
  <div class="mo-box">
    <button class="mo-close" onclick="closeMo()">✕</button>
    <div class="mo-name" id="moName"></div>
    <div style="font-size:11px;letter-spacing:2px;text-transform:uppercase;color:var(--mut);margin-bottom:.8rem;" id="moSub"></div>
    <div class="mo-desc" id="moDesc"></div>
    <div class="mo-layers-t">The Layers</div>
    <div id="moLayers" style="margin-bottom:1.2rem;"></div>
    <div class="mo-layers-t" style="margin-top:.5rem;">Choose Size</div>
    <div class="mo-sizes" id="moSizes"></div>
    <button class="mo-add" onclick="addToCart()">Add to Order 🛒</button>
  </div>
</div>

<!-- ═══ ABOUT ═══ -->
<div id="about" class="pg">
  <div class="about-pg-hero">
    <p class="sec-eye">The Story</p>
    <h1 class="sec-title" style="font-size:clamp(34px,6vw,54px);">Born from a love<br><em>of layers</em></h1>
    <p style="color:var(--mut);font-family:'Cormorant Garamond',serif;font-size:18px;max-width:540px;margin:1rem auto 0;line-height:1.95;">Iramisu started when Iram made tiramisu for a friend's gathering — and three people asked where they could buy it. The answer was simple: <em>from me.</em></p>
  </div>
  <div class="about-grid">
    <div class="acard"><div class="acard-icon">☕</div><div class="acard-t">The Origin</div><div class="acard-b">Chai because it felt like home. Matcha because balance. Ube because why not be bold? Each flavour was tested on family, refined through feedback, and perfected with patience.</div></div>
    <div class="acard"><div class="acard-icon">🥛</div><div class="acard-t">Egg-Free, Always</div><div class="acard-b">Every Iramisu is made without eggs — because delicious desserts should be for everyone. Real mascarpone, whipped cream, quality espresso. No shortcuts, no compromises.</div></div>
    <div class="acard"><div class="acard-icon">🫙</div><div class="acard-t">The Jars</div><div class="acard-b">We serve in reusable glass jars. Return yours for $1 off your next order. Good for you, good for the planet.</div></div>
    <div class="acard"><div class="acard-icon">📍</div><div class="acard-t">Halifax Made</div><div class="acard-b">Proudly made in Halifax, Nova Scotia. Local pickup or delivery within HRM. One-woman kitchen — please allow 48 hours for orders.</div></div>
    <div class="acard"><div class="acard-icon">🌿</div><div class="acard-t">Real Ingredients</div><div class="acard-b">No powders. No artificial flavours. The Chaimisu uses real cardamom and cinnamon. The Mangomisu uses real Alphonso mango. Always.</div></div>
    <div class="acard"><div class="acard-icon">✨</div><div class="acard-t">Small Batch Magic</div><div class="acard-b">We make in limited quantities each week so every jar gets full attention. Order early — flavours sell out fast.</div></div>
  </div>
  <div style="text-align:center;padding:2rem 2rem 4rem;">
    <button class="btn-p" onclick="go('menu')">Browse the Menu</button>
  </div>
  <footer>
    <div class="fl-logo">Iramisu</div>
    <ul class="fl-links"><li><a onclick="go('home')">Home</a></li><li><a onclick="go('menu')">Menu</a></li><li><a onclick="go('contact')">Order</a></li></ul>
    <div class="fl-copy">© 2025 Iramisu · Halifax</div>
  </footer>
</div>

<!-- ═══ GAME ═══ -->
<div id="game" class="pg">
  <div class="game-wrap">
    <p class="sec-eye">Mini Game</p>
    <h1 class="sec-title" style="font-size:clamp(26px,5vw,44px);">Stack the Tiramisu!</h1>
    <p style="color:var(--mut);font-family:'Cormorant Garamond',serif;font-size:17px;margin-bottom:1.5rem;">Drop the ingredients at the right moment to build perfect layers. Score 150+ to unlock a discount code!</p>
    <div class="game-stats">
      <div class="gs"><div class="gs-n" id="gsc">0</div><div class="gs-l">Score</div></div>
      <div class="gs"><div class="gs-n" id="glc">0</div><div class="gs-l">Layers</div></div>
      <div class="gs"><div class="gs-n" id="ghc">0</div><div class="gs-l">Best</div></div>
    </div>
    <div class="gc-wrap"><canvas id="gc" width="640" height="400"></canvas></div>
    <div class="g-btns">
      <button class="gbtn p" id="gStartBtn" onclick="gStart()">▶ Start Game</button>
      <button class="gbtn" onclick="go('menu')">Order Real Tiramisu →</button>
    </div>
    <div class="g-tip"><strong>How to play:</strong> Click · Tap · or press <strong>Space</strong> to drop the falling ingredient. Land it on the stack! Miss 3 times and it's over. Stack 8+ perfect layers for a secret discount code. Get creative — combos score more! 🍮</div>
  </div>
  <footer>
    <div class="fl-logo">Iramisu</div>
    <ul class="fl-links"><li><a onclick="go('home')">Home</a></li><li><a onclick="go('menu')">Menu</a></li><li><a onclick="go('contact')">Order</a></li></ul>
    <div class="fl-copy">© 2025 Iramisu · Halifax</div>
  </footer>
</div>

<!-- ═══ CONTACT ═══ -->
<div id="contact" class="pg">
  <div class="contact-wrap">
    <div style="text-align:center;margin-bottom:3rem;">
      <p class="sec-eye">Place an Order</p>
      <h1 class="sec-title" style="font-size:clamp(28px,5vw,46px);">Let's make something<br><em>delicious</em></h1>
      <p style="color:var(--mut);font-family:'Cormorant Garamond',serif;font-size:17px;margin-top:1rem;line-height:1.8;">48-hour notice · Pickup in Halifax · Delivery within HRM · Payment by e-Transfer</p>
    </div>
    <div class="fi"><label class="fl">Your Name</label><input class="finp" id="cn" placeholder="e.g. Sarah Mitchell"></div>
    <div class="fi"><label class="fl">Email</label><input class="finp" type="email" id="ce" placeholder="sarah@example.com"></div>
    <div class="fi"><label class="fl">Phone (optional)</label><input class="finp" type="tel" id="cp" placeholder="(902) 555-0100"></div>
    <div class="fi"><label class="fl">Pickup or Delivery?</label><select class="fsel" id="cd"><option>Local pickup — Halifax</option><option>Delivery within HRM (+$5)</option></select></div>
    <div class="fi"><label class="fl">Flavour(s) & Quantity</label><textarea class="ftxt" id="co" placeholder="e.g. 2× Iramisu (regular), 1× Chaimisu (large), 1× Mangomisu (mini)"></textarea></div>
    <div class="fi"><label class="fl">Allergies or notes</label><textarea class="ftxt" style="min-height:80px;" id="cnotes" placeholder="Nut allergies, it's a gift, surprise flavour welcome, discount code…"></textarea></div>
    <button class="fsub" onclick="submitOrder()">Send My Order ✦</button>
    <div style="margin-top:2.5rem;border-top:1px solid var(--border);padding-top:2rem;">
      <p class="sec-eye" style="margin-bottom:1rem;">Find us</p>
      <p style="font-family:'Cormorant Garamond',serif;font-size:17px;line-height:2;color:var(--mut);">📍 Halifax, Nova Scotia<br>📧 hello@iramisu.ca<br>📸 @iramisu.ca<br>💳 e-Transfer on confirmation</p>
    </div>
  </div>
  <footer>
    <div class="fl-logo">Iramisu</div>
    <ul class="fl-links"><li><a onclick="go('home')">Home</a></li><li><a onclick="go('menu')">Menu</a></li><li><a onclick="go('about')">Story</a></li></ul>
    <div class="fl-copy">© 2025 Iramisu · Halifax</div>
  </footer>
</div>

<script>
// ══════════════════════════════════════════
//  DATA
// ══════════════════════════════════════════
const FLAVORS = [
  {id:'iramisu',name:'Iramisu',sub:'The Original',cat:'classic',badge:'Signature',
   c1:'#5c2d0a',c2:'#c8a07a',
   desc:'The one that started it all. Strong espresso-soaked savoiardi, silky mascarpone cloud, a veil of bitter cocoa. This is home.',
   layers:['Espresso savoiardi','Mascarpone cream','Espresso savoiardi','Mascarpone cream','Dark cocoa dust'],
   prices:{mini:9,regular:14,large:20}},
  {id:'chaimisu',name:'Chaimisu',sub:'Chai & Cardamom',cat:'chai',badge:'Fan Fave',
   c1:'#7a3c10',c2:'#e8b87a',
   desc:'Cardamom, cinnamon, ginger and clove-infused espresso soaking. Warm, aromatic, deeply comforting — like a chai hug in a jar.',
   layers:['Chai-espresso savoiardi','Cardamom mascarpone','Chai savoiardi','Cinnamon cream','Cinnamon dust'],
   prices:{mini:10,regular:15,large:22}},
  {id:'matchamisu',name:'Matchamisu',sub:'Ceremonial Matcha',cat:'earthy',badge:'',
   c1:'#2d4a1e',c2:'#7aab5a',
   desc:'Ceremonial grade matcha in both the soak and cream. Earthy, smooth, and quietly extraordinary.',
   layers:['Matcha ladyfingers','Matcha mascarpone','Matcha ladyfingers','Matcha cream','Matcha powder finish'],
   prices:{mini:11,regular:16,large:23}},
  {id:'ubemisu',name:'Ubemisu',sub:'Ube & Coconut',cat:'fruity',badge:'Bold',
   c1:'#4a2070',c2:'#b07adc',
   desc:'Filipino ube purple yam meets Italian tiramisu. Coconut cream, ube extract, gorgeous violet layers.',
   layers:['Coconut savoiardi','Ube mascarpone','Coconut savoiardi','Ube cream','Shredded coconut'],
   prices:{mini:12,regular:17,large:24}},
  {id:'mangomisu',name:'Mangomisu',sub:'Alphonso Mango',cat:'fruity',badge:'New ✨',
   c1:'#7a4a05',c2:'#f5b83a',
   desc:'Real Alphonso mango folded through the mascarpone with a mango-saffron soak. Tropical, sweet, and show-stopping.',
   layers:['Mango-saffron savoiardi','Mango mascarpone','Mango savoiardi','Mango cream','Dried mango flakes'],
   prices:{mini:12,regular:17,large:24}},
  {id:'rosemisu',name:'Rosemisu',sub:'Rose & Pistachio',cat:'floral',badge:'',
   c1:'#7a2a3c',c2:'#e87ab0',
   desc:'Rose water delicately folded into cream, pistachio crumble between layers, dried rose petals on top. Romantic and refined.',
   layers:['Rose water savoiardi','Rose mascarpone','Rose savoiardi','Pistachio crumble','Dried rose petals'],
   prices:{mini:12,regular:17,large:24}},
  {id:'gulabjamunmisu',name:'Gulab Jamunmisu',sub:'Indian Rose Syrup',cat:'indian',badge:'Indian 🇮🇳',
   c1:'#7a2010',c2:'#e8804a',
   desc:'Inspired by gulab jamun — rose syrup and cardamom soak, saffron mascarpone cream, pistachio crumble. Mithai meets tiramisu.',
   layers:['Rose-cardamom savoiardi','Saffron mascarpone','Rose savoiardi','Pistachio cream','Edible silver dust'],
   prices:{mini:13,regular:18,large:25}},
  {id:'kulfi misu',name:'Kulfimisu',sub:'Cardamom & Pistachio Kulfi',cat:'indian',badge:'Indian 🇮🇳',
   c1:'#1e4a3c',c2:'#7ad4b0',
   desc:'Kulfi-inspired with cardamom, reduced milk cream, pistachio and rose — a North Indian summer in a jar.',
   layers:['Cardamom savoiardi','Reduced milk mascarpone','Cardamom savoiardi','Pistachio cream','Rose & pistachio'],
   prices:{mini:13,regular:18,large:25}},
  {id:'halwamisu',name:'Halwamisu',sub:'Carrot Halwa',cat:'indian',badge:'Indian 🇮🇳',
   c1:'#7a3010',c2:'#e89050',
   desc:'The warmth of gajar halwa — cardamom, ghee-kissed carrots folded through mascarpone with a lightly spiced soak.',
   layers:['Spiced savoiardi','Carrot halwa swirl','Cardamom mascarpone','Carrot & pistachio','Saffron dust'],
   prices:{mini:13,regular:18,large:25}},
  {id:'masalachaimisu',name:'Masala Chaimisu',sub:'Full Spice Masala',cat:'chai',badge:'Spicy',
   c1:'#5a2a08',c2:'#d4804a',
   desc:'Bolder than Chaimisu — a full masala chai soak with black pepper, ginger, clove and star anise. For spice lovers.',
   layers:['Masala chai savoiardi','Pepper-cardamom cream','Chai savoiardi','Spiced mascarpone','Black pepper dust'],
   prices:{mini:11,regular:16,large:23}},
  {id:'lemisu',name:'Lemisu',sub:'Lemon Curd & Basil',cat:'fruity',badge:'',
   c1:'#5a4a10',c2:'#e8d870',
   desc:'Bright lemon curd swirled through mascarpone, limoncello-kissed savoiardi, fresh basil oil finish. Light and refreshing.',
   layers:['Limoncello savoiardi','Lemon curd mascarpone','Lemon savoiardi','Lemon cream','Candied lemon zest'],
   prices:{mini:10,regular:15,large:22}},
  {id:'saffronmisu',name:'Saffronmisu',sub:'Saffron & Honey',cat:'limited',badge:'Limited ✦',
   c1:'#7a4a10',c2:'#e8c040',
   desc:'Persian-inspired saffron steeped in warm cream, honey-kissed mascarpone, edible gold dust on top. Our most luxurious offering.',
   layers:['Saffron savoiardi','Saffron mascarpone','Rose savoiardi','Honey cream','Edible gold dust'],
   prices:{mini:14,regular:20,large:28}},
];

const FEATURED_IDS = ['iramisu','chaimisu','mangomisu','gulabjamunmisu'];

// ══════════════════════════════════════════
//  CURSOR
// ══════════════════════════════════════════
const cur = document.getElementById('cur');
document.addEventListener('mousemove', e => {
  cur.style.left = e.clientX+'px'; cur.style.top = e.clientY+'px';
});
document.addEventListener('mousedown', () => cur.classList.add('big'));
document.addEventListener('mouseup', () => cur.classList.remove('big'));

// ══════════════════════════════════════════
//  CLICK PARTICLE CANVAS — tiny tiramisu ingredients
// ══════════════════════════════════════════
const cc = document.getElementById('clickCanvas');
const cctx = cc.getContext('2d');
let ccW, ccH;
const cParticles = [];

function resizeCC() { ccW = cc.width = window.innerWidth; ccH = cc.height = window.innerHeight; }
resizeCC(); window.addEventListener('resize', resizeCC);

// Tiramisu ingredient shapes to draw at click point
const SHAPES = [
  // Ladyfinger (rect)
  function(ctx,x,y,s,a){
    ctx.save(); ctx.globalAlpha=a;
    ctx.translate(x,y); ctx.rotate(Math.random()*Math.PI);
    ctx.fillStyle='#7a3c10';
    ctx.beginPath(); ctx.roundRect(-s*1.4,-s*.35,s*2.8,s*.7,2); ctx.fill();
    ctx.fillStyle='rgba(220,170,120,0.4)';
    for(let i=0;i<4;i++){ctx.beginPath();ctx.arc(-s*.9+i*s*.6,0,s*.08,0,Math.PI*2);ctx.fill();}
    ctx.restore();
  },
  // Cream blob
  function(ctx,x,y,s,a){
    ctx.save(); ctx.globalAlpha=a;
    ctx.translate(x,y);
    ctx.fillStyle='rgba(240,236,228,0.9)';
    for(let i=0;i<3;i++){ctx.beginPath();ctx.arc((i-1)*s*.5,i===1?-s*.2:0,s*.45,0,Math.PI*2);ctx.fill();}
    ctx.restore();
  },
  // Coffee drop
  function(ctx,x,y,s,a){
    ctx.save(); ctx.globalAlpha=a;
    ctx.fillStyle='rgba(42,18,5,0.85)';
    ctx.beginPath(); ctx.arc(x,y,s*.4,0,Math.PI*2); ctx.fill();
    ctx.fillStyle='rgba(160,90,30,0.5)';
    ctx.beginPath(); ctx.arc(x-s*.1,y-s*.12,s*.12,0,Math.PI*2); ctx.fill();
    ctx.restore();
  },
  // Star cocoa
  function(ctx,x,y,s,a){
    ctx.save(); ctx.globalAlpha=a; ctx.translate(x,y);
    ctx.fillStyle='rgba(61,26,0,0.8)';
    ctx.beginPath();
    for(let i=0;i<5;i++){
      const ang=(i*4*Math.PI/5)-Math.PI/2;
      const r=i%2===0?s*.45:s*.2;
      if(i===0)ctx.moveTo(r*Math.cos(ang),r*Math.sin(ang));
      else ctx.lineTo(r*Math.cos(ang),r*Math.sin(ang));
    }
    ctx.closePath(); ctx.fill();
    ctx.restore();
  },
  // Tiny jar
  function(ctx,x,y,s,a){
    ctx.save(); ctx.globalAlpha=a; ctx.translate(x,y);
    ctx.strokeStyle='#c8824a'; ctx.lineWidth=1.5; ctx.fillStyle='rgba(200,130,74,0.15)';
    ctx.beginPath(); ctx.roundRect(-s*.5,-s*.7,s,s*1.2,2); ctx.fill(); ctx.stroke();
    ctx.fillStyle='#8b5e3c'; ctx.fillRect(-s*.5,-s*.78,s,s*.14);
    ctx.restore();
  },
];

const WORDS = ['espresso','mascarpone','savoiardi','cocoa','tiramisu','Iramisu','creamy','layered','fresh','handmade'];

class CParticle {
  constructor(x,y){
    this.x=x; this.y=y;
    this.shapeIdx=Math.floor(Math.random()*SHAPES.length);
    this.vx=(Math.random()-.5)*7;
    this.vy=-(Math.random()*7+3);
    this.gravity=.22;
    this.s=Math.random()*9+5;
    this.life=1;
    this.decay=Math.random()*.018+.012;
    this.rot=Math.random()*Math.PI*2;
    this.rotV=(Math.random()-.5)*.12;
  }
  update(){
    this.x+=this.vx; this.y+=this.vy; this.vy+=this.gravity;
    this.rot+=this.rotV; this.life-=this.decay; this.vx*=.99;
    return this.life>0;
  }
  draw(ctx){
    ctx.save(); ctx.translate(this.x,this.y); ctx.rotate(this.rot);
    SHAPES[this.shapeIdx](ctx,0,0,this.s,this.life);
    ctx.restore();
  }
}

class FloatWord {
  constructor(x,y,word){
    this.x=x; this.y=y; this.word=word;
    this.vy=-(Math.random()*1.5+1.2);
    this.vx=(Math.random()-.5)*1.2;
    this.life=1; this.decay=.016;
    this.size=Math.random()*5+10;
  }
  update(){ this.x+=this.vx; this.y+=this.vy; this.life-=this.decay; return this.life>0; }
  draw(ctx){
    ctx.save();
    ctx.globalAlpha=this.life;
    ctx.fillStyle='#c8824a';
    ctx.font=`italic ${this.size}px 'Playfair Display',serif`;
    ctx.fillText(this.word,this.x,this.y);
    ctx.restore();
  }
}

const floatWords = [];

function burst(x,y,n=14){
  for(let i=0;i<n;i++) cParticles.push(new CParticle(x,y));
  if(Math.random()<.6){
    const w=WORDS[Math.floor(Math.random()*WORDS.length)];
    floatWords.push(new FloatWord(x+(Math.random()-.5)*60,y-10,w));
  }
}

function animCC(){
  cctx.clearRect(0,0,ccW,ccH);
  for(let i=cParticles.length-1;i>=0;i--){
    if(!cParticles[i].update()) cParticles.splice(i,1);
    else cParticles[i].draw(cctx);
  }
  for(let i=floatWords.length-1;i>=0;i--){
    if(!floatWords[i].update()) floatWords.splice(i,1);
    else floatWords[i].draw(cctx);
  }
  requestAnimationFrame(animCC);
}
animCC();

document.addEventListener('click', e => {
  if(e.target.closest('button')||e.target.closest('a')||e.target.closest('.mc')||e.target.closest('.mo-box')) {
    burst(e.clientX,e.clientY,8);
    return;
  }
  burst(e.clientX,e.clientY,18);
});

// ══════════════════════════════════════════
//  LOADER
// ══════════════════════════════════════════
const lSubs = ['soaking the ladyfingers…','whipping the mascarpone…','layering with love…','dusting cocoa…','almost ready! 😋'];
function runLoader(){
  const layers=['ll1','ll2','ll3','ll4','ll5'];
  let i=0;
  const iv=setInterval(()=>{
    if(i<layers.length){
      document.getElementById(layers[i]).classList.add('on');
      document.getElementById('lsub').textContent=lSubs[i]||lSubs[lSubs.length-1];
      document.getElementById('lbar').style.width=((i+1)/layers.length*80)+'%';
      i++;
    } else {
      clearInterval(iv);
      document.getElementById('lface').classList.add('on');
      document.getElementById('lbar').style.width='100%';
      document.getElementById('lsub').textContent='ready! 😋';
      setTimeout(()=>{
        document.getElementById('loader').classList.add('out');
        setTimeout(()=>{
          document.getElementById('loader').style.display='none';
          initHome();
        },900);
      },650);
    }
  },430);
}
runLoader();

// ══════════════════════════════════════════
//  NAV
// ══════════════════════════════════════════
window.addEventListener('scroll',()=>document.getElementById('nav').classList.toggle('scrolled',scrollY>40));

function go(id){
  document.querySelectorAll('.pg').forEach(p=>p.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  document.querySelectorAll('.nav-links a').forEach(a=>a.classList.remove('active'));
  const nl=document.getElementById('nl-'+id);
  if(nl) nl.classList.add('active');
  window.scrollTo(0,0);
  if(id==='menu') buildMenu();
  if(id==='game') initGameIdle();
}

// ══════════════════════════════════════════
//  TOAST
// ══════════════════════════════════════════
let toastTimer;
function toast(msg){
  const t=document.getElementById('toast');
  t.textContent=msg; t.classList.add('on');
  clearTimeout(toastTimer);
  toastTimer=setTimeout(()=>t.classList.remove('on'),2800);
}

// ══════════════════════════════════════════
//  CART
// ══════════════════════════════════════════
let cart=[];
function toggleCart(){
  document.getElementById('cartDrawer').classList.toggle('open');
  renderCart();
}
function renderCart(){
  const el=document.getElementById('cartItems');
  const tot=document.getElementById('cartTotal');
  if(cart.length===0){
    el.innerHTML='<div class="cd-empty">Your cart is empty.<br>Add some tiramisu! 🍮</div>';
    tot.style.display='none'; return;
  }
  el.innerHTML=cart.map((item,i)=>`
    <div class="cd-item">
      <div>
        <div class="cd-item-name">${item.name}</div>
        <div class="cd-item-det">${item.size} · $${item.price}</div>
        <button class="cd-rm" onclick="removeCart(${i})">✕ remove</button>
      </div>
      <div class="cd-item-price">$${item.price}</div>
    </div>`).join('');
  const total=cart.reduce((s,i)=>s+i.price,0);
  document.getElementById('cartTotalNum').textContent='$'+total;
  tot.style.display='block';
  document.getElementById('cartNum').textContent=cart.length;
  document.getElementById('cartNumNav').textContent=cart.length;
}
function removeCart(i){
  cart.splice(i,1);
  renderCart();
  toast('Item removed 🗑️');
}
function checkout(){
  if(cart.length===0) return;
  const items=cart.map(i=>`${i.name} (${i.size}) - $${i.price}`).join('%0A');
  const total=cart.reduce((s,i)=>s+i.price,0);
  window.location.href=`mailto:hello@iramisu.ca?subject=Iramisu Order&body=Hi Iram!%0A%0AI'd like to order:%0A${items}%0A%0ATotal: $${total}%0A%0AName:%0APhone:%0APickup or Delivery:%0A%0AThanks!`;
}

// ══════════════════════════════════════════
//  HOME INIT
// ══════════════════════════════════════════
function initHome(){
  buildMarquee();
  drawHeroArt();
  drawAboutArt();
  buildHeroParticles();
  buildFeatured();
}

function buildMarquee(){
  const items=[...FLAVORS.map(f=>f.name),'Egg-Free','Halifax','Handmade','Small Batch','Artisan','Fresh','Layered'];
  let h='';
  for(let i=0;i<3;i++) items.forEach(it=>{ h+=`<span class="mq-item">${it}<span style="opacity:.4;margin:0 .3rem">✦</span></span>`; });
  document.getElementById('mq').innerHTML=h;
}

function buildFeatured(){
  const grid=document.getElementById('featGrid');
  FEATURED_IDS.forEach(id=>{
    const f=FLAVORS.find(x=>x.id===id);
    if(!f) return;
    const d=document.createElement('div');
    d.className='feat-card';
    d.onclick=()=>{go('menu');setTimeout(()=>openModal(id),200);};
    d.innerHTML=`<div class="feat-name">${f.name}</div><div class="feat-sub">${f.sub}</div><div class="feat-price">from $${f.prices.mini}</div>`;
    grid.appendChild(d);
  });
}

function drawHeroArt(){
  const c=document.getElementById('heroC'); if(!c) return;
  const ctx=c.getContext('2d'); const W=200,H=280;
  // Shadow
  ctx.fillStyle='rgba(0,0,0,.25)'; ctx.beginPath(); ctx.ellipse(100,268,70,10,0,0,Math.PI*2); ctx.fill();
  // Dish
  ctx.fillStyle='#c8a07a';
  ctx.beginPath(); ctx.moveTo(20,250); ctx.lineTo(180,250); ctx.lineTo(190,264); ctx.lineTo(10,264); ctx.closePath(); ctx.fill();
  // Layers
  const lrs=[{h:30,c:'#5c2d0a'},{h:24,c:'#ede8e0'},{h:30,c:'#4a220a'},{h:24,c:'#f5f2ec'},{h:14,c:'#2a1205'}];
  let y=50;
  lrs.forEach(l=>{
    ctx.fillStyle=l.c;
    ctx.beginPath(); ctx.moveTo(20,y); ctx.lineTo(180,y); ctx.lineTo(175,y+l.h); ctx.lineTo(25,y+l.h); ctx.closePath(); ctx.fill();
    if(l.c==='#5c2d0a'||l.c==='#4a220a'){
      ctx.fillStyle='rgba(255,200,130,.12)';
      for(let i=0;i<5;i++){ctx.beginPath();ctx.arc(35+i*28,y+l.h/2,4,0,Math.PI*2);ctx.fill();}
    }
    ctx.fillStyle='rgba(255,255,255,.07)'; ctx.fillRect(22,y+2,155,5);
    y+=l.h;
  });
  // Cocoa dust
  ctx.fillStyle='rgba(61,26,0,.5)';
  for(let i=0;i<25;i++){ctx.beginPath();ctx.arc(25+Math.random()*150,45+Math.random()*18,Math.random()*2+.5,0,Math.PI*2);ctx.fill();}
}

function drawAboutArt(){
  const c=document.getElementById('aboutC'); if(!c) return;
  const ctx=c.getContext('2d'); const W=460,H=320;
  const g=ctx.createRadialGradient(230,160,10,230,160,220);
  g.addColorStop(0,'rgba(101,55,15,.2)'); g.addColorStop(1,'rgba(26,15,7,0)');
  ctx.fillStyle=g; ctx.fillRect(0,0,W,H);
  // Jar
  ctx.strokeStyle='#c8824a'; ctx.lineWidth=2;
  ctx.fillStyle='rgba(255,255,255,.04)';
  ctx.beginPath();
  ctx.moveTo(110,55);ctx.lineTo(350,55);ctx.quadraticCurveTo(365,57,368,75);
  ctx.lineTo(372,286);ctx.quadraticCurveTo(372,304,353,306);
  ctx.lineTo(107,306);ctx.quadraticCurveTo(88,304,88,286);
  ctx.lineTo(92,75);ctx.quadraticCurveTo(95,57,110,55);ctx.closePath();
  ctx.fill();ctx.stroke();
  // Lid
  ctx.fillStyle='#8b5e3c'; ctx.fillRect(100,42,260,20); ctx.strokeStyle='#c8a07a'; ctx.lineWidth=1.5; ctx.strokeRect(100,42,260,20);
  // Layers inside
  const jl=[{c:'#5c2d0a',h:40},{c:'#e8e0d0',h:34},{c:'#5c2d0a',h:40},{c:'#f0ece4',h:34},{c:'#2a1205',h:18}];
  let ly=78;
  jl.forEach(l=>{ctx.fillStyle=l.c;ctx.fillRect(92,ly,276,l.h);ly+=l.h;});
  // Label
  ctx.fillStyle='rgba(245,234,216,.85)'; ctx.font='italic 24px "Playfair Display",serif'; ctx.textAlign='center'; ctx.fillText('Iramisu',230,195);
  ctx.fillStyle='rgba(245,234,216,.35)'; ctx.font='11px sans-serif'; ctx.fillText('ARTISAN · EGG-FREE · HALIFAX',230,214);
  // Spoon
  ctx.strokeStyle='#c8a07a'; ctx.lineWidth=2.5;
  ctx.beginPath(); ctx.moveTo(355,75); ctx.lineTo(385,45); ctx.stroke();
  ctx.fillStyle='#c8a07a'; ctx.beginPath(); ctx.ellipse(389,42,10,7,Math.PI/4,0,Math.PI*2); ctx.fill();
}

function buildHeroParticles(){
  const c=document.getElementById('heroParts');
  ['rgba(200,130,74,.3)','rgba(212,168,83,.22)','rgba(107,58,31,.38)'].forEach(col=>{
    for(let i=0;i<8;i++){
      const el=document.createElement('div'); el.className='hpt';
      const s=Math.random()*4+1;
      el.style.cssText=`width:${s}px;height:${s}px;left:${Math.random()*100}%;background:${col};animation-duration:${9+Math.random()*11}s;animation-delay:${Math.random()*12}s;`;
      c.appendChild(el);
    }
  });
}

// ══════════════════════════════════════════
//  MENU
// ══════════════════════════════════════════
let menuBuilt=false;
function buildMenu(){
  if(menuBuilt) return; menuBuilt=true;
  const grid=document.getElementById('menuGrid');
  FLAVORS.forEach(f=>{
    const card=document.createElement('div');
    card.className='mc'; card.dataset.cat=f.cat;
    card.innerHTML=`
      <canvas class="mc-art" width="320" height="185" id="ca-${f.id}"></canvas>
      ${f.badge?`<div class="mc-badge">${f.badge}</div>`:''}
      <div class="mc-body">
        <div class="mc-name">${f.name}</div>
        <div class="mc-sub">${f.sub}<br><span style="font-size:11px;opacity:.65;">${f.layers.slice(0,3).join(' · ')}</span></div>
        <div class="mc-foot">
          <div><div class="mc-price">$${f.prices.regular}</div><div class="mc-sz">Regular jar</div></div>
          <button class="mc-add" onclick="openModal('${f.id}',event)">+</button>
        </div>
      </div>`;
    card.addEventListener('click', e=>{ if(!e.target.classList.contains('mc-add')) openModal(f.id,e); });
    grid.appendChild(card);
    setTimeout(()=>drawCardArt(f), 30);
  });

  document.querySelectorAll('.fb').forEach(btn=>{
    btn.addEventListener('click',function(){
      document.querySelectorAll('.fb').forEach(b=>b.classList.remove('on'));
      this.classList.add('on');
      const f=this.dataset.f;
      document.querySelectorAll('.mc').forEach(c=>{ c.style.display=(f==='all'||c.dataset.cat===f)?'':'none'; });
    });
  });
}

function drawCardArt(f){
  const c=document.getElementById('ca-'+f.id); if(!c) return;
  const ctx=c.getContext('2d'); const W=320,H=185;
  // BG gradient
  const bg=ctx.createLinearGradient(0,0,W,H);
  bg.addColorStop(0,adjustHex(f.c1,-15)); bg.addColorStop(1,adjustHex(f.c1,25));
  ctx.fillStyle=bg; ctx.fillRect(0,0,W,H);
  // Layer silhouettes
  const lh=22; const n=f.layers.length; const startY=20;
  f.layers.forEach((lyr,i)=>{
    const col=i%2===0?f.c1:f.c2;
    const xOff=30+i*5; const ww=W-60-i*10; const y=startY+i*(lh+5);
    ctx.fillStyle=col;
    ctx.beginPath();
    ctx.moveTo(xOff,y); ctx.lineTo(xOff+ww,y); ctx.lineTo(xOff+ww-5,y+lh); ctx.lineTo(xOff+5,y+lh);
    ctx.closePath(); ctx.fill();
    ctx.fillStyle='rgba(255,255,255,.07)'; ctx.fillRect(xOff+4,y+2,ww-8,4);
    // Label on layer
    ctx.fillStyle='rgba(255,255,255,.55)'; ctx.font='10px sans-serif'; ctx.textAlign='left';
    ctx.fillText(lyr,xOff+10,y+lh-6);
  });
  // Gradient overlay bottom
  const ov=ctx.createLinearGradient(0,H-55,0,H);
  ov.addColorStop(0,'rgba(0,0,0,0)'); ov.addColorStop(1,'rgba(0,0,0,.55)');
  ctx.fillStyle=ov; ctx.fillRect(0,H-55,W,55);
  // Jar icon
  ctx.font='28px serif'; ctx.fillText('🫙',W-46,H-14);
  // Cocoa dust
  ctx.fillStyle='rgba(61,26,0,.4)';
  for(let i=0;i<20;i++){ctx.beginPath();ctx.arc(30+Math.random()*(W-60),18+Math.random()*(n*(lh+5)),Math.random()*1.8+.5,0,Math.PI*2);ctx.fill();}
}

function adjustHex(hex,amt){
  const n=parseInt(hex.slice(1),16);
  const r=Math.min(255,Math.max(0,(n>>16)+amt));
  const g=Math.min(255,Math.max(0,((n>>8)&0xFF)+amt));
  const b=Math.min(255,Math.max(0,(n&0xFF)+amt));
  return '#'+((1<<24)+(r<<16)+(g<<8)+b).toString(16).slice(1);
}

// ══════════════════════════════════════════
//  MODAL
// ══════════════════════════════════════════
let curF=null, curSz='regular';
function openModal(id,e){
  if(e) e.stopPropagation();
  const f=FLAVORS.find(x=>x.id===id); if(!f) return;
  curF=f; curSz='regular';
  document.getElementById('moName').textContent=f.name;
  document.getElementById('moSub').textContent=f.sub;
  document.getElementById('moDesc').textContent=f.desc;
  document.getElementById('moLayers').innerHTML=f.layers.map(l=>`<span class="mo-pill">${l}</span>`).join('');
  const szs=[{k:'mini',l:'Mini',n:'~200ml'},{k:'regular',l:'Regular',n:'~350ml'},{k:'large',l:'Large',n:'~500ml'}];
  document.getElementById('moSizes').innerHTML=szs.map(s=>`
    <div class="sz ${s.k==='regular'?'sel':''}" onclick="selSz('${s.k}',this)">
      <div style="font-weight:500">${s.l}</div>
      <div style="font-size:11px;opacity:.7">$${f.prices[s.k]} · ${s.n}</div>
    </div>`).join('');
  document.getElementById('mo').classList.add('open');
}
function selSz(k,el){ curSz=k; document.querySelectorAll('.sz').forEach(e=>e.classList.remove('sel')); el.classList.add('sel'); }
function closeMo(e){ if(e&&e.target!==document.getElementById('mo')) return; document.getElementById('mo').classList.remove('open'); }
function addToCart(){
  if(!curF) return;
  cart.push({name:curF.name,size:curSz,price:curF.prices[curSz]});
  document.getElementById('cartNum').textContent=cart.length;
  document.getElementById('cartNumNav').textContent=cart.length;
  document.getElementById('mo').classList.remove('open');
  toast(`${curF.name} (${curSz}) added! 🛒`);
  burst(window.innerWidth/2,window.innerHeight/2,10);
}

// ══════════════════════════════════════════
//  CONTACT
// ══════════════════════════════════════════
function submitOrder(){
  const n=document.getElementById('cn').value.trim();
  const e=document.getElementById('ce').value.trim();
  const o=document.getElementById('co').value.trim();
  if(!n||!e||!o){ toast('Please fill in name, email, and order details.'); return; }
  toast(`Thank you ${n}! Iram will confirm within 24 hrs 💌`);
  ['cn','ce','cp','co','cnotes'].forEach(id=>document.getElementById(id).value='');
  burst(window.innerWidth/2,300,20);
}

// ══════════════════════════════════════════
//  GAME — Tiramisu Stacker
// ══════════════════════════════════════════
const INGR=[
  {name:'Ladyfinger',c:'#7a3c10',c2:'#c8a07a'},
  {name:'Mascarpone',c:'#e8e0d0',c2:'#f5f2ec'},
  {name:'Espresso',c:'#2a1205',c2:'#5c2d0a'},
  {name:'Cocoa',c:'#3d1a00',c2:'#7a3a10'},
  {name:'Cream',c:'#f0ece4',c2:'#faf8f4'},
];

let gRunning=false,gState={},gRAF,gHighScore=0;

function initGameIdle(){
  const canvas=document.getElementById('gc'); if(!canvas) return;
  const ctx=canvas.getContext('2d'); const W=640,H=400;
  ctx.clearRect(0,0,W,H);
  ctx.fillStyle='#0d0803'; ctx.fillRect(0,0,W,H);
  // Grid
  ctx.strokeStyle='rgba(200,130,74,.04)'; ctx.lineWidth=1;
  for(let x=0;x<W;x+=40){ctx.beginPath();ctx.moveTo(x,0);ctx.lineTo(x,H);ctx.stroke();}
  for(let y=0;y<H;y+=40){ctx.beginPath();ctx.moveTo(0,y);ctx.lineTo(W,y);ctx.stroke();}
  ctx.fillStyle='#c8824a'; ctx.font='italic bold 30px "Playfair Display",serif'; ctx.textAlign='center';
  ctx.fillText('Stack the Tiramisu!',W/2,H/2-20);
  ctx.font='14px sans-serif'; ctx.fillStyle='rgba(245,234,216,.5)';
  ctx.fillText('Press ▶ Start Game to play',W/2,H/2+14);
  ctx.font='44px serif'; ctx.fillText('🍮',W/2,H/2+72);
}

function gStart(){
  if(gRunning){ gRestart(); return; }
  gRunning=true;
  document.getElementById('gStartBtn').textContent='↺ Restart';

  const canvas=document.getElementById('gc');
  const W=640,H=400,ctx=canvas.getContext('2d');
  const BASE_Y=H-55;

  gState={
    score:0,layers:0,misses:0,phase:'playing',
    pieceW:140,pieceH:28,pieceVX:2.4,
    piece:null,stack:[],particles:[],
  };

  function spawnPiece(){
    const ing=INGR[gState.layers%INGR.length];
    gState.piece={
      x:W/2,y:55,w:gState.pieceW,h:gState.pieceH,
      c:ing.c,c2:ing.c2,name:ing.name,
      vx:gState.pieceVX*(Math.random()>.5?1:-1),vy:0,falling:false,
    };
  }

  function drop(){
    if(!gRunning||gState.phase!=='playing') return;
    if(gState.piece&&!gState.piece.falling){
      gState.piece.falling=true; gState.piece.vy=5;
    }
  }

  canvas.onclick=drop;
  const kd=e=>{ if(e.code==='Space'&&gRunning){e.preventDefault();drop();} };
  document.addEventListener('keydown',kd);

  function spawnParts(x,y,col,n=12){
    for(let i=0;i<n;i++){
      gState.particles.push({
        x,y,vx:(Math.random()-.5)*6,vy:-(Math.random()*4+1),
        life:1,decay:.035+Math.random()*.02,c:col,r:Math.random()*4+2
      });
    }
  }

  function update(){
    if(!gRunning||!gState.piece) return;
    const p=gState.piece;
    if(!p.falling){
      p.x+=p.vx;
      if(p.x+p.w/2>=W-16||p.x-p.w/2<=16) p.vx*=-1;
    } else {
      p.y+=p.vy;
      const topY=gState.stack.length>0?gState.stack[gState.stack.length-1].y-p.h:BASE_Y-p.h;
      if(p.y>=topY){
        p.y=topY;
        const top=gState.stack.length>0?gState.stack[gState.stack.length-1]:null;
        let nw=p.w;
        if(top){
          const L=Math.max(p.x-p.w/2,top.x-top.w/2);
          const R=Math.min(p.x+p.w/2,top.x+top.w/2);
          const ov=R-L;
          if(ov<=0){
            gState.misses++;
            spawnParts(p.x,p.y,'#e84444',8);
            if(gState.misses>=3){endGame(false);return;}
            spawnPiece(); return;
          }
          nw=ov; p.x=(L+R)/2; p.w=nw;
          const diff=Math.abs(p.x-top.x);
          const pts=diff<12?25:diff<30?15:8;
          gState.score+=pts;
          if(diff<12) toast('Perfect layer! +25 ✨');
          else if(diff<30) toast('Good! +15');
        } else { gState.score+=15; }
        gState.pieceW=Math.max(38,nw);
        spawnParts(p.x,topY+p.h/2,p.c,10);
        gState.stack.push({x:p.x,y:topY,w:nw,h:p.h,c:p.c,c2:p.c2,name:p.name});
        gState.layers++;
        document.getElementById('gsc').textContent=gState.score;
        document.getElementById('glc').textContent=gState.layers;
        gState.pieceVX=Math.min(6,2.4+gState.layers*.28);
        if(gState.layers>=8){endGame(true);return;}
        spawnPiece();
      }
    }
    gState.particles=gState.particles.filter(pt=>pt.life>0);
    gState.particles.forEach(pt=>{pt.x+=pt.vx;pt.y+=pt.vy;pt.vy+=.18;pt.life-=pt.decay;});
  }

  function draw(){
    ctx.clearRect(0,0,W,H);
    ctx.fillStyle='#0d0803'; ctx.fillRect(0,0,W,H);
    // Grid
    ctx.strokeStyle='rgba(200,130,74,.04)'; ctx.lineWidth=1;
    for(let x=0;x<W;x+=40){ctx.beginPath();ctx.moveTo(x,0);ctx.lineTo(x,H);ctx.stroke();}
    // Base
    ctx.fillStyle='#8b5e3c'; ctx.fillRect(40,BASE_Y,W-80,20);
    ctx.fillStyle='#c8a07a'; ctx.fillRect(40,BASE_Y,W-80,5);
    // Stack
    gState.stack.forEach(s=>{
      ctx.fillStyle=s.c; ctx.fillRect(s.x-s.w/2,s.y,s.w,s.h);
      ctx.fillStyle='rgba(255,255,255,.08)'; ctx.fillRect(s.x-s.w/2+3,s.y+2,s.w-6,4);
      ctx.strokeStyle='rgba(255,255,255,.08)'; ctx.lineWidth=.5; ctx.strokeRect(s.x-s.w/2,s.y,s.w,s.h);
      ctx.fillStyle='rgba(245,234,216,.55)'; ctx.font='9px sans-serif'; ctx.textAlign='center';
      if(s.w>60) ctx.fillText(s.name,s.x,s.y+s.h-5);
    });
    // Piece
    const p=gState.piece;
    if(p){
      ctx.fillStyle=p.c; ctx.fillRect(p.x-p.w/2,p.y,p.w,p.h);
      ctx.fillStyle='rgba(255,255,255,.1)'; ctx.fillRect(p.x-p.w/2+3,p.y+2,p.w-6,5);
      ctx.strokeStyle='rgba(200,130,74,.6)'; ctx.lineWidth=1.5; ctx.strokeRect(p.x-p.w/2,p.y,p.w,p.h);
      ctx.fillStyle='rgba(245,234,216,.8)'; ctx.font='11px sans-serif'; ctx.textAlign='center';
      ctx.fillText(p.name,p.x,p.y+p.h/2+4);
      if(!p.falling){
        const tY=gState.stack.length>0?gState.stack[gState.stack.length-1].y:BASE_Y;
        ctx.strokeStyle='rgba(200,130,74,.12)'; ctx.setLineDash([4,5]);
        ctx.beginPath(); ctx.moveTo(p.x,p.y+p.h); ctx.lineTo(p.x,tY); ctx.stroke();
        ctx.setLineDash([]);
      }
    }
    // Particles
    gState.particles.forEach(pt=>{
      ctx.globalAlpha=pt.life; ctx.fillStyle=pt.c;
      ctx.beginPath(); ctx.arc(pt.x,pt.y,pt.r,0,Math.PI*2); ctx.fill();
    }); ctx.globalAlpha=1;
    // HUD
    ctx.font='15px serif'; ctx.textAlign='left';
    for(let i=0;i<3;i++) ctx.fillText(i<(3-gState.misses)?'❤️':'🖤',14+i*22,22);
    ctx.fillStyle='rgba(200,130,74,.7)'; ctx.font='11px sans-serif'; ctx.textAlign='right';
    ctx.fillText('LAYERS: '+gState.stack.length+'/8',W-14,22);
    // Progress bar
    const pct=gState.stack.length/8;
    ctx.fillStyle='rgba(200,130,74,.15)'; ctx.fillRect(14,H-20,W-28,6);
    ctx.fillStyle='#c8824a'; ctx.fillRect(14,H-20,(W-28)*pct,6);
    if(gState.phase!=='playing') drawOverlay(ctx,W,H);
    if(gRunning||gState.phase!=='playing'){ update(); gRAF=requestAnimationFrame(draw); }
  }
  gRAF=requestAnimationFrame(draw);
  spawnPiece();
}

function drawOverlay(ctx,W,H){
  ctx.fillStyle='rgba(0,0,0,.75)'; ctx.fillRect(0,0,W,H);
  if(gState.phase==='win'){
    ctx.fillStyle='#d4a853'; ctx.font='italic bold 32px "Playfair Display",serif'; ctx.textAlign='center';
    ctx.fillText('🎉 Perfect Tiramisu! 🎉',W/2,H/2-30);
    ctx.font='16px sans-serif'; ctx.fillStyle='#f5ead8';
    ctx.fillText('Use code IRAMISU10 for 10% off',W/2,H/2+10);
    ctx.fillStyle='rgba(245,234,216,.5)'; ctx.font='13px sans-serif';
    ctx.fillText('Show this screen when ordering!',W/2,H/2+36);
  } else {
    ctx.fillStyle='#c8824a'; ctx.font='italic bold 30px "Playfair Display",serif'; ctx.textAlign='center';
    ctx.fillText('The tower tumbled! 🍮',W/2,H/2-20);
    ctx.font='15px sans-serif'; ctx.fillStyle='rgba(245,234,216,.7)';
    ctx.fillText('Score: '+gState.score+' · Press Restart to try again',W/2,H/2+18);
  }
}

function endGame(won){
  gRunning=false; gState.phase=won?'win':'over';
  if(gState.score>gHighScore){ gHighScore=gState.score; document.getElementById('ghc').textContent=gHighScore; }
  if(won) toast('You won! Code: IRAMISU10 — 10% off! 🎉');
  else toast('Game over! Score: '+gState.score+'. Try again? 💪');
}
function gRestart(){
  gRunning=false; cancelAnimationFrame(gRAF);
  document.getElementById('gsc').textContent='0';
  document.getElementById('glc').textContent='0';
  document.getElementById('gStartBtn').textContent='▶ Start Game';
  document.getElementById('gStartBtn').onclick=gStart;
  gRunning=false;
  initGameIdle();
  setTimeout(gStart,100);
}
</script>
</body>
</html>
