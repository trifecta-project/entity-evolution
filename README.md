# Introduction 
Code and data for "When a Search Engine Company Buys a Robotics Company, Is It Still a Search Engine Company? Exploring Entity Change in Wikidata" (under review) 

In the paper, we present an approach and experiments that make explicit entity change in Wikidata. We present a model for identifying types of change, an approach to obtain changes in entities from Wikidata, a dataset of entities with explicit evolution information and analytics on this dataset. In this Github repo, you will find the code and data for this paper. 

## Prerequisites 
- Python3
- SPARQLWrapper
- Pandas
- Seaborn 

## How to run 
Notebook "0-Query & Download from Wikidata.ipynb" provides the core information needed to run the analyses. Before you start running all cells and query Wikidata: the results of all queries are also stored in the .tsv files in data/ The 'stats' cells in the notebook generate the input for Table 1 in the paper. 

To generate the figures and input for tables in the paper, run the other notebooks. The header specifies which notebook generates which table/figure input. 

## License
This code is [Apache licensed](https://github.com/Odeuropa/explorer/blob/main/LICENSE).

