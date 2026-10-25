# UCSD 1:1 Minecraft Campus Project

This repository contains the backend configuration to run a 1:1 scale replica of the UC San Diego campus in Minecraft. Follow the instructions below to generate the map, initialize the server, and host it for your friends using Playit.gg.

## 1. Download the Project Files
Clone this repository to your local machine using Git, or click the **Code** button at the top of this page and select **Download ZIP**. Extract the folder to an easily accessible location, such as your Desktop.

## 2. Generate the World using Arnis
Because map files are too large to host on GitHub, you must generate the 1:1 campus map yourself.
1. Download and install the [Arnis](https://github.com/) mapping tool.
2. Select the UC San Diego geographical coordinates within the Arnis interface.
3. Export the generated map to your computer. Keep track of this exported map folder.
4. Replace "world" folder with generated Arnis map

## 3. Setup Public Hosting with Playit.gg
To let friends join without modifying your router's port forwarding settings, use the Playit.gg plugin.
1. Download the **Playit.gg Minecraft Java plugin** (`.jar` format) from their official website.
2. Drag the downloaded `.jar` file into your server's `plugins` folder.
3. Restart the server in your Terminal.
4. If you do not see a claim link in the console, type `playit account guest-login-link` directly into the Terminal and press Enter.
5. Copy the provided `https://playit.gg/claim/...` link and paste it into a web browser.
6. Follow the web dashboard prompts to configure a Minecraft Java tunnel. Once finished, the dashboard will assign you a permanent public address (e.g., `word-word.auto.playit.gg`).

## 4. Play with Friends
Keep your Terminal open and the server running. Share your permanent Playit.gg public address with your friends. 
1. Open Minecraft Java Edition **26.3**.
2. Click **Multiplayer** -> **Direct Connection**.
3. Paste the `.auto.playit.gg` address into the Server Address box (ensure there are no blank spaces at the beginning or end).
4. Click **Join Server** to enter the campus.
