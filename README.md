# exacrio-AI
EXACRIO-AI the exam mentor
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>ExaCrio AI – Study with Discipline</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- HOME SCREEN -->
<div id="home" class="screen active">
  <h1>ExaCrio AI</h1>
  <p>Your AI Mentor & Mummy for Exams</p>
  <button onclick="startChat()">Start Studying with AI</button>
</div>

<!-- CHAT SCREEN -->
<div id="chat" class="screen">
  <div id="messages"></div>

  <div class="input-area">
    <input type="text" id="userInput" placeholder="Ask your doubt..." />
    <button onclick="sendMessage()">Send</button>
  </div>
</div>

<script src="script.js"></script>
</body>
</html>
