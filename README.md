# Installation de Kali Nethunter sur Android sans root

Ce script permet d'installer Kali Nethunter sur un appareil Android sans nécessiter de root. Il est mis à disposition par **trhacknon**.

**[Read this in English](https://github.com/tucommenceapousser/installnh/blob/main/README-EN.md)**

## Prérequis

- Un appareil Android avec Termux installé.
- Connexion Internet active.

## Instructions

### Étape 1 : Télécharger le script

Téléchargez le script en exécutant les commandes suivantes dans Termux :

```bash
pkg install wget -y
wget -O install_kali.sh https://haste-server-me13.onrender.com/raw/iroceholar
chmod +x install_kali.sh
```

### Étape 2 : Exécuter le script

Exécutez le script téléchargé :

```bash
./install_kali.sh
```

### Détails du script

Le script effectue les actions suivantes :

1. **Configuration du stockage pour Termux** :
    - Commande : `termux-setup-storage`
    - Description : Configure les permissions de stockage pour Termux.

2. **Installation de wget** :
    - Commande : `pkg install wget -y`
    - Description : Installe l'outil wget pour télécharger des fichiers.

3. **Téléchargement du script d'installation** :
    - Commande : `wget -O install-nethunter-termux https://haste-server-me13.onrender.com/raw/ogixuzodeh`
    - Description : Télécharge le script d'installation de Kali Nethunter.

4. **Rendre le script d'installation exécutable** :
    - Commande : `chmod +x install-nethunter-termux`
    - Description : Modifie les permissions du script pour le rendre exécutable.

5. **Exécution du script d'installation** :
    - Commande : `bash install-nethunter-termux`
    - Description : Exécute le script d'installation téléchargé.

### Avertissements

- Assurez-vous que votre appareil Android est compatible avec Termux et Kali Nethunter.
- Ce script est fourni tel quel, sans garantie. Utilisez-le à vos propres risques.

### Support

Pour toute question ou assistance, veuillez contacter **trhacknon** via [lien de contact].

### Capture d'écran

Voici une capture d'écran simulant l'exécution du script :

![Capture d'écran](sc.png)

---

**Note** : Ce README utilise une mise en forme simple pour une meilleure lisibilité. Pour des effets visuels avancés, vous pouvez explorer les fonctionnalités de Markdown étendues et des plugins GitHub.
