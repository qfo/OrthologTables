# OrthologTables

Each file represents orthology predictions made for a query protein by multiple orthology algorithms. Tables are created by searching for a gene within ortholog lists, and listing genes named as orthologs to it according to each database. 

Each row is a putative ortholog, and contains Uniprot Accession, Uniprot Entry, Ensmebl proteins ID, species, count of algorithms prediction orthology, and individual algorithm predictions. 

Note on naming: Since most protein IDs were given in uniprot format, I converted the minority ensembl proteins IDs to uniprot where possible. In these cases, both the ensemble ID and uniprot ID are kept, but no effort was made to convert uniprot IDs into Ensembl. 

| **Common Name** | **Uniprot ID** | 
| --------------- | -------------- |
| *Anopheles gambiae* (Mosquito) | ANOGA | 
| *Aquifex aeolicus* | AQUAE | 
| *Arabidopsis Thaliana* | ARATH | 
| *Neosartorya fumigata* (Black mold) | ASPFU | 
| *Bacillus subtilis*  | BACSU | 
| *Bacteroides thetaiotaomicron*  | BACTN | 
| *Bos taurus* (Cattle) | BOVIN | 
| *Bradyrhizobium diazoefficiens* | BRADU | 
| *Branchiostoma floridae* (Lancelet) | BRAFL | 
| *Caenorhabditis elegans* (Worm) | CAEEL | 
| *Candida albicans* | CANAL | 
| *Canis lupus familiaris* (Dog) | CANFA |
| *Chlamydia trachomatis* | CHLTR | 
| *Chloroflexus aurantiacus* | CHLAA | 
| *Gallus gallus* (Chicken) | CHICK | 
| *Ciona intestinalis* (Tunicate) | CIOIN | 
| *Cryptococcus neoformans* | CRYNJ | 
| *Danio rerio* (Zebrafish) | DANRE | 
| *Deinococcus radiodurans* | DEIRA | 
| *Dictyoglomus turgidum* | DICTD | 
| *Dictyosteium discoideum* | DICTI | 
| *Drosophila melanogaster* (Fly) | DROME | 
| *Escherichia coli* | ECOLI | 
| *Fusobacterium nucleatum* | FUSNN | 
| *Geobacter sulfurreducens* | GEOSL | 
| *Giardia intestinalis* | GIAIC | 
| *Gloeobacter violaceus* | GLOVI | 
| *Halobacterium salinarum* | HALSA | 
| *Homo sapiens* (Human) | HUMAN | 
| *Ixodes scapularis* (Tick) | IXOSC |
| *Korarchaeum cryptofilum* | KORCO | 
| *Leishmania major* | LEIMA | 
| *Leptospira interrogans* | LEPIN | 
| *Macaca mulatta* (Rhesus macaque) | MACMU | 
| *Methanocaldococcus jannaschii* | METJA | 
| *Methanosarcina acetivorans* | METAC | 
| *Monosiga brevicollis* (Choanoflagellate) | MONBE | 
| *Monodelphis domestica* (Opossum) | MONDO | 
| *Mus musculus* (Mouse) | MOUSE | 
| *Mycobacterium tuberculosis* | MYCTU | 
| *Nematostella vectensis* (Sea anemone) | NEMVE | 
| *Neurospora crassa* (Bread mold) | NEUCR | 
| *Ornithorhynchus anatinus* (Platypus) | ORNAN | 
| *Pan troglodytes* (Chimp) | PANTR | 
| *Phaeosphaeria nodorum* | PHANO | 
| *Physcomitrella patens* | PHYPA |
| *Plasmodium falciparum* | PLAF7 |
| *Pseudomonas aeruginosa* | PSEAE |
| *Rattus rattus* (Rat) | RAT | 
| *Rhodopirellula baltica* | RHOBA |
| *Saccaromyces cerevisiae* (Budding yeast) | YEAST | 
| *Schistosoma mansoni* (Blood fluke) | SCHMA | 
| *Schizosaccharomyces pombe* (Fission yeast) | SCHPO | 
| *Sclerotinia sclerotiorum* | SCLS1 | 
| *Streptomyces coelicolor* | STRCO |
| *Sulfolobus solfataricus* | SULSO |
| *Synechocystis sp.* | SYNY3 |
| *Takifugu rubripes* (Pufferfish) | TAKRU | 
| *Thermococcus kodakaraensis* | THAPS |
| *Thermodesulfovibrio yellowstonii* | THEKO |
| *Thermotoga maritima* | THEYD |
| *Trichomonas vaginalis* | TRIVA |
| *Ustilago maydis* (Corn smut/Huitlacoche | USTMA | 
| *Xenopus tropicalis* (Frog) | XENTR | 
| *Yarrowia lipolytica* | YARLI |


Ortholog groups are pulled from the Quest for Orthologs reference proteome benchmarking 2011. The following algorithms ortholog calling algorithms were run on identical proteome sets covering 66 species, including eukaryotes, archaea and bacteria. http://www.ebi.ac.uk/reference_proteomes

Hieranoid 2.0 (KO) release 74

EnsemblCompara v2

InParanoid

InParanoidCore

metaPhOrs missing genomes: {PYRKO,STRCO,THEMA}

OMA Groups (RefSet5)

OMA OMA Pairs (Refset5)

orthoinspector 1.30

PANTHER 8.0 (all)

PANTHER 8.0 (LDO only)

phylomeDB

RBH - 26 genomes missing

RSD 0.8 1e-5 Deluca (Roundup)
