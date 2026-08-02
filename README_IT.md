<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=4CAF50&height=180&section=header&text=Ciao%20Mondo,%20sono%20Francesco!&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=&descAlignY=55" width="100%"/>
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&pause=1000&color=4CAF50&center=true&vCenter=true&width=650&lines=Studente+Magistrale+in+Ingegneria+Informatica;Realt%C3%A0+Estesa,+Aumentata+%26+Virtuale;Computer+Vision+%26+Grafica+3D" alt="Typing SVG" />

<a href="mailto:francescodisanto14@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://www.linkedin.com/in/francesco-di-santo-1b6ab7261/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://github.com/Frads01/Frads01/blob/main/cv_eng.pdf"><img src="https://img.shields.io/badge/CV%20(Inglese)-4CAF50?style=for-the-badge&logo=googledocs&logoColor=white" alt="CV English"></a>
<a href="https://github.com/Frads01/Frads01/blob/main/cv_ita.pdf"><img src="https://img.shields.io/badge/CV%20(Italiano)-4CAF50?style=for-the-badge&logo=googledocs&logoColor=white" alt="CV Italian"></a>

<br>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=python,cs,rust,c,cpp,java,js,ts,react" alt="My Skills" />
</a>
<br>
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=unity,blender,opencv,vscode,pycharm,rider,clion,idea,windows,linux" alt="My Skills" />
</a>

</div>

<!--
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Frads01&label=Profile%20Views&color=4CAF50&style=flat-square" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/Frads01?label=Followers&style=flat-square&color=4CAF50" alt="GitHub Followers" />
</p>
-->

<br>

> [!NOTE]
> <i>Il README di questo profilo è attualmente in costruzione. Nel frattempo, puoi dare un'occhiata ai progetti a cui ho contribuito qui sotto!</i>

<div>

## ℹ️ Chi sono!

Studente magistrale in Ingegneria Informatica al **Politecnico di Torino**, specializzato in **Computer Graphics & Multimedia**.

I miei principali interessi e aree di focus:
- 🥽 **Realtà Estesa, Aumentata & Virtuale**
- 🎨 **Grafica e Modellazione 3D**
- 👁️ **Computer Vision & Elaborazione delle Immagini**
- 🎵 **Elaborazione Audio & Segnali**
- 🤖 **Machine Learning applicato a Vision e Multimedia**

*Attualmente sto completando una tesi magistrale sulla valutazione degli stati cognitivi in ambienti XR tramite interfacce cervello-computer attive e passive.*

---

## 🚀 Progetti in evidenza

