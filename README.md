# Introduction à la fouille de texte

Ce cours fait partie du [*séminaire d'introduction aux humanités numériques*](https://odhn.ens.psl.eu/evenements/manipulation-de-textes-avec-python), donné à l'Observatoire des humanités numériques de l'ENS-PSL. Ce dépôt GitHub conserve tous les supports de cours utilisés.

---

## Utilisation

### Google Colab

- 1er notebook: [1_python_basique](https://colab.research.google.com/drive/1v5KxcpGpO9SIPQZ3UmVSwozzPzr5YYAm?usp=sharing)
- 2e notebook: [2_manipyler_du_texte_simple](https://colab.research.google.com/drive/1muK2q0T_X0AKXwsZe9TlH0CIopI501_E?usp=sharing)

Il faudra charger tous les textes dans la partie "fichiers" de votre Google Colab (onglet en forme de dossier à gauche de l'écran).

### En local (MacOs / Linux)

L'utilisation en local est possible (et plutôt facile) et conseillée: c'est plus rapide et ça évite de passer par Google. Pour utiliser un notebook en local, on utilise le super projet `jupyter`, qu'on installe en suivant les étapes ci-dessous.

Pour l'installation en local, il faut avoir Git installé sur son ordinateur.

```bash
git clone https://github.com/paulhectork/cours_ens2025_fouille_de_texte.git  # on télécharge le projet
cd cours_ens2025_fouille_de_texte  # se déplacer dans le dossier du projet
python3 -m venv env  # créer un "environnement virtuel" qui contient toutes les librairie python propre au projet
source env/bin/activate  # activer l'environnement virtuel
pip install -r requirements.txt  # installer toutes les librairies, et surtout jupyter notebook
jupyter notebook  # lancer jupyter
```

Pour pouvoir utiliser les notebooks correctement, le fichier `in_correspondance_matsutaka_full.txt` doit être présent à la racine de `cours_ens2025_fouille_de_texte.git`. Il n'est pas présent dans le dépôt Git.

---

## Sources

Le corpus de correspondances Matsutaka est conservé à l'INHA et a été retranscrit par Léa Saint-Raymond.

Les trois romans de Woolf utilisés dans ce notebook ont été légèrement modifiés à partir de version en texte libre téléchargées sur:
- Woolf, V. (1937, 1e édition 1927). *To The Lighthouse*. New York: The Modern Library. 326p. Téléchargé sur [archive.org](https://archive.org/details/in.ernet.dli.2015.376)
- Woolf, V. (1960, 1e édition 1931). *The Waves*. London: The Hogarth Press. 216 p. Téléchargé sur [archive.org](https://archive.org/details/in.ernet.dli.2015.2478/)
- Woolf V. (1963, 1e édition 1925). *Mrs. Dalloway*. London: The Hogarth Press. 213 p. Téléchargé sur [archive.org](https://archive.org/details/dli.ernet.16394/)

---

## Pour aller plus loin

- Laramée, F. D. (2018). Introduction à la stylométrie en Python. *Programming historian*. [En ligne](https://programminghistorian.org/fr/lecons/introduction-a-la-stylometrie-avec-python)
- Lavin, Matthew J. (2019). Analyse de documents avec TF-IDF. *Programming historian*. [En ligne](https://programminghistorian.org/fr/lecons/analyse-de-documents-avec-tfidf)
- Bird, S. & Klein E. & Loper E. (1e édition 2009). *Natural language processing with pyton. Analyzing text with the natural language toolkit*. [En ligne](https://www.nltk.org/book/) (pour aller beaucoup plus loin) 

---

## Licence et crédits

Les notebooks sont sous licence libre `GNU GPL 3.0`. Les textes sont sous licence libre creative commons (`CC BY 4.0`), sauf `in_corrspondance_matsutaka_full.txt`, qui est prêté par Léa Saint Raymond et ne doit pas être diffusé en dehors de ce cours (il n'est pas stocké dans le Git).
