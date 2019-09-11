


## Objective 
Avoir les connaissances théoriques et pratiques en bioinformatique 
pour produire et comprendre des données génomiques

## Méthodes

- Ne pas faire d'impasse sur le théorique tout en restant simple
- Schématiser ++
- Préférer l'exemple à l'abstraction
- Commencer par un concept théorique et finir sur de la pratique
- TP et exercice sur github / jupyter 


# Plan (en cours)

+ **L'ADN comme support d'information numérique**
    + Rappel en biologie moléculaire
        + cellule / noyaux / chromosomes / ADN 
            + Taille et composition du génome
            + Distinguer le génome du caryotype 
        + Structure des gènes / transcription / traduction / epissage
        + Non codant / épigénétique / regulation 
        + L'évolution darwinienne comme orchestre
        + En médecine
            + Génétique constitutionnelle
            + Génétique somatique
    + Informatique et Théorie de l'information
        + De Turing à Shannon
            + Binaire / machine de Turing / algorithme / Information
            + Numérique / analogique
        + L'ADN est un support numérique comme un autre
            + Exemple; encoder une vidéo dans l'ADN 
            + Toutes les méthodes en informatique s'appliquent donc à l'ADN
            
+ **Technologie en génétique moléculaire**
    + Méthode classique
        + PCR / Sanger 
    + Méthode de génotypage
        + Puce à ADN / ARMS ....
    + Séquençage de nouvelle génération 
        + Illumina 
            + Technique 
                + Librairie
                    + Capture / Amplicons 
                + Biais d'amplification / de séquençage
                + Phred Score
        + Données de sortie
            + Reads
                + Fasta / Fastq
        + Metrics des reads 
            + taille des reads 
            + Nombre de reads
            + Qualité des reads
            + FastQC
            + Savoir comparer des séquenceurs 
                + HiSeq / MiSeq / MinSeq / NovaSeq
        + Stratégie de séquençage
            + Alignement sur référence
                + Panel / Exome / Genome
            + Assemblage de novo 
    + Autres technologies et méthodes 
        + Single Cell
        + 3ème génération
            + Nanopore / PacBio
        + Transcriptome
            + RnaSeq / Single Cell 
        + Régulome
            + HiC / epigénétique / methylation
        + Microbiome
            
           
+ **Assemblage des génomes**
    + Théorie des graphes 
        + Parcours eulerien / hamiltonien
        + Graphe de Debruijn 
    + Metrics d'assemblage 
        + N50 .. 
        + Trimming, Contig, unitig
    + En pratique
        + Outils / ligne de commandes / fichiers
        + Fichier Fasta / GFA

+ **Alignement de séquences** 
    + Algorithme d'alignement
        + Multiple Alignement
            + Chaine de Markov 
        + Pairwise-alignement
            + Algorithme Dynamique
                + Smith/Waterman 
            + Tries / Burrows wheeler alignment
    + Génome de référence 
        + hg19 / hg38
        + UCSC / Ensembl
        + Coordonnée génomique
    + En pratique
        + Outils : Bwa
        + Fichiers: SAM/BAM 
            + Visualiser dans IGV
                + Notion de Couverture et de Profondeur
                + Différencier Panel / Capture
                + MapQ score / Phred Score 
            
+ **Détection des variants**
    + Inférence Bayesienne
        + Vraisemblances des données vs Crédences des Théories
        + Fréquentistes vs Bayes
            + En profiter pour critiquer la p-value
    + En pratique
        + pillup des variants
            + Distinguer variant homozygote / hétérozygote
            + Fréquence allèlique en somatique
        + FreeBayes
        + GATK HaplotypeCaller


+ **Interpreration des variants** 
    + Machine learning: 
        + Apprentissage supervisé
            + Regression 
                + Regression linéaire
            + Classification (des variants )
                + Regression logisitique
                + SVM 
                + Random Forest
                + Neural Network
    + Base de données et Annotations
        + GnomAd, Clinvar, omim , FrenchExac
        + Ontologie (HPO)
        + Score de prediction in-silico
        + Score phylogénétique
    + Mutation et nomenclature HGVS
        + Nomenclature c., p.
        + Types de variation
        + Polymorphisme / Variant 
    + En pratique
        + SnpEff / VEP / Annovar
        + classification ACMG
        + BAYES POWER ++

+ **Analyses multivariées**
    + algèbre linéaire
        + Vecteur / Matrice / Tenseur 
        + Espace à n dimensions 
    + Machine Learning:
        + Reduction de dimension
            + PCA / t-SNE 
        + Classification non supervisée 
            + Centroid
    + En pratique
        + Single cells / RNA Seq 
        + Microbiome

+ **Génomique de demain**
    + Séquençage des génomes (Médecine génomique)
    + Technologie à venir 
        + Variant Graph (référence sous forme de graphe)

+ **Annexes** 
    + Commande de base sous Unix
    + Utlisation d'un notebook jupyter 

# Notions à caser
- Maximum de vraisemblance 
- Chaine de Markov 
- Ontologie HPO 
- Protéomique 
- Pooper Science: On ne démontre pas , on réfute 
- Structure du génome : Taille, composition 
-  Les variants structuraux dans tout ca ? 
-  Utilisation de UCSC / Ensembl
-  Mettres des anecdotes sympas ? 
    -  Les pont de Konigsberg ? 
    -  Probleme bayesien 
+ Allignement: bwa, bowite2, samtools 
+ Variant calling: Freebayes, Gatk
+ Annotation: SnpEff, VEP, Annovar 
+ Analyse : snpeff 
+ Score: DANN, plI, conservation des espèces 
+ plink
- Programmation 
    + Python 
        * Pandas
        * Jupyter notebook 
- Base de donnée 
    + GenomAD
    + ClinVar
    + Omim

Format de fichier : 
FASTA, Fastq, BAM/SAM , Bed , VCF 
GFF, GTF3 , BEDGRAPH,

Divers
LogoPlot
DotPlot
Hi-C 




