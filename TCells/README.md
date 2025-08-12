---
layout: default
title: Results Gallery
---

<style>
/* simple, responsive cards */
.gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px,1fr)); gap: 16px; }
.row { margin: 28px 0 8px; }
.card { background: var(--card-bg,#fff); border: 1px solid #dfe2e5; border-radius: 12px; padding: 8px; }
.card img { width: 100%; height: auto; display: block; border-radius: 8px; }
.card figcaption { font-size: 12px; text-align: center; margin-top: 6px; color: #57606a; }
.centerwide { display:flex; justify-content:center; }
.hero { text-align:center; margin: 10px 0 24px; }
@media (prefers-color-scheme: dark){
  :root{ --card-bg:#0d1117; }
  .card{ border-color:#30363d; }
  .card figcaption{ color:#8b949e; }
}
details summary { cursor:pointer; font-weight:600; margin:8px 0 12px; }
</style>

<div class="hero">
  <h1>Signature T-cell States — Results Gallery</h1>
  <p>UMAPs, marker panels, exhaustion/Treg scores, and supporting figures.</p>
</div>

<h3>Row 1 — Overview</h3>
<div class="gallery row">
  <figure class="card">
    <a href="https://github.com/user-attachments/assets/f3a0eeeb-975a-409d-b278-9ef856a2be2e">
      <img loading="lazy" alt="UMAP" src="https://github.com/user-attachments/assets/f3a0eeeb-975a-409d-b278-9ef856a2be2e">
    </a>
    <figcaption>UMAP — T cell landscape</figcaption>
  </figure>
  <figure class="card">
    <a href="https://github.com/user-attachments/assets/08f96436-6816-4f41-8ccd-253960beaf4d">
      <img loading="lazy" alt="Marker genes" src="https://github.com/user-attachments/assets/08f96436-6816-4f41-8ccd-253960beaf4d">
    </a>
    <figcaption>Marker genes by subtype</figcaption>
  </figure>
</div>

<h3>Row 2 — Fig 2 + Fig 3</h3>
<div class="gallery row">
  <figure class="card">
    <a href="https://github.com/user-attachments/assets/b137d846-dff3-4225-95df-eade647db32e">
      <img loading="lazy" alt="Fig 2" src="https://github.com/user-attachments/assets/b137d846-dff3-4225-95df-eade647db32e">
    </a>
    <figcaption>Fig 2</figcaption>
  </figure>
  <figure class="card">
    <a href="https://github.com/user-attachments/assets/2e11ddd0-60e2-43ca-9494-62a5cd78f006">
      <img loading="lazy" alt="Fig 3" src="https://github.com/user-attachments/assets/2e11ddd0-60e2-43ca-9494-62a5cd78f006">
    </a>
    <figcaption>Fig 3</figcaption>
  </figure>
</div>

<h3>Row 3 — Tex + Treg + Fig 4</h3>
<div class="gallery row">
  <figure class="card">
    <a href="https://github.com/user-attachments/assets/6d4e1a4c-5aae-474a-8e68-b31f063e0a27">
      <img loading="lazy" alt="Tex score" src="https://github.com/user-attachments/assets/6d4e1a4c-5aae-474a-8e68-b31f063e0a27">
    </a>
    <figcaption>CD8 Tex score</figcaption>
  </figure>
  <figure class="card">
    <a href="https://github.com/user-attachments/assets/042e316f-8570-4ac1-b0f1-b1f5a7691107">
      <img loading="lazy" alt="Treg score" src="https://github.com/user-attachments/assets/042e316f-8570-4ac1-b0f1-b1f5a7691107">
    </a>
    <figcaption>Treg score</figcaption>
  </figure>
  <figure class="card">
    <a href="https://github.com/user-attachments/assets/895fe05e-fdd3-414e-8bde-532c98cbf3b9">
      <img loading="lazy" alt="Fig 4" src="https://github.com/user-attachments/assets/895fe05e-fdd3-414e-8bde-532c98cbf3b9">
    </a>
    <figcaption>Fig 4</figcaption>
  </figure>
</div>

<h3>Row 4 — Fig 5</h3>
<div class="centerwide row">
  <figure class="card" style="max-width: 900px; width:100%;">
    <a href="https://github.com/user-attachments/assets/dad051ce-04d8-4481-ac8b-268da4cf7bab">
      <img loading="lazy" alt="Fig 5" src="https://github.com/user-attachments/assets/dad051ce-04d8-4481-ac8b-268da4cf7bab">
    </a>
    <figcaption>Fig 5</figcaption>
  </figure>
</div>
