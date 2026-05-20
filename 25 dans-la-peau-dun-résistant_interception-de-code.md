# Dans la peau d'un résistant

## Interception de code

<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/beb76dd1-145c-42d2-b695-02af428f5eee" />

> Dans les nombreux documents laissés dans la valise de votre grand-père, certains sont beaucoup plus récents. Il semblerait qu'un ami de votre grand-père, lui aussi passionné, par le courage des résistants, a laissé un message chiffré à l’aide d’un algorithme baptisé CTFCodec. Vous avez en votre possession le code source de l’algorithme ainsi qu’un message chiffré.

> On sait que la clé a été communiquée par un certain Philippe Kieffer. Retrouvez-la.

> Cet algorithme de chiffrement vous permettra de retrouver des informations complémentaires. Le message chiffré dont vous disposez est le suivant : 59.YclN9cRcazVHWkbj3YRjHGIvALPBJCTU

> Où est-ce que cela vous mène ?

----------------------------------------------------------------------------------------------------------------
*Format du flag : plage_du_petit_sperone (le résultat attendu est sans accents en minuscules)*

----------------------------------------------------------------------------------------------------------------
*Ressources :*

[code source de l’algorithme : ./Ressources/CTF_Bleuet_2K26_-_Alpha_ici_Bravo_-_audio.wav
![code source de l’algorithme ]

<img width="648" height="704" alt="image" src="https://github.com/user-attachments/assets/645e006a-6dcc-4551-bb96-959809746972" />

----------------------------------------------------------------------------------------------------------------

Sheeeeeee "la bête" a clairement poncé ce chall en moins de 20min.

<img width="826" height="664" alt="image" src="https://github.com/user-attachments/assets/8860b8ac-79c4-43af-acd7-54821981df56" />

Le [2e lien](https://github.com/Philippe-Kieffer) nous donne la clé : **Key : Commandos-SAS-Qui-ose-gagne!**

<img width="400" height="532" alt="image" src="https://github.com/user-attachments/assets/2761e6a5-8689-4935-9718-6c4f73fa1a66" />

Le message déchifré avec la clé donne : **(49.3696815, -0.8710842)**

Et ces coordonnées dans google maps donnent "exactement là où se trouve le monument dédié au Commandant Kieffer" :

<img width="410" height="954" alt="image" src="https://github.com/user-attachments/assets/691f0707-a019-4282-a7bf-9589bd2a3f4e" />

Après quelques doutes sur le format car pas d'accent, il a validé.

**flag : omaha_beach** ✅

> P.S: Le github est le 1er lien duckduckgo en mettant le nom du type + github
