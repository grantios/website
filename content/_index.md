---
title: "Home"
---

# Granti<span>OS</span>

<p class="tagline"><strong>Grant's Personal <i class="fas fa-user"></i> Operating System</strong></p>


On all daily-driver machines via ArchLinux (For My: Desktop, Server, Smart-Clock, Media-Center PCs.)


## Quick Start

<div class="quick-links">
  <a href="#install">Install</a>
  <a href="#rebase">Rebase</a>
  <a href="#readme">Readme</a>
  <a href="#faq">FAQs</a>
  <a href="#gallery">Gallery</a>
</div>

## Install

We plan to have a dedicated ISO image at some point, <br>but for now GrantiOS is based on ArchLinux with a default btrfs partition.

<div class="download-section">
  <a href="https://archlinux.org/" target="_blank" class="download-btn">Learn About</a>
  <a href="https://geo.mirror.pkgbuild.com/iso/latest/archlinux-x86_64.iso" class="download-btn primary">Get ArchIso</a>
  <a href="https://github.com/grantios/grantios/releases" target="_blank" class="download-btn">Get TestIso</a>
</div>

<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="write iso command">
    <code>sudo dd if=archlinux-x86_64.iso of=/dev/sdx status=progress conv=fsync bs=1M</code>
  </div>
</div>

Boot into the live image, then run:

<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="initial setup commands">
    <code>sudo pacman-key --refresh-keys && sudo pacman -Sy archlinux-keyring && sudo pacman -S git</code>
  </div>
</div>

## Rebase

<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="clone command">
    <code>git clone https://github.com/grantios/instagrant && cd instagrant</code>
  </div>
</div>

To rebase to GrantiOS, choose the variant for your use case:

**Desktop (Via KDE):**
<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="desktop installation command">
    <code>./insta/run.sh</code>
  </div>
</div>

**Server (Headless):**
<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="server installation command">
    <code>./insta/run.sh --config homeserver.sh</code>
  </div>
</div>

<details class="specialized-variants">
<summary><strong>Specialized Variants</strong></summary>

**Smart Clock (Godot App):**
<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="clock installation command">
    <code>./insta/run.sh --config smartclock.sh</code>
  </div>
</div>

**Media Center (Kodi HTPC):**
<div class="command-banner-wrapper" aria-hidden="false">
  <div class="command-banner-box" role="status" aria-label="media installation command">
    <code>./insta/run.sh --config mediacenter.sh</code>
  </div>
</div>

</details>

\* `Then reboot to stage the changes.`

## Readme

<details class="centered-summary">

<summary>⏺⏺⏺</summary>

## Overview

Built on ArchLinux with a default btrfs partition, GrantiOS provides stable experiences with carefully selected customizations across multiple specialized variants.

> **Note:** These are personal images. While you're welcome to try them, they're not officially supported for third-party use.

<div class="section-divider"></div>

## About GrantiOS

GrantiOS is [Grant](https://github.com/grantsform)'s personal Bootc images with desktop and server variants.

## Origins

This project started as a way to create a personalized Linux experience based on ArchLinux with a default btrfs partition. It leverages the stability and reliability of ArchLinux while providing customized configurations for different use cases.

## Intentions
This is a stop-gap, personal solution that I'm going to use as a stable base on-top of ArchLinux for all my machines until I get a enough good understanding of the bootc ecosystem to reasonably get dug in maintaining [GateLinux](https://github.com/gatelinux) and my Spatial-Computing Distro built around Godot, [UF-OS](https://github.com/uf-os). 

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