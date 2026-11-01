# isc.github.io

Ce site renvoie les anciennes adresses des sites déménagés vers les nouvelles. GitHub
ne redirige pas l'adresse d'un site Pages quand son dépôt change de nom, et les applis
déjà installées pointent encore sur l'ancienne.

- `404.html` : `isc.github.io/reading-practice/…` → `isc.github.io/marzouzoute/…`
- `reading-practice/index.html` : l'adresse de départ des applis installées. Elle lie le
  manifeste de la nouvelle adresse, qui garde l'`id` de l'ancienne : Chrome sur Android
  détecte ainsi la mise à jour, à condition que la page reste ouverte quelques secondes.
  Sur iPad, elle explique comment réinstaller.
