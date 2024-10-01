# Ronin Ecosystem Projects

This public repository is a collection of projects that are part of the Ronin ecosystem.

## How to contribute

1. Fork this repository,
2. Create a directory with the name of your project in `/projects`.
3. Add your logo in PNG format `logo.png`. (Less than 2 MB, 1:1 ratio, min 256x256 and max 1024x1024 px size)
4. Create `data.json`, using the format below.
5. Open a Pull Request from the fork to this repository.
6. A GitHub workflow will automatically check the validity of the changed / added files, please follow the bot's instructions if the validation fails.
7. After the validation passed, a team member will merge the PR.

## Use Case & Best Practices

Contract addresses for your project can be queried by analytics/indexing sites. Ensure that only relavant contracts are submitted & sufficiently labelled.

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
  "categories": [
    "bot",
    "dao",
    "finance",
    "game", 
    "nft",
    "tool",
    "other"
  ],
  "email": "(optional) myemail@mail.com",
  "social": {
    "x": "(optional) https://x.com/...",
    "telegram": "(optional) https://t.me/...",
    "discord": "(optional) https://discord.gg/...",
    "facebook" : "(optional) https://www.facebook.com/...",
    "instagram" : "(optional) https://www.instagram.com/...",
    "linkedin" : "(optional) https://www.linkedin.com/...",
  }
}
```