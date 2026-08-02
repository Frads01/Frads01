<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=4CAF50&height=180&section=header&text=Hello%20World,%20I'm%20Francesco!&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=&descAlignY=55" width="100%"/>
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&pause=1000&color=4CAF50&center=true&vCenter=true&width=650&lines=Master+Student+in+Computer+Engineering;Extended,+Augmented+%26+Virtual+Reality;Computer+Vision+%26+3D+Graphics" alt="Typing SVG" />

<a href="mailto:francescodisanto14@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://www.linkedin.com/in/francesco-di-santo-1b6ab7261/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://github.com/Frads01/Frads01/blob/main/cv_eng.pdf"><img src="https://img.shields.io/badge/CV%20(English)-4CAF50?style=for-the-badge&logo=googledocs&logoColor=white" alt="CV English"></a>
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
> <i>The README for this profile is currently under construction. In the meantime, you can check out the projects I have contributed to below!</i>

<div>

## ℹ️ About me!

Master's student in Computer Engineering at **Politecnico di Torino**, specializing in **Computer Graphics & Multimedia**. 

My main interests and focus areas:
- 🥽 **Extended, Augmented & Virtual Reality**
- 🎨 **3D Graphics & Modeling**
- 👁️ **Computer Vision & Image Processing**
- 🎵 **Audio Elaboration & Signal Processing**
- 🤖 **Machine Learning applied to Vision and Multimedia**

*Currently completing a Master's thesis on evaluating cognitive states in XR environments through active and passive brain-computer interfaces.*

---

## 🚀 Featured Projects

