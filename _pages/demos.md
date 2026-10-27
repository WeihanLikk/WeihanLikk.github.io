---
permalink: /demos/
title: "Robot Demos"
author_profile: true
---

<!--
  Each task is one .demo-row: a heading, then a human demo and the robot policy trained from it.
  Videos live in /files/videos/. Every <video> needs: autoplay muted loop playsinline
  (required for autoplay on phones), preload="metadata", a poster image, and an aria-label.
  Set --ar (width / height) on each figure so both videos in a row get the same height.
  If one video already shows human and robot side by side, put it in a single figure
  and give its figcaption two spans.
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

  <p class="demo-intro">Each task below pairs one human demonstration (left) with the robot policy learned from it (right). All robot videos are in simulation.</p>

  <section class="demo-row">
    <h3 class="demo-row__title">Lift, hand over and place a box <span>two Sharpa hands</span></h3>
    <div class="demo-row__media">
      <figure style="--ar: 2.008">
        <video autoplay muted loop playsinline preload="metadata"
               poster="/files/videos/handover_human_vs_sharpa_poster.jpg"
               src="/files/videos/handover_human_vs_sharpa.mp4"
               aria-label="Left: a person lifts a wooden box, hands it from one hand to the other and puts it back. Right: a simulated robot with two Sharpa hands does the same."></video>
        <figcaption><span>Human demo</span><span>Robot policy, in simulation</span></figcaption>
      </figure>
    </div>
    <p class="demo-row__credit">Human demo: ARCTIC (Fan et al., CVPR 2023).</p>
  </section>

  <section class="demo-row">
    <h3 class="demo-row__title">Open and close a box lid <span>one Wuji hand</span></h3>
    <div class="demo-row__media">
      <figure style="--ar: 0.856">
        <video autoplay muted loop playsinline preload="metadata"
               poster="/files/videos/human_box_open_demo_poster.jpg"
               src="/files/videos/human_box_open_demo.mp4"
               aria-label="A person opens the hinged lid of a wooden box on a stand and closes it again."></video>
        <figcaption><span>Human demo</span></figcaption>
      </figure>
      <figure style="--ar: 1">
        <video autoplay muted loop playsinline preload="metadata"
               poster="/files/videos/wuji_lid_one_hand_poster.jpg"
               src="/files/videos/wuji_lid_one_hand.mp4"
               aria-label="A simulated robot opens and closes a box lid with one Wuji hand."></video>
        <figcaption><span>Robot policy, in simulation</span></figcaption>
      </figure>
    </div>
    <p class="demo-row__credit">Human demo: ARCTIC (Fan et al., CVPR 2023).</p>
  </section>

  <section class="demo-row">
    <h3 class="demo-row__title">Unscrew a jar lid <span>two Wuji hands</span></h3>
    <div class="demo-row__media">
      <figure style="--ar: 1.767">
        <video autoplay muted loop playsinline preload="metadata"
               poster="/files/videos/human_unscrew_demo_poster.jpg"
               src="/files/videos/human_unscrew_demo.mp4"
               aria-label="First-person view: a person unscrews the lid of a large jar with both hands."></video>
        <figcaption><span>Human demo</span></figcaption>
      </figure>
      <figure style="--ar: 1.778">
        <video autoplay muted loop playsinline preload="metadata"
               poster="/files/videos/robot_unscrew_policy_poster.jpg"
               src="/files/videos/robot_unscrew_policy.mp4"
               aria-label="A simulated robot with two Wuji hands reaches a jar; the left hand holds the jar while the right hand turns the lid, then both hands let go and pull back."></video>
        <figcaption><span>Robot policy, in simulation (2× speed)</span></figcaption>
      </figure>
    </div>
    <p class="demo-row__credit">Human demo: OakInk2 (Zhan et al., CVPR 2024).</p>
  </section>

</div>
