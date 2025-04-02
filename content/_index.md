---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: my-resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: vlti_22.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false

  - block: my-markdown
    id: research-highlights-title
    content:
      title: "Research Highlights"

  - block: research-highlights
    id: 'tstbar_intro'
    content:
      title: 'Imaging HR 8799 bcde and 51 Eri b with JWST'
      subtitle: ''
      figtext: '{{< figure src="/uploads/hr8799bcde_tstbar_opo_fancy.png" width="320">}}'
      external_link: https://webbtelescope.org/contents/news-releases/2025/news-2025-114
      highlight: 'tstbar_intro'
  - block: research-highlights-left
    content:
      title: 'Measuring CO2 Absorption, Constraining Composition'
      subtitle: ''
      figtext: '{{< figure src="/uploads/51erib_tstbar_opo_fancy.png" width="320">}}'
      external_link: https://ui.adsabs.harvard.edu/abs/2025AJ....169..209B/abstract
      highlight: tstbar_details
  - block: research-highlights
    content:
      title: 'How Typical Is AF Leporis b? Answers from Interferometry'
      subtitle: ''
      figtext: '{{< figure src="/uploads/astrometric_orbit_aflepb.png" width="400">}}'
      external_link: https://ui.adsabs.harvard.edu/abs/2025AJ....169...30B/abstract
      highlight: vlti_aflepb_char


  - block: awards-and-observing
    content:
      title: Awards & Observing Programs
      username: admin
    design:
      show_skill_percentage: false

# new section, publications
  - block: collection
    id: publications
    content:
      title: Select Publications
      weight: 30
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      view: citation
      columns: "2"
      background:
        image: 
          filename: paranal_22.jpg
        image_darken: 0.5
        image_parallax: true
        image_position: center
        image_size: cover
        text_color_light: true
      spacing:
        padding: ["50px", "0", "50px", "0"]
