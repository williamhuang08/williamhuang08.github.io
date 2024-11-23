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

<script>
  const text = "Hello 👋!";
  const typingSpeed = 100; // milliseconds per character
  let i = 0;

  function typeWriter() {
    if (i < text.length) {
      document.getElementById("typing-effect").textContent += text.charAt(i);
      i++;
      setTimeout(typeWriter, typingSpeed);
    }
  }

  document.addEventListener("DOMContentLoaded", typeWriter);
</script>


> <div class="typing-container">
    <p id="typing-effect"></p>
  </div>

<script>
  const text = "I'm **William**. I'm an avid ML researcher and developer broadly interested in intelligent robotics, computer vision, and embedded systems. Currently modeling human behavior within serialized media industries.";
  const typingSpeed = 50; // milliseconds per character
  let i = 0;

  function typeWriterIntro() {
    if (i < text.length) {
      document.getElementById("typing-effect").innerHTML += text.charAt(i) === "*" 
        ? "<b>" : text.charAt(i) === "*" ? "</b>" : text.charAt(i);
      i++;
      setTimeout(typeWriterIntro, typingSpeed);
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
    overflow: hidden;    /* Hides text that's not fully typed */
    border-left: 4px solid #ddd; /* Simulates the block quote's styling */
    padding-left: 10px;
  }

  @keyframes blink-caret {
    from, to {
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

