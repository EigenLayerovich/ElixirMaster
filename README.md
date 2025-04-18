# Elixir Checker

Software for automatic checking of drop [Elixir](https://claim.elixir.xyz/).

## 📢 Contacts

- My telegram: [@BaizaQ)

## 🐍 Requirements

- Python 3.12

## ⚙️ Setup

```sh
# Clone repository
git clone https://github.com/EigenLayerovich/ElixirMaster
cd elixir-checker

# Setup dependencies
pip install -r requirements.txt
```

## 📂 Import files

Place required files to folder `imports`:
- **proxies.txt** (**mandatory**): proxy list in format `http://login:password@ip:port`
- **wallets.txt** (**mandatory**): list of EVM-addresses needed to check

⚠️ Number of proxy cannot be less than number of addresses! 
