# AI-TS
Automatic Italian Ticket Sorting

## Folder structure

<ul>
  <li><strong>datasets</strong>: contains our test sets</li>
  <lI><strong>environment.yml</strong>: requirements file to build the conda environment to run the scripts</lI>
  <lI><strong>sorter.py</strong>: python script to run the zero shots and few shots experiments</lI>
  <li><strong>voting.py</strong>: python script to run the ensemble experiments</li>
</ul>

## Run Experiments

```console
conda env create -f environment.yml
conda activate aits
python sorter.py
```

## Citing our work

If you use this code or our datasets, please cite us:

<i>Arici N, Gerevini AE, Putelli L, Sigalini L, Serina I, LLM-based Approaches for Automatic Ticket Assignment: A Real-World Italian Application. In: Seventh Workshop on Natural Language for Artificial Intelligence (NL4AI 2023) co-located with 22th International Conference of the Italian Association for Artificial Intelligence (AI* IA 2023). 2023.</i>
