# Configuração de Rede

Vamos criar duas redes diferentes e estabelecer comunicação entre elas via ICMP.

## Rede A (Alunos)

- **Endereço de Rede:** `192.168.0.0/24`
- **Gateway:** `192.168.10.254`
- **DHCP e DNS:** `192.168.10.253`

Vamos criar mais 4 máquinas na Rede Interna A. Os desktops usarão DHCP, enquanto os servidores terão IP fixo.

## Rede B (Alunos)

- **Endereço de Rede:** `172.15.0.254/24`
- **Gateway:** `172.15.0.254`
- **DHCP e DNS:** `172.15.0.253`
- **Servidor Web:** `172.15.0.252`

Vamos criar mais 5 máquinas na Rede Interna B. Os desktops usarão DHCP, enquanto os servidores terão IP fixo.

## Equipamentos

- 1 Router 1841
- 2 Switches 2960 24TT

## Objetivo

O objetivo final é que um dos desktops da Rede A consiga acessar o site do Servidor WEB que está na REDE B através de seu navegador interno. A página deve ser carregada corretamente, validando assim o roteamento entre as redes, o funcionamento do DNS e da camada de aplicação.

## Resultado

![image](https://github.com/nicholasloureiro/projeto-final-redes/assets/105894972/95c37322-6339-440e-ad00-db3f01288876)


