---
layout: page
title: Anima Brain in action
description: Three short English demos of character speech, live audio calls, and animated video calls.
permalink: /anima-brain-demos/
nav: false
---

<div class="case-study demo-gallery" markdown="1">

<p class="case-study__lede">One brain. A voice, a conversation, a face.</p>

Three short clips from the Anima Brain Python SDK and local showcase. Press play to
hear each example. These are configured-provider demonstrations with fictional exchanges.

<div class="home-actions">
  <a class="button button--primary" href="https://github.com/spearsheep/anima-brain">Get the open-source framework <span aria-hidden="true">↗</span></a>
  <a class="button button--quiet" href="{{ '/projects/anima-lab/' | relative_url }}">About the project <span aria-hidden="true">→</span></a>
</div>

<section id="voice-message" class="demo-gallery__clip" aria-labelledby="voice-message-title">
  <p class="demo-gallery__eyebrow">01 / CHARACTER SPEECH · 6.5 SECONDS</p>
  <h2 id="voice-message-title">A voice that fits the character</h2>
  <p>A short speech sample generated through the Python SDK, using a configured English voice.</p>
  <video controls playsinline preload="none" width="3840" height="2160" poster="{{ '/assets/img/projects/anima-brain-voice-message.jpg' | relative_url }}" aria-label="Play the English character speech sample">
    <source src="https://github.com/spearsheep/anima-brain/releases/download/demo-media-2026-11/voice-message.mp4" type="video/mp4">
    <a href="https://github.com/spearsheep/anima-brain/releases/download/demo-media-2026-11/voice-message.mp4">Download the voice sample</a>
  </video>
  <details><summary>Transcript</summary><p>Rina: “So, are we being productive tonight, or just pretending?”</p></details>
  <a class="demo-gallery__download" href="https://github.com/spearsheep/anima-brain/releases/download/demo-media-2026-11/voice-message.mp4">Download MP4 ↗</a>
</section>

<section id="audio-call" class="demo-gallery__clip" aria-labelledby="audio-call-title">
  <p class="demo-gallery__eyebrow">02 / LIVE AUDIO CALL · 5.9 SECONDS</p>
  <h2 id="audio-call-title">Just call. Just talk.</h2>
  <p>Spoken input passes through recognition, the brain, and character speech. The audio is the actual call response; the interface was re-recorded around it.</p>
  <video controls playsinline preload="none" width="3840" height="2160" poster="{{ '/assets/img/projects/anima-brain-audio-call.jpg' | relative_url }}" aria-label="Play the English audio-call demo">
    <source src="https://github.com/spearsheep/anima-brain/releases/download/demo-media-2026-11/audio-call.mp4" type="video/mp4">
    <a href="https://github.com/spearsheep/anima-brain/releases/download/demo-media-2026-11/audio-call.mp4">Download the audio-call demo</a>
  </video>
  <details><summary>Exchange transcript</summary><p>User: “I was going to bed an hour ago. Somehow I'm still scrolling. Don't judge me.”</p><p>Rina: “I wouldn't dare judge. I'm just impressed by your commitment to procrastination.”</p></details>
  <a class="demo-gallery__download" href="https://github.com/spearsheep/anima-brain/releases/download/demo-media-2026-11/audio-call.mp4">Download MP4 ↗</a>
</section>

<section id="video-call" class="demo-gallery__clip" aria-labelledby="video-call-title">
  <p class="demo-gallery__eyebrow">03 / ANIMATED VIDEO CALL · 6.6 SECONDS</p>
  <h2 id="video-call-title">A face in the conversation</h2>
  <p>The S2 avatar and speech were captured together over RTC, then trimmed together to preserve synchronization.</p>
  <video controls playsinline preload="none" width="3840" height="2160" poster="{{ '/assets/img/projects/anima-brain-video-call.jpg' | relative_url }}" aria-label="Play the English animated video-call demo">
    <source src="https://github.com/spearsheep/anima-brain/releases/download/demo-media-2026-11/video-call.mp4" type="video/mp4">
    <a href="https://github.com/spearsheep/anima-brain/releases/download/demo-media-2026-11/video-call.mp4">Download the video-call demo</a>
  </video>
  <details><summary>Exchange transcript</summary><p>User: “Pizza, or should I pretend I'm actually going to cook?”</p><p>Rina: “Do you want the truth or a thinly veiled excuse to eat pizza? Because I can deliver both.”</p></details>
  <a class="demo-gallery__download" href="https://github.com/spearsheep/anima-brain/releases/download/demo-media-2026-11/video-call.mp4">Download MP4 ↗</a>
</section>

## Try it yourself

[Anima Brain on GitHub](https://github.com/spearsheep/anima-brain) includes the SDK,
provider configuration, and showcase setup. For the ready-to-use consumer app, visit
[Anima Lab](https://www.anima-lab.io/).

The clips are 4K presentations with English captions and no background music. The avatar
stream itself is 768 × 1364, preserved inside the composition. These short excerpts are
not latency benchmarks. See [recording provenance and media terms](https://github.com/spearsheep/anima-brain/blob/main/docs/demos.md).

</div>
