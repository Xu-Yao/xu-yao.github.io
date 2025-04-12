---
title: ""
permalink: /publications/
author_profile: true
---

{% include base_path %}

<style>
  .publication {
    display: flex;
    flex-wrap: nowrap;
    margin-bottom: 30px;
    align-items: flex-start;
    gap: 20px;
  }

  .pub-media {
    width: 300px;
    flex-shrink: 0;
    border-radius: 8px;
  }

  .pub-media img,
  .pub-media video {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 8px;
  }

  .pub-text {
    flex: 1;
    font-size: 1rem;
  }

  @media (max-width: 768px) {
    .publication {
      flex-direction: column;
    }

    .pub-media {
      width: 100%;
    }

    .pub-text {
      font-size: 0.95rem;
    }
  }

  @media (max-width: 480px) {
    .pub-text {
      font-size: 0.9rem;
    }
  }
</style>

---

<div class="publication">
  <div class="pub-media">
    <a href="https://arxiv.org/pdf/2504.07146" target="_blank">
      <img src="/images/publications/videospats.png" alt="VideoSPatS">
    </a>
  </div>
  <div class="pub-text">
    <strong>VideoSPatS: Video SPatiotemporal Splines for Disentangled Occlusion, Appearance and Motion Modeling and Editing</strong><br>
    Juan Luis Gonzalez, Xu Yao, Alex Whelan, Kyle Olszewski, Hyeongwoo Kim, Pablo Garrido<br>
    <em>CVPR 2025</em><br>
    <a href="https://juanluisg-flwls.github.io/videospats-website/">Project Page</a> |
    <a href="https://arxiv.org/pdf/2504.07146">Paper</a>
  </div>
</div>

---
<div class="publication">
  <div class="pub-media">
    <a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750579.pdf" target="_blank">
      <img src="/images/publications/stylegan_encoder_thumb.jpg" alt="StyleGAN Encoder">
    </a>
  </div>
  <div class="pub-text">
    <strong>A style-based GAN encoder for high fidelity reconstruction of images and videos</strong><br>
    Xu Yao, Alasdair Newson, Yann Gousseau, Pierre Hellier<br>
    <em>ECCV 2022</em><br>
    <a href="https://github.com/InterDigitalInc/FeatureStyleEncoder">Code</a> |
    <a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750579.pdf">Paper</a>
  </div>
</div>

<div class="publication">
  <div class="pub-media">
    <a href="https://xu-yao.github.io/videos/latent_transformer_thumb.mp4" target="_blank">
      <video autoplay muted loop playsinline>
        <source src="https://xu-yao.github.io/videos/latent_transformer_thumb.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </a>
  </div>
  <div class="pub-text">
    <strong>A Latent Transformer for Disentangled Face Editing in Images and Videos</strong><br>
    Xu Yao, Alasdair Newson, Yann Gousseau, Pierre Hellier<br>
    <em>ICCV 2021</em><br>
    <a href="https://github.com/InterDigitalInc/Latent-Transformer">Code</a> |
    <a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Yao_A_Latent_Transformer_for_Disentangled_Face_Editing_in_Images_and_ICCV_2021_paper.pdf">Paper</a>
  </div>
</div>

<div class="publication">
  <div class="pub-media">
    <a href="https://xu-yao.github.io/files/2021ICIP_Disentanglement_final_version.pdf" target="_blank">
      <img src="/images/publications/nonlinear_editing_thumb.jpg" alt="Non-linear Editing">
    </a>
  </div>
  <div class="pub-text">
    <strong>Learning Non-Linear Disentangled Editing for StyleGAN</strong><br>
    Xu Yao, Alasdair Newson, Yann Gousseau, Pierre Hellier<br>
    <em>ICIP 2021</em><br>
    <a href="https://xu-yao.github.io/files/2021ICIP_Disentanglement_final_version.pdf">Paper</a>
  </div>
</div>

<div class="publication">
  <div class="pub-media">
    <a href="https://arxiv.org/pdf/2005.04410.pdf" target="_blank">
      <img src="/images/publications/face_age_thumb.jpg" alt="Face Age Editing">
    </a>
  </div>
  <div class="pub-text">
    <strong>High Resolution Face Age Editing</strong><br>
    Xu Yao, Gilles Puy, Alasdair Newson, Yann Gousseau, Pierre Hellier<br>
    <em>ICPR 2020</em><br>
    <a href="https://github.com/InterDigitalInc/HRFAE">Code</a> |
    <a href="https://arxiv.org/pdf/2005.04410.pdf">Paper</a>
  </div>
</div>

<div class="publication">
  <div class="pub-media">
    <a href="https://arxiv.org/pdf/2005.04408.pdf" target="_blank">
      <img src="/images/publications/style_transfer_thumb.jpg" alt="Photo Style Transfer">
    </a>
  </div>
  <div class="pub-text">
    <strong>Photo Style Transfer with Consistency Losses</strong><br>
    Xu Yao, Gilles Puy, Patrick Pérez<br>
    <em>ICIP 2019</em><br>
    <a href="https://arxiv.org/pdf/2005.04408.pdf">Paper</a>
  </div>
</div>


<!-- [A style-based gan encoder for high fidelity reconstruction of images and videos](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750579.pdf)  
Xu Yao, Alasdair Newson, Yann Gousseau, Pierre Hellier \
*ECCV 2022* [[code](https://github.com/InterDigitalInc/FeatureStyleEncoder)]

[A Latent Transformer for Disentangled Face Editing in Images and Videos](https://openaccess.thecvf.com/content/ICCV2021/papers/Yao_A_Latent_Transformer_for_Disentangled_Face_Editing_in_Images_and_ICCV_2021_paper.pdf)  
Xu Yao, Alasdair Newson, Yann Gousseau, Pierre Hellier \
*ICCV 2021* [[code](https://github.com/InterDigitalInc/Latent-Transformer)]

[Learning Non-Linear Disentangled Editing for StyleGAN](https://xu-yao.github.io/files/2021ICIP_Disentanglement_final_version.pdf)  
Xu Yao, Alasdair Newson, Yann Gousseau, Pierre Hellier \
*ICIP 2021*

[High Resolution Face Age Editing](https://arxiv.org/pdf/2005.04410.pdf)  
Xu Yao, Gilles Puy, Alasdair Newson, Yann Gousseau, Pierre Hellier \
*ICPR 2020* [[code](https://github.com/InterDigitalInc/HRFAE)]

[Photo Style Transfer with Consistency Losses](https://arxiv.org/pdf/2005.04408.pdf)  
Xu Yao, Gilles Puy, Patrick Pérez \
*ICIP 2019*  -->