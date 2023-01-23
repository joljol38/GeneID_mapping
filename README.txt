gene_id_mapping file

1) mapping_data

/chromosome
각 chromosome 별로 mapping된 tsv파일

ex. chr1_map_fin.tsv column별
GeneID : Entrez ID
Symbol : Gene Symbol
EnsemblID
HGNCID
MIM Number
UniprotAC : Uniprot Accession Code
UniprotID : Uniprot ID
type_of_gene : gene type
------------------------------------------------------------------------------------

/relation
각 relation 별로 mapping된 tsv파일

ex. child_mapping3.tsv column별
chr# : chromosome number
GeneID : Entrez ID
Symbol : Gene Symbol
EnsemblID
HGNCID
MIM Number
UniprotAC : Uniprot Accession Code
UniprotID : Uniprot ID
------------------------------------------------------------------------------------

all_gene_mapping2.tsv

chr# : chromosome number
GeneID : Entrez ID
Symbol : Gene Symbol
EnsemblID
HGNCID
MIM Number
UniprotAC : Uniprot Accession Code
UniprotID : Uniprot ID
type_of_gene : gene type
------------------------------------------------------------------------------------

feature_result_fin.tsv

chr# : chromosome number
GeneID : Entrez ID
Symbol : Gene Symbol
EnsemblID
HGNCID
MIM Number
UniprotAC : Uniprot Accession Code
UniprotID : Uniprot ID
type_of_gene : gene type
FIELD2~FIELD11 : also gene type
------------------------------------------------------------------------------------

2) website

website를 구현할 때 필요한 모든 파일들

------------------------------------------------------------------------------------

3) data_mapping_percent.xlsx

각 데이터 column별 개수 및 mapping율 계산한 excel파일
------------------------------------------------------------------------------------