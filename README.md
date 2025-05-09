
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FLAK</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body, html {
      height: 100%;
      width: 100%;
    }

    .container {
      display: flex;
      height: 100vh;
    }

    .left-panel {
      width: 10%;
      background-color: #ffffff;
      padding: 40px 20px;
      display: flex;
      flex-direction: column;
      gap: 20px;
      justify-content: center;
      align-items: flex-start;
    }

    .left-panel .btn {
      display: flex;
      align-items: center;
      padding: 12px 16px;
      background-color: #f0f0f0;
      border: none;
      border-radius: 8px;
      text-decoration: none;
      color: #000;
      font-weight: bold;
      font-size: 16px;
      transition: background 0.3s;
    }

    .left-panel .btn:hover {
      background-color: #e0e0e0;
    }

    .left-panel .btn img {
      width: 24px;
      height: 24px;
      margin-right: 12px;
    }

    .middle-panel {
      width: 70%;
      background-color: #000000;
      color: #ffffff;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 20px;
      text-align: center;
    }

    #aboutBtn {
      padding: 12px 20px;
      font-size: 16px;
      background-color: #ffffff;
      color: #000000;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.3s;
    }

    #aboutBtn:hover {
      background-color: #dddddd;
    }

    .right-panel {
      width: 200%;
      background-color: #f9f9f9;
      padding: 30px;
      overflow-y: auto;
      display: none;
    }

    .right-panel.active {
      display: block;
    }

    .right-panel p {
      margin-bottom: 1em;
      line-height: 1.6;
    }

    .right-panel ul {
      margin-top: 10px;
      padding-left: 20px;
    }

    .right-panel li {
      margin-bottom: 8px;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Left Panel -->
    <div class="left-panel">
      <a href="https://www.instagram.com/flak_COMMUNITY/" target="_blank" class="btn">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram" />
        Follow us on Instagram
      </a>
      <a href="https://discord.com/invite/rVU4H7mcwF" target="_blank" class="btn">
        <img src="https://cdn.discordapp.com/attachments/1365681695218466889/1370302951003787315/LxiaKf7.jpg?ex=681f0192&is=681db012&hm=c0b3b36f3007923ef6d207e27a00810ee892d39d5830941d0ea8b505459dce80&" alt="Discord" />
        Join our Discord Server
      </a>
      <a href="https://www.guilded.gg/i/2Z1RDw9E" target="_blank" class="btn">
        <img src="https://cdn.discordapp.com/attachments/1365681695218466889/1370303342307442738/x0EEuJK.png?ex=681f01ef&is=681db06f&hm=0feba06023a91c44092bd455096f69d6c3a0d599cd24a51b26e67d22a3b6472e&" alt="Guilded" />
        Join our Guilded Server
      </a>
    </div>

    <!-- Middle Panel -->
    <div class="middle-panel">
      <img src="https://cdn.discordapp.com/attachments/1365681695218466889/1365977300469944360/rumFZRb.png?ex=681e6e3f&is=681d1cbf&hm=b76ab4a1ccba100141f987c883f2b44b260291ed2d033e9e15a1fb150fc789ca&" alt="FLAK Logo" class="flak-logo" />
      <button id="aboutBtn">About Us</button>
    </div>

    <!-- Right Panel -->
    <div class="right-panel" id="aboutText">
      <p><strong>Welcome to FLAK!</strong> We’re a community for gamers, friends, and anyone exploring new interests. Whether you’re playing, studying, or just hanging out, there’s a place for you here. With fun roles, helpful support, and tons to do, there’s always something new to discover. We’re glad you’re here!</p>
      <p><strong>What You’ll Find at FLAK:</strong></p>
      <ul>
        <li><strong>💬 Chat Category</strong>
          <ul>
            <li>General Chat for daily convos and random talks.</li>
            <li>Gaming Chat to team up, share tips, or flex your wins.</li>
            <li>Gym Chat for fitness tips and gains.</li>
            <li>Car Chat for showing off rides and automotive talk.</li>
            <li>Pics Chat for selfies, photography, and artwork.</li>
            <li>Memes Chat for sharing hilarious content.</li>
            <li>Leveling system: the more you chat, the more perks you unlock!</li>
          </ul>
        </li>
        <li><strong>🗣️ Talking Category</strong>
          <ul>
            <li>Create your own custom VC.</li>
            <li>Personalize your hangout, bring your friends, vibe your way.</li>
          </ul>
        </li>
        <li><strong>🎬 Movies Category</strong>
          <ul>
            <li>Watching Together Stage for movie nights.</li>
            <li>Two VCs for movie discussion.</li>
            <li>Movie & Show Suggestions forum.</li>
          </ul>
        </li>
        <li><strong>📚 Studying Category</strong>
          <ul>
            <li>Two Classroom Stages for study sessions.</li>
            <li>Students’ Lounges (VCs) for chill studying.</li>
            <li>Study-Topics Forum for tips and group planning.</li>
          </ul>
        </li>
        <li><strong>🎥 Streaming Category</strong>
          <ul>
            <li>Live Stage for recordings and streams.</li>
            <li>VCs for gaming parties and live edits.</li>
            <li>Stream & Content Suggestions Forum.</li>
          </ul>
        </li>
      </ul>
      <p><strong>At FLAK</strong>, we’re more than just a server — we’re a community where friendships form, passions grow, and good memories are made. This space is built by all of us, and now you’re part of the story too. We’re so glad you’re here — welcome to FLAK!</p>
    </div>
  </div>

  <script>
    const aboutBtn = document.getElementById('aboutBtn');
    const aboutText = document.getElementById('aboutText');

    aboutBtn.addEventListener('click', () => {
      aboutText.classList.toggle('active');
    });
  </script>
</body>
</html>
