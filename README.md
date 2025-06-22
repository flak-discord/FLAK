<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
 
  <style>
    body {
      background-color: #0a0a0a;
      color: #ffffff;
      font-family: 'Arial', sans-serif;
      text-align: center;
      padding: 50px;
    }

   
    }
    h1 {
      font-size: 3em;
      margin-bottom: 20px;
 
    }

    button {
      background-color: #81a5ca;
      border: none;
      padding: 15px 30px;
      font-size: 1.2em;
      cursor: pointer;
      color: #fff;
      border-radius: 8px;
      transition: background-color 0.3s ease;
      margin-top: 10px;
    }

    button:hover {
      background-color: #81a5ca;
      color: #fff;
    }

    .discord-button {
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

    .discord-button:hover {
      background-color: #81a5ca;
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
  <img src="https://cdn.discordapp.com/attachments/1371148648477626490/1382818562074476648/casidMu.webp?ex=68590fe4&is=6857be64&hm=19434b73faab3e46ada8000fd628839098bbeb06c78012d9aad7447270f1d507&">

<div>

    <h1>WELCOME TO FLAK</h1>
    <!-- Button for About Us -->
    <button onclick="showAbout()">About Us</button>
    <!-- Button for Join the Server (Discord) -->
    <a href="https://discord.gg/rVU4H7mcwF" target="_blank">
      <button class="discord-button">Join our discord server</button>
    </a>
    
    <a href="https://instagram.com/flak_COMMUNITY" target="_blank">
    <button style="background-color: #81a5ca; color: white; border: none; padding: 15px 30px; font-size: 1.2em; cursor: pointer; border-radius: 8px; margin-top: 10px; transition: background-color 0.3s ease;">  Follow us on Instagram
    </button>
  </a>
  <button onclick="window.open('https://www.guilded.gg/i/2Z1RDw9E', '_blank')">Join Our Server in Guilded</button> 
  
  </div>

  <div id="about" class="hidden">
    <h2>Welcome to FLAK!</h2>
    <p></p>Welcome to FLAK! We’re a community for gamers, friends, and anyone exploring new interests. Whether you’re playing, studying, or just hanging out, there’s a place for you here. With fun roles, helpful support, and tons to do, there’s always something new to discover. We’re glad you’re here!
What You’ll Find at FLAK:

    <h3>💬 Chat Category</h3>
    <ul>
      <li>Hang out in General Chat for daily convos and random talks.</li>
      <li>Dive into Gaming Chat to team up, share tips, or flex your wins.</li>
      <li>Flex your gains or share fitness tips in Gym Chat.</li>
      <li>Rev your engines in Car Chat — show off your rides, discuss mods, share car news, and everything automotive</li>
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


    <p>At FLAK, we’re more than just a server — we’re a community where friendships form, passions grow, and good memories are made. No matter why you joined, you’re welcome here just as you are. This space is built by all of us, and now you’re part of the story too. We’re so glad you’re here — welcome to FLAK!</p>
   <!-- Button for Instagram -->
  
</div>

  <script>
    function showAbout() {
      document.getElementById('about').classList.toggle('hidden');
    }
  </script>
</body>
</html>
