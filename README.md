# Documentação de RPA: TOMECONTAPE
 
## Visão Geral

Este documento oferece uma visão geral do script de Automação de Processos Robóticos (RPA) projetado para extrair dados do site TOMECONTA e armazená-los em um banco de dados MongoDB. O script utiliza a biblioteca Selenium para interação com a web, o PyAutoGUI para automação de interface de usuário e o pymongo para operações com o MongoDB.

O RPA irá buscar dados referentes a CNPJ de empresas Fornecedoras vinculadas ao Estado de Pernambuco

Link do site: <https://sistemas.tce.pe.gov.br/tomeconta/TelaInicial!principal>


## Índice 📖
1. *Introdução*
    * Propósito
    * Escopo
    * Público-alvo
  
2. *Estrutura do Script*
    * Bibliotecas e Importações
    * Configurações e Definiçõe
    * Funções de Extração de Dados
    * Função Principal de Extração
    * Loop Principal e Execução
  
3. *Funcionalidade do Script*
    * Pesquisa e Entrada de CNPJ
    * Navegação pelas Seções do Site
    * Extração de Dados e Scraping
    * Tratamento de Erros
  
   
4. *Dependências*
    * Selenium
    * PyAutoGUI
    * Pymongo
    * Outras bibliotecas relevantes
  
5. *Uso*
    * Pré-requisitos
    * Instalação das Dependências
    * Execução do Script
    * Saída

6. *Manutenção e Considerações*
    * Lidando com Mudanças no Site
    * Tratamento de Erros e Registros
    * Escalabilidade

7. *Conclusão*
   * Resumo da Funcionalidade do Script
   * Agradecimentos
  

## Introdução
Propósito
O propósito deste script de RPA é automatizar o processo de coleta de dados de um site específico e armazená-los em um banco de dados MongoDB. O script visa agilizar a obtenção de dados para análise e geração de relatórios.

Escopo
O script concentra-se na raspagem de dados relacionados a várias categorias usando a biblioteca Selenium. Ele suporta a extração de informações de diferentes seções do site, como EmpenhosMunicipais, Licitacoes, Contrato, etc.

Público-alvo
Esta documentação destina-se a desenvolvedores, analistas de dados e indivíduos envolvidos na manutenção ou uso do script de RPA para extração e armazenamento de dados.



