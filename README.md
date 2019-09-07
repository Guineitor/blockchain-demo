# Blockchain Demo
Demostracao conceitual plataforma blockchain.

# Tips 
Melhor no Google Chrome. xD

Os blocos contém:

"Bloco:"-> Id do bloco.
"Nonce"-> Representa a dificuldade.
“DE / PARA”: São os nomes dos participantes envolvidos nas transações. Cada um com o seu endereço associado. O “De” representa o remetente e o “Para” o destinatário da transação. Isto é, ao digitar o endereço da carteira, o nome de seu dono aparece nos campos em questão. 
Participantes da rede (Nome e Endereço)
Eduardo
39981B0880B1956BFCCBBA9260BB848CCD28ED2651E11553C53489847A252BA4
Solange
3C56715664A646445083CD44011B309C0B423149DCE60BEC272E825E3115C0DD
Carla
AD8D83FFD82B5A8ED429E8592B5CB3E6E83A033770868A1A00C6FD1E7FAE242C
Satoshi Nakamoto
A0DC65FFCA799873CBEA0AC274015B9526505DAAAED385155425F7337704883E
Itamar
26DDA94DB37658833998316E1B3F9B19704D48AED3A6F1FFF1F775C4A8C77ED6


"Coinbase"-> Transação de remuneração do minerador de cada bloco. Ao invés do endereço da carteira, utiliza-se o nome do minerador para identifica-lo e o fee representa o montante remunerado para ele pelo serviço de mineração prestado.
“Fee”-> recompensa paga ao minerador de cada bloco pelos usuários da rede.

Neste blockchain, a taxa de recompensa para o minerador é fixa em 1 unidade de token por transação, isto é, o número de transações equivale a quantidade de tokens repassados ao minerador. 
“Saldo”-> existe o controle/gestão do saldo dos participantes, impedindo que o usuário envie mais do que possui em seu endereço.

“Troco” -> Por default, usuários com saldo maior que o montante próprio transacionado no bloco, enviam o troco diretamente para sua conta. Diferente do blockchain do bitcoin, que o troco não explicitado é automaticamente direcionado ao minerador.


O botão “Minerar”:
- escolhe de maneira aleatória o minerador do bloco em questão
- executa a mineração do bloco e calcula o fee total a ser pago ao minerador


# Alunos 
```
Alexandre Akel 
Eduardo Franklin  
Itamar Ribeiro 
Guilherme Araujo
```
# Veja mais 
Jade 

# Acesse na nuvem
https://blockchain-fiap.azurewebsites.net



# Rodando local
Donwload node js - https://nodejs.org/en/download

install npm -  (npm package)


run `npm install`


run `npm start`

Baseado no conceito criado por @anders94
