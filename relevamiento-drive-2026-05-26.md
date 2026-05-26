# Relevamiento del Drive `7. Page Breakdowns and Wireframes`

Fecha de relevamiento: `2026-05-26`  
Drive analizado: `https://drive.google.com/drive/folders/12p9jdfB1MrOiV8sJG5UkxKWqJJ-QWonf?usp=sharing`

## Resumen ejecutivo

El contenido del Drive **no corresponde a un estudio jurídico** ni a documentación legal.  
Lo que hay es una **biblioteca de wireframes, page breakdowns y walkthroughs visuales** para páginas de marketing/performance, e-commerce, lead generation y funnels.

Hallazgos principales:

- El folder contiene `50` archivos.
- Distribución:
  - `16` videos `.mp4`
  - `33` archivos `.pdf`
  - `1` archivo técnico `.DS_Store`
- Peso total aproximado del material: `1043.6 MB`.
- Casi todo el material fue modificado el `11 abr 2024`.
- La estructura del folder está organizada por **familias de páginas**:
  - Homepage
  - Product page
  - Collections page
  - Cart draw
  - Sales page
  - Listicle page
  - Advertorial page
  - Quiz page
  - Lead generation page
  - Multistep lead generation page
  - Opt-in pages
  - Top X page
  - VSL page
  - Webinar
  - SaaS
  - Service

Conclusión práctica:

- El Drive es una **base de referencia UX/UI para funnels y landings de conversión**.
- Sirve como input para diseñar o replicar estructuras de páginas.
- No contiene, al menos en lo visible del folder analizado, contenido jurídico de marca, expedientes, PDFs legales ni material institucional del estudio.

## Qué se validó técnicamente

Se verificó:

- acceso público de lectura al folder
- extracción del índice completo del Drive
- recuperación de `fileId`, tipo MIME, tamaño y fecha de modificación de cada archivo
- descarga y lectura de muestras de PDFs desktop
- validación visual por muestreo de páginas representativas
- validación por muestreo de videos

Muestras visuales efectivamente verificadas:

- `2.1 Product page - desktop.pdf`
- `7.1 Advertorial - desktop.pdf`
- `8.1 Quiz - desktop.pdf`
- `9.1 Leadgen - desktop.pdf`
- `11.3 Opt in modal - desktop.pdf`
- `13.1 VSL - desktop.pdf`
- `16.1 Service - desktop.pdf`
- frame de `1. Homepage.mp4`
- frame de `8. Quiz page.mp4`

Muestras de video validadas:

- `1. Homepage.mp4`
  - resolución: `1280x720`
  - codecs: `h264` + `aac`
  - duración: `308.373 s`
  - tamaño real descargado: `53,595,967 bytes`
- `8. Quiz page.mp4`
  - resolución: `1280x720`
  - codecs: `h264` + `aac`
  - duración: `285.717 s`
  - tamaño real descargado: `43,032,137 bytes`

## Lectura funcional del material

## Hallazgo central

El folder parece ser una **colección de assets para desarmar y estudiar estructuras de páginas de conversión**.  
Cada familia normalmente viene con:

- `1` video `.mp4` mostrando la experiencia o walkthrough
- `1` PDF desktop
- `1` PDF mobile

Excepciones:

- `Cart draw` incluye variantes `empty` y `full`
- `Opt-In pages` incluye además `opt in modal`
- `Homepage` solo tiene video
- `Service` visible solo con video + desktop PDF

## Síntesis por familia de página

Las descripciones marcadas como `validado visualmente` surgen de muestras abiertas/renderizadas.  
Las marcadas como `inferido por nombre + estructura del folder` se derivan del patrón del material.

### 1. Homepage

- Estado: `validado por frame de video`
- Tipo: landing/homepage de marca o producto
- Estructura observada:
  - header
  - hero con propuesta de valor
  - CTA dominante
  - bloques de beneficios
  - secciones de confianza/proof
- Uso probable:
  - página principal de marca
  - entry point del funnel

### 2. Product page

- Estado: `validado visualmente`
- Tipo: product page / sales page larga de producto
- Estructura observada:
  - hero con producto + CTA
  - navegación interna
  - beneficios
  - features
  - prueba social
  - tabla/comparación
  - FAQ
  - footer
- Objetivo:
  - compra o inicio de checkout

### 3. Collections page

- Estado: `inferido por nombre + assets`
- Tipo: collection/category page de e-commerce
- Activos:
  - video
  - desktop PDF pesado (`72.7 MB`)
  - mobile PDF pesado (`24.3 MB`)
- Lectura:
  - probablemente concentra grillas, filtros, categorías y browsing de catálogo

### 4. Cart draw

