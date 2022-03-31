# word_embeddings_Lexika

Gegenstand dieses Repositorys ist die Untersuchung der Eignung von Bert zur Überprüfung von Wortbedeutungswandel.
Im Rahmen dieser Untersuchung wurde sowohl Word2Vec als auch BERT verwendet. 

Die verwendeten vortrainierten Modell und der Code zu HistWords sind hier zu finden: 

- https://huggingface.co/bert-base-german-cased
- https://huggingface.co/redewiedergabe/bert-base-historical-german-rw-cased
- https://devmount.github.io/GermanWordEmbeddings/
- https://github.com/williamleif/histwords

Die verwendete Liste der zu untersuchenden Wörter auf Bedeutungswandel wurde von diesem Artikel inspiriert:

- https://www.welt.de/kultur/article187273070/Weltmeister-bloede-Feminismus-20-Woerter-die-frueher-etwas-ganz-anderes-bedeuteten.html

Das Repository ist viel folgt aufgebaut: 

    Literatur
        Diachronic Word Embeddings Reveal Statistical Laws of Semantic Change.pdf
    notebooks
        0_Exploration
            Exploration_model_bert_base_german_cased.ipynb
            Exploration_fine_tuning_data.ipynb
            Exploration bert-base-historical-german-rw-cased.ipynb
