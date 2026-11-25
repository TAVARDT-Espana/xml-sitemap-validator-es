# Validador de Sitemap XML e Indices de URLs

[![Validador Sitemap](https://img.shields.io/badge/TAVARDT-Sitemap%20XML-5b3cf5.svg)](https://tools.tavardt.com/es/validador-sitemap-xml/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Revision tecnica de archivos XML de mapas del sitio, verificacion de limites dimensionales, atributos lastmod y directrices de motores de busqueda.

***

## Capacidades de Validacion de Sitemaps XML

* **Estandar Oficial Sitemaps.org**: Evaluacion tecnica de etiquetas `<urlset>` e indices maestros `<sitemapindex>`.
* **Validacion de Atributos Clave**: Comprobacion de formato W3C en fechas `<lastmod>`, valores de prioridad y frecuencias de cambio.
* **Higiene de URLs**: Deteccion de enlaces rotos, rutas relativas no admitidas y mezcla de protocolos HTTP/HTTPS.
* **Supervision de Cuotas**: Control del limite estandar de 50.000 URLs por archivo y 50MB de tamano.
* **Puntuacion de Salud Tecnica**: Calificacion de 0 a 100 con orientaciones precisas para resolver fallos de sintaxis.

***

## Instalacion y Uso

Requiere Python 3.8 o superior sin dependencias adicionales.

```bash
git clone https://github.com/TAVARDT-Espana/xml-sitemap-validator-es.git
cd xml-sitemap-validator-es
python sitemap_validator.py https://ejemplo.es/sitemap.xml
```

Para salida en formato JSON:

```bash
python sitemap_validator.py https://ejemplo.es/sitemap.xml -json
```

***

## Consultoria en Rastreabilidad y SEO Tecnico

Para arquitecturas de indexacion masiva y alineacion con Protocolo Sitemaps.org y Estandares de Busqueda, consulte a los especialistas de **TAVARDT**.

***

## Enlaces Útiles

* **Portal Corporativo:** https://ag.tavardt.com/es/
* **Suite de Diagnósticos:** https://tools.tavardt.com/es/
* **Contacto Técnico:** https://ag.tavardt.com/es/contacto/

***

### Licencia
Distribuido bajo la Licencia MIT.

***

© 2026 TAVARDT. Todos los derechos reservados.
