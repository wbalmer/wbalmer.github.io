---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
# new section, presentations
  - block: markdown
    id: presentations
    content:
      title: Research Presentations
      subtitle: ''
      text: |
        Selected invited talks or conference proceedings. Where possible I've included links to slides or posters associated with my presentations. Last updated 2023/08/23

        "A missing link? First look at the L-T transition planet AF Lep b with VLTI/GRAVITY and JWST/NIRCam" ESO Star and Planet Formation Seminar, Nov. 21st, 2023

        "[The Unexpected Detection of HR 8799 e [with JWST] and Implications for Cycle 3](https://cloudproject.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=0f015e1d-f571-4698-9323-b00c017d9772)" STScI Spring Symposium, May 18th, 2023

        "Optical Interferometry of Exoplanets & Brown Dwarfs" American Museum of Natural History Astrophysics Colloqium, February 14th, 2023

        "[Optical Interferometry of Exoplanets & Brown Dwarfs](https://www.facebook.com/watch/live/?ref=watch_permalink&v=1197586477467689)" STScI HotSci Talk Series, August 17th, 2022

        "[Unprecedented precision: using VLTI/GRAVITY jointly with Gaia to characterize substellar companions near and far, young and old](https://www.astrowill.page/wp-content/uploads/2022/07/wbalmer_coolstars_splinter_slides.pdf)" Cool Stars 21 (talk), July 2022, Toulouse

        "[The orbit and Hα variability of HD 142527B](https://www.astrowill.page/wp-content/uploads/2022/07/hd142527B_wbalmer_coolstars_poster.pdf)" Cool Stars 21 (poster), July 2022, Toulouse

        "[CHARACTERIZATION OF THE L‑TYPE BROWN DWARF COMPANION TO THE NEARBY SOLAR‑TYPE STAR HD 72946 WITH VLTI/GRAVITY, VLT/SPHERE, AND RVS](https://www.astrowill.page/wp-content/uploads/2022/06/wbalmer_Lyot22_poster_final.pdf)"

        "[The orbit and Hα variability of HD 142527B](https://www.astrowill.page/wp-content/uploads/2021/05/wbalmer_stsciposter_final-scaled.jpg)" STScI Spring Symposium, April 19th-24th, 2021
    design:
      background:
        image: 
          filename: veil.jpg
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
# new section, presentations
  - block: markdown
    id: press-and-reporting
    content:
      title: In the Press
      subtitle: ''
      text: |
        Articles I’ve written or been interviewed for. Last updated 2023/10/12.

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

        “[Reaching for the Stars: William Balmer Thesis Spotlight](https://www.amherststemnetwork.com/post/reaching-for-the-stars-william-balmer-thesis-spotlight)” by Sarah Lapean in *The Amherst STEM Network* on May 14th, 2021.

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
