# ACADworkshop
**A workshop at ACAD**

#notsure
srun -n 1 --mem 1GB  vsearch --fastx_uniques euks_data/ERR10493277_small-FINAL.fq.gz --fastqout ./ERR10493277_small-FINAL.vs.fq --minseqlength 30 --strand both

#activate conda
'''
conda activate acad-euks_1
'''
#open a new screen called 'robbirulz'
'''
screen -R robbirulz
'''

