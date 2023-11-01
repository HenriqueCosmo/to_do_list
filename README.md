# Readme do Projeto Todo-List

Este projeto é uma simples aplicação de lista de tarefas (Todo List) que permite ao usuário adicionar, editar, marcar como concluída e excluir tarefas. A aplicação foi construída usando HTML, CSS e JavaScript. Abaixo estão as principais funcionalidades do projeto e como ele funciona:

## Funcionalidades

1. **Adicionar Tarefa:** Você pode adicionar novas tarefas à lista preenchendo o campo de entrada e clicando no botão "Adicionar" ou pressionando Enter. A tarefa será exibida na lista de tarefas pendentes.

2. **Editar Tarefa:** Cada tarefa na lista possui um botão de edição que permite modificar o texto da tarefa. Ao clicar no ícone de edição, o texto da tarefa selecionada é copiado para o campo de edição, onde você pode fazer as alterações desejadas. Após editar a tarefa, pressione o botão "Editar" para salvar as alterações.

3. **Marcar como Concluída:** Cada tarefa tem um botão de conclusão que permite marcá-la como concluída. Clique no ícone de marca de verificação para indicar que a tarefa foi finalizada. A tarefa concluída terá sua aparência modificada.

4. **Excluir Tarefa:** Você pode excluir uma tarefa da lista clicando no ícone de exclusão (X). A tarefa será removida permanentemente da lista.

## Uso

1. **Adicionar Tarefa:**

   - Digite a descrição da tarefa no campo de entrada.
   - Clique no botão "Adicionar" ou pressione Enter para adicionar a tarefa à lista.

2. **Editar Tarefa:**

   - Clique no ícone de edição (ícone de lápis) ao lado da tarefa que deseja editar.
   - O texto da tarefa será copiado para o campo de edição.
   - Faça as alterações desejadas no texto da tarefa.
   - Clique no botão "Editar" para salvar as alterações.

3. **Marcar como Concluída:**

   - Clique no ícone de marca de verificação (ícone de check) ao lado da tarefa para marcá-la como concluída.
   - A tarefa concluída terá sua aparência modificada, indicando que foi finalizada.

4. **Excluir Tarefa:**

   - Clique no ícone de exclusão (X) ao lado da tarefa que deseja remover da lista.
   - A tarefa será excluída permanentemente.

## Estrutura do Código

O código JavaScript é responsável por manipular as interações do usuário e controlar as tarefas na lista. Os elementos HTML são selecionados usando `document.querySelector` para permitir a interação com o DOM.

A lógica do projeto é dividida em funções que realizam as principais ações, como adicionar, editar, marcar como concluída e excluir tarefas. Event listeners são adicionados aos elementos para responder a eventos do usuário, como clique e envio de formulário.

Este projeto é uma demonstração simples de como criar uma aplicação de lista de tarefas e pode ser estendido com recursos adicionais, como armazenamento local para salvar tarefas, ordenação por prioridade, categorização de tarefas e muito mais. Sinta-se à vontade para personalizar e expandir o projeto de acordo com suas necessidades.
