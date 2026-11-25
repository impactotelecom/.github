<!--
Preencha todas as seções. PR sem issue vinculada, sem teste para os critérios de aceite
ou com CI vermelha volta ao autor sem revisão.
Título no padrão Conventional Commits, ex.: feat(atendimento): permitir reabertura em até 7 dias
-->

## O que muda

<!-- 2 a 4 linhas: o que este PR faz e por quê. -->

## Issue e Especificação

Closes #
Especificação: impactotelecom/engineering#

## Critérios de aceite atendidos

| CA | Teste que comprova (arquivo e nome do teste) |
|---|---|
| CA-01 | |
| CA-02 | |

## Como testar manualmente

1.
2.

## Evidências

<!-- Front: capturas ou vídeo, em desktop e mobile, incluindo os estados de erro e vazio.
Back: exemplo de requisição e resposta, sem dado real e sem token. -->

## Impacto operacional

- **Migrações:** <!-- não há / quais, se são reversíveis e o tempo estimado em produção -->
- **Variáveis de ambiente novas:** <!-- não há / os nomes; o valor fica no cofre, nunca aqui -->
- **Dependências novas:** <!-- não há / qual, por quê e a licença -->
- **Feature flag:**
- **Plano de reversão:**

## Checklist do autor (Definition of Done)

- [ ] Todo CA coberto por este PR tem teste automatizado que o comprova.
- [ ] Suíte completa, lint e checagem de tipos passam localmente e na CI.
- [ ] Contrato de API igual ao da Especificação, ou a Especificação foi atualizada antes.
- [ ] Autorização e isolamento entre empresas testados em todo endpoint novo ou alterado.
- [ ] Nenhum segredo, token, senha ou arquivo `.env` no diff.
- [ ] Migração reversível e testada do zero.
- [ ] Logs sem dado pessoal.
- [ ] Documentação atualizada: README, `.env.example`, CHANGELOG e ADR, se houve decisão de arquitetura.
- [ ] Branch atualizada com a principal e sem conflito.
- [ ] Commits no padrão Conventional Commits.
- [ ] Revisei o meu próprio diff antes de pedir revisão.

## Checklist do revisor

- [ ] O código faz o que a Especificação pede, e só isso.
- [ ] Os testes falhariam se a regra fosse quebrada, não só passam.
- [ ] Nomes claros, sem duplicação, sem código morto ou comentado.
- [ ] Erros tratados; nada é engolido em silêncio.
- [ ] Nenhum risco de segurança evidente: autorização, injeção, exposição de dado.
