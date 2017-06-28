# PopularMovies v1.0

An app to help users discover popular and recent movies.

<b>Note</b>: In order to build your own app, you must have your own API key. API key can be obtained from http://themoviedb.org to ```build.gradle:Module``` as 
```
buildTypes.each{
        it.buildConfigField 'String', 'MOBDB_API_KEY',"\"api_key\""
    }
```
Once you have your key you will need to update it in: FetchMoviesTask.java
Replace api_key with your own API KEY.<br />

Libraries Used : <br />
[Picasso](https://github.com/square/picasso)<br />
[Butterknife](https://github.com/JakeWharton/butterknife)<br />
[Retrofit](https://github.com/square/retrofit)<br />
[Glide](https://github.com/bumptech/glide)
