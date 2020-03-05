COS 360: Computational Models of Cognition  
Princeton University, Fall 2019  
Michael Hu  
Advisor: [Tom Griffiths](http://cocosci.princeton.edu/tom/index.php "Tom's Homepage")

## Introduction

This final project examines text generation using language models. Current language models tend to overpredict the likelihood of the most commonly appearing token. In other words, they say the most likely thing too often. We fix this issue using calibration. We collect the occurrence statistics of tokens on a small corpus, and calibrate the language model's outputs to match these occurrence statistics. The technique is fast, easy to implement, and performs favorably in practice.

