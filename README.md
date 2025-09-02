# Meu Primeiro Pipeline de CI com GitHub Actions

Este projeto demonstra como criar um workflow simples de Integração Contínua (CI) utilizando GitHub Actions.

## Objetivo
Criar um pipeline que é executado automaticamente sempre que há um push para a branch `main`, exceto quando o commit altera apenas o arquivo `README.md`.

## Estrutura do Workflow
O arquivo de workflow está localizado em `.github/workflows/primeiro-workflow.yml` e realiza as seguintes tarefas:

- **Exibe RA e Nome:** Imprime uma mensagem personalizada no console.
- **Mostra o diretório de trabalho:** Executa o comando `pwd` para mostrar o diretório atual.
- **Mostra o nome do repositório:** Utiliza a variável `${{ github.repository }}` para exibir o nome do repositório.

## Como funciona
1. O workflow é acionado por pushs na branch `main`.
2. Ignora commits que alteram apenas o `README.md`.
3. Executa os passos definidos para demonstrar o ambiente de execução do GitHub Actions.

## Como visualizar
Após enviar o workflow para o GitHub, acesse a aba **Actions** do repositório para acompanhar a execução e visualizar os logs de cada etapa.

---

> Este projeto é parte do exercício de aula sobre CI pipelines com GitHub Actions.
