# L'échelle d'adoption et la scripte — ce qu'un modèle de maturité d'ingénierie ne voit pas du travail créatif

*par Ismaël Joffroy Chandoutis — juillet 2026*

---

Le 16 juillet 2026, Boris Cherny, le créateur de Claude Code, a publié un tableau intitulé [« Steps of AI Adoption »](https://claude.ai/code/artifact/bfdfaef9-bc62-4dfe-ba9e-c58a26c9accf). Cinq étapes. À l'étape 0, votre organisation vous bloque. À l'étape 1, vous travaillez en binôme avec un agent et vous relisez chaque ligne. À l'étape 2, vous en orchestrez une dizaine. À l'étape 3, une centaine, et les agents commencent à se lancer entre eux. À l'étape 4, vous pilotez par intention, mille agents plus bas, et vous ne surveillez plus que les exceptions.

Je l'ai lu comme je lis la plupart des documents d'ingénierie : depuis l'extérieur, avec une méfiance de traducteur. Et ce qui m'a arrêté tient dans une seule condition, glissée dans le passage de l'étape 1 à l'étape 2 : *une boucle d'auto-vérification en laquelle vous avez confiance*. Tests, build, lint, vérifications de bout en bout. L'ingénieur cesse de tout relire parce qu'une machine lit avant lui. Tous les barreaux supérieurs reposent sur cette boucle. Multipliez les agents autant que vous voudrez : ce qui monte l'échelle, en réalité, c'est la confiance.

Mon travail n'a pas de suite de tests. Un raccord tient ou ne tient pas. Une scène respire ou ne respire pas. Il n'existe aucune commande à lancer contre un bout-à-bout qui retournerait *conforme*. Quand le travail est un film, la vérification est un jugement, et ce jugement est le travail.

---

## Le cinéma avait déjà résolu ça, avec des personnes

Voilà ce que le tableau ne peut pas voir, et que les plateaux savaient bien avant l'informatique : le cinéma est plein de boucles de vérification. Elles sont simplement faites de personnes.

La scripte regarde chaque prise contre toutes les autres, pour que le réalisateur puisse détourner les yeux des raccords et regarder les acteurs. Le rapport laboratoire revenait pendant la nuit, à l'époque photochimique : rayures, exposition, un poil dans la fenêtre, découverts avant que le décor soit démonté. Les rushes du soir existaient pour que le travail de la veille soit vérifié tant qu'on pouvait encore retourner la scène. L'assistant monteur pointait et vérifiait chaque mètre de pellicule avant que le monteur y touche.

Rien de tout cela n'était de la bureaucratie. C'était de la confiance, construite. Une équipe de tournage est une structure qui permet à une personne de tenir une vision pendant que des dizaines de boucles vérifient l'exécution. Le réalisateur qui ne vérifie plus la fenêtre de la caméra s'appuie sur un siècle de vérification accumulée, incarnée dans des métiers.

En travaillant seul avec des agents, j'ai perdu cet héritage. La pratique solo avec l'IA, c'est l'équipe en moins, et les boucles sont parties avec elle. Les modèles écrivent, génèrent, assemblent, répondent, à une vitesse qu'aucun assistant monteur n'a jamais approchée. Et derrière eux : rien. Pas de scripte, pas de rapport labo, personne qui a regardé la prise. Un agent vous affirme, avec une confiance parfaite, que le travail est fait. Parfois, le fichier qu'il décrit n'existe pas.

---

## Reconstruire la scripte, en agents

Le vrai travail de cette échelle, pour une pratique créative, s'est donc révélé être l'inverse de ce que j'attendais. Je croyais que c'était l'orchestration : plus de sessions, plus de parallèle, plus d'automatisation. L'orchestration est la partie facile, et le tableau le dit aussi, à sa manière. Le travail, c'est de reconstruire la scripte.

Concrètement, sur des mois, ça a ressemblé à ceci. Un évaluateur calibré sur une grille de notation écrite, avec des seuils sous lesquels le travail est refusé, pour qu'une scène faible soit rejetée avant que j'y passe une soirée. Un agent dont le seul pouvoir est un veto, qui vérifie chaque génération contre les invariants de ma pratique visuelle, parce qu'un agent qui ne peut que dire non est ce que j'ai trouvé de plus proche d'un rapport laboratoire. Des panels de lecteurs adverses, délibérément hostiles, appliqués à tout ce qui sort de l'atelier, en partant du principe qu'un lecteur bienveillant ne vérifie rien. Des brouillons critiques triangulés entre trois modèles différents, parce que trois machines statistiques hallucinent rarement dans la même direction. Et une règle dure, née d'un échec : un agent qui affirme avoir produit quelque chose doit montrer l'objet lui-même, jamais sa description.

Chacun de ces dispositifs existe parce que quelque chose a mal tourné sans lui. Chacun est un métier de l'ancienne équipe, reconstruit en boucle. Ils sont artisanaux et imparfaits, révisés après chaque échec, comme la pratique des raccords elle-même s'est affinée, prise ratée par prise ratée, pendant un siècle.

---

## Le paradoxe que l'échelle désigne

L'étape 4 décrit quelqu'un qui pilote par intention et ne surveille que les exceptions. Les cinéastes reconnaissent cette figure immédiatement : c'est une fiche de poste de réalisateur. Un réalisateur n'a jamais poussé la dolly. Déléguer l'exécution en tenant une vision, c'est le geste le plus ancien de ce métier.

Mais il y a ici deux bouts à tenir, et je veux tenir les deux. La délégation sans vérification est un abandon ; et la vérification sans délégation, c'est l'ingénieur de l'étape 1 qui ne détourne jamais les yeux, ou le réalisateur qui vérifie lui-même la fenêtre de caméra et finit un film par décennie. Tout l'art, sur un plateau comme dans un terminal, vit entre ces deux-là, et aucun barreau d'aucune échelle ne tranche à votre place. Dans ma pratique, les agents se sont multipliés d'abord ; la confiance est encore en chantier, et honnêtement, c'est elle qui doit être en retard. Une confiance qui arrive avant que la boucle l'ait méritée porte un nom dans les deux métiers : la négligence.

Alors, où j'en suis, sur les cinq étapes ? Quelque part entre 2 et 3, selon les critères du tableau lui-même, avec des routines qui se réveillent avant moi et des agents qui lancent des agents. Et je relis encore presque tout ce qui compte, comme un débutant de l'étape 1. J'ai longtemps pris cet écart pour un retard d'outillage. Je pense maintenant que cet écart est l'endroit du travail : une soirée passée à écrire une grille de notation pour des scènes, c'est une soirée passée à apprendre à une machine ce que je vérifie quand je vérifie, et cette grille, j'aurais été incapable de l'écrire avant d'essayer. L'ancienne équipe a eu un siècle pour affiner la scripte. J'essaie de le faire en cours de production, seul, pour des métiers qui n'ont jamais existé. Ça rate régulièrement. Au moins, sur ce point, je suis fidèle à l'histoire du cinéma.

---

*Ismaël Joffroy Chandoutis est artiste et cinéaste, basé à Paris, travaillant à l'intersection du cinéma, de l'art contemporain et de l'intelligence artificielle.*
