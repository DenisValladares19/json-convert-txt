# json-convert-txt

Libreria para convertir json a txt que esta basada en este proyecto de [github](https://github.com/vprince001/json_to_txt) en el cual solo se puede usar en el backend con Node Js, hice la adaptación para poder utilizar esta pero en el frontend

## instalación

```js
import jsonToTxt from "json-convert-txt";
```

## uso

```js
const dataString = jsonToTxt({ data: someData });
```

## Ejemplo de data que debe recibir

```json
[
  {
    "NAME": { "FIRST_NAME": "Debra", "LAST_NAME": "Burks" },
    "NUMBER": "880012XXXX",
    "EMAIL": "debra.burks@yahoo.com",
    "ADDRESS": "9273 Thome Ave., Orchard Park, NY - 14127"
  },
  {
    "NAME": { "FIRST_NAME": "Kasha", "LAST_NAME": "Todd" },
    "NUMBER": null,
    "EMAIL": "kasha.todd@yahoo.com",
    "ADDRESS": "910, Vine Street, Campbell, CA - 95008"
  },
  {
    "NAME": { "FIRST_NAME": "Tameka", "LAST_NAME": "Fisher" },
    "NUMBER": "880111XXXX",
    "EMAIL": "tameka.fisher@yahoo.com",
    "ADDRESS": "7693 Honey Creek St., Redondo Beach, CA - 90278"
  },
  {
    "NAME": { "FIRST_NAME": "Daryl", "LAST_NAME": "Spence" },
    "NUMBER": "990015XXXX",
    "EMAIL": null,
    "ADDRESS": "988 Pearl Lane!!! (Uniondale), NY - 11553"
  },
  {
    "NAME": { "FIRST_NAME": "Charolette", "LAST_NAME": "Rice" },
    "NUMBER": "720012XXXX",
    "EMAIL": "charolette.rice@msn.com",
    "ADDRESS": "107 ~ River Dr. `Sacramento`, \"CA\"      95820"
  }
]
```
