---
layout: default
title: Home
---

Welcome to my page!



<!-- Email icon in top-right corner -->
<style>
#emailIcon {
  position: fixed;
  top: 20px;
  right: 20px;
  font-size: 1.8em;
  cursor: pointer;
  transition: transform 0.2s;
}
#emailIcon:hover {
  transform: scale(1.2);
}
.tooltip {
  position: fixed;
  top: 50px;
  right: 25px;
  background: #333;
  color: #fff;
  padding: 5px 10px;
  border-radius: 4px;
  font-size: 0.9em;
  opacity: 0;
  transition: opacity 0.2s;
  pointer-events: none;
}
.tooltip.show {
  opacity: 1;
}
</style>

<div id="emailIcon" title="Copy email">📧</div>
<div id="tooltip" class="tooltip">Email copied!</div>

<script>
const email = "gabriella.wallentin@kit.edu"; // replace with your email
const icon = document.getElementById("emailIcon");
const tooltip = document.getElementById("tooltip");

icon.addEventListener("click", () => {
  navigator.clipboard.writeText(email).then(() => {
    tooltip.classList.add("show");
    setTimeout(() => tooltip.classList.remove("show"), 1500);
  }).catch(() => {
    alert("Failed to copy email.");
  });
});
</script>
