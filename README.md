# Geminus Agent

Um Agente totalmente autônomo para executar tarefas complexas sem intervenção humana!

o Propósito do Geminus Agent é facilitar tarefas complexas que levariam muito tempo para serem concluídas.

Geminus Agent é um Agente Autônomo CLI para terminal escrito em python com capacidades incríveis, quando Geminus recebe sua tarefa, ele monta uma To-Do-List do que ele precisa fazer para completar sua tarefa, após montar a To-Do-List, Geminus começa a executar sua tarefa, caso ele encontre algum erro durante a tarefa (ex: dependência ausente, erro de sintaxe) ele planeja uma sub-tarefa para tentar corrigir o erro em no máximo 3 Tarefas, caso o Geminus não consiga, ou dizer que o não é corrigível automáticamente, ele irá pedir para você dizer oque fazer a seguir, você pode pedir encerrar TODAS as tarefas, ou pedir para ele pular a tarefa.

Geminus tem a capacidade de executar comandos shell, caso ele encontre uma tarefa que necessita de alguma biblioteca específica, ele irá instala-la sozinho, após concluir a instalação, continuará a tarefa.

Geminus consegue pesquisar na Web através de scraping, atualmente Geminus não consegue pesquisar pelo Google pois não tem uma API (ainda).

Geminus consegue executar blocos de código python sozinho para concluir uma tarefa que necessita de comandos complexos.

(Mais informações Em Breve)

## Futuras Capacidades
O Geminus ainda tem muito a melhorar, pra isso, estou atualizando muita coisa, algumas das futuras atualizações incluem:

1. Geminus Studio
2. Modo Livre & Modo Ambiente
3. Navegação por diretórios
4. Ler arquivos específicos
5. Rollback caso algum arquivo tenha falha durante alteração
6. Escolha de limite de tarefas & modo infinito de tarefas

Em Breve mostrarei mais atualizações futuras pra vocês.

## Como utilizar
para utilizar o Geminus você vai precisar do **Python 3** você pode baixar o python diretamente pelo site oficial.

as bibliotecas necessárias são:
1. google-generativeai
2. colorama
3. bs4
4. requests
5. platform
6. logging
7. os
8. json
9. subprocess
10. sys
11. tempfile

a maioria são pré-instaladas, mas vale a pena tentar instalar cada uma.

Depois de instalar todas as dependências necessárias, baixe o arquivo correspondente com seu Sistema Operacional (ex: Windows) e colar em um arquivo, antes de executar o arquivo, coloque sua chave API do Gemini aonde está escrito "YOUR-API-KEY", se você não sabe como conseguir a API, basta acessar o Google Ai Studio, lá você pode obter sua API.

Após colocar sua API, execute o arquivo do Geminus, ex:
```
python3 Geminus-Windows.py
```
após isso, o Geminus está pronto para executar suas tarefas.

## Tecnologias
- Python

## Como contribuir
Veja o arquivo [CONTRIBUTING.md](CONTRIBUTING.md) para orientações de contribuição.

## Licença
Distribuído sob a licença MIT. Veja em [LICENSE](LICENSE) para mais informações.
