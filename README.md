# ProjetoModular

Treino para criar um projeto submodular no git.

Fonte: https://www.atlassian.com/git/tutorials/git-submodule

Aula Alura de microserviços
https://cursos.alura.com.br/course/Microsservicos-pratica-tomada-decisoes/task/96529

# Procedimentos

Fiz os seguintes passos.

Criei os 2 projetos no github

- ProjetoModular
- Agente-df

## Adicionando o submodule ao projeto principal

`git submodule add https://github.com/estevamdf2/agent-df.git`

Como já havia feito outras tentativas com este nome e no "Windows" ele ficou com referencias que não consegui remover então renomeei o subdiretório para `agente`

`git submodule add https://github.com/estevamdf2/agent-df.git agente`

- Resultado do clone do submódulo
![texto](/src/imagens/1-resultado-clone.png "Clonando projeto submodulo")

Em seguida fiz um `git status` para verificar se o submodulo foi carregado com sucesso.
Arquivos visualizados:
 - .gitmodules
 - agente: diretório clonado do projeto submodule

![texto](/src/imagens/2-git-status-verificar-submodulo.png "Git status submodule")

Na fonte de referência está no item **Add git submodule**

- Commitando o submodule

![texto](/src/imagens/3-commit-submodule.png "Submodule commit")

# Visão do projeto

Está e a visão do projeto após os procedimentos.

Acredito que nos ajudara a dar sequência nos estudos.

![texto](/src/imagens/4-visao-modulo.png "visão projeto")