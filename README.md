# Introducción paso a paso al framework web [Laravel]

**El curso está disponible en línea aquí: [https://stahe.github.io/ales-laravel-sept-2026/](https://stahe.github.io/ales-laravel-sept-2026/)**

## Autor

El curso y todo su código fueron escritos por **Claude**, la IA de Anthropic, **único autor**, a petición de Serge Tahé (septiembre de 2026).

## Descripción general

Este curso ofrece una guía paso a paso para construir una aplicación web MVC con el framework **Laravel 13** y el lenguaje **PHP 8.4**. El servidor genera las páginas HTML mediante vistas **Blade**, sin un framework JavaScript del lado del navegador.

Adapta el curso [Introducción paso a paso al framework web [Flask]](https://stahe.github.io/ales-flask-sept-2026/), basado a su vez en los cursos de [Spring MVC](https://stahe.github.io/ales-springmvc-sept-2026/), [ASP.NET Core MVC](https://stahe.github.io/ales-aspnetcoremvc-sept-2026/) y [NestJS](https://stahe.github.io/ales-nestjs-html-sept-2026/). Los ejemplos llevan los mismos números y abordan los mismos temas: es posible comparar los frameworks ejemplo por ejemplo.

## Contenido

| Capítulo | Temas | Ejemplos |
|---|---|---|
| Acciones, enrutamiento, respuestas | rutas, controladores, respuestas, redirecciones, contenedor de servicios | 01–06 |
| El modelo de la acción | parámetros de la solicitud, enlace (binding), validación, solicitudes POST | 07–12 |
| La vista y su plantilla | Blade, plantilla, componentes, formularios, validación, Post/Redirect/Get, protección CSRF | 13–21 |
| Internacionalización | Una aplicación en francés e inglés | 22 |
| Ámbitos de datos | Solicitud, sesión, caché, cookies | 23 |
| El ciclo de vida de la solicitud | middleware, enlace de parámetros, manejadores de excepciones | 24 |
| Autenticación y autorización | JWT en una cookie, guardias, roles, CAPTCHA, limitación de tasa | 25–27 |
| Arquitectura en capas | web / lógica de negocio / DAO con Eloquent y MySQL | 28 |
| Caso de estudio | **RdvMedecins**, una aplicación de agenda de citas médicas, explicada archivo por archivo | - |

El caso de estudio `rdvmedecins2-laravel` gestiona tres roles (administrador, médicos, pacientes): agendas, reservas, gestión de médicos y clientes, creación de cuentas protegida por CAPTCHA e interfaz en francés/inglés. Utiliza la misma base de datos `dbrdvmedecins2` que las demás versiones de la aplicación.

## Requisitos previos

- PHP 8.4 o posterior (extensiones `intl`, `mbstring`, `openssl`, `pdo_mysql`);
- Composer 2;
- MySQL 8 o MariaDB (Laragon en Windows);
- Visual Studio Code con las extensiones PHP Intelephense y Laravel;
- curl.

El código puede descargarse desde el sitio web del curso. Las carpetas `vendor` no se incluyen: `composer install` las crea, una en la carpeta `exemples` y otra en la carpeta `rdvmedecins2-laravel`.
