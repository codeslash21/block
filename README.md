# Blockchian implementation using POW consensus algorithm
#### Group Member (G40)
- Soumyadip Guha (2022H1030092H)
- Dantu Havishteja (2022H1030083H)
- Aman Paliwal (2022H1030082H)
- Katuri Revanth (2022H1030065H)
- Pavan Sadanala (2022H1030061H)

## Project Details
### File Details
We implemented using Python language. This project has three files
- `main.py` : We implemented POW consensus algorithm in with the functions named `updateHash` and `mine`. We implemented merkle root using `merkle` function.
- `qr.py` : file for creating qr code.
- `timestamp.py` : file to get the timestamp

### Block Details
Each block has `4` transactions. Initally each transaction will be in queue until we have `4` transactions to create a new block. When we have `4` transaction we create a new block with `merkle hash` value.

### Default values
Initially there are some default products, default distributors and client with client ID `CLI001`. 

### QR Code
QR code will be generated after each successful transaction and QR code will be opened to default image app.
