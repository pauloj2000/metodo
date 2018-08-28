# Rapid Application Development

## Integrantes 

- Paulo Junio Sales Rodrigues
- Augusto Borges de Moura
- Fernando Henrique Coimbra
- João Paulo Oliveira Cabral

## Planejamento:

  O trabalho será feito conforme a disponibilidade de cada um, o qual será acrescentado no documento, após ler as pesquisas e o que foi escrito anteriormente, cada um contribuindo conforme pesquisou também. Os slides serão criados após o término do documento de texto ou concorrentemente via documento Power Point ou similar de software livre, neste repositório, onde todos poderão atualizar os slides e contribuir com novos slides, até que seja completado todo o trabalho sobre RAD. 
  
  A sugestão é que cada inicialmente busque algumas referências sobre o assunto, 2 ou 3, e faça uma leitura das mesmas, e as adicione na seção 'Bibliografia e fontes' deste documento. Recomenda-se também fazer a leitura das fontes dos outros integrantes do grupo. 
  
  O escopo do texto é abranger uma visão ampla do RAD, de forma simplificada porém tentando cobrir amplamente todos os tópicos do RAD, de forma que tanto um leigo, quanto um profissional da área, possam compreender o artigo e todos os seus tópicos. 
  
  A idéia é que os slides só tenham início após a conclusão do texto. Desta forma poderemos basear o desenvolvimento da apresentação e dos nossos slides já com um texto completo e sólido sobre o RAD, de forma que os slides e a apresentação serão de alta qualidade e completos, se considerarmos nosso texto pronto, de alta qualidade e completo. 
  
  É permitido a qualquer um editar os textos, excluindo, modificando coisas, porém antes de excluir ou modificar seções que estão erradas ou se considera que poderia melhorar, o ideal é avisar os membros no nosso grupo do 'whatsapp', de forma que ninguém fique insatisfeito com a retirada ou edição de partes que o mesmo adicionou ao texto. 
  
  Avisar aos membros do grupo quando for editar o texto via github, já que se duas pessoas editarem ao mesmo tempo e depois fizerem o commit, haverá inconsistência nas informações e texto perdido. O ideal é que, se for editar, que seja um por vez, avisando assim os membros via grupo 'whatsapp'.
  
  De qualquer forma, não haverá nenhum problema, pois usando o GIT temos rastreabilidade dos commits e da informação referente ao texto que estava antes, portanto nada será perdido. Qualquer insatisfação, podemos recuperar o texto antigo e adicioná-lo novamente. Portanto o sugerido é que se faça como o RAD, que editemos o texto com eficiência e bom senso, porém sempre tentando evitar excluir informações sem antes consultar os membros do grupo, quando necessário, e avisando o grupo ao editar. 
  
  Lembrando a todos de que até mesmo este planejamento pode vir a ser editado posteriormente, conforme a necessidade, se algum membro do grupo desejar modificar ou discordar de qualquer ponto no planejamento. Tudo é livremente discutido e acordado, e todos têm o direito de sugerir e fazer modificações, seja no texto ou no próprio planejamento de como será feito o trabalho.
  
  O ideal é que todos contribuam igualmente, porém sabemos que isso nunca é possível em qualquer trabalho em grupo. Mas cabe a cada um utilizar do bom senso, e buscar fazer sua parte, de forma que possamos todos obter um bom trabalho e uma boa nota. Bom trabalho a todos!



## Introdução:

  Rapid Application Development, ou desenvolvimento de aplicação rápido, é um modelo de processo de software iterativo e incremental que enfatiza um ciclo de desenvolvimento extremamente curto (entre 60 e 90 dias). É considerada uma metodologia ágil de desenvolvimento de software. Foi criado em 1991, por James Martin, como necessidade devido ao modelo cascata estar antiquado e já não oferecer a eficiência necessária.

  Diferentemente dos métodos waterfall, RAD coloca ênfase em obter software já em funcionamento quanto antes melhor, e em obter feedback do usuário sobre este software, muitas vezes ainda imcompleto em todas suas funcionalidades, mas já com alguns módulos em funcionamento, de forma ao usuário poder já dar um feedback sobre, o que irá auxiliar muito a obter, no desenvolvimento, o que o usuário realmente quer.
  
  Desta forma o RAD é menos conversa, e mais ação. E muitos testes. Teste é uma parte extremamente importante na metodologia RAD. O planejamento extremamente rigoroso não é algo desejável no RAD, mas ainda assim a metodologia possui um passo-a-passo e fases para os projetos de desenvolvimento de software.
  
  
  
