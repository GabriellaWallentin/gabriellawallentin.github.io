---
layout: default
title: Gabriella Wallentin

---

[About Me](/about/)

Welcome to my page!

# Research Interest


# Publications

* Preprint: [The Prevalence of Arctic Multilayer Clouds and their Observed and Modelled Characteristics](https://egusphere.copernicus.org/preprints/2025/egusphere-2025-5070/)
* [Sensitivities of simulated mixed-phase Arctic multilayer clouds to primary and secondary ice processes](https://acp.copernicus.org/articles/25/6607/2025/)
* PhD Thesis: [The Microphysical and Radiative Interactions of Arctic Multilayer Clouds](https://publikationen.bibliothek.kit.edu/1000179667)
  
# Datasets
* [Model Data for "The Prevalence of Arctic Multilayer Clouds and their Observed and Modelled Characteristics"](https://zenodo.org/records/15829738)
* [Research data for "Sensitivities of Simulated Mixed-phase Arctic Multilayer Clouds to Primary and Secondary Ice Processes"](https://publikationen.bibliothek.kit.edu/1000180885)
* [Research Data for the PhD Thesis "The Microphysical and Radiative Interactions of Arctic Multilayer Clouds"](https://publikationen.bibliothek.kit.edu/1000180884)
  

<style>
/* Grid container */
.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

/* Card style */
.grid-card {
  background: #f5f5f5;
  border-radius: 10px;
  padding: 20px;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.2s, box-shadow 0.2s;
}

.grid-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 12px rgba(0,0,0,0.2);
}

.grid-card a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
  display: block;
}
</style>

<div class="grid-container">
  <div class="grid-card">
    <a href="/subpage1/">Subpage 1</a>
    <p>Short description of subpage 1</p>
  </div>
  <div class="grid-card">
    <a href="/subpage2/">Subpage 2</a>
    <p>Short description of subpage 2</p>
  </div>
  <div class="grid-card">
    <a href="/subpage3/">Subpage 3</a>
    <p>Short description of subpage 3</p>
  </div>
</div>


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
