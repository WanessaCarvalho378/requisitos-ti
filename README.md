## Estudando requisitos em TI 

<details>
<summary>Levantamento de requisitos</summary>

Os requisitos são classificados em: 

Requisitos funcionais (funcionalidades): O que deve ser feito, como quer que o aplicativo se comporte 

Requisitos não funcionais (características do sistema): Como deve ser feito, questões relacionadas a capacidade de processamento do sistema

https://papogp.com/2011/08/10-dicas-para-coleta-de-requisitos-2/

Como levantar os requisitos do cliente ? 

1. Elaborar roteiro antes da entrevista 
Qual o principal objetivo do sistema a ser desenvolvido? 
Quais os principais problemas que enfrentam atualmente sem um sistema de operação? 
Quais informações devem ser armazenadas no cadastro de histórico? 
Gostaria de acrescentar algo a mais?

roteiro de entrevista:
[roteiro-de-entrevista-com-o-usuc3a1rio.pdf](https://github.com/WanessaCarvalho378/requisitos-ti/files/12507745/roteiro-de-entrevista-com-o-usuc3a1rio.pdf)

[Video 1.4 [Fazendo as perguntas certas] Roteiro para elaboração de perguntas.pdf](https://github.com/WanessaCarvalho378/requisitos-ti/files/12507752/Video.1.4.Fazendo.as.perguntas.certas.Roteiro.para.elaboracao.de.perguntas.pdf)

Obs.: Fazer a entrevista com mais de uma pessoa 

Obs.: Uma outra técnica para levantamento de requisitos além de entrevistas, é fazer brainstorm

https://www.alura.com.br/artigos/5-tecnicas-para-otimizar-processo-brainstorming

</details>

<details>
<summary> Analise das demandas, viabilidade e partes interessadas </summary>

Ao receber uma demanda, o primeiro passo de todos é elaborar um roteiro de poucas perguntas, permitindo questionar sobre o entendimento macro do cenário e validar o entendimento inicial da demanda.

Ao receber a demanda, precisa analisar a demanda através dos seguintes pontos: 
- entender o problema  
- entender a necessidade
- Gerar a primeira lista de dúvidas

Depois, se precisa entender o macro da situação, que envolve: 
- reconhecer o cenário macro 
- identificar premissas e restriçõrs 
- localizar as partes interessadas

Por fim, avaliar a viabilidade, que é ver se existe todos os recursos necessários, e se faz isso através de um relatório de viabilidade, em que esse relatório tem como base se questionar:
Quais problemas atuais essa solução resolve?
É possivel integrar com outras soluções? 
O que deve ser e não deve ser contemplado? 
[Video 1.6 [Analise de Viabilidade] Estudo de Viabilidade.pdf](https://github.com/WanessaCarvalho378/requisitos-ti/files/12508075/Video.1.6.Analise.de.Viabilidade.Estudo.de.Viabilidade.pdf)

Perguntas chaves para entender o cenário macro da situação:
- Quem solicitou?
- Quem vai utilizar? 
- Quais os benefícios da solução?

Perguntas chaves para entender a solução junto do cliente:
- Para você, qual seria uma boa solução? 
- Quais os problemas que a solução deve resolver?
- Em qual ambiente de negócios a solução vai ser aplicada?
- Quais os pontos que precisa ter mais atenção?

A identificação de partes interessadas pode ser feita através de uma reunião com os clientes, em que o compilado da reunião pode ser numa planilha com: nome, área, função, email, celular, principais responsabilidades, principais expectativas, nível de interesse no projeto e nível de engajamento
[Video 1.5 [Identficando as partes interessadas]  Partes Interessadas - Planilha1 (1).pdf](https://github.com/WanessaCarvalho378/requisitos-ti/files/12508076/Video.1.5.Identficando.as.partes.interessadas.Partes.Interessadas.-.Planilha1.1.pdf)

</details>

<details>
<summary>Escrita de requisitos</summary>

É importante que o requisito seja: necessário, verificável, atingível e claro

Você agrupa ou por funcionalidade ou prioridade.
Se escolhido a priorização, é importante verificar se o requisito precisa ter algum outro desenvolvido anteriormente e também se a necessidade do cliente para a utilização deste requisito.

Para classificação e priorização de requisitos, é interessante usar a técnica Moscow:
Must - Tem que ter (Sem eles o sistema não funciona)
Should - Deveria ter (Importantes porém menos críticos)
Could - Poderia ter (requisitos que ajudam na usabilidade)
Want - Interessante ter (requisitos de melhoria)

[Video 4.2 [Classificação e Priorização de Requisitos] Priorização e Classificação de Requisitos - Planilha1.pdf](https://github.com/WanessaCarvalho378/requisitos-ti/files/12508077/Video.4.2.Classificacao.e.Priorizacao.de.Requisitos.Priorizacao.e.Classificacao.de.Requisitos.-.Planilha1.pdf)

Ao escrever, é importante numerar/"etiquetar" cada requisito
Também é importante que cada requisito da lista contemple uma funcionalidade inteira, como se tivesse contando uma 'história'
                                
https://medium.com/lfdev-blog/como-escrever-requisitos-de-software-de-forma-simples-e-garantir-o-m%C3%ADnimo-de-erros-no-sistema-app-74df2ee241cc

</details>

<details>
<summary>Validação de requisitos</summary>

A pessoa para validar precisa ser diferente da que fez o levantamento de requisitos 
Pode ser usado uma planilha para verificação de itens de validação, como essa:
[Alura-engenharia-requisitos-CheckListValidacaoDosRequisitos.xlsx](https://github.com/WanessaCarvalho378/requisitos-ti/files/12507824/Alura-engenharia-requisitos-CheckListValidacaoDosRequisitos.xlsx)

Durante o processo de validação, precisa conferir os seguintes critérios: 

- ser modificável 
- ser rastreável (origem de cada um de seus requisitos é clara e a referência a cada um deles é  facilitada nos documentos subsequentes do processo)
- não ser ambíguo 
- ser verificável (existe um processo finito e economicamente viável do qual uma pessoa ou máquina possa assegurar que o produto de software atende ao requisito)

</details>

<details>
<summary>Refinando os requisitos</summary>

É nesta etapa em que vamos avaliar se há a necessidade de ajuste ou reescrita do requisito para melhor compreensão.

Técnica de cenários: entender o contexto do requisito por inteiro 
dar um nome do cenário tendo a ver com a funcionalidade em questão, ter um ator (ex cliente), pré condição, fluxo normal, fluxo alternativo, pós condição

</details>

<details>
<summary>UML</summary>

- Linguagem única de modelagem de sistemas  
- Ajuda na comunicação entre as partes 
- diagrama mais famoso: caso de uso 
- todo documento de requisitos deve conter ao menos o diagrama de casos de uso 

</details>

<details>
<summary>Artefatos</summary>
  
- artefatos é tudo que a gente reuniu em relação ao projeto até o momento                                                
- revisar diagrama de caso, cenários, requisitos não funcionais 
- reunir para consolidar, essa etapa também envolve refinar e reescrever os requisitos, se necessário
- O diagrama de caso deve ser construído pois irá apoiar no entendimento mais amplo do projeto, além de contribuir para que a documentação do projeto fique mais completa.

</details>

<details>
<summary>Construção do documento de requisitos</summary>

- precisa ter introdução (principais pontos do projeto), cenário atual, descrição dos requisitos separando em requisitos funcionais e não funcionais, incluir protótipos das telas iniciais, ter diagramas dos casos de uso, e evoluções que o sistema pode ter ao longo do tempo
  
  - existe sim a necessidade dessa documentação, entretanto ela não precisa ser longa e tampouco rígida mas deve ser simples, direta e que traga e esclareça as principais dúvidas do cliente e da equipe de desenvolvimento. 
  
  - terminado o documento oficial de requisitos, valida e tira as dúvidas com o cliente, e ou o documento já vai voltar ok ou com muitos ajustes, caso volte com muitos ajustes, é realizar as revisões, entender o motivo de cada alteração e realizar os ajustes

[Documento+de+Requisitos.docx](https://github.com/WanessaCarvalho378/requisitos-ti/files/12508080/Documento%2Bde%2BRequisitos.docx)

[Video 5.1 [Construção do Documento de Requisitos] Documentos de Requisitos.pdf](https://github.com/WanessaCarvalho378/requisitos-ti/files/12508084/Video.5.1.Construcao.do.Documento.de.Requisitos.Documentos.de.Requisitos.pdf)

</details>

<details>
<summary>Gerenciamento de requisitos</summary>

- Acompanhamento e controle para que se possa ao final garantir que o projeto será 
entregue de maneira adequada
- 1. Garantir sempre a versão atualizada do documento de requisitos para o time
- 2. Priorizar requisitos: Monitorar a priorização 
- 3. Avaliar mudanças

link geral importante: https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/guidances/concepts/requirements_management_8067CA83.html#Problem%20Analysis

Link para fluxo de trabalho muito bom: https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/capabilitypatterns/manage_the_scope_of_the_system_7E0B34E5.html

</details>
