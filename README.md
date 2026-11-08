# .github

Este repositório não tem código. É uma configuração da organização `hunter-oficina`: o GitHub lê o que está aqui e aplica em todos os repositórios dela.

O que ele faz:

- Formulários de issue. Quando alguém clica em "New issue" em qualquer repositório do Hunter, o GitHub mostra os formulários de História, Bug, Tarefa e Estudo que estão em `.github/ISSUE_TEMPLATE/`. Cada formulário já pede as informações certas, define o tipo da issue e coloca a issue no quadro da esteira.
- Modelo de pull request. Toda pull request começa com o texto de `.github/pull_request_template.md`, com o checklist de revisão.

Por que é público: o GitHub só aplica essas configurações à organização inteira se este repositório for público. Por isso ele guarda apenas os formulários e o modelo, sem nenhuma informação interna. As issues e o código continuam nos repositórios privados.

Para mudar um formulário, edite o arquivo dele e abra uma pull request. A mudança vale para todos os repositórios assim que entrar na `main`.
