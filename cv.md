## Andrei Osipik

####Frontend Developer (I hope)
***
####Contacts:
- **Discord:** osipikav#4680
- **E-mail:** osipik.av@yandex.by
- **Tel:** +375298009607
- **GitHub:** osipikav

####About myself:
I want to work Front-End Developer! 

####Skills and Proficiency:
- HTML5, CSS
- JavaScript Basics
- Git, GitHub
- VSCode

####Code example:
```
const personalMovieDB = {
    count: 0,
    movies: {},
    actors: {},
    genres: [],
    privat: false,
    start: function () {
      personalMovieDB.count = +prompt("сколько фильмов вы уже посмотрели?", '');
      while (personalMovieDB.count == '' || personalMovieDB.count == null || isNaN(personalMovieDB.count)) {
        personalMovieDB.count = +prompt("сколько фильмов вы уже посмотрели?", '');
      }
      },
     rememberMyFilms: function () {
      for (let i = 0; i < 2; i++) {
        const a = prompt('Один из последних просмотренных фильмов?', '');
        const b = prompt('На сколько оцените его?', '');
        if (a != null && b != null && a != '' && b != '' && a.length < 50) {
          personalMovieDB.movies[a] = b;
          console.log('hor');
        } else {
          alert('некорректные данные');
          console.log('pl');
          i--;
        }
      }
    },

```

####Work experience:
Nothing yet…

####Education and courses:
1. JS basics course Udemi
2. CSS, HTML  basics courses Yandex
3. JavaScript https://learn.javascript.ru/
####Language:
English  **A2**
