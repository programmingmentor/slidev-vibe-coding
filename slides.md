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

<div class="m-6 flex gap-2 fixed bottom-0 left-0">
  <a href="https://www.youtube.com/c/programmingmentorua">
    <div class="h-8 w-8">
      <img src="/pm-logo.jpg" class="h-full w-full rounded-full"/>
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
layout: image-left
image: /software-engineer-1-0.jpg
---

# Software Engineer 1.0

- Knowledge: books, articles, paper documentation
- Communication via email, phone
- Primitive developer tools, version control systems
- SDLC: Waterfall, V-model
  <br>
  <br>
  <v-click>What was the development speed?</v-click>
  <br>
  <v-click>Were they less qualified specialists than today?</v-click>

---
layout: image-left
image: /software-engineer-2-0.webp
---

# Software Engineer 2.0

- Knowledge: Internet, online courses, Google, StackOverflow
- Communication via Slack, Teams, Discord, Zoom, Google Meet, Telegram
- Advanced developer tools, version control systems with CI/CD
- SDLC: Agile, DevOps
  <br>
  <br>
  <v-click>What is the development speed?</v-click>
  <br>
  <v-click>How much more qualified compared to 1.0?</v-click>

<!--
Nasa Programmer Margret Hamilton standing next to the code that brought man to the moon.
-->

---

# Software Engineer 3.0

<div class="absolute inset-0 flex justify-center items-center">
  <div class="text-9xl font-bold">?</div>
</div>

---
layout: image
image: /timeline-of-tech-longterm.png
backgroundSize: contain
title: Timeline of Tech
---

---
layout: center
---

#### It's not that everything is developing quickly now, it's that everything used to happen slowly

<div class="flex justify-center">
  <Tweet class="w-1/2" id="1848558163756519607" />
</div>

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

# repl.it agent

<div class="w-full flex justify-center">
  <img src="/replit.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://repl.it/">https://repl.it/</a>
</div>

---

# Github Copilot

<div class="w-full flex justify-center">
  <img src="/github-copilot.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://copilot.github.com/">https://copilot.github.com/</a>
</div>

---

# Cursor

<div class="w-full flex justify-center">
  <img src="/cursor.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://www.cursor.com/">https://www.cursor.com/</a>
</div>

---

# Windsurf

<div class="w-full flex justify-center">
  <img src="/windsurf.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://codeium.com/windsurf">https://codeium.com/windsurf</a>
</div>

---

# Cline

<div class="w-full flex justify-center">
  <img src="/cline.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://cline.bot/">https://cline.bot/</a>
</div>

---

# MCP - Model Context Protocol

<div class="w-full flex justify-center">
  <img src="/mcp.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://modelcontextprotocol.io/">https://modelcontextprotocol.io/</a>
</div>

---

# MCP.so

<div class="w-full flex justify-center">
  <img src="/mcp-list.png" class="w-1/2"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://mcp.so/">https://mcp.so/</a>
</div>

---

<div class="w-full h-full flex justify-center items-center">
  <h1 class="text-center">Tips, Tricks and Resources</h1>
</div>

---

# Cursor Rules

<div class="w-full flex justify-center">
  <img src="/cursor-rules.png" class="w-2/3"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://docs.cursor.com/context/rules-for-ai">https://docs.cursor.com/context/rules-for-ai</a>
</div>

---

# Cursor.directory

<div class="w-full flex justify-center">
  <img src="/cursor-directory.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://cursor.directory/">https://cursor.directory/</a>
</div>

---

# llms.txt

<div class="w-full flex justify-center">
  <img src="/llms-txt.png" class="w-1/2"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://llmstxt.org/">https://llmstxt.org/</a>
</div>

---

# Drizzle ORM llms.txt

<Tweet scale="0.65" id="1896981123559002158" class="w-3/4"/>

https://orm.drizzle.team/llms.txt

---

# Plan Mode

<div class="w-full flex justify-center">
  <img src="/cursor-plan-mode.png" class="w-1/2"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://forum.cursor.com/t/plan-vs-act-mode-xml-prompt/50996">https://forum.cursor.com/t/plan-vs-act-mode-xml-prompt/50996</a>
</div>

---

# Docs

<div class="w-full flex justify-center">
  <img src="/cursor-docs.png" class="w-3/4"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://docs.cursor.com/context/@-symbols/@-docs">https://docs.cursor.com/context/@-symbols/@-docs</a>
</div>

---

# TDD

# Prompt:

## create ...

## write tests first, then the code, then update code until tests pass

---

# Local History Plugin

<div class="w-full flex justify-center">
  <img src="/local-history.png" class="w-1/2"/>
</div>

---

# Issues

- Breaking code changes
- Hallucinations and incorrect solutions
- Deadlocks
- Limited knowledge of new libraries/frameworks
- Issues with large codebases
- Issues with security
- Speed of development
- Cost of usage
- ...

---
## layout: end
---

# Thank you!

<div class="flex justify-center w-full h-30 items-center">
  <img src="/slides-qr.png" class="w-25 h-25"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://programmingmentor.github.io/slidev-vibe-coding/">https://programmingmentor.github.io/slidev-vibe-coding/</a>
</div>
