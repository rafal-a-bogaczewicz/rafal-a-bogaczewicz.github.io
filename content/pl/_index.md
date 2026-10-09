---
title: ""
---

<style>
  /* Kontener główny - na desktopie rządek, na mobilkach kolumna */
  .intro-container {
    display: flex;
    flex-direction: row;
    gap: 16px; 
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
    height: 70px; 
    width: auto;
    transition: all 0.3s ease;
  }

  /* KONTROLA WIDOCZNOŚCI LOGO */
  /* Domyślnie (tryb jasny): Pokazuj normalne logo, ukryj wersję dark */
  .logo-umk-dark {
    display: none !important;
  }
  .logo-umk-light {
    display: block !important;
    mix-blend-mode: multiply; /* Usuwa ewentualne białe tło z niedoskonałego pliku */
  }

  /* TRYB CIEMNY: Ukryj jasne logo, pokaż natywne ciemne logo */
  [data-theme="dark"] .logo-umk-light {
    display: none !important;
  }
  [data-theme="dark"] .logo-umk-dark {
    display: block !important;
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
        <!-- Obie wersje logotypu osadzone jednocześnie, sterowane klasami CSS -->
        <img src="/images/logoUMK.png" alt="Logo UMK" class="uni-logo-img logo-umk-light">
        <img src="/images/logoUMK-dark.png" alt="Logo UMK" class="uni-logo-img logo-umk-dark">
    </a>
  </div>
  
    
<div class="intro-text">
    Fizyk teoretyk na&nbsp;<a href="https://www.umk.pl/" class="pub-link" target="_blank">Uniwersytecie Mikołaja Kopernika w Toruniu</a>.<br>
    Jako postdok w zespole naukowym <a href="https://fizyka.umk.pl/~karolina/index.html" class="pub-link" target="_blank">dr&nbsp;hab.&nbsp;Karoliny Słowik</a> badam optyczne&nbsp;właściwości&nbsp;nanostruktur&nbsp;2D.
  </div>
</div>

<span class="cv-style-header" style="display: block; border-bottom: 1px solid var(--gorska-zielen); margin-top: 35px; margin-bottom: 15px; font-size: 1.1em; font-weight: bold; text-transform: uppercase; letter-spacing: 0.5px;">Zainteresowania naukowe</span>

*   optyka kwantowa ciała stałego
*   dekoherencja i&nbsp;dynamika fononowa w&nbsp;układach kwantowych
*   kwantowe układy otwarte

<span class="cv-style-header" style="display: block; border-bottom: 1px solid var(--gorska-zielen); margin-top: 35px; margin-bottom: 15px; font-size: 1.1em; font-weight: bold; text-transform: uppercase; letter-spacing: 0.5px;">Kontakt i profile naukowe</span>

**e-mail:** rafalabogaczewicz<span>@</span>proton.me

<a href="https://scholar.google.com/citations?hl=pl&user=PLex6OUAAAAJ" class="pub-link" target="_blank">GoogleScholar</a> | <a href="https://orcid.org/0000-0001-7148-5250" class="pub-link" target="_blank">ORCID</a> | <a href="https://www.researchgate.net/profile/Rafal_Bogaczewicz" class="pub-link" target="_blank">ResearchGate</a> | <a href="https://pwr-wroc.academia.edu/Rafa%C5%82Bogaczewicz" class="pub-link" target="_blank">Academia.edu</a> | <a href="https://www.linkedin.com/in/rafa%C5%82-bogaczewicz-21a32a385/" class="pub-link" target="_blank">LinkedIn</a>

Katedra&nbsp;Mechaniki&nbsp;Kwantowej | Instytut&nbsp;Fizyki | Uniwersytet&nbsp;Mikołaja&nbsp;Kopernika&nbsp;w&nbsp;Toruniu

Grudziądzka 5, 87-100 Toruń
