# PSE em Ação

Sistema de planejamento e acompanhamento de ações coletivas do **Programa Saúde na Escola (PSE)**, desenvolvido em linguagem C, executado em terminal.

Atividade Extensionista de Prática (AEP) — Análise e Desenvolvimento de Sistemas, 2º semestre — Universidade Cesumar (UniCesumar).

## Integrantes

- Kaue Martimiano Gomes — RA:  26007835-2
- Pedro Henrique Silva de Souza — RA: 26011609-2

## Sobre o projeto

O PSE em Ação é uma aplicação introdutória, executada em terminal, que apoia o registro, o planejamento e o acompanhamento de ações coletivas do Programa Saúde na Escola. O sistema não realiza diagnóstico, triagem ou tratamento, e não armazena dados clínicos ou informações individuais sensíveis de estudantes — utiliza exclusivamente dados fictícios e informações coletivas.

### Funcionalidades previstas

- Cadastrar ação
- Listar ações
- Pesquisar ação (por código, escola ou tema)
- Atualizar situação e registrar participantes
- Gerar resumo (planejadas, realizadas, canceladas e percentual de participação)
- Validar entradas (códigos duplicados, campos vazios, valores negativos)

## Estrutura do repositório

```
.
├── documentacao/
│   └── AEP_PSE_em_Acao_Etapa_1_ABNT.docx   # documento escrito da Etapa 1 (ABNT)
├── src/
│   └── (código-fonte em C, a partir da Etapa 2)
└── README.md
```

## Status do desenvolvimento

- [x] Etapa 1 — Documento escrito: problema, objetivos, justificativa, requisitos, fluxogramas e planejamento das sprints
- [ ] Etapa 2 — Implementação em linguagem C
- [ ] Testes e documentação final
- [ ] Apresentação

## Planejamento das sprints

| Sprint | Foco |
|---|---|
| 1 | Levantamento do problema e escopo |
| 2 | Requisitos funcionais e não funcionais |
| 3 | Fluxogramas e pseudocódigos |
| 4 | Estrutura inicial em C (struct, vetor, menu) |
| 5 | Cadastro, listagem e pesquisa |
| 6 | Atualização, participantes, resumo e validações |
| 7 | Testes, correções e documentação |
| 8 | Preparação da apresentação final |

Detalhamento completo em `documentacao/AEP_PSE_em_Acao_Etapa_1_ABNT.docx`.

## Tecnologias

- Linguagem C (padrão compatível com o ambiente definido pelo professor)
- Execução em terminal, sem dependência de interface gráfica ou banco de dados

## Licença

Projeto acadêmico, sem fins comerciais, desenvolvido para a disciplina de Análise e Desenvolvimento de Sistemas — UniCesumar.
