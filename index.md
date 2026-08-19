---
custom_page_title: CRADLE project
banner_image: images/Entorno_MdT.jpg
banner_title: Welcome to the SPAC-CRADLE project!
banner_subtitle: <strong> Cascading energy </strong> - Carbon and water through the soil-plant atmosphere continuum using integrated observations and modelling
banner_links:
  - name: The team
    id: team/index
  - name: The research
    id: research/index
template: home.html
---

{% import "macros.html" as macros %}

## What is it about? 




<div class="callout">
<span class="callout-title">Key methods &amp; outputs</span>
<ul>
The project’s acronym is inspired by Newton's cradle analogy, which was used to demonstrate principles of conservation of momentum and energy using a series of metal balls. Similarly, the soil–plant–atmosphere continuum (SPAC) depends on all its interacting layers, and removing one “ball”, for instance, overlooking any of the soil, plant, or atmospheric dynamics, disrupts the chain of energy and mass transfer across the SPAC. 
</ul>
</div>


When that link is missing, the final “ball” doesn’t move, and we lose the ability to capture key ecological and Earth-system interactions that are essential for fully understanding and monitoring agro-ecosystems. 

As such, to adequately characterize critical processes across the SPAC, a holistic approach integrating multidisciplinary expertise is needed, especially to unravel poorly understood processes, such as deep subsoil dynamics and the role of non-water rainfall inputs. In light of this and to overcome current limitations in state-of-the-art models and observation systems, the project comprises two interconnected subprojects (SP): 
- **Newton’s Cradle Action (SP1, CRADLE-ROOTS)**, which focuses on the soil–root system, and 
- **Newton’s Cradle Reaction (SP2, CRADLE-FLUX)**, which addresses plant–atmosphere interactions.

---

{{ macros.figure(src="./images/concept_SPAC_cradle.png", 
    alt="concept_SPAC_cradle.png", 
    caption="The Soil-Plant-Atmosphere Continuum (SPAC)-CRADLE conceptual design with subproject 1 (SP1) and subproject 2 (SP2) interactions. SP1 and SP2 are linked by the Integrated Observation System (IOS).", 
    figsize="width:auto; height:auto;") }}

## Work Packages

<div class="card-grid">

<a class="wp-card" style="--wp-color: var(--color-accent-maroon);" href="{{ site['research/wp1'].path|relative_to(page.path) }}">
  <span class="wp-eyebrow">WP1</span>
  <h3>Soil</h3>
  <p>Subsoil geophysical imaging to map moisture and hydraulic properties beyond the reach of point sensors.</p>
</a>

<a class="wp-card" style="--wp-color: var(--color-accent-crimson);" href="{{ site['research/wp2'].path|relative_to(page.path) }}">
  <span class="wp-eyebrow">WP2</span>
  <h3>Plant</h3>
  <p>Physiological measurements and remote sensing of vegetation traits and non-rainfall water inputs.</p>
</a>

<a class="wp-card" style="--wp-color: var(--color-primary);" href="{{ site['research/wp3'].path|relative_to(page.path) }}">
  <span class="wp-eyebrow">WP3</span>
  <h3>Atmosphere</h3>
  <p>Micrometeorological, proximal and spaceborne observation of land–atmosphere exchange.</p>
</a>

<a class="wp-card" style="--wp-color: var(--color-accent-green);" href="{{ site['research/wp4'].path|relative_to(page.path) }}">
  <span class="wp-eyebrow">WP4</span>
  <h3>Connecting the pieces</h3>
  <p>An integrated SPAC model linking soil, plant and atmosphere fluxes end to end.</p>
</a>

<a class="wp-card" style="--wp-color: var(--color-secondary);" href="{{ site['research/wp5'].path|relative_to(page.path) }}">
  <span class="wp-eyebrow">WP5</span>
  <h3>Evaluation</h3>
  <p>Applying the integrated model to water management, ecosystem function and soil health.</p>
</a>

<a class="wp-card" style="--wp-color: var(--color-dark);" href="{{ site['research/wp6'].path|relative_to(page.path) }}">
  <span class="wp-eyebrow">WP6</span>
  <h3>Communication &amp; Dissemination</h3>
  <p>Sharing project outcomes with scientists, students, farmers and the wider public.</p>
</a>

