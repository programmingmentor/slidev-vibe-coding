---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Vibe Coding
info: |
  ## Виступ для SoftServe

# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
---

# 1000x Software Engineer

В'ячеслав Колдовський, SoftServe

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="m-6 flex gap-2 fixed bottom-0 right-0 flex-col items-end">
  <a href="https://www.youtube.com/c/programmingmentorua">
    <div class="h-8 w-8">
      <img src="/pm-logo.jpg" class="h-full w-full rounded-full"/>
    </div>
  </a>
  <a href="https://career.softserveinc.com/uk-ua/softserve-academy">
    <div class="h-12 w-24">
      <img src="/ssa-logo-white.svg" class="h-full w-full"/>
    </div>
  </a>
</div>

<style>
  a {
    text-decoration: none;
    border: 2.4px solid transparent;
  }
  a:hover {
    border-color: var(--slidev-theme-primary);
  }
</style>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Vibe Coding

<div class="flex justify-center">
  <Tweet class="w-1/2" id="1848558163756519607" />
</div>

---

# TODO: Success Vibe Coding

---

# TODO: Fail Vibe Coding

---

# Формула 1000x Developer

## 1000x Developer = Software Engineering Skills \* AI Codegen Skills

## Bad Developer: 0 \* 1000 == 0

## Also Bad Developer: 1000 \* 0 == 0

## Good Developer: 1000 \* 1 == 1 \* 1000

---

---

# TDD

---

Prompt:
create ...
write tests first, then the code, then update code until tests pass

# Repository Prompt Tools

---

# 16x Prompt

https://prompt.16x.engineer/

---

# Repomix

https://repomix.com/

---

# llms.txt

<iframe src="https://twitframe.com/show?url=https://x.com/DrizzleORM/status/1896981123559002158" width="500" height="600" frameborder="0" scrolling="no"></iframe>

https://orm.drizzle.team/llms.txt

---

layout: image
image: /chat-gpt-developer.png
backgroundSize: contain

---

---

layout: image
image: /ai-adoption-0-100-detailed.png
backgroundSize: contain

---

# То де ми зараз?

<style>
h1 {
  color: black;
}
.slidev-layout {
  background-color: white;
}
</style>

<v-click>
  <div
      v-motion
      :initial="{ y: 260, x: -450, opacity: 1 }"
      :enter="{ y: 0, x: 0, opacity: 1, transition: { delay: 0, duration: 30000 } }"
      class="absolute top-[110px] left-3/5 transform -translate-x-1/2">
    <div class="text-6xl text-red-500">↓</div>
  </div>
</v-click>

---

layout: image-left
image: /vyacheslav-koldovskyy.png

---

# В'ячеслав Колдовський

- Ph.D, доцент
- 20+ років в IT
- SoftServe Academy Competence Manager
- Certified Google Cloud Professional Architect
- Ентузіаст Практичного AI
- Ютубер: [youtube.com/@programmingmentorua](https://www.youtube.com/@programmingmentorua)
- Блогер: [t.me/programmingmentor](https://t.me/programmingmentor)
- Лінкедін: [koldovsky](https://www.linkedin.com/in/koldovsky/)

---

## layout: end

# Дякую за увагу!

<div class="flex justify-center w-full h-30 items-center">
  <img src="/slides-qr.png" class="w-25 h-25"/>
</div>
