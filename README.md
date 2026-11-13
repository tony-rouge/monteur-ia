# Le Monteur IA de Tony

Claude monte vos vidéos à votre place. Vous n'avez rien à coder.

Vous filmez. Claude coupe les blancs et les ratés, nettoie le son, ajoute les sous-titres et vous livre une vidéo prête à poster. Vous donnez vos retours, il les note dans son cahier et les applique aux vidéos suivantes.

C'est le monteur que j'utilise pour mes propres vidéos YouTube et mes shorts. Toutes mes règles de montage sont dedans, déjà réglées.

**Le tuto complet, pas à pas :** [ma chaîne YouTube](https://www.youtube.com/@tonyrougeofficiel).

## Ce qu'il vous faut

- Un Mac.
- L'application Claude, avec un abonnement payant. L'onglet **Code**, c'est Claude Code.
- Deux comptes : ElevenLabs (il écrit vos mots, quelques centimes par vidéo) et Auphonic (il nettoie le son, gratuit quelques heures par mois). Claude vous dit où cliquer.

## Étape 1 : télécharger le monteur

[**Télécharger le monteur (fichier ZIP)**](https://github.com/tony-rouge/monteur-ia/archive/refs/heads/main.zip)

Double-cliquez sur le ZIP : un dossier `monteur-ia-main` apparaît. Rangez-le dans « Vidéos ».

## Étape 2 : l'ouvrir dans Claude

Dans l'application Claude, onglet **Code**, choisissez le dossier `monteur-ia-main`.

## Étape 3 : installer (une seule fois)

Collez ce message, puis suivez Claude :

> Installe mon monteur IA.

Claude installe les outils un par un et vous explique chaque étape. Vous cliquez sur « Autoriser » quand il le demande.

Claude vous demandera deux clés. Voici les liens directs :
- **ElevenLabs** : créez un compte, puis [https://elevenlabs.io/app/developers/api-keys](https://elevenlabs.io/app/developers/api-keys)
- **Auphonic** : créez un compte, puis [https://auphonic.com/accounts/settings/#api-key](https://auphonic.com/accounts/settings/#api-key) (section « API Key »)

Vos clés secrètes vont dans un fichier sur votre Mac. Ne les collez jamais dans la conversation.

## Étape 4 : monter une vidéo

Glissez votre vidéo brute dans le dossier `rushes`. Puis collez :

> Monte cette vidéo. Commence par les 30 premières secondes.

Claude vous montre d'abord une image fixe, puis 30 secondes. Vous validez, il monte le reste.

Le résultat arrive dans le dossier `livrables`. Si vous avez Final Cut, il vous donne aussi un fichier à ouvrir d'un double-clic pour retoucher.

## Étape 5 : vos retours

> Voici mes retours. Corrige, puis retiens-les.
> (par exemple : « 0:12 coupe trop tôt. Sous-titres plus petits. »)

Chaque retour devient une règle dans `cahier-du-monteur.md`. Claude la relit avant chaque montage.

## Ce qu'il y a dedans

| Fichier | À quoi il sert |
| --- | --- |
| `CLAUDE.md` | Les consignes de Claude : installer, monter, retenir vos retours. |
| `cahier-du-monteur.md` | Mes règles de montage (son, coupes, cadrage, sous-titres). Les vôtres s'ajoutent en bas. |
| `rushes/` | Vous y glissez vos vidéos brutes. |
| `livrables/` | Claude y dépose vos vidéos montées. |

## Combien ça coûte

- L'abonnement Claude : à partir de 17 $ par mois (Pro). Pour des vidéos longues chaque semaine, prenez plus grand.
- ElevenLabs : environ 0,22 $ par heure de vidéo.
- Auphonic : quelques heures gratuites par mois.
- FFmpeg et les autres outils : gratuits.

## Pour aller plus loin

Une fois vos premières vidéos validées, demandez à Claude :
- des **animations** (HyperFrames, gratuit),
- des **bruitages** discrets (Earshot, gratuit),
- un **monteur de nuit** : vos vidéos se montent sur un ordinateur en ligne pendant que vous dormez, et votre Mac reste froid.

## Vous bloquez ?

Dites à Claude : « Je bloque, explique-moi simplement. »

Toujours bloqué ? Posez votre question dans la communauté gratuite Les Experts Libres : [skool.com/libre](https://www.skool.com/libre).

## L'auteur

Tony Rougé, coach business pour coachs, formateurs et experts.

- YouTube : [@tonyrougeofficiel](https://www.youtube.com/@tonyrougeofficiel)
- Communauté gratuite « Les Experts Libres » : [skool.com/libre](https://www.skool.com/libre)
- Site : [tonyrouge.com](https://tonyrouge.com)

## Licence

MIT © 2026 Tony Rougé. Vous pouvez l'utiliser, le modifier et le partager librement, en gardant cette mention. Voir [LICENSE](LICENSE).
