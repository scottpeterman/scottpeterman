<div align="center">

# Scott Peterman

**Network tooling built by a network engineer.**
30 years in DC, core and peering. Everything here is open source, self-hosted, and runs with no external services.

</div>

---

### [netbridgeng](https://github.com/scottpeterman/netbridgeng): your switch, rendered your way!

<a href="https://github.com/scottpeterman/netbridgeng"><img src="https://raw.githubusercontent.com/scottpeterman/netbridgeng/main/screenshots/screenshots.gif" width="100%" alt="netbridgeng: 3D neighbor radar, port utilization skyline, chassis environment, BGP and OSPF views"></a>

A switch already holds live, structured data about its neighbors, ports, sensors and routing sessions. netbridgeng pulls it over SSH and draws it as a 3D bridge: neighbor radar, port-utilization skyline, see-through chassis, BGP shields, OSPF map, and the device's own CLI. Arista EOS and Juniper Junos. A proof of concept with a point: as customers, we decide what our equipment looks like.

`pip install netbridgeng` &nbsp;·&nbsp; then open `http://127.0.0.1:8470/?demo`

---

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/scottpeterman/securecartography2">Secure Cartography 2</a></h3>
<p><i>Network discovery and topology mapping</i></p>
<a href="https://github.com/scottpeterman/securecartography2"><img src="https://raw.githubusercontent.com/scottpeterman/securecartography2/main/screenshots/main_complete_light.png" width="100%" alt="Secure Cartography 2: completed crawl with discovered topology"></a>
<p>Seed one IP and it crawls over SNMP with SSH fallback, following CDP/LLDP and optionally BGP/OSPF/EIGRP neighbors to find the mixed-vendor links CDP and LLDP miss. Interactive map with saved layouts; exports to Draw.io, yEd, PNG, CSV and JSON. No database, no web server, no Docker.</p>
<p><code>pip install seccart2</code></p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/scottpeterman/netlapse">netlapse</a></h3>
<p><i>Network state time-lapse</i></p>
<a href="https://github.com/scottpeterman/netlapse"><img src="https://raw.githubusercontent.com/scottpeterman/netlapse/main/screenshots/template_lab.png" width="100%" alt="netlapse Template Lab: raw show output auto-matched to a TextFSM template with scored, parsed records"></a>
<p>An Oxidized replacement that captures any CLI output, not just configs. ARP, BGP, routes and interfaces are parsed to structured JSON, versioned, and diffed semantically. One Search finds an IP, MAC, ASN or serial across the fleet, and an Oxidized-compatible API puts its configs and diffs inside LibreNMS. Shown: the Template Lab, where the output selects its own TextFSM template.</p>
<p><code>pip install git+https://github.com/scottpeterman/netlapse</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/scottpeterman/terminaltelemetry2">terminaltelemetry2</a></h3>
<p><i>An SSH terminal with live telemetry beside it</i></p>
<a href="https://github.com/scottpeterman/terminaltelemetry2"><img src="https://raw.githubusercontent.com/scottpeterman/terminaltelemetry2/main/screenshots/linux.png" width="100%" alt="terminaltelemetry2: terminal session with live telemetry panels"></a>
<p>Log in the way you always do, and the panels next to the terminal keep polling the device: interfaces, BGP, OSPF, LLDP, CPU, memory and top processes. Panels are plain YAML, so you can change them or write your own. Full coverage for EOS, IOS, NX-OS, Junos and Linux, with platform packs for about 40 more vendors.</p>
<p><code>pip install terminaltelemetry2</code> then <code>tt2</code></p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/scottpeterman/omegasshqt">OmegaSSH</a></h3>
<p><i>A native terminal for Windows, macOS and Linux</i></p>
<a href="https://github.com/scottpeterman/omegasshqt"><img src="https://raw.githubusercontent.com/scottpeterman/omegasshqt/main/screenshots/btop.png" width="100%" alt="OmegaSSH running btop in a native Qt terminal"></a>
<p>Tabbed SSH, telnet and serial sessions, a session tree, an encrypted credential vault and per-session logging, with a terminal that handles full-screen apps like btop and vim. Go engine behind a C ABI, Qt on top. Part of the Omega Network Suite below.</p>

</td>
</tr>
</table>

## The Omega Network Suite

<a href="https://apps.microsoft.com/detail/9NSMH9950K1B?mode=direct"><img src="https://get.microsoft.com/images/en-us%20dark.svg" width="180" alt="Get it from Microsoft" align="right"></a>

Three native apps that install together from the Microsoft Store: no admin rights, no Python, no WSL. macOS and Linux builds are on each project's Releases page.

- **[OmegaMaps](https://github.com/scottpeterman/omegamaps)**: point it at a seed device and get a map; LLDP/CDP crawl over SNMP and SSH, draw.io export
- **[OmegaCat](https://github.com/scottpeterman/omegacatqt)**: CatTools-style, read-only archive of configs and device state, with version diffs and parsed ARP/MAC tables
- **[OmegaSSH](https://github.com/scottpeterman/omegasshqt)**: the terminal above

## Building blocks

- **[anytermqt](https://github.com/scottpeterman/anytermqt)**: native Qt terminal widget with PySide6 bindings
- **[anyeditqt](https://github.com/scottpeterman/anyeditqt)**: C++/Qt6 code editor with ace's 198 grammars ported to native code
- **[AutiobooksQTa](https://github.com/scottpeterman/autiobooksqta)**: EPUB to m4b audiobooks with Kokoro TTS

## Off hours: the arcade

Browser games I build on Friday nights and share with my sons: vector and wireframe shooters, 3D chess, a Wolfenstein-style Normandy landing. No install, they run in the page, phones included. **[Play them](https://scottpeterman.github.io/arcade)** &nbsp;·&nbsp; [source](https://github.com/scottpeterman/arcade)

<table>
<tr>
<td width="25%" align="center"><a href="https://scottpeterman.github.io/arcade"><img src="https://raw.githubusercontent.com/scottpeterman/arcade/main/games/deckrunner/thumb.webp" width="100%" alt="DECKRUNNER"></a><br><sub>DECKRUNNER</sub></td>
<td width="25%" align="center"><a href="https://scottpeterman.github.io/arcade"><img src="https://raw.githubusercontent.com/scottpeterman/arcade/main/games/banrion/thumb.webp" width="100%" alt="Banrion"></a><br><sub>Banrion</sub></td>
<td width="25%" align="center"><a href="https://scottpeterman.github.io/arcade"><img src="https://raw.githubusercontent.com/scottpeterman/arcade/main/games/normandy/thumb.webp" width="100%" alt="Normandy"></a><br><sub>Normandy</sub></td>
<td width="25%" align="center"><a href="https://scottpeterman.github.io/arcade"><img src="https://raw.githubusercontent.com/scottpeterman/arcade/main/games/six-fleets/thumb.webp" width="100%" alt="Six Fleets"></a><br><sub>Six Fleets</sub></td>
</tr>
</table>

---

<div align="center">

Denver &nbsp;·&nbsp; Former Cisco instructor

</div>