# Movie Database data

Filmdata i JSON-format från IMDb. Det finns sex oilka JSON-filer i [json-foldern](https://github.com/FEND16/movie-json-data/tree/master/json). Allt som allt är det cirka 500 titlar. Enjoy!

### Data

| JSON                             | IMDb source                                                                         | 
| :--------------------------------| :-----------------------------------------------------------------------------------|
|  movies-coming-soon.json         | [imdb](http://www.imdb.com/movies-coming-soon/?ref_=nv_mv_cs_4)                     | 
|  movies-in-theaters.json         | [imdb](http://www.imdb.com/movies-in-theaters/?ref_=cs_inth)                        |  
|  top-rated-movies-01.json        | [imdb](http://www.imdb.com/chart/top?ref_=nv_mv_250_6)                              |     
|  top-rated-movies-02.json        |                                                                                     | 
|  top-rated-indian-movies-01.json | [imdb](http://www.imdb.com/chart/top-indian-movies?ref_=nv_mv_250_in_7)             | 
|  top-rated-indian-movies-02.json |                                                                                     |

### Bilder  
Propertyn "poster" innehåller filnamnet på en bild som återfinns i [img-foldern](https://github.com/FEND16/movie-json-data/tree/master/img).
Om man vill länka till en extern bild istället finns det en länk i propertyn "posterurl".

### Struktur på JSON datan
```JSON
[
  {
      "title": "Get Out",
      "year": "2017",
      "genres": [
          "Horror",
          "Mystery"
      ],
      "ratings": [
          6, 6, 7, 6, 7, 9
      ],
      "poster": "MV5BNTE2Nzg1NjkzNV5BMl5BanBnXkFtZTgwOTgyODMyMTI@._V1_SY500_CR0,0,315,500_AL_.jpg",
      "contentRating": "R",
      "duration": "PT103M",
      "releaseDate": "2017-02-24",
      "averageRating": 0,
      "originalTitle": "",
      "storyline": "A young African American man visits his European American girlfriend's family estate where he learns that many of its residents, who are black, have gone missing, and he soon learns the horrible truth when another frantic African-American warns him to \"get out\". He soon learns this is easier said than done.",
      "actors": [
          "Daniel Kaluuya",
          "Allison Williams",
          "Bradley Whitford"
      ],
      "imdbRating": 8.0,
      "posterurl": "https://images-na.ssl-images-amazon.com/images/M/MV5BNTE2Nzg1NjkzNV5BMl5BanBnXkFtZTgwOTgyODMyMTI@._V1_SY500_CR0,0,315,500_AL_.jpg"
  }
]

```
