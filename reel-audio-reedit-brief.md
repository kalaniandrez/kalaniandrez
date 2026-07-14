# Brief: Re-edit motivational audio for IG reel (@kalaniandrez)

Handoff doc for a Ceiba session that has audio/video tooling + network access.
This session (the one that wrote this) is a locked-down coding sandbox: no
YouTube access, no `ffmpeg`/`yt-dlp`, no audio playback — so it could only spec
the work, not do it.

## Goal

Take an existing motivational audio montage and **re-cut it** — same source
audio, new running order. Specifically: move the speeches currently at the
**end** (which are different motivational speakers) to the **front**, then
re-sequence the whole thing into a stronger arc. Output a clean re-edited audio
track ready to drop under B-roll in CapCut.

## Source

- Audio is from: https://youtu.be/EMaULPCtdig
- Not the YouTube uploader's original work either; the original creator's
  account is inactive / hasn't posted in years and it's no longer on Spotify.
- Action: add a credit line to the original creator in the IG caption (best
  effort, since permission can't be obtained). See packaging section.

## Constraints / heads-up

- **IG Content ID risk:** uploaded reused audio can get muted or region-blocked.
  First check Instagram's native audio library for this exact clip and use the
  in-app sound if it exists. If not, upload the custom track and accept a small
  flag risk.
- Keep the final cut tight — reel pacing, not a podcast.

## The re-sequence strategy

Core principle: a reel is won or lost in the first 2–3 seconds.

- **Open** with the single most distinct / hardest-hitting line — pattern
  interrupt. A montage of *different* speakers up top signals "curated mix,
  stay."
- Don't blow the climax in the first 5s. Shape to aim for:
  **hook (best line) → build/tension → quieter reflective breather → climax → short exhale/outro.**
- Kalani's hypothesis (ending speakers → front) is right **only if** those
  ending lines are the most intense. If they're slow/reflective, place them as
  the mid breather instead, not the opener.

## Tasks for the executing session

1. **Transcribe** the full audio with timestamps. Label each segment by speaker
   (voice 1 / voice 2 / name if identifiable) and mark the standout line of each.
2. **Score** each segment: intensity (hook potential) vs. reflective (breather
   potential), and length.
3. **Propose a reorder** that fits the arc above. Produce a **cut list**:
   `segment → in/out timestamps → new position`, so it can be rebuilt in CapCut.
4. **Render** the re-sequenced audio (and/or hand back the precise cut list if
   Kalani wants to assemble it himself).
5. Flag any segment where the reorder needs a human ear to decide (e.g., two
   candidates for the opener).

## Deliverables

- Full transcript w/ timestamps + speaker labels.
- Recommended new order with rationale (one line per segment).
- Cut list with in/out points for CapCut.
- Re-edited audio file (if tooling allows).

## IG packaging (Spanish — Kalani's audience)

- **Hook overlay (first on-screen line):** the opening speech's strongest phrase.
- **Caption:** short, in Spanish, motivational; end with a soft CTA to
  `kalani.place`.
- **Credit:** a line crediting the original creator (audio re-edited, not mine).
- **Hashtags:** tuned set for motivación / IA en español / mentalidad-emprendedor.
- **Visual pairing:** B-roll of Kalani building (Behike, vibe coding en español),
  text synced to the punchy lines, burned-in captions.

## Open question for Kalani

Which segment is the hardest-hitting? That decides the opener. If unsure, the
executing session should transcribe first and present 2–3 candidate openers.
