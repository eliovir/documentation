Hier ist eine Schritt für Schritt Dokumentation um Jeedom auf Raspberry Pi 1 oder 2 zu installieren

> **Tip**
>
> Der Name des heruntergeladenen Jeedom-Abbilds kann sich von dem in dieser Dokumentation unterscheiden.

Schritt 1 : Installieren mit win32diskimager
============================================

Sie müssen den Win32diskimager [hier](http://sourceforge.net/projects/win32diskimager/) herunterladen und ihn auf Ihrem PC installieren

Schritt 2: Wiederherstellung Jeedom-Abbild
==========================================

Vous devez aller [ici](https://www.amazon.fr/clouddrive/share/OwYXPEKiIMdsGhkFeI3eUQ0VcvTEBq0qxQevlXPvPIy/folder/IT3WZ3N0RqGzaLBnBo0qog), puis dans le dossier Images récuperer l’image Raspberry…netinstall.zip

![](../images/install_humming_1.PNG)

Schritt 3: Jeedom-Abbild Dekomprimieren
=======================================

Dekomprimieren des Jeedom-Abbild ( falls Sie nichts zum dekomprimieren haben können Sie hier [winrar](http://www.clubic.com/telecharger-fiche9632-winrar.html) herunterladen ), Sie müssen erhalten:

![](../images/install_humming_2.PNG)

![](../images/install_humming_8.PNG)

Schritt 4 : Das Abbild auf die SD-Karte brennen
===============================================

Legen Sie die SD-Karte in den Computer ein und starten Sie die Win32diskimager Software :

![](../images/install_humming_3.PNG)

Vérifier que dans "Device" c’est bien votre carte SD qui est sélectionnée puis cliquez sur l’icône Dossier pour indiquer le chemin de l’image téléchargée et decompressée (étape 2 et 3) :

![](../images/install_humming_4.PNG)

Klicken Sie auf "Write", um das Abbild zu schreiben, bestätigen Sie die Warnmeldung:

![](../images/install_humming_5.PNG)

Sie können den Fortschritt des Schreibens des Abbildes verfolgen (etwa zehn Minuten) :

![](../images/install_humming_6.PNG)

Sobald Sie fertig sind werden Sie diese Nachricht bekommen :

![](../images/install_humming_7.PNG)

Sie müssen nur die SD-Karte in den Raspberry-Pi stecken, sobald sie das Board mit Strom und dem Netzwerk verbinden, wird Ihre Jeedom (5 min) starten und Sie sollten ihn im Netzwerk sehen.

> **Important**
>
> L’installation se lance automatiquement et vous pouvez la suivre en vous rendant depuis votre navigateur sur l’adresse <http://IP_RASPBERRY/>. Quand l’installation sera terminée, vous vous retrouverez sur l’interface de connexion Jeedom.

> **Tip**
>
> Les identifiants SSH sont root/Mjeedom96. Néanmoins, vous n’avez pas besoin de vous connecter en SSH pour une installation simple.

> **Tip**
>
> L’installation à partir de l’image netinstall réalise les étapes suivantes à votre place : mise à jour du système et des paquets, extension de la partition de la SD au maximum de la capacité de celle-ci.

> **Important**
>
> Wenn Sie einen rpi2 haben, VOR ALLEM NICHT ÜBERTACKTEN, das könnte ein instabiles System zur folge haben mit zahlreicher Beschädigung der SD Karte

Ensuite vous pouvez suivre la documentation [Premier pas avec Jeedom](https://www.jeedom.fr/doc/documentation/premiers-pas/fr_FR/doc-premiers-pas.html)
