
# Materiale didattico per il corso di Classificazione e Analisi dei dati Multivariati AA 15/16, Università di Padova

In questa esercitazione di modelli di previsione per dati testuali, lavoreremo sul dataset usato da 

###[sentipolc-evalita14](http://www.di.unito.it/~tutreeb/sentipolc-evalita14/index.html) 
all'interno della
`fourth evaluation campaign of Natural Language Processing and Speech tools for Italian`:

###[Evalita 2014](http://www.evalita.it/2014).


Se inoltre siete interessati a parteciapre all'edizione del 2016 

###[Evalita 2016](http://www.di.unito.it/~tutreeb/sentipolc-evalita16/)
- [descrizione dei task](http://www.evalita.it/2016/tasks)
- su [Facebook](https://www.facebook.com/evalita2016) o Twitter @EVALITAcampaign



* * *

## Documenti e File Utili

- [Atti del Convegno EVALITA-2014 ](http://clic.humnet.unipi.it/proceedings/Proceedings-EVALITA-2014.pdf)
Qui trovate la descrizione delle competizioni e i modelli usati dai vincitori della competizione (in particolare si veda: Basile et al. Overview of the Evalita 2014 SENTIment POLarity Classification Task, pag 50)
- [Esempio preprocessing dei dati](https://rawgit.com/livioivil/Evalita-2014/master/EsempioPreprocessing.html)
- [Dataset preprocessato e funzioni di valutazione dei risultati](dati_FunScore.Rdata)
- [Esempio Modelli di predizione](https://rawgit.com/livioivil/Evalita-2014/master/EsempioAnalisi.html)

Il file zip con tutti i documenti e i file dati la potete scaricare da (in alto a destra, bottone verde): [`Clone or Download` > `Dowload ZIP`](https://github.com/livioivil/Evalita-2014/archive/master.zip)

## Set up `R`

Avrete bisogno di alcuni package `R` disponibili su CRAN (ad esempio `tm`), ma anche del package `TextWiller` disponibile su [GitHub](https://github.com/)

    # install.packages("devtools") 
    library(devtools)
    install_github("livioivil/TextWiller")
