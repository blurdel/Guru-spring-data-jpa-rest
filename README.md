# Guru-spring-data-jpa-rest
Demo project for Spring Data JPA REST

Note: By adding spring-boot-starter-data-rest to the pom <BR> 
Spring automatically exposes endpoints via Repository Methods

http://localhost:8080/api/v1/beer


And you can directly call repository methods through the 'search' api

http://localhost:8080/api/v1/beer/search/findByUpc?upc=9122089364369

You just add the query parameters in Postman 'Parameters' tab
http://localhost:8080/api/v1/beer/search/findAllByBeerStyle?beerStyle=ALE
