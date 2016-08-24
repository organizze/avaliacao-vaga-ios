# Teste de avaliação Vaga iOS - [Organizze](www.organizze.com.br)
--- 

O [Organizze](www.organizze.com.br), a solução de controle financeiro, está selecionando um Lead Developer iOS para assumir a frente do nosso querido aplicativo iOS :heart:.

Nosso aplicativo é feito em [RubyMotion](http://www.rubymotion.com/) que é a tecnologia base do nosso teste. 


### O Teste

Primeiro você deve fazer o download da versão Starter do RM [http://www.rubymotion.com/download/].

Instalar a rodar o RubyMotion é trivial para quem trabalha com um Mac.

Você irá construir uma aplicação em RubyMotion que irá consumir a [api do Organizze](https://github.com/organizze/api-doc).

Somente a parte iOS do RubyMotion nos interessa. Não se preocupe com Android e OSX. Apenas nosso app iOS utiliza o RM.

A aplicação tem os seguintes requisitos:

1 - Tela de Login com 2 inputs (email e token de acesso à api) para podermos testar a aplicação com qualquer conta do Organizze.

2 - Após efetuar Login com sucesso, mostrar uma tela de lançamentos, semelhante a do aplicativo iOS do Organizze atual, mas com apenas 2 items. A barra de navegação entre meses e a table view com os lançamentos.

3 - Deve ser implementado uma camada de persistencia da sua escolha. Além do token e do email de acesso que devem ser persistidos, os lançamentos a medida que forem sendo carregados na navegação entre os meses também devem ser persistidos. Não é necessário criar algo muito avançado aqui nessa camada de persistência. O Objetivo aqui é fugir um pouco do trivial que já existe nos [Exemplos do Rubymotion](http://www.rubymotion.com/developers/samples/) e sentir a capacidade de abstração e organização de código do candidato.

4 - A interface pode ser totalmente feita por código, construindo as UIView`s e os posicionamentos dos frames manualmente.

5 - Instalar pelo menos um CocoaPod na aplicação de sua escolha. Essa tarefa é para você, developer iOS, se sentir mais em casa. ;)

6 - O Design da Interface não faz parte do escopo da avaliação. Mas qualquer capricho a mais, sim. Minha sugestão é que você se preocupe com acabamendo da UI apenas se tiver resolvido os problemas fundamentais antes.

7 - Escrever testes em RubyMotion não está no escopo da avaliação, mas estará no seu dia a dia de trabalho. Não se preocupe com isso agora.


### Submissão da aplicação

O link do seu repositório gihhub com a aplicação deve ser enviado para o email felipe@organizze.com.br até as 23:59 do dia 29/08/2016. Próxima segunda. :-) Por favor nao divulgue esse seu repo para evitar cópias de outros candidatos.







