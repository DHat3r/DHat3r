# Hola, soy Leandro 👋

Desarrollador de software de Chile y estudiante de Ingeniería Civil en Informática y Telecomunicaciones (UDP). Me interesa construir sistemas que funcionen de punta a punta: desde los datos y el modelo hasta la API, el contenedor y el despliegue. Últimamente, integrar agentes de IA en software real, con reglas de negocio que el modelo no puede romper y tests que no dependen de la API.

## Tecnologías

![C#](https://img.shields.io/badge/C%23-.NET-512BD4?logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vuedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?logo=apachespark&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![OpenRouter](https://img.shields.io/badge/OpenRouter-LLM-6566F1)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

## Proyectos destacados

| Proyecto | Qué es | Stack |
|----------|--------|-------|
| [TutorHub](https://github.com/DHat3r/TutorHub) | Plataforma que conecta estudiantes universitarios con tutores: publicar tutorías y disponibilidad, reservar, confirmar y calificar. Rehice solo un proyecto en equipo (LinkUDP): un repo con `docker compose up`, huecos de seguridad cerrados (el usuario sale del JWT, nunca del body), 26 tests en CI y diseño nuevo | TypeScript, NestJS, Prisma, Next.js, PostgreSQL, Docker |
| [Cafeteria](https://github.com/DHat3r/Cafeteria) | Sistema de marketing para una cafetería: los clientes se registran por QR con consentimiento, el administrador importa el Excel de ventas, ve un dashboard y envía ofertas por correo a segmentos. Contactos cifrados (AES-256-GCM), 202 tests y CI que levanta el stack con Docker Compose | TypeScript, NestJS, Next.js, Prisma, SQLite, Docker |
| [agentes-php](https://github.com/DHat3r/agentes-php) | Tres aplicaciones con agentes de IA (*tool calling* real) sobre un mismo núcleo: evaluador de respuestas, tutor adaptativo de matemáticas y conciliación bancaria. Las reglas de negocio viven en las herramientas, no en el prompt. 158 tests con un LLM simulado y CI | PHP 8, Laravel, Slim, OpenRouter, Vue 3, PostgreSQL, Redis, Docker |
| [Taquilla](https://github.com/DHat3r/entradas-soa) | Venta de entradas para eventos con 7 servicios independientes que solo se hablan por RabbitMQ y una web en React (clientes e interno, con modo claro y oscuro). La compra es una saga que libera el cupo si el pago falla, los cupos se descuentan de forma atómica y las entradas llevan un QR firmado. 177 tests y CI | Python, FastAPI, RabbitMQ, PostgreSQL, React, Docker |
| [InventoryManagement](https://github.com/DHat3r/InventoryManagement) | API REST de inventario para pymes: kardex valorizado, flujo de aprobación de productos (Inventario propone, Admin aprueba y define el precio), JWT con refresh tokens y 4 roles de negocio, y panel web en React. 73 tests contra PostgreSQL real (Testcontainers) y CI con 69,7 % de cobertura | C#, .NET 8, PostgreSQL, React, Docker |
| [Banco Futura](https://github.com/DHat3r/Banco-Futura-Servicio) | Predicción de fuga de clientes (XGBoost, AUC 0,95) y análisis de sentimiento de reclamos con BETO, entrenado con 13 mil reseñas reales de apps de bancos. Pipeline medallion en Databricks, API de scoring y panel, todo con `docker compose up`, tests y CI | Python, Databricks, FastAPI, React, Docker |
| [To-Do-List](https://github.com/DHat3r/To-Do-List) | API REST de tareas con registro y login JWT, donde cada usuario solo ve sus tareas. 19 tests, Docker y CI | Python, FastAPI, SQLite, Docker |

## En qué estoy trabajando

- 🎓 TutorHub: tests de reservas y perfil, ESLint del backend en el CI y despliegue público.
- ☕ Cafeteria: límite de peticiones en el registro y el login, doble confirmación del correo y despliegue público.
- 🤖 agentes-php: siguiente paso, reescribir yo mismo el ciclo del agente a partir de sus tests, para entenderlo línea por línea.
- 🎟️ Taquilla: validación de entradas por evento, límite de reservas por cliente y una cola de mensajes fallidos.
- 🛠️ InventoryManagement: despliegue público con demo, y después caché con Redis y módulos de proveedores y pedidos.
- 🔭 Banco Futura: registrar los modelos con MLflow y desplegar la demo.

## Contacto

- GitHub: [@DHat3r](https://github.com/DHat3r)
- LinkedIn: [leandro-alberto-norambuena-paine](https://www.linkedin.com/in/leandro-alberto-norambuena-paine/)
