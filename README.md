![icon_small](https://github.com/user-attachments/assets/10876868-dbe5-47cd-9d0e-650450e6a29a) 
# Obtainium Emulator Pack

**(Forked from: https://github.com/RJNY/Obtainium-Emulation-Pack)**

An [Obtainium](https://github.com/ImranR98/Obtainium) import file that adds popular Android
emulation applications to Obtainium.

To begin, head over to the releases section and download the latest 'obtainium-emulator-pack.json' file. Then, import the file using Obtainium.

**Included Applications:**

- Daijishou
- Dolphin (Development Versions)
- DuckStation (Beta Version)
- Cemu
- EKA2L1
- Key Mapper
- Azahar
- MelonDS (stable)
- MelonDS (nightly)
- NetherSX2 Patch (TRACK ONLY)
- PPSSPP
- RetroArch (AArch64) (nightly)
- ScummVM
- Ship of Harkinian (Zelda - OOT Port)
- 2 Ship 2 Harkinian (Zelda - MM Port)
- Turnip Drivers (TRACK ONLY)
- Vita3K
- Winlator
- Obtainium

**Optional:**
- More Crowdsourced app configurations available here; hosted by the maintainer of Obtainium:
    [apps.obtainium.imranr.dev](https://apps.obtainium.imranr.dev)

**Explanation of “TRACK ONLY” Applications:**
- As the name suggests, these application versions are only tracked, not automatically downloaded. This was implemented due to legal restrictions that prevent us from directly downloading these resources. However, you will still receive update notifications, allowing you to manually download the resources when they become available. For instance, NetherSX2 cannot provide an APK for legal reasons, but you will be notified of updates so that you can download the resource manually.

**Instructions for Using “TRACK ONLY” Resources:**
- Upon receiving an update notification for a “TRACK ONLY” resource:
    - visit the link to your resource
    - download it manually
    - in obtainium > click resource > click "Mark Updated"

**Removing Applications:**
- If you do not wish to include an application, simply remove it from your list.

**Citra and Yuzu:**
- Regrettably, Citra and Yuzu are not included in this pack due to legal restrictions imposed by Nintendo.

**A Note Regarding Stable, Nightly, and Canary Versions of the Same Application:**
- It is not possible to install multiple versions of the same application. For instance, you must choose between RetroArch (stable) and RetroArch (nightly). You cannot have both versions installed simultaneously.

**How Does This Function?**
- Obtainium enables you to filter for links on a webpage using regular expressions (regex).
Additionally, it allows you to follow multiple links using regex.
For a basic example of how this works, please refer to https://regexr.com/7rmf7.

**Potential Risks and Considerations:**
- It is important to note that this functionality is not foolproof and can potentially be affected by changes made by the website’s maintainer.
Any scrapers that utilize regex may encounter issues if the maintainer modifies their webpage.
In contrast, applications that retrieve data from GitHub tend to be more stable and less prone to breaking due to such changes.
