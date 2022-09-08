# OneBitExchange

Aplicação desenvolvida para conversão de moedas online, integrada com a API `https://currencydatafeed.com`

## Instalação

```
docker-compose build
```

## Iniciar o servidor

```
docker-compose up
```

## Acessar no navegador

http://localhost:3000

## Testes (Rspec)

```
docker-compose run --rm app bundle exec rspec spec/services/exchange_service_spec.rb
docker-compose run --rm app bundle exec rspec spec/requests/exchanges_request_spec.rb
```

## Desenvolvimento

- Ruby On Rails
- PostgreSQL
- Docker
- Docker Compose
- Yarn
- Testes: RSpec

## Deploy automatizado

- Codeship
- Heroku

## Aplicação disponível em produção:

https://onebitexchangeprod.herokuapp.com