- [👀 Facial Verification — Geometric Landmarks vs. Neural Embeddings](#facial-verification)
- [🚗 DriveAcademyVR — VR Driving School Simulator](#driveacademyvr)
- [🎵 Song Noise Reduction Without Clean Training Data](#noise-reduction)
- [📹 Canoa Slalom — Video Performance Analysis](#canoa-slalom)
- [🏛️ My Museum Adventure — Gamified Museum Guide](#museum-adventure)
- [🕹️ Computer Graphics: 3D Modeling & Interactive Graphics](#computer-graphics)
- [↔️ Multi-Platform Screen-Casting](#screen-casting)
- [📚 TaskLass: Full-Stack Web Platform for School Assignments](#tasklass)
- [🧱 Quoridor — Embedded Board Game](#quoridor)

---

<a id="facial-verification"></a>
### 👀 [Facial Verification — Geometric Landmarks vs. Neural Embeddings](https://github.com/SalvatoreGiugliano98/FaceVerification)

<p>
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/AR_Foundation-000000?style=flat-square&logo=apple&logoColor=white" alt="AR Foundation">
</p>

This project evaluates two facial verification methods built into an iOS application using Unity, C#, and AR Foundation: a **3D Geometric Approach** and a **2D Neural Approach**. 

- **3D Approach:** Captures TrueDepth point clouds via ARKit to measure normalized Euclidean distances across 17 anatomical landmarks (from 1,220 tracked points).
- **2D Approach:** Uses ArcFace (ResNet-100 backbone) on Unity's Barracuda engine to compare 512-dimensional embeddings from RGB images using cosine similarity.

The application features real-time face detection, a 3D facial viewer, live dual-pipeline testing, biometric measurement logging, and CSV export. Experimental results across 100+ tests showed the 3D method achieved **97.12% overall accuracy** and **100% recall**, whereas the ArcFace model achieved **100% precision**.

<p align="center">
  <img src="imgs/sg3d.bmp" alt="Facial Verification Preview" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="driveacademyvr"></a>
### 🚗 [DriveAcademyVR — VR Driving School Simulator](https://github.com/SalvatoreGiugliano98/DriveAcademyVR)

<p>
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/Meta_Quest_3-0081FB?style=flat-square&logo=meta&logoColor=white" alt="Meta Quest 3">
</p>

Drive Academy VR is a virtual reality driving school simulator developed for the **Meta Quest 3** headset. It provides an immersive, risk-free environment for users to practice driving, learn traffic rules, and receive real-time vocal guidance from a virtual instructor. 

Built with realistic vehicle physics, the system features a fully interactive cockpit where users manually operate controls (steering wheel, gear shift, turn signals, handbrake, seatbelt), backed by a diegetic UI integrated into the dashboard. Operating within a grid-based city filled with traffic and pedestrians, the application tracks performance, provides immediate visual, auditory, and haptic feedback on infractions, and includes an introductory tutorial module.

<p align="center">
  <img src="imgs/driveacademy_examp.png" alt="DriveAcademyVR Preview 1" width="49%" style="border-radius: 6px;" />
  <img src="imgs/driveacademy_examp3.png" alt="DriveAcademyVR Preview 2" width="49%" style="border-radius: 6px;" />
</p>

---

<a id="noise-reduction"></a>
### 🎵 [Song Noise Reduction Without Clean Training Data](https://github.com/Frads01/mlvm-noise-remover)

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
</p>

A deep learning audio denoising pipeline built using a 20-layer Deep Complex U-Net (**DCUNet-20**) architecture to perform music denoising without requiring clean training data. 

Adopting the **Noise2Noise** paradigm, the network was trained exclusively on pairs of noisy audio signals generated by combining tracks from the MUSDB18 dataset with environmental and gaussian sound events from UrbanSound8K. The implementation operates directly on complex-valued Short-Time Fourier Transform (STFT) spectrograms to preserve magnitude and phase information. 

- **Key Technical Highlights:** Complex convolutions, complex batch normalization, Rayleigh-distribution complex weight initialization, and gradient optimization via Weighted Signal-to-Distortion Ratio (WSDR) loss.
- **Results:** Achieved an average Signal-to-Noise Ratio (SNR) improvement of **+7.54 dB**, outperforming baseline speech-oriented models on musical signals.

<p align="center">
  <img src="imgs/dcunet20.png" alt="Noise Reduction Spectrogram" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="canoa-slalom"></a>
### 📹 [Canoa Slalom — Video Performance Analysis](https://github.com/Frads01/ipcv-canoa)

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
</p>

Developed for the Image Processing and Computer Vision course at Politecnico di Torino to analyze Canoe Slalom performances. Built using Python and OpenCV, the system applies computer vision techniques to track the canoe and detect slalom gates in dynamic video streams under water reflections and camera movement.

- **Key Features:** Gate detection & segmentation, athlete and boat tracking, automated evaluation of gate touches/misses, and optimized frame processing.
- **Techniques Used:** Morphological operations, contour detection, and optical flow for real-world sports analytics.

<p align="center">
  <img src="imgs/CanoaSlalom.png" alt="Canoa Slalom Preview" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="museum-adventure"></a>
### 🏛️ [My Museum Adventure — Gamified Museum Guide](https://github.com/SalvatoreGiugliano98/my-museum-adventure-main)

<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=android&logoColor=white" alt="Jetpack Compose">
</p>

Developed for the Human-Computer Interaction course at Politecnico di Torino, **My Museum Adventure** is an Android app designed to gamify museum visits through theme-based interactive quests. 

Users choose narrative paths (Adventure, Fantasy, Sci-Fi) and solve riddles to discover artworks while earning medals. 

- **Features:** Camera-based artwork scanning via external image recognition APIs, crowdsourced interactive maps for navigation, and detailed descriptions with multilingual audio guides.
- **Tech Stack:** Kotlin, Jetpack Compose, Room (offline storage), CameraX, OkHttp, and Jetpack Navigation.

<p align="center">
  <img src="imgs/MyMuseumAdventure.png" alt="My Museum Adventure Preview" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="computer-graphics"></a>
### 🕹️ [Computer Graphics: 3D Modeling and Interactive Graphics Application](https://github.com/SalvatoreGiugliano98/Computer-Graphics)

<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" alt="OpenGL">
  <img src="https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white" alt="Blender">
</p>

Created for the Computer Graphics course, this project implements core principles of 3D rendering, modeling, and interactive visual computing. 

It consists of a real-time game application built with OpenGL along with a realistic 3D scene modeled in Blender using physics simulation techniques. 

- **Features:** Geometric transformations, scene graph management, dynamic lighting (Phong/Blinn-Phong), texture mapping, and custom shaders.

<p align="center">
  <img src="imgs/ScenaCompleta.png" alt="3D Graphics Scene Preview" width="49%" style="border-radius: 8px;" />
  <img src="imgs/compGraphicsGame.bmp" alt="Game Scene Preview" width="49%" style="border-radius: 8px;" />
</p>

---

<a id="tasklass"></a>
### 📚 [TaskLass: Full-Stack Web Platform for Managing and Grading School Assignments](https://github.com/Frads01/progetto-webapp1)

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express">
</p>

TaskLass is a full-stack web platform developed for Web Applications 1, designed to digitize assignment creation, submission, and grading.

- **User Roles:** Teachers create assignments for specific student groups and grade submitted work; students submit responses and track their server-calculated GPA.
- **Architecture:** Reactive frontend built with React and React Router paired with a Node.js/Express backend exposing authenticated REST APIs with session management.
- **Data Management:** Relational database schema modeling many-to-many relationships, REST APIs, and concurrency handling.

<p align="center">
  <img src="imgs/screenshot-1751640190460.png" alt="TaskLass Web App Preview" width="100%" style="border-radius: 8px;" />
</p>

---

<a id="screen-casting"></a>
### ↔️ [Multi-Platform Screen-Casting](https://github.com/Frads01/pds-screencast)

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white" alt="FFmpeg">
</p>

Developed for the System Programming course at Politecnico di Torino, this cross-platform PC application in Rust enables low-latency real-time screen sharing on Windows, macOS, and Linux using IPv4 multicast with an intuitive `egui` GUI.

- **Sender:** Configures IP/port and monitor selection. Real-time controls to pause sharing, send a blank white screen, draw annotations (rectangles, arrows), share specific regions, or stop stream with hotkeys (`Ctrl+P`, `Ctrl+B`, `Ctrl+D`, `Ctrl+S`, `Ctrl+Q`). Includes fallback handling if a monitor disconnects.
- **Receiver:** Connects via IPv4 multicast, featuring session exit options and built-in screen recording powered by FFmpeg (with automatic download handling if not pre-installed).

---

<a id="quoridor"></a>
### 🧱 [Quoridor — Embedded Board Game](https://github.com/Frads01/ase-quoridor)

<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/Assembly-654FF0?style=flat-square" alt="Assembly">
  <img src="https://img.shields.io/badge/ARM_Cortex--M3-00979D?style=flat-square&logo=arm&logoColor=white" alt="ARM Cortex-M3">
</p>

Quoridor is a from-scratch embedded implementation of the classic board game, developed for the Computer Systems Architecture course at Politecnico di Torino on an ARM Cortex-M3 platform (Keil µVision), programmed in C with critical routines in Assembly.

- **Gameplay & Logic:** The 13×13 board is modeled as a matrix alternating player and wall cells, with a recursive DFS-based algorithm ensuring no wall placement can ever fully trap an opponent.
- **Hardware & Peripherals:** GLCD display and touch panel for rendering, joystick and buttons (via RIT-based polling/debouncing) for input, and multiple hardware timers to manage the 20-second move clock and on-screen messages.
- **NPC & Multiplayer:** A single-board mode features an NPC opponent that pathfinds with a Dijkstra-based algorithm, while a two-board mode enables head-to-head play over CAN bus, synchronized through a handshake protocol.
  
<!--
<p align="center">
   inserisci qui uno screenshot/foto del setup, es. imgs/quoridor.png 
</p>
-->
---

<div align="center">
  
> *Always happy to talk about graphics, XR or anything computer vision related — feel free to reach out.* 🤗

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=flat-square" alt="Made with love">
  &nbsp;&nbsp;
  <a href="#top"><img src="https://img.shields.io/badge/⬆%20Back%20to%20top-4CAF50?style=flat-square" alt="Back to top"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=4CAF50&height=100&section=footer" width="100%"/>
</div>
