# Chat Widget

## Installation
### Website Integration

```html
<!-- Add this snippt as last tag in body -->
<script src="http://api.mehery.com/plugins/customer.js">
  {
    "entity" : "app",
    "channelId" : "MeherYWebsite",
    "config" : {
      //Optional Config   
    }
  }
</script>
```

## Config Options
```javascript
  {
    "entity" : "<entity>",
    "channelId" : "<channelId>",
    "config" : {
      "header.bg.color" : "#000",
      "header.text.color" : "#ffffff",
      "header.icon.url" : "https://cdn.jsdelivr.net/gh/mehery-soccom/mehery-web-dist@834bfa2c3b8060cac2ebcd7778758d6021be2dca/dist/logo/logo-tiny-o.png",
      "header.title.text" : "Support",

      "launcher.bg.color" : "#000",
      
      "messageList.bg.color" : "#ffffff",
      
      "sentMessage.bg.color" : "#4e8cff",
      "sentMessage.text.color" : "#ffffff",
      
      "receivedMessage.bg.color" : "#eaeaea",
      "receivedMessage.text.color" : "#222222",
      
      "userInput.bg.color" : "#f4f7f9",
      "userInput.text.color" : "#565867"
    }
  }

```


