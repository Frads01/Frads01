<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=4CAF50&height=180&section=header&text=Ciao%20Mondo,%20sono%20Francesco!&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=&descAlignY=55" width="100%"/>
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&pause=1000&color=4CAF50&center=true&vCenter=true&width=650&lines=Studente+Magistrale+in+Ingegneria+Informatica;Realta%27+Estesa%2C+Aumentata+e+Virtuale;Computer+Vision+e+Grafica+3D" alt="Typing SVG" />

<a href="mailto:francescodisanto14@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://www.linkedin.com/in/francesco-di-santo-1b6ab7261/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://github.com/Frads01/Frads01/blob/main/cv_eng.pdf"><img src="https://img.shields.io/badge/CV%20(Inglese)-4CAF50?style=for-the-badge&logo=googledocs&logoColor=white" alt="CV Inglese"></a>
<a href="https://github.com/Frads01/Frads01/blob/main/cv_ita.pdf"><img src="https://img.shields.io/badge/CV%20(Italiano)-4CAF50?style=for-the-badge&logo=googledocs&logoColor=white" alt="CV Italiano"></a>

<br>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=python,cs,rust,c,cpp,java,js,ts,react" alt="Le mie competenze" />
</a>
<br>
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=unity,blender,opencv,vscode,pycharm,rider,clion,idea,windows,linux" alt="Le mie competenze" />
</a>

</div>

<!--
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Frads01&label=Visualizzazioni%20Profilo&color=4CAF50&style=flat-square" alt="Visualizzazioni Profilo" />
  <img src="https://img.shields.io/github/followers/Frads01?label=Follower&style=flat-square&color=4CAF50" alt="GitHub Follower" />
</p>
-->

<br>

> [!NOTE]
> <i>Il README per questo profilo è attualmente in fase di sviluppo. Nel frattempo, puoi dare un'occhiata ai progetti a cui ho contribuito qui sotto!</i>

<div>

## ℹ️ Chi sono!

Studente magistrale in Ingegneria Informatica presso il **Politecnico di Torino**, specializzato in **Grafica al Calcolatore e Multimedia**. 

I miei principali interessi e settori di ricerca:
- 🥽 **Realtà Estesa, Aumentata e Virtuale (XR/AR/VR)**
- 🎨 **Grafica 3D e Modellazione**
- 👁️ **Computer Vision ed Elaborazione delle Immagini**
- 🎵 **Elaborazione Audio e dei Segnali**
- 🤖 **Machine Learning applicato a Visione e Multimedia**

*Attualmente sto completando una tesi di laurea magistrale sulla valutazione degli stati cognitivi in ambienti XR attraverso interfacce cervello-computer (BCI) attive e passive.*

---

## 🚀 Progetti in evidenza

