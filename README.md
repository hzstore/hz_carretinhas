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


![1](https://github.com/hzstore/hz_carretinhas/assets/145871489/c151eb97-d45a-4273-9c33-b8cff66a9dbb)
![2](https://github.com/hzstore/hz_carretinhas/assets/145871489/dab87718-3037-4460-a824-61c863593bdb)
![3](https://github.com/hzstore/hz_carretinhas/assets/145871489/2442ebee-80da-4aaf-86ef-4cdb50ea8b46)
![4](https://github.com/hzstore/hz_carretinhas/assets/145871489/86a27994-2e28-4c92-8d98-fdb1556cf622)
![5](https://github.com/hzstore/hz_carretinhas/assets/145871489/06853bed-74f6-492f-85d7-c6773a0b8c83)
![6](https://github.com/hzstore/hz_carretinhas/assets/145871489/fbbb08d7-8f6b-47f1-a9bc-9cc7c1329448)
![7](https://github.com/hzstore/hz_carretinhas/assets/145871489/b09c8140-c3e0-4f19-b705-cded15bc0647)
![8](https://github.com/hzstore/hz_carretinhas/assets/145871489/f978eb3c-1f6e-494d-bc4d-a5ecedb683de)
![9](https://github.com/hzstore/hz_carretinhas/assets/145871489/f0b2d33a-3ae1-4add-beda-047f070bf81f)
![10](https://github.com/hzstore/hz_carretinhas/assets/145871489/67cdb62b-5fd8-4b25-8f59-e6b82e690135)
![11](https://github.com/hzstore/hz_carretinhas/assets/145871489/916549ef-0bf8-4965-ae6b-02d2c25e08e9)
![12](https://github.com/hzstore/hz_carretinhas/assets/145871489/a3d34ea5-d06c-44c6-aac6-ae1905400b05)
![13](https://github.com/hzstore/hz_carretinhas/assets/145871489/697aef3d-8d80-4ddb-994d-851992e69898)
![14](https://github.com/hzstore/hz_carretinhas/assets/145871489/417106c2-66f8-4463-9797-c8b1c6682ccc)
![15](https://github.com/hzstore/hz_carretinhas/assets/145871489/a3e9b1e9-6db5-4817-bd70-620c49c8253f)
![16](https://github.com/hzstore/hz_carretinhas/assets/145871489/245c5b50-52ba-4536-a444-8aace623a043)
