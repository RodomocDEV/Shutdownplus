SHUTDOWN PLUS
-------------
- Version : 2.0
- Auteur  : Rodomoc

DESCRIPTION
-----------
Shutdown Plus est un utilitaire Windows moderne et léger
permettant de programmer un ARRÊT, une VEILLE ou un REDÉMARRAGE
automatique de l’ordinateur.

Deux modes de fonctionnement :
- Mode Inactivité : déclenche l’action après X minutes sans activité clavier/souris.
- Mode Différé : déclenche l’action après un compte à rebours défini.

L’application peut s’exécuter en arrière-plan (systray),
émettre une notification sonore avant l’action et conserver
les paramètres entre les sessions.

------------------------------------------------------------
FONCTIONNALITÉS
------------------------------------------------------------
- Interface moderne avec CustomTkinter.
- Arrêt / Veille / Redémarrage selon délai ou inactivité.
- Barre système (icône systray) et réduction en arrière-plan.
- Notification sonore et visuelle avant exécution.
- Thème personnalisable et multilingue (FR/EN).
- Option de démarrage automatique avec Windows.
- Sauvegarde des paramètres dans %APPDATA%.
- Empêche les doubles instances de l’application.
- Compatible exécutable autonome via PyInstaller.

------------------------------------------------------------
CONFIGURATION REQUISE
------------------------------------------------------------
- Windows 10 ou 11
- Python 3.10+ (si non packagé en .exe)
- Modules Python : customtkinter, pynput, pywin32, pillow

------------------------------------------------------------
INSTALLATION DES DÉPENDANCES (mode développement)
------------------------------------------------------------
pip install customtkinter pynput pywin32 pillow

------------------------------------------------------------
UTILISATION
------------------------------------------------------------
1. Lancer l'application.
2. Choisir un mode (Inactivité ou Différé).
3. Régler le délai avec le curseur.
4. Cliquer sur l’action souhaitée (Arrêt, Veille, Redémarrage).
5. Une notification sonore et visuelle sera émise avant exécution.
6. Utiliser le bouton Annuler pour interrompre une action programmée.
7. Accéder aux paramètres via le menu Options > Paramètres.

------------------------------------------------------------
PARAMÈTRES
------------------------------------------------------------
- Langue : Français ou Anglais.
- Démarrage automatique : oui/non.
- Démarrage minimisé : oui/non.
- Action au démarrage : aucune ou action prédéfinie.
- Délai par défaut : en minutes.

------------------------------------------------------------
COMPILATION EN EXÉCUTABLE
------------------------------------------------------------
Exemple avec PyInstaller :
pyinstaller --onefile --noconsole --icon "assets/icons/Red-Skull.ico" --add-data "assets;assets" shutdown_plus.py

------------------------------------------------------------
LICENCE
------------------------------------------------------------
MIT Copyright (c) 2025 RodomocDEV

