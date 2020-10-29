# Git Cherry Pick 

#### Identificando as alterções

```
git log --oneline --decorate --color --graph pastaEscolhida
```


#### Destino

<p> Faça o download da branch de destino </p>

```
git cherry-pick <hash>
```

Verificando se as alterações foram agregadas na branch.

```
git log --oneline --decorate --color --graph pastaEscolhida
```

#### Se ocorrer conflitos

1. Resolver manualmente
2. Execute o comando
   ```
    git cherry-pick -- continue
   ```
3. Validar se as alterações fora agregadas na branch.
   ```
    git log --oneline --decorate --color --graph pastaEscolhida
   ```
4. Fazer o push
   ```
   git push
   ```
