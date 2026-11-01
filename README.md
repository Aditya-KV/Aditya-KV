<div align="center">

<img src="./assets/banner.png" width="100%" alt="A lone climber on an icy ledge facing a storm-wrapped snow mountain under a full moon" />

<h1>Aditya K V</h1>

<br/><br/>

<b>Machine learning &bull; Full-stack apps &bull; Local-first AI tools</b>

<br/><br/>

<a href="https://github.com/Aditya-KV?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-1f6f57?style=for-the-badge&logo=github&logoColor=white" alt="Browse repositories" /></a>
<a href="https://github.com/Aditya-KV/Anomaly-detection-in-satellite-telemetry"><img src="https://img.shields.io/badge/Published-ICDAM%202026-0d3b30?style=for-the-badge" alt="Published at ICDAM 2026" /></a>
<a href="mailto:adityakvnov05@gmail.com"><img src="https://img.shields.io/badge/Email-Get%20in%20touch-a8e3c4?style=for-the-badge&logo=gmail&logoColor=0d3b30" alt="Email Aditya" /></a>

</div>

---

### Overview

<table>
  <tr>
    <td width="32%" valign="top" align="center">
      <br/>
      <img src="./assets/avatar-v3.png" width="220" alt="Pixel art of Aditya in profile, coding on a laptop in a cafe with a boba and a light blue henley" />
      <br/><br/>
      <b>Aditya K V</b><br/>
      <code>@Aditya-KV</code>
      <br/><br/>
      <p align="left">
        <b>Studying:</b> B.E. CSE (AI &amp; ML), Chandigarh University<br/>
        <b>Based in:</b> India<br/>
        <b>Focus:</b> ML systems and full-stack apps<br/>
        <b>Status:</b> Open to internships<br/>
        <b>Contact:</b> <a href="mailto:adityakvnov05@gmail.com">adityakvnov05@gmail.com</a>
      </p>
    </td>
    <td width="68%" valign="top">
      <b>What I work on</b>
      <ul>
        <li><b>Anomaly detection.</b> A hybrid ensemble for spacecraft telemetry, evaluated on synthetic, NASA SMAP and ESA OPS-SAT data and published at ICDAM 2026.</li>
        <li><b>Local-first AI tools.</b> SyncDrive AI watches folders, screens files for confidential content with a pretrained model plus rules, and searches them with hybrid retrieval, all on the user's own machine.</li>
        <li><b>Computer vision.</b> Real-time sign-language recognition from MediaPipe hand landmarks, with a vote-based stabiliser for steady live predictions.</li>
        <li><b>Full-stack and mobile.</b> React, Node.js, Flask and FastAPI back ends, an Electron desktop app, and a React Native app in three languages.</li>
      </ul>
      <b>How I like to work</b>
      <ul>
        <li>Put the model behind a real interface, then measure it.</li>
        <li>Keep user data on the user's machine unless they approve otherwise.</li>
        <li>Report the numbers I can reproduce, with the failure cases next to them.</li>
      </ul>
    </td>
  </tr>
</table>

---

### Selected projects

