# 1erProjetWeb
## GIT

#### Commandes "Générales"

- Tu codes sur ta branche (karim)
- git status (pour voir les fichiers modifiés)
- git branch (pour voir la liste des branches)
- git checkout nomDeLaBranche (pour changer de branche ou en créer une nouvelle)


#### Commandes pour Push ton code sur le répo Github

- git add -A (ou git add nomDuFichier pour ajouter les fichiers que tu veux commit)
- git commit -m "description du commit" (pour créer un commit avec les fichiers que tu as add précèdemment)
- git push origin nomDeLaBranche (pour push tes changements sur github, ex: git push origin karim)

<br>

- Une fois que tu as push, sur github tu crées une pull request avec le nouveau commit
- Ensuite il faut le merge sur la branche master une fois que les conflits sont résolus si jamais il y en a


#### Commandes pour Pull le code que j'ai pushé

- git fetch --all (pour récupérer les changements qui ont été merge dans la branch master, pas besoin de le faire si c'est toi qui a commit car tu as déjà les changements sur ton code local)
- git rebase nomDeLaBranche (pour "rebase" ton project en local avec les changements qui sont sur la branche master que tu as fetch, exemple: git rebase origin/master une fois que tu as fetch les changements que j'ai push & merge sur github)


<br>

- Si tu veux annuler les changements fait sur un fichiers tu peux faire ctrl + z mais tu peux aussi git add leFichier et ensuite git stash (Au cas ou tu peux récupérer les fichiers "stash" grâce à l'extension Git lens)
