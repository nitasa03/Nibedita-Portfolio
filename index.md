---
layout: null
---

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title></title>

<style>
  body { margin: 0; font-family: "Segoe UI", sans-serif; }

  /* ✅ Position custom Portfolio heading at the red marked level */
  .custom-header {
    width:100%;
    text-align:center;
    font-size:26px;
    font-weight:700;
    position:relative;
    top:48px;  /* adjust until it sits exactly at the red line */
    margin-bottom:90px;
  }

  /* ✅ Shift sidebar slightly right so it doesn’t stick to left edge */
  .sidebar {
    width:260px;
    padding:30px 18px;
    background:#f7f7f7;
    margin-left:28px;  /* 👈 drag sidebar towards right a bit */
    margin-top:40px;
    text-align:center;
  }

  .sidebar img {
    width:150px; height:150px;
    object-fit:cover;
    border-radius:6px;
    margin-bottom:10px;
  }

  .sidebar-name {
    font-weight:700;
    font-size:19px;
    white-space:nowrap; /* full name in single line */
    margin-bottom:4px;
  }

  .sidebar-role { font-size:14px; color:#555; }

  .sidebar-contact {
    list-style:none;
    padding:0;
    margin-top:22px;
    font-size:14px;
    text-align:left;
    margin-left:24px;
  }

  .content {
    flex:1;
    padding:40px 60px;
    max-width:860px;
  }

  .page { display:flex; }

</style>
</head>

<body>

<!-- ✅ This is your new centered title -->
<div class="custom-header">Portfolio</div>

<div class="page">
  <aside class="sidebar">
    <img src="{{ '/assets/images/profile.png' | relative_url }}" alt="Profile">
    <div class="sidebar-name">Nibedita Satapathy</div>
    <div class="sidebar-role">AI/ML Explorer</div>

    <ul class="sidebar-contact">
      <li><strong>GitHub:</strong> <a href="https://github.com/nitasa03">github.com/nitasa03</a></li>
      <li><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/nibedita-satapathy">linkedin.com/in/nibedita-satapathy</a></li>
      <li><strong>Email:</strong> <a href="mailto:nibedita.iter03@gmail.com">nibedita.iter03@gmail.com</a></li>
    </ul>
  </aside>

  <main class="content">

    <h2 id="about">👩‍💻 About Me</h2>
    <p>
      I’m a software engineer currently pursuing MSc in Machine Learning and Artificial Intelligence.
      My passion lies in exploring and implementing cutting-edge technologies in the world of AI/ML,
      with a focus on building production-grade applications that bridge research with real-world deployment.
      Through my projects, I aim to combine technical rigor with practical impact, showcasing solutions
      that are both innovative and impactful in real-world contexts.
    </p>

    <hr>

    <h2>🎨 Project 1: PixelAlchemy</h2>
    <p>
      PixelAlchemy is a generative AI app deployed on Hugging Face Spaces.
      It transforms images with artistic styles and creative blends, and provides output comparisons
      so users can clearly see how the model’s transformations differ from the original.
    </p>
    <p><strong>Try Me on Hugging Face →</strong> <a href="https://huggingface.co/spaces/nibedita03/PixelAlchemy">PixelAlchemy</a></p>
    <img src="{{ '/assets/images/PixelAlchemy_Result.PNG' | relative_url }}" alt="PixelAlchemy Result">

    <hr>

    <h2>💳 Project 2: Credit Card Fraud Detection App</h2>
    <p>
      A Streamlit-based app for detecting fraudulent transactions with a clean, user-friendly UI.
      Built with scikit-learn and LightGBM, deployed for practical demos.
    </p>
    <p><strong>View on GitHub →</strong> <a href="https://github.com/nitasa03/credit_card_fraud_detection_app">Credit Card Fraud Detection</a></p>
    <img src="{{ '/assets/images/fraud_detection_visual.png' | relative_url }}" alt="Fraud Detection Visual">

  </main>
</div>

</body>
</html>

