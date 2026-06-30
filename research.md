---
layout: research
title: Research

# ── How to add or edit a topic ───────────────────────────────────
# Each item below becomes one alternating image/text block on the
# page, in the order listed. They don't need a "side" setting --
# left/right alternates automatically.
#
#   title:        short topic heading
#   image:        path to a photo under assets/images/research/
#                 (leave as the placeholder path if you don't have
#                 one yet -- it'll just show an empty gray box)
#   section:      groups topics under a heading. Topics must be
#                 listed in order -- once you move to a new section
#                 value, you can't go back to an earlier one without
#                 it creating a second heading further down the page.
#                 Use whatever labels you like, e.g. "Past work",
#                 "Ongoing", "Future directions" -- or omit this key
#                 entirely on a topic to leave it un-headed.
#   text:         one paragraph describing the topic
#   publications: a list of citation strings. Add as many as you
#                 like, or remove the whole `publications:` key
#                 for a topic with nothing published yet. Markdown
#                 works inside each string -- use _underscores_ for
#                 italic journal names and [text](url) for links.
#                 IMPORTANT: indent list items with spaces only,
#                 never tabs -- a tab anywhere in this file will
#                 break the YAML parsing for the whole page.
topics:
  - title: "Groundwater and landscape coevolution"
    image: /assets/images/research/coevol-mosaic.png
    section: "Ongoing"           # <- adjust these section labels/groupings as you see fit
    text: >
      Our foundational work involved developing coupled groundwater–landscape evolution
      models to understand how subsurface properties and climate are
      expressed in topography, and how landscapes respond to tectonics. Ongoing work tests this with data. 
    publications:
      - "Litwin, D. G., Tucker, G., Barnhart, K., & Harman, C. (2020). GroundwaterDupuitPercolator: A Landlab component for groundwater flow. Journal of Open Source Software. [https://doi.org/10.21105/joss.01935](https://doi.org/10.21105/joss.01935)"
      - "Litwin, D. G., Tucker, G. E., Barnhart, K. R., & Harman, C. J. (2022). Groundwater affects the geomorphic and hydrologic properties of coevolved landscapes. Journal of Geophysical Research: Earth Surface. [https://doi.org/10.1029/2021JF006239](https://doi.org/10.1029/2021JF006239)"
      - "Litwin, D. G., Tucker, G. E., Barnhart, K. R., & Harman, C. J. (2024). Catchment coevolution and the geomorphic origins of variable source area hydrology. Water Resources Research. [https://doi.org/10.1029/2023WR034647](https://doi.org/10.1029/2023WR034647)"
      - "Litwin, D. G., & Harman, C. J. (2024). Evidence of Subsurface Control on the Coevolution of Hillslope Morphology and Runoff Generation. Water Resources Research. [https://doi.org/10.1029/2024WR037301](https://doi.org/10.1029/2024WR037301)"

  - title: "Groundwater and tectonic geomorphology"
    image: /assets/images/research/swabian-alb.png
    section: "Ongoing"
    text: >
      In karst landscapes, groundwater can flow efficiently across
      topographic divides rather than following slope, with consequences
      for how landscapes respond to tectonics and baselevel change. We use
      numerical models to study these dynamics in places like the
      karstified plateau between the Rhine and Danube watersheds.
    publications:
      - "Litwin, D. G., & Malatesta, L. C. (In Review). Slower erosion in carbonate landscapes due to partitioning of energy between surface and groundwater flow. Geology."
  
  - title: "Groundwater, slope creep, and failure"
    image: /assets/images/research/placeholder.jpg
    section: "Ongoing"
    text: >
      We are working on how groundwater dynamics influence soil creep and
      slope failure under extreme precipitation — a growing hazard
      concern as storm intensity shifts with climate change.
    publications:
      - "Houssais, M., Litwin, D. G. (Submitted). Modeling hillslope sediment creep dynamics triggered by seepage events."


  - title: "Hydrological insights with geophysics"
    image: /assets/images/research/geophys-mosaic.png
    section: "Ongoing"
    text: >
      Geophysical and seismic methods are powerful tools for probing CZ structure. We collaborate with geophysicists and seismologists to bring hydrological expertise 
      to their work, for example, helping interpret how seasonal hydrology may drive 
      changes in seismic wave attenuation.
    publications:
      - "Händel, A., Pilz, M., Malatesta, L. C., Litwin, D., & Cotton, F. (2025). Detecting seasonal differences in high-frequency site response using κ0. Seismica. [https://doi.org/10.26443/seismica.v4i1.1425](https://doi.org/10.26443/seismica.v4i1.1425)"
      - "Motz, S., Litwin, D. G., Chiaviello, A., Flinchum, B., Harman, C. J. (2022). NS32B-0369: Looking for the Fill-and-Spill Mechanism with Ground Penetrating Radar–Panola Mountain, Georgia. Poster. American Geophysical Union Fall Meeting."
  
  - title: "Groundwater and landscape change in cold regions"
    image: /assets/images/research/water-tracks.png
    section: "Ongoing"
    text: >
      We are developing models that couple shallow groundwater flow to the
      thermal dynamics of permafrost thaw, to understand how subsurface
      properties shape the emergence of melt patterns in Arctic and
      high-latitude landscapes.
    publications:
      - " "

  - title: "Future Directions"
    image: /assets/images/research/lehigh-1.jpeg
    section: "Future Work"
    text: >
      Future work in the lab will extend these themes toward water resources under climate and land-use change — including questions about regional groundwater recharge and groundwater-dependent ecosystems in mountainous headwaters. I'm also interested in growing research connecting hydrology to local water issues in the Philadelphia region. Students are welcome to bring their own project ideas in any of these areas, or in CZ hydrology and geomorphology more broadly.


  - title: "Channel-hillslope coupling"
    image: /assets/images/research/esurf-2025-fig.png
    section: "Past"
    text: >
      This work aimed to improve understanding of the link
      between hillslope and channel processes, identifying scaling
      relationships and limitations that affect how widely-used
      landscape evolution models should be interpreted.
    publications:
      - "Litwin, D. G., Malatesta, L. C., & Sklar, L. S. (2025). Hillslope diffusion and channel steepness in landscape evolution models. Earth Surface Dynamics, 13(2), 277–293. [https://doi.org/10.5194/esurf-13-277-2025](https://doi.org/10.5194/esurf-13-277-2025)"



  # Example of a topic in a new section -- uncomment and fill in when
  # you have a future-direction topic ready to add. Since it has a new
  # `section` value, it'll automatically get its own heading below the
  # "Ongoing" topics above.
  # - title: "Water resources under climate and land-use change"
  #   image: /assets/images/research/placeholder.jpg
  #   section: "Future directions"
  #   text: >
  #     A paragraph describing this direction.
  #   publications:
  #     - "Add citation here once this work is published."
---

<!-- Optional short intro paragraph above the topic list. Delete this
     comment and the line below if you'd rather start straight into
     the topics. -->
Below are the main directions of current and ongoing work in the lab.
