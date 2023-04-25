# Melhorias propostas

- Criar um arquivo .gitignore, para evitar de subir para o repositório arquivos desnecessários, mais detalhes no artigo (https://www.atlassian.com/git/tutorials/saving-changes/gitignore)

- Criar o arquivo requirements.txt, esse arquivo é usado para "congelar" as versões das bibliotecas usadas no projeto, evitando assim que na hora de instalar a mesma seja usada uma versão que não é compatível com o projeto.
     para criar o arquivo, com o ambiente virtual usado usa-se o comando: 

     ```bash
     python -m pip freeze > requirements.txt
     ```

     Mais detalhes no artigo (https://jtemporal.com/requirements-txt/)

- Criar um arquivo README.md com uma pequena descrição do projeto.