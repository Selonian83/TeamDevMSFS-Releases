<p align="center">
  <img src="logo.png" alt="TeamDev Virtual Aviation — MSFS 2024" width="480">
</p>

# TeamDev Virtual Aviation — MSFS 2024

> Compagnon de vol pour Microsoft Flight Simulator 2024, avec ses missions
> directement dans la tablette EFB de l’appareil.

**[⬇ Télécharger la dernière version](../../releases/latest)**

---

## Installation

Le programme d’installation met tout en place en un seul clic. Aucune
configuration n’est nécessaire.

**Prérequis** : Windows 10 (mise à jour d’avril 2018) ou Windows 11 en
64 bits, et Microsoft Flight Simulator 2024. Le .NET Framework 4.7.2 est
fourni avec ces versions de Windows.

### Étapes

1. Téléchargez `TeamDevVirtualAviation-<version>-setup.exe` depuis la
   [dernière version](../../releases/latest).

2. Lancez le fichier. Windows affiche **« Windows a protégé votre PC »** :
   cliquez sur **Informations complémentaires**, puis sur **Exécuter quand
   même**.

   > Cet avertissement apparaît pour tout programme non signé numériquement.
   > Il ne signale aucun problème avec le logiciel : Windows indique
   > simplement qu’il ne connaît pas encore son éditeur.

3. Suivez l’assistant. Il ne demande rien d’autre que l’emplacement
   d’installation.

4. **Lancez TeamDev une première fois avant de démarrer MSFS 2024.**
   Le logiciel installe alors le pont EFB dans le dossier `Community` du
   simulateur et vous en avertit.

5. **Fermez complètement MSFS 2024 s’il était ouvert, puis relancez-le.**
   Les paquets du dossier `Community` ne sont lus qu’au démarrage du
   simulateur. Cette étape n’est nécessaire qu’une seule fois.

6. Entrez dans un vol, relancez TeamDev, puis choisissez une mission.

L’application **TeamDev Missions** apparaît alors dans la tablette EFB de
l’appareil, missions et routes comprises.

## Ce que l’installation met en place

- Le client Windows et les bibliothèques SimConnect;
- le paquet EFB `teamdev-route-bridge`, déployé dans votre dossier
  `Community` au premier lancement du logiciel;
- des raccourcis dans le menu Démarrer et, au choix, sur le Bureau.

Le dossier `Community` est localisé automatiquement. Les installations
Microsoft Store/Xbox et Steam sont prises en charge, ainsi que les dossiers
de paquets déplacés sur un autre disque.

## Désinstallation

Par **Paramètres → Applications** de Windows. Le désinstalleur propose de
retirer également le pont du dossier `Community` : répondez **Non** si vous
comptez réinstaller le logiciel.

## Un problème ?

Ouvrez un [ticket](../../issues) en précisant votre version de Windows,
votre édition de MSFS 2024 (Microsoft Store, Xbox ou Steam) et ce que le
journal de TeamDev affiche au démarrage.

---

<p align="center"><sub>
Ce dépôt ne contient que les versions publiées. Le code source est privé.
</sub></p>
