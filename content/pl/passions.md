---
title: "Pasje"
date: 2026-01-18
slug: "passions"
---

<p style="text-align: center; font-size: 1.1em; margin-bottom: 40px; color: var(--text-color);">
    Nie samą fizyką teoretyczną żyje <i>Pasjonat odkrywania świata</i>, lecz ma też inne zainteresowania:
</p>

1. **Podróże i zwiedzanie miast** — poznawanie historii i architektury.  
   > *„Kto podróżował, pełen jest zaradności, a kto ma wielkie doświadczenie, mądrze przemawiać będzie.” (Syr 34, 9)*

<!-- SEKCJA FOTO: RESPONSYWNY GRID POD CYTATEM -->
<div class="passions-grid">
    <div class="passion-item">
        <img src="/images/sansebastian.webp" alt="San Sebastian o zmierzchu" class="img-responsive">
        <p class="img-caption">
            San Sebastian — zwiedzanie miasta po 
            <a href="/conferences/#conf-1" class="pub-link">konferencji (nr 1)</a>.
        </p>
    </div>
    <div class="passion-item">
        <img src="/images/lot.webp" alt="Zatoka Biskajska z lotu ptaka" class="img-responsive">
        <p class="img-caption">
            Widok na Zatokę Biskajską w drodze powrotnej.
        </p>
    </div>
</div>

2. **Rower i góry** — trening charakteru, samodyscypliny i pokory wobec sił natury. Cisza szczytów to przestrzeń niezbędna do pracy intelektualnej.

3. **Pływanie i snorkeling** — odkrywanie złożoności podwodnego świata i zachwyt nad precyzją stworzenia.

<!-- UKŁAD NAPRZEMIENNY Z LINIAMI ODDZIELAJĄCYMI -->
<div style="display: grid; grid-template-columns: 1fr 1.2fr; gap: 30px; align-items: center; margin-bottom: 50px; margin-top: 40px; border-bottom: 1px solid var(--gray-ref); padding-bottom: 30px;" class="passions-grid-alt">
    <div>
        <h4 style="color: var(--gorska-zielen); margin-top: 0;">Ląd i wytrzymałość</h4>
        <p>Rower oraz góry to droga do samokontroli i budowania wewnętrznej dyscypliny.</p>
    </div>
    <img src="/images/gory.jpg" alt="Góry" class="img-responsive">
</div>

<div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 30px; align-items: center; margin-bottom: 50px; border-bottom: 1px solid var(--gray-ref); padding-bottom: 30px;" class="passions-grid-alt">
    <img src="/images/rafa.jpg" alt="Rafa koralowa" class="img-responsive">
    <div>
        <h4 style="color: var(--gorska-zielen); margin-top: 0;">Uważność i detal</h4>
        <p>Eksploracja podwodnego świata uczy dostrzegania systemów, które na pierwszy rzut oka pozostają ukryte.</p>
    </div>
</div>

### Oczarowanie tajemnicą

Mam też inne pasje, ale...

<div class="values-header" style="margin-top: 30px; border-left: 3px solid var(--gorska-zielen); padding-left: 20px;">
    <div class="quote-text">
        „Najpiękniejszą rzeczą, jakiej możemy doświadczyć, jest oczarowanie tajemnicą.”
    </div>
    <div class="quote-ref">— Albert Einstein</div>
</div>

<style>
    /* Stylowanie gridu dla zdjęć pod podróżami */
    .passions-grid {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
        margin-top: 20px;
        margin-bottom: 40px;
    }
    /* Stylowanie gridu dla pasji naprzemiennych */
    .passions-grid-alt {
        display: grid;
        gap: 30px;
    }
    .img-responsive {
        width: 100%;
        height: auto;
        max-width: 100%;
        border-radius: 8px;
        border: 3px solid var(--gorska-zielen);
        display: block;
    }
    .img-caption {
        font-size: 0.85em;
        font-style: italic;
        margin-top: 8px;
        color: var(--gray-quote);
        text-align: center;
    }
    /* Responsywność dla smartfonów (poniżej 600px) */
    @media (max-width: 600px) {
        .passions-grid, .passions-grid-alt {
            grid-template-columns: 1fr !important;
        }
        /* Na smartfonie w pasjach naprzemiennych tekst zawsze nad zdjęciem */
        .passions-grid-alt div {
            order: 1;
        }
        .passions-grid-alt img {
            order: 2;
        }
    }
</style>
