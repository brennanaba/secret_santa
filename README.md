# Secret Santa PeerJS Game

A real-time multiplayer Secret Santa game using PeerJS for WebRTC connectivity. No server required.

## How to Play

1.  **Host**: Open the game on a laptop. Click "HOST GAME".
2.  **Players**: Open the game on their phones. Enter their name and the Room Code displayed on the Host's screen (or scan the QR code).
3.  **Lobby**: Wait for all players to join. Host clicks "Start Game".
4.  **The Wheel**: Host spins the wheel to select a person.
5.  **Voting**: Players vote on who they think the selected person is (or follow the chaos challenge).
6.  **Scoring**: Host reveals the answer and scores are updated.

## Tech Stack

-   HTML5
-   CSS Grid (Festive Theme)
-   PeerJS (WebRTC)
-   QRCode.js

## Hosting

This game works perfectly on **GitHub Pages**.

1.  Push this code to a GitHub repository.
2.  Go to **Settings** > **Pages**.
3.  Select the `main` branch and save.
4.  Your game will be live at `https://<your-username>.github.io/<repo-name>/`.

**Note**: PeerJS requires HTTPS (which GitHub Pages provides) or localhost. It will not work on HTTP over a local network (e.g., `http://192.168.1.5:5500`) unless you set up your own PeerServer or use a tunneling service.
