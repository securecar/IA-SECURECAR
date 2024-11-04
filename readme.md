Dentro desse projeto:

`main.py`: executa a API FLASK*
`ia-sc.py` : gera o modelo e lê o dataset `problemas_combinados_2.csv`
`criar-pdf` : arquivo usado para gerar exportar função de gerar pdf de acordo com id_conserto
`modelo_causas_aprimorado.pkl` : modelo de ia pickle baixado
`requirements.txt` : dependências do projeto

*Nota: O main.py também tem funções para o desenvolvimento de front-end, por isso carrega libs como `oracledb` para acesso ao bando de dados Oracle.
