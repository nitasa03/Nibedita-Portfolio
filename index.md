---
layout: default
---

<style>
  /* If the header still renders an empty bar, hide it completely */
  .site-header {
    display: none !important;
  }
  .page-content {
    padding-top: 0 !important;
  }
</style>

<h1 style="text-align:center; margin-bottom: 40px;">PORTFOLIO</h1>

<div style="display: flex; align-items: flex-start; gap: 40px;">

  <!-- Left column: photo + name -->
  <div style="flex: 0 0 260px; text-align: center;">
    <img src="{{ '/assets/images/profile.png' | relative_url }}"
         alt="Profile picture"
         style="width: 190px; margin-bottom: 10px;" />
    <p style="margin-top: 4px; margin-bottom: 0; font-size: 15px;">
      <strong style="white-space: nowrap;">Nibedita Satapathy</strong><br/>
      <span>AI/ML Explorer</span>
    </p>
  </div>

  <!-- Right column: main content -->
  <div style="flex: 1;">

    <h2>👩‍💻 About Me</h2>
    <p>
      I’m a software engineer currently pursuing MSc in Machine Learning and Artificial Intelligence.
      My passion lies in exploring and implementing cutting-edge technologies in the world of AI/ML, with
      a focus on building production-grade applications that bridge research with real-world deployment.
      Through my projects, I aim to combine technical rigor with practical impact, showcasing solutions
      that are both innovative and impactful in real-world contexts.
    </p>

    <hr/>

    <h2>🎨 Project 1: PixelAlchemy</h2>
    <p>
      PixelAlchemy is a generative AI app deployed on Hugging Face Spaces.
      It transforms images with artistic styles and creative blends, and provides output comparisons
      so users can clearly see how the model’s transformations differ from the original — helping them
      understand the creative context behind each transformation.
    </p>
    <p><strong>Try Me on Hugging Face →</strong>
      <a href="https://huggingface.co/spaces/nibedita03/PixelAlchemy">PixelAlchemy</a>
    </p>
    <img src="{{ '/assets/images/PixelAlchemy_Result.PNG' | relative_url }}"
         alt="PixelAlchemy Result Screenshot"
         style="max-width: 100%; margin-bottom: 20px;" />

    <hr/>

    <h2>💳 Project 2: Credit Card Fraud Detection App</h2>
    <p>
      A Streamlit-based app for detecting fraudulent transactions with a clean, user-friendly UI.
      Built with scikit-learn and LightGBM, deployed for practical demonstrations.
    </p>
    <p><strong>View on GitHub →</strong>
      <a href="https://github.com/nitasa03/credit_card_fraud_detection_app">
        Credit Card Fraud Detection
      </a>
    </p>
    <img src="{{ '/assets/images/fraud_detection_visual.png' | relative_url }}"
         alt="Fraud Detection Visual"
         style="max-width: 100%; margin-bottom: 20px;" />

    <hr/>

    <h2>📬 Contact</h2>
    <ul>
      <li><strong>GitHub:</strong> <a href="https://github.com/nitasa03">github.com/nitasa03</a></li>
      <li><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/nibedita-satapathy">linkedin.com/in/nibedita-satapathy</a></li>
      <li><strong>Email:</strong> <a href="mailto:nibedita.iter03@gmail.com">nibedita.iter03@gmail.com</a></li>
    </ul>

  </div>
</div>
