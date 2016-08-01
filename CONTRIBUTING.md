#Guia de Contribuição

##Organização das Pastas

Como perceberam no [README](README.md) do repositório, a organização dos capítulos é feita por pastas e dentro das pastas tem os arquivos que são as explicações dos tópicos.

##Como começar?

Bom, se você quer cooperar com a tradução da documentação, basta você ir na seção de ```issues``` do repositório que fica bem aqui. Lá, você vai ver que as ```issues``` na verdade são os capítulos da documentação original.

Basta você entrar numa ```issue``` e comentar qual tópico ou quais tópicos você pretende ter a responsabilidade de traduzir. Pedimos que essa parte seja levada bem à sério, já que, uma vez separada a tradução do tópico para você, outra pessoa não irá fazer.

A partir do seu comentário, um dos nossos contribuidores vai colocar seu usuário na frente do tópico escolhido.

Depois disso, é só você ```forkar``` o nosso repositório e escrever suas traduções.

##Enviando as traduções

###Commits
Commitar apenas os arquivos que estão sendo modificados, NÃO utilizar ```git add .``` e SIM ```git add nome_arquivo```. Assim poderemos evitar possíveis conflitos na hora do PR.

###Pull request

Depois que tiver terminado suas traduções, você só precisa fazer um ```pull request``` para nosso repositório.

Em relação aos ```pull requests```, pedimos que sejam enviados da forma mais simples possível. O que queremos dizer é que seja enviando tópico por tópico. Dessa forma, tornamos o processo de revisão e correção mais dinâmico e mais rápido possível.

Ao criar um novo PR, seguir os padrões abaixo:

**1. Nome do PR:** Para um novo PR com sua tradução pronta para revisão, utilizar os termos a seguir como padrão para o nome do PR > **[Para Revisão] - [Número do Capítulo e ou subcapítulo]Nome do Capítulo**. Ex: 1.2 - The Importance of a Styleguide, ou 3.1.1 - Object–Extension Pointers.

**1.1 Nome do PR:** Caso seja solicitado correções em sua tradução, por favor, feche o PR atual, efetue as devidas correções, e, ao encerrá-las, crie um novo PR com os termos a seguir como padrão para o nome do PR > **[Correções] - [Número do Capítulo e ou subcapítulo]Nome do Capítulo**. Ex: 1.2 - The Importance of a Styleguide, ou 3.1.1 - Object–Extension Pointers.

**2. Conversation:** Mencionar o @lucasktrindade,@gabrielclima no PR

**Não é necessário linkar no README principal e também no README de cada capítulo.** Apenas enviem em seu PR o capítulo traduzido, conforme mencionado anteriormente.

Lembrando, não creim PR que possuam conflitos. Caso, ao criar seu PR seja encontrado algum conflito, por favor, resolvam os conflitos primeiramente antes de criar o PR. Só serão aceitos PR para revisão hábeis para merge, com confitos serão fechados imediatamente.


###Revisão

Em seguida, um de nossos contribuidores vai analisar todo o texto para ver se está tudo correto. Passando dessa parte, é feito um ```merge``` da sua tradução.
