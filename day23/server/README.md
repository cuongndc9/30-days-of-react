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
<p>🇻🇳</p>
![Image](https://github.com/user-attachments/assets/9d3847b4-d01e-4e62-b18e-12706b955cf3)
<!-- INSPIRATIONAL_QUOTE_END -->
