# Ronin Ecosystem Projects

This public repository is a collection of projects that are part of the Ronin ecosystem.

## How to contribute

1. Fork this repository,
2. Create a directory with the name of your project in `/projects`.
3. Add your logo in PNG format `logo.png`.
4. Create `data.json`, using the format below.
5. Open a Pull Request from the fork to this repository.

### data.json format

```json
{
  "name": "Project Name",
  "description": "Project Description",
  "websites":[
    {
      "url": "https://project.com",
      "description":"Website description"
    },
    {
      "url": "https://support.project.com",
      "description":"Website2 description"
    }
  ],
  "contracts": [
    {
      "address": "0x1....",
      "label": "Contract name",
      "description": "Short contract description"
    },
    {
      "address": "0x2....",
      "label": "Contract name #2",
      "description": "Short contract description"
    }
  ],
  "categories": ["game", "finance"],
  "email": "(optional) myemail@mail.com",
  "social": {
    "twitter": "(optional) https://twitter.com/ID",
    "telegram": "(optional) https://t.me/ID",
    "discord": "(optional) https://discord.gg/ID"
  }
}
```