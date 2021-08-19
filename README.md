# Lists from multiple sources for use in Mtb genomics

## Includes lists of genes to mask from variant coverage due to poor short read coverage (eg PE/PPE), genes associated with drug resistance, and gene annotations

### Most folders contain 

### 1) the original data, usually a supplementary file to a publication, 

### 2) A Jupyter notebook to translate the original data into a more readable (for humans or computers) format, and 

### 3) The output of that transformation


To make the Jupyter notebooks git friendly, follow the steps
1) Install nbstripout
`pip install --upgrade nbstripout`
2) Set up the git filter using .gitattributes
`nbstripout --install --attributes .gitattributes`
