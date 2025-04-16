# 1c-gruppo

# Configura l'upstream (se non esiste già)
git remote set-url upstream https://github.com/stefanolazzari/1c-gruppo.git 2>/dev/null || git remote add upstream https://github.com/stefanolazzari/1c-gruppo.git

# Recupera gli aggiornamenti dal repository originale
 git fetch upstream

# Passa al branch principale
git checkout main

# Unisce gli aggiornamenti dell'insegnante
git merge upstream/main

# Invia le modifiche al proprio fork
git push origin main




