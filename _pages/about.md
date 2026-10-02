---
layout: about
title: About
permalink: /
subtitle: PhD student in Outburst Floods | Hydrodynamics | Erosion and deposit process

profile:
  align: right
  image: zewen1.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>• PhD Student</p>
    <p>• University of Chinese Academy of Sciences</p>
    <p>• Institute of Mountain Hazards and Environment, CAS, Chengdu, China</p>
    <p>• Joint PhD Student, Geo3BCN–CSIC, Barcelona, Spain</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # set to true to show news on the homepage
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false # set to true to show recent blog posts on the homepage
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

My research focuses on outburst floods and their geomorphic impacts. I’m especially interested in how erosion and deposition under rapidly changing, unsteady flow conditions can quickly reshape river channels over short timescales.

I mainly study catastrophic outburst floods on Earth, and I also extend this work to planetary environments such as Mars. By combining numerical modeling, flume experiments, and field investigations, I analyze how outburst floods shape the landscape across different spatial and temporal scales. Through studying the interactions between flow, sediment, and the riverbed, I aim to better understand how extreme flood events control landform evolution, and more broadly, how extreme hydrodynamic processes influence the evolution of planetary surfaces.


**Affiliation: Institute of Mountain Hazards and Environment, Chinese Academy of Sciences**

<section class="research-landscapes" aria-labelledby="research-landscapes-title">
  <h2 id="research-landscapes-title">Research Landscapes</h2>

  <div class="research-landscapes-grid">
    <figure class="research-landscape-card">
      <img src="/assets/img/research-glacier-lake-breach.jpg" alt="Glacier lake and surrounding snow-covered mountains" loading="lazy">
      <figcaption>Glacier Lake breach</figcaption>
    </figure>

    <figure class="research-landscape-card">
      <img src="/assets/img/research-river-morphodynamics.jpg" alt="Gravel-bed mountain river and surrounding valley" loading="lazy">
      <figcaption>Outburst-Flood River Morphology</figcaption>
    </figure>

    <figure class="research-landscape-card">
      <img src="/assets/img/research-outburst-flood-deposits.jpg" alt="Thick deposits shaped by an outburst flood" loading="lazy">
      <figcaption>Outburst flood deposits</figcaption>
    </figure>

    <figure class="research-landscape-card">
      <img src="/assets/img/research-martian-outburst-floods.jpg" alt="Reconstruction of a lake and outflow channels on Mars" loading="lazy">
      <figcaption>Martian Outburst Flood</figcaption>
    </figure>
  </div>
</section>

<style>
  .research-landscapes {
    clear: both;
    margin: 2.5rem 0 3rem;
  }

  .research-landscapes h2 {
    margin-bottom: 1.25rem;
  }

  .research-landscapes-grid {
    display: grid;
    grid-template-columns: repeat(4, minmax(0, 1fr));
    gap: 1rem;
    position: relative;
  }

  .research-landscape-card {
    position: relative;
    min-width: 0;
    margin: 0;
    aspect-ratio: 4 / 3;
    overflow: hidden;
    border-radius: 8px;
    background: #222;
    z-index: 0;
  }

  .research-landscape-card::after {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(to top, rgba(0, 0, 0, 0.78) 0%, rgba(0, 0, 0, 0.08) 55%, transparent 75%);
    pointer-events: none;
    transition: opacity 0.2s ease;
  }

  .research-landscape-card img {
    position: relative;
    z-index: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 8px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    will-change: transform;
  }

  .research-landscape-card figcaption {
    position: absolute;
    left: 1rem;
    right: 1rem;
    bottom: 0.85rem;
    z-index: 1;
    color: #fff;
    font-size: 1rem;
    font-weight: 700;
    line-height: 1.25;
    text-shadow: 0 1px 3px rgba(0, 0, 0, 0.65);
    transition: opacity 0.2s ease;
  }

  .social .contact-note {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    column-gap: 3rem;
    row-gap: 0.4rem;
  }

  .social .contact-detail {
    white-space: nowrap;
  }

  @media (hover: hover) and (pointer: fine) {
    .research-landscape-card {
      cursor: zoom-in;
    }

    .research-landscape-card:hover {
      z-index: 20;
      overflow: visible;
    }

    .research-landscape-card:hover img {
      transform: scale(4);
      box-shadow: 0 18px 42px rgba(0, 0, 0, 0.38);
    }

    .research-landscape-card:first-child img {
      transform-origin: left center;
    }

    .research-landscape-card:last-child img {
      transform-origin: right center;
    }
  }

  @media (max-width: 900px) {
    .research-landscapes-grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 900px) and (hover: hover) and (pointer: fine) {
    .research-landscape-card:nth-child(odd) img {
      transform-origin: left center;
    }

    .research-landscape-card:nth-child(even) img {
      transform-origin: right center;
    }
  }

  @media (max-width: 576px) {
    .research-landscapes-grid {
      grid-template-columns: 1fr;
    }
  }
</style>
