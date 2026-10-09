---
title: ""
---





<style>
  /* Kontener główny - na desktopie rządek, na mobilkach kolumna */
  .intro-container {
    display: flex;
    flex-direction: row;
    gap: 16px; /* Zwiększony odstęp między pojedynczym logo a tekstem dla lepszego balansu */
    align-items: flex-start;
    margin-bottom: 20px;
  }

  /* Kontener na pojedyncze logo */
  .uni-logo-wrapper {
    display: flex;
    align-items: center;
    flex-shrink: 0;
  }

  .no-wrap {
    white-space: nowrap;
    display: inline-block;
  }
  
  /* Tekst zajmuje dostępną przestrzeń */
  .intro-text {
    flex: 1;
  }

  /* Wysokość logotypu */
  .uni-logo-img {
    height: 58px; 
    width: auto;
    transition: all 0.3s ease;
  }

  /* LOGO UMK: Wygładzający cień dla lepszej widoczności na skrajnych tłach */
  .logo-umk {
    filter: drop-shadow(0px 0px 1px rgba(0,0,0,0.2));
  }

  /* TRYB CIEMNY */
  /* Jeśli logo UMK w wersji bazowej słabo kontrastuje z ciemnym tłem, 
     delikatnie podbijamy jego jasność */
  [data-theme="dark"] .logo-umk {
    filter: drop-shadow(0px 0px 2px rgba(255,255,255,0.3)) brightness(1.1);
  }

  @media (max-width: 800px) {
    .intro-container {
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
    .uni-logo-wrapper {
      margin-bottom: 12px;
    }
    .intro-text {
        text-align: left;
    }
  }
</style>

<div class="intro-container">
  <div class="uni-logo-wrapper">
    <a href="https://umk.pl" target="_blank">
        <img src="/images/logoUMK.png" alt="Logo UMK" class="uni-logo-img logo-umk">
    </a>
  </div>

<div class="intro-text">
    Fizyk teoretyk na&nbsp;<a href="https://pwr.edu.pl" class="pub-link" target="_blank">Politechnice Wrocławskiej</a>.<br>
    W zespole <a href="https://www.pm.kft.pwr.edu.pl" class="pub-link" target="_blank">prof.&nbsp;Pawła Machnikowskiego</a> badam rezonansową&nbsp;fluorescencję emiterów&nbsp;kwantowych.
  </div>
</div>

<span class="cv-style-header" style="display: block; border-bottom: 1px solid var(--gorska-zielen); margin-top: 35px; margin-bottom: 15px; font-size: 1.1em; font-weight: bold; text-transform: uppercase; letter-spacing: 0.5px;">Zainteresowania naukowe</span>

*   optyka kwantowa ciała stałego
*   dekoherencja i&nbsp;dynamika fononowa w&nbsp;układach kwantowych
*   kwantowe układy otwarte

<span class="cv-style-header" style="display: block; border-bottom: 1px solid var(--gorska-zielen); margin-top: 35px; margin-bottom: 15px; font-size: 1.1em; font-weight: bold; text-transform: uppercase; letter-spacing: 0.5px;">Kontakt i profile naukowe</span>

**e-mail:** rafal.bogaczewicz<span>@</span>pwr.edu.pl

<div class="flex-row">
<span class="no-wrap"> <a href="https://scholar.google.com/citations?hl=pl&user=PLex6OUAAAAJ" class="pub-link" target="_blank">GoogleScholar</a> | <a href="https://orcid.org/0000-0001-7148-5250" class="pub-link" target="_blank">ORCID</a> | <a href="https://www.researchgate.net/profile/Rafal_Bogaczewicz" class="pub-link" target="_blank">ResearchGate</a> | <a href="https://pwr-wroc.academia.edu/Rafa%C5%82Bogaczewicz" class="pub-link" target="_blank">Academia.edu</a> | <a href="https://www.linkedin.com/in/rafa%C5%82-bogaczewicz-21a32a385/" class="pub-link" target="_blank">LinkedIn</a> </span> </div>

<div class="flex-row">
  <span class="no-wrap"> Katedra&nbsp;Mechaniki&nbsp;Kwantowej | Instytut&nbsp;Fizyki | Uniwersytet&nbsp;Mikołaja&nbsp;Kopernika&nbsp;w&nbsp;Toruniu
 </span>
</div>

Grudziądzka 5, 87-100 Toruń
