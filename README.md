# Les prompts exacts : laisser Claude chercher ton job à ta place

Le principe : tu donnes ton CV à Claude, il trie les offres, réécrit ton CV pour chacune, et toi tu n'as plus qu'à envoyer.
Ordre à suivre : 1 → 2 → 3 → 4 → 5. Remplace ce qui est entre [crochets].

> Claude prépare, **tu relis chaque mot et c'est toi qui envoies**. Ne laisse jamais une IA postuler seule en ton nom.

---

## 1. Lui donner ton CV (et ce que tu cherches)

Colle ton CV (ou joins le PDF), puis :

```
Voici mon CV. Tu es mon coach carrière.
Lis-le et résume en 10 lignes : mon profil, mes 5 forces les plus vendeuses, mes réalisations chiffrées, et ce qui manque ou est faible.

Ce que je cherche :
- Poste : [intitulé visé]
- Lieu / télétravail : [ville, remote, hybride]
- Salaire minimum : [montant]
- Ce que je refuse : [secteurs, types de contrat, déplacements...]

Pose-moi toutes les questions qui te manquent avant de continuer.
```

## 2. Trouver le top 20 des postes qui te correspondent

```
À partir de mon CV et de mes critères, donne-moi :
1. Les 10 intitulés de poste les plus proches de mon profil (y compris ceux auxquels je n'aurais pas pensé).
2. Les mots-clés exacts que les recruteurs et les robots de tri (ATS) cherchent pour ces postes.
3. Les 20 types d'entreprises ou de secteurs qui recrutent ce profil, classés par chances d'embauche.

Pour chaque ligne, une phrase : pourquoi ça colle avec mon CV.
```

Ensuite, colle les offres trouvées sur LinkedIn, Indeed ou Welcome to the Jungle (texte complet de l'annonce) pour passer à l'étape suivante.

## 3. Noter chaque offre et garder les meilleures

```
Voici une offre d'emploi :
[colle l'annonce]

Compare-la à mon CV et note-la sur 5 :
- Adéquation compétences : x/5
- Adéquation expérience : x/5
- Adéquation avec mes critères (lieu, salaire, ce que je refuse) : x/5
- Note globale : x/5

Donne-moi : les 3 points forts de ma candidature, les 3 points faibles, et un verdict clair : POSTULER ou PASSER.
Sois honnête : si je n'ai pas 60 % des exigences, dis-le.
```

Fais-le pour toutes les offres, puis :

```
Voici les notes de mes [nombre] offres. Classe-les de la meilleure à la moins bonne
et dis-moi sur lesquelles je dois concentrer mon énergie cette semaine (maximum 10).
```

## 4. Réécrire ton CV pour chaque offre

```
Voici mon CV et l'offre visée :
[colle l'annonce]

Réécris mon CV pour cette offre :
- Reprends les mots-clés exacts de l'annonce (sans mentir).
- Remonte en premier mes expériences les plus pertinentes.
- Reformule chaque réalisation avec un chiffre ou un résultat.
- 1 page maximum.

Règle absolue : n'invente aucune expérience, aucun diplôme, aucun chiffre.
Si une info manque, pose-moi la question au lieu de l'inventer.
```

## 5. Lettre de motivation et réponses aux questions

```
Écris une lettre de motivation pour cette offre à partir de mon CV :
[colle l'annonce]

- 150 à 200 mots, ton direct, pas de formules creuses ("passionné", "dynamique").
- Une accroche liée à l'entreprise (ce qu'elle fait, pas des banalités).
- Deux exemples concrets tirés de mon CV qui répondent à leurs besoins.
- Une phrase de fin qui propose un échange, pas un "dans l'attente de votre réponse".
```

Pour les questions du formulaire de candidature :

```
Voici les questions du formulaire de candidature :
[colle les questions]
Réponds à chacune en 3-4 lignes max, à partir de mon CV et de l'offre. Pas de réponse générique.
```

## Bonus : préparer l'entretien

```
Voici l'offre et mon CV. Joue le recruteur.
Pose-moi les 10 questions les plus probables, une par une.
Après chaque réponse, note-la sur 10, dis-moi ce qui est faible et donne une meilleure version.
Termine par les 5 questions que je devrais poser, moi, à la fin de l'entretien.
```

---

## Aller plus loin : le système complet

Celui qui a signé après 68 candidatures a tout automatisé avec **Career-Ops** (gratuit, open source) :
https://github.com/career-ops-hq/career-ops

Il tourne sur ton ordinateur dans Claude Code : il note chaque offre sur 5 par rapport à ton CV, adapte ton CV et prépare les réponses du formulaire. Il n'envoie jamais rien à ta place.

---

Fait par [Aptibots](https://aptibots.com) · Des outils IA sur mesure et des automatisations pour les entreprises.
