<div align="center">

# Scott Peterman

**Network tooling built by a network engineer.**
30 years in DC, core and peering. Everything here is open source, self-hosted, and runs with no external services.

</div>

---

### [netbridgeng](https://github.com/scottpeterman/netbridgeng): your switch, rendered as a ship's bridge

<a href="https://github.com/scottpeterman/netbridgeng"><img src="https://raw.githubusercontent.com/scottpeterman/netbridgeng/main/screenshots/screenshots.gif" width="100%" alt="netbridgeng: 3D neighbor radar, port utilization skyline, chassis environment, BGP and OSPF views"></a>

A switch already holds live, structured data about its neighbors, ports, sensors and routing sessions. netbridgeng pulls it over SSH and draws it as a 3D bridge: neighbor radar, port-utilization skyline, see-through chassis, BGP shields, OSPF map, and the device's own CLI. Arista EOS and Juniper Junos. A proof of concept with a point: as customers, we decide what our equipment looks like.

`pip install netbridgeng` &nbsp;·&nbsp; then open `http://127.0.0.1:8470/?demo`

---

### [Secure Cartography 2](https://github.com/scottpeterman/securecartography2): network discovery and topology mapping

<a href="https://github.com/scottpeterman/securecartography2"><img src="https://raw.githubusercontent.com/scottpeterman/securecartography2/main/screenshots/main_complete_light.png" width="100%" alt="Secure Cartography 2: completed crawl with discovered topology"></a>

Seed one IP and it crawls the network over SNMP with SSH fallback, following CDP/LLDP and, optionally, BGP/OSPF/EIGRP neighbors to find the mixed-vendor links CDP and LLDP miss. Interactive map with saved layouts, exports to Draw.io, yEd, PNG, CSV and JSON. No database, no web server, no Docker.

`pip install seccart2`

---

### [netlapse](https://github.com/scottpeterman/netlapse): network state time-lapse

<a href="https://github.com/scottpeterman/netlapse"><img src="https://raw.githubusercontent.com/scottpeterman/netlapse/main/screenshots/template_lab.png" width="100%" alt="netlapse Template Lab: raw show output auto-matched to a TextFSM template with scored, parsed records"></a>

An Oxidized replacement that captures any CLI output, not just configs. ARP, BGP, routes and interfaces are parsed into structured JSON, versioned, and diffed semantically: "peer went Established → Idle, prefixes 4200 → 0." One Search finds an IP, MAC, ASN or serial across the whole fleet. Serves an Oxidized-compatible API, so LibreNMS shows its configs and diffs natively. Shown: the Template Lab, where the output selects its own TextFSM template.

`pip install git+https://github.com/scottpeterman/netlapse`

---

### [terminaltelemetry2](https://github.com/scottpeterman/terminaltelemetry2): an SSH terminal with live telemetry beside it

<a href="https://github.com/scottpeterman/terminaltelemetry2"><img src="https://raw.githubusercontent.com/scottpeterman/terminaltelemetry2/main/screenshots/dashboard1.png" width="100%" alt="terminaltelemetry2: terminal session with live interface, BGP, OSPF, LLDP and CPU panels"></a>

Log in the way you always do, and the panels next to the terminal keep polling the device: interfaces, BGP, OSPF, LLDP, CPU, memory and top processes. Panels are plain YAML, so you can change them or write your own. Full coverage for EOS, IOS, NX-OS, Junos and Linux, with platform packs for about 40 more vendors.

`pip install terminaltelemetry2` &nbsp;·&nbsp; then `tt2`

---

### [OmegaSSH](https://github.com/scottpeterman/omegasshqt): a native terminal for Windows, macOS and Linux

<a href="https://github.com/scottpeterman/omegasshqt"><img src="https://raw.githubusercontent.com/scottpeterman/omegasshqt/main/screenshots/btop.png" width="100%" alt="OmegaSSH running btop in a native Qt terminal"></a>

Tabbed SSH, telnet and serial sessions, a session tree, an encrypted credential vault and per-session logging, with a terminal that handles full-screen apps like btop and vim. Go engine behind a C ABI, Qt on top. Part of the Omega Network Suite below.

---

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

---

<div align="center">

Denver &nbsp;·&nbsp; Former Cisco instructor

</div>