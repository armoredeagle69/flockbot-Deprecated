# FlockBot 1.3.6 release!



## **Languages** 

[Languages] Added 16 new languages and removed a few. More coming soon! Hindi, Turkish, Irish, Polish to be updated as well.
```
+ Bulgarian
+ Czech
+ Dutch
+ English-GB
+ Estonian
+ Finnish
+ Greek
+ Hungarian
+ Italian
+ Japanese
+ Latvian
+ Lithuanian
- Arabic 
- Korean
```




## **Coding**
> - [Database] Updated bot to MongoDB fully - @MrQuartz#1001
> - [Database] Removed MySQL support - @MrQuartz#1001 
> - [Database] Added new Schema >> clients
> - [Banking] Changed work, crime, rob cooldown type to `boolean` in `economyUsers` - @MrQuartz#1001 
> - [Banking] Fixed rob cooldown. Was checking cooldown of person being robbed, not robber. - @MrQuartz#1001 
> - [Music] Fixed database errors when fetching in `musicSystem.js` - @MrQuartz#1001 
> - [Core] Removed unnecessary permission checking in some commands - @MrQuartz#1001 
> - [Core] Added function to check perms in `utils.js` - @MrQuartz#1001 
> - [Core] Fixed `themecolor` and `embedColor` variables - @MrQuartz#1001 
> - [Languages] Removed unnecessary language values that weren't being use
> - [Banking] Fixed `bankingDeposit` throwing `Cannot read properties of undefined` error
> - [Commands] Fixed sticky messages not sending in chat
> - [Core] Fixed `Invalid Client` error for modal builder
> - [Core] Fixed `Invalid Enum Value` error for modal builder
> - [NPM] Updated to NodeJS v16.16.0 & NPM v8.17.0



## **Misc**
> - [Github] Added `languages.json` to FlockBot Github

Want to be a tester? Join the [Discord](https://discord.gg/c8auE6DFvg).
