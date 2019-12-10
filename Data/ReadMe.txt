
# File types
==============
*.csv:	comma separated files
*.tsv:	tab separated files
*.txt:	plain text file
*.md:	R markdown files

# iris_dataset.csv
========================
This famous (Fisher's or Anderson's) iris data set gives the measurements in centimeters of the variables sepal length and width and petal length and width, respectively, for 50 flowers from each of 3 species of iris. The species are Iris setosa, Ir. versicolor, and Ir. virginica.
Source: Base R package. Edgar Anderson's Iris Data.
A dataset with 150 observations and 5 variables 
	Sepal.Length:	a numeric vector, sepal lengths in centimeters 
	Sepal.Width : 	a numeric vector, sepal width in centimeters 
 	Petal.Length:	a numeric vector, petal lengths in centimeters 
	Petal.Width :	a numeric vector, petal width in centimeters 
 	Species     : a Factor with 3 levels, "setosa","versicolor","virginica". 

# pokemon_data.csv
========================
This dataset contains information on all 801 Pokemons from all Seven Generations of Pokemon. The information contained in this dataset include Base Stats, Performance against Other Types, Height, Weight, Classification, Egg Steps, Experience Points, Abilities, etc.
Source: https://www.kaggle.com/rounakbanik/pokemon

A dataset with 801 observations and 16 variables 
	percentage male:  a numeric vector, The percentage of the species that are male. Blank if the Pokemon is genderless.
	type1:	 Factor w/ 18 levels,  The Primary Type of the Pokemon
	type2:  Factor w/ 19 levels, The Secondary Type of the Pokemon
	weight_kg:	 a numeric vector, The Weight of the Pokemon in kilograms
	height_m: a numeric vector,Height of the Pokemon in metres
	generation:  an integer vector, The numbered generation which the Pokemon was first introduced
	classfication:	 a Factor with 588 levels, The Classification of the Pokemon as described by the Sun and Moon Pokedex
	defense:	 a numeric vector, The Base Defense of the Pokemon
	hp:	 a numeric vector, The Base HP of the Pokemon
	attack: a numeric vector,The Base attack of the Pokemon
	special attack:	 a numeric vector,The Base Special Attack of the Pokemon
	special defense:	 a numeric vector,The Base Special defense of the Pokemon
	speed:	 a numeric vector,The Base Speed of the Pokemon
	Is legendary:  a numeric vector, Denotes if the Pokemon is legendary.

# visitors.csv
========================
Randomly created data. Number of persons visited per hour to a shop in a week.
Dataset with 7 observations with 25 variables.
	Day: 	a factor with 7 levels, day names
	1-24:	integer vectors, number of persons visited during that time of the day

# tips.tsv
=============
One waiter recorded information about each tip he received over a period of a few months working in one restaurant. He collected several variables. 
Source: https://rdrr.io/cran/regclass/man/TIPS.html

A data set with 244 observations on the following 8 variables.
	TipPercentage:	a numeric vector, the tip written as a percentage (0-100) of the total bill
	Bill:	a numeric vector, the bill amount (dollars)
	Tip:    a numeric vector, the tip amount (dollars)
	Gender:    a factor with levels Female Male, gender of the payer of the bill
	Smoker:	   a factor with levels No Yes, whether the party included smokers
	Weekday:   a factor with levels Friday Saturday Sunday Thursday, day of the week
	Time:    a factor with levels Day Night, rough time of day
	PartySize:    a numeric vector, number of people in party

# Infant_mortality_rate_UN.csv
===========================
Estimates developed by the UN Inter-agency Group for Child Mortality Estimation ( UNICEF, WHO, World Bank, UN DESA Population Division ) at childmortality.org. Data represents subset of Mortality rates from 63 randomly selected countries during 1960-2010. 
Source: https://data.worldbank.org/indicator/SP.DYN.IMRT.IN

A dataset with 64 observations and 53 variables 
	Country Name:	a factor with 63 levels, Full Country names
	Country Code:	a factor with 63 levels, 3 letter Country Codes
	1960-2010:	numeric vactors, Mortality rate, infant (per 1,000 live births)


# women.tsv
====================

A dataset with 4514 obs. of  3 variables
	Age   : a Factor with 2 levels "adult","child"
	Height: a numeric vector, 5Height in inches
	Weight: a numeric vector, Weight in pound (lb). 

# Zeffa_et_al.xlsx
=========================
Azospirillum brasilense promotes increases in growth and nitrogen use efficiency of maize genotypes.
Source: https://doi.org/10.1371/journal.pone.0215332

Sheet 1 contains 216 observation of 11 variables. 
	Gen	genotypes
	Rep	Replicates
	Azo	A. brasilense treatment
	SDM	Shoot Dry Mass
	RDM	Root Dry Mass
	RSA	Root Surface Area
	RL	Root Length
	IAA	amount of indole-3-acetic acid in mg/gm 
	PRO	Soluble proteins (mg/gm) from 
	PPO	polyphenoloxidase activity in micrMol min-1 mg-1
	PAL	phenylalanine ammonia-lyase activity in micrMol min-1 mg-1

# Ath_RNAseq.final.csv
==========================
Expression data of 92 Arabidopsis thaliana genes in 2 tissues (Leaf and Root) trated with ammonia, nitrate and urea.
Source: https://phytozome.jgi.doe.gov

	ID:  facor of 92 levels, A. thaliana locus ID
	Leaf.ammonia:	a numeric vector, Expression (in FPKM) as estimated in Leaf treated with ammonia.
	Leaf.nitrate:	a numeric vector, Expression (in FPKM) as estimated in Leaf treated with nitrate
	Leaf.urea:	a numeric vector, Expression (in FPKM) as estimated in Leaf treated with urea
	Root.ammonia: a numeric vector, Expression (in FPKM) as estimated in Root treated with ammonia.
	Root.nitrate: a numeric vector, Expression (in FPKM) as estimated in Root treated with nitrate
	Root.urea: a numeric vector, Expression (in FPKM) as estimated in Root treated with urea.

# Gene_desc_summary.csv
============================
Gene descriptions and annotations of 92 genes 
	ID            : a Factor w/ 92 levels, A. thaliana locus ID
	Gene.Defline  : a Factor w/ 27 levels Gene defination 
	Gene.Symbol   : a Factor w/ 44 levels, Gene symbols 
	GeneLength    : an integer vector, Gene length in bp
	Chromosome    : a Factor w/ 5 levels,  
	Location.start: a integer vector
	Location.end  : a integer vector,  

# BLAST_hitTable.csv
=========================
BLASTn tabular output.
954 observations with 12 variables.

	q.seqid	 a factor, query (e.g., gene) sequence id
	sseqid	 a factor, subject (e.g., reference genome) sequence id
	pident	 numeric vector, percentage of identical matches
	length	integer vector, alignment length
	mismatch	integer vector, number of mismatches
	gapopen	 integer vector, number of gap openings
	q.start	 integer vector, start of alignment in query
	q.end	 integer vector, end of alignment in query
	s.start	 integer vector, start of alignment in subject
	s.end	 integer vector, end of alignment in subject
	evalue	 numeric vector, expect value
	bitscore	 numeric vector, bit score



# Get more datasets
=============================
https://github.com/mwaskom/seaborn-data.git
	- https://raw.githubusercontent.com/mwaskom/seaborn-data/master/diamonds.csv



