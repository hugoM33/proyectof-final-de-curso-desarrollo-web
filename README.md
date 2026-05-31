# Granitos e Obras Mosquera  
## Web Corporativa e Tenda Online con WordPress

---

## Descrición do Proxecto

Este proxecto consiste no deseño, desenvolvemento e publicación dunha páxina web corporativa con tenda online integrada para a empresa **Granitos e Obras Mosquera (GRAOMOS)**.

A empresa non dispoñía de presenza web, polo que se creou unha solución completa que inclúe:

- Información corporativa e de contacto.
- Presentación dos servizos profesionais.
- Galería de proxectos realizados.
- Tenda online con merchandising corporativo e produtos de pedra.
- Acceso desde rede local e acceso externo mediante DDNS.
- Medidas básicas de seguridade e copias de seguridade.

O sistema baséase nunha arquitectura **LAMP** instalada nun **Ubuntu Server** configurado manualmente.

---

## Obxectivos

### Obxectivo Xeral
Crear e publicar unha páxina web corporativa con tenda online funcional, accesible desde rede local e externa, garantindo seguridade básica e estabilidade.

### Obxectivos Específicos
- Instalación e configuración de **Ubuntu Server 24.04**.
- Instalación e configuración de **Apache**, **MariaDB** e **PHP**.
- Instalación manual de **WordPress**.
- Integración de **WooCommerce** para a tenda online.
- Creación dun catálogo real de produtos corporativos e produtos de pedra.
- Configuración de acceso externo mediante **DDNS**.
- Aplicación de medidas de seguridade básicas.
- Realización de copias de seguridade.
- Documentación completa do proceso.

---

## Arquitectura do Sistema

Arquitectura **LAMP**:

- **Linux:** Ubuntu Server 24.04  
- **Apache:** Servidor web  
- **MariaDB:** Base de datos  
- **PHP:** Execución de WordPress  
- **WordPress:** CMS principal  
- **WooCommerce:** Motor da tenda online  

Acceso mediante navegador web desde calquera dispositivo da rede.

---

## Estrutura da Web

### Parte Corporativa
- Inicio  
- Quen somos  
- Servizos  
- Proxectos  
- Contacto (formulario)

### Tenda Online (WooCommerce)

#### Produtos reais incluídos no proxecto

##### **Merchandising corporativo**
- Gorra corporativa GRAOMOS  
- Camiseta corporativa GRAOMOS  
- Bolígrafo corporativo GRAOMOS  
- Calendario corporativo GRAOMOS  

##### **Produtos de pedra**
- Maceta de pedra natural  
- Banco de pedra morena  
- Cruz de pedra morena  
- Lavabo de pedra  

##### **Servizos de pedra**
- **Viaxe de Cachotes (Transporte e colocación de pedra para muros, valados e obras)**  
  - Produto configurado como servizo  
  - Prezo variable segundo destino e cantidade  
  - Inclúe transporte e colocación  

#### Funcionalidades
- Carrito  
- Pedido simulado  
- Páxina de confirmación  
- Xestión de produtos desde o panel de administración  

---

## Plugins Instalados (Reais do Proxecto)

### Comercio electrónico
- WooCommerce

### Seguridade
- Wordfence Security  
- Limit Login Attempts Reloaded  
- Really Simple SSL

### Copias de Seguridade
- Duplicator

### Formularios
- WPForms Lite

### SEO
- Yoast SEO

### Rendemento
- Autoptimize

---

## Medidas de Seguridade Aplicadas

- Eliminación do usuario *admin* por defecto.
- Contrasinais seguras.
- Actualizacións periódicas de WordPress e plugins.
- Permisos correctos en ficheiros e carpetas.
- Limitación de intentos de acceso.
- Copias de seguridade mediante Duplicator.
- Explicación dos riscos de exposición a Internet.

---

## Publicación Externa

Para permitir acceso desde fóra da rede local configurouse:

- Servizo **DDNS**.  
- Redirección de portos no router (80/443).  
- Probas de acceso externo desde móbil e redes alleas.

---

## Probas Realizadas

- Acceso desde rede local.  
- Acceso desde rede externa mediante DDNS.  
- Funcionamento do carrito e pedido simulado.  
- Alta, edición e eliminación de produtos.  
- Acceso ao panel de administración protexido.  
- Restauración da web mediante Duplicator.

---

## Documentación Incluída

- Memoria técnica en PDF.  
- Capturas de pantalla.  
- Evidencias das probas.  
- Configuración completa do servidor.  
- Arquitectura do sistema.  
- Procedemento de publicación externa.  
- Procedemento de restauración da copia de seguridade.

---

## Copia de Seguridade da Web

A copia completa da web está incluída neste repositorio como:

- **installer.php**  
- **archive.zip** (paquete xerado con Duplicator)

Estes dous arquivos permiten restaurar a web completa en calquera servidor.

---

## Posibles Melloras Futuras

- Activación de HTTPS con certificado SSL.  
- Sistema de rexistro de usuarios.  
- Envío automático de correos de confirmación.  
- Xestión avanzada de stock.  
- Mellora do deseño responsive.  
- Integración con pasarela de pago real.
## Copia de seguridade da web

A copia completa da web (ZIP + installer.php) está dispoñible na sección de Releases:

**Descargar copia de seguridade:**  
https://github.com/hugoM33/proyectof-final-de-curso-desarrollo-web/releases/latest
