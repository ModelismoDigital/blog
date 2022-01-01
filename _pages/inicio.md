---
title: "modelismo digital"
layout: splash
permalink: /inicio/
date: 2021-12-03T12:00:00-00:00
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: https://modelismodigital.com/assets/img/header-bg.jpg
  actions:
    - label: "Acceder gratis"
      url: "https://institute-of-digital-art.teachable.com/p/introduccion-al-modelismo-digital"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Bienvenido al mundo del modelismo digital"
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: https://modelismodigital.com/assets/img/capitulos/C1_img180.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: https://modelismodigital.com/assets/img/capitulos/C2_img180.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: https://modelismodigital.com/assets/img/capitulos/C1_img180.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

<div style="padding:25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/655858613?h=656ceb1cad&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="P_00_01.mp4"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

<div class="row text-center">
    <div class="col-md-4">
        <span class="fa-stack fa-4x">
            <i class="fas fa-circle fa-stack-2x text-primary"></i>
            <i class="fas fa-subway fa-stack-1x fa-inverse"></i>
        </span>
        <h4 class="my-3">Modelos</h4>
        <p class="text-muted">Utilizar o crear modelos digitales para incluirlos en nuestros dioramas.</p>
    </div>
    <div class="col-md-4">
        <span class="fa-stack fa-4x">
            <i class="fas fa-circle fa-stack-2x text-primary"></i>
            <i class="fas fa-tree fa-stack-1x fa-inverse"></i>
        </span>
        <h4 class="my-3">Entorno</h4>
        <p class="text-muted">Crear un entorno con terrenos, vegetación, edificios, árboles donde situar los modelos.</p>
    </div>
    <div class="col-md-4">
        <span class="fa-stack fa-4x">
            <i class="fas fa-circle fa-stack-2x text-primary"></i>
            <i class="fas fa-desktop fa-stack-1x fa-inverse"></i>
        </span>
        <h4 class="my-3">Visualizar</h4>
        <p class="text-muted">Generar las imágenes, videos o visualización 3D de los modelos en su entorno.</p>
    </div>
</div>


{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
