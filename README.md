# wikid2vec
Wikiid2vec adalah library untuk melakukan download, extract, dan training article yang ada pada wikipedia bahasa indonesia menjadi word2vec.

# How to Install
pip install wikiid2vec

# How to Use
from wiki2vec.wiki2vec import Wiki2Vec

wikiid2vec = Wiki2Vec()
wikiid2vec.download()

*TUnggu hingga selesai setelah itu cukup dengan 

model = wiki2vec.load_model()

#TODO
- Testing
- Tutorial
