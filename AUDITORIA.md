# Auditoría rápida — PixelFest 2026

| # | Problema detectado | Categoría | ¿Por qué es problema? |
|---|---|---|---|
| 1 | Falta la etiqueta meta viewport. | Responsive Design | Sin ella, la página no se escala correctamente en móviles y se ve como una versión de escritorio miniaturizada. |
| 2 | El id del menú colapsable no coincide con el data-bs-target del botón. | Uso incorrecto de Bootstrap | El botón hamburguesa no despliega el menú en móviles porque apunta a un id que no existe. |
| 3 | La sección Hero no tiene un contenedor (container) ni espaciado. | Layout o grid mal aplicado  |	El contenido del hero está pegado a los bordes de la pantalla, se ve desordenado y sin estructura. |
| 4 | Las tarjetas (cards) de actividades no tienen la misma altura. | Jerarquía visual / UX | Al tener diferentes cantidades de texto, las tarjetas tienen alturas distintas y se ve desalineado. |
| 5 | El navbar no tiene un contenedor interno (.container). | Uso incorrecto de bootstrap | 	La marca y los enlaces del menú están pegados al borde izquierdo, sin el espaciado estándar. |
| 6 | Todos los enlaces usan # sin funcionalidad real. | Links incorrectos o sin funcionalidad |Los enlaces no llevan a ningún lado.  |
