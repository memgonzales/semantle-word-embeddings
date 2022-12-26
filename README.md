# Recreating Semantle (Experimenting with Word Embeddings)
![badge][badge-jupyter]
![badge-python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flate&logo=numpy&logoColor=white)

This project attempts to recreate a version of the game [Semantle](https://semantle.com/), a variant of the five-letter word guessing game [Wordle](https://www.nytimes.com/games/wordle/index.html) that gives the semantic similarity of the player's guess to the secret word of the day. Our version of Semantle allows the player to choose from the following **pretrained word embeddings**:
- [word2vec](https://proceedings.neurips.cc/paper/2013/file/9aa42b31882ec039965f3c4923ce901b-Paper.pdf)
- [GloVe](https://aclanthology.org/D14-1162.pdf)
- [fastText](https://aclanthology.org/E17-2068.pdf)

All the scripts are placed inside a [Jupyter notebook](https://github.com/memgonzales/semantle-word-embeddings/blob/master/Semantle%20Recreation.ipynb), which also includes a detailed write-up covering the following:
- Design decisions in the implementation of the program
- Walkthrough of the implementation of the program
- Comparative analysis of selected word embeddings in the context of the program
- Insights on vector semantics, including:
  - Possible applications outside natural language processing (e.g., vectorizing protein sequences)
  - Ethical issues and latent biases in word embeddings

This [notebook](https://github.com/memgonzales/semantle-word-embeddings/blob/master/Semantle%20Recreation.ipynb) was created using [Google Colab](https://colab.research.google.com/) and invokes commands such as `gdown` and `wget`. The memory requirement of loading pretrained word embeddings may also be heavy for some local machines. Therefore, we recommend running the notebook on Colab.

This is a major course output in an introduction to natural language processing class under Mr. Edward P. Tighe of the Department of Software Technology, De La Salle University.

## Built Using
This project is a Jupyter notebook, with the following Python libraries and modules used:

Library/Module |	Description |	License
-- | -- | --
[`gensim`](https://radimrehurek.com/gensim/) | Provides functions for training vector embeddings, topic modelling, document indexing, and similarity retrieval with large corpora | GNU Lesser General Public License v2.1
[`regex`](https://pypi.org/project/regex/)	| Provides additional functionality over the standard [`re`](https://docs.python.org/3/library/re.html) module while maintaining backwards-compatibility	| Apache 2.0 License
<a href = "https://numpy.org/"><code>numpy</code></a> | Provides a multidimensional array object, various derived objects, and an assortment of routines for fast operations on arrays | BSD 3-Clause "New" or "Revised" License
[`io`](https://docs.python.org/3/library/io.html) | Provides Python's main facilities for dealing with various types of I/O | Python Software Foundation License
<a href = "https://docs.python.org/3/library/random.html"><code>random</code></a> | Provides functions for generating pseudo-random numbers with various common distributions | Python Software Foundation License

*The descriptions are taken from their respective websites.*

## Author
- <b>Mark Edward M. Gonzales</b> <br/>
  mark_gonzales@dlsu.edu.ph <br/>
  gonzales.markedward@gmail.com <br/>
  
- <b>Hylene Jules G. Lee</b> <br/>
  hylene_jules_lee@dlsu.edu.ph <br/>
  lee.hylene@gmail.com
  
- <b>Phoebe Clare L. Ong</b> <br/>
  phoebs_ong@dlsu.edu.ph <br/>
  ongphoebeclare@gmail.com

[badge-jupyter]: https://img.shields.io/badge/Jupyter-F37626.svg?&style=flat&logo=Jupyter&logoColor=white
[badge-pandas]: https://img.shields.io/badge/Pandas-2C2D72?style=flat&logo=pandas&logoColor=white
[badge-numpy]: https://img.shields.io/badge/Numpy-777BB4?style=flat&logo=numpy&logoColor=white
[badge-scipy]: https://img.shields.io/badge/SciPy-654FF0?style=flat&logo=SciPy&logoColor=white

