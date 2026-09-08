<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About Me | Creator</title>
  <style>
    :root {
      --bg: #0f172a;
      --card-bg: #1e293b;
      --text: #f8fafc;
      --muted: #94a3b8;
      --accent: #ffdd00;
      --accent-text: #000000;
      --btn-bg: #334155;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }

    body {
      background-color: var(--bg);
      color: var(--text);
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 24px 16px;
    }

    .card {
      background-color: var(--card-bg);
      border-radius: 20px;
      padding: 36px 24px;
      max-width: 440px;
      width: 100%;
      text-align: center;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
    }

    .avatar {
      width: 110px;
      height: 110px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 18px;
      border: 3px solid var(--accent);
    }

    h1 {
      font-size: 1.5rem;
      margin-bottom: 6px;
    }

    .handle {
      color: var(--muted);
      font-size: 0.95rem;
      margin-bottom: 16px;
    }

    .bio {
      font-size: 1rem;
      line-height: 1.6;
      color: #cbd5e1;
      margin-bottom: 24px;
    }

    .links {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .btn {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      text-decoration: none;
      font-weight: 600;
      font-size: 0.95rem;
      padding: 14px;
      border-radius: 12px;
      transition: transform 0.15s ease, opacity 0.15s ease;
    }

    .btn:active {
      transform: scale(0.98);
    }

    .btn-coffee {
      background-color: var(--accent);
      color: var(--accent-text);
    }

    .btn-social {
      background-color: var(--btn-bg);
      color: var(--text);
    }

    .btn:hover {
      opacity: 0.9;
    }
  </style>
</head>
<body>

  <main class="card">
    <!-- Profile Photo (Replace the link or upload your photo) -->
    <img class="avatar" src="https://via.placeholder.com/150" alt="Profile Picture" />

    <!-- Name & Handle -->
    <h1>Your Name / Channel Name</h1>
    <p class="handle">@yourtiktokhandle</p>

    <!-- Bio -->
    <p class="bio">
      Hey there! 👋 I make short-form content on TikTok about [Your Topic]. 
      If you enjoy my work and want to support what I do, consider fueling my next video with a coffee!
    </p>

    <!-- Call to Actions -->
    <div class="links">
      <!-- Buy Me a Coffee / Ko-fi link -->
      <a class="btn btn-coffee" href="https://buymeacoffee.com/YOUR_SLUG" target="_blank" rel="noopener">
        ☕ Buy Me a Coffee
      </a>

      <!-- TikTok Link -->
      <a class="btn btn-social" href="https://tiktok.com/@YOUR_HANDLE" target="_blank" rel="noopener">
        📱 Watch on TikTok
      </a>
    </div>
  </main>

</body>
</html>
