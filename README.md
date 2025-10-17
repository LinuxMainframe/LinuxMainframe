# Aidan Bradley (@LinuxMainframe) 👋

Hi, I'm Aidan, a senior Chemistry major at the University of Connecticut with a passion for integrating advanced chemistry with innovative tech solutions. Self-taught in programming, I’ve built production-grade systems for livestream automation, embedded hardware, and network infrastructure over 3+ years. My chemistry expertise spans analytical techniques (GCMS, HPLC, electrochemistry, NMR), synthetic organic chemistry (porphyrins, titanium complexes), and biochemistry (phase transfer, drug delivery). I’m developing personal open-source lab equipment to democratize access to advanced tools for students. Currently learning the Qt Framework, I/O, threading, and multiprocessing to enhance my application development skills. I’m eager to contribute to open-source projects and secure internships or part-time roles in software development, embedded systems, scientific computing, or cybersecurity.

## 👀 Interests
- Python and C application development
- Embedded systems (Raspberry Pi Pico, microcontrollers, custom PCBs)
- Networking and infrastructure automation (ProxMox, Ubiquiti, PoE, VLANs, trunking, loopback protection)
- Analytical chemistry (chromatography, spectrometry, electrochemistry, NMR)
- Synthetic organic chemistry and biochemistry (porphyrins, drug delivery)
- Open-source lab equipment design (fluid handling, reaction monitoring, data analysis, calibration)
- Cybersecurity (network security, ethical hacking, program and hardware security)

## 🌱 Currently Learning
- **Qt Framework**: Building cross-platform GUI applications
- **I/O, Threading, Multiprocessing**: Optimizing performance in Python and C
- **Cybersecurity Tools**: Nmap, Wireshark for network analysis
- **Advanced Chemistry**: High-level theory (QFT, TDDFT, DFT); analytical sensor theory and manufacturing

## 💻 Key Projects
- **[OPS-Live-Controller](https://github.com/LinuxMainframe/OPS-Live-Controller)**  
  Python-based automation suite for OBS Studio, powering 24/7 livestreams for paintball tournaments. Manages 16+ IP cameras using FFmpeg/RTMP, WebSockets, and v4l2loopback, achieving near-zero downtime over 3 years. Implements exponential retries and stream quality scoring (resolution, FPS, duplicates) for robust performance.  

- **[RPiPicoMAX6921lib](https://github.com/LinuxMainframe/RPiPicoMAX6921lib)**  
  C library for RP2040/2030 microcontrollers to drive MAX6921 LED displays via SPI, with plans to support MAX6921 + VFD combos. Applied in custom paintball velocity detection circuits using radar (BGT24LTR11N16) and STM32L476 MCU. Arduino-compatible with Doxygen documentation.  

- **Persistent IP Camera Connector (libpicc)**  
  Modular C library for persistent RTMP connections to IP PoE cameras (Reolink models), featuring stream quality scoring and recovery states. Tested with Valgrind (94% pass rate, zero memory leaks) and integrated with v4l2loopback for virtual devices. *(In development, private repo)*  

- **OBS WebSocket v5 Protocol Library (libwsv5)**  
  C library for persistent RPC-JSON connections to OBS WebSocket v5 servers, enabling all officially supported commands (e.g., scene control, authentication). Designed for thread-safety and modularity, used in production for multi-instance OBS management. *(In development, private repo)*  

- **ProxMox Cluster Infrastructure**  
  Configured a 3-node cluster on HP ProLiant servers (Gen7/8), testing applications like Ente (troubleshooting S3/Redis issues) and headless Debian LXC containers for multi-machine script deployment. Ensured data hygiene with scheduled backups via ProxMox’s built-in scheduler and custom rsync scripts for redundant storage.  

- **Personal Chemistry & Open-Source Lab Equipment Projects**  
  Conducted academic research at UConn on analytical chemistry (GCMS, HPLC, electrochemistry, NMR), synthetic organic chemistry (McMurray Coupling for porphyrin synthesis, novel titanium complexes for photocatalysts), and biochemistry (phase transfer, drug transfer in homogenized solutions like stomach/bile systems). Independently exploring personal chemistry projects, including titanium-based photocatalysts, natural dye synthesis, and abandoned violurate dye synthesis. Developing open-source lab tools (in progress), including contactless fluid pumps to avoid chemical-valve interactions, load-cell circuitry for precise measurements, a DIY spectrophotometer for spectrometry, and reaction monitoring systems for cost-effective student access.  

- **Network Management**  
  Designed and maintained network infrastructure for paintball tournaments, installing 1000-2000 feet of shielded CAT6/e outdoor cabling and managing Reolink PoE IP cameras (e.g., B810A, 1210A). Configured Ubiquiti dual-band WiFi (private/public networks) supporting 500+ weekly visitors. Optimized access point placement, implemented spanning tree protocol for loopback prevention, and performed fault testing. Developed custom Nmap scripts for Reolink device monitoring, including a MAC lookup table to track network changes (e.g., detecting camera resets/reconfigurations).

- **[Paintball Chronography System]**  
  Developing a modern chronography system for Matt's Outback Paintball to measure FPS of 0.68 caliber paintballs, adapting a SeedStudio module to replace an outdated 1989 design. Secured contracts with nearly paintball fields across the USA to deploy this system, addressing the gap left by a retired electrical engineer who ceased support and repairs. Integrates embedded hardware and software for robust, field-ready velocity detection, enhancing safety and performance for tournament play. Mainly designed with green ideology: ie. ultra-low power consumption technology, and sofware designed to minize power consumption. *(In development, private repo)*

## 🛠️ Skills
- **Programming**: Python (asyncio, Selenium, FFmpeg), C (thread-safety, API design), HTML/CSS/JS (fundamentals)
- **Systems & Networking**: ProxMox, LXC, Docker basics, PoE standards, Ubiquiti configuration, cable termination, fault isolation
- **Embedded**: RP2040/2030, SPI, KiCad circuit design, radar/MCU integration
- **Chemistry**: Analytical (HPLC, spectrometry), synthetic organic (McMurray Coupling, porphyrins), transition metal complexes (titanium), polymerizations, biochemistry (phase transfer, drug transfer)
- **Lab Equipment Design**: Contactless fluid handling, load-cell circuits, DIY spectrophotometry, reaction monitoring (in development)
- **Tools**: Git, Valgrind/Helgrind, OBS WebSockets, v4l2loopback, Doxygen
- **Soft Skills**: Problem-solving, documentation (READMEs with diagrams), project management

## 🏆 Achievements
- **Charles E. Warring Chemistry Scholarship**, UConn (2024)
- **Cum Laude**, NJCL Latin Honor Society
- **Volunteer**, Science Olympiad (3D protein modeling instructor)
- **AP Scores**: Computer Science A (4), Chemistry (4), Psychology (4)

## 💞️ Collaboration
I’m excited to contribute to open-source projects in:
- Media automation (e.g., OBS, FFmpeg plugins)
- Embedded systems (Raspberry Pi, IoT)
- Cybersecurity tools or network automation
- Computational chemistry or open-source lab equipment design

Reach out via GitHub Issues or email to collaborate!

## 📫 Contact
- **Email**: aidan.bradley@uconn.edu
- **LinkedIn**: [linkedin.com/in/aidanbradleyresearch](https://linkedin.com/in/aidanbradleyresearch)
- **GitHub**: [github.com/LinuxMainframe](https://github.com/LinuxMainframe)

## ⚡ Fun Fact
I’m a long-distance backpacker and cyclist, always planning my next adventure on the trails or roads!

---

*This profile is a work in progress, just like my projects. Check back for updates!*
