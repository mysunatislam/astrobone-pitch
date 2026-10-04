# 240-Second Presentation and Voiceover

Open `pitch.html`: on Windows, double-click `present.cmd` in the project folder (it serves the build at `http://127.0.0.1:4173/pitch.html` and opens your browser; keep its window open). Hosted: `https://mysunatislam.github.io/astrobone-pitch/pitch.html`. Opening `pitch.html` straight from the file explorer does not work, because browsers block its scripts, models and video on `file://`. It plays like a 4-minute video with real app demos inside it. Record the window with any screen recorder and read the script below.

## Controls

| Key | Action |
| --- | --- |
| Space | Play / pause (the 3D twin and pose model load during scenes without video) |
| ← → | Back / forward 5 s |
| 1–4 | Jump to WHO, WHY, WHAT, HOW |
| H | Hide all controls for recording |
| N | Open the teleprompter in a second window (follows the timeline, shows this script) |
| F | Fullscreen |

## Recording Checklist

1. Open the presentation once while online (the hosted link, or double-click `present.cmd`) so the offline pack installs; the Offline scene shows the cached file count.
2. Turn on airplane mode and reload. The network badge then truthfully reads **OFFLINE · running from this device** and every demo still runs.
3. Press **F**, then **H**, then **N** and move the teleprompter to a second screen. Press **Space** and start recording.
4. Record at 1920×1080. The presentation runs 3:56; cut the start screen and anything after the close so the uploaded video stays **under 4:00** (the guide cuts over-length videos off).
5. Add English subtitles (required by the guide): import `docs/pitch-subtitles.srt` in the video editor and nudge any caption that runs ahead of or behind the voiceover. Regenerate it with `python scripts/export-pitch-subtitles.py` after script changes.
6. Upload to YouTube and paste the link into the Bangladesh Google Form before the deadline.

## Structure (240 Seconds of Glory)

| Time | Chapter | Scene | On screen |
| --- | --- | --- | --- |
| 0:00 | WHO | Cold open | AI-generated bone-loss footage, "22 minutes", "who notices first?" |
| 0:14 | WHO | Challenge | Team's screen recording of the official 2026 challenge page (spaceappschallenge.org): description, then title and subject tags |
| 0:17 | WHO | Team | Photos aligned on one eye line, names, roles (Redwan: lead data analyst) |
| 0:34 | WHO | What we built | Lines of code, tests, NASA life-science records, 3D structures, documents, Monte Carlo runs, module chips |
| 0:46 | WHY | Problem | Challenge quote, five hazards, four health outcomes |
| 0:57 | WHY | Live simulation | Live twin: body, skeleton with Day 1 → 147, muscles, heart and vessels, all systems |
| 1:15 | WHY | NASA life sciences data | OSD-804 / LSDS-130, OSD-656 / LSDS-64, OSD-569 / LSDS-7, OSD-575 / LSDS-8, OSD-435 / LSDS-22 with real values, then the offline evidence pack |
| 1:45 | WHAT | Big idea | How the data protects her: bone & muscle, heart, mind & sleep, immune, each with what she gathers, what it is compared with and its NASA evidence; then the safe next steps. The concept animation plays once behind it and ends on its title |
| 2:03 | WHAT | Live demo 1 | Squat video once at 0.5×, live MediaPipe tracking, musculoskeletal twin squatting with feet planted, knee angle, reps, quality, inference; bones revealed with the NASA LSDS-130 femur callout; session result: knee range of motion, left-right gap, full extension and what each is for |
| 2:23 | WHAT | Live demo 2 | Live twin self-check: refusal, repeat, evaluation, action |
| 2:43 | WHAT | Live demo 3 | Live Impact Lab: reconstruction, stress map, 10,000-run Monte Carlo |
| 3:00 | HOW | Offline | Live network badge, cached files, SHA-256 of the five NASA life-science sources |
| 3:15 | HOW | Impact | Astronauts, her medical & exercise team, Earth |
| 3:33 | HOW | Needs | Validation, analog pilot, restricted crew records, sensors; open science we build on |
| 3:48 | HOW | Close | Predict · Observe · Update · Protect |

## Script

**0:00 Cold open.** Day one hundred forty-seven of a Mars transit. A message to Earth takes up to twenty-two minutes, one way. So when an astronaut's body starts to change, who notices first?

**0:14 Challenge.** Our challenge: health monitoring software for astronauts on space missions.

**0:17 Team.** We are Team AstroBone from Bangladesh. I'm Mysunat Islam, biomedical engineer and team lead. Redwan Ahamed Tamim is our lead data analyst, and Mashyiat Islam Borno designs everything you're about to see.

