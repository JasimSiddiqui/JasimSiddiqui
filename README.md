<img src="assets/header.svg" width="100%" alt="Jasim Siddiqui — useful software, thoughtful interfaces. Built in Toronto." />

I build apps that make everyday friction disappear, with a **strong sense of user experience and visual aesthetics**. I care about how a product looks, how naturally it works, and the engineering behind it.

I've **won hackathons** and know how to **solve problems under pressure**: break down an unfamiliar challenge, prioritize what matters, and turn an idea into a working product on a tight deadline.

[Email me](mailto:jasims.0002@gmail.com) · [Explore my repositories](https://github.com/JasimSiddiqui?tab=repositories) · He/Him

## Selected work

### 01 / Stopover
**Every errand. One trip.**

<table>
<tr>
<td width="38%" align="center" valign="top">
<a href="https://stopover-site.vercel.app/"><img src="assets/stopover-demo.gif" width="280" alt="Stopover app demo: searching for a place, adding a stop, and building a transit trip" /></a>
</td>
<td width="62%" valign="top">
<h3>A whole errand run, planned together.</h3>
<p>Transit apps usually plan one leg at a time. Stopover accounts for time at each stop, departure times, and transfer windows across the whole trip.</p>
<p><b>Behind the interface</b></p>
<p>Timetable-based routing with OpenTripPlanner, stop-order optimization, and fare continuity across a multi-stop trip.</p>
<p><b>Designed for clarity</b></p>
<p>A mostly monochrome UI keeps transit line colours meaningful, with the next step and the route ahead easy to find.</p>
<p><a href="https://stopover-site.vercel.app/">Explore Stopover ↗</a><br />Mobile app in development</p>
<p><sub>22-second app recording from the Stopover site.</sub></p>
</td>
</tr>
</table>

### 02 / Riyazat
**Practice, daily.**

<a href="https://riyazat-omega.vercel.app/"><img src="assets/riyazat-home.png" width="100%" alt="Inside Riyazat: a daily study dashboard with a gold arch, quest ring, due flashcards, and geometric course tiles" /></a>

A study companion for TMU Computer Science that brings the degree roadmap, daily practice, and GPA planning into one place.

**Behind the interface:** prerequisite and elective rules, FSRS spaced repetition, browser-based Python practice, and GPA calculations that account for repeated courses. Designed around a daily study routine, with an indigo-and-gold identity drawn from Pakistani and Islamic geometric traditions: ogee arches, manuscript rules, and generative course medallions.

<table>
<tr>
<td width="50%" valign="top">
<img src="assets/riyazat-lesson.gif" width="100%" alt="Riyazat lesson demo: answering a check question, receiving feedback, and unlocking the next step" />
<p><b>Practice with feedback.</b> Inline questions make learners commit to an answer before moving on.</p>
</td>
<td width="50%" valign="top">
<img src="assets/riyazat-planner.gif" width="100%" alt="Riyazat planner demo: dragging a time range to create a study block with the time prefilled" />
<p><b>Plan with a gesture.</b> Drag across the calendar to create a study block in the selected time slot.</p>
</td>
</tr>
</table>

<details>
<summary><b>Explore the degree roadmap</b></summary>
<br />
<img src="assets/riyazat-roadmap.png" width="100%" alt="Riyazat degree roadmap with year waypoints, semester panels, completed courses, and elective progress" />
</details>

[Explore Riyazat ↗](https://riyazat-omega.vercel.app/) · TMU sign-in required for the app

<sub>App screenshots and interaction recordings from my Riyazat portfolio; view them here without a TMU account.</sub>

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

**UX and visual craft.** Pair a distinct visual identity with clear hierarchy, useful feedback, and an obvious next action.

**Useful engineering.** Handle the less visible parts: timing constraints, queue state, cancellation, fallback, and recovery.

**Problem-solving in a crunch.** Bring the same focus that has helped me win hackathons: identify the core problem, make deliberate tradeoffs, and get the important flow working under a deadline.

**Local where it matters.** Keep recordings and media processing on the user's machine in the desktop tools.

---

<p><a href="mailto:jasims.0002@gmail.com">Let's talk about something worth building.</a></p>
<img src="https://komarev.com/ghpvc/?username=JasimSiddiqui&label=Profile+views&color=7560b5&style=flat-square" alt="Profile view counter" />
