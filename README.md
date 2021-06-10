<h1 align="Center">Arquitetura MVC</h1>

![MVC](https://i1.wp.com/mahalo-studio.com/wp-content/uploads/2020/05/MVC-Design-Pattern-Mahalo-Studio-Marbella.jpg?fit=1024%2C683&ssl=1&is-pending-load=1)



## O que é?

MVC é um ***padrão de arquitetura de software*** que ajuda na velocidade entre as requisições feitas pelo usuario e também garante mais segurança comparado com a tecnica de usar apenas o sistema de rotas para determinar as funções e regras de negócio. O padrao de arquitetura MVC é formado por 3 componentes, tais eles chamados de:

- Model ou Modelo
- View ou Visão
- Controller ou Controlador

Os nomes dos componentes ja traz uma leve ideia de como funciona,mas mais a frente trarei mais informações.

## Model

Model é um componente que rege os modelos de negócio daquela aplicação, ele gerencia os dados e a lógica por meio das regras de negócio antes criadas. Recebendo dados vindos do controlador ele se comunica também com o banco, ao criar uma aplicação e utilizando a arquitetura você verá como ele se comunica entre o controlador e o banco.

## View

View é a camada visual, aquela que é apresentada ao monitor do cliente ou aquele que utiliza, ela renderiza tudo que vem em dados, ela captura o que o usuario pede e também faz a comunicação entre os o controlador e o próprio usuario. Tida como a linha de frente do usuario, ela deve apenas conter a parte grafica feita, como botões, mensagens, etc.


## Controller

O intermediador entre o View e os Models, ele faz toda a parte de controle sobre tudo oque passa para view e model e também tudo que vem dos mesmos, ele garante também a segurança, pois sem ele, as informações não teriam um mediador e passariam direto ou seriam feitas na propria view, que poderia trazer problemas futuros ja que alguma técnica poderia ser feita para visualizar e manipular os dados.

<h1 align="center">A comunicação entre os componentes</h1>

A forma como os componentes se comunicam eu diria que é retilínea. O primeiro passo é a interação do usuario com a view, que passa dados e requisições para o controlador, nele, é feita o direcionamento dos dados para o model, que aplica as regras de negócio e valida, entregando novamente ao controlador, que então envia uma resposta ao view, mostrando então uma visualização daquilo para o usuário.

<h1 align="center">Conclusão</h1>

Sem duvidas a arquitetura MVC é uma das mais usadas hoje em dia em diversas aplicações de tipos e funcionalidades diferentes, muito escolhida por suas vantagens na questão de eficiência e segurança, além da sua simplicidade de entendimento, já que, os seus conceitos não são tão complexos e entendendo eles você já pode começar a utiliza-la e ver a diferença acontecer na sua frente!

<h1 align="center">Links de Estudo</h1>

- DevMedia: ![Introdução ao Padrão MVC](https://www.devmedia.com.br/introducao-ao-padrao-mvc/29308#Introducao)
- Lewagon: ![O que é padrão MVC? Entenda arquitetura de softwares!](https://www.lewagon.com/pt-BR/blog/o-que-e-padrao-mvc)
- TreinaWeb: ![ O que é MVC? ](https://www.treinaweb.com.br/blog/o-que-e-mvc)
- DevMedia: ![Criando Aplicações com MVC em Java](https://www.devmedia.com.br/criando-aplicacoes-com-mvc-em-java/18021)
- DevMedia: ![Conceito de MVC e sua funcionalidade usando o PHP](https://www.devmedia.com.br/conceito-de-mvc-e-sua-funcionalidade-usando-o-php/22324)

