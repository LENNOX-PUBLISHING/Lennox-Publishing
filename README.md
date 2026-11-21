<!DOCTYPE html><!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Lennox Publishing</title>
  <style>
    body { font-family: sans-serif; max-width: 700px; margin: 40px auto; padding: 0 16px; line-height: 1.6; color: #222; }
    footer { margin-top: 60px; font-size: 14px; }
  </style>
</head>
<body>
  <h1>Lennox Publishing</h1>
  <p>Willkommen auf meiner Webseite. Hier kommt bald mehr Inhalt.</p>

  <footer>
    <a href="datenschutzerklaerung_lennox_publishing_github_io_de.pdf" target="_blank" rel="noopener">Datenschutzerklärung</a>
  </footer>

  <div id="cookie-banner" style="display:none;position:fixed;bottom:0;left:0;right:0;background:#12284c;color:#fff;padding:16px;font-family:sans-serif;z-index:9999;">
    <p style="margin:0 0 12px 0;">
      Wir verwenden Cookies, um unsere Seite zu verbessern. Mehr dazu in unserer
      <a href="datenschutzerklaerung_lennox_publishing_github_io_de.pdf" target="_blank" rel="noopener" style="color:#9cc4ff;">Datenschutzerklärung</a>.
    </p>
    <button id="cookie-accept" style="background:#fff;color:#12284c;border:0;padding:10px 18px;border-radius:6px;cursor:pointer;margin-right:8px;">Akzeptieren</button>
    <button id="cookie-reject" style="background:transparent;color:#fff;border:1px solid #fff;padding:10px 18px;border-radius:6px;cursor:pointer;">Ablehnen</button>
  </div>

  <script>
    function setCookie(name, value, days) {
      var expires = new Date(Date.now() + days * 24 * 60 * 60 * 1000).toUTCString();
      document.cookie = name + "=" + value + "; expires=" + expires + "; path=/; SameSite=Lax";
    }

    function getCookie(name) {
      var parts = document.cookie.split("; ");
      for (var i = 0; i < parts.length; i++) {
        var pair = parts[i].split("=");
        if (pair[0] === name) return pair[1];
      }
      return null;
    }

    function loadTracking() {
      // Hier nur Skripte laden, die Cookies setzen (z. B. Analytics)
    }

    var banner = document.getElementById("cookie-banner");
    var choice = getCookie("cookie_consent");

    if (!choice) {
      banner.style.display = "block";
    } else if (choice === "accepted") {
      loadTracking();
    }

    document.getElementById("cookie-accept").onclick = function () {
      setCookie("cookie_consent", "accepted", 180);
      banner.style.display = "none";
      loadTracking();
    };

    document.getElementById("cookie-reject").onclick = function () {
      setCookie("cookie_consent", "rejected", 30);
      banner.style.display = "none";
    };
  </script>
</body>
</html>
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
    .profil {
      display: block;
      width: 100%;
      max-width: 360px;
      height: auto;
      border-radius: 16px;
      margin: 0 auto 20px auto;
      border: 4px solid #1e5631;
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

  <img class="profil" src="Profil.jpg.PNG" alt="Logo von Lennox Publishing">

  <h1>Willkommen bei Lennox Publishing</h1>
  <p>Schön, dass du hier bist! Das ist die offizielle Website von Lennox Berg.</p>

  <h2>Über mich</h2>
  <p>Hallo, ich bin Lennox Berg und 16 Jahre alt. Ich schreibe gerne Geschichten und träume davon, eines Tages meine eigenen Bücher zu veröffentlichen.</p>

  <h2>Mein Hobby: Golf</h2>
  <p>In meiner Freizeit spiele ich Golf. Auf dem Platz lerne ich Geduld und Konzentration, und das hilft mir auch beim Schreiben.</p>

  <h2>Meine Bücher</h2>
  <h3>📖 Neuigkeiten von Lennox Publishing</h3>
  <p>Mein neues Weihnachtsbuch „Das Licht von Bethlehem – Die Geschichte von Jesus und dem Wunder der Weihnacht“ befindet sich derzeit in Entwicklung.</p>
  <p>Ich arbeite aktuell an den Kapiteln, den Inhalten und der Gestaltung des Buches.</p>
  <p>Das Projekt soll die biblische Weihnachtsgeschichte erzählen und die Botschaft von Jesus Christus, Hoffnung und Nächstenliebe vermitteln.</p>
  <p><strong>✨ Status: In Entwicklung</strong></p>
  <p>Weitere Informationen zur Veröffentlichung folgen!</p>
  <p><em>Lennox Berg<br>Gründer und Verleger – Lennox Publishing</em></p>

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
