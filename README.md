# Poulpe : téléchargements

Poulpe est un organiseur de projets pour Windows et Linux. Vos projets restent
des dossiers sur votre disque, avec leurs notes, tâches, agenda et comptes
rendus de réunion, et une messagerie chiffrée de bout en bout pour échanger
avec d'autres utilisateurs.

Pour vos projets de recherche, l'onglet R&D rassemble le temps passé, le code,
les pipelines de CI et les tests en un dossier de preuves, prêt pour un dossier
de crédit d'impôt recherche ou innovation (CIR, CII).

Ce dépôt ne contient que les installeurs.
**[Télécharger la dernière version](https://github.com/quetzalcoatl79/poulpe-releases/releases/latest)**

## Installer

**Windows 10 et 11** : téléchargez `poulpe-X.Y.Z-x86_64.msi` et lancez-le.
L'installeur n'est pas encore signé par un certificat : si Windows affiche
« Windows a protégé votre ordinateur », cliquez sur *Informations
complémentaires*, puis sur *Exécuter quand même*.

**Debian 12 et plus, Ubuntu 22.04 et plus** : téléchargez
`poulpe_X.Y.Z-1_amd64.deb`, puis :

```bash
sudo apt install ./poulpe_X.Y.Z-1_amd64.deb
```

## Vérifier le fichier téléchargé

Chaque version publie un fichier `SHA256SUMS`. L'empreinte de votre fichier
doit être identique à celle de sa ligne :

- Windows (PowerShell) : `Get-FileHash .\poulpe-X.Y.Z-x86_64.msi`
- Linux : `sha256sum -c SHA256SUMS --ignore-missing`

## Vous avez reçu une invitation ?

1. Installez Poulpe, puis ouvrez-le.
2. Page **Messages** : choisissez un pseudo, puis collez l'adresse **complète**
   de l'invitation dans le champ prévu. Elle contient un « # » : copiez-la en
   entier, depuis la barre d'adresse.
3. Créez votre profil : vous êtes en contact avec la personne qui vous a
   invité, vérifiés des deux côtés.

Le lien ne sert qu'une fois et expire au bout de 30 jours. Les messages et les
fichiers sont chiffrés de bout en bout : le serveur Poulpe ne peut pas les lire.

## Licence

MIT, voir [LICENSE](LICENSE).
