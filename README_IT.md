<h1 align="center">Benvenuti nella pagina di Frads! 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&pause=1000&color=4CAF50&center=true&vCenter=true&width=650&lines=Studente+Magistrale+in+Ingegneria+Informatica;Realta%27+Estesa%2C+Aumentata+e+Virtuale;Computer+Vision+e+Grafica+3D" alt="Typing SVG" />
</p>

<!--
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Frads01&label=Visualizzazioni%20Profilo&color=4CAF50&style=flat-square" alt="Visualizzazioni Profilo" />
  <img src="https://img.shields.io/github/followers/Frads01?label=Follower&style=flat-square&color=4CAF50" alt="GitHub Follower" />
</p>
-->

<p align="center">
  <a href="mailto:francescodisanto14@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/francesco-di-santo-1b6ab7261/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/Frads01/Frads01/blob/main/cv_eng.pdf"><img src="https://img.shields.io/badge/CV%20(Inglese)-4CAF50?style=for-the-badge&logo=googledocs&logoColor=white" alt="CV Inglese"></a>
  <a href="https://github.com/Frads01/Frads01/blob/main/cv_ita.pdf"><img src="https://img.shields.io/badge/CV%20(Italiano)-4CAF50?style=for-the-badge&logo=googledocs&logoColor=white" alt="CV Italiano"></a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,cs,rust,c,cpp,java,js,ts,react" alt="Le mie competenze" />
  </a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=unity,blender,opencv,vscode,pycharm,rider,clion,idea,windows,linux" alt="Le mie competenze" />
  </a>
</p>

> [!NOTE]
> <i>Il README per questo profilo è attualmente in fase di sviluppo. Nel frattempo, puoi dare un'occhiata ai progetti a cui ho contribuito qui sotto!</i>

## 📖 Indice

