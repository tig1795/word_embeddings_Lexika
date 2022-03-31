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

Bilder

    Datenexploration
        Anzahl_Laenge_Kategorie
             Anzahl_der_Newsartikel_pro_Kategorie.png
             Artikellängen_pro_Kategorie.png
             Verteilung_der_Artikellängen.png 
        MFW30_categroy
             freq_30mfw_korrekt.png
        Wordclouds 
             wordcloud_Business.png
             wordcloud_Entertainment.png
             wordcloud_Politics.png
             wordcloud_Sport.png
             wordcloud_Technology.png 
        Gaussian Mixture Models
             GMM_AIC.png
             GMM_BIC.png
             GMM_Sport_Politics_TSNE.png
             GMM_Sport_Politics_Tech_TSNE.png
             GMM_Sport_Tech_TSNE.png
             GMM_alle_Kategorien_TSNE.png 
        HC
         HC_PCA_2.5_percent_all_categorys.png
         HC_PCA_Business_Tech_5_percent.png
         HC_PCA_Sport_Tech_5_percent.png
         HC_Sport_Entertainment.png
         HC_Sport_Entertainment_5_percent_filenames.png 
       KMeans
         Ellenbogen_Methode_und_Silhouetten_Koeffizient
              EM.png
