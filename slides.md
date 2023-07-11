---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
title: 多模态大模型Demo
---

# 多模态大模型Demo

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/omni-gpt/OmniGPT4" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
transition: fade-out
---

# 功能

- 📝 **图、文理解** - 描述图片，解释图片中发生的事情，识别图片中的著名人物等
- 🎨 **诗歌生成** - 根据图片和文本的意境，生成诗歌
- 🧑‍💻 **小说生成** - 以图片和文本作为背景，写小说/故事
- 🤹 **广告词生成** - 根据产品图片，生成广告词
- 🎥 **食谱生成** - 根据食物照片，生成相应的食谱
- ...


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: center
class: text-center
---

# Learn More

[GitHub](https://github.com/omni-gpt/OmniGPT4) · [Discord Bot](https://discord.com/channels/@me/1106865585800892517)
