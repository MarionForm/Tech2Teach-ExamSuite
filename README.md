⚡ Tech2Teach ExamSuite (PHP + SQLite)

Convierte experiencia técnica real en docencia evaluable en minutos.

Tech2Teach ExamSuite es una micro-suite desarrollada en PHP puro que permite transformar incidencias, apuntes técnicos o temarios brutos en:

📑 Pack didáctico (guía, objetivos, contenidos, metodología)
📝 Ejercicios prácticos
📊 Rúbrica de evaluación
❓ Exámenes tipo test (variantes A / B / C)
✅ Corrección automática
📈 Resultados detallados por pregunta
📤 Exportación en HTML printable, JSON y Moodle GIFT

Pensado para:
👨‍🏫 Docentes IT
🖥 Técnicos que quieren enseñar
🏫 Centros de formación profesional
📚 Autoaprendizaje estructurado

🧠 Filosofía del proyecto
No es un producto cerrado ni un SaaS.
Es una base didáctica funcional para:
Aprender arquitectura MVC ligera en PHP
Practicar generación dinámica de exámenes
Construir herramientas reales para formación técnica
Convertir experiencia técnica en material evaluable
Aprender haciendo.

🧰 Stack Tecnológico
PHP 7.4+ (compatible con PHP 8)
SQLite (base de datos local)
Arquitectura MVC simple
Sin frameworks externos
Sin dependencias pesadas

📂 Estructura del proyecto
app/
 ├── Controllers/
 ├── Models/
 ├── Services/
 ├── Views/
public/
scripts/
storage/
 ├── uploads/
 ├── exports/
README.md
LICENSE
.gitignore

🚀 Instalación rápida (Local)
1️⃣ Requisitos

PHP 7.4 o superior
Extensión SQLite habilitada

Comprobar:
php -v
php -m | findstr /i sqlite

2️⃣ Inicializar base de datos
php scripts/init_db.php
php scripts/seed_questions.php


Esto crea:
storage/tech2teach.sqlite
Banco inicial de preguntas

3️⃣ Levantar servidor local
php -S localhost:8080 -t public
Abrir navegador:
http://localhost:8080

🔄 Flujo de uso
1️⃣ Crear nuevo pack didáctico
2️⃣ Generar examen (A/B/C)
3️⃣ Realizar examen
4️⃣ Corregir automáticamente
5️⃣ Ver resultados detallados
6️⃣ Exportar en formato deseado

📤 Exportaciones disponibles
HTML printable (Ctrl+P → Guardar como PDF)
JSON estructurado
Moodle GIFT (importable en banco de preguntas)

📦 Seguridad y privacidad
El repositorio NO incluye:
Base de datos local
Archivos subidos
Exportaciones generadas
La estructura de carpetas se mantiene con .gitkeep.

🧩 Posibles mejoras futuras
CRUD visual para banco de preguntas
Importación masiva desde CSV
Export ZIP “paquete alumno”
Roles (docente / alumno)
Estadísticas avanzadas por dificultad
Integración con dompdf para PDF nativo

🎯 Casos de uso reales
Preparación de exámenes ASIR
Competencias Digitales Intermedias
Laboratorios evaluables
Simulaciones tipo certificación
Generación rápida de material docente

📌 Roadmap
v1.0 → MVP funcional (packs + exámenes + export)
v1.1 → Banco de preguntas editable
v1.2 → Export ZIP alumno
v2.0 → Multiusuario

📜 Licencia
MIT License
👤 Autor
Desarrollado por MarionForm
Docente IT · Soporte Técnico · Formación Profesional
