# COHORT5
Test
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cohort 5</title>
  <style>
    :root {
      --bg-color: #f9f9f9;
      --text-color: #222;
      --accent-color: #0055ff;
      --card-bg: #ffffff;
      --card-border: #e0e0e0;
      --font: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      margin: 0;
      background-color: var(--bg-color);
      font-family: var(--font);
      color: var(--text-color);
    }

    header {
      background-color: var(--accent-color);
      color: white;
      padding: 1.5rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
      letter-spacing: 1px;
    }

    .container {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    .intro {
      text-align: center;
      margin-bottom: 2rem;
    }

    .intro p {
      font-size: 1.1rem;
      color: #555;
    }

    .idea-card {
      background: var(--card-bg);
      border: 1px solid var(--card-border);
      border-radius: 8px;
      padding: 1.5rem;
      margin-bottom: 1.5rem;
      box-shadow: 0 4px 8px rgba(0,0,0,0.03);
    }

    .idea-card h2 {
      margin-top: 0;
      color: var(--accent-color);
    }

    .idea-card .meta {
      font-size: 0.9rem;
      color: #888;
      margin-bottom: 0.5rem;
    }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #777;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Cohort 5</h1>
  </header>

  <div class="container">
    <div class="intro">
      <p>A living archive of concepts, experiments, and half-brilliant ideas by [Your Name] & John.</p>
    </div>

    <!-- Idea Entry Example -->
    <div class="idea-card">
      <h2>Project Atlas</h2>
      <div class="meta">Posted by John · June 2025</div>
      <p>A crowdsourced knowledge map that visually connects niche concepts across disciplines. Each node leads to a rabbit hole.</p>
    </div>

    <div class="idea-card">
      <h2>Sleep Debt Bank</h2>
      <div class="meta">Posted by [Your Name] · June 2025</div>
      <p>An app that tracks your sleep deficit like a financial account, suggesting recovery strategies and forecasting fatigue risk.</p>
    </div>

    <!-- Add more ideas here -->

  </div>

  <footer>
    &copy; 2025 Cohort 5 · Built by [Your Name] & John
  </footer>

</body>
</html>
