# OrthologTables

Each file represents orthology predictions made for a query protein by multiple orthology algorithms. Tables are created by searching for a gene within ortholog lists, and listing genes named as orthologs to it according to each database. 

Each row is a putative ortholog, and contains Uniprot Accession, Uniprot Entry, Ensmebl proteins ID, species, vount of algorithms prediction orthology, and individual algorithm predictions. 
Note on naming: Since most protein IDs were given in uniprot format, I tried to convert the minority of ensembl proteins IDs to uniprot where possible. In these cases, both the ensemble ID and uniprot ID are kept, but no effect was made to convert uniprot IDs into Ensembl. 

Ortholog groups are pulled from the Quest for Orthologs reference proteome benchmarking 2011. The following algorithms ortholog calling algorithms were run on identical proteome sets covering 66 species, including eukaryotes, archaea and bacteria. 

Hieranoid 2.0 (KO) release 74
EnsemblCompara v2
InParanoid
InParanoidCore
metaPhOrs missing genomes: {PYRKO,STRCO,THEMA}
OMA GETHOGs
OMA Groups (RefSet5)
OMA OMA Pairs (Refset5)
orthoinspector 1.30
PANTHER 8.0 (all)
PANTHER 8.0 (LDO only)
phylomeDB
RBH - 26 genomes missing
RSD 0.8 1e-5 Deluca (Roundup)
