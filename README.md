<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>ProHelmet — Smart Helmet Cleaning Kiosk</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <style>
    :root{
      --bg:#000;            /* black background */
      --text:#f5f5f5;       /* basic text */
      --muted:#c9c9c9;
      --teal:#14b8b6;       /* headers & links (teal) */
      --line:#1f2937;       /* subtle divider */
      --wrap:940px;
    }

    html,body{height:100%}
    html{scroll-behavior:smooth}
    body{
      margin:0;
      background:var(--bg);
      color:var(--text);
      font-family:"Georgia Pro", Georgia, "Times New Roman", serif; /* falls back if Georgia Pro isn't installed */
      line-height:1.6;
    }

    .wrap{max-width:var(--wrap); margin:0 auto; padding:18px 16px 72px}

    /* Header logo */
    header{padding:28px 0 8px; text-align:center}
    header img{max-width:420px; width:75%; height:auto; display:inline-block}

    /* Nav */
    .nav{
      position:sticky; top:0; z-index:10;
      background:rgba(0,0,0,.9);
      border-top:1px solid var(--line);
      border-bottom:1px solid var(--line);
    }
    .nav-inner{max-width:var(--wrap); margin:0 auto; padding:10px 16px; text-align:center}
    .nav a{
      color:var(--teal); text-decoration:none; padding:6px 8px; margin:0 6px; border-radius:8px;
    }
    .nav a:hover, .nav a:focus{background:#0b0f14; outline:none; text-decoration:underline; text-underline-offset:3px}
    .bar{color:var(--muted); margin:0 2px; user-select:none}

    /* Sections */
    section{scroll-margin-top:84px; padding:26px 0; border-bottom:1px solid var(--line)}
    h1,h2{color:var(--teal); margin:0 0 10px; line-height:1.25}
    p{margin:0 0 12px}
    ul{margin:8px 0 12px 20px}
    li{margin:6px 0}

    /* Footer */
    footer{text-align:center; color:var(--muted); padding:26px 0 8px; font-size:.95rem}

    @media (max-width:520px){
      header img{width:88%}
      .nav-inner{font-size:0.98rem}
    }
  </style>
</head>
<body>

  <div class="wrap">
    <!-- Top logo -->
    <header>
      <!-- If you place the file elsewhere, update the src path -->
      <img src="assets/ProHelmet3.png" alt="ProHelmet logo">
    </header>
  </div>

  <!-- Sticky in-page nav -->
  <nav class="nav" aria-label="Section navigation">
    <div class="nav-inner">
      <a href="#about">About ProHelmet</a><span class="bar">|</span>
      <a href="#pricing">Pricing</a><span class="bar">|</span>
      <a href="#privacy">Privacy Policy</a><span class="bar">|</span>
      <a href="#terms">Terms</a><span class="bar">|</span>
      <a href="#refunds">Refunds</a><span class="bar">|</span>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <div class="wrap">
    <!-- About -->
    <section id="about">
      <h2>About ProHelmet</h2>
      <p>Your helmet protects you every day – but keeping it clean, fresh, and germ-free is often a hassle. ProHelmet makes it effortless.</p>
      <p>A dirty helmet isn’t just uncomfortable – it can cause bad odor, skin irritation, dandruff, hair fall, and even bacterial growth that affects your health. ProHelmet takes away these worries by giving your helmet a hygienic deep clean in just a few minutes.</p>
      <p>No mess, no waiting, no complicated steps – simply place your helmet in, let the machine do its work, and enjoy a helmet that feels as good as new.</p>
      <p>Because cleanliness is not OCD, “Cleanliness is Godliness.”</p>
      <p>ProHelmet isn’t just about cleaning – it’s about confidence, hygiene, and care for something you use every single day.</p>
    </section>

    <!-- Pricing -->
    <section id="pricing">
      <h2>Pricing</h2>
      <p>Keeping your helmet fresh and germ-free doesn’t have to be expensive. ProHelmet offers a professional deep clean at a very low cost – so anyone can afford to ride with confidence.</p>
      <p>We recommend giving your helmet a clean once every 15 days to maintain hygiene, freshness, and comfort.</p>
      <p>For business owners who wish to set up a ProHelmet Kiosk and offer this service to riders, please call us at <strong>9849080443</strong> for a customized quote.</p>
    </section>

    <!-- Privacy Policy -->
    <section id="privacy">
      <h2>Privacy Policy</h2>
      <p>At ProHelmet, we respect your privacy.</p>
      <p>We don’t collect personal information unless you share it with us (for example, when you contact us or make a payment).</p>
      <p>Any info you provide is used only to serve you better—like processing payments or replying to your messages.</p>
      <p>We don’t sell, rent, or share your information with third parties.</p>
      <p>Payments are processed securely by trusted partners such as Razorpay. We do not store your card or bank details.</p>
      <p>Our site may use basic cookies or logs to improve your experience. We do not track sensitive personal data.</p>
      <p>By using ProHelmet, you agree to this privacy policy.</p>
      <p>Questions? Call <strong>9849080443</strong> or email <strong>prohelmet.protoptye@gmail.com</strong>.</p>
    </section>

    <!-- Terms -->
    <section id="terms">
      <h2>Terms &amp; Conditions</h2>

      <h3 style="color:var(--teal); margin-top:6px">Service Use</h3>
      <ul>
        <li>ProHelmet sanitizes and refreshes helmets.</li>
        <li>It is not intended to remove existing stains, scratches, or marks.</li>
        <li>For best upkeep, please wipe your helmet daily between sanitizing cycles.</li>
      </ul>

      <h3 style="color:var(--teal)">Automation &amp; Connectivity</h3>
      <ul>
        <li>The machine is fully automated. If there are brief lags or connectivity glitches, please allow the system a moment to recover and follow on-screen instructions patiently.</li>
        <li>If a cycle does not start or complete due to a technical issue, reach out to us right away.</li>
      </ul>

      <h3 style="color:var(--teal)">Payments</h3>
      <ul>
        <li>Payments are processed securely by trusted partners such as Razorpay. We do not store card or bank details.</li>
        <li>If you face any payment issue (failed/duplicate charge, charged but service not delivered), contact us immediately for checks and prompt refunds when applicable.</li>
        <li>Once a cleaning cycle has successfully begun, payments are generally non-refundable.</li>
      </ul>

      <h3 style="color:var(--teal)">Liability</h3>
      <ul>
        <li>We handle your helmet with care, but we are not responsible for pre-existing damage, normal wear and tear, or user mishandling.</li>
      </ul>

      <h3 style="color:var(--teal)">Public Use</h3>
      <ul>
        <li>ProHelmet kiosks are placed in unmanned public spaces. Please use them responsibly.</li>
        <li>Intentional misuse or damage may lead to necessary legal action.</li>
      </ul>

      <h3 style="color:var(--teal)">Business Owners</h3>
      <ul>
        <li>For kiosk setups, pricing and terms may vary. Contact <strong>9849080443</strong> or <strong>prohelmet.protoptye@gmail.com</strong> for a customized agreement.</li>
      </ul>

      <h3 style="color:var(--teal)">Updates</h3>
      <p>We may update these terms from time to time. Continued use means you accept the latest version.</p>
    </section>

    <!-- Refunds -->
    <section id="refunds">
      <h2>Refunds</h2>
      <p>At ProHelmet, we believe in being fair and transparent.</p>

      <h3 style="color:var(--teal); margin-top:6px">For Users</h3>
      <ul>
        <li>Once a cleaning cycle successfully begins, the payment is non-refundable.</li>
        <li>If your payment is charged but the cycle does not start, please contact us immediately at <strong>9849080443</strong> or <strong>prohelmet.protoptye@gmail.com</strong>. We will verify and process a refund promptly.</li>
        <li>Refunds are always returned through the same payment method you used.</li>
      </ul>

      <h3 style="color:var(--teal)">For Business Owners</h3>
      <ul>
        <li>Advance payments or kiosk setup fees are subject to the specific agreement shared at the time of onboarding.</li>
        <li>Refunds (if any) will follow the terms of that agreement.</li>
        <li>For any concerns, please reach out to us directly at <strong>9849080443</strong> or <strong>prohelmet.protoptye@gmail.com</strong>.</li>
      </ul>
    </section>

    <!-- Contact -->
    <section id="contact">
      <h2>Contact</h2>
      <p>📞 Call us: <strong>9849080443</strong><br>
         📧 Email us: <strong>prohelmet.protoptye@gmail.com</strong></p>
    </section>

    <footer>
      © <span id="y"></span> ProHelmet. All rights reserved.
    </footer>
  </div>

  <script>document.getElementById('y').textContent=new Date().getFullYear()</script>
</body>
</html>
