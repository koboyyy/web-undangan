<section>
  <div class="container">
    <div class="title">Our Story</div>

    <div class="wrapper">
      <div class="foto" style="background-image: url('/assets/Story1.jpg');"></div>
      <div class="sub-title">Awal Cerita</div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum natus nulla similique provident ullam fugit molestiae omnis suscipit voluptate non architecto, ipsa adipisci cumque quo distinctio pariatur ex accusamus modi.</p>
    </div>

    <div class="wrapper">
      <div class="foto" style="background-image: url('/assets/Story2.jpg');"></div>
      <div class="sub-title">Awal Cerita</div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum natus nulla similique provident ullam fugit molestiae omnis suscipit voluptate non architecto, ipsa adipisci cumque quo distinctio pariatur ex accusamus modi.</p>
    </div>

    <div class="wrapper">
      <div class="foto" style="background-image: url('/assets/Story3.jpg');"></div>
      <div class="sub-title">Awal Cerita</div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum natus nulla similique provident ullam fugit molestiae omnis suscipit voluptate non architecto, ipsa adipisci cumque quo distinctio pariatur ex accusamus modi.</p>
    </div>
    
  </div>
</section>

<style>
  section {
    width: 100%;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    width: 100%;
    min-height: 100vh;
    background-color: #051d30;
    display: flex;
    align-items: center;
    flex-direction: column;
    gap: 20px;
    padding: 50px;
    box-sizing: border-box;
  }

  .title {
    color: white;
    font-size: 30px;
    font-family: "wasted-vindey", sans-serif;
    text-align: center;
  }

  .sub-title {
    font-family: "AbhayaLibre", sans-serif;
    color: white;
    font-size: 20px;
  }

  p {
    font-size: 14px;
    font-family: "AbhayaLibre", serif;
    color: white;
    max-width: 600px; /* Membatasi lebar teks untuk keterbacaan */
  }

  .wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 14px;
    text-align: center;
    max-width: 600px; /* Membatasi lebar wrapper */
  }

  .foto {
    width: 330px;
    height: 185px;
    border-radius: 20px;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat; /* Perbaikan typo dari 'none' ke 'no-repeat' */
  }

  .foto, .sub-title, p {
    transform: translateY(100%);
    opacity: 0.5;
    animation: slide linear forwards;
    animation-timeline: view();
    animation-range: 50px 500px;
  }

  @keyframes slide {
    to {
      transform: translateY(0);
      opacity: 1;
    }
  }

  /* Media query untuk perangkat mobile */
  @media (max-width: 768px) {
    .container {
      padding: 20px;
    }

    .foto {
      width: 100%;
      max-width: 300px;
      height: 150px;
    }

    .title {
      font-size: 24px;
    }

    .sub-title {
      font-size: 18px;
    }

    p {
      font-size: 12px;
    }
  }
</style>