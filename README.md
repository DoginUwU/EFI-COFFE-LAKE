
# EFI COFFE LAKE (OPENCORE)

Pasta contendo minhas configurações EFI para os processadores de 9° geração da Intel.

![Screen Shot 2022-10-05 at 22 10 11](https://user-images.githubusercontent.com/59850361/194191878-44241ab1-792b-46e8-ae2b-98a0a8518b33.png)


## Documentação da API

#### Configurações

| Tipo   | Componente       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `Processador` | `i3-9100F` | Coffe Lake |
| `Placa Gráfica` | `NVIDIA GeForce GTX 750 Ti 2GB` | OpenCore Legacy |
| `Memória` | `16GB 2400 MHz DDR4`
| `LAN` | `Intel I219` | IntelMausi.kext |
| `USB-Ports` | `H310` | XHCI-unsupported.kext |

#### Problemas identificados

| Tipo   | Descrição                           |
| :---------- | :---------------------------------- |
| `Metal API` | `Não funcionando nas placas Maxwell`
