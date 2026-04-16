# guia-turistico
Abaixo, segue uma explicação sobre o que pensei para a escala e propósito dos repositórios, divididos em classes. No final haverá uma tabela para compreensão mais rápida.

#### REPOSITÓRIO DE ESTUDO

- Explorações preliminares de um tema

- Até 8 arquivos (exceto arquivos gerados automaticamente)

- Emprego de tecnologias cruas (ex.: "Treina um modelo de classificação")

- Sem listagem de requisitos funcionais



#### REPOSITÓRIO INTERMEDIÁRIO

- Se o de estudo é "uni-coisa", o intermediário explora as integrações entre elas mais profundamente

- Estrutura de arquivos e diretórios segue as convenções, mas não é completa

- Pode usar API, mas não há Dockerfile

- De 8 a 20 arquivos

- Listagem parcial de requisitos funcionais



#### REPOSITÓRIO DE PORTFÓLIO

- Geralmente, estrutura de arquivos e diretórios completa, de acordo com as convenções

- Uso de Docker

- Mais de 20 arquivos

- Respeito às melhores práticas (PEP 8, SOLID, etc.)

- Listagem de todos os requisitos funcionais

---

***Segue um quadro comparativo para compreensão mais rápida***


| Critério | Repositório de estudo | Repositório Intermediário | Repositório de Portfólio |
| :---: | :---: | :---: | :---: |
| Arquivos | < 8* | 8-20 | > 20 |
| Escopo | Testes | Integrado | Industrial |
| Listagem de RF's | ❌ | Parcial | ✅ |
| Estrutura  | Orgânica | Convencional | Arquitetural |
| Docker | ❌ | ❌ | ✅ |
| API** | ❌ | ✅ | ✅ |
| Boas práticas | 🙂 | ✅ | ✨ |

---

\* = Exceto arquivos gerados automaticamente

\** = Se necessária. Normalmente não hospedada

**NOTA:** Como achei isso uma ferramenta útil para organização de perfis, coloquei uma licença CC BY, já que, se eu não colocasse, esse texto seria formalmente proprietário, o que acharia um circo.
