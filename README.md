# TP CLIP : représentations texte/image sur des images médicales (ROCO)

TP du cours Multi-modalité et IA générative (IFLCE055), M2 VMI, Université Paris Cité.

Le notebook part du tutoriel CLIP de C. Kurtz et X. Wei ([teaching_UPC_UFRMI](https://github.com/ckurtz/teaching_UPC_UFRMI)). Le début est le tutoriel exécuté tel quel, la partie « Partie TP » à la fin répond aux consignes :

1. prise en main des démos (similarité image/texte, zero-shot) ;
2. comparaison des 9 modèles CLIP (CIFAR-100 zero-shot, recherche image/texte sur ROCO, temps de calcul) ;
3. CLIP sur d'autres images ROCO, avant et après fine-tuning (recherche, classification de la modalité) ;
4. classification zero-shot sur Oxford-IIIT Pet.

Chaque sortie est suivie d'une cellule de commentaire.

## Lancer le notebook

- Google Colab avec un GPU (T4).
- Ajouter le dossier de données partagé du TP dans « Mon Drive » sous le nom `dataset_roco`.
- Se placer sur la cellule « 0. Installation » de la partie TP puis *Exécution > Exécuter les cellules suivantes*. Pas besoin de relancer le fine-tuning du tutoriel.

Les résultats (JSON et figures) sont écrits dans `MyDrive/TP_CLIP_resultats/`.

Dépendances : voir `requirements.txt` (le package `clip` s'installe depuis le dépôt d'OpenAI).
