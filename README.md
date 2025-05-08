
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>FLAK</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body, html {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: black;
      color: white;
      height: 100vh;
      width: 100vw;
    }

    .container {
      display: flex;
      height: 100%;
      width: 100%;
    }

    .left-panel {
      width: 30%;
      background-color: #111;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 40px 20px;
      gap: 30px;
    }

    .link-button {
      background-color: white;
      color: black;
      border: none;
      font-size: 22px;
      font-weight: bold;
      padding: 20px 30px;
      width: 100%;
      max-width: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;
      border-radius: 12px;
      cursor: pointer;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .link-button:hover {
      transform: scale(1.05);
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
    }

    .link-button img {
      height: 30px;
    }

    .right-panel {
      width: 70%;
      background-color: black;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 40px;
      text-align: center;
    }

    #aboutButton {
      background-color: white;
      color: black;
      border: none;
      padding: 15px 25px;
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
      border-radius: 10px;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    #aboutButton:hover {
      transform: scale(1.05);
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
    }

    #aboutText {
      margin-top: 30px;
      max-width: 750px;
      text-align: left;
      white-space: pre-wrap;
      font-size: 16px;
      line-height: 1.6;
    }

    .hidden {
      display: none;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="left-panel">
      <button class="link-button" onclick="window.open('https://www.instagram.com/flak_COMMUNITY/', '_blank')">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram"> 
        Follow us on Instagram
      </button>
     discord-button {
      background-color: #81a5ca; /* Discord blue */
      border: none;
      padding: 15px 30px;
      font-size: 1.2em;
      cursor: pointer;
      color: white;
      border-radius: 8px;
      transition: background-color 0.3s ease;
      margin-top: 10px;
    }
</button>
    .discord-button:hover {
      background-color: #81a5ca;
    }
</button>
      <button class="link-button" onclick="window.open('https://www.guilded.gg/i/2Z1RDw9E
', '_blank')">
        <img src="https://images.app.goo.gl/66wXyuhsNtqCZMCL9" alt="Guilded"> 
        Join our Guilded Server
      </button>
    </div>
    <div class="right-panel">
      <img src="https://cdn.discordapp.com/attachments/1365681695218466889/1365977300469944360/rumFZRb.png?ex=681dc57f&is=681c73ff&hm=d0a533cc715de1fb764287c4cb8ed1b3b4b3fa2887026536294802e4e6979bee&" alt="FLAK Logo" class="flak-logo">
      <button id="aboutButton">About Us</button>
      <div id="aboutText" class="hidden">
        Welcome to FLAK! We’re a community for gamers, friends, and anyone exploring new interests. Whether you’re playing, studying, or just hanging out, there’s a place for you here. With fun roles, helpful support, and tons to do, there’s always something new to discover. We’re glad you’re here!

        What You’ll Find at FLAK:

        💬 Chat Category
        • Hang out in General Chat for daily convos and random talks.
        • Dive into Gaming Chat to team up, share tips, or flex your wins.
        • Flex your gains or share fitness tips in Gym Chat.
        • Rev your engines in Car Chat — show off your rides, discuss mods, share car news, and everything automotive
        • Drop your best shots in Pics Chat — selfies, photography, artwork, anything visual.
        • Post the funniest content in our Memes Chat — because who doesn’t love a good meme?
        • Leveling system: the more you chat, the more perks you unlock!

        🗣️ Talking Category
        • Create your own custom VC whenever you want.
        • Personalize your hangout, bring your friends, vibe your way.

        🎬 Movies Category
        • Watching Together Stage for movie watch-alongs.
        • Two VC Channels for movie discussions.
        • Movie & Show Suggestions Forum.

        📚 Studying Category
        • Two Classroom Stages for study sessions and workshops.
        • Two Students’ Lounges (VCs) for casual studying.
        • Study-Topics Forum for sharing tips and organizing group studies.

        🎥 Streaming Category
        • Live Stage for recordings and streams.
        • Two VC Channels for gaming parties and live editing.
        • Stream & Content Suggestions Forum.

        At FLAK, we’re more than just a server — we’re a community where friendships form, passions grow, and good memories are made. No matter why you joined, you’re welcome here just as you are. This space is built by all of us, and now you’re part of the story too. We’re so glad you’re here — welcome to FLAK!
      </div>
    </div>
  </div>

  <script>
    document.getElementById('aboutButton').addEventListener('click', () => {
      const aboutText = document.getElementById('aboutText');
      aboutText.classList.toggle('hidden');
    });
  </script>
</body>
</html>
