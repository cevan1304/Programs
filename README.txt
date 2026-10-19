CEVAN APPS – balík pre GitHub Pages
=================================

Obsah balíka
------------
index.html                              Hlavný rozcestník v angličtine
apps/Campaign-Lab.html                 Campaign Lab
apps/Hypotekarna_kalkulacka.html        Hypotekárna kalkulačka
apps/Marketing_English_Trainer.html     Marketing English Trainer
apps/Vikend_spolu.html                 Víkend spolu
.nojekyll                              Statické publikovanie bez Jekyllu

Nahratie na GitHub
-----------------
1. Rozbaľte ZIP.
2. Obsah nahrajte do hlavného priečinka repozitára: index.html musí byť
   priamo v hlavnom priečinku, aplikácie v podpriečinku apps/.
3. V nastaveniach repozitára otvorte Pages a nastavte publikovanie
   z príslušnej vetvy a hlavného priečinka (/root).
4. Otvorte adresu, ktorú zobrazí GitHub Pages.

ZIP nenahrávajte ako jediný súbor. Nahrajte rozbalený obsah.
Na zobrazenie rozcestníka nie je potrebný build ani inštalácia balíkov.
Index sa dá otvoriť aj priamo z disku, ak zostane zachovaný priečinok apps/.

Aktualizácia existujúcej aplikácie
--------------------------------
Nahraďte iba jej HTML súbor v apps/ a zachovajte jeho názov.
Rozcestník potom netreba meniť, pokiaľ nemeníte názov alebo popis aplikácie.

Pridanie novej aplikácie
-----------------------
1. Nahrajte nový samostatný HTML súbor do apps/. Názov bez medzier
   a diakritiky uľahčí spravovanie odkazov.
2. V index.html v časti <div class="apps" id="apps"> skopírujte
   jednu celú kartu <a class="app ..."> ... </a>.
3. Zmeňte href na apps/Nazov_novej_aplikacie.html, potom názov, popis,
   štítky a aria-label. Môžete upraviť aj ikonu a farebnú triedu.
4. Počet aplikácií sa pri načítaní aktualizuje automaticky.
   Hodnotu v <span id="appCount"> upravte tiež, aby sedela aj bez JavaScriptu.

Dôležité k údajom aplikácií
-------------------------
Originálne súbory aplikácií sú zachované bez zmien, vrátane ich jazykov.
Presunutie z lokálneho súboru alebo inej webovej adresy na GitHub Pages
neprenáša automaticky údaje uložené v prehliadači. Ak aplikácia podporuje
zálohovanie, pred presunom si uložte zálohu a potom ju načítajte na novej adrese.
Marketing English Trainer používa voliteľný odkaz do ChatGPT; táto časť
potrebuje internet. Žiadny API kľúč sa do balíka nepridával.
