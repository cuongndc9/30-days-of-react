## API get scheduling movie

| Route             |Method               |Params               |        Functions      |
|-------------------|:-------------------:|---------------------|-----------------------|
| /cinemas.php      |GET                  |None                 |Get cinema             |
| /locations.php    |GET                  |None                 |Get location           |
| /movies.php       |GET                  |None                 |Get movies             |
| /movies-coming.php|GET                  |None                 |Get movies coming      |
| /movie.php        |GET                  |`movieID`: ID movie  |Get infomation film    |
| /sessions.php     |GET                  |`cinemaID`: ID Cenema</br>`filmID`: ID movie</br>`startDate`: Date start</br>`endDate`: Date end    | Get sessions movie    |

## Usage

Example:
- `http://domain/cinemas.php`
 
- `http://domain/movie.php?movieID=4512`

- `http://domain/sessions.php?cinemaID=-1&filmID=123&startDate=2019-04-14&endDate=2019-04-19`


<!-- INSPIRATIONAL_QUOTE_START -->
![Image](https://github.com/user-attachments/assets/e5dd7943-9aef-4ee2-94a1-c411600f6674)
✍️
<!-- INSPIRATIONAL_QUOTE_END -->
