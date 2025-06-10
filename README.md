# 🎮 Multiplayer Game using Unreal Engine + Steam Advanced Sessions

This project is a **multiplayer game prototype** built using **Unreal Engine** with **Steam Advanced Sessions integration**. The game provides a **smooth and secure multiplayer experience** by leveraging **Steam's peer-to-peer networking**, eliminating the need to manually share IP addresses.

---

## 🚀 Project Overview

- **Engine**: Unreal Engine 5 (UE 4.27+ supported)
- **Networking**: Peer-to-peer via Steam
- **Multiplayer Framework**: Steam Advanced Sessions Plugin
- **Purpose**: Secure, seamless, plug-and-play multiplayer experience

This game enables players to host and join online sessions using their Steam accounts. The entire connection flow works with **Steam Authentication**, enhancing **player security**, **session reliability**, and simplifying the matchmaking process.

---

## 🔑 Why Steam Advanced Sessions?

Traditional multiplayer games using Unreal’s native Online Subsystem often require IP addresses for connection, which:
- Poses **privacy concerns**
- Requires **port forwarding** and manual setup

Instead, **Steam Advanced Sessions** offers:
- ✅ **No IP sharing** – only Steam ID required
- ✅ **Private & public lobbies**
- ✅ **Friend-based invites & session browser**
- ✅ **Session stability and NAT traversal**
- ✅ **Improved player authentication & reliability**

---

## ✨ Key Features

- 🔗 **Steam-based login system**
- 🧩 **Join via friends list or session browser**
- 🛠️ **Dedicated or listen-server hosting**
- 🎮 **Optimized for smooth multiplayer experience**
- 🔒 **No port forwarding / IP required**
- 📡 **Peer-to-peer architecture via Steam**

---

## 🛠️ Technologies Used

- Unreal Engine 5 / 4.27
- Blueprints & C++
- Steamworks SDK
- Steam Advanced Sessions Plugin (by mordentral)
- Epic Online Services (Optional fallback)

---

## 🧪 How to Use

### 🧷 Prerequisites

- Steam installed and running
- Unreal Engine (4.27+ or UE5)
- Plugin: [Steam Advanced Sessions](https://github.com/mordentral/AdvancedSessions)

### 🔧 Setup Instructions

1. Clone or download this repository.
2. Make sure Steam is running in the background.
3. Enable the following plugins in Unreal:
   - **Online Subsystem**
   - **Online Subsystem Steam**
   - **Advanced Sessions**
   - **Advanced Steam Sessions**

4. Configure DefaultEngine.ini for Steam:
   ini
   [OnlineSubsystem]
   DefaultPlatformService=Steam

   [OnlineSubsystemSteam]
   bEnabled=true
   SteamDevAppId=480


5. Package the game and run via Steam OR use **Play as Standalone** with **Number of Players > 1**.

---

## 📂 Folder Structure


/Source/
├── CoreGameplay/
├── MultiplayerLogic/
│   ├── CreateSession
│   ├── FindSessions
│   └── JoinSession
├── UI/
│   ├── MainMenu
│   └── LobbyScreen
/Config/
├── DefaultEngine.ini




## 🎯 Planned Improvements

* In-game voice chat via Steam
* Server browser with filters
* LAN + Steam hybrid support
* UI polish and match settings customization
* Steam Achievements & Rich Presence

---

## 👨‍💻 Author

**Durkesh Kumar S**
🎮 Unreal Engine Developer | Multiplayer Systems Designer
📫 [durkeshkumarofficial@gmail.com](mailto:durkeshkumarofficial@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/durkesh-kumar-s)

---

## 🙌 Acknowledgements

* [Mordentral](https://github.com/mordentral) – Steam Advanced Sessions plugin
* Epic Games – Unreal Engine
* Steamworks SDK – Multiplayer backend
* Community contributors for Unreal multiplayer tutorials

---

## 📢 Feedback & Contributions

Feel free to star ⭐, fork 🍴, or raise an issue 🛠️.
Pull requests are welcome — let’s build more reliable multiplayer systems together!

> “Multiplayer should be seamless, not stressful.”



