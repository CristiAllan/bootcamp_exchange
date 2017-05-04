Sobre o projeto

Sistema incrivelmente simples para conversão de moedas.



About the project

Increadible simple exchange currencies sistem

Access: <a href="http://bootcamp-exchange.herokuapp.com/">Here</a>

Stack

  * Application
Dependencies

  * Fixer.io to consult currency rates
Getting Started

  * docker-compose build
  * docker-compose run --rm website rake db:create db:migrate
  * docker-compose up
Test

  * docker-compose run --rm website rspec