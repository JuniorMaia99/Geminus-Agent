# Geminus Agent

Um Agente totalmente autônomo para executar tarefas complexas sem intervenção humana!

o Propósito do Geminus Agent é facilitar tarefas complexas que levariam muito tempo para serem concluídas.

Geminus Agent é um Agente Autônomo CLI para terminal escrito em python com capacidades incríveis, quando Geminus recebe sua tarefa, ele monta uma To-Do-List do que ele precisa fazer para completar sua tarefa, após montar a To-Do-List, Geminus começa a executar sua tarefa, caso ele encontre algum erro durante a tarefa (ex: dependência ausente, erro de sintaxe) ele planeja uma sub-tarefa para tentar corrigir o erro em no máximo 3 Tarefas, caso o Geminus não consiga, ou dizer que o não é corrigível automáticamente, ele irá pedir para você dizer oque fazer a seguir, você pode pedir encerrar TODAS as tarefas, ou pedir para ele pular a tarefa.

Geminus tem a capacidade de executar comandos shell, caso ele encontre uma tarefa que necessita de alguma biblioteca específica, ele irá instala-la sozinho, após concluir a instalação, continuará a tarefa.

Geminus consegue pesquisar na Web através de scraping, atualmente Geminus não consegue pesquisar pelo Google pois não tem uma API (ainda).

Geminus consegue executar blocos de código python sozinho para concluir uma tarefa que necessita de comandos complexos.

(Mais informações Em Breve)

## Tecnologias
- Python

## Como contribuir
Veja o arquivo [CONTRIBUTING.md](CONTRIBUTING.md) para orientações de contribuição.

## Licença
Distribuído sob a licença MIT. Veja em [LICENSE](LICENSE) para mais informações.
