<section>
  <div class="container">
    
<!-- Frame Kiri -->
    <div class="frame-1">
      <h1 class="title">Our Gallery</h1>
      <div class="foto-wrapper">
        <img src="/assets/foto4.jpg" alt="">
        <img src="/assets/foto1.jpg" alt="">
        <img src="/assets/foto3.jpg" alt="">
        <img src="/assets/foto2.jpg" alt="">
      </div>
      <div class="foto-wrapper">
        <img src="/assets/foto2.jpg" alt="">
        <img src="/assets/foto3.jpg" alt="">
        <img src="/assets/foto4.jpg" alt="">
        <img src="/assets/foto1.jpg" alt="">
      </div>
      <p>"Every Love Story Is Beautiful, But Ours Is My Favorite"</p>
    </div>

<!-- Frame Kanan -->
    <div class="frame-2">
      <div class="foto-wrapper left">
        <img src="/assets/foto1.jpg" alt="">
        <img src="/assets/foto2.jpg" alt="">
        <img src="/assets/foto4.jpg" alt="">
        <img src="/assets/foto3.jpg" alt="">
      </div>
      <div class="foto-wrapper left">
        <img src="/assets/foto2.jpg" alt="">
        <img src="/assets/foto1.jpg" alt="">
        <img src="/assets/foto3.jpg" alt="">
        <img src="/assets/foto4.jpg" alt="">
      </div>
      <div class="foto-wrapper left">
        <img src="/assets/foto1.jpg" alt="">
        <img src="/assets/foto3.jpg" alt="">
        <img src="/assets/foto2.jpg" alt="">
        <img src="/assets/foto4.jpg" alt="">
      </div>
    </div>

  </div>
</section>

<style>
  .container {
    display: grid;
    width: 100%;
    background-color: #445563;
    grid-template-columns: 2fr 1.35fr;
    grid-template-rows: 1fr;
  }

  .frame-1 {
    grid-area: 1 / 1 / 2 / 2;
    display: flex;
    flex-direction: column;
    gap: 10px;
    padding: 60px 0 0 10px;

  }

  h1 {
    font-family: "Bodoni Moda", serif;
    width: 100px;
    color: white;
    font-size: 32px;
    margin-bottom: 15px;

  }

  p {
    color: white;
    font-family: 'Times New Roman', Times, serif;
    font-size: 14px;
    width: 90%;
  }

  h1, p {
    transform: translateX(-100%);
    animation: slide forwards;
    animation-timeline: view();
    animation-range: 100px 400px;
  }
  
  .frame-2 {
    grid-area: 1 / 2 / 3 / 3;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    padding: 40px 10px;
  }

  .foto-wrapper {
    width: 100%;
    height: 200px;
    display: flex;
    overflow: hidden;
    transform: translateX(-100%);
    animation: up forwards;
    animation-timeline: view();
    animation-range: 100px 400px;
    opacity: 0.5;

  }

  .foto-wrapper.left {
    width: 100%;
    height: 300px;
    display: flex;
    overflow: hidden;
    transform: translateY(100%);
    animation: up forwards;
    animation-timeline: view();
    animation-range: 100px 400px;
    opacity: 0.5;

  }

  .foto-wrapper img {
    flex-shrink: 0;
    width: 100%;
    height: 100%;
    object-position: center;
    object-fit: cover;
  }

  .foto-wrapper img {
    animation: foto-slide 30s infinite;
  }

  .foto-wrapper:nth-child(2) img {
    animation: foto-slide 30s 1s infinite;
  }

  .foto-wrapper.left:nth-child(1) img {
    animation: foto-slide 30s 2s infinite;
  }

  .foto-wrapper.left:nth-child(2) img {
    animation: foto-slide 30s 2.3s infinite;
  }

  .foto-wrapper.left:nth-child(3) img {
    animation: foto-slide 30s 2.9s infinite;
  }


  @keyframes up {
    to {
      transform: translateY(0);
      opacity: 1;
    }
  }

  @keyframes slide {
    to {
      transform: translateX(0);
    }
  }


  @keyframes foto-slide {
    0% {
      transform: translateX(0);
    }
    15% {
      transform: translateX(0);
    }
    20% {
      transform: translateX(-100%);
    }
    35% {
      transform: translateX(-100%);
    }
    40% {
      transform: translateX(-200%);
    }
    55% {
      transform: translateX(-200%);
    }
    60% {
      transform: translateX(-300%);
    }
    75% {
      transform: translateX(-300%);
    }
    80% {
      transform: translateX(-200%);
    }
    95% {
      transform: translateX(-200%);
    }
    100% {
      transform: translateX(0);
    }
}
</style>