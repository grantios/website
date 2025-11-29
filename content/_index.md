---
title: "Home"
---

# Granti<span>OS</span>

<p class="tagline"><strong>Grant's Personal <i class="fas fa-user"></i> Operating System</strong></p>


On all daily-driver machines via Debian 13 (For My: Desktop, Server, Smart-Clock, Media-Center PCs.)


## Quick Start

<div class="quick-links">
  <a href="#install">Install</a>
  <a href="#rebase">Rebase</a>
  <a href="#readme">Readme</a>
  <a href="#faq">FAQs</a>
  <a href="#gallery">Gallery</a>
</div>

## Install

We plan to have a dedicated ISO image at some point, but for now GrantiOS is based on Debian 13.

<div class="download-section">
  <a href="https://www.debian.org/releases/trixie/" target="_blank" class="download-btn">Learn About</a>
  <a href="https://cdimage.debian.org/debian-cd/current-live/amd64/iso-hybrid/debian-live-13.2.0-amd64-kde.iso" class="download-btn primary">Get Debian</a>
</div>

## Rebase

<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="clone command">
    <code>git clone https://github.com/grantios/grantios && cd grantios</code>
  </div>
</div>

To rebase to GrantiOS, choose the variant for your use case:

**Desktop (Via KDE):**
<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="desktop installation command">
    <code>just setup-desktop</code>
  </div>
</div>

**Server (Headless):**
<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="server installation command">
    <code>just setup-server</code>
  </div>
</div>

<details class="specialized-variants">
<summary><strong>Specialized Variants</strong></summary>

**Smart Clock (Godot App):**
<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="clock installation command">
    <code>just setup-clock</code>
  </div>
</div>

**Media Center (Kodi HTPC):**
<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="media installation command">
    <code>just setup-media</code>
  </div>
</div>

</details>

\* `Then reboot to stage the changes.`

## Readme

<details class="centered-summary">

<summary>⏺⏺⏺</summary>

## Overview

Built on Debian 13, GrantiOS provides stable experiences with carefully selected customizations across multiple specialized variants.

> **Note:** These are personal images. While you're welcome to try them, they're not officially supported for third-party use.

<div class="section-divider"></div>

## About GrantiOS

GrantiOS is [Grant](https://github.com/grantsform)'s personal Bootc images with desktop and server variants.

## Origins

This project started as a way to create a personalized Linux experience based on Debian 13. It leverages the stability and reliability of Debian while providing customized configurations for different use cases.

## Intentions
This is a stop-gap, personal solution that I'm going to use as a stable base on-top of Debian for all my machines until I get a enough good understanding of the bootc ecosystem to reasonably get dug in maintaining [GateLinux](https://github.com/gatelinux) and my Spatial-Computing Distro built around Godot, [UF-OS](https://github.com/uf-os). 

## Philosophy

...

</details>


## FAQs {#faq}

Below are some commonly asked questions about GrantiOS. Click a question to expand the answer.

<div class="faq-list">

<details class="faq-item">
<summary><span class="faq-label faq-label--q">Q:</span> What GrantiOS intended for?</summary>

<p><span class="faq-label faq-label--a">A:</span><span class="faq-answer-text">At this point, personal use.</span></p>
</details>

<details class="faq-item">
<summary><span class="faq-label faq-label--q">Q:</span> Should I actually use this?</summary>

<p><span class="faq-label faq-label--a">A:</span><span class="faq-answer-text">Probably not.</span></p>
</details>

<details class="faq-item">
<summary><span class="faq-label faq-label--q">Q:</span> If anything goes wrong?</summary>

<p><span class="faq-label faq-label--a">A:</span><span class="faq-answer-text">That's your problem. I assume no liability or warranty.</span></p>
</details>

</div>

</br>
</br>

*For the latest updates, follow [@grantsform](https://github.com/grantsform) on GitHub.*