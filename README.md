# mybrowservpn
JavaScript library for mybrowservpn.com
# main
```js
async function main(){
    const {mybrowservpn} = require('./mybrowservpn');
    const myvpn= new mybrowservpn();
    let req=await myvpn.premium_proxy()
    console.log(req)
}
main()
```
