<section>
  <div class="container overflow-hidden">
    <div class="frame-rsvp-wishes">
      <div class="frame-rsvp">
        <div class="title">
          <h2>RSVP</h2>
          <p>Isi Buku Tamu Online Pernikahan kami</p>
        </div>

        <form action="">
          <input type="text" name="nama" id="nama" placeholder="Masukkan Nama">
          <input type="text" name="alamat" id="alamat" placeholder="Masukkan Nama">
          <select name="kehadiran" id="kehadiran">
            <option value="Pasti hadir">Saya Pasti Hadir</option>
            <option value="Akan hadir">Saya Akan Hadir</option>
            <option value="Tidak hadir">Saya Tidak Hadir</option>
          </select>
          <button>Krim Sekarang</button>
        </form>
      </div>

      <div class="frame-wishes">
        <div class="title">
          <h2>Wishes</h2>
          <p>Berikan Ucapan & Do'a Terbaik Untuk kami</p>
        </div>

        <div class="wishes">
          <h3>53 Comments</h3>
          <form action="">
            <input type="text" placeholder="Nama">
            <textarea name="Ucapan" id="Ucapan" placeholder="Ucapan"></textarea>
            <button>Kirim</button>
          </form>

          <div class="Chat">
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<style>

/* CONTAINER */
  .container {
    width: 100%;
    padding: 50px 15px;
  }

  .frame-rsvp-wishes {
    width: 100%;
    padding: 30px 15px;
    background-color: #051d30;
    border-radius: 20px;
  }

/* FRAME RSVP */
  .frame-rsvp {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    gap: 15px;
    margin-bottom: 50px;
  }

  .title h2 {
    font-family: "wasted-vindey", sans-serif;
    font-size: 30px;
    color: white;
  }

  p {
    font-size: 14px;
    color: white;
    width: 160px;
    font-family: 'AbhayaLibre', sans-serif;
  }

  .frame-rsvp input {
    width: 100%;
    padding: 8.4px 10px;
    border-radius: 4px;
    background-color: white;
  }

  .frame-rsvp select {
    width: 100%;
    padding: 8.4px 10px;
    border-radius: 4px;
    background-color: white;
  }

  .frame-rsvp button {
    background-color: black;
    border-radius: 20px;
    width:100%;
    padding: 8px;
    color: white;
    font-weight: bolder;
    cursor: pointer;
  }

  .frame-rsvp form {
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 10px;
  }


  /* FRAME WISHES */
  .wishes {
    color: rgb(0, 0, 0);
    display: flex;
    flex-direction: column;
    align-self: center;
    background-color: #eff2f6;
    border-radius: 10px;
    height: 526px;
  }

  .wishes h3 {
    color:#495e98 ;
    font-weight: bold;
    font-size: 14px;
    text-align: center;
    padding: 13px;
    border-bottom: solid 1px rgba(0, 0, 0, 0.119);

  }
  .title {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    margin-bottom: 30px;
  }

  .wishes form {
    padding: 15px;
    width: 100%;
    border-bottom: solid 1px rgba(0, 0, 0, 0.119);
    padding-bottom: 50px;
  }

  .wishes form input {
    background-color: white;
    border: solid 1px rgba(0, 0, 0, 0.115);
    width: 100%;
    padding: 7px 10px;
    border-radius: 10px;
    margin-bottom: 15px;
  }

  .wishes form textarea {
    background-color: white;
    border: solid 1px rgba(0, 0, 0, 0.115);
    width: 100%;
    padding: 7px 10px;
    border-radius: 10px;
    margin-bottom: 15px;
  }

  .wishes button {
    font-size: 14px;
    font-weight:  bold;
    padding: 5.5px 25px;
    background-color: #3b5998;
    cursor: pointer;
    border-radius: 5px;
    color: white;

  }

</style>