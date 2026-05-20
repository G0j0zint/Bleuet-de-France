# Dans la peau d'un résistant

## Plastique et crayons

<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/a4859050-f6df-4896-9d0e-02bbf5793de6" />

> Parmi les images conservées par votre grand-père figure cet endroit. Après quelques recherches, vous vous apercevez qu'ici s’est joué l'un des sabotages ferroviaires les plus efficaces de la résistance française. L’auteur des faits a agi en plein jour, alors même que les sentinelles allemandes patrouillaient dans les alentours. Par ailleurs, un document titré de son nom relate encore son exploit.

> D’après ce dernier, combien de temps ont duré les explosions et à quelle distance ont-elles pu être entendues ?

----------------------------------------------------------------------------------------------------------------
*Format du flag : moins_de_15h_plus_de_37km*

----------------------------------------------------------------------------------------------------------------
*Ressources : image du chall*

----------------------------------------------------------------------------------------------------------------

Après la déculotté que nous a mise ChatGPT sur le dernier challenge, on lui donne celui-ci en patûre di-rect.

"Le sabotage correspond très probablement réalisé par Henri Ferrand avec du plastic et des crayons détonateurs.

D’après le récit conservé sur l’événement :

les explosions ont commencé à 19h35 et se sont terminées vers 1h du matin, soit 5h25 ;
elles ont été entendues à 80 km à la ronde.

Flag : 5h25_80km"

On vérifie quand même (on va pas se mettre à lui faire confiance quand même)... 

[Wikipedia](https://fr.wikipedia.org/wiki/Sabotage_du_train_de_munitions_de_Laluque) confirme l'heure mais pas la distance : "La première explosion intervient en avance à 19h35. L'incendie se propage à l'ensemble du train, allumant une série d'explosions qui se termine à 1h du matin. L'explosion fut entendue au-delà de Mont de Marsan."

BOUH ChatGPT ! Nul.

Nico continue à fouiller les wikis et trouve dans [cet article](https://archive.wikiwix.com/cache/index2.php?url=http%3A%2F%2Fwww.anacr.com%2Fhtfr%2F0027.htm#federation=archive.wikiwix.com&tab=url) : "L'explosion a provoqué un vacarme extraordinaire entendu à 50 km à la ronde; un affolement général s'en est suivi. Mais personne n'a été tué."

Ce qui nous donne le 1er fails d'une longue série : moins_de_6h_plus_de_50km ❌

Nico continue de plonger dans les archives et tombe, après 40min, sur [LE récit que l'on cherche](https://archives.landes.fr/service-educatif/concours-national-de-la-resistance-et-de-la-deportation/cnrd-2022-2023/les-documents/theme-4--enseignants-et-eleves-resistants/henri-ferrand#visionneuse-cms_3942694_0). Mais voilà, il est 23h18, on est fatigué et on tente des flags tous plus éclatés les uns que les autres :

moins_de_49h_plus_de_50km ❌ & moins_de_48h_plus_de_50km ❌

On se dit que c'est pas ça... Quelle erreur...

On est désespéré, on tente des flags randoms : moins_de_06h_plus_de_50km ❌

Je bataille jusqu'à minuit et demie, puis je pars faire des cauchemars de ce chall T-T

Le lendemain matin, mon cauchemar devient réalité :

<img width="572" height="895" alt="image" src="https://github.com/user-attachments/assets/f3036c98-c314-4f03-8456-d8993b3307d0" />

**flag : plus_de_48h_plus_de_50km** ✅

> P.S: J'ai jamais eu autant le seum sur un chall d'OSINT, Sheeeeeee et Pl0k ont continué de me ragebait un bon moment après ça, ils m'ont pas lâché x)
