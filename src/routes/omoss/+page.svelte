<div class="header">
  <div class="inner">
    <h1>Litt om oss!</h1>
    <div class="ommeg">
      <span class="text">
        Her på Akademiet E-sport lærer vi om hvordan bli bedre til å samarbeide innenfor E-sport. Vi spiller forskjellige spill som Valorant, Rocket League og League of Legends. Vårt Valorant lag konkurrerer i flere forskjellige turneringer. Akkurat er vi i 2. divisjon i gamer.no ligaen og skal spille en LAN-finale i Grimstad. <br><br>

        I timene lærer vi mye om kommunikasjon og samarbeid og vi jobber for å bli bedre til å spille sammen. I E-sport er det veldig viktig og ikke bli sure og formidle det du prøver å si ordentlig. Siden vi ikke kan bruke kroppsspråk og ansiktuttrykk kan det bli vanskelig og kommunisere på en effektiv måte uten å tilte hverandre. 

      </span>
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

  .ommeg {
    display: flex;
    flex-direction: row;
    align-items: center;
    background: rgba(0, 0, 0, 0.5);
    padding: 15px;
    gap: 10px;
    border-radius: 10px;
    width: 90%;
    max-width: 800px;
    font-size: 24px;
    margin-top: 10px;
  }

  @media screen and (max-width: 700px) {
    .ommeg {
      flex-direction: column;
    }
  }

  .ommeg .profile-image {
    display: flex;
    align-items: right;
    width: 300px;
    height: auto;
    border-radius: 10px;
    flex: 1;
  }
</style>
 