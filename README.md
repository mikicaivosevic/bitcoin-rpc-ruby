# bitcoin-rpc-ruby
Bitcoin JSON-RPC Ruby

## Usage

    bitcoin_rpc = BitcoinRPC.new('http://user:password@127.0.0.1:8332')

    bitcoin_rpc.get_balance_by_address '1NzKsHxncpJ4ShEQVwcydhsCyzFkKJMZ5f'

    bitcoin_rpc.getbalance
