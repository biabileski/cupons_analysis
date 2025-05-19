# Cupons Analysis

Este repositório contém todos os materiais relacionados ao projeto **Cupons Analysis**, incluindo notebooks, relatórios e visualizações interativas.

## 📘 Conteúdo do Repositório

- 📓 **Notebook Databricks** – Análise interativa de dados diretamente na plataforma Databricks.  
- 📄 **Relatório em PDF** – Apresentação com os principais resultados e conclusões do projeto.  
- 💻 **Notebook `.ipynb`** – Versão local do notebook para execução em ambientes Jupyter ou compatíveis.

## 🔗 Acesso ao Notebook no Databricks

Você pode visualizar o notebook diretamente no Databricks clicando no link abaixo:

👉 [**Abrir notebook no Databricks**](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1160620042231411/4374738631172771/7203037088294615/latest.html)

> ⚠️ **Importante:** Certifique-se de estar logado na sua conta Databricks ou que o link esteja com permissões públicas para garantir o acesso.

## ⚙️ Sobre o Cluster do Databricks

Para executar o notebook no Databricks, é necessário que um **cluster esteja ativo**. O cluster é responsável por fornecer os recursos computacionais (memória e CPU) para processar os dados e rodar o código.

### 🧱 Configuração do Cluster

Recomenda-se utilizar um cluster com a seguinte configuração mínima:

- **Tipo de Cluster:** Standard
- **Versão do Runtime:** 15.4 LTS (Scala 2.12, Spark 3.5.0)

> ⚠️ **Importante:** Certifique-se de que o cluster esteja **iniciado** antes de tentar executar qualquer célula do notebook.

### 🚀 Executando o Notebook

1. Acesse o [notebook no Databricks](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1160620042231411/4374738631172771/7203037088294615/latest.html).
2. Verifique se há um cluster disponível.
3. Clique em **Attach to** e selecione o cluster.
4. Execute as células normalmente (Shift + Enter).

Se o notebook estiver configurado com dependências específicas (como bibliotecas externas), elas devem ser instaladas no ambiente do cluster. Verifique o início do notebook para instruções adicionais.

## 📄 Relatório PDF

O relatório com os resultados está disponível neste repositório:

📁 `relatorio.pdf`

## 📄 Como abrir um arquivo PDF neste repositório

Se este repositório contém arquivos PDF e você deseja visualizá-los, siga uma das opções abaixo:

### 🔹 Opção 1: Visualizar diretamente no GitHub

1. Navegue até o PDF na interface web do GitHub.  
2. Clique no nome do arquivo `.pdf`.  
3. O GitHub exibirá o conteúdo diretamente no navegador (sem necessidade de download).

### 🔹 Opção 2: Clonar o repositório e abrir localmente

1. Clone este repositório para sua máquina:

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git

2. Navegue até o diretório do repositório:

    ```bash
   cd nome-do-repositorio

3. Abra o arquivo PDF com seu visualizador padrão:

    *Linux*:
    ```bash
    xdg-open nome-do-arquivo.pdf
    ```
    *macOS*:
    ```bash
    xopen nome-do-arquivo.pdf
    ```

    *Windows (Prompt de Comando)*:
    ```bash
    start nome-do-arquivo.pdf
    ```

💡 **Dica:** Certifique-se de ter um leitor de PDF instalado no seu sistema.