- [👀 Verifica Facciale — Landmark Geometrici vs. Neural Embeddings](#verifica-facciale)
- [🚗 DriveAcademyVR — Simulatore VR per Scuola Guida](#driveacademyvr)
- [🎵 Riduzione del Rumore nei Brani senza Dati di Addestramento Puliti](#riduzione-rumore)
- [📹 Canoa Slalom — Analisi delle Prestazioni Video](#canoa-slalom)
- [🏛️ My Museum Adventure — Guida Museale Gamificata](#museum-adventure)
- [🕹️ Grafica al Calcolatore: Modellazione 3D e Applicazione Grafica Interattiva](#grafica-al-calcolatore)
- [↔️ Screen-Casting Multi-Piattaforma](#screen-casting)
- [📚 TaskLass: Piattaforma Web Full-Stack per la Gestione e Valutazione dei Compiti Scolastici](#tasklass)

---

<a id="verifica-facciale"></a>
### 👀 [Verifica Facciale — Landmark Geometrici vs. Neural Embeddings](https://github.com/SalvatoreGiugliano98/FaceVerification)

<p>
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/AR_Foundation-000000?style=flat-square&logo=apple&logoColor=white" alt="AR Foundation">
</p>

Questo progetto valuta due metodi di verifica facciale integrati in un'applicazione iOS sviluppata con Unity, C# e AR Foundation: un **approccio geometrico 3D** e un **approccio neurale 2D**. 

- **Approccio 3D:** Acquisisce nuvole di punti TrueDepth tramite ARKit per misurare le distanze euclidee normalizzate tra 17 landmark anatomici (su 1.220 punti tracciati).
- **Approccio 2D:** Utilizza ArcFace (backbone ResNet-100) sul motore Barracuda di Unity per confrontare embedding a 512 dimensioni da immagini RGB tramite la similarità del coseno.

L'applicazione offre rilevamento facciale in tempo reale, visualizzatore facciale 3D, test in parallelo delle due pipeline, registrazione delle misurazioni biometriche ed esportazione in CSV. I risultati sperimentali su oltre 100 test hanno mostrato che il metodo 3D ha raggiunto un'accuratezza complessiva del **97,12%** e un richiamo (recall) del **100%**, mentre il modello ArcFace ha ottenuto una precisione del **100%**.

<p align="center">
  <img src="imgs/sg3d.bmp" alt="Anteprima Verifica Facciale" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="driveacademyvr"></a>
### 🚗 [DriveAcademyVR — Simulatore VR per Scuola Guida](https://github.com/SalvatoreGiugliano98/DriveAcademyVR)

<p>
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/Meta_Quest_3-0081FB?style=flat-square&logo=meta&logoColor=white" alt="Meta Quest 3">
</p>

Drive Academy VR è un simulatore di scuola guida in realtà virtuale sviluppato per il visore **Meta Quest 3**. Fornisce un ambiente immersivo e privo di rischi in cui gli utenti possono esercitarsi nella guida, imparare le regole del traffico e ricevere indicazioni vocali in tempo reale da un istruttore virtuale. 

Realizzato con una fisica dei veicoli realistica, il sistema presenta un abitacolo completamente interattivo dove gli utenti azionano manualmente comandi come volante, cambio, frecce, freno a mano e cinture di sicurezza, supportato da un'interfaccia utente diegetica integrata nel cruscotto. Inserita in una città a griglia popolata da traffico e pedoni, l'applicazione traccia le prestazioni, fornisce feedback visivi, uditivi e aptici immediati sulle infrazioni e include un modulo tutorial introduttivo.

<p align="center">
  <img src="imgs/driveacademy_examp.png" alt="Anteprima DriveAcademyVR 1" width="49%" style="border-radius: 6px;" />
  <img src="imgs/driveacademy_examp3.png" alt="Anteprima DriveAcademyVR 2" width="49%" style="border-radius: 6px;" />
</p>

---

<a id="riduzione-rumore"></a>
### 🎵 [Riduzione del Rumore nei Brani senza Dati di Addestramento Puliti](https://github.com/Frads01/mlvm-noise-remover)

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
</p>

Una pipeline di denoiser audio basata su deep learning basata su un'architettura Deep Complex U-Net a 20 livelli (**DCUNet-20**) per rimuovere il rumore dalla musica senza richiedere dati di addestramento puliti. 

Adottando il paradigma **Noise2Noise**, la rete è stata addestrata esclusivamente su coppie di segnali audio rumorosi generati combinando tracce del dataset MUSDB18 con eventi sonori ambientali e gaussiani presi da UrbanSound8K. L'implementazione opera direttamente su spettrogrammi STFT (Short-Time Fourier Transform) a valori complessi per preservare sia le informazioni di ampiezza che di fase. 

- **Aspetti Tecnici Salienti:** Convoluzioni complesse, batch normalization complessa, inizializzazione complessa dei pesi basata sulla distribuzione di Rayleigh e ottimizzazione del gradiente tramite funzione di perdita WSDR (Weighted Signal-to-Distortion Ratio).
- **Risultati:** Il sistema finale ottimizzato ha ottenuto un miglioramento medio del rapporto segnale-rumore (SNR) di **+7,54 dB**, superando i modelli baseline orientati al parlato sui segnali musicali.

<p align="center">
  <img src="imgs/dcunet20.png" alt="Spettrogramma Riduzione Rumore" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="canoa-slalom"></a>
### 📹 [Canoa Slalom — Analisi delle Prestazioni Video](https://github.com/Frads01/ipcv-canoa)

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
</p>

Sviluppato per il corso di Elaborazione delle Immagini e Visione Artificiale presso il Politecnico di Torino per analizzare le prestazioni nella Canoa Slalom. Realizzato in Python e OpenCV, il sistema applica tecniche di computer vision per tracciare la canoa e rilevare le porte da slalom in flussi video dinamici, affrontando sfide quali riflessi dell'acqua e movimenti della telecamera.

- **Funzionalità Principali:** Rilevamento e segmentazione delle porte, tracciamento dell'atleta e dell'imbarcazione, valutazione automatizzata del tocco o del salto delle porte ed elaborazione ottimizzata dei fotogrammi.
- **Tecniche Utilizzate:** Operazioni morfologiche, rilevamento dei contorni e flusso ottico per l'analisi sportiva reale.

<p align="center">
  <img src="imgs/CanoaSlalom.png" alt="Anteprima Canoa Slalom" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="museum-adventure"></a>
### 🏛️ [My Museum Adventure — Guida Museale Gamificata](https://github.com/SalvatoreGiugliano98/my-museum-adventure-main)

<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=android&logoColor=white" alt="Jetpack Compose">
</p>

Sviluppata per il corso di Interazione Uomo-Macchina presso il Politecnico di Torino, **My Museum Adventure** è un'applicazione Android progettata per rendere gamificata la visita ai musei attraverso sfide interattive a tema. 

Gli utenti scelgono percorsi narrativi (Avventura, Fantasy, Fantascienza) e risolvono indovinelli per scoprire opere d'arte, guadagnando medaglie e obiettivi lungo il percorso. 

- **Funzionalità:** Scansione delle opere tramite fotocamera gestita da API esterne di riconoscimento immagini per verificare le risposte, mappe interattive crowdsourced per la navigazione e descrizioni dettagliate con audioguide multilingua.
- **Tech Stack:** Kotlin, Jetpack Compose, Room (archiviazione locale offline), CameraX, OkHttp e Jetpack Navigation.

<p align="center">
  <img src="imgs/MyMuseumAdventure.png" alt="Anteprima My Museum Adventure" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="grafica-al-calcolatore"></a>
### 🕹️ [Grafica al Calcolatore: Modellazione 3D e Applicazione Grafica Interattiva](https://github.com/SalvatoreGiugliano98/Computer-Graphics)

<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" alt="OpenGL">
  <img src="https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white" alt="Blender">
</p>

Sviluppato per il corso di Grafica al Calcolatore per implementare i principi fondamentali del rendering 3D, della modellazione e del calcolo visivo interattivo. 

È composto da un'applicazione 3D interattiva in tempo reale creata con librerie grafiche a basso livello come OpenGL, affiancata da una scena 3D modellata su Blender mediante tecniche di fisica. 

- **Funzionalità:** Ambiente 3D navigabile con controlli per la telecamera, trasformazioni geometriche, gestione dello grafo della scena, illuminazione dinamica (Phong/Blinn-Phong), mappatura delle texture e shader personalizzati.

<p align="center">
  <img src="imgs/ScenaCompleta.png" alt="Anteprima Scena Grafica 3D" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="screen-casting"></a>
### ↔️ [Screen-Casting Multi-Piattaforma](https://github.com/Frads01/pds-screencast)

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white" alt="FFmpeg">
</p>

Sviluppata per il corso di Programmazione di Sistema presso il Politecnico di Torino, questa applicazione PC multipiattaforma scritta in Rust consente la condivisione dello schermo in tempo reale a bassa latenza su Windows, macOS e Linux tramite multicast IPv4 con un'interfaccia grafica `egui`.

- **Mittente (Sender):** Configura IP/porta e selezione del monitor. Controlli in tempo reale per mettere in pausa la condivisione, inviare una schermata bianca vuota, disegnare annotazioni (rettangoli, frecce), condividere una regione specifica dello schermo o interrompere lo streaming (con scorciatoie come `Ctrl+P`, `Ctrl+B`, `Ctrl+D`, `Ctrl+S`, `Ctrl+Q`). Include la gestione del fallback se un monitor viene scollegato.
- **Ricevitore (Receiver):** Si connette tramite multicast IPv4, con opzioni di uscita dalla sessione e registrazione dello schermo integrata tramite FFmpeg (con download automatico se non preinstallato).

---

<a id="tasklass"></a>
### 📚 [TaskLass: Piattaforma Web Full-Stack per la Gestione e Valutazione dei Compiti Scolastici](https://github.com/Frads01/progetto-webapp1)

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express">
</p>

TaskLass è un'applicazione web full-stack sviluppata per l'esame di Applicazioni Web 1, pensata per digitalizzare l'assegnazione, la consegna e la valutazione dei compiti a casa.

- **Ruoli Utente:** Gli insegnanti creano compiti per specifici gruppi di studenti e valutano i lavori consegnati; gli studenti inviano le soluzioni e monitorano la propria media voti calcolata lato server.
- **Architettura:** Frontend reattivo in React con React Router affiancato da un backend Node.js/Express che espone API REST autenticate basate su sessione.
- **Gestione Dati:** Schema di database relazionale con relazioni molti-a-molti, API REST e gestione della concorrenza.

<p align="center">
  <img src="imgs/screenshot-1751640190460.png" alt="Anteprima TaskLass Web App" width="100%" style="border-radius: 8px;" />
</p>

---

<div align="center">
  
> *Mi fa sempre piacere parlare di grafica, XR o di qualsiasi argomento legato alla computer vision — non esitare a contattarmi!* 🤗

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Fatto%20con-%E2%9D%A4-red?style=flat-square" alt="Fatto con amore">
  &nbsp;&nbsp;
  <a href="#top"><img src="https://img.shields.io/badge/⬆%20Torna%20su-4CAF50?style=flat-square" alt="Torna su"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=4CAF50&height=100&section=footer" width="100%"/>
</div>
