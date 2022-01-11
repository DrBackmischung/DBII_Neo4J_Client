mutation create($input: [MovieCreateInput!]!) {
  createMovies(input: $input) { 
    movies {
      title
      plot
      year
      actors {
        name
      }
    }
  }
}

{
  "input": [
    {
      "title": "ABAP - die Verfilmung",
      "plot": "Es war einmal eine etwas andere Programmiersprache...",
      "year": 2022,
      "actors": {
        "create": [
          {
            "node": {
              "name": "Kitty Blume"
            }
          }
        ]
      }
    }
  ]
}
