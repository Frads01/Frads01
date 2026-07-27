<div align="center">

# Welcome to Frads' homepage! 👋

> [!NOTE]
> The README for this profile is currently under construction. In the meantime, you can check out the projects I have contributed to below!

<br>

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:francescodisanto14@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/francesco-di-santo-1b6ab7261/)
[![CV (English)](https://img.shields.io/badge/CV%20(English)-4CAF50?style=for-the-badge&logo=googledocs&logoColor=white)](https://github.com/Frads01/Frads01/blob/main/cv_eng.pdf)
[![CV (Italian)](https://img.shields.io/badge/CV%20(Italiano)-4CAF50?style=for-the-badge&logo=googledocs&logoColor=white)](https://github.com/Frads01/Frads01/blob/main/cv_ita.pdf)

</div>

<br>

## About

Master's student in Computer Engineering at **Politecnico di Torino**, specializing in Computer Graphics & Multimedia. I work at the intersection of **Extended Reality, 3D graphics and applied Machine Learning** — designing immersive environments and building the computer vision / ML pipelines that make them smarter.

Currently completing a thesis on evaluating cognitive states in XR environments through active and passive brain-computer interfaces.

<br>

## Stack

**Languages**
&nbsp;&nbsp;![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Graphics & XR**
&nbsp;&nbsp;![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white)
![ARKit](https://img.shields.io/badge/AR%20Foundation-000000?style=flat-square&logo=apple&logoColor=white)

**AI / Computer Vision**
&nbsp;&nbsp;![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Web**
&nbsp;&nbsp;![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

<br>

## Featured Projects

<details open>
<summary><strong>🧑‍🤝‍🧑 Facial Verification — Geometric Landmarks vs. Neural Embeddings</strong></summary>
<br>

iOS app (Unity + AR Foundation) comparing two face-verification approaches: a 3D geometric method using TrueDepth point clouds across 17 anatomical landmarks, versus a 2D neural method (ArcFace / ResNet-100) comparing 512-d embeddings via cosine similarity. Over 100+ trials, the 3D approach reached **97.12% accuracy / 100% recall**, while the neural approach reached **100% specificity**.

`Unity` `C#` `AR Foundation` `ArcFace`
&nbsp;·&nbsp; [Repository →](https://github.com/SalvatoreGiugliano98/FaceVerification)

</details>

<details>
<summary><strong>🚗 DriveAcademyVR — VR Driving School Simulator</strong></summary>
<br>

A driving-school simulator for Meta Quest 3 with an interactive cockpit (wheel, automatic gearbox, indicators, handbrake, seatbelt), diegetic dashboard UI, realistic vehicle physics, and an urban grid populated with traffic and pedestrians. Provides real-time visual, audio and haptic feedback on driving mistakes.

`Unity` `C#` `Meta Quest 3`
&nbsp;·&nbsp; [Play on itch.io →](https://frads01.itch.io/drive-academy)
&nbsp;·&nbsp; [Repository →](https://github.com/SalvatoreGiugliano98/DriveAcademyVR)

</details>

<details>
<summary><strong>🎵 Music Denoising Without Clean Training Data</strong></summary>
<br>

Deep-learning audio denoising pipeline using a 20-layer Deep Complex U-Net (DCUNet-20), trained with the Noise2Noise paradigm on pairs of noisy signals only — no clean reference audio required. Operates directly on complex STFT spectrograms with complex convolutions, complex batch norm and Rayleigh weight initialization. Achieved a **+7.54 dB average SNR improvement** over speech-denoising baselines.

`Python` `PyTorch` `DCUNet`
&nbsp;·&nbsp; [Repository →](https://github.com/Frads01/mlvm-noise-remover)

</details>

<details>
<summary><strong>🛶 Canoe Slalom — Video Performance Analysis</strong></summary>
<br>

Computer vision pipeline that tracks the canoe and detects slalom gates in dynamic video footage, handling water reflections and camera motion. Includes gate detection/segmentation, athlete and boat tracking, and automated scoring of touched or missed gates.

`Python` `OpenCV`
&nbsp;·&nbsp; [Repository →](https://github.com/Frads01/ipcv-canoa)

</details>

<details>
<summary><strong>🏛️ My Museum Adventure — Gamified Museum Guide</strong></summary>
<br>

Android app that turns museum visits into a game: users pick a narrative theme (Adventure, Fantasy, Sci-Fi) and solve puzzles to find artworks, earning medals along the way. Features camera-based artwork recognition, crowdsourced interactive maps and multilingual audio guides.

`Kotlin` `Jetpack Compose` `Room` `CameraX`
&nbsp;·&nbsp; [Repository →](https://github.com/SalvatoreGiugliano98/my-museum-adventure-main)

</details>

<details>
<summary><strong>🖥️ Computer Graphics — 3D Modeling & Interactive Rendering</strong></summary>
<br>

Real-time interactive 3D application built with low-level graphics libraries, paired with a physically-based 3D scene modeled in Blender. Features free camera navigation, geometric transformations, scene graph management, dynamic lighting, texture mapping and custom shaders.

`C++` `OpenGL` `Blender`
&nbsp;·&nbsp; [Repository →](https://github.com/SalvatoreGiugliano98/Computer-Graphics)

</details>

<details>
<summary><strong>🖥️ Cross-Platform Screen Casting</strong></summary>
<br>

Multi-platform screen-sharing tool (Windows / macOS / Linux) over IPv4 multicast, with a lightweight `egui` interface. The sender supports pausing, blanking the screen, live annotations, area selection and hotkeys; the receiver can join sessions and record the stream via `ffmpeg`.

`Rust` `egui` `FFmpeg`
&nbsp;·&nbsp; [Repository →](https://github.com/Frads01/pds-screencast)

</details>

<details>
<summary><strong>📚 TaskLass — Task Management Platform for Teachers & Students</strong></summary>
<br>

Full-stack web app for managing school assignments, with separate dashboards for teachers (create tasks, assign groups, grade responses) and students (view tasks, submit answers, track weighted-average performance). REST API with session-based auth and a relational schema with a many-to-many task/student relationship.

`React` `Node.js` `Express`
&nbsp;·&nbsp; [Repository →](https://github.com/Frads01/progetto-webapp1)

</details>

<br>

<div align="center">

*Always happy to talk about graphics, XR or anything computer vision related — feel free to reach out.*

</div>
