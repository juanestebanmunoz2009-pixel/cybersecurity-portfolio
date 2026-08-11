# Cybersecurity Portfolio & Research

Este repositorio documenta mi proceso de aprendizaje, mis hallazgos éticos y el desarrollo de herramientas personalizadas para la auditoría de infraestructuras.

## 🛠 Proyectos Desarrollados
* [NanoPass-CLI](https://github.com/juanestebanmunoz2009-pixel/NanoPass-CLI): Generador de contraseñas seguras enfocado en privacidad local.

## 🧪 Notas de Investigación
Aquí detallo mi estudio sobre protocolos de red y enumeración:
- [Modelo OSI y Análisis de Protocolos](/lab-notes/modelo-osi.md)
- [Metodología de Reconocimiento (OSINT)](/recon-methodology/recon.md)

## 🐞 Divulgaciones de Vulnerabilidades (Bug Bounty)
Writeups de hallazgos reportados a programas públicos de bug bounty en HackerOne:
- [Leaked RSA private key on intercity.indrive.com](https://github.com/juanestebanmunoz2009-pixel/indrive-rsa-key-leak): clave RSA privada filtrada en el frontend permite forjar la firma anti-abuso de un endpoint de envío de SMS (OTP), confirmada en 3 aplicaciones distintas.
- [Hardcoded domain-rotation API key on 1win](https://github.com/juanestebanmunoz2009-pixel/1win-domain-key-exposure): API key hardcodeada expone la tabla completa de dominios espejo/anti-bloqueo de 1win; incluye análisis honesto de por qué el rechazo del programa fue justificado.
- - [Bucket S3 con PII expuesto: "duplicado" no es lo mismo que "arreglado"](https://github.com/juanestebanmunoz2009-pixel/bancoplata-s3-bucket-exposure): bucket de almacenamiento sin autenticación exponiendo PII real de terceros, cerrado como duplicado de un reporte previo, pero confirmado que sigue expuesto y creciendo meses después.

## Objetivo
Como futuro ingeniero, mi meta es cerrar la brecha entre el desarrollo de software seguro y la auditoría de sistemas. Este repositorio es un reflejo de mi constante búsqueda por entender cómo los sistemas pueden ser comprometidos y, más importante aún, **cómo defenderlos**.

---
*Nota: Este portafolio sigue estrictas normas de ética y seguridad responsable. Toda investigación se realiza en entornos controlados o bajo metodologías de reconocimiento pasivo.*
