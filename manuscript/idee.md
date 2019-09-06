

# Idée 

Objective: 
Avoir une connaissance théorique et pratique en bioinformatique 
pour interpreter les données de la génomique.


# Théorique:
Comprendre les notions de base : 
- En mathématique & statistique : 
    + Algèbre linéaire
        * Espace vectorielle, matrice, multidimensionnalité
        * Machine learning
            - Suppervisé: Regression linéaire, logistique, random forest, SVM 
            - Non suppervisé: reduction de dimension 
    + Statistique
        * Modèle et Donnée
        * Les différentes distribution
        * Distinguer la vraissemblance des données avec la crédence d'une théorie
        * Statistique fréquentiste 
            - Maximum de vraissemblance 
            - Expliquer la p-value et ses problèmes
        * Statistique bayesienne
            - Inférence Bayesienne
    + Algorithmique 
        * Théorie des graphes
            - Assemblage de Novo : Graphe de Debruijn
            - Allignement: Suffix Tree & Burrows wheeler 
        * Chaine de Markov 
        * Théorie de l'information: Turing & Entropie 
    + Biologie
        * L'organisme, la cellule, le Gène 
        * Le génome selon l'echelle : 
            - Chromosomes: Coordonnée chromosomique / anomalie cytogénétique 
            - Génome: Contenu du génome / Mutations / Nomenclature HGVS 
        * Evolution du vivant: clef de voute de la biologie 
        * Technologie de biologie moléculaire
            - Séquencage:
                + Illumina / IonTorrent
                    * Méthode: librairie de séquençage
                    * Stratégie : Panel , Exome , Génome 
                    * Autre application:
                        - Transcriptomique
                        - Métagénomique
                        - Single Cells 
                + Puce à ADN
                + PacBio / NanoPore 
        
# Pratique 
- Outils Bash  
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
- Intérpration des variants 
    + Méthode 
    + ACMG


# Plan 

- Préface 
- L'ADN de l'information numérique 
    + C'est quoi l'ADN
        * biologie / cellule / noyaux/ chromosomes / ADN 
        * Structure des gènes / transcription / Contenu / epigenietique 
    + code génétique / code ASCII 
    + Format de fichier texte / binaire 
    + Théorie de l'information : Entropie 
    + Exemple cheval encoder dans l'ADN 
- Lire l'ADN
    + Dans le chapitre 1 comment lire ces informations? 
    + Séquençage Sanger : format ab1
    + NGS 
    + Autre technologie : Singgle Cells
    + Format de sortie : Fastq / Fasta 
- Assemblage 
    + Génome humain
    + Algorithme de de bruijn 
- Allignement 
    + Algorithme de Burrows wheelers 
- Variant calling
    + Modèle Bayesien 
    + statistique 
    + variants 
- Interpreration des variants 
    + Machine learning 
    + classification 
    + classifcation ACMG
    + Base de donnée 
- Analyse multivarié 
    + algèbre linéaire 
    + single cells & microbiome
    + Decomposition

