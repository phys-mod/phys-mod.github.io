Outils numériques
=================

Cette année nous utiliserons plusieurs outils numériques:

  - les calepins de Jupyter
  - Moodle
  - Trello
  - Spyder

Jupyter Notebooks
-----------------
`Jupyter <https://jupyter.org/>`_ permet de réaliser des calepins ou *notebooks*, c’est-à-dire des
programmes contenant à la fois du texte et du code informatique. Ces
calepins sont utilisés en science des données pour explorer et analyser des
données. Vous pouvez télécharger les calepins de l’UE en une fois
avec le lien suivant:

:download:`Télécharger tous les calepins de l'UE (fichier zip) <../notebooks/calepins-etu.zip>`

:download:`Télécharger tous les calepins de l'UE (fichier tar) <../notebooks/calepins-etu.tar>`

Pour travailler sur les calepins, vous avez de nombreuses solutions. Nous vous conseillons d'utiliser JupyterHub. L'avantage de JupyterHub est que vous n'avez rien à installer, vous avez accès à vos calepins personnels depuis n'importe quel navigateur de n'importe quel ordinateur qui dispose d'un accès à internet, vous utilisez les serveurs de la fac.

Pour cela il faut:

  1. Télécharger le fichier TAR contenant tous les calepins pour l'année
  2. Ouvrir JupyterHub avec le lien disponible sur la page d'accueil Moodle de l'UE (attention il faut être authentifié à Moodle pour que cela fonctionne)
  3. Cliquer sur le bouton "Start my server" si celui-ci n'est pas déjà démarré
  4. Cliquer sur le bouton "Upload", chercher dans l'arborescence et sélectionner le fichier TAR téléchargé en 1, puis cliquer sur "téléverser"
  5. Cliquer sur le bouton "New", puis sur "Terminal"
  6. Ecrire dans le terminal la commande "tar -xvf nom-du-fichier.tar"
  7. Fermer la fenêtre du terminal
  8. et voilà vous pouvez cliquer sur n'importe quel calepin (extension ipynb) et l'ouvrir dans une instance de Jupyter Notebook
  9. Attention à ne pas ouvrir plusieurs calepin en même temps. Lorsque vous fermez un notebook, cliquer sur "Close and halt" dans le menu déroulant "Files" en haut. Si vous ne le faites pas, le calepin reste en mémoire et utilise les ressources des serveurs et peut le saturer. Un calepin est automatiquement "déconnecté" au bout d'une heure sans action. Vous pouvez voir vos calepins actifs avec le bouton "Running" dans la page d'accueil de JupyterHub.

D'autres solutions existent pour faire tourner vos calepins:

  - en local à la fac sur une session Linux ou Windows. Attention vos calepins seront en local. Cependant la session Windows est accessible à distance: `Accéder à l’environnement virtuel Capsule <https://lutes.upmc.fr/bdl-ext.php>`_
  - en local sur votre ordinateur personnel: il faut alors installer tous les programmes nécessaires à l'UE, ce qui peut facilement être fait avec la distribution Anaconda. Cependant nous vous conseillons cette solution seulement si vous êtes un utilisateur alerté et que vous avez déjà l'habitude de coder.

Moodle
------
Nous utiliserons les activités Moodle suivantes:

  - **Quiz**: les quiz vous permettent de vous auto-évaluer.
  - **Devoirs** : vous déposerez les comptes-rendus des mini-projets. L'enseignant·e vous fera alors un retour et une évaluation basée sur une grille d'évaluation.
  - **Forum** : vous pouvez utiliser le forum si vous avez un problème avec le contenu ou les outils du cours. Un·e enseignant·e ou un·e camarade pourra ensuite vous répondre.
  - **Évaluations** : vous pourrez consulter l'ensemble de vos évaluations sur Moodle.

.. _`créer mon tableau de gestion de mon apprentissage`:

Trello
------
Nous utiliserons Trello pour suivre votre progression dans le cours. Afin de créer un compte et créer votre propre
tableau de gestion de votre apprentissage :

  1. Créer un compte Trello sur https://trello.com/home ;
  2. Envoyer un message à votre enseignant·e avec l'adresse email utilisée pour vous inscrire ;
  3. Appuyer sur le lien dans le mail d'invitation envoyé par votre enseignant·e pour rejoindre l'équipe ;
  4. Aller sur le tableau "Modélisation Numérique en Physique" ;
  5. Appuyer sur "Menu", "... Plus", "Copier le tableau" ;
  6. Mettre son nom en Titre du tableau, puis appuyer sur "Créer".

Spyder
------
Spyder est un outil complémentaire à Jupyter Notebooks. 
Il est disponible sur les postes à l'Atrium et fourni avec la distribution Anaconda de python. 
:download:`Plus d'informations dans ce document PDF <spyderIntro_2021-2022.pdf>`.