# Transparence, vie privée & éthique

Tout comme l'écologie, les questions de transparence et de respect de la vie privée concernant Google ont pendant des années fait l'objet de débats controversés. C'est un sujet sur lequel Google a dû faire des efforts afin de rassurer la communauté. Des efforts toujours considérés comme insuffisants par la communauté.

## Application du réglement

> Chez YouTube, nous nous efforçons de préserver une communauté sûre et dynamique. Le règlement de la communauté définit les règles de conduite à suivre sur YouTube. Par exemple, nous n'autorisons pas la pornographie, l'incitation à la violence ou à la haine, ni le harcèlement.

Peut-on lire sur le rapport d'[application du règlement de la communauté YouTube][3]. En effet depuis 2017, YouTube partage ses statistiques relatives à la suppression de vidéos, chaînes, ou encore commentaires.

![](../assets/screenshot_46.png)

> Nous nous appuyons à la fois sur les individus et sur la technologie pour signaler le contenu inapproprié et faire respecter ces règles. Les signalements peuvent provenir de nos systèmes de détection automatique, de membres du programme Trusted Flagger (ONG, autorités administratives et individus) ou d'utilisateurs au sein de la vaste communauté YouTube.

Ce graphique indique le nombre de vidéos supprimées par YouTube en fonction de la source de détection initiale (signalement automatique ou détection manuelle). Les signalements par détection manuelle peuvent provenir d'un utilisateur ou d'un membre du programme [Trusted Flagger](https://support.google.com/youtube/answer/7554338) de YouTube. Un programme composé d'individus, d'ONG et d'autorités administratives qui informent YouTube des cas de contenus enfreignant le règlement de la communauté.

> YouTube est une communauté et, au fil des ans, les internautes ont utilisé la fonctionnalité de signalement située sous chaque vidéo et chaque commentaire pour signaler le contenu qui, selon eux, enfreint le règlement de la communauté. Nous souhaitons permettre à la communauté YouTube de comprendre comment fonctionne le signalement et de contribuer au respect du règlement de la communauté.

Cependant ce que YouTube ne dévoile pas, c'est le fonctionnement de la détection automatique, vraisemblablement responsable de la majorité de la suppression de contenu. **Parmis plus de 5,8 milliards de vidéos supprimées entre Octobre et Décembre 2019, 5,3 milliards l'ont été par la détection automatique**, soit environ 90%. Puisque le code source de YouTube n'est pas open source, il est impossible pour les internautes de savoir comment la plateforme et ses algorithmes fonctionne, ce qui rentre donc en conflit avec les garanties de transparence que Google souhaite instaurer.

## L'algorithme de recommandation, un fonctionnement obscur ?

Dans [un document de recherche][5] publié en 2016, un groupe d'ingénieurs de Google a fait part de ses projets sur la manière dont les vidéos pourraient être référencées par le moteur de recommandation de YouTube pour une meilleure expérience utilisateur.

![](../assets/screenshot_48.png)

Bien qu'il n'ait pas attiré beaucoup d'attention à l'époque, il est aujourd'hui très pertinent puisque, selon le chef de produit de YouTube, 70 % des vues passent maintenant par cet algorithme de recommandation.

![](../assets/screenshot_47.png)

> Au [CES (Consumer Electronics Show)](https://en.wikipedia.org/wiki/Consumer_Electronics_Show), le chef de produit de YouTube a affirmé que dans 70 % des cas, vous suivez une chaîne de recommandations orchestrée par un [algorithme d'apprentissage automatique](https://fr.wikipedia.org/wiki/Apprentissage_automatique).

D'après le document de recherche, voici les facteurs qui rentrent en compte dans l'algorithme de recommandation d'une vidéo YouTube :

-   Temps de visionnage moyen par les utilisateurs de la plateforme
-   Taux de clics (probabilité que quelqu'un clique sur la vidéo après l'avoir vue)
-   Combien de vidéos l'utilisateur a-t-il regardé sur la chaîne
-   La date à laquelle l'utilisateur a regardé une vidéo sur ce sujet
-   Ce que l'utilisateur a cherché dans le passé
-   Les vidéos précédemment regardées par l'utilisateur
-   Les informations démographiques et la localisation de l'utilisateur

### Le P-Score YouTube

Mais derrière l'algorithme de recommandation se cache d'autres facteurs plus obscurs, comme le _P-Score_, une note cachée attribuée à une chaîne YouTube qui désignerait son niveau de fiabilité pour les annonceurs, et qui permettrait donc de profiter d'un meilleur référencement par la plateforme. Il est calculé à partir de divers facteurs tel que :

-   Temps de visionnage moyen par les utilisateurs de la plateforme
-   L'engagement des utilisateurs (commentaires, votes, abonnements...)
-   La qualité de production de la vidéo
-   La plateforme sur laquelle les utilisateurs ont regardé la vidéo
-   La sécurité du contenu (contenu tout public, sans propos ou images dérangeantes, ...)

Ce score permettrait à YouTube de sélectionner 5% des créateurs ayant le plus haut score et de leur faire accèder au programme **Google Preferred**, ce qui leur permet de bénéficier de campagnes publicitaires avantageuses, et plus rémunératrices. Cette note n'est normalement visible que par les employés de YouTube et les annonceurs. Mais courant 2019, des vidéastes l'ont trouvée par hasard, dans le code source public de certaines pages YouTube.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/PYrJq7r90Ao" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

_Vidéo de Sylvqin, vidéaste français, sur le P-Score_

> YouTube avait détaillé ce procédé dans une vidéo publiée en avril dernier. La plateforme expliquait que seuls les 5 % des créateurs et créatrices de contenus les plus populaires étaient notés et classés.

Peut-on lire dans [cet article de Perrine Signoret sur Numerama][8].

Après avoir découvert le P-Score dissimulé dans plusieurs pages, Bowbax et d’autres vidéastes, ainsi que le journaliste et auteur Chris Stokel-Walker ont listé les notes obtenues par un peu plus de 230 vidéastes et les ont consignées dans [un document Excel](https://docs.google.com/spreadsheets/d/130CDsPSjg2BzzlA476AxjZQDdGiHGejhwV_F1H99RMs/edit#gid=0).

> Le tableau montre des scores contenus entre 230 et 1 050 environ (et qui diffèrent selon les pays). Les notes les plus hautes ont été attribuées à des shows télévisés comme le Late Show de Stephen Colbert, le Tonight Show de Jimmy Fallon, le Jimmy Kimmel Live, ou des chaînes télévisées comme CBC, Fox News, CNN ou la BBC.

![](../assets/screenshot_50.png)

> Ce classement a fait renaître certaines frustrations. Pour beaucoup, il prouve que YouTube favorise des entreprises, personnalités du monde du spectacle et médias plutôt que les créateurs de contenus qui ont fait sa renommée. La très bonne position de Will Smith est symptomatique de ce décalage. L’acteur a une chaîne active et de qualité, mais il ne compte que 7 millions d’abonnés. Pourquoi se retrouve-t-il au dessus de PewDiePie, qui en a plus de 100 millions, et de bien d’autres vidéastes plus populaires que lui ? Des internautes y voient un simple traitement de faveur, pour un acteur qui avait déjà été mis en tête d’affiche sur [le Rewind (vidéo bilan de l’année) controversé de 2018](https://www.youtube.com/watch?v=YbJOTdZBX1g).

## La course au "commercialement viable"

Le modèle économique basé sur la publicité a démontré à de nombreuses reprises, que YouTube était dans l'incapacité de se montrer impartial sur les décisions de démonétisation. Principalement à cause du pouvoir qu'ont les annonceurs sur ces décisions. Dans un article publié sur LeMonde, on peut voir que de nombreux vidéastes ont vu leurs vidéos supprimées ou démonétisées pour des motifs nébuleux.

![](../assets/screenshot_49.png)
_[Article publié en 2016 sur LeMonde][7]_

> YouTube ruine ma chaîne et je ne sais pas quoi faire.

Dans une vidéo publiée mercredi 31 août et consultée plus de 3 millions de fois, le youtubeur américain Philip DeFranco s’en prend à la plateforme qu’il accuse de « censure ».

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/Gbph5or0NuM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

> YouTube retire la publicité sur « les sujets et événements controversés, ce qui inclut des sujets relatifs à la guerre, aux conflits politiques, aux catastrophes naturelles et tragédies, même si aucune image explicite n’est montrée ». \[...] Des domaines extrêmement vastes et, surtout, soumis à interprétation. YouTube n’a pas précisé, dans les messages envoyés aux youtubeurs, la raison exacte qui, à chaque fois, l’a poussé à démonétiser la vidéo. Concernant Philip DeFranco, parmi les douze vidéos concernées, certaines évoquaient par exemple la sortie de prison d’un violeur ou encore un récent accrochage du chanteur Chris Brown avec la police.

La démonétisation concernerait donc les sujets abordés, et non la prise de position des vidéastes sur ceux-ci. Cela contribue à rendre les règles ambigues et désavantageuses pour les créateurs voulant aborder des sujets sensibles mais importants, comme par exemple des passages de l'histoire. De ce fait, YouTube n'est pas seulement un endroit où le contenu doit être tout public mais surtout un endroit où le contenu ne doit présenter aucun sujet sensible ou controversé.

* * *

Un autre exemple avec le vidéaste Luke Cutforth qui a vu sa vidéo abordant sa propre dépression censurée.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">YouTube disabled ads on my DEPRESSION video cus advisers dont like it. Sorry depression isn&#39;t fucking pretty enough… <a href="https://t.co/YXs0YFGVAb">pic.twitter.com/YXs0YFGVAb</a></p>&mdash; Luke Cutforth (@LukeCutforth) <a href="https://twitter.com/LukeCutforth/status/771124768280043521?ref_src=twsrc%5Etfw">August 31, 2016</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

> YouTube a désactivé les publicités de mes vidéos sur la dépression parce que les publicitaires ne l’aiment pas. Désolée que la dépression ne soit pas assez jolie…

* * *

Dans une vidéo publiée en Août 2019, le vidéaste Mastu indique qu'une de ces vidéos se fait systématiquement démonétisée à l'instant où elle est postée sur sa chaîne. Après plusieurs expérimentations et enquête, il en conclu que la totalité de la piste audio de sa vidéo se fait bloquée par le système de détection automatique, uniquement lorsqu'elle est postée sur sa chaîne. Selon le créateur il s'agirait d'un blocage sur liste noire de la part de YouTube, ce que dément la plateforme en indiquant qu'une telle liste n'existe pas.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/M65mTcFuJU0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

> YouTube m'a mis sur une liste noire !

Le créateur se voit donc contraint d'utiliser sa notoriété pour obtenir de l'aide de la part de la plateforme. Malgré une documentation détaillée sur l'algorithme de détection automatique, il n'est pas possible de savoir comment celui-ci fonctionne réellement, ni de savoir les raisons qui se cachent derrière les décisions de démonétisation.

> Et pourtant, YouTube n’a rien changé, ces derniers jours, à sa politique de monétisation des contenus. \[...] Néanmoins, elle \[la société YouTube] a expliqué avoir modifié la façon dont elle informait les youtubeurs de cette démonétisation. Alors qu’auparavant, l’entreprise désactivait les publicités sans les prévenir, elle a récemment décidé de leur envoyer un courriel.

Même si YouTube tend à se montrer plus transparent envers la communauté, sa notoriété semble lui faire défaut. La pression mise par les annonceurs et la détection automatique de contenu non réglementaire trop restrictive empêchent également la plateforme de se rapprocher des créateurs. Ces derniers peuvent se retrouver dans l'incapacité de continuer leur activité en toute liberté, car menacés en permanence par la gouvernance unique et centralisée que représente la plateforme de Google.

* * *

## Ressources

-   [Creators Say They’ve Cracked YouTube’s Monetization Algorithm][1] \[[archive][1_archive]]
-   [The YouTube P-Score — Is it the End of Real Viral Videos?][2] \[[archive][2_archive]]
-   [Rapport de transparence Google][3] \[[archive][3_archive]]
-   [How the YouTube Algorithm Works (Or Why Your Videos Aren’t Getting Views)][4] \[[archive][4_archive]]
-   [Document de recherche sur l'algorithme de recommandation YouTube][5] \[[archive][5_archive]]
-   [YouTube's AI is the puppet master over most of what you watch][6] \[[archive][6_archive]]
-   [Des vidéastes accusent YouTube de « censure qui ne dit pas son nom »][7] \[[archive][7_archive]]
-   [Que sont les notes « P-score » attribuées par YouTube à des vidéastes et publiées par erreur ?][8] \[[archive][8_archive]]
-   [Page de présentation du programme Google Preferred][9]

[1]: https://ffwd.medium.com/creators-think-theyve-reverse-engineered-the-p-score-youtube-s-monetization-algorithm-ce64c95a4510

[1_archive]: https://ffwd.medium.com/creators-think-theyve-reverse-engineered-the-p-score-youtube-s-monetization-algorithm-ce64c95a4510

[2]: https://medium.com/swlh/the-youtube-p-score-is-it-the-end-of-real-viral-videos-45f0f73ec247

[2_archive]: https://medium.com/swlh/the-youtube-p-score-is-it-the-end-of-real-viral-videos-45f0f73ec247

[3]: https://transparencyreport.google.com/youtube-policy/removals

[3_archive]: https://transparencyreport.google.com/youtube-policy/removals

[4]: https://www.shopify.com/blog/youtube-algorithm

[4_archive]: https://www.shopify.com/blog/youtube-algorithm

[5]: https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45530.pdf

[5_archive]: https://web.archive.org/web/20200531173209/https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45530.pdf

[6]: https://www.cnet.com/news/youtube-ces-2018-neal-mohan/

[6_archive]: https://www.cnet.com/news/youtube-ces-2018-neal-mohan/

[7]: https://www.lemonde.fr/pixels/article/2016/09/02/des-videastes-accusent-youtube-de-censure-qui-ne-dit-pas-son-nom_4991794_4408996.html

[7_archive]: https://www.lemonde.fr/pixels/article/2016/09/02/des-videastes-accusent-youtube-de-censure-qui-ne-dit-pas-son-nom_4991794_4408996.html

[8]: https://www.numerama.com/tech/566029-que-ce-sont-ces-notes-p-score-attribuees-par-youtube-a-des-videastes-et-publiees-par-erreur.html

[8_archive]: https://www.numerama.com/tech/566029-que-ce-sont-ces-notes-p-score-attribuees-par-youtube-a-des-videastes-et-publiees-par-erreur.html

[9]: https://youtube.com/ads/youtube-select/
