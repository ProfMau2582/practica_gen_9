# Prácticas de Matemática · Noveno

Prácticas autocorregibles con retroalimentación para preparar la prueba parcial.
El estudiante elige el tema en el menú (`index.html`).

| Tema | Contenido | Preguntas |
|---|---|---|
| 1 | Razones trigonométricas, elevación y depresión, problemas de aplicación | 18 |
| 2 | Ley de senos y ley de cosenos | 13 |
| 3 | Identidades trigonométricas | 15 |
| 4 | Operaciones con monomios y polinomios | 13 |
| 5 | Factorización | 15 |
| 6 | Fracciones algebraicas (restricciones y simplificación) | 12 |
| 7 | Operaciones con fracciones algebraicas | 12 |

## Cómo publicarlo en GitHub Pages

Son solo **8 archivos sueltos, sin carpetas**, así que funcionan aunque se suban arrastrándolos.

1. En su repositorio, borre los archivos de la versión anterior (`practica.html` y las carpetas `assets` y `datos`), si los subió.
2. Presione **Add file → Upload files** y arrastre: `index.html`, `tema1.html` … `tema7.html` y `README.md`. Luego **Commit changes**.
3. En **Settings → Pages** debe estar la rama `main` y la carpeta `/ (root)`.
4. En uno o dos minutos el sitio queda en `https://SU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

Para enlazar un tema directamente: `.../tema5.html`.

## Estructura

```
index.html            Menú de temas (con ilustraciones y mejor resultado de cada tema)
tema1.html … tema7.html   Cada práctica completa en un solo archivo
```

Las fórmulas se dibujan con KaTeX desde internet (jsDelivr), por eso se necesita conexión.

## Tipos de pregunta

- **Selección única** (`mc`): retroalimentación específica para cada opción incorrecta.
- **Numérica** (`num`): acepta coma o punto; detecta errores comunes (calculadora en radianes, razón equivocada, despeje al revés, olvidar sumar una altura).
- **Respuesta escrita** (`expr`): el estudiante escribe una expresión, por ejemplo `(x-7)(x+5)`. Se comprueba que sea equivalente y además:
  - en factorización, que esté escrita como producto y **completamente** factorizada;
  - en operaciones con polinomios, que esté desarrollada y reducida;
  - en fracciones, que sea una sola fracción **simplificada**.
- **Pareo** (`match`): con opciones adicionales que no se usan.

## Importante

La revisión ocurre en el navegador del estudiante: **las notas no se envían al profesor**.
Al final, el estudiante presiona «Ver resumen» para imprimir, guardar en PDF o copiar sus resultados.