* [ℹ️ Chi sono!](#chi-sono)
* [🚀 Progetti In Evidenza](#progetti-in-evidenza)
  * [👀 Verifica Facciale — Landmark Geometrici vs. Neural Embeddings](#verifica-facciale)
  * [🚗 DriveAcademyVR — Simulatore VR per Scuola Guida](#driveacademyvr)
  * [🎵 Riduzione del Rumore nei Brani senza Dati di Addestramento Puliti](#riduzione-rumore)
  * [📹 Canoa Slalom — Analisi delle Prestazioni Video](#canoa-slalom)
  * [🏛️ My Museum Adventure — Guida Museale Gamificata](#museum-adventure)
  * [🕹️ Grafica al Calcolatore: Modellazione 3D e Applicazione Grafica Interattiva](#grafica-al-calcolatore)
  * [↔️ Screen-Casting Multi-Piattaforma](#screen-casting)
  * [📚 TaskLass: Piattaforma Web Full-Stack per la Gestione e Valutazione dei Compiti Scolastici](#tasklass)

<a id="chi-sono"></a>

## ℹ️ Chi sono!

Studente magistrale in Ingegneria Informatica presso il **Politecnico di Torino**, specializzato in Grafica al Calcolatore e Multimedia. I miei principali interessi riguardano **Realtà Estesa/Virtuale, Grafica e Modellazione 3D, Computer Vision, Elaborazione delle Immagini, Elaborazione Audio e Machine Learning applicato a questi settori**.

Attualmente sto completando una tesi di laurea sulla valutazione degli stati cognitivi in ambienti XR attraverso interfacce cervello-computer (BCI) attive e passive.

<a id="progetti-in-evidenza"></a>

## 🚀 Progetti in evidenza

<!--
<p align="center">
  <a href="#verifica-facciale">Verifica Facciale</a> •
  <a href="#driveacademyvr">DriveAcademyVR</a> •
  <a href="#riduzione-rumore">Riduzione Rumore</a> •
  <a href="#canoa-slalom">Canoa Slalom</a> •
  <a href="#museum-adventure">Museum Adventure</a> •
  <a href="#grafica-al-calcolatore">Grafica al Calcolatore</a> •
  <a href="#screen-casting">Screen-Casting</a> •
  <a href="#tasklass">TaskLass</a>
</p>
-->

<a id="verifica-facciale"></a>

### 👀 [Verifica Facciale — Landmark Geometrici vs. Neural Embeddings](https://github.com/SalvatoreGiugliano98/FaceVerification)

<p>
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/AR_Foundation-000000?style=flat-square&logo=apple&logoColor=white" alt="AR Foundation">
</p>

Questo progetto valuta due metodi di verifica facciale integrati in un'applicazione iOS sviluppata con Unity, C# e AR Foundation: un approccio geometrico 3D e un approccio neurale 2D. L'approccio 3D acquisisce nuvole di punti TrueDepth tramite ARKit per misurare le distanze euclidee normalizzate tra 17 landmark anatomici (su 1.220 punti tracciati). L'approccio 2D utilizza ArcFace (backbone ResNet-100) sul motore Barracuda di Unity per confrontare embedding a 512 dimensioni da immagini RGB tramite la similarità del coseno. L'applicazione offre rilevamento facciale in tempo reale, visualizzatore facciale 3D, test in parallelo delle due pipeline, registrazione delle misurazioni biometriche ed esportazione in CSV. I risultati sperimentali su oltre 100 test hanno mostrato che il metodo 3D ha raggiunto un'accuratezza complessiva del 97,12% e un richiamo (recall) del 100%, mentre il modello ArcFace ha ottenuto una precisione del 100%.

<p align="center">
  <img src="https://github.com/Frads01/Frads01/blob/main/imgs/sg3d.bmp" alt="Anteprima Verifica Facciale" width="50%">
</p>

<br>

<a id="driveacademyvr"></a>

### 🚗 [DriveAcademyVR — Simulatore VR per Scuola Guida](https://github.com/SalvatoreGiugliano98/DriveAcademyVR)

<p align="center">
  <a href="https://www.youtube.com/watch?v=g6p-ZQi5erc">
    <img src="https://github.com/Frads01/Frads01/blob/main/imgs/driveacademy.png" alt="Video DriveAcademyVR" width="50%">
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/Meta_Quest_3-0081FB?style=flat-square&logo=meta&logoColor=white" alt="Meta Quest 3">
</p>

Drive Academy VR è un simulatore di scuola guida in realtà virtuale sviluppato per il visore Meta Quest 3. Fornisce un ambiente immersivo e privo di rischi in cui gli utenti possono esercitarsi nella guida, imparare le regole del traffico e ricevere indicazioni vocali in tempo reale da un istruttore virtuale. Realizzato con una fisica dei veicoli realistica, il sistema presenta un abitacolo completamente interattivo dove gli utenti azionano manualmente comandi come volante, cambio, frecce, freno a mano e cinture di sicurezza, supportato da un'interfaccia utente diegetica integrata nel cruscotto. Inserita in una città a griglia popolata da traffico e pedoni, l'applicazione traccia le prestazioni, fornisce feedback visivi, uditivi e aptici immediati sulle infrazioni e include un modulo tutorial introduttivo.

<p align="center">
  <img src="https://github.com/Frads01/Frads01/blob/main/imgs/driveacademy_examp.png" alt="Anteprima DriveAcademyVR" width="50%">
</p>

<br>

<a id="riduzione-rumore"></a>

### 🎵 [Riduzione del Rumore nei Brani senza Dati di Addestramento Puliti](https://github.com/Frads01/mlvm-noise-remover)

<p align="center">
  <img src="https://via.placeholder.com/800x400?text=Anteprima+Riduzione+Rumore" alt="Anteprima Riduzione del Rumore" width="100%">
</p>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
</p>

In questo progetto è stata sviluppata una pipeline di denoiser audio basata su deep learning basata su un'architettura Deep Complex U-Net a 20 livelli (DCUNet-20) per rimuovere il rumore dalla musica senza richiedere dati di addestramento puliti. Adottando il paradigma Noise2Noise, la rete è stata addestrata esclusivamente su coppie di segnali audio rumorosi generati combinando tracce del dataset MUSDB18 con eventi sonori ambientali e gaussiani presi da UrbanSound8K. L'implementazione opera direttamente su spettrogrammi STFT (Short-Time Fourier Transform) a valori complessi per preservare sia le informazioni di ampiezza che di fase. Tra gli aspetti tecnici salienti figurano le convoluzioni complesse, la batch normalization complessa, l'inizializzazione complessa dei pesi basata sulla distribuzione di Rayleigh e l'ottimizzazione del gradiente tramite una funzione di perdita WSDR (Weighted Signal-to-Distortion Ratio). Il sistema finale ottimizzato ha ottenuto un miglioramento medio del rapporto segnale-rumore (SNR) di +7,54 dB, superando i modelli baseline orientati al parlato sui segnali musicali.

<br>

<a id="canoa-slalom"></a>

### 📹 [Canoa Slalom — Analisi delle Prestazioni Video](https://github.com/Frads01/ipcv-canoa)

<p align="center">
  <img src="https://via.placeholder.com/800x400?text=Anteprima+Canoa+Slalom" alt="Anteprima Canoa Slalom" width="100%">
</p>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
</p>

Questo progetto è stato sviluppato per il corso di Elaborazione delle Immagini e Visione Artificiale presso il Politecnico di Torino per analizzare le prestazioni nella Canoa Slalom. Realizzato in Python e OpenCV, il sistema applica tecniche di computer vision per tracciare la canoa e rilevare le porte da slalom in flussi video dinamici, affrontando sfide quali riflessi dell'acqua e movimenti della telecamera. Le funzionalità principali includono il rilevamento e la segmentazione delle porte, il tracciamento dell'atleta e dell'imbarcazione, la valutazione automatizzata del tocco o del salto delle porte e l'elaborazione ottimizzata dei fotogrammi. Sfruttando tecniche come operazioni morfologiche, rilevamento dei contorni e flusso ottico, il progetto applica la teoria dell'image processing all'analisi sportiva reale.

<br>

<a id="museum-adventure"></a>

### 🏛️ [My Museum Adventure — Guida Museale Gamificata](https://github.com/SalvatoreGiugliano98/my-museum-adventure-main)

<p align="center">
  <img src="https://via.placeholder.com/800x400?text=Anteprima+My+Museum+Adventure" alt="Anteprima My Museum Adventure" width="100%">
</p>

<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=android&logoColor=white" alt="Jetpack Compose">
</p>

Sviluppata per il corso di Interazione Uomo-Macchina presso il Politecnico di Torino, My Museum Adventure è un'applicazione Android progettata per rendere gamificata la visita ai musei attraverso sfide interattive a tema. Gli utenti scelgono percorsi narrativi (es. Avventura, Fantasy, Fantascienza) e risolvono indovinelli per scoprire opere d'arte, guadagnando medaglie e obiettivi lungo il percorso. Le caratteristiche chiave includono la scansione delle opere tramite fotocamera gestita da API esterne di riconoscimento immagini per verificare le risposte, mappe interattive crowdsourced per la navigazione e descrizioni dettagliate con audioguide multilingua. Dal punto di vista tecnico, l'app è realizzata in Kotlin e Jetpack Compose, integrando Room per l'archiviazione locale offline, CameraX, OkHttp per le chiamate API e Jetpack Navigation.

<br>

<a id="grafica-al-calcolatore"></a>

### 🕹️ [Grafica al Calcolatore: Modellazione 3D e Applicazione Grafica Interattiva](https://github.com/SalvatoreGiugliano98/Computer-Graphics)

<p align="center">
  <img src="https://via.placeholder.com/800x400?text=Anteprima+Grafica+al+Calcolatore" alt="Anteprima Grafica al Calcolatore" width="100%">
</p>

<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" alt="OpenGL">
  <img src="https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white" alt="Blender">
</p>

Questo progetto è stato sviluppato per il corso di Grafica al Calcolatore con l'obiettivo di implementare i principi fondamentali del rendering 3D, della modellazione e del calcolo visivo interattivo. È composto da un'applicazione 3D interattiva in tempo reale creata con librerie grafiche a basso livello come OpenGL, affiancata da una scena 3D modellata su Blender mediante tecniche di fisica. L'applicazione presenta un ambiente 3D navigabile con controlli per la telecamera, trasformazioni geometriche, gestione dello grafo della scena, illuminazione dinamica (Phong/Blinn-Phong), mappatura delle texture e shader personalizzati, mettendo in connessione i concetti matematici con la programmazione grafica pratica.

<br>

<a id="screen-casting"></a>

### ↔️ [Screen-Casting Multi-Piattaforma](https://github.com/Frads01/pds-screencast)

<p align="center">
  <img src="https://via.placeholder.com/800x400?text=Anteprima+Screen-Casting+Multi-Piattaforma" alt="Anteprima Screen-Casting Multi-Piattaforma" width="100%">
</p>

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white" alt="FFmpeg">
</p>

Sviluppata per il corso di Programmazione di Sistema presso il Politecnico di Torino, questa applicazione PC multipiattaforma scritta in Rust consente la condivisione dello schermo in tempo reale su Windows, macOS e Linux tramite multicast IPv4. Costruita con un'interfaccia grafica intuitiva in egui, supporta due ruoli principali:
- **Mittente (Sender):** Configura IP/porta e selezione del monitor, fornendo controlli in tempo reale per mettere in pausa la condivisione, inviare una schermata bianca vuota, disegnare annotazioni (rettangoli, frecce), condividere una regione specifica dello schermo o interrompere lo streaming (con supporto a scorciatoie da tastiera come Ctrl+P, Ctrl+B, Ctrl+D, Ctrl+S, Ctrl+Q). Include la gestione del fallback nel caso in cui un monitor venga scollegato.
- **Ricevitore (Receiver):** Si connette tramite indirizzo IPv4 e porta, mettendo a disposizione opzioni di uscita dalla sessione e registrazione dello schermo integrata tramite ffmpeg (con download automatico se non preinstallato).

<br>

<a id="tasklass"></a>

### 📚 [TaskLass: Piattaforma Web Full-Stack per la Gestione e Valutazione dei Compiti Scolastici](https://github.com/Frads01/progetto-webapp1)

<p align="center">
  <img src="https://via.placeholder.com/800x400?text=Anteprima+TaskLass" alt="Anteprima TaskLass" width="100%">
</p>

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express">
</p>

TaskLass è un'applicazione web full-stack sviluppata per l'esame di Applicazioni Web 1, pensata per digitalizzare l'assegnazione, la consegna e la valutazione dei compiti a casa. L'applicazione gestisce due ruoli utente distinti: insegnanti, che possono creare compiti per specifici gruppi di studenti e valutare i lavori consegnati, e studenti, che possono visualizzare gli incarichi, inviare le soluzioni e monitorare la propria media voti calcolata lato server. L'architettura prevede un frontend reattivo sviluppato in React con React Router, basato su componenti modulari per dashboard separate, affiancato da un backend Node.js/Express che espone API REST dotate di autenticazione basata su sessione e gestione strutturata degli errori HTTP. I dati vengono salvati in un database relazionale configurato con relazioni molti-a-molti. Tra le competenze acquisite durante lo sviluppo rientrano la modellazione di schemi relazionali, la progettazione di API REST autenticate, la gestione della concorrenza lato client e la strutturazione di un'interfaccia utente basata su componenti.

<div align="center">

> *Mi fa sempre piacere parlare di grafica, XR o di qualsiasi argomento legato alla computer vision — non esitare a contattarmi!* 🤗

</div>

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Fatto%20con-%E2%9D%A4-red?style=flat-square" alt="Fatto con amore">
  &nbsp;
  <a href="#"><img src="https://img.shields.io/badge/⬆%20Torna%20su-4CAF50?style=flat-square" alt="Torna su"></a>
</p>
