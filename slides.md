---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cdn.jsdelivr.net/gh/slidevjs/slidev-covers@main/static/w68kZc0L69w.webp
# some information about your slides (markdown enabled)
title: TCoeus 導覽
info: TCoeus 行銷自動化系統導覽
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
fonts:
  sans: Robot
  serif: Robot Slab
  mono: Fira Code
mdc: true
---
<div class="flex flex-col justify-center items-center w-full relative">
  <img class="w-[180px] mb-4" src="/images/logo.png"/>
  <h1>智慧代理</h1>
</div>
---
src: pages/introduction.md
---

---
transition: fade-out
src: pages/login.md
---

---
transition: fade-out
src: pages/home.md
---

---
transition: fade-out
src: pages/model-setting.md
---

---
transition: fade-out
src: pages/agent-setting.md
---

---
transition: fade-out
src: pages/chat.md
---

---
transition: fade-out
src: pages/manage.md
---

---
transition: fade-out
src: pages/setting.md
---

---
transition: fade-out
src: pages/about.md
---

---
layout: center
class: text-center
---

<div>
  <div class="w-full h-full absolute bg-[#000000e8] top-0 left-0">
    <div class="flex flex-col items-center justify-center h-full text-center">
      <img class="w-[180px] mb-4" src="/images/logo.png"/>
      <h1 style="color: white">讓 AI 協助您解決營運問題</h1>
    </div>
  </div>
</div>

<style>
@import "./styles.css";
</style>