<table>
  <thead>
    <tr>
      <th width="26%">Project</th>
      <th width="50%">What I built</th>
      <th width="24%">State</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top"><b>SyncDrive AI</b><br/><sub>Intelligent file sync</sub><br/><br/><img src="https://img.shields.io/badge/Electron%20+%20React%20+%20Python-0d3b30?style=flat-square&logo=electron&logoColor=a8e3c4" alt="Electron + React + Python" /></td>
      <td valign="top">
        <ul>
          <li>Electron desktop agent and React dashboard with a detect, review, upload flow, so files are approved before they reach Google Drive.</li>
          <li>Python service that extracts text (PDF, DOCX, OCR) and screens it for confidential content with the pretrained Laya model and checksum-validated rules.</li>
          <li>Hybrid file search: embeddings, BM25 and a graph memory, reranked by a cross-encoder.</li>
        </ul>
      </td>
      <td valign="top">Working prototype<br/>Repository is private for now</td>
    </tr>
    <tr>
      <td valign="top"><a href="https://github.com/Aditya-KV/Anomaly-detection-in-satellite-telemetry"><b>Satellite telemetry anomaly detection</b></a><br/><sub>Research paper</sub><br/><br/><img src="https://img.shields.io/badge/Python%20+%20scikit--learn-0d3b30?style=flat-square&logo=scikitlearn&logoColor=a8e3c4" alt="Python + scikit-learn" /></td>
      <td valign="top">
        <ul>
          <li>Ensemble of Isolation Forest, One-Class SVM and Random Forest with synthetic anomaly injection.</li>
          <li>F1 of 0.990 on a 2,000-point synthetic benchmark and 0.958 on NASA SMAP.</li>
          <li>99.8% precision on ESA OPS-SAT, with 3 false positives in 2,594 normal points.</li>
        </ul>
      </td>
      <td valign="top">Published at ICDAM 2026<br/><a href="https://github.com/Aditya-KV/Anomaly-detection-in-satellite-telemetry">View repository &rarr;</a></td>
    </tr>
    <tr>
      <td valign="top"><a href="https://github.com/Aditya-KV/sign-detector-ai"><b>Sign language detection</b></a><br/><sub>Real-time computer vision</sub><br/><br/><img src="https://img.shields.io/badge/React%20+%20Flask%20+%20MediaPipe-0d3b30?style=flat-square&logo=react&logoColor=a8e3c4" alt="React + Flask + MediaPipe" /></td>
      <td valign="top">
        <ul>
          <li>Image upload and live webcam modes that turn hand signs into letters, words and sentences.</li>
          <li>21 MediaPipe landmarks and geometry features feed the classifier.</li>
          <li>A 10-frame stabiliser with 7-vote consensus and a 0.55 confidence threshold keeps live output steady.</li>
        </ul>
      </td>
      <td valign="top">Working full-stack app<br/><a href="https://github.com/Aditya-KV/sign-detector-ai">View repository &rarr;</a></td>
    </tr>
    <tr>
      <td valign="top"><a href="https://github.com/Aditya-KV/kalakar-setu"><b>Kalakar Setu</b></a><br/><sub>Mobile app for artisans</sub><br/><br/><img src="https://img.shields.io/badge/React%20Native%20+%20FastAPI-0d3b30?style=flat-square&logo=react&logoColor=a8e3c4" alt="React Native + FastAPI" /></td>
      <td valign="top">
        <ul>
          <li>A photo and a voice note become a catalogue-style listing with a suggested price.</li>
          <li>Available in English, Hindi and Marathi.</li>
          <li>React Native (Expo) app, FastAPI back end and Supabase database.</li>
        </ul>
      </td>
      <td valign="top">Demo video and deployment guide in the repository<br/><a href="https://github.com/Aditya-KV/kalakar-setu">View repository &rarr;</a></td>
    </tr>
  </tbody>
</table>

