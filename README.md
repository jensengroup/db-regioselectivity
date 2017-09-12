# db-regioselectivity

A database of real compounds and their regioselective products.

See (insert DOI here) for more details.

## Help

To play with this data is recommended to use RDKit (www.rdkit.org) and Python.

## Structure

The data is split into three files

 - `./compounds_smiles.csv` contains the compound SMILES and the experimental center of EAS (the atomic order follows the SMILES).

 - `./compounds_yield.csv` contains the yield of the compound. If multiple references, multiple yields are included.

 - `./compounds_doi.csv` contains the reference to literature in the form of either a DOI or a patent number. 
      If no DOI exists a reference is made and can be found in `bib/library.bib`.

## Cite

insert DOI here

