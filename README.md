<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NetGuard Solutions</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: #0f172a;
      color: #e5e7eb;
      line-height: 1.6;
    }

    header {
      padding: 80px 20px;
      text-align: center;
      background: radial-gradient(circle at top, #1d4ed8, #020617);
    }

    header h1 {
      font-size: 3rem;
      font-weight: 700;
      margin-bottom: 10px;
    }

    header p {
      opacity: 0.7;
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 40px 20px;
    }

    h2 {
      font-size: 1.8rem;
      margin-bottom: 20px;
      border-left: 4px solid #3b82f6;
      padding-left: 10px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: #1e293b;
      padding: 20px;
      border-radius: 16px;
      transition: 0.3s;
      border: 1px solid transparent;
    }

    .card:hover {
      transform: translateY(-5px);
      border: 1px solid #3b82f6;
    }

    .card h3 {
      margin-bottom: 10px;
      color: #60a5fa;
    }

    ul {
      padding-left: 20px;
    }
