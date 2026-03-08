# Hi there 👋, I'm Ricardo Lopez

**Social Media Manager 📱 | Creative Content Producer 🎥 | QA Tester 🐛**

I am a digital strategist with 10+ years of experience in the gaming and tech industry (Xbox, G2A). I specialize in community building and content production. Recently, I expanded my technical toolkit into **Quality Assurance (QA)** to bridge the gap between community expectations and flawless digital product delivery.

## 📫 Contact & Links
- 💼 **LinkedIn:** [linkedin.com/in/richolopez](https://www.linkedin.com/in/richolopez/)
- ✉️ **Email:** richfokalot@gmail.com

---

## 📁 Portafolio de Proyectos QA

### Proyecto 1: Pruebas Funcionales y de UI para Urban Routes
<img width="1913" height="902" alt="Captura de pantalla 2026-03-08 171100" src="https://github.com/user-attachments/assets/a6b5c06b-0c07-4d79-9cbe-607b4759c2a0" />


- **Contexto del proyecto:** Urban Routes es una aplicación web de transporte y car-sharing. El objetivo de este proyecto en mi Sprint 3 fue probar la funcionalidad de cálculo de rutas, reservas de automóviles y diseño de formularios, asegurando que la interfaz fuera intuitiva y libre de errores en navegadores cruzados (Chrome y Firefox).
- **Mi análisis:** Utilicé técnicas de diseño de pruebas (Clases de Equivalencia y Valores Límite) para probar los campos de entrada y métodos de pago. Durante la ejecución, descubrí que la aplicación presentaba bloqueos críticos (Blockers); por ejemplo, la pantalla se congelaba totalmente cuando el temporizador de reserva llegaba a cero, y el botón de cancelar no respondía. Además, identifiqué vulnerabilidades en el formulario de pago al permitir caracteres especiales.
- **Conclusiones principales:** Documenté y reporté 8 errores válidos en Jira, priorizando los defectos críticos que impedían el flujo principal del usuario. Este proyecto demostró que un buen diseño visual pierde su valor si los flujos críticos de pago y reserva fallan, reforzando la importancia de probar escenarios límite (edge cases) para proteger la experiencia del usuario final.

**Material Visual y Documentación:**
- 📄 [[Enlace a mi matriz de pruebas en Google Sheets]](https://docs.google.com/spreadsheets/d/1QeahXyoT8rZyFQL6uBt5Nb2nI7XzfUg4/edit?usp=sharing&ouid=115821388286610848447&rtpof=true&sd=true)
- 🐛 **Ejemplo de Bug Reportado (Jira):*
*<img width="1035" height="691" alt="Captura de pantalla 2026-03-08 171608" src="https://github.com/user-attachments/assets/ac9fb0e3-113b-4b6e-9a74-23796205a6de" />


---

### Proyecto 2: Pruebas de API para Urban Grocers
<img width="1392" height="761" alt="Captura de pantalla 2026-03-08 172630" src="https://github.com/user-attachments/assets/542adb32-c33b-451e-a1ab-17cd58ab91d5" />


- **Contexto del proyecto:** Urban Grocers es una plataforma de e-commerce. Como parte del Sprint 4, me encargaron validar la actualización del backend que maneja la lógica de servicios de entrega y kits de productos mediante peticiones HTTP.
- **Mi análisis:** Utilicé Postman para realizar pruebas de API consultando la documentación en Apidoc. Diseñé escenarios positivos y negativos, validando que el servidor respondiera con los códigos de estado correctos (ej. 200 OK, 400 Bad Request). Comprobé el comportamiento del sistema ante entradas faltantes o inválidas en el cuerpo de la solicitud JSON.
- **Conclusiones principales:** Logré confirmar que la lógica de entrega funciona correctamente en la mayoría de los casos, pero aseguré que el sistema manejara de forma robusta los errores cuando el servicio de entrega no estaba disponible (`"isItPossibleToDeliver": false`). Aprendí a interpretar la lógica de negocio desde el backend antes de que exista una interfaz gráfica.

**Material Visual y Documentación:**
- 📄 [[Enlace a mi documentación de API]](https://docs.google.com/spreadsheets/d/169vBBM-h6uA2N18BmiDuImwZDTxuoOJw/edit?usp=sharing&ouid=115821388286610848447&rtpof=true&sd=true)
- 🐛 **Ejemplo de Bug Reportado (Jira):*
<img width="1024" height="484" alt="Captura de pantalla 2026-03-08 173020" src="https://github.com/user-attachments/assets/9ed38c0a-7a6e-4489-95d4-fbec10eabf7b" />

