# progetto-pero-il-compito

questo è un progetto di visual Studio fatto a scuola che è composto di vari passaggi.
1. Preparare le 4 immagini raffiguranti tipi di frutta.
2. Memorizzare le immagini in una sottodirectory della directory del progetto.
3. Creiamo il progetto in modalità grafica (Windows Form Application).
4. La form di base su cui creare l’interfaccia viene generata automaticamente già dal programma.
5. Di norma si cambia sempre il titolo (che appare nella barra di titolo), agendo sulla proprietà Text.
6. Si fissa le dimensioni della form modificando la proprietà FormBorderStyle. Normalmente essa è al
valore Sizable, ed invece deve essere regolata al valore FixedSingle per permettere al bordo della
form di non essere ridimensionabile.
7. Disabilitare il pulsante di massimizzazione della form. Ciò può essere fatto regolando la
8. proprietà MaximizeBox a False. Di default questa proprietà è a True.
9. Si prendono tre controlli di tipo Picturebox e si trascinano sulla form. Il controllo Picturebox
permette di visualizzare immagini all’interno di esso.
10. Si ridenominano i tre controlli (nel nostro caso picBx1, picBx2 e picBx3). La proprietà per
ridenominare i controlli è la Name.
11. Ovviamente si rimensionano i controlli in modo opportuno.
12. Inserire un pulsante che comanderà i lanci delle combinazioni di tre figure. Cambiare il suo nome
ad esempio in btnLancia (proprietà Name). Dimensionarlo e posizionarlo opportunamente.
13. Modificare opportunamente la sua proprietà Text (ad esempio scrivendo in esso “Lancia”).
14. “Agganciare” ad esso, ossia associare ad esso un evento di tipo Click. Per fare ciò nella finestra
Proprietà si seleziona il pulsante con l’icona del fulmine. Appare una nuova lista di voci
corrispondenti a tutti i tipi di eventi che possono essere abbinati al pulsante.  Viene mostrata il sorgente
con la relativa routine evento pronta da essere utilizzata. A fianco dell’evento Click sulla griglia-
elenco degli eventi scrivere btnLancia_Click.
15. Selezionando le Picturebox, si cambierà il valore di un’altra proprietà in grado di ridimensionare
l’immagine caricata SizeMode, che da Normal dovrà assumere il valore di selezione StretchImage.
Questo indica che l’immagine visualizzata, se più grande o più piccola o con una dimensione di
16. diverso rapporto altezza / larghezza, rispetto al controllo Picturebox dovrà essere opportunamente
17. ridimensionata e riformattata.
18. A questo punto l’interfaccia è del tutto pronta e ora necessita scrivere il codice per completare il
progetto dal punto di vista della logica interna. Per farlo, clicco due volte su uno spazio vuoto
della form e si aprà una scheda “Form.cs”, all’interno modificare il codice come da file allegato.
