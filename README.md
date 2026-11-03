<h1 align="center">Hi, I'm Nusrat Begum</h1>

<p align="center">
  <b>Full-stack web developer in Bangkok</b> · FastAPI · React · TypeScript · PostgreSQL<br>
  M.Sc. Computer Science, Mahidol University (MUICT) · First author, IEEE JCSSE 2026
</p>

<p align="center">
  <a href="https://nusratbegum.dev"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-nusratbegum.dev-111827?style=for-the-badge"></a>
  <a href="https://www.linkedin.com/in/nusrat-begum/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-nusrat--begum-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://ieeexplore.ieee.org/document/11596765"><img alt="IEEE paper" src="https://img.shields.io/badge/IEEE-JCSSE_2026_paper-00629B?style=for-the-badge&logo=ieee&logoColor=white"></a>
  <a href="https://medium.com/@rupunzelnusrat5"><img alt="Medium" src="https://img.shields.io/badge/Medium-articles-000000?style=for-the-badge&logo=medium&logoColor=white"></a>
</p>

Nusrat builds and deploys web apps end to end: typed REST APIs in FastAPI, React and TypeScript front ends, PostgreSQL schemas, tests and CI, all live on Vercel. Her master's thesis turned into a drift-detection library for ML monitoring, published at IEEE JCSSE 2026. She is now learning cloud and distributed systems: Kubernetes, AWS, GCP, Redis and microservices.

## Featured projects

Every project below is live, and each repo has a README that explains how it works.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://stocksense-demo-mauve.vercel.app"><img src="https://raw.githubusercontent.com/NusratBegum/stocksense/main/docs/dashboard-light.png" alt="StockSense dashboard"></a>
      <h3><a href="https://github.com/NusratBegum/stocksense">StockSense</a></h3>
      Inventory and order dashboard for small online shops. Stock rows are locked per order, so 16 parallel orders against 10 units never oversell. Idempotent order creation, channel analytics, 13 pytest tests on PostgreSQL.<br><br>
      <code>FastAPI</code> <code>PostgreSQL</code> <code>React</code> <code>TypeScript</code><br><br>
      <a href="https://stocksense-demo-mauve.vercel.app"><b>Live demo</b></a> · <a href="https://stocksense-api-nine.vercel.app/docs">API docs</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://eadd-demo.vercel.app"><img src="https://raw.githubusercontent.com/NusratBegum/eadd/main/docs/demo.png" alt="EADD drift detection demo"></a>
      <h3><a href="https://github.com/NusratBegum/eadd">EADD drift detector</a></h3>
      Master's thesis: label-free drift detection for ML features. Caught all 4 synthetic drift types with zero false alarms, and more drift types than D3 on 13 real-world streams (sign test p = 0.001). A clear drift is confirmed after 20 of 199 permutations.<br><br>
      <code>Python</code> <code>LightGBM</code> <code>SHAP</code> <code>pytest</code><br><br>
      <a href="https://eadd-demo.vercel.app"><b>Live demo</b></a> · <a href="https://ieeexplore.ieee.org/document/11596765">Paper</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://nusrat-diabetes-api.vercel.app"><img src="https://raw.githubusercontent.com/NusratBegum/Diabetes-Prediction/main/docs/web-client.png" alt="Diabetes risk API web client"></a>
      <h3><a href="https://github.com/NusratBegum/Diabetes-Prediction">Diabetes Risk API</a></h3>
      scikit-learn model behind a validated FastAPI service with a web form. ROC AUC 0.83 and 76% accuracy on held-out data, with CI on every push.<br><br>
      <code>FastAPI</code> <code>Pydantic</code> <code>scikit-learn</code><br><br>
      <a href="https://nusrat-diabetes-api.vercel.app"><b>Live demo</b></a>
    </td>
    <td width="50%" valign="top">
      <a href="https://bangkok-air-quality.vercel.app"><img src="https://raw.githubusercontent.com/NusratBegum/Data-Science-Final-Project/main/docs/dashboard.png" alt="Bangkok air quality dashboard"></a>
      <h3><a href="https://github.com/NusratBegum/Data-Science-Final-Project">Bangkok Air Quality Tracker</a></h3>
      Scheduled GitHub Actions pipeline that has collected 570 days of PM2.5 readings for Bangkok, Beijing and Los Angeles since March 2025, with a live dashboard.<br><br>
      <code>Python</code> <code>pandas</code> <code>GitHub Actions</code> <code>Chart.js</code><br><br>
      <a href="https://bangkok-air-quality.vercel.app"><b>Live dashboard</b></a>
    </td>
  </tr>
</table>

More projects:

| Project | What it is | Live |
|---|---|---|
| [QueueFlow](https://github.com/NusratBegum/queueflow) | Walk-in queue app for clinics: customers join from their phone and see their place in line; `SKIP LOCKED` stops two counters calling the same person; 14 pytest tests | [Demo](https://queueflow-demo.vercel.app) |
| [Smart Calculator API](https://github.com/NusratBegum/smart-calculator) | Authenticated REST API and web client: OAuth2 with JWT and bcrypt, per-user history, 20 pytest tests and a Docker build in CI | [Demo](https://smart-calculator-api.vercel.app) |
| [Portfolio site](https://github.com/NusratBegum/portfolio) | Scroll-driven 3D portfolio in React, TypeScript, Three.js and GSAP; 3D model cut from 10 MB to 0.8 MB (−92%) | [nusratbegum.dev](https://nusratbegum.dev) |

## Tech stack

**Backend:** ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?logo=pydantic&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=white)

**Frontend:** ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000000?logo=threedotjs&logoColor=white)

**Data:** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)

**Tooling:** ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

**Learning now:** Kubernetes · AWS · GCP · Redis · microservices

## Contact

Open to full-stack, backend and software engineering roles in Bangkok. Reach Nusrat on [LinkedIn](https://www.linkedin.com/in/nusrat-begum/) or at [rupunzelnusrat5@gmail.com](mailto:rupunzelnusrat5@gmail.com).
