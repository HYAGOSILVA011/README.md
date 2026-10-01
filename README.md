# Guia Definitivo: Ciclo de Vida de um Projeto no GitHub

Documento criado para consolidar e documentar a compreensão prática sobre o fluxo de trabalho, documentação e manutenção de projetos no GitHub.

---

## 🚀 Sessão 1: O Passo a Passo da Criação e Envio

Tirar um projeto da máquina local e publicá-lo na nuvem é o ponto de partida de qualquer desenvolvimento moderno. Abaixo está o tutorial detalhado narrando o caminho completo desse processo.

### 1. O Início: Criando o Repositório no GitHub
Para criar o local onde o projeto residirá na nuvem:
1. Acesse o [GitHub](https://github.com) e clique no botão **"New"** (Novo) na aba de repositórios.
2. Defina o **Nome do Repositório** (de preferência sem espaços e usando hífens, ex: `meu-projeto-guiado`).
3. Escolha a visibilidade:
   * **Público:** visível para qualquer pessoa na internet.
   * **Privado:** acessível apenas por você e colaboradores autorizados.
4. Para evitar conflitos no primeiro vínculo local, crie o repositório **totalmente vazio** (sem marcar a opção de adicionar automaticamente `README.md`, `.gitignore` ou licença).

---

### 2. A Conexão: Vinculando a Pasta Local ao Repositório Remoto
Com o repositório remoto criado, é hora de associar a pasta no computador local ao servidor do GitHub:

1. Abra o terminal de comando (ou o Git Bash) na pasta do seu projeto local.
2. Inicialize o controle de versão Git na pasta executando:
   ```bash
   git init