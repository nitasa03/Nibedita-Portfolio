---
layout: null
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Portfolio - Nibedita Satapathy</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <style>
    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    }

    .page { display: flex; min-height: 100vh; }

    /* ✅ Sidebar */
    .sidebar {
      width: 260px;
      background: #f7f7f7;
      padding: 30px 18px;
      text-align: center;
    }

    /* ✅ Square profile image */
    .sidebar img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;  /* small rounding, still square */
      margin-bottom: 12px;
    }

    /* ✅ Full name one line */
    .sidebar-name {
      font-weight: 700;
      font-size: 19px;
      white-space: nowrap;
      margin-bottom: 2px;
    }

    .sidebar-role {
      font-size: 14px;
      color: #555;
      margin-bottom: 18px;
    }

    /* ✅ Contact list below profile */
    .sidebar-contact {
      list-style: none;
      padding: 0;
      margin-top: 20px;
      font-size: 14px;
      text-align: left;
      margin-left: 22px;
    }

    .sidebar-contact li { margin: 6px 0; }

    .sidebar-contact a {
      text-decoration: none;
      color: #0073e6;
    }

    /* ✅ Content area */
    .content {
      flex: 1;
      padding: 40px 60px;
      max-width: 900px;
    }

    .content h1 {
      font-size: 32px;
      margin-top: 0;
      text-align: center;
    }

    hr { border: 0; border-top: 1px solid #ddd; margin: 28px 0; }

    .content img { max-width: 100%; height: auto; }

    @media (max-width: 800px) {
      .page { flex-direction: column; }
      .sidebar { width: 100%; }
      .sidebar-contact { margin-left: 0; display: inline-block; }
      .content { padding: 24px 16px; }
    }
  </style>
</head>

<body>
  <div class="page">

    <!-- LEFT SIDEBAR -->
    <aside class="sidebar">
      <img src="{{ '/assets/images/profile.png' | relative_url }}" alt="Profile picture" />
      <div class="sidebar-name">Nibedita Satapathy</div>
      <div class="sidebar-role">AI/ML Explorer</div>

      <!-- ✅ Shifted Contact Details (2 spaces down) -->
      <ul class="sidebar-contact">
        <br/><br/>  <!-- 2 spaces down -->
        <li><strong>GitHub:</strong> <a href="https://github.com/nitasa03">github.com/nitasa03</a></li>
        <li><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/nibedita-satapathy">linkedin.com/in/nibedita-satapathy</a></li>
        <li><strong>Email:</strong> <a href="mailto:nibedita.iter03@gmail.com">nibedita.iter03@gmail.com</a></li>
      </ul>
    </aside>

    <!-- MAIN PORTFOLIO CONTENT -->
    <main class="content">
      <h1>Portfolio</h1>

      <section id="about">
        <h2>👩‍💻 About Me</h2>
        <p>
          I’m a software engineer currently pursuing MSc in Machine Learning and Artificial Intelligence.
          My passion lies in exploring and implementing cutting-edge technologies in the world of AI/ML,
          with a focus on building production-grade applications that bridge research with real-world
          deployment. Through my projects, I aim to combine technical rigor with practical impact,
          showcasing solutions that are both innovative and impactful in real-world contexts.
        </p>
      </section>

      <hr/>

      <h2>🎨 Project 1: PixelAlchemy</h2>
      <p>
        PixelAlchemy is a generative AI app deployed on Hugging Face Spaces.  
        It transforms images with artistic styles and creative blends, and provides output comparisons
        so users can clearly see how the model’s transformations differ from the original.
      </p>
      <p><strong>Try Me on Hugging Face →</strong>
        <a href="https://huggingface.co/spaces/nibedita03/PixelAlchemy">PixelAlchemy</a>
      </p>
      <img src="{{ '/assets/images/PixelAlchemy_Result.PNG' | relative_url }}" alt="PixelAlchemy result"/>

      <hr/>

      <h2>💳 Project 2: Credit Card Fraud Detection App</h2>
      <p>
        A Streamlit-based app for detecting fraudulent transactions with a clean,
        user-friendly UI. Built with scikit-learn and LightGBM, deployed for practical demos.
      </p>
      <p><strong>View on GitHub →</strong>
        <a href="https://github.com/nitasa03/credit_card_fraud_detection_app">Credit Card Fraud Detection</a>
      </p>
      <img src="{{ '/assets/images/fraud_detection_visual.png' | relative_url }}" alt="fraud detection visual"/>

      <hr/>

      <!-- Optional footer credit you can keep/remove -->
      <p style="text-align:center; font-size:13px; color:#777;">
        Hosted on GitHub Pages — Jekyll Minimal Theme Customized
      </p>
    </main>

  </div>
</body>
</html>

