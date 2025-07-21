
# 🧰 Ecossistema de Desenvolvimento na Cardano

Este documento apresenta as principais ferramentas, linguagens e aplicações disponíveis para o desenvolvimento e uso da Cardano.

---

## 🔧 Ambientes e Ferramentas para Desenvolvedores Cardano

### 1. Linguagens e SDKs

| Ferramenta              | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Plutus**              | Linguagem baseada em Haskell para escrever contratos inteligentes.        |
| **Marlowe**             | DSL visual e textual para contratos financeiros (low-code/no-code).       |
| **Aiken**               | Linguagem funcional moderna e mais simples que Plutus (emergente).       |
| **Lucid**               | Biblioteca TypeScript/JS para interagir com a blockchain Cardano.        |
| **Cardano Serialization Lib** | Biblioteca JS/WASM para construir e manipular transações Cardano.  |
| **Mesh**                | Framework JS full-stack para criar dApps com integração de carteiras.     |
| **PyCardano**           | Biblioteca Python para construir transações e scripts.                   |
| **cardano-cli**         | Ferramenta oficial de linha de comando para operação de nós e transações.|

---

### 2. Carteiras e APIs de Integração

| Ferramenta              | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Nami Wallet**         | Extensão de navegador com injeção de API CIP-30 para dApps.              |
| **Eternl Wallet**       | Suporte avançado a multisig, hardware wallets e dApps.                   |
| **Flint Wallet**        | Leve, open source e mobile-ready.                                        |
| **Lace Wallet**         | Carteira oficial da IOG com integração de identidade e staking.          |
| **CIP-30 dApp Connector** | Interface padrão para dApps se comunicarem com carteiras Cardano.     |

---

### 3. Ambientes de Teste e Simulação

| Ferramenta              | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Preview/Testnet**     | Redes públicas para testar contratos e dApps com ADA de faucet.          |
| **Plutus Playground**   | Ambiente online para simular e testar contratos Plutus.                  |
| **Marlowe Playground**  | Interface visual para simular contratos Marlowe sem código.              |
| **Demeter.run**         | Plataforma para deploy instantâneo de backend e nodes (IAAS/SaaS).       |
| **Cardano Devnet**      | Ambiente isolado para testes com controle completo.                      |

---

### 4. Blockchains Paralelas e Infraestrutura

| Nome                    | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Hydra**               | Protocolo de escalabilidade Layer 2 para transações rápidas e baratas.   |
| **Mithril**             | Protocolo de sincronização leve para full-nodes rápidos.                 |
| **Ouroboros**           | Protocolo de consenso proof-of-stake da Cardano.                         |
| **Cardano Node**        | Node completo para operação da rede, validação e block-producing.        |

---

### 5. APIs e Indexadores

| Ferramenta              | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Blockfrost**          | API REST popular para consultar dados da blockchain (transações, UTxOs). |
| **Koios**               | Alternativa ao Blockfrost com dados completos on-chain.                  |
| **Ogmios**              | WebSocket interface para node Cardano (ideal para indexadores).          |
| **Kupo**                | Indexador leve de UTxOs e scripts.                                       |
| **db-sync**             | Indexador oficial usado por explorers como o CardanoScan.                |

---

### 6. Identidade Descentralizada

| Ferramenta              | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Atala PRISM**         | Framework para identidade descentralizada (SSI, credenciais verificáveis).|
| **CIP-68, CIP-25, CIP-94** | Padrões para NFTs e metadados estruturados.                         |

---

### 7. Exploradores e Dashboards

| Ferramenta              | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **CardanoScan**         | Explorador de blocos, transações e tokens.                               |
| **Adastat**             | Estatísticas on-chain detalhadas.                                        |
| **PoolTool**            | Informações sobre pools de stake.                                       |
| **Cexplorer**           | Foco em análises de staking e performance de pools.                      |

---

### 8. Ferramentas para NFTs e Tokens

| Ferramenta              | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **NFT-Maker Pro**       | Plataforma para mintagem e venda de NFTs em Cardano.                     |
| **JPG.store**           | Principal marketplace de NFTs na Cardano.                                |
| **TokenForge**          | Geração de tokens nativos (sem contrato inteligente).                    |

---

### 9. Frameworks de Desenvolvimento Rápido

| Ferramenta              | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Plu-ts**              | Transpilador TypeScript → Plutus (dev emergente).                        |
| **Helios**              | Linguagem funcional simplificada para contratos.                         |
| **TxPipe stack**        | Conjunto de ferramentas como Demeter, Pallas, Oura, Kupo, etc.           |

---

## 🧭 Fluxo Básico de Desenvolvimento

1. **Escrever contrato**: Plutus, Marlowe, Helios, etc.  
2. **Simular/Testar**: Playground, preview/testnet.  
3. **Construir transações**: `cardano-cli`, Lucid, Blockfrost.  
4. **Assinar e enviar**: Via carteira (Nami, Eternl) ou node.  
5. **Monitorar**: via API, indexador ou explorer.  
6. **Produção**: Deploy em mainnet.
