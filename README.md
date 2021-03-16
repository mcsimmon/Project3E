# Project3E
The scientific question for this project is: If mice and humans have different Per2 gene protein sequences, will this affect the expression of the Per2 gene in different tissues? The hypothesis states: If there is a difference in the protein sequence of the Per2 gene between mice and humans, then the Per2 gene will be expressed differently in tissues. 


To run the code:
  -Jupyter Notebook 
  -FASTA files for Per2 in mice, human and cattle 


The FASTA files can be found on NCBI database by searching Per2 https://www.ncbi.nlm.nih.gov/. Under the tab that says 'Genes' there is a 'Gene' tab. By clicking that, it will take you to all the Per2 genes found in different organisms https://www.ncbi.nlm.nih.gov/gene/?term=Per2. The first two searches were for the Per2 gene found in Mus musculus (house mouse https://www.ncbi.nlm.nih.gov/gene/18627) and Homo sapiens (humans https://www.ncbi.nlm.nih.gov/gene/8864). Then by scrolling down a bit you will find the Per2 gene for Bos Taurus (cattle https://www.ncbi.nlm.nih.gov/gene/512237). When clicking on each organism, in the right hand corner there is a blue 'Download Datasets' button in which you can find the protein sequence FASTA file which will save as a .faa file. Once that is downloaded I used the directory of that file in my jupyter notebook. 


The code will result in three pairwise sequence alignment scores that compares the similarities between different sequences. In this case, the sequences come from mouse, humans and cattle. There is also a scatterplot that is presented which demonstrates the expression of the Per2 gene in mouse and human tissues. 
