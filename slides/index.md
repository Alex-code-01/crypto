---
marp: true
title: Criptografía - Índice
paginate: true
footer: '[Inicio](index.html)'
headingDivider: 2
theme: marp-viu
---

<style>
    /* You can add custom style here. VSCode supports this.
    Other editor might need these custom code in
    the YAML header: section: | */
</style>

# Criptografía y teoría de códigos
<!-- _class: first-slide -->

**Presentación**

Juan Vera del Campo - <juan.vera@campusviu.es>


## Temario
<!-- _class: cool-list -->

1. [Conceptos básicos](01-conceptos.html)
1. [Criptografía clásica](02-historia.html)
1. [Criptografía de clave simétrica: AES y ChaCha](03-simetrica.html)
    - Anexo: [RNG y HSM](A2-rng.html)
1. [Teoría complejidad y acuerdo Diffie-Hellman](04-complejidad.html)
1. [Criptografía de clave pública: RSA](05-asimetrica.html)

---
<!-- _class: cool-list -->

<style scoped>
    ol { counter-reset: li 5; }
</style>

6. [Funciones de Hash y Blockchain](06-hashes.html)
1. [TLS y Public Key Infrastructure](07-pki.html)
1. [Ransomware](08-ransomware.html)
1. [Esteganografía](09-esteganografia.html)

# Presentación
<!-- _class: lead -->

## Sobre mí

![bg left:45%](images/juanvi.jpg)

Dr. Juan Vera (Juanvi)

juan.vera@campusviu.es

Intereses:

- DFIR: Análisis forense e *Incident Response*
- Miembro del Cyber Incident Response Team de [Valeo](https://es.wikipedia.org/wiki/Valeo)
- Cualquier cosa que vuele

## Intrucciones de uso de las transparencias
<!-- _class: smaller-font -->

Versión más actualizada:

- Acceso directo HTML: <http://juanvvc.github.io/crypto>
    - Puedes pulsar `p` para ver las notas de presentación
    - Con "Inicio" (en pie de cada transparencia) puedes venir a esta presentación, con el índice global de contenidos
- Código Markdown: <https://github.com/juanvvc/crypto>

Durante el estudio personal es muy recomendable seguir los enlaces que aparecen en las transparencias para completar el tema.

El curso está adaptado de [las notas de Jordi Íñigo Griera](https://github.com/jig/crypto), antiguo profesor de la asignatura

[![Licencia de Creative Commons](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/) Esta obra esta sujeta a una licencia de [Atribución 4.0 Internacional de Creative Commons](http://creativecommons.org/licenses/by/4.0/)

## Instrucciones de uso de las actividades
<!-- _class: with-warning smaller-font -->

Los ejercicios son notebook de Jupyter:

1. Instala Jupyter como módulo de Python (Windows, MacOS, Linux): `python3 -m pip install jupyter`
1. En el directorio de ejercicios, ejecuta `jupyter notebook`
1. Comandos básicos:
    - INTRO: edita línea actual
    - SHIFT+INTRO: ejecuta línea actual
1. Tutoriales:
    - https://www.youtube.com/watch?v=jZ952vChhuI
    - https://www.dataquest.io/blog/jupyter-notebook-tutorial/

Presenta las actividades como PDF: si usas los notebook, opción **imprimir a PDF**

## Conocimientos recomendables

- Álgebra básica, teoría de conjuntos, probabilidad
- Conocimientos básicos de programación: ejemplos en Python
- Conocimientos básicos de Linux: comandos en consola
- Conocimientos básicos de redes: cómo funciona la WWW.

## Bibliografía
<!-- _class: smaller-font -->

- Del profesor: <https://juanvvc.github.io/crypto/>
- "[*A Graduate Course in Applied Cryptography*](http://toc.cryptobook.us/)".  Dan Boneh   and   Victor Shoup. Con vídeos en:
    - <https://crypto.stanford.edu/~dabo/courses/OnlineCrypto/>
    - https://www.coursera.org/learn/crypto
    - https://www.coursera.org/learn/crypto2
    - https://www.coursera.org/learn/cryptography
- "[*The Joy of Cryptography*](https://joyofcryptography.com/)" de Mike Rosulek, 2021
- "[*A Course in Cryptography*](https://www.cs.cornell.edu/courses/cs4830/2010fa/lecnotes.pdf)" Rafael Pass & Abhi Shelat. Más ligero que el anterior.
- "[*Handbook of Applied Cryptography*](http://cacr.uwaterloo.ca/hac/)" Alfred J. Menezes. Un clásico para conceptos fundamentales.
- "A Course in Cryptography" Heiko Knospe.
- "Criptografía Ofensiva. Atacando y defendiendo organizaciones". Dr. Alfonso Muñoz.

---
<!-- _class: center -->

Continúa en: [Principios básicos](01-conceptos.html)

# ¡Gracias!
<!-- _class: last-slide -->
