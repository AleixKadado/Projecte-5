# T03: Serveis de transferència de fitxers

## Breu descripció

### Introducció a la tasca
En la vostra experiència en **EverPia** heu configurat serveis molt importants com **DHCP**, **DNS**, així com la **connexió i administració remota dels equips**.

Ara que comenceu el vostre camí en solitari, necessiteu ampliar coneixements. Tot i que serveis de *cloud* com **Dropbox**, **Google Drive**, etc. són en moltes ocasions la forma més habitual de descarregar i compartir arxius, és imprescindible dominar els **protocols fonamentals de transferència de fitxers**.

Per aquest motiu, us inscriviu a una formació amb l’objectiu de **convertir-vos en experts en transferència de fitxers a nivell de sistema i xarxa**.

---

## Objectius de la formació
En acabar aquesta formació, haureu de ser capaços de respondre a les preguntes següents **amb fets i configuracions reals**:

- Com funciona el protocol **FTP**?
- Quina diferència hi ha entre el **mode actiu** i el **mode passiu**?
- Com s’implementa un **servidor FTP segur**?
- El protocol **sFTP** com a alternativa al FTP tradicional.
- **Engabiat (chroot) d’usuaris** en connexions sFTP.
- **Altres mètodes alternatius** per a la transferència de fitxers.

---

## Pla de treball: què farem?
Aquesta formació es divideix en **dues parts clarament diferenciades**: la fonamentació teòrica i la implementació real.

### 1. Fonaments teòrics i seguretat
Estudi dels protocols **FTP** i **sFTP**, posant especial atenció a:
- Modes actiu i passiu del protocol FTP
- Engabiat d’usuaris
- Aspectes de **seguretat** i riscos associats

### 2. Laboratori pràctic (The “Real World”)
Posarem les mans al teclat. Configurarem **dos entorns diferenciats** utilitzant màquines virtuals:

#### Activitat A – Servidor FTP
- Configuració d’un servidor FTP estàndard
- Creació d’usuaris
- Engabiat (chroot)
- Permisos de lectura i escriptura
- Observació de com les dades viatgen **en clar (sense xifrar)**

#### Activitat B – Servidor sFTP (Secure FTP)
- Implementació de la transferència de fitxers sobre **SSH**
- Configuració d’usuaris sFTP
- Engabiat d’usuaris per evitar **fuites de seguretat**

> **Nota important:**  
> Com a administradors de sistemes, la **seguretat no és una opció, és una obligació**.  
> Entendre la diferència entre FTP i sFTP és **vital per al vostre futur professional**.

---

## Sistema d’avaluació
Per superar aquesta formació, haureu de demostrar la vostra competència mitjançant **dos formats d’avaluació**:

### Prova escrita (40%)
- Preguntes sobre:
  - Protocols
  - Ports
  - Modes de connexió
  - Conceptes de seguretat teòrica

### Examen pràctic – Repte de configuració cronometrat (60%)
- Aixecar **des de zero**:
  - Un servidor FTP
  - Un servidor sFTP
- Configurar usuaris amb permisos específics
- Verificar la connexió des d’un **client extern**

---

## Tancament
Prepareu les vostres **màquines virtuals**.  
**Comencem a transferir dades!**

---

## Materials i links de suport
- Materials de l’assignatura: **Moodle – Serveis de Xarxa**
