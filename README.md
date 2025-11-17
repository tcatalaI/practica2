# Pràctica 2 - Markdown i Col·laboració amb GitHub
> Curs: Git i GitHub (FP)
> 
> Professor: Miquel A. Cabot

## Descripció

Aquesta pràctica introdueix l'ús del **llenguatge de marques Markdown** i les eines de **col·laboració de GitHub**.

Aprendràs a crear documents `.md` i a simular un flux de treball típic a GitHub (branques, commits, pull requests i issues) dins el teu **propi repositori**.

El repositori s'ha creat automàticament mitjançant **GitHub Classroom**. No cal crear-ne cap altre: simplement treballau dins aquest.

## Objectius

- Escriure documents ben estructurats amb sintaxi Markdown.
- Crear i gestionar branques dins d'un repositori GitHub.
- Simular una col·laboració completa utilitzant **pull requests** i **issues**.
- Opcionalment, publicar els resultats com a web amb **GitHub Pages**.

## Passes a seguir

1. **Clona el repositori a l'ordinador**

   - Ves a la pàgina del teu repositori dins l'organització [curs-git-fp](https://github.com/curs-git-fp).
   - Copia l'adreça HTTPS del botó verd "Code".
   - Obre el terminal i executa:

   ```bash
   git clone https://github.com/curs-git-fp/nom-del-teu-repositori.git
   cd nom-del-teu-repositori
    ```

2. **Crea un fitxer PRACTICA2.md**
   - Utilitza **Markdown** per descriure la pràctica:
     - Títol (`#`)
     - El teu nom i la data
     - Breu descripció de la tasca
     - Índex de continguts amb enllaços als altres fitxers
     - Enllaç al teu perfil de GitHub
   - Exemple:
   ```markdown
   # Pràctica 2 - Markdown i Col·laboració

   **Nom:** Miquel A. Cabot
   **Data:** 23/10/2025

   ## Continguts
   1. [Sintaxi bàsica](./format.md)
   2. [Enllaços i imatges](./enllacos_i_imatges.md)
   3. [Taules i codi](./taules_i_codi.md)
   4. [Simulació de col·laboració](./colaboracio.md)

   [Perfil GitHub](https://github.com/elmeuusuari)
   ```

3. **Crea tres fitxers Markdown temàtics**
   - Cada fitxer ha de demostrar elements de la sintaxi Markdown:
     - `format.md`: Títols, negreta, cursiva, ratllat i llistes numerades i amb punts.
     - `enllacos_i_imatges.md`: Enllaços, imatges externes i una imatge local dins img/.
     - `taules_i_codi.md`: Taules amb alineacions i exemples de blocs de codi amb ressaltat.

4. **Treballa en branques separades**
   - Crea una branca per a cada tema:

   ```bash
   git branch format
   git branch enllacos-i-imatges
   git branch taules-i-codi
   ```

   - A cada branca:
     - Escriu el fitxer corresponent.
     - Fes `git add`, `git commit` i `git push origin <nom-de-la-branca>`.

5. **Simula col·laboració amb Pull Requests**
   - A GitHub, obre una **Pull Request (PR)** per fusionar cada branca amb `main`.
   - Escriu una descripció clara a la PR (ex: _"Afegit fitxer de format Markdown"_).
   - Accepta la PR (Merge) tu mateix.
   - Esborra la branca després del merge.

6. **Crea el fitxer `colaboracio.md`**
   - Aquest fitxer documentarà el procés de col·laboració individual.
   - Inclou-hi:
     - Explicació de què és un **fork**, una **PR** i una **issue**.
     - Captures de pantalla de les teves PRs i issues (desa-les dins `img/`).
     - Una petita reflexió final sobre els avantatges del flux GitHub per treballar en equip.

7. **Obre i tanca una issue simulada**
   - A l'apartat "Issues" del teu repositori, crea una issue amb títol:
     > "Afegir el fitxer colaboracio.md al repositori"
   - Escriu una breu descripció i etiqueta-la com `enhancement`.
   - Assigna-la a tu mateix.
   - Crea una PR que afegeixi el fitxer `colaboracio.md` al repositori, esmentant la issue.
   - Mergeja la PR.
   - Veuràs que la issue es tanca automàticament.

8. **(Opcional) Publica amb GitHub Pages**
   - Ves a la configuració del repositori i activa GitHub Pages des de la branca `main`.
   - Selecciona la carpeta `/ (root)` com a font.
   - Espera uns minuts i comprova que el teu contingut està disponible en línia.
   - Potser necessitaràs alguns ajustos més (consulta-ho).
   - Documenta l'enllaç a la teva pàgina GitHub Pages dins del fitxer `PRACTICA2.md`.

9. **Revisa el repositori a GitHub**
   - Assegura't que a la branca `main` hi apareixen els quatre fitxers:

   ```txt
   PRACTICA2.md
   format.md
   enllacos_i_imatges.md
   taules_i_codi.md
   colaboracio.md
   img/(carpeta amb imatges)
   ```

## Lliurament

1. Obre la tasca corresponent a Google Classroom
2. Enganxa l'enllaç del teu repositori de GitHub (exemple):

   ```txt
   https://github.com/curs-git-fp/nom-del-teu-repositori
   ```
