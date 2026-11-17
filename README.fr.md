[English](README.md) · **Français**

# eDNA Student Hub

**Une carte partagée des méthodes de l'ADN environnemental, et des chercheurs qui les utilisent.**

[![Le globe de l'accueil, la carte ouverte sur l'étape labo, une fiche de méthode, le filtre par chercheur, une question du forum, puis le français et le thème clair (version anglaise, cliquer pour la vidéo complète)](docs/demo.webp)](https://drive.google.com/file/d/1SRzqDCk7krNjmo-yMZ6l9-5I63kjwFhW/view)

<details><summary>Version française</summary>

[![Le globe de l'accueil, la carte ouverte sur l'étape labo, une fiche de méthode, le filtre par chercheur, une question du forum, puis le français et le thème clair (cliquer pour la vidéo complète)](docs/demo.fr.webp)](https://drive.google.com/file/d/1uoB8rdebPYjlVtq-janLgtl_5qKE9xBT/view)

</details>

*Les personnes et les labos montrés sont fictifs. [Vidéo complète (1 min 28)](https://drive.google.com/file/d/1uoB8rdebPYjlVtq-janLgtl_5qKE9xBT/view)*

## Utilisation

- **Carte des méthodes.** Six étapes, de la question écologique aux statistiques. Un clic ouvre une étape, puis un groupe de méthodes, puis la fiche d'une méthode avec ses articles de référence.
- **Filtres.** Par milieu (air, sol, eau douce, marin, microbiome, ADN ancien), par chercheur ou par labo.
- **Personnes et labos.** Un annuaire des chercheurs avec les méthodes qu'ils utilisent, et une page par labo.
- **Forum et séminaires.** Questions rangées par étape ; séminaires mensuels, avec un fichier d'agenda à télécharger.
- **Comptes.** La lecture se fait sans compte. Un étudiant demande l'accès, un responsable de labo l'accepte ; les membres proposent des méthodes, les responsables les valident.
- **Console d'administration.** Actualités, séminaires, rôles et droits, import du tableur, et le décompte mensuel de la littérature sur OpenAlex.

## Architecture

![Architecture d'eDNA Hub : le navigateur charge l'appli depuis le VPS, lit et écrit la base Supabase selon le rôle de l'utilisateur, importe les publications d'ORCID et de Crossref et compte les articles sur OpenAlex ; les mails sortants attendent dans une file](docs/architecture.svg)

<details><summary>Diagramme en français</summary>

![Architecture d'eDNA Hub : le navigateur charge l'appli depuis le VPS, lit et écrit la base Supabase selon le rôle de l'utilisateur, importe les publications d'ORCID et de Crossref et compte les articles sur OpenAlex ; les mails sortants attendent dans une file](docs/architecture.fr.svg)

</details>

## Exploitation

- **Version.** Version de test en ligne depuis le 10 novembre 2026, non indexée, en attente des retours du labo.
- **Hébergement.** Mon VPS pour l'appli, Supabase dans l'UE pour les données.
- **Pas encore actif.** Les mails sortants restent en file tant que l'adresse d'expédition n'est pas choisie.
- **Vérifications.** 89 tests automatiques ; chaque action testée pour chaque rôle ; ordinateur et téléphone.

---

**Anthony Hunt** · [ingevision.cloud](https://ingevision.cloud/?p=edna-student-hub) · [LinkedIn](https://www.linkedin.com/in/anthony-hunt-3948a9196) · [GitHub](https://github.com/anthohunt)

Le code est privé.
