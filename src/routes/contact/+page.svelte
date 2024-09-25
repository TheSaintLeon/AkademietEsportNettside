<div class="header">
  <div class="inner">
    <h1>Kontakt Oss!</h1>
    <div class="contact">
      <a href="mailto:kundeservice.esport@akademiet.no">kundeservice.esport@akademiet.no</a>
      <p class="gray-text">DETTE ER EN ELEVSTYRT NETTSIDE OG HAR IKKE NOE Å GJØRE MED AKADEMIET LEDELSE</p>
    </div>
  </div>
</div>

<style>
  .header {
    background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
      url(https://images.unsplash.com/photo-1506104489822-562ca25152fe?q=80&w=1000&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8NGslMjBuYXR1cmV8ZW58MHx8MHx8fDA%3D);
    background-position: center;
    background-attachment: fixed;
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
  }

  .contact {
    display: flex;
    flex-direction: column;
    align-items: center;
    background: rgba(0, 0, 0, 0.5);
    padding: 15px;
    border-radius: 10px;
    width: 100%;
    max-width: 800px;
    font-size: 24px;
    margin-top: 10px;
  }

  .contact a {
    color: white;
  }

  .gray-text {
    color: gray;
    text-align: center;
  }
</style>