- Estado: `inferido por nombre + estructura`
- Tipo: carrito lateral / mini-cart
- Variantes:
  - empty desktop
  - empty mobile
  - full desktop
  - full mobile
- Valor:
  - sirve para estudiar estados vacíos y estados con productos cargados

### 5. Sales page

- Estado: `inferido por nombre + patrón del material`
- Tipo: sales page orientada a conversión
- Esperable:
  - hero
  - oferta
  - beneficios
  - social proof
  - CTA repetidos

### 6. Listicle page

- Estado: `inferido por nombre + patrón del material`
- Tipo: página tipo ranking/lista editorial
- Uso probable:
  - comparativas
  - “top picks”
  - contenido híbrido entre SEO/editorial y conversión

### 7. Advertorial page

- Estado: `validado visualmente`
- Tipo: advertorial / artículo persuasivo
- Estructura observada:
  - título largo
  - cuerpo editorial
  - imágenes de apoyo
  - CTA intercalados
  - bloques de prueba social
- Objetivo:
  - convertir lectura en lead o click de oferta

### 8. Quiz page

- Estado: `validado visualmente + frame de video`
- Tipo: quiz / formulario guiado
- Estructura observada:
  - barra de progreso
  - pregunta central
  - opciones tipo card
  - CTA de avance
  - prueba social liviana
- Objetivo:
  - cualificación
  - segmentación
  - captura de datos previa al offer step

### 9. Lead generation page

- Estado: `validado visualmente`
- Tipo: landing de captura de leads
- Estructura observada:
  - hero con propuesta de valor
  - formulario
  - beneficios
  - social proof
  - CTA repetido
- Objetivo:
  - registro / envío de formulario

### 10. Multistep lead generation page

- Estado: `inferido por nombre + assets`
- Tipo: captación en varios pasos
- Uso probable:
  - lead qualification progresiva
  - mayor compromiso antes del submit final

### 11. Opt-In pages

- Estado: `validado parcialmente`
- Variantes:
  - opt in desktop/mobile
  - opt in modal desktop/mobile
- Observación visual validada:
  - `11.3 Opt in modal - desktop.pdf` muestra overlay/modal con captura de email
- Objetivo:
  - captar email
  - interceptar abandono
  - ofrecer lead magnet / acceso / descuento

### 12. Top X page

- Estado: `inferido por nombre + assets`
- Tipo: página de ranking o curación (“Top X…”)
- Uso probable:
  - comparativas
  - selección editorial
  - empuje a clics de afiliación o compra

### 13. VSL page

- Estado: `validado visualmente`
- Tipo: Video Sales Letter
- Estructura observada:
  - video protagonista
  - CTA cercano al player
  - pruebas sociales
  - secciones de beneficios
  - FAQ
- Objetivo:
  - vender desde narrativa audiovisual

### 14. Webinar

- Estado: `inferido por nombre + assets`
- Tipo: landing para webinar / registro
- Uso probable:
  - registro
  - agenda
  - speakers / beneficios
  - CTA a inscripción

### 15. SaaS

- Estado: `inferido por nombre + assets`
- Tipo: landing SaaS
- Uso probable:
  - producto software
  - features
  - pricing/benefits
  - CTA demo / signup

### 16. Service

- Estado: `validado visualmente`
- Tipo: landing de servicio
- Estructura observada:
  - hero
  - bloques explicativos largos
  - beneficios por módulos
  - social proof
  - FAQ
  - CTA final
- Objetivo:
  - lead / consulta / agendamiento

## Lectura estratégica del folder

Este Drive parece pensado como una **biblioteca de referencia para construir páginas de alto rendimiento**.  
No es solo diseño: también organiza formatos por intención de negocio.

Patrones claros:

- funnel awareness:
  - homepage
  - advertorial
  - listicle
  - top x
- funnel consideration:
  - product page
  - collections
  - sales page
  - service
  - saas
- funnel capture:
  - leadgen
  - multistep leadgen
  - opt-in
  - opt-in modal
  - quiz
- funnel conversion:
  - VSL
  - webinar
  - cart drawer

En otras palabras: el folder cubre casi todo el ciclo de adquisición/conversión.

## Riesgos o límites del relevamiento

- La carpeta analizada es pública y accesible, pero el contenido es predominantemente visual.
- Muchos PDFs parecen funcionar como mockups o slides visuales, no como documentos textuales ricos.
- Se pudo validar visualmente una muestra representativa y el inventario completo.
- En varios casos, la descripción funcional está `inferida por nombre + patrón del set`, no por lectura completa frame a frame del video entero.

## Inventario exhaustivo

Cada línea incluye: `nombre | mime | tamaño | fecha | fileId`

