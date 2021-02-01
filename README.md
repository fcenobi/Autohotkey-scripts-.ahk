#### Script Autohotkey .ahk

La mia raccolta di script di autohotkey. Alcuni script sono scritti da me, alcuni sono modificati da me, alcuni sono completamente creati da altri.

AutoHotkey è necessario per eseguire e / o compilare gli script. Gli script compilati possono essere eseguiti senza autohotkey installato sulla macchina dell'utente.

Per scaricare AutoHotkey, visitare http://www.autohotkey.com/
<hr>
#### Script in ordine alfabetico
 
##### [Suggerimenti dita AltTab] (AltTab% 20 Suggerimenti dita)
Aggiunge un tasto di scelta rapida che apre un menu contestuale (nella posizione corrente del cursore) con tutte le finestre aperte elencate come voci di menu.
Utilizzo: premere il tasto di scelta rapida (l'impostazione predefinita è F10) per aprire il menu contestuale.

##### [BBCodes] (BBCodes)
Aggiunge tasti di scelta rapida (che funzionano solo nei browser) per inserire rapidamente il testo selezionato nei corrispondenti tag BBCode.
Utilizzo: in un browser selezionare qualsiasi testo in un campo di testo e utilizzare qualsiasi tasto di scelta rapida per inserire il testo selezionato nei tag BBCode corrispondenti.

##### [Capitalize] (Capitalize)
Converte automaticamente in maiuscolo le lettere dopo aver premuto Invio o digitato un punto, un punto esclamativo o un punto interrogativo o tre punti.

##### [DetachVideo] (DetachVideo)
Scollega il frame di un contenitore Flash da un browser in una finestra separata (in Windows). Non funziona bene con Firefox.
Utilizzo: in un browser aprire una pagina con contenitore flash, passare il mouse su di essa e premere il tasto di scelta rapida (l'impostazione predefinita è F12).

##### [DevTools] (DevTools)
Questo è un gruppo di script che sono strumenti per sviluppatori o piccoli esempi di codice (come "best practice") per alcune attività specifiche, come lo scambio di valori di 2 variabili senza creare una terza variabile temporanea. Alcuni codici sono presi direttamente dalla documentazione ahk.

##### [DropCommand] (DropCommand)
Abilita il trascinamento della selezione dei file in una finestra di comando (li incolla come percorsi dei file).

##### [DrugWinManager] (DrugWinManager)
Uno script piuttosto pesante con molte funzioni, tutte mirate a fornire un maggiore controllo sulle finestre. Ad esempio, ti consente di scorrere le finestre inattive senza attivarle, ti consente di scorrere le barre delle applicazioni in alcuni programmi (come alcuni browser ed editor di testo) per cambiare scheda, ti consente di impostare / rimuovere il flag "sempre in primo piano" per la finestra sotto il cursore o la finestra attiva, consente di ridimensionare e spostare rapidamente la finestra attiva in una posizione predeterminata (qualsiasi metà o qualsiasi quarto dell '"area utilizzabile" dello schermo [area del monitor esclusa l'area della barra delle applicazioni]), consente di nascondere / ripristinare le barre dei titoli delle finestre o spostare la finestra inattiva senza attivarla.
Lo script utilizza molti tasti di scelta rapida, ma molti di essi per impostazione predefinita utilizzano pulsanti non standard di mouse e tastiera, quindi se il mouse e / o la tastiera non dispongono di questi pulsanti, dovrai riconfigurare quei tasti di scelta rapida.
Inoltre, la sceneggiatura contiene molte cose che probabilmente non ti interessano (quelle cose sono state scritte solo per soddisfare le mie esigenze).

##### [FastenFileUploadFromURLs] (FastenFileUploadFromURLs)
Non molte persone sanno che quando si carica un file (ad esempio, impostando un avatar sul proprio profilo su un forum), è consentito utilizzare URL che puntano ad alcuni file che non sono stati salvati localmente. Tutto ciò che serve è incollare l'URL nel campo di immissione "nome file": in tal caso, il file verrà scaricato in una cartella% temp% sul computer e verrà utilizzato il percorso locale di quel file.
Tuttavia, i sistemi operativi Windows sono piuttosto buggati e talvolta il download di un'immagine minuscola può richiedere fino a 1 minuto, che è troppo lungo.
Questo script limita semplicemente questo processo al tempo minimo richiesto per scaricare il file. Tutto ciò di cui hai bisogno è che questo script sia in esecuzione, ogni volta che incolli un URL nella finestra "Caricamento file".

##### [FlashPluginUnpacker.ahk-4FxPE] (FlashPluginUnpacker.ahk-4FxPE)
Scritto per gli utenti di Firefox Portable che necessitano dei file dll di Flash Player, ma che non vogliono installarlo nel sistema.
Inserisci questo script nella cartella "% firefoxportable% \ Data \ Plugins", scarica il plug-in Flash da <a href = "http://portableappz.blogspot.ru/2011/03/flash-1021531-10318042-plugins.html" > qui </a> e trascina semplicemente il file exe che hai scaricato sullo script.
Questo script richiede l'installazione di 7-Zip. Lo script può essere eseguito da una posizione diversa (chiederà quindi all'utente di specificare il percorso della cartella "% firefoxportable% \ Data \ Plugins" e può anche eseguire il backup di vecchie DLL. E se il processo plugin-container.exe è in esecuzione: lo script lo interrompe per sbloccare i file in uso ma che devono essere sostituiti.

##### [GoneIn60s] (GoneIn60s)
Recupera applicazioni chiuse. Caratteristiche:
- Fare clic sulla X o premere Alt-F4 per chiudere un'applicazione
- Per ripristinare, fare clic con il pulsante destro del mouse sull'icona della barra delle applicazioni e scegliere un'applicazione
- Fare doppio clic sull'icona della barra delle applicazioni per ripristinare tutte le applicazioni
- Se non viene ripristinato, scompare in 60 secondi

##### [Icona Menu Launcher] (Icona% 20Menu% 20Launcher)
Script molto breve che dimostra solo l'idea di come combinare più scorciatoie in una sola che apre un menu contestuale, in cui ogni voce di menu esegue una scorciatoia corrispondente.

##### [Biblioteche] (Biblioteche)
Queste sono le librerie, che potrebbero essere richieste da alcuni degli script.

##### [MetaDescription per Windows Explorer] (MetaDescription% 20per% 20Windows% 20Explorer)
Questo script consente di aggiungere commenti (in testo semplice o sintassi HTML) ai file. I commenti verranno archiviati in un flusso di dati alternativo collegato direttamente al file a cui aggiungi commenti. Il file commentato rimane invariato.
Utilizzo:
	Aggiungi / modifica descrizione: in Windows Explorer seleziona un file e premi il tasto di scelta rapida "Alt + F1". Verrà visualizzata una finestra con un campo di immissione in cui è possibile inserire una descrizione. Scrivi qualcosa e premi il pulsante "Salva".
	Mostra descrizione: in Windows Explorer seleziona uno o più file o non selezionare nulla, quindi premi e tieni premuto il tasto "F1": verrà visualizzata una finestra con la descrizione aggiunta in precedenza.
Questo script è un'alternativa a [descript.ion per Windows Explorer] (descript.ion per Windows Explorer) e ora puoi spostare i file come preferisci (su disco NTFS) e non preoccuparti di spostare anche la descrizione.

##### [MoveOut] (MoveOut)
Stabilisci regole per spostare i file automaticamente. Usalo per creare una regola che sposta i file dal desktop a una sottocartella, in base al tipo di file, parte di un nome di file o qualsiasi altra cosa. Chiedi di sostituire i file esistenti o di rinominarli. Può anche ignorare i file. Caratteristiche:
- Fare clic con il pulsante destro del mouse sull'icona della barra delle applicazioni per configurare
- Scegli Impostazioni per modificare regole e opzioni
- Scegli Abilita per avviare o interrompere tutte le regole

##### [Meta Shortcut] (Meta% 20Shortcut)
Una versione migliorata dello script "[Icon Menu Launcher] (Icon Menu Launcher)".
Mostra un elenco di voci di menu: se fai clic su una di esse, agiscono come scorciatoie per i file precedentemente trascinati su di essa. Lo script supporta il drag'n'drop di più file contemporaneamente.

! [icona] (https://i.imgur.com/n6GH8gX.png)

##### [MiddleClickInstantScroll] (MiddleClickInstantScroll)
Fare clic con il pulsante centrale su una posizione arbitraria sulla barra di scorrimento per scorrere istantaneamente fino a quella posizione.

##### [Non aggiornato] (Non aggiornato)
Questa cartella contiene script obsoleti, per lo più obsoleti dalle nuove realizzazioni. Non hai bisogno di nessuno di loro.

##### [PerApplicationVolumeControl] (PerApplicationVolumeControl)
Aggiunge tasti di scelta rapida per controllare il livello del volume dell'applicazione attiva (non il livello del volume generale nell'intero sistema).
L'intero script potrebbe essere ridotto a poche righe, se utilizzassi <a href="http://www.nirsoft.net/utils/nircmd.html"> NirCmd </a> (leggi il codice dello script per imparare come).

##### [QuickSaveThisScript] (QuickSaveThisScript)
Uno script che reagisce a un tasto di scelta rapida e salva rapidamente il testo selezionato in un file * .ahk e lo apre nel tuo editor di testo.

##### [Rimappa ALT + F4 in CTRL + W] (Rimappa% 20ALT% 2BF4% 20 in% 20CTRL% 2BW)
Fa funzionare il tasto di scelta rapida "Ctrl + W" come "Alt + F4" per molti programmi e finestre di sistema diversi. Mi piace Ctrl + W più di Alt + F4, poiché i tasti sono più vicini l'uno all'altro.

##### [SOT2ST] (SOT2ST)
SOT2ST sta per "Scorri sulla barra delle applicazioni per cambiare attività": sposta il cursore sulla barra delle applicazioni in Windows e fai scorrere la rotellina del mouse su / giù per passare da una finestra all'altra: quando sposterai il cursore lontano dalla barra delle applicazioni, la finestra preselezionata verrà attivata.
Questo è uno script non ancora finito ed è generalmente abbastanza difettoso al momento, non raccomandato per l'uso.

##### [ScriptManager.ahk] (ScriptManager.ahk)
Questa cartella contiene diversi gestori di script ahk.
Uno di questi è [MasterScript.ahk] (ScriptManager.ahk / MasterScript.ahk), che è un gestore di script avanzato per gli script AHK:
- ha un TreeView che ti permette di navigare tra le tue cartelle fino ai file .ahk;
- supporta il bookmarking dei percorsi dei file .ahk;
- supporta il bookmarking dei percorsi a qualsiasi cartella (per una navigazione più facile in futuro);
- traccia la connessione / disconnessione delle unità rimovibili;
- è in grado di scansionare la memoria per gli script .ahk in esecuzione per visualizzare i dati sui loro processi e per controllarli inviando loro comandi;
- ha anche una fantastica funzionalità di "Process Assistant" che ti consente di associare tutti i processi e / o script insieme in un modo molto flessibile, quindi, ad esempio, potresti fare in modo che l'esecuzione di un notepad.exe esegua anche notepadAssistantScript.ahk e a seconda il tipo di regola che hai scelto - puoi fare in modo che uccidendo calc.exe anche lo script.

##### [SilentScreenshotter] (SilentScreenshotter)
Uno screenshotter molto ascetico ma potente che ti consente di selezionare l'area di cui fare lo screenshot, quindi utilizza una compressione senza perdite per ridurre al minimo le dimensioni del file, quindi carica automaticamente lo screenshot su Imgur e infine copia (e / o apre) il percorso dello screenshot. Supporta il drag'n'drop delle immagini per caricarle su Imgur.
Lo script richiede una pre-configurazione prima di poter essere utilizzato, quindi leggi l'intestazione nel codice dello script.

##### [StandDescription] (StandDescription)
Uno script che dimostra l'idea di una GUI dinamica e di salvare / ripristinare i dati da un array o un oggetto) nel / dal formato JSON.

##### [StringyLauncher] (StringyLauncher)
Questo è un lanciatore (esegui programmi digitando parole chiave). Segue le regole specificate nel file "rules.ini".
La sintassi per questo file è la seguente:
0. È meglio impostare la tabella codici su 65001 (UTF-8).
1. Ogni regola dovrebbe essere sulla propria riga.
2. Ogni regola è composta da parola chiave + percorso. Tutti dovrebbero essere separati con tubi.
3. Per supportare l'avvio dei file direttamente dagli archivi:
	un. È necessario associare una parola chiave "archiver" all'archiver: attualmente, lo script supporta solo 7-Zip (specificare il percorso per 7z.exe) e WinRar (specificare il percorso per WinRAR.exe, UnRAR.exe o RAR.exe).
	b. La sintassi per tali regole è la seguente: ad esempio, è necessario avviare "\ archived_folder \ with \ test.exe" da "arch.rar", quindi la regola dovrebbe essere così: "parola chiave` | C: \ path \ to \ arch.rar! archived_folder \ with \ test.exe ".
Appunti:
1. Attualmente il lancio è limitato a un posto: tutti i trigger funzionano solo se sono stati digitati su "Win + R" o "Start> Esegui" (o "Пуск> Выполнить" in Windows con locale "ru"). Per rimuovere questo limite è necessario eliminare la riga "#IfWinActive, ahk_exe explorer.exe ahk_class # 32770" ma si dovrebbe considerare l'aggiunta di alcuni caratteri di chiusura alle parole chiave, altrimenti il ​​programma di avvio funzionerà subito dopo aver digitato una parola chiave.
2. È possibile specificare una cartella temporanea in cui verranno decompressi gli archivi. E puoi anche specificare di non rimuovere i file decompressi dopo aver chiuso il programma avviato che era in un archivio.

##### [TheEnd] (TheEnd)
Deseleziona il tipo di file quando rinomini i file in XP (proprio come avviene per impostazione predefinita in Windows 7).

##### [TransliterateText] (TransliterateText)
Uno script abbastanza instabile ancora. Aggiunge ru <> alla traslitterazione dell'ultima parola / riga / testo intero come qwerty <> йцукен.

##### [VDesktops] (VDesktops)
Aggiunge desktop pseudo-virtuali: in primo luogo, premi "Win + Maiusc + 0/1/2/3" per associare Windows ai desktop e poi premi "Win + 0/1/2/3" per passare a quei desktop.

##### [WinTraymin] (WinTraymin)
Fare clic con il pulsante destro del mouse sul pulsante "minimizza" per ridurre a icona una finestra in una trayicon. Un clic sinistro / centrale / destro sull'icona del vassoio ripristinerà la finestra. E se la finestra viene attivata tramite altri mezzi, verrà rimossa anche l'icona del vassoio corrispondente.

##### [descript.ion per Windows Explorer] (descript.ion% 20per% 20Windows% 20Explorer)
Questo script ti consente di ottenere i commenti dei file.
Se sono selezionati file, i commenti verranno visualizzati solo per loro, altrimenti per tutti i file nella cartella.
I commenti vengono presi dal file descript.ion che dovrebbe essere presente nella cartella.

Utilizzo:
1. Ottieni TotalCommander (o simile), seleziona un file lì, premi Ctrl + Z, aggiungi alcuni commenti al file. Questo creerà un file descript.ion (solitamente nascosto) in quella cartella.
2. Aprire la cartella del file commentato in Windows Explorer.
3. Esegui questo script e tieni premuto F1 per ottenere un suggerimento con commenti per tutti i file in quella cartella o seleziona prima i file necessari e poi ottieni commenti solo per i file selezionati.

##### [hyde] (hyde)
Quasi blackhat: hyde.dll nasconde un processo dal task manager su Windows 2000 - sistemi operativi Windows 7 x86 e x64 bit. Il tuo processo può iniettarlo in altri processi come preferisci. L'esempio utilizza SetWindowsHookEx con un hook CBT (la dll esporta un CBTProc) per iniettarlo in tutti i processi in esecuzione.

##### [pgTable] (pgTable)
Questo script ti consente di convertire una tabella copiata in una tabella con bordi pseudo-grafici.
Copia una tabella, premi F12, incolla la tabella con bordi pseudo-grafici.
Lo script ha anche impostazioni che ti consentono di specificare la spaziatura interna e l'allineamento del testo nelle celle, lo stile del bordo, se utilizzare separatori tra le righe, se aggiungere un bordo superiore, se aggiungere il bordo inferiore.
`` `
this	is	a	table
with	3 rows	and	4 columns
and it	is	absolutely	awesome
```
for example into
```
┌────────┬────────┬────────────┬───────────┐
│  this  │   is   │      a     │   table   │
├────────┼────────┼────────────┼───────────┤
│  with  │ 3 rows │     and    │ 4 columns │
├────────┼────────┼────────────┼───────────┤
│ and it │   is   │ absolutely │  awesome  │
└────────┴────────┴────────────┴───────────┘
```
or for another example into
```
╔══════╦══════╦══════════╦═════════╗
║  this║    is║         a║    table║
║  with║3 rows║       and║4 columns║
║and it║    is║absolutely║  awesome║
╚══════╩══════╩══════════╩═════════╝
```
`` `
