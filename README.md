# Hola, soy Leandro 👋

Desarrollador de software de Chile y estudiante de Ingeniería Civil en Informática y Telecomunicaciones (UDP). Me interesa construir sistemas que funcionen de punta a punta: desde los datos y el modelo hasta la API, el contenedor y el despliegue. Últimamente, integrar agentes de IA en software real, con reglas de negocio que el modelo no puede romper y tests que no dependen de la API.

## Tecnologías

![C#](https://img.shields.io/badge/C%23-.NET-512BD4?logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vuedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?logo=apachespark&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![OpenRouter](https://img.shields.io/badge/OpenRouter-LLM-6566F1)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

## Proyectos destacados

| Proyecto | Qué es | Stack |
|----------|--------|-------|
| [agentes-php](https://github.com/DHat3r/agentes-php) | Tres aplicaciones con agentes de IA (*tool calling* real) sobre un mismo núcleo: evaluador de respuestas, tutor adaptativo de matemáticas y conciliación bancaria. Las reglas de negocio viven en las herramientas, no en el prompt. 158 tests con un LLM simulado y CI | PHP 8, Laravel, Slim, OpenRouter, Vue 3, PostgreSQL, Redis, Docker |
| [InventoryManagement](https://github.com/DHat3r/InventoryManagement) | API REST de inventario para pymes: kardex valorizado, flujo de aprobación de productos (Inventario propone, Admin aprueba y define el precio), JWT con refresh tokens y 4 roles de negocio, y panel web en React. 73 tests contra PostgreSQL real (Testcontainers) y CI con 69,7 % de cobertura | C#, .NET 8, PostgreSQL, React, Docker |
| [Banco Futura](https://github.com/DHat3r/Banco-Futura-Servicio) | Predicción de fuga de clientes (XGBoost, AUC 0,95) y análisis de sentimiento de reclamos con BETO, entrenado con 13 mil reseñas reales de apps de bancos. Pipeline medallion en Databricks, API de scoring y panel, todo con `docker compose up`, tests y CI | Python, Databricks, FastAPI, React, Docker |
| [Sistemas2](https://github.com/DHat3r/Sistemas2) · [Sistemas3](https://github.com/DHat3r/Sistemas3) | Sistemas Distribuidos (UDP), con Gonzalo Gaete. Un LLM responde preguntas de Yahoo Answers y otro evalúa sus respuestas frente a las humanas (*LLM-as-a-judge*), sobre Kafka con reintentos en Flink. La entrega 3 agrega análisis lingüístico offline con Hadoop y Pig | Python, Kafka, Flink, Hadoop, Pig, PostgreSQL, Redis |

## En qué estoy trabajando

- 🤖 agentes-php: siguiente paso, reescribir yo mismo el ciclo del agente a partir de sus tests, para entenderlo línea por línea.
- 🛠️ InventoryManagement: despliegue público con demo, y después caché con Redis y módulos de proveedores y pedidos.
- 🔭 Banco Futura: registrar los modelos con MLflow y desplegar la demo.

## Contacto

- GitHub: [@DHat3r](https://github.com/DHat3r)
- LinkedIn: [leandro-alberto-norambuena-paine](https://www.linkedin.com/in/leandro-alberto-norambuena-paine/)
