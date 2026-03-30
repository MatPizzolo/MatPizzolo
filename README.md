<p align="center">
  <a href="https://github.com/MatPizzolo/MatPizzolo/blob/main/readmes/readme.es.md">
    <img src="https://img.shields.io/badge/lang-es-yellow.svg" alt="Spanish">
  </a>
</p>
<h1 align="center"><b>Hi, I'm Mateo Pizzolo</b> <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1>

<p align="center">
  <b>MLOps & Machine Learning Engineer</b><br>
</p>

## 📖 **About Me**
- 🤖 **MLOps & Infrastructure:**
  I specialize in bridging the gap between local model experimentation and resilient, production-grade deployments, whether in the cloud or at the edge.
  
- 🏗️ **Engineering Foundation:**
	My approach to architecture is rooted in **Systems Programming (C/C++)** from **42 Madrid** and extensive **Full-Stack Development** experience within the FinTech and Crypto industries.

- 🚀 **Builder at Heart:**
	Beyond corporate roles, I actively design self-hosted open-source platforms and architect event-driven pipelines to solve complex, real-world physical problems.

- 🏄‍♂️ **Outside of Code:**
	Intermediate rock/jazz drummer and surfer.

- 📄 **My Resume:** [View Resume](https://docs.google.com/document/d/1BQan3iunXthCLceiRWkLKzzh42Nb4q0TndGyF_pXBww/edit?usp=sharing)

---

## 🛠 **Technical Stack**

### **Machine Learning & Data Science**
- **Core Frameworks:** PyTorch, TensorFlow, Keras, Scikit-learn, Hugging Face.
- **Data Engineering:** Pandas, Matplotlib, Seaborn.
- **Domain-Specific:** YOLOv8 / ONNX (Computer Vision), Demucs, Librosa, madmom (Audio/Signal Processing).

### **MLOps, Orchestration & Observability**
- **Pipelines & Queues:** Apache Airflow (DAGs), Celery, Redis.
- **Infrastructure & CI/CD:** Docker, Docker Compose, GitHub Actions, Linux/Bash.
- **Observability:** OpenTelemetry, Prometheus, structlog.

### **Backend & Distributed Systems**
- **Languages:** Python, C, C++, TypeScript, JavaScript.
- **APIs & Frameworks:** FastAPI, Node.js, Django.
- **Databases:** PostgreSQL, TimescaleDB, MongoDB, SQLite.

### **Front-End & Client Interfaces**
- **Core:** Next.js, React 19, Tailwind CSS, Material UI.
- **ML Interfaces:** Streamlit.


## 🚀 **Featured Machine Learning Projects**

### 🥁 [Automatic Drum Transcriber](https://github.com/MatPizzolo/Automatic-Drum-Transcription)
*Signal processing and ML for musical notation.*
- **The Core:** Converting percussive audio signals into digital drum tabs using onset detection and pattern recognition.
- **Machine Learning:** Orchestrated a multi-stage pipeline using **Demucs** for source separation, a **Keras CNN** for hit classification, and **madmom/librosa** for BPM detection, quantizing the output with **music21**.
- **Engineering:** Built a decoupled asynchronous architecture using **FastAPI** and **Celery**, isolating memory-intensive ML inference workers from I/O workers to prevent OOM failures, complete with atomic file writes and OpenTelemetry observability.
- **Impact:** Automates the transcription process for complex percussive patterns, bridging the gap between raw audio and readable sheet music.
- **Tech Stack:** Python, FastAPI, Next.js, Celery, Redis, PostgreSQL, Keras, Demucs, Librosa, Docker, OpenTelemetry.

### 🌊 [Swell-Drift](https://github.com/MatPizzolo/swell-drift) *(Work in Progress)*
*Edge-based computer vision and MLOps pipeline for localized coastal intelligence.*
- **The Core:** Calculating forecast drift by orchestrating a continuous feedback loop between global wave APIs and live beach webcams.
- **Machine Learning:** Running lightweight object detection models (YOLOv8) at the edge to classify real-time coastal conditions and wave textures.
- **Engineering:** Built an autonomous, event-driven architecture to ingest streaming data and compute localized weather deviations.
- **Impact:** Acts as a headless intelligence system that corrects global weather model biases using real-time edge inference, triggering custom alerts.
- **Tech Stack:** Python, ONNX / YOLOv8 (Edge CV), Docker, GitHub Actions (CI/CD), PostgreSQL / TimescaleDB.

---

## 🏫 **Anyone AI Sprints: Machine Learning Academy**
*Foundational Data Engineering and Machine Learning pipelines.*

<details>
<summary><b>View Anyone AI Sprints</b></summary>
<br>

### 🛒 [Best Buy Product Classification](https://github.com/MatPizzolo/Sprint4_AnyoneAi)
*A multimodal machine learning system for e-commerce product categorization.*
- **The Core:** Developed a multimodal classification system that intelligently combines both product images and text descriptions to accurately categorize Best Buy inventory.
- **Machine Learning:** Leveraged transfer learning to extract complex embeddings using pre-trained CNNs (ResNet50) and transformers (ConvNextV2, MiniLM), fusing features to train high-performing classifiers.
- **Engineering:** Structured a modular, containerized pipeline enforcing robust code quality and test-driven reliability.
- **Tech Stack:** Python, TensorFlow, Hugging Face, Docker, Pytest, Black.

### 🖼️ [FastAPI ML App - Image Classification](https://github.com/MatPizzolo/Sprint3_AnyoneAi)
*A microservices-based image classification system.*
- **The Core:** Built a robust, containerized microservices architecture for REST APIs and asynchronous message queuing between services.
- **Machine Learning:** Integrated a pre-trained CNN model capable of identifying over 1000 categories, featuring a seamless front-end for user interaction.
- **Engineering:** Managed user and feedback data with relational databases, orchestrated the environment, and ensured system reliability under load.
- **Tech Stack:** Python, FastAPI, Redis, TensorFlow, Streamlit, PostgreSQL, Docker Compose, Locust, Pytest.

### 💳 [Home Credit Default Risk Prediction](https://github.com/MatPizzolo/Sprint2_AnyoneAi)
*Financial risk assessment based on the Home Credit Group Kaggle competition.*
- **The Core:** Developed an end-to-end pipeline to assess financial risk and predict loan repayment ability for leading institutions.
- **Machine Learning:** Engineered features and trained binary classification models using **Scikit-learn** to accurately predict credit default risk, optimizing for ROC-AUC metrics.
- **Engineering:** Built robust data preprocessing pipelines using **Pandas** to clean, handle missing values, encode categorical variables, and transform large-scale tabular data.
- **Tech Stack:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Jupyter, Pytest.
  
### 🏗️ [E-Commerce Data Engineering Environment](https://github.com/MatPizzolo/Sprint1_AnyoneAi)
*A complete Data Engineering environment for scalable AI.*
- **The Core:** Designed and implemented a scalable data environment to support interactive data science and machine learning workflows.
- **Data Engineering:** Orchestrated an automated ETL pipeline to process raw e-commerce data and load it into a structured relational database.
- **MLOps:** Provided a reliable, containerized workspace tailored for model experimentation and streamlined development.
- **Tech Stack:** Python, Apache Airflow, SQLite, Docker, Jupyter.

</details>


</details>


## 🏫 **The 42 Madrid Journey**
*Lower-level systems engineering and performance optimization.*

<details>
<summary><b>View all 42 Projects (C/C++)</b></summary>

| 🌟 Project | Description |
|:--- |:--- |
| [**📚 Libft**](https://github.com/MatPizzolo/my-libft) | C standard library recreation |
| [**✍🏼 Ft_printf**](https://github.com/MatPizzolo/ft_printf) | Recreation of printf() |
| [**⏩ Get_next_line**](https://github.com/MatPizzolo/GNL) | Efficient file reading buffer |
| [**🤖 Born2beroot**](https://github.com/MatPizzolo/born2beroot) | Virtualization & SysAdmin |
| [**👾 So_long**](https://github.com/MatPizzolo/Solong) | 2D Game in C (minilibx) |
| [**🗜 Pipex**](https://github.com/MatPizzolo/Pipex) | Bash pipe implementation |
| [**🔢 Push_swap**](https://github.com/MatPizzolo/push_swap) | Sorting algorithm optimization |
| [**🖥 Minishell**](https://github.com/MatPizzolo/minishell) | [cite_start]Bash-like shell in C  |
| [**🍴 Philosophers**](https://github.com/MatPizzolo/philosophers) | Threading & Mutexes |
| [**🕹️ Cub3D**](https://github.com/MatPizzolo/cub3d) | 3D Raycaster in C |
| [**🧱 C++ Modules**](https://github.com/MatPizzolo/cpp-modules-5-9) | OOP, Templates, & STL |
| [**🌐 Ft_IRC**](https://github.com/MatPizzolo/ft_irc) | [cite_start]IRC Server in C++98 |
| [**💽 Inception**](https://github.com/MatPizzolo/Inception) | Multi-container Docker system |
| [**🏓 Trascendence**](https://github.com/MatPizzolo/ft_transcendence) | [cite_start]WebApp with AI opponent  |
| [**📟 Ft_Ping**](https://github.com/MatPizzolo/ft_ping) | Ping command recreation |
| [**⛓️ Tokenizer**](https://github.com/MatPizzolo/Tokenizer) | ERC-20 Token development |
| [**📜 Ft_Ls**](https://github.com/MatPizzolo/ft_ls) | ls() command recreation |
| [**🏓 Ft_Malloc**](https://github.com/MatPizzolo/ft_malloc) | Dynamic memory allocation |
| [**🖼️ Camagru**](https://github.com/MatPizzolo/Camagru) | Web app with image processing |

</details>

## 📫 Contact
<div align='left'>

<ul>

<div>
    <a href="https://linkedin.com/in/mateo-pizzolo" target="_blank">
    <img src="https://img.shields.io/badge/linkedin:  mateo/pizzolo-%2300acee.svg?color=405DE6&style=for-the-badge&logo=linkedin&logoColor=white" alt=linkedin style="margin-bottom: 5px;"/>
</a>
</div>

<br>

<div>
<a href="mailto:matpizzolo@gmail.com" target="_blank">
<img src="https://img.shields.io/badge/gmail:  matpizzolo-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white" t=mail style="margin-bottom: 5px;" />
</a>
</div>
	
</ul>
</div>
