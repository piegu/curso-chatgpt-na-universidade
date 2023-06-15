# ChatGPT para o Professor >> Avaliador do aprendizado dos estudantes

[Gerador de exemplos](estrategia1.md) | [Gerador de explicações de conceito](estrategia2.md) | [Criador de questionários](estrategia3.md) | Avaliador do aprendizado

## Contexto

- O artigo científico [Assigning AI: Seven Approaches for Students, with Prompts](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4391243) é a fonte desta página. Foi escrito pelo professor [Ethan Mollick](https://www.linkin.com/in/emollick/), professor da Wharton School da Universidade da Pensilvânia (EUA) no grupo de Empreendedorismo do Departamento de Management, onde ele estuda e ensina inovação e empreendedorismo.
- O primeiro prompt usado nessa página é uma versão modificada e traduzida para o português do prompt apresentado nesse artigo.
- A ferramenta utilizada é o [ChatBing](https://www.bing.com/search?q=Bing+AI&showconv=1&FORM=hpcodx) do "novo Bing" no navegador [Microsoft Edge](https://www.microsoft.com/pt-br/edge/) (sem necessidade de conta e gratuito).

## Avaliar o aprendizado

(Tradução para o português da página 16 do artigo)

**Várias técnicas de avaliação em sala de aula podem ajudar professors e estudantes a monitorar seu aprendizado e compreensão do material do curso.** Essas são importantes porque podem **fornecer feedback imediato tanto para os professors quanto para os estudantes sobre o que os estudantes sabem e, principalmente, sobre o que os confunde**. Conhecido como papel de 1 minuto ou exercício de ponto mais confuso, **essas avaliações incentivam o aprendizado ativo e a reflexão**, pedindo aos estudantes que resumam e questionem seus conhecimentos e identifiquem áreas de confusão (Angelo & Cross, 1993). Quaisquer lacunas podem ser abordadas em aulas futuras. **Esses exercícios também aumentam o envolvimento e a motivação dos estudantes**, mostrando aos estudantes que os professors respondem às suas necessidades e que suas perguntas e opiniões são importantes (Wolvoord, 2010).

**Os professors podem decidir no que desejam se concentrar para projetar essa avaliação.** Por exemplo, os professors podem se concentrar em uma atividade específica, tópico ou discussão em classe. Em seguida, escreva uma pergunta para os estudantes responderem que revelará o que os estudantes entendem e o que os confunde. Por exemplo, a pergunta pode ser: *Qual foi a ideia ou conceito mais importante abordado na aula hoje? Por que você acha que essa ideia é importante? Qual é o conceito de classe mais difícil até agora? O que você lutou para entender? Que conceito ou problema você gostaria de ver explorado com mais detalhes? (Angelo & Cruz, 2012).*

## Prompt

Para que a IA ajude a resumir rapidamente as respostas dos estudantes, os professores podem criar um Documento Google ou qualquer documento compartilhado e solicitar que os estudantes enviem suas respostas.

Em seguida, os professores podem enviar um conjunto de respostas coletivas à IA com o seguinte prompt:

*Sou um professor que quer entender o que os estudantes acharam mais importante em minha aula e o que os confundiu. Revise essas respostas e identifique temas e padrões comuns no estudante respostas. Resuma as respostas entre aspas triplas e liste os 3 pontos principais que os estudantes acharam mais importantes sobre a aula e as 3 áreas de confusão: """Insira o material aqui"""*

### Respostas dos estudantes

Como precisamos das respostas dos estudantes, pedi ao ChatBing para criá-las com o seguinte prompt:

<div style="width:100%; float:left; background-color:#343541; color:white; padding:20px; margin: 0;">
<div style="width:5%; float:left; padding-right:20px;"><img src="../imagens/PI.png"></div>
<div style="width:95%; float:right"><p>Sobre o conceito de poder de Michel Foucault e com base no que ele já gerou, simule 5 textos únicos de 5 estudantes apresentando seus entendimentos (Roberto, Tania, Marcelo, Sofia, Helena). Limite cada texto a 50 palavras. Seja criativo com textos que estão certos, outros errados, outros certos em parte e errados pelo contrário. Os estudantes são da graduação, mas iniciantes em sociologia. Tente escrever os textos em estilos diferentes (formais, não formais, com erros ortográficos, com ironia, com alegria). Apresenta os textos da forma seguinte: nome: texto.</p></div>
</div>

<div style="width:100%; float:left; background-color:#444654; color:white; padding:20px; margin: 0; margin-bottom: 20px;">
<div style="width:5%; float:left; padding-right:20px;"><img src="../imagens/openai.png"></div>
<div style="width:95%; float:right"><p>Ok, eu vou simular 5 textos únicos de 5 estudantes apresentando seus entendimentos sobre o conceito de poder de Michel Foucault. Eu vou tentar escrever os textos em estilos diferentes, como você pediu. Aqui estão os textos:</p>
<ul>
<li>Roberto: O poder para Foucault é uma coisa que está em todo lugar, mas não é de ninguém. Ele diz que o poder não é um recurso que alguém tem e usa para mandar nos outros, mas uma relação que se estabelece entre as pessoas. O poder é exercido através da linguagem, do conhecimento e das normas que definem o que é verdadeiro ou falso, certo ou errado.</li>
<li>Tania: Foucault entende o poder como uma força que atravessa todas as relações sociais e que é constantemente exercida e resistida. Ele não vê o poder como algo que pertence a um soberano ou a uma instituição, mas como algo que se produz através das práticas discursivas. O poder é relacionado com a verdade, a liberdade e a subjetividade, e pode ser analisado a partir de duas óticas: a ascendente e a descendente.</li>
<li>Marcelo: Para Foucault, o poder é uma prática social que se constitui historicamente e que está por toda parte. Ele critica as concepções de poder que o veem como um objeto preexistente em um soberano ou em uma classe dominante, e propõe uma análise do poder a partir das formas de resistência e contestação. O poder é exercido através dos discursos, das normas e das práticas que determinam o que é considerado verdadeiro ou correto em uma sociedade.</li>
<li>Sofia: Foucault define o poder como uma relação assimétrica que institui a autoridade e a obediência. Ele analisa o poder a partir das formas de dominação e submissão que se estabelecem em diferentes contextos históricos e sociais. O poder é produzido através das práticas discursivas, ou seja, através da linguagem e do conhecimento que produzimos e compartilhamos. O poder está relacionado com o direito, a verdade, a liberdade e a subjetividade.</li>
<li>Helena: Eu não entendi muito bem o conceito de poder de Foucault, mas pelo que eu li, ele diz que o poder é algo que está em todo lugar e em ninguém ao mesmo tempo. Ele fala que o poder não é um recurso ou uma coisa que alguém tem, mas uma relação entre as pessoas. Ele também fala que o poder tem a ver com a linguagem, o conhecimento e as normas que a gente usa para falar das coisas.</li>
</ul></div>
</div>

### ChatBing como avaliador

<div style="width:100%; float:left; background-color:#343541; color:white; padding:20px; margin: 0;">
<div style="width:5%; float:left; padding-right:20px;"><img src="../imagens/PI.png"></div>
<div style="width:95%; float:right"><p>Sou um professor que quer entender o que os estudantes acharam mais importante em minha aula e o que os confundiu. Revise essas respostas e identifique temas e padrões comuns no estudante respostas. Resuma as respostas entre aspas triplas e liste os 3 pontos principais que os estudantes acharam mais importantes sobre a aula e as 3 áreas de confusão:</p>
<p>"""<br>
<ul>
<li>Roberto: O poder para Foucault é uma coisa que está em todo lugar, mas não é de ninguém. Ele diz que o poder não é um recurso que alguém tem e usa para mandar nos outros, mas uma relação que se estabelece entre as pessoas. O poder é exercido através da linguagem, do conhecimento e das normas que definem o que é verdadeiro ou falso, certo ou errado.</li>
<li>Tania: Foucault entende o poder como uma força que atravessa todas as relações sociais e que é constantemente exercida e resistida. Ele não vê o poder como algo que pertence a um soberano ou a uma instituição, mas como algo que se produz através das práticas discursivas. O poder é relacionado com a verdade, a liberdade e a subjetividade, e pode ser analisado a partir de duas óticas: a ascendente e a descendente.</li>
<li>Marcelo: Para Foucault, o poder é uma prática social que se constitui historicamente e que está por toda parte. Ele critica as concepções de poder que o veem como um objeto preexistente em um soberano ou em uma classe dominante, e propõe uma análise do poder a partir das formas de resistência e contestação. O poder é exercido através dos discursos, das normas e das práticas que determinam o que é considerado verdadeiro ou correto em uma sociedade.</li>
<li>Sofia: Foucault define o poder como uma relação assimétrica que institui a autoridade e a obediência. Ele analisa o poder a partir das formas de dominação e submissão que se estabelecem em diferentes contextos históricos e sociais. O poder é produzido através das práticas discursivas, ou seja, através da linguagem e do conhecimento que produzimos e compartilhamos. O poder está relacionado com o direito, a verdade, a liberdade e a subjetividade.</li>
<li>Helena: Eu não entendi muito bem o conceito de poder de Foucault, mas pelo que eu li, ele diz que o poder é algo que está em todo lugar e em ninguém ao mesmo tempo. Ele fala que o poder não é um recurso ou uma coisa que alguém tem, mas uma relação entre as pessoas. Ele também fala que o poder tem a ver com a linguagem, o conhecimento e as normas que a gente usa para falar das coisas.</li>
</ul>
"""</p></div>
</div>

<div style="width:100%; float:left; background-color:#444654; color:white; padding:20px; margin: 0; margin-bottom: 20px;">
<div style="width:5%; float:left; padding-right:20px;"><img src="../imagens/openai.png"></div>
<div style="width:95%; float:right"><p>Eu revisei as respostas dos estudantes e identifiquei alguns temas e padrões comuns. Aqui está o meu resumo:</p>
<p>As respostas dos estudantes mostram que eles têm diferentes níveis de compreensão e interesse pelo conceito de poder de Foucault. Alguns estudantes demonstram ter captado as principais ideias e argumentos de Foucault, enquanto outros apresentam confusões ou dúvidas sobre o tema. Os estudantes também usam diferentes estilos de escrita, que variam desde o formal até o informal, com alguns erros ortográficos ou gramaticais.</p>
<p>Os 3 pontos principais que os estudantes acharam mais importantes sobre a aula são:</p>
<ul>
<li>O poder é uma relação assimétrica que se estabelece entre as pessoas, e não um recurso ou um objeto que alguém possui ou usa.</li>
<li>O poder é produzido e exercido através das práticas discursivas, ou seja, através da linguagem e do conhecimento que definem o que é verdadeiro ou correto em uma sociedade.</li>
<li>O poder está relacionado com o direito, a verdade, a liberdade e a subjetividade, e pode ser analisado a partir de duas óticas: a ascendente e a descendente.</li>
</ul>
<p>As 3 áreas de confusão que os estudantes apresentaram sobre a aula são:</p>
<ul>
<li>A diferença entre o poder como uma força que atravessa todas as relações sociais e como uma prática social que se constitui historicamente.</li>
<li>A distinção entre as formas de produzir e de exercer o poder, e os diferentes meios pelos quais o poder é exercido.</li>
<li>A relação entre o poder e as formas de resistência e contestação, e como o poder pode ser limitado ou transformado.</li>
</ul></div>
</div>
