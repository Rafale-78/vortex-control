# VORTEX Control

Logiciel gratuit pour Windows 10/11 (64 bits) : pilote chaque ventilateur du PC (courbes, courbes mixtes, profils, automatismes), règle la luminosité des écrans, surveille toutes les températures et explique les pannes grâce à son dépannage automatique. En français, anglais, espagnol, allemand et italien.

**Télécharger :** [dernière version](../../releases/latest) → `VORTEX-Control-Setup-x.y.z.exe` (tout est inclus : .NET et le pilote PawnIO).
**Présentation et notice :** [rafale-78.github.io/vortex-control](https://rafale-78.github.io/vortex-control/).
**Un problème ?** Le bouton « Signaler un problème » de l'application ouvre une fenêtre pour le décrire et l'envoyer directement, avec le rapport technique si vous le souhaitez.
**Contact :** `vortex.support.contact` (arobase) `gmail.com`.

Windows peut afficher « Windows a protégé votre ordinateur » : VORTEX n'est pas encore signé par un certificat payant. Cliquez sur *Informations complémentaires*, puis *Exécuter quand même*. Les empreintes SHA-256 des fichiers figurent dans `SHA256SUMS.txt`.

Vie privée : VORTEX ne se connecte à internet que si vous le demandez (recherche de mise à jour, test de connexion), si vous avez activé la mise à jour automatique ou si vous avez accepté l'envoi de rapports d'erreur (sans nom ni adresse IP). Aucune donnée n'est vendue. Détails : [confidentialité](https://rafale-78.github.io/vortex-control/confidentialite.html) · [mentions légales](https://rafale-78.github.io/vortex-control/mentions-legales.html).

Ce dépôt ne contient que le site, le fichier de version (`latest.json`) et les versions publiées ; le code source n'est pas public.

Composants tiers : LibreHardwareMonitor, DiskInfoToolkit, BlackSharp et RAMSPDToolkit (MPL-2.0 ; code source sur GitHub : LibreHardwareMonitor/LibreHardwareMonitor et Blacktempel/DiskInfoToolkit, BlackSharp, RAMSPDToolkit), HidSharp (Apache-2.0), PawnIO (GPL-2.0, © namazso), .NET, WPF, CommunityToolkit.Mvvm et Sentry (MIT). Leurs licences sont installées avec VORTEX (dossier `licences`).
