---

layout: about
title: about
permalink: /
subtitle: Sophomore @ Yale '27 | CS + ML Research.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Silliman College</p>
    <p>Yale University</p>
    <p>New Haven, CT 06511</p>

news: false # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

<div class="typing-container">
  <p id="typing-effect-hello"></p>
  <p id="typing-effect-intro"></p>
</div>

<script>
  // First typing effect for "Hello 👋!"
  const textHello = "Hello 👋!";
  const typingSpeedHello = 100; // milliseconds per character
  let iHello = 0;

  function typeWriterHello() {
    if (iHello < textHello.length) {
      document.getElementById("typing-effect-hello").textContent += textHello.charAt(iHello);
      iHello++;
      setTimeout(typeWriterHello, typingSpeedHello);
    }
  }

  document.addEventListener("DOMContentLoaded", typeWriterHello);

  // Second typing effect with bold text
  const textIntro =
    "I'm **William**. I'm an avid ML researcher and developer broadly interested in intelligent robotics, computer vision, and embedded systems. Currently modeling human behavior within serialized media industries.";
  const typingSpeedIntro = 50; // milliseconds per character
  let iIntro = 0;
  let bold = false;

  function typeWriterIntro() {
    if (iIntro < textIntro.length) {
      const char = textIntro.charAt(iIntro);
      const typingEffectIntro = document.getElementById("typing-effect-intro");

      if (char === "*" && !bold) {
        typingEffectIntro.innerHTML += "<b>";
        bold = true;
      } else if (char === "*" && bold) {
        typingEffectIntro.innerHTML += "</b>";
        bold = false;
      } else {
        typingEffectIntro.innerHTML += char;
      }

      iIntro++;
      setTimeout(typeWriterIntro, typingSpeedIntro);
    }
  }

  document.addEventListener("DOMContentLoaded", typeWriterIntro);
</script>

<style>
  .typing-container {
    font-family: Arial, sans-serif;
    font-size: 1rem;
    color: #333;
    white-space: nowrap; /* Prevents line breaks during typing */
    overflow: hidden; /* Hides text that's not fully typed */
    border-left: 4px solid #ddd; /* Simulates block quote styling */
    padding-left: 10px;
  }

  @keyframes blink-caret {
    from,
    to {
      border-color: transparent;
    }
    50% {
      border-color: black;
    }
  }
</style>



Previously @:
- **[Yale School of Management](https://som.yale.edu/)** (Tobin Undergraduate Research Assistant - under Prof. Wang Tong)
- **[OptoKnowledge Systems Inc.](https://oksi.ai/)** (Applied AI/ML Software Engineer Intern)
- **[University of Southern California Melady Lab](https://melady.usc.edu/)** (ML Research Intern - under Prof. Yan Liu); as a USC-Meta SURE Fellow.
- **[Stony Brook University 3D Scanning Lab](https://www3.cs.stonybrook.edu/~gu/software/holoimage/index.html)** (ML Research Assistant - under Prof. Xianfeng Gu)
- **[University of Southern California Institute for Biomedical Therapeutics](https://ibt.usc.edu/)** (Computer Vision Research Assistant - under Dr. Lan Yue)

Check out some things I have built/am working on: [publications](https://scholar.google.com/citations?user=cinjCSwAAAAJ&hl=en&authuser=1) and [code](https://github.com/williamhuang08).

