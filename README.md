# Extração de Informações de Notas Fiscais Eletrônicas (XML)

Este repositório contém um script em Python para processar arquivos XML de Notas Fiscais Eletrônicas (NF-e) e extrair informações relevantes como número da nota, empresa emissora, cliente, endereço e peso. Os dados extraídos são organizados em uma tabela e exportados para um arquivo Excel.

---

## 🛠 Funcionalidades

- **Leitura de arquivos XML de NF-e**: Lê arquivos XML localizados na pasta `nfs/`.
- **Extração de dados principais**: Extrai informações como:
  - Número da Nota Fiscal
  - Nome da Empresa Emissora
  - Nome do Cliente
  - Endereço do Cliente
  - Peso da Carga (se disponível)
- **Geração de relatório em Excel**: Organiza os dados extraídos em uma tabela e exporta para um arquivo Excel chamado `NotasFiscais.xlsx`.

---

## 📂 Estrutura do Projeto


