![alt text](https://github.com/akiid777/Stage1_Team_Tesla/blob/master/WhatsApp%20Image%202020-08-14%20at%2011.52.18%20PM.jpeg)

# :heart: Welcome to Team_Tesla_Genomics Project :heart:
## This project is part of Hackbio2020 internship.

**We worked on Red Queen Hypothesis on the basis of host-pathogen interaction to see whehter the ACE2 enzyme in bats are under positive selection and giving some advantages from being infected by the SARS-COV2 virus.** 

## Step :one: 
> Fetching the codon sequence from the NCBI nucleotide website.
## Step :two: 
> Blastn the sequence using the Blast webtool.
## Step :three:  
> Selected specific ortholog sequences of the protein of thirteen different bats species.
## Step :four: 
> Using the Linux server, aligned the collected sequence using multiple alignment software, clustalw.
## Step :five: 
> Developed a phylogenetic tree using dnaml tool from PhyLip software in the Linux server.
## Step :six: 
> Screened the alignment file and the phylogenetic tree file in the PAML software.

**Through history, war has shaped the world and marked it with borders and divided it by countries. The scar of humans’ war is today’s world of continents and countries. Battlefields are everywhere, and war is so inevitable that the presence of such battles can be found at the molecular level inside the living organisms.** 

**Here,  we  looked  at  the  Red  Queenhypothesis  on  the  perspective  of  host-pathogen  arms  race between  bats  and  viruses.  We  have  chosen  the  ACE2  protein  as  this  is  the  receptor  for  SARS-COV2 virus to enter the hosts’ cells and replicate and spread form one host to another.In the figure below, we can see the sites that is under positive selection as found by the analysis of codeml of PAML. The starred sites showing that the sites are under significance.**

![alt text](https://github.com/akiid777/Stage1_Team_Tesla/blob/master/PMAL%20result.jpg)

### Fig.1: PAML result showing sites with positive selection.

The figure below is the phylogenetic tree constructed using dnaml tool of PhyLip software. The tree showing how *R. ferrumequinum* species of the bat diverge from other species based on the gene, ACE2. This is showing the rise of the change in the codon due to the selection pressure posed by the COVID-19 virus.

![alt text](https://github.com/akiid777/Stage1_Team_Tesla/blob/master/Phylogenetic_tree.png)

### Fig.2: Phylogenetic tree visualized by iTOL and constructed by dnaml tool.

## **Tools used in our project**💻
- Biopython : for sequence

- Clustlaw: for multiple alignment

- dnaml tool: for phylogenetic tree construction

- iTOL: For phylogenetic tree visualisation


### **Installation of Biopython**
![alt text](https://upload.wikimedia.org/wikipedia/commons/1/13/Biopython_logo.png)

**1-Check which python version installed on your OS**
 ```

> $ python --version

```
**2-a- To install pip3**
```
$ Curl https://bootstrap.pypa.io/get-pip.py -Oget-pip3.py

```

**b- To upgrade pip to version 20.2.2 (latest version as 14.08.2020)**
```
Python3.8 -m pip install —upgrade pip
```
**3- To  install Biopython**
```
Pip3 install biopython
```
