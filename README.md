## Comandos nodes uteis 

Permissão no npm root

```
npm install -g --unsafe-perm=true --allow-root
```

Rodar em versões anterioes, possivel erro ("ERESOLVE unable to resolve dependency tree")

```
 npm install --save --legacy-peer-deps
 npm config set legacy-peer-deps true
```
