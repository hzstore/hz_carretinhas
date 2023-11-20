### HZ CARRETINHAS - Versão 2.0 - 10/11/2023
--------------------------------------------
- Recurso feito com base lua para servidor vRP e vRPEX para possibilitar carregar motos e carros em varias camionetes e alguns guinchos 
- Configurei 23 veiculos e modelei engates compativeis para acoplar carretinhas, traileres, e nas carroceria para trasporte de outros veiculos em cima
- Não tem dependencias de outros recursos, basta ter esta script + veiculos da coleção HZ Tow
- Os arquivos de texturas são totalmente editaveis conforme a necessidade ou preferencia do seu servidor
- Vou deixar a baixo informações necessarias para instalação e video usando o recurso
- Se você precisar de qualquer forma de suporte após adquirir este recurso, o lugar certo para perguntar é o nosso Servidor do Discord:
- O arquivo contem apenas 1 resource, nela conta 23 veiculos, 2 audios realistas, 1 server.lua, 1 client.lua, README.md
--------------------------------------------
Em server.cfg ou config.cfg do seu servidor adicione a linha para das start na resource
```
start hz_carretinhas
```
--------------------------------------------
`DICA BASICA PARA CONSEGUIR CARREGAR E DESCARREGAR FACILMENTE QUALQUER VEICULO`
- 1° Posicione o veiculo que deseja carregar proximo a parte traseira do veiculo que vai transportar
- 2° Entre (F) e saida (F) do veiculo que vai transportar
- 3° Aproxime-se do veiculo que deseja carregar e use o comando referente a veiculos de transporte
--------------------------------------------
- CASO TENHA DIFICULDADE PARA CARREGAR OU DESCARREGAR
`DICA PARA FACILITAR JÁ QUE EM ALGUMAS SITUAÇÕES É DIFICIL DE CARREGAR OU DESCARREGAR DEVIDA A POSISÃO PRECISA QUE DEVE ESTAR PARA UTILIZAR O COMANDO.`
- Crie uma bind em alguma tecla que você não use, após criar a bind com o comando, fique pressionando a tecla andando ao redor do veiculo até que consiga carregar ou descarregar.
- Modelo de bind a baixo, lembre-se de mudar o comando e a letra conforme desejar
**EX:**
```bind keyboard "e" "towf250"```
```bind keyboard "LETRA" "COMANDO"```
--------------------------------------------
_SPAWN_VEICULO_   		=   		_COMANDO_

