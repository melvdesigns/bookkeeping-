<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- ✨ EDIT YOUR WEBSITE / BUSINESS NAME + LINK HERE ✨ -->
  <script>
    const siteName = "Melvin Jay Canoy"; // Change your website/business name
    // const siteLink removed // Change your website link/domain anytime

    document.addEventListener("DOMContentLoaded", () => {
      document.title = `${siteName} | Accounting & Bookkeeping`;
      document.getElementById("site-name").textContent = siteName;
      document.getElementById("footer-name").textContent = siteName;
      // removed site link display
      // removed site link display
    });
  </script>

  <style>
    :root { --primary:#0a2640; --secondary:#4a90e2; --text:#2a2a2a; --bg:#eef2f5; --card:#ffffff; }
    body { margin:0; font-family:"Segoe UI",sans-serif; background:var(--bg); color:var(--text); }
    header { background:linear-gradient(135deg,var(--primary),#154c7a); padding:80px 20px; text-align:center; color:white; box-shadow:0 4px 20px rgba(0,0,0,0.15); }
    header h1 { font-size:3rem; margin-bottom:8px; font-weight:600; }
    header p { font-size:1.2rem; opacity:.95; }
    .container { max-width:1000px; margin:40px auto; padding:0 20px; }
    section { background:var(--card); padding:36px; border-radius:12px; margin-bottom:32px; box-shadow:0 4px 12px rgba(0,0,0,0.08); border:1px solid #d8e0e8; }
    h2 { margin-top:0; font-size:1.9rem; color:var(--primary); font-weight:600; }
    ul li { margin-bottom:10px; font-size:1.05rem; }
    .btn { display:inline-block; margin:8px; padding:12px 26px; background:var(--primary); color:white; text-decoration:none; border-radius:6px; font-weight:500; transition:.3s; }
    .btn:hover { background:#1a537a; }
    .group-title { font-size:1.15rem; font-weight:600; margin-top:15px; margin-bottom:10px; color:var(--primary); }
    footer { text-align:center; padding:28px; color:white; background:var(--primary); margin-top:50px; font-size:.95rem; }
    a.site-url { color:#ffd; text-decoration:underline; }
  </style>
</head>
<body>

<header>
  <h1 id="site-name"></h1>
  <p> Accounting & Bookkeeping Services for Businesses</p>
  
</header>

<div class="container">

  <section>
    <h2>About Me</h2>
    <p>I am a bookkeeping and accounting professional with experience managing financial records, analyzing business transactions, and preparing accurate financial statements. I help businesses stay compliant, organized, and financially informed by maintaining clean and reliable books.</p>
  </section>

  <section>
    <h2>Services Offered</h2>
    <ul>
      <li>Complete Bookkeeping (Monthly / Weekly)</li>
      <li>Bank & Account Reconciliation</li>
      <li>Accounts Payable & Receivable Management</li>
      <li>Financial Statement Preparation & Reporting</li>
      <li>Payroll Processing & Recording</li>
      <li>Book Cleanup & Catch-Up for Backlogged Records</li>
    </ul>
  </section>

  <section>
    <h2>Contact & Social</h2>
    <p>For inquiries, collaboration, or service requests:</p>

    <div class="group-title">📩 Contact</div>
    <a class="btn" href="mailto:melvincanoy0929@gmail.com">Email Me</a>
    <a class="btn" href="https://wa.me/+639762268109" target="_blank">WhatsApp</a>

    <div class="group-title">🌐 Social Profiles</div>
    <a class="btn" href="https://facebook.com/melvinjaycanoy" target="_blank">Facebook</a>
    <a class="btn" href="https://www.instagram.com/itsm3lv_asusual?igsh=aW05emdtNWxmc3Rn" target="_blank">Instagram</a>
    <a class="btn" href="https://t.me/melvx1" target="_blank">Telegram</a>
  </section>

</div>

<footer>
  <p>© 2025 <span id="footer-name"></span> — Accounting & Bookkeeping</p>
</footer>

</body>
</html>
