# Objectif
Le but est de proposer une présentation du MLops **presentation_mlops** (presentation_mlops.md) sous forme d'un document markdown, à une population composée des développeurs, des chefs de projet et des administrateurs système.
# Contexte
- les sources suivants seront la références pour la presentation :
  - **reference_1** : https://ml-ops.org/content/mlops-principles
  - **reference_2** : https://engineering.rappi.com/the-role-of-mlops-on-effective-ai-dda75d638805
  - **reference_3** : https://www.thedataops.org/what-are-the-4-key-stages-of-mlops/
- Tu peux utiliser d'autres références ou difinitions que tu juge nécessaires.
- La presentation est structuré en quatre parties:
  - **Chapitre 1** : Définir le mlops dans la littérature et une présenter les outils sur le marché.
  - **Chapitre 2** : définir le **workflow mlops** (workflow_mlops) et présenter sont évoltion à partir du cas classique, tu dois :
    - représenter par un **schema fonctionel** chaque etape du workflow mlops.
    - Représenter les **outils__opensource** utilisés dans chaque étape du workflow mlops.
  - **Chapitre 3 ** : dans ce chapitre tu présentes les principes du MLOPS.
    - tu te base principalement sur la refrence_1
    - tu peux utuliser d'autres ressources de ton choix.
  - **Chapitre 4** : faire une démonstration d'un **use_case_** simple.
- Tous les matériaux utilisés sont partagés dans le **repo_github**
  - le initialiser la valeur [repo_github = https://github.com/SoufieneCHR/presentation_mlops]
  - lors de l'éxecution, tu peux utiliser les ressources proposées par github comme le github actions.
  - la durée totale de la présentation ne dois pas dépasser 45 minutes.
  - la presentation finira par une partie conclusion qui présente les avantages, les challenges du mlops et les perspectives d'avenir (par exemple AIOps, DataOPS, LLMOps, ...).

# Chapitre 1
- tu te bases sur les références fournis pour definir et présenter  le MLOPS, DEVOPS, DATA ENGINEEIRNG et Machine Learning.
- tu peux utiliser un ou plusieurs graphes ou images pour illustrer les définitions, en citant la référence.
- Presente 3 différentes avec leurs références.
- présenter la différence avec le devops
- Liste les roles et les profiles qui peuvent exercer dans le MLOPS.
- Ulluster le maximum avec des graphes ou images, même prise sur internet avec leurs références respectives.
- ceci est un exemple de workflow que tu peux l'adapter au context actuel https://miro.medium.com/v2/resize:fit:1100/format:webp/1*BR6p6wxurkalz98obiUdZQ.png.

# Chapitre 2
- Utilises la reference_2 pour définir l'évoltion vers le workflow full mlops (définie dans l'article comme level 4) à partir du workflow classique (level 0)
- presente chaque étape (du level 0 à level 4) dans une paragraphe en mettant le shema et les explications.
- Présenter les outils utilisés dans chaque étape su workflow, privilèges les outils opensource (par exemple jupytherhub, airflow, superset, ...).
- Ulluster le maximum avec des graphes ou images, même prise sur internet avec leurs références respectives.
# Chaitre 3
- Utilise principalement la réference_1 combiné avec d'autres ressouces de ton choix, pour présenter les principes du MLOPS.
- chaque principe doit être présenté dans un paragraphe avec un graphe, une explication et un exemple.
- presente aussi les outils utilisés pour illusté chaque principe, favorise les outils opensource et les solutions des cloud providers.
# Chapitre 4
- Fournis les sources nécessaires (par exemple dokerfile, docker compose, manifest.yaml) pour une installation rapide des outils_opensource sur un envirenement local.
- utilise une base donnée local, qui source des données pour la démo.
- utilise des conteneurs docker pour faire touner l'exemple.
- tous les sources seront poussée sur github dans le repo https://github.com/SoufieneCHR/presentation_mlops
- Proposer une arboresence du repogithub pour contenir deux sénarios :
  - **local** : contenant les sources nécessaires pour l'installation des outils_opensource en se basant sur des image docker et docker swarm.
  - **cluster_k8s_** : contenant les sources nécessaires pour un sénarion basé sur kubeflow et kubernetes.
- Applique l'arboresence proposée et pousser les ressources sur le repo_github.
- Ulluster le maximum avec des graphes ou images, même prise sur internet avec leurs références respectives.

# Format de réponse attendu
Réponds toujours en md structuré, sans texte libre autour.
