# 🎮 Clouheim - Beta

📅 Beta Dates: 07/18/2025 - 07/21/2025

🖥️ Platform: PC

📝 Description: Structure with collision outside boundaries after mountain jump

⚠ Bug found - 🔸 Exploit / Design and Visual – Allows access to unintended areas and reveals visual flaws

In the mountain area to the left, after using the jump mechanism, it’s possible to climb the slope up to the highest reachable point. From there, jumping to the left allows 
the player to cross a canyon and reach a structure that appears to be outside the map boundaries. Surprisingly, this structure has collision, allowing the player to walk on it.

However, there’s no continuation of the scenery — only a direct view into what can be described as the “limbo.” If the player falls from this structure, they are automatically 
teleported back to the start of the current stage.
