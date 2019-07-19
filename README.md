# **Descrição**

Você deverá cirar um projeto simples consumindo a API [The Movie Database (TMDb)](https://www.themoviedb.org/).

# Recursos

API URL - [https://api.themoviedb.org/3/](https://api.themoviedb.org/3/)

API KEY - `1f54bd990f1cdfb230adb312546d765d`

- GET upcoming movies - [https://developers.themoviedb.org/3/movies/get-upcoming](https://developers.themoviedb.org/3/movies/get-upcoming)
- GET movie details - [https://developers.themoviedb.org/3/movies/get-movie-details](https://developers.themoviedb.org/3/movies/get-movie-details)

LANGUAGE - `pt-BR`

REGION - `BR`

POSTER URL - [https://image.tmdb.org/t/p/w154](https://image.tmdb.org/t/p/w154)

BACKDROP URL - [https://image.tmdb.org/t/p/w780](https://image.tmdb.org/t/p/w780)

# **O App**

O app precisa ter duas telas com as seguintes funcionalidades:

1. Primeira Tela

    A primeira tela é uma lista simples de 'upcoming movies'.

    Você precisará mostrar as seguintes propriedades:

    - `title`
    - `vote_average`
    - `release_date`
    - `poster_path`
    
2. Segunda tela

    Essa tela mostrará os detalhes do filme.

    Você precisará mostrar as seguintes propriedades:

    - `backdrop_path`
    - `genres`
    - `title`
    - `overview`
    - `vote_average`
    - `runtime`
    - `release_date`
    - `budget`
    - `revenue`

# Implementações Necessárias

- Use **Xamarin**
- Administre erros de network
- Paginação
- Pesquisa
- O projeto deve compilar e rodar sem erros

# Implementações opcionais

- Image caching
- Sharing

Você precisará submeter o projeto no GitHub [https://github.com/](https://github.com/) e nos enviar o link.

**Você terá pontos extras se implementar:**
- MVVM, MVP, ou similar
