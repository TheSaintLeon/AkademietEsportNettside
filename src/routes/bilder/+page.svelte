<div class="header">
  <div class="inner">
    <h1>Andre ting jeg har gjort</h1>
    <div class="portofolio">
      <div class="row">
        <div class="section">
          <span class="text">Bro Michael</span>
          <img
            src="/MichaelBro.jpg"
            class="profile-image"
            alt="Bro michael"
          />
        </div>
        <div class="section">
          <span class="text">Kirke i Oslo</span>
          <img
            src="/OsloKirk.jpg"
            class="profile-image"
            alt="Kirke i oslo"
          />
        </div>
        <div class="section">
          <span class="text">Teknisk museum</span>
          <img
            src="/BilMuseum.jpg"
            class="profile-image"
            alt="teknisk museum"
          />
        </div>
      </div>
      <div class="row">
        <div class="section">
          <span class="text">Snø</span>
          <img src="/snø.png" class="profile-image" alt="tekisn museum" />
        </div>
        <div class="section">
          <span class="text">Glitredumpa</span>
          <img src="/natur.png" class="profile-image" alt="Glitredumpa" />
        </div>
      </div>
    </div>
  </div>
</div>

<style>
  .header {
    background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
      url(https://images.unsplash.com/photo-1506104489822-562ca25152fe?q=80&w=1000&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8NGslMjBuYXR1cmV8ZW58MHx8MHx8fDA%3D);
    background-position: center;
    background-size: cover;
    height: 100%;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
    animation: fadeout 500ms ease;
  }

  @keyframes fadein {
    from {
      opacity: 0;
    }

    to {
      opacity: 1;
    }
  }

  .inner {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    animation: appear 1000ms ease;
    margin-top: 100px;
  }

  @keyframes appear {
    from {
      transform: translateY(-20%);
      opacity: 0;
    }

    to {
      transform: translateY(0%);
      opacity: 1;
    }
  }

  .header h1 {
    font-size: 64px;
    text-align: center;
    margin: 0 10px;
  }

  .portofolio {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    background: rgba(0, 0, 0, 0.5);
    padding: 15px;
    border-radius: 10px;
    font-size: 24px;
    margin-top: 10px;
    color: white;
    gap: 20px;
    margin-bottom: 20px;
  }

  .row {
    display: flex;
    gap: 20px;
  }

  .portofolio .section {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100%;
  }

  .portofolio .text {
    text-align: center;
  }

  .portofolio .profile-image {
    display: flex;
    align-items: center;
    width: 300px;
    height: auto;
    border-radius: 10px;
    flex: 1;
    object-fit: cover;
  }

  @media screen and (max-width: 1000px) {
    .portofolio .profile-image {
      width: 28vw;
    }
  }

  @media screen and (max-width: 700px) {
    .row {
      flex-direction: column;
      gap: 20px;
    }

    .portofolio .profile-image {
      width: 300px;
    }
  }
</style>
