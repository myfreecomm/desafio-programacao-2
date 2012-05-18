# Desafio de programação 2
A idéia deste desafio é nos permitir avaliar melhor as habilidades de candidatos à vagas de programador, de vários níveis.

Este desafio deve obrigatoriamente ser resolvido em **Ruby 1.9+**.

Este desafio deve ser feito por você em conjunto com o avaliador, durante sua entrevista na Myfreecomm.

## Descrição do projeto

Dado um arquivo Yaml no formato encontrado em *music.yaml* (incluído neste repositório), interprete ("parseie") este arquivo de modo que possamos acessar seu conteúdo em Ruby.

Seu código de parsing deve retornar um objeto que permita acessar os atributos dos dados usando o operador []:

```ruby
data["genres"].last["artists"].first["albums"].first["tracks"].last["name"] => "But Not For Me"
```

Este mesmo objeto também deve permitir acessar os atributos dos dados usando chamadas à métodos:

```ruby
data.genres.last.artists.first.albums.first.tracks.last.name => "But Not For Me"
```

### Referência

Este desafio foi baseado neste outro desafio: https://github.com/KeeperPat/music-yaml-parsing
