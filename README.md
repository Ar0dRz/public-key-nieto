# Clave Pública PGP

¡Hola! En este repositorio comparto mis claves públicas PGP para que puedas cifrar correos electrónicos o mensajes de manera segura, asegurándote de que solo yo pueda leerlos. Es perfecto para comunicaciones confidenciales con Proton Mail, Thunderbird u otras herramientas compatibles con PGP.

*Si te interesa Proton, aquí puedes obtener una prueba gratis de Proton Plus: [enlace recomendado](https://pr.tn/ref/4SVAYXNQGBHG)*

---

## ¿Cómo contactarme de forma segura?

Dependiendo de tu cliente de correo, tienes varias opciones:

### ✅ Opción 1 — ProtonMail o Tuta

**ProtonMail**: De proton a proton el cifrado E2E es automático al escribirme a `dr.nietodavid@protonmail.com`.
**Tuta**: puedes enviarme un mensaje cifrado por contraseña (modo "confidencial"). Compárteme la contraseña por un canal seguro como Signal antes de enviar.


### ⚙️ Opción 2 — Usas Thunderbird u otro cliente compatible con PGP
Importa mi clave pública directamente desde este repositorio o búscala por mi fingerprint en [keys.openpgp.org](https://keys.openpgp.org).

Si tienes dudas sobre cómo importarla, consulta estas guías:
- [proton.me](https://proton.me)
- [Guía de cifrado asimétrico con Kleopatra — UNAM](https://www.seguridad.unam.mx/sites/default/files/guia-cifrado-asimetrico-con-kleopatra.pdf)
- [keys.openpgp.org](https://keys.openpgp.org)
- [openpgp.org](https://www.openpgp.org)
- [gnupg.org](https://gnupg.org)

---

## Claves Públicas

### 🔑 Principal — ProtonMail

Para comunicaciones profesionales y confidenciales.

| Campo | Valor |
|---|---|
| **Email** | dr.nietodavid@protonmail.com |
| **Fingerprint** | 969C 0614 BA83 3E17 D0DC 6E5D E194 A408 A68C C1BE |
| **Algoritmo** | Ed25519 |

Descarga: [clave-publica-proton.asc](./clave-publica-proton.asc)

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

### 🔑 Secundaria — Gmail

| Campo | Valor |
|---|---|
| **Email** | davo.olive18@gmail.com |
| **Fingerprint** | C829 3765 9CF2 F293 7488  159C 7BCF 80E4 1E44 E1AF |
| **Algoritmo** | Ed25519 / Curve25519 |

Descarga: [clave-publica-gmail.asc](./clave-publica-gmail.asc)

```pgp
-----BEGIN PGP PUBLIC KEY BLOCK-----

mDMEahr1yxYJKwYBBAHaRw8BAQdAovqkJmInYntBjhEME+czD8ErZxc/q00ZDd56
ki6ZifG0HURhdm8gPGRhdm8ub2xpdmUxOEBnbWFpbC5jb20+iHIEExYIABoECwkI
BwIVCAIWAQIZAQWCahr1ywKeAQKbAwAKCRB7z4DkHkThrxEDAP90YqF4QeToMKk2
KjDFhp8vCM6Gt3JD6ZemxazTQbs+GwD/aRGv+7zogFDMhyOf1OsS+j2xKzQusL8C
nVvHTso5fwm4OARqGvXLEgorBgEEAZdVAQUBAQdAjInUO/qScRjCg4IalLLfWZgZ
BN7IK/YojknkXUlKwxMDAQgHiGEEGBYIAAkFgmoa9csCmwwACgkQe8+A5B5E4a8Z
qwEAxyXLYIFQRMC9ccJlDuoKsRcmGbslTJVMkc/3epUVjHMA/jf78Mw6ozWZAh5Y
1x/LQZoXgkn3UUmqDWbEA+uzfIgP
=4Yc7
-----END PGP PUBLIC KEY BLOCK-----
```

---

## Verificar autenticidad

Para verificar que esta clave pública no fue alterada:

1. Importa la clave pública:
```bash
gpg --import clave-publica-proton.asc
```

2. Verifica el fingerprint:
```bash
gpg --fingerprint dr.nietodavid@protonmail.com
```

Confirma que el fingerprint mostrado coincide con el publicado en este repositorio.

---

¡Gracias por visitar! Si me contactas usando estas claves, verifica siempre el fingerprint para evitar suplantación. Si actualizo las claves en el futuro, lo anunciaré aquí con un nuevo commit. ¿Tienes dudas? Envíame un correo cifrado y charlamos. 😊
