1. Check a gene from NCBI database -Tp53 Tumor gene .
2. Download the Gene Sequence as FASTA File 
3. Import the Gene Sequence directly to the Snapgene.
4. Open the FASTA file in the NOTEPAD – Then Copy the Gene Sequence in SnapGene -> Create a New File -> Create.
5. Change the Gene visual Map to Sequence Format
6. Then Select a part(500-600bp) of the sequence or the full Sequence
7. Copy the Sequence and Paste in the CHOPCHOP website.
8. Open Google-> CHOPCHOP-> Click “PASTE TARGET”
9. Paste The copied Sequence from SanpGene . Set required Parameters. 
10. Parameters: -
a.	Target – Paste the sequence  
b.	In – Homo Sapiens (Choose from where the Sample taken) 
c.	Using – CRISPR/Cas-9
d.  For-Activation -> then Go for the “Option” box.
11. Then Check for the Options -> Click On the “Find Target Site”.
a)	Click on Option -> Cas9
b)	sgRNA length Without PAM – 20  
c)	PAM3 – NGG
12. Collection Of Varieties Of Guide RNA + PAM Sequence are listed. ( 23 bp sequence  = 20bp (gRNA)+ 3bp (PAM))
a.	Download - Result Table as .tsv 
b.	Open In EXCEL -> Filter the Best Sequence.
13. Filter the Sequence according to the following Criteria.
a.	GC content % = 40 < GC >= 60
b.	Self-Complementarity = 0
c.	MM0 = 1
d.	MM1 = 0
e.	MM2 = 0
f.	MM3 = 1
g.	Efficiency = > 50 = Good, > 70 = Best 
14. Now we have our three best Guide RNA sequence to visualize in SnapGene->
a.	Copy one of the Sequence
b.	Then put in the “Find DNA sequence”
15. Automatically, the given Sequence was highlighted.	
16. Now, “Add Features” to the Sequences like the direction, Colour,Annotation(gRNA,PAM).
17. Now, This is the gRNA sequence and PAM for our Target Gene.
18. Above we have got for the CRISPR Cas9 but we can also do this process for Cas12 also. This process is quite similar as Cas9.
a.	Take the gene -> download FASTA-> copy the sequence /open in  SnapGene.
b.	Now take the part of the sequence -> paste in CHOPCHOP.
c.	Select the option ->using- Cas12/CasX.
d.	Set the criteria ->cpf1= sequence-20, 5’PAM= TTTN
e.	We will got some 23bp Sequences.
f.	Export to the Excel ->Filter the sequence->copy the sequence -> paste in the “Find the DNA”.
g.	The sequence will be highlighted-> add Features .
