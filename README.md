# 🌌 LexiVault  

**LexiVault** is a centralized, high-performance personal vault designed for developers and Android modders. It serves as a secure repository for mission-critical notes, reverse engineering snippets, and curated media archives.

---

## 🚀 Core Modules

- **📝 Neural Notes:** A workspace for documenting logic flows and project ideas.
- **🔗 Hyperlink Hub:** Quick access to essential tools, APIs, and documentation.
- **🎬 Media Archive:** Organized tracking for Anime and Movies (Naruto/Boruto/JJK/CSM).
- **⚡ Modding Forge:** - **Smali & DEX Patches:** Pre-configured logic fixes.
    - **Regex Vault:** Custom regular expressions for bulk string manipulation and DEX editing.
    - **NDK Snippets:** Optimized code for `.so` library modification.

---

## 🛠 Tech Stack & Environment

- **Aesthetic:** Cyberpunk / Glassmorphism (Neon Purple Accents)
- **Primary Environment:** Termux (Android ARM64)
- **Tools Integrated:** MT Manager, NP Manager, LGL Mod Menu logic.

---

## 🧩 Sample Modding Regex

-  **Stored within LexiVault for quick retrieval:** 
Patch logic for *isPremium* checks:
Search: *\.method public static isPremium\(.*\)Z*
Replace: ```smali
*.method public static isPremium(Landroid/content/Context;)Z
.registers 2
const/4 v0, 0x1
return v0
.end method*

---

## 👤 Developer & Socials

**Built by:** **🦋⃟ᴠͥɪͣᴘͫ•𝐒𝐑𝟕 𝐌𝐨𝐝𝐬** *Expert Android Reverse Engineer & Software Modder*

- **GitHub:** [alexsifatrayhan](https://github.com/alexsifatrayhan)
- **Official Store:** [SR7 App Store](https://alexsifatrayhan.github.io/sr7mods-app-store/)
- **Specialization:** Smali Patching | DEX Editing | NDK Modification

---

## 🤝 Contribution
Contributions are strictly for authorized modders. If you have a high-efficiency regex or a new ARM64 patch, feel free to open a PR.

*Stay Technical. Stay Grounded.*
