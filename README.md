<div align="center">

# Никита Маначинский

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2196F3&center=true&vCenter=true&width=435&lines=Android+Developer+(Kotlin);Mobile+Engineer;Fan+of+Clean+Architecture;Building+Full-cycle+Products" alt="Typing SVG" />
</a>

**Android Engineer** · 4 курс ЮФУ (выпуск 2026) · Ростов-на-Дону, Россия (Открыт для переезда и удаленной работы)

Ищу **стажировку / Junior** позиции.
Специализируюсь на **нативном Android**, **Kotlin Multiplatform** с  **Clean Architecture** и **Modern Android Development (MAD)**.
<br/>
Интересуют продукты со сложной бизнес-логикой и высокими требованиями к архитектуре.

<p>
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white" />
  <img alt="Android" src="https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white" />
  <img alt="Jetpack Compose" src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat&logo=jetpackcompose&logoColor=white" />
  <img alt="Coroutines / Flow" src="https://img.shields.io/badge/Coroutines%20%2F%20Flow-0095D5?style=flat&logo=kotlin&logoColor=white" />
  <img alt="Room" src="https://img.shields.io/badge/Room-3DDC84?style=flat&logo=android&logoColor=white" />
  <img alt="Hilt" src="https://img.shields.io/badge/Hilt-00C853?style=flat&logo=dagger&logoColor=white" />
  <img alt="WorkManager" src="https://img.shields.io/badge/WorkManager-795548?style=flat&logo=android&logoColor=white" />
</p>

<p>
  <img alt="Ktor" src="https://img.shields.io/badge/Ktor-000000?style=flat&logo=ktor&logoColor=white" />
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white" />
  <img alt="BLE" src="https://img.shields.io/badge/BLE%20%2F%20IoT-0082FC?style=flat&logo=bluetooth&logoColor=white" />
</p>

