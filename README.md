# Bridge to Turbin3

This is the brief update of my homework for this course

## Installation
```bash
pnpm i
```



## Files created

### Keygen

Command to generate a KeyPair and print it in the console 
```bash
pnpm run keygen
```

### Airdrop

Command to airdrop SOL to the keyPair saved in the file `dev-wallet.json`.
```bash
pnpm run airdrop
```

### Transfer

Command to transfer SOL from the `dev-wallet` to a new generated wallet (the public key has been hardcoded)
```bash
pnpm run transfer
```

### Enroll

Command to call a deployed program by WBA using the IDL and creating a new PDA. 

The PDA seed is created with: `prereq` + wallet public key. 

It calls to `complete` instruction passing my github user as argument.

```bash
pnpm run enroll
```


#### Tx link

https://explorer.solana.com/tx/2Cq8hHT1r96CU5rsCecQDNpi8C7fVjrXuA2mF5TZA2txw6Q43kYPxu31BDryZePnJS4faB2YjfsaBRcD7ohisKag?cluster=devnet


