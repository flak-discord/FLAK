<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>FLAK</title>
  <style>
    body {
      background-color: #0a0a0a;
      color: #ffffff;
      font-family: 'Arial', sans-serif;
      text-align: center;
      padding: 50px;
    }

    #flak-logo {
      width: 150px; /* Adjust size */
      margin-bottom: 30px;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 20px;
    }

    button {
      background-color: #00ffff;
      border: none;
      padding: 15px 30px;
      font-size: 1.2em;
      cursor: pointer;
      color: #0a0a0a;
      border-radius: 8px;
      transition: background-color 0.3s ease;
      margin-top: 10px;
    }

    button:hover {
      background-color: #ff00ff;
      color: #fff;
    }

    .discord-button {
      background-color: #7289DA; /* Discord blue */
      border: none;
      padding: 15px 30px;
      font-size: 1.2em;
      cursor: pointer;
      color: white;
      border-radius: 8px;
      transition: background-color 0.3s ease;
      margin-top: 10px;
    }

    .discord-button:hover {
      background-color: #5b6e96;
    }

    .hidden {
      display: none;
      margin-top: 50px;
      text-align: left;
    }

    #about {
      max-width: 800px;
      margin: 0 auto;
    }

    h2, h3 {
      color: #00ffff;
    }

    ul {
      text-align: left;
      margin: 20px 0;
      padding-left: 20px;
    }

    li {
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <img src="https://media.discordapp.net/attachments/1365681695218466889/1365977300469944360/rumFZRb.png?ex=680fedbf&is=680e9c3f&hm=907a81c11475b4ad1954a1fc4c5d6d7587e34ed0ccd010da830161b0c564d488&=&width=405&height=405" alt="FLAK Logo" id="flak-logo">

  <div class="home">
    <h1>WELCOME TO FLAK</h1>
    <!-- Button for About Us -->
    <button onclick="showAbout()">About Us</button>
    <!-- Button for Join the Server (Discord) -->
    <a href="https://discord.gg/rVU4H7mcwF" target="_blank">
      <button class="discord-button">Join the Server</button>
    </a>
  </div>

  <div id="about" class="hidden">
    <h2>Welcome to FLAK!</h2>
    <p>We’re thrilled to have you join us! FLAK is more than just a server – it’s a community built for everyone who loves gaming, connecting, and exploring new interests together...</p>

    <h3>💬 Chat Category</h3>
    <ul>
      <li>Hang out in General Chat for daily convos and random talks.</li>
      <li>Dive into Gaming Chat to team up, share tips, or flex your wins.</li>
      <li>Flex your gains or share fitness tips in Gym Chat.</li>
      <li>Drop your best shots in Pics Chat — selfies, photography, artwork, anything visual.</li>
      <li>Post the funniest content in our Memes Chat — because who doesn’t love a good meme?</li>
      <li>Leveling system: the more you chat, the more perks you unlock!</li>
    </ul>

    <h3>🗣️ Talking Category</h3>
    <ul>
      <li>Create your own custom VC whenever you want.</li>
      <li>Personalize your hangout, bring your friends, vibe your way.</li>
    </ul>

    <h3>🎬 Movies Category</h3>
    <ul>
      <li>Watching Together Stage for movie watch-alongs.</li>
      <li>Two VC Channels for movie discussions.</li>
      <li>Movie & Show Suggestions Forum.</li>
    </ul>

    <h3>📚 Studying Category</h3>
    <ul>
      <li>Two Classroom Stages for study sessions and workshops.</li>
      <li>Two Students’ Lounges (VCs) for casual studying.</li>
      <li>Study-Topics Forum for sharing tips and organizing group studies.</li>
    </ul>

    <h3>🎥 Streaming Category</h3>
    <ul>
      <li>Live Stage for recordings and streams.</li>
      <li>Two VC Channels for gaming parties and live editing.</li>
      <li>Stream & Content Suggestions Forum.</li>
    </ul>


    <p>At FLAK, we’re not just here to build a server — we’re building a place where friendships form, passions grow, and good memories are made.
We’re proud of the space we’ve created together, and we’re even more excited about where we’re headed next.

No matter why you joined — whether it’s to find a squad, vibe in VC, share your wins, study for exams, or just make a few new friends — know that you’re welcome here, just as you are.
We’re a community that’s all about positivity, support, and good times.

This server is shaped by everyone who’s a part of it — and now that you’re here, you’re part of the story too.
So jump in, make yourself at home, and don’t be afraid to be yourself.

We’re so glad you’re here.
Welcome to FLAK — let’s make it unforgettable!</p>
  </div>

  <script>
    function showAbout() {
      document.getElementById('about').classList.toggle('hidden');
    }
  </script>
</body>
</html>
