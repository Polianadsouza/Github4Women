# GitHub Repositories - Módulo 2 | WomakersCode

Este repositório foi criado como parte da atividade prática do **Módulo 2 - Working with GitHub Repositories**, no curso da [WomakersCode](https://www.youtube.com/@WoMakersCode). O objetivo é consolidar os conhecimentos sobre o uso do GitHub, tanto pela interface quanto pela linha de comando.

## ✅ Atividades Realizadas

### 1. 📁 Criação do Repositório
- Repositório criado diretamente pelo GitHub.
- Visibilidade definida como **pública**.
- Incluídos arquivos iniciais:
  - `README.md`
  - `LICENSE` (Licença MIT)

### 2. 📄 Adição de Arquivos

#### 🔹 Via Interface Gráfica
- Upload de arquivos diretamente pela opção `Add file > Upload files`.
- Commit realizado em uma **nova branch**.
- Criação de um **Pull Request**.

#### 🔹 Via Linha de Comando (Git Bash)
- Clonado repositório com `git clone`.
- Criação de nova branch com `git checkout -b`.
- Arquivo criado com `touch`.
- Arquivo adicionado ao repositório com `git add`, `git commit` e `git push`.

## 💻 Comandos Utilizados

```bash
git clone <URL-do-repositório>
cd <nome-da-pasta>
Dir
git checkout -b <nova-branch>
touch <arquivo.txt>
git add .
git commit -m "mensagem do commit"
git push --set-upstream origin <nova-branch>

