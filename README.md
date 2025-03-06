Gerenciador de Tarefas (Task Manager)
Descrição
Um sistema de linha de comando para gerenciar tarefas, permitindo que os usuários adicionem, listem, atualizem e removam tarefas.

Requisitos Funcionais
Adicionar Tarefa

O usuário pode adicionar uma nova tarefa com uma descrição.
Cada tarefa recebe um identificador único.
Listar Tarefas

O sistema exibe todas as tarefas cadastradas.
Deve indicar se a tarefa está pendente ou concluída.
Atualizar Tarefa

O usuário pode marcar uma tarefa como concluída.
Remover Tarefa

O usuário pode excluir uma tarefa pelo seu identificador.
Persistência Opcional

As tarefas podem ser salvas em um arquivo para serem recuperadas após o encerramento do programa (JSON, CSV ou SQLite).
Requisitos Não Funcionais
Interface Simples

Deve rodar no terminal e aceitar entrada do usuário via stdin.
Código Idiomático

Seguir boas práticas do Rust, como ownership e borrowing adequados.
Boa Manipulação de Erros

O sistema não deve quebrar com entradas inválidas.
Possíveis Extensões
Suporte a datas de vencimento.
Organização de tarefas por prioridade.
Adicionar suporte a múltiplos usuários.
Interface Web com Rocket ou Axum.
