Branches :

main → branche stable du projet.

amel → ta branche, où tu as créé tp.md et fait le revert.

faty → la branche de ton binôme, avec ses propres commits.

eleve3 → simulée par faty et moi (modifications sur README).

Commits importants :
création du fichier tp.md par Amel (feat/amel: creation du fichier tp.md).
Création du fichier tp.md par Faty (created tp.md).
Merge de la branche de Faty dans celle d’Amel (merge avec la branch eleve3).
Revert d’Amel (Revert "created tp.md") pour annuler le commit de Faty.

Pour la pull request impossible de demander des changement du côté de faty

Historique graphique :
Les merges apparaissent avec des branches divergentes qui se rejoignent.
Le revert a ajouté un commit qui annule un précédent commit sans supprimer l’historique.

- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
  | |
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
  | |
  | | merge avec la brach eleve3
  | |
  | \* commit 001ffcff1c920207cf0e1be98e823068805a79ae (origin/eleve3)
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:33:35 2025 +0100
  | |
  | | made some changes on the README
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
  | |
  | | merge avec la brach eleve3
  | |
  | _ commit 001ffcff1c920207cf0e1be98e823068805a79ae (origin/eleve3)
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:33:35 2025 +0100
  | |
  | | made some changes on the README
  | |
  | _ commit ea7cf74e378bd5894b7a0cad77be466868b5005b
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
  | |
  | | merge avec la brach eleve3
  | |
  | _ commit 001ffcff1c920207cf0e1be98e823068805a79ae (origin/eleve3)
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:33:35 2025 +0100
  | |
  | | made some changes on the README
  | |
  | _ commit ea7cf74e378bd5894b7a0cad77be466868b5005b
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:26:22 2025 +0100
  | |
  | | created tp.md
  | |
- | commit 4236af609780de1d74038393b50770d31669448a
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
  | |
  | | merge avec la brach eleve3
  | |
  | _ commit 001ffcff1c920207cf0e1be98e823068805a79ae (origin/eleve3)
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:33:35 2025 +0100
  | |
  | | made some changes on the README
  | |
  | _ commit ea7cf74e378bd5894b7a0cad77be466868b5005b
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:26:22 2025 +0100
  | |
  | | created tp.md
  | |
- | commit 4236af609780de1d74038393b50770d31669448a
  |/ Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 11:26:37 2025 +0100
  |
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
  | |
  | | merge avec la brach eleve3
  | |
  | _ commit 001ffcff1c920207cf0e1be98e823068805a79ae (origin/eleve3)
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:33:35 2025 +0100
  | |
  | | made some changes on the README
  | |
  | _ commit ea7cf74e378bd5894b7a0cad77be466868b5005b
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:26:22 2025 +0100
  | |
  | | created tp.md
  | |
- | commit 4236af609780de1d74038393b50770d31669448a
  |/ Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 11:26:37 2025 +0100
  |
  | feat/amel: creation du fichier tp.md
  |
- commit 0a73267cd34828c5dc7a977cabcd3a7af45ace01 (origin/master, origin/branch/faty, origin/HEAD, master)
  | Author: Sarah Schlegel <sschlegel@myges.fr>
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
  | |
  | | merge avec la brach eleve3
  | |
  | _ commit 001ffcff1c920207cf0e1be98e823068805a79ae (origin/eleve3)
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:33:35 2025 +0100
  | |
  | | made some changes on the README
  | |
  | _ commit ea7cf74e378bd5894b7a0cad77be466868b5005b
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:26:22 2025 +0100
  | |
  | | created tp.md
  | |
- | commit 4236af609780de1d74038393b50770d31669448a
  |/ Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 11:26:37 2025 +0100
  |
  | feat/amel: creation du fichier tp.md
  |
- commit 0a73267cd34828c5dc7a977cabcd3a7af45ace01 (origin/master, origin/branch/faty, origin/HEAD, master)
  | Author: Sarah Schlegel <sschlegel@myges.fr>
  | Date: Wed Nov 12 22:01:27 2025 +0100
  |
  | Instructions TP Final
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
  | |
  | | merge avec la brach eleve3
  | |
  | _ commit 001ffcff1c920207cf0e1be98e823068805a79ae (origin/eleve3)
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:33:35 2025 +0100
  | |
  | | made some changes on the README
  | |
  | _ commit ea7cf74e378bd5894b7a0cad77be466868b5005b
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:26:22 2025 +0100
  | |
  | | created tp.md
  | |
- | commit 4236af609780de1d74038393b50770d31669448a
  |/ Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 11:26:37 2025 +0100
  |
  | feat/amel: creation du fichier tp.md
  |
