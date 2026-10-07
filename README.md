# Gestor ADSO - Proyecto Integrador (Semana 1)

## 🛠️ Herramientas y Versiones Reales
* **PHP:** (Ej: PHP 8.2.12 - Verificado con `php -v`)[cite: 33]
* **Composer:** (Ej: Composer version 2.6.5 - Verificado con `composer -V`)[cite: 33]
* **Git:** (Ej: git version 2.43.0 - Verificado con `git --version`)[cite: 33]
* **Laravel:** (Ej: Laravel Framework 11.x - Verificado con `php artisan --version`)[cite: 33]

## 🚀 Pasos de Instalación y Configuración
1. Clonar o posicionarse en la carpeta del proyecto `gestor-adso`.
2. Duplicar el archivo de entorno y generar la llave de seguridad[cite: 27, 33]:
   ```bash
   copy .env.example .env
   php artisan key:generate