# SAF Casa — Token List

Lista de tokens no padrão [Uniswap Token Lists](https://github.com/Uniswap/token-lists),
publicada pela casa (SAF — Synthetic Asset Framework).

- **List URL:** https://luccmick121.github.io/tokenlist/casa-tokenlist.json
- **Fonte:** endereços lidos dos registros (`addresses.bsc.json`, `addresses.ethereum.json`)
  por `saf logo list` — nunca de memória.
- **Semver:** adicionar token = minor · mudar metadata (nome/símbolo/logo) = patch · remover = major.

## Tokens

| chainId | token | endereço |
|---|---|---|
| 56 | Bitcoin (BTC) | `0x7130D1d8693C300F48A4b778d96290Ff0AfDad9c` |
| 56 | Tether USD Bridged ZED20 (USDT.z) | `0x4BE31a5FBEEa7D73b59Ae538B56dAC7A60aB7Db4` |
| 1 | Mini Tether (MUSDT) | `0xdAC15c8B27CC1D0AEC5c28F568D7664da0401ec7` |

Gerado/validado contra o schema oficial `Uniswap/token-lists` (testes em `tests/tokenlist.test.ts`).