- hz_carretinhacarro		=			towcarretinhacarro
- hz_carretinhamotos		=			towcarretinhamoto
- hz_cotrailer			=			towcarretinhacarro2
- hz_ctjetski			=			towjet
- hz_ctmotos			=			towmoto
- hz_ctrailer			=			towcracingg
- hz_enclosedgoose		=			towracing				
- hz_longtrailer		=			towlong1, towlong2
- hz_trailercar			=			towcarretinhacarro3
- hz_tripletrailer		=			towtriple1, towtriple2, towtriple3
- hz_paredao			=			
- hz_superduty			=			towsuperd
- hz_raptor150			=			towraptor
- hz_dodgeram2500		=			towram2
- hz_f250td			=			towf250
- hz_f350d			=			towf350d
- hz_f350offroadspec		=			towf350spec
- hz_ford70f100			=			towf100
- hz_classx			=			towx
- hz_ramlong 			=			towram
- hz_flatbedm2			=			towg2
- hz_dsflatbed			=			towdsf
- hz_gtow			=			towg
- hz_paredao			=			Só engatar
--------------------------------------------
--------------------------------------------
- `PARA QUE OS VEICULOS FUNCIONE PERFEITAMENTE DEVE CRIAR ALGUMAS LINHAS NA SUA BASE`
- `ESTAS AFETAM "RECONHECIMENTO EM GARAGENS" - "TRANCAS" - "PORTA-MALAS"`
- `FAÇA UM LINHA REFERENTE A CADA VEICULO NOS LOCAIS DESCRITOS, LEMBRANDO QUE PODE TER MÉRA DIFERENÇA ENTRE UMA BASE E OUTRA`
- `CASO TENHA ALGUMA DIFERENÇA NA SUA BASE, OBSERVE COMO É A LINHA E REPITA.`
--------------------------------------------
### vrp/modules/inventory
--------------------------------------------
```
["hz_nome_de_spawn"] = { ['name'] = "NOME DO VEICULO", ['price'] = 99999999, ['tipo'] = "carros" },
```
--------------------------------------------
### vrp/client/basic_garage
--------------------------------------------
```
{ ['name'] = "hz_nome_de_spawn", ['hash'] = GetHashKey"hz_nome_de_spawn", ['banned'] = false },
```
--------------------------------------------
### vrp_garage  -- A GARAGEM PODE ESTAR USANDO OUTRA, ENTÃO A LINHA DE IDENTIFICAÇÃO DO VEICULO PODE SER DIFERENTE
--------------------------------------------
```
{ hash = GetHashKey("hz_nome_de_spawn"), name = 'hz_nome_de_spawn', price = 99999999, banido = false, modelo = 'NOME DO VEICULO', capacidade = 200, tipo = 'exclusive' },  
```
- [BUY TEBEX](https://hz-store.tebex.io/package/6000878)

- [DISCORD](https://discord.gg/YMznAAaaVC)

- [github](https://github.com/hzstore)

- [VIDEO](https://youtu.be/lRve2K0Pgpw)

![1](https://github.com/hzstore/hz_carretinhas/assets/145871489/76fa9e10-ce7e-4f75-8837-fa65dae7029b)
![2](https://github.com/hzstore/hz_carretinhas/assets/145871489/9bcb8e58-af50-4f69-8a8f-9f8646111f4e)
![3](https://github.com/hzstore/hz_carretinhas/assets/145871489/24dfe730-817b-452a-b37f-2e85212a9de4)
![4](https://github.com/hzstore/hz_carretinhas/assets/145871489/b4bfc596-d601-430a-94ee-3e39dc526536)
![5](https://github.com/hzstore/hz_carretinhas/assets/145871489/e415d00a-74cb-487f-ad46-ff46b1dd1ff6)
![6](https://github.com/hzstore/hz_carretinhas/assets/145871489/9c3c23cf-7ef0-4c57-a2bf-b338d48dc5ac)
![7](https://github.com/hzstore/hz_carretinhas/assets/145871489/85efdd56-b909-4341-9ee1-c396725b6af6)
![8](https://github.com/hzstore/hz_carretinhas/assets/145871489/33140510-4028-43c2-9c16-c21cff2bf39c)
![9](https://github.com/hzstore/hz_carretinhas/assets/145871489/5979fc43-a3f3-4c5b-bf0a-e0df3940b0f9)
![10](https://github.com/hzstore/hz_carretinhas/assets/145871489/8f6ef607-ae88-46a6-a239-ccb1c3972cff)
![11](https://github.com/hzstore/hz_carretinhas/assets/145871489/68f48a89-b1dd-4c8b-9f2e-dd774de4120f)
![12](https://github.com/hzstore/hz_carretinhas/assets/145871489/149576fe-2e7f-4988-8958-6dc2f9011770)
![13](https://github.com/hzstore/hz_carretinhas/assets/145871489/ab39b41d-b90b-438c-a1bd-7f7c8c36e8d0)
![14](https://github.com/hzstore/hz_carretinhas/assets/145871489/2fbb8d6b-74ed-4cdc-8203-678d0960a846)
![15](https://github.com/hzstore/hz_carretinhas/assets/145871489/523f9753-7d26-4f0e-8f85-2d7365fadbce)
![16](https://github.com/hzstore/hz_carretinhas/assets/145871489/cbc79b47-e54d-4994-be6f-313eb5c8844b)

