---
permalink: /demos/
title: "Robot Demos"
author_profile: true
---

<!--
  Each project is one .project block. Videos live in /files/videos/.
  Every <video> needs: autoplay muted loop playsinline (required for autoplay on phones),
  preload="metadata", a poster image, and an aria-label describing what happens.
  Use .project__media-wide for a full-width video and .project__media-pair for two side by side.
-->

<div class="project">

  <div class="project__header">
    <h2 class="project__title">Learning Dexterous Bimanual Skills from Human Demonstrations</h2>
    <p class="project__summary">A human demonstration shows what to do with an object, but not how a robot hand should do it. Robot hands differ from human hands in size, joints and dynamics, so replaying human motion directly breaks contact and drops the object. The question is how to turn human hand–object motion into skills a robot can actually execute, on more than one kind of robot hand.</p>
  </div>

  <ol class="pipeline">
    <li class="pipeline__step"><span class="pipeline__num">1</span><strong>Human demonstration</strong><span>what to do</span></li>
    <li class="pipeline__step"><span class="pipeline__num">2</span><strong>Retargeting</strong><span>human hand → robot hand</span></li>
    <li class="pipeline__step"><span class="pipeline__num">3</span><strong>RL in simulation</strong><span>how to do it robustly</span></li>
  </ol>

  <div class="hardware">
    <span class="hardware__label">Hardware</span>
    <span class="tag tag--current">Sharpa hands</span>
    <span class="tag tag--current">Wuji hands</span>
    <span class="tag">Vega humanoid arms</span>
  </div>

  <figure class="project__media-wide">
    <video autoplay muted loop playsinline preload="metadata"
           poster="/files/videos/handover_human_vs_sharpa_poster.jpg"
           src="/files/videos/handover_human_vs_sharpa.mp4"
           aria-label="Left: a person lifts a wooden box, hands it from one hand to the other and puts it back. Right: a simulated robot with two Sharpa hands does the same."></video>
    <figcaption>Human demo (left) and an RL expert with Sharpa hands in simulation (right): lift, hand over, place.</figcaption>
  </figure>

  <div class="project__media-pair">
    <figure>
      <video autoplay muted loop playsinline preload="metadata"
             poster="/files/videos/wuji_lid_one_hand_poster.jpg"
             src="/files/videos/wuji_lid_one_hand.mp4"
             aria-label="A simulated robot opens and closes a box lid with one Wuji hand."></video>
      <figcaption>One Wuji hand opens and closes the lid, in simulation.</figcaption>
    </figure>
    <figure>
      <video autoplay muted loop playsinline preload="metadata"
             poster="/files/videos/wuji_lid_two_hands_poster.jpg"
             src="/files/videos/wuji_lid_two_hands.mp4"
             aria-label="A simulated robot opens and closes a box lid with two Wuji hands."></video>
      <figcaption>Two Wuji hands open and close the lid, in simulation.</figcaption>
    </figure>
  </div>

</div>
