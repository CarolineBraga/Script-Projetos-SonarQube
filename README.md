# Script Projetos SonarQube

## Conteúdo
- [Script Projetos SonarQube](#script-projetos-sonarqube)
  - [Conteúdo](#conteúdo)
  - [Informações gerais](#informações-gerais)
  - [Tecnologias utilizadas](#tecnologias-utilizadas)
  - [Uso](#uso)

## Descrição
O projeto consiste numa automação que extrai do GitLab SaaS todos os repositórios existentes num determinado grupo, verifica quais desses repositórios são analisados pelo SonarQube e exporta esses dados para uma planilha.

Observação: Essa pipeline foi construída para GitLab CI.

## Tecnologias utilizadas
### Linguagens
- Python 3
- YAML
### Bibliotecas
- gitlab
- json
- logging
- openpyxl
- requests
- sys

## Uso
Executar a pipeline do repositório.