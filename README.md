<div align="center">

# Javier Santamaría Pascual

**Ingeniería Informática · Último año**

Desarrollo full stack · Sistemas embebidos · Inteligencia artificial

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/javier-santamaria-pascual-871597213/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:javiersantamariapascual04@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/javiers2004)

</div>

---

## Sobre mí

Trabajo en la frontera entre el software y el hardware. Lo que me interesa no es una capa concreta de la pila, sino el sistema completo: el microcontrolador que lee un sensor, el firmware que garantiza que esa lectura llega íntegra, el modelo que la interpreta y la interfaz desde la que alguien toma una decisión con ella.

Esa forma de trabajar viene de moverme entre dos mundos que rara vez se juntan. Por un lado, laboratorios remotos y firmware bare-metal, donde un error de temporización se mide en microsegundos y no hay stack trace que te salve. Por otro, machine learning aplicado a problemas industriales reales, donde el dato llega sucio, desbalanceado e incompleto, y la precisión del modelo importa menos que saber justificar su predicción.

Mi objetivo a corto plazo es llevar esa combinación a producción: sistemas de IA que no se queden en el notebook.

**En qué estoy ahora**

- Construyendo un **SaaS de mantenimiento industrial con IA**, que combina RAG sobre documentación técnica con telemetría de sensores en tiempo real.
- Especializándome en **agentes de IA, sistemas RAG y reinforcement learning**.
- Profundizando en **arquitecturas cloud** y en el despliegue de sistemas de ML en producción.
- Abierto a **prácticas, proyectos y colaboraciones** — especialmente donde el software toque hardware real.

---

## Proyectos destacados

### Proyecto-RAG — Consulta de documentación industrial

