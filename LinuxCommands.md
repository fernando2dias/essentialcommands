# Para matar um processo.
## Primeiro você precisa descobrir PID do processo
```
lsof -i :5000

lsof -i :<PORT>
```

## Com o numero da PID voce consegue matar o processo
```
kill -9 <PID>
```