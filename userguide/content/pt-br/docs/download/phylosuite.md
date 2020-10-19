---
title: "Produção de Alinhamentos, Teste de Modelos Evolutivos, Concatenação de Sequências, Análises Filogenéticas de Máxima Verossimilhança e Inferência Bayesiana: PhyloSuite"
linkTitle: "Produção de Alinhamentos, Teste de Modelos Evolutivos, Concatenação de Sequências, Análises Filogenéticas de Máxima Verossimilhança e Inferência Bayesiana: PhyloSuite"
weight: 3
description: >
  Como instalar o software multi-uso para boa parte das análises
---
<div align="justify">
O PhyloSuite é uma plataforma multifunctional destinada ao processamento de sequências de DNA e proteínas, e preparação para diferentes análises evolutivas e filogenéticas. Seu principal objetivo é fornecer uma interface gráfica intuitiva que permite a centralização de diversos softwares, facilitando a automação e gerenciamento de diferentes tipos de análises.
<br><br>
Ao utilizar o PhyloSuite em suas publicações, inclua a seguinte citação:
</div>

```
Zhang, D, Gao F, Jakovlić I, Zou H, Zhang J, Li WX, and Wang GT, 2020. PhyloSuite: An integrated and scalable desktop platform for streamlined molecular sequence data management and evolutionary phylogenetics studies. Molecular Ecology Resources 20, 348–355. DOI: 10.1111/1755-0998.13096.
```

<div align="justify">
Como o PhyloSuite centraliza diversos softwares e projetos produzidos por terceiros, além de citar o PhyloSuite, é necessário citar os responsáveis pelas ferramentas individuais, de acordo com as ferramentas que você utilizar em suas publicações:
</div>

<table>
  <tr>
    <th><strong>Software</strong></th>
	<th><strong>Referência</strong></th>
  <tr>
    <td>MAFFT</td>
    <td>Katoh K, Standley DM, 2013. MAFFT multiple sequence alignment software version 7: improvements in performance and usability. <b>Molecular Biology and Evolution</b> 30, 772-780. DOI: <a href="https://doi.org/10.1093/molbev/mst010">10.1093/molbev/mst010</a></td>
  </tr> 
  <tr>
    <td>PartitionFinder2</td>
    <td>Lanfear R, Frandsen PB, Wright AM, Senfeld T, Calcott B, 2017. PartitionFinder 2: new methods for selecting partitioned models of evolution for molecular and morphological phylogenetic analyses. <b>Molecular Biology and Evolution</b> 34, 772-773. DOI: <a href="https://doi.org/10.1093/molbev/msw260">10.1093/molbev/msw260</a></td>
  <tr>
    <td>Gblocks</td>
    <td>Talavera G, Castresana J, 2007. Improvement of phylogenies after removing divergent and ambiguously aligned blocks from protein sequence alignments. <b>Systematic Biology</b> 56, 564-577. DOI: <a href="https://doi.org/10.1080/10635150701472164">10.1080/10635150701472164</a></td>
  </tr>
  <tr>
    <td>IQ-Tree</td>
    <td>Nguyen LT, Schmidt HA, von Haeseler A, Minh BQ, 2015. IQ-TREE: a fast and effective stochastic algorithm for estimating maximum-likelihood phylogenies. <b>Molecular Biology and Evolution</b> 32, 268-274. DOI: <a href="https://doi.org/10.1093/molbev/msu300">10.1093/molbev/msu300</a></td>
  </tr>
  <tr>
    <td>MrBayes</td>
    <td>Ronquist F, Teslenko M, van der Mark P, Ayres DL, Darling A, Höhna S, Larget B, Liu L, Suchard MA, Huelsenbeck JP, 2012. MrBayes 3.2: efficient Bayesian phylogenetic inference and model choice across a large model space. <b>Systematic Biology</b> 61, 539-542. DOI: <a href="https://doi.org/10.1093/sysbio/sys029"> 10.1093/sysbio/sys029</a></td>
  </tr>
  <tr>
    <td>MACSE</td>
    <td>Ranwez V, Douzery EJP, Cambon C, Chantret N, Delsuc F, 2018. MACSE v2: Toolkit for the alignment of coding sequences accounting for frameshifts and stop codons. <b>Molecular Biology and Evolution</b> 35, 2582-2584. DOI: <a href="https://doi.org/10.1093/molbev/msy159">10.1093/molbev/msy159</a></td>
  </tr>
  <tr>
    <td>trimAL</td>
    <td>Capella-Gutierrez S, Silla-Martinez JM, Gabaldon T, 2009. trimAl: a tool for automated alignment trimming in large-scale phylogenetic analyses. <b>Bioinformatics</b> 25, 1972-1973. DOI: <a href="https://doi.org/10.1093/bioinformatics/btp348">10.1093/bioinformatics/btp348</a></td>
  </tr>    
</table> 
  
## Download

<div align="justify">
Clique <a href="https://github.com/dongzhang0725/PhyloSuite/releases/tag/1.2.2">aqui</a> para acessar a versão mais recente do PhyloSuite, e escolha o arquivo mais adequado ao seu sistema operacional. Sugerimos o download do instalador (“PhyloSuite_v1.2.2_win_setup.exe”), mas também há possibilidade de baixar a pasta do software para utilizá-lo de forma portátil.
</div>

## Instalação

<div align="justify">
Após realizar o download do arquivo de instalação, inicie a instalação do PhyloSuite com um clique duplo sobre o arquivo. Em seguida, siga as instruções do Instalador, que envolvem fechar outros softwares que estejam abertos no momento de instalação, ler com atenção a Licença de Uso do PhyloSuite e aceitar os termos clicando em “I accept the agreement”, escolher a local de preferência para a instalação (por padrão, o PhyloSuite sugere a instalação dentro da pasta “C:\Users\seu_user\AppData\Roaming ”, mas outra pasta pode ser escolhida sem problemas). O instalador também perguntará se é necessário criar um atalho na Área de Trabalho.
<br><br>
Em seguida, basta prosseguir e esperar que a instalação seja concluída. Se a instalação foi realizada corretamente, o PhyloSuite já pode ser utilizado, seja clicando em seu ícone na Área de Trabalho ou Barra de Ferramentas. Apenas realizaremos mais algumas configurações pós-instalação.
<br><br>
Ao abrir o PhyloSuite, a seguinte notificação aparecerá, perguntando sobre a pasta que deverá ser escolhida como ambiente de trabalho. Nesta pasta, o PhyloSuite irá salvar os arquivos que forem produzidos durante as análises. Recomendamos não selecionar nenhuma pasta como padrão, e sempre escolher a pasta ao inicializar o programa. Dessa forma, é sempre possível criar novas pastas para as análises e facilitar a organização. A pasta de interesse pode ser escolhida clicando no ícone de pasta em amarelo.
<br><br>
<center>
<img src="https://raw.githubusercontent.com/desirrepetters/cursodefilogenia.ufpr/master/userguide/content/pt-br/docs/download/img/phylosuite/phylosuite_1.png" alt="Janela de Seleção da Pasta de Ambiente de Trabalho do PhyloSuite" align="center">
</center>
<br><br>