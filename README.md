[[READ IN ENGLISH]](https://github.com/MultiPtero/Public-Data/tree/main?tab=readme-ov-file#MultiPtero%27s%20Public%20Data)

# Datos públicos de MultiPtero
> Este repositorio es para mostrar datos públicos como nombres de Hostings relacionados al proyecto o que nos apoyan de alguna u otra forma. 
## ¿Eres dueño de un Hosting y quieres que tu Hosting aparezca?
Pues, sigue este formato en una Pull Request al archivo hostings.json:
```json
{
    "name": "Cool Hosting Name",
    "description": "Your description goes here",
    "logo": "https://cdn.cool-hosting.com/logo.webp",
    "shortname": "cool",
    "tags": ["free", "paid", "america", "europe"],
    "links": {
      "panel": "https://panel.cool-hosting.com",
      "dash": "https://dash.cool-hosting.com",
      "discord": "https://discord.gg/cool-hosting",
      "website": "https://cool-hosting.com"
    }
}
```
> [!IMPORTANT]
> El dato `shortname` es un nombre que debe ser unico y solo debe ser **UNA PALABRA**. En caso de que sea mas de una palabra, el nombre se cortará a la primera palabra para evitar problemas en el sistema.
¿No tienes alguno de los requisitos? ¡Puedes dejar la opción en `null` y no se mostrará en la web! Ejemplo:
```json
{
    "name": "Cool Hosting Name",
    "description": "Your description goes here",
    "logo": "https://cdn.cool-hosting.com/logo.webp",
    "shortname": "cool",
    "tags": ["free", "paid", "america", "europe"],
    "links": {
      "panel": "https://panel.cool-hosting.com",
      "dash": null, //No tenemos Dashboard
      "discord": null, //No tenemos discord tampoco
      "website": "https://cool-hosting.com" //Tenemos web
    }
}
```

# MultiPtero's Public Data

This repository showcases public data, such as the names of hostings associated with or supporting the project in some way.

## Are you a hosting owner and want your hosting to appear here?

Simply follow this format and make a Pull Request to the `hostings.json` file:
```json
{
    "name": "Cool Hosting Name",
    "description": "Your description goes here",
    "logo": "https://cdn.cool-hosting.com/logo.webp",
    "shortname": "cool",
    "tags": ["free", "paid", "america", "europe"],
    "links": {
      "panel": "https://panel.cool-hosting.com",
      "dash": "https://dash.cool-hosting.com",
      "discord": "https://discord.gg/cool-hosting"
    }
}
```

Don't meet all the requirements? You can leave an option as `null`, and it won't be displayed on the website! Example:
```json
{
    "name": "Cool Hosting Name",
    "description": "Your description goes here",
    "logo": "https://cdn.cool-hosting.com/logo.webp",
    "shortname": "cool",
    "tags": ["free", "paid", "america", "europe"],
    "links": {
      "panel": "https://panel.cool-hosting.com",
      "dash": null,
      "discord": null,
      "website": "https://cool-hosting.com"
    }
}
```