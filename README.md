# Git-Flow.

### O Git Flow é um modelo de desenvolvimento que utiliza branches para gerenciar os ambientes de produção, teste e desenvolvimento. O fluxo de trabalho é organizado da seguinte forma:
### Branch Master: Esta é a branch que contém o código de produção.
### Branch Develop: Esta branch é o ambiente de desenvolvimento. A partir dela, serão criadas branches para os projetos, seja para correções (Fix) ou para melhorias (Feat).
### Padrão de Nomenclatura: As branches devem seguir um padrão de nomenclatura, por exemplo, feat/2107-add-price-filter (prefixo Feat ou Fix / numeração do card da tarefa – nome da branch, normalmente em inglês). O mesmo padrão se aplica para as branches de correção (Fix), trocando apenas o prefixo.
### Realização de Tarefas: Após a criação da branch específica e a realização da tarefa, o desenvolvedor fará o commit, push e o Pull Request para a branch DEVELOP. Ao concluir esta etapa, o desenvolvedor retornará para a branch DEVELOP com o comando “git checkout develop” e atualizará o código com a nova alteração, utilizando “git pull origin develop”. Dessa forma, o projeto estará em conformidade com o padrão de desenvolvimento e entrega do Git Flow.

