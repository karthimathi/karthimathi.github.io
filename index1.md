<!--
  index.html - Jekyll-friendly single-file layout with attractive CSS
  How to use:
  1. Save this as `index.html` in your GitHub Pages repo (or convert to index.md).
  2. Replace IMAGE_URL and AFFILIATE_LINK placeholders for each product.
  3. If using Jekyll, move the <style> block to /assets/css/style.css and add
     <link rel="stylesheet" href="/assets/css/style.css"> inside your Jekyll layout.
-->

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Best Amazon Deals</title>
  <meta name="description" content="Handpicked Amazon affiliate products with the best reviews and deals." />

  <style>
    :root{
      --bg:#0f1724; /* deep navy */
      --card:#0b1220;
      --muted:#9aa6b2;
      --accent:#ff6b6b; /* coral */
      --accent-2:#4fd1c5; /* teal */
      --glass: rgba(255,255,255,0.04);
      --radius:16px;
      --max:1100px;
      --gap:18px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }

    html,body{height:100%;margin:0;background:linear-gradient(180deg,#071024 0%, #071226 55%, #07182c 100%);color:#e6eef6}
    .wrap{max-width:var(--max);margin:36px auto;padding:28px;border-radius:20px;background:linear-gradient(180deg,rgba(255,255,255,0.02), rgba(255,255,255,0.01));box-shadow:0 10px 30px rgba(2,6,23,0.6)}

    header{display:flex;align-items:center;gap:18px;margin-bottom:18px}
    .logo{width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;font-weight:700;color:#061321;box-shadow:0 6px 18px rgba(79,209,197,0.12)}
    h1{margin:0;font-size:22px}
    p.lead{color:var(--muted);margin:6px 0 0 0}

    .controls{display:flex;gap:10px;margin-left:auto}
    .chip{background:var(--glass);padding:8px 12px;border-radius:999px;font-size:13px;color:var(--muted)}

    .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:var(--gap);margin-top:22px}
    .card{background:linear-gradient(180deg,rgba(255,255,255,0.015), rgba(255,255,255,0.01));border-radius:var(--radius);overflow:hidden;padding:12px;border:1px solid rgba(255,255,255,0.02);transition:transform .18s ease, box-shadow .18s ease}
    .card:hover{transform:translateY(-6px);box-shadow:0 18px 40px rgba(2,6,23,0.6)}

    .thumb{width:100%;height:160px;object-fit:contain;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));display:block;border-radius:10px}
    .meta{display:flex;align-items:center;justify-content:space-between;margin-top:10px}
    .title{font-size:15px;margin:0 0 6px 0}
    .desc{color:var(--muted);font-size:13px;margin:0 0 12px 0}

    .price-row{display:flex;align-items:center;gap:10px}
    .price{font-weight:700;color:#fff}
    .old{color:var(--muted);text-decoration:line-through;font-size:13px}

    .actions{display:flex;gap:8px}
    .btn{flex:1;padding:10px 12px;border-radius:10px;text-align:center;text-decoration:none;font-weight:600}
    .btn-cta{background:linear-gradient(90deg,var(--accent),var(--accent-2));color:#08131b}
    .btn-secondary{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--muted)}

    footer{margin-top:26px;color:var(--muted);font-size:13px;text-align:center}

    /* Responsive tweaks */
    @media (max-width:520px){.thumb{height:140px}.wrap{padding:18px}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo">JD</div>
      <div>
        <h1>🔥 Top 20 Amazon Products – Handpicked for You</h1>
        <p class="lead">A curated list of the best-rated products. We may earn a small commission when you buy through our links — at no extra cost to you.</p>
      </div>
      <div class="controls">
        <div class="chip">GitHub Pages • Jekyll</div>
        <div class="chip">20 Products</div>
      </div>
    </header>

    <main>
      <div class="grid">
        <!-- Product 1 -->
        <article class="card">
          <img class="thumb" src="/assets/images/earbuds.jpg" alt="Wireless Earbuds" />
          <h3 class="title">1. Wireless Earbuds</h3>
          <p class="desc">Great sound quality and long battery life.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹1,799</div><div class="old">₹2,499</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE1" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 2 -->
        <article class="card">
          <img class="thumb" src="/assets/images/smartwatch.jpg" alt="Smartwatch" />
          <h3 class="title">2. Smartwatch</h3>
          <p class="desc">Track fitness, heart rate, and receive notifications.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹2,999</div><div class="old">₹4,199</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE2" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 3 -->
        <article class="card">
          <img class="thumb" src="/assets/images/ringlight.jpg" alt="LED Ring Light" />
          <h3 class="title">3. LED Ring Light</h3>
          <p class="desc">Perfect for YouTube, Instagram, and Zoom calls.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹1,199</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE3" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 4 -->
        <article class="card">
          <img class="thumb" src="/assets/images/powerbank.jpg" alt="Power Bank" />
          <h3 class="title">4. Power Bank</h3>
          <p class="desc">Fast-charging and travel friendly.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹899</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE4" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 5 -->
        <article class="card">
          <img class="thumb" src="/assets/images/toothbrush.jpg" alt="Electric Toothbrush" />
          <h3 class="title">5. Electric Toothbrush</h3>
          <p class="desc">Advanced cleaning with smart timer.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹1,499</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE5" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 6 -->
        <article class="card">
          <img class="thumb" src="/assets/images/fryingpan.jpg" alt="Non-Stick Frying Pan" />
          <h3 class="title">6. Non-Stick Frying Pan</h3>
          <p class="desc">Easy to clean and perfect for daily cooking.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹899</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE6" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 7 -->
        <article class="card">
          <img class="thumb" src="/assets/images/minifridge.jpg" alt="Mini Fridge" />
          <h3 class="title">7. Mini Fridge</h3>
          <p class="desc">Compact and ideal for small rooms or office.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹5,499</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE7" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 8 -->
        <article class="card">
          <img class="thumb" src="/assets/images/trimmer.jpg" alt="Trimmer for Men" />
          <h3 class="title">8. Trimmer for Men</h3>
          <p class="desc">Smooth trim with skin protection.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹1,299</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE8" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 9 -->
        <article class="card">
          <img class="thumb" src="/assets/images/laptopstand.jpg" alt="Laptop Stand" />
          <h3 class="title">9. Laptop Stand</h3>
          <p class="desc">Ergonomic design for better posture.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹1,199</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE9" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 10 -->
        <article class="card">
          <img class="thumb" src="/assets/images/mouse.jpg" alt="Wireless Mouse" />
          <h3 class="title">10. Wireless Mouse</h3>
          <p class="desc">Comfortable grip with long battery life.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹599</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE10" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 11 -->
        <article class="card">
          <img class="thumb" src="/assets/images/pillow.jpg" alt="Memory Foam Pillow" />
          <h3 class="title">11. Memory Foam Pillow</h3>
          <p class="desc">Better sleep and neck support.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹1,699</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE11" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 12 -->
        <article class="card">
          <img class="thumb" src="/assets/images/tripod.jpg" alt="Tripod Stand" />
          <h3 class="title">12. Tripod Stand</h3>
          <p class="desc">Perfect for content creators and vloggers.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹999</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE12" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 13 -->
        <article class="card">
          <img class="thumb" src="/assets/images/controller.jpg" alt="Gamepad Controller" />
          <h3 class="title">13. Gamepad Controller</h3>
          <p class="desc">For Android or PC gaming.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹1,499</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE13" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 14 -->
        <article class="card">
          <img class="thumb" src="/assets/images/vacuum.jpg" alt="Vacuum Cleaner" />
          <h3 class="title">14. Vacuum Cleaner</h3>
          <p class="desc">Compact and powerful suction.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹2,999</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE14" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 15 -->
        <article class="card">
          <img class="thumb" src="/assets/images/skincare.jpg" alt="Skincare Kit" />
          <h3 class="title">15. Skincare Kit</h3>
          <p class="desc">For glowing and healthy skin.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹899</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE15" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 16 -->
        <article class="card">
          <img class="thumb" src="/assets/images/book.jpg" alt="Motivational Book" />
          <h3 class="title">16. Motivational Book</h3>
          <p class="desc">Boost your productivity and mindset.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹299</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE16" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 17 -->
        <article class="card">
          <img class="thumb" src="/assets/images/organizer.jpg" alt="Storage Organizer" />
          <h3 class="title">17. Storage Organizer</h3>
          <p class="desc">Space-saving and foldable.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹499</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE17" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 18 -->
        <article class="card">
          <img class="thumb" src="/assets/images/shoes.jpg" alt="Running Shoes" />
          <h3 class="title">18. Running Shoes</h3>
          <p class="desc">Comfortable, durable, and lightweight.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹2,199</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE18" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 19 -->
        <article class="card">
          <img class="thumb" src="/assets/images/kettle.jpg" alt="Electric Kettle" />
          <h3 class="title">19. Electric Kettle</h3>
          <p class="desc">Boil water quickly and safely.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹1,099</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE19" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

        <!-- Product 20 -->
        <article class="card">
          <img class="thumb" src="/assets/images/hairoil.jpg" alt="Hair Oil for Growth" />
          <h3 class="title">20. Hair Oil for Growth</h3>
          <p class="desc">Natural formula for healthy hair.</p>
          <div class="meta">
            <div class="price-row"><div class="price">₹449</div></div>
            <div class="actions"><a class="btn btn-cta" href="https://www.amazon.in/dp/YOUR_AFFILIATE_CODE20" target="_blank" rel="noopener">Buy on Amazon</a></div>
          </div>
        </article>

      </div>

      <footer>
        Thanks for visiting — bookmark this page and check back for deals and updates.
      </footer>
    </main>
  </div>
</body>
</html>
