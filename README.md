# 🕹️ OMNI-ARCADE: Project Outbreak 
> **The bastard child of *Dead Ops Arcade*, *Halo's* systemic sandbox, and *Half-Life's* physics playground.**  
> Built with modern modular software architecture in Godot 4.
> (A.I IS HELPING THIS RUSTY SOFTWARE DEVELOPER! Helping me learning godot and gdscript!)
> Probably some assets too (if i were to model, draw, animate, do it all. I would never complete it
> HONESTY!!!!! ALWAYS!

---

### 💥 Vision
Most horde shooters fall into one of two traps: they are either mindless screen-melting bullet-hells where you hold one button, or rigid scripted arenas that get stale after three runs.

**Omni-Arcade** is an explosive, physics-driven arcade rogue-lite built around **emergent systemic combat, targeted weapon engineering, and dynamic perspective shifts.** 

You start in tight, claustrophobic industrial zones fighting off hordes with twin-stick precision. As waves escalate, the environment itself cracks open into massive multi-tiered tactical sectors with choke points, vertical catwalks, and interactable environmental traps. Pick up temporary exotic super-weapons, solve mid-wave adrenaline challenges to earn permanent targeted weapon mods, and jump through secret portals into retro first-person motorcycle blitzes.

---

### 🏛️ Core Pillars

#### 1. Systemic Sandbox Combat (*Halo & Half-Life DNA*)
* **Physics as a Weapon:** Explosions, kinetic shotguns, and gravity traps don't just do number damage—they apply physical impulse (`RigidBody3D`). Launch explosive canisters into charging brutes, punt armored zombies into bottomless chasms, or drop suspended cargo crates onto elite swarms.
* **Elemental Reactions:** Water conducts electricity into shock-arcs; oil slicks cause enemies to lose steering control before being ignited into burning blockades; frozen targets shatter into lethal shrapnel when hit with blunt kinetic weapons.

#### 2. Targeted Weapon Engineering & The "Power Weapon" Economy
* **Primary / Secondary / Heavy Slots:** You keep your reliable sidearms and rifles, while devastating exotics (Flamethrowers, Chain-Lightning Cannons, Miniguns) act like *Halo power weapons*—time-limited or ammo-limited tools of mass destruction designed to turn the tide of impossible waves.
* **Targeted Mod Sockets:** When you complete a challenge or secure a rare upgrade (e.g., `+15% Fire Rate`, `Bouncing Shrapnel`, `Cryo-Rounds`), you choose **which specific weapon** in your arsenal gets the socket. Do you turn your reliable shotgun into a room-clearing frost bomb, or make your fast SMG a hyper-velocity laser?

#### 3. Expanding, Tactical Arenas
* **Dynamic Multi-Sector Layouts:** You don't stay trapped in a small square. As rounds advance, security blast doors unlock, power stations come online, and bridges extend, revealing high-ground sniper catwalks, hazard zones, and automated factory traps. Survival becomes about macro-kiting and spatial awareness, not just spinning in circles.

#### 4. The Multi-Perspective Engine (*The Omni-Camera*)
* **Seamless Perspective Morphing:** Built entirely in 3D, the camera isn't locked. 
  * *Top-Down Twin-Stick:* The primary tactical view for crowd control.
  * *2D Side-View Platforming:* Vertical levels where jumping, climbing ladders, and dropping grenades from overhead pipes are the only way to avoid ground stampedes.
  * *3D Over-The-Shoulder:* Precision encounters against colossal multi-phase bosses.

#### 5. Wacky Secret Romps & Adrenaline Trials
* **In-Wave Mastery Trials:** Picking up a weapon triggers an optional high-stakes trial (*"Slay 30 crawlers in 20 seconds"*). Pull it off, and you earn a permanent mod socket. Fail, and you just burned your ammo for nothing.
* **Secret Arcade Portals:** Discover hidden exits that throw you into standalone retro minigames—like a high-speed pixelated motorcycle highway run mowing down zombies for high-tier loot, or piloting an industrial mech for an upcoming boss round.

#### More to come, to think of in the future... (TBD)
---

### 🛠️ Technical Specifications
* **Engine:** Godot 4.x
* **Language:** GDScript
* **Architecture:** Composition-over-inheritance, Event Bus signal routing, and Data-Driven `Resource` configuration.
* **License:** MIT
