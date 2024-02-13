# Diretrizes para Demais Commits numa Fonte

- Recomenda-se realizar um commit após a conclusão do resumo/resenha de cada seçao ou parte do capítulo, em virtude de:
  - Melhorar o fluxo de trabalho do resumo/resenha;
  - Deixar o repositório mais organizado;
- Durante os trabalhos de elaboração de um resumo/resenha, existem os seguintes **TIPOS DE TAREFAS** que <u>**orientarão a MENSAGEM DE COMMIT adequada**</u>, conforme abaixo:
  - **REDIGIR** um resumo/resenha;
    - Usado quando é necessário:
      - Realizar o trabalho de resumo ou transcrição;
    - A mensagem de commit começa com "**REDIGIR:**"
  - **REVISAR** um resumo/resenha;
    - Usado quando é necessário:
      - Alterar a formatação ou qualquer outros aspecto da aparência do documento;
      - Inserir/remover links;
      - Transformar texto em tabela;
      - Revisar ortografia, morfologia, sintaxe ou estilística do documento;
    - A mensagem de commit começa com "**REVISAR:**"
  - **ADICIONAR** recursos a fonte;
    - Usado quando é necessário:
      - Adicionar arquivos à fonte;
    - A mensagem de commit começa com "**ADICIONAR RECURSO:**"
  - **REMOVER** recurso da fonte
    - Usado quando é necessário:
      - Remover arquivos à fonte;
    - A mensagem de commit começa com "**REMOVER RECURSO:**"
- Na mesma branch criada no "[Passo a Passo para Primeiro Commit](#passo-a-passo-para-primeiro-commit)":

## Comitar A Cada Seçao Ou Parte Do Capítulo

- Modelo da mensagem de commit: "**REDIGIR: seção "NOME-DA-SEÇAO".**"

### Caso sejam necessários vários commits numa mesma seção do capítulo

- No caso de
  - Seções de capítulo extensas em que sejam necessários vários commits;
  - Interrupção necessária da realização do resumo/resenha sem a conclusão dos trabalhos numa determinada seção.
- Seguir o modelo da mensagem de commit: "**REDIGIR: seção "NOME-DA-SEÇAO". (em Elaboração)**"
- Após a conclusão dos trabalho de resumo/resenha de uma determinada seção:
  - Juntar os commits "**REDIGIR: seção "NOME-DA-SEÇAO". (em Elaboração)**" num único commit "**REDIGIR: seção "NOME-DA-SEÇAO".**"

## Caso Seja Preciso Revisar o Resumo/Resenha

- Seguir o modelo da mensagem de commit iniciando com "**REVISAR: ... (em Elaboração)**" e, no que resta, seguindo as mesmas orientações da seção "[Caso sejam necessários vários commits numa mesma seção do capítulo](#caso-sejam-necessários-vários-commits-numa-mesma-seção-do-capítulo)"
