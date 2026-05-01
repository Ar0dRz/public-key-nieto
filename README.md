# Clave Pública PGP

¡Hola! En este repositorio comparto mi clave pública PGP para que puedas cifrar correos electrónicos o mensajes de manera segura, asegurándote de que solo yo pueda leerlos. Es perfecto para comunicaciones confidenciales con Proton Mail, Thunderbird u otras herramientas compatibles con PGP.

*Si te interesa Proton, aquí puedes obtener un mes gratis de Proton Plus: [enlace recomendado](https://pr.tn/ref/4SVAYXNQGBHG)*

---

## ¿Cómo contactarme de forma segura?

Dependiendo de tu cliente de correo, tienes varias opciones:

### ✅ Opción 1 — ProtonMail o Tuta

**ProtonMail**: el cifrado E2E es automático al escribirme.
**Tuta**: puedes enviarme un mensaje cifrado por contraseña (modo "confidencial"). Compárteme la contraseña por un canal seguro como Signal antes de enviar.

### ✅ Opción 2 — Usas Gmail (recomendado para usuarios de Google)
Instala **[FlowCrypt](https://flowcrypt.com)**, disponible de forma gratuita para Chrome, Firefox, Android e iOS. Una vez instalado, detecta mi clave pública automáticamente y cifra el mensaje sin configuración adicional. Es la forma más rápida de empezar si ya usas Gmail.

### ⚙️ Opción 3 — Usas Thunderbird u otro cliente compatible con PGP
Importa mi clave pública directamente desde este repositorio o búscala por mi fingerprint en [keys.openpgp.org](https://keys.openpgp.org):

```
969C 0614 BA83 3E17 D0DC 6E5D E194 A408 A68C C1BE
```

Si tienes dudas sobre cómo importarla, consulta estas guías:
- [proton.me](https://proton.me)
- [Guía de cifrado asimétrico con Kleopatra — UNAM](https://www.seguridad.unam.mx/sites/default/files/guia-cifrado-asimetrico-con-kleopatra.pdf)
- [keys.openpgp.org](https://keys.openpgp.org)
- [openpgp.org](https://www.openpgp.org)
- [gnupg.org](https://gnupg.org)


---

## Clave Pública

Aquí está el bloque completo de la clave en formato ASCII. Copíalo directamente o impórtalo en tu software PGP favorito, como GPG o Kleopatra, para empezar a cifrar.

### Detalles de la clave

| Campo | Valor |
|---|---|
| **Email** | dr.nietodavid@protonmail.com |
| **Fingerprint** | 969C 0614 BA83 3E17 D0DC 6E5D E194 A408 A68C C1BE |
| **Algoritmo** | Ed25519 |

### Descarga el archivo

Si prefieres descargar la clave en un archivo listo para importar, haz clic en [clave-publica.asc](./clave-publica.asc) directamente en este repositorio. Es un archivo `.asc` estándar compatible con la mayoría de herramientas PGP.

```pgp
-----BEGIN PGP PUBLIC KEY BLOCK-----

xjMEY+r88BYJKwYBBAHaRw8BAQdAYo1IYlCEVAC4VcSKX3VUOlNCGVRKqr5N
7JTjXSdEQRTNO2RyLm5pZXRvZGF2aWRAcHJvdG9ubWFpbC5jb20gPGRyLm5p
ZXRvZGF2aWRAcHJvdG9ubWFpbC5jb20+wowEExYIAD4FAmPq/PAJkOGUpAim
jMG+FiEElpwGFLqDPhfQ3G5d4ZSkCKaMwb4CGwMCHgECGQEDCwkHAhUIAxYA
AgIiAQAAaMYBAObb896uEcZtpLmLW6Ob9tkX940feZToMJQAut/fwSK8AP43
ICs2sqCYya4j8ZKk2WehwuqmNm1gCSAgS5jN2Yf6B844BGPq/PASCisGAQQB
l1UBBQEBB0B2ZbuwRkjJdhhJMMQKsBe5r/kSlTQqCxxnx+440+fTdAMBCgnC
eAQYFggAKgUCY+r88AmQ4ZSkCKaMwb4WIQSWnAYUuoM+F9Dcbl3hlKQIpozB
vgIbDAAAlBEA/3I7c0ttCVa/yiIUiLeVQUZCXcFHGAhNEs2wt3Inc6e5AP9C
XoKMgV1LAckTOi5pE11W7n3zWeiDQnthDL3w7dPFCw==
=lz6O
-----END PGP PUBLIC KEY BLOCK-----
```

---

## Verificar autenticidad

Para verificar que esta clave pública no fue alterada:

1. Importa la clave pública:
```bash
gpg --import clave-publica.asc
```

2. Verifica la firma:
```bash
gpg --verify clave-publica.asc.sig clave-publica.asc
```

Un mensaje **"Good signature"** confirma que el archivo es auténtico y no fue modificado.

---

¡Gracias por visitar! Si me contactas usando esta clave, verifica siempre el fingerprint para evitar suplantación. Si actualizo la clave en el futuro, lo anunciaré aquí con un nuevo commit. ¿Tienes dudas? Envíame un correo cifrado y charlamos. 😊

