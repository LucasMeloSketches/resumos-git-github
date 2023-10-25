
# Resumos Git e GitHub

Repositório para armazenar resumos de git e github do curso de versionamento de códigos da [DIO](https://www.dio.me/).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

## 💻 Configuração inicial

| Código | Descrição |
|------|------|
| git config --global user.name "nome de usuario" | muda o nome |
| git config --global user.email email@email.com | muda o email do usuario |
| git config --global init.defaultBranch **main** | muda o nome da branch principal |

## ⌨ Alguns comandos interessantes
| Código | Descrição |
|------|------|
| ls | lista os itens dentro da pasta |
| cat **nome do arquivo** | abre o arquivo em texto |
| cd **nome da pasta** | abre a pasta |
| cd .. | volta uma pasta acima |
| mkdir | cria pasta no local atual |
| git init | inicia versionamento na pasta selecionada |
| git remote add origin **link** | adiciona origem a partir de um repositório remoto na pasta selecionada |
| git status | mostra a branch atual e lista arquivos não rastreados |
| git add **nome do arquivo** | rastreia o arquivo da lista |
| git commit -m"**nome da commit**" | cria um comit com os arquivos novos rastreados |