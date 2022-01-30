[
Eventos](https://www.zup.com.br/eventos)

Pesquisar

# Código Limpo: dicas práticas para turbinar a escrita, leitura e escalabilidade de um código

- [Mobile](https://www.zup.com.br/categorias/mobile) • 27 maio 2020

  

<iframe width="100%" height="83" scrolling="no" src="https://go.vooozer.com/embed/faa20a1c" frameborder="0" allowfullscreen="" style="box-sizing: border-box; max-width: 100%; width: 664px; margin: 0px; line-height: 1; border: none; height: 83px !important;"></iframe>

#### Neste artigo você vai ver:

- [Uncle Bob](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
- [Clean Code](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
- [Nomes são importantes](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
  - [Evite abreviações](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
  - [Passe a ideia central](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
  - [Não tenha medo de nomes grandes](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
  - [Isole as palavras de referências de negócio](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
  - [DRY (Don’t Repeat Yourself)](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
  - [Código limpo: funções simples e claras](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
  - [Regra do Escoteiro: deixe o código mais limpo do que você encontrou](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
    - [Refatorar o código deve ser um hábito.](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
- [Código comentado é bom?](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
- [PRINCÍPIOS S.O.L.I.D](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
  - [Tenha orgulho do seu código!](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)
  - [Vagas de desenvolvimento](https://www.zup.com.br/blog/codigo-limpo-dicas-praticas#texto-blog)

Todo código é uma sequência de ações que definimos para que a máquina execute algo, e muitas vezes escrevê-las pode parecer simples, mas com certeza você já se deparou com várias perguntas pelo processo.

Será que o nome desta variável ou método está ok? Será que poderia criar um método para determinado bloco de código ou até criar outras classes, refatorar? E tenho certeza que não param por aí.

### Uncle Bob

Sentindo esse problema e alguns outros relacionados em diversos ecossistemas, Robert C. Martin ou também conhecido popularmente como “Uncle Bob”, escreveu um livro chamado Clean Code.

Dentro do Desenvolvimento ágil de software, o Clean Code é considerado por muitos programadores como um livro de cabeceira, nele é possível encontrar formas de como escrever códigos bons e como transformar um ruim em um bom, e muitas outras coisas essenciais como, aplicações de teste de unidade, tratamento de erros e muitos outros estudos de caso importantes para o dia a dia de qualquer programador.

### Clean Code

O Clean Code se tornou uma filosofia de desenvolvimento cuja o principal objetivo é aplicar técnicas simples que visam facilitar a escrita e leitura de um código. Sua principal perspectiva é a de que **detalhes importam.**

Meu objetivo com este artigo é mostrar essa visão de maneira prática com dicas chave e também com algumas perspectivas pessoais, que por mais que sejam simples e muitas vezes ignoradas contribuem significativamente para que o código cresça de maneira limpa, saudável e escalável.

‍

> **Qualquer um consegue escrever código que um computador entende. Bons programadores escrevem código que humanos entendem. – Martin Fowler**



O ato de escrever código pode ser muitas vezes subestimado, mas ele é o princípio de tudo, a base e o que irá mover cada movimento positivo ou negativo até o nosso objetivo final e ao meu ver pode ser muito bem comparado à arte de escrever um livro, artigos científicos, letras de música, etc, e ainda com o plus de dificuldade, que são várias pessoas trabalhando em conjunto.

‍

→ **Um código limpo é a composição de diversas características e aqui vou tentar te passar algumas dicas importantes.
‍**

## Nomes são importantes

#### Evite abreviações

Em muitos casos procuramos praticidade, e junto com uma ideia de negócio ou algo simplesmente que se tornou recorrente, denominamos abreviações para agilizar nossa escrita. **Abreviações podem ser um atalho para um caminho mais longo** na maioria dos casos, **elas dificultam entendimentos de negócio para novos membros do time ou até simplificam contextos** que não deveriam ser simplificados ou menosprezados.

Seu uso é algo muito fácil de se tornar uma rotina e se alastra rapidamente pelo código de todo o projeto.
‍

#### Passe a ideia central

Identificar a ideia central e a intenção de um contexto pode ser um grande exercício de reflexão que pode nos trazer uma evolução constante. o ato de nomear uma variável, método ou classe é algo prático e simples que podemos utilizar diariamente. Entenda a responsabilidade do que você cria e os contextos que ele se envolve, muitas vezes uma nova implementação pode mudar essa ideia central e é importante sempre atualizar sua ideia central através do nome, que é a primeira coisa que o próximo desenvolvedor ou você mesmo irá ter contato no futuro.



#### Não tenha medo de nomes grandes 

Um nome longo e descritivo é melhor do que um nome pequeno e enigmático e ainda melhor que um comentário longo e descritivo.

Muitas pessoas têm medo de criar nomes grandes, e claro que é sempre passível a reflexão, “será que esse nome ta grande porque ele tem muita responsabilidade? ” e muitas outras, mas é importante nomear um contexto devidamente dando um motivo claro para sua existência e expondo suas relações melhorando sua compreensão e posteriormente sua manutenção.
‍

#### Isole as palavras de referências de negócio

Palavras de referências de negócio são praticamente inevitáveis dentro de um projeto, mas procurar evitá-la ou isolá-la pode ser uma prática importante que irá facilitar o desacoplamento e permitirá abstrair mais casos em seu código. Procure achar uma referência mais genérica do mundo externo ao negócio e especialize o que precisar.

Para finalizar, é recomendável que:
‍

- **Métodos ou Funções:** devem ter nome de verbos (gosto bastante de utilizar do infinitivo), para assim, expressar quais são suas finalidades;
- **Classes e Objetos:** deve ser utilizado substantivos.

‍

### **DRY (Don’t Repeat Yourself)**

Os dedos do CTRL+C choram, mas o princípio DRY “Não se Repita” é um importante princípio base criado por Andy Hunt que procura reduzir a duplicação de código e os problemas oriundos dessa prática. A definição formal desse princípio diz:

> “Cada parte do conhecimento deve ter uma representação única, não ambígua e definitiva dentro do sistema.”



O DRY, como muita gente pensa, não se trata apenas de “não vamos repetir essa linha código”, mas está também muito ligado à outra prática importante, o “Single Source of Truth”, Única Fonte de Verdade, ou seja, você conseguir manter uma única fonte de verdade no que se refere a um pedaço de conhecimento ou contexto, isso faz com que o que estamos modificando não seja só para não repetir código, mas também criar contextos e conhecimentos reutilizáveis de modo mais contextual e significativo, facilitando coisas simples como nomeação de métodos, variáveis, classes e até aplicar design patterns que resultarão em estruturas elegantes, organizadas e escaláveis.

Dessa forma, quando você estiver desenvolvendo e desconfiar que está usando um código semelhante (duplicado) mais de uma vez, pense um pouco no que aquilo significa para osistema e decida de que forma faz mais sentido ele ser implementado e exposto adequadamente, seja uma classe privada reutilizável, classe pública utilitária (classe Helper) ou utilizar algum design pattern para criar uma estrutura.

É importante também pensarmos em alguns fatores que devemos considerar quando estamos construindo essas soluções.
‍

→ Seja fácil de se manter, adaptar e se ajustar às alterações de escopo;

→ Seja testável e de fácil entendimento;

→ Seja extensível para alterações com o menor esforço necessário;

→ Que forneça o máximo de reaproveitamento;

→ Que permaneça o máximo de tempo possível em utilização.
‍

**![❗](https://s.w.org/images/core/emoji/13.1.0/svg/2757.svg)** O DRY e suas outras práticas relacionadas são práticas fundamentais para evitar modificações em vários lugares e side effects não previstos que podem gerar vários fantasminhas no código. Experimente essa forma de pensar**.
‍**

**Sempre lembre-se da velha e boa orientação a objeto**

A Orientação a Objeto é um dos primeiros passos na programação na vida de vários Devs, por curiosidade, não foi o meu. Começando com o desenvolvimento de websites, onde o que importa são telas bonitinhas, sem muita importância do que tem por trás.

Eu descobri a importância da Orientação a Objeto ao longo do tempo, e com a necessidade, mas nunca é tarde para firmar ou revisar uma base dessas. Além disso, nos dias atuais as coisas mudaram e até para pequenos sites e linguagens mais funcionais como Javascript é importante que você se lembre dessa base e saiba como aplicar seus diversos princípios.

Quando programamos com a orientação a objeto é importante lembrar dos princípios que foram criados e que permitem exercer muitas práticas saudáveis no design do seu código.

Não tenha medo de tentar utilizar-se da abstração, encapsulamento, herança, composição, modularidade e polimorfismo para algum contexto. Muitos desses princípios muitas vezes são esquecidos, mas eles podem resolver de maneiras extremamente elegantes o seu problema, sem falar de como são práticos. Quanto mais tentamos aplicar, mais descobrimos possibilidades.

Cuidado aqui com o “[overengineering](https://www.youtube.com/watch?v=59kM-awaEw0&list=PLkX9oUrQ1ev4qEfn1nmeNtSnKtHLYDcmZ&index=6)”, ou seja, fazer uma evolução precoce, abstrair demais algo que poderia ser simples.

Importante analisar até que ponto o que você está fazendo é realmente necessário e se seu caso de software não pede uma implementação mais direta e simples. Não tenha medo de simplificar o que você complicou, esse também é um grande exercício.

### Código limpo: funções simples e claras

O código é uma história. Então, como um bom autor, devemos nos preocupar em como contá-las. Para estruturar um código limpo, é necessário criar funções simples, pequenas e claras. E ao meu ver existem 2 pontos claros que devemos ter atenção nas funções, aleḿ de claro seu nome, seriam seus argumentos e quantidade de linhas, nesses casos se houverem muitos em algum desses dois, já é um sinal de que o contexto desse método pode ser desacoplado e movido para outro lugar ou simplesmente criar um nova função.

Segundo Tio Bob, a primeira regra das funções é a seguinte:

> “A primeira regra das funções é que tem de ser pequenas. A segunda regra das funções é que elas têm de ser ainda menores.” Robert C. Martin

Bem comum também na programação funcional, a utilização de funções puras para satisfazer essas regrinhas se tornou algo bem comum para mim, como conceito, uma função pura é aquela que não provoca efeitos colaterais, ou seja, ela não muda qualquer estado na aplicação, simplesmente recebe algo, processa e retorna algo.

Mas não é só isto, ela precisa sempre gerar o mesmo resultado com os mesmos argumentos, ou seja, ela precisa ser completamente determinística. Claro que nem sempre dá pra satisfazer determinada lógica com esse tipo de função, mas ela faz com que possamos criar menos métodos centrais e que contém a lógica necessária.

Com isso em mente, executar apenas 1 papel dentro das funções e fazer com que elas sejam altamente testáveis se torna fácil. 

Outro ponto bem importante sobre funções pequenas são para encontrar bugs, muita gente pensa que existe um mínimo de linhas pra ser motivo para se criar um novo método, mas não, é importante pensar que criar um novo método não serve só pra não repetir código, um método novo pode ter até uma linha, mas a criação desse método é importante para isolar contextos pontuais, facilitar para que seja encontrado e expôr devidamente sua significância, sendo assim, fácil de testar e localizar.

Imagina que essa 1 linha desse método estivesse solta dentro de outro método que faz muitas outras coisas. Seria muito mais difícil identificá-lo e entender o que ele faz, concorda?



### Regra do Escoteiro: deixe o código mais limpo do que você encontrou

É comum termos que alterar um código fonte escrito por outras pessoas. Em muitos casos, nós mesmos somos os responsáveis. Acontece que esse código pode ter sido criado há muito tempo, em um contexto diferente. Mal lembramos em que momento o escrevemos. Independente de quem seja o “pai da criança”, a alteração deve ser realizada e essa seria uma boa oportunidade para se fazer pequenas melhorias.



#### Refatorar o código deve ser um hábito.

É uma atividade essencial para a modernização do software e deve ser feita com muito cuidado para não impactar as funcionalidades existentes. Pensamentos como “isso é perder tempo valioso” ou “se está funcionando melhor não mexer” são prejudiciais a longo prazo. **O melhor é refatorar o mais rápido possível** enquanto a lógica ainda está fresca na cabeça.

Entretanto, existem mudanças que interferem diretamente na lógica da aplicação. Para realizá-las, é preciso ter alguma garantia de que essas mudanças não irão quebrar o sistema.

**Uma forma de ter essa garantia é através de** [**testes**](https://www.zup.com.br/blog/teste-manual-vs-teste-automatizado). Caso seu sistema não tenha um conjunto confiável deles, o primeiro passo para ”deixar esse mundo um pouco melhor do que quando você o encontrou” seria criar alguns testes. Com uma bateria de testes nos resguardando, poderemos realizar alterações no código com a confiança de que não alteramos o comportamento esperado do sistema e não geramos novos bugs.

[![img](https://secureservercdn.net/198.71.233.31/36q.76e.myftpupload.com/wp-content/uploads/2021/03/5eb45649151afb4ffbaf0824_newsletter.png)](https://www.zup.com.br/newsletter)



## Código comentado é bom?

Com certeza a galera mais velha na programação já ouviu bastante que “Código bom é código comentado”.

Eu, particularmente, sou defensor de um **código não comentado**, ou com o mínimo de comentários possível, salvo para documentações e bibliotecas públicas, mas mesmo assim existem ferramentas de documentação muito melhores que um comentário.

Eu nunca entendi bem a necessidade de precisar escrever de novo o que aquela lógica, variáveis, métodos já deixavam bem explícitos e foi uma grande felicidade quando li esse tópico no livro de Tio Bob. Mas veja bem, não vou generalizar, acredito que certos códigos realmente são difíceis de serem expressivos, mas nada tira a importância de que ele precisa ser explícito e que podemos brigar por esse ponto.
‍

**Pontos rápidos:**

- Nada garante que em uma nova modificação que outro desenvolvedor fez no método/classe o comentário foi atualizado, forçando o desenvolvedor a se preocupar além a implementação mas também com o comentário, perdendo tempo e produtividade.
- Procure deixar o seu código mais explícito e legível invés de adicionar comentário.
- Lembre-se, testes também são uma forma de documentar e podem deixar um código muito mais explícito de que com comentários, além de forçar sua manutenção em caso de modificação e aumentar a garantia do mesmo.



## PRINCÍPIOS S.O.L.I.D

O SOLID é um conjunto de princípios que auxiliam o desenvolvedor na programação. Este é um assunto super relacionado e essencial para construção de qualquer código limpo principalmente para tratar uma evolução importante em qualquer projeto e, claro, ele não poderia ficar de fora deste artigo.

Fizemos recentemente, aqui na Zup, uma [**aula aberta sobre o Solid**](https://www.youtube.com/watch?v=rnWPWU7XKeg) **com Mario Rezende**, um dos nossos desenvolvedores especialistas, que na minha opinião é super claro e mais completo do que qualquer citação que possa colocar aqui. Vale muito a pena assistir!



### Tenha orgulho do seu código!

O [Clean Code](http://xn--o clean code  uma das obras do mundo da programao que vale a pena sempre ser revisitada e pra resumir um pouco essa minha ltima decidi escrever esse post-vgr09cpll5k.xn-- um cdigo limpo deve ser eficiente%2C simples%2C direto ao ponto%2C ter mnimas dependncias%2C no tem duplicaes%2C fcil de corrigir%2C precisa ter padres definidos%2C tem fcil leitura e entendimento%2C  elegante e coberto de testes-61xsd02aq3b1uxe02b56covxb.xn-- uma frase michael feathers (autor do livro legacy code) pode resumir e complementar bem em uma frase o que seria em sua raiz o cdigo limpo-its.xn--  um cdigo limpo sempre parece que foi escrito por algum que se importava-h2i87g5618u1fa/) é uma das obras do mundo da programação que vale a pena sempre ser revisitada.

**Um código limpo deve ser eficiente, simples, direto ao ponto, ter mínimas dependências**, não tem duplicações, é fácil de corrigir, precisa ter padrões definidos, tem fácil leitura e entendimento, é elegante e coberto de testes.

O Michael Feathers (autor do livro Legacy Code) resumiu e complementou em apenas uma frase o que seria em sua raiz o Código Limpo.

> “Um código limpo sempre parece que foi escrito por alguém que se importava” – Michael Feather



E se importar com um código é estar atento aos detalhes, tomar cuidado na hora de escrevê-lo com os tópicos que comentamos neste artigo e explorar muitos outros que também são importantes. No fim, a sensação de orgulho e dever cumprido é recompensadora! Como um artista que finalizou um belo quadro ou livro. O que compensa todo o trabalho duro durante o desenvolvimento!



Espero que o o artigo seja útil e ajude a melhorar o seu desempenho na hora de programar. **Não esqueça de deixar nos comentários suas dúvidas, críticas e opinião sobre o assunto** pra continuarmos a discussão e aprender ainda mais.

‍

*Algumas referências práticas e rápidas para complementar o tema:*

- [SOLID – Teoria e Prática](https://www.youtube.com/watch?v=Q2QdkiX6p_Y)
- [SOLID – Programação Orientada a Objetos](https://www.youtube.com/watch?v=rnWPWU7XKeg)
- [Principios SOLID](https://www.youtube.com/playlist?list=PLixbMfnU6RAnPKJ2O-uP1SeYedzQiMvFy)
- [Becoming a better developer by using the SOLID design principles by Katerina Trajchevska](https://www.youtube.com/watch?v=rtmFCcjEgEw)
- [Clean Code: SOLID – Beau teaches JavaScript](https://www.youtube.com/watch?v=XzdhzyAukMM)
- [Série Felipe Deschamps](https://www.youtube.com/watch?v=9w3o9NHXqu0&list=PLMdYygf53DP5Sc6yFYs6ZmjsuuA2fu0TK)
- [Clean Code // Dicionário do Programador](https://www.youtube.com/watch?v=ln6t3uyTveQ)
- [[Online | NerdGirlz\] Código Limpo: Boas práticas de Programação](https://www.youtube.com/watch?v=4neQ7h2_Odw)
- https://www.alura.com.br/artigos/o-que-e-clean-code
- https://dextra.com.br/pt/clean-code/
- https://pt.slideshare.net/rodrigokono/boas-prticas-tcnica-para-um-cdigo-limpo-clean-code
- https://www.infoq.com/br/articles/clean-code-book-review/
- https://www.devmedia.com.br/clean-code-desenvolvimento-com-qualidade/30717
- http://www.macoratti.net/16/04/net_dry1.htm
- https://becode.com.br/clean-code/
- https://imasters.com.br/desenvolvimento/a-falsa-impressao-de-um-bom-codigo‍

‍