# Viktar Hushchin

## Software Ingineer

- Cell: +375(29) 399-25-41 - [groftblr@gmail.com](mailto:groftblr@gmail.com)

## Summary

Result-orientired software ingeneer with experiance building applications. Seeking a role building WEB applications for a well-established software company

## Skills

- HTML, CSS
- JavaScript, PHP
- JQuery
- PostgreSQL
- git (GitHub, GitLab)

## Code examples

```javascript
function getLoveTrianglesCount(preferences = []) {
  let count = 0;
  for (let index = 1; index < preferences.length - 1; index++) {
    let first = preferences[index - 1];
    if (first !== 0) {
      let second = preferences[first - 1];
      if (second !== 0) {
        let third = preferences[second - 1];
        if (+third === +index && first !== second) {
          count++;
          preferences[index - 1] = 0;
          preferences[first - 1] = 0;
          preferences[second - 1] = 0;
        }
      }
    }
    preferences[index - 1] = 0;
  }
  return count;
}
```

## Experience

### System administrator

#### 2013 - Present

##### "Bittechnoservice" LTD

Support for enterprise LAN and workstations (Windows).

- Development and maintenance of internal activity accounting system (PHP, JQuery, PostgreSql)
- Developed system sending SMS informarion to company clients (Delphi)

### System administrator

#### 2010 - 2012

##### Visuteh System

Support for enterprise LAN and workstations (Windows, Linux(Debian)).

## Education

Software Ingineer
2010 - 2012
Institute for Advanced Studies and Retraining of managers and industry specialists
Information technology, software computing and automated systems

English A2
