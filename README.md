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

    /* Feedback Section */
    #feedback-section {
      background-color: #1e1e1e;
      padding: 20px;
      margin-top: 30px;
      border-radius: 8px;
    }

    #feedback-section h3 {
      color: #ff00ff;
    }

    #feedback-section textarea, #feedback-section input {
      width: 80%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 8px;
      border: none;
    }

    #feedback-section button {
      background-color: #ff00ff;
      color: white;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
      border-radius: 8px;
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
    <p>We’re thrilled to have you join us! FLAK is more than just a server – it’s a community built for everyone who loves gaming, connecting, and exploring new interests together. Here, we celebrate our members’ unique passions, whether it’s diving into an intense game, chilling with friends, or getting focused in a study session.</p>

    <p>At FLAK, we believe that gaming and community go hand in hand, and we’re dedicated to creating a space where everyone feels welcome. Our channels cover a wide variety of topics, so whether you’re here to find teammates, share your latest favorite song, or buckle down and study with others, you’ll find the right place to belong. With our supportive ticket system, fun server roles, and plenty of engaging activities, there’s always something new to discover.</p>

    <h3>What You’ll Find at FLAK:</h3>

    <h3>💬 Chat Category</h3>
    <ul>
      <li>Hang out in General Chat for daily convos and random talks.</li>
      <li>Dive into Gaming Chat to team up, share tips, or flex your wins.</li>
      <li>Flex your gains or share fitness tips in Gym Chat.</li>
      <li>Drop your best shots in Pics Chat — selfies, photography, artwork, anything visual.</li>
      <li>Post the funniest content in our Memes Chat — because who doesn’t love a good meme?</li>
      <li>Plus, a full Levelling System — the more you chat, the higher you climb, unlocking roles and perks!</li>
    </ul>

    <h3>🗣️ Talking Category</h3>
    <ul>
      <li>Create your own custom VC (voice channel) whenever you want.</li>
      <li>Personalize your hangout, bring your friends, vibe your way.</li>
    </ul>

    <h3>🎬 Movies Category</h3>
    <ul>
      <li>Watching Together Stage — a dedicated spot for hosting movie watch-alongs.</li>
      <li>Two VC Channels — perfect for casual movie discussions or syncing up while watching.</li>
      <li>Movie & Show Suggestions Forum — recommend your favorite films, TV shows, anime, or series, and discover what others love!</li>
    </ul>

    <h3>📚 Studying Category</h3>
    <ul>
      <li>Two Classroom Stages — structured spaces for hosting study sessions, workshops, or lectures.</li>
      <li>Two Students’ Lounges (VCs) — relaxed voice channels for casual studying, group projects, or chill work sessions.</li>
      <li>Study-Topics Forum — a place to share study tips, ask questions, organize group studies, and post resources.</li>
    </ul>

    <h3>🎥 Streaming Category</h3>
    <ul>
      <li>Live Stage — host live recordings, streams, or major announcements.</li>
      <li>Two VC Channels — for gaming parties, stream setups, or live editing hangouts.</li>
      <li>Stream & Content Suggestions Forum — drop ideas on what we should record, stream, or create together!</li>
    </ul>

    <h3>Diverse Channels for Every Interest</h3>
    <p>Beyond gaming and media, explore channels dedicated to music, art, and general discussions. Whether you’re sharing content or just chatting, there’s always a conversation waiting for you.</p>

    <h3>Interactive Events and Competitions</h3>
    <p>FLAK hosts regular events like tournaments, trivia nights, movie marathons, and themed events. Our competitions and activities make it easy to engage and have fun with other members.</p>

    <h3>Support and Feedback</h3>
    <p>Use our ticket system for any support you need, from navigating the server to sharing ideas for improvement. We value member input and aim to keep Game Sphere a positive, welcoming place for all.</p>

    <h3>Achievements and Ranks</h3>
    <p>As you engage and contribute, you can earn ranks and special roles. It’s our way of recognizing and celebrating the unique energy each member brings to the community.</p>

    <p>At FLAK, we’re not just here to build a server — we’re building a place where friendships form, passions grow, and good memories are made.</p>
    <p>We’re proud of the space we’ve created together, and we’re even more excited about where we’re headed next.</p>

    <p>No matter why you joined — whether it’s to find a squad, vibe in VC, share your wins, study for exams, or just make a few new friends — know that you’re welcome here, just as you are.</p>

    <p>We’re a community that’s all about positivity, support, and good times.</p>

    <p>This server is shaped by everyone who’s a part of it — and now that you’re here, you’re part of the story too.</p>

    <p>So jump in, make yourself at home, and don’t be afraid to be yourself.</p>

    <p>We’re so glad you’re here. Welcome to FLAK — let’s make it unforgettable.</p>
  </div>

  <!-- Feedback Section -->
  <div id="feedback-section">
    <h3>Send Us Your Feedback</h3>
    <textarea id="feedback-message" rows="4" placeholder="Enter your feedback here"></textarea>
    <br>
    <button onclick="sendFeedback()">Submit Feedback</button>
  </div>

  <script src="https://cdn.emailjs.com/dist/email.min.js"></script>
  <script>
    // Initialize EmailJS with your user ID
    emailjs.init("Elia"); // Replace with your EmailJS user ID

    function sendFeedback() {
      var feedbackMessage = document.getElementById('feedback-message').value;

      if (feedbackMessage) {
        var feedbackData = {
          message: feedbackMessage,
          user_email: "user@example.com",  // Optional: You can also collect user's email if desired
        };

        // Sending feedback using EmailJS
        emailjs.send("service_mw8uqcj", "template_v4t9z7e", feedbackData)
          .then(function(response) {
            alert('Feedback sent successfully!');
            document.getElementById('feedback-message').value = ''; // Clear the textarea after submission
          }, function(error) {
            alert('Failed to send feedback. Please try again later.');
            console.log(error);
          });
      } else {
        alert("Please enter your feedback before submitting.");
      }
    }

    // Show the About section
    function showAbout() {
      document.getElementById('about').classList.toggle('hidden');
    }
  </script>
</body>
</html>
