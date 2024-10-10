# Turbin3 Rust Registration Assignment

## Task 1 - Create a new Keypair

### Setup

- Initialise a new Rust library.

```bash 
cargo init --lib
```

### Dependencies

- solana-sdk = "1.15.2"

### Functions

- In src/lib.rs file, create

```rust 
  #[cfg(test)]
mod tests {
    use solana_sdk;

    // Create new Keypair
    #[test]
    fn keygen() {}

    //  base58 to byte array encoding
    #[test]
    fn base58_to_wallet() {}

    // byte array to base58 encoding
    #[test]
    fn wallet_to_base58() {}
}
```

---

## Task 2 - Claim Token Airdrop

### Functions

- In src/lib.rs, create

```rust
    // Airdrop SOL to our dev-wallet on devnet 
#[test]
fn airdop() {} 
```

---

## Task 3 - Transfer tokens to  Turbin3 Address

### Dependencies

- solana-program = "1.15.2"

### Functions

- In src/lib.rs, create

```rust
// Send devnet SOL to Turbin3 registered wallet address
#[test]
fn transfer_sol() {} 
```

---

## Task 4 - Empty devnet wallet into Turbin3 wallet

### Functions

- In src/lib.rs, create

```rust
// Send remaining lamports to Turbin3 dev wallet
#[test]
fn empty_wallet() {} 
```

---

## Task 5 - Submit completion of the Turbin3 pre-requisites program

### Dependencies

- borsh = "0.10.3"
- solana-idlgen = { git = "https://github.com/deanmlittle/solana-idlgen.git" }
-

### Functions

- In src/lib.rs, create

```rust
// Submit  github account and  Pubkey to signify our completion of the Turbin3 pre-requisite materials
#[test]
fn completion_of_turbin3_program() {} 
```

-
Transaction [hash](https://explorer.solana.com/tx/6j7v1gr1Hmg19syp2Vng7xDSWtriQMxwtwYabPhMtGMEMLRTz4WkRdvJZsZ6uA5QHYntv8okGdngbAWet72XVdn?cluster=devnet)