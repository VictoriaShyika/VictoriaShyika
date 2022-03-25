### Hi there 👋
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      HTML,
      BODY {
        height: 100%;
      }
      BODY {
        background-size: 0.12em 100%;
        font: 16em/1 Arial;
      }
      .text--line {
        font-size: 0.5em;
      }
      svg {
        position: absolute;
        width: 100%;
        height: 100%;
      }
      .text-copy {
        fill: none;
        stroke: white;
        stroke-dasharray: 7% 28%;
        stroke-width: 3px;
        animation: stroke-offset 9s infinite linear;
      }
      .text-copy:nth-child(1) {
        stroke: #360745;
        stroke-dashoffset: 7%;
      }
      .text-copy:nth-child(2) {
        stroke: #d61c59;
        stroke-dashoffset: 14%;
      }
      .text-copy:nth-child(3) {
        stroke: #e7d84b;
        stroke-dashoffset: 21%;
      }
      .text-copy:nth-child(4) {
        stroke: #efeac5;
        stroke-dashoffset: 28%;
      }
      .text-copy:nth-child(5) {
        stroke: #1b8798;
        stroke-dashoffset: 35%;
      }
      @keyframes stroke-offset {
        50% {
          stroke-dashoffset: 35%;
          stroke-dasharray: 0 87.5%;
        }
      }
    </style>
  </head>
  <body>
    <svg viewBox="0 0 800 600">
      <symbol id="s-text">
        <text text-anchor="middle" x="50%" y="35%" class="text--line">
          Victoria
        </text>
        <text text-anchor="middle" x="50%" y="68%" class="text--line2">
          Shyika
        </text>
      </symbol>

      <g class="g-ants">
        <use xlink:href="#s-text" class="text-copy"></use>
        <use xlink:href="#s-text" class="text-copy"></use>
        <use xlink:href="#s-text" class="text-copy"></use>
        <use xlink:href="#s-text" class="text-copy"></use>
        <use xlink:href="#s-text" class="text-copy"></use>
      </g>
    </svg>
  </body>
</html>





<!--
**VictoriaShyika/VictoriaShyika** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
