# Kit pour YouTube

Un assistant en français pour préparer vidéos longues et Shorts.

## Ce que fait le pack
- **Écrire** : `yt-script`, `yt-package` (titre et miniature), `yt-seo`, `yt-chapters`
- **Monter** : `yt-edit` liste les coupes à partir d'une transcription
- **Recycler** : `yt-shorts`, `viral-youtube-shorts`
- **Progresser** : `yt-audit`, `yt-retention`, `yt-plan`, `yt-comment`, `yt-viral`

## Installation dans Claude Code
Ces deux commandes fonctionnent une fois le dépôt en ligne :

```
/plugin marketplace add Supra-skills-mdd7/kit-pour-youtube
/plugin install kit-pour-youtube@kit-pour-youtube-depot
```

Ailleurs : copiez le dossier d'un skill dans le dossier de skills de votre assistant, avec son fichier `LICENSE`.
Lisez les fichiers avant de les installer.

## Bien l'utiliser
1. Commencez par `yt-audit`.
2. Copiez `templates/voice.md` vers `~/.claude/youtube/voice.md` et remplissez-le.
3. Pour une vidéo : `yt-viral`, `yt-script`, `yt-package`, `yt-seo`.
4. Donnez la transcription à `yt-edit`.
5. Après publication : donnez votre export de rétention à `yt-retention`.

## Limites et règles
- Ce kit prépare du contenu : il ne filme pas, ne publie pas et n'envoie aucun message.
- Aucune clé, aucun mot de passe, aucune collecte automatique.
- Aucun résultat ni nombre de vues n'est garanti.
- Signalez publicité, partenariat et contenu IA quand c'est exigé, et revérifiez les règles de la plateforme.
- Certains skills repris sont rédigés en anglais ; l'assistant peut répondre en français.
- Les scripts demandent Python 3. `video-script` a un script facultatif qui demande aussi Pillow et NumPy.
- Ce kit ne télécharge aucune vidéo.

## Licences
Le contenu original est sous licence MIT (`LICENSE`). Les fichiers repris gardent leur licence et leurs auteurs : voir `CREDITS.md`, `LICENSES/` et `MODIFICATIONS.md`.

Projet non officiel : aucun lien avec les plateformes, moteurs ou auteurs cités, ni approbation de leur part.
Les marques appartiennent à leurs propriétaires. Rédigé avec l'aide d'une IA. Voir aussi `SECURITY.md`.
