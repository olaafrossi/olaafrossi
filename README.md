# Hey, I'm Olaaf 👋

**CTO at [Three Byte](https://www.3-byte.com)** — a hardware, software, and design company helping teams build scalable operating systems from concept to production.

I run the engineering org, but I still write code every day. I believe CTOs who stop building lose their edge.

## The work that shaped us

Three Byte served as the **primary technology consultant** for [MoMath](https://momath.org), the National Museum of Mathematics in NYC. We were there from opening day in 2012 and again in 2026 and built a lot of what visitors interact with:

🤖 **Robot Swarm Exhibit** — Co-built the Robot Swarm with Knowledge Resources: two dozen glowing robots that pursue, evade, and self-organize in response to visitors tracked by infrared cameras. [Featured in IEEE Spectrum](https://spectrum.ieee.org/play-with-a-swarm-of-robots-at-nycs-museum-of-mathematics).

🔷 **The Mathenaeum** — A polyhedron builder where visitors model complex 3D shapes. Multi-threaded C++/OpenGL with the Cinder framework, optimized for real-time geometric manipulation on custom hardware.

🖥️ **Exhibit Control** — The entire museum runs on a control system we architected: power management, status reporting, and analytics. Exhibits talk to the backend via a signalR. Staff control and troubleshoot everything from their phones via a responsive browser interface. Built with C# Blazor and SQL in Docker/Portainer on Ubuntu. Agents run on the local machines (x64 and ARM32/64 windows, linux, mac, Raspberry pi) and Datadog & Vector for observability. 

## What I work with

**Daily drivers:** C# · .NET · TypeScript · Blazor · SignalR · Claude Code · Codex · Github Copilot · GStack     
**Infrastructure:** Azure · AWS · Vercel · GitHub Actions · CI/CD pipelines · TeamCity (RIP)  
**Currently exploring:** Neon · Supabase · Vercel · Next.js · Edge functions · React Native
**Hardware:** ClearCore Controllers · Raspberry Pi · RFID · Custom control systems  
**Museum tech:** Show control · Real-time tracking · Interactive exhibits · Kiosk applications

## 🌱 What I'm focused on now

- Leading Three Byte's product and engineering strategy
- Evaluating modern dev platforms (Neon, Supabase, Vercel) for rapid prototyping and production
- Bridging the gap between physical hardware systems and modern cloud software
- Staying hands-on — shipping features, reviewing PRs, and architecting solutions
- Shipping more code per day than I've ever done in my life with AI Tools. 

## Selected open source

🖥️ **[CrestronNetworkMonitor](https://github.com/olaafrossi/CrestronNetworkMonitor)** — Remote PC control over UDP via Crestron/AMX. Purpose-built for museum and corporate AV environments where dozens of PCs need automated power management. C#/WPF.  
🌡️ **[PiControlApp](https://github.com/olaafrossi/PiControlApp)** — Raspberry Pi sensor data streamed to a Blazor Server app via SignalR. A prototype for the kind of hardware↔cloud bridge we build at Three Byte.  
💡 **[HueControlWebAssemblyExample](https://github.com/olaafrossi/HueControlWebAssemblyExample)** — Browser-based Hue lighting control for live performance environments. Blazor WebAssembly talking to a WPF/Console backend via Azure App Service.  
⚙️ **[BuildServerProvision](https://github.com/olaafrossi/BuildServerProvision)** — CI server provisioning scripts.

## The philosophy

Technology is table stakes. Systems win. Whether it's a museum floor that knows who's walking on it or a cloud backend that scales without babysitting, the job is the same: build integrated, measurable platforms that let teams move fast without breaking things that matter.

---

📍 NYC · 🌐 [3-byte.com](https://www.3-byte.com) · 🏛️ [MoMath](https://momath.org)

<!--
**olaafrossi/olaafrossi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
