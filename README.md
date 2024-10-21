# Generic toDo
Gerenciador de tarefas genérico para a aplicação das principais funcionalidade do Vue.js.

## Histórias de Usuário

1. #### Adicionar Tarefas
    + Como um usuário, quero poder adicionar novas tarefas à minha lista, para que eu possa gerenciar minhas pendências diárias.
    + ##### Critérios de Aceitação:
        + Deve haver um campo de entrada para adicionar o título da tarefa.
        + Deve haver um botão para adicionar a tarefa à lista.
        + Ao adicionar, a tarefa deve aparecer na lista de tarefas com status "pendente".

2. #### Marcar Tarefas como Concluídas
    + Como um usuário, quero marcar uma tarefa como concluída, para que eu possa ver visualmente o que já foi feito.
    + ##### Critérios de Aceitação:
        + Deve haver uma maneira de marcar/desmarcar uma tarefa como concluída.
        + Tarefas concluídas devem ser visualmente diferenciadas das pendentes (ex: riscar o texto).

3. #### Remover Tarefas
    + Como um usuário, quero poder remover tarefas da lista, para que eu possa eliminar itens que não são mais necessários.
    + ##### Critérios de Aceitação:
        + Deve haver um botão de remoção em cada tarefa.
        + Quando o botão for clicado, a tarefa deve ser removida da lista.

4. #### Filtrar Tarefas
    + Como um usuário, quero poder filtrar minhas tarefas, para que eu veja apenas as concluídas, pendentes ou todas.
    + ##### Critérios de Aceitação:
        + Deve haver três opções de filtro: "Todas", "Concluídas", "Pendentes".
        + Quando um filtro for selecionado, apenas as tarefas correspondentes devem ser exibidas.

5. #### Persistir Tarefas (opcional)
    + Como um usuário, quero que minhas tarefas sejam salvas mesmo após eu fechar o navegador, para que eu não perca minha lista.
    + ##### Critérios de Aceitação:
        + As tarefas devem ser armazenadas no localStorage.
        + Ao recarregar a página, as tarefas salvas devem ser carregadas automaticamente.