[![Resume](https://img.shields.io/badge/Резюме-PDF-blue?style=for-the-badge&logo=adobeacrobatreader)](https://github.com/nmanachinsky/nmanachinsky/blob/main/docs/Nikita_Manachinsky_Android_Dev.pdf) [![HH.ru](https://img.shields.io/badge/HH.ru-Profile-red?style=for-the-badge&logo=headhunter)](https://rostov.hh.ru/resume/f8bf939fff0ff813ee0039ed1f6d78366a314e) [![Telegram](https://img.shields.io/badge/Telegram-Написать_мне-2CA5E0?style=for-the-badge&logo=telegram)](https://t.me/nikirO1) [![Email](https://img.shields.io/badge/Email-manachinsky88@gmail.com-D14836?style=for-the-badge&logo=gmail)](mailto:manachinsky88@gmail.com)
</div>

---

## 🛠 Технический Арсенал

Я не просто использую библиотеки, я понимаю, как они работают под капотом.

- **Android:** Kotlin, Jetpack Compose, Navigation, Custom Views.
- **System Design:** Clean Architecture, Multi-module (feature-api/impl), Offline-first.
- **Concurrency:** Coroutines, Flow, Channels, работа с Race Conditions.
- **Data & Network:** Room, DataStore, Retrofit, Ktor Client, WebSocket.
- **Backend & IoT:** Ktor Server, Supabase (Postgres/RLS), Docker, C/C++ (ESP32 Firmware), BLE Protocol Design.

---

## 🏆 Избранные проекты (Portfolio)

### 1️⃣ Amulet — Full-cycle IoT Ecosystem (Hardware + Android + Cloud)

> **Моя гордость.** Полный цикл разработки: от пайки железа и прошивки на С++ до мобильного приложения и бэкенда.

**Суть:** Экосистема для тактильной коммуникации на расстоянии. Устройство синхронизируется с телефоном по BLE v2.0, передает паттерны через сервер партнеру.

<div align="center">
 
<table>
  <tr>
    <td align="center"><b>Demo & BLE Sync</b><br><img src="gif/VID_20260124201019.gif" width="200" alt="Amulet demo" /></td>
    <td align="center"><b>Dashboard</b><br><img src="screenshots/home-guest-dashboard.jpg" width="200" alt="Главный экран" /></td>
    <td align="center"><b>Interaction</b><br><img src="screenshots/hugs-pair.jpg" width="200" alt="Объятия" /></td>
    <td align="center"><b>Logic Editor</b><br><img src="screenshots/timeline-editor-paint.jpg" width="200" alt="Редактор" /></td>
  </tr>
</table>

</div>

**Ключевые инженерные решения:**
- **Модульная архитектура:** `:core`, `:data`, `:feature` с четким разделением ответственности.
- **Kotlin Multiplatform:** Общая бизнес-логика вынесена в Shared модуль.
- **Сложный BLE:** Реализован собственный менеджер очереди команд (Command Queue), защита от потери пакетов, OTA-обновление прошивки.
- **Отказоустойчивость:** Offline-first подход (Outbox pattern) через WorkManager — данные уходят на сервер, когда появляется сеть.

🔗 **Ссылки:** [Android App](https://github.com/nmanachinsky/amulet_android_app) | [Backend](https://github.com/nmanachinsky/amulet_backend) | [Firmware](https://github.com/nmanachinsky/Amulet_Firmware)

---

### 2️⃣ P2P Analytics Platform — Data Engineering & Infrastructure

 **Тип:** Инфраструктурный Big Data проект
 
 Разработка и деплой платформы для сбора, обработки и анализа данных. Проект демонстрирует навыки работы со сложными распределенными системами и контейнеризацией.
 
 <div align="center">
 
 <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
 <img alt="Apache Airflow" src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white" />
 <img alt="Apache Spark" src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white" />
 <img alt="HDFS" src="https://img.shields.io/badge/Apache%20Hadoop-66CCFF?style=flat&logo=apachehadoop&logoColor=black" />
 <img alt="MinIO" src="https://img.shields.io/badge/MinIO-C72E49?style=flat&logo=minio&logoColor=white" />
 <img alt="MLflow" src="https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white" />
 <img alt="Apache Superset" src="https://img.shields.io/badge/Apache%20Superset-1FA8C9?style=flat&logo=apachesuperset&logoColor=white" />
 <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
 
 </div>
 
 <details>
 <summary><b>Схема архитектуры (Mermaid)</b></summary>
 
 ```mermaid
 graph TD
     subgraph Источник Данных
         A[PostgreSQL] --> B{HDFS - Landing Zone};
     end
 
     subgraph ETL-пайплайн на Spark
         B --> C[Delta Lake - Bronze];
         C --> D[Delta Lake - Silver];
         D --> E{DQ Checks};
         E -- OK --> F[Delta Lake - Gold Витрины];
         F --> G[BI-аналитика];
         D --> H[ML Scoring];
     end
 
     subgraph MLOps-цикл
         I[JupyterLab] --> J(MLflow Server);
         J --> K[MinIO S3];
         J --> L[PostgreSQL MLflow];
         J --> H;
     end
 
     subgraph Аналитика и Визуализация
         H --> M[Delta Lake - Predictions];
         G(Apache Superset) --> F;
         G --> M;
     end
 
     style A fill:#D6EAF8,stroke:#333,stroke-width:2px
     style G fill:#D5F5E3,stroke:#333,stroke-width:2px
     style I fill:#FCF3CF,stroke:#333,stroke-width:2px
 ```
 
 </details>
 
 - **Задачи:** Настройка ETL-пайплайнов, оркестрация процессов, организация Data Lake.
 - **Стек:** Docker Compose, Apache Airflow, Apache Spark, HDFS, PostgreSQL, MinIO.
 - **Результат:** Реализована "Медальонная архитектура" (Bronze/Silver/Gold layers), обеспечивающая полный цикл жизни данных от сырого вида до BI-витрин.

🔗 **Репозиторий:** [github.com/BUka228/p2p-analytics-platform](https://github.com/nmanachinsky/p2p-analytics-platform)

---

### 3️⃣ ProgressQuest — Productivity & Gamification

Классическое Android-приложение, демонстрирующее **Clean Architecture** и **Modern Android Development (MAD)**.

- **UI:** 100% Jetpack Compose + Material 3.
- **Tech:** Hilt, Room, Firebase (Auth, Cloud Functions).
- **Фича:** Геймификация задач (RPG-система) с синхронизацией в реальном времени.

🔗 **Репозиторий:** [github.com/BUka228/ProgressQuest](https://github.com/nmanachinsky/ProgressQuest)

---

## 📈 GitHub Stats

<div align="center">
<img height="160" src="https://github-readme-stats-oxyk.vercel.app/api?username=nmanachinsky&show_icons=true&hide_title=true&rank_icon=github&theme=tokyonight&cache_seconds=21600" />
<img height="160" src="https://github-readme-stats-oxyk.vercel.app/api/top-langs/?username=nmanachinsky&layout=compact&theme=tokyonight&cache_seconds=21600" />
</div>
