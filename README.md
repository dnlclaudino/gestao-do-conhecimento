# Política de Gestão de Conhecimento

Este documento estabelece diretrizes para minha gestão do conhecimento com vistas ao meu desenvolvimento pessoal e profissional.

|Contribuição|Data|Versão|Observações #124; Notas |
|:---:|:---:|:---:|:---|
|Daniel Claudino|15/06/2023|v0.0.1|Versão Inicial do documento|

# Necessidades

|#|Necessidade|
|:---:|:---|
|1|Tornar o conhecimento explicitamente registrado;|
|2|Demonstrar habilidades;|
|3|Demonstrar atitudes;|
|4|Facilitar a localização dos resumos;|
|5|Rapidamente recuperar conhecimentos e habilidades que foram registradas;|

# Objetivos

|# Objetivo |Relacionado a Necessidade # | Descrição do Objetivo|
|:---:|:---|:---|
|1|#1, #4 e #5|Registrar o conhecimento de forma hierarquizada e padronizada a partir de diretrizes claras;|

# A hierarquia dos repositórios

1. O primeiro nível do repositório corresponderá a um tema, assunto, disciplina, tecnologia, metodologia, método ou boa prática;
    - No primeiro nível será criado o arquivo “README.md” contendo um documento markdown de sumário contendo manifesto (o que o repositório contém), uma tabela com as versões com descrições (TAGS) e outra tabela com as relações de partes do do resumo com seus respectivos links ;
2. O segundo nível na hierarquia do repositório será a FONTE do material a ser resumido (livro, artigo, dissertação, monografia, site, manual,plano, norma [lei, decreto,portaria, resolução, regimento-interno, regulamento] , notas-de-aula, resumo-de-terceiros, curso, workshop, vídeo-aula, podcast, slide, etc)
    - Cada pasta FONTE conterá um arquivo README.md contendo sumário com (o que o FONTE contém) e uma tabela com as relações de partes do do resumo com - seus respectivos links;
    - Cada pasta FONTE conterá pastas para os RECURSOS agregados aos resumos e conhecimento registrados:
    - Uma pasta chamada “figuras” para armazenar imagens a serem utilizadas no terceiro nível;
    - Uma pasta chamada “planilhas” para armazenar planilhas eletrônicas
    - Uma pasta chamada "código-fonte" para armazenar códigos-fonte;
    - Obs: podem haver outras pastas para armazenar outros RECURSOS, devendo ser seguido as regras de nomenclatura de PASTAS explicitadas mais adiante;

3. O terceiro nível na hierarquia do repositório conterá pastas para cada capítulo, unidade, artigo, documento, etc a ser resumido em um arquivo markdown (*.MD)

# Fluxo de trabalho para elaboração de resumos

Deve-se usar o Github e a conta “dnlclaudino@gmail.com” para criar e manter resumos.

1. Deve-se identificar o tema, assunto, disciplina, tecnologia, metodologia, método, boa prática a ser resumida (veja lista em XXXXXX na forma de mapa mental);
2. Verificar se já existe um repositório (Github) para o resumo
    - Caso não exista, criar um repositório no Github;
3. Verificar se já existe a FONTE no repositório (Github) para o resumo
    - Caso não exista, criar a FONTE dentro do repositório;
4. Organizar o repositório em pastas para cada capítulo, unidade, artigo, documento, etc a ser resumido em um arquivo markdown próprio;
5. O repositório do github deve conter
    - Um Branch chamada master para a versão final dos documentos (arquivos)
    - Deve ser criada uma branch chamada desenvolvimento-’nome-da-fonte’-’nome-do-capitulo/unid.parte’ para adição, alteração, remoção de texto do resumo
    - Não modificar diretamente a branch master !

6. Após a revisão do texto elaborado na branch desenvolvimento-’nome-da-fonte’-’nome-do-capitulo/unid.parte’’ , deve ser feito um merge com a branch master;
7. Após a conclusão do resumo de uma capítulo, unidade, parte do documento, etc:
    - Deve ser criado uma TAG no repositório com o número da versão e descrição do que foi resumido;
      - Obs: Seguir regras de versionamento semântico deste documento para denominação das TAGS
    - O arquivo “README.md” deve ser atualizado;

# Regras para versionamento semântico nos documentos

1. Usar o seguinte versionamento semântico:

    - MAJOR.MINOR.PATCH
    - PATCH -> Aumentar sempre que partes de um documento (arquivo) de resumo forem sendo entregues;
    - MINOR -> Sempre que um (arquivo) documento foi finalizado (capítulo, unidade, artigo, documento, etc)
    - MAJOR* -> Sempre que um mesmo tópico for resumido a partir de outra fonte

