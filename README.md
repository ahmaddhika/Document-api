
 
# REST- API FULL 
<p align="center">
</p>
<p align="center">
<a href="https://github.com/zeeoneofc"><img title="Author" src="https://img.shields.io/badge/Author-ThisLeonReal-orange.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/130N-STUDIO/followers"><img title="Followers" src="https://img.shields.io/github/followers/zeeoneofc?color=red&style=flat-square"></a>
<a href="https://github.com/130N-STUDIO/api-zeeoneofc/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/zeeoneofc/api-zeeoneofc?color=blue&style=flat-square"></a>
<a href="https://github.com/zeeoneofc/api-zeeoneofc/network/members"><img title="Forks" src="https://img.shields.io/github/forks/zeeoneofc/api-zeeoneofc?color=red&style=flat-square"></a>
<a href="https://github.com/zeeoneofc/api-zeeoneofc/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/zeeoneofc/api-zeeoneofc?label=Watchers&color=blue&style=flat-square"></a>
</p>

## main REST- API
Check it [Here](https://restapifull-by-rey.herokuapp.com/api)


## Endopoint?
Pengambilan Endopoint
```js
https://restapifull-by-rey.herokuapp.com/api/anime/minato?apikey=administrator
https://raw.githubusercontent.com/inirey/Document-api/main/minato.json
```
## Client settings
Atur di case bot WhatsApp mu

```js
anu = await fetchJson(`https://restapifull-by-rey.herokuapp.com/api/anime/minato?&Apikey=administrator`, {method: 'get'})
min = JSON.parse(JSON.stringify(anu));
ato =  min[Math.floor(Math.random() * min.length)];
nye = await getBuffer(ato)
rey.sendMessage(from, nye, image, { caption: 'minato!!', quoted: mek })
```
</p>

Atau juga bisa

```js
anu = await fetchJson(`https://raw.githubusercontent.com/inirey/Document-api/main/minato.json`, {method: 'get'})
min = JSON.parse(JSON.stringify(anu));
ato =  min[Math.floor(Math.random() * min.length)];
nye = await getBuffer(ato)
rey.sendMessage(from, nye, image, { caption: 'minato!!', quoted: mek })
```
</p>