**0:34 What we built.** We've written about twenty-nine thousand lines of code, two hundred fifty-seven tests and forty-one documents, and turned fourteen hundred NASA life-science records into one working system.

**0:46 Problem.** NASA names five hazards of spaceflight: radiation, isolation, distance, altered gravity and a hostile closed environment. They hit four systems: immune, bone, cardiovascular and behavioral health.

**0:57 Live simulation.** Meet Commander Elena Torres, a fictional astronaut on day one forty-seven, with no flight surgeon on board. This is her digital twin: her skeleton changing across the mission, the muscles that protect it, and a heart beating at her recorded rate.

**1:15 NASA life sciences data.** And the twin's main characters are NASA's own life-science data, from the Ames Life Sciences Data Archive. Study 804: after just thirty-seven days in space, mice lost fifty-five percent of trabecular bone volume in the femur. Inspiration4 crew data show immune and blood markers shifting after flight. Two more studies cover the heart and radiation. AstroBone carries fourteen hundred of these records on board, each verified by its SHA-256 fingerprint.

**1:45 Big idea.** Here's how the data protects her. Every day, four kinds of signals. AstroBone compares each one with her own baseline, and NASA's life-science data tells it what to watch for. When something drifts, she gets a safe next step, and her medical and exercise team sees exactly what changed.

**2:03 Live demo 1.** Here's the engine, in slow motion. MediaPipe tracks the body on this device, and the musculoskeletal twin copies the squat with its feet planted. From one squat AstroBone measures knee range of motion, the left-right gap and full extension: the same signals the daily check compares with the astronaut's own baseline.

**2:23 Live demo 2.** Now Elena's daily self-check in her digital twin. Her first capture is badly framed, so AstroBone refuses to compare it. She repeats it. With her reaction test, sleep and mood, three domains move outside her personal range, and the twin shows exactly where.

**2:43 Live demo 3.** If something unexpected happens, like a loose tool striking her shin, AstroBone reconstructs the impact with physics, maps bending stress along the tibia, and runs ten thousand Monte Carlo simulations in seconds.

**3:00 Offline.** And it all works with no connection. The pose AI, the NASA life-science evidence pack and the 3D models are cached on the device. No health data ever leaves it.

**3:15 Impact.** That changes who notices first. She sees a change at the next daily check, not the next ground contact. Her medical and exercise team sees whether her countermeasures are working. And on Earth, the same tool can serve rural clinics in Bangladesh and anyone far from a specialist.

**3:33 Needs.** What we need next: a validation study against a clinical goniometer, a pilot in an analog mission, access to restricted long-duration crew records in NASA's Life Sciences Data Archive to calibrate personal baselines, and wearable sensors.

**3:48 Close.** AstroBone. Predict. Observe. Update. Protect. Because on the way to Mars, the first responder is the astronaut.

## What Is Real On Screen

- NASA values come from `public/data/*.json`: summaries of five NASA Ames Life Sciences Data Archive (ALSDA) datasets served by OSDR (LSDS-130, LSDS-64, LSDS-7, LSDS-8, LSDS-22), each with the SHA-256 of its source file.
- Project statistics were counted from the repository on 4 October 2026. The presentation states no development time span.
- Live simulation: the twin page running inside the presentation. Elena and her values are synthetic and labeled as such.
- Demo 1 runs MediaPipe pose tracking live on the squat clip (shown once at 0.5× speed); every card, the chart and the session result are measured from the frames. The musculoskeletal twin (`models/anatomy/musculoskeletal-rigged.glb`) plays a clean squat locked to the clip's playback position: its depth comes from this video's landmarks (the recorded pass of the same model; because the clip is filmed from behind, knee flexion is rebuilt from each thigh and shin's foreshortening against its standing length, smoothed and limited to parallel), with feet planted, an authored trunk lean and a barbell back-squat upper body. Until the live model is ready, the recorded pass (`public/pitch/squat-pose.json`, made by `node scripts/record-pitch-pose.mjs`) also feeds the cards, and the inference card says "Recorded pass" while it does.
- Demos 2 and 3 are the live twin page. Elena and her values are synthetic and labeled as such.
- The cold open and the concept animation are AI-generated videos and are labeled on screen; the concept animation's corner logo sits under its "AI-generated" tag.
- AstroBone does not prescribe exercise or treatment. It flags quality-checked changes against the astronaut's own baseline for her medical and exercise team.
- The network badge reads the browser's real connection state.

## Media Credits

- Squat clip: Pexels video 4921644 (Pexels License).
- Cold-open and concept videos: generated by the team with Google Gemini.
- Team photos: supplied by the team members.
