# TripleRE + NodePiece


This implementation of TripleRE + NodePiece for [**Open Graph Benchmak**](https://arxiv.org/abs/2005.00687) datasets (ogbl-wikikg) is based on [**OGB**](https://github.com/snap-stanford/ogb), [**NodePiece**](https://github.com/migalkin/NodePiece). Thanks for their contributions.


## Running the experiment
1, [**NodePiece**](https://github.com/migalkin/NodePiece) have pre-computed a vocabulary of 20k anchor nodes (~910 MB). Download it using the download.sh script:
```bash
cd TripleRE+Nodepiece && sh download.sh
```
2, Install the requirements from the requirements.txt

3, Run the code with the best hyperparameters using the main script
```bash
cd TripleRE+Nodepiece && sh run_ogb.sh
```

### ogbl-wikikg2
Please update ogb package to version 1.3.2. 
The details of the optional hyperparameters can be found in examples.sh.
