<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lennox Publishing</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 700px;
      margin: 40px auto;
      padding: 0 20px;
      line-height: 1.6;
      color: #222;
      background-color: #f7f7f2;
    }
    h1, h2 {
      color: #1e5631;
    }
    h2 {
      margin-top: 30px;
    }
    label {
      display: block;
      margin-top: 12px;
      font-weight: bold;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 4px;
      border: 1px solid #aaa;
      border-radius: 6px;
      font-size: 16px;
      box-sizing: border-box;
    }
    button {
      margin-top: 16px;
      padding: 12px 24px;
      background-color: #1e5631;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 16px;
    }
  </style>
</head>
<body>

  <h1>Willkommen bei Lennox Publishing</h1>
  <p>Schön, dass du hier bist! Das ist die offizielle Website von Lennox Berg.</p>

  <h2>Über mich</h2>
  <p>Hallo, ich bin Lennox Berg und 16 Jahre alt. Ich schreibe gerne Geschichten und träume davon, eines Tages meine eigenen Bücher zu veröffentlichen.</p>

  <h2>Mein Hobby: Golf</h2>
  <p>In meiner Freizeit spiele ich Golf. Auf dem Platz lerne ich Geduld und Konzentration, und das hilft mir auch beim Schreiben.</p>

  <h2>Meine Bücher</h2>
  <p>Hier werde ich bald meine Texte und Buchprojekte vorstellen. Schau gerne bald wieder vorbei!</p>

  <h2>Kontakt</h2>
  <p>Schreib mir gern eine Nachricht!</p>
  <form action="https://formspree.io/f/xdeglabr" method="POST">
    <label for="name">Dein Name</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Deine E-Mail</label>
    <input type="email" id="email" name="email" required>

    <label for="message">Deine Nachricht</label>
    <textarea id="message" name="message" rows="5" required></textarea>

    <button type="submit">Senden</button>
  </form>

</body>
</html>