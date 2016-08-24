# Teste de avaliação Vaga iOS - [Organizze](www.organizze.com.br)
--- 

O [Organizze](www.organizze.com.br), a solução de controle financeiro, está selecionando um Lead Developer iOS para assumir a frente do nosso querido aplicativo iOS :heart:.

Nosso aplicativo é feito em [RubyMotion](http://www.rubymotion.com/) que é a tecnologia base do nosso teste.


### O Teste

Primeiro você deve fazer o download da versão Starter do RM [http://www.rubymotion.com/download/].

Instalar a rodar o RubyMotion é trivial para quem trabalha com um Mac.

Você irá construir uma aplicação que irá consumir a [api do Organizze](https://github.com/organizze/api-doc).

A aplicação tem os seguintes requisitos:

1 - Tela de Login com 2 inputs (email e token de acesso à api) para podermos testar a aplicação com qualquer conta do Organizze.

2 - Feito o Login, mostrar uma tela de lançamentos, semelhante a do aplicativo iOS do Organizze atual, mas com apenas 2 items. A barra de navegação entre meses e a table view com os lançamentos.

3 - Deve ser implementado uma camada de persistencia da sua escolha. Além do token e do email de acesso que devem ser persistidos, os lançamentos a medida que forem sendo carregados na navegação entre os meses também devem ser persistidos. Não é necessário criar algo muito avançado aqui nessa camada de persistência. O Objetivo aqui é fugir um pouco do trivial que já existe nos [Exemplos do Rubymotion](http://www.rubymotion.com/developers/samples/) e sentir a capacidade de abstração e organização de código do candidato.
