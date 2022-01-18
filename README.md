# ✨ Steam API client for userscript ✨

This library help to interact to **[Steam API](https://steamcommunity.com/dev)**.

### Supported Endpoints

- IPlayerService/GetOwnedGames

## 📌Dependencies📎

- [Elasticlunr.js (Lightweight full-text search engine)](http://elasticlunr.com/)

## 🖥Usage🖱️

To use this library in an userscript you have to include the script file and its dependencies:

```
// @grant        GM_xmlhttpRequest
// @require      https://cdnjs.cloudflare.com/ajax/libs/elasticlunr/0.9.6/elasticlunr.js
// @require      https://raw.githubusercontent.com/sergiosusa/steam-api-client-for-userscript/main/steam-api-client.js
```

## 🔧Configuration🔧

The first time you use the library, it asks for two mandatory fields:

Steam API Dev Key (<code>STEAM_API_ID</code>). You can get yours [here](https://steamcommunity.com/dev/apikey).  
SteamID64 (<code>STEAM_USER</code>). You can find it [here](https://steamid.io).

And store them in ``localstorage``.

## 🐛Known limitations🐛

- The Steam API result don't provide the DLCs that the account own, so DLCs are not supported.

### ☕Buy me a coffee☕

- My Amazon [affiliate link](https://amazon.es/?tag=sergiosusa-21) or add this query string ``?tag=sergiosusa-21`` before add a product to the basket when you buy on Amazon spain.
- My Letyshops [referal link](https://letyshops.com/es/winwin?ww=17530599) to get €5 each.
- My Payme [link](https://paypal.me/sergiosusa?locale.x=es_ES) to send me a tip.