==========================================================================
      ██████╗ ██╗   ██╗███████╗████████╗   ███████╗██╗   ██╗███████╗
      ██╔══██╗██║   ██║██╔════╝╚══██╔══╝  ██╔════╝╚██╗ ██╔╝██╔════╝
      ██████╔╝██║   ██║███████╗   ██║       █████╗    ╚████╔╝ █████╗  
      ██╔══██╗██║   ██║╚════██║   ██║       ██╔══╝    ╚██╔╝  ██╔══╝  
      ██║  ██║╚██████╔╝███████║   ██║       ███████╗   ██║   ███████╗
      ╚═╝  ╚═╝ ╚═════╝ ╚══════╝   ╚═╝       ╚══════╝   ╚═╝   ╚══════╝
                     
                     SURVEILLANCE IS ACTIVE // v1.0.0
==========================================================================

Welcome to RustEye — the ultimate CLI-based utility tool for solo players 
and competitive Rust clans. Keep your eyes on the server without losing 
a single FPS or Alt-Tabobsessing over BattleMetrics in heavy browsers.

--------------------------------------------------------------------------
[!] CRITICAL SETUP (PLEASE READ BEFORE RUNNING)
--------------------------------------------------------------------------
For RustEye to work properly on your system, you MUST place the executable 
file and all config files in the EXACT same folder [example 4]. 

Make sure your folder structure looks like this:
  📂 RustEye_v1.0/
   ├── 📄 RustEye.exe        <-- The main application
   ├── ⚙️ constraction.json  <-- Raid calculation database
   ├── ⚙️ liveRadar.json     <-- Enemy tracker storage
   └── ⚙️ profileInfo.json    <-- Personal stats storage

If you delete or separate any .json files from the .exe, the application 
will crash with a FileNotFoundError!

--------------------------------------------------------------------------
[⚡] INITIAL ACTIVATION
--------------------------------------------------------------------------
1. Run RustEye.exe for the first time.

2. You will be taken to the basic subscription program interface.

3. If you need a subscription, select Mode 6 and paste the key in the following format: RUSTEYE-XXXX-XXXX-XXXX
4. Press Enter. The application will sync with the cloud database, activate your premium license, and securely link the build to your PC.

5. Subsequent launches will launch the application in premium mode.

--------------------------------------------------------------------------
[📡] CORE FEATURES & COMMANDS
--------------------------------------------------------------------------
• MODE 1: BattleMetrics Server & Player Search
  Look up any active Rust server, see live pop, and instantly search for 
  specific players currently roaming on that server.

• MODE 2: RustStats Player Profile
  Get a full deep-dive into any player's lifetime stats (K/D ratio, 
  bullets fired vs hits, accuracy, custom gathering metrics, and bans).

• MODE 3: RaidCalc
  Calculates the exact amount of C4, Rockets, Satchels, Explo Ammo, or 
  Beancans needed to blast through any wall, door, or trap in the game.

• MODE 4: My Profile
  Link your own SteamID to track your session progress and personal K/D.

• MODE 5: LiveRadar (THE CHIEF MODULE)
  Add your toxic neighbors or rival clan members to the tracking list. 
  The script autonomously loops in the background every 30 seconds:
   -> [ONLINE] Alert: RustEye will play a loud system BEEP notice the 
      second your tracked enemy logs into the server. Defend your base!
   -> [OFFLINE] Intel: Displays exactly which server they just rage-quitted 
      from and logs their exact logout time. Perfect for tactical offline raids.
   -> Press [Ctrl + C] anytime to safely pause the background loops and 
      open the radar management menu (Add/Delete/Exit).

--------------------------------------------------------------------------
[🛡️] SECURITY & PERFORMANCE
--------------------------------------------------------------------------
- 100% Safe from Anti-Cheat: RustEye communicates strictly via public web 
  endpoints (BattleMetrics / RustStats RPC). It does NOT inject, modify, 
  or read game memory. Zero risk of getting an EasyAntiCheat (EAC) ban.
- 0% Resource Consumption: Built entirely as a rigid command-line utility. 
  It runs perfectly on a second monitor, consuming 0% of your GPU and 
  RAM, leaving all execution power to your game.

--------------------------------------------------------------------------
[🔧] TROUBLESHOOTING
--------------------------------------------------------------------------
- "Database server error / Cloud connection failed":
  Make sure your Windows Firewall isn't blocking RustEye from making outbound 
  HTTPS requests. Internet connection is required for activation and radar.
- "Invalid Input / Out of range":
  Always read the menu prompts. Use the designated integer numbers (or -1) 
  to navigate the shell correctly.

==========================================================================
       Eye for an eye. Rust for the Rust. Good luck on the wipe!
==========================================================================