* Se após eu fizer um resumo de um manual do TCU sobre gestão de riscos (uma versão MAJOR), eu fizer um outro resumo sobre o mesmo tema (gestão de riscos) de um manual de gestão de riscos do CNJ (outra versão MAJOR acrescentada).

# Regras para nomenclatura de fontes

1. Todas as letras em minúscula;
2. As palavras não devem conter acentos diacríticos (agudo, circunflexo,crase,etc);
3. Palavras separadas por hífen “-”;
4. Para nomenclatura de FONTES
    - Elementos:
      - Tipo da fonte: livro, livro-treinamento,apostila-treinamento,slide-treinamento,livro-curso,apostila-curso,slide-curso, artigo, dissertação, monografia, site, manual,plano, norma [lei, decreto,portaria, resolução, regimento-interno, regulamento], notas-de-aula, resumo-de-terceiros, curso, treinamento, workshop, vídeo-aula, podcast, slide, etc (sem acentos diacríticos);
      - Sobrenome dos autores (pessoa física, ou pessoa jurídica quando institucional) em MAIÚSCULA separados por hífen “-”
      - Ano com quatro dígitos;
      - Uma descrição com o título da fonte (separadas por hífen e sem sinais diacríticos). Encurtar, se necessário.

5. Exemplos:
      - Livros
        - livro-SAYER-WILLIANS-2015-lean-para-leigos
        - livro-SIQUEIRA-2014-certificacao-lpi-1
        - livro-GUEDES-2018-uml-2-uma-abordagem-pratica
      - Cursos
        - curso-ENAP-2023-gerenciamento-de-servicos-de-ti 
        - curso-CNJ-2023-analise-de-dados-com-r
        - curso-CNJ-2023-analise-de-dados-com-excel
      - Normas
        - portaria-TRE-PB-14-2019-regulamento-interno-da-secretaria 
        - resolucao-CNJ-324-2020-diretrizes-para-gestao-documental-e-da-memoria-no-poder-judiciario
      - Manuais
        - manual-CNJ-2020-manual-de-gestao-documental
        - manual-CNJ-2020-manual-de-digitalizacao-de-documentos
        - manual-TSE-2021-manual-de-gestao-documental
        - manual-TSE-2021-manual-de-digitalizacao-de-documentos

# Regras para nomenclatura de pastas e documentos de resumo

1. Todas as letras em minúscula;
2. As palavras não devem conter acentos diacríticos (agudo, circunflexo, cedilha, crase,etc);
3. Palavras separadas por hífen “-”;
4. Para nomenclatura de PASTAS
      - Escolha uma nomenclatura que reflita de forma suficientemente genérica o tema / assunto / disciplina / tecnologia / metodologia / método / boa prática
5. Para nomenclatura de ARQUIVOS
    - Caso o objeto do resumo seja dividido em CAPÍTULOS
      - Elementos:
        - A expressão “capitulo”
        - O número do capítulo/parte com dois dígitos;
        - Uma descrição breve do capítulo;
      - Exemplo.:
         - capitulo-02-conhecendo-o-gerenciamento-de-Servicos.MD
      - Caso o objeto do resumo seja dividido em <ESPECIFICAR A FORMA DE DIVISÃO>

# Regras para nomenclatura de imagens

1. Todas as letras em minúscula;
2. As palavras não devem conter acentos diacríticos (agudo, circunflexo,crase,etc);
3. Palavras separadas por hífen “-”;
4. Para nomenclatura de ARQUIVOS DE IMAGENS
    - Caso o objeto do resumo seja dividido em CAPÍTULOS
      - Elementos:
         - A expressão ‘figura’
         - O número do capítulo/parte com dois dígitos;
          - Uma descrição breve da figura;
      - Exemplo.:
      - figura-02-classificacao-das-tipologias-de-servicos.PNG
    - Caso o objeto do resumo seja dividido em < ESPECIFICAR A FORMA DE DIVISÃO >

# Regras para nomenclatura de tabelas e quadros

1. Para nomenclatura de TABELAS e QUADROS
    - Caso o objeto do resumo seja dividido em CAPÍTULOS
      - Elementos:
        - A expressão ‘Tabela’;
        - Um hífen “-”;
        - Uma descrição breve da tabela com todos os sinais diacríticos pertinentes;
    - Exemplo.:
      - Tabela - Classificação das tipologias de serviços

# Regras para nomenclatura de commits no Github

Em construção...
