<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Personal Website</title>
  <style>
    /* CSS Styles */
    /* Reset some basic styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    /* Body styles */
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      color: #333;
      text-align: center;
      padding: 20px;
    }
    /* Header styling */
    header {
      background-color: #2196F3;
      padding: 10px;
      color: white;
    }
    h1 {
      font-size: 3em;
    }
    /* Main content styles */
    main {
      margin-top: 20px;
    }
    p {
      font-size: 1.2em;
      margin-bottom: 20px;
    }
    /* Button styling */
    .cta-button {
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 1.1em;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    .cta-button:hover {
      background-color: #3e8e41;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Personal Website</h1>
  </header>
  <main>
    <p>This is my personal website, created using HTML and CSS.</p>
    <button class="cta-button" onclick="alert('Button clicked!')">Click Me!</button>
  </main>
  <script>
    // Add a script tag to make the button interactive
  </script>
</body>
</html>
