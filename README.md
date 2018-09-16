### Создание бота

POST localhost:4000/api/v0/bots

```
{
  "bot": {
    "platform": "telegram",
    "uid": "bot_name",
    "creds":{
    	"token": "TOKEN"
    }
  }
}
```

