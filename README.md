# StrucVar

This package has only one function, and it takes in a data structure (the output from the other function) and a vcf file and returns the genes out interest that were found within a certain range. 

To run, run Struc_var(genes_of_interest,"vcf_file",num_of_var,how_far)
where genes of interest in the output from the other functions, vcf_file is the vcf file containing the structural variants, num_of_var is the number of variants you expect (pick a sufficiently large value for this) and how_far is the distance after the input position that you want the code to look for stuctural variants. 

I've included a csv file of genes of interest and a file containing structural variants. 

