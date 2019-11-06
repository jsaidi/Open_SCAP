# Open_SCAP
playbook ansible scan OpenSCAP

==> Définition :

Le protocole SCAP (Security Content Automation Protocol) est une méthode d'utilisation de normes spécifiques pour permettre la gestion automatisée des vulnérabilités, la mesure et l'évaluation de la conformité aux stratégies des systèmes déployés dans une organisation, notamment la conformité FISMA. La National Vulnerability Database (NVD) est le référentiel de contenu gouvernemental américain pour SCAP. Les langages :

OVAL : Open Vulnerability and Assessment Language OCIL : Open Checklist Interactive Language

==> Les formats :

XCCDF : Extensible Configuration Checklist Description Format ** XCCDF est un format de fichier, bien souvent utilisé pour l'interprétation machine d'un guide de recommandation de sécurité (SSG pour SCAP Security Guide). Ces fichiers documentaires permettent de documenter un contrôle ou une "remédiation" (un code permettant la sécurisation).

==> Les protocoles :

SCAP : Security Content Automation Protocol DS : DataStream

==> Les guides:

STIG : Security Technical Implementation Guide SSG : SCAP Security Guide

==> Les entités :

DISA : Defense Information Systems Agency ANSSI : Agence Nationale de la Sécurité des Systèmes d'Information NIST : National Institute of Standards and Technology RHEL : RedHat Enterprise Linux CIS : Community Internet Security

==> HOW TO USE ?

Lancer la ligne de commande suivante :

ansible-playbook -i inv -vv openscap_scan.yml

