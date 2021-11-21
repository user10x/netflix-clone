```
fetchComedyMovies: curl -s https://api.themoviedb.org/3/discover/movie\?api_key\=4843a4735f67a364d1e2d1de399d8237\&with_eneres\=35 | jq ".results[].genre_ids"
```
```
popularMovies: curl -s https://api.themoviedb.org/3/discover/movie\?api_key\=4843a4735f67a364d1e2d1de399d8237 | jq
```
```
resultKeys: curl -s https://api.themoviedb.org/3/discover/movie\?api_key\=4843a4735f67a364d1e2d1de399d8237 | jq ".results[] | keys"
```
```
bacdropPaths: curl -s https://api.themoviedb.org/3/discover/movie\?api_key\=4843a4735f67a364d1e2d1de399d8237 | jq ".results[] | .backdrop_path"
```

```
base="https://api.themoviedb.org/3/discover/movie?api_key=4843a4735f67a364d1e2d1de399d8237"
curl "$base"
````
