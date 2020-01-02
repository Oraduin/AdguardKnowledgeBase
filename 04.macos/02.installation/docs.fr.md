---
title: 'Installation/Désinstallation'
taxonomy:
    category:
        - docs
---

## Configuration requise

**Système d'exploitation :** macOS 10.10 (64 bit) ou plus récent

**Mémoire vive (RAM) :** minimum 2Go

**Navigateurs :** Safari, Google Chrome, Opera, Yandex.Browser, Mozilla Firefox, tout navigateur compatible macOS

**Espace disque requis :** 120Mo

## Installation

Afin d'installer AdGuard pour macOS, ouvrez votre navigateur internet et rendez vous sur _adguard.com_, puis choisissez **Télécharger** sur la page qui s'affiche.

<img src="https://cdn.adguard.com/public/Adguard/kb/newscreenshots/En/MacOs/mainpageEn.png" />

Attendez la fin du téléchargement d'_Adguard.release.dmg_ et double-cliquez sur son icône dans la liste des téléchargements du Dock ou le dossier Téléchargements. L'icône AdGuard apparaît sur votre Bureau, cliquez pour lancer le processus d'installation.

<img src="https://cdn.adguard.com/public/Adguard/kb/newscreenshots/Ru/MacOs/installerRu.png" />

 Lors de la première ouverture, le système d'exploitation vous avertit que cette application a été téléchargée depuis internet. Sélectionnez **Ouvrir**.

<img src="https://cdn.adguard.com/public/Adguard/kb/newscreenshots/En/MacOs/notificationEn.png" />

À l'étape suivante, cliquez sur **Installer**.

<img src="https://cdn.adguard.com/public/Adguard/kb/newscreenshots/En/MacOs/installEn.png" />

Pour utiliser l'application, vous aurez besoin du mot de passe administrateur de votre mac.
Entrez le mot de passe lorsqu'il vous est demandé et choissisez **OK**.

<img src="https://cdn.adguard.com/public/Adguard/kb/newscreenshots/En/MacOs/userpwEn.png" />

<a name="uninstall"></a>
## Désinstallation

### Normale
Ouvrez l'application Finder dans le Dock :

![](https://cdn.adguard.com/public/Adguard/En/Articles/howtodelete/finder.png)

Naviguez jusqu'au dossier "Applications". Cliquez-droit sur AdGuard et choisissez "Placer dans la corbeille" ou glissez l'icône dans la corbeille.

![](https://cdn.adguard.com/public/Adguard/En/Articles/howtodelete/delete_mac.png)

### Avancée
**Ces étapes ne peuvent être accomplies qu'après avoir réaliser une désinstallation normale.** Après la désinstallation, effectuez les actions suivantes :

* Supprimez les fichiers et dossiers suivants :
	* */Bibliothèque/Application Support/com.adguard.Adguard* (dossier)
	* *~/Bibliothèque/Application Support/com.adguard.Adguard* (dossier)
	* *~/Bibliothèque/Preferences/com.adguard.Arguard.plist* (fichier)

* Ouvrez l'application "Moniteur d'activité".
* Dans la barre de recherche, trouvez le processus **cfprefsd**.

![](https://cdn.adguard.com/public/Adguard/En/Articles/howtodelete/cfprefsd_find.png)

* Arrêtez le processus assigné à l'utilisateur (pas celui assigné au root).

![](https://cdn.adguard.com/public/Adguard/En/Articles/howtodelete/cfprefsd_abort.png)

AdGuard est maintenant totalement désinstallé.
