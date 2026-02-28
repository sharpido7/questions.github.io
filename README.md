# questions.github.io
This Page will show Different questions for the Scanned QR Code.
<!DOCTYPE html>
<html>
<head>
  <title>Random Question</title>
</head>
<body>
  <h2 id="question"></h2>

  <script>
    const questions = [
      "What is your biggest goal this year?",
      "If you could travel anywhere, where would you go?",
      "What motivates you the most?",
      "What is one skill you want to master?",
      "What makes you happy?"
    ];

    const randomIndex = Math.floor(Math.random() * questions.length);
    document.getElementById("question").innerText = questions[randomIndex];
  </script>
</body>
</html>
