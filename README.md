# Projeto final de Engenharia de Software

Este repositório reúne os documentos e diagramas do projeto final de Engenharia de Software I. O trabalho foi feito sobre o ESM Forum, um fórum de perguntas e respostas. O backend e o frontend estão nos repositórios abaixo.

## Repositórios e planejamento

- [Backend — esmforum](https://github.com/matheusmi2/esmforum)
- [Frontend — esmforum-react](https://github.com/matheusmi2/esmforum-react)
- [Quadro Kanban no GitHub Projects](https://github.com/users/matheusmi2/projects/5)

## Parte 1 — Ambiente e planejamento

A pasta parte1 contém as instruções para executar o sistema, a escolha do processo de desenvolvimento e os documentos sobre as práticas de XP.

- [INSTALACAO.md](parte1/INSTALACAO.md): instalação e execução do backend e do frontend.
- [PROCESSO.md](parte1/PROCESSO.md): escolha do Kanban, colunas e prioridades.
- [DESIGN_SIMPLES.md](parte1/DESIGN_SIMPLES.md): análise do backend com exemplos de código e possíveis melhorias.
- [PAIR_PROGRAMMING.md](parte1/PAIR_PROGRAMMING.md): planejamento das sessões, ferramentas e troca de papéis.

## Parte 2 — Requisitos e diagramas UML

A pasta parte2 contém as histórias de votação, busca e tags, o caso de uso da votação e os quatro diagramas. Cada imagem tem seu arquivo fonte Mermaid na mesma pasta.

- [HISTORIAS.md](parte2/HISTORIAS.md): três histórias com critérios de aceitação e justificativa da prioridade.
- [CASO_DE_USO.md](parte2/CASO_DE_USO.md): votação em perguntas, com os caminhos para trocar e retirar o voto.

### Diagrama de classes

Mostra Usuario, Pergunta, Resposta, Voto e Tag, com seus atributos e relacionamentos.

![Diagrama de classes do ESM Forum](parte2/diagramas/diagrama_classes.png)

[Arquivo fonte Mermaid](parte2/diagramas/diagrama_classes.mmd)

### Diagrama de sequência

Mostra a comunicação entre usuário, frontend, API e banco durante a votação.

![Diagrama de sequência da votação](parte2/diagramas/diagrama_sequencia.png)

[Arquivo fonte Mermaid](parte2/diagramas/diagrama_sequencia.mmd)

### Diagrama de atividades

Mostra os passos da busca por palavra-chave e as decisões sobre campo vazio e resultados encontrados.

![Diagrama de atividades da busca](parte2/diagramas/diagrama_atividades.png)

[Arquivo fonte Mermaid](parte2/diagramas/diagrama_atividades.mmd)

### Diagrama de estados

Mostra os estados do voto e o que acontece ao registrar, trocar, repetir ou retirar um voto.

![Diagrama de estados do voto](parte2/diagramas/diagrama_estados.png)

[Arquivo fonte Mermaid](parte2/diagramas/diagrama_estados.mmd)

## Parte 3 — SOLID, padrões de projeto e arquitetura

Esta parte analisa o código do backend e apresenta a implementação da votação com princípios SOLID. Também identifica padrões usados no sistema e propõe outros três para as funcionalidades planejadas.

- [ANALISE_SOLID.md](parte3/ANALISE_SOLID.md): pontos positivos e possibilidades de melhoria no código.
- [IMPLEMENTACAO_SOLID.md](parte3/IMPLEMENTACAO_SOLID.md): votação, divisão dos módulos e aplicação de SRP, DIP e OCP.
- [PADROES_EXISTENTES.md](parte3/PADROES_EXISTENTES.md): padrões presentes no código.
- [PADROES_PROPOSTOS.md](parte3/PADROES_PROPOSTOS.md): propostas de Decorator, Observer e Facade, com exemplos e diagramas.
- [ARQUITETURA.md](parte3/ARQUITETURA.md): arquitetura atual do sistema, camadas, comunicação e diagrama.
- [PROPOSTA_ARQUITETURA.md](parte3/PROPOSTA_ARQUITETURA.md): organização em camadas e proposta de MVC para perguntas e votação.

O [índice da Parte 3](parte3/README.md) reúne os documentos e diagramas dessa etapa.
