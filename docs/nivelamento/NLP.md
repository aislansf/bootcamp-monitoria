# NLP 

Quando começamos a estudar sobre machine learning, diversos termos em inglês aparecem de uma só vez. Quanto mais nos aprofundamos nos assuntos específicos, mais palavras aparecem.

O Processamento de Linguagem Natural (PLN), mais conhecido pelo termo em inglês Natural Language Processing (NLP), é uma das áreas de machine learning que vem crescendo todos os dias. Ela está inserida no nosso cotidiano nas pesquisas que fazemos no Google, por exemplo, e faz a ponte entre a comunicação humana e a das máquinas.

Para fazer essa ponte, existem diversas técnicas aplicadas à nossa linguagem humana para que ela seja compreendida pelas máquinas. Termos como: corpus, fazer tokenização e normalização, aplicar técnicas para retirar ruídos, aplicar stemming e lemmatization… Nossa! É muita informação! Mas, vamos por partes.

Primeiro, vamos conhecer os conceitos básicos de NLP e depois passaremos para as técnicas, já que muitos desses termos são interligados. No final, você vai estar craque em termos de NLP.

## Conceitos
### Corpus
Palavra do latim que significa corpo. Refere-se ao corpo de um texto, que pode ser escrito ou falado, contendo um ou mais idiomas. Para representar uma coleção de textos, temos a palavra corpora, plural de corpus. Esta coleção de textos pode ter um tema específico ou temas gerais. Alguns exemplos de textos usados em NLP são: resenhas de filmes, comentários da internet, reviews de cursos, críticas à aplicativos online, e-mails, entre outros.

### Tokenization
Tokenização é o processo de dividir uma frase em palavras ou tokens individuais. Durante esse processo, pontuações e caracteres especiais são completamente removidos. É importante ressaltar que os tokens não são necessariamente apenas uma palavra.

Quando temos palavras compostas, elas podem ter significados totalmente diferentes, como: “beija-flor” e “segunda-feira”. De uma forma geral, tokenização é o ato de simplificar o corpus e prepará-lo para os outros estágios de processamento.

### Normalization
A normalização dos textos é feita para que o processo de análise seja mais preciso e tem a característica de manter um padrão com todas as letras maiúsculas ou minúsculas. Geralmente, a normalização é feita depois do processo de tokenização, onde podemos encontrar frases que são semelhantes e fazer a combinação entre elas, caso queiramos, independente das diferenças.

Um exemplo disso é quando encontramos as palavras “Terra” e “terra” que têm significados diferentes, já que uma se refere ao planeta e a outra ao chão/solo. Na normalização podemos combinar esses termos e utilizar apenas “terra”. Existem diversos prós e contras em todas as fases. Ao mesmo tempo que é possível ter uma melhor correspondência na hora da pesquisa, a confiabilidade geral da aplicação pode ter uma interferência por conta dessa mudança de letras maiúsculas e minúsculas.

### n-grams
n-gram é um tipo de modelo probabilístico usado para prever o próximo item de uma sequência na forma de um modelo de Markov. Em um contexto linguístico, o n-grams refere-se a uma sequência n de palavras. Como podemos perceber nos exemplos a seguir: “Estudando” tem um 1-gram (unigrama); na sequência “Estudando NLP” temos um 2-gram (bigrama); e em “Estudando Machine Learning” temos um 3-gram (trigrama).
