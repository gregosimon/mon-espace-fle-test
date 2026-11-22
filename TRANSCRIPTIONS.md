# Transcriptions DELF B1 — site test

Publication des trois transcriptions autorisée par le propriétaire le 22 novembre 2026. Il a explicitement choisi un affichage pédagogique après correction et accepté que les textes soient publics. Le masquage côté navigateur n'est pas un contrôle d'accès.

Source : PDF utilisateur delf-b1-tp-surveillant-coll-exemple1.pdf (France Éducation international). Dialogues extraits sans reformulation, espaces et retours à la ligne harmonisés ; consignes de surveillance exclues.

Les trois exercices proviennent de la branche feature/add-b1-listening-exercise-2. Questions, barèmes (7/9/9), références et fichiers audio conservés. Migration en lecture des anciens scores B1-co vers b1-co-1, sans suppression.

Vérifications : questions incomplètes bloquées ; score maximal et nul ; texte exact pour chaque exercice ; ouverture/fermeture ; remise à zéro et modification des réponses ; changement d'exercice ; affichage à 390 px sans débordement ; aucune erreur JavaScript. Authentification simulée dans les tests, aucune donnée Supabase modifiée.

## Anomalies audio préexistantes

- Les deux fichiers MP3 présents durent 49,15275 secondes, alors que les durées annoncées sont environ 4 min 41 et 5 min 36.
- Le fichier assets/audio/delf-b1-tp-coll-exemple1-exercice3.mp3 manque dans la branche source.
- Le serveur officiel a retourné une page HTML de contrôle à la place du MP3 demandé ; aucun faux MP3 HTML n'a été publié.
- L'interface signale les fichiers indisponibles ou anormalement courts. Les trois enregistrements complets restent à fournir/remettre en place.

Seul gregosimon/mon-espace-fle-test est modifié. Aucun changement au site principal ni à sa base Supabase.
