# Solana Cluster RPC Endpoints

Solana maintains dedicated api nodes to fulfill [JSON-RPC](https://docs.solana.com/developing/clients/jsonrpc-api) requests for each public cluster, and third parties may as well. Here are the public RPC endpoints currently available and recommended for each public cluster with their specific rate limits:

## Devnet

#### Endpoint

- `https://devnet.solana.com` - single Solana-hosted api node; rate-limited

#### Rate Limits

- Maximum number of requests per 10 seconds per IP: 100
- Maximum number of requests per 10 seconds per IP for a single RPC: 40
- Maximum current connections per IP: 40
- Maximum connection rate per 10 seconds per IP: 40
- Maximum amount of data per 30 second: 100 MB

## Testnet

#### Endpoint

- `https://testnet.solana.com` - single Solana-hosted api node; rate-limited

#### Rate Limits

- Maximum number of requests per 10 seconds per IP: 100
- Maximum number of requests per 10 seconds per IP for a single RPC: 40
- Maximum current connections per IP: 40\
- Maximum connection rate per 10 seconds per IP: 40
- Maximum amount of data per 30 second: 100 MB

## Mainnet Beta

#### Endpoints

- `https://api.mainnet-beta.solana.com` - Solana-hosted api node cluster, backed by a load balancer; rate-limited
- `https://solana-api.projectserum.com` - Project Serum-hosted api node

Rate Limits 

- Maximum number of requests per 10 seconds per IP: 100
- Maximum number of requests per 10 seconds per IP for a single RPC: 40
- Maximum current connections per IP: 40
- Maximum connection rate per 10 seconds per IP: 40
- Maximum amount of data per 30 second: 100 MB