- [👀 Facial Verification — Landmark Geometrici vs. Neural Embeddings](#facial-verification)
- [🚗 DriveAcademyVR — Simulatore di Scuola Guida VR](#driveacademyvr)
- [🎵 Riduzione del Rumore in Brani Musicali Senza Dati di Training Puliti](#noise-reduction)
- [📹 Canoa Slalom — Analisi Video delle Performance](#canoa-slalom)
- [🏛️ My Museum Adventure — Guida Museale Gamificata](#museum-adventure)
- [🕹️ Computer Graphics: Modellazione 3D & Applicazione Grafica Interattiva](#computer-graphics)
- [↔️ Screen-Casting Multi-Piattaforma](#screen-casting)
- [📚 TaskLass: Piattaforma Web Full-Stack per la Gestione dei Compiti Scolastici](#tasklass)
- [🧱 Quoridor — Gioco da Tavolo Embedded](#quoridor)

---

<a id="facial-verification"></a>
### 👀 [Facial Verification — Landmark Geometrici vs. Neural Embeddings](https://github.com/SalvatoreGiugliano98/FaceVerification)

<p>
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/AR_Foundation-000000?style=flat-square&logo=apple&logoColor=white" alt="AR Foundation">
</p>

Questo progetto valuta due metodi di verifica facciale integrati in un'applicazione iOS realizzata con Unity, C# e AR Foundation: un **Approccio Geometrico 3D** e un **Approccio Neurale 2D**.

- **Approccio 3D:** Cattura point cloud TrueDepth tramite ARKit per misurare distanze Euclidee normalizzate su 17 landmark anatomici (a partire da 1.220 punti tracciati).
- **Approccio 2D:** Utilizza ArcFace (backbone ResNet-100) sul motore Barracuda di Unity per confrontare embedding a 512 dimensioni ricavati da immagini RGB tramite similarità del coseno.

L'applicazione offre rilevamento facciale in tempo reale, un visualizzatore 3D del volto, test live su doppia pipeline, logging delle misurazioni biometriche ed esportazione CSV. I risultati sperimentali su oltre 100 test hanno mostrato che il metodo 3D ha raggiunto un'**accuratezza complessiva del 97,12%** e un **recall del 100%**, mentre il modello ArcFace ha ottenuto una **precisione del 100%**.

<p align="center">
  <img src="imgs/sg3d.bmp" alt="Facial Verification Preview" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="driveacademyvr"></a>
### 🚗 [DriveAcademyVR — Simulatore di Scuola Guida VR](https://github.com/SalvatoreGiugliano98/DriveAcademyVR)

<p>
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/Meta_Quest_3-0081FB?style=flat-square&logo=meta&logoColor=white" alt="Meta Quest 3">
</p>

Drive Academy VR è un simulatore di scuola guida in realtà virtuale sviluppato per il visore **Meta Quest 3**. Offre un ambiente immersivo e privo di rischi in cui esercitarsi alla guida, imparare le regole del traffico e ricevere indicazioni vocali in tempo reale da un istruttore virtuale.

Costruito con una fisica veicolare realistica, il sistema presenta un abitacolo completamente interattivo in cui l'utente aziona manualmente i comandi (volante, cambio, frecce, freno a mano, cintura), supportato da una UI diegetica integrata nel cruscotto. Operando all'interno di una città a griglia popolata da traffico e pedoni, l'applicazione monitora le prestazioni, fornisce feedback visivo, sonoro e aptico immediato sulle infrazioni, e include un modulo tutorial introduttivo.

<p align="center">
  <img src="imgs/driveacademy_examp.png" alt="DriveAcademyVR Preview 1" width="49%" style="border-radius: 6px;" />
  <img src="imgs/driveacademy_examp3.png" alt="DriveAcademyVR Preview 2" width="49%" style="border-radius: 6px;" />
</p>

---

<a id="noise-reduction"></a>
### 🎵 [Riduzione del Rumore in Brani Musicali Senza Dati di Training Puliti](https://github.com/Frads01/mlvm-noise-remover)

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
</p>

Una pipeline di deep learning per il denoising audio, costruita con un'architettura Deep Complex U-Net a 20 livelli (**DCUNet-20**), per rimuovere il rumore da brani musicali senza richiedere dati di training puliti.

Adottando il paradigma **Noise2Noise**, la rete è stata addestrata esclusivamente su coppie di segnali audio rumorosi, generati combinando tracce del dataset MUSDB18 con eventi sonori ambientali e gaussiani da UrbanSound8K. L'implementazione opera direttamente su spettrogrammi STFT (Short-Time Fourier Transform) a valori complessi, per preservare sia l'informazione di magnitudine sia quella di fase.

- **Aspetti tecnici principali:** Convoluzioni complesse, batch normalization complessa, inizializzazione dei pesi complessa basata sulla distribuzione di Rayleigh, e ottimizzazione tramite loss WSDR (Weighted Signal-to-Distortion Ratio).
- **Risultati:** Miglioramento medio del rapporto segnale-rumore (SNR) di **+7,54 dB**, superando i modelli baseline orientati al parlato su segnali musicali.

<p align="center">
  <img src="imgs/dcunet20.png" alt="Noise Reduction Spectrogram" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="canoa-slalom"></a>
### 📹 [Canoa Slalom — Analisi Video delle Performance](https://github.com/Frads01/ipcv-canoa)

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
</p>

Sviluppato per il corso di Image Processing and Computer Vision al Politecnico di Torino per analizzare le performance nella Canoa Slalom. Realizzato con Python e OpenCV, il sistema applica tecniche di computer vision per tracciare la canoa e rilevare le porte di slalom in flussi video dinamici, gestendo criticità come i riflessi sull'acqua e il movimento della camera.

- **Funzionalità principali:** Rilevamento e segmentazione delle porte, tracking di atleta e imbarcazione, valutazione automatica di porte toccate o mancate, ed elaborazione ottimizzata dei fotogrammi.
- **Tecniche impiegate:** Operazioni morfologiche, contour detection e optical flow per l'analisi sportiva nel mondo reale.

<p align="center">
  <img src="imgs/CanoaSlalom.png" alt="Canoa Slalom Preview" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="museum-adventure"></a>
### 🏛️ [My Museum Adventure — Guida Museale Gamificata](https://github.com/SalvatoreGiugliano98/my-museum-adventure-main)

<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=android&logoColor=white" alt="Jetpack Compose">
</p>

Sviluppata per il corso di Human-Computer Interaction al Politecnico di Torino, **My Museum Adventure** è un'app Android pensata per gamificare le visite museali attraverso quest interattive a tema.

Gli utenti scelgono percorsi narrativi (Avventura, Fantasy, Sci-Fi) e risolvono enigmi per scoprire le opere d'arte, guadagnando medaglie.

- **Funzionalità:** Scansione delle opere tramite fotocamera con API esterne di riconoscimento immagini, mappe interattive crowdsourced per la navigazione, e descrizioni dettagliate con audioguide multilingua.
- **Stack tecnologico:** Kotlin, Jetpack Compose, Room (storage offline), CameraX, OkHttp e Jetpack Navigation.

<p align="center">
  <img src="imgs/MyMuseumAdventure.png" alt="My Museum Adventure Preview" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="computer-graphics"></a>
### 🕹️ [Computer Graphics: Modellazione 3D e Applicazione Grafica Interattiva](https://github.com/SalvatoreGiugliano98/Computer-Graphics)

<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" alt="OpenGL">
  <img src="https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white" alt="Blender">
</p>

Realizzato per il corso di Computer Graphics, questo progetto implementa i principi fondamentali del rendering 3D, della modellazione e del computing visivo interattivo.

Consiste in un'applicazione di gioco in tempo reale costruita con OpenGL, affiancata da una scena 3D realistica modellata in Blender con tecniche di simulazione fisica.

- **Funzionalità:** Trasformazioni geometriche, gestione dello scene graph, illuminazione dinamica (Phong/Blinn-Phong), texture mapping e shader personalizzati.

<p align="center">
  <img src="imgs/ScenaCompleta.png" alt="3D Graphics Scene Preview" width="49%" style="border-radius: 8px;" />
  <img src="imgs/compGraphicsGame.bmp" alt="Game Scene Preview" width="49%" style="border-radius: 8px;" />
</p>

---

<a id="tasklass"></a>
### 📚 [TaskLass: Piattaforma Web Full-Stack per la Gestione e Valutazione dei Compiti Scolastici](https://github.com/Frads01/progetto-webapp1)

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express">
</p>

TaskLass è una piattaforma web full-stack sviluppata per l'esame di Web Applications 1, pensata per digitalizzare la creazione, la consegna e la valutazione dei compiti.

- **Ruoli utente:** I docenti creano compiti per specifici gruppi di studenti e valutano gli elaborati consegnati; gli studenti consegnano le risposte e monitorano la propria media calcolata lato server.
- **Architettura:** Frontend reattivo realizzato con React e React Router, abbinato a un backend Node.js/Express che espone API REST autenticate con gestione delle sessioni.
- **Gestione dati:** Schema di database relazionale con relazioni molti-a-molti, API REST e gestione della concorrenza.

<p align="center">
  <img src="imgs/screenshot-1751640190460.png" alt="TaskLass Web App Preview" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="screen-casting"></a>
### ↔️ [Screen-Casting Multi-Piattaforma](https://github.com/Frads01/pds-screencast)

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white" alt="FFmpeg">
</p>

Sviluppata per il corso di System Programming al Politecnico di Torino, questa applicazione desktop multipiattaforma in Rust consente la condivisione dello schermo in tempo reale e a bassa latenza su Windows, macOS e Linux tramite multicast IPv4, con un'interfaccia grafica realizzata con `egui`.

- **Sender:** Configura IP/porta e selezione del monitor. Controlli in tempo reale per mettere in pausa la condivisione, inviare una schermata bianca, disegnare annotazioni (rettangoli, frecce), condividere una regione specifica dello schermo o interrompere lo stream tramite scorciatoie (`Ctrl+P`, `Ctrl+B`, `Ctrl+D`, `Ctrl+S`, `Ctrl+Q`). Include la gestione di fallback in caso di disconnessione di un monitor.
- **Receiver:** Si connette tramite multicast IPv4, con opzioni di uscita dalla sessione e registrazione dello schermo integrata tramite FFmpeg (con download automatico se non è già installato).

---

<a id="quoridor"></a>
### 🧱 [Quoridor — Gioco da Tavolo Embedded](https://github.com/Frads01/ase-quoridor)

<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/Assembly-654FF0?style=flat-square" alt="Assembly">
  <img src="https://img.shields.io/badge/ARM_Cortex--M3-00979D?style=flat-square&logo=arm&logoColor=white" alt="ARM Cortex-M3">
</p>

Quoridor è un'implementazione embedded realizzata da zero del celebre gioco da tavolo, sviluppata per il corso di Architetture dei Sistemi di Elaborazione al Politecnico di Torino su piattaforma ARM Cortex-M3 (Keil µVision), programmata in C con routine critiche in Assembly.

- **Logica di gioco:** La board 13×13 è modellata come una matrice che alterna celle giocatore e celle muro, con un algoritmo ricorsivo basato su DFS che garantisce che nessun posizionamento di muro possa mai intrappolare completamente un avversario.
- **Hardware & Periferiche:** Display GLCD e touch panel per il rendering, joystick e pulsanti (con polling e debouncing via RIT) per l'input, e diversi timer hardware per gestire il countdown di 20 secondi a mossa e i messaggi a schermo.
- **NPC & Multiplayer:** Una modalità a singola scheda offre un avversario NPC che calcola il percorso tramite un algoritmo basato su Dijkstra, mentre una modalità a due schede consente di giocare uno contro l'altro tramite bus CAN, sincronizzato attraverso un protocollo di handshake.

<!--
<p align="center">
   inserisci qui uno screenshot/foto del setup, es. imgs/quoridor.png 
</p>
-->
---

<div align="center">

> *Sono sempre felice di parlare di grafica, XR o qualsiasi cosa legata alla computer vision — non esitare a contattarmi.* 🤗

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Fatto%20con-%E2%9D%A4-red?style=flat-square" alt="Made with love">
  &nbsp;&nbsp;
  <a href="#top"><img src="https://img.shields.io/badge/⬆%20Torna%20su-4CAF50?style=flat-square" alt="Back to top"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=4CAF50&height=100&section=footer" width="100%"/>
</div>
