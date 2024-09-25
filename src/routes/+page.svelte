<div class="header">
  <div class="inner">
    <h1>Akademiet e-Sport</h1>
    <p></p>
  </div>

  <a class="btn contact" href="contact">Kontakt oss!</a>
</div>

<style>
  .header {
    background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
      url(https://images.unsplash.com/photo-1506104489822-562ca25152fe?q=80&w=1000&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8NGslMjBuYXR1cmV8ZW58MHx8MHx8fDA%3D);
    background-position: center;
    background-size: cover;
    height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    position: relative;
    animation: fadein 500ms ease;
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

  .header p {
    font-size: 32px;
    text-align: center;
  }

  .header .btn {
    all: unset;
    display: flex;
    line-height: 1;
    background: rgba(0, 0, 0, 0.5);
    padding: 15px;
    border-radius: 9999px;
    cursor: pointer;
  }

  .header .contact {
    position: absolute;
    bottom: 15px;
  }
</style>