- `.DS_Store | application/octet-stream | 12 KB | 11 may 2025 | 1VCUoSdZkvpIaLGIU-JTapeWVjrHz9DVV`
- `1. Homepage.mp4 | video/mp4 | 51.1 MB | 11 abr 2024 | 1pyAeJhQEVOFN7N9ntOWHGfcvJ9U1YTBT`
- `2. Product page.mp4 | video/mp4 | 100 MB | 11 abr 2024 | 1kGcHEYsG0xJF2FEqTu4QFxRMuWnAUSQ6`
- `2.1 Product page - desktop.pdf | application/pdf | 19.9 MB | 11 abr 2024 | 1JZ1H8Yhf2loYmhzeY2Kt5TEkuc5D89fZ`
- `2.2 Product page - mobile.pdf | application/pdf | 3.7 MB | 11 abr 2024 | 16LZsTtbvj9XOUTG4x1xOTc7LuU7lIy7A`
- `3. Collections page.mp4 | video/mp4 | 43.9 MB | 11 abr 2024 | 11EB1HKuPei_UNegZrGlUOwL279Q-2egs`
- `3.1 Collection page - desktop.pdf | application/pdf | 72.7 MB | 11 abr 2024 | 1UhinA8pj0vYg1BMAioUN5iJiX8K-2t-3`
- `3.2 Collection page - mobile.pdf | application/pdf | 24.3 MB | 11 abr 2024 | 140Q-x4q2EZqdVbNh5XO1DHMpM1XTLyqR`
- `4. Cart draw.mp4 | video/mp4 | 38.2 MB | 11 abr 2024 | 1IaDHK0hX6NJMmSxo0JSrMwHYBwCJnjJ5`
- `4.1 Cart Draw Empty - desktop.pdf | application/pdf | 1.6 MB | 11 abr 2024 | 1d4jaTUEj9j--iaHCu8afEKNBbKB0aCAV`
- `4.2 Cart Draw Empty - mobile.pdf | application/pdf | 1.4 MB | 11 abr 2024 | 1-9uxSw82DIYlOctIhinD3QrfFP3jBTDH`
- `4.3 Cart Draw Full - desktop.pdf | application/pdf | 1.7 MB | 11 abr 2024 | 1jhvKpbCCMqMHGOoIgjTyXZlJaaX0texu`
- `4.4 Cart Draw Full - mobile.pdf | application/pdf | 1.5 MB | 11 abr 2024 | 1-cHX2-qCkWcetrJoy44JVaIGIbC6NhxE`
- `5. Sales page.mp4 | video/mp4 | 36.7 MB | 11 abr 2024 | 1j0C4Bc-1ZnlqzoP441IMcPIrr0Lb17M-`
- `5.1 Sales - desktop.pdf | application/pdf | 18.5 MB | 11 abr 2024 | 1YLEWcDPDbcgOJYd53gsNi82Yq150KqMs`
- `5.2 Sales - mobile.pdf | application/pdf | 3.5 MB | 11 abr 2024 | 1VC2JoLpDGIlmmqz3eawuDk5lXF-YdWn4`
- `6. Listicle page.mp4 | video/mp4 | 48.6 MB | 11 abr 2024 | 1pxkuMoHHe_KmfMHmJeUa1D20g1OUh87a`
- `6.1 Listicle - desktop.pdf | application/pdf | 4.1 MB | 11 abr 2024 | 1HXDpwiFUpYpU0OKceeUcD0rZgx1wp88C`
- `6.2 Listicle - mobile.pdf | application/pdf | 5 MB | 11 abr 2024 | 1nOSwVqVqHZYUZOL_MhX9MZTnRgsssySY`
- `7. Advertorial page.mp4 | video/mp4 | 61.1 MB | 11 abr 2024 | 1wJHN4ITTh1UsftyNqaaWCmZyeNzXQjnO`
- `7.1 Advertorial - desktop.pdf | application/pdf | 368 KB | 11 abr 2024 | 1aYE-sZnNNn3rOD7IH897lzvUBNgRmmUV`
- `7.2 Advertorial - mobile.pdf | application/pdf | 186 KB | 11 abr 2024 | 1a0gvrFQtwoh8yiIUaWL4njpmhwdLljRG`
- `8. Quiz page.mp4 | video/mp4 | 41 MB | 11 abr 2024 | 1gAa2PNB1n7gdgjpjPcB3Bl_mmI7rMtzs`
- `8.1 Quiz - desktop.pdf | application/pdf | 1.1 MB | 11 abr 2024 | 1dLOJN5nQNU15RlBr5G3grfgUJTFCgQYq`
- `8.2 Quiz - mobile.pdf | application/pdf | 1.3 MB | 11 abr 2024 | 1pR3LTupyM-uySQ_KDxyBMge4vHlodhEC`
- `9. Lead generation page.mp4 | video/mp4 | 51.6 MB | 11 abr 2024 | 1JsnaDRPtCf0KNHiQ_iunEl92a0O9P46J`
- `9.1 Leadgen - desktop.pdf | application/pdf | 1.1 MB | 11 abr 2024 | 1P5LqarB5y_seNdMe9MnZCoOlMfODWYpb`
- `9.2 Leadgen - mobile.pdf | application/pdf | 369 KB | 11 abr 2024 | 1qqFqeseDtBvgf-LwgO14p6eQ72yTf2WL`
- `10. Multistep lead generation page.mp4 | video/mp4 | 42.9 MB | 11 abr 2024 | 1mgneSMxHrzddV0kMTrJlKlaAh3AoLZyq`
- `10.1 Multistep lead generation - desktop.pdf | application/pdf | 670 KB | 11 abr 2024 | 1QcAGRaVlE2ep7o1A85qTa9rJuhPkT-_6`
- `10.2 Multistep lead generation - mobile.pdf | application/pdf | 466 KB | 11 abr 2024 | 1j70glO_llNDSAM1KLDQO0VZKAJFlOZmL`
- `11. Opt-In pages.mp4 | video/mp4 | 42.2 MB | 11 abr 2024 | 1x_6zrNS-gJyi3NFV8TfjfMJJRDg0IyQA`
- `11.1 Opt in - desktop.pdf | application/pdf | 1.6 MB | 11 abr 2024 | 1fpnwO3E5gp_sTdTSZF3jMzN8QYXY02S8`
- `11.2 Opt in - mobile.pdf | application/pdf | 2.6 MB | 11 abr 2024 | 1JYgnBNSV6MeVJMloSXh2wIaVWAowbqK8`
- `11.3 Opt in modal - desktop.pdf | application/pdf | 1.7 MB | 11 abr 2024 | 1qkjjlBfBxJz9-j0oLA9HxpDugkdqgZ85`
- `11.4 Opt in modal - mobile.pdf | application/pdf | 1.5 MB | 11 abr 2024 | 1-0Wp_6gbzDg-kYUXsKpOQ-l_mendTahC`
- `12. Top X page.mp4 | video/mp4 | 57.5 MB | 11 abr 2024 | 1koNikTHP_Zl7xQ6AbMPU-ec8iu3755wG`
- `12.1 Top X page - desktop.pdf | application/pdf | 23.6 MB | 11 abr 2024 | 1jENS04ozcZx8s8zLb8XT_NJV_cavt6h_`
- `12.2 Top X page - mobile.pdf | application/pdf | 1.7 MB | 11 abr 2024 | 16P4jC8uy0wy38T8-HwK2wwP45aFelEKO`
- `13. VSL page.mp4 | video/mp4 | 45.5 MB | 11 abr 2024 | 11cWRPlWkcfLPQTLfc6L2V5mBfv9k_Ncw`
- `13.1 VSL - desktop.pdf | application/pdf | 3.6 MB | 11 abr 2024 | 1_ObLFXeGXdfJbv0a9UKfGNWJwwhLbP-b`
- `13.2 VSL - mobile.pdf | application/pdf | 1.2 MB | 11 abr 2024 | 1PFRBYh_EVBKj-1I5xc5iKl8oxUuUz-ut`
- `14. Webinar.mp4 | video/mp4 | 55.1 MB | 11 abr 2024 | 1d1PGXamaXlt5b1kuUIyPxZmjCghvF4T9`
- `14.1 Webinar - desktop.pdf | application/pdf | 6.7 MB | 11 abr 2024 | 1AbqobpGkoQZrwYoa92hs5BVzdwgr-Zgo`
- `14.2 Webinar - mobile.pdf | application/pdf | 1.7 MB | 11 abr 2024 | 1V9YOXTbqy9qBxDEcPVun20WIlkq2s2iN`
- `15. SaaS.mp4 | video/mp4 | 50 MB | 11 abr 2024 | 1-c_GKDgcgCjhjC1W_TX4BAbdidIGhLg_`
- `15.1 SaaS - desktop.pdf | application/pdf | 9.1 MB | 11 abr 2024 | 1YdVEtinRuQkH99fO926ASDOe1IFNwRRY`
- `15.2 SaaS - mobile.pdf | application/pdf | 2.6 MB | 11 abr 2024 | 1qwh42HDNNmUFBm23S8zBltVg8Y2o8CnB`
- `16. Service.mp4 | video/mp4 | 49.2 MB | 11 abr 2024 | 1LHglzCw2xK1Tc87jBLBT-ARKPbRfDQgr`
- `16.1 Service - desktop.pdf | application/pdf | 8 MB | 11 abr 2024 | 1RsNDrNSt7bMT3Iw-n7P6xv8YoIRmDlLt`
