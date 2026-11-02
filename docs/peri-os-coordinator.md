# PERI OS Coordinator

Coordenadora do sistema de skills do **Peri&Positivas**, de Lisbeth Oliveira.

O ficheiro principal define como receber pedidos, selecionar as capacidades necessárias, validar passagens entre skills, tratar evidência e distinguir revisão de conteúdo de autorização para executar ações externas.

## Estado da publicação

Esta publicação contém o **ficheiro principal da coordenadora** fornecido pela autora. A matriz de encaminhamento, os contratos e as restantes skills não estão incluídos nesta versão; o pacote completo ainda não está disponível para instalação e execução.

**A versão funcional do PERI OS não foi identificada no material fornecido.** A publicação não declara que a instalação atual da autora ou uma versão anterior foram verificadas.

## Ficheiro disponível

- [skills/peri-os-coordinator/SKILL.md](../skills/peri-os-coordinator/SKILL.md)

O conteúdo funcional foi preservado. Foram apenas retiradas as barras de escape de colagem para repor o YAML e o Markdown.

## O que a coordenadora define

- Receção do pedido e identificação de objetivo, audiência, canais, fontes e autorizações.
- Escolha da rota mínima e validação dos contratos entre etapas.
- Evidência e revisão de afirmações antes e depois de nova escrita de saúde.
- Separação entre descoberta e arquitetura de produto e entre desenho de aprendizagem e produção de materiais.
- Revisão final de marca e conteúdo, com interrupção da rota quando surge um bloqueio.
- Exigência de autorização humana explícita para a ação externa concreta.

A arquitetura descrita atribui a WordPress o centro editorial, a Systeme.io a subscrição, newsletter, funil, entrega e curso, a Pinterest a descoberta e a Lovable as ferramentas. Estas referências são instruções de arquitetura; este repositório não inclui integrações ou credenciais dessas plataformas.

## Dependências por integrar

| Elemento | Estado nesta publicação |
|---|---|
| `skills/peri-os-coordinator/references/routing.md` | Referenciado no `SKILL.md`, mas ainda não fornecido. |
| Contrato `task-envelope` e outros contratos entre etapas | Os schemas, versões e adaptadores não foram fornecidos. |
| Skills chamadas pelas rotas | Não incluídas; a relação completa depende da matriz original. |
| Regras e recursos auxiliares referenciados por essas dependências | Por identificar a partir dos ficheiros originais. |

O ficheiro principal cita capacidades de pesquisa/revisão de evidência, verificação de afirmações, audiência, estratégia de conteúdo, escrita, SEO/distribuição, conteúdo social, descoberta e arquitetura de produto, desenho de aprendizagem, workbooks, especificação de ferramentas e QA de marca.

As skills `peri-positivas-knowledge` e `peri-positivas-content-intelligence` são referidas como opcionais, apenas quando explicitamente necessárias. O ficheiro também identifica componentes legados excluídos do encaminhamento; essa é uma declaração do documento, não uma inspeção da instalação atual.

## Utilização e verificação

O `SKILL.md` pode ser consultado para conhecer o método de coordenação. Para executar a coordenadora, é necessário integrar os ficheiros originais em falta, verificar as referências, validar os contratos e testar as rotas no ambiente de destino.

As verificações desta publicação abrangem a formatação e os metadados do ficheiro principal. Não foi realizado um teste funcional do PERI OS completo.

## Autoria e licença

**Lisbeth Oliveira — Peri&Positivas.**

Não foi indicada uma licença no material fornecido; esta publicação não acrescenta uma licença de reutilização.