# new section, 
  - block: markdown
    id: volunteer-outreach
    content: 
      title: ""
      subtitle: ""
      text: |
        ## <center> Outreach Activites </center>

        Observatory Fellow, Maryland Space Grant Consortium | September 2022 - May 2023

        Volunteer, Maryland Space Grant Observatory | May 2023 - present

        Penpal, Letters to a Pre-Scientist | February 2025 - present

        Volunteer, Youth in Engineering and Astronomy, STScI | October 2022 - September 2023

        Author, [Astrobites, the astro-ph reader's digest](https://astrobites.org/author/wbalmer/) | December 2021 - present

        Author, [personal blog](https://www.astrowill.page/) | June 2018 – present

        Astronomy Editor, [Amherst STEM Network](https://www.amherststemnetwork.com/) | October 2019 – May 2021

    design:
      columns: "1"
      background:
        image: 
          filename: kpno.jpeg
        image_darken: 0.5
        image_parallax: true
        image_position: center
        image_size: cover
        text_color_light: true
      spacing:
        padding: ["50px", "0", "50px", "0"]
# new section
  - block: markdown
    id: press
    content:
      title: Research in the Press
      subtitle: ''
      text: |
        A selection of articles written about research I'm involved in; articles on a repeated topic typically indicate I provided additional comments for that particular article. Last updated 2025/03/27.

        "[Scientists used JWST instruments 'wrong' on purpose to capture direct images of exoplanets](https://www.space.com/space-exploration/james-webb-space-telescope/scientists-used-jwst-instruments-wrong-on-purpose-to-capture-direct-images-of-exoplanets)," by Victoria Corless for *Space.com*.

        "[Webb telescope directly observes exoplanet CO<sub>2</sub> for first time](https://phys.org/news/2025-03-webb-telescope-exoplanet.html)," by Daniel Lawler for *AFP*, available on *phys.org*.

        "[El supertelescopio James Webb logra sus primeras imágenes directas de dióxido de carbono fuera de nuestro sistema solar](https://www.elmundo.es/ciencia-y-salud/ciencia/2025/03/17/67d47779fc6c837f728b458f.html)," by Teresa Guerrero for *El Mundo*. 

        "NASA's Webb Images Young, Giant Exoplanets, Detects Carbon Dioxide," by Roberto Molar Candanosa for [JHU](https://hub.jhu.edu/2025/03/17/webb-telescope-carbon-dioxide-exoplanet/), and Hannah Braun for [STScI](https://webbtelescope.org/contents/news-releases/2025/news-2025-114?ftag=MSF0951a18) and [NASA](https://science.nasa.gov/missions/webb/nasas-webb-images-young-giant-exoplanets-detects-carbon-dioxide/). 

        "[UT Astronomers Race To Capture Image of Exoplanet Near Star](https://mcdonaldobservatory.org/news/releases/20241009)," McDonald Observatory Press Release, October 9, 2024

        "[Newfound alien planet has nuclear fusion going in its core](https://www.space.com/europe-gaia-mission-exoplanet-nuclear-fusion)," by Andrew Jones for *Space.com* 

    design:
      columns: "1"
      background:
        image: 
          filename: JHU_beehive.jpg
        image_darken: 0
        image_parallax: true
        image_position: center
        image_size: cover
        text_color_light: true
      spacing:
        padding: ["50px", "0", "50px", "0"]
# new section
  - block: markdown
    id: reporting
    content:
      title: Science Journalism
      subtitle: ''
      text: |
        Articles I’ve written. Last updated 2025/03/13.

        "[How astronomers search for life on exoplanets](https://www.planetary.org/articles/how-astronomers-search-for-life-on-exoplanets)" by William Balmer for *The Planetary Society*, Oct 11, 2023

        "[Where do Hot-Jupiters come from? RV population statistics suggests planet-planet interactions](https://astrobites.org/2023/10/11/hj-ecc-migration/)" by William Balmer for *[Astrobites](https://astrobites.org/)*, Oct 11, 2023

        "[Advisee to Advising (your first research student)](https://astrobites.org/2023/07/28/advisee-to-advisor/)" by William Balmer for *[Astrobites](https://astrobites.org/)*, Jul 28, 2023

        "[Did early Earth order delivery, or did it make its oceans at home?](https://astrobites.org/2023/04/27/earths-water-oceans-from-h2-atmosphere/)" by William Balmer for *[Astrobites](https://astrobites.org/)*, Apr 27, 2023

        "[Newly discovered planet AF Lep is leading its star astray](https://astrobites.org/2023/02/25/af-lep-discovery/)" by William Balmer for *[Astrobites](https://astrobites.org/)*, Feb 25, 2023

        "[Dancing with the (Six) Stars, or, a 200 year story of the Castor system](https://astrobites.org/2022/11/07/castor-interferometry-orbits/)" by William Balmer for *[Astrobites](https://astrobites.org/)*, Nov 7, 2022

        "[JWST’s carbon dioxide discovery is good news for Earth-like worlds](https://www.planetary.org/articles/jwst-carbon-dioxide-discovery-earth-like-worlds)" by William Balmer for *The Planetary Society*, Sep 27, 2022

        "[Fly-bye, Baby: a review of the impact of stellar flybys on protoplanetary disks](https://astrobites.org/2022/08/23/stellar-fly-bye-baby/)" by William Balmer for *[Astrobites](https://astrobites.org/)*, Aug 23, 2022

        "[What might JWST reveal about TRAPPIST-1?](https://www.planetary.org/articles/james-webb-space-telescope-trappist-1)" by William Balmer for *The Planetary Society*, June 9th, 2022.

        "[Flipping the table: inferring planet formation from atmospheric composition](https://astrobites.org/2022/05/06/planet-history-from-atmos/)" by William Balmer for *[Astrobites](https://astrobites.org/)*, May 6th, 2022.

        "[Herald of the Change: A microlensing Jupiter-analogue spotted in K2 data portends Roman’s yield of new planets](https://astrobites.org/2022/04/11/k2-first-microlensing/)" by William Balmer for *[Astrobites](https://astrobites.org/)*, April 11th, 2022.

        "[Peek-a-boo! Forming Moons Revealed Around a Baby Planet](https://astrobites.org/2022/02/09/pds70c-disk/)" by William Balmer for *[Astrobites](https://astrobites.org/)*, February 9th, 2022.

        “[The Orbit and Growth of HD 142527B](https://astrobites.org/2021/03/14/ur-orbit-growth-hd142527b/)” by William Balmer for *[Astrobites](https://astrobites.org/)*, March 14th, 2021.

        “[Planetary cradles: UMass/FCAD colloquium speaker Feng Long presents ALMA view of early solar systems](https://www.canva.com/design/DAERpXSyw0w/WmJjaMKrcUTdcG3b41gqHQ/view?utm_content=DAERpXSyw0w#35)” by William Balmer in *The Amherst STEM Network Magazine*, Issue 1.3, Fall 2020.

        “[What makes a planet? Daniela Bardalez Gagliuffi seeks answers in the lowest mass stars](https://www.canva.com/design/DAD9TCKM5ZQ/1lsfJaVxS_S-3MS0N55Bvw/view#33)” by William Balmer in *The Amherst STEM Network Magazine*, Issue 1.1, Spring 2020.
    design:
      columns: "1"
      background:
        image: 
          filename: vlt_2.jpg
        image_darken: 0
        image_parallax: true
        image_position: center
        image_size: cover
        text_color_light: true
      spacing:
        padding: ["50px", "0", "50px", "0"]
---


---
