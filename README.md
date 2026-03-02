# Granitos e Obras Mosquera  
## Web Corporativa e Tenda Online con WordPress

---

## Descrición do Proxecto

Este proxecto consiste no deseño, desenvolvemento e publicación desde cero dunha páxina web corporativa con tenda online integrada para a empresa Granitos e Obras Mosquera.

A empresa non dispón actualmente de presenza web, polo que se desenvolverá unha solución completa que permita:

- Presentar información corporativa.
- Mostrar os servizos ofrecidos.
- Amosar proxectos realizados.
- Dispoñer dunha tenda online con produtos promocionais e personalizados.
- Permitir acceso desde rede local e externa.
- Aplicar medidas básicas de seguridade.

O sistema estará baseado nunha arquitectura cliente-servidor empregando tecnoloxía LAMP.

---

## Obxectivos

### Obxectivo Xeral

Deseñar, implementar e publicar unha páxina web corporativa con sistema de comercio electrónico integrado, garantindo funcionalidade, seguridade básica e accesibilidade externa.

### Obxectivos Específicos

- Instalar e configurar Ubuntu Server.
- Instalar e configurar Apache.
- Instalar e configurar MariaDB.
- Instalar WordPress manualmente.
- Integrar WooCommerce para a tenda online.
- Crear un catálogo con mínimo 8–10 produtos.
- Configurar sistema de carrito e pedido simulado.
- Permitir acceso externo mediante DDNS.
- Aplicar medidas básicas de seguridade.
- Realizar copias de seguridade periódicas.
- Documentar todo o proceso.

---

## Arquitectura do Sistema

Empregarase unha arquitectura LAMP:

- Linux: Ubuntu Server
- Apache: Servidor web
- MariaDB: Base de datos
- PHP: Linguaxe de execución de WordPress

O acceso realizarase mediante navegador web conectándose ao servidor.

---

## Estrutura da Web

### Parte Corporativa

- Inicio
- Quiénes somos
- Servizos
- Proxectos realizados
- Contacto (formulario)

### Parte Tenda Online

- Produtos promocionais:
  - Llaveros
  - Bolígrafos
  - Camisetas
  - Gorras
- Produto decorativo personalizado:
  - Logo tallado en pedra (medida fixa estándar)
- Carrito de compra
- Pedido simulado
- Confirmación de pedido

---

## Entorno Tecnolóxico

Sistema Operativo:
- Ubuntu Server

Servidor Web:
- Apache

Base de Datos:
- MariaDB

CMS:
- WordPress

Plugin de Comercio Electrónico:
- WooCommerce

---

## Plugins Previstos

Comercio electrónico:
- WooCommerce

Seguridade:
- Wordfence Security
- Limit Login Attempts Reloaded

Copias de Seguridade:
- UpdraftPlus

Formularios:
- WPForms

Optimización:
- WP Super Cache
- Autoptimize

---

## Medidas de Seguridade

- Eliminación do usuario administrador por defecto.
- Uso de contrasinais seguras.
- Actualización periódica de WordPress e plugins.
- Permisos correctos en ficheiros e carpetas.
- Limitación de intentos de login.
- Copias de seguridade automáticas programadas.
- Explicación dos riscos derivados da exposición a Internet.

---

## Publicación Externa

Para permitir acceso desde fóra da rede local utilizarase:

- Servizo de DNS dinámico (DDNS).
- Configuración de redirección de portos no router.
- Acceso mediante nome de dominio dinámico.

Isto permitirá que a web sexa accesible desde Internet sen necesidade de IP fixa.

---

## Probas Previstas

O proxecto deberá demostrar:

- Acceso desde rede local.
- Acceso desde rede externa.
- Funcionamento correcto do carrito.
- Pedido simulado completado.
- Acceso protexido ao panel de administración.
- Alta, edición e eliminación de produtos.
- Funcionamento das copias de seguridade.

---

## Documentación

A documentación final incluirá:

- Memoria técnica en formato PDF.
- Capturas de pantalla.
- Evidencias das probas realizadas.
- Explicación da configuración do servidor.
- Explicación da arquitectura do sistema.
- Procedemento de publicación externa.
- Procedemento de restauración de copias de seguridade.

---

## Posibles Ampliacións Futuras

- Implementación de HTTPS mediante certificado SSL.
- Sistema de rexistro de usuarios.
- Confirmación automática de pedidos por correo electrónico.
- Xestión avanzada de stock.
- Mellora do deseño responsive.
- Integración con pasarela de pago real.

---

## Autor

Proxecto académico desenvolvido para a materia de Desenvolvemento Web e Administración de Sistemas.
