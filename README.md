<img src="assets/header.svg" width="100%" alt="Jasim Siddiqui — useful software, thoughtful interfaces. Built in Toronto." />

I build apps that make everyday friction disappear: planning a transit run, finding a moment in a lecture, or getting a file under an upload limit. I care about the interface **and** the engineering that makes it work.

[Email me](mailto:jasims.0002@gmail.com) · [Explore my repositories](https://github.com/JasimSiddiqui?tab=repositories) · He/Him

## Selected work

### 01 / Stopover
**Every errand. One trip.**

<a href="https://stopover-site.vercel.app/"><img src="assets/stopover.jpg" width="100%" alt="Stopover's transit-map landing page with three mobile app previews" /></a>

Transit apps usually plan one leg at a time. Stopover brings a whole errand run together, accounting for time at each stop, departure times, and transfer windows.

**Behind the interface:** timetable-based routing with OpenTripPlanner, stop-order optimization, and fare continuity across a multi-stop trip. A mostly monochrome UI keeps the transit line colours meaningful.

[Explore Stopover ↗](https://stopover-site.vercel.app/) · Mobile app in development

<details>
<summary><b>Watch a trip come together · 22-second demo</b></summary>
<br />
<p align="center"><img src="assets/stopover-demo.gif" width="280" alt="Recorded Stopover demo: search for a place, add a stop, and build a transit trip" /></p>
<p align="center">Actual app recording from the Stopover site.</p>
</details>

### 02 / Riyazat
**Practice, daily.**

<a href="https://riyazat-omega.vercel.app/"><img src="assets/riyazat.jpg" width="100%" alt="Riyazat's indigo and gold study companion interface, with the headline Practice, daily" /></a>

A study companion for TMU Computer Science that brings the degree roadmap, daily practice, and GPA planning into one place.

**Behind the interface:** prerequisite and elective rules, FSRS spaced repetition, browser-based Python practice, and GPA calculations that account for repeated courses. Designed around a daily study routine, with a distinct indigo-and-gold visual identity.

[Explore Riyazat ↗](https://riyazat-omega.vercel.app/) · TMU sign-in required for the app

## Small tools, real problems

Open-source desktop apps with focused interfaces and local processing.

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/JasimSiddiqui/port-process-pal"><img src="assets/ports.png" width="100%" alt="Port Process Pal showing listening ports, their processes, and row actions" /></a>
<h3>Port Process Pal</h3>
<p><b>Find what is holding your port.</b> Inspect listening ports and reclaim them without hunting through terminal output.</p>
<p>Live table reconciliation, OS-specific process discovery, and protected processes excluded from bulk termination.</p>
<p><code>Rust</code> <code>Tauri</code> <code>JavaScript</code></p>
<p><a href="https://github.com/JasimSiddiqui/port-process-pal">Code ↗</a> · <a href="https://portpal.vercel.app/">Download ↗</a></p>
</td>
<td width="50%" valign="top">
<a href="https://github.com/JasimSiddiqui/tape-to-transcript-tool"><img src="assets/transcript.png" width="100%" alt="Tape to Transcript Tool with a lecture transcript and saved recordings" /></a>
<h3>Tape to Transcript Tool</h3>
<p><b>Search the lecture instead of rewatching it.</b> Turn recordings into searchable transcripts on your own computer.</p>
<p>Background Whisper inference, timestamped SQLite storage, and GPU-to-CPU fallback. Works offline after the model download.</p>
<p><code>Python</code> <code>PySide6</code> <code>Whisper</code></p>
<p><a href="https://github.com/JasimSiddiqui/tape-to-transcript-tool">Code ↗</a> · <a href="https://tapetotranscript.vercel.app/">Download ↗</a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/JasimSiddiqui/clip-compression-companion"><img src="assets/compression.png" width="100%" alt="Clip Compression Companion showing a media queue and target-size controls" /></a>
<h3>Clip Compression Companion</h3>
<p><b>Make the file fit.</b> Pick an upload limit and compress video, audio, or images locally.</p>
<p>Bitrate budgeting, adaptive resolution, two-pass encoding, and hardware encoder detection with CPU fallback.</p>
<p><code>Rust</code> <code>Tauri</code> <code>FFmpeg</code></p>
<p><a href="https://github.com/JasimSiddiqui/clip-compression-companion">Code ↗</a> · <a href="https://clipcompression.vercel.app/">Download ↗</a></p>
</td>
<td width="50%" valign="top">
<a href="https://github.com/JasimSiddiqui/dynamic-downloading-dashboard"><img src="assets/downloads.png" width="100%" alt="Dynamic Downloading Dashboard with download progress, speeds, and queue controls" /></a>
<h3>Dynamic Downloading Dashboard</h3>
<p><b>Keep every connection working.</b> A Windows download manager with parallel transfers and resumable downloads.</p>
<p>Adaptive connection counts, work splitting between connections, server backoff, and disk-aware resume checkpoints.</p>
<p><code>Rust</code> <code>Tokio</code> <code>Tauri</code></p>
<p><a href="https://github.com/JasimSiddiqui/dynamic-downloading-dashboard">Code ↗</a> · <a href="https://ddd-site.vercel.app/">Download ↗</a></p>
</td>
</tr>
</table>

### Also pinned: Clinica

[Clinica — Frontend](https://github.com/Adityasharma0101911/Clinica-Frontend) is a team hackathon project built around the doctor-visit journey: prepare, listen, understand. Explore the shared repository for the Next.js / TypeScript interface and architecture.

## What connects the work

**Clear interfaces.** Make the next action obvious, whether that is adding a stop or choosing a file-size limit.

**Useful engineering.** Handle the less visible parts: timing constraints, queue state, cancellation, fallback, and recovery.

**Local where it matters.** Keep recordings and media processing on the user's machine in the desktop tools.

---

<p><a href="mailto:jasims.0002@gmail.com">Let's talk about something worth building.</a></p>
<img src="https://komarev.com/ghpvc/?username=JasimSiddiqui&label=Profile+views&color=7560b5&style=flat-square" alt="Profile view counter" />
