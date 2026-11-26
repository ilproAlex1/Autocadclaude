# Misure Forme

App web per disegnare forme col dito (o col mouse), inserire le misure e calcolare automaticamente **aree**, **perimetri** e **volumi**, con computo metrico in PDF.

**Apri l'app:** https://ilproalex1.github.io/Autocadclaude/

## Cosa fa

- **Cartelle e sottocartelle** per organizzare i disegni (rinomina, elimina, duplica).
- **Strumenti 2D:** linee, mano libera e **Forme**: rettangolo, quadrato, cerchio, ellisse, ovale, semicerchio, quarto di cerchio, settore, segmento circolare, semiluna, corona circolare, mezza corona, triangoli (3 lati, equilatero, isoscele, rettangolo), trapezi, parallelogramma, rombo, pentagono, esagono, ottagono, poligono regolare, stella, forme a L, T e U.
- **Misure:** tocca un lato (o una forma) e scrivi la misura in mm, cm, m o km. Cambiare unità cambia solo l'etichetta: i numeri restano quelli (4 cm → 4 m) e il disegno resta identico.
- **Forme composte:** se due forme si toccano lungo un lato, tocca quel lato e scegli “Elimina questa linea e unisci” (oppure seleziona una forma → “Unisci con un’altra forma”): diventano un’unica forma con la sua area.
- **Selezione:** tocca un lato per selezionare solo quel lato (arancione) e scriverne la misura; tocca dentro la forma per selezionarla tutta. Con un lato selezionato, “Elimina” toglie solo quel lato.
- **Ruota forma:** seleziona una forma e premi “⟳ Ruota”: la giri dell'angolo che vuoi (cursore, gradi scritti a mano o pulsanti ±1°, ±15°, ±90°) attorno al suo centro; le misure restano uguali. “Annulla” la rimette com'era.
- **Calamita:** spostando una forma vicino a un’altra, si attacca da sola agli angoli e ai lati (anche i punti che disegni si attaccano ai lati).
- **Stessa forma con qualsiasi misura:** se scrivi la prima misura (5 cm, 5 m o 5 km) la forma sullo schermo resta identica; cambia solo la scala. La prima misura di ogni nuova forma la ingrandisce o rimpicciolisce tutta insieme, senza deformarla.
- **Disegno sempre visibile:** qualunque misura scrivi (anche 25 km) il disegno resta della stessa grandezza sullo schermo; cambiano solo le proporzioni.
- **Misure solo tue:** l'app non propone le misure degli altri lati; i lati senza misura mostrano “?” finché non le scrivi.
- **Solidi uniti (3D):** tocca un solido, premi “Unisci”, tocca il secondo e scegli dove attaccarlo: diventano un unico solido senza parete interna.
- **Linee riprese:** ripartendo dall’estremo di una linea aperta la si continua; collegando i due estremi la forma si chiude.
- **Zoom illimitato** con due dita, rotella o pulsanti.
- **3D:** solidi (parallelepipedo, cubo, cilindro, tubo, cono, tronco di cono, sfera, semisfera, calotta, ellissoide, piramide, tronco di piramide, prismi, toro) ed **estrusione** di una forma del disegno 2D. Volume in m³ e litri.
- **Computo metrico PDF:** descrizione per ogni voce, disegno in scala, tabella di superfici e volumi con i totali.
- **Account:** aperta da claude.ai, ogni persona salva i propri disegni nel proprio account (privati) e li ritrova su tutti i dispositivi. Backup esportabile/importabile in .json.

## Note

- È un unico file (`index.html`), senza dipendenze: funziona anche aprendolo con doppio clic.
- Aperta da GitHub Pages o dal file, i disegni restano nel browser del dispositivo (usa il backup per spostarli).
