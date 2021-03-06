---
# Automatically generated by bib2md.py
title: "BankSealer: A decision support system for online banking fraud analysis and investigation"
slug: "Carminati2015BankSealer_A"
date: "2015-05-23"
publishdate: "2000-01-01"

authors:
  - "Michele Carminati"
  - "Roberto Caron"
  - "Federico Maggi"
  - "Ilenia Epifani"
  - "Stefano Zanero"

category: journal

venue: "Computers & Security (Volume , Issue )"

slides: no
paper: no
text: no
external_url: http://www.sciencedirect.com/science/article/pii/S0167404815000437
video_url: no

bibtex: |
    @article{Carminati2015BankSealer_A,
      title     = {{BankSealer: A decision support system for online banking fraud analysis and investigation}},
      author    = {Carminati, Michele and Caron, Roberto and Maggi, Federico and Epifani, Ilenia and Zanero, Stefano},
      month     = {April},
      year      = {2015},
      issn      = {0167-4048},
      journal   = {Computers \& Security},
      url       = {http://www.sciencedirect.com/science/article/pii/S0167404815000437}
    }




---

The significant growth of online banking frauds, fueled by the underground economy of malware, raised the need for effective fraud analysis systems. Unfortunately, almost all of the existing approaches adopt black box models and mechanisms that do not give any justifications to analysts. Also, the development of such methods is stifled by limited Internet banking data availability for the scientific community. In this paper we describe BankSealer, a decision support system for online banking fraud analysis and investigation. During a training phase, BankSealer builds easy-to-understand models for each customer's spending habits, based on past transactions. First, it quantifies the anomaly of each transaction with respect to the customer historical profile. Second, it finds global clusters of customers with similar spending habits. Third, it uses a temporal threshold system that measures the anomaly of the current spending pattern of each customer, with respect to his or her past spending behavior. With this threefold profiling approach, it mitigates the under-training due to the lack of historical data for building well-trained profiles, and the evolution of users' spending habits over time. At runtime, BankSealer supports analysts by ranking new transactions that deviate from the learned profiles, with an output that has an easily understandable, immediate statistical meaning.  Our evaluation on real data, based on fraud scenarios built in collaboration with domain experts that replicate typical, real-world attacks (e.g., credential stealing, banking trojan activity, and frauds repeated over time), shows that our approach correctly ranks complex frauds. In particular, we measure the effectiveness, the computational resource requirements and the capabilities of BankSealer to mitigate the problem of users that performed a low number of transactions. Our system ranks frauds and anomalies with up to 98% detection rate and with a maximum daily computation time of 4 min. Given the good results, a leading Italian bank deployed a version of BankSealer in their environment to analyze frauds.