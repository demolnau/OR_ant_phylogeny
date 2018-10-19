# OR_ant_phylogeny

#Rebuilding the Zhou phylogeny
The Zhou phylogeny is a great resource, but you cant see the names at the end of the branches.
I exported the Zhou OR ant phylogeny newick file as a text file and then imported that into iTol (ant_OR_Zhou_newick_format_tree.txt).
I added color to all clades identified in the Zhou paper (ant_OR_zhou_paper.png) and exported this as a pdf (Zhou_ant_OR_iTol_colored_clades.pdf).
A script was written in jupyter notebook to find the most common recent ancestor of two members of a clade and then to find all fellow members of a clade.
This script was later expanded on to loop through all clades given. Clades must be delimited manually,
 hence why I build a colored tree with the clades labeled at the tips.
 
The next step will be to read in comparative phylogeny, delimit the clades
 and see how many members of each family are represented in both the Zhou original paper
 and my own possible delimitation. 
This is simply to use a consistent nomenclature.