# T04: Instal·lació Windows Server 2025

## Breu descripció

### Introducció al cas
Després del nostre assessorament, **TransLògic S.A.** ens encarrega el desplegament dels seus **servidors Windows Server 2025**.

Per aquest motiu, haurem de desplegar diverses **màquines virtuals** i, amb l’objectiu de ser eficients i seguir **bones pràctiques**, realitzarem una **instal·lació de prova**.  
Aquesta instal·lació servirà tant per:
- aprendre els procediments,
- com per elaborar una **guia d’instal·lació** que actuarà com a documentació base per a la posterior implantació als sistemes del client.

---

## Procediment

- Crear una **màquina virtual** amb les característiques següents:
  - **8 GB de RAM**
  - **2 processadors**
  - **2 discos**:
    - Disc principal de **32 GB** (instal·lació del SO)
    - Disc secundari de **10 GB**
  - **2 interfícies de xarxa**:
    - Una en xarxa **NAT (no NAT)**  
    - Una en xarxa **Host-only**

- Instal·lar **Windows Server 2025** amb:
  - Mode **GUI**
  - Idioma del sistema: **US**
  - Configuració regional i teclat: **Espanyol**

- Canviar el nom de l’equip a:
  - **DCxx** (on *xx* correspon al vostre número de llista)

- Actualitzar la màquina virtual.
  - Un cop finalitzades les actualitzacions, **pausar-les el màxim temps possible**.

---

## Contingut de la guia

La guia d’instal·lació ha d’incloure:

- Comparació entre:
  - la configuració de la màquina virtual definida anteriorment
  - els **requisits oficials de Microsoft** per a Windows Server 2025  
  → Valorar si són **coherents** i justificar-ho.

- Documentació detallada dels **procediments d’instal·lació**, incloent:
  - captures de pantalla
  - observacions i comentaris tècnics

- **Format obligatori**: **Markdown**

---

## Materials i links de suport

- **UD.6. AA2. Instal·lació Windows Server 2025**  
  *Moodle – 0224 Sistemes Operatius en Xarxa*

- **Requisitos de hardware para Windows Server**  
  Microsoft Learn (enllaç)
