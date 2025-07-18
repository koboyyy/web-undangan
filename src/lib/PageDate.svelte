<section>
  <div class="content">
      <div class="title">Save The Date</div>
      <div class="date">
        <div>
          <p>0</p>
          <p>Hari</p>
        </div>
        <div>
          <p>0</p>
          <p>Jam</p>
        </div>
        <div>
          <p>0</p>
          <p>Menit</p>
        </div>
        <div>
          <p>0</p>
          <p>Detik</p>
        </div>
      </div>
  </div>
</section>

<style>
  .content {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 15px;
    border-radius: 10px;
    backdrop-filter: blur(2px); /* Inti blur-nya */
    background-color: transparent;
    color: white;
    padding: 10px;
  }

  .title {
    font-family: "Bodoni Moda", serif;
    font-size: 24px;
    color: rgb(255, 255, 255);
  }

  .date {
    display: flex;
    gap: 6px;
  }

  .date div {
    font-family: "Domine", serif;
    font-size: 0.7em;
    color: white;
    padding: 5px 14px;
    border-radius: 10px;
    background-color: rgba(8, 59, 35, 0.273);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
</style>