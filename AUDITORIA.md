# Auditoría inicial — Atlas Jurídico / Common Law

El archivo solicitado `common_law_irlanda_reino_unido.html` no existe en el estado actual del proyecto. El único HTML disponible es `index.html`; esta revisión se refiere a ese portal, no a la presentación ausente.

## Avances que deben conservarse

- Portal editorial blanco con acentos rojos y tipografía Inter.
- Cinco sistemas con portadas locales y navegación sistema → país o jurisdicción → noticias.
- Ocho noticias: cuatro de Tecnología y cuatro de Relaciones interpersonales, repartidas entre Reino Unido e Irlanda.
- Diferenciación de Escocia como jurisdicción mixta dentro del Reino Unido.
- Filtros temáticos, enlaces originales, adaptación móvil y foco accesible.

## Diferencias respecto al documento recibido

- El documento pide chocolate y títulos serif; las últimas instrucciones del portal piden blanco, rojo e Inter. Debe resolverse el destino antes de cambiar su identidad.
- No hay presentación con nueve secciones, introducción ni conclusiones desarrolladas.
- Los cuatro ejes adicionales muestran estados vacíos: faltan de tres a cinco noticias verificadas por eje.
- Faltan modo de presentación, navegación por teclado entre secciones, controles de pantalla completa y bloques expandibles.
- Los filtros por país se realizan mediante la navegación; no existe filtro conjunto de noticias por Estado.
- No hay gráficas documentadas. No deben compararse en una misma escala cifras con universos y períodos distintos.
- Inter se carga desde Google Fonts: sin red se usa una fuente del sistema. Para Inter sin conexión debe incluirse un archivo de fuente local.
- Las noticias requieren campos separados para jurisdicción, norma, consecuencia jurídica y estado de verificación.
- La impresión actual muestra secciones dinámicas que pueden estar vacías o conservar la última selección; debe definirse e implementar una salida completa y coherente.

## Verificación preliminar de fuentes

- Coimisiún na Meán: la publicación de 8 de septiembre de 2026 confirma la investigación formal sobre X, mecanismos de edad y controles parentales; no acredita culpabilidad.
- Home Office: la publicación de 8 de octubre de 2026 limita su ámbito a Inglaterra y Gales y distingue registros policiales de prevalencia.
- La página de Ofcom sobre la multa se abrió, pero la extracción inicial no permite aún validar todo el cuerpo de la noticia.
- RTÉ devolvió 403 en la consulta: no se considera verificación del contenido. Debe buscarse acceso o corroboración adicional.

## Orden de implementación

1. Resolver si se amplía el portal actual o se crea una presentación separada.
2. Consolidar los ocho casos con verificación individual y jurisdicciones precisas.
3. Investigar los cuatro ejes restantes con fuentes directas.
4. Integrar los seis ejes mediante componentes reutilizables conservando la base existente.
5. Validar teclado, filtros, impresión, funcionamiento local y tamaños de pantalla.
