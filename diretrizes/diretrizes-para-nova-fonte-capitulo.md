# Diretrizes para Criar um Resumo/Resenha de um Capítulo em Fonte

- Estas dretrizes aplicam-se as seguintes possibilidades de organização de uma fonte:
  - Quando a fonte é dividida da seguinte forma:
    - Parte X
    - Unidade Y
    - Capítulo Z
  - Quando a fonte é dividida da seguinte forma:
    - Unidade Y
    - Capítulo Z
  - Quando a fonte é dividida da seguinte forma:
    - Capítulo Z
  - Quando a fonte é dividida da seguinte forma:
    - Parte Y
    - Unidade Z
  - Quando a fonte é dividida da seguinte forma:
    - Unidade Z

## Passo a Passo para Primeiro Commit

### Criar Branch

- Modelo:
  - AUTOR-ANO do NOME DA PASTA;
  - "-capitulo-
  - 01
- Exemplo:
  - Nome da Branch: **NADER-2016-capitulo-01**
  - Nome da Branch: **NADER-2016-unidade-01**

### Incluir Ícones de Navegação

<table align="right" border="0">
  <tr>
    <td align="center" valign="top">
      <a href="https://github.com/dnlclaudino/gestao-do-conhecimento#readme">
        <img src="https://github.com/dnlclaudino/imagens/blob/master/icones/icone-casa3.png?raw=true" heigh="60" width="60"><br>Início da <br>Gestão do <br>Conhecimento
      </a>
    </td>
    <td align="center" valign="top">
      <a href="./README.md">
        <img src="https://github.com/dnlclaudino/imagens/blob/master/icones/icone-sumario.png?raw=true" heigh="60" width="60"><br>Sumário<br>da Fonte
      </a>
    </td>
    <td align="center" valign="top">
      <a href="../README.md">
        <img src="https://github.com/dnlclaudino/imagens/blob/master/icones/icone-casa2.png?raw=true" heigh="60" width="60"><br>Início deste <br>Repositório
      </a>
    </td>
    <td align="center" valign="top">
        <img src="https://github.com/dnlclaudino/imagens/blob/master/icones-aplicativos/pdf/pdf.png?raw=true" heigh="60" width="60"><br>Baixar em PDF
    </td>
  </tr>
</table><br><br><br><br><br><br><br>

<!-- ATENÇÃO: APAGUE as linhas abaixo e este documentário !!!-->

![](https://github.com/dnlclaudino/imagens/blob/master/gestao-do-conhecimento/capitulo-estrutura-padrao.png?raw=true)

<!-- Colocar a expressão SUMÁRIO abaixo depois do NOME DO ARQUIVO *.md -->

### Incluir Tópicos/Elementos do Capítulo

- Não incluir o nome do capítulo no sumário

### Incluir "Sumário"

<center><b>SUMÁRIO</b></center>

<!-- Não esqueça de adicionar o PARÂMETRO abaixo na Table of Contents (TOC) -->

<!-- TOC updateonsave:false-->

### Realizar o Primeiro Commit

- Exemplo de mensagem do **primeiro commit**:
  - Redigir: Versão inicial do capituloXX
  - (linha em branco)
  - NADER, Paulo. Introdução ao Estudo do Direito. 38. ed. Rio de Janeiro:Forense, 2016.

## Passo a Passo para Demais Commits

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

### Comitar A Cada Seçao Ou Parte Do Capítulo

- Modelo da mensagem de commit: "**REDIGIR: seção "NOME-DA-SEÇAO".**"

#### Caso sejam necessários vários commits numa mesma seção do capítulo

- No caso de
  - Seções de capítulo extensas em que sejam necessários vários commits;
  - Interrupção necessária da realização do resumo/resenha sem a conclusão dos trabalhos numa determinada seção.
- Seguir o modelo da mensagem de commit: "**REDIGIR: seção "NOME-DA-SEÇAO". (em Elaboração)**"
- Após a conclusão dos trabalho de resumo/resenha de uma determinada seção:
  - Juntar os commits "**REDIGIR: seção "NOME-DA-SEÇAO". (em Elaboração)**" num único commit "**REDIGIR: seção "NOME-DA-SEÇAO".**"

### Caso Seja Preciso Revisar o Resumo/Resenha

- Seguir o modelo da mensagem de commit iniciando com "**REVISAR: ... (em Elaboração)**" e, no que resta, seguindo as mesmas orientações da seção "[Caso sejam necessários vários commits numa mesma seção do capítulo](#caso-sejam-necessários-vários-commits-numa-mesma-seção-do-capítulo)"
