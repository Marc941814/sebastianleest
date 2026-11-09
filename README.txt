Sebastian's Leesavontuur – versie 8 (fase 1)

INHOUD
- De bestaande leesapp v7 als technische basis.
- Overzichtsomgeving met acht plekken: vier actieve oefenlocaties en vier nog niet actieve toekomstige plekken.
- De vier actieve locaties zijn gekoppeld aan de herkenningspunten op de goedgekeurde oefenachtergronden:
  * Boekenrots – Lees maar!
  * Lichtgevende grot – Flits maar!
  * Schelpenplek – Spel maar!
  * Koraalpoort – Sleep maar!
- Sebastian staat één keer in de overzichtsomgeving.
- De zes goedgekeurde Sebastian-poses zijn als afzonderlijke PNG-bestanden opgenomen in images/sebastian/; de oorspronkelijke posekaart blijft eveneens bewaard.
- De vier door de gebruiker goedgekeurde oefenachtergronden zijn ongewijzigd opgenomen in images/oefenachtergronden/.
- De vier uitsneden van de herkenningspunten worden alleen gebruikt als kleine visuele verwijzingen in de overzichtsomgeving.

NOG NIET OPGENOMEN IN DEZE FASE
- De nieuwe, uitbundige welkomstpagina met naamveld en persoonlijke begroeting.
- De nieuwe vormgeving van de binnenkant van de vier oefeningen.
- Definitieve invulling/activering van de vier toekomstige plekken.

INSTALLATIE
Plaats alle bestanden en mappen uit deze bundel in de hoofdmap van de bestaande GitHub Pages-repository en overschrijf de bestaande bestanden. Laat de map images volledig intact. Commit en push daarna de wijzigingen. Herlaad de app daarna met Ctrl+F5; bij een geïnstalleerde PWA kan het nodig zijn de app eenmaal opnieuw te openen zodat de nieuwe service-worker-cache wordt geactiveerd.

CONTROLE
Test de overzichtsomgeving op desktop en tablet, controleer de vier actieve routes, de vier niet-actieve plekken en offline laden. De bestaande oefeningen, woordenbank en instellingen zijn behouden.


Versie 8 – fase 1 (achtergrond overzichtsomgeving)
De goedgekeurde achtergrond voor de overzichtsomgeving staat in images/overview-background.png en wordt lokaal gecachet voor offline gebruik. De bestaande kaartindeling en navigatie zijn in deze stap nog niet opnieuw vormgegeven.

Versie 8 – overzichtsomgeving update
De overzichtsomgeving gebruikt de goedgekeurde doorlopende achtergrond. Acht locatieknoppen zijn als interactieve elementen over het landschap geplaatst; vier openen de bestaande oefeningen en vier zijn nog niet actief. Sebastian verschijnt één keer met de goedgekeurde begroetingspose. De onderste footerbanner is verwijderd. De oefenomgevingen zelf zijn nog niet opnieuw vormgegeven.

Onderhoud: underwater-footer.jpg is verwijderd; deze afbeelding wordt niet meer gebruikt door de app en staat niet meer in de offlinecache.