- commit 0a73267cd34828c5dc7a977cabcd3a7af45ace01 (origin/master, origin/branch/faty, origin/HEAD, master)
  | Author: Sarah Schlegel <sschlegel@myges.fr>
  | Date: Wed Nov 12 22:01:27 2025 +0100
  |
  | Instructions TP Final
  |
  :...skipping...
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
  | |
  | | merge avec la brach eleve3
  | |
  | _ commit 001ffcff1c920207cf0e1be98e823068805a79ae (origin/eleve3)
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:33:35 2025 +0100
  | |
  | | made some changes on the README
  | |
  | _ commit ea7cf74e378bd5894b7a0cad77be466868b5005b
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:26:22 2025 +0100
  | |
  | | created tp.md
  | |
- | commit 4236af609780de1d74038393b50770d31669448a
  |/ Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 11:26:37 2025 +0100
  |
  | feat/amel: creation du fichier tp.md
  |
- commit 0a73267cd34828c5dc7a977cabcd3a7af45ace01 (origin/master, origin/branch/faty, origin/HEAD, master)
  | Author: Sarah Schlegel <sschlegel@myges.fr>
  | Date: Wed Nov 12 22:01:27 2025 +0100
  |
  | Instructions TP Final
  |
- commit 767f380a5bb96234debe23e6eb9cc6e3ccda2e43
  :...skipping...
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
  | |
  | | merge avec la brach eleve3
  | |
  | _ commit 001ffcff1c920207cf0e1be98e823068805a79ae (origin/eleve3)
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:33:35 2025 +0100
  | |
  | | made some changes on the README
  | |
  | _ commit ea7cf74e378bd5894b7a0cad77be466868b5005b
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:26:22 2025 +0100
  | |
  | | created tp.md
  | |
- | commit 4236af609780de1d74038393b50770d31669448a
  |/ Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 11:26:37 2025 +0100
  |
  | feat/amel: creation du fichier tp.md
  |
- commit 0a73267cd34828c5dc7a977cabcd3a7af45ace01 (origin/master, origin/branch/faty, origin/HEAD, master)
  | Author: Sarah Schlegel <sschlegel@myges.fr>
  | Date: Wed Nov 12 22:01:27 2025 +0100
  |
  | Instructions TP Final
  |
- commit 767f380a5bb96234debe23e6eb9cc6e3ccda2e43
  |\ Merge: a8be53b e2dd662
  :...skipping...
- commit 44ac428325fc63ceb768a075fd1e15707fd6c522 (HEAD -> amel, origin/amel)
  | Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 12:09:49 2025 +0100
  |
  | Revert " created tp.md"
  |
  | This reverts commit ea7cf74e378bd5894b7a0cad77be466868b5005b.
  |
- commit f86a451628677e582136f5f3555427be5babd116
  |\ Merge: 4236af6 001ffcf
  | | Author: amelbdj <amelboudjenanee@icloud.com>
  | | Date: Fri Dec 19 11:53:55 2025 +0100
  | |
  | | merge avec la brach eleve3
  | |
  | _ commit 001ffcff1c920207cf0e1be98e823068805a79ae (origin/eleve3)
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:33:35 2025 +0100
  | |
  | | made some changes on the README
  | |
  | _ commit ea7cf74e378bd5894b7a0cad77be466868b5005b
  | | Author: fatymut <158191632+fatymut@users.noreply.github.com>
  | | Date: Fri Dec 19 11:26:22 2025 +0100
  | |
  | | created tp.md
  | |
- | commit 4236af609780de1d74038393b50770d31669448a
  |/ Author: amelbdj <amelboudjenanee@icloud.com>
  | Date: Fri Dec 19 11:26:37 2025 +0100
  |
  | feat/amel: creation du fichier tp.md
  |
- commit 0a73267cd34828c5dc7a977cabcd3a7af45ace01 (origin/master, origin/branch/faty, origin/HEAD, master)
  | Author: Sarah Schlegel <sschlegel@myges.fr>
  | Date: Wed Nov 12 22:01:27 2025 +0100
  |
  | Instructions TP Final
  |
- commit 767f380a5bb96234debe23e6eb9cc6e3ccda2e43
  |\ Merge: a8be53b e2dd662
  | | Author: Sarah Schlegel <sschlegel@myges.fr>
  | | Date: Wed May 25 18:39:15 2022 +0200
  | |
  | | Merge pull request #1 from SarahSch19/develop

2.  git fetch → récupère les commits du remote sans les intégrer.
    Exemple : si on veut vérifier les mises à jour sur main avant de merger, pour éviter les conflits.
    git pull → récupère les commits et les merge automatiquement dans ta branche locale.
    Exemple : je veux mettre ma branche à jour directement avec les derniers changements de main.

        3 . git reset → annule des commits dans ta branche locale.
            situation risquée : les commits annulés disparaissent de l’historique.
        git revert → crée un nouveau commit qui annule les changements d’un commit précédent, sans modifier l’historique.
        situation risquée : l’historique peut devenir difficile à comprendre avec beaucoup de reverts.
