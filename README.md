# NFT na Prática: Criando uma NFT na prática

Para esta prática usaremos a testnet da OpenSea

## OpenSea Testnets

Vamos na rede testnet da OpenSea em `https://testnets.opensea.io/`, e no primeiro `Login` usamos o **MetaMask** como carteira. Selecionamos uma conta (ethDeve - 0x3c3a3...de766).

Aceitar a configuração:

```sh
Signature request

Only confirm this message if you approve the content and trust the requesting site.

Request from

testnets.opensea.io

Mensagem

Welcome to OpenSea!

Click to sign in and accept the OpenSea Terms of Service (https://opensea.io/tos) and Privacy Policy (https://opensea.io/privacy).

This request will not trigger a blockchain transaction or cost any gas fees.

Wallet address: 0x3c3a3...de766

Nonce: 0b35d...-...-...-...-...35412
```

Finalmente, confirmar a assinatura.

## Criando a primeira coleção

Uma vez conectado à [OpenSea Testnets](https://testnets.opensea.io/), selecionar `Create`.

Nas opções de criação, selecionar:

- `Collection or item`

Na tela `Create an NFT` preencher as informações:

- Em `Drag and drop media`: Arrastar ou informar a imagem a ser utilizada;

Em `Collection`: `Create a new collection`

- `Drag and drop or click to upload`: coloque uma logo para a coleção
- `Contract name`: Tarso Queiroz NFT Collection
- `Token symbol`: TQNC
- `Blockchain`: Base Sepolia (Base Sepolia (Alchemy) Testnet)
- `Continue`

A coleção será criada (`Your collection has been created`).

## Criando a primeira NFT

No resultado de criação da coleção podemos partir para `Create an NFT`, ou na tela inicial da [OpenSea Testnets](https://testnets.opensea.io/), selecionar `Create`.

Selecionamos então `Collection or item` e preechemos as demais informações:

- `Drag and drop media`: arrastamos a primeira imagem
- `Collection`: selecionar a coleção acima criada (`Tarso Queiroz NFT Collection`)
- `Name`: Primeira NFT
- `Description`: Esta é a primeira NFT de muitas.
- Clicar em `Create`;
- Confirmar a transação no **MetaMask**;

O item estará em sua coleção (Your item has been minted).
