# git-hack
Algunos comandos de git que son pocas veces usados

# Creando un branch desde un commit muy antiguo


git reset --keep HEAD~{numero de orden del commit}
git checkout -t -b {nombre del nuevo branch}
git cherry-pick ..HEAD@{2}
