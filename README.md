# 👋 ¡Hola! Soy Obed Luna Velázquez

Psicólogo clínico en transición al desarrollo de software, apasionado por la inteligencia artificial, el desarrollo de chatbots, el análisis de datos y la creación de soluciones digitales innovadoras, con un interés particular en aplicaciones para la salud mental.

## 🧠 Habilidades Técnicas

* **Lenguajes:** Python (Avanzado), JavaScript (Básico), HTML/CSS (Básico)
* **IA & Chatbots:** OpenAI API (GPT-3.5/4), Google Gemini API, DeepSeek API, LangChain (Básico), Diseño de Prompts
* **Desarrollo Backend/General:** Manejo de APIs REST, JSON, Persistencia de Datos (JSON), Regex (`re`)
* **Desarrollo Frontend/GUI:** Tkinter (`ttk`), Streamlit (Básico)
* **Concurrencia:** `threading`, `queue` (para UI responsiva)
* **Herramientas y Control de Versiones:** Git, GitHub, Visual Studio Code
* **Otros:** Metodologías Ágiles (Conceptual), Resolución de Problemas

## 🔧 Proyectos Destacados

### 🤖 Micro Calabozos y Chatbots (RPG de Texto con IA como DM)

* **[Enlace al Repositorio en GitHub]([(https://github.com/obedlunavel/chatbot-calabozos-y-dragones)])**
* **Descripción:** Un juego de rol (RPG) conversacional de texto inspirado en Dungeons & Dragons, desarrollado en Python con una interfaz gráfica creada usando Tkinter y `ttk`. Este proyecto utiliza múltiples APIs de Modelos de Lenguaje Grandes (OpenAI GPT-3.5, Google Gemini, DeepSeek) para que una IA actúe como Dungeon Master (DM), generando narrativas dinámicas, gestionando eventos del juego y respondiendo a las acciones del jugador en tiempo real.
* **Tecnologías y Características Demostradas:**
    * **Integración Multi-API:** Conexión y gestión de múltiples APIs de LLM con rotación automática (`HybridAIConnector`, `python-dotenv`).
    * **GUI Responsiva:** Interfaz gráfica creada con **Tkinter/ttk**, mantenida fluida durante llamadas API mediante **`threading`** y **`queue`**.
    * **Gestión de Estado y Persistencia:** Implementación de estadísticas de personaje (HP, Stats, Nivel, XP), inventario y contexto de juego, con guardado y cargado automático/manual a archivos **JSON**.
    * **Procesamiento de Lenguaje Natural (Básico):** Parseo de respuestas de la IA usando **Regex (`re`)** para extraer información estructurada (daño, curación, XP, ítems) y actualizar el estado del juego.
    * **Lógica de Juego RPG:** Sistema de niveles, inventario básico con uso de objetos (pociones) y manejo de comandos de jugador (`/inv`, `/usar`, `/stats`, `/save`, `/load`, `/help`).
    * **Código Modular:** Separación de la lógica de conexión API en una clase reutilizable.
    * **Desarrollo con Python:** Aplicación completa demostrando manejo de módulos estándar y librerías externas.
