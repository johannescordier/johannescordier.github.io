---
title: "Entity embedding of high-dimensional claims data for hospitalized exacerbation prediction"
collection: publications
category: manuscripts
permalink: /publication/2024-03-07-entityembedding
date: 2024-05-31
venue: 'Health, Econometrics and Data Group Working Papers, c/o Department of Economics, University of York.'
paperurl: 'https://www.york.ac.uk/media/economics/documents/hedg/workingpapers/2024/2409.pdf'
citation: 'Cordier, J., Geissler, A., & Vogel, J. (2024). Entity embedding of high-dimensional claims data for hospitalized exacerbation prediction. Health, Econometrics and Data Group (HEDG) Working Papers 24/08, HEDG, c/o Department of Economics, University of York.'
---

This study addresses the challenges of using high-dimensional claims data, typically represented by  categorical features, for prediction tasks. Traditional one-hot encoding methods lead to computational inefficiencies and sparse data issues. To overcome these challenges, we propose using entity embedding, a technique that has shown promise in natural language processing, to transform  categorical claims data into dense, low-dimensional vectors as input for downstream prediction tasks.  Our study focuses on predicting hospitalizations for patients with Chronic Obstructive Pulmonary Disease using the Word2Vec Continuous Bag-of-Words model. Our findings indicate that entity embedding enhances model performance, achieving an AUC of 0.92 compared to 0.91 with one-hot encoding, and improves specificity from 0.55 to 0.60 for a recall of 0.95. Additionally, entity embedding significantly reduces required computation power. These results suggest that entity embedding not only captures the dynamics of medical events more effectively but also enhances the efficiency of training predictive models, making it a valuable tool for healthcare and insurance analytics.