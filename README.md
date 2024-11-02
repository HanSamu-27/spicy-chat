![Preview](https://i.postimg.cc/hGG7mt4t/images-21.jpg)

# **Spicy - AI Characters**

**Spicy Chat is a simple module that is used to interact with artificial intelligence, whether it is celebrities or animated characters**

## **Installation**

```
npm i github: HanSamu-27/spicy-chat 
```

## Usage
```
const { spicy } = require('spicy-chat')

//The first is the character ID 
//The second is the message that is sent to the character 
//The third is the name of the User 
//Four is the language that is being used 
//You can get more character ids by going to: https://spicychat.ai/
spicy("d4c21ac9-602f-4c62-83b1-0547984df723", "Hello", "Samu", "en" ).then(cxf => {
if (cxf) {
console.log('🥡 Result:', cxf)
}})
```