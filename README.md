<div align="center">
<h1>📚 Morph-it Lexicon Processor 🧠</h1>

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/5159e5b528634dbdb00ad58f10bc5171)](https://app.codacy.com/gh/R0mb0/Morph-it_Lexicon_Processor_Exporter/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![pages-build-deployment](https://github.com/R0mb0/Morph-it_Lexicon_Processor_Exporter/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/R0mb0/Morph-it_Lexicon_Processor_Exporter/actions/workflows/pages/pages-build-deployment)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/R0mb0/Morph-it_Lexicon_Processor_Exporter)
[![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/R0mb0/Morph-it_Lexicon_Processor_Exporter)
[![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/license/mit)
[![Donate](https://img.shields.io/badge/PayPal-Donate%20to%20Author-blue.svg)](http://paypal.me/R0mb0)

<p>
A lightning-fast, client-side web application designed to parse, filter, and export the massive <strong>Morph-it</strong> Italian lexicon dataset. Upload the raw <code>.txt</code> file, explore complex linguistic categories through an intuitive collapsible tree interface, and instantly download your custom dictionary in JSON, CSV, or TXT format. Everything runs locally in your browser for maximum privacy and performance! 🚀
</p>

<div align="center">
  <a href="http://paypal.me/R0mb0">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Light.svg">
      <img alt="Saved you time? Support the dev" src="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Default.svg">
    </picture>
  </a>
</div>

## [👉 Click here to test the App! 👈](https://r0mb0.github.io/Morph-it_Lexicon_Processor_Exporter/)



</div>
<hr>

<h2>🚀 Features</h2>
<ul>
<li><strong>100% Local Processing</strong>: Capable of parsing over 500,000 lines of text instantly in your browser. Zero server uploads, zero latency, and absolute data privacy.</li>
<li><strong>Recursive Tree UI</strong>: Intelligently groups 600+ complex morphological tags (like <code>VER:ind+pres+1+p</code>) into a clean, collapsible directory-style tree using native HTML <code>&lt;details&gt;</code> tags.</li>
<li><strong>Smart Selection</strong>: Prevent misclicks! Select or deselect entire branches (e.g., all Adjectives or Verbs) with a single click using the dedicated branch controls.</li>
<li><strong>Multi-Format Export</strong>: Tailor your output to your needs. Export a key-value <strong>JSON</strong> for software development, a <strong>CSV</strong> for data science and databases, or a pure <strong>TXT</strong> wordlist for Scrabble and anagram games.</li>
<li><strong>Completely Offline Ready</strong>: Powered by a local Tailwind CSS script. You can run the entire application perfectly without an active internet connection.</li>
<li><strong>Bilingual & Dark Mode</strong>: Automatically adapts the interface to English or Italian, and perfectly aligns with your system's Light or Dark theme preferences.</li>
</ul>

<h2>🛠️ How it works</h2>
<ol>
<li><strong>File Parsing:</strong> The HTML5 <code>FileReader</code> API reads the tab-separated Morph-it document line by line, ensuring only unique words are kept.</li>
<li><strong>Tree Construction:</strong> The algorithm splits the category tags using <code>:</code> and <code>+</code> delimiters to dynamically generate a nested JavaScript object, mapping the macroscopic categories down to the most granular leaf nodes.</li>
<li><strong>Asynchronous UI:</strong> Utilizes <code>requestAnimationFrame</code> and JavaScript Promises to render elegant loading overlays, preventing the browser's main thread from freezing during heavy array processing.</li>
<li><strong>Blob Generation:</strong> Upon export, the app filters the massive array in milliseconds and generates a downloadable Blob URL completely on the fly.</li>
</ol>

<h2>🏆 What makes it special?</h2>
<ul>
<li><strong>Highly Optimized</strong>: Handling half a million DOM nodes can crash a browser. By using collapsible sections and smart asynchronous yielding, the app remains responsive and smooth.</li>
</ul>

<h2>💡 Why use this project?</h2>
<ul>
<li><strong>Game Development</strong>: Easily extract a clean TXT list of valid Italian words (excluding proper nouns or specific verb tenses) to power your next crossword, Scrabble clone, or Wordle-like game.</li>
<li><strong>NLP & Data Science</strong>: Quickly generate tailored CSV datasets for machine learning models or linguistic research without touching a command line.</li>
</ul>

<h2>⚡ Getting Started</h2>

<h3>Online</h3>
<p>Simply open the <a href="https://r0mb0.github.io/Morph-it_Lexicon_Processor_Exporter/">Live Demo link</a> on any browser, drop your <code>.txt</code> file, and start filtering!</p>

<h3>Local Installation</h3>
<p>Want to run it locally or use it entirely offline?</p>
<ol>
<li><strong>Clone this repository</strong> or download the source code ZIP.</li>
<li>Make sure the <code>tailwind.js</code> file is located in your <code>src</code> folder as referenced in the <code>index.html</code>.</li>
<li>Double-click <code>index.html</code> to open it in your browser. No local server required!</li>
</ol>

<br>

<a href="https://github.com/R0mb0/Crafted_with_AI">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/CraftedWithAIDark.svg">
<source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/NotMadeByAILight.svg">
<img alt="Crafted with AI" src="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/CraftedWithAIDefault.svg">
</picture>
</a>
