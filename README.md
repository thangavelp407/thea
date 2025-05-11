\study-website/
│
├── index.html
├── style.css
└── script.js

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Study Website</title>
  <link rel="stylesheet" href="style.css" />
</head>

<body>
  <header>
    <h1>Study Hub</h1>
    <nav>
      <a href="#notes">Notes</a>
      <a href="#quizzes">Quizzes</a>
      <a href="#resources">Resources</a>
    </nav>
  </header>

  <main>
    <section id="notes">
      <h2>Study Notes</h2>
      <p>Click the button to show a random study tip:</p>
      <button onclick="showTip()">Show Tip</button>
      <p id="tip"></p>
    </section>

    <section id="quizzes">
      <h2>Mini Quiz</h2>
      <p>What is 2 + 2?</p>
      <input type="text" id="answer" />
      <button onclick="checkAnswer()">Submit</button>
      <p id="result"></p>
    </section>

    <section id="resources">
      <h2>Useful Resources</h2>
      <ul>
        <li><a href="https://www.khanacademy.org" target="_blank">Khan Academy</a></li>
        <li><a href="https://www.coursera.org" target="_blank">Coursera</a></li>
      </ul>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Study Website</p>
  </footer>

  <script src="script.js"></script>
</body>

</html>
