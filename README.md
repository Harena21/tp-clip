# TP CLIP sur les images médicales ROCO

TP du cours Multi-modalité et IA générative (M2 VMI, Université Paris Cité).

Je suis parti du tutoriel CLIP de M. C. Kurtz et X. Wei ([teaching_UPC_UFRMI](https://github.com/ckurtz/teaching_UPC_UFRMI)). Le début du notebook est ce tutoriel, lancé tel quel sur Colab. J'ai ajouté à la fin une partie TP qui répond aux quatre consignes :

1. lancer les démos et mesurer ce qu'elles montrent ;
2. comparer les 9 modèles CLIP sur CIFAR-100 et sur la recherche image/texte dans ROCO ;
3. tester CLIP sur d'autres images ROCO, avant et après fine-tuning ;
4. classer les races d'Oxford-IIIT Pet en zero-shot.

Sous chaque sortie, une cellule commente le résultat.

## Contenu

- `TP_CLIP_ROCO.ipynb` : le notebook avec ses sorties
- `rapport/` : le compte rendu en PDF et ses figures
- `requirements.txt` : les bibliothèques utilisées

## Relancer le notebook

Il faut un runtime Colab avec GPU (j'ai utilisé un T4). Le dossier de données du TP doit être ajouté en raccourci dans « Mon Drive » sous le nom `dataset_roco`. Pour ne lancer que ma partie, sans refaire le fine-tuning du tutoriel, se placer sur la cellule « 0. Installation » de la partie TP puis faire *Exécution > Exécuter les cellules suivantes*. Les résultats (JSON et figures) arrivent dans `MyDrive/TP_CLIP_resultats/`.
