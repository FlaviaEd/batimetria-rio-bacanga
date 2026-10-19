# Levantamento batimétrico do Rio Bacanga – São Luís, Maranhão

Este repositório reúne códigos desenvolvidos em linguagem Python utilizados nas etapas de extração, organização, tratamento e visualização inicial de dados batimétricos obtidos durante o levantamento realizado no Rio Bacanga, em São Luís, Maranhão.

Os procedimentos integram uma pesquisa de mestrado desenvolvida no Programa de Pós-Graduação em Ciência e Tecnologia Ambiental da Universidade Federal do Maranhão (UFMA), com utilização de veículo de superfície não tripulado equipado com sistema de aquisição batimétrica monofeixe.

## Arquivos disponíveis

**01_Extracao_Dados.ipynb**

Notebook destinado à leitura e extração dos registros batimétricos, organização das informações e aplicação da compensação de 0,20 m correspondente à imersão do transdutor.

**02_Visualizacao_Inicial.ipynb**

Notebook utilizado na exploração e visualização espacial inicial dos dados batimétricos, incluindo procedimentos experimentais de interpolação e elaboração de mapas.

## Processamento espacial

As etapas posteriores de interpolação pelos métodos TIN e IDW e a elaboração dos produtos cartográficos finais foram realizadas no software QGIS. Os respectivos procedimentos não estão integralmente implementados nos notebooks disponibilizados neste repositório.

## Finalidade

A disponibilização dos códigos busca documentar parte dos procedimentos computacionais utilizados na pesquisa e contribuir para a transparência e a reprodutibilidade do tratamento inicial dos dados.
