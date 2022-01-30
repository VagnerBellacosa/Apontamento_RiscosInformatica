# Conheça os 7 princípios do Clean Code

8 abril, 2020

![img](https://assets-blog.hostgator.com.br/wp-content/uploads/2020/10/snappy-profile-150x150.png)

Conteúdo por:

[**HostGator**](https://www.hostgator.com.br/blog/author/hostgator/)

![Clean-Code-Codigo-Limpo](https://assets-blog.hostgator.com.br/wp-content/uploads/2020/04/05-abril-Clean-Code-Codigo-Limpo.png)



Quem é programador certamente já se deparou com um código ruim, mal feito ou um título que não demonstrava efetivamente sua função. Esse cenário é mais comum do que se imagina e é justamente o que o Clean Code busca combater. Clean Code, ou Código Limpo, é uma filosofia de desenvolvimento de softwares que consiste […]

Quem é programador certamente já se deparou com um código ruim, mal feito ou um título que não demonstrava efetivamente sua função. Esse cenário é mais comum do que se imagina e **é justamente o que o Clean Code busca combater**.

Clean Code, ou Código Limpo, é uma filosofia de desenvolvimento de softwares que consiste em aplicar **técnicas simples que facilitam a escrita e a leitura de um código**. Tornando-o, assim, de fácil compreensão.

Neste artigo, você vai conhecer mais sobre essa expressão, incluindo sua origem, princípios e benefícios que oferece no dia a dia.

## Quando surgiu o termo Clean Code?

As técnicas do Clean Code apareceram pela primeira vez no livro “[Clean Code: A Handbook of Agile Software Craftsmanship](https://www.amazon.com.br/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)“, lançado em 2008. Ele foi escrito por Robert Cecil Martin, conhecido na comunidade como Uncle Bob. O autor atua na área de desenvolvimento desde 1970 e é um dos profissionais por trás do [Manifesto Ágil](https://voitto.com.br/blog/artigo/manifesto-agil?utm_source=parcerias&utm_medium=email&utm_campaign=backlinks), lançado em 2001.

Com seus longos anos de experiência, ele conseguiu perceber que **o** **gargalo principal no desenvolvimento de software estava justamente na manutenção**. Ou seja, um código mal escrito desde a sua primeira versão pode funcionar mas vai gerar prejuízos enormes.

O termo se disseminou pela comunidade de uma forma praticamente unânime. E um dos motivos pode ser justificado no seguinte dado: **a proporção média de leitura e escrita de códigos fonte é de 10 para 1**. Isso significa que as pessoas passam mais tempo tentando entender os códigos existentes do que efetivamente escrevendo novos códigos.

Com essa informação, é possível perceber que, muito além de uma boa arquitetura e boas práticas computacionais, o código fonte – que é aquilo que faz o computador executar nossos comandos – precisa de princípios. E é justamente isso que o Clean Code traz.

## Para que serve o Clean Code?

Um dos principais erros que os programadores cometem é acreditar que, uma vez que o código está pronto e funcionando, não precisa mais de revisão.

Porém, **um sistema nunca está totalmente finalizado**, sempre existe a necessidade de atualizações e novas funcionalidades. Além disso, o código envelhece e pode se tornar obsoleto. É nesse cenário que o Clean Code se encaixa.

A ideia por trás dos seus princípios é **tornar o desenvolvimento e a manutenção cada vez mais simples**. Afinal, um código sendo remendado por muito tempo torna-se impossível de manter, fazendo com que seja mais vantajoso iniciar do zero do que prosseguir em uma versão ruim.

Logo, o código limpo evita gastos desnecessários com manutenção e torna o software preparado para novas atualizações e melhorias.

## Conheça as 7 principais regras do Clean Code

No livro do Uncle Bob foram listadas algumas boas práticas para se obter um código limpo. Os principais são:

### 1 – Nomes são muito importantes

A definição de nome é essencial para o bom entendimento de um código. Aqui, não importa o tipo de nome, seja ele:

- Variável;
- Função;
- Parâmetro;
- Classe;
- Método.

Ao definir um nome, é preciso ter em mente **2 pontos principais**:

1. Ele deve ser preciso e passar logo de cara sua ideia central. Ou seja, deve ir direto ao ponto;
2. Não se deve ter medo de nomes grandes. Se a sua função ou parâmetro precisa de um nome extenso para demonstrar o que realmente representa, é o que deve ser feito.

### 2 – Regra do escoteiro

Há um princípio do escotismo que diz que, uma vez que você sai da área em que está acampando, você deve deixá-la mais limpa do que quando a encontrou.

Trazendo a regra para o mundo da programação, a regra significa **deixar o código mais limpo do que estava antes de mexer nele**.

### 3 – Seja o verdadeiro autor do código

O ser humano é acostumado a pensar de forma narrativa , portanto, o código funciona da mesma forma. Logo, ele é uma história e, como os programadores são seus autores, **precisam se preocupar na maneira com que ela será contada**.

Em resumo, para estruturar um código limpo, é necessário criar funções simples, claras e pequenas. Existem 2 regras para criar a narrativa via código:

1. As funções precisam ser pequenas;
2. Elas têm de ser ainda menores.

Não confunda com os termos “nome” e “função”. Como dissemos no primeiro princípio, nomes grandes não são um problema. Já as funções precisam ser as menores possíveis.

### 4 – DRY (Don’t Repeat Yourself)

Esse princípio pode ser traduzido como “não repita a si mesmo”. Essa expressão foi descrita pela primeira vez em um livro chamado *[The Pragmatic Programmer](https://www.amazon.com.br/Pragmatic-Programmer-journey-mastery-Anniversary/dp/0135957052/ref=sr_1_1?adgrpid=83827289160&gclid=Cj0KCQiAkKnyBRDwARIsALtxe7jrTiUiNk9hGK3mGBorko9v2qxjviskmvDcmYN0bCGVlx4Mt9ZtoicaAqBsEALw_wcB&hvadid=393020348123&hvdev=c&hvlocphy=1001706&hvnetw=g&hvpos=1t2&hvqmt=e&hvrand=1573397200582144760&hvtargid=kwd-302199567278&hydadcr=5655_10696963&keywords=the+pragmatic+programmer&qid=1581962840&sr=8-1)* e se aplica a diversas áreas de desenvolvimento, como:

- Banco de Dados;
- Testes;
- Documentação;
- Codificação.

O DRY diz que cada pedaço do conhecimento de um sistema deve ter uma representação única e **ser** **totalmente livre de ambiguidades**. Em outras palavras, define que não pode existir duas partes do programa que desempenhem a mesma função.

### 5 – Comente apenas o necessário

Esse princípio afirma que comentários podem ser feitos, porém, se forem realmente necessários. Segundo Uncle Bob, os comentários mentem. E isso tem uma explicação lógica.

O que ocorre é que, **enquanto os códigos são constantemente modificados, os comentários não**. Eles são esquecidos e, portanto, deixam de retratar a funcionalidade real dos códigos.

Logo, se for para comentar, que seja somente o necessário e que seja revisado juntamente com o código que o acompanha.

### 6 – Tratamento de erros

Tem uma frase do autor Michael Feathers, muito conhecido na área de desenvolvimento, que diz que as coisas podem dar errado, mas, quando isso ocorre, os programadores são os responsáveis por **garantir que o código continuará fazendo o que precisa**.

Ou seja: saber tratar as exceções de forma correta é um grande e importante passo para um programador em desenvolvimento.

### 7 – Testes limpos

Testar, na área de programação, é uma etapa muito importante. Afinal, **um código só é considerado limpo após ser validado através de testes –** que também devem ser limpos.

Por isso, ele deve seguir algumas regras, como:

- **Fast:** O teste deve ser rápido, permitindo que seja realizado várias vezes e a todo momento;
- **Independent:** Ele deve ser independente, a fim de evitar que cause efeito cascata quando da ocorrência de uma falha – o que dificulta a análise dos problemas;
- **Repeatable:** Deve permitir a repetição do teste diversas vezes e em ambientes diferentes;
- **Self-Validation:** Os testes bem escritos retornam com as respostas true ou false, justamente para que a falha não seja subjetiva;
- **Timely:** Os testes devem seguir à risca o critério de pontualidade. Além disso, o ideal é que sejam escritos antes do próprio código, pois evita que ele fique complexo demais para ser testado.



O Clean Code é um conceito que veio para ficar. Afinal, seus princípios solucionam com eficácia um dos principais problemas que grande parte dos projetos de sistemas enfrentam: a manutenção.

Gostou desse conteúdo? Dê uma passada no canal da galera do [Código Fonte TV](https://www.youtube.com/channel/UCFuIUoyHB12qpYa8Jpxoxow). Lá, você encontra um [vídeo](https://www.youtube.com/watch?v=ln6t3uyTveQ&list=PLVc5bWuiFQ8GgKm5m0cZE6E02amJho94o&index=10) muito bacana sobre o assunto.