Smaller projects: [Resume Genie](https://github.com/Aditya-KV/resume-genie) (resume analyzer), [React login with JWT](https://github.com/Aditya-KV/react-login-jwt-demo) and coursework in [Full-stack-Lab](https://github.com/Aditya-KV/Full-stack-Lab).

<br/>

<div align="center">
  <table border="0">
    <tr>
      <td>
        <a href="https://github.com/Aditya-KV/Anomaly-detection-in-satellite-telemetry"><img src="https://github-readme-stats-fast.vercel.app/api/pin/?username=Aditya-KV&repo=Anomaly-detection-in-satellite-telemetry&bg_color=0d3b30&title_color=a8e3c4&text_color=d6efe2&icon_color=a8e3c4&border_color=1f6f57&border_radius=10" alt="Anomaly-detection-in-satellite-telemetry repository card" /></a>
      </td>
      <td>
        <a href="https://github.com/Aditya-KV/kalakar-setu"><img src="https://github-readme-stats-fast.vercel.app/api/pin/?username=Aditya-KV&repo=kalakar-setu&bg_color=0d3b30&title_color=a8e3c4&text_color=d6efe2&icon_color=a8e3c4&border_color=1f6f57&border_radius=10" alt="kalakar-setu repository card" /></a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/Aditya-KV/sign-detector-ai"><img src="https://github-readme-stats-fast.vercel.app/api/pin/?username=Aditya-KV&repo=sign-detector-ai&bg_color=0d3b30&title_color=a8e3c4&text_color=d6efe2&icon_color=a8e3c4&border_color=1f6f57&border_radius=10" alt="sign-detector-ai repository card" /></a>
      </td>
      <td>
        <a href="https://github.com/Aditya-KV/resume-genie"><img src="https://github-readme-stats-fast.vercel.app/api/pin/?username=Aditya-KV&repo=resume-genie&bg_color=0d3b30&title_color=a8e3c4&text_color=d6efe2&icon_color=a8e3c4&border_color=1f6f57&border_radius=10" alt="resume-genie repository card" /></a>
      </td>
    </tr>
  </table>
</div>

---

### Tech stack

<div align="center">

| Domain | Tools |
| :--- | :--- |
| **Languages** | <img src="https://img.shields.io/badge/Python-0d3b30?style=flat-square&logo=python&logoColor=a8e3c4" alt="Python" /> <img src="https://img.shields.io/badge/C++-0d3b30?style=flat-square&logo=cplusplus&logoColor=a8e3c4" alt="C++" /> <img src="https://img.shields.io/badge/C-0d3b30?style=flat-square&logo=c&logoColor=a8e3c4" alt="C" /> <img src="https://img.shields.io/badge/JavaScript-0d3b30?style=flat-square&logo=javascript&logoColor=a8e3c4" alt="JavaScript" /> <img src="https://img.shields.io/badge/TypeScript-0d3b30?style=flat-square&logo=typescript&logoColor=a8e3c4" alt="TypeScript" /> <img src="https://img.shields.io/badge/SQL-0d3b30?style=flat-square&logo=postgresql&logoColor=a8e3c4" alt="SQL" /> |
| **ML and data** | <img src="https://img.shields.io/badge/scikit--learn-0d3b30?style=flat-square&logo=scikitlearn&logoColor=a8e3c4" alt="scikit-learn" /> <img src="https://img.shields.io/badge/MediaPipe-0d3b30?style=flat-square&logo=google&logoColor=a8e3c4" alt="MediaPipe" /> <img src="https://img.shields.io/badge/Pandas-0d3b30?style=flat-square&logo=pandas&logoColor=a8e3c4" alt="Pandas" /> <img src="https://img.shields.io/badge/NumPy-0d3b30?style=flat-square&logo=numpy&logoColor=a8e3c4" alt="NumPy" /> <img src="https://img.shields.io/badge/Plotly-0d3b30?style=flat-square&logo=plotly&logoColor=a8e3c4" alt="Plotly" /> <img src="https://img.shields.io/badge/PyTorch-0d3b30?style=flat-square&logo=pytorch&logoColor=a8e3c4" alt="PyTorch" /> |
| **Web and apps** | <img src="https://img.shields.io/badge/React-0d3b30?style=flat-square&logo=react&logoColor=a8e3c4" alt="React" /> <img src="https://img.shields.io/badge/Node.js-0d3b30?style=flat-square&logo=nodedotjs&logoColor=a8e3c4" alt="Node.js" /> <img src="https://img.shields.io/badge/Express-0d3b30?style=flat-square&logo=express&logoColor=a8e3c4" alt="Express" /> <img src="https://img.shields.io/badge/Flask-0d3b30?style=flat-square&logo=flask&logoColor=a8e3c4" alt="Flask" /> <img src="https://img.shields.io/badge/FastAPI-0d3b30?style=flat-square&logo=fastapi&logoColor=a8e3c4" alt="FastAPI" /> <img src="https://img.shields.io/badge/Electron-0d3b30?style=flat-square&logo=electron&logoColor=a8e3c4" alt="Electron" /> <img src="https://img.shields.io/badge/React%20Native-0d3b30?style=flat-square&logo=react&logoColor=a8e3c4" alt="React Native" /> |
| **Data and tools** | <img src="https://img.shields.io/badge/MongoDB-0d3b30?style=flat-square&logo=mongodb&logoColor=a8e3c4" alt="MongoDB" /> <img src="https://img.shields.io/badge/MySQL-0d3b30?style=flat-square&logo=mysql&logoColor=a8e3c4" alt="MySQL" /> <img src="https://img.shields.io/badge/Supabase-0d3b30?style=flat-square&logo=supabase&logoColor=a8e3c4" alt="Supabase" /> <img src="https://img.shields.io/badge/SQLite-0d3b30?style=flat-square&logo=sqlite&logoColor=a8e3c4" alt="SQLite" /> <img src="https://img.shields.io/badge/Git-0d3b30?style=flat-square&logo=git&logoColor=a8e3c4" alt="Git" /> <img src="https://img.shields.io/badge/VS%20Code-0d3b30?style=flat-square&logo=visualstudiocode&logoColor=a8e3c4" alt="VS Code" /> |

</div>

---

### GitHub activity

<div align="center">
  <a href="https://github.com/Aditya-KV"><img src="https://github-readme-stats-fast.vercel.app/api?username=Aditya-KV&show_icons=true&bg_color=0d3b30&title_color=a8e3c4&text_color=d6efe2&icon_color=a8e3c4&border_color=1f6f57&border_radius=10" alt="GitHub stats" /></a>
  <a href="https://github.com/Aditya-KV"><img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=Aditya-KV&layout=compact&bg_color=0d3b30&title_color=a8e3c4&text_color=d6efe2&icon_color=a8e3c4&border_color=1f6f57&border_radius=10" alt="Top languages" /></a>
  <br/><br/>
  <a href="https://github.com/Aditya-KV"><img src="https://ghchart.rshah.org/1f6f57/Aditya-KV" alt="Contribution graph" width="100%" /></a>
</div>

---

### Contact

<div align="center">

<a href="mailto:adityakvnov05@gmail.com"><img src="https://img.shields.io/badge/Email-adityakvnov05%40gmail.com-a8e3c4?style=for-the-badge&logo=gmail&logoColor=0d3b30" alt="Email Aditya" /></a>
<a href="https://github.com/Aditya-KV"><img src="https://img.shields.io/badge/GitHub-Aditya--KV-1f6f57?style=for-the-badge&logo=github&logoColor=white" alt="Aditya-KV on GitHub" /></a>

</div>