## Fase 1: Planejamento dos requisitos

  Cada parte de um software é construída por determinada razão, e o RAD começa tentando descobrir os requisitos, como qualquer outro projeto de software. A coleta dos requisitos e sua análise são de vital importância em qualquer projeto de software, e devem ser feitas cuidadosamente, pois sabe-se que um pequeno erro nos requisitos pode causar grandes problemas na frente. Deve-se descobrir o que o sistema está buscando realizar. É um ponto crítico no projeto.
  
  É recomendado que se faça pesquisas sobre o referente projeto, referentes por exemplo ao seu escopo, suas terminologias, por exemplo, ao se fazer um aplicativo sobre apostas esportivas, é necessário que todos na equipe possuam um mínimo de conhecimento sobre o mercado de apostas esportivas, sobre o futebol, e sobre o assunto da área, pelo menos dar uma pesquisada rápida e entender as terminologias básicas e seus significados.
  
  Deve-se avaliar as metas e expectativas do projeto, tanto em relação ao gerente, à equipe, e também ao cliente e os usuários. O que cada um espera do projeto? Quais os objetivos e como alcançá-los? 
  
  Deve-se obter a aprovação do stakeholder em relação aos requisitos, escopo e custo do projeto, e formas de pagamento, de forma que ambas as partes, cliente e empresa, além dos funcionários, fiquem satisfeitos e interessados em completar o projeto.
  
  Combinando elementos de planejamento de sistema, e fases de análise de sistema do 'System Development Life Cycle' (SDLC), usuários, gerentes, e a equipe de TI reúne, discutindo e definindo as regras de negócio, as necessidades do negócio, o escopo do projeto, constantes, e os requisitos do sistema. Quando há um consenso nos pontos chaves e aprovação do gerente de projeto para continuar o projeto, segue-se em frente.
  
  Após descobrir os requisitos do sistema, deve-se então fazer um certo planejamento e estimativa de tempo para o projeto. A partir de uma estimativa de tempo para o cumprimento de cada requisito, pode-se criar uma espécie de linha do tempo, com as fases do projeto, alocação de trabalho e de tempo das pessoas interessadas no projeto. É realizada nesta fase também a estimativa de recursos financeiros e a aprovação final do projeto, que irá seguir em frente caso a estimativa financeira seja adequada, levando em conta os recursos financeiros e recursos humanos da empresa.

## Fase 2: Design da interface de usuário e prototipação

  Após a definição do escopo do projeto e dos requisitos, é hora de começar o desenvolvimento, começando pela construção da interface de usuário, através de vários protótipos.
  
  Este é o básico da metodologia RAD, o diferencial da metodologia de certa forma, aquilo que a faz única e diferente das outras. Este começo, o começo através do desenvolvimento da interface de usuário, através de protótipos que são entregues ao cliente, e avaliados pelo mesmo, que então envia um feedback para os desenvolvedores, e estes então melhoram o protótipo de acordo com o feedback. Esta é a essência do RAD. 
  
  Nesta fase o cliente de certa forma também trabalha dura junto à equipe de desenvolvimento, disponibilizando seu tempo para testar e avaliar os protótipos feitos pela equipe de desenvolvimento e verificando se os seus propósitos e necessidades desejadas estão sendo atendidas, de maneira correta e o mais eficiente possível, da forma que o cliente queria.
  
  É um desenvolvimento de software customizável, onde os usuários testam cada protótipo do produto, a cada estágio de desenvolvimento, para garantir que está indo de acordo com suas expectativas. E assim a equipe vai melhorando e atualizando este protótipo de acordo com o que o cliente identifica que poderia melhorar ou que não está de acordo com o que ele queria, com suas necessidades.
  
  Todos os bugs e problemas são resolvidos num processo iterativo. Os desenvolvedores fazem o design de um protótipo, o próprio cliente testa este protótipo, e há então a comunicação do que funcionou e do que não funcionou, insatisfações ou sugestões de melhorias.
  
  Este método é bem interessante, pois ele permite que os desenvolvedores tenham essa oportunidade de atualizar e modificar, modelar o software, até que eles cheguem num design satisfatório, que o cliente deseja e gosta. É um aprendizado e experiência, tanto para a equipe de desenvolvimento quanto para o cliente, de tentar garantir que o design chegue num modelo ótimo e satisfatório, de forma que depois no futuro, após a adição gradual das funcionalidades, seja evitada qualquer falta de funcionalidade ou possível insatisfação em relação aos objetivos e interface gráfica do software. O objetivo é chegar no melhor produto final possível!
  
  Desta forma aos poucos a equipe de desenvolvimento pode também ir adicionando as funcionalidades aos protótipos, que inicialmente são apenas a interface de usuário. Dividindo em módulos de acordo com a funcionalidade, adicionando módulo por módulo, de uma forma que possam ser testadas partes separadas, facilitando assim o desenvolvimento, testes e posteriormente a integração, que é feita gradualmente conforme são adicionadas as funcionalidades.
  
## Fase 3: Construção

  Nesta fase é realizada...
  
## Fase 4: Testes e entregas

  Nesta fase é realizada...
  
## Vantagens do RAD

  As vantagens do RAD...
  
## Desvantagens do RAD

  As desvantagens do RAD...
  
## Quando é recomendado o uso do RAD

  O Rad é recomendado...
  
## Ferramentas auxiliares ao RAD

  As ferramentas do RAD são...
  
## Alternativas ao RAD

  As alternativas ao uso do RAD são...

## Bibliografia e fontes:

https://pt.wikipedia.org/wiki/Desenvolvimento_r%C3%A1pido_de_aplica%C3%A7%C3%B5es
https://blog.capterra.com/what-is-rapid-application-development/
https://www.lucidchart.com/blog/rapid-application-development-methodology
