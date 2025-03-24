---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hello, I'm Will Balmer.
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: research
    content:
      color: #ffffff
      title: Research Highlights
      subtitle: ''
      text: |2-
          ________
          ## <center> Imaging HR 8799 bcde and 51 Eri b with JWST </center>
          ________
          
          <img src="/uploads/hr8799bcde_tstbar_opo_fancy.png" width="25%" hspace="20" vspace="20" align="left" />

          As a member of the JWST Telescope Scientist Team (JWST-TST), I used guaranteed time observations planned by our high contrast imaging group at STScI to reveal the atmospheres of the iconic HR 8799 planets at never-before-seen wavelengths of light. The data is described in a <a href="https://doi.org/10.3847/1538-3881/adb1c6">first author paper I published in March 2025</a>. The paper had a press release, <a href="https://webbtelescope.org/contents/news-releases/2025/news-2025-114">found here</a>. This result validates the findings of our <a href="https://arxiv.org/abs/2404.03776">ExoGRAVITY collaboration paper on the system</a>, that the four gas giants in the HR 8799 system appear to be metal rich compared to their host star, indicating that they formed via core accretion. In order to block the light from the bright host star and reveal these faint planets, we used a novel mode of the Near Infrared Camera (NIRCam) coronagraph, placing all the observations at the narrowest end of the underutilized wedge shaped mask.

          <img src="/uploads/51erib_tstbar_opo_fancy.png" width="30%" hspace="5" vspace="5" align="right" />

          In particular, our JWST observations show carbon dioxide absorption (CO<sub>2</sub>) in each planet's atmosphere, which, compared to the carbon monoxide absorption (CO) gives us a handle on the relative enrichment of heavy elements in the atmosphere. I was awarded about 23 hours of additional JWST observing time in order to measure this same absorption feature in <a href="https://www.stsci.edu/jwst/science-execution/program-information?id=6905">four additional directly imaged systems</a>. That means four more beautiful images of giant exoplanets from JWST in the near future!

          We also observed the young, Jupiter-mass planet 51 Eri b. Despite how faint this planet is, we were able to detect it at a wavelength of 4.1 microns, which tells us indirectly about how hot the planet is, and how much CO<sub>2</sub> is in its atmosphere. 51 Eri b is one of my favorite planets, so it was a pleasure to be able to observe it with JWST and update its orbit with <a href="https://orbitize.info/">orbitize!</a>.

          ________
          ## <center>Characterizing Exolanets and Brown Dwarf Companions with VLTI/GRAVITY</center>
          ________
          <img src="/uploads/astrometric_orbit_aflepb.png" width="25%" hspace="20" vspace="20" align="right" />
          I use the K-band (2-2.5 micron) beam combining instrument GRAVITY to study exoplanets and brown dwarfs as a member of the ExoGRAVITY collaboration. Using optical interferometry, we make very precise measurements of the orbital motion of giant planets, and collect spectra containing information about the abundances of carbon and oxygen bearing molecules in their atmospheres. We use both of these measurements to better understand the formation and composition of giant planets. Recent work inclues an <a href="https://arxiv.org/abs/2411.05917">in-depth study of AF Lep b</a>, the <a href="https://arxiv.org/abs/2310.00148">first constraints on the eccentricity of HIP 65426 b</a> (led by Sarah Blunt), and two studies I led investigating the orbits and compositions of two brown dwarfs, the chemical and mass benchmark <a href="https://arxiv.org/abs/2309.04403">HD 72946 B</a> and the youngest imaged brown dwarf with a dynamical mass measurement <a href="https://arxiv.org/abs/2312.08283">HD 136164 Ab </a>.

          ________
          ## <center>Imaging AF Lep b with JWST</center>
          ________
          <img src="/uploads/fancy_combined_f444w-removebg.png" width="25%" hspace="20" vspace="20" align="left" />

          I co-PI'd a [JWST Cycle 2 Director's Discretionary program](https://www.stsci.edu/jwst/science-execution/program-information?id=4558) with [Kyle Franson](https://kfranson.github.io) to image the [AF Leporis system](https://en.wikipedia.org/wiki/AF_Leporis). We sought to characterize the atmosphere of the giant planet AF Lep b and search the system for other, smaller gaseous planets. At a projected (on-sky) separation of 320 milliarcseconds, AF Lep b planet was incredibly challenging to detect with JWST. It was only 5 pixels away from the super bright host star AF Lep A, and partially obscured by the coronagraph we used to suppress the light from the host. Despite these technical challenges, we successfully detected the planet by leveraging the stability of the telescope's wavefront and differntial imaging strategies. The resulting brightness measurement at these long wavelengths told us that the atmosphere of the planet was very turbulent, with hot gas from the deep layers of the atmosphere being flung far, far up, into the cold upper layers of the atmosphere. You can read a press release on the paper [here](https://mcdonaldobservatory.org/news/releases/), or check out the [paper itself](https://arxiv.org/abs/2406.09528).
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
          filename: vlt_2.jpg
        image_darken: 0.75
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
      title: Outreach
      subtitle: ""
      text: |
        ## <center> Outreach Activites </center>

        Observatory Fellow, Maryland Space Grant Consortium | September 2022 - May 2023

        Volunteer, Maryland Space Grant Observatory | May 2023 - present

        Penpal, Letters to a Pre-Scientist | February 2025 - present

        Volunteer, Youth in Engineering and Astronomy, STScI | October 2022 - present

        Author, [Astrobites, the astro-ph reader's digest](https://astrobites.org/author/wbalmer/) | December 2021 - present

        Author, [personal blog](https://www.astrowill.page/) | June 2018 – present

        Astronomy Editor, [Amherst STEM Network](https://www.amherststemnetwork.com/) | October 2019 – May 2021

        ## <center> Public Talks </center>

        "How to take pictures of planets in other solar systems" North County High School, June 2023

        “[Directly Imaging Exoplanets, determining their orbits and atmospheres](https://youtu.be/5Djcbbj-HQ0?t=1893)” Howard Astronomical League, June 16th, 2022

        “[The Growth of Young Stars and Protoplanets!](https://www.balticon.org/wp56/)” Balticon 56, May 27th, 2022

        “[Adolescent astronomy: Planet formation, Direct imaging, and early-career astronomy research](https://www.astrowill.page/blog/2021/05/19/talkin-the-talk-and-presenting-the-posters/)” UMass Astronomy Club, April 20th, 2021
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
        A selection of articles written about research I'm involved in; articles on a repeated topic typically indicate I provided additional comments for that particular article. Last updated 2025/03/18.

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
          filename: paranal_22.jpg
        image_darken: 0
        image_parallax: true
        image_position: center
        image_size: cover
        text_color_light: true
      spacing:
        padding: ["50px", "0", "50px", "0"]
---
