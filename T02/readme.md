# T02: Control de versions. Treballant amb git

## Breu descripció
De moment hem gestionat el control de versions usant directament el repositori des de la web de **GitHub**. Tot i que ens ha solucionat força problemes, és evident que aquesta metodologia té diverses limitacions:

- **Lentitud a l’hora d’editar**: l’editor web no és tan versàtil com un editor local, ja sigui de codi (Visual Studio Code) o un editor de Markdown específic com **Ghostwriter**.
- **Dificultat en la gestió del repositori**: afegir arxius o carpetes pot resultar feixuc i requereix accions poc eficients.

Per aquest motiu, començarem a treballar **tal com es fa en el món real**: combinant el **control de versions local amb git** i un **gestor de repositoris remots**, en aquest cas **GitHub**.  
No són les úniques solucions disponibles, especialment a nivell remot, on també existeixen alternatives com **Bitbucket** o **GitLab**.

De fet, **git va aparèixer abans que GitHub**, com un protocol de control de versions **descentralitzat**, que va trencar amb el model centralitzat que imperava fins aquell moment. Git va ser creat per **Linus Torvalds**, el creador de **Linux**.

---

## Com hi treballarem?
En el nostre cas, **partirem sempre d’un repositori existent a GitHub**. El primer pas serà disposar d’una **còpia sincronitzada en local**, per exemple al disc dur del PC.

A partir d’aquí:

1. **Els canvis es faran sempre en local**, utilitzant editors adequats.
2. Seguirem el flux de treball habitual de git:
   - `git add`
   - `git commit`
3. Cada cop que deixem la feina, **pujarem els canvis a GitHub** mitjançant un `git push`.
4. Quan reprenguem la feina, farem un `git pull` per assegurar-nos que la còpia local està actualitzada.

Això és especialment important si:
- canviem d’ordinador,
- treballem des del PC de l’escola i el de casa,
- o col·laborem amb altres persones sobre el mateix repositori.

---

## Materials i links de suport
- **Introducció a GitHub**  
  https://github.com/SMX2n/IntroGitHub

- **Guia de Control de Versions**  
  https://github.com/SMX2n/ControlVersions
