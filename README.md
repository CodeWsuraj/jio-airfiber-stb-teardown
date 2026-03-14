<div align="center">
  <img src="banner.svg" alt="Jio AirFiber STB Teardown Title Banner" width="100%">
</div>

# Jio AirFiber Set-Top Box (IPSTB JMSC200A2_J) Complete Teardown

This repository contains an extensive hardware breakdown, high-resolution internal gallery, and component research for the **Jio Set-Top Box**—specifically the **IPSTB JMSC200A2_J** model provided with Jio AirFiber network subscriptions.

**🌐 Live Site (SEO & Gallery Optimized):** [https://CodeWsuraj.github.io/jio-airfiber-stb-teardown](https://CodeWsuraj.github.io/jio-airfiber-stb-teardown)

---

## 🔬 Hardware Specifications

At the core of the IPSTB JMSC200A2_J rests an extremely robust architecture powered by Amlogic. This silicon configuration allows native decoding for emerging standards like AV1 and VP9 at smooth 4K 60fps frame rates.

| Chip / Component | Manufacturer | Specifications / Identification | Details |
| :--- | :--- | :--- | :--- |
| **Main SoC Processor** | Amlogic | **S905X4** (MA1356-0604)<br>Quad-core ARM Cortex-A55 @ 2.0 GHz<br>Mali-G31 MP2 GPU | BGA package, prominent in high-end 4K media devices. Supports AV1, Gigabit Ethernet, and HDMI 2.1 traces. |
| **eMMC Storage (32GB)** | SCY | **E32GCYNB1ABE00**<br>256Gb TLC x1 Die | YMTC Xtacking 3D architecture. JEDEC eMMC 5.1 compliant (1.8V/3.3V). High-density surface mount. |
| **Memory Config (RAM)** | SCY | **SD40D86G-FC / -FG** | High-speed LPDDR4 DRAM configured in dual-channel footprints to supply peak cache speeds for system UI loops. |

---

## 🖼️ High-Resolution Photography

This repository houses all original, cleanly numbered components inside the `/assets/` directory.

The frontend (`index.html`) is structured with **Zero-Gap Box Grid Layouts** allowing visitors to analyze intricate surface-mount tracings, network shielding footprints, and thermal management layout uninhibited.

* **Tech Stack for frontend:** 
  * Absolute zero-dependency vanilla HTML/CSS.
  * Native CSS Grid logic for optimized layout rendering. 
  * Raw DOM Lightbox integration.
  * 100/100 Core Web Vital metrics formatting.

---

## 🛠️ Community & Modding

Are you looking to break boundaries, unlock advanced functionalities, and explore custom firmware within the Jio Set-Top environment? 

**We highly recommend checking out the developers at the [JFC-Group](https://github.com/JFC-Group).**

Their massive open-source ecosystem focuses around:
* JioFiber (JF) & AirFiber (AF) specific Firmware customizations.
* Specialized MIPSEL network configurations like OpenSSH and Dropbear endpoints.
* Tunnelling restricted networking layers with Cloudflare metrics.
* Standalone JioTV bypasses running directly over `Go`. 

## 🚀 Deployment Instruction for GitHub Pages

If deploying your own version or translating:

1. Fork this repository.
2. Ensure the repository name matches the URL structure (e.g., `jio-airfiber-stb-teardown`).
3. Navigate to **Settings > Pages**.
4. Set the build source to **Deploy from a branch** and select the `main` or `master` branch.
5. GitHub will index the rich JSON-LD data and automatically serve the fully responsive application.

---

<p align="center">
  <i>Documented for Open-Source Security Analysis and Educational Engineering.</i>
</p>