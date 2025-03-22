<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <!-- Ensures proper scaling on mobile devices -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bikram Karmakar - Portfolio</title>
  <style>
    /* Base styles */
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
      color: #333;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 20px;
      background: #fff;
    }
    h1, h3 {
      text-align: center;
      margin: 20px 0 10px;
    }
    p {
      text-align: center;
      margin: 10px 0;
    }
    .img-center {
      display: block;
      width: 100%;
      height: auto;
      max-width: 100%;
      margin: 0 auto;
    }

    /* Row container for badges */
    .metrics-row {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin: 10px 0;
      flex-wrap: wrap; /* Wrap on smaller screens */
    }
    /* Each badge in the row */
    .metrics-row .badge {
      max-height: 50px;
      margin: 5px;
    }
    /* If you want them strictly left & right on small screens, remove flex-wrap or adjust the media query */

    /* Flexbox layout for side-by-side elements */
    .flex-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      margin: 20px 0;
    }
    .flex-container a,
    .flex-container img {
      flex: 1;
      margin: 10px;
      max-width: 300px;
    }

    /* Footer layout */
    .footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      margin-top: 40px;
    }
    .footer > div {
      flex: 1;
      text-align: center;
      margin: 10px 0;
    }

    /* Responsive adjustments */
    @media (max-width: 600px) {
      .metrics-row {
        flex-direction: column;
        align-items: center;
      }
      .flex-container,
      .footer {
        flex-direction: column;
        text-align: center;
      }
      .flex-container a,
      .flex-container img,
      .metrics-row .badge {
        max-width: 100%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header Section -->
    <h1>Hi 👋, I'm Bikram Karmakar</h1>
    <p>
      <img class="img-center" src="https://wallpapercave.com/wp/wp9500685.jpg" alt="Task Force 141" title="Task Force 141" />
    </p>

    
    <!-- Profile Metrics -->
    <!-- First row: Profile Views (left), Followers (right) -->
    <div class="metrics-row">
      <a href="https://komarev.com/ghpvc/?username=bikramkarmakar&label=Profile%20views&lcolor=640464&style=for-the-badge&color=7c007c&logo=AngelList&logoColor=white" target="_blank" rel="noreferrer">
        <img class="badge" src="https://komarev.com/ghpvc/?username=bikramkarmakar&label=Profile%20views&lcolor=640464&style=for-the-badge&color=7c007c&logo=AngelList&logoColor=white" alt="Profile Views" />
      </a>
      <a href="https://github.com/bikramkarmakar?tab=followers" target="_blank" rel="noreferrer">
        <img class="badge" src="https://img.shields.io/github/followers/bikramkarmakar?label=Follow&style=for-the-badge" alt="Follow me on Github" />
      </a>
    </div>

  

    <!-- Support Section -->
    <h3 style="text-align: left;">🤝 Support:</h3>
    <div class="flex-container">
      <a href="https://www.buymeacoffee.com/bikramkarmakar" target="_blank" rel="noreferrer">
        <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" />
      </a>
      <a href="https://ko-fi.com/bikramkarmakar" target="_blank" rel="noreferrer">
        <img src="https://cdn.ko-fi.com/cdn/kofi3.png?v=3" alt="Ko-fi" />
      </a>
    </div>

    <!-- Octodex Images -->
    <div class="flex-container">
      <img src="https://octodex.github.com/images/daftpunktocat-thomas.gif" alt="Octodex Thomas" />
      <img src="https://octodex.github.com/images/daftpunktocat-guy.gif" alt="Octodex Guy" />
    </div>

    <!-- Footer Section -->
    <div class="footer">
      <div>
        <img src="https://profile-counter.glitch.me/bikramkarmakar/count.svg" alt="Profile Counter" />
      </div>
      <div>
        <samp>Made with 💜</samp>
      </div>
      <div>
        <a href="#top">
          <img src="https://img.shields.io/static/v1?label=&message=back+to+top&color=7E3ACE&style=for-the-badge" alt="Back to top" />
        </a>
      </div>
    </div>
  </div>
</body>
</html>
