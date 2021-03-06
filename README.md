[![Build Status](https://travis-ci.org/ourcities/multitude.png?branch=master)](https://travis-ci.org/ourcities/multitude)
[![CodeClimate](https://codeclimate.com/github/ourcities/multitude.png)](https://codeclimate.com/github/ourcities/multitude)
[![Coverage Status](https://coveralls.io/repos/ourcities/multitude/badge.png)](https://coveralls.io/r/ourcities/multitude)

Querido voluntário,

Nas próximas semanas, o Multitude será desativado e queríamos explicar para
você o motivo dessa decisão. Primeiro, fique tranquilo: vamos continuar
oferecendo oportunidades de ação de para nossos membros. No entanto, o
Multitude como você conhece vai acabar, e o motivo é bem simples: desenvolvemos
um jeito mais rápido e prático de conectar os cidadãos com as causas de seu
interesse. Agora, você só precisa preencher seu perfil na rede, que nossa
equipe vai selecionar e enviar as melhores oportunidades de ação diretamente
pra você, por email! Simples, não é?


Caso tenha alguma dúvida ou sugestão, mande um email para
[contato@nossascidades.org](mailto:contato@nossascidades.org) ou visite [nosso site](http://www.nossascidades.org).


## Setup
### DISCLAIMER: This project is no longer maintained.

To run Multitude, you need also to run [Meu Rio Accounts](http://github.com/ourcities/meurio_accounts)

1. Setup [Ruby on Rails environment](http://installrails.com/steps/choose_os)

2. Run `bundle exec rake db:create db:migrate db:test:prepare`

3. Set `MEURIO_DOMAIN` environment variable:

  `export MEURIO_DOMAIN="lvh.me:3000"`

4. Run meurio_accounts on port 3000:

5. Run Multitude on port 3001 with `rails s -p 3001`
