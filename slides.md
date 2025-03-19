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

# Vibe Coding

В'ячеслав Колдовський, SoftServe Academy

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

# Vibe Coding

<div class="w-full flex justify-center">
  <img src="/vibe-coding-tweet.png" class="w-1/2"/>
</div>

---

# Pieter Levels

<div class="w-full flex justify-center">
  <img src="/levelsio.png" class="w-1/2"/>
</div>

---

<div class="w-full flex justify-center">
  <Tweet scale="0.65" id="1901660771505021314" class="w-3/4"/>
</div>

---

<div class="w-full flex justify-center">
  <img src="/personal-motivation-calendar.png" class="w-1/2"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://personalmotivationcalendar.com/">https://personalmotivationcalendar.com/</a>
</div>

---

# Fails - SaaS

<div class="w-full flex justify-center">
  <img src="/fail-saas.png" class="w-1/3"/>
</div>

---

# Fails - Fetch

<div class="w-full flex justify-center">
  <img src="/fail-fetch.png" class="w-1/3"/>
</div>

---

# Fails - rm -rf

<div class="w-full flex justify-center">
  <img src="/fail-clean-directory.png" class="w-4/5"/>
</div>

---

# Tools

- Cursor
- Windsurf
- Cline
- Github Copilot
- v0.dev
- bolt.new
- repl.it agent
- lovable
- ChatGPT
- Grok
- ...

---

# How it works?

<div class="w-full flex justify-center">
  <img src="/how-works-prompt-llm-code.png" class="w-4/5"/>
</div>

---

# LLM

<div class="w-full flex justify-center">
  <img src="/chatbot-arena-language.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://lmarena.ai/">https://lmarena.ai/</a>
</div>

---

# WebDev Arena

<div class="w-full flex justify-center">
  <img src="/web-dev-arena.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://web.lmarena.ai/">https://web.lmarena.ai/</a>
</div>

---

# How it works - more details

<div class="w-full flex justify-center">
  <img src="/how-works-prompt-expanded-llm-code.png" class="w-4/5"/>
</div>

---

# How it works - simple agent

<div class="w-full flex justify-center">
  <img src="/how-works-simple-agent.png" class="w-4/5"/>
</div>

---

# How it works - modern agent

<div class="w-full flex justify-center">
  <img src="/how-works-modern-agent.png" class="w-4/5"/>
</div>

---

# Main issue: context window limit and price

<div class="w-full flex justify-center">
  <img src="/context-window.png" class="w-4/5"/>
</div>

---

# LOC to LLM tokens

## React:

- **React jsx (100 lines):** 700 tokens
- **React jsx (200 lines):** 1,500 tokens

## SQL:

- **SQL script (100 lines):** 1,150 tokens
- **SQL script (200 lines):** 2,500 tokens

## Python:

- **Python source code file (100 lines):** 1,000 tokens
- **Python source code file (200 lines):** 1,700 tokens

Source https://prompt.16x.engineer/blog/chatgpt-context-window-token-limit

---

# Price

<div class="w-full flex justify-center">
  <img src="/openai-pricing.png" class="w-4/5"/>
</div>

https://openai.com/api/pricing/

---

# Security and Legal Issues with AI Code Generation Tools

- Run arbitrary commands on system
- Use integrations with external services without proper control
- Leak sensitive information and intellectual property
- Generate insecure (vulnerable) code
- Install unwanted dependencies
- Generate code with intellectual property violations

---

# Tools: general purpose

- ChatGPT
- Grok
- Gemini (gemini.google, aistudio.google.com)
- Claude
- DeepSeek

---

# ChatGPT

<div class="w-full flex justify-center">
  <img src="/chatgpt-canvas.png" class="w-4/5"/>
</div>

---

# Grok

<div class="w-full flex justify-center">
  <img src="/grok.png" class="w-1/2"/>
</div>

---

# Gemini

<div class="w-full flex justify-center">
  <img src="/gemini.png" class="w-4/5"/>
</div>

---

# Gemini AI Studio

<div class="w-full flex justify-center">
  <img src="/gemini-ai-studio.png" class="w-4/5"/>
</div>

---

# Repository Prompt Tools

- Repomix
- 16x Prompt
- Repo Prompt
- ...

---

# Repomix

<div class="w-full flex justify-center">
  <img src="/repomix.png" class="w-1/2"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://repomix.com/">https://repomix.com/</a>
</div>

---

# 16x Prompt

<div class="w-full flex justify-center">
  <img src="/16x-prompt.png" class="w-1/2"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://prompt.16x.engineer/">https://prompt.16x.engineer/</a>
</div>

---

# bolt.new

<div class="w-full flex justify-center">
  <img src="/bolt-new.png" class="w-1/2"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://bolt.new/">https://bolt.new/</a>
</div>

---

# v0.dev

<div class="w-full flex justify-center">
  <img src="/v0-dev.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://v0.dev/">https://v0.dev/</a>
</div>

---
# TDD
---

Prompt:
create ...
write tests first, then the code, then update code until tests pass

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

## layout: end

# Дякую за увагу!

<div class="flex justify-center w-full h-30 items-center">
  <img src="/slides-qr.png" class="w-25 h-25"/>
</div>
