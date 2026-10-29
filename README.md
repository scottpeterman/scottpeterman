
<div align="center">

# The Omega Network Suite

**Native network tooling for Windows, macOS and Linux.**
Go engines behind a C ABI, Qt on top. Self-hosted, no external services.

Map the network, archive what's on it, connect to any of it.

<a href="https://apps.microsoft.com/detail/9NSMH9950K1B?mode=direct"><img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Get it from Microsoft"></a>

**Windows gets equal standing.** All three apps install together from the Microsoft Store: no admin rights, no Python, no WSL, updates handled by the Store.
macOS and Linux builds are on each project's Releases page.

</div>

| | |
|---|---|
| <a href="https://github.com/scottpeterman/omegamaps"><img src="https://raw.githubusercontent.com/scottpeterman/omegamaps/main/screenshots/splash-maps.png" width="400"></a> | **[OmegaMapsQt](https://github.com/scottpeterman/omegamaps)**<br>Point it at a seed device and get a map of your network. Crawls LLDP/CDP over SNMP and SSH across Junos, EOS and IOS, shows live crawl progress, and exports to draw.io. |
| <a href="https://github.com/scottpeterman/omegacatqt"><img src="https://raw.githubusercontent.com/scottpeterman/omegacatqt/main/screenshots/splash.png" width="400"></a> | **[OmegaCatQt](https://github.com/scottpeterman/omegacatqt)**<br>A CatTools-style archive for configs and device state, read-only by design. Pulls configs and show output, keeps every version, diffs what changed, and parses ARP/MAC tables into searchable data. Imports OmegaMaps crawls as inventory. |
| <a href="https://github.com/scottpeterman/omegasshqt"><img src="https://raw.githubusercontent.com/scottpeterman/omegasshqt/main/screenshots/splash-ssh.png" width="400"></a> | **[OmegaSSHQt](https://github.com/scottpeterman/omegasshqt)**<br>A native terminal for engineers who live in PuTTY. Tabbed SSH, telnet and serial sessions, a session tree, an encrypted credential vault, and per-session logging. |

### Building blocks

- **[anytermqt](https://github.com/scottpeterman/anytermqt)**: native Qt terminal widget with PySide6 bindings
- **[anyeditqt](https://github.com/scottpeterman/anyeditqt)**: C++/Qt6 code editor with ace's 198 grammars ported to native code

### Earlier work

- **Secure Cartography**: the Python network mapper omegamaps grew out of
- **[AutiobooksQTa](https://github.com/scottpeterman/autiobooksqta)**: EPUB to m4b audiobooks with Kokoro TTS

---

30 years in network engineering: DC, core and peering. Denver.