[![Repo](https://img.shields.io/badge/Ver_repositorio-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/javiers2004/Proyecto-RAG)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

Sistema de *retrieval-augmented generation* que permite preguntar en lenguaje natural sobre documentación de maquinaria industrial — manuales, especificaciones, procedimientos de mantenimiento — y devuelve la respuesta **citando la fuente exacta**.

La trazabilidad es el punto central del diseño: en un entorno industrial, una respuesta sin referencia verificable no es utilizable. Cada afirmación del modelo queda anclada al fragmento de documento del que proviene.

### Free-Fall Remote Experiment — Laboratorio remoto con STM32 y Raspberry Pi 5

[![Repo](https://img.shields.io/badge/Ver_repositorio-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/javiers2004/Free-Fall-Remote-Experiment-STM32-RaspberryPi5)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)

Firmware para la liberación controlada de un objeto y la medición de su tiempo de tránsito entre barreras de sensores, pensado para que un estudiante pueda ejecutar el experimento físico de forma remota.

Un proyecto donde la ingeniería está en los detalles que no se ven: eliminar el rebote de los sensores, garantizar que el mecanismo de liberación sea reproducible y asegurar que la medida temporal no dependa de la latencia del sistema que la reporta.

### Unity-RL-Controller — Orquestación de entrenamientos de RL

[![Repo](https://img.shields.io/badge/Ver_repositorio-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/javiers2004/Unity-RL-Controller)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

Librería y CLI para gestionar entrenamientos de reinforcement learning sobre entornos de Unity, construida para dejar de lanzar experimentos a mano.

Cubre el ciclo completo — lanzamiento, configuración y seguimiento — con el objetivo de que un entrenamiento sea reproducible a partir de su configuración, no del recuerdo de qué flags se usaron aquella vez.

### Electric-Arc-Furnace-Prediction — Analítica de proceso siderúrgico

[![Repo](https://img.shields.io/badge/Ver_repositorio-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/javiers2004/Electric-Arc-Furnace-Prediction)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

Predicción de la temperatura y la composición de azufre en un horno de arco eléctrico a partir de datos de proceso.

Un caso representativo de ML industrial: señales ruidosas, variables acopladas entre sí y un coste de error asimétrico, donde equivocarse por arriba y por abajo no sale igual de caro.

---

## Más proyectos

<details>
<summary><b>Inteligencia artificial y machine learning</b></summary>

<br/>

| Proyecto | Descripción |
|---|---|
| [**ImageCLEFmed-Caption**](https://github.com/javiers2004/ImageCLEFmed-Caption) | Réplica del reto ImageCLEFmedical Caption 2025 sobre el dataset ROCOv2: generación de descripciones para imagen médica. |
| [**Beans_classification**](https://github.com/javiers2004/Beans_classification) | Análisis del desbalanceo de clases en clasificación multiclase sobre el Dry Bean dataset, con ensembles y optimización de hiperparámetros con Optuna. |
| [**RL-E1-CrossTheRoad**](https://github.com/javiers2004/RL-E1-CrossTheRoad) | Entorno tipo Frogger donde agentes tabulares aprenden a cruzar una carretera y un río, comparando Q-Learning, SARSA y Expected SARSA. |
| [**Snake_env**](https://github.com/javiers2004/Snake_env) | Entorno de reinforcement learning sobre el juego de la serpiente. |
| [**ImageGenerator2026**](https://github.com/javiers2004/ImageGenerator2026) | DCGAN entrenada sobre CelebA para generar rostros a partir de ruido. |
| [**Appliances-Energy-Prediction**](https://github.com/javiers2004/Appliances-Energy-Prediction) | Previsión de series temporales de consumo energético doméstico. |
| [**Movie-Recommendation-System**](https://github.com/javiers2004/Movie-Recommendation-System) | Sistema de recomendación de películas. |
| [**Titanic — ML from Disaster**](https://github.com/javiers2004/Titanic---Machine-Learning-from-Disaster) | Solución documentada a la competición clásica de Kaggle. |

</details>

<details>
<summary><b>Hardware, sistemas embebidos y laboratorios remotos</b></summary>

<br/>

| Proyecto | Descripción |
|---|---|
| [**Sustained-Pulse-FPGA**](https://github.com/javiers2004/Sustained-Pulse-FPGA) | Laboratorio remoto que permite controlar dispositivos electrónicos y cargar programas en una FPGA a distancia. |
| [**stm32f0-dfrobot-4digit7segment**](https://github.com/javiers2004/stm32f0-dfrobot-4digit7segment-display) | Control de un display de 7 segmentos sobre I²C desde un STM32F0 con HAL, hablando directamente con el driver TM1650 y sin capa Arduino. |

</details>

<details>
<summary><b>Software, web y fundamentos</b></summary>

<br/>

| Proyecto | Descripción |
|---|---|
| [**TrabajoGrupoProgIII — Cantares de Iberia**](https://github.com/javiers2004/TrabajoGrupoProgIII-CantaresDeIberia) | Videojuego 2D en Java con monstruos, niveles y sistema de puntuación. |
| [**TrabajoProgIV — MessageApp**](https://github.com/javiers2004/TrabajoProgIV-MessageApp) | Gestión de usuarios, conversaciones y comentarios en un sistema interactivo con estadísticas. |
| [**Apple-Worm**](https://github.com/javiers2004/Apple-Worm) | Juego en Python y Pygame: recolección de objetivos, obstáculos y progresión por niveles. |
| [**ClassNote**](https://github.com/javiers2004/ClassNote) | Herramienta de gestión de apuntes. |

</details>

---

## Stack técnico

<table>
<tr>
<td><b>Lenguajes</b></td>
<td>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

</td>
</tr>
<tr>
<td><b>IA y datos</b></td>
<td>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![Optuna](https://img.shields.io/badge/Optuna-2E4756?style=flat-square)
![Gymnasium](https://img.shields.io/badge/Gymnasium-0081A5?style=flat-square)

</td>
</tr>
<tr>
<td><b>Web y backend</b></td>
<td>

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
<tr>
<td><b>Hardware y sistemas</b></td>
<td>

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![FPGA](https://img.shields.io/badge/FPGA-1C1C1C?style=flat-square)

</td>
</tr>
<tr>
<td><b>Herramientas</b></td>
<td>

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</td>
</tr>
</table>

---

## Contacto

Si algo de lo que hay aquí te encaja — una práctica, un proyecto, una colaboración o simplemente una conversación sobre IA aplicada o sistemas embebidos — escríbeme.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Conectar_en_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/javier-santamaria-pascual-871597213/)
[![Email](https://img.shields.io/badge/Enviar_un_email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:javiersantamariapascual04@gmail.com)

</div>
