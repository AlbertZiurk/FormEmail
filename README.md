# 📧 FormEmail

## 🛠️ Ferramentas Utilizadas
- **HTML**
- **CSS**
- **[Editor de README](https://readme.so/pt)** 
- **API [FormSubmit](https://formsubmit.co/)** – Utilizada para envio de formulários sem necessidade de backend.

---

## 🚀 Passos da Criação do Repositório

1. **Abrir o Git Bash na pasta do projeto**
2. **Configurar o nome de usuário:**
   ```bash
   git config --global user.name "Alberto_Senai"
3. **Configurar o email de usuário:**
   ```bash
   git config --global user.email "alberto.z.araujo@aluno.senai.br"
4. **Definir main como branch principal padrão:**
   ```bash
    git config --global init.defaultBranch main
5. **Inicializar o repositório e conectar ao remoto:**   
   ```bash
    git init
    git remote add origin https://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@github.com/AlbertZiurk/FormEmail.git
   ```
    | Obs.: O token utilizado só é válido para o administrador. Verifique a [documentação](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) para mais informações.

6. **Primeiro commit::**    
    ```bash
    git add .
    git commit -m "Add: Implementando estrutura de pastas, adicionando páginas thanks.html e form2.html, estilizando componentes com style.css e thanks.css"
    git push -u origin main
7. **Refatoração Posterior**
    ```bash
    git add .
    git commit -m "refact: Alterando nome de form2.html para form.html e alterando nome de thankfull.html para thanks.html, incluindo alterações de nomes nos caminhos dos arquivos"
    git push origin main

## 📥 Clonando o Respositório

- **Clonando um repositório existente do GitHub para seu computador:**
    ```bash
    git clone https://github.com/AlbertZiurk/FormEmail.git
    cd FormEmail
    git init

## 🔄 Publicando Alterações Locais

- **Após clonar e fazer alterações no seu computador:**
    ```bash
    git add .
    git commit -m "Descreva sua alteração"
    git push origin main

## 📄 Criando e Publicando .gitignore

- **Criando um arquivo .gitignore personalizado:**
    1. Criar o arquivo .gitignore na raiz do projeto.
    2. Adicionar os arquivos ou pastas que devem ser ignorados.
    3. Publicar no GitHub:
    ```bash
    git add .gitignore
    git commit -m "Add: Criando arquivo .gitignore com regras específicas"
    git push origin main
