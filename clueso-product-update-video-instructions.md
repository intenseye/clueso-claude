# Clueso product update videos: instructions for Claude

Use these when someone asks you to turn a product update (usually a #product-updates post) into a Clueso video.

> **How to use this file:** paste it into the channel's Claude instructions (Claude configuration page for the channel), or drop it in a thread and ask Claude to save it. Intenseye-specific defaults are marked so another team can swap them.

## Prerequisites

- **Clueso access:** anyone can request a video; the requester doesn't need their own Clueso connection. Claude uses the requester's Clueso connection if they have one, otherwise the channel's Clueso connector. Only if neither exists, Claude says so in the thread and asks someone with Clueso connected to re-send the request.
- **Network:** the environment allows `connect.us.clueso.io` with **PUT** (GET-only blocks uploads). With it, Claude pushes screenshots from Slack into Clueso itself.
- **Source files:** Claude must be able to open them. Invite Claude to the source channel (`/invite @Claude`) or drop the files into the request thread. Otherwise, video files (mp4) go through a Clueso upload link Claude posts; the requester drops the files there and replies "uploaded".

## Inputs

- Link to the release post (or its text).
- Screenshots and/or screen recordings of the feature.
- Optional: voice, length, or a different clueprint.

## Defaults

- **Clueprint:** "Product Update" (title card, screen recordings or screenshots with zooms and spotlights, video outro). Use another clueprint only if the requester names it. If several clueprints match the name, list them and say which you'd use. *(Intenseye workspace)*
- **Structure:**
  1. Title card: feature name as heading, product area as the tab, PRODUCT UPDATE label.
  2. Why it matters: the problem from the post, in one line.
  3. One walkthrough section per recording or screenshot, in the post's order.
  4. Outro: availability plus the post's call to action (use its "Say it" line).
- **Script:** opens with "Hello and welcome to the Intenseye Product Update! Today we're introducing …" *(Intenseye)*. After watching the media, rewrite lines so they describe what each recording actually shows.
- **Look and sound:** Jeff voice, branded captions on every clip, background music under the walkthrough, dissolve into the outro.
- **Zooms and spotlights:** always add them, timed to the voiceover, on the key click and the key result in each clip. Remove Clueso's auto-placed highlights if they drift after voiceover retiming.
- **Sales enablement brief:** post it in the thread and as a Clueso project comment. Never put it in the video. Contents:
  - 3 discovery questions
  - 3 common objections, each with a one-line response
  - Target industries
  - Ideal customer profile
  - Opening line and closing line

## Workflow

1. Read the post and every screenshot or recording attached to it.
2. If you need an upload link for video files, post it and wait for "uploaded". Otherwise go straight to building; don't wait for approval.
3. Build the project in Clueso: clueprint, media, voiceover, captions, music, outro.
4. Add zooms and spotlights.
5. Check frames: one per clip, and one inside every zoom or spotlight.
6. **Publish as a player** to get the watchclueso.com link. This is a separate step from export, so never skip it.
7. Export the MP4 too when asked.
8. Post the result and the sales enablement brief (format below).

## Deliverable

Reply in the thread with:

- **Watch link:** `https://watchclueso.com/embed/...` Permanent, plays without a Clueso login, and shows the new version after any republish. This is the main deliverable.
- **MP4** (if exported): the download link expires after about an hour, so say so; the file also stays in the editor's Exports tab.
- **Sales enablement brief** (also added as a Clueso project comment).
- Length, what's in each section, which effects you added, and what you checked versus did not check (for example, "not watched end to end").

## Don'ts

- Don't hand over only an MP4 download link; always publish and share the watchclueso link.
- Don't put sales enablement content in the video.
- Don't skip zooms and spotlights or wait to be asked for them.
- Don't include the Clueso editor (web.clueso.io) link in the reply.
