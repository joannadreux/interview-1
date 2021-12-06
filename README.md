# interview
interview questions

Write a function that parses sequences from this fastq input as a string input and returns the 3 most frequently occurring sequences, along with the number of times they appeared.

Input
@3TSEQ:113:000000000-JRRHL:1:1101:10184:1937 1:N:0:1
AGGATTCTATTTCGTGGGAGAACCCGGATCCCCCCGTGCAGACGATAGATCGGA
+
--@-AFEG9EEGDAF<7:,8--CCC+++B@FF<6@:B6@,,,;++8,,,<C<,,,
@3TSEQ:115:000000000-JRRHL:1:1201:15611:1939 1:N:0:1
TATCGGTAGCAAGCACATCACCTTGAATGCCACCGGATGCTGCTTTTTTACCGCCT
+
A-B@-+B-66,,,9,6,CF,CCCC,,,<,;C,;6+++,+;,,6C6,;C+,C,,@@@,
@3TSEQ:113:000000000-JRRHL:1:1101:10184:1937 1:N:0:1
AGGATTCTATTTCGTGGGAGAACCCGGATCCTGCCGTGCAGACGATAGATCGGA
+
A-@-AFEG9EEGDAF<7:,8--CCC+++B@FF<6@:B6@,,,;++8,,,<C<,,,
@3TSEQ:113:000000000-JRRHL:1:1101:15576:1953 1:N:0:1
TTAATCCACTGTTCACCATAAACGTGACGATGAGGGACATAAAAAGTAAAAATGT
+
BC9-BCC9EE<EEC9C@@<,--C;C,,:,-8,,,,,,:,,,,,,,8C,6,,,;;C
@3TSEQ:113:000000000-JRRHL:1:1101:1018:1937 1:N:0:1
AGGATTCTATTTCGTGGGAGAACCCGGATCCCCCCGTGCAGACGATAGATCGGA
+
--@-AFEG9EEGDAF<7:,8--CGC+++B@FF<6@:B6@,,,;++8,,,<C<,,,
@3TSEQ:113:000000000-JRRHL:1:1101:15611:1959 1:N:0:1
TATCGGTAGCAAGCACATCACCTTGAATGCCACCGGATGCTGCTTTTTTACCGCCT
+
A<B@-+B-66,,,9,6,CF,CCCC,,,<,;C,;6+++,+;,,6C6,;C+,C,,@@@,
@3TSEQ:113:000000000-JRRHL:1:1101:15248:1956 1:N:0:1
CTTACTGGATTTCGATGGAGAACCCGGATCCTGCCGTGGCAACTGTAGATCGGAAGA
+
<CC9BE<-,CEFA,,C,,,6--CEF7++B@EE<<<:@+6@,,9CC@,,,CF,,7,+,,
@3TSEQ:113:000000000-JRRHL:1:1101:10852:1959 1:N:0:1
TCAACACGCATTGCGTCTAGCGCCACCATGAAGACCATCATCGCACTGTCATACAT
+
BB99@-@-@+BC,@,@@C8,C+@@+8C,@--,,,;;,CE,C@,6,@@,CC,C,C<E
@3TSEQ:113:000000001-JRRHL:1:1101:1511:19569 1:N:0:1
TATCGGTAGCAAGCACATCACCTTGAATGCCACCGGATGCTGCTTTTTTACCGCCT
+
A-B@-+B-66,,,9,6,CF,CCCC,,,<,;C,;6+++,+;,,6C6,;C+,C,,@@@,
@3TSEQ:113:000000000-JRRHL:1:1101:15611:1959 1:N:0:1
TATCGGTAGCAAGCACATCACCTTGAAGCTANCACCGGATGCTGCTTTTTTACCGCCT
+
A-B@-+B-66,,,9,6,CF,CCCC,,,<,;C,;6+++,+;,,6C6,;C+,C,,@@@,,
@3TSEQ:113:000000000-JRRHL:1:1101:15576:1953 1:N:0:1
TTAATCCACTGTTCATTTTAAACGTGACGATGAGGGACATAAAAAGTAAAAATGT
+
BC9-BCC9EE<EEC9C@@<,--C;C,,:,-8,,,,,,:,,,,,,,8C,6,,,;;C
@3TSEQ:113:000000000-JRRHL:1:1101:15576:1953 1:N:0:1
TTAATCCACTGTTCACCATAAACGCCCCGATGAGGGACATAAAAAGTAAAAATGT
+
BC9-BCC9EE<EEC9C@@<,--C;C,,:,-8,,,,,,:,,,,,,,8C,6,,,;;C
@3TSEQ:113:000000000-JRRHL:1:1101:10852:1959 1:N:0:1
TTAATCCACTGTTCACCATAAACGTGACGATGAGGGACATAAAAAGTAAAAATGT
+
BB99@-@-@+BC,@,@@C8,C+@@+8C,@--,,,;;,CE,C@,6,@@,CC,C,C<E



See the attached link to enter a virtual environment and answer the listed question(s): 
# # # # # Copy and paste this below into your python coding environment
# # # # # Q1 - write a function that finds the reverse complement of input DNA

Input: A G A A



# # # # # Q2 - Using the data below, provide the following:
sort a combined table by activity (highest to lowest)
Get the average activity for each target
For each patient for which a date is listed, get the total number of visits on different dates

# # # # # You are free to use any package or approach you feel is best, but please pay attention to efficiency and comprehensibility   

Input
header_A=['acc','date','patient','target','activity']
# Each list below is a column 
A1=['T789','T790','T791','T792','T793','T794','T794','T796','T797','T798']
A2=['20200101','20200101','20200101','20200201','20200201','20201102','20201102','20201102','20201102','20201102']
A3=['PAT005','PAT009','PAT017','PAT024','PAT024','PAT024','','','PAT030','PAT030']
A4=['X','X','X','Y','Y','Y','Y','Y','Z','Z']
A5=[0.15000,0.05000,0.89000,0.00100,0.00045,0.00150,0.00095,0.0855,0.57460,0.80564]
header_B=['acc','date','patient','target','activity','qual']
B1=['T799','T800','T801','T802','T803','T804','T805']
B2=['20210101','20210102','20210101','20210102']
B3=['PAT024','PAT031','PAT031','PAT032','PAT035','PAT042','PAT051']
B4=['AA','AB','X','X','Y','AC','AD']
B5=[0.15880,0.25459,0.45567,1.30564,0.05648,0.13452,0.04351]
B6=[2,3,4,4,2,1,1]




Write a function that takes in a Binary Search Tree (BST) and a positive integer k and returns the kth largest integer contained in the BST. Assume that there will only be integer values in the BST and that k is less or equal to the number of nodes in the tree. Also for the purpose of this question, duplicate integers will be treated as distinct values (ie. the second largest value in a BST containing values {5, 7, 7} will be 7 and not 5).
Ex. BST 

You are given three inputs, all of which are instances of an OrgChart class that have a directReports property pointing to their direct reports. The first input is the top manager in an organizational chart (i.e., the only instance that isn’t anybody else’s direct report), and the other two inputs are reports in the organizational chart. The two reports are guaranteed to be distinct.


![alt text](https://github.com/3TBiosciences/interview/blob/main/binarysearchtree.png?raw=true)

Write a function that returns the lowest common manager to the two reports.
```
def getLowestCommonManager(topManager, reportOne, reportTwo):
    # Write your code here.
    pass
```

# This is an input class. Do not edit.
```
class OrgChart:
    def __init__(self, name):
        self.name = name
        self.directReports = []
```
