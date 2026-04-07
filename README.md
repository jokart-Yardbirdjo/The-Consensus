🎮 The Consensus Party Game
A fast-paced, real-time multiplayer party game where players use their phones as controllers to vote, guess, and debate. Host the game on a big TV or laptop, and let everyone in the room connect instantly via a 4-letter code or QR scan!

Built with Vanilla JavaScript, Firebase, and OpenAI.

✨ Features
📱 Mobile-as-Controller: No app downloads required. Players join via a simple web link and room code.

🤖 Infinite AI Engine: Bring Your Own Key (BYOK) OpenAI integration. The game uses GPT-4o-mini and a custom "entropy engine" of 160,000+ wildcard theme combinations to ensure you never see the same question twice.

📦 Party Pack Mode: Don't want to use AI? The game includes a built-in database of 100 hand-crafted, party-tested questions ready to play offline.

⚡ Real-Time Sync: Powered by Firebase Realtime Database for sub-second latency between the Host screen and Player phones.

🔥 Double Points Rounds: Hidden multipliers are injected into random rounds to keep the stakes high.

⏸️ Host Controls: A universal Pause button freezes the game across all devices. Auto-advancing timers keep the game moving without the host having to click "Next" all night.

🎲 The 5 Question Types
The game randomly balances rounds across five distinct game mechanics:

👉 The Finger Point: "Who is most likely to do absolutely nothing on a vacation?" (Vote for the player in the room who fits the prompt best).

⚖️ The Great Divide: "Which is the superior pet: Dogs or Cats?" (Vote for your favorite, then guess which one the room picked).

🧠 Hive Mind: "Name something you'd pack for a trip to the Bahamas." (Pick the #1 most popular survey answer to score the most points).

✋ Guilty As Charged: "Raise your hand if you have ever built a web app." (Players secretly confess, then guess the total number of hands raised in the room).

🎯 Shot In The Dark: "Guess the exact number of miles between Chicago and Singapore." (The closest numeric guess takes the gold).

🚀 How to Play
Host the Game: Open the game link on a laptop, tablet, or smart TV and click 📺 HOST A GAME.

Set the Rules: Choose your round count (5, 10, or 15) and select your question source (Party Pack or Infinite AI).

Join the Lobby: Players scan the QR code on the screen or visit the site on their phones and enter the 4-letter room code.

Start: Once everyone is in, the host clicks "Generate & Start." Put your phones down, look at the TV, and get ready!

🛠️ Tech Stack
Frontend: HTML5, CSS3, Vanilla JavaScript (Zero heavy frameworks, entirely single-page architecture).

Backend / State Management: Firebase Realtime Database (using firebase-app-compat).

AI Generation: Direct client-to-API calls using the OpenAI gpt-4o-mini model.

Utilities: QRCode.js for dynamic lobby generation.

💻 Local Development & Deployment
Because this is a completely serverless frontend application, deployment is incredibly simple.

Clone this repository.

Ensure index.html and db_questions.json are in the same root directory.

Host the folder using any static web host (GitHub Pages, Vercel, Netlify, or a local Live Server).

(Optional): If you want to isolate the database completely to your own Firebase project, replace the firebaseConfig object in the <script> tag with your own Firebase credentials.

Developed by Karthik Raja
